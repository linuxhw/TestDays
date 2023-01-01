Ubuntu Budgie 20.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 20.04.

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

Total: 101

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte  | Z170X-Gaming 3              | [1773b79334](https://linux-hardware.org/?probe=1773b79334) | Dec 17, 2022 |
| MSI       | H67MA-E35                   | [d4f5628033](https://linux-hardware.org/?probe=d4f5628033) | Oct 11, 2022 |
| HP        | 3397                        | [335f59c96f](https://linux-hardware.org/?probe=335f59c96f) | Aug 22, 2022 |
| ASUSTek   | Berkeley                    | [e9998910ee](https://linux-hardware.org/?probe=e9998910ee) | Aug 17, 2022 |
| MSI       | H81M-E33                    | [33547f6d85](https://linux-hardware.org/?probe=33547f6d85) | Apr 11, 2022 |
| Gigabyte  | 970A-DS3P                   | [eaae14de4f](https://linux-hardware.org/?probe=eaae14de4f) | Mar 05, 2022 |
| ASUSTek   | ROG STRIX B550-E GAMING     | [7fa418eb00](https://linux-hardware.org/?probe=7fa418eb00) | Feb 25, 2022 |
| ASUSTek   | M4A87TD/USB3                | [88768afd55](https://linux-hardware.org/?probe=88768afd55) | Feb 10, 2022 |
| Gigabyte  | 970A-DS3P                   | [b96e414ae9](https://linux-hardware.org/?probe=b96e414ae9) | Jan 21, 2022 |
| Gigabyte  | 970A-DS3P                   | [96047ce382](https://linux-hardware.org/?probe=96047ce382) | Jan 19, 2022 |
| ASRock    | 4X4-4000 Series             | [172d5b0abc](https://linux-hardware.org/?probe=172d5b0abc) | Jan 12, 2022 |
| ASUSTek   | H81M-C                      | [f0e03ffaed](https://linux-hardware.org/?probe=f0e03ffaed) | Dec 22, 2021 |
| Lenovo    | 36F7 SDK0J40700 WIN 3258... | [ddf55561ad](https://linux-hardware.org/?probe=ddf55561ad) | Dec 21, 2021 |
| Lenovo    | 36F7 SDK0J40700 WIN 3258... | [d416ec7878](https://linux-hardware.org/?probe=d416ec7878) | Dec 17, 2021 |
| Intel     | DP55WB AAE64798-206         | [6e77546d03](https://linux-hardware.org/?probe=6e77546d03) | Dec 06, 2021 |
| HP        | 0A5Ch                       | [4858eb5c73](https://linux-hardware.org/?probe=4858eb5c73) | Nov 21, 2021 |
| Gigabyte  | B560M AORUS ELITE           | [b397fce5b8](https://linux-hardware.org/?probe=b397fce5b8) | Nov 20, 2021 |
| HP        | 0A5Ch                       | [8d102a03f6](https://linux-hardware.org/?probe=8d102a03f6) | Oct 19, 2021 |
| HP        | 0A5Ch                       | [139efd1a3d](https://linux-hardware.org/?probe=139efd1a3d) | Oct 19, 2021 |
| ASUSTek   | P7P55D                      | [c62d162396](https://linux-hardware.org/?probe=c62d162396) | Aug 02, 2021 |
| ASUSTek   | PRIME B450M-A               | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| ASUSTek   | P7P55D                      | [cd96dbf86a](https://linux-hardware.org/?probe=cd96dbf86a) | Jul 30, 2021 |
| ASUSTek   | P7P55D                      | [b983e48d71](https://linux-hardware.org/?probe=b983e48d71) | Jul 24, 2021 |
| ASUSTek   | P7P55D                      | [2335f32be7](https://linux-hardware.org/?probe=2335f32be7) | Jul 22, 2021 |
| ASUSTek   | PRIME B450M-A               | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| Fujitsu   | D3227-A1 S26361-D3227-A1    | [157b9695ae](https://linux-hardware.org/?probe=157b9695ae) | Jul 15, 2021 |
| Dell      | 048DY8 A01                  | [04c41fe4c2](https://linux-hardware.org/?probe=04c41fe4c2) | Jun 30, 2021 |
| ASUSTek   | Maximus VIII IMPACT         | [2c0a43e573](https://linux-hardware.org/?probe=2c0a43e573) | Apr 24, 2021 |
| Gigabyte  | Z77X-D3H                    | [28751098a6](https://linux-hardware.org/?probe=28751098a6) | Apr 23, 2021 |
| ASRock    | X370 Gaming-ITX/ac          | [e0fa7ade7a](https://linux-hardware.org/?probe=e0fa7ade7a) | Apr 06, 2021 |
| ASUSTek   | Z77-A                       | [ca21510412](https://linux-hardware.org/?probe=ca21510412) | Mar 23, 2021 |
| ASUSTek   | P7P55D-E LX                 | [83f55d5bf7](https://linux-hardware.org/?probe=83f55d5bf7) | Mar 20, 2021 |
| HP        | 3031h                       | [ee5e7baf77](https://linux-hardware.org/?probe=ee5e7baf77) | Mar 16, 2021 |
| ASUSTek   | PRIME B450-PLUS             | [79b5c4e048](https://linux-hardware.org/?probe=79b5c4e048) | Mar 07, 2021 |
| Unknown   | Unknown                     | [f97163d774](https://linux-hardware.org/?probe=f97163d774) | Feb 24, 2021 |
| ASUSTek   | ROG STRIX H470-I GAMING     | [f747681c25](https://linux-hardware.org/?probe=f747681c25) | Feb 19, 2021 |
| MSI       | A320M PRO-VD PLUS           | [24a9ae34ed](https://linux-hardware.org/?probe=24a9ae34ed) | Feb 13, 2021 |
| Gigabyte  | B450M DS3H-CF               | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Gigabyte  | B450M DS3H-CF               | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| HP        | 1589                        | [fe93b414cb](https://linux-hardware.org/?probe=fe93b414cb) | Jan 09, 2021 |
| ASUSTek   | TUF Z370-PLUS GAMING        | [276dda536a](https://linux-hardware.org/?probe=276dda536a) | Jan 06, 2021 |
| ASUSTek   | TUF Z370-PLUS GAMING        | [a80e8c5eb0](https://linux-hardware.org/?probe=a80e8c5eb0) | Jan 02, 2021 |
| Gigabyte  | B550I AORUS PRO AX          | [1effa5938b](https://linux-hardware.org/?probe=1effa5938b) | Dec 31, 2020 |
| Gigabyte  | B550M AORUS PRO-P           | [c32461bc20](https://linux-hardware.org/?probe=c32461bc20) | Dec 19, 2020 |
| ASUSTek   | PRIME A320M-K/BR            | [d65d3733f6](https://linux-hardware.org/?probe=d65d3733f6) | Dec 07, 2020 |
| Gigabyte  | Z170X-Gaming 3              | [58b6426d57](https://linux-hardware.org/?probe=58b6426d57) | Oct 30, 2020 |
| ASUSTek   | Maximus VIII IMPACT         | [b5a98b7ffa](https://linux-hardware.org/?probe=b5a98b7ffa) | Oct 24, 2020 |
| HP        | 1998                        | [e8076a87a0](https://linux-hardware.org/?probe=e8076a87a0) | Oct 20, 2020 |
| Apple     | Mac-F4208DC8 PVT            | [25565a3bbf](https://linux-hardware.org/?probe=25565a3bbf) | Oct 19, 2020 |
| Apple     | Mac-F4208DC8 PVT            | [3aa954c07b](https://linux-hardware.org/?probe=3aa954c07b) | Oct 19, 2020 |
| MSI       | MAG X570 TOMAHAWK WIFI      | [7c78d9b4da](https://linux-hardware.org/?probe=7c78d9b4da) | Oct 18, 2020 |
| MSI       | MAG X570 TOMAHAWK WIFI      | [ca85fa1d88](https://linux-hardware.org/?probe=ca85fa1d88) | Oct 18, 2020 |
| AAEON     | UP-APL01 V0.4               | [3d2cb2e4d1](https://linux-hardware.org/?probe=3d2cb2e4d1) | Oct 12, 2020 |
| AAEON     | UP-APL01 V0.4               | [16d3bf5578](https://linux-hardware.org/?probe=16d3bf5578) | Oct 12, 2020 |
| MSI       | MAG X570 TOMAHAWK WIFI      | [4a62de4c07](https://linux-hardware.org/?probe=4a62de4c07) | Oct 01, 2020 |
| ASRock    | B550 Phantom Gaming 4       | [a996c3d55c](https://linux-hardware.org/?probe=a996c3d55c) | Sep 29, 2020 |
| ASUSTek   | P9X79 DELUXE                | [5b7738af52](https://linux-hardware.org/?probe=5b7738af52) | Sep 23, 2020 |
| Gigabyte  | B360 AORUS GAMING 3-CF      | [663a5ef41a](https://linux-hardware.org/?probe=663a5ef41a) | Sep 21, 2020 |
| Dell      | 0200DY A03                  | [e91f9c04b9](https://linux-hardware.org/?probe=e91f9c04b9) | Sep 21, 2020 |
| Gigabyte  | Z68M-D2H                    | [d746ae5a52](https://linux-hardware.org/?probe=d746ae5a52) | Sep 19, 2020 |
| MSI       | MAG X570 TOMAHAWK WIFI      | [1037d2b746](https://linux-hardware.org/?probe=1037d2b746) | Sep 09, 2020 |
| MSI       | MAG X570 TOMAHAWK WIFI      | [b3d6fb36eb](https://linux-hardware.org/?probe=b3d6fb36eb) | Sep 08, 2020 |
| Gigabyte  | Z390 DESIGNARE-CF           | [d36f3124d1](https://linux-hardware.org/?probe=d36f3124d1) | Sep 06, 2020 |
| ASUSTek   | ROG STRIX X470-F GAMING     | [e90f4fb0e5](https://linux-hardware.org/?probe=e90f4fb0e5) | Sep 06, 2020 |
| PCSMART   | 6.0                         | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| MSI       | Z97 GAMING 5                | [3f1b387a92](https://linux-hardware.org/?probe=3f1b387a92) | Sep 04, 2020 |
| ASUSTek   | P9X79 DELUXE                | [75f32f4978](https://linux-hardware.org/?probe=75f32f4978) | Aug 16, 2020 |
| Gigabyte  | P55A-UD4P                   | [c908fd4599](https://linux-hardware.org/?probe=c908fd4599) | Aug 07, 2020 |
| ASUSTek   | P8H77-M PRO                 | [d943208a7c](https://linux-hardware.org/?probe=d943208a7c) | Jul 30, 2020 |
| Gigabyte  | Z170-HD3 DDR3-CF            | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| ASUSTek   | STRIX B250F GAMING          | [cb5d511453](https://linux-hardware.org/?probe=cb5d511453) | Jul 28, 2020 |
| ASUSTek   | P8H77-M PRO                 | [87d7bc3077](https://linux-hardware.org/?probe=87d7bc3077) | Jul 28, 2020 |
| MSI       | X370 GAMING PRO CARBON      | [f38e8a0201](https://linux-hardware.org/?probe=f38e8a0201) | Jul 26, 2020 |
| HP        | 82F2                        | [172d6aed2a](https://linux-hardware.org/?probe=172d6aed2a) | Jul 26, 2020 |
| Gigabyte  | B360 AORUS GAMING 3 WIFI... | [2e6c21ed23](https://linux-hardware.org/?probe=2e6c21ed23) | Jul 26, 2020 |
| HP        | 3397                        | [edd52c2428](https://linux-hardware.org/?probe=edd52c2428) | Jul 24, 2020 |
| HP        | 3397                        | [20b3d353d8](https://linux-hardware.org/?probe=20b3d353d8) | Jul 24, 2020 |
| Gigabyte  | H61M-S1                     | [3ce4143dee](https://linux-hardware.org/?probe=3ce4143dee) | Jul 24, 2020 |
| Gigabyte  | B360 AORUS GAMING 3 WIFI... | [534a204796](https://linux-hardware.org/?probe=534a204796) | Jul 17, 2020 |
| ASUSTek   | M51AC                       | [fcc0f73453](https://linux-hardware.org/?probe=fcc0f73453) | Jul 15, 2020 |
| ASUSTek   | M4A87TD/USB3                | [7d642bd7dc](https://linux-hardware.org/?probe=7d642bd7dc) | Jul 14, 2020 |
| ASUSTek   | M4A87TD/USB3                | [76752b2d00](https://linux-hardware.org/?probe=76752b2d00) | Jul 13, 2020 |
| ASUSTek   | M4A87TD/USB3                | [8639032305](https://linux-hardware.org/?probe=8639032305) | Jul 13, 2020 |
| ASUSTek   | M51AC                       | [6af32ff946](https://linux-hardware.org/?probe=6af32ff946) | Jul 01, 2020 |
| ASUSTek   | B85M-E                      | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| Dell      | 09KPNV A00                  | [9f63cccd5c](https://linux-hardware.org/?probe=9f63cccd5c) | Jun 21, 2020 |
| ASUSTek   | P8Z68-V PRO GEN3            | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| ASUSTek   | ROG STRIX X570-E GAMING     | [49486e2abf](https://linux-hardware.org/?probe=49486e2abf) | May 24, 2020 |
| ASUSTek   | P8H77-M PRO                 | [e8b5bf55c7](https://linux-hardware.org/?probe=e8b5bf55c7) | May 20, 2020 |
| Dell      | 0J32FG A06                  | [d5d2970bc5](https://linux-hardware.org/?probe=d5d2970bc5) | May 15, 2020 |
| Gigabyte  | Z68M-D2H                    | [70c167639c](https://linux-hardware.org/?probe=70c167639c) | May 15, 2020 |
| Dell      | 0TNXNR A01                  | [c16ecd859c](https://linux-hardware.org/?probe=c16ecd859c) | May 11, 2020 |
| Lenovo    | 3704 SDK0R32862 WIN 3258... | [eb7d6f2ec3](https://linux-hardware.org/?probe=eb7d6f2ec3) | May 10, 2020 |
| Biostar   | G31-M7 TE                   | [e9d31442df](https://linux-hardware.org/?probe=e9d31442df) | May 09, 2020 |
| ASRock    | B450 Gaming-ITX/ac          | [2e108e8f82](https://linux-hardware.org/?probe=2e108e8f82) | May 06, 2020 |
| MSI       | MEG Z390 GODLIKE            | [f5c70a1643](https://linux-hardware.org/?probe=f5c70a1643) | Apr 30, 2020 |
| ASUSTek   | TUF B450-PLUS GAMING        | [6982ff0a12](https://linux-hardware.org/?probe=6982ff0a12) | Apr 25, 2020 |
| Gigabyte  | Z68M-D2H                    | [3db29a7f67](https://linux-hardware.org/?probe=3db29a7f67) | Apr 12, 2020 |
| Dell      | 0J32FG A06                  | [efb8737ca2](https://linux-hardware.org/?probe=efb8737ca2) | Mar 20, 2020 |
| eMachines | EL1852G                     | [e90ac3f652](https://linux-hardware.org/?probe=e90ac3f652) | Feb 27, 2020 |
| Gigabyte  | Z68M-D2H                    | [6cfda70306](https://linux-hardware.org/?probe=6cfda70306) | Feb 15, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.4.0-42-generic        | 7        | 9.33%   |
| 5.4.0-52-generic        | 4        | 5.33%   |
| 5.4.0-48-generic        | 4        | 5.33%   |
| 5.4.0-45-generic        | 4        | 5.33%   |
| 5.4.0-37-generic        | 4        | 5.33%   |
| 5.4.0-47-generic        | 3        | 4%      |
| 5.4.0-29-generic        | 3        | 4%      |
| 5.8.0-59-generic        | 2        | 2.67%   |
| 5.4.0-91-generic        | 2        | 2.67%   |
| 5.4.0-72-generic        | 2        | 2.67%   |
| 5.4.0-59-generic        | 2        | 2.67%   |
| 5.4.0-40-generic        | 2        | 2.67%   |
| 5.4.0-31-generic        | 2        | 2.67%   |
| 5.13.0-39-generic       | 2        | 2.67%   |
| 5.9.1-050901-generic    | 1        | 1.33%   |
| 5.8.0-59-lowlatency     | 1        | 1.33%   |
| 5.8.0-45-generic        | 1        | 1.33%   |
| 5.8.0-44-generic        | 1        | 1.33%   |
| 5.8.0-43-generic        | 1        | 1.33%   |
| 5.7.7-xanmod1           | 1        | 1.33%   |
| 5.5.8-050508-lowlatency | 1        | 1.33%   |
| 5.4.0-96-generic        | 1        | 1.33%   |
| 5.4.0-80-generic        | 1        | 1.33%   |
| 5.4.0-70-generic        | 1        | 1.33%   |
| 5.4.0-67-generic        | 1        | 1.33%   |
| 5.4.0-66-generic        | 1        | 1.33%   |
| 5.4.0-65-generic        | 1        | 1.33%   |
| 5.4.0-58-generic        | 1        | 1.33%   |
| 5.4.0-44-generic        | 1        | 1.33%   |
| 5.4.0-39-generic        | 1        | 1.33%   |
| 5.4.0-29-lowlatency     | 1        | 1.33%   |
| 5.4.0-28-generic        | 1        | 1.33%   |
| 5.4.0-26-generic        | 1        | 1.33%   |
| 5.4.0-24-generic        | 1        | 1.33%   |
| 5.4.0-18-generic        | 1        | 1.33%   |
| 5.4.0-16-generic        | 1        | 1.33%   |
| 5.4.0-14-generic        | 1        | 1.33%   |
| 5.4.0-135-generic       | 1        | 1.33%   |
| 5.4.0-126-generic       | 1        | 1.33%   |
| 5.4.0-102-generic       | 1        | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 49       | 75.38%  |
| 5.8.0   | 6        | 9.23%   |
| 5.13.0  | 3        | 4.62%   |
| 5.11.0  | 3        | 4.62%   |
| 5.9.1   | 1        | 1.54%   |
| 5.7.7   | 1        | 1.54%   |
| 5.5.8   | 1        | 1.54%   |
| 5.15.0  | 1        | 1.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 49       | 75.38%  |
| 5.8     | 6        | 9.23%   |
| 5.13    | 3        | 4.62%   |
| 5.11    | 3        | 4.62%   |
| 5.9     | 1        | 1.54%   |
| 5.7     | 1        | 1.54%   |
| 5.5     | 1        | 1.54%   |
| 5.15    | 1        | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 65       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Budgie | 64       | 98.46%  |
| GNOME  | 1        | 1.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 64       | 98.46%  |
| Wayland | 1        | 1.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 37       | 55.22%  |
| TDM     | 15       | 22.39%  |
| LightDM | 10       | 14.93%  |
| GDM     | 3        | 4.48%   |
| GDM3    | 2        | 2.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 23       | 35.38%  |
| de_DE | 10       | 15.38%  |
| pt_BR | 7        | 10.77%  |
| fr_FR | 4        | 6.15%   |
| en_CA | 3        | 4.62%   |
| en_AU | 3        | 4.62%   |
| zh_TW | 2        | 3.08%   |
| es_CO | 2        | 3.08%   |
| en_GB | 2        | 3.08%   |
| uk_UA | 1        | 1.54%   |
| ru_RU | 1        | 1.54%   |
| it_IT | 1        | 1.54%   |
| fr_CH | 1        | 1.54%   |
| es_MX | 1        | 1.54%   |
| es_ES | 1        | 1.54%   |
| es_CL | 1        | 1.54%   |
| en_IL | 1        | 1.54%   |
| bg_BG | 1        | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 39       | 57.35%  |
| EFI  | 29       | 42.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 60       | 92.31%  |
| Zfs   | 3        | 4.62%   |
| Btrfs | 2        | 3.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 44       | 65.67%  |
| GPT     | 14       | 20.9%   |
| MBR     | 9        | 13.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 81.82%  |
| Yes       | 12       | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 64.18%  |
| Yes       | 24       | 35.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21       | 32.31%  |
| Gigabyte Technology | 13       | 20%     |
| MSI                 | 8        | 12.31%  |
| Hewlett-Packard     | 7        | 10.77%  |
| Dell                | 5        | 7.69%   |
| ASRock              | 3        | 4.62%   |
| Lenovo              | 2        | 3.08%   |
| PCSMART             | 1        | 1.54%   |
| Intel               | 1        | 1.54%   |
| Fujitsu             | 1        | 1.54%   |
| eMachines           | 1        | 1.54%   |
| Biostar             | 1        | 1.54%   |
| Apple               | 1        | 1.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| MSI MS-7C84                             | 2        | 3.08%   |
| HP Compaq Elite 8300 SFF                | 2        | 3.08%   |
| ASUS All Series                         | 2        | 3.08%   |
| PCSMART 6.0                             | 1        | 1.54%   |
| MSI MS-7B38                             | 1        | 1.54%   |
| MSI MS-7B10                             | 1        | 1.54%   |
| MSI MS-7A32                             | 1        | 1.54%   |
| MSI MS-7917                             | 1        | 1.54%   |
| MSI MS-7817                             | 1        | 1.54%   |
| MSI MS-7680                             | 1        | 1.54%   |
| Lenovo Legion T530-28ICB 90L300BQMW     | 1        | 1.54%   |
| Lenovo IdeaCentre 310S-08ASR 90G9007EGE | 1        | 1.54%   |
| Intel DP55WB AAE64798-206               | 1        | 1.54%   |
| HP Z420 Workstation                     | 1        | 1.54%   |
| HP Pavilion Desktop PC 570-p0xx         | 1        | 1.54%   |
| HP EliteDesk 800 G1 SFF                 | 1        | 1.54%   |
| HP Compaq dc7900 Small Form Factor      | 1        | 1.54%   |
| HP Compaq dc7700 Ultra-slim Desktop     | 1        | 1.54%   |
| Gigabyte Z77X-D3H                       | 1        | 1.54%   |
| Gigabyte Z68M-D2H                       | 1        | 1.54%   |
| Gigabyte Z390 DESIGNARE                 | 1        | 1.54%   |
| Gigabyte Z170X-Gaming 3                 | 1        | 1.54%   |
| Gigabyte Z170-HD3 DDR3                  | 1        | 1.54%   |
| Gigabyte P55A-UD4P                      | 1        | 1.54%   |
| Gigabyte H61M-S1                        | 1        | 1.54%   |
| Gigabyte B550M AORUS PRO-P              | 1        | 1.54%   |
| Gigabyte B550I AORUS PRO AX             | 1        | 1.54%   |
| Gigabyte B450M DS3H                     | 1        | 1.54%   |
| Gigabyte B360 AORUS GAMING 3 WIFI       | 1        | 1.54%   |
| Gigabyte B360 AORUS GAMING 3            | 1        | 1.54%   |
| Gigabyte 970A-DS3P                      | 1        | 1.54%   |
| Fujitsu CELSIUS W530                    | 1        | 1.54%   |
| eMachines EL1852G                       | 1        | 1.54%   |
| Dell Precision WorkStation T3500        | 1        | 1.54%   |
| Dell Precision T1700                    | 1        | 1.54%   |
| Dell OptiPlex XE                        | 1        | 1.54%   |
| Dell OptiPlex 9010                      | 1        | 1.54%   |
| Dell OptiPlex 780                       | 1        | 1.54%   |
| Biostar G31-M7 TE                       | 1        | 1.54%   |
| ASUS Z77-A                              | 1        | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP Compaq             | 4        | 6.15%   |
| Dell OptiPlex         | 3        | 4.62%   |
| ASUS ROG              | 3        | 4.62%   |
| ASUS PRIME            | 3        | 4.62%   |
| MSI MS-7C84           | 2        | 3.08%   |
| Gigabyte B360         | 2        | 3.08%   |
| Dell Precision        | 2        | 3.08%   |
| ASUS TUF              | 2        | 3.08%   |
| ASUS All              | 2        | 3.08%   |
| PCSMART 6.0           | 1        | 1.54%   |
| MSI MS-7B38           | 1        | 1.54%   |
| MSI MS-7B10           | 1        | 1.54%   |
| MSI MS-7A32           | 1        | 1.54%   |
| MSI MS-7917           | 1        | 1.54%   |
| MSI MS-7817           | 1        | 1.54%   |
| MSI MS-7680           | 1        | 1.54%   |
| Lenovo Legion         | 1        | 1.54%   |
| Lenovo IdeaCentre     | 1        | 1.54%   |
| Intel DP55WB          | 1        | 1.54%   |
| HP Z420               | 1        | 1.54%   |
| HP Pavilion           | 1        | 1.54%   |
| HP EliteDesk          | 1        | 1.54%   |
| Gigabyte Z77X-D3H     | 1        | 1.54%   |
| Gigabyte Z68M-D2H     | 1        | 1.54%   |
| Gigabyte Z390         | 1        | 1.54%   |
| Gigabyte Z170X-Gaming | 1        | 1.54%   |
| Gigabyte Z170-HD3     | 1        | 1.54%   |
| Gigabyte P55A-UD4P    | 1        | 1.54%   |
| Gigabyte H61M-S1      | 1        | 1.54%   |
| Gigabyte B550M        | 1        | 1.54%   |
| Gigabyte B550I        | 1        | 1.54%   |
| Gigabyte B450M        | 1        | 1.54%   |
| Gigabyte 970A-DS3P    | 1        | 1.54%   |
| Fujitsu CELSIUS       | 1        | 1.54%   |
| eMachines EL1852G     | 1        | 1.54%   |
| Biostar G31-M7        | 1        | 1.54%   |
| ASUS Z77-A            | 1        | 1.54%   |
| ASUS STRIX            | 1        | 1.54%   |
| ASUS P9X79            | 1        | 1.54%   |
| ASUS P8Z68-V          | 1        | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 12       | 18.46%  |
| 2013 | 8        | 12.31%  |
| 2020 | 6        | 9.23%   |
| 2017 | 6        | 9.23%   |
| 2012 | 6        | 9.23%   |
| 2011 | 6        | 9.23%   |
| 2019 | 4        | 6.15%   |
| 2009 | 4        | 6.15%   |
| 2015 | 3        | 4.62%   |
| 2010 | 3        | 4.62%   |
| 2007 | 3        | 4.62%   |
| 2008 | 2        | 3.08%   |
| 2016 | 1        | 1.54%   |
| 2014 | 1        | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 65       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 65       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 65       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 30       | 44.78%  |
| 8.01-16.0   | 12       | 17.91%  |
| 3.01-4.0    | 8        | 11.94%  |
| 32.01-64.0  | 7        | 10.45%  |
| 4.01-8.0    | 5        | 7.46%   |
| 64.01-256.0 | 4        | 5.97%   |
| 24.01-32.0  | 1        | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 24       | 33.8%   |
| 4.01-8.0   | 17       | 23.94%  |
| 1.01-2.0   | 14       | 19.72%  |
| 3.01-4.0   | 10       | 14.08%  |
| 8.01-16.0  | 4        | 5.63%   |
| 32.01-64.0 | 1        | 1.41%   |
| 16.01-24.0 | 1        | 1.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 19       | 28.36%  |
| 2      | 18       | 26.87%  |
| 3      | 13       | 19.4%   |
| 5      | 8        | 11.94%  |
| 4      | 7        | 10.45%  |
| 8      | 1        | 1.49%   |
| 6      | 1        | 1.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 52.31%  |
| No        | 31       | 47.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 65       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 36       | 55.38%  |
| No        | 29       | 44.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 57.58%  |
| Yes       | 28       | 42.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 15       | 23.08%  |
| Germany      | 10       | 15.38%  |
| Brazil       | 6        | 9.23%   |
| France       | 5        | 7.69%   |
| Canada       | 3        | 4.62%   |
| Australia    | 3        | 4.62%   |
| Switzerland  | 2        | 3.08%   |
| Mexico       | 2        | 3.08%   |
| Colombia     | 2        | 3.08%   |
| Ukraine      | 1        | 1.54%   |
| UK           | 1        | 1.54%   |
| Taiwan       | 1        | 1.54%   |
| Sweden       | 1        | 1.54%   |
| Spain        | 1        | 1.54%   |
| Saudi Arabia | 1        | 1.54%   |
| Russia       | 1        | 1.54%   |
| Norway       | 1        | 1.54%   |
| Japan        | 1        | 1.54%   |
| Italy        | 1        | 1.54%   |
| Israel       | 1        | 1.54%   |
| Hungary      | 1        | 1.54%   |
| Croatia      | 1        | 1.54%   |
| Chile        | 1        | 1.54%   |
| Bulgaria     | 1        | 1.54%   |
| Bolivia      | 1        | 1.54%   |
| Belgium      | 1        | 1.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Paris                 | 2        | 2.99%   |
| Miami                 | 2        | 2.99%   |
| Maringá              | 2        | 2.99%   |
| Dallas                | 2        | 2.99%   |
| Bogotá               | 2        | 2.99%   |
| Zagreb                | 1        | 1.49%   |
| Uman                  | 1        | 1.49%   |
| Trondheim             | 1        | 1.49%   |
| Traunstein            | 1        | 1.49%   |
| Tobyhanna             | 1        | 1.49%   |
| Tijuana               | 1        | 1.49%   |
| Sydney                | 1        | 1.49%   |
| Stara Zagora          | 1        | 1.49%   |
| Smithville            | 1        | 1.49%   |
| Seraing               | 1        | 1.49%   |
| Senaide               | 1        | 1.49%   |
| Seminary              | 1        | 1.49%   |
| Sao Caetano do Sul    | 1        | 1.49%   |
| Sao Bernardo do Campo | 1        | 1.49%   |
| Santa Cruz            | 1        | 1.49%   |
| San Pedro de la Paz   | 1        | 1.49%   |
| Salach                | 1        | 1.49%   |
| Saint Paul            | 1        | 1.49%   |
| Queens                | 1        | 1.49%   |
| Pouso Alegre          | 1        | 1.49%   |
| Pomaz                 | 1        | 1.49%   |
| Petaẖ Tiqwa         | 1        | 1.49%   |
| Perth                 | 1        | 1.49%   |
| Palm Springs          | 1        | 1.49%   |
| Paderborn             | 1        | 1.49%   |
| New York              | 1        | 1.49%   |
| New Milford           | 1        | 1.49%   |
| Natal                 | 1        | 1.49%   |
| Nagoya                | 1        | 1.49%   |
| Münster              | 1        | 1.49%   |
| Montreal              | 1        | 1.49%   |
| Mainburg              | 1        | 1.49%   |
| Ljungby               | 1        | 1.49%   |
| Leopold               | 1        | 1.49%   |
| Kirov                 | 1        | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 24       | 41     | 18.05%  |
| Seagate                   | 22       | 37     | 16.54%  |
| Samsung Electronics       | 20       | 28     | 15.04%  |
| Kingston                  | 10       | 16     | 7.52%   |
| Toshiba                   | 8        | 8      | 6.02%   |
| SanDisk                   | 8        | 12     | 6.02%   |
| Phison                    | 6        | 9      | 4.51%   |
| Hitachi                   | 3        | 3      | 2.26%   |
| HGST                      | 3        | 4      | 2.26%   |
| Crucial                   | 3        | 4      | 2.26%   |
| Unknown                   | 2        | 3      | 1.5%    |
| PNY                       | 2        | 2      | 1.5%    |
| OCZ                       | 2        | 2      | 1.5%    |
| Maxtor                    | 2        | 5      | 1.5%    |
| HS-SSD-C100               | 2        | 2      | 1.5%    |
| A-DATA Technology         | 2        | 2      | 1.5%    |
| XrayDisk                  | 1        | 1      | 0.75%   |
| Transcend                 | 1        | 1      | 0.75%   |
| Silicon Motion            | 1        | 1      | 0.75%   |
| SABRENT                   | 1        | 1      | 0.75%   |
| Plextor                   | 1        | 1      | 0.75%   |
| Netac                     | 1        | 1      | 0.75%   |
| Micron/Crucial Technology | 1        | 1      | 0.75%   |
| KingDian                  | 1        | 1      | 0.75%   |
| JMicron Technology        | 1        | 1      | 0.75%   |
| Intel                     | 1        | 1      | 0.75%   |
| China                     | 1        | 1      | 0.75%   |
| Axiom                     | 1        | 1      | 0.75%   |
| Apacer                    | 1        | 1      | 0.75%   |
| AMD                       | 1        | 8      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 3        | 1.84%   |
| Samsung SSD 860 EVO 500GB        | 3        | 1.84%   |
| Samsung NVMe SSD Drive 500GB     | 3        | 1.84%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 1.84%   |
| WDC WD5000AAKX-001CA0 500GB      | 2        | 1.23%   |
| WDC WD5000AAKS-00UU3A0 500GB     | 2        | 1.23%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 2        | 1.23%   |
| Seagate ST4000DM000-1F2168 4TB   | 2        | 1.23%   |
| Seagate ST380815AS 80GB          | 2        | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 1.23%   |
| SanDisk SDSSDA240G 240GB         | 2        | 1.23%   |
| SanDisk SDSSDA120G 120GB         | 2        | 1.23%   |
| Samsung SSD 860 QVO 1TB          | 2        | 1.23%   |
| Samsung NVMe SSD Drive 512GB     | 2        | 1.23%   |
| Phison Sabrent Rocket 4.0 1TB    | 2        | 1.23%   |
| Phison NVMe SSD Drive 240GB      | 2        | 1.23%   |
| Kingston SV300S37A60G 64GB SSD   | 2        | 1.23%   |
| Kingston SA400S37480G 480GB SSD  | 2        | 1.23%   |
| XrayDisk 256GB                   | 1        | 0.61%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 0.61%   |
| WDC WDS400T1R0A-68A4W0 4TB SSD   | 1        | 0.61%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 0.61%   |
| WDC WDS200T2B0A 2TB SSD          | 1        | 0.61%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.61%   |
| WDC WD80EFAX-68LHPN0 8TB         | 1        | 0.61%   |
| WDC WD7502AAEX-00Y9A0 752GB      | 1        | 0.61%   |
| WDC WD7501AALS-00J7B1 752GB      | 1        | 0.61%   |
| WDC WD7500BPVT-24HXZT3 752GB     | 1        | 0.61%   |
| WDC WD6401AALS-00L3B2 640GB      | 1        | 0.61%   |
| WDC WD6000HLHX-01JJPV0 600GB     | 1        | 0.61%   |
| WDC WD5000AVCS-632DY1 500GB      | 1        | 0.61%   |
| WDC WD5000AAKS-75V0A0 500GB      | 1        | 0.61%   |
| WDC WD5000AAKS-00V1A0 500GB      | 1        | 0.61%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1        | 0.61%   |
| WDC WD40EZRZ-00G                 | 1        | 0.61%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 0.61%   |
| WDC WD4003FZEX-00Z4SA0 4TB       | 1        | 0.61%   |
| WDC WD2500AAJS-60M0A0 250GB      | 1        | 0.61%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.61%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 1        | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 37     | 36.07%  |
| WDC                 | 21       | 35     | 34.43%  |
| Toshiba             | 8        | 8      | 13.11%  |
| Hitachi             | 3        | 3      | 4.92%   |
| HGST                | 3        | 4      | 4.92%   |
| Maxtor              | 2        | 5      | 3.28%   |
| Unknown             | 1        | 1      | 1.64%   |
| Samsung Electronics | 1        | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 12       | 15     | 24.49%  |
| Kingston            | 10       | 16     | 20.41%  |
| SanDisk             | 7        | 10     | 14.29%  |
| WDC                 | 4        | 6      | 8.16%   |
| Crucial             | 2        | 3      | 4.08%   |
| A-DATA Technology   | 2        | 2      | 4.08%   |
| Transcend           | 1        | 1      | 2.04%   |
| PNY                 | 1        | 1      | 2.04%   |
| Plextor             | 1        | 1      | 2.04%   |
| OCZ                 | 1        | 1      | 2.04%   |
| Netac               | 1        | 1      | 2.04%   |
| KingDian            | 1        | 1      | 2.04%   |
| JMicron Technology  | 1        | 1      | 2.04%   |
| Intel               | 1        | 1      | 2.04%   |
| China               | 1        | 1      | 2.04%   |
| Axiom               | 1        | 1      | 2.04%   |
| Apacer              | 1        | 1      | 2.04%   |
| AMD                 | 1        | 8      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 47       | 94     | 43.52%  |
| SSD     | 37       | 71     | 34.26%  |
| NVMe    | 20       | 29     | 18.52%  |
| Unknown | 4        | 5      | 3.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 60       | 165    | 72.29%  |
| NVMe | 19       | 28     | 22.89%  |
| SAS  | 4        | 6      | 4.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 47       | 94     | 52.22%  |
| 0.51-1.0   | 21       | 30     | 23.33%  |
| 1.01-2.0   | 12       | 25     | 13.33%  |
| 3.01-4.0   | 7        | 11     | 7.78%   |
| 4.01-10.0  | 3        | 5      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 18       | 26.09%  |
| 101-250        | 18       | 26.09%  |
| More than 3000 | 9        | 13.04%  |
| 501-1000       | 9        | 13.04%  |
| 1001-2000      | 6        | 8.7%    |
| 2001-3000      | 3        | 4.35%   |
| 21-50          | 2        | 2.9%    |
| 1-20           | 2        | 2.9%    |
| Unknown        | 2        | 2.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 17       | 24.29%  |
| 101-250        | 12       | 17.14%  |
| 251-500        | 11       | 15.71%  |
| 21-50          | 10       | 14.29%  |
| 1001-2000      | 6        | 8.57%   |
| 51-100         | 6        | 8.57%   |
| 501-1000       | 3        | 4.29%   |
| More than 3000 | 2        | 2.86%   |
| Unknown        | 2        | 2.86%   |
| 2001-3000      | 1        | 1.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 2        | 2      | 14.29%  |
| WDC WD6000HLHX-01JJPV0 600GB    | 1        | 1      | 7.14%   |
| WDC WD5000AVCS-632DY1 500GB     | 1        | 1      | 7.14%   |
| WDC WD5000AAKX-001CA0 500GB     | 1        | 1      | 7.14%   |
| WDC WD4003FZEX-00Z4SA0 4TB      | 1        | 1      | 7.14%   |
| WDC WD2500AAJS-60M0A0 250GB     | 1        | 1      | 7.14%   |
| WDC WD20EFRX-68EUZN0 2TB        | 1        | 2      | 7.14%   |
| Seagate ST9500325AS 500GB       | 1        | 1      | 7.14%   |
| Seagate ST5000DM000-1FK178 5TB  | 1        | 1      | 7.14%   |
| Seagate ST3320620AS 320GB       | 1        | 1      | 7.14%   |
| Maxtor STM3250310AS 250GB       | 1        | 1      | 7.14%   |
| Maxtor 6B200M0 208GB            | 1        | 2      | 7.14%   |
| Hitachi HDS721032CLA362 320GB   | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 7      | 42.86%  |
| Seagate | 5        | 5      | 35.71%  |
| Maxtor  | 2        | 3      | 14.29%  |
| Hitachi | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 7      | 42.86%  |
| Seagate | 5        | 5      | 35.71%  |
| Maxtor  | 2        | 3      | 14.29%  |
| Hitachi | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 16     | 100%    |

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
| Detected | 46       | 131    | 62.16%  |
| Works    | 18       | 52     | 24.32%  |
| Malfunc  | 10       | 16     | 13.51%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 45       | 45.92%  |
| AMD                           | 20       | 20.41%  |
| Samsung Electronics           | 9        | 9.18%   |
| Phison Electronics            | 6        | 6.12%   |
| Marvell Technology Group      | 5        | 5.1%    |
| JMicron Technology            | 4        | 4.08%   |
| Micron/Crucial Technology     | 2        | 2.04%   |
| Silicon Motion                | 1        | 1.02%   |
| Silicon Image                 | 1        | 1.02%   |
| SanDisk                       | 1        | 1.02%   |
| OCZ Technology Group          | 1        | 1.02%   |
| Integrated Technology Express | 1        | 1.02%   |
| ASMedia Technology            | 1        | 1.02%   |
| Adaptec                       | 1        | 1.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 11.29%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 5.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 4.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 4.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 4.03%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 4        | 3.23%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 3.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 3.23%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 3.23%   |
| Phison E12 NVMe Controller                                                              | 3        | 2.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 2.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 2.42%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2        | 1.61%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 1.61%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 1.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.61%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.61%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.61%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.61%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.81%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.81%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.81%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.81%   |
| OCZ Group RD400/400A SSD                                                                | 1        | 0.81%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 0.81%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.81%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.81%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1        | 0.81%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.81%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.81%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.81%   |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 0.81%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.81%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 50       | 54.95%  |
| NVMe | 19       | 20.88%  |
| IDE  | 15       | 16.48%  |
| RAID | 6        | 6.59%   |
| SAS  | 1        | 1.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 45       | 69.23%  |
| AMD    | 20       | 30.77%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 6.06%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 4.55%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 4.55%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 4.55%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 3.03%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 3.03%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 3.03%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 3.03%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 3.03%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1        | 1.52%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz          | 1        | 1.52%   |
| Intel Xeon CPU 5150 @ 2.66GHz               | 1        | 1.52%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 1.52%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 1.52%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 1        | 1.52%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 1.52%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.52%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.52%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.52%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.52%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.52%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.52%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 1.52%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 1.52%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 1        | 1.52%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.52%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.52%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 1.52%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.52%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.52%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1        | 1.52%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.52%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.52%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1        | 1.52%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.52%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 1.52%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 1        | 1.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 1.52%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 1        | 1.52%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i7     | 18       | 27.27%  |
| Intel Core i5     | 12       | 18.18%  |
| AMD Ryzen 5       | 7        | 10.61%  |
| AMD Ryzen 7       | 5        | 7.58%   |
| Intel Xeon        | 3        | 4.55%   |
| Intel Core 2 Duo  | 3        | 4.55%   |
| AMD Ryzen 3       | 3        | 4.55%   |
| Intel Pentium     | 2        | 3.03%   |
| Intel Core i9     | 2        | 3.03%   |
| Intel Core i3     | 2        | 3.03%   |
| Intel Core 2 Quad | 2        | 3.03%   |
| Intel Core 2      | 2        | 3.03%   |
| Other             | 1        | 1.52%   |
| AMD Ryzen 9       | 1        | 1.52%   |
| AMD Phenom II X6  | 1        | 1.52%   |
| AMD FX            | 1        | 1.52%   |
| AMD A6            | 1        | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 32       | 49.23%  |
| 6      | 11       | 16.92%  |
| 2      | 10       | 15.38%  |
| 8      | 9        | 13.85%  |
| 12     | 1        | 1.54%   |
| 3      | 1        | 1.54%   |
| 1      | 1        | 1.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 64       | 98.46%  |
| 2      | 1        | 1.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 37       | 56.06%  |
| 1      | 29       | 43.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 65       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 16.42%  |
| 0x306c3    | 7        | 10.45%  |
| 0x306a9    | 7        | 10.45%  |
| 0x506e3    | 4        | 5.97%   |
| 0x206a7    | 4        | 5.97%   |
| 0x906ec    | 3        | 4.48%   |
| 0x106e5    | 3        | 4.48%   |
| 0x1067a    | 3        | 4.48%   |
| 0x08701021 | 3        | 4.48%   |
| 0x0800820d | 3        | 4.48%   |
| 0x906ea    | 2        | 2.99%   |
| 0x6f6      | 2        | 2.99%   |
| 0x206d7    | 2        | 2.99%   |
| 0x906ed    | 1        | 1.49%   |
| 0x6fb      | 1        | 1.49%   |
| 0x6f2      | 1        | 1.49%   |
| 0x106a5    | 1        | 1.49%   |
| 0x08701013 | 1        | 1.49%   |
| 0x08600103 | 1        | 1.49%   |
| 0x08108109 | 1        | 1.49%   |
| 0x08101016 | 1        | 1.49%   |
| 0x0810100b | 1        | 1.49%   |
| 0x06006704 | 1        | 1.49%   |
| 0x0600611a | 1        | 1.49%   |
| 0x06000852 | 1        | 1.49%   |
| 0x010000dc | 1        | 1.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 9        | 13.85%  |
| Haswell     | 8        | 12.31%  |
| KabyLake    | 7        | 10.77%  |
| IvyBridge   | 7        | 10.77%  |
| SandyBridge | 6        | 9.23%   |
| Zen+        | 5        | 7.69%   |
| Nehalem     | 5        | 7.69%   |
| Skylake     | 4        | 6.15%   |
| Penryn      | 4        | 6.15%   |
| Core        | 4        | 6.15%   |
| Zen         | 2        | 3.08%   |
| Excavator   | 2        | 3.08%   |
| Piledriver  | 1        | 1.54%   |
| K10         | 1        | 1.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 36       | 50%     |
| AMD    | 21       | 29.17%  |
| Intel  | 15       | 20.83%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 6.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 5.48%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 5.48%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 5.48%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 4.11%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 4.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 4.11%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 4.11%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 4.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.74%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 2.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.74%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 2        | 2.74%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.37%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.37%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 1.37%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 1.37%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.37%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.37%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 1.37%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 1.37%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.37%   |
| Nvidia GT200GL [Quadro FX 3800]                                             | 1        | 1.37%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.37%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.37%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.37%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.37%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.37%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.37%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 1.37%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.37%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 1.37%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                           | 1        | 1.37%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.37%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 1.37%   |
| Nvidia G92 [GeForce 9800 GTX+]                                              | 1        | 1.37%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 1.37%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.37%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 1        | 1.37%   |
| AMD RV790 [Radeon HD 4890]                                                  | 1        | 1.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 31       | 45.59%  |
| 1 x AMD        | 18       | 26.47%  |
| 1 x Intel      | 14       | 20.59%  |
| AMD + Nvidia   | 3        | 4.41%   |
| 2 x Nvidia     | 1        | 1.47%   |
| Intel + Nvidia | 1        | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Proprietary | 33       | 48.53%  |
| Free        | 33       | 48.53%  |
| Unknown     | 2        | 2.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 30%     |
| 1.01-2.0   | 11       | 15.71%  |
| 7.01-8.0   | 10       | 14.29%  |
| 5.01-6.0   | 8        | 11.43%  |
| 3.01-4.0   | 8        | 11.43%  |
| 0.51-1.0   | 7        | 10%     |
| 0.01-0.5   | 4        | 5.71%   |
| 8.01-16.0  | 1        | 1.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 15       | 21.43%  |
| Dell                 | 10       | 14.29%  |
| Goldstar             | 6        | 8.57%   |
| Unknown              | 5        | 7.14%   |
| Ancor Communications | 5        | 7.14%   |
| AOC                  | 4        | 5.71%   |
| LG Electronics       | 3        | 4.29%   |
| Hewlett-Packard      | 3        | 4.29%   |
| BenQ                 | 3        | 4.29%   |
| Idek Iiyama          | 2        | 2.86%   |
| Eizo                 | 2        | 2.86%   |
| Sceptre Tech         | 1        | 1.43%   |
| Pioneer Electronic   | 1        | 1.43%   |
| Philips              | 1        | 1.43%   |
| NEC Computers        | 1        | 1.43%   |
| MStar                | 1        | 1.43%   |
| MPI                  | 1        | 1.43%   |
| Medion               | 1        | 1.43%   |
| Iiyama               | 1        | 1.43%   |
| Daewoo               | 1        | 1.43%   |
| ASUSTek Computer     | 1        | 1.43%   |
| AGO                  | 1        | 1.43%   |
| Acer                 | 1        | 1.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics S27B550 SAM091B 1920x1080 598x336mm 27.0-inch      | 2        | 2.56%   |
| Samsung Electronics LCD Monitor SAM0BB4 3840x2160 890x500mm 40.2-inch  | 2        | 2.56%   |
| Samsung Electronics LCD Monitor C34H89x 3440x1440                      | 2        | 2.56%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1        | 1.28%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 1        | 1.28%   |
| Unknown LCD Monitor SAMSUNG                                            | 1        | 1.28%   |
| Unknown LCD Monitor GTW KX2153                                         | 1        | 1.28%   |
| Unknown LCD Monitor EMA E202HL                                         | 1        | 1.28%   |
| Sceptre Tech Sceptre B34 SPT0D52 2560x1080 800x340mm 34.2-inch         | 1        | 1.28%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 1        | 1.28%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch   | 1        | 1.28%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch   | 1        | 1.28%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch      | 1        | 1.28%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch      | 1        | 1.28%   |
| Samsung Electronics S24C650 SAM09E9 1920x1080 521x293mm 23.5-inch      | 1        | 1.28%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch      | 1        | 1.28%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch      | 1        | 1.28%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 410x230mm 18.5-inch  | 1        | 1.28%   |
| Samsung Electronics LCD Monitor SAM06CA 1920x1080 1110x620mm 50.1-inch | 1        | 1.28%   |
| Samsung Electronics LCD Monitor S24E310 3840x1080                      | 1        | 1.28%   |
| Samsung Electronics LCD Monitor S24E310                                | 1        | 1.28%   |
| Samsung Electronics LCD Monitor C32F391 1920x1080                      | 1        | 1.28%   |
| Pioneer Electronic LCD Monitor PDP-42FXE10 2646x768                    | 1        | 1.28%   |
| Pioneer Electronic LCD Monitor PDP-42FXE10 2390x768                    | 1        | 1.28%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 1        | 1.28%   |
| NEC Computers LCD2070NX NEC667B 1600x1200 410x310mm 20.2-inch          | 1        | 1.28%   |
| NEC Computers LCD2070NX NEC667B 1600x1200 408x306mm 20.1-inch          | 1        | 1.28%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                         | 1        | 1.28%   |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                       | 1        | 1.28%   |
| Medion MD41077EA MED078B 1280x1024 330x270mm 16.8-inch                 | 1        | 1.28%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 1        | 1.28%   |
| LG Electronics LCD Monitor LG QHD 2560x1440                            | 1        | 1.28%   |
| LG Electronics LCD Monitor 2D HD LG TV 1366x768                        | 1        | 1.28%   |
| Iiyama X2483/2481 IVM6128 1920x1080 527x296mm 23.8-inch                | 1        | 1.28%   |
| Idek Iiyama LCD Monitor X2485 1920x1200                                | 1        | 1.28%   |
| Idek Iiyama LCD Monitor PL2730H 1920x1080                              | 1        | 1.28%   |
| Hewlett-Packard w185e HWP292E 1366x768 410x230mm 18.5-inch             | 1        | 1.28%   |
| Hewlett-Packard LCD Monitor LP3065 2560x1600                           | 1        | 1.28%   |
| Hewlett-Packard L1940T HWP2682 1280x1024 338x270mm 17.0-inch           | 1        | 1.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 1        | 1.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 21       | 28.77%  |
| 3840x2160 (4K)     | 7        | 9.59%   |
| 1280x1024 (SXGA)   | 6        | 8.22%   |
| Unknown            | 6        | 8.22%   |
| 2560x1080          | 5        | 6.85%   |
| 1366x768 (WXGA)    | 5        | 6.85%   |
| 3840x1080          | 3        | 4.11%   |
| 3440x1440          | 3        | 4.11%   |
| 1920x1200 (WUXGA)  | 3        | 4.11%   |
| 1680x1050 (WSXGA+) | 3        | 4.11%   |
| 2560x1440 (QHD)    | 2        | 2.74%   |
| 3520x1080          | 1        | 1.37%   |
| 2646x768           | 1        | 1.37%   |
| 2560x1600          | 1        | 1.37%   |
| 2560x1024          | 1        | 1.37%   |
| 2390x768           | 1        | 1.37%   |
| 2048x1152          | 1        | 1.37%   |
| 1600x1200          | 1        | 1.37%   |
| 1400x1050          | 1        | 1.37%   |
| 1280x720 (HD)      | 1        | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 32.84%  |
| 27      | 9        | 13.43%  |
| 24      | 6        | 8.96%   |
| 34      | 4        | 5.97%   |
| 19      | 4        | 5.97%   |
| 23      | 3        | 4.48%   |
| 20      | 3        | 4.48%   |
| 84      | 2        | 2.99%   |
| 18      | 2        | 2.99%   |
| 17      | 2        | 2.99%   |
| 63      | 1        | 1.49%   |
| 54      | 1        | 1.49%   |
| 52      | 1        | 1.49%   |
| 28      | 1        | 1.49%   |
| 22      | 1        | 1.49%   |
| 21      | 1        | 1.49%   |
| 16      | 1        | 1.49%   |
| 15      | 1        | 1.49%   |
| 12      | 1        | 1.49%   |
| 8       | 1        | 1.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 22       | 32.84%  |
| 501-600     | 15       | 22.39%  |
| 401-500     | 8        | 11.94%  |
| 701-800     | 4        | 5.97%   |
| 601-700     | 4        | 5.97%   |
| 301-350     | 4        | 5.97%   |
| 351-400     | 3        | 4.48%   |
| 1001-1500   | 3        | 4.48%   |
| 1501-2000   | 2        | 2.99%   |
| 201-300     | 1        | 1.49%   |
| 101-200     | 1        | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 25       | 38.46%  |
| Unknown | 21       | 32.31%  |
| 5/4     | 5        | 7.69%   |
| 21/9    | 5        | 7.69%   |
| 4/3     | 4        | 6.15%   |
| 16/10   | 4        | 6.15%   |
| 6/5     | 1        | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 22       | 33.33%  |
| 301-350        | 9        | 13.64%  |
| 201-250        | 9        | 13.64%  |
| 151-200        | 6        | 9.09%   |
| More than 1000 | 5        | 7.58%   |
| 351-500        | 4        | 6.06%   |
| 141-150        | 4        | 6.06%   |
| 251-300        | 3        | 4.55%   |
| 71-80          | 1        | 1.52%   |
| 1-40           | 1        | 1.52%   |
| 131-140        | 1        | 1.52%   |
| 91-100         | 1        | 1.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 46.88%  |
| Unknown | 22       | 34.38%  |
| 1-50    | 3        | 4.69%   |
| 161-240 | 3        | 4.69%   |
| 121-160 | 3        | 4.69%   |
| 101-120 | 3        | 4.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 47       | 71.21%  |
| 2     | 14       | 21.21%  |
| 0     | 4        | 6.06%   |
| 3     | 1        | 1.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 37       | 36.27%  |
| Intel                 | 34       | 33.33%  |
| Qualcomm Atheros      | 9        | 8.82%   |
| Ralink Technology     | 5        | 4.9%    |
| Broadcom              | 5        | 4.9%    |
| NetGear               | 2        | 1.96%   |
| D-Link                | 2        | 1.96%   |
| Xiaomi                | 1        | 0.98%   |
| Wacom                 | 1        | 0.98%   |
| Ralink                | 1        | 0.98%   |
| Microsoft             | 1        | 0.98%   |
| Linksys               | 1        | 0.98%   |
| D-Link System         | 1        | 0.98%   |
| Belkin Components     | 1        | 0.98%   |
| ASIX Electronics      | 1        | 0.98%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28       | 24.14%  |
| Intel Wi-Fi 6 AX200                                               | 7        | 6.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 5.17%   |
| Intel I211 Gigabit Network Connection                             | 5        | 4.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 3.45%   |
| Intel Wireless-AC 9260                                            | 3        | 2.59%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.59%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.59%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3        | 2.59%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2        | 1.72%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 1.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 1.72%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.72%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 1.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.86%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                          | 1        | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.86%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.86%   |
| Realtek 802.11ac NIC                                              | 1        | 0.86%   |
| Ralink RT5372 Wireless Adapter                                    | 1        | 0.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.86%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1        | 0.86%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.86%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.86%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 0.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 0.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.86%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]           | 1        | 0.86%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1        | 0.86%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1        | 0.86%   |
| Microsoft XBOX ACC                                                | 1        | 0.86%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                 | 1        | 0.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 33.33%  |
| Realtek Semiconductor | 6        | 14.29%  |
| Ralink Technology     | 5        | 11.9%   |
| Qualcomm Atheros      | 4        | 9.52%   |
| Broadcom              | 3        | 7.14%   |
| NetGear               | 2        | 4.76%   |
| D-Link                | 2        | 4.76%   |
| Wacom                 | 1        | 2.38%   |
| Ralink                | 1        | 2.38%   |
| Microsoft             | 1        | 2.38%   |
| Linksys               | 1        | 2.38%   |
| D-Link System         | 1        | 2.38%   |
| Belkin Components     | 1        | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 7        | 16.28%  |
| Intel Wireless-AC 9260                                                                  | 3        | 6.98%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 3        | 6.98%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                              | 2        | 4.65%   |
| Ralink MT7601U Wireless Adapter                                                         | 2        | 4.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 2        | 4.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                                         | 2        | 4.65%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                                | 1        | 2.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                         | 1        | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                | 1        | 2.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                         | 1        | 2.33%   |
| Realtek 802.11ac NIC                                                                    | 1        | 2.33%   |
| Ralink RT5372 Wireless Adapter                                                          | 1        | 2.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                   | 1        | 2.33%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                       | 1        | 2.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                               | 1        | 2.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                        | 1        | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                          | 1        | 2.33%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                                 | 1        | 2.33%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                                         | 1        | 2.33%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                             | 1        | 2.33%   |
| Microsoft XBOX ACC                                                                      | 1        | 2.33%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                                       | 1        | 2.33%   |
| Intel Wireless 7265                                                                     | 1        | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1        | 2.33%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 2.33%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                    | 1        | 2.33%   |
| D-Link DWA-127 Wireless N 150 High-Gain Adapter(rev.A1) [Ralink RT3070]                 | 1        | 2.33%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 35       | 50%     |
| Intel                 | 26       | 37.14%  |
| Qualcomm Atheros      | 5        | 7.14%   |
| Broadcom              | 2        | 2.86%   |
| Xiaomi                | 1        | 1.43%   |
| ASIX Electronics      | 1        | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28       | 38.36%  |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 8.22%   |
| Intel I211 Gigabit Network Connection                             | 5        | 6.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 5.48%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 4.11%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 4.11%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 4.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 2.74%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.74%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.74%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 2.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.37%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.37%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.37%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 1.37%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.37%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 1.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.37%   |
| ASIX AX88772A Fast Ethernet                                       | 1        | 1.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 65       | 64.36%  |
| WiFi     | 36       | 35.64%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 67.61%  |
| WiFi     | 23       | 32.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 40       | 61.54%  |
| 2     | 18       | 27.69%  |
| 3     | 7        | 10.77%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 56       | 84.85%  |
| Yes  | 10       | 15.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 14       | 48.28%  |
| Cambridge Silicon Radio         | 7        | 24.14%  |
| Broadcom                        | 3        | 10.34%  |
| Belkin Components               | 2        | 6.9%    |
| ASUSTek Computer                | 2        | 6.9%    |
| Qualcomm Atheros Communications | 1        | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 7        | 24.14%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7        | 24.14%  |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3        | 10.34%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 6.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 6.9%    |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 2        | 6.9%    |
| Qualcomm Atheros AR3011 Bluetooth                     | 1        | 3.45%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 3.45%   |
| Intel Bluetooth wireless interface                    | 1        | 3.45%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 3.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 3.45%   |
| ASUS Bluetooth Adapter                                | 1        | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 44       | 36.97%  |
| Nvidia              | 34       | 28.57%  |
| AMD                 | 28       | 23.53%  |
| C-Media Electronics | 3        | 2.52%   |
| Logitech            | 2        | 1.68%   |
| SteelSeries ApS     | 1        | 0.84%   |
| Microsoft           | 1        | 0.84%   |
| Kingston Technology | 1        | 0.84%   |
| Focusrite-Novation  | 1        | 0.84%   |
| DSEA A/S            | 1        | 0.84%   |
| Creative Labs       | 1        | 0.84%   |
| Bose                | 1        | 0.84%   |
| Blue Microphones    | 1        | 0.84%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 5.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 4.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 3.68%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 2.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 2.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 2.94%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 2.94%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 2.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 2.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 2.94%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 2.21%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 2.21%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 2.21%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 2.21%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.47%   |
| Nvidia High Definition Audio Controller                                    | 2        | 1.47%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 1.47%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.47%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 1.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.47%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 2        | 1.47%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2        | 1.47%   |
| SteelSeries ApS SteelSeries Arctis 5                                       | 1        | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.74%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.74%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.74%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.74%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.74%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.74%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.74%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 6        | 18.18%  |
| G.Skill             | 4        | 12.12%  |
| Crucial             | 4        | 12.12%  |
| Corsair             | 4        | 12.12%  |
| Unknown             | 3        | 9.09%   |
| SK hynix            | 3        | 9.09%   |
| Samsung Electronics | 3        | 9.09%   |
| Timetec             | 1        | 3.03%   |
| Team                | 1        | 3.03%   |
| Sesame              | 1        | 3.03%   |
| Micron Technology   | 1        | 3.03%   |
| A-DATA Technology   | 1        | 3.03%   |
| Unknown             | 1        | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s   | 2        | 5.71%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 2.86%   |
| Unknown RAM Module 4096MB DIMM DDR 1066MT/s              | 1        | 2.86%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 2.86%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s              | 1        | 2.86%   |
| Unknown RAM Module 2048MB DIMM DDR 1066MT/s              | 1        | 2.86%   |
| Timetec RAM ED3-1600 8192MB DIMM DDR3 1600MT/s           | 1        | 2.86%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3007MT/s       | 1        | 2.86%   |
| SK hynix RAM Module 4096MB FB-DIMM DDR2 667MT/s          | 1        | 2.86%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2.86%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s  | 1        | 2.86%   |
| Sesame RAM S939A2UGS-ITR 8GB DIMM DDR3 1600MT/s          | 1        | 2.86%   |
| Samsung RAM M391B5673EH1-CF8 2048MB DIMM DDR3 1066MT/s   | 1        | 2.86%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s      | 1        | 2.86%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 1        | 2.86%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s     | 1        | 2.86%   |
| Kingston RAM KHX2133C11D3/4GX 4096MB DIMM DDR3 2134MT/s  | 1        | 2.86%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s      | 1        | 2.86%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s        | 1        | 2.86%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 2.86%   |
| Kingston RAM 99U5403-159.A01LF 8GB DIMM 800MT/s          | 1        | 2.86%   |
| Kingston RAM 9905403-199.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 2.86%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 1        | 2.86%   |
| G.Skill RAM F4-3200C16-8GVK 8GB DIMM DDR4 3200MT/s       | 1        | 2.86%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 1        | 2.86%   |
| G.Skill RAM F3-1600C11-4GNT 4GB DIMM DDR3 1600MT/s       | 1        | 2.86%   |
| Crucial RAM CT4G4DFS824A.M8FB 4096MB DIMM DDR4 2400MT/s  | 1        | 2.86%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s    | 1        | 2.86%   |
| Crucial RAM BLT8G3D1608DT1TX0. 8192MB DIMM DDR3 1600MT/s | 1        | 2.86%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2472MT/s    | 1        | 2.86%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s    | 1        | 2.86%   |
| Corsair RAM CMD16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s    | 1        | 2.86%   |
| A-DATA RAM DDR4 3000 16384MB DIMM DDR4 3600MT/s          | 1        | 2.86%   |
| Unknown                                                  | 1        | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR3  | 14       | 48.28%  |
| DDR4  | 11       | 37.93%  |
| SDRAM | 2        | 6.9%    |
| DDR2  | 1        | 3.45%   |
| DDR   | 1        | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 28       | 96.55%  |
| FB-DIMM | 1        | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 12       | 38.71%  |
| 4096  | 11       | 35.48%  |
| 16384 | 4        | 12.9%   |
| 2048  | 4        | 12.9%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 10       | 29.41%  |
| 3200    | 5        | 14.71%  |
| 1333    | 4        | 11.76%  |
| 3600    | 2        | 5.88%   |
| 1066    | 2        | 5.88%   |
| 3866    | 1        | 2.94%   |
| 3500    | 1        | 2.94%   |
| 3007    | 1        | 2.94%   |
| 2472    | 1        | 2.94%   |
| 2400    | 1        | 2.94%   |
| 2134    | 1        | 2.94%   |
| 2048    | 1        | 2.94%   |
| 1866    | 1        | 2.94%   |
| 1800    | 1        | 2.94%   |
| 667     | 1        | 2.94%   |
| Unknown | 1        | 2.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 66.67%  |
| Sharp  | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| Sharp AL-2030         | 1        | 33.33%  |
| Canon TR7500 series   | 1        | 33.33%  |
| Canon MF240 Series V4 | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 8        | 50%     |
| Sunplus Innovation Technology | 1        | 6.25%   |
| Realtek Semiconductor         | 1        | 6.25%   |
| OPPO Electronics              | 1        | 6.25%   |
| Microsoft                     | 1        | 6.25%   |
| LG Electronics                | 1        | 6.25%   |
| Guillemot                     | 1        | 6.25%   |
| Generalplus Technology        | 1        | 6.25%   |
| Cubeternet                    | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 2        | 12.5%   |
| Logitech Webcam B500                     | 2        | 12.5%   |
| Sunplus HD 720P webcam                   | 1        | 6.25%   |
| Realtek Web Camera                       | 1        | 6.25%   |
| OPPO Reno4 5G                            | 1        | 6.25%   |
| Microsoft LifeCam HD-3000                | 1        | 6.25%   |
| Logitech Webcam C925e                    | 1        | 6.25%   |
| Logitech Webcam C170                     | 1        | 6.25%   |
| Logitech Logitech Webcam C160            | 1        | 6.25%   |
| Logitech HD Pro Webcam C920              | 1        | 6.25%   |
| LG Optimus (Various Models) MTP Mode     | 1        | 6.25%   |
| Guillemot Hercules HD Sunset             | 1        | 6.25%   |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 6.25%   |
| Cubeternet GL-UPC822 UVC WebCam          | 1        | 6.25%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 61       | 92.42%  |
| 1     | 4        | 6.06%   |
| 9     | 1        | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 2        | 25%     |
| Graphics card            | 2        | 25%     |
| Sound                    | 1        | 12.5%   |
| Communication controller | 1        | 12.5%   |
| Camera                   | 1        | 12.5%   |
| Bluetooth                | 1        | 12.5%   |

