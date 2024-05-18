Alpine - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Alpine.

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

Total: 97

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z270X-Gaming 8              | [00e056103f](https://linux-hardware.org/?probe=00e056103f) | Apr 22, 2024 |
| ASRock        | B85M-ITX                    | [c868a15a8f](https://linux-hardware.org/?probe=c868a15a8f) | Apr 20, 2024 |
| Intel         | H81                         | [8b51b58c02](https://linux-hardware.org/?probe=8b51b58c02) | Apr 11, 2024 |
| HP            | 18E7                        | [06187ec68b](https://linux-hardware.org/?probe=06187ec68b) | Apr 09, 2024 |
| Dell          | 0CU395                      | [0ba3773be8](https://linux-hardware.org/?probe=0ba3773be8) | Apr 03, 2024 |
| Intel         | H81                         | [c62889d4a5](https://linux-hardware.org/?probe=c62889d4a5) | Apr 02, 2024 |
| Inventec      | DQ Class A02                | [6539e1cbe7](https://linux-hardware.org/?probe=6539e1cbe7) | Mar 22, 2024 |
| MACHINIST     | X99 PR9                     | [481821b9ad](https://linux-hardware.org/?probe=481821b9ad) | Mar 12, 2024 |
| Intel         | D102GGC2 AAD42789-204       | [0da90b1518](https://linux-hardware.org/?probe=0da90b1518) | Mar 03, 2024 |
| Acer          | TDPS05                      | [9156de5a01](https://linux-hardware.org/?probe=9156de5a01) | Feb 15, 2024 |
| AMI           | Intel                       | [15abbc4eb4](https://linux-hardware.org/?probe=15abbc4eb4) | Feb 11, 2024 |
| Unknown       | Unknown                     | [413fbae0c9](https://linux-hardware.org/?probe=413fbae0c9) | Jan 17, 2024 |
| Unknown       | Unknown                     | [69d393fc55](https://linux-hardware.org/?probe=69d393fc55) | Jan 17, 2024 |
| HP            | 3397                        | [c33a1d3b01](https://linux-hardware.org/?probe=c33a1d3b01) | Jan 09, 2024 |
| ASUSTek       | Z87-DELUXE                  | [018238aa79](https://linux-hardware.org/?probe=018238aa79) | Jan 01, 2024 |
| Acer          | TDPS05                      | [ce9b5d0c48](https://linux-hardware.org/?probe=ce9b5d0c48) | Dec 23, 2023 |
| Acer          | TDPS05                      | [d0260b1327](https://linux-hardware.org/?probe=d0260b1327) | Dec 23, 2023 |
| ZOTAC         | Unknown                     | [a91d567af3](https://linux-hardware.org/?probe=a91d567af3) | Dec 14, 2023 |
| Compaq        | 0684h                       | [54c2d84103](https://linux-hardware.org/?probe=54c2d84103) | Dec 02, 2023 |
| Compaq        | 0684h                       | [b2d96b48dc](https://linux-hardware.org/?probe=b2d96b48dc) | Dec 02, 2023 |
| ECS           | M789CG                      | [7c2e2de188](https://linux-hardware.org/?probe=7c2e2de188) | Dec 01, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1909f3fbff](https://linux-hardware.org/?probe=1909f3fbff) | Nov 15, 2023 |
| Unknown       | Unknown                     | [80774e2d18](https://linux-hardware.org/?probe=80774e2d18) | Nov 14, 2023 |
| ECS           | M789CG                      | [49edfe005c](https://linux-hardware.org/?probe=49edfe005c) | Nov 07, 2023 |
| Gigabyte      | 945GCM-S2C                  | [c714bf35c2](https://linux-hardware.org/?probe=c714bf35c2) | Nov 06, 2023 |
| ECS           | M789CG                      | [87fe73ee84](https://linux-hardware.org/?probe=87fe73ee84) | Nov 02, 2023 |
| ECS           | M789CG                      | [b767549953](https://linux-hardware.org/?probe=b767549953) | Oct 15, 2023 |
| ASRock        | Q1900B-ITX                  | [8625166ef3](https://linux-hardware.org/?probe=8625166ef3) | Oct 14, 2023 |
| ECS           | M789CG                      | [6f446a6f77](https://linux-hardware.org/?probe=6f446a6f77) | Oct 14, 2023 |
| ECS           | M789CG                      | [0a0df79fcd](https://linux-hardware.org/?probe=0a0df79fcd) | Oct 14, 2023 |
| Inventec      | D CLASS A02                 | [9559c016fb](https://linux-hardware.org/?probe=9559c016fb) | Oct 13, 2023 |
| ASRock        | Z790M-ITX WiFi              | [560aec8a01](https://linux-hardware.org/?probe=560aec8a01) | Oct 06, 2023 |
| ASRock        | H55M-LE                     | [6b7e52fd8c](https://linux-hardware.org/?probe=6b7e52fd8c) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | [ceefe742e2](https://linux-hardware.org/?probe=ceefe742e2) | Sep 20, 2023 |
| Dell          | 0RY007                      | [3bcbd1f6c3](https://linux-hardware.org/?probe=3bcbd1f6c3) | Sep 19, 2023 |
| Dell          | 096JG8 A01                  | [00e5bebc6a](https://linux-hardware.org/?probe=00e5bebc6a) | Sep 06, 2023 |
| ASRock        | 970 Extreme4                | [de055c3a95](https://linux-hardware.org/?probe=de055c3a95) | Jul 17, 2023 |
| ASUSTek       | Z170-E                      | [8be9720ca6](https://linux-hardware.org/?probe=8be9720ca6) | Jun 29, 2023 |
| ASUSTek       | PRIME B360M-C               | [4dca77df51](https://linux-hardware.org/?probe=4dca77df51) | Jun 21, 2023 |
| HP            | 83E2                        | [0db8dcbc23](https://linux-hardware.org/?probe=0db8dcbc23) | May 28, 2023 |
| MSI           | MAG B460M MORTAR            | [da74cacf64](https://linux-hardware.org/?probe=da74cacf64) | May 18, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [429dc207a6](https://linux-hardware.org/?probe=429dc207a6) | May 15, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [f887e6f037](https://linux-hardware.org/?probe=f887e6f037) | May 15, 2023 |
| UGREEN        | DX4600                      | [cbe70de89c](https://linux-hardware.org/?probe=cbe70de89c) | Apr 19, 2023 |
| ASUSTek       | PRIME B360M-C               | [8cf7b9cc76](https://linux-hardware.org/?probe=8cf7b9cc76) | Mar 23, 2023 |
| Intel         | D525MW AAE93082-401         | [590309a32b](https://linux-hardware.org/?probe=590309a32b) | Mar 18, 2023 |
| Intel         | D525MW AAE93082-401         | [bc847b4586](https://linux-hardware.org/?probe=bc847b4586) | Mar 09, 2023 |
| Intel         | D525MW AAE93082-401         | [d02959f9ad](https://linux-hardware.org/?probe=d02959f9ad) | Mar 02, 2023 |
| ASRock        | X470 Master SLI/ac          | [d8f1121a19](https://linux-hardware.org/?probe=d8f1121a19) | Jan 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [68a73ee517](https://linux-hardware.org/?probe=68a73ee517) | Jan 19, 2023 |
| ASRock        | X470 Master SLI/ac          | [6b6a4929de](https://linux-hardware.org/?probe=6b6a4929de) | Jan 16, 2023 |
| ASRock        | X470 Master SLI/ac          | [8775308115](https://linux-hardware.org/?probe=8775308115) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | [473b4d0e6e](https://linux-hardware.org/?probe=473b4d0e6e) | Jan 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [747c3d8c1f](https://linux-hardware.org/?probe=747c3d8c1f) | Jan 11, 2023 |
| Gigabyte      | X570S AERO G                | [053b8697ce](https://linux-hardware.org/?probe=053b8697ce) | Jan 06, 2023 |
| Dell          | 03V7GF A01                  | [3847c61b81](https://linux-hardware.org/?probe=3847c61b81) | Dec 17, 2022 |
| Dell          | 03V7GF A01                  | [e491b54a3c](https://linux-hardware.org/?probe=e491b54a3c) | Dec 17, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [bbf4464c41](https://linux-hardware.org/?probe=bbf4464c41) | Nov 27, 2022 |
| Fujitsu       | FujitsuTP7000 -1            | [89198d262f](https://linux-hardware.org/?probe=89198d262f) | Nov 17, 2022 |
| Lenovo        | 31900058 STD                | [d7cc344b2f](https://linux-hardware.org/?probe=d7cc344b2f) | Oct 31, 2022 |
| Lenovo        | 31900058 STD                | [9f7158b883](https://linux-hardware.org/?probe=9f7158b883) | Oct 16, 2022 |
| HP            | 1493                        | [60ebd1d8dd](https://linux-hardware.org/?probe=60ebd1d8dd) | Sep 29, 2022 |
| Gateway       | SX2185                      | [8372be8fe3](https://linux-hardware.org/?probe=8372be8fe3) | Sep 29, 2022 |
| ASRock        | H81M                        | [d59c4705a2](https://linux-hardware.org/?probe=d59c4705a2) | Aug 17, 2022 |
| Intel         | DH61BF AAG81311-101         | [5a3ed0cf62](https://linux-hardware.org/?probe=5a3ed0cf62) | Jul 30, 2022 |
| Intel         | DH61BF AAG81311-101         | [719bbf817c](https://linux-hardware.org/?probe=719bbf817c) | Jul 30, 2022 |
| Intel         | DQ67SW AAG12527-310         | [9a4907d88c](https://linux-hardware.org/?probe=9a4907d88c) | Jul 17, 2022 |
| Unknown       | Unknown                     | [d857b93614](https://linux-hardware.org/?probe=d857b93614) | Jul 13, 2022 |
| Lenovo        | 31900058 STD                | [2f6356a177](https://linux-hardware.org/?probe=2f6356a177) | Jun 17, 2022 |
| Lenovo        | 31900058 STD                | [582fd88dbe](https://linux-hardware.org/?probe=582fd88dbe) | Jun 14, 2022 |
| MSI           | Z170A GAMING PRO            | [73b3e29101](https://linux-hardware.org/?probe=73b3e29101) | Jun 14, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [e692b2a091](https://linux-hardware.org/?probe=e692b2a091) | May 26, 2022 |
| ASUSTek       | H97-PLUS                    | [cab2025064](https://linux-hardware.org/?probe=cab2025064) | May 24, 2022 |
| MSI           | J1900I                      | [86f37a71f5](https://linux-hardware.org/?probe=86f37a71f5) | May 15, 2022 |
| MSI           | J1900I                      | [5a48d83596](https://linux-hardware.org/?probe=5a48d83596) | May 15, 2022 |
| ASUSTek       | Z97-K                       | [53cba6b4f8](https://linux-hardware.org/?probe=53cba6b4f8) | Apr 14, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [908edb3724](https://linux-hardware.org/?probe=908edb3724) | Jan 27, 2022 |
| Dell          | 02YRK5 A02                  | [58c2ed388b](https://linux-hardware.org/?probe=58c2ed388b) | Dec 02, 2021 |
| HP            | 21B4 A01                    | [98accc83e4](https://linux-hardware.org/?probe=98accc83e4) | Nov 11, 2021 |
| Dell          | 0T10XW A00                  | [585636f7fe](https://linux-hardware.org/?probe=585636f7fe) | Sep 08, 2021 |
| Shuttle       | FS81                        | [9a98a31681](https://linux-hardware.org/?probe=9a98a31681) | Sep 06, 2021 |
| Dell          | 0VRWRC A00                  | [37a6ad6e02](https://linux-hardware.org/?probe=37a6ad6e02) | Apr 09, 2021 |
| ASUSTek       | P8H67-V                     | [89edd8b343](https://linux-hardware.org/?probe=89edd8b343) | Mar 17, 2021 |
| HP            | ProLiant MicroServer Gen... | [af637820c2](https://linux-hardware.org/?probe=af637820c2) | Feb 12, 2021 |
| VIA Techno... | KM266APro-835               | [1334ad3f74](https://linux-hardware.org/?probe=1334ad3f74) | Dec 22, 2020 |
| Fujitsu       | D2779 S26361-D2779-A1       | [07795a357a](https://linux-hardware.org/?probe=07795a357a) | Oct 09, 2020 |
| Dell          | 0PU052                      | [9a31999f07](https://linux-hardware.org/?probe=9a31999f07) | Aug 31, 2020 |
| ASUSTek       | TS10                        | [71d7f6e110](https://linux-hardware.org/?probe=71d7f6e110) | Aug 20, 2020 |
| VIA Techno... | KM266APro-835               | [25ec3d44ff](https://linux-hardware.org/?probe=25ec3d44ff) | Aug 16, 2020 |
| Gigabyte      | Z490I AORUS ULTRA           | [58dce1215c](https://linux-hardware.org/?probe=58dce1215c) | Aug 13, 2020 |
| ASUSTek       | PRIME H370M-PLUS            | [0c50242cc5](https://linux-hardware.org/?probe=0c50242cc5) | Aug 09, 2020 |
| ASRock        | J3455M                      | [05f9d5c3b4](https://linux-hardware.org/?probe=05f9d5c3b4) | Aug 06, 2020 |
| eMachines     | EL1352G                     | [4513d2931f](https://linux-hardware.org/?probe=4513d2931f) | Jul 03, 2020 |
| eMachines     | EL1352G                     | [4b26717c89](https://linux-hardware.org/?probe=4b26717c89) | Jul 03, 2020 |
| ASRock        | J3455M                      | [3719f96b60](https://linux-hardware.org/?probe=3719f96b60) | Jul 03, 2020 |
| Unknown       | i855GM/E-ITE8712            | [7b9cbd816b](https://linux-hardware.org/?probe=7b9cbd816b) | Dec 27, 2019 |
| ASRock        | D1800B-ITX                  | [f962d4bbf9](https://linux-hardware.org/?probe=f962d4bbf9) | Dec 22, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Alpine 3.12.0               | 5        | 7.25%   |
| Alpine 3.19.1               | 4        | 5.8%    |
| Alpine 3.18.4               | 4        | 5.8%    |
| Alpine 3.18.0               | 4        | 5.8%    |
| Alpine 3.17_alpha20220809   | 4        | 5.8%    |
| Alpine 3.19_alpha20230901   | 3        | 4.35%   |
| Alpine 3.19.0               | 3        | 4.35%   |
| Alpine 3.16.0               | 3        | 4.35%   |
| Alpine 3.15.4               | 3        | 4.35%   |
| Alpine 3.13.0_alpha20200626 | 3        | 4.35%   |
| Alpine 3.18.6               | 2        | 2.9%    |
| Alpine 3.18.5               | 2        | 2.9%    |
| Alpine 3.18.3               | 2        | 2.9%    |
| Alpine 3.18.2               | 2        | 2.9%    |
| Alpine 3.17.2               | 2        | 2.9%    |
| Alpine 3.17.1               | 2        | 2.9%    |
| Alpine 3.16.1               | 2        | 2.9%    |
| Alpine 3.11.2               | 2        | 2.9%    |
| Alpine 3.8.4                | 1        | 1.45%   |
| Alpine 3.20.0_alpha20240329 | 1        | 1.45%   |
| Alpine 3.20.0_alpha20231219 | 1        | 1.45%   |
| Alpine 3.17.7               | 1        | 1.45%   |
| Alpine 3.17.4               | 1        | 1.45%   |
| Alpine 3.17.0               | 1        | 1.45%   |
| Alpine 3.16.2               | 1        | 1.45%   |
| Alpine 3.16.0_alpha20220328 | 1        | 1.45%   |
| Alpine 3.15.6               | 1        | 1.45%   |
| Alpine 3.15.0               | 1        | 1.45%   |
| Alpine 3.14.3               | 1        | 1.45%   |
| Alpine 3.14.2               | 1        | 1.45%   |
| Alpine 3.13.6               | 1        | 1.45%   |
| Alpine 3.13.2               | 1        | 1.45%   |
| Alpine 3.13.1               | 1        | 1.45%   |
| Alpine 3.13.0_alpha20201218 | 1        | 1.45%   |
| Alpine 3.12.3               | 1        | 1.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Alpine | 64       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Desktops | Percent |
|----------------|----------|---------|
| 5.4.43-1-lts   | 5        | 7.35%   |
| 6.1.57-0-lts   | 3        | 4.41%   |
| 6.6.23-0-lts   | 2        | 2.94%   |
| 6.5.11-4-pve   | 2        | 2.94%   |
| 6.1.51-0-lts   | 2        | 2.94%   |
| 5.15.60-0-lts  | 2        | 2.94%   |
| 6.6.8-0-lts    | 1        | 1.47%   |
| 6.6.7-0-lts    | 1        | 1.47%   |
| 6.6.6-0-lts    | 1        | 1.47%   |
| 6.6.25-haos    | 1        | 1.47%   |
| 6.6.16-0-lts   | 1        | 1.47%   |
| 6.6.10-0-lts   | 1        | 1.47%   |
| 6.6.1-0-edge   | 1        | 1.47%   |
| 6.3.3-0-edge   | 1        | 1.47%   |
| 6.1.87-0-lts   | 1        | 1.47%   |
| 6.1.77-0-lts   | 1        | 1.47%   |
| 6.1.64-0-lts   | 1        | 1.47%   |
| 6.1.61-0-lts   | 1        | 1.47%   |
| 6.1.60-0-lts   | 1        | 1.47%   |
| 6.1.55-2-lts   | 1        | 1.47%   |
| 6.1.54-0-lts   | 1        | 1.47%   |
| 6.1.36-0-lts   | 1        | 1.47%   |
| 6.1.34-0-lts   | 1        | 1.47%   |
| 6.1.30-0-lts   | 1        | 1.47%   |
| 6.1.28-2-lts   | 1        | 1.47%   |
| 6.0.10-0-edge  | 1        | 1.47%   |
| 5.8.0          | 1        | 1.47%   |
| 5.4.84-0-lts   | 1        | 1.47%   |
| 5.4.6-0-lts    | 1        | 1.47%   |
| 5.4.58-0-lts   | 1        | 1.47%   |
| 5.4.57-0-lts   | 1        | 1.47%   |
| 5.18.0-0-asahi | 1        | 1.47%   |
| 5.17.9-0-edge  | 1        | 1.47%   |
| 5.17.3-0-edge  | 1        | 1.47%   |
| 5.15.98-0-lts  | 1        | 1.47%   |
| 5.15.87-0-lts  | 1        | 1.47%   |
| 5.15.86-0-lts  | 1        | 1.47%   |
| 5.15.83-0-lts  | 1        | 1.47%   |
| 5.15.80        | 1        | 1.47%   |
| 5.15.74-0-lts  | 1        | 1.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.43  | 5        | 7.35%   |
| 6.1.57  | 3        | 4.41%   |
| 6.6.23  | 2        | 2.94%   |
| 6.5.11  | 2        | 2.94%   |
| 6.1.51  | 2        | 2.94%   |
| 5.15.60 | 2        | 2.94%   |
| 6.6.8   | 1        | 1.47%   |
| 6.6.7   | 1        | 1.47%   |
| 6.6.6   | 1        | 1.47%   |
| 6.6.25  | 1        | 1.47%   |
| 6.6.16  | 1        | 1.47%   |
| 6.6.10  | 1        | 1.47%   |
| 6.6.1   | 1        | 1.47%   |
| 6.3.3   | 1        | 1.47%   |
| 6.1.87  | 1        | 1.47%   |
| 6.1.77  | 1        | 1.47%   |
| 6.1.64  | 1        | 1.47%   |
| 6.1.61  | 1        | 1.47%   |
| 6.1.60  | 1        | 1.47%   |
| 6.1.55  | 1        | 1.47%   |
| 6.1.54  | 1        | 1.47%   |
| 6.1.36  | 1        | 1.47%   |
| 6.1.34  | 1        | 1.47%   |
| 6.1.30  | 1        | 1.47%   |
| 6.1.28  | 1        | 1.47%   |
| 6.0.10  | 1        | 1.47%   |
| 5.8.0   | 1        | 1.47%   |
| 5.4.84  | 1        | 1.47%   |
| 5.4.6   | 1        | 1.47%   |
| 5.4.58  | 1        | 1.47%   |
| 5.4.57  | 1        | 1.47%   |
| 5.18.0  | 1        | 1.47%   |
| 5.17.9  | 1        | 1.47%   |
| 5.17.3  | 1        | 1.47%   |
| 5.15.98 | 1        | 1.47%   |
| 5.15.87 | 1        | 1.47%   |
| 5.15.86 | 1        | 1.47%   |
| 5.15.83 | 1        | 1.47%   |
| 5.15.80 | 1        | 1.47%   |
| 5.15.74 | 1        | 1.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 16       | 24.24%  |
| 6.1     | 15       | 22.73%  |
| 6.6     | 9        | 13.64%  |
| 5.4     | 9        | 13.64%  |
| 5.10    | 5        | 7.58%   |
| 6.5     | 2        | 3.03%   |
| 5.17    | 2        | 3.03%   |
| 6.3     | 1        | 1.52%   |
| 6.0     | 1        | 1.52%   |
| 5.8     | 1        | 1.52%   |
| 5.18    | 1        | 1.52%   |
| 4.4     | 1        | 1.52%   |
| 4.20    | 1        | 1.52%   |
| 4.14    | 1        | 1.52%   |
| 3.10    | 1        | 1.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 57       | 89.06%  |
| i686    | 6        | 9.38%   |
| aarch64 | 1        | 1.56%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 51       | 79.69%  |
| XFCE    | 5        | 7.81%   |
| KDE5    | 3        | 4.69%   |
| GNOME   | 3        | 4.69%   |
| sway    | 1        | 1.56%   |
| i3      | 1        | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 43       | 65.15%  |
| X11     | 17       | 25.76%  |
| Wayland | 6        | 9.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 57       | 89.06%  |
| LightDM | 5        | 7.81%   |
| SDDM    | 2        | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 39       | 60.94%  |
| Unknown | 21       | 32.81%  |
| en_US   | 2        | 3.13%   |
| pt_BR   | 1        | 1.56%   |
| en_GB   | 1        | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 40       | 62.5%   |
| EFI  | 24       | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 52       | 80%     |
| Btrfs   | 4        | 6.15%   |
| Unknown | 3        | 4.62%   |
| Tmpfs   | 2        | 3.08%   |
| Overlay | 2        | 3.08%   |
| Zfs     | 1        | 1.54%   |
| Fake    | 1        | 1.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 43       | 66.15%  |
| GPT     | 15       | 23.08%  |
| MBR     | 7        | 10.77%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 84.38%  |
| Yes       | 10       | 15.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 92.19%  |
| Yes       | 5        | 7.81%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASRock              | 9        | 14.06%  |
| Gigabyte Technology | 8        | 12.5%   |
| Dell                | 8        | 12.5%   |
| ASUSTek Computer    | 8        | 12.5%   |
| Hewlett-Packard     | 5        | 7.81%   |
| Intel               | 4        | 6.25%   |
| Unknown             | 3        | 4.69%   |
| MSI                 | 2        | 3.13%   |
| Lenovo              | 2        | 3.13%   |
| Inventec            | 2        | 3.13%   |
| Fujitsu             | 2        | 3.13%   |
| ZOTAC               | 1        | 1.56%   |
| VIA Technologies    | 1        | 1.56%   |
| UGREEN              | 1        | 1.56%   |
| Shuttle             | 1        | 1.56%   |
| MACHINIST           | 1        | 1.56%   |
| Gateway             | 1        | 1.56%   |
| eMachines           | 1        | 1.56%   |
| ECS                 | 1        | 1.56%   |
| Compaq              | 1        | 1.56%   |
| AMI                 | 1        | 1.56%   |
| Acer                | 1        | 1.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 4        | 6.25%   |
| ASUS All Series                    | 3        | 4.69%   |
| Gigabyte Z490I AORUS ULTRA         | 2        | 3.13%   |
| VIA KM266APro-835                  | 1        | 1.56%   |
| UGREEN DX4600                      | 1        | 1.56%   |
| Shuttle DS81D                      | 1        | 1.56%   |
| MSI MS-7C82                        | 1        | 1.56%   |
| MSI MS-7877                        | 1        | 1.56%   |
| MACHINIST X99 PR9                  | 1        | 1.56%   |
| Lenovo ThinkCentre M93p 10AB0016US | 1        | 1.56%   |
| Lenovo H535 10117                  | 1        | 1.56%   |
| Inventec DQ Class                  | 1        | 1.56%   |
| Inventec D CLASS                   | 1        | 1.56%   |
| Intel H81                          | 1        | 1.56%   |
| Intel DQ67SW                       | 1        | 1.56%   |
| Intel DH61BF AAG81311-101          | 1        | 1.56%   |
| Intel D525MW AAE93082-401          | 1        | 1.56%   |
| HP ProLiant MicroServer Gen8       | 1        | 1.56%   |
| HP ProDesk 600 G1 TWR              | 1        | 1.56%   |
| HP EliteDesk 800 G4 DM 35W         | 1        | 1.56%   |
| HP Compaq Elite 8300 SFF           | 1        | 1.56%   |
| HP Compaq 4000 Pro SFF PC          | 1        | 1.56%   |
| Gigabyte Z270X-Gaming 8            | 1        | 1.56%   |
| Gigabyte Z170X-UD5                 | 1        | 1.56%   |
| Gigabyte X570S AERO G              | 1        | 1.56%   |
| Gigabyte X570 I AORUS PRO WIFI     | 1        | 1.56%   |
| Gigabyte B550 AORUS ELITE V2       | 1        | 1.56%   |
| Gigabyte 945GCM-S2C                | 1        | 1.56%   |
| Gateway SX2185                     | 1        | 1.56%   |
| Fujitsu PRIMERGY TX100 S2          | 1        | 1.56%   |
| Fujitsu FujitsuTP7000              | 1        | 1.56%   |
| eMachines EL1352G                  | 1        | 1.56%   |
| ECS M789CG                         | 1        | 1.56%   |
| Dell OptiPlex 755                  | 1        | 1.56%   |
| Dell OptiPlex 7040                 | 1        | 1.56%   |
| Dell OptiPlex 5000                 | 1        | 1.56%   |
| Dell OptiPlex 320                  | 1        | 1.56%   |
| Dell OptiPlex 3020M                | 1        | 1.56%   |
| Dell OptiPlex 3010                 | 1        | 1.56%   |
| Dell Inspiron 530s                 | 1        | 1.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 6        | 9.38%   |
| Unknown               | 4        | 6.25%   |
| ASUS All              | 3        | 4.69%   |
| HP Compaq             | 2        | 3.13%   |
| Gigabyte Z490I        | 2        | 3.13%   |
| Dell Inspiron         | 2        | 3.13%   |
| ASUS PRIME            | 2        | 3.13%   |
| VIA KM266APro-835     | 1        | 1.56%   |
| UGREEN DX4600         | 1        | 1.56%   |
| Shuttle DS81D         | 1        | 1.56%   |
| MSI MS-7C82           | 1        | 1.56%   |
| MSI MS-7877           | 1        | 1.56%   |
| MACHINIST X99         | 1        | 1.56%   |
| Lenovo ThinkCentre    | 1        | 1.56%   |
| Lenovo H535           | 1        | 1.56%   |
| Inventec DQ           | 1        | 1.56%   |
| Inventec D            | 1        | 1.56%   |
| Intel H81             | 1        | 1.56%   |
| Intel DQ67SW          | 1        | 1.56%   |
| Intel DH61BF          | 1        | 1.56%   |
| Intel D525MW          | 1        | 1.56%   |
| HP ProLiant           | 1        | 1.56%   |
| HP ProDesk            | 1        | 1.56%   |
| HP EliteDesk          | 1        | 1.56%   |
| Gigabyte Z270X-Gaming | 1        | 1.56%   |
| Gigabyte Z170X-UD5    | 1        | 1.56%   |
| Gigabyte X570S        | 1        | 1.56%   |
| Gigabyte X570         | 1        | 1.56%   |
| Gigabyte B550         | 1        | 1.56%   |
| Gigabyte 945GCM-S2C   | 1        | 1.56%   |
| Gateway SX2185        | 1        | 1.56%   |
| Fujitsu PRIMERGY      | 1        | 1.56%   |
| Fujitsu FujitsuTP7000 | 1        | 1.56%   |
| eMachines EL1352G     | 1        | 1.56%   |
| ECS M789CG            | 1        | 1.56%   |
| Compaq Deskpro        | 1        | 1.56%   |
| ASUS Z170-E           | 1        | 1.56%   |
| ASUS TS10             | 1        | 1.56%   |
| ASUS P8H67-V          | 1        | 1.56%   |
| ASRock Z790M-ITX      | 1        | 1.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 10       | 15.63%  |
| 2014    | 8        | 12.5%   |
| 2020    | 5        | 7.81%   |
| 2018    | 5        | 7.81%   |
| 2016    | 5        | 7.81%   |
| 2010    | 5        | 7.81%   |
| 2012    | 4        | 6.25%   |
| 2023    | 3        | 4.69%   |
| 2011    | 3        | 4.69%   |
| 2007    | 3        | 4.69%   |
| 2022    | 2        | 3.13%   |
| 2019    | 2        | 3.13%   |
| 2009    | 2        | 3.13%   |
| 2001    | 2        | 3.13%   |
| Unknown | 2        | 3.13%   |
| 2017    | 1        | 1.56%   |
| 2015    | 1        | 1.56%   |
| 2004    | 1        | 1.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 64       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 64       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 64       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 17       | 25.76%  |
| 16.01-24.0  | 13       | 19.7%   |
| 8.01-16.0   | 8        | 12.12%  |
| 4.01-8.0    | 7        | 10.61%  |
| 32.01-64.0  | 7        | 10.61%  |
| 0.51-1.0    | 4        | 6.06%   |
| 1.01-2.0    | 3        | 4.55%   |
| 0.01-0.5    | 3        | 4.55%   |
| 2.01-3.0    | 2        | 3.03%   |
| 64.01-256.0 | 2        | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 18       | 27.27%  |
| 1.01-2.0  | 15       | 22.73%  |
| 0.51-1.0  | 13       | 19.7%   |
| 3.01-4.0  | 6        | 9.09%   |
| 2.01-3.0  | 5        | 7.58%   |
| 4.01-8.0  | 3        | 4.55%   |
| 0         | 3        | 4.55%   |
| Unknown   | 2        | 3.03%   |
| 8.01-16.0 | 1        | 1.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 30       | 46.88%  |
| 2      | 15       | 23.44%  |
| 3      | 9        | 14.06%  |
| 4      | 7        | 10.94%  |
| 12     | 1        | 1.56%   |
| 5      | 1        | 1.56%   |
| 0      | 1        | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 85.94%  |
| Yes       | 9        | 14.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 62       | 96.88%  |
| No        | 2        | 3.13%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 64.62%  |
| Yes       | 23       | 35.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 71.88%  |
| Yes       | 18       | 28.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 16       | 24.62%  |
| Germany     | 8        | 12.31%  |
| Russia      | 4        | 6.15%   |
| UK          | 3        | 4.62%   |
| Norway      | 3        | 4.62%   |
| Brazil      | 3        | 4.62%   |
| Sweden      | 2        | 3.08%   |
| Finland     | 2        | 3.08%   |
| Argentina   | 2        | 3.08%   |
| Vietnam     | 1        | 1.54%   |
| Uruguay     | 1        | 1.54%   |
| Ukraine     | 1        | 1.54%   |
| Switzerland | 1        | 1.54%   |
| Spain       | 1        | 1.54%   |
| Romania     | 1        | 1.54%   |
| Portugal    | 1        | 1.54%   |
| Poland      | 1        | 1.54%   |
| Pakistan    | 1        | 1.54%   |
| Netherlands | 1        | 1.54%   |
| Mexico      | 1        | 1.54%   |
| Ireland     | 1        | 1.54%   |
| Indonesia   | 1        | 1.54%   |
| Hong Kong   | 1        | 1.54%   |
| Guatemala   | 1        | 1.54%   |
| France      | 1        | 1.54%   |
| China       | 1        | 1.54%   |
| Canada      | 1        | 1.54%   |
| Belarus     | 1        | 1.54%   |
| Austria     | 1        | 1.54%   |
| Australia   | 1        | 1.54%   |
| Algeria     | 1        | 1.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Springfield              | 4        | 6.15%   |
| St Petersburg            | 3        | 4.62%   |
| Traunstein               | 2        | 3.08%   |
| Stillwater               | 2        | 3.08%   |
| Manitowoc                | 2        | 3.08%   |
| Harrisonburg             | 2        | 3.08%   |
| Frankfurt am Main        | 2        | 3.08%   |
| As                       | 2        | 3.08%   |
| Zurich                   | 1        | 1.54%   |
| Tuusula                  | 1        | 1.54%   |
| Tinh Binh Duong          | 1        | 1.54%   |
| Stuttgart                | 1        | 1.54%   |
| Stockholm                | 1        | 1.54%   |
| Somerset                 | 1        | 1.54%   |
| Ski                      | 1        | 1.54%   |
| Salzburg                 | 1        | 1.54%   |
| Saint-Julien-en-Genevois | 1        | 1.54%   |
| Redwood City             | 1        | 1.54%   |
| Penza                    | 1        | 1.54%   |
| Oberhausen               | 1        | 1.54%   |
| Nussdorf am Inn          | 1        | 1.54%   |
| Noblesville              | 1        | 1.54%   |
| Montevideo               | 1        | 1.54%   |
| Minsk                    | 1        | 1.54%   |
| Lisbon                   | 1        | 1.54%   |
| Lahore                   | 1        | 1.54%   |
| Kharkiv                  | 1        | 1.54%   |
| Jember                   | 1        | 1.54%   |
| Hong Kong                | 1        | 1.54%   |
| Helsinki                 | 1        | 1.54%   |
| Hangzhou                 | 1        | 1.54%   |
| Hamburg                  | 1        | 1.54%   |
| Guatemala City           | 1        | 1.54%   |
| Gothenburg               | 1        | 1.54%   |
| Gorredijk                | 1        | 1.54%   |
| Glasgow                  | 1        | 1.54%   |
| General San Martin       | 1        | 1.54%   |
| Farmington               | 1        | 1.54%   |
| Durham                   | 1        | 1.54%   |
| Dublin                   | 1        | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Samsung Electronics   | 17       | 30     | 16.67%  |
| WDC                   | 16       | 21     | 15.69%  |
| Seagate               | 14       | 30     | 13.73%  |
| Toshiba               | 7        | 7      | 6.86%   |
| SanDisk               | 5        | 8      | 4.9%    |
| Crucial               | 5        | 8      | 4.9%    |
| A-DATA Technology     | 5        | 7      | 4.9%    |
| Hitachi               | 4        | 4      | 3.92%   |
| HGST                  | 4        | 4      | 3.92%   |
| Kingston              | 3        | 3      | 2.94%   |
| Unknown               | 2        | 2      | 1.96%   |
| SK hynix              | 2        | 2      | 1.96%   |
| Intel                 | 2        | 3      | 1.96%   |
| Transcend             | 1        | 1      | 0.98%   |
| SPCC                  | 1        | 1      | 0.98%   |
| Realtek Semiconductor | 1        | 1      | 0.98%   |
| Phison Electronics    | 1        | 1      | 0.98%   |
| Micron Technology     | 1        | 1      | 0.98%   |
| Maxtor                | 1        | 1      | 0.98%   |
| LITEON                | 1        | 1      | 0.98%   |
| Lexar                 | 1        | 1      | 0.98%   |
| KIOXIA                | 1        | 1      | 0.98%   |
| Kingmax               | 1        | 1      | 0.98%   |
| Intenso               | 1        | 1      | 0.98%   |
| EDILOCA               | 1        | 1      | 0.98%   |
| Corsair               | 1        | 1      | 0.98%   |
| ASMT                  | 1        | 1      | 0.98%   |
| Apple                 | 1        | 3      | 0.98%   |
| Apacer                | 1        | 1      | 0.98%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3        | 2.56%   |
| Seagate ST380815AS 80GB                           | 2        | 1.71%   |
| Samsung SSD 960 EVO 500GB                         | 2        | 1.71%   |
| Samsung SSD 870 QVO 1TB                           | 2        | 1.71%   |
| Samsung SSD 870 EVO 1TB                           | 2        | 1.71%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1        | 0.85%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                  | 1        | 0.85%   |
| WDC WDS250G2B0B 250GB SSD                         | 1        | 0.85%   |
| WDC WD80EFZZ-68B 8TB                              | 1        | 0.85%   |
| WDC WD800JD-75MSA3 80GB                           | 1        | 0.85%   |
| WDC WD800AAJS-00 80GB                             | 1        | 0.85%   |
| WDC WD7500BPKT-80PK4T0 752GB                      | 1        | 0.85%   |
| WDC WD5000AZRX-00A8LB0 500GB                      | 1        | 0.85%   |
| WDC WD5000AAKX-00ERMA0 500GB                      | 1        | 0.85%   |
| WDC WD40EFZX-68AWUN0 4TB                          | 1        | 0.85%   |
| WDC WD3200AAKX-0 320GB                            | 1        | 0.85%   |
| WDC WD20EZRZ-00Z 2TB                              | 1        | 0.85%   |
| WDC WD1600JS-60NCB1 160GB                         | 1        | 0.85%   |
| WDC WD1600BEVT-2 160GB                            | 1        | 0.85%   |
| WDC WD140EDGZ-11B2DA2 14TB                        | 1        | 0.85%   |
| WDC WD120EFBX-68B0EN0 12TB                        | 1        | 0.85%   |
| WDC WD10JPVX-75JC3T0 1TB                          | 1        | 0.85%   |
| WDC WD10EZEX-75WN4A1 1TB                          | 1        | 0.85%   |
| WDC WD10EZEX-21M2NA0 1TB                          | 1        | 0.85%   |
| Unknown SD/MMC/MS PRO 128GB                       | 1        | 0.85%   |
| Unknown MMC Card  32GB                            | 1        | 0.85%   |
| Transcend SSD 1GB                                 | 1        | 0.85%   |
| Toshiba MQ04ABF100 1TB                            | 1        | 0.85%   |
| Toshiba MQ01ABF050 500GB                          | 1        | 0.85%   |
| Toshiba MK3252GS 320GB                            | 1        | 0.85%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD           | 1        | 0.85%   |
| Toshiba HDWK105 500GB                             | 1        | 0.85%   |
| Toshiba HDWD130 3TB                               | 1        | 0.85%   |
| Toshiba DT01ACA2 2TB                              | 1        | 0.85%   |
| SPCC Solid State Disk 120GB                       | 1        | 0.85%   |
| SK hynix SC300 M.2 2280 256 256GB SSD             | 1        | 0.85%   |
| SK hynix BC501 NVMe Solid State Drive 512GB       | 1        | 0.85%   |
| Seagate ST980310AS 80GB                           | 1        | 0.85%   |
| Seagate ST500LT012-1DG14 500GB                    | 1        | 0.85%   |
| Seagate ST500LM021-1KJ152 500GB                   | 1        | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 18     | 28.57%  |
| Seagate             | 14       | 30     | 28.57%  |
| Toshiba             | 6        | 6      | 12.24%  |
| Hitachi             | 4        | 4      | 8.16%   |
| HGST                | 4        | 4      | 8.16%   |
| Samsung Electronics | 3        | 6      | 6.12%   |
| Unknown             | 1        | 1      | 2.04%   |
| Maxtor              | 1        | 1      | 2.04%   |
| EDILOCA             | 1        | 1      | 2.04%   |
| ASMT                | 1        | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 23.68%  |
| Crucial             | 5        | 8      | 13.16%  |
| A-DATA Technology   | 4        | 5      | 10.53%  |
| Kingston            | 3        | 3      | 7.89%   |
| WDC                 | 2        | 3      | 5.26%   |
| SanDisk             | 2        | 3      | 5.26%   |
| Intel               | 2        | 3      | 5.26%   |
| Transcend           | 1        | 1      | 2.63%   |
| Toshiba             | 1        | 1      | 2.63%   |
| SPCC                | 1        | 1      | 2.63%   |
| SK hynix            | 1        | 1      | 2.63%   |
| Micron Technology   | 1        | 1      | 2.63%   |
| LITEON              | 1        | 1      | 2.63%   |
| Lexar               | 1        | 1      | 2.63%   |
| Kingmax             | 1        | 1      | 2.63%   |
| Intenso             | 1        | 1      | 2.63%   |
| Corsair             | 1        | 1      | 2.63%   |
| Apacer              | 1        | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 38       | 72     | 42.7%   |
| SSD  | 33       | 48     | 37.08%  |
| NVMe | 17       | 26     | 19.1%   |
| MMC  | 1        | 1      | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 55       | 116    | 72.37%  |
| NVMe | 17       | 26     | 22.37%  |
| SAS  | 3        | 4      | 3.95%   |
| MMC  | 1        | 1      | 1.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 48       | 73     | 67.61%  |
| 0.51-1.0   | 10       | 17     | 14.08%  |
| 3.01-4.0   | 3        | 7      | 4.23%   |
| 2.01-3.0   | 3        | 7      | 4.23%   |
| 4.01-10.0  | 3        | 3      | 4.23%   |
| 10.01-20.0 | 2        | 9      | 2.82%   |
| 1.01-2.0   | 2        | 4      | 2.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 17       | 26.56%  |
| 101-250        | 11       | 17.19%  |
| More than 3000 | 7        | 10.94%  |
| 251-500        | 6        | 9.38%   |
| 1-20           | 6        | 9.38%   |
| 51-100         | 5        | 7.81%   |
| 21-50          | 4        | 6.25%   |
| 501-1000       | 4        | 6.25%   |
| 2001-3000      | 2        | 3.13%   |
| 1001-2000      | 2        | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 27       | 42.19%  |
| Unknown        | 17       | 26.56%  |
| 21-50          | 6        | 9.38%   |
| 251-500        | 5        | 7.81%   |
| 51-100         | 3        | 4.69%   |
| More than 3000 | 2        | 3.13%   |
| 1001-2000      | 2        | 3.13%   |
| 2001-3000      | 1        | 1.56%   |
| 501-1000       | 1        | 1.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD3200AAKX-0 320GB             | 1        | 1      | 9.09%   |
| Toshiba MK3252GS 320GB             | 1        | 1      | 9.09%   |
| Seagate ST500LM021-1KJ152 500GB    | 1        | 1      | 9.09%   |
| SanDisk SDSA6MM 16GB SSD           | 1        | 1      | 9.09%   |
| Samsung Electronics SSD PM81 128GB | 1        | 1      | 9.09%   |
| Samsung Electronics SP0411N 40GB   | 1        | 2      | 9.09%   |
| Maxtor 2B020H1 20GB                | 1        | 1      | 9.09%   |
| Kingmax SSD 120G                   | 1        | 1      | 9.09%   |
| Hitachi HTS722080K9A300 80GB       | 1        | 1      | 9.09%   |
| HGST HTS725050A7 500GB             | 1        | 1      | 9.09%   |
| A-DATA Technology SU800 128GB SSD  | 1        | 2      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 3      | 18.18%  |
| WDC                 | 1        | 1      | 9.09%   |
| Toshiba             | 1        | 1      | 9.09%   |
| Seagate             | 1        | 1      | 9.09%   |
| SanDisk             | 1        | 1      | 9.09%   |
| Maxtor              | 1        | 1      | 9.09%   |
| Kingmax             | 1        | 1      | 9.09%   |
| Hitachi             | 1        | 1      | 9.09%   |
| HGST                | 1        | 1      | 9.09%   |
| A-DATA Technology   | 1        | 2      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 14.29%  |
| Toshiba             | 1        | 1      | 14.29%  |
| Seagate             | 1        | 1      | 14.29%  |
| Samsung Electronics | 1        | 2      | 14.29%  |
| Maxtor              | 1        | 1      | 14.29%  |
| Hitachi             | 1        | 1      | 14.29%  |
| HGST                | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 8      | 63.64%  |
| SSD  | 4        | 5      | 36.36%  |

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
| Works    | 42       | 91     | 59.15%  |
| Detected | 19       | 43     | 26.76%  |
| Malfunc  | 10       | 13     | 14.08%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 46       | 53.49%  |
| AMD                       | 10       | 11.63%  |
| Samsung Electronics       | 8        | 9.3%    |
| ASMedia Technology        | 4        | 4.65%   |
| SanDisk                   | 3        | 3.49%   |
| VIA Technologies          | 2        | 2.33%   |
| Marvell Technology Group  | 2        | 2.33%   |
| LSI Logic / Symbios Logic | 2        | 2.33%   |
| Adaptec                   | 2        | 2.33%   |
| SK hynix                  | 1        | 1.16%   |
| Realtek Semiconductor     | 1        | 1.16%   |
| Promise Technology        | 1        | 1.16%   |
| Phison Electronics        | 1        | 1.16%   |
| Nvidia                    | 1        | 1.16%   |
| KIOXIA                    | 1        | 1.16%   |
| ADATA Technology          | 1        | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8        | 7.84%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 6        | 5.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5        | 4.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4        | 3.92%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 4        | 3.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3        | 2.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3        | 2.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 3        | 2.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3        | 2.94%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 2        | 1.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2        | 1.96%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 2        | 1.96%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]          | 2        | 1.96%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2        | 1.96%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2        | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                       | 2        | 1.96%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                                 | 2        | 1.96%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1        | 0.98%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                       | 1        | 0.98%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1        | 0.98%   |
| SanDisk WD Black NVMe SSD                                                        | 1        | 0.98%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 1        | 0.98%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1        | 0.98%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                      | 1        | 0.98%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1        | 0.98%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                | 1        | 0.98%   |
| Promise PDC42819 [FastTrak TX2650/TX4650]                                        | 1        | 0.98%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 1        | 0.98%   |
| Nvidia MCP61 SATA Controller                                                     | 1        | 0.98%   |
| Nvidia MCP61 IDE                                                                 | 1        | 0.98%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1        | 0.98%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                       | 1        | 0.98%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1        | 0.98%   |
| Intel SATA Controller [RAID mode]                                                | 1        | 0.98%   |
| Intel Raptor Lake SATA AHCI Controller                                           | 1        | 0.98%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1        | 0.98%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1        | 0.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1        | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 0.98%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 1        | 0.98%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 46       | 53.49%  |
| IDE  | 16       | 18.6%   |
| NVMe | 15       | 17.44%  |
| RAID | 7        | 8.14%   |
| SAS  | 2        | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 50       | 78.13%  |
| AMD          | 11       | 17.19%  |
| iSH          | 1        | 1.56%   |
| CentaurHauls | 1        | 1.56%   |
| Unknown      | 1        | 1.56%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i9-10900 CPU @ 2.80GHz      | 2        | 3.13%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2        | 3.13%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 2        | 3.13%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 3.13%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 2        | 3.13%   |
| Intel Celeron CPU J1900 @ 1.99GHz      | 2        | 3.13%   |
| Intel Atom CPU D525 @ 1.80GHz          | 2        | 3.13%   |
| iSH Processor                          | 1        | 1.56%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1        | 1.56%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz    | 1        | 1.56%   |
| Intel Pentium III (Coppermine)         | 1        | 1.56%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1        | 1.56%   |
| Intel Pentium CPU G3460 @ 3.50GHz      | 1        | 1.56%   |
| Intel Pentium CPU E5700 @ 3.00GHz      | 1        | 1.56%   |
| Intel Genuine CPU 2140 @ 1.60GHz       | 1        | 1.56%   |
| Intel Core i7-8700T CPU @ 2.40GHz      | 1        | 1.56%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 1.56%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 1        | 1.56%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 1        | 1.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 1.56%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1        | 1.56%   |
| Intel Core i5-6600K CPU @ 3.50GHz      | 1        | 1.56%   |
| Intel Core i5-6500T CPU @ 2.50GHz      | 1        | 1.56%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 1        | 1.56%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 1        | 1.56%   |
| Intel Core i5-4570T CPU @ 2.90GHz      | 1        | 1.56%   |
| Intel Core i5-3450 CPU @ 3.10GHz       | 1        | 1.56%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 1.56%   |
| Intel Core i5-1030NG7 CPU @ 1.10GHz    | 1        | 1.56%   |
| Intel Core i3-3240 CPU @ 3.40GHz       | 1        | 1.56%   |
| Intel Core i3-3220T CPU @ 2.80GHz      | 1        | 1.56%   |
| Intel Core i3-2100 CPU @ 3.10GHz       | 1        | 1.56%   |
| Intel Core i3 CPU 540 @ 3.07GHz        | 1        | 1.56%   |
| Intel Core 2 CPU 4300 @ 1.80GHz        | 1        | 1.56%   |
| Intel Celeron N5105 @ 2.00GHz          | 1        | 1.56%   |
| Intel Celeron M processor 1.00GHz      | 1        | 1.56%   |
| Intel Celeron CPU N3150 @ 1.60GHz      | 1        | 1.56%   |
| Intel Celeron CPU J3455 @ 1.50GHz      | 1        | 1.56%   |
| Intel Celeron CPU J1800 @ 2.41GHz      | 1        | 1.56%   |
| Intel Celeron CPU G1850 @ 2.90GHz      | 1        | 1.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 13       | 20.31%  |
| Intel Celeron      | 8        | 12.5%   |
| Intel Core i7      | 7        | 10.94%  |
| Other              | 6        | 9.38%   |
| Intel Core i3      | 6        | 9.38%   |
| Intel Atom         | 3        | 4.69%   |
| AMD Ryzen 7        | 3        | 4.69%   |
| Intel Xeon         | 2        | 3.13%   |
| Intel Pentium      | 2        | 3.13%   |
| Intel Core i9      | 2        | 3.13%   |
| Intel Pentium III  | 1        | 1.56%   |
| Intel Pentium Dual | 1        | 1.56%   |
| Intel Genuine      | 1        | 1.56%   |
| Intel Core 2       | 1        | 1.56%   |
| Intel Celeron M    | 1        | 1.56%   |
| AMD Sempron        | 1        | 1.56%   |
| AMD Ryzen 9        | 1        | 1.56%   |
| AMD GX             | 1        | 1.56%   |
| AMD G              | 1        | 1.56%   |
| AMD FX             | 1        | 1.56%   |
| AMD E1             | 1        | 1.56%   |
| AMD A8             | 1        | 1.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 25       | 39.06%  |
| 2       | 19       | 29.69%  |
| 1       | 7        | 10.94%  |
| 8       | 4        | 6.25%   |
| 6       | 3        | 4.69%   |
| 12      | 2        | 3.13%   |
| 10      | 2        | 3.13%   |
| 24      | 1        | 1.56%   |
| Unknown | 1        | 1.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 61       | 95.31%  |
| 0       | 2        | 3.13%   |
| Unknown | 1        | 1.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 37       | 57.81%  |
| 2       | 26       | 40.63%  |
| Unknown | 1        | 1.56%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 35       | 54.69%  |
| 32-bit, 64-bit | 26       | 40.63%  |
| 32-bit         | 2        | 3.13%   |
| 64-bit         | 1        | 1.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 37       | 56.06%  |
| 0x306c3    | 4        | 6.06%   |
| 0x906ea    | 2        | 3.03%   |
| 0x306a9    | 2        | 3.03%   |
| 0xb0671    | 1        | 1.52%   |
| 0xa0655    | 1        | 1.52%   |
| 0x90672    | 1        | 1.52%   |
| 0x6fd      | 1        | 1.52%   |
| 0x6f2      | 1        | 1.52%   |
| 0x6d8      | 1        | 1.52%   |
| 0x68a      | 1        | 1.52%   |
| 0x506e3    | 1        | 1.52%   |
| 0x506c9    | 1        | 1.52%   |
| 0x406c4    | 1        | 1.52%   |
| 0x30678    | 1        | 1.52%   |
| 0x20655    | 1        | 1.52%   |
| 0x106e5    | 1        | 1.52%   |
| 0x106ca    | 1        | 1.52%   |
| 0x1067a    | 1        | 1.52%   |
| 0x0a20120e | 1        | 1.52%   |
| 0x08701021 | 1        | 1.52%   |
| 0x0800820d | 1        | 1.52%   |
| 0x06000817 | 1        | 1.52%   |
| 0x05000101 | 1        | 1.52%   |
| 0x010000b6 | 1        | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 11       | 17.19%  |
| Silvermont       | 5        | 7.81%   |
| Skylake          | 4        | 6.25%   |
| IvyBridge        | 4        | 6.25%   |
| Unknown          | 4        | 6.25%   |
| SandyBridge      | 3        | 4.69%   |
| KabyLake         | 3        | 4.69%   |
| Core             | 3        | 4.69%   |
| CometLake        | 3        | 4.69%   |
| Zen 3            | 2        | 3.13%   |
| Piledriver       | 2        | 3.13%   |
| Penryn           | 2        | 3.13%   |
| P6               | 2        | 3.13%   |
| Jaguar           | 2        | 3.13%   |
| Bonnell          | 2        | 3.13%   |
| Alderlake Hybrid | 2        | 3.13%   |
| Zen+             | 1        | 1.56%   |
| Zen 2            | 1        | 1.56%   |
| Westmere         | 1        | 1.56%   |
| Nehalem          | 1        | 1.56%   |
| K6               | 1        | 1.56%   |
| K10              | 1        | 1.56%   |
| IceLake          | 1        | 1.56%   |
| Goldmont         | 1        | 1.56%   |
| Broadwell        | 1        | 1.56%   |
| Bobcat           | 1        | 1.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 40       | 60.61%  |
| AMD                        | 15       | 22.73%  |
| Nvidia                     | 7        | 10.61%  |
| VIA Technologies           | 2        | 3.03%   |
| S3 Graphics                | 1        | 1.52%   |
| Matrox Electronics Systems | 1        | 1.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8        | 12.12%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 4.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 4.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 4.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 3.03%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 3.03%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.03%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 3.03%   |
| VIA Technologies VT8623 [Apollo CLE266] integrated CastleRock graphics                   | 1        | 1.52%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1        | 1.52%   |
| S3 Graphics Savage 4                                                                     | 1        | 1.52%   |
| Nvidia GT218 [ION]                                                                       | 1        | 1.52%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 1.52%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 1.52%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.52%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1        | 1.52%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1        | 1.52%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 1.52%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.52%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 1        | 1.52%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 1.52%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.52%   |
| Intel Iris Plus Graphics G7 (Ice Lake)                                                   | 1        | 1.52%   |
| Intel HD Graphics 530                                                                    | 1        | 1.52%   |
| Intel HD Graphics 500                                                                    | 1        | 1.52%   |
| Intel DG2 [Arc A770]                                                                     | 1        | 1.52%   |
| Intel DG2 [Arc A750]                                                                     | 1        | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 1.52%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 1.52%   |
| Intel AlderLake-S GT1                                                                    | 1        | 1.52%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 1.52%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.52%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1        | 1.52%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.52%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1        | 1.52%   |
| AMD Trinity [Radeon HD 7560D]                                                            | 1        | 1.52%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                                   | 1        | 1.52%   |
| AMD RC410 [Radeon Xpress 200/1100]                                                       | 1        | 1.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 37       | 57.81%  |
| 1 x AMD         | 14       | 21.88%  |
| 1 x Nvidia      | 5        | 7.81%   |
| Other           | 2        | 3.13%   |
| 2 x Intel       | 1        | 1.56%   |
| 1 x VIA         | 1        | 1.56%   |
| 1 x S3 Graphics | 1        | 1.56%   |
| 1 x Matrox      | 1        | 1.56%   |
| Intel + Nvidia  | 1        | 1.56%   |
| AMD + VIA       | 1        | 1.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 50       | 78.13%  |
| Unknown | 14       | 21.88%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 50       | 78.13%  |
| 0.01-0.5   | 5        | 7.81%   |
| 7.01-8.0   | 4        | 6.25%   |
| 0.51-1.0   | 2        | 3.13%   |
| 3.01-4.0   | 1        | 1.56%   |
| 1.01-2.0   | 1        | 1.56%   |
| 8.01-16.0  | 1        | 1.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 8        | 17.39%  |
| Goldstar            | 7        | 15.22%  |
| Samsung Electronics | 6        | 13.04%  |
| AOC                 | 6        | 13.04%  |
| BenQ                | 4        | 8.7%    |
| Hewlett-Packard     | 2        | 4.35%   |
| Belinea             | 2        | 4.35%   |
| Acer                | 2        | 4.35%   |
| Vizio               | 1        | 2.17%   |
| ViewSonic           | 1        | 2.17%   |
| Philips             | 1        | 2.17%   |
| Mi                  | 1        | 2.17%   |
| Huion               | 1        | 2.17%   |
| HJW                 | 1        | 2.17%   |
| Elo Touch           | 1        | 2.17%   |
| CTC                 | 1        | 2.17%   |
| CS_                 | 1        | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch     | 3        | 6.52%   |
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                     | 3        | 6.52%   |
| Belinea B101555 MAX05DF 1024x768 304x228mm 15.0-inch                 | 2        | 4.35%   |
| Vizio VX42L HDTV10A VIZ0030 1366x768 930x523mm 42.0-inch             | 1        | 2.17%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch             | 1        | 2.17%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 2.17%   |
| Samsung Electronics S27A950D SAM079E 1920x1080 598x336mm 27.0-inch   | 1        | 2.17%   |
| Samsung Electronics LS24AG30x SAM7179 1920x1080 527x296mm 23.8-inch  | 1        | 2.17%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch              | 1        | 2.17%   |
| Mi Monitor XMI2701 2560x1440 597x336mm 27.0-inch                     | 1        | 2.17%   |
| Huion GT-192 HAT1920 1920x1080 432x243mm 19.5-inch                   | 1        | 2.17%   |
| HJW MACROSILICON HJW1836 1680x1050 530x290mm 23.8-inch               | 1        | 2.17%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch          | 1        | 2.17%   |
| Hewlett-Packard LA1751 HWP2858 1280x1024 340x270mm 17.1-inch         | 1        | 2.17%   |
| Goldstar W2253 GSM56DD 1920x1080 510x290mm 23.1-inch                 | 1        | 2.17%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 1        | 2.17%   |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch             | 1        | 2.17%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 1        | 2.17%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 2.17%   |
| Goldstar M2752D GSM60B2 1920x1080 531x299mm 24.0-inch                | 1        | 2.17%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                | 1        | 2.17%   |
| Elo Touch ET1717L ELO1717 1280x1024 338x270mm 17.0-inch              | 1        | 2.17%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                   | 1        | 2.17%   |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                    | 1        | 2.17%   |
| Dell E1911 DELF037 1440x900 408x255mm 18.9-inch                      | 1        | 2.17%   |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                    | 1        | 2.17%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                    | 1        | 2.17%   |
| CTC KD02909-8770A CTC0770 1024x768 304x228mm 15.0-inch               | 1        | 2.17%   |
| CS_ LCD Monitor CS_5211 1920x1080 519x324mm 24.1-inch                | 1        | 2.17%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch              | 1        | 2.17%   |
| BenQ ZOWIE RL LCD BNQ7F4F 1920x1080 531x299mm 24.0-inch              | 1        | 2.17%   |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                    | 1        | 2.17%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                    | 1        | 2.17%   |
| AOC 912Vwa AOC1912 1440x900 408x255mm 18.9-inch                      | 1        | 2.17%   |
| AOC 718Swsg-1 AOCC750 1440x900 367x230mm 17.1-inch                   | 1        | 2.17%   |
| AOC 2476W AOC2476 1920x1080 521x293mm 23.5-inch                      | 1        | 2.17%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                      | 1        | 2.17%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                     | 1        | 2.17%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1        | 2.17%   |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                    | 1        | 2.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 14       | 33.33%  |
| 1680x1050 (WSXGA+) | 4        | 9.52%   |
| 1280x1024 (SXGA)   | 4        | 9.52%   |
| 3840x2160 (4K)     | 3        | 7.14%   |
| 3440x1440          | 3        | 7.14%   |
| 2560x1440 (QHD)    | 3        | 7.14%   |
| 1366x768 (WXGA)    | 3        | 7.14%   |
| 1024x768 (XGA)     | 3        | 7.14%   |
| 1440x900 (WXGA+)   | 2        | 4.76%   |
| 1400x1050          | 1        | 2.38%   |
| 1360x768           | 1        | 2.38%   |
| 1280x960           | 1        | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 7        | 15.56%  |
| 23     | 6        | 13.33%  |
| 24     | 4        | 8.89%   |
| 21     | 4        | 8.89%   |
| 20     | 4        | 8.89%   |
| 19     | 4        | 8.89%   |
| 18     | 4        | 8.89%   |
| 17     | 4        | 8.89%   |
| 34     | 3        | 6.67%   |
| 15     | 3        | 6.67%   |
| 42     | 1        | 2.22%   |
| 31     | 1        | 2.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 36.36%  |
| 401-500     | 14       | 31.82%  |
| 301-350     | 6        | 13.64%  |
| 701-800     | 3        | 6.82%   |
| 351-400     | 3        | 6.82%   |
| 601-700     | 1        | 2.27%   |
| 901-1000    | 1        | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 22       | 53.66%  |
| 16/10 | 8        | 19.51%  |
| 5/4   | 4        | 9.76%   |
| 4/3   | 3        | 7.32%   |
| 21/9  | 3        | 7.32%   |
| 6/5   | 1        | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 24.44%  |
| 151-200        | 11       | 24.44%  |
| 301-350        | 7        | 15.56%  |
| 141-150        | 6        | 13.33%  |
| 351-500        | 4        | 8.89%   |
| 101-110        | 3        | 6.67%   |
| 251-300        | 1        | 2.22%   |
| 131-140        | 1        | 2.22%   |
| 501-1000       | 1        | 2.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 27       | 65.85%  |
| 101-120 | 8        | 19.51%  |
| 1-50    | 4        | 9.76%   |
| 161-240 | 1        | 2.44%   |
| 121-160 | 1        | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 36       | 55.38%  |
| 0     | 24       | 36.92%  |
| 2     | 4        | 6.15%   |
| 4     | 1        | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 32       | 37.21%  |
| Intel                           | 28       | 32.56%  |
| Qualcomm Atheros                | 7        | 8.14%   |
| Broadcom                        | 5        | 5.81%   |
| Xiaomi                          | 2        | 2.33%   |
| VIA Technologies                | 2        | 2.33%   |
| Qualcomm Atheros Communications | 2        | 2.33%   |
| T & A Mobile Phones             | 1        | 1.16%   |
| Qualcomm                        | 1        | 1.16%   |
| Nvidia                          | 1        | 1.16%   |
| MediaTek                        | 1        | 1.16%   |
| D-Link System                   | 1        | 1.16%   |
| D-Link                          | 1        | 1.16%   |
| Broadcom Limited                | 1        | 1.16%   |
| Belkin Components               | 1        | 1.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                | 26       | 24.76%  |
| Intel Ethernet Controller I225-V                                                      | 4        | 3.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 3        | 2.86%   |
| Intel I211 Gigabit Network Connection                                                 | 3        | 2.86%   |
| Intel Ethernet Connection (2) I219-V                                                  | 3        | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3        | 2.86%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 2        | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                                     | 2        | 1.9%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 2        | 1.9%    |
| Qualcomm Atheros AR9271 802.11n                                                       | 2        | 1.9%    |
| Intel Ethernet Connection I217-LM                                                     | 2        | 1.9%    |
| Intel Ethernet Connection (7) I219-V                                                  | 2        | 1.9%    |
| Intel Comet Lake PCH CNVi WiFi                                                        | 2        | 1.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                        | 1        | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                  | 1        | 0.95%   |
| T & A Mobile Phones TCL 20E                                                           | 1        | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1        | 0.95%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                           | 1        | 0.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 0.95%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1        | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 0.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1        | 0.95%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                             | 1        | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1        | 0.95%   |
| Qualcomm Nokia G42 5G                                                                 | 1        | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 1        | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1        | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                             | 1        | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1        | 0.95%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1        | 0.95%   |
| Nvidia MCP61 Ethernet                                                                 | 1        | 0.95%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 0.95%   |
| Intel Wireless 3160                                                                   | 1        | 0.95%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 0.95%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                     | 1        | 0.95%   |
| Intel I210 Gigabit Network Connection                                                 | 1        | 0.95%   |
| Intel Ethernet Controller I226-V                                                      | 1        | 0.95%   |
| Intel Ethernet Controller I219-V                                                      | 1        | 0.95%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 28%     |
| Realtek Semiconductor           | 6        | 24%     |
| Qualcomm Atheros                | 4        | 16%     |
| Broadcom                        | 3        | 12%     |
| Qualcomm Atheros Communications | 2        | 8%      |
| MediaTek                        | 1        | 4%      |
| D-Link                          | 1        | 4%      |
| Belkin Components               | 1        | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                                       | 2        | 7.69%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 2        | 7.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1        | 3.85%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                           | 1        | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 3.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1        | 3.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 3.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 3.85%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                             | 1        | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 1        | 3.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1        | 3.85%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 3.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1        | 3.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 3.85%   |
| Intel Wireless 3160                                                                   | 1        | 3.85%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 3.85%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                     | 1        | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 3.85%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 3.85%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                         | 1        | 3.85%   |
| Broadcom BCM4378 802.11ax Dual Band Wireless Network Adapter                          | 1        | 3.85%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                          | 1        | 3.85%   |
| Broadcom BCM43227 802.11b/g/n                                                         | 1        | 3.85%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]                    | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 31       | 42.47%  |
| Intel                 | 27       | 36.99%  |
| Qualcomm Atheros      | 4        | 5.48%   |
| Xiaomi                | 2        | 2.74%   |
| VIA Technologies      | 2        | 2.74%   |
| Broadcom              | 2        | 2.74%   |
| T & A Mobile Phones   | 1        | 1.37%   |
| Qualcomm              | 1        | 1.37%   |
| Nvidia                | 1        | 1.37%   |
| D-Link System         | 1        | 1.37%   |
| Broadcom Limited      | 1        | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 26       | 33.33%  |
| Intel Ethernet Controller I225-V                                       | 4        | 5.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 3.85%   |
| Intel I211 Gigabit Network Connection                                  | 3        | 3.85%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 3.85%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 2        | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 2.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2        | 2.56%   |
| Intel Ethernet Connection I217-LM                                      | 2        | 2.56%   |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 2.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 1.28%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1        | 1.28%   |
| T & A Mobile Phones TCL 20E                                            | 1        | 1.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 1.28%   |
| Qualcomm Nokia G42 5G                                                  | 1        | 1.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1        | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 1.28%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 1.28%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 1.28%   |
| Intel Ethernet Controller I226-V                                       | 1        | 1.28%   |
| Intel Ethernet Controller I219-V                                       | 1        | 1.28%   |
| Intel Ethernet Connection I217-V                                       | 1        | 1.28%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 1.28%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1        | 1.28%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                           | 1        | 1.28%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 1.28%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 1.28%   |
| Intel 82567V-4 Gigabit Network Connection                              | 1        | 1.28%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 1.28%   |
| Intel 82562V-2 10/100 Network Connection                               | 1        | 1.28%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 1        | 1.28%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1        | 1.28%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                       | 1        | 1.28%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                 | 1        | 1.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 62       | 72.09%  |
| WiFi     | 23       | 26.74%  |
| Unknown  | 1        | 1.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 53       | 88.33%  |
| WiFi     | 7        | 11.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 37       | 56.92%  |
| 2     | 19       | 29.23%  |
| 3     | 5        | 7.69%   |
| 4     | 2        | 3.08%   |
| 5     | 1        | 1.54%   |
| 0     | 1        | 1.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 50       | 76.92%  |
| Yes  | 15       | 23.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 30%     |
| Cambridge Silicon Radio         | 4        | 20%     |
| Realtek Semiconductor           | 3        | 15%     |
| Actions                         | 2        | 10%     |
| Qualcomm Atheros Communications | 1        | 5%      |
| MediaTek                        | 1        | 5%      |
| IMC Networks                    | 1        | 5%      |
| ASUSTek Computer                | 1        | 5%      |
| Unknown                         | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 20%     |
| Realtek Bluetooth Radio                             | 2        | 10%     |
| Intel AX201 Bluetooth                               | 2        | 10%     |
| Actions general adapter                             | 2        | 10%     |
| Realtek Bluetooth 5.3 Radio                         | 1        | 5%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 5%      |
| MediaTek Wireless_Device                            | 1        | 5%      |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5%      |
| Intel Bluetooth wireless interface                  | 1        | 5%      |
| Intel AX211 Bluetooth                               | 1        | 5%      |
| Intel AX200 Bluetooth                               | 1        | 5%      |
| IMC Networks Bluetooth Device                       | 1        | 5%      |
| ASUS BCM20702A0                                     | 1        | 5%      |
| Unknown                                             | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 44       | 55.7%   |
| AMD                                  | 17       | 21.52%  |
| Nvidia                               | 6        | 7.59%   |
| VIA Technologies                     | 2        | 2.53%   |
| Generalplus Technology               | 2        | 2.53%   |
| Creative Labs                        | 2        | 2.53%   |
| C-Media Electronics                  | 2        | 2.53%   |
| Thesycon Systemsoftware & Consulting | 1        | 1.27%   |
| RODE Microphones                     | 1        | 1.27%   |
| Nordic Semiconductor ASA             | 1        | 1.27%   |
| Native Instruments                   | 1        | 1.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9        | 9.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8        | 8.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4        | 4.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 3.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 3.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3        | 3.26%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 3.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3        | 3.26%   |
| AMD FCH Azalia Controller                                                                         | 3        | 3.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3        | 3.26%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 2        | 2.17%   |
| Nvidia High Definition Audio Controller                                                           | 2        | 2.17%   |
| Intel DG2 Audio Controller                                                                        | 2        | 2.17%   |
| Intel Comet Lake PCH cAVS                                                                         | 2        | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2        | 2.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2        | 2.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 2.17%   |
| Generalplus Technology USB Audio Device                                                           | 2        | 2.17%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 2.17%   |
| Thesycon Systemsoftware & Consulting DX3 Pro+                                                     | 1        | 1.09%   |
| RODE Microphones RODE NT-USB Mini                                                                 | 1        | 1.09%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 1.09%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1        | 1.09%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 1.09%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1        | 1.09%   |
| Nordic Semiconductor ASA USB Composite Device                                                     | 1        | 1.09%   |
| Native Instruments Komplete Audio 2                                                               | 1        | 1.09%   |
| Intel USB PnP Sound Device                                                                        | 1        | 1.09%   |
| Intel Smart Sound Technology Audio Controller                                                     | 1        | 1.09%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 1        | 1.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.09%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1        | 1.09%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 1.09%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1        | 1.09%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                                          | 1        | 1.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1        | 1.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1        | 1.09%   |
| Intel 200 Series PCH HD Audio                                                                     | 1        | 1.09%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1        | 1.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 10       | 14.08%  |
| SK hynix            | 9        | 12.68%  |
| Crucial             | 9        | 12.68%  |
| Unknown             | 8        | 11.27%  |
| Kingston            | 8        | 11.27%  |
| Micron Technology   | 5        | 7.04%   |
| Elpida              | 5        | 7.04%   |
| Corsair             | 5        | 7.04%   |
| Unknown             | 2        | 2.82%   |
| Visipro             | 1        | 1.41%   |
| Team                | 1        | 1.41%   |
| Smart               | 1        | 1.41%   |
| Qimonda             | 1        | 1.41%   |
| PNY                 | 1        | 1.41%   |
| Patriot             | 1        | 1.41%   |
| Novatech            | 1        | 1.41%   |
| Hewlett-Packard     | 1        | 1.41%   |
| Cors                | 1        | 1.41%   |
| A-DATA Technology   | 1        | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 2        | 2.67%   |
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s      | 2        | 2.67%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s | 2        | 2.67%   |
| Unknown                                                  | 2        | 2.67%   |
| Visipro RAM T2G88S1-H9H 2GB DIMM DDR3 1333MT/s           | 1        | 1.33%   |
| Unknown RAM Module 512MB DIMM                            | 1        | 1.33%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 1.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 1.33%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                 | 1        | 1.33%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s             | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 1.33%   |
| Unknown RAM Module 128MB DIMM                            | 1        | 1.33%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 1.33%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s       | 1        | 1.33%   |
| Smart RAM SH564568FH8NZPHSCT 2GB SODIMM DDR3 1333MT/s    | 1        | 1.33%   |
| SK hynix RAM Module 1GB DIMM DDR 667MT/s                 | 1        | 1.33%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 1.33%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 1.33%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.33%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 1.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.33%   |
| SK hynix RAM 71V16635HCT8-H 128MB DIMM SDRAM 133MT/s     | 1        | 1.33%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s              | 1        | 1.33%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 1.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.33%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 1.33%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s      | 1        | 1.33%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.33%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.33%   |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s      | 1        | 1.33%   |
| Samsung RAM M3 78T2953EZ3-CE6 1024MB DIMM DDR2 1331MT/s  | 1        | 1.33%   |
| Samsung RAM M3 66S1623DT0-C75 128MB DIMM SDRAM 133MT/s   | 1        | 1.33%   |
| Samsung RAM 4D34373142353237 4GB SODIMM DDR3 1600MT/s    | 1        | 1.33%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR 667MT/s          | 1        | 1.33%   |
| PNY RAM Module 1GB DIMM DDR2 667MT/s                     | 1        | 1.33%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 1.33%   |
| Novatech RAM N3S02H1600B-L67LR0 2GB DIMM DDR3 1333MT/s   | 1        | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 32       | 58.18%  |
| DDR4    | 11       | 20%     |
| SDRAM   | 5        | 9.09%   |
| DDR2    | 2        | 3.64%   |
| DDR     | 2        | 3.64%   |
| Unknown | 2        | 3.64%   |
| DDR5    | 1        | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 45       | 84.91%  |
| SODIMM | 8        | 15.09%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 16       | 26.67%  |
| 4096  | 15       | 25%     |
| 2048  | 14       | 23.33%  |
| 1024  | 5        | 8.33%   |
| 32768 | 4        | 6.67%   |
| 16384 | 3        | 5%      |
| 128   | 2        | 3.33%   |
| 512   | 1        | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 24       | 39.34%  |
| 1333    | 7        | 11.48%  |
| 3600    | 5        | 8.2%    |
| 667     | 5        | 8.2%    |
| Unknown | 3        | 4.92%   |
| 3200    | 2        | 3.28%   |
| 2400    | 2        | 3.28%   |
| 1866    | 2        | 3.28%   |
| 1800    | 2        | 3.28%   |
| 5808    | 1        | 1.64%   |
| 3800    | 1        | 1.64%   |
| 2667    | 1        | 1.64%   |
| 2200    | 1        | 1.64%   |
| 2133    | 1        | 1.64%   |
| 1867    | 1        | 1.64%   |
| 1331    | 1        | 1.64%   |
| 800     | 1        | 1.64%   |
| 133     | 1        | 1.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intermec Technologies | 1        | 50%     |
| Brother Industries    | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Intermec PC43t           | 1        | 50%     |
| Brother HL-L2360D series | 1        | 50%     |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Z-Star Microelectronics | 2        | 66.67%  |
| Olympus Optical         | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Z-Star Vimicro USB2.0 Camera      | 1        | 33.33%  |
| Z-Star A4 TECH USB2.0 PC Camera J | 1        | 33.33%  |
| Olympus Optical PCM RECORDER      | 1        | 33.33%  |

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
| 0     | 44       | 66.67%  |
| 1     | 14       | 21.21%  |
| 2     | 4        | 6.06%   |
| 3     | 2        | 3.03%   |
| 7     | 1        | 1.52%   |
| 4     | 1        | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 16       | 48.48%  |
| Net/wireless             | 6        | 18.18%  |
| Communication controller | 5        | 15.15%  |
| Storage/ata              | 2        | 6.06%   |
| Net/ethernet             | 2        | 6.06%   |
| Sound                    | 1        | 3.03%   |
| Network                  | 1        | 3.03%   |

