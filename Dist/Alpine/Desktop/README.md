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

Total: 83

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Alpine 3.12.0               | 5        | 8.47%   |
| Alpine 3.18.4               | 4        | 6.78%   |
| Alpine 3.17_alpha20220809   | 4        | 6.78%   |
| Alpine 3.19_alpha20230901   | 3        | 5.08%   |
| Alpine 3.18.0               | 3        | 5.08%   |
| Alpine 3.16.0               | 3        | 5.08%   |
| Alpine 3.15.4               | 3        | 5.08%   |
| Alpine 3.13.0_alpha20200626 | 3        | 5.08%   |
| Alpine 3.19.0               | 2        | 3.39%   |
| Alpine 3.18.5               | 2        | 3.39%   |
| Alpine 3.18.3               | 2        | 3.39%   |
| Alpine 3.18.2               | 2        | 3.39%   |
| Alpine 3.17.2               | 2        | 3.39%   |
| Alpine 3.17.1               | 2        | 3.39%   |
| Alpine 3.16.1               | 2        | 3.39%   |
| Alpine 3.11.2               | 2        | 3.39%   |
| Alpine 3.8.4                | 1        | 1.69%   |
| Alpine 3.20.0_alpha20231219 | 1        | 1.69%   |
| Alpine 3.17.4               | 1        | 1.69%   |
| Alpine 3.17.0               | 1        | 1.69%   |
| Alpine 3.16.2               | 1        | 1.69%   |
| Alpine 3.16.0_alpha20220328 | 1        | 1.69%   |
| Alpine 3.15.6               | 1        | 1.69%   |
| Alpine 3.15.0               | 1        | 1.69%   |
| Alpine 3.14.3               | 1        | 1.69%   |
| Alpine 3.14.2               | 1        | 1.69%   |
| Alpine 3.13.6               | 1        | 1.69%   |
| Alpine 3.13.2               | 1        | 1.69%   |
| Alpine 3.13.1               | 1        | 1.69%   |
| Alpine 3.13.0_alpha20201218 | 1        | 1.69%   |
| Alpine 3.12.3               | 1        | 1.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Alpine | 55       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Desktops | Percent |
|----------------|----------|---------|
| 5.4.43-1-lts   | 5        | 8.62%   |
| 6.1.57-0-lts   | 3        | 5.17%   |
| 6.1.51-0-lts   | 2        | 3.45%   |
| 5.15.60-0-lts  | 2        | 3.45%   |
| 6.6.8-0-lts    | 1        | 1.72%   |
| 6.6.7-0-lts    | 1        | 1.72%   |
| 6.6.6-0-lts    | 1        | 1.72%   |
| 6.6.1-0-edge   | 1        | 1.72%   |
| 6.3.3-0-edge   | 1        | 1.72%   |
| 6.1.64-0-lts   | 1        | 1.72%   |
| 6.1.61-0-lts   | 1        | 1.72%   |
| 6.1.60-0-lts   | 1        | 1.72%   |
| 6.1.55-2-lts   | 1        | 1.72%   |
| 6.1.54-0-lts   | 1        | 1.72%   |
| 6.1.36-0-lts   | 1        | 1.72%   |
| 6.1.34-0-lts   | 1        | 1.72%   |
| 6.1.30-0-lts   | 1        | 1.72%   |
| 6.1.28-2-lts   | 1        | 1.72%   |
| 6.0.10-0-edge  | 1        | 1.72%   |
| 5.8.0          | 1        | 1.72%   |
| 5.4.84-0-lts   | 1        | 1.72%   |
| 5.4.6-0-lts    | 1        | 1.72%   |
| 5.4.58-0-lts   | 1        | 1.72%   |
| 5.4.57-0-lts   | 1        | 1.72%   |
| 5.18.0-0-asahi | 1        | 1.72%   |
| 5.17.9-0-edge  | 1        | 1.72%   |
| 5.17.3-0-edge  | 1        | 1.72%   |
| 5.15.98-0-lts  | 1        | 1.72%   |
| 5.15.87-0-lts  | 1        | 1.72%   |
| 5.15.86-0-lts  | 1        | 1.72%   |
| 5.15.83-0-lts  | 1        | 1.72%   |
| 5.15.80        | 1        | 1.72%   |
| 5.15.74-0-lts  | 1        | 1.72%   |
| 5.15.70-0-lts  | 1        | 1.72%   |
| 5.15.64-1-pve  | 1        | 1.72%   |
| 5.15.57-0-lts  | 1        | 1.72%   |
| 5.15.46-1-lts  | 1        | 1.72%   |
| 5.15.40-0-lts  | 1        | 1.72%   |
| 5.15.38-0-lts  | 1        | 1.72%   |
| 5.15.32-0-lts  | 1        | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.43  | 5        | 8.62%   |
| 6.1.57  | 3        | 5.17%   |
| 6.1.51  | 2        | 3.45%   |
| 5.15.60 | 2        | 3.45%   |
| 6.6.8   | 1        | 1.72%   |
| 6.6.7   | 1        | 1.72%   |
| 6.6.6   | 1        | 1.72%   |
| 6.6.1   | 1        | 1.72%   |
| 6.3.3   | 1        | 1.72%   |
| 6.1.64  | 1        | 1.72%   |
| 6.1.61  | 1        | 1.72%   |
| 6.1.60  | 1        | 1.72%   |
| 6.1.55  | 1        | 1.72%   |
| 6.1.54  | 1        | 1.72%   |
| 6.1.36  | 1        | 1.72%   |
| 6.1.34  | 1        | 1.72%   |
| 6.1.30  | 1        | 1.72%   |
| 6.1.28  | 1        | 1.72%   |
| 6.0.10  | 1        | 1.72%   |
| 5.8.0   | 1        | 1.72%   |
| 5.4.84  | 1        | 1.72%   |
| 5.4.6   | 1        | 1.72%   |
| 5.4.58  | 1        | 1.72%   |
| 5.4.57  | 1        | 1.72%   |
| 5.18.0  | 1        | 1.72%   |
| 5.17.9  | 1        | 1.72%   |
| 5.17.3  | 1        | 1.72%   |
| 5.15.98 | 1        | 1.72%   |
| 5.15.87 | 1        | 1.72%   |
| 5.15.86 | 1        | 1.72%   |
| 5.15.83 | 1        | 1.72%   |
| 5.15.80 | 1        | 1.72%   |
| 5.15.74 | 1        | 1.72%   |
| 5.15.70 | 1        | 1.72%   |
| 5.15.64 | 1        | 1.72%   |
| 5.15.57 | 1        | 1.72%   |
| 5.15.46 | 1        | 1.72%   |
| 5.15.40 | 1        | 1.72%   |
| 5.15.38 | 1        | 1.72%   |
| 5.15.32 | 1        | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 15       | 26.79%  |
| 6.1     | 13       | 23.21%  |
| 5.4     | 9        | 16.07%  |
| 5.10    | 5        | 8.93%   |
| 6.6     | 4        | 7.14%   |
| 5.17    | 2        | 3.57%   |
| 6.3     | 1        | 1.79%   |
| 6.0     | 1        | 1.79%   |
| 5.8     | 1        | 1.79%   |
| 5.18    | 1        | 1.79%   |
| 4.4     | 1        | 1.79%   |
| 4.20    | 1        | 1.79%   |
| 4.14    | 1        | 1.79%   |
| 3.10    | 1        | 1.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 48       | 87.27%  |
| i686    | 6        | 10.91%  |
| aarch64 | 1        | 1.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 44       | 80%     |
| XFCE    | 5        | 9.09%   |
| GNOME   | 3        | 5.45%   |
| sway    | 1        | 1.82%   |
| KDE5    | 1        | 1.82%   |
| i3      | 1        | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 37       | 66.07%  |
| X11     | 15       | 26.79%  |
| Wayland | 4        | 7.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 49       | 89.09%  |
| LightDM | 5        | 9.09%   |
| SDDM    | 1        | 1.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 34       | 61.82%  |
| Unknown | 18       | 32.73%  |
| pt_BR   | 1        | 1.82%   |
| en_US   | 1        | 1.82%   |
| en_GB   | 1        | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 35       | 63.64%  |
| EFI  | 20       | 36.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 45       | 81.82%  |
| Btrfs   | 4        | 7.27%   |
| Tmpfs   | 2        | 3.64%   |
| Zfs     | 1        | 1.82%   |
| Overlay | 1        | 1.82%   |
| Fake    | 1        | 1.82%   |
| Unknown | 1        | 1.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 34       | 60.71%  |
| GPT     | 15       | 26.79%  |
| MBR     | 7        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 81.82%  |
| Yes       | 10       | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 90.91%  |
| Yes       | 5        | 9.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 8        | 14.55%  |
| ASRock              | 8        | 14.55%  |
| Gigabyte Technology | 7        | 12.73%  |
| Dell                | 7        | 12.73%  |
| Intel               | 3        | 5.45%   |
| Hewlett-Packard     | 3        | 5.45%   |
| Unknown             | 3        | 5.45%   |
| MSI                 | 2        | 3.64%   |
| Lenovo              | 2        | 3.64%   |
| Fujitsu             | 2        | 3.64%   |
| ZOTAC               | 1        | 1.82%   |
| VIA Technologies    | 1        | 1.82%   |
| UGREEN              | 1        | 1.82%   |
| Shuttle             | 1        | 1.82%   |
| Inventec            | 1        | 1.82%   |
| Gateway             | 1        | 1.82%   |
| eMachines           | 1        | 1.82%   |
| ECS                 | 1        | 1.82%   |
| Compaq              | 1        | 1.82%   |
| Acer                | 1        | 1.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 4        | 7.27%   |
| ASUS All Series                    | 3        | 5.45%   |
| Gigabyte Z490I AORUS ULTRA         | 2        | 3.64%   |
| VIA KM266APro-835                  | 1        | 1.82%   |
| UGREEN DX4600                      | 1        | 1.82%   |
| Shuttle DS81D                      | 1        | 1.82%   |
| MSI MS-7C82                        | 1        | 1.82%   |
| MSI MS-7877                        | 1        | 1.82%   |
| Lenovo ThinkCentre M93p 10AB0016US | 1        | 1.82%   |
| Lenovo H535 10117                  | 1        | 1.82%   |
| Inventec D CLASS                   | 1        | 1.82%   |
| Intel DQ67SW                       | 1        | 1.82%   |
| Intel DH61BF AAG81311-101          | 1        | 1.82%   |
| Intel D525MW AAE93082-401          | 1        | 1.82%   |
| HP ProLiant MicroServer Gen8       | 1        | 1.82%   |
| HP EliteDesk 800 G4 DM 35W         | 1        | 1.82%   |
| HP Compaq 4000 Pro SFF PC          | 1        | 1.82%   |
| Gigabyte Z170X-UD5                 | 1        | 1.82%   |
| Gigabyte X570S AERO G              | 1        | 1.82%   |
| Gigabyte X570 I AORUS PRO WIFI     | 1        | 1.82%   |
| Gigabyte B550 AORUS ELITE V2       | 1        | 1.82%   |
| Gigabyte 945GCM-S2C                | 1        | 1.82%   |
| Gateway SX2185                     | 1        | 1.82%   |
| Fujitsu PRIMERGY TX100 S2          | 1        | 1.82%   |
| Fujitsu FujitsuTP7000              | 1        | 1.82%   |
| eMachines EL1352G                  | 1        | 1.82%   |
| ECS M789CG                         | 1        | 1.82%   |
| Dell OptiPlex 755                  | 1        | 1.82%   |
| Dell OptiPlex 7040                 | 1        | 1.82%   |
| Dell OptiPlex 5000                 | 1        | 1.82%   |
| Dell OptiPlex 3020M                | 1        | 1.82%   |
| Dell OptiPlex 3010                 | 1        | 1.82%   |
| Dell Inspiron 530s                 | 1        | 1.82%   |
| Dell Inspiron 3647                 | 1        | 1.82%   |
| Compaq Deskpro                     | 1        | 1.82%   |
| ASUS Z170-E                        | 1        | 1.82%   |
| ASUS TS10                          | 1        | 1.82%   |
| ASUS PRIME H370M-PLUS              | 1        | 1.82%   |
| ASUS PRIME B360M-C                 | 1        | 1.82%   |
| ASUS P8H67-V                       | 1        | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 5        | 9.09%   |
| Unknown               | 4        | 7.27%   |
| ASUS All              | 3        | 5.45%   |
| Gigabyte Z490I        | 2        | 3.64%   |
| Dell Inspiron         | 2        | 3.64%   |
| ASUS PRIME            | 2        | 3.64%   |
| VIA KM266APro-835     | 1        | 1.82%   |
| UGREEN DX4600         | 1        | 1.82%   |
| Shuttle DS81D         | 1        | 1.82%   |
| MSI MS-7C82           | 1        | 1.82%   |
| MSI MS-7877           | 1        | 1.82%   |
| Lenovo ThinkCentre    | 1        | 1.82%   |
| Lenovo H535           | 1        | 1.82%   |
| Inventec D            | 1        | 1.82%   |
| Intel DQ67SW          | 1        | 1.82%   |
| Intel DH61BF          | 1        | 1.82%   |
| Intel D525MW          | 1        | 1.82%   |
| HP ProLiant           | 1        | 1.82%   |
| HP EliteDesk          | 1        | 1.82%   |
| HP Compaq             | 1        | 1.82%   |
| Gigabyte Z170X-UD5    | 1        | 1.82%   |
| Gigabyte X570S        | 1        | 1.82%   |
| Gigabyte X570         | 1        | 1.82%   |
| Gigabyte B550         | 1        | 1.82%   |
| Gigabyte 945GCM-S2C   | 1        | 1.82%   |
| Gateway SX2185        | 1        | 1.82%   |
| Fujitsu PRIMERGY      | 1        | 1.82%   |
| Fujitsu FujitsuTP7000 | 1        | 1.82%   |
| eMachines EL1352G     | 1        | 1.82%   |
| ECS M789CG            | 1        | 1.82%   |
| Compaq Deskpro        | 1        | 1.82%   |
| ASUS Z170-E           | 1        | 1.82%   |
| ASUS TS10             | 1        | 1.82%   |
| ASUS P8H67-V          | 1        | 1.82%   |
| ASRock Z790M-ITX      | 1        | 1.82%   |
| ASRock X470           | 1        | 1.82%   |
| ASRock Q1900B-ITX     | 1        | 1.82%   |
| ASRock J3455M         | 1        | 1.82%   |
| ASRock H81M           | 1        | 1.82%   |
| ASRock H55M-LE        | 1        | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 8        | 14.55%  |
| 2013    | 7        | 12.73%  |
| 2020    | 5        | 9.09%   |
| 2018    | 5        | 9.09%   |
| 2010    | 5        | 9.09%   |
| 2016    | 4        | 7.27%   |
| 2012    | 3        | 5.45%   |
| 2011    | 3        | 5.45%   |
| 2007    | 3        | 5.45%   |
| 2022    | 2        | 3.64%   |
| 2001    | 2        | 3.64%   |
| Unknown | 2        | 3.64%   |
| 2023    | 1        | 1.82%   |
| 2019    | 1        | 1.82%   |
| 2017    | 1        | 1.82%   |
| 2015    | 1        | 1.82%   |
| 2009    | 1        | 1.82%   |
| 2004    | 1        | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 55       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 55       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 55       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 15       | 26.32%  |
| 16.01-24.0  | 11       | 19.3%   |
| 4.01-8.0    | 7        | 12.28%  |
| 32.01-64.0  | 6        | 10.53%  |
| 8.01-16.0   | 6        | 10.53%  |
| 0.51-1.0    | 3        | 5.26%   |
| 0.01-0.5    | 3        | 5.26%   |
| 2.01-3.0    | 2        | 3.51%   |
| 64.01-256.0 | 2        | 3.51%   |
| 1.01-2.0    | 2        | 3.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 15       | 26.79%  |
| 1.01-2.0  | 14       | 25%     |
| 0.51-1.0  | 11       | 19.64%  |
| 3.01-4.0  | 4        | 7.14%   |
| 2.01-3.0  | 4        | 7.14%   |
| 4.01-8.0  | 3        | 5.36%   |
| 0         | 2        | 3.57%   |
| Unknown   | 2        | 3.57%   |
| 8.01-16.0 | 1        | 1.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 41.82%  |
| 2      | 13       | 23.64%  |
| 3      | 9        | 16.36%  |
| 4      | 7        | 12.73%  |
| 12     | 1        | 1.82%   |
| 5      | 1        | 1.82%   |
| 0      | 1        | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 85.45%  |
| Yes       | 8        | 14.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 53       | 96.36%  |
| No        | 2        | 3.64%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 66.07%  |
| Yes       | 19       | 33.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 76.36%  |
| Yes       | 13       | 23.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 13       | 23.64%  |
| Germany     | 7        | 12.73%  |
| Russia      | 4        | 7.27%   |
| Norway      | 3        | 5.45%   |
| UK          | 2        | 3.64%   |
| Sweden      | 2        | 3.64%   |
| Finland     | 2        | 3.64%   |
| Brazil      | 2        | 3.64%   |
| Argentina   | 2        | 3.64%   |
| Vietnam     | 1        | 1.82%   |
| Ukraine     | 1        | 1.82%   |
| Switzerland | 1        | 1.82%   |
| Spain       | 1        | 1.82%   |
| Romania     | 1        | 1.82%   |
| Portugal    | 1        | 1.82%   |
| Poland      | 1        | 1.82%   |
| Pakistan    | 1        | 1.82%   |
| Netherlands | 1        | 1.82%   |
| Mexico      | 1        | 1.82%   |
| Ireland     | 1        | 1.82%   |
| Indonesia   | 1        | 1.82%   |
| Guatemala   | 1        | 1.82%   |
| China       | 1        | 1.82%   |
| Canada      | 1        | 1.82%   |
| Austria     | 1        | 1.82%   |
| Australia   | 1        | 1.82%   |
| Algeria     | 1        | 1.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Springfield         | 4        | 7.27%   |
| St Petersburg       | 3        | 5.45%   |
| Manitowoc           | 2        | 3.64%   |
| Harrisonburg        | 2        | 3.64%   |
| Frankfurt am Main   | 2        | 3.64%   |
| As                  | 2        | 3.64%   |
| Zurich              | 1        | 1.82%   |
| Tuusula             | 1        | 1.82%   |
| Traunstein          | 1        | 1.82%   |
| Tinh Binh Duong     | 1        | 1.82%   |
| Stuttgart           | 1        | 1.82%   |
| Stockholm           | 1        | 1.82%   |
| Somerset            | 1        | 1.82%   |
| Ski                 | 1        | 1.82%   |
| Salzburg            | 1        | 1.82%   |
| Redwood City        | 1        | 1.82%   |
| Penza               | 1        | 1.82%   |
| Oberhausen          | 1        | 1.82%   |
| Nussdorf am Inn     | 1        | 1.82%   |
| Noblesville         | 1        | 1.82%   |
| Lisbon              | 1        | 1.82%   |
| Lahore              | 1        | 1.82%   |
| Kharkiv             | 1        | 1.82%   |
| Jember              | 1        | 1.82%   |
| Helsinki            | 1        | 1.82%   |
| Hangzhou            | 1        | 1.82%   |
| Hamburg             | 1        | 1.82%   |
| Guatemala City      | 1        | 1.82%   |
| Gothenburg          | 1        | 1.82%   |
| Gorredijk           | 1        | 1.82%   |
| Glasgow             | 1        | 1.82%   |
| General San Martin  | 1        | 1.82%   |
| Durham              | 1        | 1.82%   |
| Dublin              | 1        | 1.82%   |
| Czarna Białostocka | 1        | 1.82%   |
| Chihuahua City      | 1        | 1.82%   |
| Chicago             | 1        | 1.82%   |
| Buenos Aires        | 1        | 1.82%   |
| Brasov              | 1        | 1.82%   |
| Bradford            | 1        | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 30     | 18.68%  |
| WDC                 | 14       | 19     | 15.38%  |
| Seagate             | 14       | 30     | 15.38%  |
| Toshiba             | 6        | 6      | 6.59%   |
| A-DATA Technology   | 5        | 6      | 5.49%   |
| SanDisk             | 4        | 7      | 4.4%    |
| Hitachi             | 4        | 4      | 4.4%    |
| HGST                | 4        | 4      | 4.4%    |
| Crucial             | 4        | 7      | 4.4%    |
| Kingston            | 3        | 3      | 3.3%    |
| Unknown             | 2        | 2      | 2.2%    |
| SK hynix            | 2        | 2      | 2.2%    |
| Intel               | 2        | 3      | 2.2%    |
| Transcend           | 1        | 1      | 1.1%    |
| SPCC                | 1        | 1      | 1.1%    |
| Phison Electronics  | 1        | 1      | 1.1%    |
| Maxtor              | 1        | 1      | 1.1%    |
| LITEON              | 1        | 1      | 1.1%    |
| Lexar               | 1        | 1      | 1.1%    |
| KIOXIA              | 1        | 1      | 1.1%    |
| Kingmax             | 1        | 1      | 1.1%    |
| Intenso             | 1        | 1      | 1.1%    |
| Apple               | 1        | 3      | 1.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 3        | 2.83%   |
| Seagate ST380815AS 80GB                             | 2        | 1.89%   |
| Samsung SSD 960 EVO 500GB                           | 2        | 1.89%   |
| Samsung SSD 870 QVO 1TB                             | 2        | 1.89%   |
| Samsung SSD 870 EVO 1TB                             | 2        | 1.89%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1        | 0.94%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                    | 1        | 0.94%   |
| WDC WDS250G2B0B 250GB SSD                           | 1        | 0.94%   |
| WDC WD800AAJS-00 80GB                               | 1        | 0.94%   |
| WDC WD7500BPKT-80PK4T0 752GB                        | 1        | 0.94%   |
| WDC WD5000AZRX-00A8LB0 500GB                        | 1        | 0.94%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 1        | 0.94%   |
| WDC WD40EFZX-68AWUN0 4TB                            | 1        | 0.94%   |
| WDC WD3200AAKX-0 320GB                              | 1        | 0.94%   |
| WDC WD20EZRZ-00Z 2TB                                | 1        | 0.94%   |
| WDC WD1600JS-60NCB1 160GB                           | 1        | 0.94%   |
| WDC WD1600BEVT-2 160GB                              | 1        | 0.94%   |
| WDC WD140EDGZ-11B2DA2 14TB                          | 1        | 0.94%   |
| WDC WD120EFBX-68B0EN0 12TB                          | 1        | 0.94%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1        | 0.94%   |
| WDC WD10EZEX-75WN4A1 1TB                            | 1        | 0.94%   |
| WDC WD10EZEX-21M2NA0 1TB                            | 1        | 0.94%   |
| Unknown SD/MMC/MS PRO 512GB                         | 1        | 0.94%   |
| Unknown MMC Card  32GB                              | 1        | 0.94%   |
| Transcend SSD 1GB                                   | 1        | 0.94%   |
| Toshiba MQ04ABF100 1TB                              | 1        | 0.94%   |
| Toshiba MQ01ABF050 500GB                            | 1        | 0.94%   |
| Toshiba MK3252GS 320GB                              | 1        | 0.94%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD             | 1        | 0.94%   |
| Toshiba HDWD130 3TB                                 | 1        | 0.94%   |
| Toshiba DT01ACA2 2TB                                | 1        | 0.94%   |
| SPCC Solid State Disk 120GB                         | 1        | 0.94%   |
| SK hynix SC300 M.2 2280 256 256GB SSD               | 1        | 0.94%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1        | 0.94%   |
| Seagate ST980310AS 80GB                             | 1        | 0.94%   |
| Seagate ST500LT012-1DG14 500GB                      | 1        | 0.94%   |
| Seagate ST500LM021-1KJ152 500GB                     | 1        | 0.94%   |
| Seagate ST5000LM000-2AN170 5TB                      | 1        | 0.94%   |
| Seagate ST4000VN008-2DR1 4TB                        | 1        | 0.94%   |
| Seagate ST4000NC000-1FR1 4TB                        | 1        | 0.94%   |

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
| Samsung Electronics | 9        | 12     | 26.47%  |
| Crucial             | 4        | 7      | 11.76%  |
| A-DATA Technology   | 4        | 4      | 11.76%  |
| Kingston            | 3        | 3      | 8.82%   |
| WDC                 | 2        | 3      | 5.88%   |
| SanDisk             | 2        | 3      | 5.88%   |
| Intel               | 2        | 3      | 5.88%   |
| Transcend           | 1        | 1      | 2.94%   |
| Toshiba             | 1        | 1      | 2.94%   |
| SPCC                | 1        | 1      | 2.94%   |
| SK hynix            | 1        | 1      | 2.94%   |
| LITEON              | 1        | 1      | 2.94%   |
| Lexar               | 1        | 1      | 2.94%   |
| Kingmax             | 1        | 1      | 2.94%   |
| Intenso             | 1        | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 34       | 67     | 43.04%  |
| SSD  | 29       | 43     | 36.71%  |
| NVMe | 15       | 24     | 18.99%  |
| MMC  | 1        | 1      | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 48       | 107    | 72.73%  |
| NVMe | 15       | 24     | 22.73%  |
| SAS  | 2        | 3      | 3.03%   |
| MMC  | 1        | 1      | 1.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 42       | 64     | 65.63%  |
| 0.51-1.0   | 10       | 17     | 15.63%  |
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
| Unknown        | 15       | 27.27%  |
| 101-250        | 10       | 18.18%  |
| 1-20           | 6        | 10.91%  |
| 251-500        | 5        | 9.09%   |
| More than 3000 | 4        | 7.27%   |
| 21-50          | 4        | 7.27%   |
| 501-1000       | 4        | 7.27%   |
| 51-100         | 3        | 5.45%   |
| 2001-3000      | 2        | 3.64%   |
| 1001-2000      | 2        | 3.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 23       | 41.82%  |
| Unknown        | 15       | 27.27%  |
| 21-50          | 6        | 10.91%  |
| 251-500        | 5        | 9.09%   |
| 1001-2000      | 2        | 3.64%   |
| 51-100         | 2        | 3.64%   |
| More than 3000 | 1        | 1.82%   |
| 2001-3000      | 1        | 1.82%   |

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
| Works    | 37       | 86     | 59.68%  |
| Detected | 15       | 37     | 24.19%  |
| Malfunc  | 10       | 12     | 16.13%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 41       | 53.95%  |
| Samsung Electronics       | 8        | 10.53%  |
| AMD                       | 8        | 10.53%  |
| ASMedia Technology        | 3        | 3.95%   |
| VIA Technologies          | 2        | 2.63%   |
| SanDisk                   | 2        | 2.63%   |
| Marvell Technology Group  | 2        | 2.63%   |
| LSI Logic / Symbios Logic | 2        | 2.63%   |
| Adaptec                   | 2        | 2.63%   |
| SK hynix                  | 1        | 1.32%   |
| Promise Technology        | 1        | 1.32%   |
| Phison Electronics        | 1        | 1.32%   |
| Nvidia                    | 1        | 1.32%   |
| KIOXIA                    | 1        | 1.32%   |
| ADATA Technology          | 1        | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6        | 6.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5        | 5.56%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5        | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4        | 4.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3        | 3.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 3        | 3.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3        | 3.33%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3        | 3.33%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 2        | 2.22%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2        | 2.22%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 2        | 2.22%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]          | 2        | 2.22%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2        | 2.22%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2        | 2.22%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                       | 2        | 2.22%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                                 | 2        | 2.22%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1        | 1.11%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                       | 1        | 1.11%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1        | 1.11%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 1        | 1.11%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1        | 1.11%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                      | 1        | 1.11%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1        | 1.11%   |
| Promise PDC42819 [FastTrak TX2650/TX4650]                                        | 1        | 1.11%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 1        | 1.11%   |
| Nvidia MCP61 SATA Controller                                                     | 1        | 1.11%   |
| Nvidia MCP61 IDE                                                                 | 1        | 1.11%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1        | 1.11%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                       | 1        | 1.11%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1        | 1.11%   |
| Intel SATA Controller [RAID mode]                                                | 1        | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1        | 1.11%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1        | 1.11%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1        | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 1.11%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 1        | 1.11%   |
| Intel 82Q35 Express PT IDER Controller                                           | 1        | 1.11%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1        | 1.11%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1        | 1.11%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 40       | 53.33%  |
| NVMe | 13       | 17.33%  |
| IDE  | 13       | 17.33%  |
| RAID | 7        | 9.33%   |
| SAS  | 2        | 2.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 42       | 76.36%  |
| AMD          | 10       | 18.18%  |
| iSH          | 1        | 1.82%   |
| CentaurHauls | 1        | 1.82%   |
| Unknown      | 1        | 1.82%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i9-10900 CPU @ 2.80GHz      | 2        | 3.64%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2        | 3.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 3.64%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 2        | 3.64%   |
| Intel Celeron CPU J1900 @ 1.99GHz      | 2        | 3.64%   |
| Intel Atom CPU D525 @ 1.80GHz          | 2        | 3.64%   |
| iSH Processor                          | 1        | 1.82%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1        | 1.82%   |
| Intel Pentium III (Coppermine)         | 1        | 1.82%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1        | 1.82%   |
| Intel Pentium CPU E5700 @ 3.00GHz      | 1        | 1.82%   |
| Intel Core i7-8700T CPU @ 2.40GHz      | 1        | 1.82%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 1.82%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 1        | 1.82%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1        | 1.82%   |
| Intel Core i5-6600K CPU @ 3.50GHz      | 1        | 1.82%   |
| Intel Core i5-6500T CPU @ 2.50GHz      | 1        | 1.82%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 1        | 1.82%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 1        | 1.82%   |
| Intel Core i5-4570T CPU @ 2.90GHz      | 1        | 1.82%   |
| Intel Core i5-3450 CPU @ 3.10GHz       | 1        | 1.82%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 1.82%   |
| Intel Core i3-3240 CPU @ 3.40GHz       | 1        | 1.82%   |
| Intel Core i3-3220T CPU @ 2.80GHz      | 1        | 1.82%   |
| Intel Core i3-2100 CPU @ 3.10GHz       | 1        | 1.82%   |
| Intel Core i3 CPU 540 @ 3.07GHz        | 1        | 1.82%   |
| Intel Core 2 CPU 4300 @ 1.80GHz        | 1        | 1.82%   |
| Intel Celeron N5105 @ 2.00GHz          | 1        | 1.82%   |
| Intel Celeron M processor 1.00GHz      | 1        | 1.82%   |
| Intel Celeron CPU N3150 @ 1.60GHz      | 1        | 1.82%   |
| Intel Celeron CPU J3455 @ 1.50GHz      | 1        | 1.82%   |
| Intel Celeron CPU J1800 @ 2.41GHz      | 1        | 1.82%   |
| Intel Celeron CPU G1850 @ 2.90GHz      | 1        | 1.82%   |
| Intel Celeron CPU E3400 @ 2.60GHz      | 1        | 1.82%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz      | 1        | 1.82%   |
| Intel 13th Gen Core i9-13900           | 1        | 1.82%   |
| Intel 12th Gen Core i7-12700T          | 1        | 1.82%   |
| CentaurHauls VIA Samuel 2              | 1        | 1.82%   |
| AMD Sempron 145 Processor              | 1        | 1.82%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 1        | 1.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 10       | 18.18%  |
| Intel Celeron      | 8        | 14.55%  |
| Other              | 6        | 10.91%  |
| Intel Core i3      | 6        | 10.91%  |
| Intel Core i7      | 5        | 9.09%   |
| Intel Atom         | 3        | 5.45%   |
| AMD Ryzen 7        | 3        | 5.45%   |
| Intel Core i9      | 2        | 3.64%   |
| Intel Xeon         | 1        | 1.82%   |
| Intel Pentium III  | 1        | 1.82%   |
| Intel Pentium Dual | 1        | 1.82%   |
| Intel Pentium      | 1        | 1.82%   |
| Intel Core 2       | 1        | 1.82%   |
| Intel Celeron M    | 1        | 1.82%   |
| AMD Sempron        | 1        | 1.82%   |
| AMD Ryzen 9        | 1        | 1.82%   |
| AMD G              | 1        | 1.82%   |
| AMD FX             | 1        | 1.82%   |
| AMD E1             | 1        | 1.82%   |
| AMD A8             | 1        | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 19       | 34.55%  |
| 2       | 17       | 30.91%  |
| 1       | 6        | 10.91%  |
| 8       | 4        | 7.27%   |
| 6       | 3        | 5.45%   |
| 12      | 2        | 3.64%   |
| 10      | 2        | 3.64%   |
| 24      | 1        | 1.82%   |
| Unknown | 1        | 1.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 53       | 96.36%  |
| 0       | 1        | 1.82%   |
| Unknown | 1        | 1.82%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 32       | 58.18%  |
| 2       | 22       | 40%     |
| Unknown | 1        | 1.82%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 28       | 50.91%  |
| 32-bit, 64-bit | 24       | 43.64%  |
| 32-bit         | 2        | 3.64%   |
| 64-bit         | 1        | 1.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 51.79%  |
| 0x306c3    | 4        | 7.14%   |
| 0x906ea    | 2        | 3.57%   |
| 0x306a9    | 2        | 3.57%   |
| 0xb0671    | 1        | 1.79%   |
| 0xa0655    | 1        | 1.79%   |
| 0x90672    | 1        | 1.79%   |
| 0x6fd      | 1        | 1.79%   |
| 0x6f2      | 1        | 1.79%   |
| 0x6d8      | 1        | 1.79%   |
| 0x68a      | 1        | 1.79%   |
| 0x506c9    | 1        | 1.79%   |
| 0x406c4    | 1        | 1.79%   |
| 0x30678    | 1        | 1.79%   |
| 0x20655    | 1        | 1.79%   |
| 0x106e5    | 1        | 1.79%   |
| 0x1067a    | 1        | 1.79%   |
| 0x0a20120e | 1        | 1.79%   |
| 0x08701021 | 1        | 1.79%   |
| 0x0800820d | 1        | 1.79%   |
| 0x06000817 | 1        | 1.79%   |
| 0x05000101 | 1        | 1.79%   |
| 0x010000b6 | 1        | 1.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 8        | 14.55%  |
| Silvermont       | 5        | 9.09%   |
| Unknown          | 4        | 7.27%   |
| Skylake          | 3        | 5.45%   |
| SandyBridge      | 3        | 5.45%   |
| KabyLake         | 3        | 5.45%   |
| IvyBridge        | 3        | 5.45%   |
| CometLake        | 3        | 5.45%   |
| Zen 3            | 2        | 3.64%   |
| Piledriver       | 2        | 3.64%   |
| Penryn           | 2        | 3.64%   |
| P6               | 2        | 3.64%   |
| Core             | 2        | 3.64%   |
| Bonnell          | 2        | 3.64%   |
| Alderlake Hybrid | 2        | 3.64%   |
| Zen+             | 1        | 1.82%   |
| Zen 2            | 1        | 1.82%   |
| Westmere         | 1        | 1.82%   |
| Nehalem          | 1        | 1.82%   |
| K6               | 1        | 1.82%   |
| K10              | 1        | 1.82%   |
| Jaguar           | 1        | 1.82%   |
| Goldmont         | 1        | 1.82%   |
| Bobcat           | 1        | 1.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 35       | 62.5%   |
| AMD                        | 11       | 19.64%  |
| Nvidia                     | 6        | 10.71%  |
| VIA Technologies           | 2        | 3.57%   |
| S3 Graphics                | 1        | 1.79%   |
| Matrox Electronics Systems | 1        | 1.79%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5        | 8.93%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 5.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 5.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 5.36%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 5.36%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 3.57%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 3.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 3.57%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.57%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 3.57%   |
| VIA Technologies VT8623 [Apollo CLE266] integrated CastleRock graphics                   | 1        | 1.79%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1        | 1.79%   |
| S3 Graphics Savage 4                                                                     | 1        | 1.79%   |
| Nvidia GT218 [ION]                                                                       | 1        | 1.79%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 1.79%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.79%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1        | 1.79%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1        | 1.79%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 1.79%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.79%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 1        | 1.79%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 1.79%   |
| Intel HD Graphics 530                                                                    | 1        | 1.79%   |
| Intel HD Graphics 500                                                                    | 1        | 1.79%   |
| Intel DG2 [Arc A770]                                                                     | 1        | 1.79%   |
| Intel DG2 [Arc A750]                                                                     | 1        | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 1.79%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 1.79%   |
| Intel AlderLake-S GT1                                                                    | 1        | 1.79%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 1.79%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.79%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1        | 1.79%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.79%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1        | 1.79%   |
| AMD Trinity [Radeon HD 7560D]                                                            | 1        | 1.79%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                                   | 1        | 1.79%   |
| AMD Rage 3 [Rage XL PCI]                                                                 | 1        | 1.79%   |
| AMD ES1000                                                                               | 1        | 1.79%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                                            | 1        | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 33       | 60%     |
| 1 x AMD         | 10       | 18.18%  |
| 1 x Nvidia      | 5        | 9.09%   |
| Other           | 2        | 3.64%   |
| 2 x Intel       | 1        | 1.82%   |
| 1 x VIA         | 1        | 1.82%   |
| 1 x S3 Graphics | 1        | 1.82%   |
| 1 x Matrox      | 1        | 1.82%   |
| AMD + VIA       | 1        | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 42       | 76.36%  |
| Unknown | 13       | 23.64%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 43       | 78.18%  |
| 0.01-0.5   | 4        | 7.27%   |
| 7.01-8.0   | 3        | 5.45%   |
| 0.51-1.0   | 2        | 3.64%   |
| 3.01-4.0   | 1        | 1.82%   |
| 1.01-2.0   | 1        | 1.82%   |
| 8.01-16.0  | 1        | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 8        | 20.51%  |
| Samsung Electronics | 6        | 15.38%  |
| Goldstar            | 5        | 12.82%  |
| AOC                 | 5        | 12.82%  |
| BenQ                | 4        | 10.26%  |
| Belinea             | 2        | 5.13%   |
| Acer                | 2        | 5.13%   |
| ViewSonic           | 1        | 2.56%   |
| Philips             | 1        | 2.56%   |
| Mi                  | 1        | 2.56%   |
| Huion               | 1        | 2.56%   |
| Hewlett-Packard     | 1        | 2.56%   |
| Elo Touch           | 1        | 2.56%   |
| CTC                 | 1        | 2.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch     | 3        | 7.69%   |
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                     | 3        | 7.69%   |
| Belinea B101555 MAX05DF 1024x768 304x228mm 15.0-inch                 | 2        | 5.13%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch             | 1        | 2.56%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch | 1        | 2.56%   |
| Samsung Electronics S27A950D SAM079E 1920x1080 598x336mm 27.0-inch   | 1        | 2.56%   |
| Samsung Electronics LS24AG30x SAM7179 1920x1080 527x296mm 23.8-inch  | 1        | 2.56%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch              | 1        | 2.56%   |
| Mi Monitor XMI2701 2560x1440 597x336mm 27.0-inch                     | 1        | 2.56%   |
| Huion GT-192 HAT1920 1920x1080 432x243mm 19.5-inch                   | 1        | 2.56%   |
| Hewlett-Packard LA1751 HWP2858 1280x1024 340x270mm 17.1-inch         | 1        | 2.56%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 1        | 2.56%   |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch             | 1        | 2.56%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 2.56%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 1        | 2.56%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                | 1        | 2.56%   |
| Elo Touch ET1717L ELO1717 1280x1024 338x270mm 17.0-inch              | 1        | 2.56%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                   | 1        | 2.56%   |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                    | 1        | 2.56%   |
| Dell E1911 DELF037 1440x900 408x255mm 18.9-inch                      | 1        | 2.56%   |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                    | 1        | 2.56%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                    | 1        | 2.56%   |
| CTC KD02909-8770A CTC0770 1024x768 304x228mm 15.0-inch               | 1        | 2.56%   |
| BenQ ZOWIE RL LCD BNQ7F4F 1920x1080 531x299mm 24.0-inch              | 1        | 2.56%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                   | 1        | 2.56%   |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                    | 1        | 2.56%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                    | 1        | 2.56%   |
| AOC 912Vwa AOC1912 1440x900 408x255mm 18.9-inch                      | 1        | 2.56%   |
| AOC 718Swsg-1 AOCC750 1440x900 367x230mm 17.1-inch                   | 1        | 2.56%   |
| AOC 2476WM AOC2476 1920x1080 521x293mm 23.5-inch                     | 1        | 2.56%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                     | 1        | 2.56%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1        | 2.56%   |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                    | 1        | 2.56%   |
| Acer S236HL ACR0387 1920x1080 510x286mm 23.0-inch                    | 1        | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 32.43%  |
| 1680x1050 (WSXGA+) | 4        | 10.81%  |
| 1280x1024 (SXGA)   | 4        | 10.81%  |
| 3840x2160 (4K)     | 3        | 8.11%   |
| 3440x1440          | 3        | 8.11%   |
| 2560x1440 (QHD)    | 3        | 8.11%   |
| 1024x768 (XGA)     | 3        | 8.11%   |
| 1440x900 (WXGA+)   | 2        | 5.41%   |
| 1366x768 (WXGA)    | 1        | 2.7%    |
| 1360x768           | 1        | 2.7%    |
| 1280x960           | 1        | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 6        | 15.79%  |
| 23     | 4        | 10.53%  |
| 20     | 4        | 10.53%  |
| 19     | 4        | 10.53%  |
| 17     | 4        | 10.53%  |
| 34     | 3        | 7.89%   |
| 24     | 3        | 7.89%   |
| 21     | 3        | 7.89%   |
| 18     | 3        | 7.89%   |
| 15     | 3        | 7.89%   |
| 31     | 1        | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 34.21%  |
| 401-500     | 12       | 31.58%  |
| 301-350     | 6        | 15.79%  |
| 701-800     | 3        | 7.89%   |
| 351-400     | 3        | 7.89%   |
| 601-700     | 1        | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 17       | 48.57%  |
| 16/10 | 7        | 20%     |
| 5/4   | 4        | 11.43%  |
| 4/3   | 3        | 8.57%   |
| 21/9  | 3        | 8.57%   |
| 6/5   | 1        | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 10       | 26.32%  |
| 201-250        | 9        | 23.68%  |
| 301-350        | 6        | 15.79%  |
| 141-150        | 5        | 13.16%  |
| 351-500        | 4        | 10.53%  |
| 101-110        | 3        | 7.89%   |
| 131-140        | 1        | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 66.67%  |
| 101-120 | 7        | 19.44%  |
| 1-50    | 3        | 8.33%   |
| 161-240 | 1        | 2.78%   |
| 121-160 | 1        | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 57.14%  |
| 0     | 20       | 35.71%  |
| 2     | 3        | 5.36%   |
| 4     | 1        | 1.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 28       | 37.33%  |
| Intel                           | 25       | 33.33%  |
| Qualcomm Atheros                | 5        | 6.67%   |
| Broadcom                        | 5        | 6.67%   |
| Xiaomi                          | 2        | 2.67%   |
| VIA Technologies                | 2        | 2.67%   |
| T & A Mobile Phones             | 1        | 1.33%   |
| Qualcomm Atheros Communications | 1        | 1.33%   |
| Qualcomm                        | 1        | 1.33%   |
| Nvidia                          | 1        | 1.33%   |
| MediaTek                        | 1        | 1.33%   |
| D-Link System                   | 1        | 1.33%   |
| D-Link                          | 1        | 1.33%   |
| Belkin Components               | 1        | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 22       | 25%     |
| Intel Ethernet Controller I225-V                                                      | 4        | 4.55%   |
| Intel I211 Gigabit Network Connection                                                 | 3        | 3.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 2        | 2.27%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 2        | 2.27%   |
| Intel Ethernet Connection (7) I219-V                                                  | 2        | 2.27%   |
| Intel Ethernet Connection (2) I219-V                                                  | 2        | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 2        | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 2        | 2.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                        | 1        | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                  | 1        | 1.14%   |
| T & A Mobile Phones TCL 20E                                                           | 1        | 1.14%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1        | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 1.14%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1        | 1.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1        | 1.14%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                             | 1        | 1.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1        | 1.14%   |
| Qualcomm FP3                                                                          | 1        | 1.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 1        | 1.14%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 1        | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1        | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1        | 1.14%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 1.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1        | 1.14%   |
| Nvidia MCP61 Ethernet                                                                 | 1        | 1.14%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 1.14%   |
| Intel Wireless 3160                                                                   | 1        | 1.14%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 1.14%   |
| Intel I210 Gigabit Network Connection                                                 | 1        | 1.14%   |
| Intel Ethernet Controller I226-V                                                      | 1        | 1.14%   |
| Intel Ethernet Controller I219-V                                                      | 1        | 1.14%   |
| Intel Ethernet Connection I217-V                                                      | 1        | 1.14%   |
| Intel Ethernet Connection I217-LM                                                     | 1        | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                                                 | 1        | 1.14%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 1        | 1.14%   |
| Intel Ethernet Connection (17) I219-LM                                                | 1        | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 1.14%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 1.14%   |

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
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 4.76%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 4.76%   |
| Intel 700 Series Chipset Family Wi-Fi                                                 | 1        | 4.76%   |
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
| Realtek Semiconductor | 27       | 42.86%  |
| Intel                 | 24       | 38.1%   |
| Xiaomi                | 2        | 3.17%   |
| VIA Technologies      | 2        | 3.17%   |
| Qualcomm Atheros      | 2        | 3.17%   |
| Broadcom              | 2        | 3.17%   |
| T & A Mobile Phones   | 1        | 1.59%   |
| Qualcomm              | 1        | 1.59%   |
| Nvidia                | 1        | 1.59%   |
| D-Link System         | 1        | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22       | 33.33%  |
| Intel Ethernet Controller I225-V                                  | 4        | 6.06%   |
| Intel I211 Gigabit Network Connection                             | 3        | 4.55%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 3.03%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 3.03%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 3.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.52%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 1.52%   |
| T & A Mobile Phones TCL 20E                                       | 1        | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.52%   |
| Qualcomm FP3                                                      | 1        | 1.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.52%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.52%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.52%   |
| Intel Ethernet Controller I226-V                                  | 1        | 1.52%   |
| Intel Ethernet Controller I219-V                                  | 1        | 1.52%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.52%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.52%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 1.52%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1        | 1.52%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.52%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.52%   |
| Intel 82567V-4 Gigabit Network Connection                         | 1        | 1.52%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.52%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 1.52%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.52%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 1.52%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 53       | 72.6%   |
| WiFi     | 19       | 26.03%  |
| Unknown  | 1        | 1.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 47       | 90.38%  |
| WiFi     | 5        | 9.62%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 31       | 55.36%  |
| 2     | 17       | 30.36%  |
| 3     | 4        | 7.14%   |
| 4     | 2        | 3.57%   |
| 5     | 1        | 1.79%   |
| 0     | 1        | 1.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 42       | 76.36%  |
| Yes  | 13       | 23.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 42.86%  |
| Cambridge Silicon Radio | 4        | 28.57%  |
| MediaTek                | 1        | 7.14%   |
| IMC Networks            | 1        | 7.14%   |
| Broadcom                | 1        | 7.14%   |
| Actions                 | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 28.57%  |
| Intel Bluetooth Device                              | 3        | 21.43%  |
| MediaTek Wireless_Device                            | 1        | 7.14%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 7.14%   |
| Intel Bluetooth wireless interface                  | 1        | 7.14%   |
| Intel AX200 Bluetooth                               | 1        | 7.14%   |
| IMC Networks Bluetooth Device                       | 1        | 7.14%   |
| Broadcom BCM20702A0                                 | 1        | 7.14%   |
| Actions general adapter                             | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 37       | 57.81%  |
| AMD                                  | 13       | 20.31%  |
| Nvidia                               | 5        | 7.81%   |
| VIA Technologies                     | 2        | 3.13%   |
| C-Media Electronics                  | 2        | 3.13%   |
| Thesycon Systemsoftware & Consulting | 1        | 1.56%   |
| RODE Microphones                     | 1        | 1.56%   |
| Native Instruments                   | 1        | 1.56%   |
| Generalplus Technology               | 1        | 1.56%   |
| Creative Labs                        | 1        | 1.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5        | 6.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5        | 6.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4        | 5.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 4.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 4.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3        | 4.11%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 4.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3        | 4.11%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 2        | 2.74%   |
| Intel DG2 Audio Controller                                                                        | 2        | 2.74%   |
| Intel Comet Lake PCH cAVS                                                                         | 2        | 2.74%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2        | 2.74%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2        | 2.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 2.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2        | 2.74%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 2.74%   |
| AMD FCH Azalia Controller                                                                         | 2        | 2.74%   |
| Thesycon Systemsoftware & Consulting D10                                                          | 1        | 1.37%   |
| RODE Microphones RODE NT-USB Mini                                                                 | 1        | 1.37%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 1.37%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 1.37%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1        | 1.37%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 1.37%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1        | 1.37%   |
| Native Instruments Komplete Audio 2                                                               | 1        | 1.37%   |
| Intel USB PnP Sound Device                                                                        | 1        | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.37%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1        | 1.37%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 1.37%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1        | 1.37%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                                          | 1        | 1.37%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1                                  | 1        | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1        | 1.37%   |
| Generalplus Technology USB Audio Device                                                           | 1        | 1.37%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1        | 1.37%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 1        | 1.37%   |
| C-Media Electronics Blue Snowball                                                                 | 1        | 1.37%   |
| AMD Wrestler HDMI Audio                                                                           | 1        | 1.37%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1        | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 9        | 14.52%  |
| Unknown             | 8        | 12.9%   |
| Crucial             | 8        | 12.9%   |
| SK hynix            | 7        | 11.29%  |
| Kingston            | 7        | 11.29%  |
| Elpida              | 5        | 8.06%   |
| Micron Technology   | 4        | 6.45%   |
| Corsair             | 3        | 4.84%   |
| Unknown             | 2        | 3.23%   |
| Visipro             | 1        | 1.61%   |
| Team                | 1        | 1.61%   |
| Qimonda             | 1        | 1.61%   |
| PNY                 | 1        | 1.61%   |
| Patriot             | 1        | 1.61%   |
| Novatech            | 1        | 1.61%   |
| Hewlett-Packard     | 1        | 1.61%   |
| Cors                | 1        | 1.61%   |
| A-DATA Technology   | 1        | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s      | 2        | 3.03%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s | 2        | 3.03%   |
| Unknown                                                  | 2        | 3.03%   |
| Visipro RAM T2G88S1-H9H 2GB DIMM DDR3 1333MT/s           | 1        | 1.52%   |
| Unknown RAM Module 512MB DIMM                            | 1        | 1.52%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 1.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 1.52%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                 | 1        | 1.52%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 1        | 1.52%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s             | 1        | 1.52%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 1.52%   |
| Unknown RAM Module 128MB DIMM                            | 1        | 1.52%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 1.52%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3800MT/s      | 1        | 1.52%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 1.52%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 1.52%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 1.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.52%   |
| SK hynix RAM 71V16635HCT8-H 128MB DIMM SDRAM 133MT/s     | 1        | 1.52%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s              | 1        | 1.52%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 1.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.52%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 1.52%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s      | 1        | 1.52%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.52%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.52%   |
| Samsung RAM M3 78T2953EZ3-CE6 1GB DIMM DDR2 1331MT/s     | 1        | 1.52%   |
| Samsung RAM M3 66S1623DT0-C75 128MB DIMM SDRAM 133MT/s   | 1        | 1.52%   |
| Samsung RAM 4D34373142353237 4GB SODIMM DDR3 1600MT/s    | 1        | 1.52%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s         | 1        | 1.52%   |
| PNY RAM Module 1GB DIMM DDR2 667MT/s                     | 1        | 1.52%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 1.52%   |
| Novatech RAM N3S02H1600B-L67LR0 2GB DIMM DDR3 1333MT/s   | 1        | 1.52%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB DIMM DDR3 1600MT/s      | 1        | 1.52%   |
| Micron RAM 8KTF51264AZ-1G9P1 4GB DIMM DDR3 1866MT/s      | 1        | 1.52%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 1.52%   |
| Micron RAM 16ATF4G64HZ-3G2F1 32GB SODIMM DDR4 3200MT/s   | 1        | 1.52%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s      | 1        | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 28       | 58.33%  |
| DDR4    | 10       | 20.83%  |
| SDRAM   | 5        | 10.42%  |
| DDR2    | 2        | 4.17%   |
| Unknown | 2        | 4.17%   |
| DDR5    | 1        | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 39       | 84.78%  |
| SODIMM | 7        | 15.22%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 15       | 28.85%  |
| 4096  | 13       | 25%     |
| 2048  | 11       | 21.15%  |
| 32768 | 4        | 7.69%   |
| 1024  | 4        | 7.69%   |
| 16384 | 2        | 3.85%   |
| 128   | 2        | 3.85%   |
| 512   | 1        | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 21       | 40.38%  |
| 1333    | 5        | 9.62%   |
| 3600    | 4        | 7.69%   |
| 667     | 3        | 5.77%   |
| Unknown | 3        | 5.77%   |
| 3200    | 2        | 3.85%   |
| 2400    | 2        | 3.85%   |
| 1866    | 2        | 3.85%   |
| 5808    | 1        | 1.92%   |
| 3800    | 1        | 1.92%   |
| 2667    | 1        | 1.92%   |
| 2200    | 1        | 1.92%   |
| 2133    | 1        | 1.92%   |
| 1867    | 1        | 1.92%   |
| 1800    | 1        | 1.92%   |
| 1331    | 1        | 1.92%   |
| 800     | 1        | 1.92%   |
| 133     | 1        | 1.92%   |

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
| 0     | 40       | 71.43%  |
| 1     | 8        | 14.29%  |
| 2     | 4        | 7.14%   |
| 3     | 2        | 3.57%   |
| 7     | 1        | 1.79%   |
| 4     | 1        | 1.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 12       | 44.44%  |
| Net/wireless             | 5        | 18.52%  |
| Communication controller | 4        | 14.81%  |
| Storage/ata              | 2        | 7.41%   |
| Net/ethernet             | 2        | 7.41%   |
| Sound                    | 1        | 3.7%    |
| Network                  | 1        | 3.7%    |

