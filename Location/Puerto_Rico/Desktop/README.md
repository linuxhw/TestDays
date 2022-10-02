Linux in Puerto Rico - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Puerto Rico.

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

Total: 109

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Intel     | SKYBAY                      | [b667cf66e8](https://linux-hardware.org/?probe=b667cf66e8) | Sep 07, 2022 |
| ASRock    | B450M-HDV                   | [e45f2cd5d8](https://linux-hardware.org/?probe=e45f2cd5d8) | Jul 20, 2022 |
| MSI       | MS-B0A1                     | [9b53e39bad](https://linux-hardware.org/?probe=9b53e39bad) | Jul 04, 2022 |
| MSI       | MS-B0A1                     | [3193cbe3fd](https://linux-hardware.org/?probe=3193cbe3fd) | Jun 20, 2022 |
| Dell      | 0N4YC8 A00                  | [83ed9adfc1](https://linux-hardware.org/?probe=83ed9adfc1) | May 04, 2022 |
| Dell      | 0G261D A00                  | [860d883e5b](https://linux-hardware.org/?probe=860d883e5b) | Apr 29, 2022 |
| ASRock    | B450M-HDV R4.0              | [bce1bba9ff](https://linux-hardware.org/?probe=bce1bba9ff) | Apr 29, 2022 |
| Dell      | 0N4YC8 A00                  | [32cc2a24ac](https://linux-hardware.org/?probe=32cc2a24ac) | Apr 20, 2022 |
| Dell      | 0N4YC8 A00                  | [b4ea114ce4](https://linux-hardware.org/?probe=b4ea114ce4) | Apr 17, 2022 |
| Gigabyte  | B450 AORUS PRO WIFI-CF      | [656e8c50dd](https://linux-hardware.org/?probe=656e8c50dd) | Apr 13, 2022 |
| Dell      | 0N4YC8 A00                  | [c32c875fc6](https://linux-hardware.org/?probe=c32c875fc6) | Apr 10, 2022 |
| ASUSTek   | ROG STRIX B450-F GAMING     | [2315db07e2](https://linux-hardware.org/?probe=2315db07e2) | Apr 02, 2022 |
| HP        | 0AA8h                       | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| Dell      | OptiPlex 7020               | [ba82f9d852](https://linux-hardware.org/?probe=ba82f9d852) | Mar 01, 2022 |
| HP        | 0AA8h                       | [21de71cf71](https://linux-hardware.org/?probe=21de71cf71) | Feb 25, 2022 |
| ASRock    | B450M-HDV R4.0              | [f2a65b8a5f](https://linux-hardware.org/?probe=f2a65b8a5f) | Feb 14, 2022 |
| ASRock    | B450M-HDV R4.0              | [8e7267692b](https://linux-hardware.org/?probe=8e7267692b) | Jan 21, 2022 |
| Gigabyte  | X570 AORUS ELITE WIFI       | [464d10c41d](https://linux-hardware.org/?probe=464d10c41d) | Dec 22, 2021 |
| Dell      | 0R6JMP A00                  | [7bc4106877](https://linux-hardware.org/?probe=7bc4106877) | Dec 12, 2021 |
| Dell      | 0R6JMP A00                  | [2b3e03c89b](https://linux-hardware.org/?probe=2b3e03c89b) | Dec 12, 2021 |
| HP        | 1998                        | [7bc6ddebf4](https://linux-hardware.org/?probe=7bc6ddebf4) | Nov 21, 2021 |
| ASRock    | Q1900M                      | [8482ae3a2f](https://linux-hardware.org/?probe=8482ae3a2f) | Nov 09, 2021 |
| HP        | 339A                        | [e2ce00d1ec](https://linux-hardware.org/?probe=e2ce00d1ec) | Nov 08, 2021 |
| Alienware | 07W25T A00                  | [c08c87521f](https://linux-hardware.org/?probe=c08c87521f) | Nov 08, 2021 |
| Gigabyte  | J1900N-D3V                  | [29c7fa76a8](https://linux-hardware.org/?probe=29c7fa76a8) | Oct 10, 2021 |
| Gigabyte  | J1900N-D3V                  | [6818ec3abc](https://linux-hardware.org/?probe=6818ec3abc) | Oct 10, 2021 |
| ASRock    | Z270 Killer SLI/ac          | [732c00f018](https://linux-hardware.org/?probe=732c00f018) | Oct 06, 2021 |
| ASUSTek   | TUF Gaming X570-PRO         | [9ed2b3cf12](https://linux-hardware.org/?probe=9ed2b3cf12) | Sep 21, 2021 |
| ASUSTek   | TUF Gaming X570-PRO         | [a96d28c504](https://linux-hardware.org/?probe=a96d28c504) | Sep 16, 2021 |
| HP        | 1495                        | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| Pegatron  | 2ACD                        | [fd757c14ce](https://linux-hardware.org/?probe=fd757c14ce) | Jun 13, 2021 |
| HP        | 1998                        | [7b400d8da6](https://linux-hardware.org/?probe=7b400d8da6) | Jun 11, 2021 |
| HP        | 1998                        | [304ce6f1c4](https://linux-hardware.org/?probe=304ce6f1c4) | Jun 02, 2021 |
| HP        | 1998                        | [4c3248677a](https://linux-hardware.org/?probe=4c3248677a) | May 25, 2021 |
| HP        | 1998                        | [9239b61815](https://linux-hardware.org/?probe=9239b61815) | May 25, 2021 |
| HP        | 1998                        | [639725c8af](https://linux-hardware.org/?probe=639725c8af) | May 24, 2021 |
| HP        | 339A                        | [ac11f05a1a](https://linux-hardware.org/?probe=ac11f05a1a) | May 21, 2021 |
| Intel     | SKYBAY                      | [9bc7ab87d1](https://linux-hardware.org/?probe=9bc7ab87d1) | May 19, 2021 |
| ASRock    | Q1900M                      | [7c778b5654](https://linux-hardware.org/?probe=7c778b5654) | May 02, 2021 |
| HP        | 1998                        | [7442c54767](https://linux-hardware.org/?probe=7442c54767) | Apr 29, 2021 |
| HP        | 1998                        | [ec0fdacf3a](https://linux-hardware.org/?probe=ec0fdacf3a) | Apr 12, 2021 |
| HP        | 1998                        | [c395021e6a](https://linux-hardware.org/?probe=c395021e6a) | Apr 12, 2021 |
| Intel     | SKYBAY                      | [472818e347](https://linux-hardware.org/?probe=472818e347) | Apr 04, 2021 |
| HP        | 1998                        | [f515fbf660](https://linux-hardware.org/?probe=f515fbf660) | Apr 01, 2021 |
| HP        | 1998                        | [3bc0a0dcb6](https://linux-hardware.org/?probe=3bc0a0dcb6) | Mar 20, 2021 |
| HP        | 1998                        | [a10d91fc1b](https://linux-hardware.org/?probe=a10d91fc1b) | Mar 20, 2021 |
| Intel     | SKYBAY                      | [5ab0183bc4](https://linux-hardware.org/?probe=5ab0183bc4) | Mar 18, 2021 |
| Intel     | SKYBAY                      | [ecefc99ed5](https://linux-hardware.org/?probe=ecefc99ed5) | Mar 14, 2021 |
| Acer      | AAHD3.VC                    | [775057eb07](https://linux-hardware.org/?probe=775057eb07) | Feb 20, 2021 |
| Acer      | AAHD3.VC                    | [b11309575f](https://linux-hardware.org/?probe=b11309575f) | Feb 19, 2021 |
| Dell      | 0DFRFW A00                  | [093c47fb9c](https://linux-hardware.org/?probe=093c47fb9c) | Feb 13, 2021 |
| ASRock    | Q1900M                      | [d4372897b8](https://linux-hardware.org/?probe=d4372897b8) | Feb 13, 2021 |
| MSI       | H81M-P33                    | [190f14bae7](https://linux-hardware.org/?probe=190f14bae7) | Feb 13, 2021 |
| ASUSTek   | PRIME B550M-A               | [81a3e9faea](https://linux-hardware.org/?probe=81a3e9faea) | Feb 11, 2021 |
| HP        | 18E4                        | [db6eb1d366](https://linux-hardware.org/?probe=db6eb1d366) | Feb 05, 2021 |
| HP        | 18E4                        | [bad5f5110c](https://linux-hardware.org/?probe=bad5f5110c) | Feb 03, 2021 |
| ASUSTek   | M2N-E SLI                   | [b2513f813d](https://linux-hardware.org/?probe=b2513f813d) | Jan 16, 2021 |
| HP        | 18E4                        | [729391b32e](https://linux-hardware.org/?probe=729391b32e) | Jan 08, 2021 |
| ASUSTek   | ROG STRIX X570-E GAMING     | [8396553751](https://linux-hardware.org/?probe=8396553751) | Dec 26, 2020 |
| Lenovo    | ThinkCentre M58p 6136A66    | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Lenovo    | 36EE SDK0J40700 WIN 3258... | [5e4b418568](https://linux-hardware.org/?probe=5e4b418568) | Dec 19, 2020 |
| Gigabyte  | X570 GAMING X               | [646f020b0d](https://linux-hardware.org/?probe=646f020b0d) | Nov 27, 2020 |
| Gigabyte  | B450M DS3H-CF               | [844bb428a9](https://linux-hardware.org/?probe=844bb428a9) | Nov 22, 2020 |
| MSI       | MS-B1711                    | [8d69ecec16](https://linux-hardware.org/?probe=8d69ecec16) | Nov 17, 2020 |
| MSI       | MS-B1711                    | [958741b7b6](https://linux-hardware.org/?probe=958741b7b6) | Nov 17, 2020 |
| MSI       | MS-B1711                    | [3c327ae485](https://linux-hardware.org/?probe=3c327ae485) | Nov 17, 2020 |
| MSI       | MS-B1711                    | [26c2dcf112](https://linux-hardware.org/?probe=26c2dcf112) | Nov 01, 2020 |
| Gigabyte  | X570 GAMING X               | [62ebca752a](https://linux-hardware.org/?probe=62ebca752a) | Oct 31, 2020 |
| Gigabyte  | X570 GAMING X               | [362d74125d](https://linux-hardware.org/?probe=362d74125d) | Oct 31, 2020 |
| ASRock    | Q1900M                      | [72cddfd9ae](https://linux-hardware.org/?probe=72cddfd9ae) | Oct 24, 2020 |
| Dell      | 0R6JMP A00                  | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| HP        | 339A                        | [47db0521b7](https://linux-hardware.org/?probe=47db0521b7) | Sep 23, 2020 |
| HP        | 339A                        | [51cec5b6f8](https://linux-hardware.org/?probe=51cec5b6f8) | Sep 23, 2020 |
| HP        | 339A                        | [37cfc48ef8](https://linux-hardware.org/?probe=37cfc48ef8) | Sep 21, 2020 |
| HP        | 339A                        | [254f23a364](https://linux-hardware.org/?probe=254f23a364) | Sep 21, 2020 |
| Lenovo    | ThinkCentre M91p 7033CG1    | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| HP        | 18E4                        | [277593bde6](https://linux-hardware.org/?probe=277593bde6) | Aug 07, 2020 |
| Gigabyte  | F2A78M-HD2                  | [25ca74bc56](https://linux-hardware.org/?probe=25ca74bc56) | Jul 24, 2020 |
| Gigabyte  | F2A78M-HD2                  | [478381d890](https://linux-hardware.org/?probe=478381d890) | Jul 12, 2020 |
| MSI       | Z370-A PRO                  | [f8629928a6](https://linux-hardware.org/?probe=f8629928a6) | Jun 18, 2020 |
| Gigabyte  | Z97M-DS3H                   | [9aaeabab3d](https://linux-hardware.org/?probe=9aaeabab3d) | Jun 18, 2020 |
| Gigabyte  | F2A68HM-H                   | [d161c397ca](https://linux-hardware.org/?probe=d161c397ca) | Jun 14, 2020 |
| HP        | 18E4                        | [1fe1707854](https://linux-hardware.org/?probe=1fe1707854) | May 07, 2020 |
| Dell      | 0M017G A00                  | [e8b9eefb82](https://linux-hardware.org/?probe=e8b9eefb82) | Apr 13, 2020 |
| Gigabyte  | X570 GAMING X               | [44caca0bb1](https://linux-hardware.org/?probe=44caca0bb1) | Mar 12, 2020 |
| Gigabyte  | X570 GAMING X               | [c0f180f342](https://linux-hardware.org/?probe=c0f180f342) | Mar 07, 2020 |
| Gigabyte  | X399 AORUS Gaming 7         | [4ac0a3b1fe](https://linux-hardware.org/?probe=4ac0a3b1fe) | Mar 06, 2020 |
| ASRock    | G31M-S                      | [a2582aaec1](https://linux-hardware.org/?probe=a2582aaec1) | Mar 06, 2020 |
| ASRock    | G31M-S                      | [a63cd159a1](https://linux-hardware.org/?probe=a63cd159a1) | Mar 06, 2020 |
| Gigabyte  | X570 GAMING X               | [aa32ea3cb7](https://linux-hardware.org/?probe=aa32ea3cb7) | Mar 05, 2020 |
| Gigabyte  | X570 GAMING X               | [efa77a90cb](https://linux-hardware.org/?probe=efa77a90cb) | Mar 01, 2020 |
| Gigabyte  | X570 GAMING X               | [40a8750e54](https://linux-hardware.org/?probe=40a8750e54) | Feb 28, 2020 |
| Gigabyte  | X399 AORUS Gaming 7         | [399d92cf32](https://linux-hardware.org/?probe=399d92cf32) | Feb 28, 2020 |
| Gigabyte  | X399 AORUS Gaming 7         | [ddebe02bcd](https://linux-hardware.org/?probe=ddebe02bcd) | Feb 28, 2020 |
| Gigabyte  | X570 GAMING X               | [132413f9bd](https://linux-hardware.org/?probe=132413f9bd) | Feb 21, 2020 |
| HP        | 18E4                        | [ee3dae8f72](https://linux-hardware.org/?probe=ee3dae8f72) | Feb 17, 2020 |
| Gigabyte  | X570 GAMING X               | [fa684e430c](https://linux-hardware.org/?probe=fa684e430c) | Feb 13, 2020 |
| MSI       | B150 PC MATE                | [ed98074061](https://linux-hardware.org/?probe=ed98074061) | Oct 08, 2019 |
| ASRock    | G31M-S                      | [d1f69377d4](https://linux-hardware.org/?probe=d1f69377d4) | Aug 18, 2019 |
| ASRock    | G31M-S                      | [595867810d](https://linux-hardware.org/?probe=595867810d) | Aug 18, 2019 |
| ASRock    | G31M-S                      | [556d0f2ca6](https://linux-hardware.org/?probe=556d0f2ca6) | Jun 06, 2019 |
| ASRock    | 945GCM-S                    | [d4ea4c5cb6](https://linux-hardware.org/?probe=d4ea4c5cb6) | May 04, 2019 |
| HP        | 18E4                        | [36f9656af0](https://linux-hardware.org/?probe=36f9656af0) | Feb 15, 2019 |
| HP        | 18E4                        | [c6cf9c7817](https://linux-hardware.org/?probe=c6cf9c7817) | Jan 04, 2019 |
| ASUSTek   | M5A78L-M LX PLUS            | [85398272dc](https://linux-hardware.org/?probe=85398272dc) | Dec 03, 2018 |
| ASUSTek   | M5A78L-M LX PLUS            | [10a5b1559d](https://linux-hardware.org/?probe=10a5b1559d) | Dec 03, 2018 |
| ASRock    | G31M-S                      | [82229858ec](https://linux-hardware.org/?probe=82229858ec) | Jun 15, 2018 |
| ASRock    | G31M-S                      | [90f397422e](https://linux-hardware.org/?probe=90f397422e) | Jun 15, 2018 |
| ASRock    | 945GCM-S                    | [c7cbed362d](https://linux-hardware.org/?probe=c7cbed362d) | May 27, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 6        | 8.96%   |
| Ubuntu 18.04        | 6        | 8.96%   |
| OpenMandriva 4.2    | 4        | 5.97%   |
| Manjaro             | 3        | 4.48%   |
| Zorin 15            | 2        | 2.99%   |
| Ubuntu 20.10        | 2        | 2.99%   |
| ROSA R11            | 2        | 2.99%   |
| OpenMandriva 4.3    | 2        | 2.99%   |
| Lubuntu 20.04       | 2        | 2.99%   |
| LMDE 4              | 2        | 2.99%   |
| Linux Mint 20.3     | 2        | 2.99%   |
| Linux Mint 20.1     | 2        | 2.99%   |
| Linux Mint 20       | 2        | 2.99%   |
| Garuda Linux        | 2        | 2.99%   |
| ArcoLinux Rolling   | 2        | 2.99%   |
| Zorin 16            | 1        | 1.49%   |
| Xubuntu 20.10       | 1        | 1.49%   |
| Xubuntu 20.04       | 1        | 1.49%   |
| Ubuntu Budgie 21.04 | 1        | 1.49%   |
| Ubuntu 21.10        | 1        | 1.49%   |
| Ubuntu 19.10        | 1        | 1.49%   |
| ROSA R9             | 1        | 1.49%   |
| ROSA R10            | 1        | 1.49%   |
| Pop!_OS 21.10       | 1        | 1.49%   |
| Pop!_OS 21.04       | 1        | 1.49%   |
| Pop!_OS 20.10       | 1        | 1.49%   |
| Pop!_OS 20.04       | 1        | 1.49%   |
| Pop!_OS 19.10       | 1        | 1.49%   |
| Manjaro 21.1.5      | 1        | 1.49%   |
| Manjaro 20.1.2      | 1        | 1.49%   |
| LinuxFX 11          | 1        | 1.49%   |
| Linux Mint 20.2     | 1        | 1.49%   |
| Linux Mint 19.3     | 1        | 1.49%   |
| Linux Mint 19.1     | 1        | 1.49%   |
| KDE neon 20.04      | 1        | 1.49%   |
| Fedora 36           | 1        | 1.49%   |
| Endless 3.9.1       | 1        | 1.49%   |
| Devuan 4            | 1        | 1.49%   |
| Debian 9            | 1        | 1.49%   |
| BlackPanther 18.1   | 1        | 1.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 16       | 25.81%  |
| OpenMandriva  | 6        | 9.68%   |
| Linux Mint    | 6        | 9.68%   |
| Pop!_OS       | 5        | 8.06%   |
| Manjaro       | 4        | 6.45%   |
| Zorin         | 3        | 4.84%   |
| ROSA          | 3        | 4.84%   |
| Xubuntu       | 2        | 3.23%   |
| Lubuntu       | 2        | 3.23%   |
| LMDE          | 2        | 3.23%   |
| Garuda Linux  | 2        | 3.23%   |
| ArcoLinux     | 2        | 3.23%   |
| Ubuntu Budgie | 1        | 1.61%   |
| LinuxFX       | 1        | 1.61%   |
| KDE neon      | 1        | 1.61%   |
| Fedora        | 1        | 1.61%   |
| Endless       | 1        | 1.61%   |
| Devuan        | 1        | 1.61%   |
| Debian        | 1        | 1.61%   |
| BlackPanther  | 1        | 1.61%   |
| Arch          | 1        | 1.61%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002       | 4        | 5.19%   |
| 5.8.18-1-MANJARO               | 2        | 2.6%    |
| 5.8.0-45-generic               | 2        | 2.6%    |
| 5.4.0-72-generic               | 2        | 2.6%    |
| 5.4.0-58-generic               | 2        | 2.6%    |
| 5.4.0-109-generic              | 2        | 2.6%    |
| 5.16.7-desktop-1omv4003        | 2        | 2.6%    |
| 5.13.0-39-generic              | 2        | 2.6%    |
| 4.15.0-desktop-45.1rosa-x86_64 | 2        | 2.6%    |
| 5.9.16-1-MANJARO               | 1        | 1.3%    |
| 5.9.1-1-MANJARO                | 1        | 1.3%    |
| 5.8.5-zen1-1-zen               | 1        | 1.3%    |
| 5.8.14-zen1-1-zen              | 1        | 1.3%    |
| 5.8.0-7630-generic             | 1        | 1.3%    |
| 5.8.0-54-generic               | 1        | 1.3%    |
| 5.8.0-53-generic               | 1        | 1.3%    |
| 5.8.0-49-generic               | 1        | 1.3%    |
| 5.8.0-44-generic               | 1        | 1.3%    |
| 5.8.0-29-generic               | 1        | 1.3%    |
| 5.8.0-25-generic               | 1        | 1.3%    |
| 5.8.0-14-generic               | 1        | 1.3%    |
| 5.4.0-89-generic               | 1        | 1.3%    |
| 5.4.0-88-generic               | 1        | 1.3%    |
| 5.4.0-7634-generic             | 1        | 1.3%    |
| 5.4.0-73-generic               | 1        | 1.3%    |
| 5.4.0-65-generic               | 1        | 1.3%    |
| 5.4.0-59-generic               | 1        | 1.3%    |
| 5.4.0-52-generic               | 1        | 1.3%    |
| 5.4.0-48-generic               | 1        | 1.3%    |
| 5.4.0-47-generic               | 1        | 1.3%    |
| 5.4.0-42-generic               | 1        | 1.3%    |
| 5.4.0-40-generic               | 1        | 1.3%    |
| 5.4.0-37-generic               | 1        | 1.3%    |
| 5.4.0-125-generic              | 1        | 1.3%    |
| 5.3.0-7629-generic             | 1        | 1.3%    |
| 5.3.0-51-generic               | 1        | 1.3%    |
| 5.3.0-42-generic               | 1        | 1.3%    |
| 5.3.0-41-generic               | 1        | 1.3%    |
| 5.3.0-29-generic               | 1        | 1.3%    |
| 5.3.0-28-generic               | 1        | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 17       | 25%     |
| 5.8.0   | 8        | 11.76%  |
| 4.15.0  | 6        | 8.82%   |
| 5.11.0  | 4        | 5.88%   |
| 5.10.14 | 4        | 5.88%   |
| 5.3.0   | 3        | 4.41%   |
| 5.8.18  | 2        | 2.94%   |
| 5.16.7  | 2        | 2.94%   |
| 5.13.0  | 2        | 2.94%   |
| 4.19.0  | 2        | 2.94%   |
| 4.18.0  | 2        | 2.94%   |
| 5.9.16  | 1        | 1.47%   |
| 5.9.1   | 1        | 1.47%   |
| 5.8.5   | 1        | 1.47%   |
| 5.8.14  | 1        | 1.47%   |
| 5.18.9  | 1        | 1.47%   |
| 5.18.5  | 1        | 1.47%   |
| 5.17.1  | 1        | 1.47%   |
| 5.15.5  | 1        | 1.47%   |
| 5.14.8  | 1        | 1.47%   |
| 5.13.19 | 1        | 1.47%   |
| 5.11.13 | 1        | 1.47%   |
| 5.10.0  | 1        | 1.47%   |
| 4.9.60  | 1        | 1.47%   |
| 4.9.20  | 1        | 1.47%   |
| 4.9.0   | 1        | 1.47%   |
| 4.18.16 | 1        | 1.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 17       | 26.15%  |
| 5.8     | 12       | 18.46%  |
| 4.15    | 6        | 9.23%   |
| 5.10    | 5        | 7.69%   |
| 5.11    | 4        | 6.15%   |
| 5.3     | 3        | 4.62%   |
| 5.13    | 3        | 4.62%   |
| 4.9     | 3        | 4.62%   |
| 5.9     | 2        | 3.08%   |
| 5.16    | 2        | 3.08%   |
| 4.19    | 2        | 3.08%   |
| 4.18    | 2        | 3.08%   |
| 5.18    | 1        | 1.54%   |
| 5.17    | 1        | 1.54%   |
| 5.15    | 1        | 1.54%   |
| 5.14    | 1        | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 50       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 25       | 40.32%  |
| KDE5       | 12       | 19.35%  |
| X-Cinnamon | 7        | 11.29%  |
| XFCE       | 4        | 6.45%   |
| Unknown    | 4        | 6.45%   |
| LXQt       | 2        | 3.23%   |
| KDE        | 2        | 3.23%   |
| Budgie     | 2        | 3.23%   |
| MATE       | 1        | 1.61%   |
| LXDE       | 1        | 1.61%   |
| KDE4       | 1        | 1.61%   |
| Deepin     | 1        | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 47       | 94%     |
| Wayland | 2        | 4%      |
| Unknown | 1        | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 37       | 64.91%  |
| SDDM    | 9        | 15.79%  |
| GDM     | 4        | 7.02%   |
| GDM3    | 3        | 5.26%   |
| LightDM | 2        | 3.51%   |
| TDM     | 1        | 1.75%   |
| KDM     | 1        | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 42       | 82.35%  |
| Unknown | 7        | 13.73%  |
| es_ES   | 1        | 1.96%   |
| C       | 1        | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 31       | 57.41%  |
| EFI  | 23       | 42.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 42       | 76.36%  |
| Overlay | 8        | 14.55%  |
| Unknown | 3        | 5.45%   |
| Btrfs   | 2        | 3.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 40       | 72.73%  |
| GPT     | 9        | 16.36%  |
| MBR     | 6        | 10.91%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 83.33%  |
| Yes       | 9        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 78.18%  |
| Yes       | 12       | 21.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 9        | 18%     |
| ASRock              | 8        | 16%     |
| MSI                 | 6        | 12%     |
| Hewlett-Packard     | 6        | 12%     |
| Dell                | 6        | 12%     |
| ASUSTek Computer    | 6        | 12%     |
| Lenovo              | 3        | 6%      |
| Intel               | 3        | 6%      |
| Pegatron            | 1        | 2%      |
| Alienware           | 1        | 2%      |
| Acer                | 1        | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel SKYBAY                            | 3        | 6%      |
| MSI Cubi N 8GL (MS-B171)                | 2        | 4%      |
| ASRock Q1900M                           | 2        | 4%      |
| ASRock 945GCM-S                         | 2        | 4%      |
| Pegatron QW716AA#ABA                    | 1        | 2%      |
| MSI MS-7B48                             | 1        | 2%      |
| MSI MS-7971                             | 1        | 2%      |
| MSI MS-7817                             | 1        | 2%      |
| MSI Cubi N JSL (MS-B0A1)                | 1        | 2%      |
| Lenovo ThinkCentre M91p 7033CG1         | 1        | 2%      |
| Lenovo ThinkCentre M58p 6136A66         | 1        | 2%      |
| Lenovo IdeaCentre 510A-15ARR 90J0000PUS | 1        | 2%      |
| HP EliteDesk 800 G1 TWR                 | 1        | 2%      |
| HP EliteDesk 800 G1 SFF                 | 1        | 2%      |
| HP Compaq Pro 6300 SFF                  | 1        | 2%      |
| HP Compaq Pro 6300 MT                   | 1        | 2%      |
| HP Compaq dc7800p Small Form Factor     | 1        | 2%      |
| HP Compaq 8200 Elite SFF PC             | 1        | 2%      |
| Gigabyte Z97M-DS3H                      | 1        | 2%      |
| Gigabyte X570 GAMING X                  | 1        | 2%      |
| Gigabyte X570 AORUS ELITE WIFI          | 1        | 2%      |
| Gigabyte X399 AORUS Gaming 7            | 1        | 2%      |
| Gigabyte J1900N-D3V                     | 1        | 2%      |
| Gigabyte F2A78M-HD2                     | 1        | 2%      |
| Gigabyte F2A68HM-H                      | 1        | 2%      |
| Gigabyte B450M DS3H                     | 1        | 2%      |
| Gigabyte B450 AORUS PRO WIFI            | 1        | 2%      |
| Dell Studio 540                         | 1        | 2%      |
| Dell OptiPlex 960                       | 1        | 2%      |
| Dell OptiPlex 9020                      | 1        | 2%      |
| Dell OptiPlex 780                       | 1        | 2%      |
| Dell OptiPlex 7020                      | 1        | 2%      |
| Dell Inspiron 3670                      | 1        | 2%      |
| ASUS TUF Gaming X570-PRO                | 1        | 2%      |
| ASUS ROG STRIX X570-E GAMING            | 1        | 2%      |
| ASUS ROG STRIX B450-F GAMING            | 1        | 2%      |
| ASUS PRIME B550M-A                      | 1        | 2%      |
| ASUS M5A78L-M LX PLUS                   | 1        | 2%      |
| ASUS M2N-E SLI                          | 1        | 2%      |
| ASRock Z270 Killer SLI/ac               | 1        | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP Compaq            | 4        | 8%      |
| Dell OptiPlex        | 4        | 8%      |
| MSI Cubi             | 3        | 6%      |
| Intel SKYBAY         | 3        | 6%      |
| Lenovo ThinkCentre   | 2        | 4%      |
| HP EliteDesk         | 2        | 4%      |
| Gigabyte X570        | 2        | 4%      |
| ASUS ROG             | 2        | 4%      |
| ASRock Q1900M        | 2        | 4%      |
| ASRock B450M-HDV     | 2        | 4%      |
| ASRock 945GCM-S      | 2        | 4%      |
| Pegatron QW716AA#ABA | 1        | 2%      |
| MSI MS-7B48          | 1        | 2%      |
| MSI MS-7971          | 1        | 2%      |
| MSI MS-7817          | 1        | 2%      |
| Lenovo IdeaCentre    | 1        | 2%      |
| Gigabyte Z97M-DS3H   | 1        | 2%      |
| Gigabyte X399        | 1        | 2%      |
| Gigabyte J1900N-D3V  | 1        | 2%      |
| Gigabyte F2A78M-HD2  | 1        | 2%      |
| Gigabyte F2A68HM-H   | 1        | 2%      |
| Gigabyte B450M       | 1        | 2%      |
| Gigabyte B450        | 1        | 2%      |
| Dell Studio          | 1        | 2%      |
| Dell Inspiron        | 1        | 2%      |
| ASUS TUF             | 1        | 2%      |
| ASUS PRIME           | 1        | 2%      |
| ASUS M5A78L-M        | 1        | 2%      |
| ASUS M2N-E           | 1        | 2%      |
| ASRock Z270          | 1        | 2%      |
| ASRock G31M-S        | 1        | 2%      |
| Alienware Aurora     | 1        | 2%      |
| Acer Aspire          | 1        | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 11       | 22%     |
| 2019 | 5        | 10%     |
| 2014 | 5        | 10%     |
| 2008 | 5        | 10%     |
| 2013 | 4        | 8%      |
| 2011 | 4        | 8%      |
| 2021 | 2        | 4%      |
| 2020 | 2        | 4%      |
| 2017 | 2        | 4%      |
| 2016 | 2        | 4%      |
| 2015 | 2        | 4%      |
| 2012 | 2        | 4%      |
| 2010 | 1        | 2%      |
| 2009 | 1        | 2%      |
| 2007 | 1        | 2%      |
| 2006 | 1        | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 50       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 49       | 96.08%  |
| Enabled  | 2        | 3.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 50       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 12       | 23.08%  |
| 16.01-24.0  | 10       | 19.23%  |
| 3.01-4.0    | 9        | 17.31%  |
| 8.01-16.0   | 9        | 17.31%  |
| 32.01-64.0  | 6        | 11.54%  |
| 24.01-32.0  | 2        | 3.85%   |
| 64.01-256.0 | 2        | 3.85%   |
| 1.01-2.0    | 2        | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 26       | 41.94%  |
| 2.01-3.0  | 12       | 19.35%  |
| 3.01-4.0  | 9        | 14.52%  |
| 4.01-8.0  | 8        | 12.9%   |
| 0.51-1.0  | 5        | 8.06%   |
| 8.01-16.0 | 2        | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 49.09%  |
| 2      | 12       | 21.82%  |
| 3      | 10       | 18.18%  |
| 4      | 3        | 5.45%   |
| 6      | 1        | 1.82%   |
| 5      | 1        | 1.82%   |
| 0      | 1        | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 31       | 62%     |
| No        | 19       | 38%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 50       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 53.85%  |
| No        | 24       | 46.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 56.6%   |
| Yes       | 23       | 43.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Puerto Rico | 50       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| San Juan      | 14       | 24.56%  |
| Bayamón      | 10       | 17.54%  |
| Carolina      | 3        | 5.26%   |
| Caguas        | 3        | 5.26%   |
| Aguadilla     | 3        | 5.26%   |
| Vega Alta     | 2        | 3.51%   |
| Dorado        | 2        | 3.51%   |
| Cayey         | 2        | 3.51%   |
| San Sebastian | 1        | 1.75%   |
| Sabana Grande | 1        | 1.75%   |
| Ponce         | 1        | 1.75%   |
| Patillas      | 1        | 1.75%   |
| Morovis       | 1        | 1.75%   |
| Mayagüez     | 1        | 1.75%   |
| Maunabo       | 1        | 1.75%   |
| Las Piedras   | 1        | 1.75%   |
| Humacao       | 1        | 1.75%   |
| Hatillo       | 1        | 1.75%   |
| Gurabo        | 1        | 1.75%   |
| Guayama       | 1        | 1.75%   |
| Garrochales   | 1        | 1.75%   |
| Fajardo       | 1        | 1.75%   |
| Ensenada      | 1        | 1.75%   |
| Coamo         | 1        | 1.75%   |
| Catano        | 1        | 1.75%   |
| Barceloneta   | 1        | 1.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 18       | 56     | 23.68%  |
| Seagate                   | 15       | 28     | 19.74%  |
| Toshiba                   | 8        | 11     | 10.53%  |
| Samsung Electronics       | 6        | 14     | 7.89%   |
| China                     | 4        | 6      | 5.26%   |
| Micron/Crucial Technology | 3        | 4      | 3.95%   |
| TDAS                      | 2        | 10     | 2.63%   |
| Silicon Motion            | 2        | 2      | 2.63%   |
| SanDisk                   | 2        | 2      | 2.63%   |
| SABRENT                   | 2        | 3      | 2.63%   |
| Phison                    | 2        | 2      | 2.63%   |
| LITEONIT                  | 2        | 2      | 2.63%   |
| Hitachi                   | 2        | 2      | 2.63%   |
| Crucial                   | 2        | 2      | 2.63%   |
| WD MediaMax               | 1        | 3      | 1.32%   |
| Unknown                   | 1        | 2      | 1.32%   |
| Team                      | 1        | 1      | 1.32%   |
| JMicron Technology        | 1        | 4      | 1.32%   |
| addlink                   | 1        | 1      | 1.32%   |
| A-DATA Technology         | 1        | 5      | 1.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB               | 3        | 3.45%   |
| WDC WDBNCE2500PNC 250GB SSD          | 2        | 2.3%    |
| WDC WD5000LPLX-22ZNTT0 500GB         | 2        | 2.3%    |
| Toshiba DT01ACA050 500GB             | 2        | 2.3%    |
| TDAS TerraMaster 1TB                 | 2        | 2.3%    |
| Seagate ST320DM001 HD322GJ 320GB     | 2        | 2.3%    |
| Seagate ST2000VM003-1CT164 2TB       | 2        | 2.3%    |
| Seagate Expansion 1TB                | 2        | 2.3%    |
| Samsung SSD 850 EVO 500GB            | 2        | 2.3%    |
| Samsung NVMe SSD Drive 500GB         | 2        | 2.3%    |
| SABRENT Disk 1TB                     | 2        | 2.3%    |
| Micron/Crucial NVMe SSD Drive 500GB  | 2        | 2.3%    |
| China SATA SSD 512GB                 | 2        | 2.3%    |
| WDC WD7500BPVX-60JC3T0 752GB         | 1        | 1.15%   |
| WDC WD5000LPCX-00VHAT0 500GB         | 1        | 1.15%   |
| WDC WD40EZRZ-22GXCB0 4TB             | 1        | 1.15%   |
| WDC WD30EZRZ-00WN9B0 3TB             | 1        | 1.15%   |
| WDC WD2500BPVT-22ZEST0 250GB         | 1        | 1.15%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1        | 1.15%   |
| WDC WD1600AAJS-00PSA0 160GB          | 1        | 1.15%   |
| WDC WD1500HLFS-01G6U1 150GB          | 1        | 1.15%   |
| WDC WD1200BEVS-75UST0 120GB          | 1        | 1.15%   |
| WDC WD10SPZX-22Z10T1 1TB             | 1        | 1.15%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1        | 1.15%   |
| WDC WD10EZEX-75WN4A1 1TB             | 1        | 1.15%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 1.15%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 1.15%   |
| WDC WD10EURX-63FH1Y0 1TB             | 1        | 1.15%   |
| WDC WD10EAVS-00D7B1 1TB              | 1        | 1.15%   |
| WDC WD1003FBYZ-010FB0 1TB            | 1        | 1.15%   |
| WDC WD1003FBYX-05Y7B0 1TB            | 1        | 1.15%   |
| WD MediaMax WL500GSA3272 500GB       | 1        | 1.15%   |
| Unknown Externa 250GB                | 1        | 1.15%   |
| Toshiba NVMe SSD Drive 128GB         | 1        | 1.15%   |
| Toshiba MQ01ABD100 1TB               | 1        | 1.15%   |
| Toshiba DT01ABA100V 1TB              | 1        | 1.15%   |
| Team TM8FP6512G 512GB                | 1        | 1.15%   |
| Silicon Motion NVMe SSD Drive 250GB  | 1        | 1.15%   |
| Silicon Motion NVMe SSD Drive 1024GB | 1        | 1.15%   |
| Seagate ST9500423AS 500GB            | 1        | 1.15%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 52     | 39.02%  |
| Seagate             | 15       | 28     | 36.59%  |
| Toshiba             | 7        | 10     | 17.07%  |
| Hitachi             | 2        | 2      | 4.88%   |
| Samsung Electronics | 1        | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 7      | 25%     |
| China               | 4        | 6      | 25%     |
| WDC                 | 2        | 4      | 12.5%   |
| LITEONIT            | 2        | 2      | 12.5%   |
| Crucial             | 2        | 2      | 12.5%   |
| SanDisk             | 1        | 1      | 6.25%   |
| A-DATA Technology   | 1        | 5      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 36       | 93     | 52.17%  |
| SSD     | 16       | 27     | 23.19%  |
| NVMe    | 12       | 21     | 17.39%  |
| Unknown | 5        | 19     | 7.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 45       | 120    | 69.23%  |
| NVMe | 12       | 18     | 18.46%  |
| SAS  | 8        | 22     | 12.31%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 25       | 41     | 41.67%  |
| 0.51-1.0   | 23       | 51     | 38.33%  |
| 1.01-2.0   | 8        | 19     | 13.33%  |
| 3.01-4.0   | 3        | 8      | 5%      |
| 2.01-3.0   | 1        | 1      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 13       | 20.63%  |
| 101-250        | 9        | 14.29%  |
| 501-1000       | 9        | 14.29%  |
| 2001-3000      | 8        | 12.7%   |
| 1001-2000      | 8        | 12.7%   |
| More than 3000 | 7        | 11.11%  |
| 1-20           | 5        | 7.94%   |
| 51-100         | 2        | 3.17%   |
| Unknown        | 2        | 3.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 21       | 33.33%  |
| 21-50     | 10       | 15.87%  |
| 251-500   | 7        | 11.11%  |
| 101-250   | 6        | 9.52%   |
| 1001-2000 | 6        | 9.52%   |
| 501-1000  | 5        | 7.94%   |
| 51-100    | 5        | 7.94%   |
| Unknown   | 2        | 3.17%   |
| 2001-3000 | 1        | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST3320613AS 320GB        | 1        | 1      | 16.67%  |
| Seagate ST3250310AS 250GB        | 1        | 1      | 16.67%  |
| Seagate ST320DM001 HD322GJ 320GB | 1        | 1      | 16.67%  |
| Seagate ST2000VM003-1CT164 2TB   | 1        | 1      | 16.67%  |
| Seagate ST2000LM007-1R8174 2TB   | 1        | 1      | 16.67%  |
| Seagate ST2000DL001-9VT156 2TB   | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 6      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 6      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 6      | 100%    |

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
| Detected | 40       | 136    | 71.43%  |
| Works    | 12       | 18     | 21.43%  |
| Malfunc  | 4        | 6      | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 32       | 50.79%  |
| AMD                          | 17       | 26.98%  |
| Silicon Motion               | 3        | 4.76%   |
| Phison Electronics           | 3        | 4.76%   |
| Micron/Crucial Technology    | 3        | 4.76%   |
| Samsung Electronics          | 2        | 3.17%   |
| Toshiba America Info Systems | 1        | 1.59%   |
| SanDisk                      | 1        | 1.59%   |
| Nvidia                       | 1        | 1.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 16.67%  |
| Intel SATA Controller [RAID mode]                                                       | 5        | 5.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 5.95%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 5.95%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 3.57%   |
| Phison E12 NVMe Controller                                                              | 3        | 3.57%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 3.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 3.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 3.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 3.57%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 3.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 2.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 2.38%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 2.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.38%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1        | 1.19%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.19%   |
| Nvidia CK804 Serial ATA Controller                                                      | 1        | 1.19%   |
| Nvidia CK804 IDE                                                                        | 1        | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.19%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 1        | 1.19%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 1.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.19%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                                   | 1        | 1.19%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.19%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 1.19%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.19%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.19%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.19%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.19%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.19%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.19%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.19%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.19%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 36       | 52.94%  |
| IDE  | 14       | 20.59%  |
| NVMe | 12       | 17.65%  |
| RAID | 6        | 8.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 32       | 64%     |
| AMD    | 18       | 36%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz              | 3        | 6%      |
| Intel Celeron CPU 3865U @ 1.80GHz              | 3        | 6%      |
| Intel Pentium Silver N5000 CPU @ 1.10GHz       | 2        | 4%      |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 2        | 4%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 2        | 4%      |
| Intel Celeron CPU E1200 @ 1.60GHz              | 2        | 4%      |
| AMD Ryzen 7 3700X 8-Core Processor             | 2        | 4%      |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 4%      |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 2        | 4%      |
| AMD A6-5400K APU with Radeon HD Graphics       | 2        | 4%      |
| Intel Pentium Silver N6000 @ 1.10GHz           | 1        | 2%      |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 2%      |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 2%      |
| Intel Core i7-4770 CPU @ 3.40GHz               | 1        | 2%      |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 2%      |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 2%      |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1        | 2%      |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 2%      |
| Intel Core i3-4150 CPU @ 3.50GHz               | 1        | 2%      |
| Intel Core i3-3240 CPU @ 3.40GHz               | 1        | 2%      |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1        | 2%      |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 2%      |
| Intel Core i3-2100 CPU @ 3.10GHz               | 1        | 2%      |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz           | 1        | 2%      |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz           | 1        | 2%      |
| Intel Celeron CPU G1850 @ 2.90GHz              | 1        | 2%      |
| Intel Celeron CPU G1840 @ 2.80GHz              | 1        | 2%      |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz       | 1        | 2%      |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 2%      |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 2%      |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 2%      |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 2%      |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1        | 2%      |
| AMD FX-8350 Eight-Core Processor               | 1        | 2%      |
| AMD Athlon 64 X2 Dual Core Processor 6400+     | 1        | 2%      |
| AMD Athlon 220GE with Radeon Vega Graphics     | 1        | 2%      |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G  | 1        | 2%      |
| AMD A8-3850 APU with Radeon HD Graphics        | 1        | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 10       | 20%     |
| Intel Core i3           | 5        | 10%     |
| Intel Core i5           | 4        | 8%      |
| Intel Core 2 Duo        | 4        | 8%      |
| AMD Ryzen 7             | 4        | 8%      |
| Intel Pentium Silver    | 3        | 6%      |
| Intel Core i7           | 3        | 6%      |
| AMD Ryzen 5             | 3        | 6%      |
| AMD Ryzen 3             | 3        | 6%      |
| Intel Pentium Dual-Core | 2        | 4%      |
| AMD A8                  | 2        | 4%      |
| AMD A6                  | 2        | 4%      |
| Other                   | 1        | 2%      |
| AMD Ryzen Threadripper  | 1        | 2%      |
| AMD FX                  | 1        | 2%      |
| AMD Athlon 64 X2        | 1        | 2%      |
| AMD Athlon              | 1        | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 21       | 42%     |
| 4      | 16       | 32%     |
| 8      | 5        | 10%     |
| 6      | 5        | 10%     |
| 1      | 2        | 4%      |
| 16     | 1        | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 50       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 29       | 58%     |
| 2      | 21       | 42%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 50       | 98.04%  |
| Unknown        | 1        | 1.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 25.93%  |
| 0x306c3    | 6        | 11.11%  |
| 0x1067a    | 4        | 7.41%   |
| 0x806e9    | 3        | 5.56%   |
| 0x6fd      | 2        | 3.7%    |
| 0x306a9    | 2        | 3.7%    |
| 0x30678    | 2        | 3.7%    |
| 0x08701013 | 2        | 3.7%    |
| 0x06001119 | 2        | 3.7%    |
| 0xa0671    | 1        | 1.85%   |
| 0x906ed    | 1        | 1.85%   |
| 0x906ea    | 1        | 1.85%   |
| 0x906e9    | 1        | 1.85%   |
| 0x906c0    | 1        | 1.85%   |
| 0x706a1    | 1        | 1.85%   |
| 0x6fb      | 1        | 1.85%   |
| 0x506e3    | 1        | 1.85%   |
| 0x30679    | 1        | 1.85%   |
| 0x206a7    | 1        | 1.85%   |
| 0x0810100b | 1        | 1.85%   |
| 0x08101007 | 1        | 1.85%   |
| 0x0800820d | 1        | 1.85%   |
| 0x08001137 | 1        | 1.85%   |
| 0x06003106 | 1        | 1.85%   |
| 0x06000852 | 1        | 1.85%   |
| 0x03000027 | 1        | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 6        | 12%     |
| Haswell       | 6        | 12%     |
| Penryn        | 5        | 10%     |
| Zen 2         | 4        | 8%      |
| Zen           | 4        | 8%      |
| Zen+          | 3        | 6%      |
| Silvermont    | 3        | 6%      |
| Piledriver    | 3        | 6%      |
| Core          | 3        | 6%      |
| SandyBridge   | 2        | 4%      |
| IvyBridge     | 2        | 4%      |
| Goldmont plus | 2        | 4%      |
| Zen 3         | 1        | 2%      |
| Tremont       | 1        | 2%      |
| Steamroller   | 1        | 2%      |
| Skylake       | 1        | 2%      |
| K8 Hammer     | 1        | 2%      |
| K10 Llano     | 1        | 2%      |
| Unknown       | 1        | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 28       | 50.91%  |
| Nvidia | 15       | 27.27%  |
| AMD    | 12       | 21.82%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 8.47%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 6.78%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                        | 3        | 5.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3        | 5.08%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 3.39%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.39%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 3.39%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 2        | 3.39%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 2        | 3.39%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 3.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.39%   |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 2        | 3.39%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 3.39%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.69%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.69%   |
| Nvidia GK110GL [Tesla K20Xm]                                                | 1        | 1.69%   |
| Nvidia GK104GL [GRID K2]                                                    | 1        | 1.69%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.69%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 1.69%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 1        | 1.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.69%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 1.69%   |
| Intel HD Graphics 630                                                       | 1        | 1.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.69%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.69%   |
| AMD Sumo [Radeon HD 6550D]                                                  | 1        | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.69%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 1.69%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.69%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 1.69%   |
| AMD Cezanne                                                                 | 1        | 1.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.69%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                               | 1        | 1.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 25       | 48.08%  |
| 1 x AMD            | 12       | 23.08%  |
| 1 x Nvidia         | 11       | 21.15%  |
| Intel + 2 x Nvidia | 2        | 3.85%   |
| Intel + Nvidia     | 2        | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 39       | 75%     |
| Proprietary | 10       | 19.23%  |
| Unknown     | 3        | 5.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 56.36%  |
| 1.01-2.0   | 6        | 10.91%  |
| 0.01-0.5   | 6        | 10.91%  |
| 0.51-1.0   | 4        | 7.27%   |
| 3.01-4.0   | 3        | 5.45%   |
| 5.01-6.0   | 2        | 3.64%   |
| 8.01-16.0  | 2        | 3.64%   |
| 7.01-8.0   | 1        | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 7        | 12.28%  |
| Acer                 | 6        | 10.53%  |
| Samsung Electronics  | 5        | 8.77%   |
| Hewlett-Packard      | 5        | 8.77%   |
| Dell                 | 4        | 7.02%   |
| ViewSonic            | 3        | 5.26%   |
| Sony                 | 3        | 5.26%   |
| Sceptre Tech         | 3        | 5.26%   |
| Gateway              | 3        | 5.26%   |
| Element              | 3        | 5.26%   |
| Vizio                | 2        | 3.51%   |
| VIZ                  | 2        | 3.51%   |
| Tech Concepts        | 2        | 3.51%   |
| AOC                  | 2        | 3.51%   |
| Unknown              | 1        | 1.75%   |
| UGD                  | 1        | 1.75%   |
| Seiki                | 1        | 1.75%   |
| MStar                | 1        | 1.75%   |
| eMachines            | 1        | 1.75%   |
| ASUSTek Computer     | 1        | 1.75%   |
| Ancor Communications | 1        | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 4        | 6.35%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 3        | 4.76%   |
| Element ELEFW328 ELE1366 1366x768 700x400mm 31.7-inch                  | 3        | 4.76%   |
| VIZ LCD Monitor M551d-A2R                                              | 2        | 3.17%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch          | 2        | 3.17%   |
| Sony TV  *00 SNY4B04 3840x2160                                         | 2        | 3.17%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch      | 2        | 3.17%   |
| Gateway LCD Monitor FHX2300                                            | 2        | 3.17%   |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch                  | 2        | 3.17%   |
| Acer LCD Monitor G236HL 5760x1080                                      | 2        | 3.17%   |
| Vizio M551d-A2R VIZ1006 1920x1080 1430x800mm 64.5-inch                 | 1        | 1.59%   |
| Vizio M322i-B1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1        | 1.59%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch               | 1        | 1.59%   |
| Unknown LCD Monitor Dell S2719DGF 2560x1440                            | 1        | 1.59%   |
| UGD Artist 156 UGD1501 1920x1080 293x165mm 13.2-inch                   | 1        | 1.59%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                             | 1        | 1.59%   |
| Tech Concepts LCD Monitor 43S423 1920x1080                             | 1        | 1.59%   |
| Sony TV SNY4502 1920x1080                                              | 1        | 1.59%   |
| Seiki SE241TS SEK0CF0 1920x1080 520x290mm 23.4-inch                    | 1        | 1.59%   |
| Sceptre Tech Sceptre X22HG SPT2204 1920x1080 474x296mm 22.0-inch       | 1        | 1.59%   |
| Sceptre Tech Sceptre F27 SPT0AD7 1920x1080 600x330mm 27.0-inch         | 1        | 1.59%   |
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch         | 1        | 1.59%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch      | 1        | 1.59%   |
| Samsung Electronics LCD Monitor SAM0F0B 3840x2160 1210x680mm 54.6-inch | 1        | 1.59%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 1        | 1.59%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                       | 1        | 1.59%   |
| Hewlett-Packard P17A HWP3142 1280x1024 338x270mm 17.0-inch             | 1        | 1.59%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch           | 1        | 1.59%   |
| Hewlett-Packard L2105tm HWP2863 1920x1080 477x268mm 21.5-inch          | 1        | 1.59%   |
| Hewlett-Packard 2511 HWP293E 1920x1080 553x311mm 25.0-inch             | 1        | 1.59%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch            | 1        | 1.59%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch            | 1        | 1.59%   |
| Gateway LCD Monitor FHX2300 3840x1080                                  | 1        | 1.59%   |
| eMachines E19T6W EMA0783 1440x900 410x260mm 19.1-inch                  | 1        | 1.59%   |
| Dell SE2419H DELF109 1920x1080 527x296mm 23.8-inch                     | 1        | 1.59%   |
| Dell E2316H DELF06B 1920x1080 509x286mm 23.0-inch                      | 1        | 1.59%   |
| Dell DELLSE2216HV DELF072 1920x1080 476x268mm 21.5-inch                | 1        | 1.59%   |
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                       | 1        | 1.59%   |
| ASUSTek Computer VG279 AUS2782 1920x1080 598x336mm 27.0-inch           | 1        | 1.59%   |
| AOC LM742 AOCC742 1280x1024 338x270mm 17.0-inch                        | 1        | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 27       | 51.92%  |
| 3840x2160 (4K)     | 8        | 15.38%  |
| 5760x1080          | 2        | 3.85%   |
| 1600x900 (HD+)     | 2        | 3.85%   |
| 1440x900 (WXGA+)   | 2        | 3.85%   |
| 1280x1024 (SXGA)   | 2        | 3.85%   |
| Unknown            | 2        | 3.85%   |
| 3840x1080          | 1        | 1.92%   |
| 3440x1440          | 1        | 1.92%   |
| 2560x1440 (QHD)    | 1        | 1.92%   |
| 2560x1080          | 1        | 1.92%   |
| 1680x1050 (WSXGA+) | 1        | 1.92%   |
| 1366x768 (WXGA)    | 1        | 1.92%   |
| 1280x720 (HD)      | 1        | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 10       | 18.52%  |
| 23      | 8        | 14.81%  |
| 72      | 6        | 11.11%  |
| Unknown | 5        | 9.26%   |
| 31      | 4        | 7.41%   |
| 20      | 3        | 5.56%   |
| 19      | 3        | 5.56%   |
| 34      | 2        | 3.7%    |
| 27      | 2        | 3.7%    |
| 17      | 2        | 3.7%    |
| 84      | 1        | 1.85%   |
| 64      | 1        | 1.85%   |
| 52      | 1        | 1.85%   |
| 32      | 1        | 1.85%   |
| 25      | 1        | 1.85%   |
| 24      | 1        | 1.85%   |
| 22      | 1        | 1.85%   |
| 18      | 1        | 1.85%   |
| 13      | 1        | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 17       | 32.08%  |
| 501-600     | 11       | 20.75%  |
| 1501-2000   | 7        | 13.21%  |
| Unknown     | 5        | 9.43%   |
| 601-700     | 4        | 7.55%   |
| 701-800     | 3        | 5.66%   |
| 301-350     | 2        | 3.77%   |
| 1001-1500   | 2        | 3.77%   |
| 351-400     | 1        | 1.89%   |
| 201-300     | 1        | 1.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 32       | 69.57%  |
| Unknown | 5        | 10.87%  |
| 16/10   | 4        | 8.7%    |
| 5/4     | 3        | 6.52%   |
| 21/9    | 2        | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18       | 33.96%  |
| More than 1000 | 8        | 15.09%  |
| 151-200        | 8        | 15.09%  |
| 351-500        | 7        | 13.21%  |
| Unknown        | 5        | 9.43%   |
| 141-150        | 3        | 5.66%   |
| 301-350        | 2        | 3.77%   |
| 71-80          | 1        | 1.89%   |
| 251-300        | 1        | 1.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 23       | 46.94%  |
| 101-120 | 12       | 24.49%  |
| 1-50    | 7        | 14.29%  |
| Unknown | 5        | 10.2%   |
| 161-240 | 1        | 2.04%   |
| 121-160 | 1        | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 41       | 78.85%  |
| 2     | 7        | 13.46%  |
| 3     | 2        | 3.85%   |
| 0     | 2        | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 39       | 49.37%  |
| Intel                 | 25       | 31.65%  |
| Ralink Technology     | 3        | 3.8%    |
| Qualcomm Atheros      | 3        | 3.8%    |
| NetGear               | 3        | 3.8%    |
| TP-Link               | 1        | 1.27%   |
| Samsung Electronics   | 1        | 1.27%   |
| Ralink                | 1        | 1.27%   |
| Nvidia                | 1        | 1.27%   |
| Gemtek                | 1        | 1.27%   |
| Aquantia              | 1        | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 29.35%  |
| Intel Wi-Fi 6 AX200                                               | 4        | 4.35%   |
| Intel I211 Gigabit Network Connection                             | 4        | 4.35%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 4.35%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3        | 3.26%   |
| Realtek 802.11ac NIC                                              | 3        | 3.26%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 3.26%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2        | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.17%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 1        | 1.09%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.09%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.09%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1        | 1.09%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 1.09%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                            | 1        | 1.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 1.09%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 1.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.09%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 1.09%   |
| Ralink RT2870 Wireless Adapter                                    | 1        | 1.09%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1        | 1.09%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.09%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1        | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 1.09%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 1.09%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 1.09%   |
| NetGear MA111(v2) 802.11b Wireless [SIS SIS 162]                  | 1        | 1.09%   |
| NetGear LB1120-100NAS                                             | 1        | 1.09%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1        | 1.09%   |
| Intel Wireless 8265 / 8275                                        | 1        | 1.09%   |
| Intel Wireless 3160                                               | 1        | 1.09%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1        | 1.09%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.09%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 1.09%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 37.14%  |
| Intel                 | 12       | 34.29%  |
| Ralink Technology     | 3        | 8.57%   |
| Qualcomm Atheros      | 2        | 5.71%   |
| NetGear               | 2        | 5.71%   |
| TP-Link               | 1        | 2.86%   |
| Ralink                | 1        | 2.86%   |
| Gemtek                | 1        | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                         | 4        | 10.81%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]            | 4        | 10.81%  |
| Realtek RTL8188CUS 802.11n WLAN Adapter                     | 3        | 8.11%   |
| Realtek 802.11ac NIC                                        | 3        | 8.11%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter       | 2        | 5.41%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                  | 1        | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 1        | 2.7%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter     | 1        | 2.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                  | 1        | 2.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                      | 1        | 2.7%    |
| Realtek RTL8188RU 802.11n WLAN Adapter                      | 1        | 2.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                  | 1        | 2.7%    |
| Realtek RTL8187 Wireless Adapter                            | 1        | 2.7%    |
| Ralink RT2870 Wireless Adapter                              | 1        | 2.7%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter           | 1        | 2.7%    |
| Ralink MT7601U Wireless Adapter                             | 1        | 2.7%    |
| Ralink RT2561/RT61 802.11g PCI                              | 1        | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 1        | 2.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter            | 1        | 2.7%    |
| NetGear MA111(v2) 802.11b Wireless [SIS SIS 162]            | 1        | 2.7%    |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU] | 1        | 2.7%    |
| Intel Wireless 8265 / 8275                                  | 1        | 2.7%    |
| Intel Wireless 3160                                         | 1        | 2.7%    |
| Intel Wi-Fi 6 AX201 160MHz                                  | 1        | 2.7%    |
| Intel Comet Lake PCH CNVi WiFi                              | 1        | 2.7%    |
| Gemtek WUBR-177G [Ralink RT2571W]                           | 1        | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 32       | 58.18%  |
| Intel                 | 18       | 32.73%  |
| Samsung Electronics   | 1        | 1.82%   |
| Qualcomm Atheros      | 1        | 1.82%   |
| Nvidia                | 1        | 1.82%   |
| NetGear               | 1        | 1.82%   |
| Aquantia              | 1        | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 49.09%  |
| Intel I211 Gigabit Network Connection                             | 4        | 7.27%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 7.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 7.27%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 5.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 3.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.82%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 1.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.82%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 1.82%   |
| NetGear LB1120-100NAS                                             | 1        | 1.82%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.82%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.82%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.82%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 50       | 64.1%   |
| WiFi     | 28       | 35.9%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 40       | 71.43%  |
| WiFi     | 16       | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 65.38%  |
| 2     | 16       | 30.77%  |
| 3     | 2        | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 49       | 98%     |
| Yes  | 1        | 2%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 12       | 46.15%  |
| Cambridge Silicon Radio         | 7        | 26.92%  |
| Broadcom                        | 2        | 7.69%   |
| Realtek Semiconductor           | 1        | 3.85%   |
| Qualcomm Atheros Communications | 1        | 3.85%   |
| Lite-On Technology              | 1        | 3.85%   |
| Dynex                           | 1        | 3.85%   |
| Belkin Components               | 1        | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 26.92%  |
| Intel Wireless-AC 3168 Bluetooth                    | 4        | 15.38%  |
| Intel AX200 Bluetooth                               | 4        | 15.38%  |
| Intel Bluetooth wireless interface                  | 2        | 7.69%   |
| Broadcom Bluetooth Device                           | 2        | 7.69%   |
| Realtek Bluetooth Radio                             | 1        | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 3.85%   |
| Lite-On Bluetooth Device                            | 1        | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 3.85%   |
| Intel AX201 Bluetooth                               | 1        | 3.85%   |
| Dynex BCM20702A0                                    | 1        | 3.85%   |
| Belkin Components Bluetooth Mini Dongle             | 1        | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 32       | 43.24%  |
| AMD                                             | 17       | 22.97%  |
| Nvidia                                          | 14       | 18.92%  |
| Logitech                                        | 6        | 8.11%   |
| C-Media Electronics                             | 2        | 2.7%    |
| Nintendo                                        | 1        | 1.35%   |
| Licensed by Sony Computer Entertainment America | 1        | 1.35%   |
| Kingston Technology                             | 1        | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 5.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 5.43%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5        | 5.43%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 4.35%   |
| AMD FCH Azalia Controller                                                  | 4        | 4.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 3.26%   |
| Logitech EasyCall Speakerphone                                             | 3        | 3.26%   |
| Intel Sunrise Point-LP HD Audio                                            | 3        | 3.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 3.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3        | 3.26%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 3.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 3.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.26%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 2.17%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 2.17%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 2.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2        | 2.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 2.17%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 2.17%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 2.17%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 2.17%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 1.09%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.09%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.09%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.09%   |
| Nintendo WUP-021-0                                                         | 1        | 1.09%   |
| Logitech QuickCam Fusion                                                   | 1        | 1.09%   |
| Logitech Headset H390                                                      | 1        | 1.09%   |
| Logitech G635 Gaming Headset                                               | 1        | 1.09%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset    | 1        | 1.09%   |
| Kingston Technology HyperX SoloCast                                        | 1        | 1.09%   |
| Intel Jasper Lake HD Audio                                                 | 1        | 1.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.09%   |
| Intel Audio device                                                         | 1        | 1.09%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 6        | 33.33%  |
| Samsung Electronics | 3        | 16.67%  |
| G.Skill             | 2        | 11.11%  |
| Corsair             | 2        | 11.11%  |
| SK hynix            | 1        | 5.56%   |
| Sesame              | 1        | 5.56%   |
| PNY                 | 1        | 5.56%   |
| Kingston            | 1        | 5.56%   |
| Crucial             | 1        | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                     | 3        | 15%     |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 5%      |
| Unknown RAM Module 4096MB DIMM 667MT/s                   | 1        | 5%      |
| Unknown RAM CL18-20-20 D4-3600 8192MB DIMM DDR4 3600MT/s | 1        | 5%      |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s     | 1        | 5%      |
| Sesame RAM S939A2UGS-ITR 8GB DIMM DDR3 1600MT/s          | 1        | 5%      |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s      | 1        | 5%      |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s      | 1        | 5%      |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 5%      |
| Samsung RAM M378B1G73QH0-CK0 8192MB DIMM DDR3 1600MT/s   | 1        | 5%      |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s      | 1        | 5%      |
| PNY RAM 4GBH1X04E9992 4096MB DIMM DDR3 1600MT/s          | 1        | 5%      |
| Kingston RAM X2YH1K-MIE-NX 16GB DIMM DDR4 3200MT/s       | 1        | 5%      |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s       | 1        | 5%      |
| G.Skill RAM F3-10666CL9-8GBSQ 8GB DIMM DDR3 1333MT/s     | 1        | 5%      |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s    | 1        | 5%      |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 1        | 5%      |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 1        | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 9        | 50%     |
| DDR4    | 5        | 27.78%  |
| SDRAM   | 3        | 16.67%  |
| Unknown | 1        | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 18       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 44.44%  |
| 4096  | 6        | 33.33%  |
| 2048  | 3        | 16.67%  |
| 16384 | 1        | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 5        | 26.32%  |
| 1333    | 3        | 15.79%  |
| Unknown | 3        | 15.79%  |
| 3600    | 2        | 10.53%  |
| 3200    | 2        | 10.53%  |
| 3466    | 1        | 5.26%   |
| 1867    | 1        | 5.26%   |
| 1866    | 1        | 5.26%   |
| 667     | 1        | 5.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| HP OfficeJet Pro 6960 | 1        | 50%     |
| Brother MFC-L2685DW   | 1        | 50%     |

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


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Microdia         | 5        | 41.67%  |
| Logitech         | 5        | 41.67%  |
| Jieli Technology | 1        | 8.33%   |
| Cubeternet       | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Microdia Camera                 | 4        | 33.33%  |
| Microdia CameraA                | 1        | 8.33%   |
| Logitech Webcam Pro 9000        | 1        | 8.33%   |
| Logitech Webcam C310            | 1        | 8.33%   |
| Logitech Webcam C270            | 1        | 8.33%   |
| Logitech HD Pro Webcam C920     | 1        | 8.33%   |
| Logitech CrystalCam             | 1        | 8.33%   |
| Jieli USB PHY 2.0               | 1        | 8.33%   |
| Cubeternet GL-UPC822 UVC WebCam | 1        | 8.33%   |

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
| 0     | 40       | 68.97%  |
| 1     | 14       | 24.14%  |
| 2     | 4        | 6.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 12       | 63.16%  |
| Graphics card            | 4        | 21.05%  |
| Net/ethernet             | 1        | 5.26%   |
| Multimedia controller    | 1        | 5.26%   |
| Communication controller | 1        | 5.26%   |

