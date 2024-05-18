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

Total: 136

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell      | 0NW6H5 A00                  | [b70239f287](https://linux-hardware.org/?probe=b70239f287) | Apr 15, 2024 |
| Gigabyte  | F2A88XN-WIFI                | [25d9669839](https://linux-hardware.org/?probe=25d9669839) | Mar 25, 2024 |
| Dell      | 0YNVJG A02                  | [c979ee9419](https://linux-hardware.org/?probe=c979ee9419) | Feb 11, 2024 |
| MSI       | MPG B550 GAMING PLUS        | [f38d7bb62a](https://linux-hardware.org/?probe=f38d7bb62a) | Jan 24, 2024 |
| Foxconn   | 2ABF                        | [9a5efc4dd3](https://linux-hardware.org/?probe=9a5efc4dd3) | Jan 19, 2024 |
| MSI       | MPG Z590 GAMING PLUS        | [b9fe694efb](https://linux-hardware.org/?probe=b9fe694efb) | Jan 12, 2024 |
| ASUSTek   | ROG STRIX B450-F GAMING ... | [54f70ad2a1](https://linux-hardware.org/?probe=54f70ad2a1) | Jan 05, 2024 |
| Foxconn   | 2ABF                        | [86bb3586e0](https://linux-hardware.org/?probe=86bb3586e0) | Jan 04, 2024 |
| HP        | 83E1                        | [9006156354](https://linux-hardware.org/?probe=9006156354) | Jan 04, 2024 |
| HP        | 8767 A                      | [6d2a367189](https://linux-hardware.org/?probe=6d2a367189) | Dec 25, 2023 |
| Gigabyte  | Z390 AORUS PRO WIFI-CF      | [2ee56e1ee0](https://linux-hardware.org/?probe=2ee56e1ee0) | Oct 07, 2023 |
| Gigabyte  | B360M DS3H                  | [1308430981](https://linux-hardware.org/?probe=1308430981) | Sep 28, 2023 |
| Gateway   | RS780                       | [d73767c9f7](https://linux-hardware.org/?probe=d73767c9f7) | Aug 21, 2023 |
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
| Ubuntu 20.04                 | 6        | 6.67%   |
| Ubuntu 18.04                 | 6        | 6.67%   |
| OpenMandriva 4.2             | 4        | 4.44%   |
| OpenMandriva 23.03           | 4        | 4.44%   |
| Manjaro                      | 4        | 4.44%   |
| Fedora 39                    | 3        | 3.33%   |
| Zorin 16                     | 2        | 2.22%   |
| Zorin 15                     | 2        | 2.22%   |
| Ubuntu 20.10                 | 2        | 2.22%   |
| ROSA R11                     | 2        | 2.22%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 2.22%   |
| OpenMandriva 4.3             | 2        | 2.22%   |
| Lubuntu 20.04                | 2        | 2.22%   |
| LMDE 4                       | 2        | 2.22%   |
| Linux Mint 20.3              | 2        | 2.22%   |
| Linux Mint 20.1              | 2        | 2.22%   |
| Linux Mint 20                | 2        | 2.22%   |
| Garuda Linux                 | 2        | 2.22%   |
| Fedora 36                    | 2        | 2.22%   |
| ArcoLinux Rolling            | 2        | 2.22%   |
| Xubuntu 20.10                | 1        | 1.11%   |
| Xubuntu 20.04                | 1        | 1.11%   |
| Xero Rolling                 | 1        | 1.11%   |
| Ubuntu Unity 20.04           | 1        | 1.11%   |
| Ubuntu Budgie 21.04          | 1        | 1.11%   |
| Ubuntu 22.04                 | 1        | 1.11%   |
| Ubuntu 21.10                 | 1        | 1.11%   |
| Ubuntu 19.10                 | 1        | 1.11%   |
| ROSA R9                      | 1        | 1.11%   |
| ROSA R10                     | 1        | 1.11%   |
| Pop!_OS 22.04                | 1        | 1.11%   |
| Pop!_OS 21.10                | 1        | 1.11%   |
| Pop!_OS 21.04                | 1        | 1.11%   |
| Pop!_OS 20.10                | 1        | 1.11%   |
| Pop!_OS 20.04                | 1        | 1.11%   |
| Pop!_OS 19.10                | 1        | 1.11%   |
| OpenMandriva 23.10           | 1        | 1.11%   |
| OpenMandriva 23.01           | 1        | 1.11%   |
| Nobara 38                    | 1        | 1.11%   |
| Manjaro 21.1.5               | 1        | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 17       | 20.24%  |
| OpenMandriva  | 11       | 13.1%   |
| Pop!_OS       | 6        | 7.14%   |
| Linux Mint    | 6        | 7.14%   |
| Fedora        | 6        | 7.14%   |
| Manjaro       | 5        | 5.95%   |
| Zorin         | 4        | 4.76%   |
| ROSA          | 3        | 3.57%   |
| ArcoLinux     | 3        | 3.57%   |
| Xubuntu       | 2        | 2.38%   |
| openSUSE      | 2        | 2.38%   |
| Lubuntu       | 2        | 2.38%   |
| LMDE          | 2        | 2.38%   |
| KDE neon      | 2        | 2.38%   |
| Garuda Linux  | 2        | 2.38%   |
| Xero          | 1        | 1.19%   |
| Ubuntu Unity  | 1        | 1.19%   |
| Ubuntu Budgie | 1        | 1.19%   |
| Nobara        | 1        | 1.19%   |
| LinuxFX       | 1        | 1.19%   |
| Endless       | 1        | 1.19%   |
| Devuan        | 1        | 1.19%   |
| Debian        | 1        | 1.19%   |
| CentOS        | 1        | 1.19%   |
| BlackPanther  | 1        | 1.19%   |
| Arch          | 1        | 1.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 6.2.6-desktop-1omv2390              | 4        | 3.96%   |
| 5.10.14-desktop-1omv4002            | 4        | 3.96%   |
| 5.8.18-1-MANJARO                    | 2        | 1.98%   |
| 5.8.0-45-generic                    | 2        | 1.98%   |
| 5.4.0-72-generic                    | 2        | 1.98%   |
| 5.4.0-58-generic                    | 2        | 1.98%   |
| 5.4.0-109-generic                   | 2        | 1.98%   |
| 5.16.7-desktop-1omv4003             | 2        | 1.98%   |
| 5.13.0-39-generic                   | 2        | 1.98%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 2        | 1.98%   |
| 6.8.5-1-default                     | 1        | 0.99%   |
| 6.7.4-200.fc39.x86_64               | 1        | 0.99%   |
| 6.7.1-0.rc1.250.vanilla.fc39.x86_64 | 1        | 0.99%   |
| 6.6.9-arch1-1                       | 1        | 0.99%   |
| 6.6.6-76060606-generic              | 1        | 0.99%   |
| 6.6.12-200.fc39.x86_64              | 1        | 0.99%   |
| 6.5.5-desktop-1omv2390              | 1        | 0.99%   |
| 6.5.11-201.fsync.fc38.x86_64        | 1        | 0.99%   |
| 6.4.12-arch1-1                      | 1        | 0.99%   |
| 6.2.15-300.fc38.x86_64              | 1        | 0.99%   |
| 6.2.0-33-generic                    | 1        | 0.99%   |
| 6.2.0-26-generic                    | 1        | 0.99%   |
| 6.1.1-desktop-1omv2290              | 1        | 0.99%   |
| 5.9.16-1-MANJARO                    | 1        | 0.99%   |
| 5.9.1-1-MANJARO                     | 1        | 0.99%   |
| 5.8.5-zen1-1-zen                    | 1        | 0.99%   |
| 5.8.14-zen1-1-zen                   | 1        | 0.99%   |
| 5.8.0-7630-generic                  | 1        | 0.99%   |
| 5.8.0-54-generic                    | 1        | 0.99%   |
| 5.8.0-53-generic                    | 1        | 0.99%   |
| 5.8.0-49-generic                    | 1        | 0.99%   |
| 5.8.0-44-generic                    | 1        | 0.99%   |
| 5.8.0-29-generic                    | 1        | 0.99%   |
| 5.8.0-25-generic                    | 1        | 0.99%   |
| 5.8.0-14-generic                    | 1        | 0.99%   |
| 5.4.0-89-generic                    | 1        | 0.99%   |
| 5.4.0-88-generic                    | 1        | 0.99%   |
| 5.4.0-7634-generic                  | 1        | 0.99%   |
| 5.4.0-73-generic                    | 1        | 0.99%   |
| 5.4.0-65-generic                    | 1        | 0.99%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 18       | 19.57%  |
| 5.8.0    | 8        | 8.7%    |
| 4.15.0   | 6        | 6.52%   |
| 6.2.6    | 4        | 4.35%   |
| 5.11.0   | 4        | 4.35%   |
| 5.10.14  | 4        | 4.35%   |
| 5.3.0    | 3        | 3.26%   |
| 6.2.0    | 2        | 2.17%   |
| 5.8.18   | 2        | 2.17%   |
| 5.16.7   | 2        | 2.17%   |
| 5.13.0   | 2        | 2.17%   |
| 4.19.0   | 2        | 2.17%   |
| 4.18.0   | 2        | 2.17%   |
| 6.8.5    | 1        | 1.09%   |
| 6.7.4    | 1        | 1.09%   |
| 6.7.1    | 1        | 1.09%   |
| 6.6.9    | 1        | 1.09%   |
| 6.6.6    | 1        | 1.09%   |
| 6.6.12   | 1        | 1.09%   |
| 6.5.5    | 1        | 1.09%   |
| 6.5.11   | 1        | 1.09%   |
| 6.4.12   | 1        | 1.09%   |
| 6.2.15   | 1        | 1.09%   |
| 6.1.1    | 1        | 1.09%   |
| 5.9.16   | 1        | 1.09%   |
| 5.9.1    | 1        | 1.09%   |
| 5.8.5    | 1        | 1.09%   |
| 5.8.14   | 1        | 1.09%   |
| 5.19.12  | 1        | 1.09%   |
| 5.19.0   | 1        | 1.09%   |
| 5.18.9   | 1        | 1.09%   |
| 5.18.5   | 1        | 1.09%   |
| 5.18.15  | 1        | 1.09%   |
| 5.17.1   | 1        | 1.09%   |
| 5.15.5   | 1        | 1.09%   |
| 5.15.109 | 1        | 1.09%   |
| 5.15.0   | 1        | 1.09%   |
| 5.14.8   | 1        | 1.09%   |
| 5.14.0   | 1        | 1.09%   |
| 5.13.19  | 1        | 1.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 18       | 20.22%  |
| 5.8     | 12       | 13.48%  |
| 6.2     | 7        | 7.87%   |
| 4.15    | 6        | 6.74%   |
| 5.10    | 5        | 5.62%   |
| 5.11    | 4        | 4.49%   |
| 6.6     | 3        | 3.37%   |
| 5.3     | 3        | 3.37%   |
| 5.15    | 3        | 3.37%   |
| 5.13    | 3        | 3.37%   |
| 4.9     | 3        | 3.37%   |
| 6.7     | 2        | 2.25%   |
| 6.5     | 2        | 2.25%   |
| 5.9     | 2        | 2.25%   |
| 5.19    | 2        | 2.25%   |
| 5.18    | 2        | 2.25%   |
| 5.16    | 2        | 2.25%   |
| 5.14    | 2        | 2.25%   |
| 4.19    | 2        | 2.25%   |
| 4.18    | 2        | 2.25%   |
| 6.8     | 1        | 1.12%   |
| 6.4     | 1        | 1.12%   |
| 6.1     | 1        | 1.12%   |
| 5.17    | 1        | 1.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 68       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 32       | 38.1%   |
| KDE5          | 21       | 25%     |
| X-Cinnamon    | 8        | 9.52%   |
| XFCE          | 4        | 4.76%   |
| Unknown       | 4        | 4.76%   |
| MATE          | 2        | 2.38%   |
| LXQt          | 2        | 2.38%   |
| KDE           | 2        | 2.38%   |
| Budgie        | 2        | 2.38%   |
| Unity         | 1        | 1.19%   |
| LXDE          | 1        | 1.19%   |
| KDE6          | 1        | 1.19%   |
| KDE4          | 1        | 1.19%   |
| GNOME Classic | 1        | 1.19%   |
| Deepin        | 1        | 1.19%   |
| Cinnamon      | 1        | 1.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 58       | 85.29%  |
| Wayland | 9        | 13.24%  |
| Unknown | 1        | 1.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 48       | 62.34%  |
| SDDM    | 15       | 19.48%  |
| GDM     | 5        | 6.49%   |
| GDM3    | 4        | 5.19%   |
| LightDM | 3        | 3.9%    |
| TDM     | 1        | 1.3%    |
| KDM     | 1        | 1.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 58       | 84.06%  |
| Unknown | 7        | 10.14%  |
| es_ES   | 2        | 2.9%    |
| es_PR   | 1        | 1.45%   |
| C       | 1        | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 39       | 53.42%  |
| EFI  | 34       | 46.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 50       | 68.49%  |
| Overlay | 9        | 12.33%  |
| Btrfs   | 9        | 12.33%  |
| Unknown | 3        | 4.11%   |
| Xfs     | 1        | 1.37%   |
| Tmpfs   | 1        | 1.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 51       | 68%     |
| GPT     | 17       | 22.67%  |
| MBR     | 7        | 9.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 84.93%  |
| Yes       | 11       | 15.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 77.03%  |
| Yes       | 17       | 22.97%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 12       | 17.65%  |
| ASRock              | 10       | 14.71%  |
| Hewlett-Packard     | 9        | 13.24%  |
| MSI                 | 8        | 11.76%  |
| Dell                | 8        | 11.76%  |
| ASUSTek Computer    | 8        | 11.76%  |
| Lenovo              | 3        | 4.41%   |
| Intel               | 3        | 4.41%   |
| Gateway             | 2        | 2.94%   |
| Pegatron            | 1        | 1.47%   |
| Foxconn             | 1        | 1.47%   |
| ECS                 | 1        | 1.47%   |
| Alienware           | 1        | 1.47%   |
| Acer                | 1        | 1.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel SKYBAY                            | 3        | 4.41%   |
| MSI Cubi N 8GL (MS-B171)                | 2        | 2.94%   |
| ASRock Q1900M                           | 2        | 2.94%   |
| ASRock 945GCM-S                         | 2        | 2.94%   |
| Pegatron QW716AA#ABA                    | 1        | 1.47%   |
| MSI MS-7D07                             | 1        | 1.47%   |
| MSI MS-7C56                             | 1        | 1.47%   |
| MSI MS-7B48                             | 1        | 1.47%   |
| MSI MS-7971                             | 1        | 1.47%   |
| MSI MS-7817                             | 1        | 1.47%   |
| MSI Cubi N JSL (MS-B0A1)                | 1        | 1.47%   |
| Lenovo ThinkCentre M91p 7033CG1         | 1        | 1.47%   |
| Lenovo ThinkCentre M58p 6136A66         | 1        | 1.47%   |
| Lenovo IdeaCentre 510A-15ARR 90J0000PUS | 1        | 1.47%   |
| HP Pavilion Desktop TP01-3xxx           | 1        | 1.47%   |
| HP Pavilion Desktop TP01-1xxx           | 1        | 1.47%   |
| HP EliteDesk 800 G4 SFF                 | 1        | 1.47%   |
| HP EliteDesk 800 G1 TWR                 | 1        | 1.47%   |
| HP EliteDesk 800 G1 SFF                 | 1        | 1.47%   |
| HP Compaq Pro 6300 SFF                  | 1        | 1.47%   |
| HP Compaq Pro 6300 MT                   | 1        | 1.47%   |
| HP Compaq dc7800p Small Form Factor     | 1        | 1.47%   |
| HP Compaq 8200 Elite SFF PC             | 1        | 1.47%   |
| Gigabyte Z97M-DS3H                      | 1        | 1.47%   |
| Gigabyte Z390 AORUS PRO WIFI            | 1        | 1.47%   |
| Gigabyte X570 GAMING X                  | 1        | 1.47%   |
| Gigabyte X570 AORUS ELITE WIFI          | 1        | 1.47%   |
| Gigabyte X399 AORUS Gaming 7            | 1        | 1.47%   |
| Gigabyte J1900N-D3V                     | 1        | 1.47%   |
| Gigabyte F2A88XN-WIFI                   | 1        | 1.47%   |
| Gigabyte F2A78M-HD2                     | 1        | 1.47%   |
| Gigabyte F2A68HM-H                      | 1        | 1.47%   |
| Gigabyte B450M DS3H                     | 1        | 1.47%   |
| Gigabyte B450 AORUS PRO WIFI            | 1        | 1.47%   |
| Gigabyte B360M-DS3H                     | 1        | 1.47%   |
| Gateway SX2865                          | 1        | 1.47%   |
| Gateway DX4300                          | 1        | 1.47%   |
| Foxconn Pro3500 Series                  | 1        | 1.47%   |
| ECS NC696AAR-ABA SR5710Y                | 1        | 1.47%   |
| Dell Studio 540                         | 1        | 1.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 6        | 8.82%   |
| HP Compaq             | 4        | 5.88%   |
| MSI Cubi              | 3        | 4.41%   |
| Intel SKYBAY          | 3        | 4.41%   |
| HP EliteDesk          | 3        | 4.41%   |
| ASUS ROG              | 3        | 4.41%   |
| Lenovo ThinkCentre    | 2        | 2.94%   |
| HP Pavilion           | 2        | 2.94%   |
| Gigabyte X570         | 2        | 2.94%   |
| ASUS TUF              | 2        | 2.94%   |
| ASRock Q1900M         | 2        | 2.94%   |
| ASRock B450M-HDV      | 2        | 2.94%   |
| ASRock 945GCM-S       | 2        | 2.94%   |
| Pegatron QW716AA#ABA  | 1        | 1.47%   |
| MSI MS-7D07           | 1        | 1.47%   |
| MSI MS-7C56           | 1        | 1.47%   |
| MSI MS-7B48           | 1        | 1.47%   |
| MSI MS-7971           | 1        | 1.47%   |
| MSI MS-7817           | 1        | 1.47%   |
| Lenovo IdeaCentre     | 1        | 1.47%   |
| Gigabyte Z97M-DS3H    | 1        | 1.47%   |
| Gigabyte Z390         | 1        | 1.47%   |
| Gigabyte X399         | 1        | 1.47%   |
| Gigabyte J1900N-D3V   | 1        | 1.47%   |
| Gigabyte F2A88XN-WIFI | 1        | 1.47%   |
| Gigabyte F2A78M-HD2   | 1        | 1.47%   |
| Gigabyte F2A68HM-H    | 1        | 1.47%   |
| Gigabyte B450M        | 1        | 1.47%   |
| Gigabyte B450         | 1        | 1.47%   |
| Gigabyte B360M-DS3H   | 1        | 1.47%   |
| Gateway SX2865        | 1        | 1.47%   |
| Gateway DX4300        | 1        | 1.47%   |
| Foxconn Pro3500       | 1        | 1.47%   |
| ECS NC696AAR-ABA      | 1        | 1.47%   |
| Dell Studio           | 1        | 1.47%   |
| Dell Inspiron         | 1        | 1.47%   |
| ASUS PRIME            | 1        | 1.47%   |
| ASUS M5A78L-M         | 1        | 1.47%   |
| ASUS M2N-E            | 1        | 1.47%   |
| ASRock Z270           | 1        | 1.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 15       | 22.06%  |
| 2019 | 7        | 10.29%  |
| 2013 | 7        | 10.29%  |
| 2014 | 6        | 8.82%   |
| 2008 | 6        | 8.82%   |
| 2020 | 5        | 7.35%   |
| 2021 | 4        | 5.88%   |
| 2011 | 4        | 5.88%   |
| 2017 | 3        | 4.41%   |
| 2016 | 2        | 2.94%   |
| 2012 | 2        | 2.94%   |
| 2009 | 2        | 2.94%   |
| 2022 | 1        | 1.47%   |
| 2015 | 1        | 1.47%   |
| 2010 | 1        | 1.47%   |
| 2007 | 1        | 1.47%   |
| 2006 | 1        | 1.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 68       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 66       | 95.65%  |
| Enabled  | 3        | 4.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 68       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 17       | 23.61%  |
| 16.01-24.0  | 17       | 23.61%  |
| 8.01-16.0   | 11       | 15.28%  |
| 32.01-64.0  | 9        | 12.5%   |
| 3.01-4.0    | 9        | 12.5%   |
| 24.01-32.0  | 4        | 5.56%   |
| 64.01-256.0 | 2        | 2.78%   |
| 1.01-2.0    | 2        | 2.78%   |
| 0.51-1.0    | 1        | 1.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 31       | 37.8%   |
| 2.01-3.0  | 19       | 23.17%  |
| 4.01-8.0  | 12       | 14.63%  |
| 3.01-4.0  | 11       | 13.41%  |
| 0.51-1.0  | 6        | 7.32%   |
| 8.01-16.0 | 3        | 3.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 34       | 46.58%  |
| 2      | 18       | 24.66%  |
| 3      | 13       | 17.81%  |
| 4      | 4        | 5.48%   |
| 5      | 2        | 2.74%   |
| 6      | 1        | 1.37%   |
| 0      | 1        | 1.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 39       | 56.52%  |
| No        | 30       | 43.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 67       | 98.53%  |
| No        | 1        | 1.47%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 42       | 60%     |
| No        | 28       | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 55.56%  |
| Yes       | 32       | 44.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Puerto Rico | 68       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| San Juan      | 25       | 32.47%  |
| Bayamón      | 11       | 14.29%  |
| Carolina      | 4        | 5.19%   |
| Caguas        | 3        | 3.9%    |
| Aguadilla     | 3        | 3.9%    |
| Vega Alta     | 2        | 2.6%    |
| San Sebastian | 2        | 2.6%    |
| Rio Grande    | 2        | 2.6%    |
| Ponce         | 2        | 2.6%    |
| Dorado        | 2        | 2.6%    |
| Cayey         | 2        | 2.6%    |
| Yauco         | 1        | 1.3%    |
| Toa Baja      | 1        | 1.3%    |
| Sabana Grande | 1        | 1.3%    |
| Patillas      | 1        | 1.3%    |
| Morovis       | 1        | 1.3%    |
| Mayagüez     | 1        | 1.3%    |
| Maunabo       | 1        | 1.3%    |
| Manati        | 1        | 1.3%    |
| Las Piedras   | 1        | 1.3%    |
| Humacao       | 1        | 1.3%    |
| Hatillo       | 1        | 1.3%    |
| Gurabo        | 1        | 1.3%    |
| Guayama       | 1        | 1.3%    |
| Garrochales   | 1        | 1.3%    |
| Fajardo       | 1        | 1.3%    |
| Ensenada      | 1        | 1.3%    |
| Coamo         | 1        | 1.3%    |
| Catano        | 1        | 1.3%    |
| Barceloneta   | 1        | 1.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 23       | 61     | 20.91%  |
| Seagate                   | 17       | 33     | 15.45%  |
| Toshiba                   | 11       | 16     | 10%     |
| Samsung Electronics       | 8        | 17     | 7.27%   |
| Sandisk                   | 6        | 6      | 5.45%   |
| China                     | 5        | 8      | 4.55%   |
| Micron/Crucial Technology | 4        | 5      | 3.64%   |
| Kingston                  | 4        | 4      | 3.64%   |
| TDAS                      | 3        | 17     | 2.73%   |
| SPCC                      | 3        | 4      | 2.73%   |
| Crucial                   | 3        | 3      | 2.73%   |
| Silicon Motion            | 2        | 2      | 1.82%   |
| SABRENT                   | 2        | 3      | 1.82%   |
| Phison                    | 2        | 2      | 1.82%   |
| LITEONIT                  | 2        | 2      | 1.82%   |
| Hitachi                   | 2        | 2      | 1.82%   |
| WD MediaMax               | 1        | 3      | 0.91%   |
| Unknown                   | 1        | 2      | 0.91%   |
| Team                      | 1        | 1      | 0.91%   |
| Realtek Semiconductor     | 1        | 1      | 0.91%   |
| PNY                       | 1        | 2      | 0.91%   |
| Patriot                   | 1        | 2      | 0.91%   |
| OCZ                       | 1        | 1      | 0.91%   |
| Mushkin                   | 1        | 1      | 0.91%   |
| MaxDigital                | 1        | 1      | 0.91%   |
| JMicron Technology        | 1        | 4      | 0.91%   |
| Intel                     | 1        | 1      | 0.91%   |
| addlink                   | 1        | 1      | 0.91%   |
| A-DATA Technology         | 1        | 5      | 0.91%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                           | 4        | 3.25%   |
| TDAS TerraMaster 500GB                           | 3        | 2.44%   |
| WDC WDBNCE2500PNC 250GB SSD                      | 2        | 1.63%   |
| WDC WD5000LPLX-22ZNTT0 500GB                     | 2        | 1.63%   |
| WDC WD40EZRZ-22GXCB0 4TB                         | 2        | 1.63%   |
| Toshiba MQ01ABD100 1TB                           | 2        | 1.63%   |
| Toshiba DT01ACA050 500GB                         | 2        | 1.63%   |
| Seagate ST3250310AS 250GB                        | 2        | 1.63%   |
| Seagate ST320DM001 HD322GJ 320GB                 | 2        | 1.63%   |
| Seagate ST2000VM003-1CT164 2TB                   | 2        | 1.63%   |
| Seagate Expansion 2TB                            | 2        | 1.63%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB | 2        | 1.63%   |
| SanDisk NVMe SSD Drive 1TB                       | 2        | 1.63%   |
| Samsung SSD 850 EVO 500GB                        | 2        | 1.63%   |
| Samsung NVMe SSD Drive 500GB                     | 2        | 1.63%   |
| SABRENT Disk 1TB                                 | 2        | 1.63%   |
| Micron/Crucial NVMe SSD Drive 500GB              | 2        | 1.63%   |
| Kingston SKC6001024G 1TB SSD                     | 2        | 1.63%   |
| China SATA SSD 512GB                             | 2        | 1.63%   |
| China SATA SSD 1024GB                            | 2        | 1.63%   |
| WDC WDBNCE5000PNC 500GB SSD                      | 1        | 0.81%   |
| WDC WD7500BPVX-60JC3T0 752GB                     | 1        | 0.81%   |
| WDC WD5000LPCX-00VHAT0 500GB                     | 1        | 0.81%   |
| WDC WD5000BEVT-55A0RT0 500GB                     | 1        | 0.81%   |
| WDC WD40EZRZ-00GXCB0 4TB                         | 1        | 0.81%   |
| WDC WD30EZRZ-00WN9B0 3TB                         | 1        | 0.81%   |
| WDC WD2500BPVT-22ZEST0 250GB                     | 1        | 0.81%   |
| WDC WD20EZRZ-00Z5HB0 2TB                         | 1        | 0.81%   |
| WDC WD1600AAJS-00PSA0 160GB                      | 1        | 0.81%   |
| WDC WD1500HLFS-01G6U1 150GB                      | 1        | 0.81%   |
| WDC WD1200BEVS-75UST0 120GB                      | 1        | 0.81%   |
| WDC WD10SPZX-22Z10T1 1TB                         | 1        | 0.81%   |
| WDC WD10EZRX-00L4HB0 1TB                         | 1        | 0.81%   |
| WDC WD10EZEX-75WN4A1 1TB                         | 1        | 0.81%   |
| WDC WD10EZEX-08WN4A0 1TB                         | 1        | 0.81%   |
| WDC WD10EZEX-00BN5A0 1TB                         | 1        | 0.81%   |
| WDC WD10EURX-63FH1Y0 1TB                         | 1        | 0.81%   |
| WDC WD10EAVS-00D7B1 1TB                          | 1        | 0.81%   |
| WDC WD1003FBYZ-010FB0 1TB                        | 1        | 0.81%   |
| WDC WD1003FBYX-05Y7B0 1TB                        | 1        | 0.81%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 19       | 55     | 34.55%  |
| Seagate             | 17       | 33     | 30.91%  |
| Toshiba             | 10       | 15     | 18.18%  |
| TDAS                | 3        | 17     | 5.45%   |
| SABRENT             | 2        | 3      | 3.64%   |
| Hitachi             | 2        | 2      | 3.64%   |
| Samsung Electronics | 1        | 1      | 1.82%   |
| MaxDigital          | 1        | 1      | 1.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| China               | 5        | 8      | 17.24%  |
| Samsung Electronics | 4        | 8      | 13.79%  |
| Kingston            | 4        | 4      | 13.79%  |
| WDC                 | 3        | 5      | 10.34%  |
| Crucial             | 3        | 3      | 10.34%  |
| SPCC                | 2        | 3      | 6.9%    |
| LITEONIT            | 2        | 2      | 6.9%    |
| SanDisk             | 1        | 1      | 3.45%   |
| PNY                 | 1        | 2      | 3.45%   |
| Patriot             | 1        | 2      | 3.45%   |
| OCZ                 | 1        | 1      | 3.45%   |
| Mushkin             | 1        | 1      | 3.45%   |
| A-DATA Technology   | 1        | 5      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 47       | 127    | 47.47%  |
| SSD     | 27       | 45     | 27.27%  |
| NVMe    | 22       | 29     | 22.22%  |
| Unknown | 3        | 9      | 3.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 61       | 152    | 66.3%   |
| NVMe | 22       | 29     | 23.91%  |
| SAS  | 9        | 29     | 9.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 38       | 74     | 44.19%  |
| 0.51-1.0   | 30       | 62     | 34.88%  |
| 1.01-2.0   | 11       | 24     | 12.79%  |
| 3.01-4.0   | 6        | 11     | 6.98%   |
| 2.01-3.0   | 1        | 1      | 1.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 20       | 23.53%  |
| 101-250        | 13       | 15.29%  |
| 501-1000       | 12       | 14.12%  |
| 1001-2000      | 10       | 11.76%  |
| More than 3000 | 9        | 10.59%  |
| 2001-3000      | 9        | 10.59%  |
| 1-20           | 6        | 7.06%   |
| 51-100         | 3        | 3.53%   |
| Unknown        | 3        | 3.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 30       | 35.29%  |
| 21-50          | 14       | 16.47%  |
| 101-250        | 9        | 10.59%  |
| 251-500        | 8        | 9.41%   |
| 51-100         | 7        | 8.24%   |
| 1001-2000      | 6        | 7.06%   |
| 501-1000       | 5        | 5.88%   |
| Unknown        | 3        | 3.53%   |
| 2001-3000      | 2        | 2.35%   |
| More than 3000 | 1        | 1.18%   |

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
| Detected | 53       | 168    | 69.74%  |
| Works    | 19       | 34     | 25%     |
| Malfunc  | 4        | 8      | 5.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 44       | 47.83%  |
| AMD                          | 23       | 25%     |
| SanDisk                      | 6        | 6.52%   |
| Samsung Electronics          | 4        | 4.35%   |
| Phison Electronics           | 4        | 4.35%   |
| Micron/Crucial Technology    | 4        | 4.35%   |
| Silicon Motion               | 3        | 3.26%   |
| Nvidia                       | 2        | 2.17%   |
| Toshiba America Info Systems | 1        | 1.09%   |
| Realtek Semiconductor        | 1        | 1.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16       | 13.56%  |
| Intel SATA Controller [RAID mode]                                                       | 8        | 6.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 5.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 4.24%   |
| Phison E12 NVMe Controller                                                              | 4        | 3.39%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4        | 3.39%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 2.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 2.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 2.54%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 2.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 2.54%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 2.54%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 2        | 1.69%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2        | 1.69%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 2        | 1.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 1.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 1.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 1.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.69%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.69%   |
| AMD FCH IDE Controller                                                                  | 2        | 1.69%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.69%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                     | 1        | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.85%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 1        | 0.85%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.85%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.85%   |
| Nvidia CK804 Serial ATA Controller                                                      | 1        | 0.85%   |
| Nvidia CK804 IDE                                                                        | 1        | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 0.85%   |
| Intel SSD 665p Series [Neptune Harbor Refresh]                                          | 1        | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.85%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 1        | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 51       | 51.52%  |
| NVMe | 22       | 22.22%  |
| IDE  | 17       | 17.17%  |
| RAID | 9        | 9.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 43       | 63.24%  |
| AMD    | 25       | 36.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz              | 3        | 4.41%   |
| Intel Celeron CPU 3865U @ 1.80GHz              | 3        | 4.41%   |
| AMD Ryzen 5 3600 6-Core Processor              | 3        | 4.41%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz       | 2        | 2.94%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 2        | 2.94%   |
| Intel Core i5-9500 CPU @ 3.00GHz               | 2        | 2.94%   |
| Intel Core i3-3240 CPU @ 3.40GHz               | 2        | 2.94%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 2        | 2.94%   |
| Intel Celeron CPU E1200 @ 1.60GHz              | 2        | 2.94%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz         | 2        | 2.94%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 2        | 2.94%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 2        | 2.94%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 2        | 2.94%   |
| AMD A6-5400K APU with Radeon HD Graphics       | 2        | 2.94%   |
| Intel Pentium Silver N6000 @ 1.10GHz           | 1        | 1.47%   |
| Intel Core i7-9700 CPU @ 3.00GHz               | 1        | 1.47%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 1.47%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 1.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 1.47%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 1        | 1.47%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 1.47%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 1.47%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 1        | 1.47%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1        | 1.47%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.47%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 1        | 1.47%   |
| Intel Core i3-4150 CPU @ 3.50GHz               | 1        | 1.47%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1        | 1.47%   |
| Intel Core i3-2130 CPU @ 3.40GHz               | 1        | 1.47%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 1.47%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 1        | 1.47%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz           | 1        | 1.47%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz           | 1        | 1.47%   |
| Intel Celeron CPU G1850 @ 2.90GHz              | 1        | 1.47%   |
| Intel Celeron CPU G1840 @ 2.80GHz              | 1        | 1.47%   |
| Intel 12th Gen Core i3-12100                   | 1        | 1.47%   |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz       | 1        | 1.47%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 1.47%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 1.47%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 1.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 10       | 14.71%  |
| Intel Core i5           | 8        | 11.76%  |
| Intel Core i3           | 7        | 10.29%  |
| AMD Ryzen 5             | 7        | 10.29%  |
| Intel Core i7           | 5        | 7.35%   |
| Other                   | 4        | 5.88%   |
| Intel Core 2 Duo        | 4        | 5.88%   |
| AMD Ryzen 7             | 4        | 5.88%   |
| Intel Pentium Silver    | 3        | 4.41%   |
| AMD Ryzen 3             | 3        | 4.41%   |
| Intel Pentium Dual-Core | 2        | 2.94%   |
| AMD A8                  | 2        | 2.94%   |
| AMD A6                  | 2        | 2.94%   |
| AMD Ryzen Threadripper  | 1        | 1.47%   |
| AMD Phenom II X4        | 1        | 1.47%   |
| AMD FX                  | 1        | 1.47%   |
| AMD Athlon X4           | 1        | 1.47%   |
| AMD Athlon Dual Core    | 1        | 1.47%   |
| AMD Athlon 64 X2        | 1        | 1.47%   |
| AMD Athlon              | 1        | 1.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 25       | 36.23%  |
| 4      | 20       | 28.99%  |
| 6      | 14       | 20.29%  |
| 8      | 6        | 8.7%    |
| 1      | 3        | 4.35%   |
| 16     | 1        | 1.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 68       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 36       | 52.17%  |
| 2      | 33       | 47.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 68       | 98.55%  |
| Unknown        | 1        | 1.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 35.53%  |
| 0x306c3    | 6        | 7.89%   |
| 0x1067a    | 4        | 5.26%   |
| 0x806e9    | 3        | 3.95%   |
| 0xa0671    | 2        | 2.63%   |
| 0x906ea    | 2        | 2.63%   |
| 0x6fd      | 2        | 2.63%   |
| 0x306a9    | 2        | 2.63%   |
| 0x30678    | 2        | 2.63%   |
| 0x08701021 | 2        | 2.63%   |
| 0x08701013 | 2        | 2.63%   |
| 0x0800820d | 2        | 2.63%   |
| 0x06001119 | 2        | 2.63%   |
| 0x906ed    | 1        | 1.32%   |
| 0x906e9    | 1        | 1.32%   |
| 0x906c0    | 1        | 1.32%   |
| 0x90675    | 1        | 1.32%   |
| 0x706a1    | 1        | 1.32%   |
| 0x6fb      | 1        | 1.32%   |
| 0x506e3    | 1        | 1.32%   |
| 0x30679    | 1        | 1.32%   |
| 0x206a7    | 1        | 1.32%   |
| 0x0a50000d | 1        | 1.32%   |
| 0x08108109 | 1        | 1.32%   |
| 0x0810100b | 1        | 1.32%   |
| 0x08101007 | 1        | 1.32%   |
| 0x08001137 | 1        | 1.32%   |
| 0x06003106 | 1        | 1.32%   |
| 0x06003104 | 1        | 1.32%   |
| 0x06000852 | 1        | 1.32%   |
| 0x03000027 | 1        | 1.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 11       | 16.18%  |
| Haswell          | 6        | 8.82%   |
| Zen+             | 5        | 7.35%   |
| Zen 2            | 5        | 7.35%   |
| Penryn           | 5        | 7.35%   |
| Zen              | 4        | 5.88%   |
| Silvermont       | 3        | 4.41%   |
| SandyBridge      | 3        | 4.41%   |
| Piledriver       | 3        | 4.41%   |
| IvyBridge        | 3        | 4.41%   |
| Core             | 3        | 4.41%   |
| Zen 3            | 2        | 2.94%   |
| Steamroller      | 2        | 2.94%   |
| K8 Hammer        | 2        | 2.94%   |
| Goldmont plus    | 2        | 2.94%   |
| Unknown          | 2        | 2.94%   |
| Tremont          | 1        | 1.47%   |
| Skylake          | 1        | 1.47%   |
| K10 Llano        | 1        | 1.47%   |
| K10              | 1        | 1.47%   |
| Icelake          | 1        | 1.47%   |
| CometLake        | 1        | 1.47%   |
| Alderlake Hybrid | 1        | 1.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 36       | 46.75%  |
| Nvidia | 21       | 27.27%  |
| AMD    | 20       | 25.97%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 6.1%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 4.88%   |
| Intel HD Graphics 610                                                       | 3        | 3.66%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3        | 3.66%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 3.66%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 3.66%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 2.44%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.44%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 2.44%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 2        | 2.44%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.44%   |
| Intel HD Graphics 630                                                       | 2        | 2.44%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 2        | 2.44%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 2.44%   |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 2        | 2.44%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 2.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.44%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.22%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 1.22%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.22%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.22%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.22%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.22%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.22%   |
| Nvidia GK110GL [Tesla K20Xm]                                                | 1        | 1.22%   |
| Nvidia GK104GL [GRID K2]                                                    | 1        | 1.22%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.22%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.22%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 1.22%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 1        | 1.22%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 1.22%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 1.22%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 1.22%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.22%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 1        | 1.22%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 31       | 43.66%  |
| 1 x AMD            | 18       | 25.35%  |
| 1 x Nvidia         | 16       | 22.54%  |
| Intel + 2 x Nvidia | 2        | 2.82%   |
| Intel + Nvidia     | 2        | 2.82%   |
| Intel + AMD        | 1        | 1.41%   |
| AMD + Nvidia       | 1        | 1.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 57       | 80.28%  |
| Proprietary | 11       | 15.49%  |
| Unknown     | 3        | 4.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 40       | 54.05%  |
| 1.01-2.0   | 8        | 10.81%  |
| 0.01-0.5   | 8        | 10.81%  |
| 3.01-4.0   | 7        | 9.46%   |
| 0.51-1.0   | 4        | 5.41%   |
| 8.01-16.0  | 3        | 4.05%   |
| 7.01-8.0   | 2        | 2.7%    |
| 5.01-6.0   | 2        | 2.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 14       | 17.5%   |
| Samsung Electronics  | 8        | 10%     |
| Dell                 | 7        | 8.75%   |
| Acer                 | 7        | 8.75%   |
| Hewlett-Packard      | 6        | 7.5%    |
| ViewSonic            | 4        | 5%      |
| Sony                 | 4        | 5%      |
| Sceptre Tech         | 4        | 5%      |
| Vizio                | 3        | 3.75%   |
| Gateway              | 3        | 3.75%   |
| Element              | 3        | 3.75%   |
| VIZ                  | 2        | 2.5%    |
| Unknown              | 2        | 2.5%    |
| Tech Concepts        | 2        | 2.5%    |
| AOC                  | 2        | 2.5%    |
| UGD                  | 1        | 1.25%   |
| Seiki                | 1        | 1.25%   |
| SANSUI               | 1        | 1.25%   |
| MTK                  | 1        | 1.25%   |
| MStar                | 1        | 1.25%   |
| eMachines            | 1        | 1.25%   |
| ASUSTek Computer     | 1        | 1.25%   |
| Ancor Communications | 1        | 1.25%   |
| Unknown              | 1        | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5        | 5.81%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 3        | 3.49%   |
| Element ELEFW246 ELE1366 1920x1080 520x290mm 23.4-inch                | 3        | 3.49%   |
| VIZ LCD Monitor M551d-A2R                                             | 2        | 2.33%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch         | 2        | 2.33%   |
| Sony TV SNY4502 1920x1080                                             | 2        | 2.33%   |
| Sony TV *00 SNY4B04 3840x2160                                         | 2        | 2.33%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch     | 2        | 2.33%   |
| Hewlett-Packard L2105tm HWP2863 1920x1080 477x268mm 21.5-inch         | 2        | 2.33%   |
| Goldstar LG ULTRAGEAR GSM5B70 1920x1080 600x340mm 27.2-inch           | 2        | 2.33%   |
| Gateway LCD Monitor FHX2300                                           | 2        | 2.33%   |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch                 | 2        | 2.33%   |
| Acer LCD Monitor G236HL 5760x1080                                     | 2        | 2.33%   |
| Vizio M422i-B1 VIZ1006 1920x1080 930x523mm 42.0-inch                  | 1        | 1.16%   |
| Vizio M322i-B1 VIZ1005 1920x1080 698x392mm 31.5-inch                  | 1        | 1.16%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                    | 1        | 1.16%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch         | 1        | 1.16%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch              | 1        | 1.16%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 1.16%   |
| Unknown LCD Monitor Dell S2719DGF 2560x1440                           | 1        | 1.16%   |
| UGD Artist 156 UGD1501 1920x1080 344x193mm 15.5-inch                  | 1        | 1.16%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                            | 1        | 1.16%   |
| Tech Concepts LCD Monitor 43S423 1920x1080                            | 1        | 1.16%   |
| Seiki SE241TS SEK0CF0 1920x1080 520x290mm 23.4-inch                   | 1        | 1.16%   |
| Sceptre Tech Sceptre X22HG SPT2204 1920x1080 474x296mm 22.0-inch      | 1        | 1.16%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch        | 1        | 1.16%   |
| Sceptre Tech Sceptre F22 SPT08E3 1920x1080 480x260mm 21.5-inch        | 1        | 1.16%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                | 1        | 1.16%   |
| SANSUI ES-27X3 XEC2380 1920x1080 600x340mm 27.2-inch                  | 1        | 1.16%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch     | 1        | 1.16%   |
| Samsung Electronics S27C230 SAM0A87 1920x1080 598x336mm 27.0-inch     | 1        | 1.16%   |
| Samsung Electronics LCD Monitor SAM0F0B 1920x1080 708x398mm 32.0-inch | 1        | 1.16%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 1        | 1.16%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch    | 1        | 1.16%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 1        | 1.16%   |
| MTK Microtek 815C MTK1021 1280x1024 359x287mm 18.1-inch               | 1        | 1.16%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 1        | 1.16%   |
| Hewlett-Packard P17A HWP3142 1280x1024 338x270mm 17.0-inch            | 1        | 1.16%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 1        | 1.16%   |
| Hewlett-Packard 2511 HWP293E 1920x1080 553x311mm 25.0-inch            | 1        | 1.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 38       | 51.35%  |
| 3840x2160 (4K)     | 11       | 14.86%  |
| 2560x1440 (QHD)    | 5        | 6.76%   |
| 1280x1024 (SXGA)   | 3        | 4.05%   |
| 5760x1080          | 2        | 2.7%    |
| 2560x1080          | 2        | 2.7%    |
| 1600x900 (HD+)     | 2        | 2.7%    |
| 1440x900 (WXGA+)   | 2        | 2.7%    |
| 1366x768 (WXGA)    | 2        | 2.7%    |
| Unknown            | 2        | 2.7%    |
| 3840x1080          | 1        | 1.35%   |
| 3440x1440          | 1        | 1.35%   |
| 2288x1287          | 1        | 1.35%   |
| 1680x1050 (WSXGA+) | 1        | 1.35%   |
| 1280x720 (HD)      | 1        | 1.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 13       | 17.11%  |
| 23      | 9        | 11.84%  |
| 72      | 8        | 10.53%  |
| 31      | 8        | 10.53%  |
| 27      | 7        | 9.21%   |
| Unknown | 5        | 6.58%   |
| 19      | 4        | 5.26%   |
| 20      | 3        | 3.95%   |
| 34      | 2        | 2.63%   |
| 32      | 2        | 2.63%   |
| 24      | 2        | 2.63%   |
| 18      | 2        | 2.63%   |
| 17      | 2        | 2.63%   |
| 142     | 1        | 1.32%   |
| 84      | 1        | 1.32%   |
| 64      | 1        | 1.32%   |
| 52      | 1        | 1.32%   |
| 28      | 1        | 1.32%   |
| 26      | 1        | 1.32%   |
| 25      | 1        | 1.32%   |
| 22      | 1        | 1.32%   |
| 15      | 1        | 1.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 20       | 27.03%  |
| 501-600        | 18       | 24.32%  |
| 601-700        | 11       | 14.86%  |
| 1501-2000      | 8        | 10.81%  |
| Unknown        | 5        | 6.76%   |
| 701-800        | 4        | 5.41%   |
| 301-350        | 3        | 4.05%   |
| 351-400        | 2        | 2.7%    |
| 1001-1500      | 2        | 2.7%    |
| More than 2000 | 1        | 1.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 48       | 73.85%  |
| Unknown | 5        | 7.69%   |
| 5/4     | 4        | 6.15%   |
| 16/10   | 4        | 6.15%   |
| 21/9    | 3        | 4.62%   |
| 1.00    | 1        | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 30.14%  |
| 351-500        | 12       | 16.44%  |
| More than 1000 | 10       | 13.7%   |
| 151-200        | 10       | 13.7%   |
| 301-350        | 7        | 9.59%   |
| Unknown        | 5        | 6.85%   |
| 251-300        | 3        | 4.11%   |
| 141-150        | 3        | 4.11%   |
| 101-110        | 1        | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 36       | 51.43%  |
| 101-120 | 15       | 21.43%  |
| 1-50    | 10       | 14.29%  |
| Unknown | 5        | 7.14%   |
| 121-160 | 4        | 5.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 56       | 78.87%  |
| 2     | 11       | 15.49%  |
| 3     | 2        | 2.82%   |
| 0     | 2        | 2.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 52       | 48.6%   |
| Intel                 | 35       | 32.71%  |
| NetGear               | 4        | 3.74%   |
| Ralink Technology     | 3        | 2.8%    |
| Qualcomm Atheros      | 3        | 2.8%    |
| Ralink                | 2        | 1.87%   |
| Nvidia                | 2        | 1.87%   |
| TP-Link               | 1        | 0.93%   |
| Samsung Electronics   | 1        | 0.93%   |
| Microsoft             | 1        | 0.93%   |
| MediaTek              | 1        | 0.93%   |
| Gemtek                | 1        | 0.93%   |
| Aquantia              | 1        | 0.93%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 34       | 26.56%  |
| Intel I211 Gigabit Network Connection                                  | 6        | 4.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 5        | 3.91%   |
| Intel Wi-Fi 6 AX200                                                    | 4        | 3.13%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4        | 3.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 3.13%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 3        | 2.34%   |
| Realtek 802.11ac NIC                                                   | 3        | 2.34%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3        | 2.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 1.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 2        | 1.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 2        | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 1.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 1.56%   |
| Intel Ethernet Controller I225-V                                       | 2        | 1.56%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 1.56%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                             | 1        | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1        | 0.78%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 0.78%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1        | 0.78%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1        | 0.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1        | 0.78%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                 | 1        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1        | 0.78%   |
| Realtek RTL8187 Wireless Adapter                                       | 1        | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 0.78%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1        | 0.78%   |
| Ralink RT2870 Wireless Adapter                                         | 1        | 0.78%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                      | 1        | 0.78%   |
| Ralink MT7601U Wireless Adapter                                        | 1        | 0.78%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                 | 1        | 0.78%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 1        | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.78%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 0.78%   |
| Nvidia CK804 Ethernet Controller                                       | 1        | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 40%     |
| Intel                 | 16       | 32%     |
| Ralink Technology     | 3        | 6%      |
| NetGear               | 3        | 6%      |
| Ralink                | 2        | 4%      |
| Qualcomm Atheros      | 2        | 4%      |
| TP-Link               | 1        | 2%      |
| Microsoft             | 1        | 2%      |
| MediaTek              | 1        | 2%      |
| Gemtek                | 1        | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                            | 5        | 8.93%   |
| Intel Wi-Fi 6 AX200                                           | 4        | 7.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 4        | 7.14%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 3        | 5.36%   |
| Realtek 802.11ac NIC                                          | 3        | 5.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 2        | 3.57%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 2        | 3.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 2        | 3.57%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                    | 1        | 1.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1        | 1.79%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1        | 1.79%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 1        | 1.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1        | 1.79%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1        | 1.79%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                        | 1        | 1.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1        | 1.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1        | 1.79%   |
| Realtek RTL8187 Wireless Adapter                              | 1        | 1.79%   |
| Ralink RT2870 Wireless Adapter                                | 1        | 1.79%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter             | 1        | 1.79%   |
| Ralink MT7601U Wireless Adapter                               | 1        | 1.79%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter        | 1        | 1.79%   |
| Ralink RT2561/RT61 802.11g PCI                                | 1        | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1        | 1.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1        | 1.79%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]               | 1        | 1.79%   |
| NetGear MA111(v2) 802.11b Wireless [SIS SIS 162]              | 1        | 1.79%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]   | 1        | 1.79%   |
| Microsoft XBOX ACC                                            | 1        | 1.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1        | 1.79%   |
| Intel Wireless 8265 / 8275                                    | 1        | 1.79%   |
| Intel Wireless 7260                                           | 1        | 1.79%   |
| Intel Wireless 3165                                           | 1        | 1.79%   |
| Intel Wireless 3160                                           | 1        | 1.79%   |
| Intel Wi-Fi 6 AX201 160MHz                                    | 1        | 1.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1        | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1        | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1        | 1.79%   |
| Gemtek WUBR-177G [Ralink RT2571W]                             | 1        | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 40       | 55.56%  |
| Intel                 | 26       | 36.11%  |
| Nvidia                | 2        | 2.78%   |
| Samsung Electronics   | 1        | 1.39%   |
| Qualcomm Atheros      | 1        | 1.39%   |
| NetGear               | 1        | 1.39%   |
| Aquantia              | 1        | 1.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 34       | 47.22%  |
| Intel I211 Gigabit Network Connection                                          | 6        | 8.33%   |
| Intel Ethernet Connection I217-LM                                              | 4        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4        | 5.56%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3        | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2        | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 2.78%   |
| Intel Ethernet Controller I225-V                                               | 2        | 2.78%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2        | 2.78%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1        | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 1.39%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 1.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1        | 1.39%   |
| Nvidia MCP61 Ethernet                                                          | 1        | 1.39%   |
| Nvidia CK804 Ethernet Controller                                               | 1        | 1.39%   |
| NetGear LB1120-100NAS                                                          | 1        | 1.39%   |
| Intel Ethernet Connection (7) I219-V                                           | 1        | 1.39%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1        | 1.39%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.39%   |
| Intel 82579V Gigabit Network Connection                                        | 1        | 1.39%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1        | 1.39%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1        | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 67       | 61.47%  |
| WiFi     | 42       | 38.53%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 50       | 65.79%  |
| WiFi     | 26       | 34.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 42       | 60%     |
| 2     | 25       | 35.71%  |
| 3     | 2        | 2.86%   |
| 0     | 1        | 1.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 59       | 85.51%  |
| Yes  | 10       | 14.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 42.86%  |
| Cambridge Silicon Radio         | 9        | 25.71%  |
| Realtek Semiconductor           | 4        | 11.43%  |
| Broadcom                        | 2        | 5.71%   |
| Qualcomm Atheros Communications | 1        | 2.86%   |
| Lite-On Technology              | 1        | 2.86%   |
| IMC Networks                    | 1        | 2.86%   |
| Dynex                           | 1        | 2.86%   |
| Belkin Components               | 1        | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 9        | 25.71%  |
| Intel Wireless-AC 3168 Bluetooth                         | 4        | 11.43%  |
| Intel AX200 Bluetooth                                    | 4        | 11.43%  |
| Realtek Bluetooth Radio                                  | 2        | 5.71%   |
| Intel Bluetooth wireless interface                       | 2        | 5.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 2        | 5.71%   |
| Intel AX201 Bluetooth                                    | 2        | 5.71%   |
| Broadcom Bluetooth Device                                | 2        | 5.71%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1        | 2.86%   |
| Realtek Bluetooth 5.3 Radio                              | 1        | 2.86%   |
| Qualcomm Atheros  Bluetooth Device                       | 1        | 2.86%   |
| Lite-On Bluetooth Device                                 | 1        | 2.86%   |
| Intel Bluetooth Device                                   | 1        | 2.86%   |
| IMC Networks Wireless_Device                             | 1        | 2.86%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 2.86%   |
| Belkin Components Bluetooth Mini Dongle                  | 1        | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 43       | 41.35%  |
| AMD                                             | 27       | 25.96%  |
| Nvidia                                          | 20       | 19.23%  |
| Logitech                                        | 7        | 6.73%   |
| C-Media Electronics                             | 2        | 1.92%   |
| NZXT                                            | 1        | 0.96%   |
| Nintendo                                        | 1        | 0.96%   |
| Micro Star International                        | 1        | 0.96%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.96%   |
| Kingston Technology                             | 1        | 0.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 7        | 5.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 3.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 3.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 3.94%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 3.94%   |
| AMD FCH Azalia Controller                                                  | 5        | 3.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 3.15%   |
| Logitech EasyCall Speakerphone                                             | 4        | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 3.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 3.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 3.15%   |
| Intel Sunrise Point-LP HD Audio                                            | 3        | 2.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 2.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3        | 2.36%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 2.36%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 2.36%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.57%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.57%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 1.57%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 1.57%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 1.57%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2        | 1.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.57%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 1.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.57%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.57%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.57%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 1.57%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.57%   |
| NZXT USB MIC                                                               | 1        | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.79%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.79%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.79%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 0.79%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 7        | 28%     |
| Samsung Electronics | 3        | 12%     |
| G.Skill             | 3        | 12%     |
| Team                | 2        | 8%      |
| SK hynix            | 2        | 8%      |
| Crucial             | 2        | 8%      |
| Corsair             | 2        | 8%      |
| Sesame              | 1        | 4%      |
| PNY                 | 1        | 4%      |
| Kingston            | 1        | 4%      |
| Avant               | 1        | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                      | 3        | 10.71%  |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 3.57%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                    | 1        | 3.57%   |
| Unknown RAM Module 1GB DIMM                               | 1        | 3.57%   |
| Unknown RAM CL18-22-22 D4-3600 16384MB DIMM DDR4 3600MT/s | 1        | 3.57%   |
| Unknown RAM CL18-20-20 D4-3600 8192MB DIMM DDR4 3600MT/s  | 1        | 3.57%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s       | 1        | 3.57%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s        | 1        | 3.57%   |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                | 1        | 3.57%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 3.57%   |
| Sesame RAM S939A2UGS-ITR 8GB DIMM DDR3 1600MT/s           | 1        | 3.57%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s       | 1        | 3.57%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 3.57%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 3.57%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s       | 1        | 3.57%   |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s       | 1        | 3.57%   |
| PNY RAM 4GBH1X04E9992 4096MB DIMM DDR3 1600MT/s           | 1        | 3.57%   |
| Kingston RAM X2YH1K-MIE-NX 16GB DIMM DDR4 3200MT/s        | 1        | 3.57%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s        | 1        | 3.57%   |
| G.Skill RAM F3-2400C11-8G 8192MB DIMM DDR3 2133MT/s       | 1        | 3.57%   |
| G.Skill RAM F3-10666CL9-8GBSQ 8GB DIMM DDR3 1333MT/s      | 1        | 3.57%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s     | 1        | 3.57%   |
| Crucial RAM BL16G26C16U4W.16FD 16GB DIMM DDR4 2667MT/s    | 1        | 3.57%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1        | 3.57%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s     | 1        | 3.57%   |
| Avant RAM W641GU42J7240NC 8GB DIMM DDR4 2400MT/s          | 1        | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 10       | 40%     |
| DDR3    | 10       | 40%     |
| SDRAM   | 3        | 12%     |
| Unknown | 2        | 8%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 25       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 10       | 38.46%  |
| 4096  | 6        | 23.08%  |
| 16384 | 5        | 19.23%  |
| 2048  | 3        | 11.54%  |
| 32768 | 1        | 3.85%   |
| 1024  | 1        | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 5        | 19.23%  |
| 3200    | 4        | 15.38%  |
| Unknown | 4        | 15.38%  |
| 3600    | 3        | 11.54%  |
| 1333    | 3        | 11.54%  |
| 3733    | 1        | 3.85%   |
| 2667    | 1        | 3.85%   |
| 2400    | 1        | 3.85%   |
| 2133    | 1        | 3.85%   |
| 1867    | 1        | 3.85%   |
| 1866    | 1        | 3.85%   |
| 667     | 1        | 3.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 66.67%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP OfficeJet Pro 6960  | 1        | 33.33%  |
| HP DeskJet 2700 series | 1        | 33.33%  |
| Brother MFC-L2685DW    | 1        | 33.33%  |

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
| Logitech         | 6        | 35.29%  |
| Microdia         | 5        | 29.41%  |
| Razer USA        | 2        | 11.76%  |
| Trust            | 1        | 5.88%   |
| Microsoft        | 1        | 5.88%   |
| Jieli Technology | 1        | 5.88%   |
| Cubeternet       | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Microdia Camera                 | 4        | 23.53%  |
| Logitech HD Pro Webcam C920     | 2        | 11.76%  |
| Trust HDH Webcam USB            | 1        | 5.88%   |
| Razer USA Razer Kiyo Pro        | 1        | 5.88%   |
| Razer USA Gaming Webcam [Kiyo]  | 1        | 5.88%   |
| Microsoft LifeCam Cinema        | 1        | 5.88%   |
| Microdia USB 2.0 Camera         | 1        | 5.88%   |
| Logitech Webcam Pro 9000        | 1        | 5.88%   |
| Logitech Webcam C310            | 1        | 5.88%   |
| Logitech Webcam C270            | 1        | 5.88%   |
| Logitech CrystalCam             | 1        | 5.88%   |
| Jieli USB PHY 2.0               | 1        | 5.88%   |
| Cubeternet GL-UPC822 UVC WebCam | 1        | 5.88%   |

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
| 0     | 56       | 72.73%  |
| 1     | 16       | 20.78%  |
| 2     | 5        | 6.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 59.09%  |
| Graphics card            | 6        | 27.27%  |
| Net/ethernet             | 1        | 4.55%   |
| Multimedia controller    | 1        | 4.55%   |
| Communication controller | 1        | 4.55%   |

