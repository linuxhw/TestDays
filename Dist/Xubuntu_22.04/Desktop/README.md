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

Total: 332

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | DB75EN                      | [41cea41d1e](https://linux-hardware.org/?probe=41cea41d1e) | Jan 26, 2024 |
| Dell          | 0K240Y A01                  | [fe08501f76](https://linux-hardware.org/?probe=fe08501f76) | Jan 24, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d11d529522](https://linux-hardware.org/?probe=d11d529522) | Jan 23, 2024 |
| ASUSTek       | P8P67 DELUXE                | [545e0a6896](https://linux-hardware.org/?probe=545e0a6896) | Jan 23, 2024 |
| AOpen         | D2644 S26361-D2644          | [f45673bd59](https://linux-hardware.org/?probe=f45673bd59) | Jan 22, 2024 |
| ASUSTek       | TUF B450-PLUS GAMING        | [4254242157](https://linux-hardware.org/?probe=4254242157) | Jan 21, 2024 |
| Intel         | DB75EN                      | [f639799c41](https://linux-hardware.org/?probe=f639799c41) | Jan 21, 2024 |
| Dell          | 0F5C5X A00                  | [f320dddb34](https://linux-hardware.org/?probe=f320dddb34) | Jan 19, 2024 |
| ASUSTek       | H81M-C                      | [bcbb9c099f](https://linux-hardware.org/?probe=bcbb9c099f) | Jan 16, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [77032de9df](https://linux-hardware.org/?probe=77032de9df) | Jan 14, 2024 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [b6d8783c20](https://linux-hardware.org/?probe=b6d8783c20) | Jan 12, 2024 |
| Dell          | 0T0MHW A03                  | [2ad439d95f](https://linux-hardware.org/?probe=2ad439d95f) | Jan 11, 2024 |
| MSI           | B550 GAMING GEN3            | [511526bcf7](https://linux-hardware.org/?probe=511526bcf7) | Jan 08, 2024 |
| Gigabyte      | P55-UD3R                    | [44658131d3](https://linux-hardware.org/?probe=44658131d3) | Jan 05, 2024 |
| Unknown       | Unknown                     | [1f73670f10](https://linux-hardware.org/?probe=1f73670f10) | Dec 27, 2023 |
| Intel         | DB75EN                      | [c2c820f0d9](https://linux-hardware.org/?probe=c2c820f0d9) | Dec 25, 2023 |
| Intel         | DB75EN                      | [6ec790f3fc](https://linux-hardware.org/?probe=6ec790f3fc) | Dec 24, 2023 |
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
| 5.15.0-56-generic    | 18       | 6.67%   |
| 5.15.0-52-generic    | 16       | 5.93%   |
| 5.15.0-58-generic    | 9        | 3.33%   |
| 5.15.0-47-generic    | 9        | 3.33%   |
| 5.15.0-46-generic    | 9        | 3.33%   |
| 5.15.0-67-generic    | 8        | 2.96%   |
| 5.15.0-60-generic    | 8        | 2.96%   |
| 6.2.0-36-generic     | 6        | 2.22%   |
| 5.15.0-48-generic    | 6        | 2.22%   |
| 5.15.0-27-generic    | 6        | 2.22%   |
| 5.15.0-25-generic    | 6        | 2.22%   |
| 6.5.0-14-generic     | 5        | 1.85%   |
| 6.2.0-39-generic     | 5        | 1.85%   |
| 6.2.0-37-generic     | 5        | 1.85%   |
| 5.19.0-41-generic    | 5        | 1.85%   |
| 5.19.0-35-generic    | 5        | 1.85%   |
| 5.15.0-43-generic    | 5        | 1.85%   |
| 5.15.0-41-generic    | 5        | 1.85%   |
| 6.2.0-33-generic     | 4        | 1.48%   |
| 6.2.0-26-generic     | 4        | 1.48%   |
| 5.19.0-50-generic    | 4        | 1.48%   |
| 5.19.0-43-generic    | 4        | 1.48%   |
| 5.15.0-91-generic    | 4        | 1.48%   |
| 5.15.0-78-generic    | 4        | 1.48%   |
| 5.15.0-69-generic    | 4        | 1.48%   |
| 5.15.0-57-generic    | 4        | 1.48%   |
| 5.15.0-53-generic    | 4        | 1.48%   |
| 5.15.0-50-generic    | 4        | 1.48%   |
| 6.2.0-34-generic     | 3        | 1.11%   |
| 6.2.0-31-generic     | 3        | 1.11%   |
| 5.19.0-46-generic    | 3        | 1.11%   |
| 5.19.0-32-generic    | 3        | 1.11%   |
| 5.15.0-84-generic    | 3        | 1.11%   |
| 5.15.0-75-generic    | 3        | 1.11%   |
| 5.15.0-73-generic    | 3        | 1.11%   |
| 5.15.0-40-generic    | 3        | 1.11%   |
| 6.2.7-060207-generic | 2        | 0.74%   |
| 6.2.0-32-generic     | 2        | 0.74%   |
| 5.19.0-45-generic    | 2        | 0.74%   |
| 5.15.0-88-generic    | 2        | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 161      | 65.45%  |
| 6.2.0   | 32       | 13.01%  |
| 5.19.0  | 27       | 10.98%  |
| 6.5.0   | 6        | 2.44%   |
| 6.2.7   | 2        | 0.81%   |
| 6.1.0   | 2        | 0.81%   |
| 5.17.0  | 2        | 0.81%   |
| 5.13.0  | 2        | 0.81%   |
| 6.4.8   | 1        | 0.41%   |
| 6.3.3   | 1        | 0.41%   |
| 6.3.12  | 1        | 0.41%   |
| 6.2.2   | 1        | 0.41%   |
| 6.2.10  | 1        | 0.41%   |
| 6.1.10  | 1        | 0.41%   |
| 6.0.0   | 1        | 0.41%   |
| 5.4.0   | 1        | 0.41%   |
| 5.19.13 | 1        | 0.41%   |
| 5.19.1  | 1        | 0.41%   |
| 5.18.0  | 1        | 0.41%   |
| 5.17.5  | 1        | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 161      | 65.45%  |
| 6.2     | 36       | 14.63%  |
| 5.19    | 29       | 11.79%  |
| 6.5     | 6        | 2.44%   |
| 6.1     | 3        | 1.22%   |
| 5.17    | 3        | 1.22%   |
| 6.3     | 2        | 0.81%   |
| 5.13    | 2        | 0.81%   |
| 6.4     | 1        | 0.41%   |
| 6.0     | 1        | 0.41%   |
| 5.4     | 1        | 0.41%   |
| 5.18    | 1        | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 240      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| XFCE            | 233      | 96.68%  |
| GNOME           | 4        | 1.66%   |
| i3              | 2        | 0.83%   |
| KDE5            | 1        | 0.41%   |
| GNOME Flashback | 1        | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 231      | 94.67%  |
| Tty  | 13       | 5.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 197      | 82.08%  |
| Unknown | 24       | 10%     |
| GDM3    | 16       | 6.67%   |
| SDDM    | 2        | 0.83%   |
| GDM     | 1        | 0.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 89       | 37.08%  |
| fr_FR   | 30       | 12.5%   |
| de_DE   | 30       | 12.5%   |
| it_IT   | 18       | 7.5%    |
| pt_BR   | 13       | 5.42%   |
| en_CA   | 9        | 3.75%   |
| en_GB   | 7        | 2.92%   |
| ru_RU   | 5        | 2.08%   |
| en_AU   | 4        | 1.67%   |
| C       | 4        | 1.67%   |
| pl_PL   | 3        | 1.25%   |
| es_ES   | 3        | 1.25%   |
| es_AR   | 3        | 1.25%   |
| nl_NL   | 2        | 0.83%   |
| hu_HU   | 2        | 0.83%   |
| fi_FI   | 2        | 0.83%   |
| en_IN   | 2        | 0.83%   |
| cs_CZ   | 2        | 0.83%   |
| tr_TR   | 1        | 0.42%   |
| sv_SE   | 1        | 0.42%   |
| ru_UA   | 1        | 0.42%   |
| ja_JP   | 1        | 0.42%   |
| fr_CH   | 1        | 0.42%   |
| fr_CA   | 1        | 0.42%   |
| fr_BE   | 1        | 0.42%   |
| es_VE   | 1        | 0.42%   |
| es_CO   | 1        | 0.42%   |
| en_ZA   | 1        | 0.42%   |
| en_NZ   | 1        | 0.42%   |
| Unknown | 1        | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 141      | 58.26%  |
| EFI  | 101      | 41.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 202      | 83.13%  |
| Tmpfs   | 25       | 10.29%  |
| Overlay | 8        | 3.29%   |
| Btrfs   | 5        | 2.06%   |
| Zfs     | 2        | 0.82%   |
| Ext3    | 1        | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 163      | 66.53%  |
| MBR     | 46       | 18.78%  |
| Unknown | 36       | 14.69%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 191      | 78.6%   |
| Yes       | 52       | 21.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 156      | 64.46%  |
| Yes       | 86       | 35.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 62       | 25.83%  |
| Gigabyte Technology | 36       | 15%     |
| MSI                 | 33       | 13.75%  |
| Hewlett-Packard     | 23       | 9.58%   |
| Dell                | 20       | 8.33%   |
| ASRock              | 16       | 6.67%   |
| Lenovo              | 12       | 5%      |
| Intel               | 7        | 2.92%   |
| Acer                | 5        | 2.08%   |
| Unknown             | 4        | 1.67%   |
| Fujitsu             | 3        | 1.25%   |
| Foxconn             | 3        | 1.25%   |
| Pegatron            | 2        | 0.83%   |
| PCWare              | 2        | 0.83%   |
| Medion              | 2        | 0.83%   |
| Semp Toshiba        | 1        | 0.42%   |
| Packard Bell        | 1        | 0.42%   |
| OEM                 | 1        | 0.42%   |
| MACHINIST           | 1        | 0.42%   |
| Itautec             | 1        | 0.42%   |
| Hardkernel          | 1        | 0.42%   |
| eMachines           | 1        | 0.42%   |
| Biostar             | 1        | 0.42%   |
| AOpen               | 1        | 0.42%   |
| AMD                 | 1        | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS All Series                 | 6        | 2.5%    |
| Unknown                         | 5        | 2.08%   |
| Dell OptiPlex 7010              | 4        | 1.67%   |
| MSI MS-7D43                     | 3        | 1.25%   |
| MSI MS-7721                     | 3        | 1.25%   |
| ASUS K30AD_M31AD_M51AD          | 3        | 1.25%   |
| MSI MS-7D46                     | 2        | 0.83%   |
| MSI MS-7D25                     | 2        | 0.83%   |
| MSI MS-7C52                     | 2        | 0.83%   |
| MSI MS-7817                     | 2        | 0.83%   |
| Lenovo V530S-07ICB 10TX0010PB   | 2        | 0.83%   |
| HP t620 Quad Core TC            | 2        | 0.83%   |
| Dell OptiPlex 9020              | 2        | 0.83%   |
| Dell OptiPlex 390               | 2        | 0.83%   |
| ASUS ROG STRIX B450-F GAMING II | 2        | 0.83%   |
| Semp Toshiba STI                | 1        | 0.42%   |
| Pegatron FZ132AA-ABF m9456fr    | 1        | 0.42%   |
| Pegatron 20-b010                | 1        | 0.42%   |
| PCWare IPX1800E2                | 1        | 0.42%   |
| PCWare IPMH81G1                 | 1        | 0.42%   |
| Packard Bell IMEDIA X9305       | 1        | 0.42%   |
| MSI MS-7E07                     | 1        | 0.42%   |
| MSI MS-7D40                     | 1        | 0.42%   |
| MSI MS-7C91                     | 1        | 0.42%   |
| MSI MS-7C84                     | 1        | 0.42%   |
| MSI MS-7C56                     | 1        | 0.42%   |
| MSI MS-7C37                     | 1        | 0.42%   |
| MSI MS-7C08                     | 1        | 0.42%   |
| MSI MS-7C02                     | 1        | 0.42%   |
| MSI MS-7B98                     | 1        | 0.42%   |
| MSI MS-7B86                     | 1        | 0.42%   |
| MSI MS-7A74                     | 1        | 0.42%   |
| MSI MS-7A32                     | 1        | 0.42%   |
| MSI MS-7982                     | 1        | 0.42%   |
| MSI MS-7835                     | 1        | 0.42%   |
| MSI MS-7758                     | 1        | 0.42%   |
| MSI MS-7529                     | 1        | 0.42%   |
| MSI MS-7309                     | 1        | 0.42%   |
| MSI Hyrican PC A320M PRO-E      | 1        | 0.42%   |
| MSI 5860                        | 1        | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 16       | 6.67%   |
| Dell OptiPlex        | 15       | 6.25%   |
| ASUS ROG             | 8        | 3.33%   |
| Lenovo ThinkCentre   | 7        | 2.92%   |
| ASUS All             | 6        | 2.5%    |
| HP Compaq            | 5        | 2.08%   |
| ASUS TUF             | 5        | 2.08%   |
| Unknown              | 5        | 2.08%   |
| HP EliteDesk         | 4        | 1.67%   |
| Acer Veriton         | 4        | 1.67%   |
| MSI MS-7D43          | 3        | 1.25%   |
| MSI MS-7721          | 3        | 1.25%   |
| Gigabyte B550        | 3        | 1.25%   |
| ASUS K30AD           | 3        | 1.25%   |
| MSI MS-7D46          | 2        | 0.83%   |
| MSI MS-7D25          | 2        | 0.83%   |
| MSI MS-7C52          | 2        | 0.83%   |
| MSI MS-7817          | 2        | 0.83%   |
| Lenovo V530S-07ICB   | 2        | 0.83%   |
| HP t620              | 2        | 0.83%   |
| HP ProDesk           | 2        | 0.83%   |
| HP Pavilion          | 2        | 0.83%   |
| Gigabyte B450M       | 2        | 0.83%   |
| Fujitsu ESPRIMO      | 2        | 0.83%   |
| Dell XPS             | 2        | 0.83%   |
| Dell Precision       | 2        | 0.83%   |
| ASUS P8H61-M         | 2        | 0.83%   |
| ASUS M5A97           | 2        | 0.83%   |
| Semp Toshiba STI     | 1        | 0.42%   |
| Pegatron FZ132AA-ABF | 1        | 0.42%   |
| Pegatron 20-b010     | 1        | 0.42%   |
| PCWare IPX1800E2     | 1        | 0.42%   |
| PCWare IPMH81G1      | 1        | 0.42%   |
| Packard Bell IMEDIA  | 1        | 0.42%   |
| MSI MS-7E07          | 1        | 0.42%   |
| MSI MS-7D40          | 1        | 0.42%   |
| MSI MS-7C91          | 1        | 0.42%   |
| MSI MS-7C84          | 1        | 0.42%   |
| MSI MS-7C56          | 1        | 0.42%   |
| MSI MS-7C37          | 1        | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 29       | 12.08%  |
| 2013 | 24       | 10%     |
| 2018 | 23       | 9.58%   |
| 2012 | 20       | 8.33%   |
| 2020 | 17       | 7.08%   |
| 2010 | 16       | 6.67%   |
| 2021 | 15       | 6.25%   |
| 2015 | 13       | 5.42%   |
| 2022 | 12       | 5%      |
| 2019 | 11       | 4.58%   |
| 2017 | 11       | 4.58%   |
| 2016 | 11       | 4.58%   |
| 2011 | 11       | 4.58%   |
| 2009 | 8        | 3.33%   |
| 2007 | 7        | 2.92%   |
| 2008 | 5        | 2.08%   |
| 2023 | 3        | 1.25%   |
| 2006 | 2        | 0.83%   |
| 2005 | 2        | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 240      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 226      | 94.17%  |
| Enabled  | 14       | 5.83%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 240      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 56       | 23.14%  |
| 4.01-8.0    | 44       | 18.18%  |
| 3.01-4.0    | 43       | 17.77%  |
| 8.01-16.0   | 37       | 15.29%  |
| 32.01-64.0  | 35       | 14.46%  |
| 64.01-256.0 | 11       | 4.55%   |
| 24.01-32.0  | 8        | 3.31%   |
| 1.01-2.0    | 5        | 2.07%   |
| 2.01-3.0    | 3        | 1.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 92       | 35.11%  |
| 2.01-3.0   | 56       | 21.37%  |
| 3.01-4.0   | 43       | 16.41%  |
| 4.01-8.0   | 39       | 14.89%  |
| 0.51-1.0   | 15       | 5.73%   |
| 8.01-16.0  | 12       | 4.58%   |
| 16.01-24.0 | 3        | 1.15%   |
| 0.01-0.5   | 2        | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 96       | 39.02%  |
| 2      | 69       | 28.05%  |
| 3      | 39       | 15.85%  |
| 4      | 19       | 7.72%   |
| 5      | 11       | 4.47%   |
| 6      | 6        | 2.44%   |
| 7      | 2        | 0.81%   |
| 0      | 2        | 0.81%   |
| 10     | 1        | 0.41%   |
| 9      | 1        | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 126      | 52.28%  |
| Yes       | 115      | 47.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 238      | 99.17%  |
| No        | 2        | 0.83%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 139      | 57.44%  |
| Yes       | 103      | 42.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 169      | 69.83%  |
| Yes       | 73       | 30.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 43       | 17.84%  |
| Germany      | 35       | 14.52%  |
| France       | 28       | 11.62%  |
| Italy        | 17       | 7.05%   |
| Brazil       | 15       | 6.22%   |
| Canada       | 12       | 4.98%   |
| Russia       | 8        | 3.32%   |
| Sweden       | 6        | 2.49%   |
| UK           | 5        | 2.07%   |
| Poland       | 5        | 2.07%   |
| Netherlands  | 5        | 2.07%   |
| Spain        | 4        | 1.66%   |
| Belgium      | 4        | 1.66%   |
| Australia    | 4        | 1.66%   |
| Argentina    | 4        | 1.66%   |
| Switzerland  | 3        | 1.24%   |
| Portugal     | 2        | 0.83%   |
| Norway       | 2        | 0.83%   |
| Mexico       | 2        | 0.83%   |
| Iran         | 2        | 0.83%   |
| India        | 2        | 0.83%   |
| Hungary      | 2        | 0.83%   |
| Greece       | 2        | 0.83%   |
| Finland      | 2        | 0.83%   |
| Czechia      | 2        | 0.83%   |
| Colombia     | 2        | 0.83%   |
| China        | 2        | 0.83%   |
| Belarus      | 2        | 0.83%   |
| Austria      | 2        | 0.83%   |
| Turkey       | 1        | 0.41%   |
| Taiwan       | 1        | 0.41%   |
| South Africa | 1        | 0.41%   |
| Slovenia     | 1        | 0.41%   |
| Serbia       | 1        | 0.41%   |
| Romania      | 1        | 0.41%   |
| Pakistan     | 1        | 0.41%   |
| New Zealand  | 1        | 0.41%   |
| Madagascar   | 1        | 0.41%   |
| Japan        | 1        | 0.41%   |
| Ireland      | 1        | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Berlin               | 6        | 2.4%    |
| Paris                | 5        | 2%      |
| Sydney               | 3        | 1.2%    |
| Springfield          | 3        | 1.2%    |
| Rio de Janeiro       | 3        | 1.2%    |
| Milan                | 3        | 1.2%    |
| Harrisonburg         | 3        | 1.2%    |
| Toul                 | 2        | 0.8%    |
| Toronto              | 2        | 0.8%    |
| Tehran               | 2        | 0.8%    |
| Stuttgart            | 2        | 0.8%    |
| Schwerte             | 2        | 0.8%    |
| Santiago de Cali     | 2        | 0.8%    |
| Rho                  | 2        | 0.8%    |
| Peterborough         | 2        | 0.8%    |
| Munich               | 2        | 0.8%    |
| Lisbon               | 2        | 0.8%    |
| Lake Placid          | 2        | 0.8%    |
| Helsinki             | 2        | 0.8%    |
| Hanover              | 2        | 0.8%    |
| Gdansk               | 2        | 0.8%    |
| Clermont-Ferrand     | 2        | 0.8%    |
| Budapest             | 2        | 0.8%    |
| Biella               | 2        | 0.8%    |
| Amsterdam            | 2        | 0.8%    |
| Żywiec              | 1        | 0.4%    |
| Yvoir                | 1        | 0.4%    |
| Wusterhausen         | 1        | 0.4%    |
| Wojnicz              | 1        | 0.4%    |
| Winkelhaid           | 1        | 0.4%    |
| Wilhelmshaven        | 1        | 0.4%    |
| Wiener Neustadt      | 1        | 0.4%    |
| White House          | 1        | 0.4%    |
| Wettringen           | 1        | 0.4%    |
| Washington           | 1        | 0.4%    |
| Waghausel            | 1        | 0.4%    |
| Waarder              | 1        | 0.4%    |
| Vohenstrauss         | 1        | 0.4%    |
| Vohburg an der Donau | 1        | 0.4%    |
| Vise                 | 1        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 81       | 134    | 18.12%  |
| Seagate                     | 66       | 92     | 14.77%  |
| Samsung Electronics         | 65       | 86     | 14.54%  |
| Kingston                    | 33       | 43     | 7.38%   |
| Toshiba                     | 26       | 29     | 5.82%   |
| Hitachi                     | 23       | 34     | 5.15%   |
| Crucial                     | 20       | 26     | 4.47%   |
| SanDisk                     | 18       | 24     | 4.03%   |
| China                       | 9        | 9      | 2.01%   |
| Unknown                     | 8        | 12     | 1.79%   |
| Intel                       | 8        | 10     | 1.79%   |
| HGST                        | 7        | 11     | 1.57%   |
| A-DATA Technology           | 7        | 7      | 1.57%   |
| PNY                         | 6        | 7      | 1.34%   |
| SPCC                        | 4        | 4      | 0.89%   |
| Gigabyte Technology         | 4        | 5      | 0.89%   |
| ASMT                        | 4        | 7      | 0.89%   |
| Patriot                     | 3        | 3      | 0.67%   |
| Intenso                     | 3        | 3      | 0.67%   |
| Hewlett-Packard             | 3        | 4      | 0.67%   |
| TEXTORM                     | 2        | 2      | 0.45%   |
| SK hynix                    | 2        | 2      | 0.45%   |
| Phison Electronics          | 2        | 4      | 0.45%   |
| PHD 3.0                     | 2        | 2      | 0.45%   |
| OCZ                         | 2        | 2      | 0.45%   |
| Micron Technology           | 2        | 2      | 0.45%   |
| Maxtor                      | 2        | 2      | 0.45%   |
| Lexar                       | 2        | 2      | 0.45%   |
| KIOXIA                      | 2        | 2      | 0.45%   |
| Kingston Technology Company | 2        | 4      | 0.45%   |
| Corsair                     | 2        | 2      | 0.45%   |
| XPG                         | 1        | 1      | 0.22%   |
| Veno                        | 1        | 1      | 0.22%   |
| Vaseky                      | 1        | 1      | 0.22%   |
| USB3.0                      | 1        | 2      | 0.22%   |
| TO Exter                    | 1        | 2      | 0.22%   |
| Timetec                     | 1        | 1      | 0.22%   |
| Silicon Motion              | 1        | 1      | 0.22%   |
| Realtek Semiconductor       | 1        | 1      | 0.22%   |
| Phison                      | 1        | 8      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB        | 9        | 1.73%   |
| Kingston SA400S37240G 240GB SSD  | 8        | 1.54%   |
| Crucial CT480BX500SSD1 480GB     | 7        | 1.35%   |
| Toshiba DT01ACA100 1TB           | 6        | 1.15%   |
| Seagate ST1000DM003-1ER162 1TB   | 6        | 1.15%   |
| Seagate ST500DM002-1BD142 500GB  | 5        | 0.96%   |
| Seagate ST2000DM008-2FR102 2TB   | 5        | 0.96%   |
| Kingston SV300S37A120G 120GB SSD | 5        | 0.96%   |
| Kingston SA400S37480G 480GB SSD  | 5        | 0.96%   |
| Toshiba HDWD110 1TB              | 4        | 0.77%   |
| Toshiba DT01ACA200 2TB           | 4        | 0.77%   |
| Seagate ST1000DM003-1CH162 1TB   | 4        | 0.77%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 3        | 0.58%   |
| WDC WD10EZEX-08M2NA0 1TB         | 3        | 0.58%   |
| Unknown SD/MMC/MS PRO 256GB      | 3        | 0.58%   |
| Seagate ST4000DM004-2CV104 4TB   | 3        | 0.58%   |
| Seagate ST1000DM003-1SB102 1TB   | 3        | 0.58%   |
| SanDisk SDSSDA240G 240GB         | 3        | 0.58%   |
| Samsung SSD 870 QVO 1TB          | 3        | 0.58%   |
| Samsung SSD 850 EVO 500GB        | 3        | 0.58%   |
| Samsung SSD 850 EVO 250GB        | 3        | 0.58%   |
| Samsung SSD 840 Series 120GB     | 3        | 0.58%   |
| Samsung SSD 840 EVO 250GB        | 3        | 0.58%   |
| Samsung HD250HJ 250GB            | 3        | 0.58%   |
| Kingston SUV400S37120G 120GB SSD | 3        | 0.58%   |
| Kingston SA2000M81000G 1TB       | 3        | 0.58%   |
| Hitachi HDS721010CLA332 1TB      | 3        | 0.58%   |
| WDC WDS250G2B0B-00YS70 250GB SSD | 2        | 0.38%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 2        | 0.38%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 2        | 0.38%   |
| WDC WD5000AADS-00S9B0 500GB      | 2        | 0.38%   |
| WDC WD3200AAKS-00L9A0 320GB      | 2        | 0.38%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.38%   |
| WDC WD20EARS-00MVWB0 2TB         | 2        | 0.38%   |
| WDC WD10JPVX-22JC3T0 1TB         | 2        | 0.38%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 2        | 0.38%   |
| WDC WD10EZEX-00BBHA0 1TB         | 2        | 0.38%   |
| Toshiba DT01ACA050 500GB         | 2        | 0.38%   |
| TEXTORM BM5 240GB                | 2        | 0.38%   |
| Seagate ST9500420AS 500GB        | 2        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 75       | 125    | 34.4%   |
| Seagate             | 66       | 90     | 30.28%  |
| Toshiba             | 23       | 26     | 10.55%  |
| Hitachi             | 23       | 34     | 10.55%  |
| Samsung Electronics | 11       | 15     | 5.05%   |
| HGST                | 7        | 11     | 3.21%   |
| Unknown             | 3        | 4      | 1.38%   |
| ASMT                | 2        | 5      | 0.92%   |
| USB3.0              | 1        | 2      | 0.46%   |
| TO Exter            | 1        | 2      | 0.46%   |
| Maxtor              | 1        | 1      | 0.46%   |
| MARVELL             | 1        | 1      | 0.46%   |
| LaCie               | 1        | 1      | 0.46%   |
| ICY BOX             | 1        | 1      | 0.46%   |
| Hewlett-Packard     | 1        | 1      | 0.46%   |
| Apple               | 1        | 1      | 0.46%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 40       | 51     | 23.95%  |
| Kingston            | 26       | 32     | 15.57%  |
| Crucial             | 18       | 24     | 10.78%  |
| SanDisk             | 13       | 17     | 7.78%   |
| China               | 9        | 9      | 5.39%   |
| WDC                 | 8        | 8      | 4.79%   |
| A-DATA Technology   | 6        | 6      | 3.59%   |
| PNY                 | 5        | 6      | 2.99%   |
| SPCC                | 4        | 4      | 2.4%    |
| Toshiba             | 3        | 3      | 1.8%    |
| Patriot             | 3        | 3      | 1.8%    |
| Intenso             | 3        | 3      | 1.8%    |
| Intel               | 3        | 3      | 1.8%    |
| TEXTORM             | 2        | 2      | 1.2%    |
| PHD 3.0             | 2        | 2      | 1.2%    |
| OCZ                 | 2        | 2      | 1.2%    |
| Hewlett-Packard     | 2        | 3      | 1.2%    |
| Gigabyte Technology | 2        | 2      | 1.2%    |
| ASMT                | 2        | 2      | 1.2%    |
| Veno                | 1        | 1      | 0.6%    |
| Vaseky              | 1        | 1      | 0.6%    |
| Timetec             | 1        | 1      | 0.6%    |
| Micron Technology   | 1        | 1      | 0.6%    |
| Maxtor              | 1        | 1      | 0.6%    |
| LITEONIT            | 1        | 1      | 0.6%    |
| LITEON              | 1        | 1      | 0.6%    |
| Linux               | 1        | 1      | 0.6%    |
| Lexar               | 1        | 1      | 0.6%    |
| KIOXIA-EXCERIA      | 1        | 1      | 0.6%    |
| KingFast            | 1        | 1      | 0.6%    |
| KingDian            | 1        | 1      | 0.6%    |
| Dogfish             | 1        | 1      | 0.6%    |
| Corsair             | 1        | 1      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 165      | 320    | 44.72%  |
| SSD     | 141      | 196    | 38.21%  |
| NVMe    | 53       | 83     | 14.36%  |
| Unknown | 7        | 9      | 1.9%    |
| MMC     | 3        | 4      | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 223      | 485    | 73.84%  |
| NVMe | 53       | 83     | 17.55%  |
| SAS  | 23       | 40     | 7.62%   |
| MMC  | 3        | 4      | 0.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 177      | 289    | 53.15%  |
| 0.51-1.0   | 85       | 128    | 25.53%  |
| 1.01-2.0   | 40       | 52     | 12.01%  |
| 3.01-4.0   | 20       | 31     | 6.01%   |
| 2.01-3.0   | 6        | 8      | 1.8%    |
| 4.01-10.0  | 3        | 5      | 0.9%    |
| 10.01-20.0 | 2        | 3      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 62       | 25.2%   |
| 251-500        | 48       | 19.51%  |
| 1001-2000      | 36       | 14.63%  |
| 501-1000       | 36       | 14.63%  |
| More than 3000 | 29       | 11.79%  |
| 2001-3000      | 17       | 6.91%   |
| 51-100         | 7        | 2.85%   |
| 1-20           | 6        | 2.44%   |
| 21-50          | 5        | 2.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 56       | 22.13%  |
| 251-500        | 39       | 15.42%  |
| 21-50          | 34       | 13.44%  |
| 101-250        | 34       | 13.44%  |
| 51-100         | 27       | 10.67%  |
| 1001-2000      | 19       | 7.51%   |
| 501-1000       | 19       | 7.51%   |
| 2001-3000      | 14       | 5.53%   |
| More than 3000 | 11       | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB            | 2        | 2      | 3.92%   |
| Seagate ST1000DM003-1ER162 1TB    | 2        | 2      | 3.92%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 1      | 1.96%   |
| WDC WD5000BEVT-22A0RT0 500GB      | 1        | 1      | 1.96%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 1.96%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 1.96%   |
| WDC WD3200AAKS-75B3A0 320GB       | 1        | 2      | 1.96%   |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 1.96%   |
| WDC WD2500AAKS-00VSA0 250GB       | 1        | 1      | 1.96%   |
| WDC WD20EFRX-68AX9N0 2TB          | 1        | 1      | 1.96%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 1.96%   |
| WDC WD2002FYPS-02W3B0 2TB         | 1        | 1      | 1.96%   |
| WDC WD10EZEX-60ZF5A0 1TB          | 1        | 1      | 1.96%   |
| WDC WD10EAVS-00D7B1 1TB           | 1        | 1      | 1.96%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 1.96%   |
| WDC WD10EARS-003BB1 1TB           | 1        | 1      | 1.96%   |
| WDC WD1003FBYX-01Y7B1 1TB         | 1        | 1      | 1.96%   |
| Seagate ST9250410AS 250GB         | 1        | 1      | 1.96%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 1.96%   |
| Seagate ST4000DX001-1CE168 4TB    | 1        | 1      | 1.96%   |
| Seagate ST3750840AS 752GB         | 1        | 1      | 1.96%   |
| Seagate ST3500414CS 500GB         | 1        | 1      | 1.96%   |
| Seagate ST3250318AS 250GB         | 1        | 2      | 1.96%   |
| Seagate ST3250310AS 250GB         | 1        | 1      | 1.96%   |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 1.96%   |
| Seagate ST18000NM000J-2TV103 18TB | 1        | 1      | 1.96%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 1.96%   |
| Samsung Electronics SP2514N 250GB | 1        | 1      | 1.96%   |
| Samsung Electronics HM321HI 320GB | 1        | 2      | 1.96%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 1.96%   |
| Samsung Electronics HD250HJ 250GB | 1        | 1      | 1.96%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 1.96%   |
| PNY 69D03094-T 40GB SSD           | 1        | 1      | 1.96%   |
| Maxtor STM3160215AS 160GB         | 1        | 1      | 1.96%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 1.96%   |
| Kingston A400 256GB SSD           | 1        | 1      | 1.96%   |
| Intel SSDSC2BW120A4 120GB         | 1        | 1      | 1.96%   |
| ICY BOX IB-250StU3+BH15 2TB       | 1        | 1      | 1.96%   |
| Hitachi HTS723216L9A360 160GB     | 1        | 1      | 1.96%   |
| Hitachi HTS547575A9E384 752GB     | 1        | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 16     | 28.57%  |
| Seagate             | 12       | 13     | 24.49%  |
| Hitachi             | 5        | 6      | 10.2%   |
| Samsung Electronics | 4        | 6      | 8.16%   |
| Toshiba             | 2        | 2      | 4.08%   |
| Kingston            | 2        | 2      | 4.08%   |
| PNY                 | 1        | 1      | 2.04%   |
| Maxtor              | 1        | 1      | 2.04%   |
| Intel               | 1        | 1      | 2.04%   |
| ICY BOX             | 1        | 1      | 2.04%   |
| HGST                | 1        | 3      | 2.04%   |
| Hewlett-Packard     | 1        | 1      | 2.04%   |
| Crucial             | 1        | 1      | 2.04%   |
| China               | 1        | 1      | 2.04%   |
| ASMT                | 1        | 4      | 2.04%   |
| A-DATA Technology   | 1        | 1      | 2.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 15     | 31.71%  |
| Seagate             | 12       | 13     | 29.27%  |
| Hitachi             | 5        | 6      | 12.2%   |
| Samsung Electronics | 4        | 6      | 9.76%   |
| Toshiba             | 2        | 2      | 4.88%   |
| Maxtor              | 1        | 1      | 2.44%   |
| ICY BOX             | 1        | 1      | 2.44%   |
| HGST                | 1        | 3      | 2.44%   |
| Hewlett-Packard     | 1        | 1      | 2.44%   |
| ASMT                | 1        | 4      | 2.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 36       | 52     | 83.72%  |
| SSD  | 6        | 7      | 13.95%  |
| NVMe | 1        | 1      | 2.33%   |

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
| Works    | 143      | 304    | 50.35%  |
| Detected | 99       | 248    | 34.86%  |
| Malfunc  | 42       | 60     | 14.79%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 157      | 47.58%  |
| AMD                              | 74       | 22.42%  |
| Samsung Electronics              | 17       | 5.15%   |
| JMicron Technology               | 12       | 3.64%   |
| Kingston Technology Company      | 10       | 3.03%   |
| ASMedia Technology               | 10       | 3.03%   |
| Phison Electronics               | 7        | 2.12%   |
| Marvell Technology Group         | 7        | 2.12%   |
| SanDisk                          | 6        | 1.82%   |
| Nvidia                           | 4        | 1.21%   |
| VIA Technologies                 | 3        | 0.91%   |
| Silicon Image                    | 3        | 0.91%   |
| Realtek Semiconductor            | 3        | 0.91%   |
| SK hynix                         | 2        | 0.61%   |
| Silicon Motion                   | 2        | 0.61%   |
| Micron/Crucial Technology        | 2        | 0.61%   |
| KIOXIA                           | 2        | 0.61%   |
| Silicon Integrated Systems [SiS] | 1        | 0.3%    |
| Shenzhen Longsys Electronics     | 1        | 0.3%    |
| Micron Technology                | 1        | 0.3%    |
| MAXIO Technology (Hangzhou)      | 1        | 0.3%    |
| LSI Logic / Symbios Logic        | 1        | 0.3%    |
| INNOGRIT                         | 1        | 0.3%    |
| Broadcom / LSI                   | 1        | 0.3%    |
| ADATA Technology                 | 1        | 0.3%    |
| Adaptec                          | 1        | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 42       | 10%     |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 23       | 5.48%   |
| AMD 400 Series Chipset SATA Controller                                                  | 14       | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 3.1%    |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 2.86%   |
| Intel SATA Controller [RAID mode]                                                       | 11       | 2.62%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 11       | 2.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11       | 2.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10       | 2.38%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 9        | 2.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 2.14%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 8        | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8        | 1.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 1.67%   |
| AMD FCH SATA Controller D                                                               | 7        | 1.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.43%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 5        | 1.19%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5        | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.19%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 0.95%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 0.95%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.95%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.95%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 0.95%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 0.95%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 3        | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 0.71%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.71%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.71%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 3        | 0.71%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 3        | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 197      | 60.62%  |
| NVMe | 53       | 16.31%  |
| IDE  | 50       | 15.38%  |
| RAID | 21       | 6.46%   |
| SAS  | 3        | 0.92%   |
| SCSI | 1        | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 160      | 66.67%  |
| AMD    | 80       | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 7        | 2.9%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 1.66%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 1.66%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 1.24%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 3        | 1.24%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 1.24%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.24%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 1.24%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.24%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 3        | 1.24%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 3        | 1.24%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 3        | 1.24%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.24%   |
| AMD Phenom II X4 955 Processor              | 3        | 1.24%   |
| AMD FX-6300 Six-Core Processor              | 3        | 1.24%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz         | 2        | 0.83%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 0.83%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.83%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.83%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 0.83%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.83%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 2        | 0.83%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.83%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 0.83%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 2        | 0.83%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.83%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 0.83%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 0.83%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2        | 0.83%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 2        | 0.83%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 0.83%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.83%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 0.83%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 0.83%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 0.83%   |
| Intel 13th Gen Core i7-13700KF              | 2        | 0.83%   |
| Intel 13th Gen Core i5-13600K               | 2        | 0.83%   |
| Intel 12th Gen Core i7-12700                | 2        | 0.83%   |
| Intel 12th Gen Core i3-12100F               | 2        | 0.83%   |
| Intel 12th Gen Core i3-12100                | 2        | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 46       | 19.09%  |
| Intel Core i7           | 29       | 12.03%  |
| AMD Ryzen 5             | 25       | 10.37%  |
| Intel Core i3           | 23       | 9.54%   |
| Other                   | 15       | 6.22%   |
| Intel Celeron           | 15       | 6.22%   |
| AMD Ryzen 7             | 12       | 4.98%   |
| Intel Xeon              | 10       | 4.15%   |
| Intel Core 2 Duo        | 7        | 2.9%    |
| Intel Core 2 Quad       | 6        | 2.49%   |
| AMD FX                  | 6        | 2.49%   |
| AMD Ryzen 9             | 5        | 2.07%   |
| AMD A8                  | 5        | 2.07%   |
| AMD Phenom II X4        | 4        | 1.66%   |
| Intel Pentium Dual-Core | 3        | 1.24%   |
| Intel Pentium           | 3        | 1.24%   |
| AMD Ryzen 3             | 3        | 1.24%   |
| AMD Athlon II X2        | 3        | 1.24%   |
| Intel Pentium 4         | 2        | 0.83%   |
| Intel Atom              | 2        | 0.83%   |
| AMD GX                  | 2        | 0.83%   |
| AMD Athlon 64 X2        | 2        | 0.83%   |
| AMD A6                  | 2        | 0.83%   |
| AMD A10                 | 2        | 0.83%   |
| AMD Turion II Neo       | 1        | 0.41%   |
| AMD Sempron             | 1        | 0.41%   |
| AMD Ryzen 7 PRO         | 1        | 0.41%   |
| AMD Ryzen 5 PRO         | 1        | 0.41%   |
| AMD Phenom II X6        | 1        | 0.41%   |
| AMD E1                  | 1        | 0.41%   |
| AMD Athlon X4           | 1        | 0.41%   |
| AMD Athlon II           | 1        | 0.41%   |
| AMD Athlon              | 1        | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 103      | 42.56%  |
| 2      | 60       | 24.79%  |
| 6      | 36       | 14.88%  |
| 8      | 17       | 7.02%   |
| 1      | 7        | 2.89%   |
| 12     | 5        | 2.07%   |
| 16     | 4        | 1.65%   |
| 10     | 3        | 1.24%   |
| 3      | 3        | 1.24%   |
| 14     | 2        | 0.83%   |
| 24     | 1        | 0.41%   |
| 18     | 1        | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 240      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 139      | 57.92%  |
| 1      | 101      | 42.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 240      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 110      | 45.27%  |
| 0x306c3    | 14       | 5.76%   |
| 0x306a9    | 10       | 4.12%   |
| 0x206a7    | 8        | 3.29%   |
| 0x08701021 | 6        | 2.47%   |
| 0x0800820d | 6        | 2.47%   |
| 0x906ea    | 5        | 2.06%   |
| 0x1067a    | 5        | 2.06%   |
| 0x06000852 | 5        | 2.06%   |
| 0x010000c8 | 5        | 2.06%   |
| 0x506e3    | 4        | 1.65%   |
| 0xb0671    | 3        | 1.23%   |
| 0x90672    | 3        | 1.23%   |
| 0x306e4    | 3        | 1.23%   |
| 0x106e5    | 3        | 1.23%   |
| 0x08108109 | 3        | 1.23%   |
| 0x906e9    | 2        | 0.82%   |
| 0x406c3    | 2        | 0.82%   |
| 0x206d7    | 2        | 0.82%   |
| 0x10676    | 2        | 0.82%   |
| 0x0a201016 | 2        | 0.82%   |
| 0x08701030 | 2        | 0.82%   |
| 0x08701013 | 2        | 0.82%   |
| 0x0700010f | 2        | 0.82%   |
| 0x010000c7 | 2        | 0.82%   |
| 0xa0655    | 1        | 0.41%   |
| 0xa0653    | 1        | 0.41%   |
| 0x906ed    | 1        | 0.41%   |
| 0x906eb    | 1        | 0.41%   |
| 0x706a1    | 1        | 0.41%   |
| 0x6fb      | 1        | 0.41%   |
| 0x506c9    | 1        | 0.41%   |
| 0x406c4    | 1        | 0.41%   |
| 0x306f2    | 1        | 0.41%   |
| 0x30679    | 1        | 0.41%   |
| 0x30678    | 1        | 0.41%   |
| 0x206d6    | 1        | 0.41%   |
| 0x206c2    | 1        | 0.41%   |
| 0x20652    | 1        | 0.41%   |
| 0x106ca    | 1        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 32       | 13.28%  |
| SandyBridge      | 21       | 8.71%   |
| KabyLake         | 20       | 8.3%    |
| Zen 2            | 19       | 7.88%   |
| IvyBridge        | 19       | 7.88%   |
| Zen+             | 12       | 4.98%   |
| Penryn           | 12       | 4.98%   |
| Piledriver       | 11       | 4.56%   |
| Unknown          | 11       | 4.56%   |
| K10              | 10       | 4.15%   |
| Zen 3            | 9        | 3.73%   |
| Skylake          | 7        | 2.9%    |
| CometLake        | 7        | 2.9%    |
| Silvermont       | 6        | 2.49%   |
| Nehalem          | 6        | 2.49%   |
| Alderlake Hybrid | 6        | 2.49%   |
| Zen              | 5        | 2.07%   |
| Core             | 5        | 2.07%   |
| Westmere         | 3        | 1.24%   |
| Jaguar           | 3        | 1.24%   |
| Excavator        | 3        | 1.24%   |
| Steamroller      | 2        | 0.83%   |
| NetBurst         | 2        | 0.83%   |
| K8 Hammer        | 2        | 0.83%   |
| Broadwell        | 2        | 0.83%   |
| Bonnell          | 2        | 0.83%   |
| K10 Llano        | 1        | 0.41%   |
| Goldmont plus    | 1        | 0.41%   |
| Goldmont         | 1        | 0.41%   |
| Bobcat           | 1        | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 98       | 37.69%  |
| Nvidia                           | 92       | 35.38%  |
| AMD                              | 69       | 26.54%  |
| Silicon Integrated Systems [SiS] | 1        | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 18       | 6.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13       | 4.85%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 11       | 4.1%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9        | 3.36%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7        | 2.61%   |
| Intel HD Graphics 530                                                                    | 7        | 2.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6        | 2.24%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6        | 2.24%   |
| Intel HD Graphics 630                                                                    | 5        | 1.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5        | 1.87%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4        | 1.49%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4        | 1.49%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 3        | 1.12%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 3        | 1.12%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 3        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 1.12%   |
| Intel AlderLake-S GT1                                                                    | 3        | 1.12%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 3        | 1.12%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 1.12%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.12%   |
| AMD RS780L [Radeon 3000]                                                                 | 3        | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 1.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 1.12%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 1.12%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 3        | 1.12%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2        | 0.75%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 2        | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 0.75%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 0.75%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 2        | 0.75%   |
| Nvidia GK107GL [Quadro K2000]                                                            | 2        | 0.75%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 2        | 0.75%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 0.75%   |
| Intel DG2 [Arc A770]                                                                     | 2        | 0.75%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2        | 0.75%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 0.75%   |
| AMD RS880 [Radeon HD 4250]                                                               | 2        | 0.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 0.75%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 82       | 34.02%  |
| 1 x Intel      | 82       | 34.02%  |
| 1 x AMD        | 58       | 24.07%  |
| 2 x AMD        | 5        | 2.07%   |
| Intel + Nvidia | 5        | 2.07%   |
| AMD + Nvidia   | 4        | 1.66%   |
| Intel + AMD    | 3        | 1.24%   |
| 2 x Nvidia     | 1        | 0.41%   |
| 1 x SiS        | 1        | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 172      | 71.07%  |
| Proprietary | 59       | 24.38%  |
| Unknown     | 11       | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 143      | 59.09%  |
| 0.51-1.0   | 25       | 10.33%  |
| 1.01-2.0   | 24       | 9.92%   |
| 0.01-0.5   | 16       | 6.61%   |
| 3.01-4.0   | 12       | 4.96%   |
| 7.01-8.0   | 8        | 3.31%   |
| 5.01-6.0   | 6        | 2.48%   |
| 8.01-16.0  | 6        | 2.48%   |
| 2.01-3.0   | 2        | 0.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 36       | 14.4%   |
| Samsung Electronics  | 35       | 14%     |
| Hewlett-Packard      | 24       | 9.6%    |
| Goldstar             | 21       | 8.4%    |
| AOC                  | 18       | 7.2%    |
| Acer                 | 17       | 6.8%    |
| Ancor Communications | 12       | 4.8%    |
| BenQ                 | 10       | 4%      |
| Philips              | 9        | 3.6%    |
| Iiyama               | 8        | 3.2%    |
| ViewSonic            | 6        | 2.4%    |
| Fujitsu Siemens      | 5        | 2%      |
| Lenovo               | 3        | 1.2%    |
| ASUSTek Computer     | 3        | 1.2%    |
| Unknown              | 2        | 0.8%    |
| Sceptre Tech         | 2        | 0.8%    |
| RTK                  | 2        | 0.8%    |
| HannStar             | 2        | 0.8%    |
| Eizo                 | 2        | 0.8%    |
| Denver               | 2        | 0.8%    |
| Unknown              | 2        | 0.8%    |
| ___                  | 1        | 0.4%    |
| Vestel Elektronik    | 1        | 0.4%    |
| Unknown (AAA)        | 1        | 0.4%    |
| UGD                  | 1        | 0.4%    |
| Toshiba              | 1        | 0.4%    |
| TEO                  | 1        | 0.4%    |
| Tech Concepts        | 1        | 0.4%    |
| TCL                  | 1        | 0.4%    |
| Sony                 | 1        | 0.4%    |
| SNC                  | 1        | 0.4%    |
| Sharp                | 1        | 0.4%    |
| RGT                  | 1        | 0.4%    |
| Packard Bell         | 1        | 0.4%    |
| NEC Computers        | 1        | 0.4%    |
| Mi                   | 1        | 0.4%    |
| MAG                  | 1        | 0.4%    |
| LG Electronics       | 1        | 0.4%    |
| JRY                  | 1        | 0.4%    |
| JINGLITAI            | 1        | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 1.12%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 3        | 1.12%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 2        | 0.75%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 2        | 0.75%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                    | 2        | 0.75%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 2        | 0.75%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch            | 2        | 0.75%   |
| HannStar HL205DPB HSD62E0 1600x900 432x240mm 19.5-inch                | 2        | 0.75%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.75%   |
| Dell U3011 DEL4065 2560x1600 641x401mm 29.8-inch                      | 2        | 0.75%   |
| Dell 2001FP DELA008 1600x1200 367x275mm 18.1-inch                     | 2        | 0.75%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 2        | 0.75%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 2        | 0.75%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 2        | 0.75%   |
| Ancor Communications ASUS VS229 ACI22C2 1920x1080 477x268mm 21.5-inch | 2        | 0.75%   |
| Unknown                                                               | 2        | 0.75%   |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                    | 1        | 0.37%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch         | 1        | 0.37%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch            | 1        | 0.37%   |
| ViewSonic VP2365 SERIES VSC7C28 1920x1080 509x286mm 23.0-inch         | 1        | 0.37%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch          | 1        | 0.37%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 1        | 0.37%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.37%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 0.37%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch              | 1        | 0.37%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                  | 1        | 0.37%   |
| Toshiba TV TSB0109 1920x1080                                          | 1        | 0.37%   |
| TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                       | 1        | 0.37%   |
| Tech Concepts LCD Monitor 32S327 1280x720                             | 1        | 0.37%   |
| TCL TCL TCL0030 1600x1200 708x398mm 32.0-inch                         | 1        | 0.37%   |
| Sony TV SNYAB03 1920x1080                                             | 1        | 0.37%   |
| SNC SKP_E20-27 SNC2700 2560x1440 597x336mm 27.0-inch                  | 1        | 0.37%   |
| Sharp HDMI SHP0FDB 1360x768 820x460mm 37.0-inch                       | 1        | 0.37%   |
| Sceptre Tech Sceptre Y27 SPT0AB9 2560x1440 597x336mm 27.0-inch        | 1        | 0.37%   |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 597x336mm 27.0-inch        | 1        | 0.37%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                      | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM05C4 1920x1080 510x287mm 23.0-inch  | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM0577 1920x1080 476x268mm 21.5-inch  | 1        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 112      | 44.8%   |
| 1280x1024 (SXGA)   | 18       | 7.2%    |
| 2560x1440 (QHD)    | 16       | 6.4%    |
| 1366x768 (WXGA)    | 16       | 6.4%    |
| 3840x2160 (4K)     | 13       | 5.2%    |
| 1440x900 (WXGA+)   | 13       | 5.2%    |
| 1600x900 (HD+)     | 12       | 4.8%    |
| 1680x1050 (WSXGA+) | 10       | 4%      |
| 1024x768 (XGA)     | 6        | 2.4%    |
| 1600x1200          | 5        | 2%      |
| 1360x768           | 5        | 2%      |
| 2560x1600          | 4        | 1.6%    |
| 1920x1200 (WUXGA)  | 4        | 1.6%    |
| 3840x1080          | 3        | 1.2%    |
| 3440x1440          | 3        | 1.2%    |
| 2560x1080          | 3        | 1.2%    |
| 3840x1600          | 2        | 0.8%    |
| Unknown            | 2        | 0.8%    |
| 2288x1287          | 1        | 0.4%    |
| 1920x540           | 1        | 0.4%    |
| 1280x720 (HD)      | 1        | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 37       | 14.45%  |
| 23      | 34       | 13.28%  |
| 27      | 26       | 10.16%  |
| 21      | 24       | 9.38%   |
| 19      | 23       | 8.98%   |
| 18      | 18       | 7.03%   |
| 20      | 14       | 5.47%   |
| Unknown | 12       | 4.69%   |
| 17      | 9        | 3.52%   |
| 31      | 8        | 3.13%   |
| 22      | 7        | 2.73%   |
| 15      | 7        | 2.73%   |
| 34      | 6        | 2.34%   |
| 40      | 5        | 1.95%   |
| 37      | 3        | 1.17%   |
| 29      | 3        | 1.17%   |
| 25      | 3        | 1.17%   |
| 72      | 2        | 0.78%   |
| 49      | 2        | 0.78%   |
| 32      | 2        | 0.78%   |
| 26      | 2        | 0.78%   |
| 14      | 2        | 0.78%   |
| 142     | 1        | 0.39%   |
| 84      | 1        | 0.39%   |
| 54      | 1        | 0.39%   |
| 48      | 1        | 0.39%   |
| 30      | 1        | 0.39%   |
| 28      | 1        | 0.39%   |
| 6       | 1        | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 93       | 37.5%   |
| 401-500        | 79       | 31.85%  |
| 301-350        | 17       | 6.85%   |
| 601-700        | 15       | 6.05%   |
| Unknown        | 12       | 4.84%   |
| 801-900        | 8        | 3.23%   |
| 701-800        | 8        | 3.23%   |
| 351-400        | 6        | 2.42%   |
| 1001-1500      | 4        | 1.61%   |
| 1501-2000      | 3        | 1.21%   |
| More than 2000 | 1        | 0.4%    |
| 201-300        | 1        | 0.4%    |
| 101-200        | 1        | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 154      | 65.81%  |
| 16/10   | 33       | 14.1%   |
| 5/4     | 14       | 5.98%   |
| 4/3     | 10       | 4.27%   |
| Unknown | 10       | 4.27%   |
| 21/9    | 8        | 3.42%   |
| 32/9    | 2        | 0.85%   |
| 6/5     | 1        | 0.43%   |
| 3/2     | 1        | 0.43%   |
| 1.00    | 1        | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 82       | 32.67%  |
| 151-200        | 48       | 19.12%  |
| 301-350        | 27       | 10.76%  |
| 141-150        | 26       | 10.36%  |
| 351-500        | 20       | 7.97%   |
| Unknown        | 12       | 4.78%   |
| 251-300        | 11       | 4.38%   |
| 501-1000       | 9        | 3.59%   |
| 101-110        | 8        | 3.19%   |
| More than 1000 | 6        | 2.39%   |
| 81-90          | 1        | 0.4%    |
| 1-40           | 1        | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 157      | 67.09%  |
| 101-120       | 46       | 19.66%  |
| Unknown       | 12       | 5.13%   |
| 121-160       | 9        | 3.85%   |
| 1-50          | 8        | 3.42%   |
| More than 240 | 1        | 0.43%   |
| 161-240       | 1        | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 183      | 75.31%  |
| 2     | 38       | 15.64%  |
| 0     | 15       | 6.17%   |
| 3     | 7        | 2.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 163      | 47.66%  |
| Intel                           | 102      | 29.82%  |
| Qualcomm Atheros                | 21       | 6.14%   |
| Ralink Technology               | 9        | 2.63%   |
| TP-Link                         | 4        | 1.17%   |
| Nvidia                          | 4        | 1.17%   |
| Broadcom Limited                | 4        | 1.17%   |
| Broadcom                        | 4        | 1.17%   |
| NetGear                         | 3        | 0.88%   |
| Samsung Electronics             | 2        | 0.58%   |
| Ralink                          | 2        | 0.58%   |
| MediaTek                        | 2        | 0.58%   |
| Marvell Technology Group        | 2        | 0.58%   |
| D-Link System                   | 2        | 0.58%   |
| Belkin Components               | 2        | 0.58%   |
| ASIX Electronics                | 2        | 0.58%   |
| ZyDAS                           | 1        | 0.29%   |
| Zoom Telephonics                | 1        | 0.29%   |
| TRENDnet                        | 1        | 0.29%   |
| Qualcomm Atheros Communications | 1        | 0.29%   |
| OPPO Electronics                | 1        | 0.29%   |
| MicroPython                     | 1        | 0.29%   |
| Microchip Technology            | 1        | 0.29%   |
| Mellanox Technologies           | 1        | 0.29%   |
| Linksys                         | 1        | 0.29%   |
| ICS Advent                      | 1        | 0.29%   |
| Dell                            | 1        | 0.29%   |
| D-Link                          | 1        | 0.29%   |
| ASUSTek Computer                | 1        | 0.29%   |
| Aquantia                        | 1        | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 125      | 32.3%   |
| Realtek RTL8125 2.5GbE Controller                                      | 20       | 5.17%   |
| Intel I211 Gigabit Network Connection                                  | 12       | 3.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12       | 3.1%    |
| Intel Wi-Fi 6 AX200                                                    | 9        | 2.33%   |
| Intel Ethernet Connection I217-LM                                      | 9        | 2.33%   |
| Intel Ethernet Connection (2) I219-V                                   | 9        | 2.33%   |
| Intel Ethernet Controller I225-V                                       | 7        | 1.81%   |
| Ralink MT7601U Wireless Adapter                                        | 6        | 1.55%   |
| Intel Ethernet Connection I217-V                                       | 6        | 1.55%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4        | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4        | 1.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 1.03%   |
| Realtek 802.11ac NIC                                                   | 4        | 1.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4        | 1.03%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 1.03%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4        | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4        | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 3        | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3        | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3        | 0.78%   |
| Intel Wireless 7260                                                    | 3        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 0.78%   |
| Intel Ethernet Connection (14) I219-V                                  | 3        | 0.78%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2        | 0.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.52%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 2        | 0.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 2        | 0.52%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 2        | 0.52%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2        | 0.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 0.52%   |
| Intel Wireless 3160                                                    | 2        | 0.52%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 2        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 0.52%   |
| Intel Ethernet Connection (17) I219-V                                  | 2        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 31       | 28.97%  |
| Intel                           | 29       | 27.1%   |
| Qualcomm Atheros                | 16       | 14.95%  |
| Ralink Technology               | 9        | 8.41%   |
| TP-Link                         | 4        | 3.74%   |
| NetGear                         | 3        | 2.8%    |
| Ralink                          | 2        | 1.87%   |
| MediaTek                        | 2        | 1.87%   |
| Belkin Components               | 2        | 1.87%   |
| ZyDAS                           | 1        | 0.93%   |
| TRENDnet                        | 1        | 0.93%   |
| Qualcomm Atheros Communications | 1        | 0.93%   |
| Dell                            | 1        | 0.93%   |
| D-Link System                   | 1        | 0.93%   |
| D-Link                          | 1        | 0.93%   |
| Broadcom Limited                | 1        | 0.93%   |
| Broadcom                        | 1        | 0.93%   |
| ASUSTek Computer                | 1        | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 9        | 8.41%   |
| Ralink MT7601U Wireless Adapter                                                       | 6        | 5.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 4        | 3.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 4        | 3.74%   |
| Realtek 802.11ac NIC                                                                  | 4        | 3.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4        | 3.74%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 4        | 3.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 4        | 3.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 3        | 2.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 3        | 2.8%    |
| Intel Wireless 7260                                                                   | 3        | 2.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                           | 2        | 1.87%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 2        | 1.87%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 2        | 1.87%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 2        | 1.87%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2        | 1.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2        | 1.87%   |
| Intel Wireless 3160                                                                   | 2        | 1.87%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                     | 2        | 1.87%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                      | 2        | 1.87%   |
| Belkin Components F7D1102 N150/Surf Micro Wireless Adapter v1000 [Realtek RTL8188CUS] | 2        | 1.87%   |
| ZyDAS ZD1211B 802.11g                                                                 | 1        | 0.93%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]            | 1        | 0.93%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                   | 1        | 0.93%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1        | 0.93%   |
| TP-Link Archer T4U ver.3                                                              | 1        | 0.93%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1        | 0.93%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1        | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1        | 0.93%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 1        | 0.93%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1        | 0.93%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 0.93%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1        | 0.93%   |
| Realtek RTL8187 Wireless Adapter                                                      | 1        | 0.93%   |
| Ralink RT5572 Wireless Adapter                                                        | 1        | 0.93%   |
| Ralink RT2770 Wireless Adapter                                                        | 1        | 0.93%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                 | 1        | 0.93%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1        | 0.93%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1        | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 152      | 56.93%  |
| Intel                    | 88       | 32.96%  |
| Qualcomm Atheros         | 6        | 2.25%   |
| Nvidia                   | 4        | 1.5%    |
| Broadcom Limited         | 3        | 1.12%   |
| Broadcom                 | 3        | 1.12%   |
| Samsung Electronics      | 2        | 0.75%   |
| Marvell Technology Group | 2        | 0.75%   |
| ASIX Electronics         | 2        | 0.75%   |
| OPPO Electronics         | 1        | 0.37%   |
| Linksys                  | 1        | 0.37%   |
| ICS Advent               | 1        | 0.37%   |
| D-Link System            | 1        | 0.37%   |
| Aquantia                 | 1        | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 125      | 45.29%  |
| Realtek RTL8125 2.5GbE Controller                                      | 20       | 7.25%   |
| Intel I211 Gigabit Network Connection                                  | 12       | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12       | 4.35%   |
| Intel Ethernet Connection I217-LM                                      | 9        | 3.26%   |
| Intel Ethernet Connection (2) I219-V                                   | 9        | 3.26%   |
| Intel Ethernet Controller I225-V                                       | 7        | 2.54%   |
| Intel Ethernet Connection I217-V                                       | 6        | 2.17%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 1.45%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 1.09%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 1.09%   |
| Intel Ethernet Connection (14) I219-V                                  | 3        | 1.09%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 2        | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 0.72%   |
| Intel Ethernet Connection (17) I219-V                                  | 2        | 0.72%   |
| Intel 82578DM Gigabit Network Connection                               | 2        | 0.72%   |
| Intel 82578DC Gigabit Network Connection                               | 2        | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 0.72%   |
| Intel 82541PI Gigabit Ethernet Controller                              | 2        | 0.72%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2        | 0.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.36%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1        | 0.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 0.36%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 1        | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.36%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1        | 0.36%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1        | 0.36%   |
| Linksys Gigabit Ethernet Adapter                                       | 1        | 0.36%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 0.36%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 0.36%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 1        | 0.36%   |
| Intel 82566MM Gigabit Network Connection                               | 1        | 0.36%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 238      | 69.19%  |
| WiFi     | 102      | 29.65%  |
| Modem    | 3        | 0.87%   |
| Unknown  | 1        | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 191      | 74.9%   |
| WiFi     | 64       | 25.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 153      | 63.22%  |
| 2     | 74       | 30.58%  |
| 3     | 11       | 4.55%   |
| 4     | 2        | 0.83%   |
| 0     | 2        | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 161      | 65.98%  |
| Yes  | 83       | 34.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 26       | 34.67%  |
| Cambridge Silicon Radio         | 20       | 26.67%  |
| Realtek Semiconductor           | 10       | 13.33%  |
| Qualcomm Atheros Communications | 5        | 6.67%   |
| Broadcom                        | 4        | 5.33%   |
| IMC Networks                    | 3        | 4%      |
| TP-Link                         | 2        | 2.67%   |
| MediaTek                        | 2        | 2.67%   |
| Lite-On Technology              | 1        | 1.33%   |
| Fujitsu                         | 1        | 1.33%   |
| ASUSTek Computer                | 1        | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20       | 26.67%  |
| Intel AX200 Bluetooth                               | 9        | 12%     |
| Realtek Bluetooth Radio                             | 8        | 10.67%  |
| Intel Bluetooth wireless interface                  | 6        | 8%      |
| Intel Wireless-AC 3168 Bluetooth                    | 4        | 5.33%   |
| IMC Networks Bluetooth Radio                        | 3        | 4%      |
| TP-Link UB500 Adapter                               | 2        | 2.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 2.67%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2        | 2.67%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2        | 2.67%   |
| MediaTek Wireless_Device                            | 2        | 2.67%   |
| Intel Bluetooth Device                              | 2        | 2.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 2.67%   |
| Intel AX201 Bluetooth                               | 2        | 2.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 2.67%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 1.33%   |
| Lite-On Bluetooth Device                            | 1        | 1.33%   |
| Intel AX210 Bluetooth                               | 1        | 1.33%   |
| Fujitsu Bluetooth Device                            | 1        | 1.33%   |
| Broadcom BCM2210 Bluetooth                          | 1        | 1.33%   |
| Broadcom BCM20702A0                                 | 1        | 1.33%   |
| ASUS ASUS USB-BT500                                 | 1        | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 159      | 42.06%  |
| AMD                                          | 89       | 23.54%  |
| Nvidia                                       | 81       | 21.43%  |
| Creative Labs                                | 8        | 2.12%   |
| C-Media Electronics                          | 5        | 1.32%   |
| Texas Instruments                            | 2        | 0.53%   |
| Tenx Technology                              | 2        | 0.53%   |
| Sennheiser Communications                    | 2        | 0.53%   |
| SAVITECH                                     | 2        | 0.53%   |
| Medeli Electronics                           | 2        | 0.53%   |
| Logitech                                     | 2        | 0.53%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.26%   |
| VIA Technologies                             | 1        | 0.26%   |
| STMicroelectronics                           | 1        | 0.26%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.26%   |
| Samson Technologies                          | 1        | 0.26%   |
| Roland                                       | 1        | 0.26%   |
| Reloop                                       | 1        | 0.26%   |
| Razer USA                                    | 1        | 0.26%   |
| PreSonus Audio Electronics                   | 1        | 0.26%   |
| Micro Star International                     | 1        | 0.26%   |
| MAG Technology                               | 1        | 0.26%   |
| M-Audio                                      | 1        | 0.26%   |
| Lenovo                                       | 1        | 0.26%   |
| Kingston Technology                          | 1        | 0.26%   |
| JMTek                                        | 1        | 0.26%   |
| Hewlett-Packard                              | 1        | 0.26%   |
| GN Netcom                                    | 1        | 0.26%   |
| Focusrite-Novation                           | 1        | 0.26%   |
| FiiO Electronics Technology                  | 1        | 0.26%   |
| Creative Technology                          | 1        | 0.26%   |
| Corsair                                      | 1        | 0.26%   |
| BR23                                         | 1        | 0.26%   |
| BEHRINGER International                      | 1        | 0.26%   |
| ASUSTek Computer                             | 1        | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 25       | 5.68%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 20       | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18       | 4.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18       | 4.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17       | 3.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 15       | 3.41%   |
| AMD FCH Azalia Controller                                                                         | 14       | 3.18%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14       | 3.18%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13       | 2.95%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 10       | 2.27%   |
| Intel 200 Series PCH HD Audio                                                                     | 10       | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9        | 2.05%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 9        | 2.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 9        | 2.05%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8        | 1.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7        | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7        | 1.59%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7        | 1.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6        | 1.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6        | 1.36%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6        | 1.36%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 6        | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5        | 1.14%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5        | 1.14%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5        | 1.14%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5        | 1.14%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 5        | 1.14%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 5        | 1.14%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5        | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5        | 1.14%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5        | 1.14%   |
| Nvidia MCP61 High Definition Audio                                                                | 4        | 0.91%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 4        | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4        | 0.91%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 4        | 0.91%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3        | 0.68%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 3        | 0.68%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3        | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 36       | 17.82%  |
| Unknown             | 29       | 14.36%  |
| Samsung Electronics | 24       | 11.88%  |
| SK hynix            | 23       | 11.39%  |
| Corsair             | 22       | 10.89%  |
| Crucial             | 19       | 9.41%   |
| G.Skill             | 12       | 5.94%   |
| Nanya Technology    | 6        | 2.97%   |
| Ramaxel Technology  | 5        | 2.48%   |
| Elpida              | 4        | 1.98%   |
| Unknown             | 4        | 1.98%   |
| Micron Technology   | 3        | 1.49%   |
| A-DATA Technology   | 3        | 1.49%   |
| Unknown (ABCD)      | 2        | 0.99%   |
| V-Color             | 1        | 0.5%    |
| Unknown (AB)        | 1        | 0.5%    |
| Unknown (0x0B15)    | 1        | 0.5%    |
| Transcend           | 1        | 0.5%    |
| Timetec             | 1        | 0.5%    |
| Silicon Power       | 1        | 0.5%    |
| Qumo                | 1        | 0.5%    |
| GLOWAY              | 1        | 0.5%    |
| GIGA-BYTE           | 1        | 0.5%    |
| ASint Technology    | 1        | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                              | 4        | 1.86%   |
| Unknown                                                        | 4        | 1.86%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 3        | 1.4%    |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s             | 3        | 1.4%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 3        | 1.4%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 2        | 0.93%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 2        | 0.93%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 2        | 0.93%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2        | 0.93%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s           | 2        | 0.93%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s           | 2        | 0.93%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 0.93%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 2        | 0.93%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s        | 2        | 0.93%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 2        | 0.93%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 2        | 0.93%   |
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s           | 2        | 0.93%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s          | 2        | 0.93%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 2        | 0.93%   |
| V-Color RAM TN4G8C11-H11 4GB DIMM DDR3 1600MT/s                | 1        | 0.47%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                      | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                           | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                       | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2 400MT/s                       | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                      | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2                               | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM 5354MT/s                           | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.47%   |
| Unknown RAM Module 1GB DIMM DDR2                               | 1        | 0.47%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 1        | 0.47%   |
| Unknown RAM Module 1GB DIMM 667MT/s                            | 1        | 0.47%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s      | 1        | 0.47%   |
| Unknown RAM 2400 C16 Series 8192MB DIMM DDR4 1200MT/s          | 1        | 0.47%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s          | 1        | 0.47%   |
| Unknown (AB) RAM Module 2GB DIMM LPDDR3 1333MT/s               | 1        | 0.47%   |
| Unknown (0x0B15) RAM JAD3200U1816 16GB DIMM DDR4 2667MT/s      | 1        | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 72       | 42.35%  |
| DDR4    | 67       | 39.41%  |
| Unknown | 11       | 6.47%   |
| SDRAM   | 8        | 4.71%   |
| DDR2    | 5        | 2.94%   |
| DDR5    | 4        | 2.35%   |
| LPDDR4  | 2        | 1.18%   |
| LPDDR3  | 1        | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 157      | 94.01%  |
| SODIMM | 10       | 5.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 60       | 33.15%  |
| 4096  | 57       | 31.49%  |
| 16384 | 31       | 17.13%  |
| 2048  | 23       | 12.71%  |
| 32768 | 5        | 2.76%   |
| 1024  | 5        | 2.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 45       | 23.94%  |
| 1333    | 23       | 12.23%  |
| 3200    | 15       | 7.98%   |
| 2400    | 14       | 7.45%   |
| 2667    | 12       | 6.38%   |
| 3600    | 7        | 3.72%   |
| Unknown | 7        | 3.72%   |
| 2133    | 5        | 2.66%   |
| 2666    | 4        | 2.13%   |
| 1867    | 4        | 2.13%   |
| 1866    | 4        | 2.13%   |
| 3466    | 3        | 1.6%    |
| 3000    | 3        | 1.6%    |
| 2000    | 3        | 1.6%    |
| 1800    | 3        | 1.6%    |
| 1066    | 3        | 1.6%    |
| 800     | 3        | 1.6%    |
| 4800    | 2        | 1.06%   |
| 3800    | 2        | 1.06%   |
| 3733    | 2        | 1.06%   |
| 3400    | 2        | 1.06%   |
| 1067    | 2        | 1.06%   |
| 55438   | 1        | 0.53%   |
| 52217   | 1        | 0.53%   |
| 6000    | 1        | 0.53%   |
| 5600    | 1        | 0.53%   |
| 5354    | 1        | 0.53%   |
| 4000    | 1        | 0.53%   |
| 3866    | 1        | 0.53%   |
| 3533    | 1        | 0.53%   |
| 3333    | 1        | 0.53%   |
| 3266    | 1        | 0.53%   |
| 3066    | 1        | 0.53%   |
| 3020    | 1        | 0.53%   |
| 2800    | 1        | 0.53%   |
| 2200    | 1        | 0.53%   |
| 2134    | 1        | 0.53%   |
| 1648    | 1        | 0.53%   |
| 1639    | 1        | 0.53%   |
| 1334    | 1        | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 6        | 42.86%  |
| Brother Industries  | 3        | 21.43%  |
| Samsung Electronics | 2        | 14.29%  |
| Kyocera             | 1        | 7.14%   |
| Canon               | 1        | 7.14%   |
| Belkin Components   | 1        | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung SF-760 Series                  | 1        | 7.14%   |
| Samsung ML-1865                        | 1        | 7.14%   |
| Kyocera FS-1300D                       | 1        | 7.14%   |
| HP LaserJet P1102                      | 1        | 7.14%   |
| HP DeskJet F4100 Printer series        | 1        | 7.14%   |
| HP DeskJet D1360                       | 1        | 7.14%   |
| HP DeskJet 840c                        | 1        | 7.14%   |
| HP DeskJet 810c/812c                   | 1        | 7.14%   |
| HP Deskjet 3070 B611 series            | 1        | 7.14%   |
| Canon TS3500 series                    | 1        | 7.14%   |
| Brother QL-560 Label Printer           | 1        | 7.14%   |
| Brother HL-2030 Laser Printer          | 1        | 7.14%   |
| Brother DCP-7040                       | 1        | 7.14%   |
| Belkin Components IEEE-1284 Controller | 1        | 7.14%   |

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
| Logitech                    | 12       | 31.58%  |
| Microdia                    | 5        | 13.16%  |
| Realtek Semiconductor       | 2        | 5.26%   |
| Microsoft                   | 2        | 5.26%   |
| KYE Systems (Mouse Systems) | 2        | 5.26%   |
| Jieli Technology            | 2        | 5.26%   |
| Xiaomi                      | 1        | 2.63%   |
| Silicon Motion              | 1        | 2.63%   |
| Samsung Electronics         | 1        | 2.63%   |
| Ruision                     | 1        | 2.63%   |
| Quanta                      | 1        | 2.63%   |
| MacroSilicon                | 1        | 2.63%   |
| IMC Networks                | 1        | 2.63%   |
| Guillemot                   | 1        | 2.63%   |
| Generalplus Technology      | 1        | 2.63%   |
| Creative Technology         | 1        | 2.63%   |
| Chicony Electronics         | 1        | 2.63%   |
| Apple                       | 1        | 2.63%   |
| AME Optimedia Technology    | 1        | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Microdia Webcam Vitade AF                      | 2        | 5.26%   |
| Logitech HD Webcam C525                        | 2        | 5.26%   |
| Logitech HD Pro Webcam C920                    | 2        | 5.26%   |
| Logitech C922 Pro Stream Webcam                | 2        | 5.26%   |
| Logitech BRIO Ultra HD Webcam                  | 2        | 5.26%   |
| Xiaomi Mi/Redmi series (PTP)                   | 1        | 2.63%   |
| Silicon Motion 300k Pixel Camera               | 1        | 2.63%   |
| Samsung Galaxy series, misc. (MTP mode)        | 1        | 2.63%   |
| Ruision UVC Camera                             | 1        | 2.63%   |
| Realtek Full HD webcam                         | 1        | 2.63%   |
| Realtek FULL HD 1080P Webcam                   | 1        | 2.63%   |
| Quanta HP HD Camera                            | 1        | 2.63%   |
| Microsoft MicrosoftÂ LifeCam Studio           | 1        | 2.63%   |
| Microsoft LifeCam VX-2000                      | 1        | 2.63%   |
| Microdia USB 2.0 Camera                        | 1        | 2.63%   |
| Microdia Sonix USB 2.0 Camera                  | 1        | 2.63%   |
| Microdia Camera                                | 1        | 2.63%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]  | 1        | 2.63%   |
| Logitech Webcam C300                           | 1        | 2.63%   |
| Logitech Webcam C270                           | 1        | 2.63%   |
| Logitech Webcam C110                           | 1        | 2.63%   |
| Logitech Webcam B500                           | 1        | 2.63%   |
| KYE Systems (Mouse Systems) iSlim 2020AF       | 1        | 2.63%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 1        | 2.63%   |
| Jieli USB PHY 2.0                              | 1        | 2.63%   |
| Jieli USB Composite Device                     | 1        | 2.63%   |
| IMC Networks USB2.0 UVC HD Webcam              | 1        | 2.63%   |
| Guillemot Hercules Dualpix Exchange            | 1        | 2.63%   |
| Generalplus GENERAL WEBCAM                     | 1        | 2.63%   |
| Creative Live! Cam Sync 1080p                  | 1        | 2.63%   |
| Chicony HP High Definition 1MP Webcam          | 1        | 2.63%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR             | 1        | 2.63%   |
| AME Optimedia P35U Camera Capture              | 1        | 2.63%   |

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
| 0     | 205      | 84.02%  |
| 1     | 33       | 13.52%  |
| 2     | 5        | 2.05%   |
| 3     | 1        | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 19       | 44.19%  |
| Unassigned class         | 4        | 9.3%    |
| Net/wireless             | 4        | 9.3%    |
| Net/ethernet             | 3        | 6.98%   |
| Sound                    | 2        | 4.65%   |
| Network                  | 2        | 4.65%   |
| Multimedia controller    | 2        | 4.65%   |
| Chipcard                 | 2        | 4.65%   |
| Camera                   | 2        | 4.65%   |
| Dvb card                 | 1        | 2.33%   |
| Communication controller | 1        | 2.33%   |
| Bluetooth                | 1        | 2.33%   |

