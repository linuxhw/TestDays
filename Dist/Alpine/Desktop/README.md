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

Total: 73

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Z87M-PLUS                   | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Dell          | 096JG8 A01                  | [00e5bebc6a](https://linux-hardware.org/?probe=00e5bebc6a) | Sep 06, 2023 |
| ASUSTek       | Z87M-PLUS                   | [30368099b8](https://linux-hardware.org/?probe=30368099b8) | Sep 06, 2023 |
| ASUSTek       | Z87M-PLUS                   | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| ASUSTek       | Z87M-PLUS                   | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| ASUSTek       | Z87M-PLUS                   | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| ASUSTek       | Z87M-PLUS                   | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| ASUSTek       | Z87M-PLUS                   | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
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
| ASUSTek       | Z87M-PLUS                   | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
| ASRock        | X470 Master SLI/ac          | [d8f1121a19](https://linux-hardware.org/?probe=d8f1121a19) | Jan 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [68a73ee517](https://linux-hardware.org/?probe=68a73ee517) | Jan 19, 2023 |
| ASRock        | X470 Master SLI/ac          | [6b6a4929de](https://linux-hardware.org/?probe=6b6a4929de) | Jan 16, 2023 |
| ASRock        | X470 Master SLI/ac          | [8775308115](https://linux-hardware.org/?probe=8775308115) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | [473b4d0e6e](https://linux-hardware.org/?probe=473b4d0e6e) | Jan 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [747c3d8c1f](https://linux-hardware.org/?probe=747c3d8c1f) | Jan 11, 2023 |
| Gigabyte      | X570S AERO G                | [053b8697ce](https://linux-hardware.org/?probe=053b8697ce) | Jan 06, 2023 |
| Dell          | 0J1C3P A00                  | [5da7f2d3a9](https://linux-hardware.org/?probe=5da7f2d3a9) | Dec 27, 2022 |
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
| ASUSTek       | Z87M-PLUS                   | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
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
| ASUSTek       | Z87M-PLUS                   | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
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
| Alpine 3.12.0               | 6        | 12.24%  |
| Alpine 3.17_alpha20220809   | 4        | 8.16%   |
| Alpine 3.15.4               | 4        | 8.16%   |
| Alpine 3.18.0               | 3        | 6.12%   |
| Alpine 3.16.0               | 3        | 6.12%   |
| Alpine 3.13.0_alpha20200626 | 3        | 6.12%   |
| Alpine 3.18.2               | 2        | 4.08%   |
| Alpine 3.17.2               | 2        | 4.08%   |
| Alpine 3.17.1               | 2        | 4.08%   |
| Alpine 3.16.1               | 2        | 4.08%   |
| Alpine 3.11.2               | 2        | 4.08%   |
| Alpine 3.8.4                | 1        | 2.04%   |
| Alpine 3.19_alpha20230901   | 1        | 2.04%   |
| Alpine 3.17.4               | 1        | 2.04%   |
| Alpine 3.17.0               | 1        | 2.04%   |
| Alpine 3.16.3               | 1        | 2.04%   |
| Alpine 3.16.2               | 1        | 2.04%   |
| Alpine 3.16.0_alpha20220328 | 1        | 2.04%   |
| Alpine 3.15.6               | 1        | 2.04%   |
| Alpine 3.15.0               | 1        | 2.04%   |
| Alpine 3.14.2               | 1        | 2.04%   |
| Alpine 3.14.0               | 1        | 2.04%   |
| Alpine 3.13.6               | 1        | 2.04%   |
| Alpine 3.13.2               | 1        | 2.04%   |
| Alpine 3.13.1               | 1        | 2.04%   |
| Alpine 3.13.0_alpha20201218 | 1        | 2.04%   |
| Alpine 3.12.3               | 1        | 2.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Alpine | 44       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.43-1-lts      | 5        | 10.2%   |
| 5.15.60-0-lts     | 2        | 4.08%   |
| 6.3.3-0-edge      | 1        | 2.04%   |
| 6.1.51-0-lts      | 1        | 2.04%   |
| 6.1.36-0-lts      | 1        | 2.04%   |
| 6.1.34-0-lts      | 1        | 2.04%   |
| 6.1.30-0-lts      | 1        | 2.04%   |
| 6.1.28-2-lts      | 1        | 2.04%   |
| 6.0.10-0-edge     | 1        | 2.04%   |
| 5.8.0             | 1        | 2.04%   |
| 5.7.4             | 1        | 2.04%   |
| 5.4.84-0-lts      | 1        | 2.04%   |
| 5.4.6-0-lts       | 1        | 2.04%   |
| 5.4.58-0-lts      | 1        | 2.04%   |
| 5.4.57-0-lts      | 1        | 2.04%   |
| 5.4.0-77-generic  | 1        | 2.04%   |
| 5.19.0-50-generic | 1        | 2.04%   |
| 5.18.0-0-asahi    | 1        | 2.04%   |
| 5.17.9-0-edge     | 1        | 2.04%   |
| 5.17.3-0-edge     | 1        | 2.04%   |
| 5.15.98-0-lts     | 1        | 2.04%   |
| 5.15.87-0-lts     | 1        | 2.04%   |
| 5.15.86-0-lts     | 1        | 2.04%   |
| 5.15.83-0-lts     | 1        | 2.04%   |
| 5.15.80           | 1        | 2.04%   |
| 5.15.74-0-lts     | 1        | 2.04%   |
| 5.15.70-0-lts     | 1        | 2.04%   |
| 5.15.64-1-pve     | 1        | 2.04%   |
| 5.15.57-0-lts     | 1        | 2.04%   |
| 5.15.46-1-lts     | 1        | 2.04%   |
| 5.15.40-0-lts     | 1        | 2.04%   |
| 5.15.38-0-lts     | 1        | 2.04%   |
| 5.15.32-0-lts     | 1        | 2.04%   |
| 5.15.17-0-lts     | 1        | 2.04%   |
| 5.15.0-82-generic | 1        | 2.04%   |
| 5.14.0-1054-oem   | 1        | 2.04%   |
| 5.10.81           | 1        | 2.04%   |
| 5.10.61-0-lts     | 1        | 2.04%   |
| 5.10.16-0-lts     | 1        | 2.04%   |
| 5.10.12-0-lts     | 1        | 2.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.43  | 5        | 10.2%   |
| 5.15.60 | 2        | 4.08%   |
| 6.3.3   | 1        | 2.04%   |
| 6.1.51  | 1        | 2.04%   |
| 6.1.36  | 1        | 2.04%   |
| 6.1.34  | 1        | 2.04%   |
| 6.1.30  | 1        | 2.04%   |
| 6.1.28  | 1        | 2.04%   |
| 6.0.10  | 1        | 2.04%   |
| 5.8.0   | 1        | 2.04%   |
| 5.7.4   | 1        | 2.04%   |
| 5.4.84  | 1        | 2.04%   |
| 5.4.6   | 1        | 2.04%   |
| 5.4.58  | 1        | 2.04%   |
| 5.4.57  | 1        | 2.04%   |
| 5.4.0   | 1        | 2.04%   |
| 5.19.0  | 1        | 2.04%   |
| 5.18.0  | 1        | 2.04%   |
| 5.17.9  | 1        | 2.04%   |
| 5.17.3  | 1        | 2.04%   |
| 5.15.98 | 1        | 2.04%   |
| 5.15.87 | 1        | 2.04%   |
| 5.15.86 | 1        | 2.04%   |
| 5.15.83 | 1        | 2.04%   |
| 5.15.80 | 1        | 2.04%   |
| 5.15.74 | 1        | 2.04%   |
| 5.15.70 | 1        | 2.04%   |
| 5.15.64 | 1        | 2.04%   |
| 5.15.57 | 1        | 2.04%   |
| 5.15.46 | 1        | 2.04%   |
| 5.15.40 | 1        | 2.04%   |
| 5.15.38 | 1        | 2.04%   |
| 5.15.32 | 1        | 2.04%   |
| 5.15.17 | 1        | 2.04%   |
| 5.15.0  | 1        | 2.04%   |
| 5.14.0  | 1        | 2.04%   |
| 5.10.81 | 1        | 2.04%   |
| 5.10.61 | 1        | 2.04%   |
| 5.10.16 | 1        | 2.04%   |
| 5.10.12 | 1        | 2.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 16       | 33.33%  |
| 5.4     | 10       | 20.83%  |
| 6.1     | 5        | 10.42%  |
| 5.10    | 5        | 10.42%  |
| 5.17    | 2        | 4.17%   |
| 6.3     | 1        | 2.08%   |
| 6.0     | 1        | 2.08%   |
| 5.8     | 1        | 2.08%   |
| 5.7     | 1        | 2.08%   |
| 5.19    | 1        | 2.08%   |
| 5.18    | 1        | 2.08%   |
| 5.14    | 1        | 2.08%   |
| 4.4     | 1        | 2.08%   |
| 4.14    | 1        | 2.08%   |
| 3.10    | 1        | 2.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 40       | 90.91%  |
| i686    | 3        | 6.82%   |
| aarch64 | 1        | 2.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 36       | 81.82%  |
| XFCE    | 3        | 6.82%   |
| GNOME   | 2        | 4.55%   |
| sway    | 1        | 2.27%   |
| KDE5    | 1        | 2.27%   |
| i3      | 1        | 2.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 32       | 72.73%  |
| X11     | 9        | 20.45%  |
| Wayland | 3        | 6.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 41       | 93.18%  |
| LightDM | 2        | 4.55%   |
| SDDM    | 1        | 2.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 28       | 62.22%  |
| Unknown | 15       | 33.33%  |
| pt_BR   | 1        | 2.22%   |
| en_US   | 1        | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 28       | 62.22%  |
| EFI  | 17       | 37.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 35       | 77.78%  |
| Overlay | 3        | 6.67%   |
| Btrfs   | 3        | 6.67%   |
| Tmpfs   | 2        | 4.44%   |
| Zfs     | 1        | 2.22%   |
| Unknown | 1        | 2.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 28       | 60.87%  |
| GPT     | 13       | 28.26%  |
| MBR     | 5        | 10.87%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 81.82%  |
| Yes       | 8        | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 91.11%  |
| Yes       | 4        | 8.89%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 8        | 18.18%  |
| Dell                | 7        | 15.91%  |
| Gigabyte Technology | 5        | 11.36%  |
| ASRock              | 5        | 11.36%  |
| Intel               | 3        | 6.82%   |
| Hewlett-Packard     | 3        | 6.82%   |
| MSI                 | 2        | 4.55%   |
| Lenovo              | 2        | 4.55%   |
| Fujitsu             | 2        | 4.55%   |
| Unknown             | 2        | 4.55%   |
| VIA Technologies    | 1        | 2.27%   |
| UGREEN              | 1        | 2.27%   |
| Shuttle             | 1        | 2.27%   |
| Gateway             | 1        | 2.27%   |
| eMachines           | 1        | 2.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 3        | 6.82%   |
| Gigabyte Z490I AORUS ULTRA         | 2        | 4.55%   |
| Unknown                            | 2        | 4.55%   |
| VIA KM266APro-835                  | 1        | 2.27%   |
| UGREEN DX4600                      | 1        | 2.27%   |
| Shuttle DS81D                      | 1        | 2.27%   |
| MSI MS-7C82                        | 1        | 2.27%   |
| MSI MS-7877                        | 1        | 2.27%   |
| Lenovo ThinkCentre M93p 10AB0016US | 1        | 2.27%   |
| Lenovo H535 10117                  | 1        | 2.27%   |
| Intel DQ67SW                       | 1        | 2.27%   |
| Intel DH61BF AAG81311-101          | 1        | 2.27%   |
| Intel D525MW AAE93082-401          | 1        | 2.27%   |
| HP ProLiant MicroServer Gen8       | 1        | 2.27%   |
| HP EliteDesk 800 G4 DM 35W         | 1        | 2.27%   |
| HP Compaq 4000 Pro SFF PC          | 1        | 2.27%   |
| Gigabyte Z170X-UD5                 | 1        | 2.27%   |
| Gigabyte X570S AERO G              | 1        | 2.27%   |
| Gigabyte B550 AORUS ELITE V2       | 1        | 2.27%   |
| Gateway SX2185                     | 1        | 2.27%   |
| Fujitsu PRIMERGY TX100 S2          | 1        | 2.27%   |
| Fujitsu FujitsuTP7000              | 1        | 2.27%   |
| eMachines EL1352G                  | 1        | 2.27%   |
| Dell Precision 3660                | 1        | 2.27%   |
| Dell OptiPlex 755                  | 1        | 2.27%   |
| Dell OptiPlex 7040                 | 1        | 2.27%   |
| Dell OptiPlex 5000                 | 1        | 2.27%   |
| Dell OptiPlex 3020M                | 1        | 2.27%   |
| Dell OptiPlex 3010                 | 1        | 2.27%   |
| Dell Inspiron 3647                 | 1        | 2.27%   |
| ASUS Z170-E                        | 1        | 2.27%   |
| ASUS TS10                          | 1        | 2.27%   |
| ASUS PRIME H370M-PLUS              | 1        | 2.27%   |
| ASUS PRIME B360M-C                 | 1        | 2.27%   |
| ASUS P8H67-V                       | 1        | 2.27%   |
| ASRock X470 Master SLI/ac          | 1        | 2.27%   |
| ASRock J3455M                      | 1        | 2.27%   |
| ASRock H81M                        | 1        | 2.27%   |
| ASRock D1800B-ITX                  | 1        | 2.27%   |
| ASRock 970 Extreme4                | 1        | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 5        | 11.36%  |
| ASUS All              | 3        | 6.82%   |
| Gigabyte Z490I        | 2        | 4.55%   |
| ASUS PRIME            | 2        | 4.55%   |
| Unknown               | 2        | 4.55%   |
| VIA KM266APro-835     | 1        | 2.27%   |
| UGREEN DX4600         | 1        | 2.27%   |
| Shuttle DS81D         | 1        | 2.27%   |
| MSI MS-7C82           | 1        | 2.27%   |
| MSI MS-7877           | 1        | 2.27%   |
| Lenovo ThinkCentre    | 1        | 2.27%   |
| Lenovo H535           | 1        | 2.27%   |
| Intel DQ67SW          | 1        | 2.27%   |
| Intel DH61BF          | 1        | 2.27%   |
| Intel D525MW          | 1        | 2.27%   |
| HP ProLiant           | 1        | 2.27%   |
| HP EliteDesk          | 1        | 2.27%   |
| HP Compaq             | 1        | 2.27%   |
| Gigabyte Z170X-UD5    | 1        | 2.27%   |
| Gigabyte X570S        | 1        | 2.27%   |
| Gigabyte B550         | 1        | 2.27%   |
| Gateway SX2185        | 1        | 2.27%   |
| Fujitsu PRIMERGY      | 1        | 2.27%   |
| Fujitsu FujitsuTP7000 | 1        | 2.27%   |
| eMachines EL1352G     | 1        | 2.27%   |
| Dell Precision        | 1        | 2.27%   |
| Dell Inspiron         | 1        | 2.27%   |
| ASUS Z170-E           | 1        | 2.27%   |
| ASUS TS10             | 1        | 2.27%   |
| ASUS P8H67-V          | 1        | 2.27%   |
| ASRock X470           | 1        | 2.27%   |
| ASRock J3455M         | 1        | 2.27%   |
| ASRock H81M           | 1        | 2.27%   |
| ASRock D1800B-ITX     | 1        | 2.27%   |
| ASRock 970            | 1        | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 7        | 15.91%  |
| 2020    | 5        | 11.36%  |
| 2018    | 5        | 11.36%  |
| 2013    | 5        | 11.36%  |
| 2012    | 5        | 11.36%  |
| 2016    | 3        | 6.82%   |
| 2011    | 3        | 6.82%   |
| 2010    | 3        | 6.82%   |
| 2022    | 2        | 4.55%   |
| 2017    | 1        | 2.27%   |
| 2015    | 1        | 2.27%   |
| 2009    | 1        | 2.27%   |
| 2007    | 1        | 2.27%   |
| 2004    | 1        | 2.27%   |
| Unknown | 1        | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 44       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 44       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 44       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 11       | 22.92%  |
| 3.01-4.0        | 8        | 16.67%  |
| 32.01-64.0      | 7        | 14.58%  |
| 4.01-8.0        | 6        | 12.5%   |
| 8.01-16.0       | 6        | 12.5%   |
| 2.01-3.0        | 2        | 4.17%   |
| 1.01-2.0        | 2        | 4.17%   |
| 0.51-1.0        | 2        | 4.17%   |
| 0.01-0.5        | 2        | 4.17%   |
| More than 256.0 | 1        | 2.08%   |
| 64.01-256.0     | 1        | 2.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 13       | 27.66%  |
| 1.01-2.0  | 11       | 23.4%   |
| 0.51-1.0  | 7        | 14.89%  |
| 3.01-4.0  | 5        | 10.64%  |
| 2.01-3.0  | 5        | 10.64%  |
| 4.01-8.0  | 2        | 4.26%   |
| 8.01-16.0 | 2        | 4.26%   |
| 0         | 1        | 2.13%   |
| Unknown   | 1        | 2.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 44.44%  |
| 2      | 10       | 22.22%  |
| 3      | 8        | 17.78%  |
| 4      | 5        | 11.11%  |
| 12     | 1        | 2.22%   |
| 5      | 1        | 2.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 86.67%  |
| Yes       | 6        | 13.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 43       | 97.73%  |
| No        | 1        | 2.27%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 73.33%  |
| Yes       | 12       | 26.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 77.78%  |
| Yes       | 10       | 22.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 11       | 23.4%   |
| Germany     | 5        | 10.64%  |
| Russia      | 4        | 8.51%   |
| UK          | 2        | 4.26%   |
| Sweden      | 2        | 4.26%   |
| Spain       | 2        | 4.26%   |
| Norway      | 2        | 4.26%   |
| Canada      | 2        | 4.26%   |
| Brazil      | 2        | 4.26%   |
| Ukraine     | 1        | 2.13%   |
| Switzerland | 1        | 2.13%   |
| South Korea | 1        | 2.13%   |
| Portugal    | 1        | 2.13%   |
| Poland      | 1        | 2.13%   |
| Pakistan    | 1        | 2.13%   |
| Netherlands | 1        | 2.13%   |
| Indonesia   | 1        | 2.13%   |
| Guatemala   | 1        | 2.13%   |
| Greece      | 1        | 2.13%   |
| Finland     | 1        | 2.13%   |
| China       | 1        | 2.13%   |
| Austria     | 1        | 2.13%   |
| Australia   | 1        | 2.13%   |
| Argentina   | 1        | 2.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Springfield          | 4        | 8.51%   |
| St Petersburg        | 3        | 6.38%   |
| Manitowoc            | 3        | 6.38%   |
| Frankfurt am Main    | 2        | 4.26%   |
| As                   | 2        | 4.26%   |
| Zurich               | 1        | 2.13%   |
| Tuusula              | 1        | 2.13%   |
| Thornhill            | 1        | 2.13%   |
| Stuttgart            | 1        | 2.13%   |
| Stockholm            | 1        | 2.13%   |
| Somerset             | 1        | 2.13%   |
| Salzburg             | 1        | 2.13%   |
| Redwood City         | 1        | 2.13%   |
| Penza                | 1        | 2.13%   |
| Oberhausen           | 1        | 2.13%   |
| Lisbon               | 1        | 2.13%   |
| Lahore               | 1        | 2.13%   |
| Kharkiv              | 1        | 2.13%   |
| Jerez de la Frontera | 1        | 2.13%   |
| Jember               | 1        | 2.13%   |
| Heraklion            | 1        | 2.13%   |
| Hangzhou             | 1        | 2.13%   |
| Hamburg              | 1        | 2.13%   |
| Gwacheon             | 1        | 2.13%   |
| Guatemala City       | 1        | 2.13%   |
| Gothenburg           | 1        | 2.13%   |
| Gorredijk            | 1        | 2.13%   |
| Glasgow              | 1        | 2.13%   |
| General San Martin   | 1        | 2.13%   |
| Durham               | 1        | 2.13%   |
| Czarna Białostocka  | 1        | 2.13%   |
| Chicago              | 1        | 2.13%   |
| Bradford             | 1        | 2.13%   |
| Betim                | 1        | 2.13%   |
| Barrow in Furness    | 1        | 2.13%   |
| Barcelona            | 1        | 2.13%   |
| Balneário Camboriú | 1        | 2.13%   |
| Adelaide             | 1        | 2.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 15       | 23     | 18.07%  |
| WDC                         | 12       | 18     | 14.46%  |
| Seagate                     | 11       | 23     | 13.25%  |
| Toshiba                     | 5        | 5      | 6.02%   |
| HGST                        | 5        | 5      | 6.02%   |
| A-DATA Technology           | 5        | 7      | 6.02%   |
| SanDisk                     | 4        | 6      | 4.82%   |
| Kingston                    | 4        | 4      | 4.82%   |
| Crucial                     | 4        | 7      | 4.82%   |
| Intel                       | 3        | 4      | 3.61%   |
| Hitachi                     | 3        | 3      | 3.61%   |
| SK hynix                    | 2        | 2      | 2.41%   |
| Unknown                     | 1        | 1      | 1.2%    |
| Transcend                   | 1        | 1      | 1.2%    |
| SPCC                        | 1        | 1      | 1.2%    |
| Phison Electronics          | 1        | 1      | 1.2%    |
| LITEON                      | 1        | 1      | 1.2%    |
| Lexar                       | 1        | 1      | 1.2%    |
| KIOXIA                      | 1        | 1      | 1.2%    |
| Kingston Technology Company | 1        | 1      | 1.2%    |
| Kingmax                     | 1        | 1      | 1.2%    |
| Apple                       | 1        | 3      | 1.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 960 EVO 500GB                           | 2        | 2.04%   |
| Samsung SSD 870 QVO 1TB                             | 2        | 2.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2        | 2.04%   |
| WDC WDS500G2B0A 500GB SSD                           | 1        | 1.02%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                    | 1        | 1.02%   |
| WDC WDS250G2B0B 250GB SSD                           | 1        | 1.02%   |
| WDC WDS250G2B0A 250GB SSD                           | 1        | 1.02%   |
| WDC WD800AAJS-00 80GB                               | 1        | 1.02%   |
| WDC WD7500BPKT-80PK4T0 752GB                        | 1        | 1.02%   |
| WDC WD5000AZRX-00A8LB0 500GB                        | 1        | 1.02%   |
| WDC WD40EFZX-68AWUN0 4TB                            | 1        | 1.02%   |
| WDC WD3200AAKX-0 320GB                              | 1        | 1.02%   |
| WDC WD20EZRZ-00Z 2TB                                | 1        | 1.02%   |
| WDC WD1600BEVT-2 160GB                              | 1        | 1.02%   |
| WDC WD140EDGZ-11B2DA2 14TB                          | 1        | 1.02%   |
| WDC WD120EFBX-68B0EN0 12TB                          | 1        | 1.02%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1        | 1.02%   |
| WDC WD10EZEX-75WN4A1 1TB                            | 1        | 1.02%   |
| WDC WD10EZEX-21M2NA0 1TB                            | 1        | 1.02%   |
| Unknown MMC Card  32GB                              | 1        | 1.02%   |
| Transcend SSD 1GB                                   | 1        | 1.02%   |
| Toshiba MQ04ABF100 1TB                              | 1        | 1.02%   |
| Toshiba MQ01ABF050 500GB                            | 1        | 1.02%   |
| Toshiba MK3252GS 320GB                              | 1        | 1.02%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD             | 1        | 1.02%   |
| Toshiba HDWD130 3TB                                 | 1        | 1.02%   |
| SPCC Solid State Disk 120GB                         | 1        | 1.02%   |
| SK hynix SC300 M.2 2280 256 256GB SSD               | 1        | 1.02%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1        | 1.02%   |
| Seagate ST980310AS 80GB                             | 1        | 1.02%   |
| Seagate ST9160314AS 160GB                           | 1        | 1.02%   |
| Seagate ST5000LM000-2AN170 5TB                      | 1        | 1.02%   |
| Seagate ST4000VN008-2DR1 4TB                        | 1        | 1.02%   |
| Seagate ST4000NC000-1FR1 4TB                        | 1        | 1.02%   |
| Seagate ST380815AS 80GB                             | 1        | 1.02%   |
| Seagate ST3500418AS 500GB                           | 1        | 1.02%   |
| Seagate ST3000DM001-1ER166 3TB                      | 1        | 1.02%   |
| Seagate ST2000DL001-9VT1 2TB                        | 1        | 1.02%   |
| Seagate ST18000NM000J-2TV103 18TB                   | 1        | 1.02%   |
| Seagate ST14000VN0008-2KU103 14TB                   | 1        | 1.02%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 23     | 31.43%  |
| WDC                 | 10       | 14     | 28.57%  |
| HGST                | 5        | 5      | 14.29%  |
| Toshiba             | 4        | 4      | 11.43%  |
| Hitachi             | 3        | 3      | 8.57%   |
| Samsung Electronics | 2        | 3      | 5.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 8      | 20%     |
| Crucial             | 4        | 7      | 13.33%  |
| Kingston            | 3        | 3      | 10%     |
| Intel               | 3        | 4      | 10%     |
| A-DATA Technology   | 3        | 3      | 10%     |
| WDC                 | 2        | 4      | 6.67%   |
| SanDisk             | 2        | 3      | 6.67%   |
| Transcend           | 1        | 1      | 3.33%   |
| Toshiba             | 1        | 1      | 3.33%   |
| SPCC                | 1        | 1      | 3.33%   |
| SK hynix            | 1        | 1      | 3.33%   |
| LITEON              | 1        | 1      | 3.33%   |
| Lexar               | 1        | 1      | 3.33%   |
| Kingmax             | 1        | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 27       | 52     | 40.3%   |
| SSD  | 24       | 39     | 35.82%  |
| NVMe | 15       | 27     | 22.39%  |
| MMC  | 1        | 1      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 37       | 89     | 68.52%  |
| NVMe | 15       | 27     | 27.78%  |
| SAS  | 1        | 2      | 1.85%   |
| MMC  | 1        | 1      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 32       | 51     | 60.38%  |
| 0.51-1.0   | 11       | 17     | 20.75%  |
| 3.01-4.0   | 3        | 7      | 5.66%   |
| 2.01-3.0   | 2        | 2      | 3.77%   |
| 10.01-20.0 | 2        | 9      | 3.77%   |
| 4.01-10.0  | 2        | 2      | 3.77%   |
| 1.01-2.0   | 1        | 3      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 13       | 28.89%  |
| 101-250        | 8        | 17.78%  |
| More than 3000 | 4        | 8.89%   |
| 21-50          | 4        | 8.89%   |
| 2001-3000      | 4        | 8.89%   |
| 1-20           | 4        | 8.89%   |
| 251-500        | 2        | 4.44%   |
| 1001-2000      | 2        | 4.44%   |
| 501-1000       | 2        | 4.44%   |
| 51-100         | 2        | 4.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 17       | 37.78%  |
| Unknown        | 13       | 28.89%  |
| 251-500        | 5        | 11.11%  |
| 21-50          | 5        | 11.11%  |
| 1001-2000      | 2        | 4.44%   |
| More than 3000 | 1        | 2.22%   |
| 2001-3000      | 1        | 2.22%   |
| 51-100         | 1        | 2.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD3200AAKX-0 320GB             | 1        | 1      | 12.5%   |
| Toshiba MK3252GS 320GB             | 1        | 1      | 12.5%   |
| SanDisk SDSA6MM 16GB SSD           | 1        | 1      | 12.5%   |
| Samsung Electronics SP0411N 40GB   | 1        | 2      | 12.5%   |
| Kingmax SSD 120G                   | 1        | 1      | 12.5%   |
| Hitachi HTS722080K9A300 80GB       | 1        | 1      | 12.5%   |
| HGST HTS725050A7 500GB             | 1        | 1      | 12.5%   |
| A-DATA Technology IM2P33F8ABR1-1TB | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 12.5%   |
| Toshiba             | 1        | 1      | 12.5%   |
| SanDisk             | 1        | 1      | 12.5%   |
| Samsung Electronics | 1        | 2      | 12.5%   |
| Kingmax             | 1        | 1      | 12.5%   |
| Hitachi             | 1        | 1      | 12.5%   |
| HGST                | 1        | 1      | 12.5%   |
| A-DATA Technology   | 1        | 1      | 12.5%   |

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
| HDD  | 5        | 6      | 62.5%   |
| SSD  | 2        | 2      | 25%     |
| NVMe | 1        | 1      | 12.5%   |

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
| Works    | 32       | 77     | 62.75%  |
| Detected | 12       | 33     | 23.53%  |
| Malfunc  | 7        | 9      | 13.73%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 34       | 47.89%  |
| Samsung Electronics         | 9        | 12.68%  |
| AMD                         | 7        | 9.86%   |
| SanDisk                     | 2        | 2.82%   |
| Nvidia                      | 2        | 2.82%   |
| Marvell Technology Group    | 2        | 2.82%   |
| LSI Logic / Symbios Logic   | 2        | 2.82%   |
| ASMedia Technology          | 2        | 2.82%   |
| ADATA Technology            | 2        | 2.82%   |
| Adaptec                     | 2        | 2.82%   |
| VIA Technologies            | 1        | 1.41%   |
| SK hynix                    | 1        | 1.41%   |
| Promise Technology          | 1        | 1.41%   |
| Phison Electronics          | 1        | 1.41%   |
| KIOXIA                      | 1        | 1.41%   |
| Kingston Technology Company | 1        | 1.41%   |
| Broadcom / LSI              | 1        | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 6.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 5.68%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 5.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 4.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 3.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 2.27%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 2        | 2.27%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 2        | 2.27%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 2.27%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2        | 2.27%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2        | 2.27%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 2.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2        | 2.27%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 2.27%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 2.27%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 2        | 2.27%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1        | 1.14%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1        | 1.14%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 1.14%   |
| SanDisk WD Green SN350 NVMe SSD 240GB (DRAM-less)                              | 1        | 1.14%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 1.14%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 1.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 1.14%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.14%   |
| Promise PDC42819 [FastTrak TX2650/TX4650]                                      | 1        | 1.14%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 1.14%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1        | 1.14%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.14%   |
| Nvidia MCP61 IDE                                                               | 1        | 1.14%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 1.14%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 1        | 1.14%   |
| Kingston Company Company Non-Volatile memory controller                        | 1        | 1.14%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 1.14%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1        | 1.14%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 1        | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 35       | 52.24%  |
| NVMe | 13       | 19.4%   |
| RAID | 9        | 13.43%  |
| IDE  | 8        | 11.94%  |
| SAS  | 2        | 2.99%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 35       | 77.78%  |
| AMD     | 9        | 20%     |
| Unknown | 1        | 2.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i9-10900 CPU @ 2.80GHz       | 2        | 4.26%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 2        | 4.26%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2        | 4.26%   |
| Intel Core i3-4150 CPU @ 3.50GHz        | 2        | 4.26%   |
| AMD FX-8350 Eight-Core Processor        | 2        | 4.26%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz      | 1        | 2.13%   |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1        | 2.13%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz  | 1        | 2.13%   |
| Intel Core i7-8700T CPU @ 2.40GHz       | 1        | 2.13%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1        | 2.13%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 1        | 2.13%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 1        | 2.13%   |
| Intel Core i5-6600K CPU @ 3.50GHz       | 1        | 2.13%   |
| Intel Core i5-6500T CPU @ 2.50GHz       | 1        | 2.13%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 1        | 2.13%   |
| Intel Core i5-4590T CPU @ 2.00GHz       | 1        | 2.13%   |
| Intel Core i5-4570T CPU @ 2.90GHz       | 1        | 2.13%   |
| Intel Core i5-3450 CPU @ 3.10GHz        | 1        | 2.13%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1        | 2.13%   |
| Intel Core i3-3240 CPU @ 3.40GHz        | 1        | 2.13%   |
| Intel Core i3-3220T CPU @ 2.80GHz       | 1        | 2.13%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 1        | 2.13%   |
| Intel Celeron N5105 @ 2.00GHz           | 1        | 2.13%   |
| Intel Celeron M processor 1.00GHz       | 1        | 2.13%   |
| Intel Celeron CPU J3455 @ 1.50GHz       | 1        | 2.13%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 1        | 2.13%   |
| Intel Celeron CPU J1800 @ 2.41GHz       | 1        | 2.13%   |
| Intel Celeron CPU G1850 @ 2.90GHz       | 1        | 2.13%   |
| Intel Celeron CPU E3400 @ 2.60GHz       | 1        | 2.13%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 1        | 2.13%   |
| Intel Atom CPU D525 @ 1.80GHz           | 1        | 2.13%   |
| Intel 12th Gen Core i9-12900K           | 1        | 2.13%   |
| Intel 12th Gen Core i7-12700T           | 1        | 2.13%   |
| Intel 12th Gen Core i7-12700H           | 1        | 2.13%   |
| AMD Sempron 145 Processor               | 1        | 2.13%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 1        | 2.13%   |
| AMD Ryzen 7 5700X 8-Core Processor      | 1        | 2.13%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 1        | 2.13%   |
| AMD Mobile Duron processor              | 1        | 2.13%   |
| AMD E1-2500 APU with Radeon HD Graphics | 1        | 2.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 10       | 21.28%  |
| Intel Celeron      | 6        | 12.77%  |
| Other              | 5        | 10.64%  |
| Intel Core i7      | 5        | 10.64%  |
| Intel Core i3      | 5        | 10.64%  |
| Intel Core i9      | 2        | 4.26%   |
| Intel Atom         | 2        | 4.26%   |
| AMD Ryzen 7        | 2        | 4.26%   |
| AMD FX             | 2        | 4.26%   |
| Intel Xeon Gold    | 1        | 2.13%   |
| Intel Xeon         | 1        | 2.13%   |
| Intel Pentium Dual | 1        | 2.13%   |
| Intel Celeron M    | 1        | 2.13%   |
| AMD Sempron        | 1        | 2.13%   |
| AMD Ryzen 9        | 1        | 2.13%   |
| AMD E1             | 1        | 2.13%   |
| AMD A8             | 1        | 2.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 17       | 36.96%  |
| 2      | 12       | 26.09%  |
| 1      | 4        | 8.7%    |
| 8      | 3        | 6.52%   |
| 6      | 3        | 6.52%   |
| 12     | 2        | 4.35%   |
| 10     | 2        | 4.35%   |
| 32     | 1        | 2.17%   |
| 16     | 1        | 2.17%   |
| 14     | 1        | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 43       | 95.56%  |
| 2      | 1        | 2.22%   |
| 0      | 1        | 2.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 56.82%  |
| 2      | 19       | 43.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 22       | 48.89%  |
| 32-bit, 64-bit | 20       | 44.44%  |
| 32-bit         | 2        | 4.44%   |
| 64-bit         | 1        | 2.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 55.32%  |
| 0x306c3    | 4        | 8.51%   |
| 0x906ea    | 2        | 4.26%   |
| 0x306a9    | 2        | 4.26%   |
| 0xa0655    | 1        | 2.13%   |
| 0x906a3    | 1        | 2.13%   |
| 0x90672    | 1        | 2.13%   |
| 0x806ec    | 1        | 2.13%   |
| 0x6fd      | 1        | 2.13%   |
| 0x6d8      | 1        | 2.13%   |
| 0x506c9    | 1        | 2.13%   |
| 0x406c4    | 1        | 2.13%   |
| 0x106e5    | 1        | 2.13%   |
| 0x08701021 | 1        | 2.13%   |
| 0x0800820d | 1        | 2.13%   |
| 0x06000817 | 1        | 2.13%   |
| 0x010000b6 | 1        | 2.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 7        | 14.89%  |
| Skylake          | 4        | 8.51%   |
| KabyLake         | 4        | 8.51%   |
| Silvermont       | 3        | 6.38%   |
| SandyBridge      | 3        | 6.38%   |
| Piledriver       | 3        | 6.38%   |
| IvyBridge        | 3        | 6.38%   |
| CometLake        | 3        | 6.38%   |
| Unknown          | 3        | 6.38%   |
| Alderlake Hybrid | 2        | 4.26%   |
| Zen+             | 1        | 2.13%   |
| Zen 3            | 1        | 2.13%   |
| Zen 2            | 1        | 2.13%   |
| Penryn           | 1        | 2.13%   |
| P6               | 1        | 2.13%   |
| Nehalem          | 1        | 2.13%   |
| K6               | 1        | 2.13%   |
| K10              | 1        | 2.13%   |
| Jaguar           | 1        | 2.13%   |
| Goldmont         | 1        | 2.13%   |
| Core             | 1        | 2.13%   |
| Bonnell          | 1        | 2.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 30       | 62.5%   |
| AMD                        | 10       | 20.83%  |
| Nvidia                     | 5        | 10.42%  |
| Matrox Electronics Systems | 2        | 4.17%   |
| VIA Technologies           | 1        | 2.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4        | 7.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 7.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4        | 7.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 5.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 3.64%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 3.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 3.64%   |
| Intel AlderLake-S GT1                                                                    | 2        | 3.64%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.64%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 3.64%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1        | 1.82%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1        | 1.82%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.82%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.82%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1        | 1.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1        | 1.82%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1        | 1.82%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1        | 1.82%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1        | 1.82%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 1.82%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.82%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1        | 1.82%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 1.82%   |
| Intel HD Graphics 530                                                                    | 1        | 1.82%   |
| Intel HD Graphics 500                                                                    | 1        | 1.82%   |
| Intel DG2 [Arc A750]                                                                     | 1        | 1.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1        | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.82%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 1.82%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1        | 1.82%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 1.82%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1        | 1.82%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.82%   |
| AMD Trinity [Radeon HD 7560D]                                                            | 1        | 1.82%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                                   | 1        | 1.82%   |
| AMD ES1000                                                                               | 1        | 1.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1        | 1.82%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                                            | 1        | 1.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 28       | 59.57%  |
| 1 x AMD         | 10       | 21.28%  |
| 1 x Nvidia      | 3        | 6.38%   |
| Other           | 1        | 2.13%   |
| 2 x Intel       | 1        | 2.13%   |
| 1 x VIA         | 1        | 2.13%   |
| Nvidia + Matrox | 1        | 2.13%   |
| 1 x Matrox      | 1        | 2.13%   |
| Intel + Nvidia  | 1        | 2.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 36       | 80%     |
| Unknown     | 8        | 17.78%  |
| Proprietary | 1        | 2.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 79.55%  |
| 7.01-8.0   | 3        | 6.82%   |
| 0.01-0.5   | 2        | 4.55%   |
| 3.01-4.0   | 1        | 2.27%   |
| 1.01-2.0   | 1        | 2.27%   |
| 8.01-16.0  | 1        | 2.27%   |
| 0.51-1.0   | 1        | 2.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 8        | 20.51%  |
| Samsung Electronics | 5        | 12.82%  |
| Goldstar            | 5        | 12.82%  |
| BenQ                | 5        | 12.82%  |
| AOC                 | 4        | 10.26%  |
| Philips             | 2        | 5.13%   |
| Acer                | 2        | 5.13%   |
| ViewSonic           | 1        | 2.56%   |
| Mi                  | 1        | 2.56%   |
| KVM                 | 1        | 2.56%   |
| InfoVision          | 1        | 2.56%   |
| Elo Touch           | 1        | 2.56%   |
| Element             | 1        | 2.56%   |
| CTC                 | 1        | 2.56%   |
| BOE                 | 1        | 2.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                     | 3        | 7.14%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch     | 2        | 4.76%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch             | 1        | 2.38%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 2.38%   |
| Samsung Electronics S27A950D SAM079E 1920x1080 598x336mm 27.0-inch   | 1        | 2.38%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch | 1        | 2.38%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 1        | 2.38%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch              | 1        | 2.38%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                     | 1        | 2.38%   |
| KVM LCD Monitor 1 1 9" KVM4308 1280x1024 338x270mm 17.0-inch         | 1        | 2.38%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch         | 1        | 2.38%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 1        | 2.38%   |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch             | 1        | 2.38%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 1        | 2.38%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 2.38%   |
| Goldstar M227WD GSM56D5 1920x1080 480x270mm 21.7-inch                | 1        | 2.38%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch          | 1        | 2.38%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                | 1        | 2.38%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 1        | 2.38%   |
| Elo Touch ET1717L ELO1717 1280x1024 338x270mm 17.0-inch              | 1        | 2.38%   |
| Element ELCFW329 ELE1366 1366x768 700x390mm 31.5-inch                | 1        | 2.38%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                    | 1        | 2.38%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                   | 1        | 2.38%   |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                    | 1        | 2.38%   |
| Dell E1911 DELF037 1440x900 408x255mm 18.9-inch                      | 1        | 2.38%   |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                    | 1        | 2.38%   |
| CTC KD02909-8770A CTC0770 1024x768 304x228mm 15.0-inch               | 1        | 2.38%   |
| BOE LCD Monitor BOE09F1 1920x1080 355x200mm 16.0-inch                | 1        | 2.38%   |
| BenQ ZOWIE RL LCD BNQ7F4F 1920x1080 531x299mm 24.0-inch              | 1        | 2.38%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                   | 1        | 2.38%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                    | 1        | 2.38%   |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                    | 1        | 2.38%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                    | 1        | 2.38%   |
| AOC 912Vwa AOC1912 1440x900 408x255mm 18.9-inch                      | 1        | 2.38%   |
| AOC 718Swsg-1 AOCC750 1440x900 367x230mm 17.1-inch                   | 1        | 2.38%   |
| AOC 2476WM AOC2476 1920x1080 521x293mm 23.5-inch                     | 1        | 2.38%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                     | 1        | 2.38%   |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                    | 1        | 2.38%   |
| Acer S236HL ACR0387 1920x1080 510x286mm 23.0-inch                    | 1        | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 33.33%  |
| 3840x2160 (4K)     | 4        | 11.11%  |
| 2560x1440 (QHD)    | 4        | 11.11%  |
| 1680x1050 (WSXGA+) | 4        | 11.11%  |
| 1280x1024 (SXGA)   | 4        | 11.11%  |
| 3440x1440          | 3        | 8.33%   |
| 1440x900 (WXGA+)   | 2        | 5.56%   |
| 2560x1080          | 1        | 2.78%   |
| 1366x768 (WXGA)    | 1        | 2.78%   |
| 1024x768 (XGA)     | 1        | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 7        | 18.42%  |
| 24     | 4        | 10.53%  |
| 21     | 4        | 10.53%  |
| 20     | 4        | 10.53%  |
| 34     | 3        | 7.89%   |
| 23     | 3        | 7.89%   |
| 19     | 3        | 7.89%   |
| 17     | 3        | 7.89%   |
| 72     | 1        | 2.63%   |
| 31     | 1        | 2.63%   |
| 25     | 1        | 2.63%   |
| 18     | 1        | 2.63%   |
| 16     | 1        | 2.63%   |
| 15     | 1        | 2.63%   |
| 14     | 1        | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 36.11%  |
| 401-500     | 10       | 27.78%  |
| 301-350     | 4        | 11.11%  |
| 701-800     | 3        | 8.33%   |
| 351-400     | 3        | 8.33%   |
| 601-700     | 2        | 5.56%   |
| 1501-2000   | 1        | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 15       | 50%     |
| 16/10 | 7        | 23.33%  |
| 5/4   | 4        | 13.33%  |
| 21/9  | 3        | 10%     |
| 4/3   | 1        | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 24.32%  |
| 151-200        | 9        | 24.32%  |
| 301-350        | 7        | 18.92%  |
| 351-500        | 4        | 10.81%  |
| 141-150        | 2        | 5.41%   |
| 101-110        | 2        | 5.41%   |
| More than 1000 | 1        | 2.7%    |
| 81-90          | 1        | 2.7%    |
| 251-300        | 1        | 2.7%    |
| 131-140        | 1        | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 18       | 58.06%  |
| 101-120 | 7        | 22.58%  |
| 1-50    | 3        | 9.68%   |
| 121-160 | 2        | 6.45%   |
| 161-240 | 1        | 3.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 26       | 56.52%  |
| 0     | 15       | 32.61%  |
| 2     | 3        | 6.52%   |
| 4     | 1        | 2.17%   |
| 3     | 1        | 2.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 21       | 33.33%  |
| Intel                           | 21       | 33.33%  |
| Broadcom                        | 5        | 7.94%   |
| Qualcomm Atheros                | 4        | 6.35%   |
| Xiaomi                          | 2        | 3.17%   |
| MediaTek                        | 2        | 3.17%   |
| VIA Technologies                | 1        | 1.59%   |
| T & A Mobile Phones             | 1        | 1.59%   |
| Qualcomm Atheros Communications | 1        | 1.59%   |
| Qualcomm                        | 1        | 1.59%   |
| Nvidia                          | 1        | 1.59%   |
| DisplayLink                     | 1        | 1.59%   |
| D-Link System                   | 1        | 1.59%   |
| ASIX Electronics                | 1        | 1.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 16       | 21.05%  |
| Intel Ethernet Controller I225-V                                        | 5        | 6.58%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3        | 3.95%   |
| Intel I211 Gigabit Network Connection                                   | 2        | 2.63%   |
| Intel Ethernet Connection (7) I219-V                                    | 2        | 2.63%   |
| Intel Ethernet Connection (2) I219-V                                    | 2        | 2.63%   |
| Intel Ethernet Connection (17) I219-LM                                  | 2        | 2.63%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2        | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2        | 2.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1        | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1        | 1.32%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 1        | 1.32%   |
| T & A Mobile Phones Alcatel 3X                                          | 1        | 1.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1        | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1        | 1.32%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 1.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1        | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1        | 1.32%   |
| Qualcomm Redmi Note 8                                                   | 1        | 1.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 1.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1        | 1.32%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1        | 1.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 1.32%   |
| Nvidia MCP61 Ethernet                                                   | 1        | 1.32%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 1.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1        | 1.32%   |
| Intel I210 Gigabit Network Connection                                   | 1        | 1.32%   |
| Intel Ethernet Connection I217-LM                                       | 1        | 1.32%   |
| Intel Ethernet Connection (7) I219-LM                                   | 1        | 1.32%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1        | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1        | 1.32%   |
| Intel Centrino Wireless-N 105                                           | 1        | 1.32%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1        | 1.32%   |
| Intel 82578DM Gigabit Network Connection                                | 1        | 1.32%   |
| Intel 82567V-4 Gigabit Network Connection                               | 1        | 1.32%   |
| Intel 82566DM-2 Gigabit Network Connection                              | 1        | 1.32%   |
| DisplayLink Dell D3100 Docking Station                                  | 1        | 1.32%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                         | 1        | 1.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 5        | 31.25%  |
| Realtek Semiconductor           | 3        | 18.75%  |
| Broadcom                        | 3        | 18.75%  |
| Qualcomm Atheros                | 2        | 12.5%   |
| MediaTek                        | 2        | 12.5%   |
| Qualcomm Atheros Communications | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Comet Lake PCH CNVi WiFi                                          | 2        | 11.76%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1        | 5.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1        | 5.88%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 5.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 5.88%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 5.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 5.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 5.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1        | 5.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 5.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1        | 5.88%   |
| Intel Centrino Wireless-N 105                                           | 1        | 5.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1        | 5.88%   |
| Broadcom BRCM4378 Wireless Network Adapter                              | 1        | 5.88%   |
| Broadcom BCM43227 802.11b/g/n                                           | 1        | 5.88%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 37.04%  |
| Intel                 | 20       | 37.04%  |
| Broadcom              | 3        | 5.56%   |
| Xiaomi                | 2        | 3.7%    |
| Qualcomm Atheros      | 2        | 3.7%    |
| VIA Technologies      | 1        | 1.85%   |
| T & A Mobile Phones   | 1        | 1.85%   |
| Qualcomm              | 1        | 1.85%   |
| Nvidia                | 1        | 1.85%   |
| DisplayLink           | 1        | 1.85%   |
| D-Link System         | 1        | 1.85%   |
| ASIX Electronics      | 1        | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 16       | 27.59%  |
| Intel Ethernet Controller I225-V                                      | 5        | 8.62%   |
| Realtek RTL8125 2.5GbE Controller                                     | 3        | 5.17%   |
| Intel I211 Gigabit Network Connection                                 | 2        | 3.45%   |
| Intel Ethernet Connection (7) I219-V                                  | 2        | 3.45%   |
| Intel Ethernet Connection (2) I219-V                                  | 2        | 3.45%   |
| Intel Ethernet Connection (17) I219-LM                                | 2        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 2        | 3.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 1        | 1.72%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                  | 1        | 1.72%   |
| VIA VT6102/VT6103 [Rhine-II]                                          | 1        | 1.72%   |
| T & A Mobile Phones Alcatel 3X                                        | 1        | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 1        | 1.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1        | 1.72%   |
| Qualcomm Redmi Note 8                                                 | 1        | 1.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                             | 1        | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1        | 1.72%   |
| Nvidia MCP61 Ethernet                                                 | 1        | 1.72%   |
| Intel I210 Gigabit Network Connection                                 | 1        | 1.72%   |
| Intel Ethernet Connection I217-LM                                     | 1        | 1.72%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1        | 1.72%   |
| Intel Ethernet Connection (2) I219-LM                                 | 1        | 1.72%   |
| Intel 82578DM Gigabit Network Connection                              | 1        | 1.72%   |
| Intel 82567V-4 Gigabit Network Connection                             | 1        | 1.72%   |
| Intel 82566DM-2 Gigabit Network Connection                            | 1        | 1.72%   |
| DisplayLink Dell D3100 Docking Station                                | 1        | 1.72%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                       | 1        | 1.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                     | 1        | 1.72%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1        | 1.72%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1        | 1.72%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1        | 1.72%   |
| ASIX AX88179 Gigabit Ethernet                                         | 1        | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 43       | 76.79%  |
| WiFi     | 12       | 21.43%  |
| Unknown  | 1        | 1.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 38       | 88.37%  |
| WiFi     | 5        | 11.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 27       | 58.7%   |
| 2     | 15       | 32.61%  |
| 3     | 2        | 4.35%   |
| 5     | 1        | 2.17%   |
| 4     | 1        | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 35       | 79.55%  |
| Yes  | 9        | 20.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 28.57%  |
| Cambridge Silicon Radio | 4        | 28.57%  |
| IMC Networks            | 2        | 14.29%  |
| MediaTek                | 1        | 7.14%   |
| Broadcom                | 1        | 7.14%   |
| Apple                   | 1        | 7.14%   |
| Actions                 | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 28.57%  |
| Intel AX201 Bluetooth                               | 3        | 21.43%  |
| MediaTek Wireless_Device                            | 1        | 7.14%   |
| Intel Bluetooth Device                              | 1        | 7.14%   |
| IMC Networks Wireless_Device                        | 1        | 7.14%   |
| IMC Networks Bluetooth Device                       | 1        | 7.14%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 7.14%   |
| Apple Bluetooth Host Controller                     | 1        | 7.14%   |
| Actions general adapter                             | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 29       | 54.72%  |
| AMD                                  | 12       | 22.64%  |
| Nvidia                               | 4        | 7.55%   |
| VIA Technologies                     | 1        | 1.89%   |
| Thesycon Systemsoftware & Consulting | 1        | 1.89%   |
| Texas Instruments                    | 1        | 1.89%   |
| RODE Microphones                     | 1        | 1.89%   |
| Native Instruments                   | 1        | 1.89%   |
| Logitech                             | 1        | 1.89%   |
| Generalplus Technology               | 1        | 1.89%   |
| C-Media Electronics                  | 1        | 1.89%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 7.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 7.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 5.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 5.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 4.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 4.23%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 2.82%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 2.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 2.82%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 2.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 2.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 2.82%   |
| AMD FCH Azalia Controller                                                  | 2        | 2.82%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 1.41%   |
| Thesycon Systemsoftware & Consulting DX5                                   | 1        | 1.41%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.41%   |
| RODE Microphones RODE NT-USB Mini                                          | 1        | 1.41%   |
| Nvidia MCP89 High Definition Audio                                         | 1        | 1.41%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.41%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1.41%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.41%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.41%   |
| Nvidia Audio device                                                        | 1        | 1.41%   |
| Native Instruments Komplete Audio 2                                        | 1        | 1.41%   |
| Logitech G935 Gaming Headset                                               | 1        | 1.41%   |
| Intel USB PnP Sound Device                                                 | 1        | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 1.41%   |
| Intel DG2 Audio Controller                                                 | 1        | 1.41%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1        | 1.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 1.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1        | 1.41%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.41%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1        | 1.41%   |
| Generalplus Technology USB Audio Device                                    | 1        | 1.41%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.41%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 1.41%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 8        | 15.38%  |
| Kingston            | 7        | 13.46%  |
| Unknown             | 6        | 11.54%  |
| SK hynix            | 6        | 11.54%  |
| Samsung Electronics | 6        | 11.54%  |
| Micron Technology   | 4        | 7.69%   |
| Elpida              | 4        | 7.69%   |
| Corsair             | 4        | 7.69%   |
| Team                | 1        | 1.92%   |
| Qimonda             | 1        | 1.92%   |
| Patriot             | 1        | 1.92%   |
| Hewlett-Packard     | 1        | 1.92%   |
| Cors                | 1        | 1.92%   |
| A-DATA Technology   | 1        | 1.92%   |
| Unknown             | 1        | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s       | 2        | 3.39%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s  | 2        | 3.39%   |
| Unknown RAM Module 512MB DIMM                             | 1        | 1.69%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 1.69%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                  | 1        | 1.69%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s              | 1        | 1.69%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 1        | 1.69%   |
| Unknown RAM Module 128MB DIMM                             | 1        | 1.69%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 1        | 1.69%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s        | 1        | 1.69%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 1.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s      | 1        | 1.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 1        | 1.69%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1        | 1.69%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 1.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 1.69%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s               | 1        | 1.69%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                 | 1        | 1.69%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s    | 1        | 1.69%   |
| Samsung RAM M378B5773DH0-CK0 2048MB DIMM DDR3 1600MT/s    | 1        | 1.69%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s       | 1        | 1.69%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 1.69%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s       | 1        | 1.69%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s          | 1        | 1.69%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s            | 1        | 1.69%   |
| Micron RAM Module 4GB SODIMM DDR3 1067MT/s                | 1        | 1.69%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s               | 1        | 1.69%   |
| Micron RAM 8KTF51264AZ-1G9P1 4GB DIMM DDR3 1866MT/s       | 1        | 1.69%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 1.69%   |
| Micron RAM 16ATF4G64HZ-3G2F1 32GB SODIMM DDR4 3200MT/s    | 1        | 1.69%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s       | 1        | 1.69%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1923MT/s       | 1        | 1.69%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 1.69%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 1.69%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 1.69%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 1.69%   |
| Kingston RAM 9905790-010.A00G 16GB SODIMM DDR5 4800MT/s   | 1        | 1.69%   |
| Kingston RAM 9905744-064.A00G 32GB SODIMM DDR4 3200MT/s   | 1        | 1.69%   |
| Kingston RAM 9905595-005.A00LF 2GB DIMM DDR3 1600MT/s     | 1        | 1.69%   |
| Kingston RAM 9905474-019.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 1.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 24       | 60%     |
| DDR4    | 11       | 27.5%   |
| SDRAM   | 2        | 5%      |
| DDR5    | 1        | 2.5%    |
| DDR2    | 1        | 2.5%    |
| Unknown | 1        | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 32       | 84.21%  |
| SODIMM | 6        | 15.79%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 15       | 32.61%  |
| 4096  | 11       | 23.91%  |
| 2048  | 8        | 17.39%  |
| 32768 | 4        | 8.7%    |
| 16384 | 3        | 6.52%   |
| 1024  | 3        | 6.52%   |
| 512   | 1        | 2.17%   |
| 128   | 1        | 2.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 19       | 40.43%  |
| 3600    | 4        | 8.51%   |
| 1333    | 4        | 8.51%   |
| 3200    | 3        | 6.38%   |
| 2400    | 2        | 4.26%   |
| 1866    | 2        | 4.26%   |
| Unknown | 2        | 4.26%   |
| 8400    | 1        | 2.13%   |
| 4800    | 1        | 2.13%   |
| 3800    | 1        | 2.13%   |
| 3000    | 1        | 2.13%   |
| 2667    | 1        | 2.13%   |
| 2200    | 1        | 2.13%   |
| 2133    | 1        | 2.13%   |
| 1800    | 1        | 2.13%   |
| 1067    | 1        | 2.13%   |
| 800     | 1        | 2.13%   |
| 667     | 1        | 2.13%   |

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
| Z-Star Microelectronics                | 2        | 25%     |
| Trust                                  | 1        | 12.5%   |
| Samsung Electronics                    | 1        | 12.5%   |
| Luxvisions Innotech Limited            | 1        | 12.5%   |
| Logitech                               | 1        | 12.5%   |
| Chicony Electronics                    | 1        | 12.5%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Z-Star Vimicro USB2.0 Camera                                    | 1        | 12.5%   |
| Z-Star Vega USB 2.0 Camera.                                     | 1        | 12.5%   |
| Trust QHD Webcam                                                | 1        | 12.5%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1        | 12.5%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1        | 12.5%   |
| Logitech Webcam C170                                            | 1        | 12.5%   |
| Chicony HD Webcam                                               | 1        | 12.5%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1        | 12.5%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Synaptics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1        | 100%    |

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
| 0     | 32       | 68.09%  |
| 1     | 7        | 14.89%  |
| 2     | 4        | 8.51%   |
| 3     | 2        | 4.26%   |
| 7     | 1        | 2.13%   |
| 4     | 1        | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 10       | 35.71%  |
| Communication controller | 5        | 17.86%  |
| Net/wireless             | 4        | 14.29%  |
| Storage/ata              | 2        | 7.14%   |
| Net/ethernet             | 2        | 7.14%   |
| Unassigned class         | 1        | 3.57%   |
| Sound                    | 1        | 3.57%   |
| Network                  | 1        | 3.57%   |
| Fingerprint reader       | 1        | 3.57%   |
| Camera                   | 1        | 3.57%   |

