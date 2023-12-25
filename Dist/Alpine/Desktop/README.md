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

Total: 105

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | TDPS05                      | [ce9b5d0c48](https://linux-hardware.org/?probe=ce9b5d0c48) | Dec 23, 2023 |
| Acer          | TDPS05                      | [d0260b1327](https://linux-hardware.org/?probe=d0260b1327) | Dec 23, 2023 |
| HP            | 886C                        | [2432d4f585](https://linux-hardware.org/?probe=2432d4f585) | Dec 22, 2023 |
| HP            | 886C                        | [4b404f8509](https://linux-hardware.org/?probe=4b404f8509) | Dec 15, 2023 |
| ZOTAC         | Unknown                     | [a91d567af3](https://linux-hardware.org/?probe=a91d567af3) | Dec 14, 2023 |
| Compaq        | 0684h                       | [54c2d84103](https://linux-hardware.org/?probe=54c2d84103) | Dec 02, 2023 |
| Compaq        | 0684h                       | [b2d96b48dc](https://linux-hardware.org/?probe=b2d96b48dc) | Dec 02, 2023 |
| ECS           | M789CG                      | [7c2e2de188](https://linux-hardware.org/?probe=7c2e2de188) | Dec 01, 2023 |
| HP            | 886C                        | [b312b34d74](https://linux-hardware.org/?probe=b312b34d74) | Nov 20, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1909f3fbff](https://linux-hardware.org/?probe=1909f3fbff) | Nov 15, 2023 |
| HP            | 886C                        | [f48f05994e](https://linux-hardware.org/?probe=f48f05994e) | Nov 14, 2023 |
| Unknown       | Unknown                     | [80774e2d18](https://linux-hardware.org/?probe=80774e2d18) | Nov 14, 2023 |
| HP            | 886C                        | [65a7263504](https://linux-hardware.org/?probe=65a7263504) | Nov 09, 2023 |
| ECS           | M789CG                      | [49edfe005c](https://linux-hardware.org/?probe=49edfe005c) | Nov 07, 2023 |
| Gigabyte      | 945GCM-S2C                  | [c714bf35c2](https://linux-hardware.org/?probe=c714bf35c2) | Nov 06, 2023 |
| HP            | 886C                        | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| ECS           | M789CG                      | [87fe73ee84](https://linux-hardware.org/?probe=87fe73ee84) | Nov 02, 2023 |
| HP            | 886C                        | [e116ef83e9](https://linux-hardware.org/?probe=e116ef83e9) | Oct 27, 2023 |
| HP            | 886C                        | [6df3cd6820](https://linux-hardware.org/?probe=6df3cd6820) | Oct 20, 2023 |
| ECS           | M789CG                      | [b767549953](https://linux-hardware.org/?probe=b767549953) | Oct 15, 2023 |
| ASRock        | Q1900B-ITX                  | [8625166ef3](https://linux-hardware.org/?probe=8625166ef3) | Oct 14, 2023 |
| ECS           | M789CG                      | [6f446a6f77](https://linux-hardware.org/?probe=6f446a6f77) | Oct 14, 2023 |
| ECS           | M789CG                      | [0a0df79fcd](https://linux-hardware.org/?probe=0a0df79fcd) | Oct 14, 2023 |
| Inventec      | D CLASS A02                 | [9559c016fb](https://linux-hardware.org/?probe=9559c016fb) | Oct 13, 2023 |
| ASRock        | Z790M-ITX WiFi              | [560aec8a01](https://linux-hardware.org/?probe=560aec8a01) | Oct 06, 2023 |
| HP            | 886C                        | [8356867b4d](https://linux-hardware.org/?probe=8356867b4d) | Oct 04, 2023 |
| HP            | 886C                        | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| HP            | 886C                        | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| HP            | 886C                        | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| ASRock        | H55M-LE                     | [6b7e52fd8c](https://linux-hardware.org/?probe=6b7e52fd8c) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | [ceefe742e2](https://linux-hardware.org/?probe=ceefe742e2) | Sep 20, 2023 |
| Dell          | 0RY007                      | [3bcbd1f6c3](https://linux-hardware.org/?probe=3bcbd1f6c3) | Sep 19, 2023 |
| HP            | 886C                        | [d59c2170bb](https://linux-hardware.org/?probe=d59c2170bb) | Sep 08, 2023 |
| HP            | 886C                        | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Dell          | 096JG8 A01                  | [00e5bebc6a](https://linux-hardware.org/?probe=00e5bebc6a) | Sep 06, 2023 |
| HP            | 886C                        | [30368099b8](https://linux-hardware.org/?probe=30368099b8) | Sep 06, 2023 |
| HP            | 886C                        | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| HP            | 886C                        | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| HP            | 886C                        | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| HP            | 886C                        | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| HP            | 886C                        | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
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
| HP            | 886C                        | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
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
| HP            | 886C                        | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
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
| HP            | 886C                        | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
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
| Alpine 3.12.0               | 6        | 9.84%   |
| Alpine 3.18.4               | 4        | 6.56%   |
| Alpine 3.17_alpha20220809   | 4        | 6.56%   |
| Alpine 3.15.4               | 4        | 6.56%   |
| Alpine 3.19_alpha20230901   | 3        | 4.92%   |
| Alpine 3.18.0               | 3        | 4.92%   |
| Alpine 3.16.0               | 3        | 4.92%   |
| Alpine 3.13.0_alpha20200626 | 3        | 4.92%   |
| Alpine 3.19.0               | 2        | 3.28%   |
| Alpine 3.18.5               | 2        | 3.28%   |
| Alpine 3.18.3               | 2        | 3.28%   |
| Alpine 3.18.2               | 2        | 3.28%   |
| Alpine 3.17.2               | 2        | 3.28%   |
| Alpine 3.17.1               | 2        | 3.28%   |
| Alpine 3.16.1               | 2        | 3.28%   |
| Alpine 3.11.2               | 2        | 3.28%   |
| Alpine 3.8.4                | 1        | 1.64%   |
| Alpine 3.17.4               | 1        | 1.64%   |
| Alpine 3.17.0               | 1        | 1.64%   |
| Alpine 3.16.2               | 1        | 1.64%   |
| Alpine 3.16.0_alpha20220328 | 1        | 1.64%   |
| Alpine 3.15.6               | 1        | 1.64%   |
| Alpine 3.15.0               | 1        | 1.64%   |
| Alpine 3.14.3               | 1        | 1.64%   |
| Alpine 3.14.2               | 1        | 1.64%   |
| Alpine 3.14.0               | 1        | 1.64%   |
| Alpine 3.13.6               | 1        | 1.64%   |
| Alpine 3.13.2               | 1        | 1.64%   |
| Alpine 3.13.1               | 1        | 1.64%   |
| Alpine 3.13.0_alpha20201218 | 1        | 1.64%   |
| Alpine 3.12.3               | 1        | 1.64%   |

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


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.43-1-lts      | 5        | 7.81%   |
| 6.1.57-0-lts      | 3        | 4.69%   |
| 6.1.51-0-lts      | 2        | 3.13%   |
| 5.15.60-0-lts     | 2        | 3.13%   |
| 6.6.7-0-lts       | 1        | 1.56%   |
| 6.6.6-0-lts       | 1        | 1.56%   |
| 6.6.1-0-edge      | 1        | 1.56%   |
| 6.3.3-0-edge      | 1        | 1.56%   |
| 6.2.0-37-generic  | 1        | 1.56%   |
| 6.2.0-36-generic  | 1        | 1.56%   |
| 6.1.64-0-lts      | 1        | 1.56%   |
| 6.1.61-0-lts      | 1        | 1.56%   |
| 6.1.60-0-lts      | 1        | 1.56%   |
| 6.1.55-2-lts      | 1        | 1.56%   |
| 6.1.54-0-lts      | 1        | 1.56%   |
| 6.1.36-0-lts      | 1        | 1.56%   |
| 6.1.34-0-lts      | 1        | 1.56%   |
| 6.1.30-0-lts      | 1        | 1.56%   |
| 6.1.28-2-lts      | 1        | 1.56%   |
| 6.0.10-0-edge     | 1        | 1.56%   |
| 5.8.0             | 1        | 1.56%   |
| 5.7.4             | 1        | 1.56%   |
| 5.4.84-0-lts      | 1        | 1.56%   |
| 5.4.6-0-lts       | 1        | 1.56%   |
| 5.4.58-0-lts      | 1        | 1.56%   |
| 5.4.57-0-lts      | 1        | 1.56%   |
| 5.4.0-77-generic  | 1        | 1.56%   |
| 5.19.0-50-generic | 1        | 1.56%   |
| 5.19.0-35-generic | 1        | 1.56%   |
| 5.18.0-0-asahi    | 1        | 1.56%   |
| 5.17.9-0-edge     | 1        | 1.56%   |
| 5.17.3-0-edge     | 1        | 1.56%   |
| 5.15.98-0-lts     | 1        | 1.56%   |
| 5.15.87-0-lts     | 1        | 1.56%   |
| 5.15.86-0-lts     | 1        | 1.56%   |
| 5.15.83-0-lts     | 1        | 1.56%   |
| 5.15.80           | 1        | 1.56%   |
| 5.15.74-0-lts     | 1        | 1.56%   |
| 5.15.70-0-lts     | 1        | 1.56%   |
| 5.15.64-1-pve     | 1        | 1.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.43  | 5        | 8.06%   |
| 6.1.57  | 3        | 4.84%   |
| 6.1.51  | 2        | 3.23%   |
| 5.15.60 | 2        | 3.23%   |
| 6.6.7   | 1        | 1.61%   |
| 6.6.6   | 1        | 1.61%   |
| 6.6.1   | 1        | 1.61%   |
| 6.3.3   | 1        | 1.61%   |
| 6.2.0   | 1        | 1.61%   |
| 6.1.64  | 1        | 1.61%   |
| 6.1.61  | 1        | 1.61%   |
| 6.1.60  | 1        | 1.61%   |
| 6.1.55  | 1        | 1.61%   |
| 6.1.54  | 1        | 1.61%   |
| 6.1.36  | 1        | 1.61%   |
| 6.1.34  | 1        | 1.61%   |
| 6.1.30  | 1        | 1.61%   |
| 6.1.28  | 1        | 1.61%   |
| 6.0.10  | 1        | 1.61%   |
| 5.8.0   | 1        | 1.61%   |
| 5.7.4   | 1        | 1.61%   |
| 5.4.84  | 1        | 1.61%   |
| 5.4.6   | 1        | 1.61%   |
| 5.4.58  | 1        | 1.61%   |
| 5.4.57  | 1        | 1.61%   |
| 5.4.0   | 1        | 1.61%   |
| 5.19.0  | 1        | 1.61%   |
| 5.18.0  | 1        | 1.61%   |
| 5.17.9  | 1        | 1.61%   |
| 5.17.3  | 1        | 1.61%   |
| 5.15.98 | 1        | 1.61%   |
| 5.15.87 | 1        | 1.61%   |
| 5.15.86 | 1        | 1.61%   |
| 5.15.83 | 1        | 1.61%   |
| 5.15.80 | 1        | 1.61%   |
| 5.15.74 | 1        | 1.61%   |
| 5.15.70 | 1        | 1.61%   |
| 5.15.64 | 1        | 1.61%   |
| 5.15.57 | 1        | 1.61%   |
| 5.15.46 | 1        | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 16       | 26.67%  |
| 6.1     | 13       | 21.67%  |
| 5.4     | 10       | 16.67%  |
| 5.10    | 5        | 8.33%   |
| 6.6     | 3        | 5%      |
| 5.17    | 2        | 3.33%   |
| 6.3     | 1        | 1.67%   |
| 6.2     | 1        | 1.67%   |
| 6.0     | 1        | 1.67%   |
| 5.8     | 1        | 1.67%   |
| 5.7     | 1        | 1.67%   |
| 5.19    | 1        | 1.67%   |
| 5.18    | 1        | 1.67%   |
| 4.4     | 1        | 1.67%   |
| 4.20    | 1        | 1.67%   |
| 4.14    | 1        | 1.67%   |
| 3.10    | 1        | 1.67%   |

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
| C       | 34       | 60.71%  |
| Unknown | 19       | 33.93%  |
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
| Ext4    | 45       | 80.36%  |
| Btrfs   | 4        | 7.14%   |
| Tmpfs   | 2        | 3.57%   |
| Overlay | 2        | 3.57%   |
| Zfs     | 1        | 1.79%   |
| Fake    | 1        | 1.79%   |
| Unknown | 1        | 1.79%   |

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
| No        | 45       | 80.36%  |
| Yes       | 11       | 19.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 89.29%  |
| Yes       | 6        | 10.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASRock              | 8        | 14.55%  |
| Gigabyte Technology | 7        | 12.73%  |
| Dell                | 7        | 12.73%  |
| ASUSTek Computer    | 7        | 12.73%  |
| Hewlett-Packard     | 4        | 7.27%   |
| Intel               | 3        | 5.45%   |
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
| Gigabyte Z490I AORUS ULTRA         | 2        | 3.64%   |
| ASUS All Series                    | 2        | 3.64%   |
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
| HP OMEN 25L Desktop GT12-1xxx      | 1        | 1.82%   |
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

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 5        | 9.09%   |
| Unknown               | 4        | 7.27%   |
| Gigabyte Z490I        | 2        | 3.64%   |
| Dell Inspiron         | 2        | 3.64%   |
| ASUS PRIME            | 2        | 3.64%   |
| ASUS All              | 2        | 3.64%   |
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
| HP OMEN               | 1        | 1.82%   |
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

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 8        | 14.55%  |
| 2013    | 6        | 10.91%  |
| 2020    | 5        | 9.09%   |
| 2018    | 5        | 9.09%   |
| 2010    | 5        | 9.09%   |
| 2016    | 4        | 7.27%   |
| 2012    | 4        | 7.27%   |
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
| Disabled | 55       | 98.21%  |
| Enabled  | 1        | 1.79%   |

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


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 15       | 25%     |
| 16.01-24.0      | 12       | 20%     |
| 4.01-8.0        | 8        | 13.33%  |
| 32.01-64.0      | 6        | 10%     |
| 8.01-16.0       | 6        | 10%     |
| 0.51-1.0        | 3        | 5%      |
| 0.01-0.5        | 3        | 5%      |
| 2.01-3.0        | 2        | 3.33%   |
| 64.01-256.0     | 2        | 3.33%   |
| 1.01-2.0        | 2        | 3.33%   |
| More than 256.0 | 1        | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 15       | 25.86%  |
| 1.01-2.0  | 14       | 24.14%  |
| 0.51-1.0  | 10       | 17.24%  |
| 3.01-4.0  | 5        | 8.62%   |
| 2.01-3.0  | 5        | 8.62%   |
| 4.01-8.0  | 4        | 6.9%    |
| 0         | 2        | 3.45%   |
| Unknown   | 2        | 3.45%   |
| 8.01-16.0 | 1        | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 42.11%  |
| 2      | 14       | 24.56%  |
| 3      | 9        | 15.79%  |
| 4      | 6        | 10.53%  |
| 5      | 2        | 3.51%   |
| 12     | 1        | 1.75%   |
| 0      | 1        | 1.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 85.71%  |
| Yes       | 8        | 14.29%  |

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
| No        | 38       | 66.67%  |
| Yes       | 19       | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 76.79%  |
| Yes       | 13       | 23.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 14       | 22.95%  |
| Germany     | 7        | 11.48%  |
| Russia      | 4        | 6.56%   |
| Sweden      | 3        | 4.92%   |
| Norway      | 3        | 4.92%   |
| Brazil      | 3        | 4.92%   |
| UK          | 2        | 3.28%   |
| Spain       | 2        | 3.28%   |
| Finland     | 2        | 3.28%   |
| Canada      | 2        | 3.28%   |
| Argentina   | 2        | 3.28%   |
| Vietnam     | 1        | 1.64%   |
| Ukraine     | 1        | 1.64%   |
| Switzerland | 1        | 1.64%   |
| South Korea | 1        | 1.64%   |
| Portugal    | 1        | 1.64%   |
| Poland      | 1        | 1.64%   |
| Pakistan    | 1        | 1.64%   |
| Netherlands | 1        | 1.64%   |
| Mexico      | 1        | 1.64%   |
| Israel      | 1        | 1.64%   |
| Ireland     | 1        | 1.64%   |
| Indonesia   | 1        | 1.64%   |
| Guatemala   | 1        | 1.64%   |
| China       | 1        | 1.64%   |
| Austria     | 1        | 1.64%   |
| Australia   | 1        | 1.64%   |
| Algeria     | 1        | 1.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Springfield          | 4        | 6.56%   |
| St Petersburg        | 3        | 4.92%   |
| Manitowoc            | 3        | 4.92%   |
| Harrisonburg         | 2        | 3.28%   |
| Frankfurt am Main    | 2        | 3.28%   |
| As                   | 2        | 3.28%   |
| Zurich               | 1        | 1.64%   |
| Tuusula              | 1        | 1.64%   |
| Traunstein           | 1        | 1.64%   |
| Tinh Binh Duong      | 1        | 1.64%   |
| Thornhill            | 1        | 1.64%   |
| Stuttgart            | 1        | 1.64%   |
| Stockholm            | 1        | 1.64%   |
| Somerset             | 1        | 1.64%   |
| Ski                  | 1        | 1.64%   |
| Salzburg             | 1        | 1.64%   |
| Redwood City         | 1        | 1.64%   |
| Ramat Gan            | 1        | 1.64%   |
| Penza                | 1        | 1.64%   |
| Olofstorp            | 1        | 1.64%   |
| Oberhausen           | 1        | 1.64%   |
| Nussdorf am Inn      | 1        | 1.64%   |
| Noblesville          | 1        | 1.64%   |
| Lisbon               | 1        | 1.64%   |
| Lauro de Freitas     | 1        | 1.64%   |
| Lahore               | 1        | 1.64%   |
| Kharkiv              | 1        | 1.64%   |
| Jerez de la Frontera | 1        | 1.64%   |
| Jember               | 1        | 1.64%   |
| Helsinki             | 1        | 1.64%   |
| Hangzhou             | 1        | 1.64%   |
| Hamburg              | 1        | 1.64%   |
| Gwacheon             | 1        | 1.64%   |
| Guatemala City       | 1        | 1.64%   |
| Gothenburg           | 1        | 1.64%   |
| Gorredijk            | 1        | 1.64%   |
| Glasgow              | 1        | 1.64%   |
| General San Martin   | 1        | 1.64%   |
| Durham               | 1        | 1.64%   |
| Dublin               | 1        | 1.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 17       | 41     | 16.5%   |
| WDC                         | 15       | 23     | 14.56%  |
| Seagate                     | 14       | 28     | 13.59%  |
| Toshiba                     | 7        | 8      | 6.8%    |
| A-DATA Technology           | 6        | 8      | 5.83%   |
| SanDisk                     | 5        | 8      | 4.85%   |
| HGST                        | 5        | 5      | 4.85%   |
| Crucial                     | 5        | 8      | 4.85%   |
| Kingston                    | 4        | 7      | 3.88%   |
| Hitachi                     | 4        | 4      | 3.88%   |
| Intel                       | 3        | 4      | 2.91%   |
| Unknown                     | 2        | 2      | 1.94%   |
| SPCC                        | 2        | 2      | 1.94%   |
| SK hynix                    | 2        | 2      | 1.94%   |
| Transcend                   | 1        | 1      | 0.97%   |
| Secure                      | 1        | 1      | 0.97%   |
| Phison Electronics          | 1        | 1      | 0.97%   |
| Micron Technology           | 1        | 1      | 0.97%   |
| Maxtor                      | 1        | 1      | 0.97%   |
| LITEON                      | 1        | 1      | 0.97%   |
| Lexar                       | 1        | 1      | 0.97%   |
| KIOXIA                      | 1        | 1      | 0.97%   |
| Kingston Technology Company | 1        | 1      | 0.97%   |
| Kingmax                     | 1        | 1      | 0.97%   |
| Intenso                     | 1        | 1      | 0.97%   |
| Apple                       | 1        | 3      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 3        | 2.21%   |
| Seagate ST380815AS 80GB                             | 2        | 1.47%   |
| Samsung SSD 980 PRO 1TB                             | 2        | 1.47%   |
| Samsung SSD 960 EVO 500GB                           | 2        | 1.47%   |
| Samsung SSD 870 QVO 1TB                             | 2        | 1.47%   |
| Samsung SSD 870 EVO 1TB                             | 2        | 1.47%   |
| Kingston SA400S3 120GB SSD                          | 2        | 1.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1        | 0.74%   |
| WDC WDS500G2B0A 500GB SSD                           | 1        | 0.74%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                    | 1        | 0.74%   |
| WDC WDS250G2B0B 250GB SSD                           | 1        | 0.74%   |
| WDC WDS250G2B0A 250GB SSD                           | 1        | 0.74%   |
| WDC WD800AAJS-00 80GB                               | 1        | 0.74%   |
| WDC WD7500BPKT-80PK4T0 752GB                        | 1        | 0.74%   |
| WDC WD5000BEVT-7 500GB                              | 1        | 0.74%   |
| WDC WD5000AZRX-00A8LB0 500GB                        | 1        | 0.74%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 1        | 0.74%   |
| WDC WD40EFZX-68AWUN0 4TB                            | 1        | 0.74%   |
| WDC WD3200AAKX-0 320GB                              | 1        | 0.74%   |
| WDC WD20EZRZ-00Z 2TB                                | 1        | 0.74%   |
| WDC WD1600JS-60NCB1 160GB                           | 1        | 0.74%   |
| WDC WD1600BEVT-2 160GB                              | 1        | 0.74%   |
| WDC WD140EDGZ-11B2DA2 14TB                          | 1        | 0.74%   |
| WDC WD120EFBX-68B0EN0 12TB                          | 1        | 0.74%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1        | 0.74%   |
| WDC WD10EZEX-75WN4A1 1TB                            | 1        | 0.74%   |
| WDC WD10EZEX-21M2NA0 1TB                            | 1        | 0.74%   |
| WDC WD BLACK SDBPNTY-512G-1106 512GB                | 1        | 0.74%   |
| Unknown SD/MMC/MS PRO 128GB                         | 1        | 0.74%   |
| Unknown MMC Card  32GB                              | 1        | 0.74%   |
| Transcend SSD 1GB                                   | 1        | 0.74%   |
| Toshiba MQ04ABF100 1TB                              | 1        | 0.74%   |
| Toshiba MQ04ABF1 1TB                                | 1        | 0.74%   |
| Toshiba MQ01ABF050 500GB                            | 1        | 0.74%   |
| Toshiba MK3252GS 320GB                              | 1        | 0.74%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD             | 1        | 0.74%   |
| Toshiba HDWD130 3TB                                 | 1        | 0.74%   |
| Toshiba DT01ACA2 2TB                                | 1        | 0.74%   |
| Toshiba DT01ACA1 1TB                                | 1        | 0.74%   |
| SPCC Solid State Disk 120GB                         | 1        | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 28     | 29.79%  |
| WDC                 | 13       | 17     | 27.66%  |
| Toshiba             | 6        | 7      | 12.77%  |
| HGST                | 5        | 5      | 10.64%  |
| Hitachi             | 4        | 4      | 8.51%   |
| Samsung Electronics | 3        | 6      | 6.38%   |
| Unknown             | 1        | 1      | 2.13%   |
| Maxtor              | 1        | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 18     | 22.5%   |
| Crucial             | 5        | 8      | 12.5%   |
| Kingston            | 4        | 5      | 10%     |
| A-DATA Technology   | 4        | 4      | 10%     |
| WDC                 | 3        | 5      | 7.5%    |
| Intel               | 3        | 4      | 7.5%    |
| SPCC                | 2        | 2      | 5%      |
| SanDisk             | 2        | 3      | 5%      |
| Transcend           | 1        | 1      | 2.5%    |
| Toshiba             | 1        | 1      | 2.5%    |
| SK hynix            | 1        | 1      | 2.5%    |
| Secure              | 1        | 1      | 2.5%    |
| LITEON              | 1        | 1      | 2.5%    |
| Lexar               | 1        | 1      | 2.5%    |
| Kingmax             | 1        | 1      | 2.5%    |
| Intenso             | 1        | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 34       | 69     | 42.5%   |
| SSD  | 29       | 57     | 36.25%  |
| NVMe | 16       | 37     | 20%     |
| MMC  | 1        | 1      | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 48       | 123    | 71.64%  |
| NVMe | 16       | 37     | 23.88%  |
| SAS  | 2        | 3      | 2.99%   |
| MMC  | 1        | 1      | 1.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 42       | 77     | 63.64%  |
| 0.51-1.0   | 10       | 21     | 15.15%  |
| 3.01-4.0   | 4        | 8      | 6.06%   |
| 1.01-2.0   | 3        | 6      | 4.55%   |
| 4.01-10.0  | 3        | 3      | 4.55%   |
| 2.01-3.0   | 2        | 2      | 3.03%   |
| 10.01-20.0 | 2        | 9      | 3.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 16       | 28.57%  |
| 101-250        | 9        | 16.07%  |
| 1-20           | 6        | 10.71%  |
| 251-500        | 5        | 8.93%   |
| More than 3000 | 4        | 7.14%   |
| 21-50          | 4        | 7.14%   |
| 501-1000       | 4        | 7.14%   |
| 2001-3000      | 3        | 5.36%   |
| 51-100         | 3        | 5.36%   |
| 1001-2000      | 2        | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 23       | 41.07%  |
| Unknown        | 16       | 28.57%  |
| 251-500        | 6        | 10.71%  |
| 21-50          | 5        | 8.93%   |
| 1001-2000      | 2        | 3.57%   |
| 51-100         | 2        | 3.57%   |
| More than 3000 | 1        | 1.79%   |
| 2001-3000      | 1        | 1.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD3200AAKX-0 320GB             | 1        | 1      | 7.69%   |
| Toshiba MK3252GS 320GB             | 1        | 1      | 7.69%   |
| Secure Net 256GB SSD               | 1        | 1      | 7.69%   |
| Seagate ST500LM021-1KJ152 500GB    | 1        | 1      | 7.69%   |
| SanDisk SDSA6MM 16GB SSD           | 1        | 1      | 7.69%   |
| Samsung Electronics SSD PM81 128GB | 1        | 1      | 7.69%   |
| Samsung Electronics SP0411N 40GB   | 1        | 2      | 7.69%   |
| Maxtor 2B020H1 20GB                | 1        | 1      | 7.69%   |
| Kingmax SSD 120G                   | 1        | 1      | 7.69%   |
| Hitachi HTS722080K9A300 80GB       | 1        | 1      | 7.69%   |
| HGST HTS725050A7 500GB             | 1        | 1      | 7.69%   |
| A-DATA Technology SU800 128GB SSD  | 1        | 1      | 7.69%   |
| A-DATA Technology IM2P33F8ABR1-1TB | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 3      | 15.38%  |
| A-DATA Technology   | 2        | 2      | 15.38%  |
| WDC                 | 1        | 1      | 7.69%   |
| Toshiba             | 1        | 1      | 7.69%   |
| Secure              | 1        | 1      | 7.69%   |
| Seagate             | 1        | 1      | 7.69%   |
| SanDisk             | 1        | 1      | 7.69%   |
| Maxtor              | 1        | 1      | 7.69%   |
| Kingmax             | 1        | 1      | 7.69%   |
| Hitachi             | 1        | 1      | 7.69%   |
| HGST                | 1        | 1      | 7.69%   |

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
| HDD  | 7        | 8      | 53.85%  |
| SSD  | 5        | 5      | 38.46%  |
| NVMe | 1        | 1      | 7.69%   |

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
| Works    | 37       | 110    | 57.81%  |
| Detected | 16       | 40     | 25%     |
| Malfunc  | 11       | 14     | 17.19%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 41       | 49.4%   |
| Samsung Electronics         | 9        | 10.84%  |
| AMD                         | 9        | 10.84%  |
| SanDisk                     | 3        | 3.61%   |
| VIA Technologies            | 2        | 2.41%   |
| Nvidia                      | 2        | 2.41%   |
| Marvell Technology Group    | 2        | 2.41%   |
| LSI Logic / Symbios Logic   | 2        | 2.41%   |
| ASMedia Technology          | 2        | 2.41%   |
| ADATA Technology            | 2        | 2.41%   |
| Adaptec                     | 2        | 2.41%   |
| SK hynix                    | 1        | 1.2%    |
| Promise Technology          | 1        | 1.2%    |
| Phison Electronics          | 1        | 1.2%    |
| Micron Technology           | 1        | 1.2%    |
| KIOXIA                      | 1        | 1.2%    |
| Kingston Technology Company | 1        | 1.2%    |
| Broadcom / LSI              | 1        | 1.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6        | 5.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 5.22%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6        | 5.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 4.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 3.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 3.48%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3        | 2.61%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3        | 2.61%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 2        | 1.74%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2        | 1.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 1.74%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2        | 1.74%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 2        | 1.74%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 2        | 1.74%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 1.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.74%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2        | 1.74%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 1.74%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.74%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 2        | 1.74%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1        | 0.87%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.87%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1        | 0.87%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 0.87%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.87%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1        | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.87%   |
| Promise PDC42819 [FastTrak TX2650/TX4650]                                      | 1        | 0.87%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1        | 0.87%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1        | 0.87%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.87%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.87%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 1        | 0.87%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 0.87%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 1        | 0.87%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                         | 1        | 0.87%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 1        | 0.87%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 40       | 51.95%  |
| NVMe | 14       | 18.18%  |
| IDE  | 13       | 16.88%  |
| RAID | 8        | 10.39%  |
| SAS  | 2        | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 42       | 75%     |
| AMD          | 11       | 19.64%  |
| iSH          | 1        | 1.79%   |
| CentaurHauls | 1        | 1.79%   |
| Unknown      | 1        | 1.79%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i9-10900 CPU @ 2.80GHz      | 2        | 3.28%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2        | 3.28%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 3.28%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 2        | 3.28%   |
| Intel Celeron CPU J1900 @ 1.99GHz      | 2        | 3.28%   |
| Intel Atom CPU D525 @ 1.80GHz          | 2        | 3.28%   |
| AMD FX-8350 Eight-Core Processor       | 2        | 3.28%   |
| iSH Processor                          | 1        | 1.64%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz     | 1        | 1.64%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1        | 1.64%   |
| Intel Pentium III (Coppermine)         | 1        | 1.64%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1        | 1.64%   |
| Intel Pentium CPU E5700 @ 3.00GHz      | 1        | 1.64%   |
| Intel Core i7-8700T CPU @ 2.40GHz      | 1        | 1.64%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 1.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 1        | 1.64%   |
| Intel Core i7-10610U CPU @ 1.80GHz     | 1        | 1.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz     | 1        | 1.64%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1        | 1.64%   |
| Intel Core i5-6600K CPU @ 3.50GHz      | 1        | 1.64%   |
| Intel Core i5-6500T CPU @ 2.50GHz      | 1        | 1.64%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 1        | 1.64%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 1        | 1.64%   |
| Intel Core i5-4570T CPU @ 2.90GHz      | 1        | 1.64%   |
| Intel Core i5-3450 CPU @ 3.10GHz       | 1        | 1.64%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 1.64%   |
| Intel Core i3-7130U CPU @ 2.70GHz      | 1        | 1.64%   |
| Intel Core i3-3240 CPU @ 3.40GHz       | 1        | 1.64%   |
| Intel Core i3-3220T CPU @ 2.80GHz      | 1        | 1.64%   |
| Intel Core i3-2100 CPU @ 3.10GHz       | 1        | 1.64%   |
| Intel Core i3 CPU 540 @ 3.07GHz        | 1        | 1.64%   |
| Intel Core 2 CPU 4300 @ 1.80GHz        | 1        | 1.64%   |
| Intel Celeron N5105 @ 2.00GHz          | 1        | 1.64%   |
| Intel Celeron M processor 1.00GHz      | 1        | 1.64%   |
| Intel Celeron CPU N3150 @ 1.60GHz      | 1        | 1.64%   |
| Intel Celeron CPU J3455 @ 1.50GHz      | 1        | 1.64%   |
| Intel Celeron CPU J1800 @ 2.41GHz      | 1        | 1.64%   |
| Intel Celeron CPU G1850 @ 2.90GHz      | 1        | 1.64%   |
| Intel Celeron CPU E3400 @ 2.60GHz      | 1        | 1.64%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz      | 1        | 1.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 10       | 16.95%  |
| Intel Celeron      | 8        | 13.56%  |
| Other              | 7        | 11.86%  |
| Intel Core i3      | 7        | 11.86%  |
| Intel Core i7      | 5        | 8.47%   |
| Intel Atom         | 3        | 5.08%   |
| AMD Ryzen 7        | 3        | 5.08%   |
| Intel Core i9      | 2        | 3.39%   |
| AMD FX             | 2        | 3.39%   |
| Intel Xeon Gold    | 1        | 1.69%   |
| Intel Xeon         | 1        | 1.69%   |
| Intel Pentium III  | 1        | 1.69%   |
| Intel Pentium Dual | 1        | 1.69%   |
| Intel Pentium      | 1        | 1.69%   |
| Intel Core 2       | 1        | 1.69%   |
| Intel Celeron M    | 1        | 1.69%   |
| AMD Sempron        | 1        | 1.69%   |
| AMD Ryzen 9        | 1        | 1.69%   |
| AMD G              | 1        | 1.69%   |
| AMD E1             | 1        | 1.69%   |
| AMD A8             | 1        | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 19       | 32.76%  |
| 2       | 18       | 31.03%  |
| 1       | 6        | 10.34%  |
| 8       | 4        | 6.9%    |
| 6       | 3        | 5.17%   |
| 12      | 2        | 3.45%   |
| 10      | 2        | 3.45%   |
| 32      | 1        | 1.72%   |
| 24      | 1        | 1.72%   |
| 14      | 1        | 1.72%   |
| Unknown | 1        | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 53       | 94.64%  |
| 2       | 1        | 1.79%   |
| 0       | 1        | 1.79%   |
| Unknown | 1        | 1.79%   |

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
| Unknown    | 29       | 48.33%  |
| 0x306c3    | 4        | 6.67%   |
| 0x906ea    | 2        | 3.33%   |
| 0x306a9    | 2        | 3.33%   |
| 0xb0671    | 1        | 1.67%   |
| 0xa0671    | 1        | 1.67%   |
| 0xa0655    | 1        | 1.67%   |
| 0x906a3    | 1        | 1.67%   |
| 0x90672    | 1        | 1.67%   |
| 0x806ec    | 1        | 1.67%   |
| 0x806ea    | 1        | 1.67%   |
| 0x6fd      | 1        | 1.67%   |
| 0x6f2      | 1        | 1.67%   |
| 0x6d8      | 1        | 1.67%   |
| 0x68a      | 1        | 1.67%   |
| 0x506c9    | 1        | 1.67%   |
| 0x406c4    | 1        | 1.67%   |
| 0x30678    | 1        | 1.67%   |
| 0x20655    | 1        | 1.67%   |
| 0x106e5    | 1        | 1.67%   |
| 0x1067a    | 1        | 1.67%   |
| 0x0a20120e | 1        | 1.67%   |
| 0x08701021 | 1        | 1.67%   |
| 0x0800820d | 1        | 1.67%   |
| 0x06000817 | 1        | 1.67%   |
| 0x05000101 | 1        | 1.67%   |
| 0x010000b6 | 1        | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 8        | 13.56%  |
| Silvermont       | 5        | 8.47%   |
| Skylake          | 4        | 6.78%   |
| KabyLake         | 4        | 6.78%   |
| Unknown          | 4        | 6.78%   |
| SandyBridge      | 3        | 5.08%   |
| Piledriver       | 3        | 5.08%   |
| IvyBridge        | 3        | 5.08%   |
| CometLake        | 3        | 5.08%   |
| Alderlake Hybrid | 3        | 5.08%   |
| Zen 3            | 2        | 3.39%   |
| Penryn           | 2        | 3.39%   |
| P6               | 2        | 3.39%   |
| Core             | 2        | 3.39%   |
| Bonnell          | 2        | 3.39%   |
| Zen+             | 1        | 1.69%   |
| Zen 2            | 1        | 1.69%   |
| Westmere         | 1        | 1.69%   |
| Nehalem          | 1        | 1.69%   |
| K6               | 1        | 1.69%   |
| K10              | 1        | 1.69%   |
| Jaguar           | 1        | 1.69%   |
| Goldmont         | 1        | 1.69%   |
| Bobcat           | 1        | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 35       | 59.32%  |
| AMD                        | 12       | 20.34%  |
| Nvidia                     | 7        | 11.86%  |
| VIA Technologies           | 2        | 3.39%   |
| Matrox Electronics Systems | 2        | 3.39%   |
| S3 Graphics                | 1        | 1.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5        | 6.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 5%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4        | 5%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3        | 3.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 3.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 3.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 2.5%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 2.5%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 2.5%    |
| VIA Technologies VT8623 [Apollo CLE266] integrated CastleRock graphics                   | 1        | 1.25%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1        | 1.25%   |
| S3 Graphics Savage 4                                                                     | 1        | 1.25%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1        | 1.25%   |
| Nvidia GT218 [ION]                                                                       | 1        | 1.25%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 1.25%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.25%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.25%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.25%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1        | 1.25%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1        | 1.25%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1        | 1.25%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1        | 1.25%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1        | 1.25%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1        | 1.25%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 1.25%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                                          | 1        | 1.25%   |
| Nvidia AD102 [GeForce RTX 4090]                                                          | 1        | 1.25%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.25%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1        | 1.25%   |
| Intel UHD Graphics 620                                                                   | 1        | 1.25%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 1        | 1.25%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 1.25%   |
| Intel HD Graphics 630                                                                    | 1        | 1.25%   |
| Intel HD Graphics 620                                                                    | 1        | 1.25%   |
| Intel HD Graphics 530                                                                    | 1        | 1.25%   |
| Intel HD Graphics 500                                                                    | 1        | 1.25%   |
| Intel DG2 [Arc A770]                                                                     | 1        | 1.25%   |
| Intel DG2 [Arc A750]                                                                     | 1        | 1.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 1.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 33       | 55.93%  |
| 1 x AMD         | 11       | 18.64%  |
| 1 x Nvidia      | 5        | 8.47%   |
| Other           | 2        | 3.39%   |
| 2 x Intel       | 1        | 1.69%   |
| 1 x VIA         | 1        | 1.69%   |
| 1 x S3 Graphics | 1        | 1.69%   |
| Nvidia + Matrox | 1        | 1.69%   |
| 1 x Matrox      | 1        | 1.69%   |
| Intel + Nvidia  | 1        | 1.69%   |
| Intel + AMD     | 1        | 1.69%   |
| AMD + VIA       | 1        | 1.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 43       | 76.79%  |
| Unknown     | 12       | 21.43%  |
| Proprietary | 1        | 1.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 43       | 76.79%  |
| 0.01-0.5   | 4        | 7.14%   |
| 7.01-8.0   | 3        | 5.36%   |
| 3.01-4.0   | 2        | 3.57%   |
| 0.51-1.0   | 2        | 3.57%   |
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
| Dell                | 9        | 16.98%  |
| Samsung Electronics | 7        | 13.21%  |
| Goldstar            | 6        | 11.32%  |
| BenQ                | 5        | 9.43%   |
| AOC                 | 5        | 9.43%   |
| Philips             | 2        | 3.77%   |
| Belinea             | 2        | 3.77%   |
| Acer                | 2        | 3.77%   |
| Vizio               | 1        | 1.89%   |
| ViewSonic           | 1        | 1.89%   |
| Sceptre Tech        | 1        | 1.89%   |
| Mi                  | 1        | 1.89%   |
| LG Display          | 1        | 1.89%   |
| KVM                 | 1        | 1.89%   |
| InfoVision          | 1        | 1.89%   |
| Huion               | 1        | 1.89%   |
| Hewlett-Packard     | 1        | 1.89%   |
| Elo Touch           | 1        | 1.89%   |
| Element             | 1        | 1.89%   |
| CTC                 | 1        | 1.89%   |
| Chimei Innolux      | 1        | 1.89%   |
| BOE                 | 1        | 1.89%   |
| AU Optronics        | 1        | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch     | 3        | 4.62%   |
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                     | 3        | 4.62%   |
| Belinea B101555 MAX05DF 1024x768 304x228mm 15.0-inch                 | 2        | 3.08%   |
| Vizio D40f-J09 VIZ1044 1920x1080 890x490mm 40.0-inch                 | 1        | 1.54%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch             | 1        | 1.54%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 520x320mm 24.0-inch       | 1        | 1.54%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 474x296mm 22.0-inch | 1        | 1.54%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch | 1        | 1.54%   |
| Samsung Electronics S27A950D SAM079E 1920x1080 598x336mm 27.0-inch   | 1        | 1.54%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1        | 1.54%   |
| Samsung Electronics LS24AG30x SAM7179 1920x1080 527x296mm 23.8-inch  | 1        | 1.54%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch | 1        | 1.54%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 1        | 1.54%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch              | 1        | 1.54%   |
| Mi Monitor XMI2701 2560x1440 597x336mm 27.0-inch                     | 1        | 1.54%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch         | 1        | 1.54%   |
| KVM LCD Monitor 1 1 9" KVM4308 1280x1024 338x270mm 17.0-inch         | 1        | 1.54%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch         | 1        | 1.54%   |
| Huion GT-192 HAT1920 1920x1080 432x243mm 19.5-inch                   | 1        | 1.54%   |
| Hewlett-Packard LA1751 HWP2858 1280x1024 340x270mm 17.1-inch         | 1        | 1.54%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1        | 1.54%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 1        | 1.54%   |
| Goldstar ULTRAWIDE GSM5AE2 3440x1440 800x335mm 34.1-inch             | 1        | 1.54%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 1        | 1.54%   |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch             | 1        | 1.54%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 1.54%   |
| Goldstar M227WD GSM56D5 1920x1080 480x270mm 21.7-inch                | 1        | 1.54%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 1        | 1.54%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                | 1        | 1.54%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 1        | 1.54%   |
| Elo Touch ET1717L ELO1717 1280x1024 338x270mm 17.0-inch              | 1        | 1.54%   |
| Element ELEFW408 ELE1366 1920x1080 890x500mm 40.2-inch               | 1        | 1.54%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                    | 1        | 1.54%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                    | 1        | 1.54%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1        | 1.54%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                   | 1        | 1.54%   |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                    | 1        | 1.54%   |
| Dell E1911 DELF037 1440x900 408x255mm 18.9-inch                      | 1        | 1.54%   |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                    | 1        | 1.54%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                    | 1        | 1.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 13       | 27.66%  |
| 1680x1050 (WSXGA+) | 5        | 10.64%  |
| 1280x1024 (SXGA)   | 5        | 10.64%  |
| 3840x2160 (4K)     | 4        | 8.51%   |
| 3440x1440          | 4        | 8.51%   |
| 2560x1440 (QHD)    | 4        | 8.51%   |
| 1024x768 (XGA)     | 3        | 6.38%   |
| 1440x900 (WXGA+)   | 2        | 4.26%   |
| 1366x768 (WXGA)    | 2        | 4.26%   |
| 2560x1080          | 1        | 2.13%   |
| 1920x1200 (WUXGA)  | 1        | 2.13%   |
| 1600x900 (HD+)     | 1        | 2.13%   |
| 1360x768           | 1        | 2.13%   |
| 1280x960           | 1        | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 7        | 13.21%  |
| 23     | 5        | 9.43%   |
| 20     | 5        | 9.43%   |
| 19     | 5        | 9.43%   |
| 34     | 4        | 7.55%   |
| 24     | 4        | 7.55%   |
| 21     | 4        | 7.55%   |
| 17     | 4        | 7.55%   |
| 15     | 4        | 7.55%   |
| 18     | 3        | 5.66%   |
| 72     | 1        | 1.89%   |
| 40     | 1        | 1.89%   |
| 32     | 1        | 1.89%   |
| 31     | 1        | 1.89%   |
| 25     | 1        | 1.89%   |
| 22     | 1        | 1.89%   |
| 16     | 1        | 1.89%   |
| 14     | 1        | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 14       | 30.43%  |
| 401-500     | 13       | 28.26%  |
| 301-350     | 7        | 15.22%  |
| 701-800     | 4        | 8.7%    |
| 351-400     | 4        | 8.7%    |
| 601-700     | 2        | 4.35%   |
| 801-900     | 1        | 2.17%   |
| 1501-2000   | 1        | 2.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 18       | 46.15%  |
| 16/10 | 8        | 20.51%  |
| 5/4   | 5        | 12.82%  |
| 21/9  | 4        | 10.26%  |
| 4/3   | 3        | 7.69%   |
| 6/5   | 1        | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 11       | 23.4%   |
| 201-250        | 10       | 21.28%  |
| 301-350        | 7        | 14.89%  |
| 351-500        | 5        | 10.64%  |
| 141-150        | 5        | 10.64%  |
| 101-110        | 4        | 8.51%   |
| More than 1000 | 1        | 2.13%   |
| 81-90          | 1        | 2.13%   |
| 251-300        | 1        | 2.13%   |
| 131-140        | 1        | 2.13%   |
| 501-1000       | 1        | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 25       | 62.5%   |
| 101-120 | 8        | 20%     |
| 1-50    | 4        | 10%     |
| 121-160 | 2        | 5%      |
| 161-240 | 1        | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 56.9%   |
| 0     | 19       | 32.76%  |
| 2     | 4        | 6.9%    |
| 4     | 1        | 1.72%   |
| 3     | 1        | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 28       | 34.57%  |
| Intel                           | 25       | 30.86%  |
| Qualcomm Atheros                | 6        | 7.41%   |
| Broadcom                        | 5        | 6.17%   |
| Xiaomi                          | 2        | 2.47%   |
| VIA Technologies                | 2        | 2.47%   |
| MediaTek                        | 2        | 2.47%   |
| TP-Link                         | 1        | 1.23%   |
| T & A Mobile Phones             | 1        | 1.23%   |
| Qualcomm Atheros Communications | 1        | 1.23%   |
| Qualcomm                        | 1        | 1.23%   |
| Nvidia                          | 1        | 1.23%   |
| NetGear                         | 1        | 1.23%   |
| DisplayLink                     | 1        | 1.23%   |
| D-Link System                   | 1        | 1.23%   |
| D-Link                          | 1        | 1.23%   |
| Belkin Components               | 1        | 1.23%   |
| ASIX Electronics                | 1        | 1.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 22       | 20.56%  |
| Intel Ethernet Controller I225-V                                                      | 4        | 3.74%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 3        | 2.8%    |
| Intel I211 Gigabit Network Connection                                                 | 3        | 2.8%    |
| Intel Ethernet Connection (2) I219-V                                                  | 3        | 2.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3        | 2.8%    |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 2        | 1.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2        | 1.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 2        | 1.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 2        | 1.87%   |
| Intel Ethernet Connection (7) I219-V                                                  | 2        | 1.87%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 2        | 1.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                        | 1        | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                  | 1        | 0.93%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                   | 1        | 0.93%   |
| T & A Mobile Phones TCL 20E                                                           | 1        | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1        | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 0.93%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                             | 1        | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1        | 0.93%   |
| Qualcomm Redmi 9T                                                                     | 1        | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1        | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 1        | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 1        | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1        | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1        | 0.93%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1        | 0.93%   |
| Nvidia MCP61 Ethernet                                                                 | 1        | 0.93%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                                 | 1        | 0.93%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1        | 0.93%   |
| Intel Wireless 8265 / 8275                                                            | 1        | 0.93%   |
| Intel Wireless 3160                                                                   | 1        | 0.93%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 1        | 0.93%   |
| Intel I210 Gigabit Network Connection                                                 | 1        | 0.93%   |
| Intel Ethernet Controller I226-V                                                      | 1        | 0.93%   |
| Intel Ethernet Controller I219-V                                                      | 1        | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 29.63%  |
| Realtek Semiconductor           | 5        | 18.52%  |
| Qualcomm Atheros                | 4        | 14.81%  |
| Broadcom                        | 3        | 11.11%  |
| MediaTek                        | 2        | 7.41%   |
| TP-Link                         | 1        | 3.7%    |
| Qualcomm Atheros Communications | 1        | 3.7%    |
| NetGear                         | 1        | 3.7%    |
| D-Link                          | 1        | 3.7%    |
| Belkin Components               | 1        | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2        | 6.25%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 2        | 6.25%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                   | 1        | 3.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1        | 3.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 3.13%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                             | 1        | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1        | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 1        | 3.13%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1        | 3.13%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 3.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1        | 3.13%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                                 | 1        | 3.13%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 3.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1        | 3.13%   |
| Intel Wireless 8265 / 8275                                                            | 1        | 3.13%   |
| Intel Wireless 3160                                                                   | 1        | 3.13%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 3.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 1        | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 3.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1        | 3.13%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 3.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 1        | 3.13%   |
| Intel 700 Series Chipset Family Wi-Fi                                                 | 1        | 3.13%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                         | 1        | 3.13%   |
| Broadcom BCM4378 802.11ax Dual Band Wireless Network Adapter                          | 1        | 3.13%   |
| Broadcom BCM43227 802.11b/g/n                                                         | 1        | 3.13%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 1        | 3.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1        | 3.13%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]                    | 1        | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 27       | 40.91%  |
| Intel                 | 24       | 36.36%  |
| Broadcom              | 3        | 4.55%   |
| Xiaomi                | 2        | 3.03%   |
| VIA Technologies      | 2        | 3.03%   |
| Qualcomm Atheros      | 2        | 3.03%   |
| T & A Mobile Phones   | 1        | 1.52%   |
| Qualcomm              | 1        | 1.52%   |
| Nvidia                | 1        | 1.52%   |
| DisplayLink           | 1        | 1.52%   |
| D-Link System         | 1        | 1.52%   |
| ASIX Electronics      | 1        | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 22       | 29.73%  |
| Intel Ethernet Controller I225-V                                      | 4        | 5.41%   |
| Realtek RTL8125 2.5GbE Controller                                     | 3        | 4.05%   |
| Intel I211 Gigabit Network Connection                                 | 3        | 4.05%   |
| Intel Ethernet Connection (2) I219-V                                  | 3        | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 3        | 4.05%   |
| VIA VT6102/VT6103 [Rhine-II]                                          | 2        | 2.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 2        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 2        | 2.7%    |
| Intel Ethernet Connection (7) I219-V                                  | 2        | 2.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 1        | 1.35%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                  | 1        | 1.35%   |
| T & A Mobile Phones TCL 20E                                           | 1        | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1        | 1.35%   |
| Qualcomm Redmi 9T                                                     | 1        | 1.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                             | 1        | 1.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1        | 1.35%   |
| Nvidia MCP61 Ethernet                                                 | 1        | 1.35%   |
| Intel I210 Gigabit Network Connection                                 | 1        | 1.35%   |
| Intel Ethernet Controller I226-V                                      | 1        | 1.35%   |
| Intel Ethernet Controller I219-V                                      | 1        | 1.35%   |
| Intel Ethernet Connection I217-LM                                     | 1        | 1.35%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1        | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                                 | 1        | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                                 | 1        | 1.35%   |
| Intel Ethernet Connection (17) I219-LM                                | 1        | 1.35%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                          | 1        | 1.35%   |
| Intel 82578DM Gigabit Network Connection                              | 1        | 1.35%   |
| Intel 82567V-4 Gigabit Network Connection                             | 1        | 1.35%   |
| Intel 82566DM-2 Gigabit Network Connection                            | 1        | 1.35%   |
| Intel 82562V-2 10/100 Network Connection                              | 1        | 1.35%   |
| DisplayLink Dell D3100 Docking Station                                | 1        | 1.35%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                       | 1        | 1.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                     | 1        | 1.35%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1        | 1.35%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1        | 1.35%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1        | 1.35%   |
| ASIX AX88179 Gigabit Ethernet                                         | 1        | 1.35%   |

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
| Ethernet | 47       | 88.68%  |
| WiFi     | 6        | 11.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 56.14%  |
| 2     | 18       | 31.58%  |
| 3     | 4        | 7.02%   |
| 5     | 1        | 1.75%   |
| 4     | 1        | 1.75%   |
| 0     | 1        | 1.75%   |

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


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 33.33%  |
| Cambridge Silicon Radio         | 4        | 19.05%  |
| IMC Networks                    | 2        | 9.52%   |
| Qualcomm Atheros Communications | 1        | 4.76%   |
| MediaTek                        | 1        | 4.76%   |
| Foxconn / Hon Hai               | 1        | 4.76%   |
| Edimax Technology               | 1        | 4.76%   |
| Dell                            | 1        | 4.76%   |
| Broadcom                        | 1        | 4.76%   |
| Apple                           | 1        | 4.76%   |
| Actions                         | 1        | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 18.18%  |
| Intel AX201 Bluetooth                               | 3        | 13.64%  |
| Intel Bluetooth wireless interface                  | 2        | 9.09%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 4.55%   |
| MediaTek Wireless_Device                            | 1        | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 4.55%   |
| Intel Bluetooth Device                              | 1        | 4.55%   |
| Intel AX200 Bluetooth                               | 1        | 4.55%   |
| IMC Networks Wireless_Device                        | 1        | 4.55%   |
| IMC Networks Bluetooth Device                       | 1        | 4.55%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1        | 4.55%   |
| Edimax Bluetooth Adapter                            | 1        | 4.55%   |
| Dell BCM20702A0 Bluetooth Module                    | 1        | 4.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.55%   |
| Apple Bluetooth Host Controller                     | 1        | 4.55%   |
| Actions general adapter                             | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 37       | 52.86%  |
| AMD                                  | 14       | 20%     |
| Nvidia                               | 6        | 8.57%   |
| VIA Technologies                     | 2        | 2.86%   |
| C-Media Electronics                  | 2        | 2.86%   |
| Thesycon Systemsoftware & Consulting | 1        | 1.43%   |
| Texas Instruments                    | 1        | 1.43%   |
| SteelSeries ApS                      | 1        | 1.43%   |
| RODE Microphones                     | 1        | 1.43%   |
| Native Instruments                   | 1        | 1.43%   |
| Logitech                             | 1        | 1.43%   |
| Generalplus Technology               | 1        | 1.43%   |
| Focusrite-Novation                   | 1        | 1.43%   |
| Creative Labs                        | 1        | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 5.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 4.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 3.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 3.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 2.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3        | 2.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 2.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 2.97%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 2        | 1.98%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.98%   |
| Intel DG2 Audio Controller                                                 | 2        | 1.98%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 1.98%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 1.98%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.98%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.98%   |
| Thesycon Systemsoftware & Consulting DX3 Pro                               | 1        | 0.99%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.99%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1        | 0.99%   |
| RODE Microphones RODE NT-USB Mini                                          | 1        | 0.99%   |
| Nvidia MCP89 High Definition Audio                                         | 1        | 0.99%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.99%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.99%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.99%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.99%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.99%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 0.99%   |
| Nvidia Audio device                                                        | 1        | 0.99%   |
| Nvidia AD102 High Definition Audio Controller                              | 1        | 0.99%   |
| Native Instruments Komplete Audio 2                                        | 1        | 0.99%   |
| Logitech PRO                                                               | 1        | 0.99%   |
| Logitech G935 Gaming Headset                                               | 1        | 0.99%   |
| Intel USB PnP Sound Device                                                 | 1        | 0.99%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 0.99%   |
| Intel Sunrise Point-LP HD Audio                                            | 1        | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1        | 0.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 0.99%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 10       | 14.29%  |
| Unknown             | 8        | 11.43%  |
| SK hynix            | 8        | 11.43%  |
| Kingston            | 8        | 11.43%  |
| Crucial             | 8        | 11.43%  |
| Micron Technology   | 5        | 7.14%   |
| Elpida              | 5        | 7.14%   |
| Corsair             | 4        | 5.71%   |
| A-DATA Technology   | 2        | 2.86%   |
| Unknown             | 2        | 2.86%   |
| Visipro             | 1        | 1.43%   |
| Team                | 1        | 1.43%   |
| Qimonda             | 1        | 1.43%   |
| PNY                 | 1        | 1.43%   |
| Patriot             | 1        | 1.43%   |
| Novatech            | 1        | 1.43%   |
| Lexar               | 1        | 1.43%   |
| Hewlett-Packard     | 1        | 1.43%   |
| G.Skill             | 1        | 1.43%   |
| Cors                | 1        | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s      | 2        | 2.27%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s | 2        | 2.27%   |
| Unknown                                                  | 2        | 2.27%   |
| Visipro RAM T2G88S1-H9H 2GB DIMM DDR3 1333MT/s           | 1        | 1.14%   |
| Unknown RAM Module 512MB DIMM                            | 1        | 1.14%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 1.14%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 1.14%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                 | 1        | 1.14%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 1        | 1.14%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s             | 1        | 1.14%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 1.14%   |
| Unknown RAM Module 128MB DIMM                            | 1        | 1.14%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 1.14%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s      | 1        | 1.14%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.14%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.14%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 1.14%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 1.14%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.14%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 1        | 1.14%   |
| SK hynix RAM 71V16635HCT8-H 128MB DIMM SDRAM 133MT/s     | 1        | 1.14%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s              | 1        | 1.14%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 1.14%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.14%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s   | 1        | 1.14%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s    | 1        | 1.14%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 1.14%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s      | 1        | 1.14%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.14%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.14%   |
| Samsung RAM M3 78T2953EZ3-CE6 1GB DIMM DDR2 1331MT/s     | 1        | 1.14%   |
| Samsung RAM M3 66S1623DT0-C75 128MB DIMM SDRAM 133MT/s   | 1        | 1.14%   |
| Samsung RAM 4D34373142353237 4GB SODIMM DDR3 1600MT/s    | 1        | 1.14%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s         | 1        | 1.14%   |
| PNY RAM Module 1GB DIMM DDR2 667MT/s                     | 1        | 1.14%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 1.14%   |
| Novatech RAM N3S02H1600B-L67LR0 2GB DIMM DDR3 1333MT/s   | 1        | 1.14%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s  | 1        | 1.14%   |
| Micron RAM Module 4GB SODIMM DDR3 1067MT/s               | 1        | 1.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 28       | 56%     |
| DDR4    | 11       | 22%     |
| SDRAM   | 5        | 10%     |
| DDR5    | 2        | 4%      |
| DDR2    | 2        | 4%      |
| Unknown | 2        | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 39       | 81.25%  |
| SODIMM       | 8        | 16.67%  |
| Row Of Chips | 1        | 2.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 15       | 27.27%  |
| 4096  | 14       | 25.45%  |
| 2048  | 11       | 20%     |
| 32768 | 5        | 9.09%   |
| 1024  | 4        | 7.27%   |
| 16384 | 3        | 5.45%   |
| 128   | 2        | 3.64%   |
| 512   | 1        | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 22       | 36.07%  |
| 1333    | 6        | 9.84%   |
| 3600    | 4        | 6.56%   |
| 3200    | 3        | 4.92%   |
| 2400    | 3        | 4.92%   |
| 667     | 3        | 4.92%   |
| Unknown | 3        | 4.92%   |
| 3800    | 2        | 3.28%   |
| 2667    | 2        | 3.28%   |
| 1866    | 2        | 3.28%   |
| 8400    | 1        | 1.64%   |
| 5808    | 1        | 1.64%   |
| 4800    | 1        | 1.64%   |
| 3000    | 1        | 1.64%   |
| 2200    | 1        | 1.64%   |
| 2133    | 1        | 1.64%   |
| 1800    | 1        | 1.64%   |
| 1331    | 1        | 1.64%   |
| 1067    | 1        | 1.64%   |
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
| Intermec Technologies | 1        | 33.33%  |
| Hewlett-Packard       | 1        | 33.33%  |
| Brother Industries    | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Intermec PC43t           | 1        | 25%     |
| HP LaserJet 1020         | 1        | 25%     |
| HP Deskjet 3050A         | 1        | 25%     |
| Brother HL-L2360D series | 1        | 25%     |

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


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Z-Star Microelectronics                | 2        | 15.38%  |
| Trust                                  | 1        | 7.69%   |
| Syntek                                 | 1        | 7.69%   |
| Samsung Electronics                    | 1        | 7.69%   |
| Realtek Semiconductor                  | 1        | 7.69%   |
| Microdia                               | 1        | 7.69%   |
| Luxvisions Innotech Limited            | 1        | 7.69%   |
| Logitech                               | 1        | 7.69%   |
| IMC Networks                           | 1        | 7.69%   |
| Chicony Electronics                    | 1        | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 7.69%   |
| Bison Electronics                      | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Z-Star Vimicro USB2.0 Camera                                    | 1        | 7.14%   |
| Z-Star A4 TECH USB2.0 PC Camera J                               | 1        | 7.14%   |
| Trust QHD Webcam                                                | 1        | 7.14%   |
| Syntek Integrated Camera                                        | 1        | 7.14%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1        | 7.14%   |
| Realtek Integrated_Webcam_HD                                    | 1        | 7.14%   |
| Microdia Integrated_Webcam_HD                                   | 1        | 7.14%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1        | 7.14%   |
| Logitech Webcam C270                                            | 1        | 7.14%   |
| Logitech Webcam C170                                            | 1        | 7.14%   |
| IMC Networks VGA UVC WebCam                                     | 1        | 7.14%   |
| Chicony HD Webcam                                               | 1        | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1        | 7.14%   |
| Bison Integrated Camera                                         | 1        | 7.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Synaptics                  | 1        | 50%     |
| Shenzhen Goodix Technology | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1        | 50%     |
| Shenzhen Goodix  FingerPrint Device                       | 1        | 50%     |

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
| 0     | 39       | 65%     |
| 1     | 10       | 16.67%  |
| 2     | 5        | 8.33%   |
| 3     | 3        | 5%      |
| 4     | 2        | 3.33%   |
| 7     | 1        | 1.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 14       | 38.89%  |
| Net/wireless             | 6        | 16.67%  |
| Communication controller | 5        | 13.89%  |
| Storage/ata              | 2        | 5.56%   |
| Net/ethernet             | 2        | 5.56%   |
| Unassigned class         | 1        | 2.78%   |
| Sound                    | 1        | 2.78%   |
| Network                  | 1        | 2.78%   |
| Multimedia controller    | 1        | 2.78%   |
| Fingerprint reader       | 1        | 2.78%   |
| Camera                   | 1        | 2.78%   |
| Bluetooth                | 1        | 2.78%   |

