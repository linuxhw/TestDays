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

Total: 86

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Alpine 3.12.0               | 5        | 8.33%   |
| Alpine 3.18.4               | 4        | 6.67%   |
| Alpine 3.17_alpha20220809   | 4        | 6.67%   |
| Alpine 3.19_alpha20230901   | 3        | 5%      |
| Alpine 3.19.0               | 3        | 5%      |
| Alpine 3.18.0               | 3        | 5%      |
| Alpine 3.16.0               | 3        | 5%      |
| Alpine 3.15.4               | 3        | 5%      |
| Alpine 3.13.0_alpha20200626 | 3        | 5%      |
| Alpine 3.18.5               | 2        | 3.33%   |
| Alpine 3.18.3               | 2        | 3.33%   |
| Alpine 3.18.2               | 2        | 3.33%   |
| Alpine 3.17.2               | 2        | 3.33%   |
| Alpine 3.17.1               | 2        | 3.33%   |
| Alpine 3.16.1               | 2        | 3.33%   |
| Alpine 3.11.2               | 2        | 3.33%   |
| Alpine 3.8.4                | 1        | 1.67%   |
| Alpine 3.20.0_alpha20231219 | 1        | 1.67%   |
| Alpine 3.17.4               | 1        | 1.67%   |
| Alpine 3.17.0               | 1        | 1.67%   |
| Alpine 3.16.2               | 1        | 1.67%   |
| Alpine 3.16.0_alpha20220328 | 1        | 1.67%   |
| Alpine 3.15.6               | 1        | 1.67%   |
| Alpine 3.15.0               | 1        | 1.67%   |
| Alpine 3.14.3               | 1        | 1.67%   |
| Alpine 3.14.2               | 1        | 1.67%   |
| Alpine 3.13.6               | 1        | 1.67%   |
| Alpine 3.13.2               | 1        | 1.67%   |
| Alpine 3.13.1               | 1        | 1.67%   |
| Alpine 3.13.0_alpha20201218 | 1        | 1.67%   |
| Alpine 3.12.3               | 1        | 1.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Alpine | 56       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Desktops | Percent |
|----------------|----------|---------|
| 5.4.43-1-lts   | 5        | 8.47%   |
| 6.1.57-0-lts   | 3        | 5.08%   |
| 6.1.51-0-lts   | 2        | 3.39%   |
| 5.15.60-0-lts  | 2        | 3.39%   |
| 6.6.8-0-lts    | 1        | 1.69%   |
| 6.6.7-0-lts    | 1        | 1.69%   |
| 6.6.6-0-lts    | 1        | 1.69%   |
| 6.6.10-0-lts   | 1        | 1.69%   |
| 6.6.1-0-edge   | 1        | 1.69%   |
| 6.3.3-0-edge   | 1        | 1.69%   |
| 6.1.64-0-lts   | 1        | 1.69%   |
| 6.1.61-0-lts   | 1        | 1.69%   |
| 6.1.60-0-lts   | 1        | 1.69%   |
| 6.1.55-2-lts   | 1        | 1.69%   |
| 6.1.54-0-lts   | 1        | 1.69%   |
| 6.1.36-0-lts   | 1        | 1.69%   |
| 6.1.34-0-lts   | 1        | 1.69%   |
| 6.1.30-0-lts   | 1        | 1.69%   |
| 6.1.28-2-lts   | 1        | 1.69%   |
| 6.0.10-0-edge  | 1        | 1.69%   |
| 5.8.0          | 1        | 1.69%   |
| 5.4.84-0-lts   | 1        | 1.69%   |
| 5.4.6-0-lts    | 1        | 1.69%   |
| 5.4.58-0-lts   | 1        | 1.69%   |
| 5.4.57-0-lts   | 1        | 1.69%   |
| 5.18.0-0-asahi | 1        | 1.69%   |
| 5.17.9-0-edge  | 1        | 1.69%   |
| 5.17.3-0-edge  | 1        | 1.69%   |
| 5.15.98-0-lts  | 1        | 1.69%   |
| 5.15.87-0-lts  | 1        | 1.69%   |
| 5.15.86-0-lts  | 1        | 1.69%   |
| 5.15.83-0-lts  | 1        | 1.69%   |
| 5.15.80        | 1        | 1.69%   |
| 5.15.74-0-lts  | 1        | 1.69%   |
| 5.15.70-0-lts  | 1        | 1.69%   |
| 5.15.64-1-pve  | 1        | 1.69%   |
| 5.15.57-0-lts  | 1        | 1.69%   |
| 5.15.46-1-lts  | 1        | 1.69%   |
| 5.15.40-0-lts  | 1        | 1.69%   |
| 5.15.38-0-lts  | 1        | 1.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.43  | 5        | 8.47%   |
| 6.1.57  | 3        | 5.08%   |
| 6.1.51  | 2        | 3.39%   |
| 5.15.60 | 2        | 3.39%   |
| 6.6.8   | 1        | 1.69%   |
| 6.6.7   | 1        | 1.69%   |
| 6.6.6   | 1        | 1.69%   |
| 6.6.10  | 1        | 1.69%   |
| 6.6.1   | 1        | 1.69%   |
| 6.3.3   | 1        | 1.69%   |
| 6.1.64  | 1        | 1.69%   |
| 6.1.61  | 1        | 1.69%   |
| 6.1.60  | 1        | 1.69%   |
| 6.1.55  | 1        | 1.69%   |
| 6.1.54  | 1        | 1.69%   |
| 6.1.36  | 1        | 1.69%   |
| 6.1.34  | 1        | 1.69%   |
| 6.1.30  | 1        | 1.69%   |
| 6.1.28  | 1        | 1.69%   |
| 6.0.10  | 1        | 1.69%   |
| 5.8.0   | 1        | 1.69%   |
| 5.4.84  | 1        | 1.69%   |
| 5.4.6   | 1        | 1.69%   |
| 5.4.58  | 1        | 1.69%   |
| 5.4.57  | 1        | 1.69%   |
| 5.18.0  | 1        | 1.69%   |
| 5.17.9  | 1        | 1.69%   |
| 5.17.3  | 1        | 1.69%   |
| 5.15.98 | 1        | 1.69%   |
| 5.15.87 | 1        | 1.69%   |
| 5.15.86 | 1        | 1.69%   |
| 5.15.83 | 1        | 1.69%   |
| 5.15.80 | 1        | 1.69%   |
| 5.15.74 | 1        | 1.69%   |
| 5.15.70 | 1        | 1.69%   |
| 5.15.64 | 1        | 1.69%   |
| 5.15.57 | 1        | 1.69%   |
| 5.15.46 | 1        | 1.69%   |
| 5.15.40 | 1        | 1.69%   |
| 5.15.38 | 1        | 1.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 15       | 26.32%  |
| 6.1     | 13       | 22.81%  |
| 5.4     | 9        | 15.79%  |
| 6.6     | 5        | 8.77%   |
| 5.10    | 5        | 8.77%   |
| 5.17    | 2        | 3.51%   |
| 6.3     | 1        | 1.75%   |
| 6.0     | 1        | 1.75%   |
| 5.8     | 1        | 1.75%   |
| 5.18    | 1        | 1.75%   |
| 4.4     | 1        | 1.75%   |
| 4.20    | 1        | 1.75%   |
| 4.14    | 1        | 1.75%   |
| 3.10    | 1        | 1.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 49       | 87.5%   |
| i686    | 6        | 10.71%  |
| aarch64 | 1        | 1.79%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 44       | 78.57%  |
| XFCE    | 5        | 8.93%   |
| GNOME   | 3        | 5.36%   |
| KDE5    | 2        | 3.57%   |
| sway    | 1        | 1.79%   |
| i3      | 1        | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 65.52%  |
| X11     | 15       | 25.86%  |
| Wayland | 5        | 8.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 49       | 87.5%   |
| LightDM | 5        | 8.93%   |
| SDDM    | 2        | 3.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 35       | 62.5%   |
| Unknown | 18       | 32.14%  |
| pt_BR   | 1        | 1.79%   |
| en_US   | 1        | 1.79%   |
| en_GB   | 1        | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 35       | 62.5%   |
| EFI  | 21       | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 46       | 80.7%   |
| Btrfs   | 4        | 7.02%   |
| Tmpfs   | 2        | 3.51%   |
| Unknown | 2        | 3.51%   |
| Zfs     | 1        | 1.75%   |
| Overlay | 1        | 1.75%   |
| Fake    | 1        | 1.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 61.4%   |
| GPT     | 15       | 26.32%  |
| MBR     | 7        | 12.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 82.14%  |
| Yes       | 10       | 17.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 91.07%  |
| Yes       | 5        | 8.93%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 8        | 14.29%  |
| ASRock              | 8        | 14.29%  |
| Gigabyte Technology | 7        | 12.5%   |
| Dell                | 7        | 12.5%   |
| Hewlett-Packard     | 4        | 7.14%   |
| Intel               | 3        | 5.36%   |
| Unknown             | 3        | 5.36%   |
| MSI                 | 2        | 3.57%   |
| Lenovo              | 2        | 3.57%   |
| Fujitsu             | 2        | 3.57%   |
| ZOTAC               | 1        | 1.79%   |
| VIA Technologies    | 1        | 1.79%   |
| UGREEN              | 1        | 1.79%   |
| Shuttle             | 1        | 1.79%   |
| Inventec            | 1        | 1.79%   |
| Gateway             | 1        | 1.79%   |
| eMachines           | 1        | 1.79%   |
| ECS                 | 1        | 1.79%   |
| Compaq              | 1        | 1.79%   |
| Acer                | 1        | 1.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 4        | 7.14%   |
| ASUS All Series                    | 3        | 5.36%   |
| Gigabyte Z490I AORUS ULTRA         | 2        | 3.57%   |
| VIA KM266APro-835                  | 1        | 1.79%   |
| UGREEN DX4600                      | 1        | 1.79%   |
| Shuttle DS81D                      | 1        | 1.79%   |
| MSI MS-7C82                        | 1        | 1.79%   |
| MSI MS-7877                        | 1        | 1.79%   |
| Lenovo ThinkCentre M93p 10AB0016US | 1        | 1.79%   |
| Lenovo H535 10117                  | 1        | 1.79%   |
| Inventec D CLASS                   | 1        | 1.79%   |
| Intel DQ67SW                       | 1        | 1.79%   |
| Intel DH61BF AAG81311-101          | 1        | 1.79%   |
| Intel D525MW AAE93082-401          | 1        | 1.79%   |
| HP ProLiant MicroServer Gen8       | 1        | 1.79%   |
| HP EliteDesk 800 G4 DM 35W         | 1        | 1.79%   |
| HP Compaq Elite 8300 SFF           | 1        | 1.79%   |
| HP Compaq 4000 Pro SFF PC          | 1        | 1.79%   |
| Gigabyte Z170X-UD5                 | 1        | 1.79%   |
| Gigabyte X570S AERO G              | 1        | 1.79%   |
| Gigabyte X570 I AORUS PRO WIFI     | 1        | 1.79%   |
| Gigabyte B550 AORUS ELITE V2       | 1        | 1.79%   |
| Gigabyte 945GCM-S2C                | 1        | 1.79%   |
| Gateway SX2185                     | 1        | 1.79%   |
| Fujitsu PRIMERGY TX100 S2          | 1        | 1.79%   |
| Fujitsu FujitsuTP7000              | 1        | 1.79%   |
| eMachines EL1352G                  | 1        | 1.79%   |
| ECS M789CG                         | 1        | 1.79%   |
| Dell OptiPlex 755                  | 1        | 1.79%   |
| Dell OptiPlex 7040                 | 1        | 1.79%   |
| Dell OptiPlex 5000                 | 1        | 1.79%   |
| Dell OptiPlex 3020M                | 1        | 1.79%   |
| Dell OptiPlex 3010                 | 1        | 1.79%   |
| Dell Inspiron 530s                 | 1        | 1.79%   |
| Dell Inspiron 3647                 | 1        | 1.79%   |
| Compaq Deskpro                     | 1        | 1.79%   |
| ASUS Z170-E                        | 1        | 1.79%   |
| ASUS TS10                          | 1        | 1.79%   |
| ASUS PRIME H370M-PLUS              | 1        | 1.79%   |
| ASUS PRIME B360M-C                 | 1        | 1.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 5        | 8.93%   |
| Unknown               | 4        | 7.14%   |
| ASUS All              | 3        | 5.36%   |
| HP Compaq             | 2        | 3.57%   |
| Gigabyte Z490I        | 2        | 3.57%   |
| Dell Inspiron         | 2        | 3.57%   |
| ASUS PRIME            | 2        | 3.57%   |
| VIA KM266APro-835     | 1        | 1.79%   |
| UGREEN DX4600         | 1        | 1.79%   |
| Shuttle DS81D         | 1        | 1.79%   |
| MSI MS-7C82           | 1        | 1.79%   |
| MSI MS-7877           | 1        | 1.79%   |
| Lenovo ThinkCentre    | 1        | 1.79%   |
| Lenovo H535           | 1        | 1.79%   |
| Inventec D            | 1        | 1.79%   |
| Intel DQ67SW          | 1        | 1.79%   |
| Intel DH61BF          | 1        | 1.79%   |
| Intel D525MW          | 1        | 1.79%   |
| HP ProLiant           | 1        | 1.79%   |
| HP EliteDesk          | 1        | 1.79%   |
| Gigabyte Z170X-UD5    | 1        | 1.79%   |
| Gigabyte X570S        | 1        | 1.79%   |
| Gigabyte X570         | 1        | 1.79%   |
| Gigabyte B550         | 1        | 1.79%   |
| Gigabyte 945GCM-S2C   | 1        | 1.79%   |
| Gateway SX2185        | 1        | 1.79%   |
| Fujitsu PRIMERGY      | 1        | 1.79%   |
| Fujitsu FujitsuTP7000 | 1        | 1.79%   |
| eMachines EL1352G     | 1        | 1.79%   |
| ECS M789CG            | 1        | 1.79%   |
| Compaq Deskpro        | 1        | 1.79%   |
| ASUS Z170-E           | 1        | 1.79%   |
| ASUS TS10             | 1        | 1.79%   |
| ASUS P8H67-V          | 1        | 1.79%   |
| ASRock Z790M-ITX      | 1        | 1.79%   |
| ASRock X470           | 1        | 1.79%   |
| ASRock Q1900B-ITX     | 1        | 1.79%   |
| ASRock J3455M         | 1        | 1.79%   |
| ASRock H81M           | 1        | 1.79%   |
| ASRock H55M-LE        | 1        | 1.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 8        | 14.29%  |
| 2013    | 7        | 12.5%   |
| 2020    | 5        | 8.93%   |
| 2018    | 5        | 8.93%   |
| 2010    | 5        | 8.93%   |
| 2016    | 4        | 7.14%   |
| 2012    | 4        | 7.14%   |
| 2011    | 3        | 5.36%   |
| 2007    | 3        | 5.36%   |
| 2022    | 2        | 3.57%   |
| 2001    | 2        | 3.57%   |
| Unknown | 2        | 3.57%   |
| 2023    | 1        | 1.79%   |
| 2019    | 1        | 1.79%   |
| 2017    | 1        | 1.79%   |
| 2015    | 1        | 1.79%   |
| 2009    | 1        | 1.79%   |
| 2004    | 1        | 1.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 56       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 56       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 56       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 15       | 25.86%  |
| 16.01-24.0  | 12       | 20.69%  |
| 4.01-8.0    | 7        | 12.07%  |
| 32.01-64.0  | 6        | 10.34%  |
| 8.01-16.0   | 6        | 10.34%  |
| 0.51-1.0    | 3        | 5.17%   |
| 0.01-0.5    | 3        | 5.17%   |
| 2.01-3.0    | 2        | 3.45%   |
| 64.01-256.0 | 2        | 3.45%   |
| 1.01-2.0    | 2        | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 15       | 26.32%  |
| 1.01-2.0  | 14       | 24.56%  |
| 0.51-1.0  | 11       | 19.3%   |
| 3.01-4.0  | 5        | 8.77%   |
| 2.01-3.0  | 4        | 7.02%   |
| 4.01-8.0  | 3        | 5.26%   |
| 0         | 2        | 3.51%   |
| Unknown   | 2        | 3.51%   |
| 8.01-16.0 | 1        | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 42.86%  |
| 2      | 13       | 23.21%  |
| 3      | 9        | 16.07%  |
| 4      | 7        | 12.5%   |
| 12     | 1        | 1.79%   |
| 5      | 1        | 1.79%   |
| 0      | 1        | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 83.93%  |
| Yes       | 9        | 16.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 54       | 96.43%  |
| No        | 2        | 3.57%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 66.67%  |
| Yes       | 19       | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 75%     |
| Yes       | 14       | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 14       | 24.56%  |
| Germany     | 7        | 12.28%  |
| Russia      | 4        | 7.02%   |
| Norway      | 3        | 5.26%   |
| UK          | 2        | 3.51%   |
| Sweden      | 2        | 3.51%   |
| Finland     | 2        | 3.51%   |
| Brazil      | 2        | 3.51%   |
| Argentina   | 2        | 3.51%   |
| Vietnam     | 1        | 1.75%   |
| Ukraine     | 1        | 1.75%   |
| Switzerland | 1        | 1.75%   |
| Spain       | 1        | 1.75%   |
| Romania     | 1        | 1.75%   |
| Portugal    | 1        | 1.75%   |
| Poland      | 1        | 1.75%   |
| Pakistan    | 1        | 1.75%   |
| Netherlands | 1        | 1.75%   |
| Mexico      | 1        | 1.75%   |
| Ireland     | 1        | 1.75%   |
| Indonesia   | 1        | 1.75%   |
| Hong Kong   | 1        | 1.75%   |
| Guatemala   | 1        | 1.75%   |
| China       | 1        | 1.75%   |
| Canada      | 1        | 1.75%   |
| Austria     | 1        | 1.75%   |
| Australia   | 1        | 1.75%   |
| Algeria     | 1        | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Springfield         | 4        | 7.02%   |
| St Petersburg       | 3        | 5.26%   |
| Manitowoc           | 2        | 3.51%   |
| Harrisonburg        | 2        | 3.51%   |
| Frankfurt am Main   | 2        | 3.51%   |
| As                  | 2        | 3.51%   |
| Zurich              | 1        | 1.75%   |
| Tuusula             | 1        | 1.75%   |
| Traunstein          | 1        | 1.75%   |
| Tinh Binh Duong     | 1        | 1.75%   |
| Stuttgart           | 1        | 1.75%   |
| Stockholm           | 1        | 1.75%   |
| Stillwater          | 1        | 1.75%   |
| Somerset            | 1        | 1.75%   |
| Ski                 | 1        | 1.75%   |
| Salzburg            | 1        | 1.75%   |
| Redwood City        | 1        | 1.75%   |
| Penza               | 1        | 1.75%   |
| Oberhausen          | 1        | 1.75%   |
| Nussdorf am Inn     | 1        | 1.75%   |
| Noblesville         | 1        | 1.75%   |
| Lisbon              | 1        | 1.75%   |
| Lahore              | 1        | 1.75%   |
| Kharkiv             | 1        | 1.75%   |
| Jember              | 1        | 1.75%   |
| Hong Kong           | 1        | 1.75%   |
| Helsinki            | 1        | 1.75%   |
| Hangzhou            | 1        | 1.75%   |
| Hamburg             | 1        | 1.75%   |
| Guatemala City      | 1        | 1.75%   |
| Gothenburg          | 1        | 1.75%   |
| Gorredijk           | 1        | 1.75%   |
| Glasgow             | 1        | 1.75%   |
| General San Martin  | 1        | 1.75%   |
| Durham              | 1        | 1.75%   |
| Dublin              | 1        | 1.75%   |
| Czarna Białostocka | 1        | 1.75%   |
| Chihuahua City      | 1        | 1.75%   |
| Chicago             | 1        | 1.75%   |
| Buenos Aires        | 1        | 1.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 30     | 18.48%  |
| WDC                 | 14       | 19     | 15.22%  |
| Seagate             | 14       | 30     | 15.22%  |
| Toshiba             | 6        | 6      | 6.52%   |
| A-DATA Technology   | 5        | 6      | 5.43%   |
| SanDisk             | 4        | 7      | 4.35%   |
| Hitachi             | 4        | 4      | 4.35%   |
| HGST                | 4        | 4      | 4.35%   |
| Crucial             | 4        | 7      | 4.35%   |
| Kingston            | 3        | 3      | 3.26%   |
| Unknown             | 2        | 2      | 2.17%   |
| SK hynix            | 2        | 2      | 2.17%   |
| Intel               | 2        | 3      | 2.17%   |
| Transcend           | 1        | 1      | 1.09%   |
| SPCC                | 1        | 1      | 1.09%   |
| Phison Electronics  | 1        | 1      | 1.09%   |
| Micron Technology   | 1        | 1      | 1.09%   |
| Maxtor              | 1        | 1      | 1.09%   |
| LITEON              | 1        | 1      | 1.09%   |
| Lexar               | 1        | 1      | 1.09%   |
| KIOXIA              | 1        | 1      | 1.09%   |
| Kingmax             | 1        | 1      | 1.09%   |
| Intenso             | 1        | 1      | 1.09%   |
| Apple               | 1        | 3      | 1.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3        | 2.8%    |
| Seagate ST380815AS 80GB                           | 2        | 1.87%   |
| Samsung SSD 960 EVO 500GB                         | 2        | 1.87%   |
| Samsung SSD 870 QVO 1TB                           | 2        | 1.87%   |
| Samsung SSD 870 EVO 1TB                           | 2        | 1.87%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1        | 0.93%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                  | 1        | 0.93%   |
| WDC WDS250G2B0B 250GB SSD                         | 1        | 0.93%   |
| WDC WD800AAJS-00 80GB                             | 1        | 0.93%   |
| WDC WD7500BPKT-80PK4T0 752GB                      | 1        | 0.93%   |
| WDC WD5000AZRX-00A8LB0 500GB                      | 1        | 0.93%   |
| WDC WD5000AAKX-00ERMA0 500GB                      | 1        | 0.93%   |
| WDC WD40EFZX-68AWUN0 4TB                          | 1        | 0.93%   |
| WDC WD3200AAKX-0 320GB                            | 1        | 0.93%   |
| WDC WD20EZRZ-00Z 2TB                              | 1        | 0.93%   |
| WDC WD1600JS-60NCB1 160GB                         | 1        | 0.93%   |
| WDC WD1600BEVT-2 160GB                            | 1        | 0.93%   |
| WDC WD140EDGZ-11B2DA2 14TB                        | 1        | 0.93%   |
| WDC WD120EFBX-68B0EN0 12TB                        | 1        | 0.93%   |
| WDC WD10JPVX-75JC3T0 1TB                          | 1        | 0.93%   |
| WDC WD10EZEX-75WN4A1 1TB                          | 1        | 0.93%   |
| WDC WD10EZEX-21M2NA0 1TB                          | 1        | 0.93%   |
| Unknown SD/MMC/MS PRO 256GB                       | 1        | 0.93%   |
| Unknown MMC Card  32GB                            | 1        | 0.93%   |
| Transcend SSD 1GB                                 | 1        | 0.93%   |
| Toshiba MQ04ABF100 1TB                            | 1        | 0.93%   |
| Toshiba MQ01ABF050 500GB                          | 1        | 0.93%   |
| Toshiba MK3252GS 320GB                            | 1        | 0.93%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD           | 1        | 0.93%   |
| Toshiba HDWD130 3TB                               | 1        | 0.93%   |
| Toshiba DT01ACA2 2TB                              | 1        | 0.93%   |
| SPCC Solid State Disk 120GB                       | 1        | 0.93%   |
| SK hynix SC300 M.2 2280 256 256GB SSD             | 1        | 0.93%   |
| SK hynix BC501 NVMe Solid State Drive 512GB       | 1        | 0.93%   |
| Seagate ST980310AS 80GB                           | 1        | 0.93%   |
| Seagate ST500LT012-1DG14 500GB                    | 1        | 0.93%   |
| Seagate ST500LM021-1KJ152 500GB                   | 1        | 0.93%   |
| Seagate ST5000LM000-2AN170 5TB                    | 1        | 0.93%   |
| Seagate ST4000VN008-2DR1 4TB                      | 1        | 0.93%   |
| Seagate ST4000NC000-1FR1 4TB                      | 1        | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 30     | 31.82%  |
| WDC                 | 12       | 16     | 27.27%  |
| Toshiba             | 5        | 5      | 11.36%  |
| Hitachi             | 4        | 4      | 9.09%   |
| HGST                | 4        | 4      | 9.09%   |
| Samsung Electronics | 3        | 6      | 6.82%   |
| Unknown             | 1        | 1      | 2.27%   |
| Maxtor              | 1        | 1      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 25.71%  |
| Crucial             | 4        | 7      | 11.43%  |
| A-DATA Technology   | 4        | 4      | 11.43%  |
| Kingston            | 3        | 3      | 8.57%   |
| WDC                 | 2        | 3      | 5.71%   |
| SanDisk             | 2        | 3      | 5.71%   |
| Intel               | 2        | 3      | 5.71%   |
| Transcend           | 1        | 1      | 2.86%   |
| Toshiba             | 1        | 1      | 2.86%   |
| SPCC                | 1        | 1      | 2.86%   |
| SK hynix            | 1        | 1      | 2.86%   |
| Micron Technology   | 1        | 1      | 2.86%   |
| LITEON              | 1        | 1      | 2.86%   |
| Lexar               | 1        | 1      | 2.86%   |
| Kingmax             | 1        | 1      | 2.86%   |
| Intenso             | 1        | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 34       | 67     | 42.5%   |
| SSD  | 30       | 44     | 37.5%   |
| NVMe | 15       | 24     | 18.75%  |
| MMC  | 1        | 1      | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 49       | 108    | 73.13%  |
| NVMe | 15       | 24     | 22.39%  |
| SAS  | 2        | 3      | 2.99%   |
| MMC  | 1        | 1      | 1.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 43       | 66     | 67.19%  |
| 0.51-1.0   | 9        | 16     | 14.06%  |
| 3.01-4.0   | 3        | 7      | 4.69%   |
| 2.01-3.0   | 3        | 7      | 4.69%   |
| 10.01-20.0 | 2        | 9      | 3.13%   |
| 1.01-2.0   | 2        | 4      | 3.13%   |
| 4.01-10.0  | 2        | 2      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 15       | 26.79%  |
| 101-250        | 10       | 17.86%  |
| 1-20           | 6        | 10.71%  |
| More than 3000 | 5        | 8.93%   |
| 251-500        | 5        | 8.93%   |
| 21-50          | 4        | 7.14%   |
| 501-1000       | 4        | 7.14%   |
| 51-100         | 3        | 5.36%   |
| 2001-3000      | 2        | 3.57%   |
| 1001-2000      | 2        | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 23       | 41.07%  |
| Unknown        | 15       | 26.79%  |
| 21-50          | 6        | 10.71%  |
| 251-500        | 5        | 8.93%   |
| 1001-2000      | 2        | 3.57%   |
| 51-100         | 2        | 3.57%   |
| More than 3000 | 1        | 1.79%   |
| 2001-3000      | 1        | 1.79%   |
| 501-1000       | 1        | 1.79%   |

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
| A-DATA Technology SU800 128GB SSD  | 1        | 1      | 9.09%   |

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
| A-DATA Technology   | 1        | 1      | 9.09%   |

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
| SSD  | 4        | 4      | 36.36%  |

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
| Works    | 38       | 87     | 60.32%  |
| Detected | 15       | 37     | 23.81%  |
| Malfunc  | 10       | 12     | 15.87%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 42       | 54.55%  |
| Samsung Electronics       | 8        | 10.39%  |
| AMD                       | 8        | 10.39%  |
| ASMedia Technology        | 3        | 3.9%    |
| VIA Technologies          | 2        | 2.6%    |
| SanDisk                   | 2        | 2.6%    |
| Marvell Technology Group  | 2        | 2.6%    |
| LSI Logic / Symbios Logic | 2        | 2.6%    |
| Adaptec                   | 2        | 2.6%    |
| SK hynix                  | 1        | 1.3%    |
| Promise Technology        | 1        | 1.3%    |
| Phison Electronics        | 1        | 1.3%    |
| Nvidia                    | 1        | 1.3%    |
| KIOXIA                    | 1        | 1.3%    |
| ADATA Technology          | 1        | 1.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6        | 6.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5        | 5.49%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5        | 5.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4        | 4.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3        | 3.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 3        | 3.3%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3        | 3.3%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 3        | 3.3%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 2        | 2.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2        | 2.2%    |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 2        | 2.2%    |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]          | 2        | 2.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2        | 2.2%    |
| Intel Comet Lake SATA AHCI Controller                                            | 2        | 2.2%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2        | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                       | 2        | 2.2%    |
| Adaptec Series 6 - 6G SAS/PCIe 2                                                 | 2        | 2.2%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 1        | 1.1%    |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                       | 1        | 1.1%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1        | 1.1%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 1        | 1.1%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1        | 1.1%    |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                      | 1        | 1.1%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1        | 1.1%    |
| Promise PDC42819 [FastTrak TX2650/TX4650]                                        | 1        | 1.1%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 1        | 1.1%    |
| Nvidia MCP61 SATA Controller                                                     | 1        | 1.1%    |
| Nvidia MCP61 IDE                                                                 | 1        | 1.1%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1        | 1.1%    |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                       | 1        | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller                              | 1        | 1.1%    |
| Intel SATA Controller [RAID mode]                                                | 1        | 1.1%    |
| Intel Raptor Lake SATA AHCI Controller                                           | 1        | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1        | 1.1%    |
| Intel Jasper Lake SATA AHCI Controller                                           | 1        | 1.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1        | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 1.1%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 1        | 1.1%    |
| Intel 82Q35 Express PT IDER Controller                                           | 1        | 1.1%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1        | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 41       | 53.95%  |
| NVMe | 13       | 17.11%  |
| IDE  | 13       | 17.11%  |
| RAID | 7        | 9.21%   |
| SAS  | 2        | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 43       | 76.79%  |
| AMD          | 10       | 17.86%  |
| iSH          | 1        | 1.79%   |
| CentaurHauls | 1        | 1.79%   |
| Unknown      | 1        | 1.79%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i9-10900 CPU @ 2.80GHz      | 2        | 3.57%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2        | 3.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 3.57%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 2        | 3.57%   |
| Intel Celeron CPU J1900 @ 1.99GHz      | 2        | 3.57%   |
| Intel Atom CPU D525 @ 1.80GHz          | 2        | 3.57%   |
| iSH Processor                          | 1        | 1.79%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1        | 1.79%   |
| Intel Pentium III (Coppermine)         | 1        | 1.79%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1        | 1.79%   |
| Intel Pentium CPU E5700 @ 3.00GHz      | 1        | 1.79%   |
| Intel Core i7-8700T CPU @ 2.40GHz      | 1        | 1.79%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 1.79%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 1        | 1.79%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 1.79%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1        | 1.79%   |
| Intel Core i5-6600K CPU @ 3.50GHz      | 1        | 1.79%   |
| Intel Core i5-6500T CPU @ 2.50GHz      | 1        | 1.79%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 1        | 1.79%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 1        | 1.79%   |
| Intel Core i5-4570T CPU @ 2.90GHz      | 1        | 1.79%   |
| Intel Core i5-3450 CPU @ 3.10GHz       | 1        | 1.79%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 1.79%   |
| Intel Core i3-3240 CPU @ 3.40GHz       | 1        | 1.79%   |
| Intel Core i3-3220T CPU @ 2.80GHz      | 1        | 1.79%   |
| Intel Core i3-2100 CPU @ 3.10GHz       | 1        | 1.79%   |
| Intel Core i3 CPU 540 @ 3.07GHz        | 1        | 1.79%   |
| Intel Core 2 CPU 4300 @ 1.80GHz        | 1        | 1.79%   |
| Intel Celeron N5105 @ 2.00GHz          | 1        | 1.79%   |
| Intel Celeron M processor 1.00GHz      | 1        | 1.79%   |
| Intel Celeron CPU N3150 @ 1.60GHz      | 1        | 1.79%   |
| Intel Celeron CPU J3455 @ 1.50GHz      | 1        | 1.79%   |
| Intel Celeron CPU J1800 @ 2.41GHz      | 1        | 1.79%   |
| Intel Celeron CPU G1850 @ 2.90GHz      | 1        | 1.79%   |
| Intel Celeron CPU E3400 @ 2.60GHz      | 1        | 1.79%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz      | 1        | 1.79%   |
| Intel 13th Gen Core i9-13900           | 1        | 1.79%   |
| Intel 12th Gen Core i7-12700T          | 1        | 1.79%   |
| CentaurHauls VIA Samuel 2              | 1        | 1.79%   |
| AMD Sempron 145 Processor              | 1        | 1.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 10       | 17.86%  |
| Intel Celeron      | 8        | 14.29%  |
| Other              | 6        | 10.71%  |
| Intel Core i7      | 6        | 10.71%  |
| Intel Core i3      | 6        | 10.71%  |
| Intel Atom         | 3        | 5.36%   |
| AMD Ryzen 7        | 3        | 5.36%   |
| Intel Core i9      | 2        | 3.57%   |
| Intel Xeon         | 1        | 1.79%   |
| Intel Pentium III  | 1        | 1.79%   |
| Intel Pentium Dual | 1        | 1.79%   |
| Intel Pentium      | 1        | 1.79%   |
| Intel Core 2       | 1        | 1.79%   |
| Intel Celeron M    | 1        | 1.79%   |
| AMD Sempron        | 1        | 1.79%   |
| AMD Ryzen 9        | 1        | 1.79%   |
| AMD G              | 1        | 1.79%   |
| AMD FX             | 1        | 1.79%   |
| AMD E1             | 1        | 1.79%   |
| AMD A8             | 1        | 1.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 20       | 35.71%  |
| 2       | 17       | 30.36%  |
| 1       | 6        | 10.71%  |
| 8       | 4        | 7.14%   |
| 6       | 3        | 5.36%   |
| 12      | 2        | 3.57%   |
| 10      | 2        | 3.57%   |
| 24      | 1        | 1.79%   |
| Unknown | 1        | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 54       | 96.43%  |
| 0       | 1        | 1.79%   |
| Unknown | 1        | 1.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 32       | 57.14%  |
| 2       | 23       | 41.07%  |
| Unknown | 1        | 1.79%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 29       | 51.79%  |
| 32-bit, 64-bit | 24       | 42.86%  |
| 32-bit         | 2        | 3.57%   |
| 64-bit         | 1        | 1.79%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30       | 52.63%  |
| 0x306c3    | 4        | 7.02%   |
| 0x906ea    | 2        | 3.51%   |
| 0x306a9    | 2        | 3.51%   |
| 0xb0671    | 1        | 1.75%   |
| 0xa0655    | 1        | 1.75%   |
| 0x90672    | 1        | 1.75%   |
| 0x6fd      | 1        | 1.75%   |
| 0x6f2      | 1        | 1.75%   |
| 0x6d8      | 1        | 1.75%   |
| 0x68a      | 1        | 1.75%   |
| 0x506c9    | 1        | 1.75%   |
| 0x406c4    | 1        | 1.75%   |
| 0x30678    | 1        | 1.75%   |
| 0x20655    | 1        | 1.75%   |
| 0x106e5    | 1        | 1.75%   |
| 0x1067a    | 1        | 1.75%   |
| 0x0a20120e | 1        | 1.75%   |
| 0x08701021 | 1        | 1.75%   |
| 0x0800820d | 1        | 1.75%   |
| 0x06000817 | 1        | 1.75%   |
| 0x05000101 | 1        | 1.75%   |
| 0x010000b6 | 1        | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 8        | 14.29%  |
| Silvermont       | 5        | 8.93%   |
| IvyBridge        | 4        | 7.14%   |
| Unknown          | 4        | 7.14%   |
| Skylake          | 3        | 5.36%   |
| SandyBridge      | 3        | 5.36%   |
| KabyLake         | 3        | 5.36%   |
| CometLake        | 3        | 5.36%   |
| Zen 3            | 2        | 3.57%   |
| Piledriver       | 2        | 3.57%   |
| Penryn           | 2        | 3.57%   |
| P6               | 2        | 3.57%   |
| Core             | 2        | 3.57%   |
| Bonnell          | 2        | 3.57%   |
| Alderlake Hybrid | 2        | 3.57%   |
| Zen+             | 1        | 1.79%   |
| Zen 2            | 1        | 1.79%   |
| Westmere         | 1        | 1.79%   |
| Nehalem          | 1        | 1.79%   |
| K6               | 1        | 1.79%   |
| K10              | 1        | 1.79%   |
| Jaguar           | 1        | 1.79%   |
| Goldmont         | 1        | 1.79%   |
| Bobcat           | 1        | 1.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 36       | 63.16%  |
| AMD                        | 11       | 19.3%   |
| Nvidia                     | 6        | 10.53%  |
| VIA Technologies           | 2        | 3.51%   |
| S3 Graphics                | 1        | 1.75%   |
| Matrox Electronics Systems | 1        | 1.75%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5        | 8.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 5.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 5.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 5.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 3.51%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 3.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 3.51%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.51%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 3.51%   |
| VIA Technologies VT8623 [Apollo CLE266] integrated CastleRock graphics                   | 1        | 1.75%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1        | 1.75%   |
| S3 Graphics Savage 4                                                                     | 1        | 1.75%   |
| Nvidia GT218 [ION]                                                                       | 1        | 1.75%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 1.75%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.75%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1        | 1.75%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1        | 1.75%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 1.75%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.75%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 1        | 1.75%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 1.75%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.75%   |
| Intel HD Graphics 530                                                                    | 1        | 1.75%   |
| Intel HD Graphics 500                                                                    | 1        | 1.75%   |
| Intel DG2 [Arc A770]                                                                     | 1        | 1.75%   |
| Intel DG2 [Arc A750]                                                                     | 1        | 1.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 1.75%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 1.75%   |
| Intel AlderLake-S GT1                                                                    | 1        | 1.75%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 1.75%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.75%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1        | 1.75%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.75%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1        | 1.75%   |
| AMD Trinity [Radeon HD 7560D]                                                            | 1        | 1.75%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                                   | 1        | 1.75%   |
| AMD Rage 3 [Rage XL PCI]                                                                 | 1        | 1.75%   |
| AMD ES1000                                                                               | 1        | 1.75%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                                            | 1        | 1.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 34       | 60.71%  |
| 1 x AMD         | 10       | 17.86%  |
| 1 x Nvidia      | 5        | 8.93%   |
| Other           | 2        | 3.57%   |
| 2 x Intel       | 1        | 1.79%   |
| 1 x VIA         | 1        | 1.79%   |
| 1 x S3 Graphics | 1        | 1.79%   |
| 1 x Matrox      | 1        | 1.79%   |
| AMD + VIA       | 1        | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 43       | 76.79%  |
| Unknown | 13       | 23.21%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 44       | 78.57%  |
| 0.01-0.5   | 4        | 7.14%   |
| 7.01-8.0   | 3        | 5.36%   |
| 0.51-1.0   | 2        | 3.57%   |
| 3.01-4.0   | 1        | 1.79%   |
| 1.01-2.0   | 1        | 1.79%   |
| 8.01-16.0  | 1        | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 8        | 20%     |
| Samsung Electronics | 6        | 15%     |
| Goldstar            | 5        | 12.5%   |
| AOC                 | 5        | 12.5%   |
| BenQ                | 4        | 10%     |
| Belinea             | 2        | 5%      |
| Acer                | 2        | 5%      |
| Vizio               | 1        | 2.5%    |
| ViewSonic           | 1        | 2.5%    |
| Philips             | 1        | 2.5%    |
| Mi                  | 1        | 2.5%    |
| Huion               | 1        | 2.5%    |
| Hewlett-Packard     | 1        | 2.5%    |
| Elo Touch           | 1        | 2.5%    |
| CTC                 | 1        | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch     | 3        | 7.5%    |
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                     | 3        | 7.5%    |
| Belinea B101555 MAX05DF 1024x768 304x228mm 15.0-inch                 | 2        | 5%      |
| Vizio VX42L HDTV10A VIZ0030 1366x768 930x523mm 42.0-inch             | 1        | 2.5%    |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch             | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch | 1        | 2.5%    |
| Samsung Electronics S27A950D SAM079E 1920x1080 598x336mm 27.0-inch   | 1        | 2.5%    |
| Samsung Electronics LS24AG30x SAM7179 1920x1080 527x296mm 23.8-inch  | 1        | 2.5%    |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch              | 1        | 2.5%    |
| Mi Monitor XMI2701 2560x1440 597x336mm 27.0-inch                     | 1        | 2.5%    |
| Huion GT-192 HAT1920 1920x1080 432x243mm 19.5-inch                   | 1        | 2.5%    |
| Hewlett-Packard LA1751 HWP2858 1280x1024 340x270mm 17.1-inch         | 1        | 2.5%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 1        | 2.5%    |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch             | 1        | 2.5%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 1        | 2.5%    |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 2.5%    |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                | 1        | 2.5%    |
| Elo Touch ET1717L ELO1717 1280x1024 338x270mm 17.0-inch              | 1        | 2.5%    |
| Dell S2716DG DELA0D1 2560x1440 600x340mm 27.2-inch                   | 1        | 2.5%    |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                    | 1        | 2.5%    |
| Dell E1911 DELF037 1440x900 408x255mm 18.9-inch                      | 1        | 2.5%    |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                    | 1        | 2.5%    |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                    | 1        | 2.5%    |
| CTC KD02909-8770A CTC0770 1024x768 304x228mm 15.0-inch               | 1        | 2.5%    |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch              | 1        | 2.5%    |
| BenQ ZOWIE RL LCD BNQ7F4F 1920x1080 531x299mm 24.0-inch              | 1        | 2.5%    |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                    | 1        | 2.5%    |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                    | 1        | 2.5%    |
| AOC 912Vwa AOC1912 1440x900 408x255mm 18.9-inch                      | 1        | 2.5%    |
| AOC 718Swsg-1 AOCC750 1440x900 367x230mm 17.1-inch                   | 1        | 2.5%    |
| AOC 2476W AOC2476 1920x1080 521x293mm 23.5-inch                      | 1        | 2.5%    |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                     | 1        | 2.5%    |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1        | 2.5%    |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                    | 1        | 2.5%    |
| Acer S236HL ACR0387 1920x1080 510x286mm 23.0-inch                    | 1        | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 31.58%  |
| 1680x1050 (WSXGA+) | 4        | 10.53%  |
| 1280x1024 (SXGA)   | 4        | 10.53%  |
| 3840x2160 (4K)     | 3        | 7.89%   |
| 3440x1440          | 3        | 7.89%   |
| 2560x1440 (QHD)    | 3        | 7.89%   |
| 1024x768 (XGA)     | 3        | 7.89%   |
| 1440x900 (WXGA+)   | 2        | 5.26%   |
| 1366x768 (WXGA)    | 2        | 5.26%   |
| 1360x768           | 1        | 2.63%   |
| 1280x960           | 1        | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 6        | 15.38%  |
| 23     | 4        | 10.26%  |
| 20     | 4        | 10.26%  |
| 19     | 4        | 10.26%  |
| 17     | 4        | 10.26%  |
| 34     | 3        | 7.69%   |
| 24     | 3        | 7.69%   |
| 21     | 3        | 7.69%   |
| 18     | 3        | 7.69%   |
| 15     | 3        | 7.69%   |
| 42     | 1        | 2.56%   |
| 31     | 1        | 2.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 33.33%  |
| 401-500     | 12       | 30.77%  |
| 301-350     | 6        | 15.38%  |
| 701-800     | 3        | 7.69%   |
| 351-400     | 3        | 7.69%   |
| 601-700     | 1        | 2.56%   |
| 901-1000    | 1        | 2.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 18       | 50%     |
| 16/10 | 7        | 19.44%  |
| 5/4   | 4        | 11.11%  |
| 4/3   | 3        | 8.33%   |
| 21/9  | 3        | 8.33%   |
| 6/5   | 1        | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 10       | 25.64%  |
| 201-250        | 9        | 23.08%  |
| 301-350        | 6        | 15.38%  |
| 141-150        | 5        | 12.82%  |
| 351-500        | 4        | 10.26%  |
| 101-110        | 3        | 7.69%   |
| 131-140        | 1        | 2.56%   |
| 501-1000       | 1        | 2.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 64.86%  |
| 101-120 | 7        | 18.92%  |
| 1-50    | 4        | 10.81%  |
| 161-240 | 1        | 2.7%    |
| 121-160 | 1        | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 57.89%  |
| 0     | 20       | 35.09%  |
| 2     | 3        | 5.26%   |
| 4     | 1        | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 28       | 36.84%  |
| Intel                           | 26       | 34.21%  |
| Qualcomm Atheros                | 5        | 6.58%   |
| Broadcom                        | 5        | 6.58%   |
| Xiaomi                          | 2        | 2.63%   |
| VIA Technologies                | 2        | 2.63%   |
| T & A Mobile Phones             | 1        | 1.32%   |
| Qualcomm Atheros Communications | 1        | 1.32%   |
| Qualcomm                        | 1        | 1.32%   |
| Nvidia                          | 1        | 1.32%   |
| MediaTek                        | 1        | 1.32%   |
| D-Link System                   | 1        | 1.32%   |
| D-Link                          | 1        | 1.32%   |
| Belkin Components               | 1        | 1.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                | 22       | 24.72%  |
| Intel Ethernet Controller I225-V                                                      | 4        | 4.49%   |
| Intel I211 Gigabit Network Connection                                                 | 3        | 3.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3        | 3.37%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 2        | 2.25%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 2        | 2.25%   |
| Intel Ethernet Connection (7) I219-V                                                  | 2        | 2.25%   |
| Intel Ethernet Connection (2) I219-V                                                  | 2        | 2.25%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 2        | 2.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                        | 1        | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                  | 1        | 1.12%   |
| T & A Mobile Phones TCL 20E                                                           | 1        | 1.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1        | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1        | 1.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1        | 1.12%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                             | 1        | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1        | 1.12%   |
| Qualcomm Redmi 9T                                                                     | 1        | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 1        | 1.12%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 1        | 1.12%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1        | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1        | 1.12%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1        | 1.12%   |
| Nvidia MCP61 Ethernet                                                                 | 1        | 1.12%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 1.12%   |
| Intel Wireless 3160                                                                   | 1        | 1.12%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 1.12%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                     | 1        | 1.12%   |
| Intel I210 Gigabit Network Connection                                                 | 1        | 1.12%   |
| Intel Ethernet Controller I226-V                                                      | 1        | 1.12%   |
| Intel Ethernet Controller I219-V                                                      | 1        | 1.12%   |
| Intel Ethernet Connection I217-V                                                      | 1        | 1.12%   |
| Intel Ethernet Connection I217-LM                                                     | 1        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                                                 | 1        | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 1        | 1.12%   |
| Intel Ethernet Connection (17) I219-LM                                                | 1        | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 33.33%  |
| Realtek Semiconductor           | 4        | 19.05%  |
| Qualcomm Atheros                | 3        | 14.29%  |
| Broadcom                        | 3        | 14.29%  |
| Qualcomm Atheros Communications | 1        | 4.76%   |
| MediaTek                        | 1        | 4.76%   |
| D-Link                          | 1        | 4.76%   |
| Belkin Components               | 1        | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Intel Comet Lake PCH CNVi WiFi                                                        | 2        | 9.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1        | 4.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 4.76%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 4.76%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                             | 1        | 4.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 1        | 4.76%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1        | 4.76%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 4.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1        | 4.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 4.76%   |
| Intel Wireless 3160                                                                   | 1        | 4.76%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 4.76%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                     | 1        | 4.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 4.76%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 4.76%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                         | 1        | 4.76%   |
| Broadcom BCM4378 802.11ax Dual Band Wireless Network Adapter                          | 1        | 4.76%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                          | 1        | 4.76%   |
| Broadcom BCM43227 802.11b/g/n                                                         | 1        | 4.76%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]                    | 1        | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 27       | 42.19%  |
| Intel                 | 25       | 39.06%  |
| Xiaomi                | 2        | 3.13%   |
| VIA Technologies      | 2        | 3.13%   |
| Qualcomm Atheros      | 2        | 3.13%   |
| Broadcom              | 2        | 3.13%   |
| T & A Mobile Phones   | 1        | 1.56%   |
| Qualcomm              | 1        | 1.56%   |
| Nvidia                | 1        | 1.56%   |
| D-Link System         | 1        | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 22       | 32.84%  |
| Intel Ethernet Controller I225-V                                       | 4        | 5.97%   |
| Intel I211 Gigabit Network Connection                                  | 3        | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 4.48%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 2        | 2.99%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 2.99%   |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 2.99%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 2.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 1.49%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1        | 1.49%   |
| T & A Mobile Phones TCL 20E                                            | 1        | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 1.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 1.49%   |
| Qualcomm Redmi 9T                                                      | 1        | 1.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 1.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 1.49%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 1.49%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 1.49%   |
| Intel Ethernet Controller I226-V                                       | 1        | 1.49%   |
| Intel Ethernet Controller I219-V                                       | 1        | 1.49%   |
| Intel Ethernet Connection I217-V                                       | 1        | 1.49%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 1.49%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 1.49%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1        | 1.49%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                           | 1        | 1.49%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 1.49%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 1.49%   |
| Intel 82567V-4 Gigabit Network Connection                              | 1        | 1.49%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 1.49%   |
| Intel 82562V-2 10/100 Network Connection                               | 1        | 1.49%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 1        | 1.49%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1        | 1.49%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                       | 1        | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 54       | 72.97%  |
| WiFi     | 19       | 25.68%  |
| Unknown  | 1        | 1.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 90.57%  |
| WiFi     | 5        | 9.43%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 56.14%  |
| 2     | 17       | 29.82%  |
| 3     | 4        | 7.02%   |
| 4     | 2        | 3.51%   |
| 5     | 1        | 1.75%   |
| 0     | 1        | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 43       | 75.44%  |
| Yes  | 14       | 24.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 40%     |
| Cambridge Silicon Radio | 4        | 26.67%  |
| Realtek Semiconductor   | 1        | 6.67%   |
| MediaTek                | 1        | 6.67%   |
| IMC Networks            | 1        | 6.67%   |
| ASUSTek Computer        | 1        | 6.67%   |
| Actions                 | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 26.67%  |
| Intel AX201 Bluetooth                               | 2        | 13.33%  |
| Realtek Bluetooth 5.3 Radio                         | 1        | 6.67%   |
| MediaTek Wireless_Device                            | 1        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 6.67%   |
| Intel Bluetooth wireless interface                  | 1        | 6.67%   |
| Intel Bluetooth Device                              | 1        | 6.67%   |
| Intel AX200 Bluetooth                               | 1        | 6.67%   |
| IMC Networks Bluetooth Device                       | 1        | 6.67%   |
| ASUS BCM20702A0                                     | 1        | 6.67%   |
| Actions general adapter                             | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 38       | 58.46%  |
| AMD                                  | 13       | 20%     |
| Nvidia                               | 5        | 7.69%   |
| VIA Technologies                     | 2        | 3.08%   |
| C-Media Electronics                  | 2        | 3.08%   |
| Thesycon Systemsoftware & Consulting | 1        | 1.54%   |
| RODE Microphones                     | 1        | 1.54%   |
| Native Instruments                   | 1        | 1.54%   |
| Generalplus Technology               | 1        | 1.54%   |
| Creative Labs                        | 1        | 1.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5        | 6.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5        | 6.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4        | 5.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 4.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 4.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3        | 4.05%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 4.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3        | 4.05%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 2        | 2.7%    |
| Intel DG2 Audio Controller                                                                        | 2        | 2.7%    |
| Intel Comet Lake PCH cAVS                                                                         | 2        | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2        | 2.7%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2        | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2        | 2.7%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 2.7%    |
| AMD FCH Azalia Controller                                                                         | 2        | 2.7%    |
| Thesycon Systemsoftware & Consulting D50s                                                         | 1        | 1.35%   |
| RODE Microphones RODE NT-USB Mini                                                                 | 1        | 1.35%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 1.35%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 1.35%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1        | 1.35%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 1.35%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1        | 1.35%   |
| Native Instruments Komplete Audio 2                                                               | 1        | 1.35%   |
| Intel USB PnP Sound Device                                                                        | 1        | 1.35%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 1        | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.35%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1        | 1.35%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 1.35%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1        | 1.35%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                                          | 1        | 1.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1        | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1        | 1.35%   |
| Generalplus Technology USB Audio Device                                                           | 1        | 1.35%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1        | 1.35%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 1        | 1.35%   |
| C-Media Electronics Blue Snowball                                                                 | 1        | 1.35%   |
| AMD Wrestler HDMI Audio                                                                           | 1        | 1.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 10       | 15.87%  |
| Unknown             | 8        | 12.7%   |
| Crucial             | 8        | 12.7%   |
| SK hynix            | 7        | 11.11%  |
| Kingston            | 7        | 11.11%  |
| Elpida              | 5        | 7.94%   |
| Micron Technology   | 4        | 6.35%   |
| Corsair             | 3        | 4.76%   |
| Unknown             | 2        | 3.17%   |
| Visipro             | 1        | 1.59%   |
| Team                | 1        | 1.59%   |
| Qimonda             | 1        | 1.59%   |
| PNY                 | 1        | 1.59%   |
| Patriot             | 1        | 1.59%   |
| Novatech            | 1        | 1.59%   |
| Hewlett-Packard     | 1        | 1.59%   |
| Cors                | 1        | 1.59%   |
| A-DATA Technology   | 1        | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s      | 2        | 2.99%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s | 2        | 2.99%   |
| Unknown                                                  | 2        | 2.99%   |
| Visipro RAM T2G88S1-H9H 2GB DIMM DDR3 1333MT/s           | 1        | 1.49%   |
| Unknown RAM Module 512MB DIMM                            | 1        | 1.49%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 1.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                 | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 1        | 1.49%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s             | 1        | 1.49%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 1.49%   |
| Unknown RAM Module 128MB DIMM                            | 1        | 1.49%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 1.49%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s      | 1        | 1.49%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 1.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 1.49%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.49%   |
| SK hynix RAM 71V16635HCT8-H 128MB DIMM SDRAM 133MT/s     | 1        | 1.49%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s              | 1        | 1.49%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 1.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s      | 1        | 1.49%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Samsung RAM M3 78T2953EZ3-CE6 1GB DIMM DDR2 1331MT/s     | 1        | 1.49%   |
| Samsung RAM M3 66S1623DT0-C75 128MB DIMM SDRAM 133MT/s   | 1        | 1.49%   |
| Samsung RAM 4D34373142353237 4GB SODIMM DDR3 1600MT/s    | 1        | 1.49%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s         | 1        | 1.49%   |
| PNY RAM Module 1GB DIMM DDR2 667MT/s                     | 1        | 1.49%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 1.49%   |
| Novatech RAM N3S02H1600B-L67LR0 2GB DIMM DDR3 1333MT/s   | 1        | 1.49%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB DIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Micron RAM 8KTF51264AZ-1G9P1 4GB DIMM DDR3 1866MT/s      | 1        | 1.49%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Micron RAM 16ATF4G64HZ-3G2F1 32GB SODIMM DDR4 3200MT/s   | 1        | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 29       | 59.18%  |
| DDR4    | 10       | 20.41%  |
| SDRAM   | 5        | 10.2%   |
| DDR2    | 2        | 4.08%   |
| Unknown | 2        | 4.08%   |
| DDR5    | 1        | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 40       | 85.11%  |
| SODIMM | 7        | 14.89%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 16       | 30.19%  |
| 4096  | 13       | 24.53%  |
| 2048  | 11       | 20.75%  |
| 32768 | 4        | 7.55%   |
| 1024  | 4        | 7.55%   |
| 16384 | 2        | 3.77%   |
| 128   | 2        | 3.77%   |
| 512   | 1        | 1.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 22       | 41.51%  |
| 1333    | 5        | 9.43%   |
| 3600    | 4        | 7.55%   |
| 667     | 3        | 5.66%   |
| Unknown | 3        | 5.66%   |
| 3200    | 2        | 3.77%   |
| 2400    | 2        | 3.77%   |
| 1866    | 2        | 3.77%   |
| 5808    | 1        | 1.89%   |
| 3800    | 1        | 1.89%   |
| 2667    | 1        | 1.89%   |
| 2200    | 1        | 1.89%   |
| 2133    | 1        | 1.89%   |
| 1867    | 1        | 1.89%   |
| 1800    | 1        | 1.89%   |
| 1331    | 1        | 1.89%   |
| 800     | 1        | 1.89%   |
| 133     | 1        | 1.89%   |

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
| Z-Star Microelectronics | 2        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Z-Star Vimicro USB2.0 Camera      | 1        | 50%     |
| Z-Star A4 TECH USB2.0 PC Camera J | 1        | 50%     |

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
| 0     | 40       | 70.18%  |
| 1     | 9        | 15.79%  |
| 2     | 4        | 7.02%   |
| 3     | 2        | 3.51%   |
| 7     | 1        | 1.75%   |
| 4     | 1        | 1.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 13       | 46.43%  |
| Net/wireless             | 5        | 17.86%  |
| Communication controller | 4        | 14.29%  |
| Storage/ata              | 2        | 7.14%   |
| Net/ethernet             | 2        | 7.14%   |
| Sound                    | 1        | 3.57%   |
| Network                  | 1        | 3.57%   |

