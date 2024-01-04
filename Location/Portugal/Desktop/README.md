Linux in Portugal - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Portugal.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 774

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME X470-PRO              | [68d3d8c6be](https://linux-hardware.org/?probe=68d3d8c6be) | Jan 02, 2024 |
| ASRock        | B650M PG Riptide            | [9a27ea61df](https://linux-hardware.org/?probe=9a27ea61df) | Dec 27, 2023 |
| Lenovo        | MAHOBAY NOK                 | [51cee07e16](https://linux-hardware.org/?probe=51cee07e16) | Dec 22, 2023 |
| ASUSTek       | H110M-K                     | [1049cbc16b](https://linux-hardware.org/?probe=1049cbc16b) | Dec 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [05f4c47ed0](https://linux-hardware.org/?probe=05f4c47ed0) | Dec 16, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [dd6121c135](https://linux-hardware.org/?probe=dd6121c135) | Dec 15, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [9268266cec](https://linux-hardware.org/?probe=9268266cec) | Dec 15, 2023 |
| Intel         | H310 Series                 | [9565b22822](https://linux-hardware.org/?probe=9565b22822) | Dec 13, 2023 |
| MSI           | B450M PRO-VDH MAX           | [d275512269](https://linux-hardware.org/?probe=d275512269) | Dec 11, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [e521354b60](https://linux-hardware.org/?probe=e521354b60) | Dec 11, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [76a6e4545f](https://linux-hardware.org/?probe=76a6e4545f) | Dec 11, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [7ca4962c57](https://linux-hardware.org/?probe=7ca4962c57) | Dec 08, 2023 |
| Dell          | 0YXT71 A03                  | [a3080a2577](https://linux-hardware.org/?probe=a3080a2577) | Dec 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | [7ccb597e5c](https://linux-hardware.org/?probe=7ccb597e5c) | Dec 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | [be2d11a5b9](https://linux-hardware.org/?probe=be2d11a5b9) | Dec 04, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [a635fe86e0](https://linux-hardware.org/?probe=a635fe86e0) | Dec 04, 2023 |
| ASUSTek       | M4A78LT-M                   | [9edd2d878e](https://linux-hardware.org/?probe=9edd2d878e) | Dec 04, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [931c17aeb7](https://linux-hardware.org/?probe=931c17aeb7) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [305a40c9b7](https://linux-hardware.org/?probe=305a40c9b7) | Dec 02, 2023 |
| Dell          | 0P301D A00                  | [0d448c331c](https://linux-hardware.org/?probe=0d448c331c) | Nov 30, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [fc8b74d0f9](https://linux-hardware.org/?probe=fc8b74d0f9) | Nov 29, 2023 |
| Dell          | 0P301D A00                  | [719e31cd97](https://linux-hardware.org/?probe=719e31cd97) | Nov 27, 2023 |
| ASUSTek       | P7P55D PRO                  | [69ca3b417c](https://linux-hardware.org/?probe=69ca3b417c) | Nov 26, 2023 |
| Gigabyte      | Z270X-Gaming SOC-CF         | [4631cd6f1c](https://linux-hardware.org/?probe=4631cd6f1c) | Nov 26, 2023 |
| MSI           | B450M MORTAR MAX            | [7667f4a2a0](https://linux-hardware.org/?probe=7667f4a2a0) | Nov 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [4cfc87a4cd](https://linux-hardware.org/?probe=4cfc87a4cd) | Nov 24, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d1eeb55299](https://linux-hardware.org/?probe=d1eeb55299) | Nov 22, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [8049743efd](https://linux-hardware.org/?probe=8049743efd) | Nov 19, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [5dfd0d8f38](https://linux-hardware.org/?probe=5dfd0d8f38) | Nov 18, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0820ebd908](https://linux-hardware.org/?probe=0820ebd908) | Nov 16, 2023 |
| ASUSTek       | P8B75-M LE                  | [d4baa90ad5](https://linux-hardware.org/?probe=d4baa90ad5) | Nov 14, 2023 |
| ASUSTek       | P8B75-M LE                  | [5dd5ed8025](https://linux-hardware.org/?probe=5dd5ed8025) | Nov 13, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [79accb8ead](https://linux-hardware.org/?probe=79accb8ead) | Nov 12, 2023 |
| Gigabyte      | G41MT-S2                    | [c301ae970c](https://linux-hardware.org/?probe=c301ae970c) | Nov 08, 2023 |
| HP            | 2B36                        | [be86be4b09](https://linux-hardware.org/?probe=be86be4b09) | Nov 07, 2023 |
| ASRock        | H81M-VG4 R2.0               | [2de5f4ef98](https://linux-hardware.org/?probe=2de5f4ef98) | Nov 05, 2023 |
| MACHINIST     | H81M-PRO S1 V2.0            | [98b382243b](https://linux-hardware.org/?probe=98b382243b) | Nov 03, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [70365949d8](https://linux-hardware.org/?probe=70365949d8) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [7d5fd28d41](https://linux-hardware.org/?probe=7d5fd28d41) | Nov 01, 2023 |
| ABIT          | F-I90HD                     | [2d6d01983c](https://linux-hardware.org/?probe=2d6d01983c) | Nov 01, 2023 |
| Unknown       | Unknown                     | [d58a78a617](https://linux-hardware.org/?probe=d58a78a617) | Oct 31, 2023 |
| MACHINIST     | H81M-PRO S1 V2.0            | [b9ec438e43](https://linux-hardware.org/?probe=b9ec438e43) | Oct 27, 2023 |
| MSI           | Z490-A PRO                  | [011bfdd699](https://linux-hardware.org/?probe=011bfdd699) | Oct 24, 2023 |
| Acer          | Aspire X1900                | [6454f71562](https://linux-hardware.org/?probe=6454f71562) | Oct 23, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [1e4819e6d1](https://linux-hardware.org/?probe=1e4819e6d1) | Oct 23, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [e7cd525d35](https://linux-hardware.org/?probe=e7cd525d35) | Oct 21, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [722b608b43](https://linux-hardware.org/?probe=722b608b43) | Oct 18, 2023 |
| MSI           | B450M PRO-M2                | [d6e1f3c3b8](https://linux-hardware.org/?probe=d6e1f3c3b8) | Oct 15, 2023 |
| MSI           | B450M PRO-M2                | [c99b37a865](https://linux-hardware.org/?probe=c99b37a865) | Oct 15, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | [086ecfefb8](https://linux-hardware.org/?probe=086ecfefb8) | Oct 15, 2023 |
| ASUSTek       | B75M-PLUS                   | [c1baca90e6](https://linux-hardware.org/?probe=c1baca90e6) | Oct 13, 2023 |
| Dell          | 0200DY A01                  | [4e207b6ab6](https://linux-hardware.org/?probe=4e207b6ab6) | Oct 12, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [81409b14c4](https://linux-hardware.org/?probe=81409b14c4) | Oct 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [0198bbbc8c](https://linux-hardware.org/?probe=0198bbbc8c) | Oct 10, 2023 |
| Lenovo        | 3141 SDK0K17763 WIN 1801... | [da32e6e356](https://linux-hardware.org/?probe=da32e6e356) | Oct 07, 2023 |
| Acer          | Aspire X1900                | [38b7e52e6b](https://linux-hardware.org/?probe=38b7e52e6b) | Oct 06, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [ef154408cf](https://linux-hardware.org/?probe=ef154408cf) | Oct 04, 2023 |
| Acer          | Aspire X1900                | [5d958ae7d1](https://linux-hardware.org/?probe=5d958ae7d1) | Oct 02, 2023 |
| ASRock        | A520M-HVS                   | [0a29d5f7f6](https://linux-hardware.org/?probe=0a29d5f7f6) | Sep 22, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [c933105cd8](https://linux-hardware.org/?probe=c933105cd8) | Sep 21, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [6088e9b2fa](https://linux-hardware.org/?probe=6088e9b2fa) | Sep 19, 2023 |
| ASRock        | A520M-HVS                   | [2a7bf627ba](https://linux-hardware.org/?probe=2a7bf627ba) | Sep 19, 2023 |
| ASRock        | B650M PG Riptide            | [8dd27c1671](https://linux-hardware.org/?probe=8dd27c1671) | Sep 18, 2023 |
| ASRock        | B650M PG Riptide            | [06b00c7739](https://linux-hardware.org/?probe=06b00c7739) | Sep 18, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [8566235f94](https://linux-hardware.org/?probe=8566235f94) | Sep 17, 2023 |
| Gigabyte      | A520M H                     | [24efefc447](https://linux-hardware.org/?probe=24efefc447) | Sep 17, 2023 |
| ASUSTek       | EB1501P                     | [70cb61d1dc](https://linux-hardware.org/?probe=70cb61d1dc) | Sep 17, 2023 |
| HP            | 339A                        | [a9eaaaeeb0](https://linux-hardware.org/?probe=a9eaaaeeb0) | Sep 12, 2023 |
| HP            | 339A                        | [18bb44efa6](https://linux-hardware.org/?probe=18bb44efa6) | Sep 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [5e9fc2a82f](https://linux-hardware.org/?probe=5e9fc2a82f) | Sep 09, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | [602bfb550f](https://linux-hardware.org/?probe=602bfb550f) | Sep 06, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | [1535be8e5f](https://linux-hardware.org/?probe=1535be8e5f) | Sep 06, 2023 |
| Gigabyte      | H110M-Gaming3-CF            | [8985e6b1d9](https://linux-hardware.org/?probe=8985e6b1d9) | Sep 05, 2023 |
| MSI           | H61M-P20                    | [cdf64232fc](https://linux-hardware.org/?probe=cdf64232fc) | Sep 04, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [2292824064](https://linux-hardware.org/?probe=2292824064) | Sep 04, 2023 |
| ASUSTek       | P5G41T-M LX                 | [bdae370995](https://linux-hardware.org/?probe=bdae370995) | Aug 30, 2023 |
| ASUSTek       | P8Q77-M                     | [d9760de265](https://linux-hardware.org/?probe=d9760de265) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [0bf7d37cc9](https://linux-hardware.org/?probe=0bf7d37cc9) | Aug 30, 2023 |
| MSI           | B550-A PRO                  | [a4bd03aafc](https://linux-hardware.org/?probe=a4bd03aafc) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | [19f07f081f](https://linux-hardware.org/?probe=19f07f081f) | Aug 27, 2023 |
| ASUSTek       | H81M-PLUS                   | [af419fe003](https://linux-hardware.org/?probe=af419fe003) | Aug 12, 2023 |
| ASUSTek       | H81M-PLUS                   | [16cd37e4fe](https://linux-hardware.org/?probe=16cd37e4fe) | Aug 12, 2023 |
| Unknown       | Unknown                     | [45fe14954d](https://linux-hardware.org/?probe=45fe14954d) | Aug 07, 2023 |
| Unknown       | Unknown                     | [d1bca9ae8b](https://linux-hardware.org/?probe=d1bca9ae8b) | Aug 07, 2023 |
| MSI           | B450M MORTAR MAX            | [456ac6507d](https://linux-hardware.org/?probe=456ac6507d) | Aug 05, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [d58cf2a585](https://linux-hardware.org/?probe=d58cf2a585) | Jul 31, 2023 |
| HP            | 3397                        | [e61ccd6dbf](https://linux-hardware.org/?probe=e61ccd6dbf) | Jul 27, 2023 |
| Intel         | Unknown                     | [74d458db75](https://linux-hardware.org/?probe=74d458db75) | Jul 23, 2023 |
| BESSTAR Te... | JB9                         | [ea014bad4f](https://linux-hardware.org/?probe=ea014bad4f) | Jul 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | [e44fde4d59](https://linux-hardware.org/?probe=e44fde4d59) | Jul 14, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | [4122f6e73c](https://linux-hardware.org/?probe=4122f6e73c) | Jul 06, 2023 |
| ASUSTek       | H81M-R                      | [83cd667719](https://linux-hardware.org/?probe=83cd667719) | Jun 30, 2023 |
| Dell          | 07N90W A01                  | [67a12e071e](https://linux-hardware.org/?probe=67a12e071e) | Jun 25, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [39ff230ffe](https://linux-hardware.org/?probe=39ff230ffe) | Jun 24, 2023 |
| Lenovo        | 1057 SDK0T76530 WIN 3556... | [0502b8f756](https://linux-hardware.org/?probe=0502b8f756) | Jun 20, 2023 |
| Shenzhen M... | F7BFC                       | [6840ce5f21](https://linux-hardware.org/?probe=6840ce5f21) | Jun 20, 2023 |
| HP            | 84FD                        | [968b4e287f](https://linux-hardware.org/?probe=968b4e287f) | Jun 17, 2023 |
| HP            | 84FD                        | [1711c65b62](https://linux-hardware.org/?probe=1711c65b62) | Jun 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [bcb3a62b53](https://linux-hardware.org/?probe=bcb3a62b53) | Jun 17, 2023 |
| Vorke         | V1 Plus                     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| HP            | 18E4                        | [a0d8b92e3a](https://linux-hardware.org/?probe=a0d8b92e3a) | Jun 12, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [2ac8db1b4c](https://linux-hardware.org/?probe=2ac8db1b4c) | Jun 10, 2023 |
| ASUSTek       | H81M-R                      | [10d01671ad](https://linux-hardware.org/?probe=10d01671ad) | Jun 08, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [6cd3cfcacf](https://linux-hardware.org/?probe=6cd3cfcacf) | Jun 06, 2023 |
| Gigabyte      | X570 AORUS PRO              | [efa9cac1df](https://linux-hardware.org/?probe=efa9cac1df) | Jun 04, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [fa41f1f3c2](https://linux-hardware.org/?probe=fa41f1f3c2) | Jun 04, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [3f032ab035](https://linux-hardware.org/?probe=3f032ab035) | Jun 02, 2023 |
| ASUSTek       | H81M-R                      | [1a69603cc6](https://linux-hardware.org/?probe=1a69603cc6) | May 28, 2023 |
| ASUSTek       | H81M-R                      | [8edf21a203](https://linux-hardware.org/?probe=8edf21a203) | May 27, 2023 |
| ASUSTek       | M4A78LT-M                   | [7080c87654](https://linux-hardware.org/?probe=7080c87654) | May 25, 2023 |
| Vorke         | V1 Plus                     | [81c0b82d6c](https://linux-hardware.org/?probe=81c0b82d6c) | May 24, 2023 |
| ASUSTek       | P5Q-PRO                     | [87b976a24c](https://linux-hardware.org/?probe=87b976a24c) | May 22, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [63a27f785d](https://linux-hardware.org/?probe=63a27f785d) | May 22, 2023 |
| Dell          | 02N3WF A01                  | [8d0096c040](https://linux-hardware.org/?probe=8d0096c040) | May 21, 2023 |
| ASUSTek       | PRIME H410M-R               | [ee37475637](https://linux-hardware.org/?probe=ee37475637) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [68406e2c40](https://linux-hardware.org/?probe=68406e2c40) | May 18, 2023 |
| Vorke         | V1 Plus                     | [19f095fc02](https://linux-hardware.org/?probe=19f095fc02) | May 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fda523de2a](https://linux-hardware.org/?probe=fda523de2a) | May 11, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [d9f5e85b9b](https://linux-hardware.org/?probe=d9f5e85b9b) | May 10, 2023 |
| HP            | 225E                        | [06c72d2ecd](https://linux-hardware.org/?probe=06c72d2ecd) | May 10, 2023 |
| ASUSTek       | P8H67                       | [eeb083abcd](https://linux-hardware.org/?probe=eeb083abcd) | May 07, 2023 |
| MSI           | MAG B550M BAZOOKA           | [7b0b45831c](https://linux-hardware.org/?probe=7b0b45831c) | May 06, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [107752eba8](https://linux-hardware.org/?probe=107752eba8) | May 05, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [d7109f5e05](https://linux-hardware.org/?probe=d7109f5e05) | May 05, 2023 |
| ASUSTek       | A88X-PLUS                   | [7f1747c3e3](https://linux-hardware.org/?probe=7f1747c3e3) | May 04, 2023 |
| ASUSTek       | A88X-PLUS                   | [a937b9eaeb](https://linux-hardware.org/?probe=a937b9eaeb) | May 04, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [ae1618c708](https://linux-hardware.org/?probe=ae1618c708) | May 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1e26913701](https://linux-hardware.org/?probe=1e26913701) | May 03, 2023 |
| MSI           | B365M PRO-VDH               | [82d7303d5c](https://linux-hardware.org/?probe=82d7303d5c) | May 01, 2023 |
| Gigabyte      | 970A-DS3P                   | [c1fe7a5f87](https://linux-hardware.org/?probe=c1fe7a5f87) | Apr 30, 2023 |
| Acer          | E661GXM                     | [d5433b46bd](https://linux-hardware.org/?probe=d5433b46bd) | Apr 30, 2023 |
| Intel         | X99H                        | [d0f8c22128](https://linux-hardware.org/?probe=d0f8c22128) | Apr 26, 2023 |
| ASUSTek       | M4A78LT-M                   | [11f1e291a7](https://linux-hardware.org/?probe=11f1e291a7) | Apr 25, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [67f15c6f4a](https://linux-hardware.org/?probe=67f15c6f4a) | Apr 22, 2023 |
| AAEON         | UPS-EHL01 V1.0              | [14471b218c](https://linux-hardware.org/?probe=14471b218c) | Apr 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4174faae23](https://linux-hardware.org/?probe=4174faae23) | Apr 17, 2023 |
| MSI           | Z370 PC PRO                 | [fb3078d5c3](https://linux-hardware.org/?probe=fb3078d5c3) | Apr 12, 2023 |
| ASUSTek       | P7H55-M PRO                 | [69ee985017](https://linux-hardware.org/?probe=69ee985017) | Apr 09, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [c2132caa73](https://linux-hardware.org/?probe=c2132caa73) | Apr 08, 2023 |
| HP            | ProLiant MicroServer Gen... | [0258b5925f](https://linux-hardware.org/?probe=0258b5925f) | Apr 07, 2023 |
| Acer          | Aspire XC-330               | [a0e2b31c08](https://linux-hardware.org/?probe=a0e2b31c08) | Apr 05, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | [3c08cf9aba](https://linux-hardware.org/?probe=3c08cf9aba) | Apr 01, 2023 |
| ASUSTek       | P7P55D-E                    | [3db646f782](https://linux-hardware.org/?probe=3db646f782) | Mar 29, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [3b7fe31c07](https://linux-hardware.org/?probe=3b7fe31c07) | Mar 29, 2023 |
| Gigabyte      | B365M DS3H                  | [e6b01be2f1](https://linux-hardware.org/?probe=e6b01be2f1) | Mar 29, 2023 |
| ASUSTek       | B85M-G                      | [e973d0294d](https://linux-hardware.org/?probe=e973d0294d) | Mar 22, 2023 |
| ASUSTek       | M5A78L LE                   | [e18778e282](https://linux-hardware.org/?probe=e18778e282) | Mar 20, 2023 |
| Dell          | 0MY171 A00                  | [47fd974afd](https://linux-hardware.org/?probe=47fd974afd) | Mar 20, 2023 |
| HP            | 3646h                       | [812e12695b](https://linux-hardware.org/?probe=812e12695b) | Mar 19, 2023 |
| Gigabyte      | A520M H                     | [a3cee7c278](https://linux-hardware.org/?probe=a3cee7c278) | Mar 19, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7c770db7fd](https://linux-hardware.org/?probe=7c770db7fd) | Mar 18, 2023 |
| Unknown       | Unknown                     | [2389fcea33](https://linux-hardware.org/?probe=2389fcea33) | Mar 17, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [9765f2823e](https://linux-hardware.org/?probe=9765f2823e) | Mar 16, 2023 |
| HP            | 3033h                       | [ab5e388ea9](https://linux-hardware.org/?probe=ab5e388ea9) | Mar 14, 2023 |
| HP            | 3033h                       | [38ac77726b](https://linux-hardware.org/?probe=38ac77726b) | Mar 13, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [7a20b4f81a](https://linux-hardware.org/?probe=7a20b4f81a) | Mar 12, 2023 |
| ASRock        | 970M Pro3                   | [2728efea53](https://linux-hardware.org/?probe=2728efea53) | Mar 05, 2023 |
| ASRock        | 970M Pro3                   | [7235211822](https://linux-hardware.org/?probe=7235211822) | Mar 05, 2023 |
| ASUSTek       | PRIME H410M-R               | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| ASUSTek       | Z87-PRO                     | [7997191f44](https://linux-hardware.org/?probe=7997191f44) | Feb 28, 2023 |
| ASUSTek       | Z87-PRO                     | [9a6bc5f3af](https://linux-hardware.org/?probe=9a6bc5f3af) | Feb 28, 2023 |
| ASUSTek       | B85M-E                      | [8fb68b4ad6](https://linux-hardware.org/?probe=8fb68b4ad6) | Feb 26, 2023 |
| Dell          | 0MY171 A00                  | [795f707b1a](https://linux-hardware.org/?probe=795f707b1a) | Feb 25, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| ASRock        | 970M Pro3                   | [fe75bac6ce](https://linux-hardware.org/?probe=fe75bac6ce) | Feb 19, 2023 |
| ASRock        | 970M Pro3                   | [605089c66c](https://linux-hardware.org/?probe=605089c66c) | Feb 19, 2023 |
| ASUSTek       | P5G41T-M LE                 | [3ebf4858b8](https://linux-hardware.org/?probe=3ebf4858b8) | Feb 16, 2023 |
| MSI           | Z68MA-ED55                  | [e2bd6f0fb4](https://linux-hardware.org/?probe=e2bd6f0fb4) | Feb 15, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [4344acac5e](https://linux-hardware.org/?probe=4344acac5e) | Feb 11, 2023 |
| IBM           | 819046G                     | [a43370bbbd](https://linux-hardware.org/?probe=a43370bbbd) | Feb 11, 2023 |
| MSI           | A78M-E35                    | [ba4515e5ea](https://linux-hardware.org/?probe=ba4515e5ea) | Feb 08, 2023 |
| ASUSTek       | H110M-K                     | [9299261af6](https://linux-hardware.org/?probe=9299261af6) | Feb 05, 2023 |
| ASUSTek       | Z170-DELUXE                 | [d0cf3a9d76](https://linux-hardware.org/?probe=d0cf3a9d76) | Feb 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [a8f54f681a](https://linux-hardware.org/?probe=a8f54f681a) | Feb 01, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| Acer          | RS740DVF                    | [6aaeb06f9a](https://linux-hardware.org/?probe=6aaeb06f9a) | Jan 26, 2023 |
| Pegatron      | Narra6                      | [ac9462ee8e](https://linux-hardware.org/?probe=ac9462ee8e) | Jan 20, 2023 |
| HP            | ProLiant MicroServer Gen... | [cd6cedc906](https://linux-hardware.org/?probe=cd6cedc906) | Jan 17, 2023 |
| ASUSTek       | Benicia                     | [c0441ff1e5](https://linux-hardware.org/?probe=c0441ff1e5) | Jan 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [60a0157a51](https://linux-hardware.org/?probe=60a0157a51) | Jan 16, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7c62282370](https://linux-hardware.org/?probe=7c62282370) | Jan 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [71c61d98b9](https://linux-hardware.org/?probe=71c61d98b9) | Jan 10, 2023 |
| MSI           | B350 KRAIT GAMING           | [d27b435baf](https://linux-hardware.org/?probe=d27b435baf) | Jan 10, 2023 |
| ASRock        | A320M-HDV R3.0              | [cb970f09e6](https://linux-hardware.org/?probe=cb970f09e6) | Jan 09, 2023 |
| HP            | 0AA4h                       | [8d177b0b8d](https://linux-hardware.org/?probe=8d177b0b8d) | Jan 09, 2023 |
| MSI           | H97 GAMING 3                | [39ec0d3441](https://linux-hardware.org/?probe=39ec0d3441) | Jan 09, 2023 |
| ASUSTek       | P8Z77-V LX                  | [bdc427771d](https://linux-hardware.org/?probe=bdc427771d) | Jan 08, 2023 |
| HP            | 83EE                        | [cb43945233](https://linux-hardware.org/?probe=cb43945233) | Jan 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [aff5a2ce85](https://linux-hardware.org/?probe=aff5a2ce85) | Jan 07, 2023 |
| Gigabyte      | H81M-S1                     | [db0e909d27](https://linux-hardware.org/?probe=db0e909d27) | Jan 06, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [eefb2d0334](https://linux-hardware.org/?probe=eefb2d0334) | Jan 03, 2023 |
| Gigabyte      | Z77P-D3                     | [76d75de6ac](https://linux-hardware.org/?probe=76d75de6ac) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bbd09c7b2c](https://linux-hardware.org/?probe=bbd09c7b2c) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [013b1e7816](https://linux-hardware.org/?probe=013b1e7816) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [34528f04fe](https://linux-hardware.org/?probe=34528f04fe) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [7295ec02b5](https://linux-hardware.org/?probe=7295ec02b5) | Dec 31, 2022 |
| ASUSTek       | PRIME B550M-A               | [2161cbc9a0](https://linux-hardware.org/?probe=2161cbc9a0) | Dec 31, 2022 |
| ASUSTek       | Benicia                     | [9d307c5f2f](https://linux-hardware.org/?probe=9d307c5f2f) | Dec 31, 2022 |
| ASUSTek       | Benicia                     | [bc835cbca9](https://linux-hardware.org/?probe=bc835cbca9) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [76e9829e66](https://linux-hardware.org/?probe=76e9829e66) | Dec 30, 2022 |
| ASUSTek       | B85M-GAMER                  | [ded2e7e4e6](https://linux-hardware.org/?probe=ded2e7e4e6) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [b181e9e5a3](https://linux-hardware.org/?probe=b181e9e5a3) | Dec 26, 2022 |
| MSI           | B350 KRAIT GAMING           | [896aebf101](https://linux-hardware.org/?probe=896aebf101) | Dec 25, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [82f8802857](https://linux-hardware.org/?probe=82f8802857) | Dec 24, 2022 |
| HP            | 0980h                       | [d54665c87c](https://linux-hardware.org/?probe=d54665c87c) | Dec 21, 2022 |
| MSI           | H81M-P33                    | [5d91d96949](https://linux-hardware.org/?probe=5d91d96949) | Dec 20, 2022 |
| HP            | 0980h                       | [3faf0c7996](https://linux-hardware.org/?probe=3faf0c7996) | Dec 20, 2022 |
| Foxconn       | 2ABF                        | [10e579b77e](https://linux-hardware.org/?probe=10e579b77e) | Dec 18, 2022 |
| Dell          | 03V7GF A01                  | [3847c61b81](https://linux-hardware.org/?probe=3847c61b81) | Dec 17, 2022 |
| Dell          | 03V7GF A01                  | [e491b54a3c](https://linux-hardware.org/?probe=e491b54a3c) | Dec 17, 2022 |
| Unknown       | Unknown                     | [988a2e80c0](https://linux-hardware.org/?probe=988a2e80c0) | Dec 17, 2022 |
| Gigabyte      | H57M-USB3                   | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Dell          | 0MY171 A00                  | [055bc4ea78](https://linux-hardware.org/?probe=055bc4ea78) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| ASRock        | G31M-GS                     | [2e1fc34b39](https://linux-hardware.org/?probe=2e1fc34b39) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [d83227cce9](https://linux-hardware.org/?probe=d83227cce9) | Dec 10, 2022 |
| ASUSTek       | P5Q DELUXE                  | [1519fb3a87](https://linux-hardware.org/?probe=1519fb3a87) | Dec 06, 2022 |
| MSI           | Z490-A PRO                  | [34157244aa](https://linux-hardware.org/?probe=34157244aa) | Dec 05, 2022 |
| Packard Be... | FIH57                       | [a98f4adbab](https://linux-hardware.org/?probe=a98f4adbab) | Dec 05, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | [5ab13c42b3](https://linux-hardware.org/?probe=5ab13c42b3) | Dec 03, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | [b3ab0684c5](https://linux-hardware.org/?probe=b3ab0684c5) | Dec 03, 2022 |
| ASUSTek       | PRIME B360M-A               | [e28a13071a](https://linux-hardware.org/?probe=e28a13071a) | Dec 02, 2022 |
| ASUSTek       | PRIME B360M-A               | [44a7c01e06](https://linux-hardware.org/?probe=44a7c01e06) | Dec 02, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [a6a71120f2](https://linux-hardware.org/?probe=a6a71120f2) | Nov 30, 2022 |
| ASUSTek       | Benicia                     | [e5468e4258](https://linux-hardware.org/?probe=e5468e4258) | Nov 30, 2022 |
| HP            | 18E7                        | [5a5c2667a5](https://linux-hardware.org/?probe=5a5c2667a5) | Nov 26, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [ccf106edce](https://linux-hardware.org/?probe=ccf106edce) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [99fc338b3e](https://linux-hardware.org/?probe=99fc338b3e) | Nov 23, 2022 |
| MSI           | 990FXA-GD65                 | [8e134485ce](https://linux-hardware.org/?probe=8e134485ce) | Nov 22, 2022 |
| MSI           | 990FXA-GD65                 | [d41acd5075](https://linux-hardware.org/?probe=d41acd5075) | Nov 20, 2022 |
| ASRock        | B550 Extreme4               | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| ASUSTek       | B85M-E                      | [2455b541f5](https://linux-hardware.org/?probe=2455b541f5) | Nov 16, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [2c896d28a8](https://linux-hardware.org/?probe=2c896d28a8) | Nov 13, 2022 |
| ASUSTek       | B85M-GAMER                  | [112508759b](https://linux-hardware.org/?probe=112508759b) | Nov 13, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [dc1c83bed5](https://linux-hardware.org/?probe=dc1c83bed5) | Nov 11, 2022 |
| ASUSTek       | PRIME B360M-A               | [c46dd8d9b6](https://linux-hardware.org/?probe=c46dd8d9b6) | Nov 01, 2022 |
| Pegatron      | TRUCKEE                     | [2a6fe2bcd1](https://linux-hardware.org/?probe=2a6fe2bcd1) | Oct 28, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [fe9ec739e2](https://linux-hardware.org/?probe=fe9ec739e2) | Oct 24, 2022 |
| HP            | 805D                        | [ece9f05ea6](https://linux-hardware.org/?probe=ece9f05ea6) | Oct 14, 2022 |
| HP            | 805D                        | [f10271c447](https://linux-hardware.org/?probe=f10271c447) | Oct 14, 2022 |
| ASRock        | 970M Pro3                   | [ca8ac557b3](https://linux-hardware.org/?probe=ca8ac557b3) | Oct 14, 2022 |
| ASRock        | 970M Pro3                   | [9eaf0bffca](https://linux-hardware.org/?probe=9eaf0bffca) | Oct 09, 2022 |
| MSI           | B550-A PRO                  | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| ASRock        | 970M Pro3                   | [76d2eeb1d0](https://linux-hardware.org/?probe=76d2eeb1d0) | Oct 07, 2022 |
| ASUSTek       | PRIME H410M-E               | [abe6a3fde2](https://linux-hardware.org/?probe=abe6a3fde2) | Oct 06, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [a055ed4d2c](https://linux-hardware.org/?probe=a055ed4d2c) | Oct 03, 2022 |
| ASUSTek       | PRIME H510M-K               | [5bdf95fbdc](https://linux-hardware.org/?probe=5bdf95fbdc) | Oct 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9fff405744](https://linux-hardware.org/?probe=9fff405744) | Sep 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | [34035b63b6](https://linux-hardware.org/?probe=34035b63b6) | Sep 25, 2022 |
| ASRock        | B550 Pro4                   | [a1009d700e](https://linux-hardware.org/?probe=a1009d700e) | Sep 21, 2022 |
| ASUSTek       | PRIME A320M-K               | [70a7e5cad3](https://linux-hardware.org/?probe=70a7e5cad3) | Sep 20, 2022 |
| MSI           | Z77A-G45                    | [b5a8d40602](https://linux-hardware.org/?probe=b5a8d40602) | Sep 18, 2022 |
| ASUSTek       | P5L-VM 1394                 | [a7931f2026](https://linux-hardware.org/?probe=a7931f2026) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [038f57c2d8](https://linux-hardware.org/?probe=038f57c2d8) | Sep 06, 2022 |
| ASUSTek       | PRIME H510M-K               | [6fa51d2c4e](https://linux-hardware.org/?probe=6fa51d2c4e) | Aug 31, 2022 |
| OEM           | Intel H81                   | [4b45e6dc61](https://linux-hardware.org/?probe=4b45e6dc61) | Aug 31, 2022 |
| ASUSTek       | Benicia                     | [08f930384d](https://linux-hardware.org/?probe=08f930384d) | Aug 25, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [ba3fb2513f](https://linux-hardware.org/?probe=ba3fb2513f) | Aug 21, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [7ee8720a43](https://linux-hardware.org/?probe=7ee8720a43) | Aug 21, 2022 |
| MSI           | Z370 PC PRO                 | [9131aa23c4](https://linux-hardware.org/?probe=9131aa23c4) | Aug 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| MSI           | B85M-E45                    | [cb991c0789](https://linux-hardware.org/?probe=cb991c0789) | Aug 17, 2022 |
| ASUSTek       | Basswood                    | [26e4efad3f](https://linux-hardware.org/?probe=26e4efad3f) | Aug 14, 2022 |
| ASRock        | H410M-HVS                   | [4d1acc8488](https://linux-hardware.org/?probe=4d1acc8488) | Aug 11, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| ASUSTek       | P8Z77-V                     | [18935d4aff](https://linux-hardware.org/?probe=18935d4aff) | Aug 07, 2022 |
| ASUSTek       | P8H67                       | [508b0275e3](https://linux-hardware.org/?probe=508b0275e3) | Aug 02, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | [99a140d79b](https://linux-hardware.org/?probe=99a140d79b) | Aug 01, 2022 |
| ASUSTek       | P5G41C-M LX                 | [4e30dc6361](https://linux-hardware.org/?probe=4e30dc6361) | Jul 31, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [ae71cae955](https://linux-hardware.org/?probe=ae71cae955) | Jul 25, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [b3dbd37276](https://linux-hardware.org/?probe=b3dbd37276) | Jul 22, 2022 |
| MSI           | A78M-E45 V2                 | [c5007c5729](https://linux-hardware.org/?probe=c5007c5729) | Jul 22, 2022 |
| ASUSTek       | P8Z77-V                     | [bb9f40d075](https://linux-hardware.org/?probe=bb9f40d075) | Jul 18, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [e1313016ee](https://linux-hardware.org/?probe=e1313016ee) | Jul 17, 2022 |
| ASUSTek       | EX-A320M-GAMING             | [68884b1723](https://linux-hardware.org/?probe=68884b1723) | Jul 17, 2022 |
| Acer          | FMCP7AM                     | [f2fc2e98c3](https://linux-hardware.org/?probe=f2fc2e98c3) | Jul 10, 2022 |
| Lenovo        | SHARKBAY NOK                | [15088a414c](https://linux-hardware.org/?probe=15088a414c) | Jul 03, 2022 |
| MSI           | B450M BAZOOKA V2            | [bded0a2071](https://linux-hardware.org/?probe=bded0a2071) | Jul 03, 2022 |
| HP            | 8169                        | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| MSI           | A78M-E45 V2                 | [e4cd6586b4](https://linux-hardware.org/?probe=e4cd6586b4) | Jun 26, 2022 |
| Gigabyte      | H310M H                     | [90038bfa8e](https://linux-hardware.org/?probe=90038bfa8e) | Jun 22, 2022 |
| MSI           | A78M-E45 V2                 | [97b9d51036](https://linux-hardware.org/?probe=97b9d51036) | Jun 20, 2022 |
| MSI           | B85M-E45                    | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| MSI           | A78M-E45 V2                 | [86394fa5df](https://linux-hardware.org/?probe=86394fa5df) | Jun 16, 2022 |
| MSI           | A78M-E45 V2                 | [a2d26ab800](https://linux-hardware.org/?probe=a2d26ab800) | Jun 14, 2022 |
| ASUSTek       | AT5IONT-I                   | [70438d549d](https://linux-hardware.org/?probe=70438d549d) | Jun 14, 2022 |
| ASUSTek       | AT5IONT-I                   | [56abd525d8](https://linux-hardware.org/?probe=56abd525d8) | Jun 14, 2022 |
| MSI           | B460M-A PRO                 | [c858bede94](https://linux-hardware.org/?probe=c858bede94) | Jun 05, 2022 |
| Dell          | 05XGC8 A01                  | [2a1316250b](https://linux-hardware.org/?probe=2a1316250b) | Jun 05, 2022 |
| MSI           | MAG B550M BAZOOKA           | [9399a639c8](https://linux-hardware.org/?probe=9399a639c8) | May 29, 2022 |
| MSI           | MAG B550M BAZOOKA           | [42b16ce834](https://linux-hardware.org/?probe=42b16ce834) | May 28, 2022 |
| MSI           | MAG B550M BAZOOKA           | [4620e51e7b](https://linux-hardware.org/?probe=4620e51e7b) | May 28, 2022 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [ccf347729e](https://linux-hardware.org/?probe=ccf347729e) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| ASUSTek       | Maximus IV Extreme          | [08dedbb3cb](https://linux-hardware.org/?probe=08dedbb3cb) | May 18, 2022 |
| Dell          | 0HN7XN A00                  | [6fba9a10da](https://linux-hardware.org/?probe=6fba9a10da) | May 18, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a83bed6668](https://linux-hardware.org/?probe=a83bed6668) | May 16, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [a2ae5d95dd](https://linux-hardware.org/?probe=a2ae5d95dd) | May 15, 2022 |
| ASRockRack    | X399D8A-2T                  | [f1d2fbc435](https://linux-hardware.org/?probe=f1d2fbc435) | May 12, 2022 |
| Gigabyte      | Z77P-D3                     | [40de59e6f7](https://linux-hardware.org/?probe=40de59e6f7) | May 10, 2022 |
| ASUSTek       | PRIME B360M-A               | [c589ad9143](https://linux-hardware.org/?probe=c589ad9143) | May 07, 2022 |
| ASUSTek       | M4A78LT-M                   | [2a10a13430](https://linux-hardware.org/?probe=2a10a13430) | May 06, 2022 |
| ASRock        | Z77 Pro3                    | [050aee0a5f](https://linux-hardware.org/?probe=050aee0a5f) | May 03, 2022 |
| MSI           | MS-7053                     | [6de132b805](https://linux-hardware.org/?probe=6de132b805) | May 02, 2022 |
| ASUSTek       | PRIME B360M-A               | [519ed87066](https://linux-hardware.org/?probe=519ed87066) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | [c46a1d595b](https://linux-hardware.org/?probe=c46a1d595b) | Apr 29, 2022 |
| HP            | 8719                        | [7e0ae3d91f](https://linux-hardware.org/?probe=7e0ae3d91f) | Apr 22, 2022 |
| ASUSTek       | P5G41T-M LX3                | [a21dad9ee4](https://linux-hardware.org/?probe=a21dad9ee4) | Apr 20, 2022 |
| Gigabyte      | B550 GAMING X V2            | [278c76b54f](https://linux-hardware.org/?probe=278c76b54f) | Apr 18, 2022 |
| Gigabyte      | B550 GAMING X V2            | [5f49d4d7d8](https://linux-hardware.org/?probe=5f49d4d7d8) | Apr 14, 2022 |
| ASUSTek       | P5G41T-M LX                 | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| Gigabyte      | B550 GAMING X V2            | [9493efcabe](https://linux-hardware.org/?probe=9493efcabe) | Apr 03, 2022 |
| Gigabyte      | G31M-ES2L                   | [90a8431fc2](https://linux-hardware.org/?probe=90a8431fc2) | Mar 22, 2022 |
| Gigabyte      | A520M H                     | [46b8c80485](https://linux-hardware.org/?probe=46b8c80485) | Mar 17, 2022 |
| ASUSTek       | B85M-E                      | [36c1044633](https://linux-hardware.org/?probe=36c1044633) | Mar 16, 2022 |
| Gigabyte      | A520M H                     | [483e47645c](https://linux-hardware.org/?probe=483e47645c) | Mar 16, 2022 |
| ASUSTek       | PRIME H510M-K               | [8a97b4f2d3](https://linux-hardware.org/?probe=8a97b4f2d3) | Mar 09, 2022 |
| HP            | 0A54h                       | [2dfc948414](https://linux-hardware.org/?probe=2dfc948414) | Mar 08, 2022 |
| Gigabyte      | G31M-S2L                    | [dd40993d97](https://linux-hardware.org/?probe=dd40993d97) | Mar 03, 2022 |
| HP            | 3396                        | [f952a8f044](https://linux-hardware.org/?probe=f952a8f044) | Mar 01, 2022 |
| MSI           | B85M-E45                    | [42fba9424e](https://linux-hardware.org/?probe=42fba9424e) | Feb 27, 2022 |
| Minix         | NEO Z83-4 V1.1              | [8aa7469422](https://linux-hardware.org/?probe=8aa7469422) | Feb 27, 2022 |
| Biostar       | H81MHV3                     | [3fd07aef04](https://linux-hardware.org/?probe=3fd07aef04) | Feb 25, 2022 |
| ASUSTek       | PRIME X570-P                | [eacd6c646c](https://linux-hardware.org/?probe=eacd6c646c) | Feb 22, 2022 |
| IBM           | 819046G                     | [54b0798b76](https://linux-hardware.org/?probe=54b0798b76) | Feb 22, 2022 |
| ASUSTek       | P5VDC-X                     | [40943e3ee0](https://linux-hardware.org/?probe=40943e3ee0) | Feb 22, 2022 |
| HP            | 83F3                        | [9421f4385a](https://linux-hardware.org/?probe=9421f4385a) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | [f7ee45924c](https://linux-hardware.org/?probe=f7ee45924c) | Feb 17, 2022 |
| ASRock        | B550M Pro4                  | [b39fbbaec6](https://linux-hardware.org/?probe=b39fbbaec6) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8f1ce82db7](https://linux-hardware.org/?probe=8f1ce82db7) | Feb 15, 2022 |
| MSI           | MS-7053                     | [2ee97bf0a8](https://linux-hardware.org/?probe=2ee97bf0a8) | Feb 13, 2022 |
| MSI           | H61M-P20                    | [81b315b229](https://linux-hardware.org/?probe=81b315b229) | Feb 09, 2022 |
| MSI           | B85M-E45                    | [3653d29a0a](https://linux-hardware.org/?probe=3653d29a0a) | Feb 07, 2022 |
| Foxconn       | H67M-S/H67M-V/H67           | [a3f3367577](https://linux-hardware.org/?probe=a3f3367577) | Feb 02, 2022 |
| ASUSTek       | P5K3L-ASUS-S1-P5G35         | [f9e7838b90](https://linux-hardware.org/?probe=f9e7838b90) | Jan 31, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [72374dc22c](https://linux-hardware.org/?probe=72374dc22c) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [78cdf0490a](https://linux-hardware.org/?probe=78cdf0490a) | Jan 26, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | [5b23faaf76](https://linux-hardware.org/?probe=5b23faaf76) | Jan 22, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | [3791490565](https://linux-hardware.org/?probe=3791490565) | Jan 22, 2022 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [6cad862612](https://linux-hardware.org/?probe=6cad862612) | Jan 21, 2022 |
| MSI           | MS-7053                     | [8844db2984](https://linux-hardware.org/?probe=8844db2984) | Jan 13, 2022 |
| ASUSTek       | P5K PRO                     | [9338817523](https://linux-hardware.org/?probe=9338817523) | Jan 13, 2022 |
| ASUSTek       | V-P7H55E                    | [7fc2d44a4a](https://linux-hardware.org/?probe=7fc2d44a4a) | Jan 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [409de37ae4](https://linux-hardware.org/?probe=409de37ae4) | Jan 09, 2022 |
| Gigabyte      | P41T-D3P                    | [1c94714d99](https://linux-hardware.org/?probe=1c94714d99) | Jan 01, 2022 |
| Google        | Sion                        | [08215c86b6](https://linux-hardware.org/?probe=08215c86b6) | Dec 31, 2021 |
| ASUSTek       | A_F_K31AN                   | [4bd56c7243](https://linux-hardware.org/?probe=4bd56c7243) | Dec 29, 2021 |
| RKM           | Cherry Trail CR             | [907cacf8cc](https://linux-hardware.org/?probe=907cacf8cc) | Dec 29, 2021 |
| Huanan        | X79-8D VAA31                | [79be6da608](https://linux-hardware.org/?probe=79be6da608) | Dec 26, 2021 |
| HP            | 1998                        | [fffadbe1cf](https://linux-hardware.org/?probe=fffadbe1cf) | Dec 25, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [855061aa1a](https://linux-hardware.org/?probe=855061aa1a) | Dec 18, 2021 |
| MSI           | MS-7053                     | [3e9330e811](https://linux-hardware.org/?probe=3e9330e811) | Dec 18, 2021 |
| MSI           | MS-7053                     | [b32db3cd18](https://linux-hardware.org/?probe=b32db3cd18) | Dec 18, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [830b8475ac](https://linux-hardware.org/?probe=830b8475ac) | Dec 15, 2021 |
| ASUSTek       | PRIME X570-P                | [1812d44a36](https://linux-hardware.org/?probe=1812d44a36) | Dec 12, 2021 |
| Gigabyte      | B550M AORUS PRO             | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| ASUSTek       | P5G41T-M LX                 | [8b03acc524](https://linux-hardware.org/?probe=8b03acc524) | Dec 11, 2021 |
| Pegatron      | Benicia                     | [d50daedc5d](https://linux-hardware.org/?probe=d50daedc5d) | Nov 26, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [22f1f5326e](https://linux-hardware.org/?probe=22f1f5326e) | Nov 21, 2021 |
| Biostar       | FX9830M                     | [f845fe2694](https://linux-hardware.org/?probe=f845fe2694) | Nov 19, 2021 |
| Gigabyte      | G31M-ES2L                   | [f30f49d634](https://linux-hardware.org/?probe=f30f49d634) | Nov 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [fccd73da9d](https://linux-hardware.org/?probe=fccd73da9d) | Nov 12, 2021 |
| Dell          | 0HD5W2 A00                  | [d4c15ae33a](https://linux-hardware.org/?probe=d4c15ae33a) | Nov 08, 2021 |
| Minix         | NEO Z83-4 V1.1              | [c7b52e35cf](https://linux-hardware.org/?probe=c7b52e35cf) | Nov 08, 2021 |
| ASUSTek       | H87M-PLUS                   | [72e74c86fb](https://linux-hardware.org/?probe=72e74c86fb) | Nov 04, 2021 |
| ASUSTek       | H87M-PLUS                   | [bbb4e58192](https://linux-hardware.org/?probe=bbb4e58192) | Nov 04, 2021 |
| ASUSTek       | P5LD2-SE                    | [4f817c0167](https://linux-hardware.org/?probe=4f817c0167) | Nov 03, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [b643635a41](https://linux-hardware.org/?probe=b643635a41) | Nov 02, 2021 |
| ASUSTek       | P5LD2-SE                    | [8ba60d9634](https://linux-hardware.org/?probe=8ba60d9634) | Nov 01, 2021 |
| MSI           | P55-CD53                    | [d342f4e0a4](https://linux-hardware.org/?probe=d342f4e0a4) | Oct 29, 2021 |
| ASUSTek       | A_F_K31AN                   | [ebd51400e3](https://linux-hardware.org/?probe=ebd51400e3) | Oct 25, 2021 |
| ASUSTek       | B85M-E                      | [7a6479dc2d](https://linux-hardware.org/?probe=7a6479dc2d) | Oct 23, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [7313df4bd9](https://linux-hardware.org/?probe=7313df4bd9) | Oct 17, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [005e2591e8](https://linux-hardware.org/?probe=005e2591e8) | Oct 17, 2021 |
| ASUSTek       | PRIME H510M-K               | [2ee0e02dca](https://linux-hardware.org/?probe=2ee0e02dca) | Oct 08, 2021 |
| ASUSTek       | H81M-A                      | [b73e4dc969](https://linux-hardware.org/?probe=b73e4dc969) | Oct 07, 2021 |
| ASUSTek       | PRIME H510M-K               | [cc60b4cc30](https://linux-hardware.org/?probe=cc60b4cc30) | Oct 07, 2021 |
| ASUSTek       | PRIME H510M-K               | [dae39c15c9](https://linux-hardware.org/?probe=dae39c15c9) | Oct 06, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [eeae519a3e](https://linux-hardware.org/?probe=eeae519a3e) | Oct 04, 2021 |
| ASRock        | B450M Pro4                  | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASUSTek       | P5KC                        | [c6c9f72f10](https://linux-hardware.org/?probe=c6c9f72f10) | Sep 29, 2021 |
| ASUSTek       | M4N68T-M                    | [adaee7ea4e](https://linux-hardware.org/?probe=adaee7ea4e) | Sep 28, 2021 |
| ASUSTek       | PRIME H510M-K               | [c11c48b5d6](https://linux-hardware.org/?probe=c11c48b5d6) | Sep 24, 2021 |
| ASUSTek       | PRIME H510M-K               | [66900d1009](https://linux-hardware.org/?probe=66900d1009) | Sep 24, 2021 |
| ASUSTek       | PRIME X570-P                | [d8d6573dea](https://linux-hardware.org/?probe=d8d6573dea) | Sep 23, 2021 |
| Shuttle       | NC03U                       | [c5f76c4400](https://linux-hardware.org/?probe=c5f76c4400) | Sep 22, 2021 |
| Foxconn       | A74ML-K                     | [b7a9a59c77](https://linux-hardware.org/?probe=b7a9a59c77) | Sep 19, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a7a8c2cead](https://linux-hardware.org/?probe=a7a8c2cead) | Sep 18, 2021 |
| Biostar       | A68MHE                      | [8a2cdafa86](https://linux-hardware.org/?probe=8a2cdafa86) | Sep 18, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [82058974d9](https://linux-hardware.org/?probe=82058974d9) | Sep 17, 2021 |
| Libretrend    | LT1000                      | [781fa86fea](https://linux-hardware.org/?probe=781fa86fea) | Sep 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [e8ac4691b0](https://linux-hardware.org/?probe=e8ac4691b0) | Sep 16, 2021 |
| ASRock        | X570M Pro4                  | [297bbaf6a4](https://linux-hardware.org/?probe=297bbaf6a4) | Sep 14, 2021 |
| Acer          | Elena                       | [c05122b62f](https://linux-hardware.org/?probe=c05122b62f) | Sep 14, 2021 |
| ASUSTek       | B85M-E                      | [1ef0a151b1](https://linux-hardware.org/?probe=1ef0a151b1) | Sep 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VI EXTREME    | [4404093ccf](https://linux-hardware.org/?probe=4404093ccf) | Sep 12, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | [b92b2f815b](https://linux-hardware.org/?probe=b92b2f815b) | Sep 07, 2021 |
| ASUSTek       | P5L8L-SE                    | [32e39bbd4f](https://linux-hardware.org/?probe=32e39bbd4f) | Sep 02, 2021 |
| ASUSTek       | P5Q DELUXE                  | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [ca0e00bc0f](https://linux-hardware.org/?probe=ca0e00bc0f) | Sep 01, 2021 |
| ASRock        | N68-VS3 FX                  | [450ffd830c](https://linux-hardware.org/?probe=450ffd830c) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | [73edbfaf52](https://linux-hardware.org/?probe=73edbfaf52) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | [cefaaa7f19](https://linux-hardware.org/?probe=cefaaa7f19) | Sep 01, 2021 |
| ASRock        | 760GM-HDV                   | [7b2322353d](https://linux-hardware.org/?probe=7b2322353d) | Aug 29, 2021 |
| Unknown       | 1.0                         | [5e638360a8](https://linux-hardware.org/?probe=5e638360a8) | Aug 24, 2021 |
| ECS           | Livermore8                  | [a86f5a7745](https://linux-hardware.org/?probe=a86f5a7745) | Aug 18, 2021 |
| Unknown       | Unknown                     | [65ebd0006e](https://linux-hardware.org/?probe=65ebd0006e) | Aug 16, 2021 |
| ASUSTek       | P5P43TD PRO                 | [0576757382](https://linux-hardware.org/?probe=0576757382) | Aug 08, 2021 |
| Biostar       | A68MHE                      | [160e00a244](https://linux-hardware.org/?probe=160e00a244) | Aug 04, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | [a6df82ec75](https://linux-hardware.org/?probe=a6df82ec75) | Jul 30, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | [b33ddef912](https://linux-hardware.org/?probe=b33ddef912) | Jul 30, 2021 |
| HP            | ProLiant ML350 G5           | [189789f8d5](https://linux-hardware.org/?probe=189789f8d5) | Jul 23, 2021 |
| Intel         | DH61WW AAG23116-206         | [bdd8ae093d](https://linux-hardware.org/?probe=bdd8ae093d) | Jul 21, 2021 |
| Dell          | 04MFRM A02                  | [9d92f05e1c](https://linux-hardware.org/?probe=9d92f05e1c) | Jul 17, 2021 |
| Dell          | 04MFRM A02                  | [2b2a31a2f9](https://linux-hardware.org/?probe=2b2a31a2f9) | Jul 17, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [1056457127](https://linux-hardware.org/?probe=1056457127) | Jul 17, 2021 |
| ASUSTek       | Crosshair IV Formula        | [4004b6bcb6](https://linux-hardware.org/?probe=4004b6bcb6) | Jul 16, 2021 |
| ASUSTek       | Crosshair IV Formula        | [1a9dfe2f20](https://linux-hardware.org/?probe=1a9dfe2f20) | Jul 16, 2021 |
| Gigabyte      | H110-D3A-CF                 | [e2a2b5ba07](https://linux-hardware.org/?probe=e2a2b5ba07) | Jul 13, 2021 |
| Gigabyte      | B365M HD3                   | [e663cfd24c](https://linux-hardware.org/?probe=e663cfd24c) | Jul 10, 2021 |
| ASRock        | N68-VS3 FX                  | [3bde956fe7](https://linux-hardware.org/?probe=3bde956fe7) | Jul 08, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [119260db14](https://linux-hardware.org/?probe=119260db14) | Jul 05, 2021 |
| ASUSTek       | P8H67-V                     | [66b161d8d5](https://linux-hardware.org/?probe=66b161d8d5) | Jul 02, 2021 |
| HP            | ProLiant ML350 G5           | [bc362bd630](https://linux-hardware.org/?probe=bc362bd630) | Jun 30, 2021 |
| ASRock        | H370M-ITX/ac                | [a6c720d609](https://linux-hardware.org/?probe=a6c720d609) | Jun 29, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [d2a4ffa502](https://linux-hardware.org/?probe=d2a4ffa502) | Jun 26, 2021 |
| MSI           | Z590-A PRO                  | [d6df0a85b4](https://linux-hardware.org/?probe=d6df0a85b4) | Jun 12, 2021 |
| MSI           | Z590-A PRO                  | [c7295eb580](https://linux-hardware.org/?probe=c7295eb580) | Jun 12, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [d19e5c9398](https://linux-hardware.org/?probe=d19e5c9398) | Jun 11, 2021 |
| MSI           | B250 PC MATE                | [efa385c98c](https://linux-hardware.org/?probe=efa385c98c) | Jun 11, 2021 |
| ASUSTek       | D425MC                      | [aa893a2c50](https://linux-hardware.org/?probe=aa893a2c50) | Jun 10, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [599b4af4cf](https://linux-hardware.org/?probe=599b4af4cf) | Jun 06, 2021 |
| ASUSTek       | D425MC                      | [fc261e7b44](https://linux-hardware.org/?probe=fc261e7b44) | Jun 06, 2021 |
| Gigabyte      | Z77P-D3                     | [6a2bb03dcb](https://linux-hardware.org/?probe=6a2bb03dcb) | Jun 02, 2021 |
| ASUSTek       | D425MC                      | [d78ca41229](https://linux-hardware.org/?probe=d78ca41229) | Jun 01, 2021 |
| Gigabyte      | G41MT-S2                    | [5efbefcaa5](https://linux-hardware.org/?probe=5efbefcaa5) | May 30, 2021 |
| MSI           | Z490-A PRO                  | [654c105561](https://linux-hardware.org/?probe=654c105561) | May 28, 2021 |
| ASUSTek       | H110M-R                     | [62b22bfb20](https://linux-hardware.org/?probe=62b22bfb20) | May 26, 2021 |
| HP            | 3397                        | [ee57980b90](https://linux-hardware.org/?probe=ee57980b90) | May 25, 2021 |
| HP            | 1497                        | [7fa5ad3e42](https://linux-hardware.org/?probe=7fa5ad3e42) | May 25, 2021 |
| ASUSTek       | Z97-A                       | [0767c99abb](https://linux-hardware.org/?probe=0767c99abb) | May 19, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | [0548f9650b](https://linux-hardware.org/?probe=0548f9650b) | May 18, 2021 |
| MSI           | H270M BAZOOKA               | [c2fdd4a7da](https://linux-hardware.org/?probe=c2fdd4a7da) | May 06, 2021 |
| ASUSTek       | P5S-MX SE                   | [2853189089](https://linux-hardware.org/?probe=2853189089) | May 01, 2021 |
| ASUSTek       | P5S-MX SE                   | [0d40576169](https://linux-hardware.org/?probe=0d40576169) | Apr 27, 2021 |
| NEC Comput... | PALOMAR                     | [3eebff8fad](https://linux-hardware.org/?probe=3eebff8fad) | Apr 16, 2021 |
| ASUSTek       | P9X79                       | [e9636d21ef](https://linux-hardware.org/?probe=e9636d21ef) | Apr 15, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [f0a9a9b376](https://linux-hardware.org/?probe=f0a9a9b376) | Apr 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | [0f16d1f407](https://linux-hardware.org/?probe=0f16d1f407) | Apr 15, 2021 |
| MSI           | 760GA-P43                   | [f836b01395](https://linux-hardware.org/?probe=f836b01395) | Apr 14, 2021 |
| ASUSTek       | P5KC                        | [b9b6d74f4e](https://linux-hardware.org/?probe=b9b6d74f4e) | Apr 13, 2021 |
| Dell          | 0FH884                      | [93acc58efb](https://linux-hardware.org/?probe=93acc58efb) | Apr 10, 2021 |
| NEC Comput... | PALOMAR                     | [69d2761186](https://linux-hardware.org/?probe=69d2761186) | Apr 09, 2021 |
| ASUSTek       | P5KC                        | [2147d0b585](https://linux-hardware.org/?probe=2147d0b585) | Apr 08, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [3a66ababd9](https://linux-hardware.org/?probe=3a66ababd9) | Apr 08, 2021 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [9b436e3e3c](https://linux-hardware.org/?probe=9b436e3e3c) | Apr 07, 2021 |
| Dell          | 0G261D A00                  | [8b417f82c5](https://linux-hardware.org/?probe=8b417f82c5) | Apr 06, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [ed7761776f](https://linux-hardware.org/?probe=ed7761776f) | Apr 02, 2021 |
| ASUSTek       | PRIME B450M-A II            | [292671b8bb](https://linux-hardware.org/?probe=292671b8bb) | Mar 26, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [25b48fc578](https://linux-hardware.org/?probe=25b48fc578) | Mar 26, 2021 |
| ASUSTek       | P8H67-M LE                  | [d85cd54281](https://linux-hardware.org/?probe=d85cd54281) | Mar 21, 2021 |
| Gigabyte      | G41M-Combo                  | [b5838dd904](https://linux-hardware.org/?probe=b5838dd904) | Mar 20, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [d699973a80](https://linux-hardware.org/?probe=d699973a80) | Mar 15, 2021 |
| Pegatron      | 2A94h                       | [3b44f86cb2](https://linux-hardware.org/?probe=3b44f86cb2) | Mar 14, 2021 |
| ASRock        | A520M-HDV                   | [53bee57a08](https://linux-hardware.org/?probe=53bee57a08) | Mar 14, 2021 |
| MSI           | X470 GAMING PRO             | [d80b4b42b5](https://linux-hardware.org/?probe=d80b4b42b5) | Mar 10, 2021 |
| ASUSTek       | P5G41T-M LE                 | [a4382b583f](https://linux-hardware.org/?probe=a4382b583f) | Mar 09, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [aeb9dde634](https://linux-hardware.org/?probe=aeb9dde634) | Mar 09, 2021 |
| Acer          | FMCP7AM                     | [0f4686671e](https://linux-hardware.org/?probe=0f4686671e) | Mar 05, 2021 |
| ASUSTek       | A_F_K31DA_K31DAG_K20DA      | [84d8d1fd23](https://linux-hardware.org/?probe=84d8d1fd23) | Mar 03, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [f2186654a5](https://linux-hardware.org/?probe=f2186654a5) | Mar 03, 2021 |
| HP            | 3646h                       | [ae2d7f8ca8](https://linux-hardware.org/?probe=ae2d7f8ca8) | Mar 02, 2021 |
| Dell          | 0FH884                      | [e8894d16b4](https://linux-hardware.org/?probe=e8894d16b4) | Mar 02, 2021 |
| HP            | 08B8h                       | [c6f567409e](https://linux-hardware.org/?probe=c6f567409e) | Mar 02, 2021 |
| Acer          | FMCP7AM                     | [e73467285a](https://linux-hardware.org/?probe=e73467285a) | Mar 01, 2021 |
| Dell          | 0FH884                      | [3f73f703ea](https://linux-hardware.org/?probe=3f73f703ea) | Feb 25, 2021 |
| Dell          | 0FH884                      | [9ef7d7ac26](https://linux-hardware.org/?probe=9ef7d7ac26) | Feb 24, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [e0b5fd0d0f](https://linux-hardware.org/?probe=e0b5fd0d0f) | Feb 22, 2021 |
| BCM           | RX965Q                      | [889ee09398](https://linux-hardware.org/?probe=889ee09398) | Feb 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [a4096f684a](https://linux-hardware.org/?probe=a4096f684a) | Feb 21, 2021 |
| Lenovo        | MAHOBAY NOK                 | [517098f97e](https://linux-hardware.org/?probe=517098f97e) | Feb 19, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [aadae3018a](https://linux-hardware.org/?probe=aadae3018a) | Feb 19, 2021 |
| ASRock        | AB350M Pro4                 | [427b038f6c](https://linux-hardware.org/?probe=427b038f6c) | Feb 16, 2021 |
| MSI           | MS-7145                     | [9339e94272](https://linux-hardware.org/?probe=9339e94272) | Feb 15, 2021 |
| ASRock        | J3455M                      | [3858448941](https://linux-hardware.org/?probe=3858448941) | Feb 15, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | [5e21989251](https://linux-hardware.org/?probe=5e21989251) | Feb 14, 2021 |
| HP            | 2B36                        | [822dd71f17](https://linux-hardware.org/?probe=822dd71f17) | Feb 14, 2021 |
| Acer          | Aspire X1900                | [15ea004f33](https://linux-hardware.org/?probe=15ea004f33) | Feb 14, 2021 |
| MSI           | 890FXA-GD70                 | [ea6af67da0](https://linux-hardware.org/?probe=ea6af67da0) | Feb 13, 2021 |
| MSI           | G41M-P43 Combo              | [9854e43724](https://linux-hardware.org/?probe=9854e43724) | Feb 11, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [039362868b](https://linux-hardware.org/?probe=039362868b) | Feb 03, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [4c1fa69861](https://linux-hardware.org/?probe=4c1fa69861) | Feb 03, 2021 |
| MSI           | B360 GAMING PLUS            | [f409735b4a](https://linux-hardware.org/?probe=f409735b4a) | Feb 01, 2021 |
| ASRock        | AB350M Pro4                 | [f82376b2fc](https://linux-hardware.org/?probe=f82376b2fc) | Feb 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [159f94f03e](https://linux-hardware.org/?probe=159f94f03e) | Jan 29, 2021 |
| Dell          | 0GU083 A00                  | [b56844119d](https://linux-hardware.org/?probe=b56844119d) | Jan 29, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [273c518e4f](https://linux-hardware.org/?probe=273c518e4f) | Jan 28, 2021 |
| ASUSTek       | PRIME B350M-A               | [511b309049](https://linux-hardware.org/?probe=511b309049) | Jan 27, 2021 |
| MSI           | A320M PRO-VD/S              | [b0c09b63f4](https://linux-hardware.org/?probe=b0c09b63f4) | Jan 18, 2021 |
| MSI           | A320M PRO-VD/S              | [48710cf657](https://linux-hardware.org/?probe=48710cf657) | Jan 18, 2021 |
| ASUSTek       | P5SD2-VM                    | [9847d231eb](https://linux-hardware.org/?probe=9847d231eb) | Jan 14, 2021 |
| ASUSTek       | P5SD2-VM                    | [ee830fe216](https://linux-hardware.org/?probe=ee830fe216) | Jan 12, 2021 |
| ASUSTek       | P5G41T-M LX                 | [4db19bc22f](https://linux-hardware.org/?probe=4db19bc22f) | Jan 09, 2021 |
| HP            | 3397                        | [4c8e59bc44](https://linux-hardware.org/?probe=4c8e59bc44) | Jan 09, 2021 |
| HP            | Asterope                    | [9d863bfc8f](https://linux-hardware.org/?probe=9d863bfc8f) | Jan 08, 2021 |
| ASRock        | 775Dual-VSTA                | [e45a885545](https://linux-hardware.org/?probe=e45a885545) | Jan 03, 2021 |
| ASUSTek       | H87M-E                      | [d5d1562a32](https://linux-hardware.org/?probe=d5d1562a32) | Jan 01, 2021 |
| ASUSTek       | H87M-E                      | [b4a1983b91](https://linux-hardware.org/?probe=b4a1983b91) | Dec 27, 2020 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [660a038a14](https://linux-hardware.org/?probe=660a038a14) | Dec 23, 2020 |
| Dell          | 0RF703                      | [6f883fe6f5](https://linux-hardware.org/?probe=6f883fe6f5) | Dec 20, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [609543807e](https://linux-hardware.org/?probe=609543807e) | Dec 19, 2020 |
| Gigabyte      | P75-D3                      | [e50b2ea863](https://linux-hardware.org/?probe=e50b2ea863) | Dec 16, 2020 |
| ASUSTek       | B150M PRO GAMING            | [50e588847b](https://linux-hardware.org/?probe=50e588847b) | Dec 16, 2020 |
| HP            | 3031h                       | [b1c4657359](https://linux-hardware.org/?probe=b1c4657359) | Dec 16, 2020 |
| ASUSTek       | H87M-E                      | [ba189ceaa2](https://linux-hardware.org/?probe=ba189ceaa2) | Dec 14, 2020 |
| Intel         | D865GSA AAD53275-204        | [1decb62bf9](https://linux-hardware.org/?probe=1decb62bf9) | Dec 13, 2020 |
| Intel         | D865GSA AAD53275-204        | [b94183234b](https://linux-hardware.org/?probe=b94183234b) | Dec 13, 2020 |
| MSI           | X470 GAMING PRO             | [b910c55313](https://linux-hardware.org/?probe=b910c55313) | Dec 01, 2020 |
| ASUSTek       | D425MC                      | [a2a7090e43](https://linux-hardware.org/?probe=a2a7090e43) | Nov 23, 2020 |
| MSI           | 990FXA GAMING               | [c67dd69ea3](https://linux-hardware.org/?probe=c67dd69ea3) | Nov 21, 2020 |
| MSI           | 990FXA GAMING               | [7b6ef87411](https://linux-hardware.org/?probe=7b6ef87411) | Nov 21, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [3914e82da0](https://linux-hardware.org/?probe=3914e82da0) | Nov 14, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [65b64eedcc](https://linux-hardware.org/?probe=65b64eedcc) | Nov 13, 2020 |
| Gigabyte      | F2A68HM-DS2                 | [a255bdcfbc](https://linux-hardware.org/?probe=a255bdcfbc) | Nov 12, 2020 |
| ASUSTek       | D425MC                      | [50665babae](https://linux-hardware.org/?probe=50665babae) | Nov 09, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [4abd6c9e42](https://linux-hardware.org/?probe=4abd6c9e42) | Nov 08, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [0e4becb647](https://linux-hardware.org/?probe=0e4becb647) | Nov 06, 2020 |
| MSI           | G41M-P43 Combo              | [1d92dd04a2](https://linux-hardware.org/?probe=1d92dd04a2) | Oct 30, 2020 |
| ASUSTek       | P5G41T-M LE                 | [5d0df96501](https://linux-hardware.org/?probe=5d0df96501) | Oct 29, 2020 |
| ASUSTek       | P5G41T-M LE                 | [e4af11643b](https://linux-hardware.org/?probe=e4af11643b) | Oct 29, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [20acead566](https://linux-hardware.org/?probe=20acead566) | Oct 26, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [4b14ad2894](https://linux-hardware.org/?probe=4b14ad2894) | Oct 25, 2020 |
| ASUSTek       | P5G41T-M LX2/GB             | [8136a41002](https://linux-hardware.org/?probe=8136a41002) | Oct 24, 2020 |
| ASUSTek       | P8P67                       | [17105ed101](https://linux-hardware.org/?probe=17105ed101) | Oct 23, 2020 |
| ASUSTek       | B85M-E                      | [b6190da277](https://linux-hardware.org/?probe=b6190da277) | Oct 23, 2020 |
| ASUSTek       | H110M-K                     | [08c91cec4d](https://linux-hardware.org/?probe=08c91cec4d) | Oct 21, 2020 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | [b2c4383da1](https://linux-hardware.org/?probe=b2c4383da1) | Oct 20, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [12fab28ee5](https://linux-hardware.org/?probe=12fab28ee5) | Oct 14, 2020 |
| ASUSTek       | P5LD2-SE                    | [53e64ff105](https://linux-hardware.org/?probe=53e64ff105) | Oct 12, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [bfe6259c0c](https://linux-hardware.org/?probe=bfe6259c0c) | Oct 12, 2020 |
| ASUSTek       | Salmon                      | [1a9191eedc](https://linux-hardware.org/?probe=1a9191eedc) | Oct 12, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [19ef25af06](https://linux-hardware.org/?probe=19ef25af06) | Oct 09, 2020 |
| ASUSTek       | P5G41C-M LX                 | [d8d853d435](https://linux-hardware.org/?probe=d8d853d435) | Oct 09, 2020 |
| ASUSTek       | P8Z77-V LK                  | [490b10c9b5](https://linux-hardware.org/?probe=490b10c9b5) | Oct 03, 2020 |
| ASUSTek       | P9X79                       | [0cca3e59e7](https://linux-hardware.org/?probe=0cca3e59e7) | Oct 02, 2020 |
| MSI           | B350 PC MATE                | [fb4c90c999](https://linux-hardware.org/?probe=fb4c90c999) | Oct 02, 2020 |
| Foxconn       | 2ACA                        | [d1ca27b882](https://linux-hardware.org/?probe=d1ca27b882) | Oct 02, 2020 |
| ASUSTek       | Salmon                      | [67ec1c9e21](https://linux-hardware.org/?probe=67ec1c9e21) | Sep 30, 2020 |
| MSI           | B450M MORTAR                | [eb4023b66b](https://linux-hardware.org/?probe=eb4023b66b) | Sep 29, 2020 |
| MSI           | B150M MORTAR                | [1919443ef9](https://linux-hardware.org/?probe=1919443ef9) | Sep 29, 2020 |
| ASUSTek       | PRIME A320M-K               | [aa8ff9653f](https://linux-hardware.org/?probe=aa8ff9653f) | Sep 28, 2020 |
| Medion        | MS-7728                     | [27aa2e9b05](https://linux-hardware.org/?probe=27aa2e9b05) | Sep 28, 2020 |
| MSI           | B350M BAZOOKA               | [bc99ab4879](https://linux-hardware.org/?probe=bc99ab4879) | Sep 28, 2020 |
| ASUSTek       | P8H61-M LX                  | [f6ce95194c](https://linux-hardware.org/?probe=f6ce95194c) | Sep 27, 2020 |
| ASRock        | 775Dual-VSTA                | [40ed4cc83b](https://linux-hardware.org/?probe=40ed4cc83b) | Sep 24, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [1abfd8ee8e](https://linux-hardware.org/?probe=1abfd8ee8e) | Sep 23, 2020 |
| ASUSTek       | Z97-A                       | [caef8bbdd2](https://linux-hardware.org/?probe=caef8bbdd2) | Sep 23, 2020 |
| ASRock        | X399 Taichi                 | [785a16d818](https://linux-hardware.org/?probe=785a16d818) | Sep 18, 2020 |
| ASUSTek       | P5GC-MX/1333                | [dc4566d1a7](https://linux-hardware.org/?probe=dc4566d1a7) | Sep 16, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [deaed50282](https://linux-hardware.org/?probe=deaed50282) | Sep 04, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [24077cd964](https://linux-hardware.org/?probe=24077cd964) | Sep 03, 2020 |
| ASUSTek       | M4A88TD-M EVO               | [b084c1b4b6](https://linux-hardware.org/?probe=b084c1b4b6) | Aug 29, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [6fbe8eb952](https://linux-hardware.org/?probe=6fbe8eb952) | Aug 29, 2020 |
| Foxconn       | 2ACA                        | [3293f910eb](https://linux-hardware.org/?probe=3293f910eb) | Aug 26, 2020 |
| Foxconn       | 2ACA                        | [20eb163379](https://linux-hardware.org/?probe=20eb163379) | Aug 26, 2020 |
| Gigabyte      | G31M-ES2L                   | [ed4a78cd06](https://linux-hardware.org/?probe=ed4a78cd06) | Aug 24, 2020 |
| Gigabyte      | EP45C-DS3R                  | [3baa06afa2](https://linux-hardware.org/?probe=3baa06afa2) | Aug 24, 2020 |
| ASUSTek       | P8H61-M LX                  | [dcc65ae2a7](https://linux-hardware.org/?probe=dcc65ae2a7) | Aug 23, 2020 |
| ASUSTek       | B85M-E                      | [cb8240a746](https://linux-hardware.org/?probe=cb8240a746) | Aug 21, 2020 |
| ASUSTek       | P5KPL-AM IN/GB              | [004f0c4c8d](https://linux-hardware.org/?probe=004f0c4c8d) | Aug 19, 2020 |
| Gigabyte      | B75M-D3V                    | [a8a68b1821](https://linux-hardware.org/?probe=a8a68b1821) | Aug 10, 2020 |
| MSI           | G41M-P43 Combo              | [312331a2e9](https://linux-hardware.org/?probe=312331a2e9) | Aug 10, 2020 |
| ASRock        | B450M Pro4-F                | [bd00a821fd](https://linux-hardware.org/?probe=bd00a821fd) | Aug 07, 2020 |
| ASUSTek       | H87M-PLUS                   | [82f189206f](https://linux-hardware.org/?probe=82f189206f) | Aug 03, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [fff6cf2563](https://linux-hardware.org/?probe=fff6cf2563) | Aug 02, 2020 |
| ASRock        | 775Dual-VSTA                | [a2ad60fd2b](https://linux-hardware.org/?probe=a2ad60fd2b) | Aug 01, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [b981971204](https://linux-hardware.org/?probe=b981971204) | Aug 01, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [2195cd2a66](https://linux-hardware.org/?probe=2195cd2a66) | Aug 01, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [5e834a1db4](https://linux-hardware.org/?probe=5e834a1db4) | Jul 26, 2020 |
| ASUSTek       | B85M-E                      | [d745653595](https://linux-hardware.org/?probe=d745653595) | Jul 25, 2020 |
| MSI           | H81M-E33                    | [2ea88d42b6](https://linux-hardware.org/?probe=2ea88d42b6) | Jul 24, 2020 |
| Intel         | H81                         | [cd0d9e970b](https://linux-hardware.org/?probe=cd0d9e970b) | Jul 24, 2020 |
| ASUSTek       | P5VD2-MX                    | [b145b99009](https://linux-hardware.org/?probe=b145b99009) | Jul 24, 2020 |
| MSI           | B450 TOMAHAWK               | [b76c563f0f](https://linux-hardware.org/?probe=b76c563f0f) | Jul 24, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [9f64ca3b62](https://linux-hardware.org/?probe=9f64ca3b62) | Jul 24, 2020 |
| ASUSTek       | H110M-K                     | [8aeea51ed4](https://linux-hardware.org/?probe=8aeea51ed4) | Jul 24, 2020 |
| ASUSTek       | B85M-E                      | [256e33e5db](https://linux-hardware.org/?probe=256e33e5db) | Jul 24, 2020 |
| Gigabyte      | B450M DS3H-CF               | [df67dac45a](https://linux-hardware.org/?probe=df67dac45a) | Jul 23, 2020 |
| ASUSTek       | PRIME Z390-P                | [fcea9afdb8](https://linux-hardware.org/?probe=fcea9afdb8) | Jul 18, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [ed3275a3ef](https://linux-hardware.org/?probe=ed3275a3ef) | Jul 13, 2020 |
| ASUSTek       | P8H61-M                     | [a96a1f0249](https://linux-hardware.org/?probe=a96a1f0249) | Jul 08, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [b5a22259cb](https://linux-hardware.org/?probe=b5a22259cb) | Jul 06, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [3194e779dc](https://linux-hardware.org/?probe=3194e779dc) | Jul 05, 2020 |
| Acer          | Aspire M3910                | [574212361b](https://linux-hardware.org/?probe=574212361b) | Jun 28, 2020 |
| ASRock        | AB350M Pro4                 | [14e2fc82a2](https://linux-hardware.org/?probe=14e2fc82a2) | Jun 25, 2020 |
| Dell          | 09WH54 A00                  | [5c11bd4168](https://linux-hardware.org/?probe=5c11bd4168) | Jun 21, 2020 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [edab290676](https://linux-hardware.org/?probe=edab290676) | Jun 20, 2020 |
| ASUSTek       | H110M-K                     | [4d9b1b16c1](https://linux-hardware.org/?probe=4d9b1b16c1) | Jun 16, 2020 |
| HP            | 0A60h                       | [51cea91fd2](https://linux-hardware.org/?probe=51cea91fd2) | Jun 13, 2020 |
| ASRock        | 775Dual-VSTA                | [0e5ac5a0bf](https://linux-hardware.org/?probe=0e5ac5a0bf) | Jun 12, 2020 |
| HP            | 8436                        | [a714970832](https://linux-hardware.org/?probe=a714970832) | Jun 11, 2020 |
| HP            | 843B                        | [dddd13622f](https://linux-hardware.org/?probe=dddd13622f) | Jun 10, 2020 |
| MSI           | G41M-P26                    | [01089d258b](https://linux-hardware.org/?probe=01089d258b) | Jun 09, 2020 |
| ASUSTek       | H110M-K                     | [e87bd7a1e6](https://linux-hardware.org/?probe=e87bd7a1e6) | Jun 09, 2020 |
| ASRock        | 775Dual-VSTA                | [a4f3841c00](https://linux-hardware.org/?probe=a4f3841c00) | May 29, 2020 |
| Gigabyte      | B75M-D3H                    | [2e9b2bd361](https://linux-hardware.org/?probe=2e9b2bd361) | May 26, 2020 |
| ASUSTek       | PRIME A320M-K               | [2b0f0312d9](https://linux-hardware.org/?probe=2b0f0312d9) | May 20, 2020 |
| HP            | 0A54h                       | [0eb9ef0dd8](https://linux-hardware.org/?probe=0eb9ef0dd8) | May 18, 2020 |
| HP            | 0A54h                       | [c6dfcc177a](https://linux-hardware.org/?probe=c6dfcc177a) | May 17, 2020 |
| MSI           | B150M BAZOOKA PLUS          | [6042465eaf](https://linux-hardware.org/?probe=6042465eaf) | May 10, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b03c78fe4f](https://linux-hardware.org/?probe=b03c78fe4f) | May 09, 2020 |
| HP            | 3397                        | [3e224cf71e](https://linux-hardware.org/?probe=3e224cf71e) | May 07, 2020 |
| ASRock        | 775Dual-VSTA                | [3fe70d9fdd](https://linux-hardware.org/?probe=3fe70d9fdd) | May 06, 2020 |
| HP            | 8436                        | [cca70af9c6](https://linux-hardware.org/?probe=cca70af9c6) | May 05, 2020 |
| Acer          | Aspire X1900                | [8504ed80cb](https://linux-hardware.org/?probe=8504ed80cb) | May 05, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [7e0d4adca9](https://linux-hardware.org/?probe=7e0d4adca9) | May 04, 2020 |
| MSI           | 970A SLI Krait Edition      | [019e7deab8](https://linux-hardware.org/?probe=019e7deab8) | May 02, 2020 |
| HP            | 0AE8h C                     | [94f0b85b34](https://linux-hardware.org/?probe=94f0b85b34) | May 01, 2020 |
| ASRock        | 775Dual-VSTA                | [8fa9935547](https://linux-hardware.org/?probe=8fa9935547) | Apr 27, 2020 |
| Gigabyte      | B75M-D3V                    | [997cebc492](https://linux-hardware.org/?probe=997cebc492) | Apr 26, 2020 |
| Gigabyte      | B75M-D3V                    | [0001f7367a](https://linux-hardware.org/?probe=0001f7367a) | Apr 25, 2020 |
| Intel         | H81                         | [20f12251b6](https://linux-hardware.org/?probe=20f12251b6) | Apr 24, 2020 |
| ECS           | Nettle2                     | [ababaf523c](https://linux-hardware.org/?probe=ababaf523c) | Apr 19, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [4389b84dc5](https://linux-hardware.org/?probe=4389b84dc5) | Apr 16, 2020 |
| ASUSTek       | P5LD2-SE                    | [6d04e1a950](https://linux-hardware.org/?probe=6d04e1a950) | Apr 13, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b70c50223a](https://linux-hardware.org/?probe=b70c50223a) | Apr 13, 2020 |
| MSI           | AMETHYST-M                  | [d42d07bebb](https://linux-hardware.org/?probe=d42d07bebb) | Apr 13, 2020 |
| ASUSTek       | Z97-PRO GAMER               | [8ceac6a75e](https://linux-hardware.org/?probe=8ceac6a75e) | Apr 13, 2020 |
| ASUSTek       | Z97-PRO GAMER               | [6b51a788d2](https://linux-hardware.org/?probe=6b51a788d2) | Apr 13, 2020 |
| MSI           | AMETHYST-M                  | [7c3997226d](https://linux-hardware.org/?probe=7c3997226d) | Apr 12, 2020 |
| ASUSTek       | M5A78L-M LX3                | [946ccde46f](https://linux-hardware.org/?probe=946ccde46f) | Apr 11, 2020 |
| Dell          | 0D28YY A00                  | [df89132283](https://linux-hardware.org/?probe=df89132283) | Apr 07, 2020 |
| Dell          | 0D28YY A00                  | [b87bc42bd0](https://linux-hardware.org/?probe=b87bc42bd0) | Apr 07, 2020 |
| Gigabyte      | B450M S2H                   | [1d19709a92](https://linux-hardware.org/?probe=1d19709a92) | Apr 07, 2020 |
| eMachines     | EMCP73M                     | [7ff7403af5](https://linux-hardware.org/?probe=7ff7403af5) | Apr 05, 2020 |
| ASUSTek       | P5LD2-SE                    | [21301abfd3](https://linux-hardware.org/?probe=21301abfd3) | Apr 03, 2020 |
| ASUSTek       | H97M-PLUS                   | [f33249c23f](https://linux-hardware.org/?probe=f33249c23f) | Apr 02, 2020 |
| ASUSTek       | A88X-PLUS                   | [eca8e2e768](https://linux-hardware.org/?probe=eca8e2e768) | Apr 02, 2020 |
| Dell          | 0D28YY A00                  | [616bad5cf3](https://linux-hardware.org/?probe=616bad5cf3) | Apr 01, 2020 |
| Gigabyte      | H310M H x.x                 | [b162dadd40](https://linux-hardware.org/?probe=b162dadd40) | Apr 01, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [6ec95a666d](https://linux-hardware.org/?probe=6ec95a666d) | Apr 01, 2020 |
| MSI           | MS-7341 10                  | [05450f5d8f](https://linux-hardware.org/?probe=05450f5d8f) | Mar 26, 2020 |
| MSI           | MS-7341 10                  | [98321d452d](https://linux-hardware.org/?probe=98321d452d) | Mar 21, 2020 |
| Acer          | RS740DVF                    | [93b6fee4e0](https://linux-hardware.org/?probe=93b6fee4e0) | Mar 12, 2020 |
| Acer          | RS740DVF                    | [be9d829372](https://linux-hardware.org/?probe=be9d829372) | Mar 11, 2020 |
| ASUSTek       | Z97-A                       | [40aef28c8a](https://linux-hardware.org/?probe=40aef28c8a) | Mar 08, 2020 |
| ASUSTek       | P5Q SE/R                    | [e7178ba8e7](https://linux-hardware.org/?probe=e7178ba8e7) | Mar 06, 2020 |
| AMI           | Cherry Trail CR             | [7f33611531](https://linux-hardware.org/?probe=7f33611531) | Mar 06, 2020 |
| AMI           | Cherry Trail CR             | [6ba8797a59](https://linux-hardware.org/?probe=6ba8797a59) | Mar 06, 2020 |
| Gigabyte      | H310M H x.x                 | [e5d85d26dd](https://linux-hardware.org/?probe=e5d85d26dd) | Mar 05, 2020 |
| ASRock        | B450M-HDV R4.0              | [e302ca148e](https://linux-hardware.org/?probe=e302ca148e) | Mar 05, 2020 |
| Acer          | RS740DVF                    | [aeb499b9d4](https://linux-hardware.org/?probe=aeb499b9d4) | Mar 04, 2020 |
| ASUSTek       | P5QL-ASUS-SE                | [b822a2ccbc](https://linux-hardware.org/?probe=b822a2ccbc) | Mar 02, 2020 |
| ASUSTek       | M3N-H/HDMI                  | [4b08896af8](https://linux-hardware.org/?probe=4b08896af8) | Mar 01, 2020 |
| ASUSTek       | P5G41T-M LX                 | [900ebfc65f](https://linux-hardware.org/?probe=900ebfc65f) | Mar 01, 2020 |
| MSI           | 970A GAMING PRO CARBON      | [84a38bd601](https://linux-hardware.org/?probe=84a38bd601) | Mar 01, 2020 |
| ASUSTek       | P5G41T-M LX                 | [f29225f74c](https://linux-hardware.org/?probe=f29225f74c) | Feb 24, 2020 |
| Medion        | MS-7366                     | [63d7b30a5a](https://linux-hardware.org/?probe=63d7b30a5a) | Feb 23, 2020 |
| Medion        | MS-7366                     | [ca03901ede](https://linux-hardware.org/?probe=ca03901ede) | Feb 23, 2020 |
| ASUSTek       | P5G41T-M LX                 | [e60551ae18](https://linux-hardware.org/?probe=e60551ae18) | Feb 22, 2020 |
| HP            | 2B36                        | [9e63f29da5](https://linux-hardware.org/?probe=9e63f29da5) | Feb 17, 2020 |
| Gigabyte      | G1.Sniper B6-CF             | [34bc4e6ef8](https://linux-hardware.org/?probe=34bc4e6ef8) | Feb 07, 2020 |
| Gigabyte      | G1.Sniper B6-CF             | [dcb876e046](https://linux-hardware.org/?probe=dcb876e046) | Feb 07, 2020 |
| ASUSTek       | P5LD2-VM                    | [3b118987fd](https://linux-hardware.org/?probe=3b118987fd) | Feb 03, 2020 |
| ASUSTek       | P5LD2-VM                    | [7eb3d3f57c](https://linux-hardware.org/?probe=7eb3d3f57c) | Jan 27, 2020 |
| HP            | 843B                        | [603aa1061c](https://linux-hardware.org/?probe=603aa1061c) | Jan 26, 2020 |
| HP            | 843B                        | [3673691cb2](https://linux-hardware.org/?probe=3673691cb2) | Jan 24, 2020 |
| HP            | 843B                        | [19231872c2](https://linux-hardware.org/?probe=19231872c2) | Jan 24, 2020 |
| Gigabyte      | B450M S2H                   | [ce8c8e3437](https://linux-hardware.org/?probe=ce8c8e3437) | Jan 19, 2020 |
| ASRock        | N68C-GS FX                  | [ed869b8762](https://linux-hardware.org/?probe=ed869b8762) | Jan 16, 2020 |
| ASRock        | N68-GS4/USB3 FX R2.0        | [1a903c9d61](https://linux-hardware.org/?probe=1a903c9d61) | Jan 14, 2020 |
| Huanan        | X79 VAA1                    | [bf970865ee](https://linux-hardware.org/?probe=bf970865ee) | Jan 13, 2020 |
| Dell          | 0GU083 A00                  | [f0711f3888](https://linux-hardware.org/?probe=f0711f3888) | Jan 10, 2020 |
| ASUSTek       | P5K SE/EPU                  | [5ee0f1db4c](https://linux-hardware.org/?probe=5ee0f1db4c) | Dec 19, 2019 |
| ASUSTek       | P5K SE/EPU                  | [9761122ab6](https://linux-hardware.org/?probe=9761122ab6) | Dec 17, 2019 |
| ASUSTek       | PRIME B250M-A               | [ae2fce57b5](https://linux-hardware.org/?probe=ae2fce57b5) | Dec 15, 2019 |
| Gigabyte      | B450M S2H                   | [65309beec0](https://linux-hardware.org/?probe=65309beec0) | Dec 09, 2019 |
| Gigabyte      | B450M S2H                   | [69cdd45ef3](https://linux-hardware.org/?probe=69cdd45ef3) | Dec 07, 2019 |
| Gigabyte      | B450M S2H                   | [985f0a93d2](https://linux-hardware.org/?probe=985f0a93d2) | Dec 07, 2019 |
| ASRock        | ConRoe945G-DVI              | [984156a325](https://linux-hardware.org/?probe=984156a325) | Dec 05, 2019 |
| ASUSTek       | P5KPL-AM SE                 | [e62db6e4e2](https://linux-hardware.org/?probe=e62db6e4e2) | Dec 02, 2019 |
| ASUSTek       | PRIME B250M-A               | [636cf95a59](https://linux-hardware.org/?probe=636cf95a59) | Nov 28, 2019 |
| Gigabyte      | B450M S2H                   | [e08baa017d](https://linux-hardware.org/?probe=e08baa017d) | Nov 23, 2019 |
| MSI           | 760GA-P43                   | [8e365df17f](https://linux-hardware.org/?probe=8e365df17f) | Nov 23, 2019 |
| Gigabyte      | G31M-ES2L                   | [0a1bc31c2a](https://linux-hardware.org/?probe=0a1bc31c2a) | Nov 19, 2019 |
| MSI           | B360M PRO-VDH               | [f83d0a812d](https://linux-hardware.org/?probe=f83d0a812d) | Nov 15, 2019 |
| Gigabyte      | AX370M-Gaming 3-CF          | [1679a050fb](https://linux-hardware.org/?probe=1679a050fb) | Nov 15, 2019 |
| Gigabyte      | AX370M-Gaming 3-CF          | [7850ee9963](https://linux-hardware.org/?probe=7850ee9963) | Nov 14, 2019 |
| ASUSTek       | P7H55-M                     | [376e73248b](https://linux-hardware.org/?probe=376e73248b) | Nov 10, 2019 |
| ASUSTek       | P7H55-M                     | [79e7d0b350](https://linux-hardware.org/?probe=79e7d0b350) | Nov 10, 2019 |
| Gigabyte      | B450M S2H                   | [b90be9510c](https://linux-hardware.org/?probe=b90be9510c) | Nov 07, 2019 |
| ASUSTek       | PRIME B250M-A               | [eb9fc83248](https://linux-hardware.org/?probe=eb9fc83248) | Nov 04, 2019 |
| ASUSTek       | PRIME B250M-A               | [1300445d89](https://linux-hardware.org/?probe=1300445d89) | Nov 03, 2019 |
| ASUSTek       | P5P43TD PRO                 | [b56c2b2e60](https://linux-hardware.org/?probe=b56c2b2e60) | Nov 02, 2019 |
| Dell          | 0KWVT8 A02                  | [6ed3187d7a](https://linux-hardware.org/?probe=6ed3187d7a) | Nov 01, 2019 |
| Intel         | D945GCZ AAC99321-502        | [9939882441](https://linux-hardware.org/?probe=9939882441) | Oct 15, 2019 |
| Intel         | D945GCZ AAC99321-502        | [7062600603](https://linux-hardware.org/?probe=7062600603) | Oct 15, 2019 |
| eMachines     | EL1850                      | [0ab5268867](https://linux-hardware.org/?probe=0ab5268867) | Oct 12, 2019 |
| GIADA         | SHARKBAY JHS688             | [51a3f3bf52](https://linux-hardware.org/?probe=51a3f3bf52) | Oct 07, 2019 |
| Unknown       | Unknown                     | [3a75852dac](https://linux-hardware.org/?probe=3a75852dac) | Oct 05, 2019 |
| Acer          | GRS400M                     | [1d3dc49b0a](https://linux-hardware.org/?probe=1d3dc49b0a) | Sep 29, 2019 |
| ASUSTek       | Z170-A                      | [8a875af2b7](https://linux-hardware.org/?probe=8a875af2b7) | Sep 28, 2019 |
| Acer          | GRS400M                     | [e510d98ae4](https://linux-hardware.org/?probe=e510d98ae4) | Sep 22, 2019 |
| Acer          | GRS400M                     | [213156ffb7](https://linux-hardware.org/?probe=213156ffb7) | Sep 22, 2019 |
| Gigabyte      | F2A68HM-DS2                 | [b2450355f1](https://linux-hardware.org/?probe=b2450355f1) | Sep 22, 2019 |
| HP            | 18E4                        | [169718ec5d](https://linux-hardware.org/?probe=169718ec5d) | Sep 20, 2019 |
| Gigabyte      | G31M-ES2L                   | [1e6cb16b41](https://linux-hardware.org/?probe=1e6cb16b41) | Sep 16, 2019 |
| ASUSTek       | P8H67-V                     | [b0c20b14d8](https://linux-hardware.org/?probe=b0c20b14d8) | Sep 13, 2019 |
| Gigabyte      | G31M-ES2L                   | [bb555c11ae](https://linux-hardware.org/?probe=bb555c11ae) | Sep 11, 2019 |
| ASUSTek       | M4A78 PRO                   | [85dbb03610](https://linux-hardware.org/?probe=85dbb03610) | Sep 02, 2019 |
| ASUSTek       | P8H67-M PRO                 | [e287f6207b](https://linux-hardware.org/?probe=e287f6207b) | Aug 28, 2019 |
| Intel         | D33217CK G76541-301         | [11b398d3ef](https://linux-hardware.org/?probe=11b398d3ef) | Aug 20, 2019 |
| MSI           | B360M PRO-VDH               | [2d45947160](https://linux-hardware.org/?probe=2d45947160) | Aug 09, 2019 |
| Gigabyte      | B75M-D3V                    | [eaac8d48ee](https://linux-hardware.org/?probe=eaac8d48ee) | Jul 29, 2019 |
| Gigabyte      | 970A-UD3P                   | [8cdd8ffe23](https://linux-hardware.org/?probe=8cdd8ffe23) | Jul 26, 2019 |
| Gigabyte      | 970A-UD3P                   | [69d1517ba1](https://linux-hardware.org/?probe=69d1517ba1) | Jul 26, 2019 |
| ASUSTek       | PRIME B250M-A               | [7f1f084a4f](https://linux-hardware.org/?probe=7f1f084a4f) | Jul 22, 2019 |
| Acer          | Aspire X1900                | [3c153b6c2a](https://linux-hardware.org/?probe=3c153b6c2a) | Jul 01, 2019 |
| ASUSTek       | PRIME B250M-A               | [26bcd3b325](https://linux-hardware.org/?probe=26bcd3b325) | Jun 27, 2019 |
| MSI           | Z68A-GD80                   | [c63ed488ad](https://linux-hardware.org/?probe=c63ed488ad) | Jun 21, 2019 |
| MSI           | Z68A-GD80                   | [ef06e84cda](https://linux-hardware.org/?probe=ef06e84cda) | Jun 20, 2019 |
| Gigabyte      | Z97-HD3                     | [5bb09aeb32](https://linux-hardware.org/?probe=5bb09aeb32) | Jun 19, 2019 |
| Dell          | 03NVJ6 A02                  | [160c2de51f](https://linux-hardware.org/?probe=160c2de51f) | Jun 17, 2019 |
| MSI           | B75A-G41                    | [0a593d376a](https://linux-hardware.org/?probe=0a593d376a) | Jun 16, 2019 |
| Gigabyte      | 8I915P-D                    | [1012bd5a43](https://linux-hardware.org/?probe=1012bd5a43) | Jun 16, 2019 |
| Gigabyte      | 8I915P-D                    | [770fa46180](https://linux-hardware.org/?probe=770fa46180) | Jun 16, 2019 |
| Gigabyte      | X58A-UD7                    | [a72ee8fc63](https://linux-hardware.org/?probe=a72ee8fc63) | Jun 11, 2019 |
| ASRock        | 970 Extreme4                | [0fa01e4d66](https://linux-hardware.org/?probe=0fa01e4d66) | Jun 06, 2019 |
| OEM           | EIRD-SAM                    | [db87d8567e](https://linux-hardware.org/?probe=db87d8567e) | May 30, 2019 |
| HP            | 1494                        | [25810f9dc3](https://linux-hardware.org/?probe=25810f9dc3) | May 28, 2019 |
| ASUSTek       | PRIME B250M-A               | [6555e3060d](https://linux-hardware.org/?probe=6555e3060d) | May 26, 2019 |
| Gigabyte      | H55M-S2H                    | [7d62e5bc34](https://linux-hardware.org/?probe=7d62e5bc34) | May 21, 2019 |
| ASUSTek       | PRIME B250M-A               | [a595e6c0f8](https://linux-hardware.org/?probe=a595e6c0f8) | May 19, 2019 |
| ASUSTek       | P5B-VM                      | [79d120d78a](https://linux-hardware.org/?probe=79d120d78a) | May 18, 2019 |
| ASUSTek       | PRIME B250M-A               | [5c5bd85a88](https://linux-hardware.org/?probe=5c5bd85a88) | May 15, 2019 |
| ASUSTek       | PRIME B250M-A               | [eea01b0dc4](https://linux-hardware.org/?probe=eea01b0dc4) | May 15, 2019 |
| ASUSTek       | PRIME B250M-A               | [b0e6f5b516](https://linux-hardware.org/?probe=b0e6f5b516) | May 14, 2019 |
| eMachines     | EMCP73M                     | [d2994e2fad](https://linux-hardware.org/?probe=d2994e2fad) | Apr 23, 2019 |
| ASUSTek       | H81-GAMER                   | [9145f41194](https://linux-hardware.org/?probe=9145f41194) | Apr 22, 2019 |
| ASUSTek       | H110M-K                     | [73b13633f2](https://linux-hardware.org/?probe=73b13633f2) | Apr 19, 2019 |
| Acer          | FMP55                       | [8c28446a53](https://linux-hardware.org/?probe=8c28446a53) | Apr 19, 2019 |
| ASUSTek       | B85M-G                      | [658bcf12c4](https://linux-hardware.org/?probe=658bcf12c4) | Apr 15, 2019 |
| Foxconn       | G31MXP FAB:1.1              | [84ae7d38dd](https://linux-hardware.org/?probe=84ae7d38dd) | Apr 14, 2019 |
| ASUSTek       | Benicia                     | [1f8cda3921](https://linux-hardware.org/?probe=1f8cda3921) | Apr 09, 2019 |
| ASUSTek       | Benicia                     | [b1615f3369](https://linux-hardware.org/?probe=b1615f3369) | Apr 09, 2019 |
| HP            | ProLiant ML310e Gen8        | [6ffa42170b](https://linux-hardware.org/?probe=6ffa42170b) | Mar 30, 2019 |
| HP            | 1494                        | [44ac651021](https://linux-hardware.org/?probe=44ac651021) | Mar 28, 2019 |
| ASUSTek       | PRIME B250M-A               | [2f6bc6be29](https://linux-hardware.org/?probe=2f6bc6be29) | Mar 28, 2019 |
| Gigabyte      | G1.Sniper B6-CF             | [c20b184fc3](https://linux-hardware.org/?probe=c20b184fc3) | Mar 27, 2019 |
| ASRock        | 970 Extreme4                | [e2e8bb29ea](https://linux-hardware.org/?probe=e2e8bb29ea) | Mar 22, 2019 |
| Intel         | D2500HN AAG81480-500        | [18f900cb5b](https://linux-hardware.org/?probe=18f900cb5b) | Mar 04, 2019 |
| MSI           | H81M-E33                    | [920d422115](https://linux-hardware.org/?probe=920d422115) | Feb 06, 2019 |
| HP            | 843B                        | [5ffb1194b1](https://linux-hardware.org/?probe=5ffb1194b1) | Jan 30, 2019 |
| MSI           | H310M PRO-VD                | [33c6c6f3a6](https://linux-hardware.org/?probe=33c6c6f3a6) | Jan 14, 2019 |
| ASRock        | Q1900B-ITX                  | [18ca69190b](https://linux-hardware.org/?probe=18ca69190b) | Jan 07, 2019 |
| ABIT          | F-I90HD                     | [b158a21c8f](https://linux-hardware.org/?probe=b158a21c8f) | Dec 22, 2018 |
| Gigabyte      | H55M-S2H                    | [34831e35fd](https://linux-hardware.org/?probe=34831e35fd) | Dec 18, 2018 |
| ASUSTek       | M5A97 R2.0                  | [89b0446385](https://linux-hardware.org/?probe=89b0446385) | Dec 14, 2018 |
| HP            | 3031h                       | [0c08eee650](https://linux-hardware.org/?probe=0c08eee650) | Dec 12, 2018 |
| HP            | 3031h                       | [2c22bfe429](https://linux-hardware.org/?probe=2c22bfe429) | Dec 12, 2018 |
| ASUSTek       | H110M-K                     | [5169edc36e](https://linux-hardware.org/?probe=5169edc36e) | Dec 12, 2018 |
| HP            | 3646h                       | [d930f87402](https://linux-hardware.org/?probe=d930f87402) | Dec 11, 2018 |
| ASUSTek       | P5G41T-M LX2/GB             | [fe5f95f298](https://linux-hardware.org/?probe=fe5f95f298) | Nov 14, 2018 |
| Gigabyte      | GA-MA785GMT-UD2H            | [ca9cd7920f](https://linux-hardware.org/?probe=ca9cd7920f) | Oct 24, 2018 |
| Gigabyte      | GA-MA785GMT-UD2H            | [edc37ce67e](https://linux-hardware.org/?probe=edc37ce67e) | Oct 24, 2018 |
| ASUSTek       | M5A78L LE                   | [762df5fa40](https://linux-hardware.org/?probe=762df5fa40) | Oct 22, 2018 |
| ASUSTek       | PRIME B350-PLUS             | [e2d2b150a5](https://linux-hardware.org/?probe=e2d2b150a5) | Sep 26, 2018 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [491d157b81](https://linux-hardware.org/?probe=491d157b81) | Jun 03, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Portugal/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 60       | 10.93%  |
| Ubuntu 18.04                 | 49       | 8.93%   |
| Ubuntu 22.04                 | 22       | 4.01%   |
| OpenMandriva 4.3             | 14       | 2.55%   |
| OpenMandriva 4.2             | 14       | 2.55%   |
| Debian 11                    | 14       | 2.55%   |
| Zorin 16                     | 12       | 2.19%   |
| ArcoLinux Rolling            | 12       | 2.19%   |
| Arch Rolling                 | 11       | 2%      |
| Pop!_OS 22.04                | 10       | 1.82%   |
| Linux Mint 20                | 10       | 1.82%   |
| Linux Mint 19.3              | 10       | 1.82%   |
| Ubuntu 21.04                 | 8        | 1.46%   |
| Ubuntu 19.10                 | 7        | 1.28%   |
| Pop!_OS 20.04                | 7        | 1.28%   |
| openSUSE Tumbleweed-XXXXXXXX | 7        | 1.28%   |
| OpenMandriva 23.01           | 7        | 1.28%   |
| Manjaro                      | 7        | 1.28%   |
| Linux Mint 21.1              | 7        | 1.28%   |
| Fedora 39                    | 7        | 1.28%   |
| Ubuntu 23.04                 | 6        | 1.09%   |
| Linux Mint 21.2              | 6        | 1.09%   |
| Linux Mint 20.2              | 6        | 1.09%   |
| Fedora 38                    | 6        | 1.09%   |
| Fedora 31                    | 6        | 1.09%   |
| Debian 12                    | 6        | 1.09%   |
| Ubuntu 20.10                 | 5        | 0.91%   |
| Pop!_OS 21.04                | 5        | 0.91%   |
| OpenMandriva 23.03           | 5        | 0.91%   |
| Linux Mint 20.1              | 5        | 0.91%   |
| Fedora 36                    | 5        | 0.91%   |
| Zorin 15                     | 4        | 0.73%   |
| Xubuntu 20.04                | 4        | 0.73%   |
| Xubuntu 18.04                | 4        | 0.73%   |
| Pop!_OS 21.10                | 4        | 0.73%   |
| OpenMandriva 4.50            | 4        | 0.73%   |
| Linux Mint 20.3              | 4        | 0.73%   |
| Kubuntu 22.04                | 4        | 0.73%   |
| Fedora 37                    | 4        | 0.73%   |
| Fedora 32                    | 4        | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu            | 164      | 31.78%  |
| Linux Mint        | 54       | 10.47%  |
| OpenMandriva      | 48       | 9.3%    |
| Fedora            | 34       | 6.59%   |
| Debian            | 29       | 5.62%   |
| Pop!_OS           | 26       | 5.04%   |
| Manjaro           | 18       | 3.49%   |
| Zorin             | 17       | 3.29%   |
| Arch              | 13       | 2.52%   |
| ArcoLinux         | 12       | 2.33%   |
| Xubuntu           | 11       | 2.13%   |
| Kubuntu           | 10       | 1.94%   |
| ROSA              | 9        | 1.74%   |
| openSUSE          | 9        | 1.74%   |
| Endless           | 7        | 1.36%   |
| Elementary        | 6        | 1.16%   |
| Ubuntu Unity      | 4        | 0.78%   |
| Ubuntu MATE       | 4        | 0.78%   |
| KDE neon          | 4        | 0.78%   |
| Ubuntu Budgie     | 3        | 0.58%   |
| EndeavourOS       | 3        | 0.58%   |
| Clear Linux       | 3        | 0.58%   |
| UbuntuDDE         | 2        | 0.39%   |
| Slackware         | 2        | 0.39%   |
| Nobara            | 2        | 0.39%   |
| LMDE              | 2        | 0.39%   |
| CentOS            | 2        | 0.39%   |
| BigLinux          | 2        | 0.39%   |
| Xero              | 1        | 0.19%   |
| TUXEDO OS         | 1        | 0.19%   |
| SteamOS           | 1        | 0.19%   |
| Solus             | 1        | 0.19%   |
| Slackware-current | 1        | 0.19%   |
| Rocky Linux       | 1        | 0.19%   |
| Puppy             | 1        | 0.19%   |
| Peppermint        | 1        | 0.19%   |
| Pear OS           | 1        | 0.19%   |
| NixOS             | 1        | 0.19%   |
| Lubuntu           | 1        | 0.19%   |
| Gentoo            | 1        | 0.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 14       | 2.24%   |
| 5.4.0-42-generic         | 13       | 2.08%   |
| 5.16.7-desktop-1omv4003  | 12       | 1.92%   |
| 5.15.0-76-generic        | 6        | 0.96%   |
| 5.15.0-56-generic        | 6        | 0.96%   |
| 6.2.6-desktop-1omv2390   | 5        | 0.8%    |
| 6.1.1-desktop-1omv2290   | 5        | 0.8%    |
| 5.8.0-43-generic         | 5        | 0.8%    |
| 5.4.0-58-generic         | 5        | 0.8%    |
| 5.4.0-48-generic         | 5        | 0.8%    |
| 5.4.0-26-generic         | 5        | 0.8%    |
| 5.10.0-8-amd64           | 5        | 0.8%    |
| 5.8.0-48-generic         | 4        | 0.64%   |
| 5.8.0-44-generic         | 4        | 0.64%   |
| 5.4.0-77-generic         | 4        | 0.64%   |
| 5.4.0-52-generic         | 4        | 0.64%   |
| 5.19.0-76051900-generic  | 4        | 0.64%   |
| 5.19.0-35-generic        | 4        | 0.64%   |
| 5.15.0-58-generic        | 4        | 0.64%   |
| 5.15.0-57-generic        | 4        | 0.64%   |
| 5.13.0-7614-generic      | 4        | 0.64%   |
| 6.5.6-76060506-generic   | 3        | 0.48%   |
| 6.5.5-desktop-1omv2390   | 3        | 0.48%   |
| 6.5.12-300.fc39.x86_64   | 3        | 0.48%   |
| 6.5.0-10-generic         | 3        | 0.48%   |
| 6.4.11-desktop-1omv2390  | 3        | 0.48%   |
| 6.2.0-23-generic         | 3        | 0.48%   |
| 6.0.6-76060006-generic   | 3        | 0.48%   |
| 5.4.0-7634-generic       | 3        | 0.48%   |
| 5.4.0-40-generic         | 3        | 0.48%   |
| 5.4.0-37-generic         | 3        | 0.48%   |
| 5.4.0-29-generic         | 3        | 0.48%   |
| 5.4.0-28-generic         | 3        | 0.48%   |
| 5.3.0-51-generic         | 3        | 0.48%   |
| 5.3.0-46-generic         | 3        | 0.48%   |
| 5.3.0-40-generic         | 3        | 0.48%   |
| 5.15.0-91-generic        | 3        | 0.48%   |
| 5.15.0-73-generic        | 3        | 0.48%   |
| 5.15.0-72-generic        | 3        | 0.48%   |
| 5.15.0-71-generic        | 3        | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 78       | 13.43%  |
| 5.15.0  | 55       | 9.47%   |
| 4.15.0  | 40       | 6.88%   |
| 5.8.0   | 28       | 4.82%   |
| 5.3.0   | 25       | 4.3%    |
| 5.11.0  | 22       | 3.79%   |
| 5.19.0  | 17       | 2.93%   |
| 5.13.0  | 17       | 2.93%   |
| 5.0.0   | 16       | 2.75%   |
| 6.2.0   | 15       | 2.58%   |
| 5.10.14 | 14       | 2.41%   |
| 4.18.0  | 13       | 2.24%   |
| 5.16.7  | 12       | 2.07%   |
| 5.10.0  | 11       | 1.89%   |
| 6.2.6   | 7        | 1.2%    |
| 6.1.1   | 6        | 1.03%   |
| 6.5.5   | 5        | 0.86%   |
| 6.5.0   | 5        | 0.86%   |
| 6.1.0   | 5        | 0.86%   |
| 6.0.9   | 5        | 0.86%   |
| 4.19.0  | 5        | 0.86%   |
| 6.5.6   | 4        | 0.69%   |
| 6.5.12  | 4        | 0.69%   |
| 6.3.5   | 4        | 0.69%   |
| 5.15.7  | 4        | 0.69%   |
| 5.11.12 | 4        | 0.69%   |
| 4.9.155 | 4        | 0.69%   |
| 6.4.11  | 3        | 0.52%   |
| 6.1.4   | 3        | 0.52%   |
| 6.0.6   | 3        | 0.52%   |
| 5.13.19 | 3        | 0.52%   |
| 6.6.3   | 2        | 0.34%   |
| 6.2.7   | 2        | 0.34%   |
| 6.2.12  | 2        | 0.34%   |
| 6.1.20  | 2        | 0.34%   |
| 6.0.7   | 2        | 0.34%   |
| 5.8.6   | 2        | 0.34%   |
| 5.8.12  | 2        | 0.34%   |
| 5.7.10  | 2        | 0.34%   |
| 5.7.0   | 2        | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 84       | 14.87%  |
| 5.15    | 67       | 11.86%  |
| 4.15    | 41       | 7.26%   |
| 5.8     | 35       | 6.19%   |
| 6.2     | 33       | 5.84%   |
| 5.10    | 29       | 5.13%   |
| 5.11    | 27       | 4.78%   |
| 5.3     | 25       | 4.42%   |
| 5.19    | 24       | 4.25%   |
| 5.13    | 24       | 4.25%   |
| 6.5     | 21       | 3.72%   |
| 6.1     | 17       | 3.01%   |
| 5.16    | 16       | 2.83%   |
| 5.0     | 16       | 2.83%   |
| 4.18    | 16       | 2.83%   |
| 6.0     | 13       | 2.3%    |
| 6.3     | 8        | 1.42%   |
| 4.9     | 8        | 1.42%   |
| 5.18    | 7        | 1.24%   |
| 6.6     | 6        | 1.06%   |
| 5.7     | 6        | 1.06%   |
| 5.14    | 6        | 1.06%   |
| 4.19    | 6        | 1.06%   |
| 5.9     | 5        | 0.88%   |
| 5.12    | 5        | 0.88%   |
| 6.4     | 4        | 0.71%   |
| 5.6     | 3        | 0.53%   |
| 5.5     | 3        | 0.53%   |
| 5.17    | 3        | 0.53%   |
| 4.10    | 2        | 0.35%   |
| 5.2     | 1        | 0.18%   |
| 5.1     | 1        | 0.18%   |
| 4.4     | 1        | 0.18%   |
| 4.12    | 1        | 0.18%   |
| 2.6     | 1        | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 472      | 96.72%  |
| i686   | 16       | 3.28%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 205      | 39.35%  |
| KDE5            | 93       | 17.85%  |
| Unknown         | 75       | 14.4%   |
| XFCE            | 44       | 8.45%   |
| X-Cinnamon      | 42       | 8.06%   |
| KDE             | 11       | 2.11%   |
| MATE            | 10       | 1.92%   |
| Budgie          | 8        | 1.54%   |
| Pantheon        | 7        | 1.34%   |
| awesome         | 5        | 0.96%   |
| Unity           | 4        | 0.77%   |
| Cinnamon        | 4        | 0.77%   |
| KDE4            | 3        | 0.58%   |
| i3              | 2        | 0.38%   |
| GNOME Flashback | 2        | 0.38%   |
| Deepin          | 2        | 0.38%   |
| qtile           | 1        | 0.19%   |
| LXQt            | 1        | 0.19%   |
| LXDE            | 1        | 0.19%   |
| LeftWM          | 1        | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 378      | 74.7%   |
| Wayland | 74       | 14.62%  |
| Unknown | 45       | 8.89%   |
| Tty     | 9        | 1.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 283      | 55.49%  |
| SDDM    | 78       | 15.29%  |
| LightDM | 50       | 9.8%    |
| GDM3    | 47       | 9.22%   |
| GDM     | 34       | 6.67%   |
| TDM     | 14       | 2.75%   |
| KDM     | 3        | 0.59%   |
| XDM     | 1        | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| pt_PT   | 226      | 44.66%  |
| en_US   | 158      | 31.23%  |
| Unknown | 64       | 12.65%  |
| en_GB   | 21       | 4.15%   |
| C       | 10       | 1.98%   |
| ru_RU   | 6        | 1.19%   |
| pt_BR   | 5        | 0.99%   |
| fr_FR   | 4        | 0.79%   |
| sv_SE   | 3        | 0.59%   |
| es_ES   | 3        | 0.59%   |
| de_DE   | 3        | 0.59%   |
| en_CA   | 2        | 0.4%    |
| en_PT   | 1        | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 338      | 67.06%  |
| EFI  | 166      | 32.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 366      | 71.76%  |
| Btrfs   | 53       | 10.39%  |
| Overlay | 44       | 8.63%   |
| Unknown | 22       | 4.31%   |
| Tmpfs   | 11       | 2.16%   |
| Xfs     | 10       | 1.96%   |
| Zfs     | 2        | 0.39%   |
| F2fs    | 1        | 0.2%    |
| Aufs    | 1        | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 299      | 58.51%  |
| GPT     | 151      | 29.55%  |
| MBR     | 61       | 11.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 412      | 82.9%   |
| Yes       | 85       | 17.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 351      | 69.78%  |
| Yes       | 152      | 30.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 175      | 35.86%  |
| MSI                                  | 70       | 14.34%  |
| Gigabyte Technology                  | 63       | 12.91%  |
| Hewlett-Packard                      | 39       | 7.99%   |
| ASRock                               | 29       | 5.94%   |
| Dell                                 | 20       | 4.1%    |
| Acer                                 | 12       | 2.46%   |
| Lenovo                               | 10       | 2.05%   |
| Intel                                | 9        | 1.84%   |
| Fujitsu                              | 8        | 1.64%   |
| Foxconn                              | 8        | 1.64%   |
| Pegatron                             | 4        | 0.82%   |
| Unknown                              | 4        | 0.82%   |
| eMachines                            | 3        | 0.61%   |
| Biostar                              | 3        | 0.61%   |
| OEM                                  | 2        | 0.41%   |
| Minix                                | 2        | 0.41%   |
| Medion                               | 2        | 0.41%   |
| Huanan                               | 2        | 0.41%   |
| ECS                                  | 2        | 0.41%   |
| ABIT                                 | 2        | 0.41%   |
| Vorke                                | 1        | 0.2%    |
| Shuttle                              | 1        | 0.2%    |
| Shenzhen Meigao Electronic Equipment | 1        | 0.2%    |
| RKM                                  | 1        | 0.2%    |
| Packard Bell                         | 1        | 0.2%    |
| NEC Computers                        | 1        | 0.2%    |
| MACHINIST                            | 1        | 0.2%    |
| Libretrend                           | 1        | 0.2%    |
| JGINYUE                              | 1        | 0.2%    |
| IBM                                  | 1        | 0.2%    |
| Google                               | 1        | 0.2%    |
| GIADA                                | 1        | 0.2%    |
| BESSTAR Tech                         | 1        | 0.2%    |
| BCM                                  | 1        | 0.2%    |
| ASRockRack                           | 1        | 0.2%    |
| Apple                                | 1        | 0.2%    |
| AMI                                  | 1        | 0.2%    |
| Acidanthera                          | 1        | 0.2%    |
| AAEON                                | 1        | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 17       | 3.48%   |
| MSI MS-7817                        | 5        | 1.02%   |
| ASUS P5G41T-M LX                   | 5        | 1.02%   |
| ASUS H110M-K                       | 5        | 1.02%   |
| Unknown                            | 5        | 1.02%   |
| HP Compaq Elite 8300 SFF           | 4        | 0.82%   |
| ASUS M5A78L-M/USB3                 | 4        | 0.82%   |
| MSI MS-7C95                        | 3        | 0.61%   |
| MSI MS-7C91                        | 3        | 0.61%   |
| MSI MS-7C56                        | 3        | 0.61%   |
| MSI MS-7B89                        | 3        | 0.61%   |
| MSI MS-7A38                        | 3        | 0.61%   |
| Gigabyte GA-78LMT-USB3 6.0         | 3        | 0.61%   |
| Gigabyte B550 AORUS ELITE          | 3        | 0.61%   |
| Gigabyte B450M DS3H                | 3        | 0.61%   |
| ASUS PRIME H510M-K                 | 3        | 0.61%   |
| ASUS PRIME B450-PLUS               | 3        | 0.61%   |
| ASUS PRIME B350-PLUS               | 3        | 0.61%   |
| ASUS PRIME A320M-K                 | 3        | 0.61%   |
| ASUS P8H61-M LX R2.0               | 3        | 0.61%   |
| MSI MS-7C75                        | 2        | 0.41%   |
| MSI MS-7C37                        | 2        | 0.41%   |
| MSI MS-7B17                        | 2        | 0.41%   |
| MSI MS-7A34                        | 2        | 0.41%   |
| MSI MS-7721                        | 2        | 0.41%   |
| MSI MS-7640                        | 2        | 0.41%   |
| MSI MS-7592                        | 2        | 0.41%   |
| Minix Z83-4                        | 2        | 0.41%   |
| HP EliteDesk 800 G1 TWR            | 2        | 0.41%   |
| HP Compaq dc7900 Small Form Factor | 2        | 0.41%   |
| HP Compaq dc7700 Small Form Factor | 2        | 0.41%   |
| HP Compaq 8000 Elite SFF PC        | 2        | 0.41%   |
| Gigabyte X570 I AORUS PRO WIFI     | 2        | 0.41%   |
| Gigabyte X470 AORUS ULTRA GAMING   | 2        | 0.41%   |
| Gigabyte H55M-S2H                  | 2        | 0.41%   |
| Gigabyte H110M-Gaming 3            | 2        | 0.41%   |
| Gigabyte G31M-ES2L                 | 2        | 0.41%   |
| Gigabyte B550 GAMING X V2          | 2        | 0.41%   |
| Gigabyte B450 AORUS ELITE          | 2        | 0.41%   |
| Gigabyte A520M H                   | 2        | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 29       | 5.94%   |
| HP Compaq              | 18       | 3.69%   |
| ASUS All               | 17       | 3.48%   |
| Dell OptiPlex          | 13       | 2.66%   |
| ASUS ROG               | 11       | 2.25%   |
| Acer Aspire            | 11       | 2.25%   |
| ASUS P5G41T-M          | 10       | 2.05%   |
| ASUS TUF               | 8        | 1.64%   |
| ASUS P8H61-M           | 7        | 1.43%   |
| Lenovo ThinkCentre     | 6        | 1.23%   |
| HP ProDesk             | 6        | 1.23%   |
| Gigabyte B550          | 6        | 1.23%   |
| Fujitsu ESPRIMO        | 6        | 1.23%   |
| MSI MS-7817            | 5        | 1.02%   |
| ASUS M5A78L-M          | 5        | 1.02%   |
| ASUS H110M-K           | 5        | 1.02%   |
| Unknown                | 5        | 1.02%   |
| Gigabyte B450M         | 4        | 0.82%   |
| Dell Precision         | 4        | 0.82%   |
| ASUS P8Z77-V           | 4        | 0.82%   |
| MSI MS-7C95            | 3        | 0.61%   |
| MSI MS-7C91            | 3        | 0.61%   |
| MSI MS-7C56            | 3        | 0.61%   |
| MSI MS-7B89            | 3        | 0.61%   |
| MSI MS-7A38            | 3        | 0.61%   |
| HP ProLiant            | 3        | 0.61%   |
| HP Pavilion            | 3        | 0.61%   |
| HP EliteDesk           | 3        | 0.61%   |
| Gigabyte X570          | 3        | 0.61%   |
| Gigabyte GA-78LMT-USB3 | 3        | 0.61%   |
| Gigabyte B450          | 3        | 0.61%   |
| ASUS P5Q               | 3        | 0.61%   |
| ASUS P5KPL-AM          | 3        | 0.61%   |
| ASUS A                 | 3        | 0.61%   |
| MSI MS-7C75            | 2        | 0.41%   |
| MSI MS-7C37            | 2        | 0.41%   |
| MSI MS-7B17            | 2        | 0.41%   |
| MSI MS-7A34            | 2        | 0.41%   |
| MSI MS-7721            | 2        | 0.41%   |
| MSI MS-7640            | 2        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 50       | 10.25%  |
| 2020 | 47       | 9.63%   |
| 2012 | 45       | 9.22%   |
| 2009 | 36       | 7.38%   |
| 2010 | 35       | 7.17%   |
| 2019 | 28       | 5.74%   |
| 2014 | 28       | 5.74%   |
| 2013 | 26       | 5.33%   |
| 2011 | 25       | 5.12%   |
| 2021 | 23       | 4.71%   |
| 2008 | 23       | 4.71%   |
| 2017 | 22       | 4.51%   |
| 2015 | 21       | 4.3%    |
| 2006 | 20       | 4.1%    |
| 2016 | 19       | 3.89%   |
| 2007 | 17       | 3.48%   |
| 2022 | 9        | 1.84%   |
| 2005 | 7        | 1.43%   |
| 2023 | 3        | 0.61%   |
| 2004 | 3        | 0.61%   |
| 2003 | 1        | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 488      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 477      | 96.95%  |
| Enabled  | 15       | 3.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 486      | 99.59%  |
| Yes  | 2        | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 118      | 23.23%  |
| 3.01-4.0    | 108      | 21.26%  |
| 8.01-16.0   | 88       | 17.32%  |
| 4.01-8.0    | 64       | 12.6%   |
| 32.01-64.0  | 62       | 12.2%   |
| 1.01-2.0    | 22       | 4.33%   |
| 64.01-256.0 | 19       | 3.74%   |
| 24.01-32.0  | 13       | 2.56%   |
| 2.01-3.0    | 13       | 2.56%   |
| 0.51-1.0    | 1        | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 202      | 36.66%  |
| 2.01-3.0   | 119      | 21.6%   |
| 4.01-8.0   | 88       | 15.97%  |
| 3.01-4.0   | 59       | 10.71%  |
| 0.51-1.0   | 37       | 6.72%   |
| 8.01-16.0  | 29       | 5.26%   |
| 16.01-24.0 | 6        | 1.09%   |
| 0.01-0.5   | 6        | 1.09%   |
| 24.01-32.0 | 3        | 0.54%   |
| 32.01-64.0 | 1        | 0.18%   |
| Unknown    | 1        | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 192      | 37.43%  |
| 2      | 164      | 31.97%  |
| 3      | 76       | 14.81%  |
| 4      | 44       | 8.58%   |
| 5      | 14       | 2.73%   |
| 6      | 10       | 1.95%   |
| 0      | 8        | 1.56%   |
| 10     | 2        | 0.39%   |
| 7      | 2        | 0.39%   |
| 8      | 1        | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 279      | 56.59%  |
| Yes       | 214      | 43.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 486      | 99.59%  |
| No        | 2        | 0.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 313      | 62.73%  |
| Yes       | 186      | 37.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 377      | 75.4%   |
| Yes       | 123      | 24.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Portugal | 488      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Lisbon                  | 119      | 22.67%  |
| Porto                   | 39       | 7.43%   |
| Braga                   | 15       | 2.86%   |
| Leiria                  | 13       | 2.48%   |
| Setúbal                | 12       | 2.29%   |
| Coimbra                 | 12       | 2.29%   |
| Amadora                 | 11       | 2.1%    |
| Aveiro                  | 9        | 1.71%   |
| Vila Nova de Gaia       | 8        | 1.52%   |
| Portimao                | 7        | 1.33%   |
| Faro                    | 7        | 1.33%   |
| Torres Vedras           | 6        | 1.14%   |
| Quinta Do Conde         | 6        | 1.14%   |
| Amora                   | 6        | 1.14%   |
| Povoa de Santa Iria     | 5        | 0.95%   |
| Matosinhos Municipality | 5        | 0.95%   |
| Mafra                   | 5        | 0.95%   |
| Loures                  | 5        | 0.95%   |
| Evora                   | 5        | 0.95%   |
| Vila do Conde           | 4        | 0.76%   |
| Sintra                  | 4        | 0.76%   |
| Sao Domingos de Rana    | 4        | 0.76%   |
| Ponta Delgada           | 4        | 0.76%   |
| Montijo                 | 4        | 0.76%   |
| Guimaraes               | 4        | 0.76%   |
| Gondomar                | 4        | 0.76%   |
| Almada                  | 4        | 0.76%   |
| Trofa                   | 3        | 0.57%   |
| Senhora da Hora         | 3        | 0.57%   |
| Sao Joao da Madeira     | 3        | 0.57%   |
| Santarém               | 3        | 0.57%   |
| Quarteira               | 3        | 0.57%   |
| Póvoa de Varzim        | 3        | 0.57%   |
| Odivelas                | 3        | 0.57%   |
| Mem Martins             | 3        | 0.57%   |
| Funchal                 | 3        | 0.57%   |
| Covilha                 | 3        | 0.57%   |
| Chaves                  | 3        | 0.57%   |
| Cascais                 | 3        | 0.57%   |
| Beja                    | 3        | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 170      | 305    | 18.78%  |
| Seagate                   | 141      | 211    | 15.58%  |
| Samsung Electronics       | 123      | 194    | 13.59%  |
| Kingston                  | 99       | 148    | 10.94%  |
| Toshiba                   | 63       | 107    | 6.96%   |
| Crucial                   | 40       | 58     | 4.42%   |
| Hitachi                   | 35       | 44     | 3.87%   |
| Sandisk                   | 25       | 31     | 2.76%   |
| Maxtor                    | 18       | 25     | 1.99%   |
| Unknown                   | 12       | 15     | 1.33%   |
| GOODRAM                   | 12       | 16     | 1.33%   |
| PNY                       | 11       | 15     | 1.22%   |
| BlueRay                   | 10       | 13     | 1.1%    |
| Phison Electronics        | 9        | 10     | 0.99%   |
| KIOXIA-EXCERIA            | 8        | 16     | 0.88%   |
| China                     | 8        | 10     | 0.88%   |
| Phison                    | 7        | 13     | 0.77%   |
| Intel                     | 7        | 10     | 0.77%   |
| HGST                      | 6        | 12     | 0.66%   |
| Emtec                     | 6        | 7      | 0.66%   |
| S3+                       | 5        | 5      | 0.55%   |
| OCZ                       | 5        | 5      | 0.55%   |
| Micron/Crucial Technology | 5        | 6      | 0.55%   |
| KIOXIA                    | 5        | 7      | 0.55%   |
| Hewlett-Packard           | 5        | 6      | 0.55%   |
| ExcelStor                 | 5        | 5      | 0.55%   |
| Gigabyte Technology       | 4        | 4      | 0.44%   |
| Micron Technology         | 3        | 3      | 0.33%   |
| Fujitsu                   | 3        | 3      | 0.33%   |
| A-DATA Technology         | 3        | 3      | 0.33%   |
| XPG                       | 2        | 3      | 0.22%   |
| Vaseky                    | 2        | 2      | 0.22%   |
| Team                      | 2        | 2      | 0.22%   |
| SK hynix                  | 2        | 2      | 0.22%   |
| KingDian                  | 2        | 5      | 0.22%   |
| JMicron Technology        | 2        | 2      | 0.22%   |
| Intenso                   | 2        | 2      | 0.22%   |
| 2-Power                   | 2        | 3      | 0.22%   |
| Zheino                    | 1        | 2      | 0.11%   |
| XrayDisk                  | 1        | 2      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 25       | 2.48%   |
| Seagate ST1000DM010-2EP102 1TB                      | 17       | 1.68%   |
| Kingston SA400S37120G 120GB SSD                     | 13       | 1.29%   |
| Seagate ST3500418AS 500GB                           | 11       | 1.09%   |
| Seagate ST2000DM008-2FR102 2TB                      | 9        | 0.89%   |
| Samsung SSD 850 EVO 250GB                           | 9        | 0.89%   |
| Kingston SV300S37A240G 240GB SSD                    | 9        | 0.89%   |
| Kingston SV300S37A120G 120GB SSD                    | 8        | 0.79%   |
| Toshiba HDWD110 1TB                                 | 7        | 0.69%   |
| Samsung SSD 860 EVO 500GB                           | 7        | 0.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 7        | 0.69%   |
| Kingston SUV400S37120G 120GB SSD                    | 7        | 0.69%   |
| Kingston SA400S37480G 480GB SSD                     | 6        | 0.59%   |
| Crucial CT500MX500SSD1 500GB                        | 6        | 0.59%   |
| WDC WD20EARX-00PASB0 2TB                            | 5        | 0.5%    |
| WDC WD10EARS-00Y5B1 1TB                             | 5        | 0.5%    |
| WDC WD10EALX-009BA0 1TB                             | 5        | 0.5%    |
| Toshiba HDWD120 2TB                                 | 5        | 0.5%    |
| Toshiba DT01ACA050 500GB                            | 5        | 0.5%    |
| Seagate ST2000DM008-2UB102 2TB                      | 5        | 0.5%    |
| Samsung SSD 840 EVO 250GB                           | 5        | 0.5%    |
| Samsung HD502IJ 500GB                               | 5        | 0.5%    |
| Samsung HD161HJ 160GB                               | 5        | 0.5%    |
| Samsung HD103UJ 1TB                                 | 5        | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 4        | 0.4%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 4        | 0.4%    |
| WDC WD5000AAKX-60U6AA0 500GB                        | 4        | 0.4%    |
| WDC WD3200AAJS-00L7A0 320GB                         | 4        | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 4        | 0.4%    |
| WDC WD10EZEX-00BN5A0 1TB                            | 4        | 0.4%    |
| Toshiba DT01ACA100 1TB                              | 4        | 0.4%    |
| Seagate ST500DM002-1BD142 500GB                     | 4        | 0.4%    |
| Seagate ST3250820AS 250GB                           | 4        | 0.4%    |
| Seagate Expansion Desk 8TB                          | 4        | 0.4%    |
| Samsung SSD 860 QVO 1TB                             | 4        | 0.4%    |
| Samsung SSD 860 EVO 250GB                           | 4        | 0.4%    |
| Samsung SSD 840 Series 120GB                        | 4        | 0.4%    |
| Samsung NVMe SSD Drive 500GB                        | 4        | 0.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 4        | 0.4%    |
| Samsung HD502HJ 500GB                               | 4        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 148      | 252    | 32.82%  |
| Seagate             | 135      | 205    | 29.93%  |
| Toshiba             | 51       | 83     | 11.31%  |
| Samsung Electronics | 45       | 68     | 9.98%   |
| Hitachi             | 35       | 44     | 7.76%   |
| Maxtor              | 17       | 24     | 3.77%   |
| HGST                | 6        | 12     | 1.33%   |
| ExcelStor           | 5        | 5      | 1.11%   |
| Unknown             | 2        | 3      | 0.44%   |
| Fujitsu             | 2        | 2      | 0.44%   |
| TO Exter            | 1        | 1      | 0.22%   |
| Quantum             | 1        | 1      | 0.22%   |
| Hewlett-Packard     | 1        | 2      | 0.22%   |
| ASMedia             | 1        | 2      | 0.22%   |
| Apple               | 1        | 1      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 88       | 124    | 26.59%  |
| Samsung Electronics | 56       | 85     | 16.92%  |
| Crucial             | 35       | 52     | 10.57%  |
| WDC                 | 20       | 38     | 6.04%   |
| SanDisk             | 13       | 16     | 3.93%   |
| Toshiba             | 11       | 20     | 3.32%   |
| GOODRAM             | 10       | 14     | 3.02%   |
| PNY                 | 8        | 11     | 2.42%   |
| China               | 8        | 10     | 2.42%   |
| BlueRay             | 8        | 8      | 2.42%   |
| Emtec               | 6        | 7      | 1.81%   |
| S3+                 | 5        | 5      | 1.51%   |
| OCZ                 | 5        | 5      | 1.51%   |
| Intel               | 5        | 7      | 1.51%   |
| Unknown             | 4        | 4      | 1.21%   |
| Hewlett-Packard     | 4        | 4      | 1.21%   |
| KIOXIA-EXCERIA      | 3        | 10     | 0.91%   |
| Gigabyte Technology | 3        | 3      | 0.91%   |
| A-DATA Technology   | 3        | 3      | 0.91%   |
| Vaseky              | 2        | 2      | 0.6%    |
| Team                | 2        | 2      | 0.6%    |
| SK hynix            | 2        | 2      | 0.6%    |
| Seagate             | 2        | 2      | 0.6%    |
| Micron Technology   | 2        | 2      | 0.6%    |
| KingDian            | 2        | 5      | 0.6%    |
| JMicron Technology  | 2        | 2      | 0.6%    |
| Intenso             | 2        | 2      | 0.6%    |
| 2-Power             | 2        | 3      | 0.6%    |
| Zheino              | 1        | 2      | 0.3%    |
| XrayDisk            | 1        | 2      | 0.3%    |
| Transcend           | 1        | 1      | 0.3%    |
| Patriot             | 1        | 1      | 0.3%    |
| Netac               | 1        | 2      | 0.3%    |
| Mushkin             | 1        | 1      | 0.3%    |
| minisforum          | 1        | 1      | 0.3%    |
| Maxtor              | 1        | 1      | 0.3%    |
| LITEON              | 1        | 1      | 0.3%    |
| KIOXIA-E            | 1        | 1      | 0.3%    |
| KingSpec            | 1        | 1      | 0.3%    |
| INNOVATION IT       | 1        | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 341      | 705    | 46.52%  |
| SSD     | 268      | 470    | 36.56%  |
| NVMe    | 108      | 175    | 14.73%  |
| Unknown | 11       | 16     | 1.5%    |
| MMC     | 5        | 5      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 444      | 1157   | 76.55%  |
| NVMe | 108      | 175    | 18.62%  |
| SAS  | 23       | 34     | 3.97%   |
| MMC  | 5        | 5      | 0.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 367      | 744    | 59.39%  |
| 0.51-1.0   | 155      | 280    | 25.08%  |
| 1.01-2.0   | 57       | 88     | 9.22%   |
| 4.01-10.0  | 16       | 28     | 2.59%   |
| 2.01-3.0   | 14       | 18     | 2.27%   |
| 3.01-4.0   | 7        | 12     | 1.13%   |
| 10.01-20.0 | 1        | 4      | 0.16%   |
| 0          | 1        | 1      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 135      | 25.23%  |
| 251-500        | 100      | 18.69%  |
| 501-1000       | 68       | 12.71%  |
| 1001-2000      | 54       | 10.09%  |
| More than 3000 | 43       | 8.04%   |
| 1-20           | 39       | 7.29%   |
| 51-100         | 36       | 6.73%   |
| 2001-3000      | 26       | 4.86%   |
| 21-50          | 17       | 3.18%   |
| Unknown        | 17       | 3.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 209      | 38.14%  |
| 21-50          | 79       | 14.42%  |
| 101-250        | 54       | 9.85%   |
| 51-100         | 53       | 9.67%   |
| 251-500        | 40       | 7.3%    |
| 501-1000       | 39       | 7.12%   |
| 1001-2000      | 33       | 6.02%   |
| Unknown        | 17       | 3.1%    |
| More than 3000 | 12       | 2.19%   |
| 2001-3000      | 12       | 2.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB         | 3        | 3      | 3.9%    |
| WDC WD800JD-60LSA0 80GB           | 2        | 2      | 2.6%    |
| WDC WD3200AAJS-00L7A0 320GB       | 2        | 2      | 2.6%    |
| Toshiba MK2552GSX 250GB           | 2        | 2      | 2.6%    |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 2.6%    |
| Seagate ST3320413CS 320GB         | 2        | 2      | 2.6%    |
| Samsung Electronics HD252HJ 250GB | 2        | 2      | 2.6%    |
| WDC WD6400AADS-00M2B0 640GB       | 1        | 1      | 1.3%    |
| WDC WD5000LPCX-60VHAT0 500GB      | 1        | 1      | 1.3%    |
| WDC WD5000BPVT-22HXZT1 500GB      | 1        | 1      | 1.3%    |
| WDC WD5000AZRX-00A8LB0 500GB      | 1        | 1      | 1.3%    |
| WDC WD5000AZRX-00A3KB0 500GB      | 1        | 1      | 1.3%    |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 1.3%    |
| WDC WD5000AAKS-00V1A0 500GB       | 1        | 1      | 1.3%    |
| WDC WD5000AAKS-00A7B0 500GB       | 1        | 4      | 1.3%    |
| WDC WD5000AADS-00S9B0 500GB       | 1        | 1      | 1.3%    |
| WDC WD40EFRX-68WT0N0 4TB          | 1        | 2      | 1.3%    |
| WDC WD3200AAJS-07M0A0 320GB       | 1        | 1      | 1.3%    |
| WDC WD3200AAJS-00B4A0 320GB       | 1        | 1      | 1.3%    |
| WDC WD30EZRS-11J99B1 3TB          | 1        | 1      | 1.3%    |
| WDC WD2500JS-40TGB0 250GB         | 1        | 1      | 1.3%    |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 1.3%    |
| WDC WD15EARS-60MVWB0 1TB          | 1        | 1      | 1.3%    |
| WDC WD10EZRZ-00Z5HB0 1TB          | 1        | 1      | 1.3%    |
| WDC WD10EZEX-60WN4A0 1TB          | 1        | 1      | 1.3%    |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 1      | 1.3%    |
| WDC WD10EAVS-00D7B1 1TB           | 1        | 1      | 1.3%    |
| WDC WD10EAVS-00D7B0 1TB           | 1        | 1      | 1.3%    |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 1.3%    |
| WDC WD10EALX-009BA0 1TB           | 1        | 1      | 1.3%    |
| WDC WD10EADS-11M2B1 1TB           | 1        | 1      | 1.3%    |
| WDC WD1002FBYS-02A6B0 1TB         | 1        | 1      | 1.3%    |
| WDC WD1001FALS-00J7B0 1TB         | 1        | 4      | 1.3%    |
| Unknown FM-25S2S-60GBP2 64GB SSD  | 1        | 1      | 1.3%    |
| Toshiba MQ01ABD100 1TB            | 1        | 1      | 1.3%    |
| Toshiba MK3252GSX 320GB           | 1        | 2      | 1.3%    |
| Toshiba HDWD120 2TB               | 1        | 1      | 1.3%    |
| SK hynix SH920 2.5 7MM 512GB SSD  | 1        | 1      | 1.3%    |
| Seagate ST9500325AS 500GB         | 1        | 1      | 1.3%    |
| Seagate ST9250827AS 250GB         | 1        | 1      | 1.3%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 37     | 40.54%  |
| Seagate             | 13       | 15     | 17.57%  |
| Samsung Electronics | 6        | 8      | 8.11%   |
| Hitachi             | 6        | 7      | 8.11%   |
| Toshiba             | 5        | 6      | 6.76%   |
| Maxtor              | 4        | 7      | 5.41%   |
| Kingston            | 2        | 2      | 2.7%    |
| Crucial             | 2        | 3      | 2.7%    |
| Unknown             | 1        | 1      | 1.35%   |
| SK hynix            | 1        | 1      | 1.35%   |
| Patriot             | 1        | 1      | 1.35%   |
| KingDian            | 1        | 2      | 1.35%   |
| ExcelStor           | 1        | 1      | 1.35%   |
| China               | 1        | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 37     | 47.62%  |
| Seagate             | 13       | 15     | 20.63%  |
| Hitachi             | 6        | 7      | 9.52%   |
| Toshiba             | 5        | 6      | 7.94%   |
| Samsung Electronics | 4        | 5      | 6.35%   |
| Maxtor              | 4        | 7      | 6.35%   |
| ExcelStor           | 1        | 1      | 1.59%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 56       | 78     | 83.58%  |
| SSD  | 10       | 13     | 14.93%  |
| NVMe | 1        | 1      | 1.49%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Toshiba NVMe SSD Drive 256GB | 1        | 1      | 50%     |
| Seagate ST3750640NS 752GB    | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 331      | 916    | 59.96%  |
| Works    | 155      | 361    | 28.08%  |
| Malfunc  | 64       | 92     | 11.59%  |
| Failed   | 2        | 2      | 0.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 309      | 45.24%  |
| AMD                              | 153      | 22.4%   |
| Samsung Electronics              | 36       | 5.27%   |
| SanDisk                          | 22       | 3.22%   |
| JMicron Technology               | 22       | 3.22%   |
| ASMedia Technology               | 22       | 3.22%   |
| Phison Electronics               | 21       | 3.07%   |
| Kingston Technology Company      | 14       | 2.05%   |
| VIA Technologies                 | 13       | 1.9%    |
| Nvidia                           | 12       | 1.76%   |
| Marvell Technology Group         | 12       | 1.76%   |
| KIOXIA                           | 10       | 1.46%   |
| Micron/Crucial Technology        | 9        | 1.32%   |
| Silicon Integrated Systems [SiS] | 4        | 0.59%   |
| Shenzhen Longsys Electronics     | 4        | 0.59%   |
| LSI Logic / Symbios Logic        | 3        | 0.44%   |
| ADATA Technology                 | 3        | 0.44%   |
| Toshiba America Info Systems     | 2        | 0.29%   |
| Micron Technology                | 2        | 0.29%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.29%   |
| Adaptec                          | 2        | 0.29%   |
| Union Memory (Shenzhen)          | 1        | 0.15%   |
| ULi Electronics                  | 1        | 0.15%   |
| Silicon Motion                   | 1        | 0.15%   |
| Seagate Technology               | 1        | 0.15%   |
| Realtek Semiconductor            | 1        | 0.15%   |
| Hewlett-Packard                  | 1        | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 73       | 8.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 45       | 5.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 37       | 4.12%   |
| AMD 400 Series Chipset SATA Controller                                                  | 32       | 3.57%   |
| AMD 500 Series Chipset SATA Controller                                                  | 31       | 3.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 29       | 3.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 27       | 3.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 23       | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 21       | 2.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 19       | 2.12%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 19       | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 19       | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 18       | 2.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 17       | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 16       | 1.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15       | 1.67%   |
| Phison E12 NVMe Controller                                                              | 14       | 1.56%   |
| Intel SATA Controller [RAID mode]                                                       | 14       | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14       | 1.56%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 12       | 1.34%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12       | 1.34%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 10       | 1.11%   |
| AMD 300 Series Chipset SATA Controller                                                  | 10       | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 8        | 0.89%   |
| KIOXIA NVMe SSD                                                                         | 7        | 0.78%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7        | 0.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7        | 0.78%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 7        | 0.78%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 6        | 0.67%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 0.67%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 6        | 0.67%   |
| JMicron JMB368 IDE controller                                                           | 6        | 0.67%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6        | 0.67%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 6        | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6        | 0.67%   |
| AMD FCH SATA Controller D                                                               | 6        | 0.67%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5        | 0.56%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 5        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 346      | 51.8%   |
| IDE  | 175      | 26.2%   |
| NVMe | 109      | 16.32%  |
| RAID | 34       | 5.09%   |
| SCSI | 3        | 0.45%   |
| SAS  | 1        | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 329      | 67.42%  |
| AMD    | 159      | 32.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 12       | 2.45%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 10       | 2.04%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 9        | 1.84%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 8        | 1.63%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8        | 1.63%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 8        | 1.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 7        | 1.43%   |
| AMD FX-6300 Six-Core Processor              | 7        | 1.43%   |
| Intel Pentium 4 CPU 3.00GHz                 | 6        | 1.22%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 1.22%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 6        | 1.22%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 6        | 1.22%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 6        | 1.22%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 1.22%   |
| AMD FX-8320 Eight-Core Processor            | 6        | 1.22%   |
| Intel Pentium D CPU 3.00GHz                 | 4        | 0.82%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 0.82%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4        | 0.82%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 4        | 0.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 0.82%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 0.82%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 4        | 0.82%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 0.82%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 4        | 0.82%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 0.82%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 3        | 0.61%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 3        | 0.61%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.61%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 0.61%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.61%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 0.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 0.61%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 0.61%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 3        | 0.61%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 3        | 0.61%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 0.61%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 3        | 0.61%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 3        | 0.61%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 3        | 0.61%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 3        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 77       | 15.71%  |
| AMD Ryzen 5             | 51       | 10.41%  |
| Intel Core i7           | 47       | 9.59%   |
| Intel Core i3           | 35       | 7.14%   |
| AMD Ryzen 7             | 32       | 6.53%   |
| AMD FX                  | 27       | 5.51%   |
| Intel Xeon              | 24       | 4.9%    |
| Intel Core 2 Quad       | 24       | 4.9%    |
| Intel Core 2 Duo        | 18       | 3.67%   |
| Other                   | 17       | 3.47%   |
| Intel Pentium Dual-Core | 16       | 3.27%   |
| Intel Pentium 4         | 14       | 2.86%   |
| Intel Pentium           | 13       | 2.65%   |
| Intel Celeron           | 13       | 2.65%   |
| Intel Core 2            | 10       | 2.04%   |
| Intel Atom              | 8        | 1.63%   |
| Intel Pentium D         | 6        | 1.22%   |
| AMD Ryzen 9             | 6        | 1.22%   |
| AMD Ryzen 3             | 6        | 1.22%   |
| Intel Pentium Dual      | 5        | 1.02%   |
| AMD A10                 | 4        | 0.82%   |
| AMD Ryzen Threadripper  | 3        | 0.61%   |
| AMD Athlon II X3        | 3        | 0.61%   |
| AMD Athlon II X2        | 3        | 0.61%   |
| AMD Athlon 64           | 3        | 0.61%   |
| Intel Pentium Gold      | 2        | 0.41%   |
| Intel Core i9           | 2        | 0.41%   |
| AMD Phenom II X4        | 2        | 0.41%   |
| AMD E                   | 2        | 0.41%   |
| AMD Athlon              | 2        | 0.41%   |
| AMD A8                  | 2        | 0.41%   |
| AMD A6                  | 2        | 0.41%   |
| Intel Pentium Silver    | 1        | 0.2%    |
| Intel Genuine           | 1        | 0.2%    |
| AMD Sempron             | 1        | 0.2%    |
| AMD Ryzen 7 PRO         | 1        | 0.2%    |
| AMD Phenom II X6        | 1        | 0.2%    |
| AMD Phenom II X3        | 1        | 0.2%    |
| AMD Phenom              | 1        | 0.2%    |
| AMD Athlon X4           | 1        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 184      | 37.47%  |
| 2       | 132      | 26.88%  |
| 6       | 72       | 14.66%  |
| 8       | 46       | 9.37%   |
| 1       | 25       | 5.09%   |
| 3       | 14       | 2.85%   |
| 12      | 7        | 1.43%   |
| 16      | 6        | 1.22%   |
| 10      | 2        | 0.41%   |
| 24      | 1        | 0.2%    |
| 14      | 1        | 0.2%    |
| Unknown | 1        | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 482      | 98.77%  |
| 2      | 6        | 1.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 258      | 52.65%  |
| 1       | 231      | 47.14%  |
| Unknown | 1        | 0.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 474      | 95.95%  |
| Unknown        | 15       | 3.04%   |
| 32-bit         | 4        | 0.81%   |
| 64-bit         | 1        | 0.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 156      | 29.89%  |
| 0x1067a    | 31       | 5.94%   |
| 0x306c3    | 24       | 4.6%    |
| 0x306a9    | 24       | 4.6%    |
| 0x206a7    | 23       | 4.41%   |
| 0x06000852 | 17       | 3.26%   |
| 0x506e3    | 15       | 2.87%   |
| 0x08701021 | 15       | 2.87%   |
| 0x906ea    | 13       | 2.49%   |
| 0x0800820d | 13       | 2.49%   |
| 0x6fb      | 10       | 1.92%   |
| 0x906e9    | 9        | 1.72%   |
| 0x106e5    | 6        | 1.15%   |
| 0x10676    | 6        | 1.15%   |
| 0xa0655    | 5        | 0.96%   |
| 0x10677    | 5        | 0.96%   |
| 0x08701030 | 5        | 0.96%   |
| 0x010000c8 | 5        | 0.96%   |
| 0xf43      | 4        | 0.77%   |
| 0xf41      | 4        | 0.77%   |
| 0xa0671    | 4        | 0.77%   |
| 0x6fd      | 4        | 0.77%   |
| 0x6f6      | 4        | 0.77%   |
| 0x6f2      | 4        | 0.77%   |
| 0x0a20120a | 4        | 0.77%   |
| 0x0a201016 | 4        | 0.77%   |
| 0x08101016 | 4        | 0.77%   |
| 0x08001137 | 4        | 0.77%   |
| 0x06000822 | 4        | 0.77%   |
| 0xf65      | 3        | 0.57%   |
| 0x906eb    | 3        | 0.57%   |
| 0x406c4    | 3        | 0.57%   |
| 0x30678    | 3        | 0.57%   |
| 0x206d7    | 3        | 0.57%   |
| 0x08701013 | 3        | 0.57%   |
| 0x0800820b | 3        | 0.57%   |
| 0x08001129 | 3        | 0.57%   |
| 0xf64      | 2        | 0.38%   |
| 0xf62      | 2        | 0.38%   |
| 0xf4a      | 2        | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 51       | 10.41%  |
| Haswell          | 44       | 8.98%   |
| KabyLake         | 39       | 7.96%   |
| Core             | 34       | 6.94%   |
| IvyBridge        | 33       | 6.73%   |
| Zen 2            | 31       | 6.33%   |
| SandyBridge      | 27       | 5.51%   |
| Piledriver       | 26       | 5.31%   |
| Zen 3            | 24       | 4.9%    |
| Zen+             | 23       | 4.69%   |
| Skylake          | 22       | 4.49%   |
| NetBurst         | 22       | 4.49%   |
| Zen              | 20       | 4.08%   |
| K10              | 13       | 2.65%   |
| Unknown          | 10       | 2.04%   |
| Nehalem          | 9        | 1.84%   |
| CometLake        | 9        | 1.84%   |
| Silvermont       | 8        | 1.63%   |
| Westmere         | 7        | 1.43%   |
| K8 Hammer        | 5        | 1.02%   |
| Excavator        | 5        | 1.02%   |
| Alderlake Hybrid | 5        | 1.02%   |
| Steamroller      | 4        | 0.82%   |
| Icelake          | 4        | 0.82%   |
| Bonnell          | 4        | 0.82%   |
| Bulldozer        | 3        | 0.61%   |
| Tremont          | 2        | 0.41%   |
| Goldmont         | 2        | 0.41%   |
| Bobcat           | 2        | 0.41%   |
| Puma             | 1        | 0.2%    |
| Goldmont plus    | 1        | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 195      | 37.36%  |
| AMD                              | 174      | 33.33%  |
| Intel                            | 148      | 28.35%  |
| Silicon Integrated Systems [SiS] | 2        | 0.38%   |
| Matrox Electronics Systems       | 2        | 0.38%   |
| ASPEED Technology                | 1        | 0.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 33       | 6.15%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 23       | 4.28%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 18       | 3.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 18       | 3.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 14       | 2.61%   |
| Nvidia GT218 [GeForce 210]                                                               | 13       | 2.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12       | 2.23%   |
| Intel HD Graphics 530                                                                    | 11       | 2.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11       | 2.05%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9        | 1.68%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 8        | 1.49%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 8        | 1.49%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 7        | 1.3%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 7        | 1.3%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6        | 1.12%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 6        | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6        | 1.12%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 6        | 1.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 5        | 0.93%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 5        | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 0.93%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 5        | 0.93%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5        | 0.93%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 0.93%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 4        | 0.74%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 4        | 0.74%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4        | 0.74%   |
| AMD RV730 PRO [Radeon HD 4650]                                                           | 4        | 0.74%   |
| AMD RS780L [Radeon 3000]                                                                 | 4        | 0.74%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 4        | 0.74%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 4        | 0.74%   |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 4        | 0.74%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 3        | 0.56%   |
| Nvidia GT216 [GeForce 315]                                                               | 3        | 0.56%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 3        | 0.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3        | 0.56%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3        | 0.56%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 3        | 0.56%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 3        | 0.56%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 183      | 36.67%  |
| 1 x AMD         | 162      | 32.46%  |
| 1 x Intel       | 128      | 25.65%  |
| 2 x AMD         | 8        | 1.6%    |
| Intel + Nvidia  | 4        | 0.8%    |
| AMD + Nvidia    | 3        | 0.6%    |
| 2 x Nvidia      | 2        | 0.4%    |
| 2 x Intel       | 2        | 0.4%    |
| 1 x SiS         | 2        | 0.4%    |
| Other           | 1        | 0.2%    |
| Nvidia + Matrox | 1        | 0.2%    |
| Nvidia + ASPEED | 1        | 0.2%    |
| 1 x Matrox      | 1        | 0.2%    |
| Intel + AMD     | 1        | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 363      | 72.75%  |
| Proprietary | 109      | 21.84%  |
| Unknown     | 27       | 5.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 221      | 43.33%  |
| 0.51-1.0   | 63       | 12.35%  |
| 1.01-2.0   | 59       | 11.57%  |
| 0.01-0.5   | 59       | 11.57%  |
| 3.01-4.0   | 45       | 8.82%   |
| 7.01-8.0   | 35       | 6.86%   |
| 8.01-16.0  | 14       | 2.75%   |
| 5.01-6.0   | 10       | 1.96%   |
| 2.01-3.0   | 4        | 0.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 98       | 19.25%  |
| Goldstar             | 82       | 16.11%  |
| Ancor Communications | 59       | 11.59%  |
| Hewlett-Packard      | 55       | 10.81%  |
| AOC                  | 26       | 5.11%   |
| Dell                 | 22       | 4.32%   |
| BenQ                 | 20       | 3.93%   |
| Philips              | 18       | 3.54%   |
| ASUSTek Computer     | 13       | 2.55%   |
| LG Electronics       | 10       | 1.96%   |
| Lenovo               | 10       | 1.96%   |
| Acer                 | 10       | 1.96%   |
| Unknown              | 8        | 1.57%   |
| Sony                 | 8        | 1.57%   |
| ViewSonic            | 4        | 0.79%   |
| Gigabyte Technology  | 4        | 0.79%   |
| Fujitsu Siemens      | 4        | 0.79%   |
| Vestel Elektronik    | 3        | 0.59%   |
| HPN                  | 3        | 0.59%   |
| AVX                  | 3        | 0.59%   |
| Apple                | 3        | 0.59%   |
| ___                  | 2        | 0.39%   |
| Targa Visionary      | 2        | 0.39%   |
| Mi                   | 2        | 0.39%   |
| Lenovo Group Limited | 2        | 0.39%   |
| Iiyama               | 2        | 0.39%   |
| HUAWEI               | 2        | 0.39%   |
| AUS                  | 2        | 0.39%   |
| Unknown              | 2        | 0.39%   |
| Vestel               | 1        | 0.2%    |
| Toshiba              | 1        | 0.2%    |
| TEO                  | 1        | 0.2%    |
| TCL                  | 1        | 0.2%    |
| TAR                  | 1        | 0.2%    |
| STN                  | 1        | 0.2%    |
| Skyworth             | 1        | 0.2%    |
| S2-Tek               | 1        | 0.2%    |
| RTK                  | 1        | 0.2%    |
| Plain Tree Systems   | 1        | 0.2%    |
| Packard Bell         | 1        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 5        | 0.93%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch       | 5        | 0.93%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 4        | 0.74%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                 | 4        | 0.74%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch  | 4        | 0.74%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch   | 4        | 0.74%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch  | 4        | 0.74%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 3        | 0.56%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 3        | 0.56%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 3        | 0.56%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 3        | 0.56%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch  | 3        | 0.56%   |
| Goldstar M227WD GSM56D5 1920x1080 480x270mm 21.7-inch                  | 3        | 0.56%   |
| Goldstar L1919S GSM4AF0 1280x1024 376x301mm 19.0-inch                  | 3        | 0.56%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                 | 3        | 0.56%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                    | 3        | 0.56%   |
| AVX AVT GC513 AVX0034 1920x1080 698x392mm 31.5-inch                    | 3        | 0.56%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 3        | 0.56%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                        | 3        | 0.56%   |
| Ancor Communications VX228 ACI22C1 1920x1080 476x268mm 21.5-inch       | 3        | 0.56%   |
| Ancor Communications VE228 ACI22FA 1920x1080 480x270mm 21.7-inch       | 3        | 0.56%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 3        | 0.56%   |
| Ancor Communications ASUS VH197 ACI19EB 1366x768 410x230mm 18.5-inch   | 3        | 0.56%   |
| Ancor Communications ASUS 22T1E ACI22F4 1920x1080 477x268mm 21.5-inch  | 3        | 0.56%   |
| Acer KA270H ACR0522 1920x1080 598x336mm 27.0-inch                      | 3        | 0.56%   |
| ___ LCD TV ___0101 1920x1080                                           | 2        | 0.37%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 2        | 0.37%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                    | 2        | 0.37%   |
| Sony SDM-HS93 SNY1190 1280x1024 357x286mm 18.0-inch                    | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch   | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM037A 1680x1050 433x271mm 20.1-inch   | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch    | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM0301 1680x1050 459x296mm 21.5-inch   | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM0230 1280x1024 376x301mm 19.0-inch   | 2        | 0.37%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 2        | 0.37%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 2        | 0.37%   |
| Samsung Electronics LCD Monitor SyncMaster 1440x900                    | 2        | 0.37%   |
| Samsung Electronics LCD Monitor SAM0992 1920x1080 890x500mm 40.2-inch  | 2        | 0.37%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 890x500mm 40.2-inch  | 2        | 0.37%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 2        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 223      | 44.42%  |
| 1280x1024 (SXGA)   | 64       | 12.75%  |
| 3840x2160 (4K)     | 50       | 9.96%   |
| 2560x1440 (QHD)    | 28       | 5.58%   |
| 1680x1050 (WSXGA+) | 25       | 4.98%   |
| 1440x900 (WXGA+)   | 22       | 4.38%   |
| 1366x768 (WXGA)    | 18       | 3.59%   |
| 1600x900 (HD+)     | 11       | 2.19%   |
| Unknown            | 10       | 1.99%   |
| 1920x1200 (WUXGA)  | 9        | 1.79%   |
| 1360x768           | 9        | 1.79%   |
| 3840x1080          | 6        | 1.2%    |
| 2560x1080          | 6        | 1.2%    |
| 1024x768 (XGA)     | 5        | 1%      |
| 3440x1440          | 3        | 0.6%    |
| 1920x540           | 3        | 0.6%    |
| 1152x864           | 3        | 0.6%    |
| 4560x1080          | 1        | 0.2%    |
| 4480x1600          | 1        | 0.2%    |
| 3360x1080          | 1        | 0.2%    |
| 3360x1050          | 1        | 0.2%    |
| 2944x1080          | 1        | 0.2%    |
| 2560x2520          | 1        | 0.2%    |
| 1400x1050          | 1        | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 76       | 14.81%  |
| 24      | 68       | 13.26%  |
| 23      | 54       | 10.53%  |
| Unknown | 52       | 10.14%  |
| 27      | 49       | 9.55%   |
| 19      | 41       | 7.99%   |
| 17      | 33       | 6.43%   |
| 18      | 27       | 5.26%   |
| 20      | 18       | 3.51%   |
| 31      | 16       | 3.12%   |
| 15      | 13       | 2.53%   |
| 84      | 9        | 1.75%   |
| 22      | 9        | 1.75%   |
| 34      | 7        | 1.36%   |
| 54      | 6        | 1.17%   |
| 40      | 4        | 0.78%   |
| 33      | 4        | 0.78%   |
| 32      | 4        | 0.78%   |
| 28      | 4        | 0.78%   |
| 72      | 3        | 0.58%   |
| 46      | 3        | 0.58%   |
| 25      | 3        | 0.58%   |
| 48      | 2        | 0.39%   |
| 42      | 2        | 0.39%   |
| 58      | 1        | 0.19%   |
| 39      | 1        | 0.19%   |
| 26      | 1        | 0.19%   |
| 16      | 1        | 0.19%   |
| 12      | 1        | 0.19%   |
| 10      | 1        | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 156      | 31.26%  |
| 401-500     | 145      | 29.06%  |
| Unknown     | 52       | 10.42%  |
| 301-350     | 47       | 9.42%   |
| 601-700     | 26       | 5.21%   |
| 351-400     | 25       | 5.01%   |
| 701-800     | 15       | 3.01%   |
| 1501-2000   | 12       | 2.4%    |
| 1001-1500   | 12       | 2.4%    |
| 801-900     | 5        | 1%      |
| 201-300     | 2        | 0.4%    |
| 901-1000    | 2        | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 292      | 60.96%  |
| 5/4     | 54       | 11.27%  |
| 16/10   | 52       | 10.86%  |
| Unknown | 46       | 9.6%    |
| 4/3     | 17       | 3.55%   |
| 21/9    | 9        | 1.88%   |
| 3/2     | 4        | 0.84%   |
| 6/5     | 3        | 0.63%   |
| 32/9    | 2        | 0.42%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 175      | 34.79%  |
| 151-200        | 71       | 14.12%  |
| 141-150        | 56       | 11.13%  |
| Unknown        | 52       | 10.34%  |
| 301-350        | 50       | 9.94%   |
| 351-500        | 32       | 6.36%   |
| More than 1000 | 20       | 3.98%   |
| 251-300        | 20       | 3.98%   |
| 501-1000       | 11       | 2.19%   |
| 111-120        | 7        | 1.39%   |
| 101-110        | 6        | 1.19%   |
| 71-80          | 1        | 0.2%    |
| 41-50          | 1        | 0.2%    |
| 131-140        | 1        | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 295      | 61.59%  |
| 101-120 | 96       | 20.04%  |
| Unknown | 52       | 10.86%  |
| 1-50    | 14       | 2.92%   |
| 121-160 | 14       | 2.92%   |
| 161-240 | 8        | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 392      | 77.62%  |
| 2     | 63       | 12.48%  |
| 0     | 42       | 8.32%   |
| 3     | 7        | 1.39%   |
| 4     | 1        | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 312      | 47.78%  |
| Intel                                 | 150      | 22.97%  |
| Qualcomm Atheros                      | 52       | 7.96%   |
| TP-Link                               | 21       | 3.22%   |
| Broadcom                              | 19       | 2.91%   |
| Qualcomm Atheros Communications       | 16       | 2.45%   |
| Nvidia                                | 12       | 1.84%   |
| Ralink Technology                     | 8        | 1.23%   |
| Marvell Technology Group              | 6        | 0.92%   |
| VIA Technologies                      | 5        | 0.77%   |
| D-Link                                | 5        | 0.77%   |
| Silicon Integrated Systems [SiS]      | 4        | 0.61%   |
| MediaTek                              | 4        | 0.61%   |
| ASUSTek Computer                      | 4        | 0.61%   |
| Samsung Electronics                   | 3        | 0.46%   |
| Ralink                                | 3        | 0.46%   |
| Edimax Technology                     | 3        | 0.46%   |
| D-Link System                         | 3        | 0.46%   |
| Broadcom Limited                      | 3        | 0.46%   |
| ADMtek                                | 3        | 0.46%   |
| Microsoft                             | 2        | 0.31%   |
| Huawei Technologies                   | 2        | 0.31%   |
| Accton Technology                     | 2        | 0.31%   |
| TRENDnet                              | 1        | 0.15%   |
| Smart Link                            | 1        | 0.15%   |
| Sitecom Europe                        | 1        | 0.15%   |
| Motorola                              | 1        | 0.15%   |
| Mellanox Technologies                 | 1        | 0.15%   |
| Dresden Elektronik                    | 1        | 0.15%   |
| dog hunter                            | 1        | 0.15%   |
| Belkin Components                     | 1        | 0.15%   |
| ASIX Electronics                      | 1        | 0.15%   |
| Apple                                 | 1        | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 259      | 35.63%  |
| Realtek RTL8125 2.5GbE Controller                                                    | 22       | 3.03%   |
| Intel I211 Gigabit Network Connection                                                | 21       | 2.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 14       | 1.93%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 12       | 1.65%   |
| Intel Ethernet Connection (2) I219-V                                                 | 12       | 1.65%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 9        | 1.24%   |
| Intel Wi-Fi 6 AX200                                                                  | 9        | 1.24%   |
| Intel 82579V Gigabit Network Connection                                              | 9        | 1.24%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 8        | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 8        | 1.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 8        | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                | 8        | 1.1%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                             | 8        | 1.1%    |
| Intel 82567LM-3 Gigabit Network Connection                                           | 8        | 1.1%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 7        | 0.96%   |
| Intel Ethernet Connection (2) I218-V                                                 | 7        | 0.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 6        | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 6        | 0.83%   |
| Nvidia MCP61 Ethernet                                                                | 6        | 0.83%   |
| Intel Ethernet Controller I225-V                                                     | 6        | 0.83%   |
| Intel Ethernet Connection I217-LM                                                    | 6        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                                                 | 6        | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 6        | 0.83%   |
| Ralink MT7601U Wireless Adapter                                                      | 5        | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                       | 5        | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                                | 5        | 0.69%   |
| VIA VT6102/VT6103 [Rhine-II]                                                         | 4        | 0.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 4        | 0.55%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 4        | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 4        | 0.55%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 4        | 0.55%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                        | 4        | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 4        | 0.55%   |
| Intel Wireless 7265                                                                  | 4        | 0.55%   |
| Intel Ethernet Connection I217-V                                                     | 4        | 0.55%   |
| Intel Ethernet Connection (14) I219-V                                                | 4        | 0.55%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                              | 4        | 0.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 3        | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                      | 3        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 51       | 26.84%  |
| Intel                                 | 38       | 20%     |
| Qualcomm Atheros                      | 26       | 13.68%  |
| TP-Link                               | 20       | 10.53%  |
| Qualcomm Atheros Communications       | 16       | 8.42%   |
| Ralink Technology                     | 8        | 4.21%   |
| D-Link                                | 5        | 2.63%   |
| MediaTek                              | 4        | 2.11%   |
| Broadcom                              | 4        | 2.11%   |
| ASUSTek Computer                      | 4        | 2.11%   |
| Ralink                                | 3        | 1.58%   |
| Edimax Technology                     | 3        | 1.58%   |
| Microsoft                             | 2        | 1.05%   |
| TRENDnet                              | 1        | 0.53%   |
| Sitecom Europe                        | 1        | 0.53%   |
| Broadcom Limited                      | 1        | 0.53%   |
| Belkin Components                     | 1        | 0.53%   |
| Accton Technology                     | 1        | 0.53%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.53%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                                      | 12       | 6.28%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 9        | 4.71%   |
| Intel Wi-Fi 6 AX200                                                                  | 9        | 4.71%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 8        | 4.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 8        | 4.19%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 7        | 3.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 6        | 3.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 6        | 3.14%   |
| Ralink MT7601U Wireless Adapter                                                      | 5        | 2.62%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 4        | 2.09%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 4        | 2.09%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 4        | 2.09%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 4        | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 4        | 2.09%   |
| Intel Wireless 7265                                                                  | 4        | 2.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 3        | 1.57%   |
| Realtek 802.11ac NIC                                                                 | 3        | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 3        | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 3        | 1.57%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                | 2        | 1.05%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 2        | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 2        | 1.05%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 1.05%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                | 2        | 1.05%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 2        | 1.05%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                             | 2        | 1.05%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 2        | 1.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 2        | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 2        | 1.05%   |
| Intel Wireless-AC 9260                                                               | 2        | 1.05%   |
| Intel Wireless 8260                                                                  | 2        | 1.05%   |
| Intel Wireless 3165                                                                  | 2        | 1.05%   |
| Intel Wireless 3160                                                                  | 2        | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 2        | 1.05%   |
| Intel 700 Series Chipset Family Wi-Fi                                                | 2        | 1.05%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                       | 2        | 1.05%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                         | 2        | 1.05%   |
| ASUS USB-N10 802.11n Network Adapter [Realtek RTL8188SU]                             | 2        | 1.05%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]           | 1        | 0.52%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1        | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 294      | 57.31%  |
| Intel                            | 130      | 25.34%  |
| Qualcomm Atheros                 | 30       | 5.85%   |
| Broadcom                         | 15       | 2.92%   |
| Nvidia                           | 12       | 2.34%   |
| Marvell Technology Group         | 6        | 1.17%   |
| VIA Technologies                 | 5        | 0.97%   |
| Silicon Integrated Systems [SiS] | 4        | 0.78%   |
| D-Link System                    | 3        | 0.58%   |
| ADMtek                           | 3        | 0.58%   |
| Samsung Electronics              | 2        | 0.39%   |
| Huawei Technologies              | 2        | 0.39%   |
| Broadcom Limited                 | 2        | 0.39%   |
| TP-Link                          | 1        | 0.19%   |
| Mellanox Technologies            | 1        | 0.19%   |
| ASIX Electronics                 | 1        | 0.19%   |
| Apple                            | 1        | 0.19%   |
| Accton Technology                | 1        | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 259      | 48.78%  |
| Realtek RTL8125 2.5GbE Controller                                 | 22       | 4.14%   |
| Intel I211 Gigabit Network Connection                             | 21       | 3.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14       | 2.64%   |
| Intel Ethernet Connection (2) I219-V                              | 12       | 2.26%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 1.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8        | 1.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8        | 1.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8        | 1.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8        | 1.51%   |
| Intel Ethernet Connection (2) I218-V                              | 7        | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6        | 1.13%   |
| Nvidia MCP61 Ethernet                                             | 6        | 1.13%   |
| Intel Ethernet Controller I225-V                                  | 6        | 1.13%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 1.13%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 1.13%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5        | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 5        | 0.94%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 0.75%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4        | 0.75%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.75%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 0.75%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 4        | 0.75%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.56%   |
| Nvidia MCP73 Ethernet                                             | 3        | 0.56%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 0.56%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 3        | 0.56%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 3        | 0.56%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100              | 3        | 0.56%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 2        | 0.38%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.38%   |
| Nvidia MCP79 Ethernet                                             | 2        | 0.38%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2        | 0.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.38%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 0.38%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.38%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 486      | 72%     |
| WiFi     | 184      | 27.26%  |
| Modem    | 5        | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 390      | 76.17%  |
| WiFi     | 122      | 23.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 355      | 72.3%   |
| 2     | 119      | 24.24%  |
| 3     | 12       | 2.44%   |
| 5     | 2        | 0.41%   |
| 6     | 1        | 0.2%    |
| 4     | 1        | 0.2%    |
| 0     | 1        | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 368      | 73.02%  |
| Yes  | 136      | 26.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 38       | 29.92%  |
| Intel                           | 36       | 28.35%  |
| ASUSTek Computer                | 24       | 18.9%   |
| Realtek Semiconductor           | 12       | 9.45%   |
| MediaTek                        | 4        | 3.15%   |
| TP-Link                         | 3        | 2.36%   |
| IMC Networks                    | 2        | 1.57%   |
| Broadcom                        | 2        | 1.57%   |
| Belkin Components               | 2        | 1.57%   |
| Toshiba                         | 1        | 0.79%   |
| Qualcomm Atheros Communications | 1        | 0.79%   |
| Integrated System Solution      | 1        | 0.79%   |
| Apple                           | 1        | 0.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 38       | 29.92%  |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 16       | 12.6%   |
| Intel AX200 Bluetooth                                 | 10       | 7.87%   |
| Intel Bluetooth wireless interface                    | 9        | 7.09%   |
| Realtek Bluetooth Radio                               | 8        | 6.3%    |
| Intel Wireless-AC 3168 Bluetooth                      | 6        | 4.72%   |
| Realtek  Bluetooth 4.2 Adapter                        | 4        | 3.15%   |
| MediaTek Wireless_Device                              | 4        | 3.15%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 4        | 3.15%   |
| ASUS Bluetooth Device                                 | 4        | 3.15%   |
| TP-Link UB500 Adapter                                 | 3        | 2.36%   |
| Intel Bluetooth Device                                | 3        | 2.36%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 2        | 1.57%   |
| Intel AX210 Bluetooth                                 | 2        | 1.57%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 1.57%   |
| Toshiba Atheros AR3012 Bluetooth                      | 1        | 0.79%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.79%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 0.79%   |
| IMC Networks Wireless_Device                          | 1        | 0.79%   |
| IMC Networks Bluetooth Device                         | 1        | 0.79%   |
| Belkin Components Bluetooth Mini Dongle               | 1        | 0.79%   |
| Belkin Components Bluetooth Device with trace filter  | 1        | 0.79%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 0.79%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.79%   |
| ASUS Bluetooth Radio                                  | 1        | 0.79%   |
| ASUS Bluetooth Adapter                                | 1        | 0.79%   |
| Apple Bluetooth HCI                                   | 1        | 0.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 298      | 36.39%  |
| AMD                                  | 222      | 27.11%  |
| Nvidia                               | 176      | 21.49%  |
| Creative Labs                        | 20       | 2.44%   |
| C-Media Electronics                  | 20       | 2.44%   |
| Logitech                             | 11       | 1.34%   |
| Kingston Technology                  | 10       | 1.22%   |
| JMTek                                | 8        | 0.98%   |
| Texas Instruments                    | 7        | 0.85%   |
| Razer USA                            | 7        | 0.85%   |
| ASUSTek Computer                     | 5        | 0.61%   |
| Silicon Integrated Systems [SiS]     | 4        | 0.49%   |
| Focusrite-Novation                   | 3        | 0.37%   |
| VIA Technologies                     | 2        | 0.24%   |
| SteelSeries ApS                      | 2        | 0.24%   |
| Micro Star International             | 2        | 0.24%   |
| Hewlett-Packard                      | 2        | 0.24%   |
| WinChipHead                          | 1        | 0.12%   |
| ULi Electronics                      | 1        | 0.12%   |
| Turtle Beach                         | 1        | 0.12%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.12%   |
| Samsung Electronics                  | 1        | 0.12%   |
| Samson Technologies                  | 1        | 0.12%   |
| Realtek Semiconductor                | 1        | 0.12%   |
| Plantronics                          | 1        | 0.12%   |
| Philips (or NXP)                     | 1        | 0.12%   |
| Microchip Technology                 | 1        | 0.12%   |
| Harman                               | 1        | 0.12%   |
| Guillemot                            | 1        | 0.12%   |
| Generalplus Technology               | 1        | 0.12%   |
| Evolution Electronics                | 1        | 0.12%   |
| EGO SYStems                          | 1        | 0.12%   |
| DSEA A/S                             | 1        | 0.12%   |
| Corsair                              | 1        | 0.12%   |
| Blue Microphones                     | 1        | 0.12%   |
| Arturia                              | 1        | 0.12%   |
| Apple                                | 1        | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 47       | 5%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 46       | 4.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 39       | 4.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 34       | 3.62%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 33       | 3.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 32       | 3.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 27       | 2.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 26       | 2.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 25       | 2.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 22       | 2.34%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 21       | 2.23%   |
| AMD Family 17h/19h HD Audio Controller                                            | 20       | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                        | 19       | 2.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 18       | 1.91%   |
| Nvidia High Definition Audio Controller                                           | 16       | 1.7%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 15       | 1.6%    |
| Intel 200 Series PCH HD Audio                                                     | 14       | 1.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 13       | 1.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 12       | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                                     | 11       | 1.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 10       | 1.06%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 10       | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                     | 9        | 0.96%   |
| AMD Navi 10 HDMI Audio                                                            | 9        | 0.96%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 9        | 0.96%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 9        | 0.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 8        | 0.85%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 8        | 0.85%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 8        | 0.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 8        | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                                     | 7        | 0.74%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 7        | 0.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 7        | 0.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 7        | 0.74%   |
| AMD FCH Azalia Controller                                                         | 7        | 0.74%   |
| Nvidia MCP61 High Definition Audio                                                | 6        | 0.64%   |
| Nvidia GP108 High Definition Audio Controller                                     | 6        | 0.64%   |
| Kingston Technology HyperX 7.1 Audio                                              | 6        | 0.64%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 6        | 0.64%   |
| Intel Alder Lake-S HD Audio Controller                                            | 6        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 60       | 24.19%  |
| Unknown             | 47       | 18.95%  |
| G.Skill             | 37       | 14.92%  |
| Corsair             | 20       | 8.06%   |
| SK hynix            | 19       | 7.66%   |
| Crucial             | 17       | 6.85%   |
| Samsung Electronics | 16       | 6.45%   |
| Team                | 6        | 2.42%   |
| Micron Technology   | 5        | 2.02%   |
| Unknown             | 4        | 1.61%   |
| Nanya Technology    | 3        | 1.21%   |
| A-DATA Technology   | 3        | 1.21%   |
| Unknown (ABCD)      | 1        | 0.4%    |
| Unifosa             | 1        | 0.4%    |
| Transcend           | 1        | 0.4%    |
| Silicon Power       | 1        | 0.4%    |
| Ramaxel Technology  | 1        | 0.4%    |
| Patriot             | 1        | 0.4%    |
| Lexar               | 1        | 0.4%    |
| Infineon            | 1        | 0.4%    |
| Elpida              | 1        | 0.4%    |
| Atermiter           | 1        | 0.4%    |
| Apacer              | 1        | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s   | 4        | 1.42%   |
| Unknown                                                 | 4        | 1.42%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 3        | 1.06%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s             | 3        | 1.06%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s     | 3        | 1.06%   |
| G.Skill RAM F4-2400C15-16GIS 16GB DIMM DDR4 2400MT/s    | 3        | 1.06%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 3        | 1.06%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 2        | 0.71%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 2        | 0.71%   |
| Unknown RAM Module 4GB DIMM                             | 2        | 0.71%   |
| Unknown RAM Module 4096MB DIMM                          | 2        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 2        | 0.71%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 2        | 0.71%   |
| Unknown RAM Module 2GB DIMM                             | 2        | 0.71%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                 | 2        | 0.71%   |
| Unknown RAM Module 1GB DIMM SDRAM                       | 2        | 0.71%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 3000MT/s   | 2        | 0.71%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s    | 2        | 0.71%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 0.71%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 2        | 0.71%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s    | 2        | 0.71%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s     | 2        | 0.71%   |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s  | 2        | 0.71%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s   | 2        | 0.71%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s     | 2        | 0.71%   |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s      | 2        | 0.71%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s    | 2        | 0.71%   |
| G.Skill RAM F3-12800CL9-4 4GB DIMM DDR3 1866MT/s        | 2        | 0.71%   |
| G.Skill RAM F3-12800CL9-2GBXL 2048MB DIMM DDR3 1600MT/s | 2        | 0.71%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s   | 2        | 0.71%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s   | 2        | 0.71%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s   | 2        | 0.71%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s  | 2        | 0.71%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.35%   |
| Unknown RAM Module 8GB DIMM DDR 1333MT/s                | 1        | 0.35%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 1        | 0.35%   |
| Unknown RAM Module 512MB DIMM 533MT/s                   | 1        | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1        | 0.35%   |
| Unknown RAM Module 4GB DIMM 667MT/s                     | 1        | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 86       | 38.39%  |
| DDR3    | 76       | 33.93%  |
| Unknown | 22       | 9.82%   |
| DDR2    | 18       | 8.04%   |
| SDRAM   | 11       | 4.91%   |
| DDR     | 5        | 2.23%   |
| DDR5    | 4        | 1.79%   |
| LPDDR4  | 2        | 0.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 211      | 95.48%  |
| SODIMM       | 9        | 4.07%   |
| Row Of Chips | 1        | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 85       | 34.98%  |
| 4096  | 58       | 23.87%  |
| 2048  | 43       | 17.7%   |
| 16384 | 30       | 12.35%  |
| 32768 | 13       | 5.35%   |
| 1024  | 11       | 4.53%   |
| 512   | 2        | 0.82%   |
| 256   | 1        | 0.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 49       | 19.52%  |
| 1333    | 31       | 12.35%  |
| 3200    | 16       | 6.37%   |
| 2400    | 15       | 5.98%   |
| 3600    | 14       | 5.58%   |
| 2667    | 13       | 5.18%   |
| Unknown | 12       | 4.78%   |
| 667     | 9        | 3.59%   |
| 2133    | 8        | 3.19%   |
| 800     | 8        | 3.19%   |
| 2666    | 7        | 2.79%   |
| 3000    | 6        | 2.39%   |
| 1867    | 6        | 2.39%   |
| 1866    | 6        | 2.39%   |
| 3400    | 4        | 1.59%   |
| 1800    | 4        | 1.59%   |
| 533     | 4        | 1.59%   |
| 400     | 4        | 1.59%   |
| 4800    | 3        | 1.2%    |
| 3800    | 3        | 1.2%    |
| 4000    | 2        | 0.8%    |
| 3733    | 2        | 0.8%    |
| 3534    | 2        | 0.8%    |
| 3266    | 2        | 0.8%    |
| 2733    | 2        | 0.8%    |
| 2048    | 2        | 0.8%    |
| 2000    | 2        | 0.8%    |
| 1067    | 2        | 0.8%    |
| 43889   | 1        | 0.4%    |
| 6000    | 1        | 0.4%    |
| 4267    | 1        | 0.4%    |
| 3866    | 1        | 0.4%    |
| 3466    | 1        | 0.4%    |
| 3334    | 1        | 0.4%    |
| 3066    | 1        | 0.4%    |
| 2465    | 1        | 0.4%    |
| 2187    | 1        | 0.4%    |
| 2134    | 1        | 0.4%    |
| 1648    | 1        | 0.4%    |
| 1632    | 1        | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 17       | 62.96%  |
| Seiko Epson           | 3        | 11.11%  |
| Canon                 | 3        | 11.11%  |
| Brother Industries    | 2        | 7.41%   |
| Xerox                 | 1        | 3.7%    |
| Lexmark International | 1        | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| HP Deskjet 1050 J410                         | 5        | 17.24%  |
| Xerox Phaser 6000B                           | 1        | 3.45%   |
| Seiko Epson XP-225 Series                    | 1        | 3.45%   |
| Seiko Epson XP-2200 Series                   | 1        | 3.45%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 3.45%   |
| Lexmark International E120(n)                | 1        | 3.45%   |
| HP OfficeJet 5200 series                     | 1        | 3.45%   |
| HP Officejet 4620 series                     | 1        | 3.45%   |
| HP Officejet 4500 G510g-m                    | 1        | 3.45%   |
| HP LaserJet Professional P1102w              | 1        | 3.45%   |
| HP LaserJet M14-M17                          | 1        | 3.45%   |
| HP ENVY 6000 series                          | 1        | 3.45%   |
| HP ENVY 4520 series                          | 1        | 3.45%   |
| HP DeskJet F300 series                       | 1        | 3.45%   |
| HP DeskJet F2492 All-in-One                  | 1        | 3.45%   |
| HP DeskJet 930c                              | 1        | 3.45%   |
| HP DeskJet 3630 series                       | 1        | 3.45%   |
| HP Deskjet 3050 J610 series                  | 1        | 3.45%   |
| HP DeskJet 2700 series                       | 1        | 3.45%   |
| Canon TS6300 series                          | 1        | 3.45%   |
| Canon PIXMA TS6250                           | 1        | 3.45%   |
| Canon PIXMA MG2900 Series                    | 1        | 3.45%   |
| Canon LBP6200                                | 1        | 3.45%   |
| Brother DCP-L3550CDW                         | 1        | 3.45%   |
| Brother DCP-1610W                            | 1        | 3.45%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Mustek Systems  | 4        | 40%     |
| Canon           | 4        | 40%     |
| Seiko Epson     | 1        | 10%     |
| Hewlett-Packard | 1        | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 UB    | 3        | 30%     |
| Canon CanoScan 4400F                  | 2        | 20%     |
| Seiko Epson GT-X770 [Perfection V500] | 1        | 10%     |
| Mustek Systems BearPaw 2448 CU Pro    | 1        | 10%     |
| HP ScanJet 5300c/5370c                | 1        | 10%     |
| Canon CanoScan N670U/N676U/LiDE 20    | 1        | 10%     |
| Canon CanoScan LiDE 110               | 1        | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 23       | 23.96%  |
| Microsoft                     | 14       | 14.58%  |
| Hewlett-Packard               | 11       | 11.46%  |
| Creative Technology           | 10       | 10.42%  |
| Microdia                      | 5        | 5.21%   |
| Cubeternet                    | 4        | 4.17%   |
| Sunplus Innovation Technology | 3        | 3.13%   |
| Samsung Electronics           | 3        | 3.13%   |
| Realtek Semiconductor         | 3        | 3.13%   |
| Aveo Technology               | 3        | 3.13%   |
| WaveRider Communications      | 2        | 2.08%   |
| Philips (or NXP)              | 2        | 2.08%   |
| Generalplus Technology        | 2        | 2.08%   |
| Chicony Electronics           | 2        | 2.08%   |
| Z-Star Microelectronics       | 1        | 1.04%   |
| Xiaomi                        | 1        | 1.04%   |
| Trust                         | 1        | 1.04%   |
| Razer USA                     | 1        | 1.04%   |
| MacroSilicon                  | 1        | 1.04%   |
| KYE Systems (Mouse Systems)   | 1        | 1.04%   |
| Jieli Technology              | 1        | 1.04%   |
| Huawei Technologies           | 1        | 1.04%   |
| Apple                         | 1        | 1.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                | 9        | 9.38%   |
| HP Webcam HD 2300                        | 7        | 7.29%   |
| Logitech Webcam C270                     | 5        | 5.21%   |
| Logitech Webcam C310                     | 4        | 4.17%   |
| Logitech C922 Pro Stream Webcam          | 4        | 4.17%   |
| Samsung Galaxy series, misc. (MTP mode)  | 3        | 3.13%   |
| Creative Live! Cam Sync 1080p            | 3        | 3.13%   |
| Aveo UVC camera (Bresser microscope)     | 3        | 3.13%   |
| WaveRider USB Live camera                | 2        | 2.08%   |
| Sunplus Integrated_Webcam_HD             | 2        | 2.08%   |
| Microsoft LifeCam VX-800                 | 2        | 2.08%   |
| Microsoft LifeCam VX-2000                | 2        | 2.08%   |
| Microdia Sonix USB 2.0 Camera            | 2        | 2.08%   |
| Microdia Camera                          | 2        | 2.08%   |
| Logitech Webcam C925e                    | 2        | 2.08%   |
| Logitech QuickCam Express                | 2        | 2.08%   |
| HP HP Webcam HD 4310                     | 2        | 2.08%   |
| HP 320 FHD Webcam                        | 2        | 2.08%   |
| Generalplus 808 Camera #9 (web-cam mode) | 2        | 2.08%   |
| Cubeternet USB2.0 Camera                 | 2        | 2.08%   |
| Cubeternet GL-UPC822 UVC WebCam          | 2        | 2.08%   |
| Creative Live! Cam Sync 1080p V2         | 2        | 2.08%   |
| Z-Star Vega USB 2.0 Camera               | 1        | 1.04%   |
| Xiaomi Mi 11 Lite                        | 1        | 1.04%   |
| Trust USB Camera                         | 1        | 1.04%   |
| Sunplus HD 720P webcam                   | 1        | 1.04%   |
| Realtek NexiGo N960E FHD Webcam          | 1        | 1.04%   |
| Realtek Full HD webcam                   | 1        | 1.04%   |
| Realtek FULL HD 1080P Webcam             | 1        | 1.04%   |
| Razer USA Razer Kiyo Pro                 | 1        | 1.04%   |
| Philips (or NXP) Webcam SPC530NC         | 1        | 1.04%   |
| Philips (or NXP) SPZ2500                 | 1        | 1.04%   |
| Microsoft LifeCam VX-700                 | 1        | 1.04%   |
| Microdia Lumina Camera - Raw             | 1        | 1.04%   |
| MacroSilicon USB3. 0 capture             | 1        | 1.04%   |
| Logitech Webcam C200                     | 1        | 1.04%   |
| Logitech Webcam C170                     | 1        | 1.04%   |
| Logitech QuickCam Pro 4000               | 1        | 1.04%   |
| Logitech HD Webcam C910                  | 1        | 1.04%   |
| Logitech HD Webcam C525                  | 1        | 1.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| AuthenTec | 2        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| AuthenTec AES1600 | 2        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Alcor Micro           | 4        | 30.77%  |
| Gemalto (was Gemplus) | 3        | 23.08%  |
| Bit4id                | 3        | 23.08%  |
| Chicony Electronics   | 2        | 15.38%  |
| Realtek Semiconductor | 1        | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader    | 3        | 23.08%  |
| Bit4id miniLector EVO                                | 3        | 23.08%  |
| Alcor Micro AU9540 Smartcard Reader                  | 3        | 23.08%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 2        | 15.38%  |
| Realtek Semiconductor Smart Card Reader Interface    | 1        | 7.69%   |
| Alcor Micro Watchdata W 1981                         | 1        | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 434      | 86.28%  |
| 1     | 58       | 11.53%  |
| 2     | 9        | 1.79%   |
| 3     | 2        | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 39       | 49.37%  |
| Net/wireless             | 11       | 13.92%  |
| Chipcard                 | 9        | 11.39%  |
| Multimedia controller    | 3        | 3.8%    |
| Camera                   | 3        | 3.8%    |
| Bluetooth                | 3        | 3.8%    |
| Sound                    | 2        | 2.53%   |
| Network                  | 2        | 2.53%   |
| Fingerprint reader       | 2        | 2.53%   |
| Net/ethernet             | 1        | 1.27%   |
| Modem                    | 1        | 1.27%   |
| Dvb card                 | 1        | 1.27%   |
| Communication controller | 1        | 1.27%   |
| Card reader              | 1        | 1.27%   |

