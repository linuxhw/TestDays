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

Total: 123

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Gateway   | H61H2-AD V1.0               | [9a34a9295c](https://linux-hardware.org/?probe=9a34a9295c) | Jun 15, 2023 |
| ASRock    | B450M Pro4                  | [2d42a4443c](https://linux-hardware.org/?probe=2d42a4443c) | May 23, 2023 |
| Gigabyte  | B360M DS3H                  | [b6336515aa](https://linux-hardware.org/?probe=b6336515aa) | May 19, 2023 |
| Gateway   | RS780                       | [e04207a390](https://linux-hardware.org/?probe=e04207a390) | May 07, 2023 |
| Gigabyte  | X570 GAMING X               | [83132b245e](https://linux-hardware.org/?probe=83132b245e) | Apr 05, 2023 |
| ECS       | Iris8                       | [f86927f9ff](https://linux-hardware.org/?probe=f86927f9ff) | Apr 04, 2023 |
| MSI       | Z370-A PRO                  | [9aba047596](https://linux-hardware.org/?probe=9aba047596) | Mar 30, 2023 |
| MSI       | H81M-P33                    | [4606b5b93d](https://linux-hardware.org/?probe=4606b5b93d) | Mar 29, 2023 |
| HP        | 83E1                        | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| HP        | 83E1                        | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| HP        | 83E1                        | [86061f121d](https://linux-hardware.org/?probe=86061f121d) | Mar 08, 2023 |
| HP        | 89B5 A                      | [4fcef21d82](https://linux-hardware.org/?probe=4fcef21d82) | Jan 07, 2023 |
| ASUSTek   | TUF Gaming B560M-PLUS WI... | [9e63ba2bf9](https://linux-hardware.org/?probe=9e63ba2bf9) | Oct 23, 2022 |
| ASRock    | X570 Phantom Gaming 4S      | [2215129a47](https://linux-hardware.org/?probe=2215129a47) | Oct 02, 2022 |
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


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 6        | 7.59%   |
| Ubuntu 18.04                 | 6        | 7.59%   |
| OpenMandriva 4.2             | 4        | 5.06%   |
| OpenMandriva 23.03           | 4        | 5.06%   |
| Manjaro                      | 4        | 5.06%   |
| Zorin 16                     | 2        | 2.53%   |
| Zorin 15                     | 2        | 2.53%   |
| Ubuntu 20.10                 | 2        | 2.53%   |
| ROSA R11                     | 2        | 2.53%   |
| OpenMandriva 4.3             | 2        | 2.53%   |
| Lubuntu 20.04                | 2        | 2.53%   |
| LMDE 4                       | 2        | 2.53%   |
| Linux Mint 20.3              | 2        | 2.53%   |
| Linux Mint 20.1              | 2        | 2.53%   |
| Linux Mint 20                | 2        | 2.53%   |
| Garuda Linux                 | 2        | 2.53%   |
| Fedora 36                    | 2        | 2.53%   |
| ArcoLinux Rolling            | 2        | 2.53%   |
| Xubuntu 20.10                | 1        | 1.27%   |
| Xubuntu 20.04                | 1        | 1.27%   |
| Ubuntu Budgie 21.04          | 1        | 1.27%   |
| Ubuntu 22.04                 | 1        | 1.27%   |
| Ubuntu 21.10                 | 1        | 1.27%   |
| Ubuntu 19.10                 | 1        | 1.27%   |
| ROSA R9                      | 1        | 1.27%   |
| ROSA R10                     | 1        | 1.27%   |
| Pop!_OS 21.10                | 1        | 1.27%   |
| Pop!_OS 21.04                | 1        | 1.27%   |
| Pop!_OS 20.10                | 1        | 1.27%   |
| Pop!_OS 20.04                | 1        | 1.27%   |
| Pop!_OS 19.10                | 1        | 1.27%   |
| openSUSE Tumbleweed-XXXXXXXX | 1        | 1.27%   |
| OpenMandriva 23.01           | 1        | 1.27%   |
| Manjaro 21.1.5               | 1        | 1.27%   |
| Manjaro 20.1.2               | 1        | 1.27%   |
| LinuxFX 11                   | 1        | 1.27%   |
| Linux Mint 20.2              | 1        | 1.27%   |
| Linux Mint 19.3              | 1        | 1.27%   |
| Linux Mint 19.1              | 1        | 1.27%   |
| KDE neon 20.04               | 1        | 1.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 17       | 23.29%  |
| OpenMandriva  | 10       | 13.7%   |
| Linux Mint    | 6        | 8.22%   |
| Pop!_OS       | 5        | 6.85%   |
| Manjaro       | 5        | 6.85%   |
| Zorin         | 4        | 5.48%   |
| ROSA          | 3        | 4.11%   |
| Fedora        | 3        | 4.11%   |
| Xubuntu       | 2        | 2.74%   |
| Lubuntu       | 2        | 2.74%   |
| LMDE          | 2        | 2.74%   |
| Garuda Linux  | 2        | 2.74%   |
| ArcoLinux     | 2        | 2.74%   |
| Ubuntu Budgie | 1        | 1.37%   |
| openSUSE      | 1        | 1.37%   |
| LinuxFX       | 1        | 1.37%   |
| KDE neon      | 1        | 1.37%   |
| Endless       | 1        | 1.37%   |
| Devuan        | 1        | 1.37%   |
| Debian        | 1        | 1.37%   |
| CentOS        | 1        | 1.37%   |
| BlackPanther  | 1        | 1.37%   |
| Arch          | 1        | 1.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 6.2.6-desktop-1omv2390         | 4        | 4.49%   |
| 5.10.14-desktop-1omv4002       | 4        | 4.49%   |
| 5.8.18-1-MANJARO               | 2        | 2.25%   |
| 5.8.0-45-generic               | 2        | 2.25%   |
| 5.4.0-72-generic               | 2        | 2.25%   |
| 5.4.0-58-generic               | 2        | 2.25%   |
| 5.4.0-109-generic              | 2        | 2.25%   |
| 5.16.7-desktop-1omv4003        | 2        | 2.25%   |
| 5.13.0-39-generic              | 2        | 2.25%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2        | 2.25%   |
| 6.2.15-300.fc38.x86_64         | 1        | 1.12%   |
| 6.1.1-desktop-1omv2290         | 1        | 1.12%   |
| 5.9.16-1-MANJARO               | 1        | 1.12%   |
| 5.9.1-1-MANJARO                | 1        | 1.12%   |
| 5.8.5-zen1-1-zen               | 1        | 1.12%   |
| 5.8.14-zen1-1-zen              | 1        | 1.12%   |
| 5.8.0-7630-generic             | 1        | 1.12%   |
| 5.8.0-54-generic               | 1        | 1.12%   |
| 5.8.0-53-generic               | 1        | 1.12%   |
| 5.8.0-49-generic               | 1        | 1.12%   |
| 5.8.0-44-generic               | 1        | 1.12%   |
| 5.8.0-29-generic               | 1        | 1.12%   |
| 5.8.0-25-generic               | 1        | 1.12%   |
| 5.8.0-14-generic               | 1        | 1.12%   |
| 5.4.0-89-generic               | 1        | 1.12%   |
| 5.4.0-88-generic               | 1        | 1.12%   |
| 5.4.0-7634-generic             | 1        | 1.12%   |
| 5.4.0-73-generic               | 1        | 1.12%   |
| 5.4.0-65-generic               | 1        | 1.12%   |
| 5.4.0-59-generic               | 1        | 1.12%   |
| 5.4.0-52-generic               | 1        | 1.12%   |
| 5.4.0-48-generic               | 1        | 1.12%   |
| 5.4.0-47-generic               | 1        | 1.12%   |
| 5.4.0-42-generic               | 1        | 1.12%   |
| 5.4.0-40-generic               | 1        | 1.12%   |
| 5.4.0-37-generic               | 1        | 1.12%   |
| 5.4.0-125-generic              | 1        | 1.12%   |
| 5.3.0-7629-generic             | 1        | 1.12%   |
| 5.3.0-51-generic               | 1        | 1.12%   |
| 5.3.0-42-generic               | 1        | 1.12%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 17       | 21.25%  |
| 5.8.0    | 8        | 10%     |
| 4.15.0   | 6        | 7.5%    |
| 6.2.6    | 4        | 5%      |
| 5.11.0   | 4        | 5%      |
| 5.10.14  | 4        | 5%      |
| 5.3.0    | 3        | 3.75%   |
| 5.8.18   | 2        | 2.5%    |
| 5.16.7   | 2        | 2.5%    |
| 5.13.0   | 2        | 2.5%    |
| 4.19.0   | 2        | 2.5%    |
| 4.18.0   | 2        | 2.5%    |
| 6.2.15   | 1        | 1.25%   |
| 6.1.1    | 1        | 1.25%   |
| 5.9.16   | 1        | 1.25%   |
| 5.9.1    | 1        | 1.25%   |
| 5.8.5    | 1        | 1.25%   |
| 5.8.14   | 1        | 1.25%   |
| 5.19.12  | 1        | 1.25%   |
| 5.19.0   | 1        | 1.25%   |
| 5.18.9   | 1        | 1.25%   |
| 5.18.5   | 1        | 1.25%   |
| 5.18.15  | 1        | 1.25%   |
| 5.17.1   | 1        | 1.25%   |
| 5.15.5   | 1        | 1.25%   |
| 5.15.109 | 1        | 1.25%   |
| 5.15.0   | 1        | 1.25%   |
| 5.14.8   | 1        | 1.25%   |
| 5.14.0   | 1        | 1.25%   |
| 5.13.19  | 1        | 1.25%   |
| 5.11.13  | 1        | 1.25%   |
| 5.10.0   | 1        | 1.25%   |
| 4.9.60   | 1        | 1.25%   |
| 4.9.20   | 1        | 1.25%   |
| 4.9.0    | 1        | 1.25%   |
| 4.18.16  | 1        | 1.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 17       | 22.08%  |
| 5.8     | 12       | 15.58%  |
| 4.15    | 6        | 7.79%   |
| 6.2     | 5        | 6.49%   |
| 5.10    | 5        | 6.49%   |
| 5.11    | 4        | 5.19%   |
| 5.3     | 3        | 3.9%    |
| 5.15    | 3        | 3.9%    |
| 5.13    | 3        | 3.9%    |
| 4.9     | 3        | 3.9%    |
| 5.9     | 2        | 2.6%    |
| 5.19    | 2        | 2.6%    |
| 5.18    | 2        | 2.6%    |
| 5.16    | 2        | 2.6%    |
| 5.14    | 2        | 2.6%    |
| 4.19    | 2        | 2.6%    |
| 4.18    | 2        | 2.6%    |
| 6.1     | 1        | 1.3%    |
| 5.17    | 1        | 1.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 59       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 29       | 39.73%  |
| KDE5          | 17       | 23.29%  |
| X-Cinnamon    | 7        | 9.59%   |
| XFCE          | 4        | 5.48%   |
| Unknown       | 4        | 5.48%   |
| MATE          | 2        | 2.74%   |
| LXQt          | 2        | 2.74%   |
| KDE           | 2        | 2.74%   |
| Budgie        | 2        | 2.74%   |
| LXDE          | 1        | 1.37%   |
| KDE4          | 1        | 1.37%   |
| GNOME Classic | 1        | 1.37%   |
| Deepin        | 1        | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 53       | 89.83%  |
| Wayland | 5        | 8.47%   |
| Unknown | 1        | 1.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 42       | 61.76%  |
| SDDM    | 13       | 19.12%  |
| GDM3    | 4        | 5.88%   |
| GDM     | 4        | 5.88%   |
| LightDM | 3        | 4.41%   |
| TDM     | 1        | 1.47%   |
| KDM     | 1        | 1.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 50       | 83.33%  |
| Unknown | 7        | 11.67%  |
| es_PR   | 1        | 1.67%   |
| es_ES   | 1        | 1.67%   |
| C       | 1        | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 35       | 55.56%  |
| EFI  | 28       | 44.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 45       | 70.31%  |
| Overlay | 9        | 14.06%  |
| Btrfs   | 5        | 7.81%   |
| Unknown | 3        | 4.69%   |
| Xfs     | 1        | 1.56%   |
| Tmpfs   | 1        | 1.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 45       | 68.18%  |
| GPT     | 14       | 21.21%  |
| MBR     | 7        | 10.61%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 82.81%  |
| Yes       | 11       | 17.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 76.92%  |
| Yes       | 15       | 23.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 10       | 16.95%  |
| ASRock              | 10       | 16.95%  |
| Hewlett-Packard     | 8        | 13.56%  |
| ASUSTek Computer    | 7        | 11.86%  |
| MSI                 | 6        | 10.17%  |
| Dell                | 6        | 10.17%  |
| Lenovo              | 3        | 5.08%   |
| Intel               | 3        | 5.08%   |
| Gateway             | 2        | 3.39%   |
| Pegatron            | 1        | 1.69%   |
| ECS                 | 1        | 1.69%   |
| Alienware           | 1        | 1.69%   |
| Acer                | 1        | 1.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel SKYBAY                            | 3        | 5.08%   |
| MSI Cubi N 8GL (MS-B171)                | 2        | 3.39%   |
| ASRock Q1900M                           | 2        | 3.39%   |
| ASRock 945GCM-S                         | 2        | 3.39%   |
| Pegatron QW716AA#ABA                    | 1        | 1.69%   |
| MSI MS-7B48                             | 1        | 1.69%   |
| MSI MS-7971                             | 1        | 1.69%   |
| MSI MS-7817                             | 1        | 1.69%   |
| MSI Cubi N JSL (MS-B0A1)                | 1        | 1.69%   |
| Lenovo ThinkCentre M91p 7033CG1         | 1        | 1.69%   |
| Lenovo ThinkCentre M58p 6136A66         | 1        | 1.69%   |
| Lenovo IdeaCentre 510A-15ARR 90J0000PUS | 1        | 1.69%   |
| HP Pavilion Desktop TP01-3xxx           | 1        | 1.69%   |
| HP EliteDesk 800 G4 SFF                 | 1        | 1.69%   |
| HP EliteDesk 800 G1 TWR                 | 1        | 1.69%   |
| HP EliteDesk 800 G1 SFF                 | 1        | 1.69%   |
| HP Compaq Pro 6300 SFF                  | 1        | 1.69%   |
| HP Compaq Pro 6300 MT                   | 1        | 1.69%   |
| HP Compaq dc7800p Small Form Factor     | 1        | 1.69%   |
| HP Compaq 8200 Elite SFF PC             | 1        | 1.69%   |
| Gigabyte Z97M-DS3H                      | 1        | 1.69%   |
| Gigabyte X570 GAMING X                  | 1        | 1.69%   |
| Gigabyte X570 AORUS ELITE WIFI          | 1        | 1.69%   |
| Gigabyte X399 AORUS Gaming 7            | 1        | 1.69%   |
| Gigabyte J1900N-D3V                     | 1        | 1.69%   |
| Gigabyte F2A78M-HD2                     | 1        | 1.69%   |
| Gigabyte F2A68HM-H                      | 1        | 1.69%   |
| Gigabyte B450M DS3H                     | 1        | 1.69%   |
| Gigabyte B450 AORUS PRO WIFI            | 1        | 1.69%   |
| Gigabyte B360M-DS3H                     | 1        | 1.69%   |
| Gateway SX2865                          | 1        | 1.69%   |
| Gateway DX4300                          | 1        | 1.69%   |
| ECS NC696AAR-ABA SR5710Y                | 1        | 1.69%   |
| Dell Studio 540                         | 1        | 1.69%   |
| Dell OptiPlex 960                       | 1        | 1.69%   |
| Dell OptiPlex 9020                      | 1        | 1.69%   |
| Dell OptiPlex 780                       | 1        | 1.69%   |
| Dell OptiPlex 7020                      | 1        | 1.69%   |
| Dell Inspiron 3670                      | 1        | 1.69%   |
| ASUS TUF Gaming X570-PRO                | 1        | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP Compaq            | 4        | 6.78%   |
| Dell OptiPlex        | 4        | 6.78%   |
| MSI Cubi             | 3        | 5.08%   |
| Intel SKYBAY         | 3        | 5.08%   |
| HP EliteDesk         | 3        | 5.08%   |
| Lenovo ThinkCentre   | 2        | 3.39%   |
| Gigabyte X570        | 2        | 3.39%   |
| ASUS TUF             | 2        | 3.39%   |
| ASUS ROG             | 2        | 3.39%   |
| ASRock Q1900M        | 2        | 3.39%   |
| ASRock B450M-HDV     | 2        | 3.39%   |
| ASRock 945GCM-S      | 2        | 3.39%   |
| Pegatron QW716AA#ABA | 1        | 1.69%   |
| MSI MS-7B48          | 1        | 1.69%   |
| MSI MS-7971          | 1        | 1.69%   |
| MSI MS-7817          | 1        | 1.69%   |
| Lenovo IdeaCentre    | 1        | 1.69%   |
| HP Pavilion          | 1        | 1.69%   |
| Gigabyte Z97M-DS3H   | 1        | 1.69%   |
| Gigabyte X399        | 1        | 1.69%   |
| Gigabyte J1900N-D3V  | 1        | 1.69%   |
| Gigabyte F2A78M-HD2  | 1        | 1.69%   |
| Gigabyte F2A68HM-H   | 1        | 1.69%   |
| Gigabyte B450M       | 1        | 1.69%   |
| Gigabyte B450        | 1        | 1.69%   |
| Gigabyte B360M-DS3H  | 1        | 1.69%   |
| Gateway SX2865       | 1        | 1.69%   |
| Gateway DX4300       | 1        | 1.69%   |
| ECS NC696AAR-ABA     | 1        | 1.69%   |
| Dell Studio          | 1        | 1.69%   |
| Dell Inspiron        | 1        | 1.69%   |
| ASUS PRIME           | 1        | 1.69%   |
| ASUS M5A78L-M        | 1        | 1.69%   |
| ASUS M2N-E           | 1        | 1.69%   |
| ASRock Z270          | 1        | 1.69%   |
| ASRock X570          | 1        | 1.69%   |
| ASRock G31M-S        | 1        | 1.69%   |
| ASRock B450M         | 1        | 1.69%   |
| Alienware Aurora     | 1        | 1.69%   |
| Acer Aspire          | 1        | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 14       | 23.73%  |
| 2019 | 6        | 10.17%  |
| 2008 | 6        | 10.17%  |
| 2014 | 5        | 8.47%   |
| 2013 | 5        | 8.47%   |
| 2011 | 4        | 6.78%   |
| 2021 | 3        | 5.08%   |
| 2020 | 2        | 3.39%   |
| 2017 | 2        | 3.39%   |
| 2016 | 2        | 3.39%   |
| 2015 | 2        | 3.39%   |
| 2012 | 2        | 3.39%   |
| 2009 | 2        | 3.39%   |
| 2022 | 1        | 1.69%   |
| 2010 | 1        | 1.69%   |
| 2007 | 1        | 1.69%   |
| 2006 | 1        | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 59       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 58       | 96.67%  |
| Enabled  | 2        | 3.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 59       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 14       | 22.58%  |
| 16.01-24.0  | 12       | 19.35%  |
| 8.01-16.0   | 11       | 17.74%  |
| 3.01-4.0    | 9        | 14.52%  |
| 32.01-64.0  | 8        | 12.9%   |
| 24.01-32.0  | 3        | 4.84%   |
| 64.01-256.0 | 2        | 3.23%   |
| 1.01-2.0    | 2        | 3.23%   |
| 0.51-1.0    | 1        | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 27       | 37.5%   |
| 2.01-3.0  | 17       | 23.61%  |
| 3.01-4.0  | 10       | 13.89%  |
| 4.01-8.0  | 9        | 12.5%   |
| 0.51-1.0  | 6        | 8.33%   |
| 8.01-16.0 | 3        | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 48.44%  |
| 2      | 14       | 21.88%  |
| 3      | 12       | 18.75%  |
| 4      | 3        | 4.69%   |
| 5      | 2        | 3.13%   |
| 6      | 1        | 1.56%   |
| 0      | 1        | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 56.67%  |
| No        | 26       | 43.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 58       | 98.31%  |
| No        | 1        | 1.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 35       | 57.38%  |
| No        | 26       | 42.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 56.45%  |
| Yes       | 27       | 43.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Puerto Rico | 59       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| San Juan      | 20       | 29.41%  |
| Bayamón      | 11       | 16.18%  |
| Carolina      | 4        | 5.88%   |
| Caguas        | 3        | 4.41%   |
| Aguadilla     | 3        | 4.41%   |
| Vega Alta     | 2        | 2.94%   |
| San Sebastian | 2        | 2.94%   |
| Dorado        | 2        | 2.94%   |
| Cayey         | 2        | 2.94%   |
| Yauco         | 1        | 1.47%   |
| Sabana Grande | 1        | 1.47%   |
| Rio Grande    | 1        | 1.47%   |
| Ponce         | 1        | 1.47%   |
| Patillas      | 1        | 1.47%   |
| Morovis       | 1        | 1.47%   |
| Mayagüez     | 1        | 1.47%   |
| Maunabo       | 1        | 1.47%   |
| Las Piedras   | 1        | 1.47%   |
| Humacao       | 1        | 1.47%   |
| Hatillo       | 1        | 1.47%   |
| Gurabo        | 1        | 1.47%   |
| Guayama       | 1        | 1.47%   |
| Garrochales   | 1        | 1.47%   |
| Fajardo       | 1        | 1.47%   |
| Ensenada      | 1        | 1.47%   |
| Coamo         | 1        | 1.47%   |
| Catano        | 1        | 1.47%   |
| Barceloneta   | 1        | 1.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 21       | 59     | 22.34%  |
| Seagate                   | 17       | 32     | 18.09%  |
| Toshiba                   | 9        | 14     | 9.57%   |
| Samsung Electronics       | 8        | 17     | 8.51%   |
| China                     | 5        | 7      | 5.32%   |
| TDAS                      | 3        | 13     | 3.19%   |
| SanDisk                   | 3        | 3      | 3.19%   |
| Micron/Crucial Technology | 3        | 4      | 3.19%   |
| Crucial                   | 3        | 3      | 3.19%   |
| Silicon Motion            | 2        | 2      | 2.13%   |
| SABRENT                   | 2        | 3      | 2.13%   |
| Phison                    | 2        | 2      | 2.13%   |
| LITEONIT                  | 2        | 2      | 2.13%   |
| Hitachi                   | 2        | 2      | 2.13%   |
| WD MediaMax               | 1        | 3      | 1.06%   |
| Unknown                   | 1        | 2      | 1.06%   |
| Team                      | 1        | 1      | 1.06%   |
| SPCC                      | 1        | 1      | 1.06%   |
| Patriot                   | 1        | 1      | 1.06%   |
| OCZ                       | 1        | 1      | 1.06%   |
| MaxDigital                | 1        | 1      | 1.06%   |
| Kingston                  | 1        | 1      | 1.06%   |
| JMicron Technology        | 1        | 4      | 1.06%   |
| Intel                     | 1        | 1      | 1.06%   |
| addlink                   | 1        | 1      | 1.06%   |
| A-DATA Technology         | 1        | 5      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB               | 3        | 2.86%   |
| TDAS TerraMaster 16TB                | 3        | 2.86%   |
| WDC WDBNCE2500PNC 250GB SSD          | 2        | 1.9%    |
| WDC WD5000LPLX-22ZNTT0 500GB         | 2        | 1.9%    |
| WDC WD40EZRZ-22GXCB0 4TB             | 2        | 1.9%    |
| Toshiba DT01ACA050 500GB             | 2        | 1.9%    |
| Seagate ST3250310AS 250GB            | 2        | 1.9%    |
| Seagate ST320DM001 HD322GJ 320GB     | 2        | 1.9%    |
| Seagate ST2000VM003-1CT164 2TB       | 2        | 1.9%    |
| Seagate Expansion 1TB                | 2        | 1.9%    |
| Samsung SSD 850 EVO 500GB            | 2        | 1.9%    |
| Samsung NVMe SSD Drive 500GB         | 2        | 1.9%    |
| SABRENT Disk 1TB                     | 2        | 1.9%    |
| Micron/Crucial NVMe SSD Drive 500GB  | 2        | 1.9%    |
| China SATA SSD 512GB                 | 2        | 1.9%    |
| China SATA SSD 1024GB                | 2        | 1.9%    |
| WDC WD7500BPVX-60JC3T0 752GB         | 1        | 0.95%   |
| WDC WD5000LPCX-00VHAT0 500GB         | 1        | 0.95%   |
| WDC WD5000BEVT-55A0RT0 500GB         | 1        | 0.95%   |
| WDC WD30EZRZ-00WN9B0 3TB             | 1        | 0.95%   |
| WDC WD2500BPVT-22ZEST0 250GB         | 1        | 0.95%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1        | 0.95%   |
| WDC WD1600AAJS-00PSA0 160GB          | 1        | 0.95%   |
| WDC WD1500HLFS-01G6U1 150GB          | 1        | 0.95%   |
| WDC WD1200BEVS-75UST0 120GB          | 1        | 0.95%   |
| WDC WD10SPZX-22Z10T1 1TB             | 1        | 0.95%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1        | 0.95%   |
| WDC WD10EZEX-75WN4A1 1TB             | 1        | 0.95%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 0.95%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 0.95%   |
| WDC WD10EURX-63FH1Y0 1TB             | 1        | 0.95%   |
| WDC WD10EAVS-00D7B1 1TB              | 1        | 0.95%   |
| WDC WD1003FBYZ-010FB0 1TB            | 1        | 0.95%   |
| WDC WD1003FBYX-05Y7B0 1TB            | 1        | 0.95%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1        | 0.95%   |
| WD MediaMax WL500GSA3272 500GB       | 1        | 0.95%   |
| Unknown Externa 752GB                | 1        | 0.95%   |
| Toshiba NVMe SSD Drive 128GB         | 1        | 0.95%   |
| Toshiba MQ01ABF050 500GB             | 1        | 0.95%   |
| Toshiba MQ01ABD100 1TB               | 1        | 0.95%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 54     | 38.3%   |
| Seagate             | 17       | 32     | 36.17%  |
| Toshiba             | 8        | 13     | 17.02%  |
| Hitachi             | 2        | 2      | 4.26%   |
| Samsung Electronics | 1        | 1      | 2.13%   |
| MaxDigital          | 1        | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| China               | 5        | 7      | 23.81%  |
| Samsung Electronics | 4        | 8      | 19.05%  |
| Crucial             | 3        | 3      | 14.29%  |
| WDC                 | 2        | 4      | 9.52%   |
| LITEONIT            | 2        | 2      | 9.52%   |
| SanDisk             | 1        | 1      | 4.76%   |
| Patriot             | 1        | 1      | 4.76%   |
| OCZ                 | 1        | 1      | 4.76%   |
| Kingston            | 1        | 1      | 4.76%   |
| A-DATA Technology   | 1        | 5      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 42       | 103    | 48.84%  |
| SSD     | 20       | 33     | 23.26%  |
| NVMe    | 18       | 27     | 20.93%  |
| Unknown | 6        | 22     | 6.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 53       | 136    | 66.25%  |
| NVMe | 18       | 24     | 22.5%   |
| SAS  | 9        | 25     | 11.25%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 30       | 50     | 43.48%  |
| 0.51-1.0   | 24       | 54     | 34.78%  |
| 1.01-2.0   | 9        | 21     | 13.04%  |
| 3.01-4.0   | 5        | 10     | 7.25%   |
| 2.01-3.0   | 1        | 1      | 1.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 14       | 18.92%  |
| 501-1000       | 12       | 16.22%  |
| 101-250        | 11       | 14.86%  |
| 2001-3000      | 9        | 12.16%  |
| More than 3000 | 8        | 10.81%  |
| 1001-2000      | 8        | 10.81%  |
| 1-20           | 6        | 8.11%   |
| 51-100         | 3        | 4.05%   |
| Unknown        | 3        | 4.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 24       | 32.43%  |
| 21-50     | 12       | 16.22%  |
| 251-500   | 8        | 10.81%  |
| 101-250   | 8        | 10.81%  |
| 1001-2000 | 6        | 8.11%   |
| 51-100    | 6        | 8.11%   |
| 501-1000  | 5        | 6.76%   |
| Unknown   | 3        | 4.05%   |
| 2001-3000 | 2        | 2.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST3320613AS 320GB        | 1        | 2      | 16.67%  |
| Seagate ST3250310AS 250GB        | 1        | 1      | 16.67%  |
| Seagate ST320DM001 HD322GJ 320GB | 1        | 1      | 16.67%  |
| Seagate ST2000VM003-1CT164 2TB   | 1        | 1      | 16.67%  |
| Seagate ST2000LM007-1R8174 2TB   | 1        | 2      | 16.67%  |
| Seagate ST2000DL001-9VT156 2TB   | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 8      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 8      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 8      | 100%    |

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
| Detected | 46       | 150    | 69.7%   |
| Works    | 16       | 27     | 24.24%  |
| Malfunc  | 4        | 8      | 6.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 38       | 48.72%  |
| AMD                          | 20       | 25.64%  |
| Samsung Electronics          | 4        | 5.13%   |
| Phison Electronics           | 4        | 5.13%   |
| Silicon Motion               | 3        | 3.85%   |
| SanDisk                      | 3        | 3.85%   |
| Micron/Crucial Technology    | 3        | 3.85%   |
| Nvidia                       | 2        | 2.56%   |
| Toshiba America Info Systems | 1        | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 15       | 14.71%  |
| Intel SATA Controller [RAID mode]                                                       | 6        | 5.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 5.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 4.9%    |
| Phison E12 NVMe Controller                                                              | 4        | 3.92%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 2.94%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 2.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 2.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 2.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 2.94%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 2.94%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 1.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 1.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.96%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1        | 0.98%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.98%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.98%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.98%   |
| Nvidia CK804 Serial ATA Controller                                                      | 1        | 0.98%   |
| Nvidia CK804 IDE                                                                        | 1        | 0.98%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 0.98%   |
| Intel SSD 665p Series                                                                   | 1        | 0.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.98%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 1        | 0.98%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 0.98%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                                   | 1        | 0.98%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.98%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.98%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 0.98%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.98%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.98%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 43       | 50.59%  |
| NVMe | 18       | 21.18%  |
| IDE  | 16       | 18.82%  |
| RAID | 8        | 9.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 37       | 62.71%  |
| AMD    | 22       | 37.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz              | 3        | 5.08%   |
| Intel Celeron CPU 3865U @ 1.80GHz              | 3        | 5.08%   |
| AMD Ryzen 5 3600 6-Core Processor              | 3        | 5.08%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz       | 2        | 3.39%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 2        | 3.39%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 2        | 3.39%   |
| Intel Celeron CPU E1200 @ 1.60GHz              | 2        | 3.39%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 2        | 3.39%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 2        | 3.39%   |
| AMD A6-5400K APU with Radeon HD Graphics       | 2        | 3.39%   |
| Intel Pentium Silver N6000 @ 1.10GHz           | 1        | 1.69%   |
| Intel Core i7-9700 CPU @ 3.00GHz               | 1        | 1.69%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 1.69%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 1.69%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 1.69%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 1        | 1.69%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 1.69%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 1.69%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1        | 1.69%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.69%   |
| Intel Core i3-4150 CPU @ 3.50GHz               | 1        | 1.69%   |
| Intel Core i3-3240 CPU @ 3.40GHz               | 1        | 1.69%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1        | 1.69%   |
| Intel Core i3-2130 CPU @ 3.40GHz               | 1        | 1.69%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 1.69%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 1        | 1.69%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz           | 1        | 1.69%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz           | 1        | 1.69%   |
| Intel Celeron CPU G1850 @ 2.90GHz              | 1        | 1.69%   |
| Intel Celeron CPU G1840 @ 2.80GHz              | 1        | 1.69%   |
| Intel 12th Gen Core i3-12100                   | 1        | 1.69%   |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz       | 1        | 1.69%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz         | 1        | 1.69%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 1.69%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 1.69%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 1.69%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 1        | 1.69%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 1.69%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1        | 1.69%   |
| AMD Phenom II X4 805 Processor                 | 1        | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 10       | 16.95%  |
| Intel Core i3           | 6        | 10.17%  |
| Intel Core i7           | 5        | 8.47%   |
| AMD Ryzen 5             | 5        | 8.47%   |
| Intel Core i5           | 4        | 6.78%   |
| Intel Core 2 Duo        | 4        | 6.78%   |
| AMD Ryzen 7             | 4        | 6.78%   |
| Other                   | 3        | 5.08%   |
| Intel Pentium Silver    | 3        | 5.08%   |
| AMD Ryzen 3             | 3        | 5.08%   |
| Intel Pentium Dual-Core | 2        | 3.39%   |
| AMD A8                  | 2        | 3.39%   |
| AMD A6                  | 2        | 3.39%   |
| AMD Ryzen Threadripper  | 1        | 1.69%   |
| AMD Phenom II X4        | 1        | 1.69%   |
| AMD FX                  | 1        | 1.69%   |
| AMD Athlon Dual Core    | 1        | 1.69%   |
| AMD Athlon 64 X2        | 1        | 1.69%   |
| AMD Athlon              | 1        | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 23       | 38.98%  |
| 4      | 19       | 32.2%   |
| 6      | 7        | 11.86%  |
| 8      | 6        | 10.17%  |
| 1      | 3        | 5.08%   |
| 16     | 1        | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 59       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 33       | 55.93%  |
| 2      | 26       | 44.07%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 59       | 98.33%  |
| Unknown        | 1        | 1.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 30.3%   |
| 0x306c3    | 6        | 9.09%   |
| 0x1067a    | 4        | 6.06%   |
| 0x806e9    | 3        | 4.55%   |
| 0xa0671    | 2        | 3.03%   |
| 0x906ea    | 2        | 3.03%   |
| 0x6fd      | 2        | 3.03%   |
| 0x306a9    | 2        | 3.03%   |
| 0x30678    | 2        | 3.03%   |
| 0x08701021 | 2        | 3.03%   |
| 0x08701013 | 2        | 3.03%   |
| 0x06001119 | 2        | 3.03%   |
| 0x906ed    | 1        | 1.52%   |
| 0x906e9    | 1        | 1.52%   |
| 0x906c0    | 1        | 1.52%   |
| 0x90675    | 1        | 1.52%   |
| 0x706a1    | 1        | 1.52%   |
| 0x6fb      | 1        | 1.52%   |
| 0x506e3    | 1        | 1.52%   |
| 0x30679    | 1        | 1.52%   |
| 0x206a7    | 1        | 1.52%   |
| 0x08108109 | 1        | 1.52%   |
| 0x0810100b | 1        | 1.52%   |
| 0x08101007 | 1        | 1.52%   |
| 0x0800820d | 1        | 1.52%   |
| 0x08001137 | 1        | 1.52%   |
| 0x06003106 | 1        | 1.52%   |
| 0x06000852 | 1        | 1.52%   |
| 0x03000027 | 1        | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 8        | 13.56%  |
| Haswell          | 6        | 10.17%  |
| Zen 2            | 5        | 8.47%   |
| Penryn           | 5        | 8.47%   |
| Zen+             | 4        | 6.78%   |
| Zen              | 4        | 6.78%   |
| Silvermont       | 3        | 5.08%   |
| SandyBridge      | 3        | 5.08%   |
| Piledriver       | 3        | 5.08%   |
| Core             | 3        | 5.08%   |
| K8 Hammer        | 2        | 3.39%   |
| IvyBridge        | 2        | 3.39%   |
| Goldmont plus    | 2        | 3.39%   |
| Zen 3            | 1        | 1.69%   |
| Tremont          | 1        | 1.69%   |
| Steamroller      | 1        | 1.69%   |
| Skylake          | 1        | 1.69%   |
| K10 Llano        | 1        | 1.69%   |
| K10              | 1        | 1.69%   |
| Icelake          | 1        | 1.69%   |
| Alderlake Hybrid | 1        | 1.69%   |
| Unknown          | 1        | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 31       | 48.44%  |
| Nvidia | 19       | 29.69%  |
| AMD    | 14       | 21.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 7.25%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 5.8%    |
| Intel HD Graphics 610                                                       | 3        | 4.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3        | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 4.35%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 2.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.9%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.9%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 2.9%    |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 2        | 2.9%    |
| Intel GeminiLake [UHD Graphics 605]                                         | 2        | 2.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.9%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 2.9%    |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 2        | 2.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 2.9%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.45%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.45%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.45%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.45%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.45%   |
| Nvidia GK110GL [Tesla K20Xm]                                                | 1        | 1.45%   |
| Nvidia GK104GL [GRID K2]                                                    | 1        | 1.45%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.45%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.45%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 1.45%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 1        | 1.45%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 1.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.45%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 1.45%   |
| Intel HD Graphics 630                                                       | 1        | 1.45%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 1        | 1.45%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.45%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.45%   |
| AMD Sumo [Radeon HD 6550D]                                                  | 1        | 1.45%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 1.45%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.45%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 28       | 45.9%   |
| 1 x Nvidia         | 15       | 24.59%  |
| 1 x AMD            | 14       | 22.95%  |
| Intel + 2 x Nvidia | 2        | 3.28%   |
| Intel + Nvidia     | 2        | 3.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 48       | 77.42%  |
| Proprietary | 11       | 17.74%  |
| Unknown     | 3        | 4.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 36       | 55.38%  |
| 0.01-0.5   | 8        | 12.31%  |
| 1.01-2.0   | 7        | 10.77%  |
| 0.51-1.0   | 4        | 6.15%   |
| 3.01-4.0   | 3        | 4.62%   |
| 8.01-16.0  | 3        | 4.62%   |
| 7.01-8.0   | 2        | 3.08%   |
| 5.01-6.0   | 2        | 3.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 10       | 14.49%  |
| Samsung Electronics  | 7        | 10.14%  |
| Hewlett-Packard      | 6        | 8.7%    |
| Acer                 | 6        | 8.7%    |
| Dell                 | 5        | 7.25%   |
| ViewSonic            | 4        | 5.8%    |
| Sony                 | 4        | 5.8%    |
| Vizio                | 3        | 4.35%   |
| Sceptre Tech         | 3        | 4.35%   |
| Gateway              | 3        | 4.35%   |
| Element              | 3        | 4.35%   |
| VIZ                  | 2        | 2.9%    |
| Tech Concepts        | 2        | 2.9%    |
| AOC                  | 2        | 2.9%    |
| Unknown              | 1        | 1.45%   |
| UGD                  | 1        | 1.45%   |
| Seiki                | 1        | 1.45%   |
| MTK                  | 1        | 1.45%   |
| MStar                | 1        | 1.45%   |
| eMachines            | 1        | 1.45%   |
| ASUSTek Computer     | 1        | 1.45%   |
| Ancor Communications | 1        | 1.45%   |
| Unknown              | 1        | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5        | 6.67%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 3        | 4%      |
| Element ELEFW328B ELE1366 1366x768 700x400mm 31.7-inch                | 3        | 4%      |
| VIZ LCD Monitor M551d-A2R                                             | 2        | 2.67%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch         | 2        | 2.67%   |
| Sony TV SNY4502 1920x1080                                             | 2        | 2.67%   |
| Sony TV  *00 SNY4B04 3840x2160                                        | 2        | 2.67%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch     | 2        | 2.67%   |
| Hewlett-Packard L2105tm HWP2863 1920x1080 477x268mm 21.5-inch         | 2        | 2.67%   |
| Gateway LCD Monitor FHX2300                                           | 2        | 2.67%   |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch                 | 2        | 2.67%   |
| Acer LCD Monitor G236HL 5760x1080                                     | 2        | 2.67%   |
| Vizio M422i-B1 VIZ1006 1920x1080 930x523mm 42.0-inch                  | 1        | 1.33%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                    | 1        | 1.33%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1        | 1.33%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch         | 1        | 1.33%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch              | 1        | 1.33%   |
| Unknown LCD Monitor Dell S2719DGF 2560x1440                           | 1        | 1.33%   |
| UGD Artist 156 UGD1501 1920x1080 293x165mm 13.2-inch                  | 1        | 1.33%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                            | 1        | 1.33%   |
| Tech Concepts LCD Monitor 43S423 1920x1080                            | 1        | 1.33%   |
| Seiki SE241TS SEK0CF0 1920x1080 520x290mm 23.4-inch                   | 1        | 1.33%   |
| Sceptre Tech Sceptre X22HG SPT2204 1920x1080 474x296mm 22.0-inch      | 1        | 1.33%   |
| Sceptre Tech Sceptre F22 SPT08E3 1920x1080 475x267mm 21.5-inch        | 1        | 1.33%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                | 1        | 1.33%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch     | 1        | 1.33%   |
| Samsung Electronics LCD Monitor SAM0F0B 1920x1080 708x398mm 32.0-inch | 1        | 1.33%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 1        | 1.33%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch    | 1        | 1.33%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 1        | 1.33%   |
| MTK Microtek 815C MTK1021 1280x1024 359x287mm 18.1-inch               | 1        | 1.33%   |
| MStar Demo MST0030 1360x765 708x398mm 32.0-inch                       | 1        | 1.33%   |
| Hewlett-Packard P17A HWP3142 1280x1024 338x270mm 17.0-inch            | 1        | 1.33%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 1        | 1.33%   |
| Hewlett-Packard 2511 HWP293E 1920x1080 550x310mm 24.9-inch            | 1        | 1.33%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 1        | 1.33%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 1        | 1.33%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 1        | 1.33%   |
| Goldstar 27GL650F GSM5B70 1920x1080 531x298mm 24.0-inch               | 1        | 1.33%   |
| Gateway LCD Monitor FHX2300 3840x1080                                 | 1        | 1.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 32       | 51.61%  |
| 3840x2160 (4K)     | 9        | 14.52%  |
| 2560x1440 (QHD)    | 3        | 4.84%   |
| 1280x1024 (SXGA)   | 3        | 4.84%   |
| 5760x1080          | 2        | 3.23%   |
| 1600x900 (HD+)     | 2        | 3.23%   |
| 1440x900 (WXGA+)   | 2        | 3.23%   |
| 1366x768 (WXGA)    | 2        | 3.23%   |
| Unknown            | 2        | 3.23%   |
| 3840x1080          | 1        | 1.61%   |
| 3440x1440          | 1        | 1.61%   |
| 2560x1080          | 1        | 1.61%   |
| 1680x1050 (WSXGA+) | 1        | 1.61%   |
| 1280x720 (HD)      | 1        | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 13       | 20%     |
| 23      | 9        | 13.85%  |
| 72      | 8        | 12.31%  |
| 31      | 6        | 9.23%   |
| Unknown | 5        | 7.69%   |
| 19      | 4        | 6.15%   |
| 20      | 3        | 4.62%   |
| 34      | 2        | 3.08%   |
| 24      | 2        | 3.08%   |
| 18      | 2        | 3.08%   |
| 17      | 2        | 3.08%   |
| 84      | 1        | 1.54%   |
| 64      | 1        | 1.54%   |
| 52      | 1        | 1.54%   |
| 32      | 1        | 1.54%   |
| 27      | 1        | 1.54%   |
| 26      | 1        | 1.54%   |
| 25      | 1        | 1.54%   |
| 22      | 1        | 1.54%   |
| 13      | 1        | 1.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 20       | 32.26%  |
| 501-600     | 13       | 20.97%  |
| 1501-2000   | 8        | 12.9%   |
| 601-700     | 6        | 9.68%   |
| Unknown     | 5        | 8.06%   |
| 701-800     | 3        | 4.84%   |
| 351-400     | 2        | 3.23%   |
| 301-350     | 2        | 3.23%   |
| 1001-1500   | 2        | 3.23%   |
| 201-300     | 1        | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 40       | 72.73%  |
| Unknown | 5        | 9.09%   |
| 5/4     | 4        | 7.27%   |
| 16/10   | 4        | 7.27%   |
| 21/9    | 2        | 3.64%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 20       | 32.79%  |
| 151-200        | 11       | 18.03%  |
| More than 1000 | 9        | 14.75%  |
| 351-500        | 9        | 14.75%  |
| Unknown        | 5        | 8.2%    |
| 141-150        | 3        | 4.92%   |
| 251-300        | 2        | 3.28%   |
| 71-80          | 1        | 1.64%   |
| 301-350        | 1        | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 28       | 47.46%  |
| 101-120 | 15       | 25.42%  |
| 1-50    | 9        | 15.25%  |
| Unknown | 5        | 8.47%   |
| 161-240 | 1        | 1.69%   |
| 121-160 | 1        | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 79.03%  |
| 2     | 9        | 14.52%  |
| 3     | 2        | 3.23%   |
| 0     | 2        | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 46       | 48.94%  |
| Intel                 | 29       | 30.85%  |
| NetGear               | 4        | 4.26%   |
| Ralink Technology     | 3        | 3.19%   |
| Qualcomm Atheros      | 3        | 3.19%   |
| Nvidia                | 2        | 2.13%   |
| TP-Link               | 1        | 1.06%   |
| Samsung Electronics   | 1        | 1.06%   |
| Ralink                | 1        | 1.06%   |
| Microsoft             | 1        | 1.06%   |
| MediaTek              | 1        | 1.06%   |
| Gemtek                | 1        | 1.06%   |
| Aquantia              | 1        | 1.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 26.79%  |
| Intel I211 Gigabit Network Connection                             | 5        | 4.46%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4        | 3.57%   |
| Intel Wi-Fi 6 AX200                                               | 4        | 3.57%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 3.57%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3        | 2.68%   |
| Realtek 802.11ac NIC                                              | 3        | 2.68%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 2.68%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2        | 1.79%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2        | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.79%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 1        | 0.89%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1        | 0.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.89%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 0.89%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.89%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.89%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                            | 1        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 0.89%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.89%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.89%   |
| Ralink RT2870 Wireless Adapter                                    | 1        | 0.89%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1        | 0.89%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.89%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1        | 0.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 0.89%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.89%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.89%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.89%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1        | 0.89%   |
| NetGear MA111(v2) 802.11b Wireless [SIS SIS 162]                  | 1        | 0.89%   |
| NetGear LB1120-100NAS                                             | 1        | 0.89%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1        | 0.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 39.53%  |
| Intel                 | 13       | 30.23%  |
| Ralink Technology     | 3        | 6.98%   |
| NetGear               | 3        | 6.98%   |
| Qualcomm Atheros      | 2        | 4.65%   |
| TP-Link               | 1        | 2.33%   |
| Ralink                | 1        | 2.33%   |
| Microsoft             | 1        | 2.33%   |
| MediaTek              | 1        | 2.33%   |
| Gemtek                | 1        | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                            | 4        | 8.16%   |
| Intel Wi-Fi 6 AX200                                           | 4        | 8.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 4        | 8.16%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 3        | 6.12%   |
| Realtek 802.11ac NIC                                          | 3        | 6.12%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 2        | 4.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 2        | 4.08%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                    | 1        | 2.04%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1        | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1        | 2.04%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1        | 2.04%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1        | 2.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1        | 2.04%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                        | 1        | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1        | 2.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1        | 2.04%   |
| Realtek RTL8187 Wireless Adapter                              | 1        | 2.04%   |
| Ralink RT2870 Wireless Adapter                                | 1        | 2.04%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter             | 1        | 2.04%   |
| Ralink MT7601U Wireless Adapter                               | 1        | 2.04%   |
| Ralink RT2561/RT61 802.11g PCI                                | 1        | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1        | 2.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1        | 2.04%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]               | 1        | 2.04%   |
| NetGear MA111(v2) 802.11b Wireless [SIS SIS 162]              | 1        | 2.04%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]   | 1        | 2.04%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 1        | 2.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1        | 2.04%   |
| Intel Wireless 8265 / 8275                                    | 1        | 2.04%   |
| Intel Wireless 3160                                           | 1        | 2.04%   |
| Intel Wi-Fi 6 AX201 160MHz                                    | 1        | 2.04%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1        | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1        | 2.04%   |
| Gemtek WUBR-177G [Ralink RT2571W]                             | 1        | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 36       | 57.14%  |
| Intel                 | 21       | 33.33%  |
| Nvidia                | 2        | 3.17%   |
| Samsung Electronics   | 1        | 1.59%   |
| Qualcomm Atheros      | 1        | 1.59%   |
| NetGear               | 1        | 1.59%   |
| Aquantia              | 1        | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 47.62%  |
| Intel I211 Gigabit Network Connection                             | 5        | 7.94%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 6.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 6.35%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 4.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 3.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 3.17%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.59%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 1.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.59%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.59%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 1.59%   |
| NetGear LB1120-100NAS                                             | 1        | 1.59%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.59%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.59%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.59%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.59%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.59%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 58       | 62.37%  |
| WiFi     | 35       | 37.63%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 67.69%  |
| WiFi     | 21       | 32.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 62.3%   |
| 2     | 20       | 32.79%  |
| 3     | 2        | 3.28%   |
| 0     | 1        | 1.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 54       | 91.53%  |
| Yes  | 5        | 8.47%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 43.33%  |
| Cambridge Silicon Radio         | 8        | 26.67%  |
| Realtek Semiconductor           | 2        | 6.67%   |
| Broadcom                        | 2        | 6.67%   |
| Qualcomm Atheros Communications | 1        | 3.33%   |
| Lite-On Technology              | 1        | 3.33%   |
| IMC Networks                    | 1        | 3.33%   |
| Dynex                           | 1        | 3.33%   |
| Belkin Components               | 1        | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 8        | 26.67%  |
| Intel Wireless-AC 3168 Bluetooth                         | 4        | 13.33%  |
| Intel AX200 Bluetooth                                    | 4        | 13.33%  |
| Realtek Bluetooth Radio                                  | 2        | 6.67%   |
| Intel Bluetooth wireless interface                       | 2        | 6.67%   |
| Intel AX201 Bluetooth                                    | 2        | 6.67%   |
| Broadcom Bluetooth Device                                | 2        | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                       | 1        | 3.33%   |
| Lite-On Bluetooth Device                                 | 1        | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1        | 3.33%   |
| IMC Networks Wireless_Device                             | 1        | 3.33%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 3.33%   |
| Belkin Components Bluetooth Mini Dongle                  | 1        | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 37       | 42.05%  |
| AMD                                             | 21       | 23.86%  |
| Nvidia                                          | 18       | 20.45%  |
| Logitech                                        | 7        | 7.95%   |
| C-Media Electronics                             | 2        | 2.27%   |
| Nintendo                                        | 1        | 1.14%   |
| Licensed by Sony Computer Entertainment America | 1        | 1.14%   |
| Kingston Technology                             | 1        | 1.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 4.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 4.63%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 4.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 3.7%    |
| Logitech EasyCall Speakerphone                                             | 4        | 3.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 3.7%    |
| AMD FCH Azalia Controller                                                  | 4        | 3.7%    |
| Intel Sunrise Point-LP HD Audio                                            | 3        | 2.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 2.78%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 2.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3        | 2.78%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 2.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 2.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.85%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 1.85%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 1.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2        | 1.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.85%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 1.85%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 1.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.85%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 1.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.93%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.93%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.93%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.93%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 0.93%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 0.93%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 0.93%   |
| Nintendo WUP-021-0                                                         | 1        | 0.93%   |
| Logitech QuickCam Fusion                                                   | 1        | 0.93%   |
| Logitech Headset H390                                                      | 1        | 0.93%   |
| Logitech G635 Gaming Headset                                               | 1        | 0.93%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset    | 1        | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 7        | 31.82%  |
| Samsung Electronics | 3        | 13.64%  |
| SK hynix            | 2        | 9.09%   |
| G.Skill             | 2        | 9.09%   |
| Crucial             | 2        | 9.09%   |
| Corsair             | 2        | 9.09%   |
| Sesame              | 1        | 4.55%   |
| PNY                 | 1        | 4.55%   |
| Kingston            | 1        | 4.55%   |
| Avant               | 1        | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                      | 3        | 12%     |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 4%      |
| Unknown RAM Module 4096MB DIMM 667MT/s                    | 1        | 4%      |
| Unknown RAM Module 1GB DIMM                               | 1        | 4%      |
| Unknown RAM CL18-22-22 D4-3600 16384MB DIMM DDR4 3600MT/s | 1        | 4%      |
| Unknown RAM CL18-20-20 D4-3600 8192MB DIMM DDR4 3600MT/s  | 1        | 4%      |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                | 1        | 4%      |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 4%      |
| Sesame RAM S939A2UGS-ITR 8GB DIMM 1600MT/s                | 1        | 4%      |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s       | 1        | 4%      |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 4%      |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 4%      |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s       | 1        | 4%      |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s       | 1        | 4%      |
| PNY RAM 4GBH1X04E9992 4096MB DIMM DDR3 1600MT/s           | 1        | 4%      |
| Kingston RAM X2YH1K-MIE-NX 16GB DIMM DDR4 3200MT/s        | 1        | 4%      |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s        | 1        | 4%      |
| G.Skill RAM F3-10666CL9-8GBSQ 8GB DIMM DDR3 1333MT/s      | 1        | 4%      |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s     | 1        | 4%      |
| Crucial RAM BL16G26C16U4W.16FD 16GB DIMM DDR4 2667MT/s    | 1        | 4%      |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s  | 1        | 4%      |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s     | 1        | 4%      |
| Avant RAM W641GU42J7240NC 8GB DIMM DDR4 2400MT/s          | 1        | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 9        | 40.91%  |
| DDR4    | 8        | 36.36%  |
| SDRAM   | 3        | 13.64%  |
| Unknown | 2        | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 22       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 10       | 43.48%  |
| 4096  | 6        | 26.09%  |
| 16384 | 3        | 13.04%  |
| 2048  | 3        | 13.04%  |
| 1024  | 1        | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 5        | 21.74%  |
| Unknown | 4        | 17.39%  |
| 3200    | 3        | 13.04%  |
| 1333    | 3        | 13.04%  |
| 3600    | 2        | 8.7%    |
| 3533    | 1        | 4.35%   |
| 2667    | 1        | 4.35%   |
| 2400    | 1        | 4.35%   |
| 1867    | 1        | 4.35%   |
| 1866    | 1        | 4.35%   |
| 667     | 1        | 4.35%   |

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
| Logitech         | 6        | 42.86%  |
| Microdia         | 5        | 35.71%  |
| Razer USA        | 1        | 7.14%   |
| Jieli Technology | 1        | 7.14%   |
| Cubeternet       | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Microdia Camera                     | 4        | 28.57%  |
| Logitech HD Pro Webcam C920         | 2        | 14.29%  |
| Razer USA Razer Kiyo Pro            | 1        | 7.14%   |
| Microdia REDRAGON Live Camera Audio | 1        | 7.14%   |
| Logitech Webcam Pro 9000            | 1        | 7.14%   |
| Logitech Webcam C310                | 1        | 7.14%   |
| Logitech Webcam C270                | 1        | 7.14%   |
| Logitech CrystalCam                 | 1        | 7.14%   |
| Jieli USB PHY 2.0                   | 1        | 7.14%   |
| Cubeternet GL-UPC822 UVC WebCam     | 1        | 7.14%   |

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
| 0     | 49       | 73.13%  |
| 1     | 13       | 19.4%   |
| 2     | 5        | 7.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 68.42%  |
| Graphics card            | 3        | 15.79%  |
| Net/ethernet             | 1        | 5.26%   |
| Multimedia controller    | 1        | 5.26%   |
| Communication controller | 1        | 5.26%   |

