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

Total: 90

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B85M-D3H                    | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| ECS           | M789CG                      | [87fe73ee84](https://linux-hardware.org/?probe=87fe73ee84) | Nov 02, 2023 |
| Gigabyte      | B85M-D3H                    | [e116ef83e9](https://linux-hardware.org/?probe=e116ef83e9) | Oct 27, 2023 |
| Gigabyte      | B85M-D3H                    | [6df3cd6820](https://linux-hardware.org/?probe=6df3cd6820) | Oct 20, 2023 |
| ECS           | M789CG                      | [b767549953](https://linux-hardware.org/?probe=b767549953) | Oct 15, 2023 |
| ASRock        | Q1900B-ITX                  | [8625166ef3](https://linux-hardware.org/?probe=8625166ef3) | Oct 14, 2023 |
| ECS           | M789CG                      | [6f446a6f77](https://linux-hardware.org/?probe=6f446a6f77) | Oct 14, 2023 |
| ECS           | M789CG                      | [0a0df79fcd](https://linux-hardware.org/?probe=0a0df79fcd) | Oct 14, 2023 |
| Inventec      | D CLASS A02                 | [9559c016fb](https://linux-hardware.org/?probe=9559c016fb) | Oct 13, 2023 |
| ASRock        | Z790M-ITX WiFi              | [560aec8a01](https://linux-hardware.org/?probe=560aec8a01) | Oct 06, 2023 |
| Gigabyte      | B85M-D3H                    | [8356867b4d](https://linux-hardware.org/?probe=8356867b4d) | Oct 04, 2023 |
| Gigabyte      | B85M-D3H                    | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| Gigabyte      | B85M-D3H                    | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| Gigabyte      | B85M-D3H                    | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| ASRock        | H55M-LE                     | [6b7e52fd8c](https://linux-hardware.org/?probe=6b7e52fd8c) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | [ceefe742e2](https://linux-hardware.org/?probe=ceefe742e2) | Sep 20, 2023 |
| Dell          | 0RY007                      | [3bcbd1f6c3](https://linux-hardware.org/?probe=3bcbd1f6c3) | Sep 19, 2023 |
| Gigabyte      | B85M-D3H                    | [d59c2170bb](https://linux-hardware.org/?probe=d59c2170bb) | Sep 08, 2023 |
| Gigabyte      | B85M-D3H                    | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Dell          | 096JG8 A01                  | [00e5bebc6a](https://linux-hardware.org/?probe=00e5bebc6a) | Sep 06, 2023 |
| Gigabyte      | B85M-D3H                    | [30368099b8](https://linux-hardware.org/?probe=30368099b8) | Sep 06, 2023 |
| Gigabyte      | B85M-D3H                    | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| Gigabyte      | B85M-D3H                    | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| Gigabyte      | B85M-D3H                    | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Gigabyte      | B85M-D3H                    | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| Gigabyte      | B85M-D3H                    | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
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
| Gigabyte      | B85M-D3H                    | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
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
| Gigabyte      | B85M-D3H                    | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
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
| Gigabyte      | B85M-D3H                    | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
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
| Alpine 3.12.0               | 6        | 11.11%  |
| Alpine 3.17_alpha20220809   | 4        | 7.41%   |
| Alpine 3.15.4               | 4        | 7.41%   |
| Alpine 3.18.4               | 3        | 5.56%   |
| Alpine 3.18.0               | 3        | 5.56%   |
| Alpine 3.16.0               | 3        | 5.56%   |
| Alpine 3.13.0_alpha20200626 | 3        | 5.56%   |
| Alpine 3.19_alpha20230901   | 2        | 3.7%    |
| Alpine 3.18.3               | 2        | 3.7%    |
| Alpine 3.18.2               | 2        | 3.7%    |
| Alpine 3.17.2               | 2        | 3.7%    |
| Alpine 3.17.1               | 2        | 3.7%    |
| Alpine 3.16.1               | 2        | 3.7%    |
| Alpine 3.11.2               | 2        | 3.7%    |
| Alpine 3.8.4                | 1        | 1.85%   |
| Alpine 3.17.4               | 1        | 1.85%   |
| Alpine 3.17.0               | 1        | 1.85%   |
| Alpine 3.16.2               | 1        | 1.85%   |
| Alpine 3.16.0_alpha20220328 | 1        | 1.85%   |
| Alpine 3.15.6               | 1        | 1.85%   |
| Alpine 3.15.0               | 1        | 1.85%   |
| Alpine 3.14.2               | 1        | 1.85%   |
| Alpine 3.14.0               | 1        | 1.85%   |
| Alpine 3.13.6               | 1        | 1.85%   |
| Alpine 3.13.2               | 1        | 1.85%   |
| Alpine 3.13.1               | 1        | 1.85%   |
| Alpine 3.13.0_alpha20201218 | 1        | 1.85%   |
| Alpine 3.12.3               | 1        | 1.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Alpine | 49       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.43-1-lts      | 5        | 8.93%   |
| 6.1.57-0-lts      | 3        | 5.36%   |
| 6.1.51-0-lts      | 2        | 3.57%   |
| 5.15.60-0-lts     | 2        | 3.57%   |
| 6.3.3-0-edge      | 1        | 1.79%   |
| 6.2.0-36-generic  | 1        | 1.79%   |
| 6.1.55-2-lts      | 1        | 1.79%   |
| 6.1.54-0-lts      | 1        | 1.79%   |
| 6.1.36-0-lts      | 1        | 1.79%   |
| 6.1.34-0-lts      | 1        | 1.79%   |
| 6.1.30-0-lts      | 1        | 1.79%   |
| 6.1.28-2-lts      | 1        | 1.79%   |
| 6.0.10-0-edge     | 1        | 1.79%   |
| 5.8.0             | 1        | 1.79%   |
| 5.7.4             | 1        | 1.79%   |
| 5.4.84-0-lts      | 1        | 1.79%   |
| 5.4.6-0-lts       | 1        | 1.79%   |
| 5.4.58-0-lts      | 1        | 1.79%   |
| 5.4.57-0-lts      | 1        | 1.79%   |
| 5.4.0-77-generic  | 1        | 1.79%   |
| 5.19.0-50-generic | 1        | 1.79%   |
| 5.19.0-35-generic | 1        | 1.79%   |
| 5.18.0-0-asahi    | 1        | 1.79%   |
| 5.17.9-0-edge     | 1        | 1.79%   |
| 5.17.3-0-edge     | 1        | 1.79%   |
| 5.15.98-0-lts     | 1        | 1.79%   |
| 5.15.87-0-lts     | 1        | 1.79%   |
| 5.15.86-0-lts     | 1        | 1.79%   |
| 5.15.83-0-lts     | 1        | 1.79%   |
| 5.15.80           | 1        | 1.79%   |
| 5.15.74-0-lts     | 1        | 1.79%   |
| 5.15.70-0-lts     | 1        | 1.79%   |
| 5.15.64-1-pve     | 1        | 1.79%   |
| 5.15.57-0-lts     | 1        | 1.79%   |
| 5.15.46-1-lts     | 1        | 1.79%   |
| 5.15.40-0-lts     | 1        | 1.79%   |
| 5.15.38-0-lts     | 1        | 1.79%   |
| 5.15.32-0-lts     | 1        | 1.79%   |
| 5.15.17-0-lts     | 1        | 1.79%   |
| 5.15.0-82-generic | 1        | 1.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.43  | 5        | 9.09%   |
| 6.1.57  | 3        | 5.45%   |
| 6.1.51  | 2        | 3.64%   |
| 5.15.60 | 2        | 3.64%   |
| 6.3.3   | 1        | 1.82%   |
| 6.2.0   | 1        | 1.82%   |
| 6.1.55  | 1        | 1.82%   |
| 6.1.54  | 1        | 1.82%   |
| 6.1.36  | 1        | 1.82%   |
| 6.1.34  | 1        | 1.82%   |
| 6.1.30  | 1        | 1.82%   |
| 6.1.28  | 1        | 1.82%   |
| 6.0.10  | 1        | 1.82%   |
| 5.8.0   | 1        | 1.82%   |
| 5.7.4   | 1        | 1.82%   |
| 5.4.84  | 1        | 1.82%   |
| 5.4.6   | 1        | 1.82%   |
| 5.4.58  | 1        | 1.82%   |
| 5.4.57  | 1        | 1.82%   |
| 5.4.0   | 1        | 1.82%   |
| 5.19.0  | 1        | 1.82%   |
| 5.18.0  | 1        | 1.82%   |
| 5.17.9  | 1        | 1.82%   |
| 5.17.3  | 1        | 1.82%   |
| 5.15.98 | 1        | 1.82%   |
| 5.15.87 | 1        | 1.82%   |
| 5.15.86 | 1        | 1.82%   |
| 5.15.83 | 1        | 1.82%   |
| 5.15.80 | 1        | 1.82%   |
| 5.15.74 | 1        | 1.82%   |
| 5.15.70 | 1        | 1.82%   |
| 5.15.64 | 1        | 1.82%   |
| 5.15.57 | 1        | 1.82%   |
| 5.15.46 | 1        | 1.82%   |
| 5.15.40 | 1        | 1.82%   |
| 5.15.38 | 1        | 1.82%   |
| 5.15.32 | 1        | 1.82%   |
| 5.15.17 | 1        | 1.82%   |
| 5.15.0  | 1        | 1.82%   |
| 5.10.81 | 1        | 1.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 16       | 29.63%  |
| 6.1     | 11       | 20.37%  |
| 5.4     | 10       | 18.52%  |
| 5.10    | 5        | 9.26%   |
| 5.17    | 2        | 3.7%    |
| 6.3     | 1        | 1.85%   |
| 6.2     | 1        | 1.85%   |
| 6.0     | 1        | 1.85%   |
| 5.8     | 1        | 1.85%   |
| 5.7     | 1        | 1.85%   |
| 5.19    | 1        | 1.85%   |
| 5.18    | 1        | 1.85%   |
| 4.4     | 1        | 1.85%   |
| 4.14    | 1        | 1.85%   |
| 3.10    | 1        | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 44       | 89.8%   |
| i686    | 4        | 8.16%   |
| aarch64 | 1        | 2.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 40       | 81.63%  |
| XFCE    | 4        | 8.16%   |
| GNOME   | 2        | 4.08%   |
| sway    | 1        | 2.04%   |
| KDE5    | 1        | 2.04%   |
| i3      | 1        | 2.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 34       | 68%     |
| X11     | 13       | 26%     |
| Wayland | 3        | 6%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 43       | 87.76%  |
| LightDM | 5        | 10.2%   |
| SDDM    | 1        | 2.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 31       | 62%     |
| Unknown | 17       | 34%     |
| pt_BR   | 1        | 2%      |
| en_US   | 1        | 2%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 31       | 62%     |
| EFI  | 19       | 38%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 41       | 82%     |
| Btrfs   | 3        | 6%      |
| Tmpfs   | 2        | 4%      |
| Overlay | 2        | 4%      |
| Zfs     | 1        | 2%      |
| Unknown | 1        | 2%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 31       | 60.78%  |
| GPT     | 15       | 29.41%  |
| MBR     | 5        | 9.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 82%     |
| Yes       | 9        | 18%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 90%     |
| Yes       | 5        | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASRock              | 8        | 16.33%  |
| Dell                | 7        | 14.29%  |
| ASUSTek Computer    | 7        | 14.29%  |
| Gigabyte Technology | 6        | 12.24%  |
| Intel               | 3        | 6.12%   |
| Hewlett-Packard     | 3        | 6.12%   |
| MSI                 | 2        | 4.08%   |
| Lenovo              | 2        | 4.08%   |
| Fujitsu             | 2        | 4.08%   |
| Unknown             | 2        | 4.08%   |
| VIA Technologies    | 1        | 2.04%   |
| UGREEN              | 1        | 2.04%   |
| Shuttle             | 1        | 2.04%   |
| Inventec            | 1        | 2.04%   |
| Gateway             | 1        | 2.04%   |
| eMachines           | 1        | 2.04%   |
| ECS                 | 1        | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte Z490I AORUS ULTRA         | 2        | 4.08%   |
| ASUS All Series                    | 2        | 4.08%   |
| Unknown                            | 2        | 4.08%   |
| VIA KM266APro-835                  | 1        | 2.04%   |
| UGREEN DX4600                      | 1        | 2.04%   |
| Shuttle DS81D                      | 1        | 2.04%   |
| MSI MS-7C82                        | 1        | 2.04%   |
| MSI MS-7877                        | 1        | 2.04%   |
| Lenovo ThinkCentre M93p 10AB0016US | 1        | 2.04%   |
| Lenovo H535 10117                  | 1        | 2.04%   |
| Inventec D CLASS                   | 1        | 2.04%   |
| Intel DQ67SW                       | 1        | 2.04%   |
| Intel DH61BF AAG81311-101          | 1        | 2.04%   |
| Intel D525MW AAE93082-401          | 1        | 2.04%   |
| HP ProLiant MicroServer Gen8       | 1        | 2.04%   |
| HP EliteDesk 800 G4 DM 35W         | 1        | 2.04%   |
| HP Compaq 4000 Pro SFF PC          | 1        | 2.04%   |
| Gigabyte Z170X-UD5                 | 1        | 2.04%   |
| Gigabyte X570S AERO G              | 1        | 2.04%   |
| Gigabyte B85M-D3H                  | 1        | 2.04%   |
| Gigabyte B550 AORUS ELITE V2       | 1        | 2.04%   |
| Gateway SX2185                     | 1        | 2.04%   |
| Fujitsu PRIMERGY TX100 S2          | 1        | 2.04%   |
| Fujitsu FujitsuTP7000              | 1        | 2.04%   |
| eMachines EL1352G                  | 1        | 2.04%   |
| ECS M789CG                         | 1        | 2.04%   |
| Dell OptiPlex 755                  | 1        | 2.04%   |
| Dell OptiPlex 7040                 | 1        | 2.04%   |
| Dell OptiPlex 5000                 | 1        | 2.04%   |
| Dell OptiPlex 3020M                | 1        | 2.04%   |
| Dell OptiPlex 3010                 | 1        | 2.04%   |
| Dell Inspiron 530s                 | 1        | 2.04%   |
| Dell Inspiron 3647                 | 1        | 2.04%   |
| ASUS Z170-E                        | 1        | 2.04%   |
| ASUS TS10                          | 1        | 2.04%   |
| ASUS PRIME H370M-PLUS              | 1        | 2.04%   |
| ASUS PRIME B360M-C                 | 1        | 2.04%   |
| ASUS P8H67-V                       | 1        | 2.04%   |
| ASRock Z790M-ITX WiFi              | 1        | 2.04%   |
| ASRock X470 Master SLI/ac          | 1        | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 5        | 10.2%   |
| Gigabyte Z490I        | 2        | 4.08%   |
| Dell Inspiron         | 2        | 4.08%   |
| ASUS PRIME            | 2        | 4.08%   |
| ASUS All              | 2        | 4.08%   |
| Unknown               | 2        | 4.08%   |
| VIA KM266APro-835     | 1        | 2.04%   |
| UGREEN DX4600         | 1        | 2.04%   |
| Shuttle DS81D         | 1        | 2.04%   |
| MSI MS-7C82           | 1        | 2.04%   |
| MSI MS-7877           | 1        | 2.04%   |
| Lenovo ThinkCentre    | 1        | 2.04%   |
| Lenovo H535           | 1        | 2.04%   |
| Inventec D            | 1        | 2.04%   |
| Intel DQ67SW          | 1        | 2.04%   |
| Intel DH61BF          | 1        | 2.04%   |
| Intel D525MW          | 1        | 2.04%   |
| HP ProLiant           | 1        | 2.04%   |
| HP EliteDesk          | 1        | 2.04%   |
| HP Compaq             | 1        | 2.04%   |
| Gigabyte Z170X-UD5    | 1        | 2.04%   |
| Gigabyte X570S        | 1        | 2.04%   |
| Gigabyte B85M-D3H     | 1        | 2.04%   |
| Gigabyte B550         | 1        | 2.04%   |
| Gateway SX2185        | 1        | 2.04%   |
| Fujitsu PRIMERGY      | 1        | 2.04%   |
| Fujitsu FujitsuTP7000 | 1        | 2.04%   |
| eMachines EL1352G     | 1        | 2.04%   |
| ECS M789CG            | 1        | 2.04%   |
| ASUS Z170-E           | 1        | 2.04%   |
| ASUS TS10             | 1        | 2.04%   |
| ASUS P8H67-V          | 1        | 2.04%   |
| ASRock Z790M-ITX      | 1        | 2.04%   |
| ASRock X470           | 1        | 2.04%   |
| ASRock Q1900B-ITX     | 1        | 2.04%   |
| ASRock J3455M         | 1        | 2.04%   |
| ASRock H81M           | 1        | 2.04%   |
| ASRock H55M-LE        | 1        | 2.04%   |
| ASRock D1800B-ITX     | 1        | 2.04%   |
| ASRock 970            | 1        | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 8        | 16.33%  |
| 2013    | 6        | 12.24%  |
| 2020    | 5        | 10.2%   |
| 2018    | 5        | 10.2%   |
| 2012    | 4        | 8.16%   |
| 2010    | 4        | 8.16%   |
| 2016    | 3        | 6.12%   |
| 2011    | 3        | 6.12%   |
| 2022    | 2        | 4.08%   |
| 2007    | 2        | 4.08%   |
| 2023    | 1        | 2.04%   |
| 2017    | 1        | 2.04%   |
| 2015    | 1        | 2.04%   |
| 2009    | 1        | 2.04%   |
| 2004    | 1        | 2.04%   |
| 2001    | 1        | 2.04%   |
| Unknown | 1        | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 49       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 49       | 98%     |
| Enabled  | 1        | 2%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 49       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 12       | 22.22%  |
| 16.01-24.0      | 11       | 20.37%  |
| 4.01-8.0        | 7        | 12.96%  |
| 32.01-64.0      | 6        | 11.11%  |
| 8.01-16.0       | 6        | 11.11%  |
| 0.51-1.0        | 3        | 5.56%   |
| 2.01-3.0        | 2        | 3.7%    |
| 64.01-256.0     | 2        | 3.7%    |
| 1.01-2.0        | 2        | 3.7%    |
| 0.01-0.5        | 2        | 3.7%    |
| More than 256.0 | 1        | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 14       | 26.92%  |
| 0.01-0.5  | 14       | 26.92%  |
| 0.51-1.0  | 8        | 15.38%  |
| 3.01-4.0  | 5        | 9.62%   |
| 2.01-3.0  | 5        | 9.62%   |
| 4.01-8.0  | 3        | 5.77%   |
| 8.01-16.0 | 1        | 1.92%   |
| 0         | 1        | 1.92%   |
| Unknown   | 1        | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 22       | 43.14%  |
| 2      | 12       | 23.53%  |
| 3      | 8        | 15.69%  |
| 4      | 6        | 11.76%  |
| 5      | 2        | 3.92%   |
| 12     | 1        | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 88%     |
| Yes       | 6        | 12%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 48       | 97.96%  |
| No        | 1        | 2.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 72%     |
| Yes       | 14       | 28%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 78%     |
| Yes       | 11       | 22%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 13       | 24.07%  |
| Germany     | 6        | 11.11%  |
| Russia      | 4        | 7.41%   |
| Sweden      | 3        | 5.56%   |
| Norway      | 3        | 5.56%   |
| Brazil      | 3        | 5.56%   |
| UK          | 2        | 3.7%    |
| Spain       | 2        | 3.7%    |
| Canada      | 2        | 3.7%    |
| Argentina   | 2        | 3.7%    |
| Ukraine     | 1        | 1.85%   |
| Switzerland | 1        | 1.85%   |
| South Korea | 1        | 1.85%   |
| Portugal    | 1        | 1.85%   |
| Poland      | 1        | 1.85%   |
| Pakistan    | 1        | 1.85%   |
| Netherlands | 1        | 1.85%   |
| Mexico      | 1        | 1.85%   |
| Indonesia   | 1        | 1.85%   |
| Guatemala   | 1        | 1.85%   |
| Finland     | 1        | 1.85%   |
| China       | 1        | 1.85%   |
| Austria     | 1        | 1.85%   |
| Australia   | 1        | 1.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Springfield          | 4        | 7.41%   |
| St Petersburg        | 3        | 5.56%   |
| Manitowoc            | 3        | 5.56%   |
| Frankfurt am Main    | 2        | 3.7%    |
| As                   | 2        | 3.7%    |
| Zurich               | 1        | 1.85%   |
| Tuusula              | 1        | 1.85%   |
| Thornhill            | 1        | 1.85%   |
| Stuttgart            | 1        | 1.85%   |
| Stockholm            | 1        | 1.85%   |
| Somerset             | 1        | 1.85%   |
| Ski                  | 1        | 1.85%   |
| Salzburg             | 1        | 1.85%   |
| Redwood City         | 1        | 1.85%   |
| Penza                | 1        | 1.85%   |
| Olofstorp            | 1        | 1.85%   |
| Oberhausen           | 1        | 1.85%   |
| Nussdorf am Inn      | 1        | 1.85%   |
| Noblesville          | 1        | 1.85%   |
| Lisbon               | 1        | 1.85%   |
| Lauro de Freitas     | 1        | 1.85%   |
| Lahore               | 1        | 1.85%   |
| Kharkiv              | 1        | 1.85%   |
| Jerez de la Frontera | 1        | 1.85%   |
| Jember               | 1        | 1.85%   |
| Harrisonburg         | 1        | 1.85%   |
| Hangzhou             | 1        | 1.85%   |
| Hamburg              | 1        | 1.85%   |
| Gwacheon             | 1        | 1.85%   |
| Guatemala City       | 1        | 1.85%   |
| Gothenburg           | 1        | 1.85%   |
| Gorredijk            | 1        | 1.85%   |
| Glasgow              | 1        | 1.85%   |
| General San Martin   | 1        | 1.85%   |
| Durham               | 1        | 1.85%   |
| Czarna Białostocka  | 1        | 1.85%   |
| Chihuahua City       | 1        | 1.85%   |
| Chicago              | 1        | 1.85%   |
| Buenos Aires         | 1        | 1.85%   |
| Bradford             | 1        | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 17       | 36     | 18.09%  |
| WDC                         | 14       | 20     | 14.89%  |
| Seagate                     | 12       | 26     | 12.77%  |
| Toshiba                     | 7        | 7      | 7.45%   |
| HGST                        | 5        | 5      | 5.32%   |
| Crucial                     | 5        | 8      | 5.32%   |
| A-DATA Technology           | 5        | 7      | 5.32%   |
| SanDisk                     | 4        | 6      | 4.26%   |
| Kingston                    | 4        | 7      | 4.26%   |
| Intel                       | 3        | 4      | 3.19%   |
| Hitachi                     | 3        | 3      | 3.19%   |
| SPCC                        | 2        | 2      | 2.13%   |
| SK hynix                    | 2        | 2      | 2.13%   |
| Unknown                     | 1        | 1      | 1.06%   |
| Transcend                   | 1        | 1      | 1.06%   |
| Secure                      | 1        | 1      | 1.06%   |
| Phison Electronics          | 1        | 1      | 1.06%   |
| LITEON                      | 1        | 1      | 1.06%   |
| Lexar                       | 1        | 1      | 1.06%   |
| KIOXIA                      | 1        | 1      | 1.06%   |
| Kingston Technology Company | 1        | 1      | 1.06%   |
| Kingmax                     | 1        | 1      | 1.06%   |
| Intenso                     | 1        | 1      | 1.06%   |
| Apple                       | 1        | 3      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3        | 2.48%   |
| Seagate ST380815AS 80GB                           | 2        | 1.65%   |
| Samsung SSD 960 EVO 500GB                         | 2        | 1.65%   |
| Samsung SSD 870 QVO 1TB                           | 2        | 1.65%   |
| Samsung SSD 870 EVO 1TB                           | 2        | 1.65%   |
| Kingston SA400S3 120GB SSD                        | 2        | 1.65%   |
| WDC WDS500G2B0A 500GB SSD                         | 1        | 0.83%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                  | 1        | 0.83%   |
| WDC WDS250G2B0B 250GB SSD                         | 1        | 0.83%   |
| WDC WDS250G2B0A 250GB SSD                         | 1        | 0.83%   |
| WDC WD800AAJS-00 80GB                             | 1        | 0.83%   |
| WDC WD7500BPKT-80PK4T0 752GB                      | 1        | 0.83%   |
| WDC WD5000AZRX-00A8LB0 500GB                      | 1        | 0.83%   |
| WDC WD5000AAKX-00ERMA0 500GB                      | 1        | 0.83%   |
| WDC WD40EFZX-68AWUN0 4TB                          | 1        | 0.83%   |
| WDC WD3200AAKX-0 320GB                            | 1        | 0.83%   |
| WDC WD20EZRZ-00Z 2TB                              | 1        | 0.83%   |
| WDC WD1600JS-60NCB1 160GB                         | 1        | 0.83%   |
| WDC WD1600BEVT-2 160GB                            | 1        | 0.83%   |
| WDC WD140EDGZ-11B2DA2 14TB                        | 1        | 0.83%   |
| WDC WD120EFBX-68B0EN0 12TB                        | 1        | 0.83%   |
| WDC WD10JPVX-75JC3T0 1TB                          | 1        | 0.83%   |
| WDC WD10EZEX-75WN4A1 1TB                          | 1        | 0.83%   |
| WDC WD10EZEX-21M2NA0 1TB                          | 1        | 0.83%   |
| Unknown MMC Card  32GB                            | 1        | 0.83%   |
| Transcend SSD 1GB                                 | 1        | 0.83%   |
| Toshiba MQ04ABF100 1TB                            | 1        | 0.83%   |
| Toshiba MQ01ABF050 500GB                          | 1        | 0.83%   |
| Toshiba MK3252GS 320GB                            | 1        | 0.83%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD           | 1        | 0.83%   |
| Toshiba HDWD130 3TB                               | 1        | 0.83%   |
| Toshiba DT01ACA2 2TB                              | 1        | 0.83%   |
| Toshiba DT01ACA1 1TB                              | 1        | 0.83%   |
| SPCC Solid State Disk 120GB                       | 1        | 0.83%   |
| SPCC Solid State 120GB                            | 1        | 0.83%   |
| SK hynix SC300 M.2 2280 256 256GB SSD             | 1        | 0.83%   |
| SK hynix BC501 NVMe Solid State Drive 512GB       | 1        | 0.83%   |
| Secure Net 256GB SSD                              | 1        | 0.83%   |
| Seagate ST980310AS 80GB                           | 1        | 0.83%   |
| Seagate ST9160314AS 160GB                         | 1        | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 16     | 29.27%  |
| Seagate             | 12       | 26     | 29.27%  |
| Toshiba             | 6        | 6      | 14.63%  |
| HGST                | 5        | 5      | 12.2%   |
| Samsung Electronics | 3        | 5      | 7.32%   |
| Hitachi             | 3        | 3      | 7.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 16     | 23.68%  |
| Crucial             | 5        | 8      | 13.16%  |
| Kingston            | 4        | 5      | 10.53%  |
| Intel               | 3        | 4      | 7.89%   |
| A-DATA Technology   | 3        | 3      | 7.89%   |
| WDC                 | 2        | 4      | 5.26%   |
| SPCC                | 2        | 2      | 5.26%   |
| SanDisk             | 2        | 3      | 5.26%   |
| Transcend           | 1        | 1      | 2.63%   |
| Toshiba             | 1        | 1      | 2.63%   |
| SK hynix            | 1        | 1      | 2.63%   |
| Secure              | 1        | 1      | 2.63%   |
| LITEON              | 1        | 1      | 2.63%   |
| Lexar               | 1        | 1      | 2.63%   |
| Kingmax             | 1        | 1      | 2.63%   |
| Intenso             | 1        | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 31       | 61     | 41.89%  |
| SSD  | 27       | 53     | 36.49%  |
| NVMe | 15       | 31     | 20.27%  |
| MMC  | 1        | 1      | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 43       | 112    | 71.67%  |
| NVMe | 15       | 31     | 25%     |
| SAS  | 1        | 2      | 1.67%   |
| MMC  | 1        | 1      | 1.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 37       | 67     | 60.66%  |
| 0.51-1.0   | 10       | 20     | 16.39%  |
| 3.01-4.0   | 4        | 8      | 6.56%   |
| 1.01-2.0   | 3        | 5      | 4.92%   |
| 4.01-10.0  | 3        | 3      | 4.92%   |
| 2.01-3.0   | 2        | 2      | 3.28%   |
| 10.01-20.0 | 2        | 9      | 3.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 14       | 28%     |
| 101-250        | 9        | 18%     |
| 1-20           | 5        | 10%     |
| More than 3000 | 4        | 8%      |
| 251-500        | 4        | 8%      |
| 21-50          | 4        | 8%      |
| 2001-3000      | 3        | 6%      |
| 51-100         | 3        | 6%      |
| 1001-2000      | 2        | 4%      |
| 501-1000       | 2        | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 21       | 42%     |
| Unknown        | 14       | 28%     |
| 251-500        | 5        | 10%     |
| 21-50          | 5        | 10%     |
| 1001-2000      | 2        | 4%      |
| More than 3000 | 1        | 2%      |
| 2001-3000      | 1        | 2%      |
| 51-100         | 1        | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD3200AAKX-0 320GB             | 1        | 1      | 10%     |
| Toshiba MK3252GS 320GB             | 1        | 1      | 10%     |
| Secure Net 256GB SSD               | 1        | 1      | 10%     |
| SanDisk SDSA6MM 16GB SSD           | 1        | 1      | 10%     |
| Samsung Electronics SSD PM81 128GB | 1        | 1      | 10%     |
| Samsung Electronics SP0411N 40GB   | 1        | 2      | 10%     |
| Kingmax SSD 120G                   | 1        | 1      | 10%     |
| Hitachi HTS722080K9A300 80GB       | 1        | 1      | 10%     |
| HGST HTS725050A7 500GB             | 1        | 1      | 10%     |
| A-DATA Technology IM2P33F8ABR1-1TB | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 3      | 20%     |
| WDC                 | 1        | 1      | 10%     |
| Toshiba             | 1        | 1      | 10%     |
| Secure              | 1        | 1      | 10%     |
| SanDisk             | 1        | 1      | 10%     |
| Kingmax             | 1        | 1      | 10%     |
| Hitachi             | 1        | 1      | 10%     |
| HGST                | 1        | 1      | 10%     |
| A-DATA Technology   | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 20%     |
| Toshiba             | 1        | 1      | 20%     |
| Samsung Electronics | 1        | 2      | 20%     |
| Hitachi             | 1        | 1      | 20%     |
| HGST                | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 6      | 50%     |
| SSD  | 4        | 4      | 40%     |
| NVMe | 1        | 1      | 10%     |

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
| Works    | 36       | 100    | 63.16%  |
| Detected | 13       | 35     | 22.81%  |
| Malfunc  | 8        | 11     | 14.04%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 37       | 48.68%  |
| Samsung Electronics         | 9        | 11.84%  |
| AMD                         | 8        | 10.53%  |
| VIA Technologies            | 2        | 2.63%   |
| SanDisk                     | 2        | 2.63%   |
| Nvidia                      | 2        | 2.63%   |
| Marvell Technology Group    | 2        | 2.63%   |
| LSI Logic / Symbios Logic   | 2        | 2.63%   |
| ASMedia Technology          | 2        | 2.63%   |
| ADATA Technology            | 2        | 2.63%   |
| Adaptec                     | 2        | 2.63%   |
| SK hynix                    | 1        | 1.32%   |
| Promise Technology          | 1        | 1.32%   |
| Phison Electronics          | 1        | 1.32%   |
| KIOXIA                      | 1        | 1.32%   |
| Kingston Technology Company | 1        | 1.32%   |
| Broadcom / LSI              | 1        | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6        | 5.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 4.9%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 4.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 3.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 3.92%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3        | 2.94%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 2        | 1.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 1.96%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2        | 1.96%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 2        | 1.96%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 2        | 1.96%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2        | 1.96%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2        | 1.96%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 1.96%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.96%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 2        | 1.96%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1        | 0.98%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.98%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1        | 0.98%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1        | 0.98%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.98%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1        | 0.98%   |
| Promise PDC42819 [FastTrak TX2650/TX4650]                                      | 1        | 0.98%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1        | 0.98%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1        | 0.98%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.98%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.98%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 0.98%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 1        | 0.98%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                         | 1        | 0.98%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 1        | 0.98%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 0.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1        | 0.98%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 0.98%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 0.98%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 0.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1        | 0.98%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 37       | 52.11%  |
| NVMe | 13       | 18.31%  |
| IDE  | 11       | 15.49%  |
| RAID | 8        | 11.27%  |
| SAS  | 2        | 2.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 38       | 76%     |
| AMD          | 10       | 20%     |
| CentaurHauls | 1        | 2%      |
| Unknown      | 1        | 2%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i9-10900 CPU @ 2.80GHz      | 2        | 3.7%    |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2        | 3.7%    |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 3.7%    |
| Intel Core i3-4150 CPU @ 3.50GHz       | 2        | 3.7%    |
| Intel Celeron CPU J1900 @ 1.99GHz      | 2        | 3.7%    |
| AMD FX-8350 Eight-Core Processor       | 2        | 3.7%    |
| Intel Xeon Gold 5218 CPU @ 2.30GHz     | 1        | 1.85%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1        | 1.85%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1        | 1.85%   |
| Intel Core i7-8700T CPU @ 2.40GHz      | 1        | 1.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 1.85%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 1        | 1.85%   |
| Intel Core i7-10610U CPU @ 1.80GHz     | 1        | 1.85%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1        | 1.85%   |
| Intel Core i5-6600K CPU @ 3.50GHz      | 1        | 1.85%   |
| Intel Core i5-6500T CPU @ 2.50GHz      | 1        | 1.85%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 1        | 1.85%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 1        | 1.85%   |
| Intel Core i5-4570T CPU @ 2.90GHz      | 1        | 1.85%   |
| Intel Core i5-3450 CPU @ 3.10GHz       | 1        | 1.85%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 1.85%   |
| Intel Core i3-7130U CPU @ 2.70GHz      | 1        | 1.85%   |
| Intel Core i3-3240 CPU @ 3.40GHz       | 1        | 1.85%   |
| Intel Core i3-3220T CPU @ 2.80GHz      | 1        | 1.85%   |
| Intel Core i3-2100 CPU @ 3.10GHz       | 1        | 1.85%   |
| Intel Core i3 CPU 540 @ 3.07GHz        | 1        | 1.85%   |
| Intel Core 2 CPU 4300 @ 1.80GHz        | 1        | 1.85%   |
| Intel Celeron N5105 @ 2.00GHz          | 1        | 1.85%   |
| Intel Celeron M processor 1.00GHz      | 1        | 1.85%   |
| Intel Celeron CPU J3455 @ 1.50GHz      | 1        | 1.85%   |
| Intel Celeron CPU J1800 @ 2.41GHz      | 1        | 1.85%   |
| Intel Celeron CPU G1850 @ 2.90GHz      | 1        | 1.85%   |
| Intel Celeron CPU E3400 @ 2.60GHz      | 1        | 1.85%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz      | 1        | 1.85%   |
| Intel Atom CPU D525 @ 1.80GHz          | 1        | 1.85%   |
| Intel 13th Gen Core i9-13900           | 1        | 1.85%   |
| Intel 12th Gen Core i7-12700T          | 1        | 1.85%   |
| Intel 12th Gen Core i7-12700H          | 1        | 1.85%   |
| CentaurHauls VIA Samuel 2              | 1        | 1.85%   |
| AMD Sempron 145 Processor              | 1        | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 10       | 18.87%  |
| Intel Core i3      | 7        | 13.21%  |
| Intel Celeron      | 7        | 13.21%  |
| Other              | 6        | 11.32%  |
| Intel Core i7      | 5        | 9.43%   |
| Intel Core i9      | 2        | 3.77%   |
| Intel Atom         | 2        | 3.77%   |
| AMD Ryzen 7        | 2        | 3.77%   |
| AMD FX             | 2        | 3.77%   |
| Intel Xeon Gold    | 1        | 1.89%   |
| Intel Xeon         | 1        | 1.89%   |
| Intel Pentium Dual | 1        | 1.89%   |
| Intel Core 2       | 1        | 1.89%   |
| Intel Celeron M    | 1        | 1.89%   |
| AMD Sempron        | 1        | 1.89%   |
| AMD Ryzen 9        | 1        | 1.89%   |
| AMD G              | 1        | 1.89%   |
| AMD E1             | 1        | 1.89%   |
| AMD A8             | 1        | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 18       | 34.62%  |
| 2      | 16       | 30.77%  |
| 1      | 5        | 9.62%   |
| 8      | 3        | 5.77%   |
| 6      | 3        | 5.77%   |
| 12     | 2        | 3.85%   |
| 10     | 2        | 3.85%   |
| 32     | 1        | 1.92%   |
| 24     | 1        | 1.92%   |
| 14     | 1        | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 48       | 96%     |
| 2      | 1        | 2%      |
| 0      | 1        | 2%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 29       | 59.18%  |
| 2      | 20       | 40.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 26       | 52%     |
| 32-bit, 64-bit | 21       | 42%     |
| 32-bit         | 2        | 4%      |
| 64-bit         | 1        | 2%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 49.06%  |
| 0x306c3    | 4        | 7.55%   |
| 0x906ea    | 2        | 3.77%   |
| 0x306a9    | 2        | 3.77%   |
| 0xb0671    | 1        | 1.89%   |
| 0xa0671    | 1        | 1.89%   |
| 0xa0655    | 1        | 1.89%   |
| 0x906a3    | 1        | 1.89%   |
| 0x90672    | 1        | 1.89%   |
| 0x806ec    | 1        | 1.89%   |
| 0x6fd      | 1        | 1.89%   |
| 0x6f2      | 1        | 1.89%   |
| 0x6d8      | 1        | 1.89%   |
| 0x506c9    | 1        | 1.89%   |
| 0x406c4    | 1        | 1.89%   |
| 0x30678    | 1        | 1.89%   |
| 0x20655    | 1        | 1.89%   |
| 0x106e5    | 1        | 1.89%   |
| 0x08701021 | 1        | 1.89%   |
| 0x0800820d | 1        | 1.89%   |
| 0x06000817 | 1        | 1.89%   |
| 0x05000101 | 1        | 1.89%   |
| 0x010000b6 | 1        | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 8        | 15.09%  |
| Skylake          | 4        | 7.55%   |
| Silvermont       | 4        | 7.55%   |
| KabyLake         | 4        | 7.55%   |
| SandyBridge      | 3        | 5.66%   |
| Piledriver       | 3        | 5.66%   |
| IvyBridge        | 3        | 5.66%   |
| CometLake        | 3        | 5.66%   |
| Alderlake Hybrid | 3        | 5.66%   |
| Unknown          | 3        | 5.66%   |
| Core             | 2        | 3.77%   |
| Zen+             | 1        | 1.89%   |
| Zen 3            | 1        | 1.89%   |
| Zen 2            | 1        | 1.89%   |
| Westmere         | 1        | 1.89%   |
| Penryn           | 1        | 1.89%   |
| P6               | 1        | 1.89%   |
| Nehalem          | 1        | 1.89%   |
| K6               | 1        | 1.89%   |
| K10              | 1        | 1.89%   |
| Jaguar           | 1        | 1.89%   |
| Goldmont         | 1        | 1.89%   |
| Bonnell          | 1        | 1.89%   |
| Bobcat           | 1        | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 33       | 61.11%  |
| AMD                        | 12       | 22.22%  |
| Nvidia                     | 5        | 9.26%   |
| VIA Technologies           | 2        | 3.7%    |
| Matrox Electronics Systems | 2        | 3.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5        | 7.14%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 5.71%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4        | 5.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3        | 4.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 4.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 4.29%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 2.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 2.86%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 2.86%   |
| VIA Technologies VT8623 [Apollo CLE266] integrated CastleRock graphics                   | 1        | 1.43%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1        | 1.43%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1        | 1.43%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.43%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.43%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.43%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1        | 1.43%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1        | 1.43%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1        | 1.43%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1        | 1.43%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1        | 1.43%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 1.43%   |
| Nvidia AD102 [GeForce RTX 4090]                                                          | 1        | 1.43%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.43%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1        | 1.43%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 1        | 1.43%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 1.43%   |
| Intel HD Graphics 630                                                                    | 1        | 1.43%   |
| Intel HD Graphics 620                                                                    | 1        | 1.43%   |
| Intel HD Graphics 530                                                                    | 1        | 1.43%   |
| Intel HD Graphics 500                                                                    | 1        | 1.43%   |
| Intel DG2 [Arc A750]                                                                     | 1        | 1.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 1.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1        | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.43%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 1.43%   |
| Intel AlderLake-S GT1                                                                    | 1        | 1.43%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 1        | 1.43%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 1.43%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.43%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1        | 1.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 31       | 58.49%  |
| 1 x AMD         | 11       | 20.75%  |
| 1 x Nvidia      | 3        | 5.66%   |
| Other           | 1        | 1.89%   |
| 2 x Intel       | 1        | 1.89%   |
| 1 x VIA         | 1        | 1.89%   |
| Nvidia + Matrox | 1        | 1.89%   |
| 1 x Matrox      | 1        | 1.89%   |
| Intel + Nvidia  | 1        | 1.89%   |
| Intel + AMD     | 1        | 1.89%   |
| AMD + VIA       | 1        | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 39       | 78%     |
| Unknown     | 10       | 20%     |
| Proprietary | 1        | 2%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 39       | 78%     |
| 7.01-8.0   | 3        | 6%      |
| 0.01-0.5   | 3        | 6%      |
| 3.01-4.0   | 2        | 4%      |
| 1.01-2.0   | 1        | 2%      |
| 8.01-16.0  | 1        | 2%      |
| 0.51-1.0   | 1        | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 9        | 19.15%  |
| Samsung Electronics | 6        | 12.77%  |
| Goldstar            | 6        | 12.77%  |
| BenQ                | 5        | 10.64%  |
| AOC                 | 4        | 8.51%   |
| Philips             | 2        | 4.26%   |
| Acer                | 2        | 4.26%   |
| ViewSonic           | 1        | 2.13%   |
| Sceptre Tech        | 1        | 2.13%   |
| Mi                  | 1        | 2.13%   |
| KVM                 | 1        | 2.13%   |
| InfoVision          | 1        | 2.13%   |
| Hewlett-Packard     | 1        | 2.13%   |
| Elo Touch           | 1        | 2.13%   |
| Element             | 1        | 2.13%   |
| CTC                 | 1        | 2.13%   |
| Chimei Innolux      | 1        | 2.13%   |
| BOE                 | 1        | 2.13%   |
| Belinea             | 1        | 2.13%   |
| AU Optronics        | 1        | 2.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch     | 3        | 5.36%   |
| Dell 2009W DEL4041 1680x1050 433x271mm 20.1-inch                     | 3        | 5.36%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch             | 1        | 1.79%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch       | 1        | 1.79%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 474x296mm 22.0-inch | 1        | 1.79%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 1.79%   |
| Samsung Electronics S27A950D SAM079E 1920x1080 598x336mm 27.0-inch   | 1        | 1.79%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1        | 1.79%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch | 1        | 1.79%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 1        | 1.79%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch              | 1        | 1.79%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                     | 1        | 1.79%   |
| KVM LCD Monitor 1 1 9" KVM4308 1280x1024 338x270mm 17.0-inch         | 1        | 1.79%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch         | 1        | 1.79%   |
| Hewlett-Packard LA1751 HWP2858 1280x1024 340x270mm 17.1-inch         | 1        | 1.79%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1        | 1.79%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 1        | 1.79%   |
| Goldstar ULTRAWIDE GSM5AE2 3440x1440 800x335mm 34.1-inch             | 1        | 1.79%   |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch             | 1        | 1.79%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 1        | 1.79%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 1.79%   |
| Goldstar M227WD GSM56D5 1920x1080 480x270mm 21.7-inch                | 1        | 1.79%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch          | 1        | 1.79%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                | 1        | 1.79%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 1        | 1.79%   |
| Elo Touch ET1717L ELO1717 1280x1024 338x270mm 17.0-inch              | 1        | 1.79%   |
| Element ELCFW329 ELE1366 1366x768 700x390mm 31.5-inch                | 1        | 1.79%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                    | 1        | 1.79%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                    | 1        | 1.79%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1        | 1.79%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                   | 1        | 1.79%   |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                    | 1        | 1.79%   |
| Dell E1911 DELF037 1440x900 408x255mm 18.9-inch                      | 1        | 1.79%   |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                    | 1        | 1.79%   |
| Dell 1905FP DEL400C 1280x1024 380x310mm 19.3-inch                    | 1        | 1.79%   |
| CTC KD02909-8770A CTC0770 1024x768 304x228mm 15.0-inch               | 1        | 1.79%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch     | 1        | 1.79%   |
| BOE LCD Monitor BOE09F1 1920x1080 355x200mm 16.0-inch                | 1        | 1.79%   |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                 | 1        | 1.79%   |
| BenQ ZOWIE RL LCD BNQ7F4F 1920x1080 531x299mm 24.0-inch              | 1        | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 27.27%  |
| 1680x1050 (WSXGA+) | 5        | 11.36%  |
| 1280x1024 (SXGA)   | 5        | 11.36%  |
| 3840x2160 (4K)     | 4        | 9.09%   |
| 3440x1440          | 4        | 9.09%   |
| 2560x1440 (QHD)    | 4        | 9.09%   |
| 1440x900 (WXGA+)   | 2        | 4.55%   |
| 1024x768 (XGA)     | 2        | 4.55%   |
| 2560x1080          | 1        | 2.27%   |
| 1920x1200 (WUXGA)  | 1        | 2.27%   |
| 1600x900 (HD+)     | 1        | 2.27%   |
| 1366x768 (WXGA)    | 1        | 2.27%   |
| 1360x768           | 1        | 2.27%   |
| 1280x960           | 1        | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 7        | 14.58%  |
| 20     | 5        | 10.42%  |
| 34     | 4        | 8.33%   |
| 24     | 4        | 8.33%   |
| 23     | 4        | 8.33%   |
| 21     | 4        | 8.33%   |
| 19     | 4        | 8.33%   |
| 17     | 4        | 8.33%   |
| 15     | 3        | 6.25%   |
| 18     | 2        | 4.17%   |
| 72     | 1        | 2.08%   |
| 32     | 1        | 2.08%   |
| 31     | 1        | 2.08%   |
| 25     | 1        | 2.08%   |
| 22     | 1        | 2.08%   |
| 16     | 1        | 2.08%   |
| 14     | 1        | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 31.71%  |
| 401-500     | 11       | 26.83%  |
| 301-350     | 6        | 14.63%  |
| 701-800     | 4        | 9.76%   |
| 351-400     | 4        | 9.76%   |
| 601-700     | 2        | 4.88%   |
| 1501-2000   | 1        | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 16       | 44.44%  |
| 16/10 | 8        | 22.22%  |
| 5/4   | 5        | 13.89%  |
| 21/9  | 4        | 11.11%  |
| 4/3   | 2        | 5.56%   |
| 6/5   | 1        | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 10       | 23.81%  |
| 201-250        | 9        | 21.43%  |
| 301-350        | 7        | 16.67%  |
| 351-500        | 5        | 11.9%   |
| 141-150        | 4        | 9.52%   |
| 101-110        | 3        | 7.14%   |
| More than 1000 | 1        | 2.38%   |
| 81-90          | 1        | 2.38%   |
| 251-300        | 1        | 2.38%   |
| 131-140        | 1        | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 22       | 61.11%  |
| 101-120 | 7        | 19.44%  |
| 1-50    | 4        | 11.11%  |
| 121-160 | 2        | 5.56%   |
| 161-240 | 1        | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 31       | 59.62%  |
| 0     | 16       | 30.77%  |
| 2     | 3        | 5.77%   |
| 4     | 1        | 1.92%   |
| 3     | 1        | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 25       | 34.72%  |
| Intel                           | 22       | 30.56%  |
| Qualcomm Atheros                | 5        | 6.94%   |
| Broadcom                        | 5        | 6.94%   |
| Xiaomi                          | 2        | 2.78%   |
| VIA Technologies                | 2        | 2.78%   |
| MediaTek                        | 2        | 2.78%   |
| TP-Link                         | 1        | 1.39%   |
| T & A Mobile Phones             | 1        | 1.39%   |
| Qualcomm Atheros Communications | 1        | 1.39%   |
| Qualcomm                        | 1        | 1.39%   |
| Nvidia                          | 1        | 1.39%   |
| NetGear                         | 1        | 1.39%   |
| DisplayLink                     | 1        | 1.39%   |
| D-Link System                   | 1        | 1.39%   |
| ASIX Electronics                | 1        | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 20       | 21.28%  |
| Intel Ethernet Controller I225-V                                        | 4        | 4.26%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3        | 3.19%   |
| Intel Ethernet Connection (2) I219-V                                    | 3        | 3.19%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 2        | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2        | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2        | 2.13%   |
| Intel I211 Gigabit Network Connection                                   | 2        | 2.13%   |
| Intel Ethernet Connection (7) I219-V                                    | 2        | 2.13%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2        | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2        | 2.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1        | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1        | 1.06%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1        | 1.06%   |
| T & A Mobile Phones TCL 20E                                             | 1        | 1.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1        | 1.06%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1        | 1.06%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 1.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1        | 1.06%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller               | 1        | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1        | 1.06%   |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                        | 1        | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1        | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 1.06%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1        | 1.06%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 1.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1        | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 1.06%   |
| Nvidia MCP61 Ethernet                                                   | 1        | 1.06%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                   | 1        | 1.06%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 1.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1        | 1.06%   |
| Intel Wireless 8265 / 8275                                              | 1        | 1.06%   |
| Intel I210 Gigabit Network Connection                                   | 1        | 1.06%   |
| Intel Ethernet Controller I226-V                                        | 1        | 1.06%   |
| Intel Ethernet Controller I219-V                                        | 1        | 1.06%   |
| Intel Ethernet Connection I217-LM                                       | 1        | 1.06%   |
| Intel Ethernet Connection (7) I219-LM                                   | 1        | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                                   | 1        | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1        | 1.06%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 27.27%  |
| Realtek Semiconductor           | 5        | 22.73%  |
| Qualcomm Atheros                | 3        | 13.64%  |
| Broadcom                        | 3        | 13.64%  |
| MediaTek                        | 2        | 9.09%   |
| TP-Link                         | 1        | 4.55%   |
| Qualcomm Atheros Communications | 1        | 4.55%   |
| NetGear                         | 1        | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2        | 8%      |
| Intel Comet Lake PCH CNVi WiFi                                          | 2        | 8%      |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1        | 4%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1        | 4%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1        | 4%      |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 4%      |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller               | 1        | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1        | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 4%      |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 4%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 4%      |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                   | 1        | 4%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 4%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1        | 4%      |
| Intel Wireless 8265 / 8275                                              | 1        | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 4%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1        | 4%      |
| Intel Centrino Wireless-N 105                                           | 1        | 4%      |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1        | 4%      |
| Intel 700 Series Chipset Family Wi-Fi                                   | 1        | 4%      |
| Broadcom BCM4378 802.11ax Dual Band Wireless Network Adapter            | 1        | 4%      |
| Broadcom BCM43227 802.11b/g/n                                           | 1        | 4%      |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1        | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 24       | 39.34%  |
| Intel                 | 22       | 36.07%  |
| Broadcom              | 3        | 4.92%   |
| Xiaomi                | 2        | 3.28%   |
| VIA Technologies      | 2        | 3.28%   |
| Qualcomm Atheros      | 2        | 3.28%   |
| T & A Mobile Phones   | 1        | 1.64%   |
| Qualcomm              | 1        | 1.64%   |
| Nvidia                | 1        | 1.64%   |
| DisplayLink           | 1        | 1.64%   |
| D-Link System         | 1        | 1.64%   |
| ASIX Electronics      | 1        | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 20       | 29.41%  |
| Intel Ethernet Controller I225-V                                      | 4        | 5.88%   |
| Realtek RTL8125 2.5GbE Controller                                     | 3        | 4.41%   |
| Intel Ethernet Connection (2) I219-V                                  | 3        | 4.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                          | 2        | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 2        | 2.94%   |
| Intel I211 Gigabit Network Connection                                 | 2        | 2.94%   |
| Intel Ethernet Connection (7) I219-V                                  | 2        | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 2        | 2.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 1        | 1.47%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                  | 1        | 1.47%   |
| T & A Mobile Phones TCL 20E                                           | 1        | 1.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 1        | 1.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1        | 1.47%   |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                      | 1        | 1.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                             | 1        | 1.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1        | 1.47%   |
| Nvidia MCP61 Ethernet                                                 | 1        | 1.47%   |
| Intel I210 Gigabit Network Connection                                 | 1        | 1.47%   |
| Intel Ethernet Controller I226-V                                      | 1        | 1.47%   |
| Intel Ethernet Controller I219-V                                      | 1        | 1.47%   |
| Intel Ethernet Connection I217-LM                                     | 1        | 1.47%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1        | 1.47%   |
| Intel Ethernet Connection (4) I219-LM                                 | 1        | 1.47%   |
| Intel Ethernet Connection (2) I219-LM                                 | 1        | 1.47%   |
| Intel Ethernet Connection (17) I219-LM                                | 1        | 1.47%   |
| Intel 82578DM Gigabit Network Connection                              | 1        | 1.47%   |
| Intel 82567V-4 Gigabit Network Connection                             | 1        | 1.47%   |
| Intel 82566DM-2 Gigabit Network Connection                            | 1        | 1.47%   |
| Intel 82562V-2 10/100 Network Connection                              | 1        | 1.47%   |
| DisplayLink Dell D3100 Docking Station                                | 1        | 1.47%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                       | 1        | 1.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                     | 1        | 1.47%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1        | 1.47%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1        | 1.47%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1        | 1.47%   |
| ASIX AX88179 Gigabit Ethernet                                         | 1        | 1.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 76.19%  |
| WiFi     | 14       | 22.22%  |
| Unknown  | 1        | 1.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 89.8%   |
| WiFi     | 5        | 10.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 30       | 58.82%  |
| 2     | 16       | 31.37%  |
| 3     | 3        | 5.88%   |
| 5     | 1        | 1.96%   |
| 4     | 1        | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 38       | 77.55%  |
| Yes  | 11       | 22.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 5        | 27.78%  |
| Cambridge Silicon Radio         | 4        | 22.22%  |
| IMC Networks                    | 2        | 11.11%  |
| Qualcomm Atheros Communications | 1        | 5.56%   |
| MediaTek                        | 1        | 5.56%   |
| Foxconn / Hon Hai               | 1        | 5.56%   |
| Edimax Technology               | 1        | 5.56%   |
| Broadcom                        | 1        | 5.56%   |
| Apple                           | 1        | 5.56%   |
| Actions                         | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 22.22%  |
| Intel AX201 Bluetooth                               | 3        | 16.67%  |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 5.56%   |
| MediaTek Wireless_Device                            | 1        | 5.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5.56%   |
| Intel Bluetooth Device                              | 1        | 5.56%   |
| IMC Networks Wireless_Device                        | 1        | 5.56%   |
| IMC Networks Bluetooth Device                       | 1        | 5.56%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 5.56%   |
| Edimax Bluetooth Adapter                            | 1        | 5.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 5.56%   |
| Apple Bluetooth Host Controller                     | 1        | 5.56%   |
| Actions general adapter                             | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 32       | 54.24%  |
| AMD                                  | 13       | 22.03%  |
| Nvidia                               | 4        | 6.78%   |
| VIA Technologies                     | 2        | 3.39%   |
| Thesycon Systemsoftware & Consulting | 1        | 1.69%   |
| Texas Instruments                    | 1        | 1.69%   |
| RODE Microphones                     | 1        | 1.69%   |
| Native Instruments                   | 1        | 1.69%   |
| Logitech                             | 1        | 1.69%   |
| Generalplus Technology               | 1        | 1.69%   |
| Creative Labs                        | 1        | 1.69%   |
| C-Media Electronics                  | 1        | 1.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 6.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 5.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 4.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 4.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 3.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3        | 3.41%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 3.41%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 2        | 2.27%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 2.27%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 2.27%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 2.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 2.27%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.27%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 2.27%   |
| AMD FCH Azalia Controller                                                  | 2        | 2.27%   |
| Thesycon Systemsoftware & Consulting DX3 Pro+                              | 1        | 1.14%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.14%   |
| RODE Microphones RODE NT-USB Mini                                          | 1        | 1.14%   |
| Nvidia MCP89 High Definition Audio                                         | 1        | 1.14%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.14%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.14%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1.14%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.14%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.14%   |
| Nvidia Audio device                                                        | 1        | 1.14%   |
| Nvidia AD102 High Definition Audio Controller                              | 1        | 1.14%   |
| Native Instruments Komplete Audio 2                                        | 1        | 1.14%   |
| Logitech PRO                                                               | 1        | 1.14%   |
| Logitech G935 Gaming Headset                                               | 1        | 1.14%   |
| Intel USB PnP Sound Device                                                 | 1        | 1.14%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 1.14%   |
| Intel Sunrise Point-LP HD Audio                                            | 1        | 1.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 1.14%   |
| Intel DG2 Audio Controller                                                 | 1        | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1        | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 1.14%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 1.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1        | 1.14%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 8        | 12.9%   |
| Kingston            | 8        | 12.9%   |
| Crucial             | 8        | 12.9%   |
| Unknown             | 7        | 11.29%  |
| SK hynix            | 6        | 9.68%   |
| Micron Technology   | 4        | 6.45%   |
| Elpida              | 4        | 6.45%   |
| Corsair             | 4        | 6.45%   |
| A-DATA Technology   | 2        | 3.23%   |
| Visipro             | 1        | 1.61%   |
| Team                | 1        | 1.61%   |
| Qimonda             | 1        | 1.61%   |
| PNY                 | 1        | 1.61%   |
| Patriot             | 1        | 1.61%   |
| Novatech            | 1        | 1.61%   |
| Lexar               | 1        | 1.61%   |
| Hewlett-Packard     | 1        | 1.61%   |
| G.Skill             | 1        | 1.61%   |
| Cors                | 1        | 1.61%   |
| Unknown             | 1        | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s        | 2        | 2.67%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s   | 2        | 2.67%   |
| Visipro RAM T2G88S1-H9H 2GB DIMM DDR3 1333MT/s             | 1        | 1.33%   |
| Unknown RAM Module 512MB DIMM                              | 1        | 1.33%   |
| Unknown RAM Module 4GB DIMM SDRAM                          | 1        | 1.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                  | 1        | 1.33%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                   | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s               | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s               | 1        | 1.33%   |
| Unknown RAM Module 128MB DIMM                              | 1        | 1.33%   |
| Unknown RAM Module 1024MB DIMM SDRAM                       | 1        | 1.33%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s        | 1        | 1.33%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1        | 1.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s       | 1        | 1.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s  | 1        | 1.33%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1        | 1.33%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s       | 1        | 1.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1        | 1.33%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                | 1        | 1.33%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                  | 1        | 1.33%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s     | 1        | 1.33%   |
| Samsung RAM M378B5773DH0-CK0 2048MB DIMM DDR3 1600MT/s     | 1        | 1.33%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s        | 1        | 1.33%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 1.33%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s        | 1        | 1.33%   |
| Samsung RAM M3 78T2953EZ3-CE6 1GB DIMM DDR2 1331MT/s       | 1        | 1.33%   |
| Samsung RAM 4D34373142353237 4GB SODIMM DDR3 1600MT/s      | 1        | 1.33%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s           | 1        | 1.33%   |
| PNY RAM Module 1GB DIMM DDR2 667MT/s                       | 1        | 1.33%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s             | 1        | 1.33%   |
| Novatech RAM N3S02H1600B-L67LR0 2GB DIMM DDR3 1333MT/s     | 1        | 1.33%   |
| Micron RAM Module 4GB SODIMM DDR3 1067MT/s                 | 1        | 1.33%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                | 1        | 1.33%   |
| Micron RAM 8KTF51264AZ-1G9P1 4GB DIMM DDR3 1866MT/s        | 1        | 1.33%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s        | 1        | 1.33%   |
| Micron RAM 4ATF1G64HZ-3G2B1 8GB Row Of Chips DDR4 3200MT/s | 1        | 1.33%   |
| Micron RAM 16ATF4G64HZ-3G2F1 32GB SODIMM DDR4 3200MT/s     | 1        | 1.33%   |
| Lexar RAM LD4AS032G-H2666G 32GB SODIMM DDR4 2667MT/s       | 1        | 1.33%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s        | 1        | 1.33%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1923MT/s        | 1        | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 26       | 56.52%  |
| DDR4    | 11       | 23.91%  |
| SDRAM   | 4        | 8.7%    |
| DDR5    | 2        | 4.35%   |
| DDR2    | 2        | 4.35%   |
| Unknown | 1        | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 36       | 81.82%  |
| SODIMM       | 7        | 15.91%  |
| Row Of Chips | 1        | 2.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 15       | 29.41%  |
| 4096  | 13       | 25.49%  |
| 2048  | 9        | 17.65%  |
| 32768 | 5        | 9.8%    |
| 1024  | 4        | 7.84%   |
| 16384 | 3        | 5.88%   |
| 512   | 1        | 1.96%   |
| 128   | 1        | 1.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 20       | 35.09%  |
| 1333    | 6        | 10.53%  |
| 3600    | 4        | 7.02%   |
| 3200    | 3        | 5.26%   |
| 2400    | 3        | 5.26%   |
| Unknown | 3        | 5.26%   |
| 3800    | 2        | 3.51%   |
| 2667    | 2        | 3.51%   |
| 1866    | 2        | 3.51%   |
| 667     | 2        | 3.51%   |
| 8400    | 1        | 1.75%   |
| 5808    | 1        | 1.75%   |
| 4800    | 1        | 1.75%   |
| 3000    | 1        | 1.75%   |
| 2200    | 1        | 1.75%   |
| 2133    | 1        | 1.75%   |
| 1800    | 1        | 1.75%   |
| 1331    | 1        | 1.75%   |
| 1067    | 1        | 1.75%   |
| 800     | 1        | 1.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| HP LaserJet 1020 | 1        | 50%     |
| HP Deskjet 3050A | 1        | 50%     |

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
| Z-Star Microelectronics                | 2        | 18.18%  |
| Trust                                  | 1        | 9.09%   |
| Samsung Electronics                    | 1        | 9.09%   |
| Realtek Semiconductor                  | 1        | 9.09%   |
| Microdia                               | 1        | 9.09%   |
| Luxvisions Innotech Limited            | 1        | 9.09%   |
| Logitech                               | 1        | 9.09%   |
| Chicony Electronics                    | 1        | 9.09%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 9.09%   |
| Bison Electronics                      | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Z-Star Vimicro USB2.0 Camera                                    | 1        | 8.33%   |
| Z-Star A4 TECH USB2.0 PC Camera J                               | 1        | 8.33%   |
| Trust QHD Webcam                                                | 1        | 8.33%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1        | 8.33%   |
| Realtek Integrated_Webcam_HD                                    | 1        | 8.33%   |
| Microdia Integrated_Webcam_HD                                   | 1        | 8.33%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1        | 8.33%   |
| Logitech Webcam C270                                            | 1        | 8.33%   |
| Logitech Webcam C170                                            | 1        | 8.33%   |
| Chicony HD Webcam                                               | 1        | 8.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1        | 8.33%   |
| Bison Integrated Camera                                         | 1        | 8.33%   |

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
| 0     | 36       | 67.92%  |
| 1     | 7        | 13.21%  |
| 2     | 5        | 9.43%   |
| 4     | 2        | 3.77%   |
| 3     | 2        | 3.77%   |
| 7     | 1        | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 11       | 34.38%  |
| Net/wireless             | 5        | 15.63%  |
| Communication controller | 5        | 15.63%  |
| Storage/ata              | 2        | 6.25%   |
| Net/ethernet             | 2        | 6.25%   |
| Unassigned class         | 1        | 3.13%   |
| Sound                    | 1        | 3.13%   |
| Network                  | 1        | 3.13%   |
| Multimedia controller    | 1        | 3.13%   |
| Fingerprint reader       | 1        | 3.13%   |
| Camera                   | 1        | 3.13%   |
| Bluetooth                | 1        | 3.13%   |

