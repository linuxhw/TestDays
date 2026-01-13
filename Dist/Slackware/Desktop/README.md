Slackware - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Slackware.

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

Total: 118

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | B450M PRO-M2 MAX            | [9028b6c4b3](https://linux-hardware.org/?probe=9028b6c4b3) | Dec 03, 2025 |
| Loongson      | LS3A6000-7A2000-1w-V0.1-... | [8d642f41ea](https://linux-hardware.org/?probe=8d642f41ea) | Oct 15, 2025 |
| ASUSTek       | ROG Maximus XI HERO         | [467e71b4b5](https://linux-hardware.org/?probe=467e71b4b5) | Jun 11, 2025 |
| ASUSTek       | P8H61-M PRO                 | [17eb905e70](https://linux-hardware.org/?probe=17eb905e70) | Feb 11, 2025 |
| Dell          | 0HGFJM A00                  | [10a1898523](https://linux-hardware.org/?probe=10a1898523) | Jan 13, 2025 |
| ASUSTek       | PRIME B550-PLUS             | [7ab225644f](https://linux-hardware.org/?probe=7ab225644f) | Dec 29, 2024 |
| HP            | 8643 SMVB                   | [3e1d8b1c0f](https://linux-hardware.org/?probe=3e1d8b1c0f) | Dec 29, 2024 |
| HP            | 8906 SMVB                   | [f52f996dd7](https://linux-hardware.org/?probe=f52f996dd7) | Dec 29, 2024 |
| HP            | 1495                        | [0accce2a1a](https://linux-hardware.org/?probe=0accce2a1a) | Dec 29, 2024 |
| Dell          | 0X4N41 A01                  | [3aca8429ec](https://linux-hardware.org/?probe=3aca8429ec) | Dec 28, 2024 |
| HP            | 1495                        | [309b63cf7b](https://linux-hardware.org/?probe=309b63cf7b) | Dec 28, 2024 |
| ASUSTek       | TUF Gaming H770-PRO WIFI    | [8e7f03f349](https://linux-hardware.org/?probe=8e7f03f349) | Dec 07, 2024 |
| ASUSTek       | H170M-PLUS                  | [302ff2daa0](https://linux-hardware.org/?probe=302ff2daa0) | Sep 11, 2024 |
| MSI           | B450M BAZOOKA MAX WIFI      | [fffa528570](https://linux-hardware.org/?probe=fffa528570) | Aug 07, 2024 |
| ASUSTek       | PRIME B760M-A D4            | [23f34741b6](https://linux-hardware.org/?probe=23f34741b6) | Jun 17, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [66de5464ad](https://linux-hardware.org/?probe=66de5464ad) | Jun 07, 2024 |
| ASRock        | B550M-HDV                   | [eb41f5c32d](https://linux-hardware.org/?probe=eb41f5c32d) | May 15, 2024 |
| Dell          | 0X9M3X A04                  | [4b6904a00b](https://linux-hardware.org/?probe=4b6904a00b) | May 13, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | [37bd870888](https://linux-hardware.org/?probe=37bd870888) | Apr 19, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [7204492392](https://linux-hardware.org/?probe=7204492392) | Mar 05, 2024 |
| MSI           | PRO X670-P WIFI             | [0ef39f433d](https://linux-hardware.org/?probe=0ef39f433d) | Feb 27, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | [2ed279c40d](https://linux-hardware.org/?probe=2ed279c40d) | Feb 16, 2024 |
| ASRock        | B550M-ITX/ac                | [27015117d0](https://linux-hardware.org/?probe=27015117d0) | Feb 13, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | [f536b283c6](https://linux-hardware.org/?probe=f536b283c6) | Jan 27, 2024 |
| HP            | ProLiant ML110 Gen9         | [ec93a55951](https://linux-hardware.org/?probe=ec93a55951) | Jan 19, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | [5dcf737641](https://linux-hardware.org/?probe=5dcf737641) | Jan 15, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [a2ec3f504c](https://linux-hardware.org/?probe=a2ec3f504c) | Jan 14, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [167fddc449](https://linux-hardware.org/?probe=167fddc449) | Jan 14, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | [7e506254e0](https://linux-hardware.org/?probe=7e506254e0) | Dec 22, 2023 |
| Gigabyte      | Z97M-DS3H                   | [4fd5ba2289](https://linux-hardware.org/?probe=4fd5ba2289) | Dec 04, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [24ebfe35c8](https://linux-hardware.org/?probe=24ebfe35c8) | Nov 22, 2023 |
| ASUSTek       | P7P55D-E                    | [f16aeca403](https://linux-hardware.org/?probe=f16aeca403) | Nov 03, 2023 |
| ASUSTek       | PRIME A320M-K               | [3f7bed61a8](https://linux-hardware.org/?probe=3f7bed61a8) | Jul 26, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [6087b16809](https://linux-hardware.org/?probe=6087b16809) | Jul 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [dd63c138ad](https://linux-hardware.org/?probe=dd63c138ad) | Jul 15, 2023 |
| Fujitsu       | FujitsuTP7000 -1            | [231d7f8182](https://linux-hardware.org/?probe=231d7f8182) | Jun 18, 2023 |
| MSI           | X99A GAMING 7               | [ec94d173a7](https://linux-hardware.org/?probe=ec94d173a7) | May 23, 2023 |
| ASRock        | N68-S3 FX                   | [0ed94fe810](https://linux-hardware.org/?probe=0ed94fe810) | May 10, 2023 |
| HEDYCOMPUT... | IH81MF-Q3                   | [3444236ed4](https://linux-hardware.org/?probe=3444236ed4) | Apr 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [7f052050d9](https://linux-hardware.org/?probe=7f052050d9) | Apr 10, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [70314c0c37](https://linux-hardware.org/?probe=70314c0c37) | Mar 23, 2023 |
| Dell          | 0MY171 A00                  | [47fd974afd](https://linux-hardware.org/?probe=47fd974afd) | Mar 20, 2023 |
| ASUSTek       | PRIME B450M-A               | [053498458e](https://linux-hardware.org/?probe=053498458e) | Mar 03, 2023 |
| Dell          | 0MY171 A00                  | [795f707b1a](https://linux-hardware.org/?probe=795f707b1a) | Feb 25, 2023 |
| Dell          | 04YP6J A03                  | [696cc9b57a](https://linux-hardware.org/?probe=696cc9b57a) | Feb 19, 2023 |
| ASRock        | 990FX Extreme4              | [7ce91f2b1e](https://linux-hardware.org/?probe=7ce91f2b1e) | Feb 16, 2023 |
| ASRock        | N68-S UCC                   | [cb4c89a390](https://linux-hardware.org/?probe=cb4c89a390) | Jan 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1c9dc6792e](https://linux-hardware.org/?probe=1c9dc6792e) | Jan 13, 2023 |
| ASRock        | B550 Taichi                 | [469f9d71e2](https://linux-hardware.org/?probe=469f9d71e2) | Dec 29, 2022 |
| Dell          | 0MY171 A00                  | [055bc4ea78](https://linux-hardware.org/?probe=055bc4ea78) | Dec 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | [c0bf1336d5](https://linux-hardware.org/?probe=c0bf1336d5) | Dec 12, 2022 |
| HP            | 8906 SMVB                   | [d000e4e926](https://linux-hardware.org/?probe=d000e4e926) | Dec 02, 2022 |
| Lenovo        | 31900058 STD                | [1408b2dc5f](https://linux-hardware.org/?probe=1408b2dc5f) | Nov 18, 2022 |
| HP            | 3031h                       | [b6849a29a2](https://linux-hardware.org/?probe=b6849a29a2) | Sep 24, 2022 |
| HP            | 3031h                       | [40160588bb](https://linux-hardware.org/?probe=40160588bb) | Sep 20, 2022 |
| MSI           | H110M PRO-VD                | [2299dc1786](https://linux-hardware.org/?probe=2299dc1786) | Sep 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a954ba4e86](https://linux-hardware.org/?probe=a954ba4e86) | Aug 26, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [9bfc03d98e](https://linux-hardware.org/?probe=9bfc03d98e) | Aug 20, 2022 |
| Dell          | 0200DY A03                  | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| Gigabyte      | N3160TN                     | [e2f44a8274](https://linux-hardware.org/?probe=e2f44a8274) | May 31, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [533b8a9f83](https://linux-hardware.org/?probe=533b8a9f83) | Apr 13, 2022 |
| MSI           | 970 GAMING                  | [25d8968f19](https://linux-hardware.org/?probe=25d8968f19) | Apr 13, 2022 |
| ASRock        | N68-S3 FX                   | [ca818bd06d](https://linux-hardware.org/?probe=ca818bd06d) | Apr 08, 2022 |
| MSI           | MS-7365                     | [8948dea4de](https://linux-hardware.org/?probe=8948dea4de) | Apr 07, 2022 |
| Unknown       | X79-P3                      | [40e38e9a8d](https://linux-hardware.org/?probe=40e38e9a8d) | Apr 07, 2022 |
| HP            | 0A08h                       | [4df5b0832f](https://linux-hardware.org/?probe=4df5b0832f) | Apr 06, 2022 |
| ASRock        | H410M-ITX/ac                | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| ASUSTek       | PRIME Z390-A                | [5307aba2c3](https://linux-hardware.org/?probe=5307aba2c3) | Mar 30, 2022 |
| Acer          | FMCP7A-ION-LE               | [bbce73c6d6](https://linux-hardware.org/?probe=bbce73c6d6) | Mar 14, 2022 |
| ASRock        | H270 Pro4                   | [ae79ca8557](https://linux-hardware.org/?probe=ae79ca8557) | Mar 12, 2022 |
| Lenovo        | 31900058 STD                | [bc59b862f4](https://linux-hardware.org/?probe=bc59b862f4) | Mar 02, 2022 |
| Biostar       | X470GTA                     | [8d400b49f8](https://linux-hardware.org/?probe=8d400b49f8) | Feb 13, 2022 |
| MSI           | G31TM-P21                   | [dda6a57223](https://linux-hardware.org/?probe=dda6a57223) | Feb 07, 2022 |
| HP            | 212B                        | [353b0dde99](https://linux-hardware.org/?probe=353b0dde99) | Jan 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| MSI           | G31TM-P21                   | [25d668ee95](https://linux-hardware.org/?probe=25d668ee95) | Jan 10, 2022 |
| MSI           | H61M-P31                    | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| HP            | 21B4 A01                    | [871b196cc2](https://linux-hardware.org/?probe=871b196cc2) | Nov 21, 2021 |
| HP            | 21B4 A01                    | [259232d98b](https://linux-hardware.org/?probe=259232d98b) | Nov 21, 2021 |
| Supermicro    | X9DA7/E                     | [3fc1ef2b58](https://linux-hardware.org/?probe=3fc1ef2b58) | Nov 09, 2021 |
| MSI           | B450M-A PRO MAX             | [b7df25ba5d](https://linux-hardware.org/?probe=b7df25ba5d) | Oct 25, 2021 |
| ASUSTek       | SABERTOOTH X99              | [64e5ee1691](https://linux-hardware.org/?probe=64e5ee1691) | Oct 13, 2021 |
| MSI           | B450M-A PRO MAX             | [17d37c5316](https://linux-hardware.org/?probe=17d37c5316) | Oct 12, 2021 |
| Intel         | DZ77RE-75K AAG39010-302     | [069c508e80](https://linux-hardware.org/?probe=069c508e80) | Sep 25, 2021 |
| Shuttle       | NC03U                       | [c5f76c4400](https://linux-hardware.org/?probe=c5f76c4400) | Sep 22, 2021 |
| ASUSTek       | SABERTOOTH X79              | [5d6732e14c](https://linux-hardware.org/?probe=5d6732e14c) | Aug 09, 2021 |
| HPE           | ProLiant MicroServer Gen... | [9ac798b737](https://linux-hardware.org/?probe=9ac798b737) | Aug 05, 2021 |
| HPE           | ProLiant MicroServer Gen... | [095745e5fb](https://linux-hardware.org/?probe=095745e5fb) | Jul 06, 2021 |
| HP            | 158A                        | [d612124939](https://linux-hardware.org/?probe=d612124939) | Jun 21, 2021 |
| ASRock        | H310CM-HDV                  | [3291e5d2de](https://linux-hardware.org/?probe=3291e5d2de) | Jun 19, 2021 |
| ASRock        | H87M Pro4                   | [8d4b7f121d](https://linux-hardware.org/?probe=8d4b7f121d) | Jun 02, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [6e60025ac5](https://linux-hardware.org/?probe=6e60025ac5) | May 25, 2021 |
| ASUSTek       | PRIME X370-PRO              | [3e5f76719a](https://linux-hardware.org/?probe=3e5f76719a) | May 24, 2021 |
| ASUSTek       | PRIME X370-PRO              | [c75f9d5c0d](https://linux-hardware.org/?probe=c75f9d5c0d) | May 23, 2021 |
| Dell          | 0PTTT9 A00                  | [e5b81a0da1](https://linux-hardware.org/?probe=e5b81a0da1) | May 20, 2021 |
| Gigabyte      | N3160TN                     | [2fd537312f](https://linux-hardware.org/?probe=2fd537312f) | May 14, 2021 |
| MSI           | G31TM-P21                   | [91c11ae82e](https://linux-hardware.org/?probe=91c11ae82e) | May 07, 2021 |
| Foxconn       | 2ADA                        | [425d15a5ce](https://linux-hardware.org/?probe=425d15a5ce) | Mar 09, 2021 |
| Dell          | 0TP412                      | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| ASRock        | B450M Steel Legend          | [e1424f6de3](https://linux-hardware.org/?probe=e1424f6de3) | Dec 31, 2020 |
| NetGear       | ReadyDATA 5200              | [96607f4270](https://linux-hardware.org/?probe=96607f4270) | Nov 12, 2020 |
| ASRock        | Z390M-ITX/ac                | [06eb8afdbc](https://linux-hardware.org/?probe=06eb8afdbc) | Oct 19, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [d42d44dd82](https://linux-hardware.org/?probe=d42d44dd82) | Jul 23, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [888f105221](https://linux-hardware.org/?probe=888f105221) | Jul 23, 2020 |
| ASUSTek       | M5A97 R2.0                  | [2eb600bb96](https://linux-hardware.org/?probe=2eb600bb96) | Jul 10, 2020 |
| ASUSTek       | M5A97 R2.0                  | [232221bf45](https://linux-hardware.org/?probe=232221bf45) | Jul 10, 2020 |
| Huanan        | X79-8D VAA31                | [bbfc99d048](https://linux-hardware.org/?probe=bbfc99d048) | Jan 22, 2020 |
| ASUSTek       | A68HM-PLUS                  | [505df04abc](https://linux-hardware.org/?probe=505df04abc) | Oct 27, 2019 |
| ASUSTek       | PRIME B350M-A               | [0b246f9623](https://linux-hardware.org/?probe=0b246f9623) | Oct 27, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [21d76cde28](https://linux-hardware.org/?probe=21d76cde28) | Oct 22, 2019 |
| ASUSTek       | Z97-A                       | [482c60ec21](https://linux-hardware.org/?probe=482c60ec21) | Oct 21, 2019 |
| Gigabyte      | M61SME-S2                   | [10469f1659](https://linux-hardware.org/?probe=10469f1659) | Oct 21, 2019 |
| HP            | 2B35                        | [45c5e4afbe](https://linux-hardware.org/?probe=45c5e4afbe) | Oct 21, 2019 |
| Gigabyte      | 970A-DS3P                   | [70ea4f97bf](https://linux-hardware.org/?probe=70ea4f97bf) | Oct 21, 2019 |
| ASUSTek       | Maximus VII HERO            | [4751f76aa2](https://linux-hardware.org/?probe=4751f76aa2) | Oct 20, 2019 |
| ASUSTek       | Maximus VII RANGER          | [71121ccd6f](https://linux-hardware.org/?probe=71121ccd6f) | Oct 20, 2019 |
| ASUSTek       | P5QLD PRO                   | [dabc1ee203](https://linux-hardware.org/?probe=dabc1ee203) | Oct 20, 2019 |
| Gigabyte      | X150M-PRO ECC-CF            | [39987c5d8e](https://linux-hardware.org/?probe=39987c5d8e) | Oct 10, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Slackware 15.0  | 61       | 61.62%  |
| Slackware 14.2  | 32       | 32.32%  |
| Slackware 14.2+ | 4        | 4.04%   |
| Slackware 15.0+ | 1        | 1.01%   |
| Slackware 14.1  | 1        | 1.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Slackware | 97       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Desktops | Percent |
|------------------|----------|---------|
| 5.15.63          | 6        | 5.66%   |
| 5.15.19          | 6        | 5.66%   |
| 5.10.28-Unraid   | 5        | 4.72%   |
| 5.19.17-Unraid   | 4        | 3.77%   |
| 5.19.17          | 4        | 3.77%   |
| 4.19.80          | 4        | 3.77%   |
| 5.15.94          | 3        | 2.83%   |
| 4.4.190          | 3        | 2.83%   |
| 6.12.7           | 2        | 1.89%   |
| 6.11.0-8-generic | 2        | 1.89%   |
| 6.1.79-Unraid    | 2        | 1.89%   |
| 5.15.30-Unraid   | 2        | 1.89%   |
| 5.15.27          | 2        | 1.89%   |
| 5.15.145         | 2        | 1.89%   |
| 4.4.240          | 2        | 1.89%   |
| 6.9.12           | 1        | 0.94%   |
| 6.7.4-cometdust  | 1        | 0.94%   |
| 6.6.7            | 1        | 0.94%   |
| 6.6.22           | 1        | 0.94%   |
| 6.6.18           | 1        | 0.94%   |
| 6.6.11           | 1        | 0.94%   |
| 6.12.18          | 1        | 0.94%   |
| 6.12.17          | 1        | 0.94%   |
| 6.12.1           | 1        | 0.94%   |
| 6.10.7           | 1        | 0.94%   |
| 6.10.5           | 1        | 0.94%   |
| 6.10.10-zen+     | 1        | 0.94%   |
| 6.10.0-rc2-rt3   | 1        | 0.94%   |
| 6.1.64-Unraid    | 1        | 0.94%   |
| 6.1.61           | 1        | 0.94%   |
| 6.1.38           | 1        | 0.94%   |
| 6.1.20           | 1        | 0.94%   |
| 6.1.13           | 1        | 0.94%   |
| 5.4.77           | 1        | 0.94%   |
| 5.4.53-APRL      | 1        | 0.94%   |
| 5.4.43           | 1        | 0.94%   |
| 5.4.0-rc2-vto    | 1        | 0.94%   |
| 5.19.16          | 1        | 0.94%   |
| 5.17.2           | 1        | 0.94%   |
| 5.17.0-custom    | 1        | 0.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.19.17  | 8        | 7.55%   |
| 5.15.63  | 6        | 5.66%   |
| 5.15.19  | 6        | 5.66%   |
| 5.10.28  | 5        | 4.72%   |
| 4.19.80  | 4        | 3.77%   |
| 5.15.94  | 3        | 2.83%   |
| 4.4.190  | 3        | 2.83%   |
| 6.12.7   | 2        | 1.89%   |
| 6.11.0   | 2        | 1.89%   |
| 6.1.79   | 2        | 1.89%   |
| 5.15.30  | 2        | 1.89%   |
| 5.15.27  | 2        | 1.89%   |
| 5.15.145 | 2        | 1.89%   |
| 5.14.15  | 2        | 1.89%   |
| 4.4.240  | 2        | 1.89%   |
| 6.9.12   | 1        | 0.94%   |
| 6.7.4    | 1        | 0.94%   |
| 6.6.7    | 1        | 0.94%   |
| 6.6.22   | 1        | 0.94%   |
| 6.6.18   | 1        | 0.94%   |
| 6.6.11   | 1        | 0.94%   |
| 6.12.18  | 1        | 0.94%   |
| 6.12.17  | 1        | 0.94%   |
| 6.12.1   | 1        | 0.94%   |
| 6.10.7   | 1        | 0.94%   |
| 6.10.5   | 1        | 0.94%   |
| 6.10.10  | 1        | 0.94%   |
| 6.10.0   | 1        | 0.94%   |
| 6.1.64   | 1        | 0.94%   |
| 6.1.61   | 1        | 0.94%   |
| 6.1.38   | 1        | 0.94%   |
| 6.1.20   | 1        | 0.94%   |
| 6.1.13   | 1        | 0.94%   |
| 5.4.77   | 1        | 0.94%   |
| 5.4.53   | 1        | 0.94%   |
| 5.4.43   | 1        | 0.94%   |
| 5.4.0    | 1        | 0.94%   |
| 5.19.16  | 1        | 0.94%   |
| 5.17.2   | 1        | 0.94%   |
| 5.17.0   | 1        | 0.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 29       | 27.88%  |
| 5.19    | 9        | 8.65%   |
| 5.10    | 8        | 7.69%   |
| 4.4     | 8        | 7.69%   |
| 4.19    | 8        | 7.69%   |
| 6.12    | 5        | 4.81%   |
| 6.1     | 5        | 4.81%   |
| 6.6     | 4        | 3.85%   |
| 6.10    | 4        | 3.85%   |
| 5.4     | 4        | 3.85%   |
| 5.14    | 4        | 3.85%   |
| 5.16    | 3        | 2.88%   |
| 6.11    | 2        | 1.92%   |
| 5.17    | 2        | 1.92%   |
| 5.13    | 2        | 1.92%   |
| 4.9     | 2        | 1.92%   |
| 6.9     | 1        | 0.96%   |
| 6.7     | 1        | 0.96%   |
| 5.12    | 1        | 0.96%   |
| 4.20    | 1        | 0.96%   |
| 3.10    | 1        | 0.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 96       | 98.97%  |
| loongarch64 | 1        | 1.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 35.35%  |
| XFCE       | 27       | 27.27%  |
| KDE5       | 26       | 26.26%  |
| MATE       | 2        | 2.02%   |
| FVWM       | 2        | 2.02%   |
| X-Generic  | 1        | 1.01%   |
| X-Cinnamon | 1        | 1.01%   |
| weston     | 1        | 1.01%   |
| KDE        | 1        | 1.01%   |
| GNOME      | 1        | 1.01%   |
| DWM        | 1        | 1.01%   |
| Cinnamon   | 1        | 1.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 52       | 51.49%  |
| Tty     | 26       | 25.74%  |
| Unknown | 16       | 15.84%  |
| Wayland | 7        | 6.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 40       | 40%     |
| SDDM    | 29       | 29%     |
| XDM     | 21       | 21%     |
| LightDM | 5        | 5%      |
| SLiM    | 3        | 3%      |
| TDM     | 1        | 1%      |
| GDM     | 1        | 1%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 48       | 48.98%  |
| Unknown     | 28       | 28.57%  |
| en_GB       | 4        | 4.08%   |
| ru_RU       | 3        | 3.06%   |
| it_IT       | 3        | 3.06%   |
| zh_CN       | 1        | 1.02%   |
| us          | 1        | 1.02%   |
| sr_RS@latin | 1        | 1.02%   |
| pt_PT       | 1        | 1.02%   |
| pt_BR       | 1        | 1.02%   |
| ja_JP       | 1        | 1.02%   |
| es_ES.UTF8  | 1        | 1.02%   |
| es_ES       | 1        | 1.02%   |
| es_AR       | 1        | 1.02%   |
| en_US.ASCII | 1        | 1.02%   |
| en_AU       | 1        | 1.02%   |
| C           | 1        | 1.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 49       | 50.52%  |
| EFI  | 48       | 49.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 59       | 60.82%  |
| Btrfs    | 14       | 14.43%  |
| Xfs      | 8        | 8.25%   |
| Rootfs   | 5        | 5.15%   |
| Overlay  | 4        | 4.12%   |
| Tmpfs    | 2        | 2.06%   |
| Reiserfs | 2        | 2.06%   |
| F2fs     | 1        | 1.03%   |
| Ext3     | 1        | 1.03%   |
| Ext2     | 1        | 1.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 65       | 65.66%  |
| MBR     | 26       | 26.26%  |
| Unknown | 8        | 8.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 55.1%   |
| Yes       | 44       | 44.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 68.04%  |
| Yes       | 31       | 31.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 29       | 29.9%   |
| MSI                 | 14       | 14.43%  |
| ASRock              | 13       | 13.4%   |
| Hewlett-Packard     | 10       | 10.31%  |
| Gigabyte Technology | 9        | 9.28%   |
| Dell                | 8        | 8.25%   |
| Supermicro          | 1        | 1.03%   |
| Shuttle             | 1        | 1.03%   |
| NetGear             | 1        | 1.03%   |
| Loongson            | 1        | 1.03%   |
| Lenovo              | 1        | 1.03%   |
| Intel               | 1        | 1.03%   |
| Huanan              | 1        | 1.03%   |
| HPE                 | 1        | 1.03%   |
| HEDYCOMPUTER        | 1        | 1.03%   |
| Fujitsu             | 1        | 1.03%   |
| Foxconn             | 1        | 1.03%   |
| Biostar             | 1        | 1.03%   |
| Acer                | 1        | 1.03%   |
| Unknown             | 1        | 1.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS All Series                      | 4        | 4.12%   |
| MSI MS-7D76                          | 2        | 2.06%   |
| ASRock N68-S3 FX                     | 2        | 2.06%   |
| Supermicro X9DA7/E                   | 1        | 1.03%   |
| Shuttle NC03U                        | 1        | 1.03%   |
| NetGear ReadyDATA 5200               | 1        | 1.03%   |
| MSI MS-7D67                          | 1        | 1.03%   |
| MSI MS-7C87                          | 1        | 1.03%   |
| MSI MS-7C52                          | 1        | 1.03%   |
| MSI MS-7C02                          | 1        | 1.03%   |
| MSI MS-7B84                          | 1        | 1.03%   |
| MSI MS-7B79                          | 1        | 1.03%   |
| MSI MS-7996                          | 1        | 1.03%   |
| MSI MS-7885                          | 1        | 1.03%   |
| MSI MS-7788                          | 1        | 1.03%   |
| MSI MS-7693                          | 1        | 1.03%   |
| MSI MS-7529                          | 1        | 1.03%   |
| MSI MS-7365                          | 1        | 1.03%   |
| Loongson TR11B0-T020150U             | 1        | 1.03%   |
| Lenovo H50-05 90BH001WIX             | 1        | 1.03%   |
| Intel DZ77RE-75K AAG39010-302        | 1        | 1.03%   |
| Huanan X79-8D VAA31                  | 1        | 1.03%   |
| HPE ProLiant MicroServer Gen10 Plus  | 1        | 1.03%   |
| HP Z620 Workstation                  | 1        | 1.03%   |
| HP Z440 Workstation                  | 1        | 1.03%   |
| HP xw8400 Workstation                | 1        | 1.03%   |
| HP t620 Quad Core TC                 | 1        | 1.03%   |
| HP ProLiant ML110 Gen9               | 1        | 1.03%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 1        | 1.03%   |
| HP Desktop M01-F0xxx                 | 1        | 1.03%   |
| HP Compaq dc7900 Small Form Factor   | 1        | 1.03%   |
| HP Compaq 8200 Elite SFF PC          | 1        | 1.03%   |
| HP 500-515na                         | 1        | 1.03%   |
| HEDYCOMPUTER IH81MF-Q3               | 1        | 1.03%   |
| Gigabyte Z97M-DS3H                   | 1        | 1.03%   |
| Gigabyte X570 AORUS MASTER           | 1        | 1.03%   |
| Gigabyte X570 AORUS ELITE            | 1        | 1.03%   |
| Gigabyte X150M-PRO ECC               | 1        | 1.03%   |
| Gigabyte N3160TN                     | 1        | 1.03%   |
| Gigabyte M61SME-S2                   | 1        | 1.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| ASUS PRIME               | 8        | 8.25%   |
| Dell Precision           | 5        | 5.15%   |
| ASUS ROG                 | 4        | 4.12%   |
| ASUS All                 | 4        | 4.12%   |
| Dell OptiPlex            | 3        | 3.09%   |
| ASUS TUF                 | 3        | 3.09%   |
| MSI MS-7D76              | 2        | 2.06%   |
| HP Compaq                | 2        | 2.06%   |
| Gigabyte X570            | 2        | 2.06%   |
| ASUS SABERTOOTH          | 2        | 2.06%   |
| ASRock N68-S3            | 2        | 2.06%   |
| Supermicro X9DA7         | 1        | 1.03%   |
| Shuttle NC03U            | 1        | 1.03%   |
| NetGear ReadyDATA        | 1        | 1.03%   |
| MSI MS-7D67              | 1        | 1.03%   |
| MSI MS-7C87              | 1        | 1.03%   |
| MSI MS-7C52              | 1        | 1.03%   |
| MSI MS-7C02              | 1        | 1.03%   |
| MSI MS-7B84              | 1        | 1.03%   |
| MSI MS-7B79              | 1        | 1.03%   |
| MSI MS-7996              | 1        | 1.03%   |
| MSI MS-7885              | 1        | 1.03%   |
| MSI MS-7788              | 1        | 1.03%   |
| MSI MS-7693              | 1        | 1.03%   |
| MSI MS-7529              | 1        | 1.03%   |
| MSI MS-7365              | 1        | 1.03%   |
| Loongson TR11B0-T020150U | 1        | 1.03%   |
| Lenovo H50-05            | 1        | 1.03%   |
| Intel DZ77RE-75K         | 1        | 1.03%   |
| Huanan X79-8D            | 1        | 1.03%   |
| HPE ProLiant             | 1        | 1.03%   |
| HP Z620                  | 1        | 1.03%   |
| HP Z440                  | 1        | 1.03%   |
| HP xw8400                | 1        | 1.03%   |
| HP t620                  | 1        | 1.03%   |
| HP ProLiant              | 1        | 1.03%   |
| HP Pavilion              | 1        | 1.03%   |
| HP Desktop               | 1        | 1.03%   |
| HP 500-515na             | 1        | 1.03%   |
| HEDYCOMPUTER IH81MF-Q3   | 1        | 1.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 13       | 13.4%   |
| 2020 | 10       | 10.31%  |
| 2012 | 9        | 9.28%   |
| 2015 | 8        | 8.25%   |
| 2018 | 7        | 7.22%   |
| 2014 | 7        | 7.22%   |
| 2011 | 7        | 7.22%   |
| 2022 | 6        | 6.19%   |
| 2017 | 6        | 6.19%   |
| 2021 | 4        | 4.12%   |
| 2016 | 4        | 4.12%   |
| 2008 | 4        | 4.12%   |
| 2010 | 3        | 3.09%   |
| 2009 | 3        | 3.09%   |
| 2013 | 2        | 2.06%   |
| 2007 | 2        | 2.06%   |
| 2024 | 1        | 1.03%   |
| 2023 | 1        | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 97       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 97       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 97       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 25       | 25.25%  |
| 16.01-24.0  | 22       | 22.22%  |
| 8.01-16.0   | 15       | 15.15%  |
| 64.01-256.0 | 11       | 11.11%  |
| 4.01-8.0    | 10       | 10.1%   |
| 3.01-4.0    | 7        | 7.07%   |
| 24.01-32.0  | 6        | 6.06%   |
| 1.01-2.0    | 3        | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 26       | 25.24%  |
| 1.01-2.0    | 22       | 21.36%  |
| 2.01-3.0    | 20       | 19.42%  |
| 3.01-4.0    | 9        | 8.74%   |
| 8.01-16.0   | 9        | 8.74%   |
| 0.51-1.0    | 6        | 5.83%   |
| 24.01-32.0  | 3        | 2.91%   |
| 16.01-24.0  | 3        | 2.91%   |
| 0.01-0.5    | 2        | 1.94%   |
| 32.01-64.0  | 1        | 0.97%   |
| 64.01-256.0 | 1        | 0.97%   |
| Unknown     | 1        | 0.97%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 23.76%  |
| 2      | 21       | 20.79%  |
| 3      | 17       | 16.83%  |
| 4      | 12       | 11.88%  |
| 5      | 7        | 6.93%   |
| 6      | 6        | 5.94%   |
| 0      | 5        | 4.95%   |
| 10     | 2        | 1.98%   |
| 9      | 2        | 1.98%   |
| 14     | 1        | 0.99%   |
| 13     | 1        | 0.99%   |
| 11     | 1        | 0.99%   |
| 8      | 1        | 0.99%   |
| 7      | 1        | 0.99%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 54.08%  |
| Yes       | 45       | 45.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 96       | 98.97%  |
| No        | 1        | 1.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 59.79%  |
| Yes       | 39       | 40.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 61.22%  |
| Yes       | 38       | 38.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 26       | 26.8%   |
| UK           | 12       | 12.37%  |
| Italy        | 6        | 6.19%   |
| Germany      | 6        | 6.19%   |
| Russia       | 5        | 5.15%   |
| Brazil       | 5        | 5.15%   |
| Japan        | 4        | 4.12%   |
| Canada       | 4        | 4.12%   |
| Spain        | 3        | 3.09%   |
| Kazakhstan   | 3        | 3.09%   |
| Hong Kong    | 3        | 3.09%   |
| Argentina    | 3        | 3.09%   |
| Sweden       | 2        | 2.06%   |
| Portugal     | 2        | 2.06%   |
| Hungary      | 2        | 2.06%   |
| France       | 2        | 2.06%   |
| China        | 2        | 2.06%   |
| Australia    | 2        | 2.06%   |
| South Africa | 1        | 1.03%   |
| Serbia       | 1        | 1.03%   |
| Poland       | 1        | 1.03%   |
| Malaysia     | 1        | 1.03%   |
| Bulgaria     | 1        | 1.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Yekaterinburg     | 3        | 3.03%   |
| Ust-Kamenogorsk   | 2        | 2.02%   |
| Tokyo             | 2        | 2.02%   |
| Springfield       | 2        | 2.02%   |
| San Elizario      | 2        | 2.02%   |
| Rome              | 2        | 2.02%   |
| Paris             | 2        | 2.02%   |
| Milan             | 2        | 2.02%   |
| Lisbon            | 2        | 2.02%   |
| Karcsa            | 2        | 2.02%   |
| Gainesville       | 2        | 2.02%   |
| Dallas            | 2        | 2.02%   |
| Buenos Aires      | 2        | 2.02%   |
| Winter Springs    | 1        | 1.01%   |
| Weilheim          | 1        | 1.01%   |
| Warsaw            | 1        | 1.01%   |
| Tsukuba           | 1        | 1.01%   |
| Toronto           | 1        | 1.01%   |
| Tiffin            | 1        | 1.01%   |
| Tendo             | 1        | 1.01%   |
| Tatuí            | 1        | 1.01%   |
| Stockholm         | 1        | 1.01%   |
| St Petersburg     | 1        | 1.01%   |
| Southend-on-Sea   | 1        | 1.01%   |
| Shrewsbury        | 1        | 1.01%   |
| Sham Shui Po      | 1        | 1.01%   |
| Seville           | 1        | 1.01%   |
| Senhora da Hora   | 1        | 1.01%   |
| Seattle           | 1        | 1.01%   |
| Santa Cruz do Sul | 1        | 1.01%   |
| Salta             | 1        | 1.01%   |
| Saint Paul        | 1        | 1.01%   |
| Rock              | 1        | 1.01%   |
| Rio do Sul        | 1        | 1.01%   |
| Rheine            | 1        | 1.01%   |
| Porto Alegre      | 1        | 1.01%   |
| Plovdiv           | 1        | 1.01%   |
| Perm              | 1        | 1.01%   |
| Penrith           | 1        | 1.01%   |
| Palma             | 1        | 1.01%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 42       | 102    | 20.49%  |
| Seagate                   | 40       | 76     | 19.51%  |
| Samsung Electronics       | 32       | 47     | 15.61%  |
| Toshiba                   | 14       | 31     | 6.83%   |
| Kingston                  | 11       | 15     | 5.37%   |
| Hitachi                   | 8        | 11     | 3.9%    |
| Crucial                   | 8        | 9      | 3.9%    |
| SK hynix                  | 4        | 4      | 1.95%   |
| Hewlett-Packard           | 4        | 4      | 1.95%   |
| A-DATA Technology         | 4        | 4      | 1.95%   |
| Transcend                 | 3        | 3      | 1.46%   |
| SanDisk                   | 3        | 3      | 1.46%   |
| Intel                     | 3        | 4      | 1.46%   |
| Team                      | 2        | 2      | 0.98%   |
| Realtek Semiconductor     | 2        | 2      | 0.98%   |
| Patriot                   | 2        | 2      | 0.98%   |
| Maxtor                    | 2        | 2      | 0.98%   |
| HGST                      | 2        | 2      | 0.98%   |
| China                     | 2        | 3      | 0.98%   |
| ZHITAI                    | 1        | 2      | 0.49%   |
| Unknown                   | 1        | 2      | 0.49%   |
| Silicon Motion            | 1        | 2      | 0.49%   |
| PNY                       | 1        | 2      | 0.49%   |
| Pioneer                   | 1        | 1      | 0.49%   |
| Phison Electronics        | 1        | 1      | 0.49%   |
| Micron/Crucial Technology | 1        | 1      | 0.49%   |
| Lexar                     | 1        | 1      | 0.49%   |
| KIOXIA                    | 1        | 2      | 0.49%   |
| Intenso                   | 1        | 1      | 0.49%   |
| HS-SSD-C100               | 1        | 1      | 0.49%   |
| Gigabyte Technology       | 1        | 1      | 0.49%   |
| Fujitsu                   | 1        | 1      | 0.49%   |
| DUEX                      | 1        | 1      | 0.49%   |
| DATSSD                    | 1        | 1      | 0.49%   |
| Apple                     | 1        | 2      | 0.49%   |
| Unknown                   | 1        | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 6        | 2.26%   |
| WDC WD20EFRX-68EUZN0 2TB                           | 4        | 1.5%    |
| Seagate ST4000DM004-2CV104 4TB                     | 4        | 1.5%    |
| WDC WD10EZEX-08WN4A0 1TB                           | 3        | 1.13%   |
| WDC WD1003FZEX-00MK2A0 1TB                         | 3        | 1.13%   |
| Seagate ST4000VN006-3CW104 4TB                     | 3        | 1.13%   |
| Seagate ST2000DM008-2FR102 2TB                     | 3        | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB                     | 3        | 1.13%   |
| Samsung SSD 970 EVO 250GB                          | 3        | 1.13%   |
| Crucial CT500MX500SSD1 500GB                       | 3        | 1.13%   |
| WDC WD5000AAKX-00ERMA0 500GB                       | 2        | 0.75%   |
| WDC WD40EZRX-00SPEB0 4TB                           | 2        | 0.75%   |
| WDC WD40EFRX-68N32N0 4TB                           | 2        | 0.75%   |
| WDC WD30EZRX-00SPEB0 3TB                           | 2        | 0.75%   |
| WDC WD10EZEX-00RKKA0 1TB                           | 2        | 0.75%   |
| Toshiba MQ01ABD100 1TB                             | 2        | 0.75%   |
| Toshiba HDWD110 1TB                                | 2        | 0.75%   |
| Seagate ST500DM002-1BD142 500GB                    | 2        | 0.75%   |
| Seagate ST4000VN008-2DR166 4TB                     | 2        | 0.75%   |
| Seagate ST31000524AS 1TB                           | 2        | 0.75%   |
| Seagate ST2000DX001-1NS164 2TB                     | 2        | 0.75%   |
| Seagate ST2000DM001-1CH164 2TB                     | 2        | 0.75%   |
| Seagate ST2000DL003-9VT166 2TB                     | 2        | 0.75%   |
| Seagate ST1000DM003-1SB102 1TB                     | 2        | 0.75%   |
| Seagate ST1000DM003-1ER162 1TB                     | 2        | 0.75%   |
| Seagate Expansion Desk 4TB                         | 2        | 0.75%   |
| Samsung SSD 970 EVO Plus 1TB                       | 2        | 0.75%   |
| Samsung SSD 850 PRO 256GB                          | 2        | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2        | 0.75%   |
| Realtek SPCC M.2 PCIe SSD 1024GB                   | 2        | 0.75%   |
| Kingston SA400S37240G 240GB SSD                    | 2        | 0.75%   |
| Kingston SA400S37120G 120GB SSD                    | 2        | 0.75%   |
| Kingston DataTraveler Max 256GB SSD                | 2        | 0.75%   |
| ZHITAI SC001 Active 1TB SSD                        | 1        | 0.38%   |
| ZHITAI PC005 Active 512GB                          | 1        | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB                       | 1        | 0.38%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                   | 1        | 0.38%   |
| WDC WDS100T2B0C-00PXH0 1TB                         | 1        | 0.38%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                     | 1        | 0.38%   |
| WDC WDS100T1X0E-00AFY0 1TB                         | 1        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 41       | 97     | 35.65%  |
| Seagate             | 40       | 72     | 34.78%  |
| Toshiba             | 13       | 26     | 11.3%   |
| Hitachi             | 8        | 11     | 6.96%   |
| Samsung Electronics | 5        | 5      | 4.35%   |
| Maxtor              | 2        | 2      | 1.74%   |
| HGST                | 2        | 2      | 1.74%   |
| Hewlett-Packard     | 2        | 2      | 1.74%   |
| Fujitsu             | 1        | 1      | 0.87%   |
| Unknown             | 1        | 1      | 0.87%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 21     | 23.21%  |
| Kingston            | 10       | 13     | 17.86%  |
| Crucial             | 6        | 7      | 10.71%  |
| Transcend           | 3        | 3      | 5.36%   |
| WDC                 | 2        | 3      | 3.57%   |
| Team                | 2        | 2      | 3.57%   |
| SanDisk             | 2        | 2      | 3.57%   |
| Intel               | 2        | 3      | 3.57%   |
| Hewlett-Packard     | 2        | 2      | 3.57%   |
| China               | 2        | 3      | 3.57%   |
| ZHITAI              | 1        | 1      | 1.79%   |
| Toshiba             | 1        | 3      | 1.79%   |
| SK hynix            | 1        | 1      | 1.79%   |
| PNY                 | 1        | 2      | 1.79%   |
| Pioneer             | 1        | 1      | 1.79%   |
| Patriot             | 1        | 1      | 1.79%   |
| Lexar               | 1        | 1      | 1.79%   |
| Intenso             | 1        | 1      | 1.79%   |
| HS-SSD-C100         | 1        | 1      | 1.79%   |
| DUEX                | 1        | 1      | 1.79%   |
| Apple               | 1        | 2      | 1.79%   |
| A-DATA Technology   | 1        | 1      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 74       | 219    | 46.84%  |
| SSD     | 47       | 75     | 29.75%  |
| NVMe    | 36       | 51     | 22.78%  |
| Unknown | 1        | 4      | 0.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 84       | 285    | 66.67%  |
| NVMe | 36       | 51     | 28.57%  |
| SAS  | 6        | 13     | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 55       | 90     | 35.48%  |
| 0.51-1.0   | 36       | 79     | 23.23%  |
| 1.01-2.0   | 22       | 29     | 14.19%  |
| 3.01-4.0   | 19       | 37     | 12.26%  |
| 4.01-10.0  | 11       | 31     | 7.1%    |
| 2.01-3.0   | 9        | 21     | 5.81%   |
| 10.01-20.0 | 3        | 7      | 1.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 19       | 19%     |
| 501-1000       | 16       | 16%     |
| 101-250        | 15       | 15%     |
| 1001-2000      | 14       | 14%     |
| More than 3000 | 10       | 10%     |
| 2001-3000      | 9        | 9%      |
| 251-500        | 8        | 8%      |
| 1-20           | 5        | 5%      |
| 51-100         | 3        | 3%      |
| 21-50          | 1        | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 19       | 19%     |
| 101-250        | 18       | 18%     |
| 501-1000       | 14       | 14%     |
| 251-500        | 11       | 11%     |
| 1-20           | 11       | 11%     |
| 1001-2000      | 8        | 8%      |
| 51-100         | 8        | 8%      |
| More than 3000 | 5        | 5%      |
| 21-50          | 3        | 3%      |
| 2001-3000      | 3        | 3%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD20EFRX-68EUZN0 2TB              | 2        | 3      | 5.13%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1        | 1      | 2.56%   |
| WDC WD5000BPKX-60HPJT0 500GB          | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 2.56%   |
| WDC WD5000AAKS-00A7B2 500GB           | 1        | 1      | 2.56%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1        | 2      | 2.56%   |
| WDC WD40EFAX-68JH4N1 4TB              | 1        | 4      | 2.56%   |
| WDC WD3200AAJS-65B4A0 320GB           | 1        | 1      | 2.56%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1        | 1      | 2.56%   |
| WDC WD30EZRX-00M                      | 1        | 1      | 2.56%   |
| WDC WD30EZRX-00D8PB0 3TB              | 1        | 1      | 2.56%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1        | 4      | 2.56%   |
| WDC WD20PURZ-85GU6Y0 2TB              | 1        | 1      | 2.56%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 2.56%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1        | 1      | 2.56%   |
| WDC WD10EALS-00Z8A0 1TB               | 1        | 2      | 2.56%   |
| WDC WD1003FZEX-00MK2A0 1TB            | 1        | 2      | 2.56%   |
| Seagate ST380011A 80GB                | 1        | 2      | 2.56%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 2.56%   |
| Seagate ST3500410AS 500GB             | 1        | 1      | 2.56%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 2.56%   |
| Seagate ST3000VX006-1HH166 3TB        | 1        | 1      | 2.56%   |
| Seagate ST2000DL003-9VT166 2TB        | 1        | 1      | 2.56%   |
| Seagate ST1000VM002-1SD102 1TB        | 1        | 1      | 2.56%   |
| Seagate ST1000NM0011 1TB              | 1        | 2      | 2.56%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1        | 1      | 2.56%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 2      | 2.56%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD    | 1        | 1      | 2.56%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 2.56%   |
| Maxtor 4G120J6 128GB                  | 1        | 1      | 2.56%   |
| Intel SSDSA2M080G2GC 80GB             | 1        | 1      | 2.56%   |
| Hitachi HUA723030ALA640 3TB           | 1        | 1      | 2.56%   |
| Hitachi HDS721050CLA660 500GB         | 1        | 1      | 2.56%   |
| Hitachi HDS721016CLA382 160GB         | 1        | 1      | 2.56%   |
| HGST HDN726040ALE614 4TB              | 1        | 1      | 2.56%   |
| DUEX DX300256A5xnEMLC 256GB SSD       | 1        | 1      | 2.56%   |
| Unknown                               | 1        | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 29     | 45.71%  |
| Seagate             | 9        | 13     | 25.71%  |
| Hitachi             | 3        | 3      | 8.57%   |
| SanDisk             | 1        | 1      | 2.86%   |
| Samsung Electronics | 1        | 1      | 2.86%   |
| Maxtor              | 1        | 1      | 2.86%   |
| Intel               | 1        | 1      | 2.86%   |
| HGST                | 1        | 1      | 2.86%   |
| DUEX                | 1        | 1      | 2.86%   |
| Unknown             | 1        | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 15       | 28     | 50%     |
| Seagate | 9        | 13     | 30%     |
| Hitachi | 3        | 3      | 10%     |
| Maxtor  | 1        | 1      | 3.33%   |
| HGST    | 1        | 1      | 3.33%   |
| Unknown | 1        | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 27       | 47     | 84.38%  |
| SSD  | 4        | 4      | 12.5%   |
| NVMe | 1        | 1      | 3.13%   |

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
| Works    | 79       | 250    | 61.72%  |
| Malfunc  | 32       | 52     | 25%     |
| Detected | 17       | 47     | 13.28%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 49       | 28.49%  |
| AMD                             | 41       | 23.84%  |
| Samsung Electronics             | 19       | 11.05%  |
| ASMedia Technology              | 14       | 8.14%   |
| Marvell Technology Group        | 8        | 4.65%   |
| Realtek Semiconductor           | 5        | 2.91%   |
| Nvidia                          | 5        | 2.91%   |
| JMicron Technology              | 4        | 2.33%   |
| SK hynix                        | 3        | 1.74%   |
| SanDisk                         | 3        | 1.74%   |
| Micron/Crucial Technology       | 3        | 1.74%   |
| Kingston Technology Company     | 2        | 1.16%   |
| Broadcom / LSI                  | 2        | 1.16%   |
| Yangtze Memory Technologies     | 1        | 0.58%   |
| Toshiba America Info Systems    | 1        | 0.58%   |
| Silicon Motion                  | 1        | 0.58%   |
| Silicon Image                   | 1        | 0.58%   |
| Phison Electronics              | 1        | 0.58%   |
| Nextorage                       | 1        | 0.58%   |
| MAXIO Technology (Hangzhou)     | 1        | 0.58%   |
| LSI Logic / Symbios Logic       | 1        | 0.58%   |
| Loongson Technology             | 1        | 0.58%   |
| Lite-On Technology              | 1        | 0.58%   |
| KIOXIA                          | 1        | 0.58%   |
| Hefei DATANG Storage Technology | 1        | 0.58%   |
| Adaptec                         | 1        | 0.58%   |
| 3ware                           | 1        | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 22       | 10.23%  |
| AMD 400 Series Chipset SATA Controller                                        | 14       | 6.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 13       | 6.05%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                 | 10       | 4.65%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                     | 6        | 2.79%   |
| AMD 500 Series Chipset SATA Controller                                        | 6        | 2.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 5        | 2.33%   |
| Nvidia MCP61 SATA Controller                                                  | 4        | 1.86%   |
| Nvidia MCP61 IDE                                                              | 4        | 1.86%   |
| Intel SATA Controller [RAID mode]                                             | 4        | 1.86%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 4        | 1.86%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 4        | 1.86%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 3        | 1.4%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller              | 3        | 1.4%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 3        | 1.4%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 3        | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 3        | 1.4%    |
| AMD 600 Series Chipset SATA Controller                                        | 3        | 1.4%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 2        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2        | 0.93%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                             | 2        | 0.93%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                             | 2        | 0.93%   |
| JMicron JMB58x AHCI SATA controller                                           | 2        | 0.93%   |
| Intel Raptor Lake SATA AHCI Controller                                        | 2        | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 0.93%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 2        | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                          | 2        | 0.93%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode] | 2        | 0.93%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode] | 2        | 0.93%   |
| Intel 631xESB/632xESB IDE Controller                                          | 2        | 0.93%   |
| Intel 4 Series Chipset PT IDER Controller                                     | 2        | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2        | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                        | 2        | 0.93%   |
| Yangtze Memory ZHITAI PC005 NVMe SSD                                          | 1        | 0.47%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1        | 0.47%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                             | 1        | 0.47%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 1        | 0.47%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller              | 1        | 0.47%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1        | 0.47%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)     | 1        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 79       | 51.63%  |
| NVMe | 37       | 24.18%  |
| IDE  | 19       | 12.42%  |
| RAID | 12       | 7.84%   |
| SAS  | 4        | 2.61%   |
| SCSI | 2        | 1.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 51       | 52.58%  |
| AMD      | 45       | 46.39%  |
| Loongson | 1        | 1.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 5.1%    |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 3.06%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 3        | 3.06%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 2        | 2.04%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 2        | 2.04%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 2.04%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 2.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 2.04%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 2.04%   |
| AMD Ryzen 9 7900 12-Core Processor          | 2        | 2.04%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 2.04%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 2.04%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 2.04%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 2.04%   |
| AMD Athlon II X2 250 Processor              | 2        | 2.04%   |
| Loongson Loongson 3A                        | 1        | 1.02%   |
| Intel Xeon CPU X5355 @ 2.66GHz              | 1        | 1.02%   |
| Intel Xeon CPU X3450 @ 2.67GHz              | 1        | 1.02%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz         | 1        | 1.02%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1        | 1.02%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 1.02%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 1        | 1.02%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1        | 1.02%   |
| Intel Xeon CPU E5-1603 v3 @ 2.80GHz         | 1        | 1.02%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1        | 1.02%   |
| Intel Xeon CPU 5160 @ 3.00GHz               | 1        | 1.02%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 1.02%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 1.02%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 1        | 1.02%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 1.02%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 1.02%   |
| Intel Core i9-10900 CPU @ 2.80GHz           | 1        | 1.02%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.02%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.02%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.02%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.02%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 1        | 1.02%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.02%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.02%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 12       | 12.24%  |
| AMD Ryzen 5        | 12       | 12.24%  |
| Intel Core i7      | 11       | 11.22%  |
| Intel Core i5      | 11       | 11.22%  |
| AMD Ryzen 9        | 9        | 9.18%   |
| AMD Ryzen 7        | 8        | 8.16%   |
| AMD FX             | 6        | 6.12%   |
| Intel Pentium      | 4        | 4.08%   |
| Other              | 3        | 3.06%   |
| Intel Core 2 Duo   | 3        | 3.06%   |
| Intel Core i9      | 2        | 2.04%   |
| Intel Core 2 Quad  | 2        | 2.04%   |
| AMD Ryzen 3        | 2        | 2.04%   |
| AMD Athlon II X2   | 2        | 2.04%   |
| Intel Pentium Gold | 1        | 1.02%   |
| Intel Pentium Dual | 1        | 1.02%   |
| Intel Core i3      | 1        | 1.02%   |
| Intel Celeron      | 1        | 1.02%   |
| Intel Atom         | 1        | 1.02%   |
| AMD Ryzen 7 PRO    | 1        | 1.02%   |
| AMD GX             | 1        | 1.02%   |
| AMD Athlon 64 X2   | 1        | 1.02%   |
| AMD A8             | 1        | 1.02%   |
| AMD A4             | 1        | 1.02%   |
| AMD A10            | 1        | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 35       | 35.71%  |
| 6      | 16       | 16.33%  |
| 2      | 16       | 16.33%  |
| 8      | 13       | 13.27%  |
| 16     | 7        | 7.14%   |
| 12     | 5        | 5.1%    |
| 14     | 2        | 2.04%   |
| 10     | 2        | 2.04%   |
| 3      | 1        | 1.02%   |
| 1      | 1        | 1.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 92       | 94.85%  |
| 2      | 5        | 5.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 67       | 69.07%  |
| 1      | 30       | 30.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 96       | 98.97%  |
| 64-bit         | 1        | 1.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 33.67%  |
| 0x08701021 | 7        | 7.14%   |
| 0x306c3    | 5        | 5.1%    |
| 0x206d7    | 4        | 4.08%   |
| 0x306f2    | 3        | 3.06%   |
| 0x306a9    | 3        | 3.06%   |
| 0x1067a    | 3        | 3.06%   |
| 0x08701013 | 3        | 3.06%   |
| 0x906ed    | 2        | 2.04%   |
| 0x906ea    | 2        | 2.04%   |
| 0x206a7    | 2        | 2.04%   |
| 0x0a50000c | 2        | 2.04%   |
| 0x0a201016 | 2        | 2.04%   |
| 0x08108109 | 2        | 2.04%   |
| 0x06001119 | 2        | 2.04%   |
| 0x06000822 | 2        | 2.04%   |
| 0xa0653    | 1        | 1.02%   |
| 0x906e9    | 1        | 1.02%   |
| 0x6fd      | 1        | 1.02%   |
| 0x6fb      | 1        | 1.02%   |
| 0x506e3    | 1        | 1.02%   |
| 0x406c4    | 1        | 1.02%   |
| 0x306e4    | 1        | 1.02%   |
| 0x20655    | 1        | 1.02%   |
| 0x106e5    | 1        | 1.02%   |
| 0x106c2    | 1        | 1.02%   |
| 0x0a20120a | 1        | 1.02%   |
| 0x0a20102b | 1        | 1.02%   |
| 0x0810100b | 1        | 1.02%   |
| 0x0800820d | 1        | 1.02%   |
| 0x08001138 | 1        | 1.02%   |
| 0x08001126 | 1        | 1.02%   |
| 0x07030105 | 1        | 1.02%   |
| 0x07000110 | 1        | 1.02%   |
| 0x06000852 | 1        | 1.02%   |
| 0x010000b6 | 1        | 1.02%   |
| 0x00000000 | 1        | 1.02%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 13       | 13.4%   |
| Haswell          | 11       | 11.34%  |
| SandyBridge      | 9        | 9.28%   |
| KabyLake         | 9        | 9.28%   |
| Zen 3            | 7        | 7.22%   |
| Piledriver       | 6        | 6.19%   |
| Zen+             | 5        | 5.15%   |
| Unknown          | 5        | 5.15%   |
| Zen              | 4        | 4.12%   |
| Penryn           | 4        | 4.12%   |
| IvyBridge        | 4        | 4.12%   |
| Core             | 4        | 4.12%   |
| CometLake        | 3        | 3.09%   |
| K10              | 2        | 2.06%   |
| Bulldozer        | 2        | 2.06%   |
| Westmere         | 1        | 1.03%   |
| Skylake          | 1        | 1.03%   |
| Silvermont       | 1        | 1.03%   |
| Puma             | 1        | 1.03%   |
| Nehalem          | 1        | 1.03%   |
| K8 Hammer        | 1        | 1.03%   |
| Jaguar           | 1        | 1.03%   |
| Bonnell          | 1        | 1.03%   |
| Alderlake Hybrid | 1        | 1.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 38       | 38.38%  |
| Nvidia                     | 34       | 34.34%  |
| Intel                      | 23       | 23.23%  |
| Matrox Electronics Systems | 3        | 3.03%   |
| Loongson Technology        | 1        | 1.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 6.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 3.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 3.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 3.81%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 2.86%   |
| AMD Raphael                                                                 | 3        | 2.86%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 2.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.9%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.9%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.9%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.9%    |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.9%    |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 1.9%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 2        | 1.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.9%    |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 1.9%    |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 2        | 1.9%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.9%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.9%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.95%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 0.95%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.95%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.95%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.95%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.95%   |
| Nvidia GK110GL [Quadro K5200]                                               | 1        | 0.95%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.95%   |
| Nvidia GK104GL [Quadro K5000]                                               | 1        | 0.95%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                           | 1        | 0.95%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 0.95%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.95%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 0.95%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 0.95%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 1        | 0.95%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 0.95%   |
| Nvidia G80GL [Quadro FX 4600]                                               | 1        | 0.95%   |
| Nvidia G71GL [Quadro FX 1500]                                               | 1        | 0.95%   |
| Nvidia C79 [ION]                                                            | 1        | 0.95%   |
| Nvidia AD107 [GeForce RTX 4060]                                             | 1        | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x AMD                 | 32       | 32.99%  |
| 1 x Nvidia              | 31       | 31.96%  |
| 1 x Intel               | 20       | 20.62%  |
| 2 x AMD                 | 4        | 4.12%   |
| 1 x Matrox              | 3        | 3.09%   |
| Other                   | 2        | 2.06%   |
| 2 x Nvidia              | 1        | 1.03%   |
| 1 x Loongson Technology | 1        | 1.03%   |
| Intel + Nvidia          | 1        | 1.03%   |
| Intel + AMD             | 1        | 1.03%   |
| AMD + Nvidia            | 1        | 1.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 66       | 68.04%  |
| Proprietary | 18       | 18.56%  |
| Unknown     | 13       | 13.4%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 41       | 42.27%  |
| 0.51-1.0   | 12       | 12.37%  |
| 1.01-2.0   | 11       | 11.34%  |
| 3.01-4.0   | 9        | 9.28%   |
| 7.01-8.0   | 8        | 8.25%   |
| 8.01-16.0  | 6        | 6.19%   |
| 0.01-0.5   | 6        | 6.19%   |
| 5.01-6.0   | 2        | 2.06%   |
| 2.01-3.0   | 1        | 1.03%   |
| 16.01-24.0 | 1        | 1.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Dell                    | 16       | 17.2%   |
| Samsung Electronics     | 12       | 12.9%   |
| Hewlett-Packard         | 9        | 9.68%   |
| Goldstar                | 8        | 8.6%    |
| BenQ                    | 8        | 8.6%    |
| Ancor Communications    | 5        | 5.38%   |
| Acer                    | 5        | 5.38%   |
| ViewSonic               | 3        | 3.23%   |
| Toshiba                 | 2        | 2.15%   |
| Lenovo                  | 2        | 2.15%   |
| ASUSTek Computer        | 2        | 2.15%   |
| AOC                     | 2        | 2.15%   |
| Xiaomi                  | 1        | 1.08%   |
| Wacom                   | 1        | 1.08%   |
| Unknown                 | 1        | 1.08%   |
| TopView                 | 1        | 1.08%   |
| SZS                     | 1        | 1.08%   |
| RTK                     | 1        | 1.08%   |
| ONN                     | 1        | 1.08%   |
| NEC Computers           | 1        | 1.08%   |
| MSI                     | 1        | 1.08%   |
| JVC                     | 1        | 1.08%   |
| IOD                     | 1        | 1.08%   |
| Iiyama                  | 1        | 1.08%   |
| Hitachi                 | 1        | 1.08%   |
| Gigabyte Technology     | 1        | 1.08%   |
| GDH                     | 1        | 1.08%   |
| Eizo                    | 1        | 1.08%   |
| CTC                     | 1        | 1.08%   |
| Chi Mei Optoelectronics | 1        | 1.08%   |
| Unknown                 | 1        | 1.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 2        | 2.06%   |
| Goldstar HDR WQHD GSM7756 3440x1440 820x346mm 35.0-inch               | 2        | 2.06%   |
| Dell G2724D DELD175 2560x1440 596x335mm 26.9-inch                     | 2        | 2.06%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                    | 1        | 1.03%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1        | 1.03%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch            | 1        | 1.03%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                         | 1        | 1.03%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                         | 1        | 1.03%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 1.03%   |
| Toshiba TV TSB0206 1920x1080                                          | 1        | 1.03%   |
| Toshiba TV TSB0108 1920x1080 698x393mm 31.5-inch                      | 1        | 1.03%   |
| TopView HDMI TOP0814 1600x900 430x270mm 20.0-inch                     | 1        | 1.03%   |
| SZS MR124A SZS1240 1920x1080 527x296mm 23.8-inch                      | 1        | 1.03%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch  | 1        | 1.03%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                      | 1        | 1.03%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1        | 1.03%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1        | 1.03%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1        | 1.03%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1        | 1.03%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1        | 1.03%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1        | 1.03%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 1.03%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1        | 1.03%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                     | 1        | 1.03%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 950x540mm 43.0-inch | 1        | 1.03%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 597x336mm 27.0-inch    | 1        | 1.03%   |
| Samsung Electronics B2430L SAM0644 1920x1080 521x293mm 23.5-inch      | 1        | 1.03%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 1        | 1.03%   |
| ONN 100002487 ONN0101 1920x1080 520x320mm 24.0-inch                   | 1        | 1.03%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch       | 1        | 1.03%   |
| MSI MAG342CQPV MSI4DB6 3440x1440 797x333mm 34.0-inch                  | 1        | 1.03%   |
| Lenovo LEN L171p LEN24C9 1280x1024 338x270mm 17.0-inch                | 1        | 1.03%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1        | 1.03%   |
| JVC FPDEUFT3 JVC21BE 1920x540                                         | 1        | 1.03%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                  | 1        | 1.03%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch                | 1        | 1.03%   |
| Hitachi HDMI HEC0088 1920x540                                         | 1        | 1.03%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch         | 1        | 1.03%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1        | 1.03%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch          | 1        | 1.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 42       | 45.65%  |
| 1280x1024 (SXGA)   | 8        | 8.7%    |
| 2560x1440 (QHD)    | 7        | 7.61%   |
| 3840x2160 (4K)     | 6        | 6.52%   |
| 1366x768 (WXGA)    | 6        | 6.52%   |
| 1680x1050 (WSXGA+) | 5        | 5.43%   |
| 3440x1440          | 4        | 4.35%   |
| 1920x1200 (WUXGA)  | 4        | 4.35%   |
| 1920x540           | 3        | 3.26%   |
| 1440x900 (WXGA+)   | 2        | 2.17%   |
| 3200x1080          | 1        | 1.09%   |
| 2288x1287          | 1        | 1.09%   |
| 1600x1200          | 1        | 1.09%   |
| 1024x768 (XGA)     | 1        | 1.09%   |
| Unknown            | 1        | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 17       | 17.89%  |
| 27      | 14       | 14.74%  |
| 21      | 11       | 11.58%  |
| 23      | 8        | 8.42%   |
| Unknown | 7        | 7.37%   |
| 22      | 4        | 4.21%   |
| 19      | 4        | 4.21%   |
| 18      | 4        | 4.21%   |
| 17      | 4        | 4.21%   |
| 15      | 4        | 4.21%   |
| 20      | 3        | 3.16%   |
| 35      | 2        | 2.11%   |
| 34      | 2        | 2.11%   |
| 31      | 2        | 2.11%   |
| 142     | 1        | 1.05%   |
| 84      | 1        | 1.05%   |
| 74      | 1        | 1.05%   |
| 72      | 1        | 1.05%   |
| 52      | 1        | 1.05%   |
| 48      | 1        | 1.05%   |
| 46      | 1        | 1.05%   |
| 43      | 1        | 1.05%   |
| 12      | 1        | 1.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 36       | 38.71%  |
| 401-500        | 23       | 24.73%  |
| 301-350        | 8        | 8.6%    |
| Unknown        | 7        | 7.53%   |
| 601-700        | 3        | 3.23%   |
| 351-400        | 3        | 3.23%   |
| 1501-2000      | 3        | 3.23%   |
| 1001-1500      | 3        | 3.23%   |
| 801-900        | 2        | 2.15%   |
| 701-800        | 2        | 2.15%   |
| More than 2000 | 1        | 1.08%   |
| 201-300        | 1        | 1.08%   |
| 901-1000       | 1        | 1.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 51       | 58.62%  |
| 16/10   | 13       | 14.94%  |
| 5/4     | 5        | 5.75%   |
| Unknown | 5        | 5.75%   |
| 21/9    | 4        | 4.6%    |
| 4/3     | 3        | 3.45%   |
| 6/5     | 2        | 2.3%    |
| 32/9    | 1        | 1.15%   |
| 3/2     | 1        | 1.15%   |
| 1.96    | 1        | 1.15%   |
| 1.00    | 1        | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 31       | 33.7%   |
| 301-350        | 14       | 15.22%  |
| 151-200        | 9        | 9.78%   |
| 141-150        | 7        | 7.61%   |
| Unknown        | 7        | 7.61%   |
| 351-500        | 6        | 6.52%   |
| More than 1000 | 5        | 5.43%   |
| 251-300        | 5        | 5.43%   |
| 101-110        | 4        | 4.35%   |
| 501-1000       | 3        | 3.26%   |
| 71-80          | 1        | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 51       | 55.43%  |
| 101-120 | 24       | 26.09%  |
| Unknown | 7        | 7.61%   |
| 1-50    | 6        | 6.52%   |
| 121-160 | 4        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 70       | 72.16%  |
| 0     | 13       | 13.4%   |
| 2     | 11       | 11.34%  |
| 3     | 3        | 3.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 56       | 41.79%  |
| Intel                           | 42       | 31.34%  |
| Ralink Technology               | 5        | 3.73%   |
| Qualcomm Atheros                | 5        | 3.73%   |
| Broadcom                        | 5        | 3.73%   |
| TP-Link                         | 4        | 2.99%   |
| Nvidia                          | 4        | 2.99%   |
| MediaTek                        | 4        | 2.99%   |
| VIA Technologies                | 1        | 0.75%   |
| Ralink                          | 1        | 0.75%   |
| Qualcomm Atheros Communications | 1        | 0.75%   |
| Qualcomm                        | 1        | 0.75%   |
| Micro Star International        | 1        | 0.75%   |
| Mellanox Technologies           | 1        | 0.75%   |
| Dell                            | 1        | 0.75%   |
| Chelsio Communications          | 1        | 0.75%   |
| Broadcom Limited                | 1        | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 41       | 26.62%  |
| Intel I211 Gigabit Network Connection                                         | 8        | 5.19%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 3.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 2.6%    |
| Intel Wi-Fi 6 AX200                                                           | 4        | 2.6%    |
| Intel Ethernet Connection (2) I218-V                                          | 4        | 2.6%    |
| Intel 82574L Gigabit Network Connection                                       | 4        | 2.6%    |
| Ralink MT7601U Wireless Adapter                                               | 3        | 1.95%   |
| Nvidia MCP61 Ethernet                                                         | 3        | 1.95%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 3        | 1.95%   |
| Intel Ethernet Controller I225-V                                              | 3        | 1.95%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 1.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 1.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 1.3%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 1.3%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 1.3%    |
| Intel I350 Gigabit Network Connection                                         | 2        | 1.3%    |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.3%    |
| Intel 82579V Gigabit Network Connection                                       | 2        | 1.3%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 1.3%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 2        | 1.3%    |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 0.65%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 0.65%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                         | 1        | 0.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.65%   |
| TP-Link 802.11ac NIC                                                          | 1        | 0.65%   |
| Realtek USB 10/100/1G/2.5 LAN                                                 | 1        | 0.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.65%   |
| Ralink RT5372 Wireless Adapter                                                | 1        | 0.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 0.65%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 0.65%   |
| Qualcomm Nokia X30 5G                                                         | 1        | 0.65%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 0.65%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.65%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 33.33%  |
| Realtek Semiconductor           | 6        | 15.38%  |
| Ralink Technology               | 5        | 12.82%  |
| TP-Link                         | 4        | 10.26%  |
| MediaTek                        | 4        | 10.26%  |
| Qualcomm Atheros                | 3        | 7.69%   |
| Ralink                          | 1        | 2.56%   |
| Qualcomm Atheros Communications | 1        | 2.56%   |
| Micro Star International        | 1        | 2.56%   |
| Dell                            | 1        | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 4        | 10.26%  |
| Ralink MT7601U Wireless Adapter                                               | 3        | 7.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 3        | 7.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 7.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 5.13%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 5.13%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 2.56%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                         | 1        | 2.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 2.56%   |
| TP-Link 802.11ac NIC                                                          | 1        | 2.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 2.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 2.56%   |
| Ralink RT5372 Wireless Adapter                                                | 1        | 2.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 2.56%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 2.56%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 2.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 2.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 2.56%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 2.56%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]    | 1        | 2.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 1        | 2.56%   |
| Intel Wireless 7260                                                           | 1        | 2.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 1        | 2.56%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1        | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1        | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 2.56%   |
| Intel 700 Series Chipset CNVi WiFi                                            | 1        | 2.56%   |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887]         | 1        | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Realtek Semiconductor  | 54       | 49.54%  |
| Intel                  | 38       | 34.86%  |
| Broadcom               | 5        | 4.59%   |
| Nvidia                 | 4        | 3.67%   |
| Qualcomm Atheros       | 3        | 2.75%   |
| VIA Technologies       | 1        | 0.92%   |
| Qualcomm               | 1        | 0.92%   |
| Mellanox Technologies  | 1        | 0.92%   |
| Chelsio Communications | 1        | 0.92%   |
| Broadcom Limited       | 1        | 0.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 41       | 35.65%  |
| Intel I211 Gigabit Network Connection                                         | 8        | 6.96%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7        | 6.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 3.48%   |
| Intel Ethernet Connection (2) I218-V                                          | 4        | 3.48%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 3.48%   |
| Nvidia MCP61 Ethernet                                                         | 3        | 2.61%   |
| Intel Ethernet Controller I225-V                                              | 3        | 2.61%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 2.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 1.74%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 1.74%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.74%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 1.74%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 1.74%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 2        | 1.74%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 0.87%   |
| Realtek USB 10/100/1G/2.5 LAN                                                 | 1        | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.87%   |
| Qualcomm Nokia X30 5G                                                         | 1        | 0.87%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.87%   |
| Nvidia MCP79 Ethernet                                                         | 1        | 0.87%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 0.87%   |
| Intel Ethernet Controller I226-V                                              | 1        | 0.87%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.87%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 0.87%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.87%   |
| Intel Ethernet Connection (11) I219-LM                                        | 1        | 0.87%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 0.87%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.87%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 0.87%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1        | 0.87%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 0.87%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                              | 1        | 0.87%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 1        | 0.87%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 0.87%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 96       | 71.64%  |
| WiFi     | 38       | 28.36%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 79       | 82.29%  |
| WiFi     | 17       | 17.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 57       | 57.58%  |
| 2     | 27       | 27.27%  |
| 3     | 7        | 7.07%   |
| 4     | 3        | 3.03%   |
| 0     | 3        | 3.03%   |
| 5     | 2        | 2.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 83       | 83.84%  |
| Yes  | 16       | 16.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Cambridge Silicon Radio  | 14       | 36.84%  |
| Intel                    | 11       | 28.95%  |
| MediaTek                 | 5        | 13.16%  |
| Realtek Semiconductor    | 2        | 5.26%   |
| Micro Star International | 2        | 5.26%   |
| Broadcom                 | 2        | 5.26%   |
| TP-Link                  | 1        | 2.63%   |
| ASUSTek Computer         | 1        | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14       | 36.84%  |
| MediaTek Wireless_Device                            | 5        | 13.16%  |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 7.89%   |
| Intel AX200 Bluetooth                               | 3        | 7.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 5.26%   |
| TP-Link TP-T@- UB500 Adapter                        | 1        | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 2.63%   |
| Realtek Bluetooth Radio                             | 1        | 2.63%   |
| Micro Star International Bluetooth Dongle           | 1        | 2.63%   |
| Micro Star International Bluetooth Device           | 1        | 2.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.63%   |
| Intel Bluetooth wireless interface                  | 1        | 2.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 2.63%   |
| Intel AX210 Bluetooth                               | 1        | 2.63%   |
| Intel AX201 Bluetooth                               | 1        | 2.63%   |
| ASUS ASUS USB-BT500                                 | 1        | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 48       | 32.65%  |
| Intel                    | 43       | 29.25%  |
| Nvidia                   | 29       | 19.73%  |
| Creative Labs            | 9        | 6.12%   |
| Micro Star International | 3        | 2.04%   |
| Texas Instruments        | 2        | 1.36%   |
| Kingston Technology      | 2        | 1.36%   |
| C-Media Electronics      | 2        | 1.36%   |
| VIA Technologies         | 1        | 0.68%   |
| RME                      | 1        | 0.68%   |
| M-Audio                  | 1        | 0.68%   |
| Loongson Technology      | 1        | 0.68%   |
| Holtek Semiconductor     | 1        | 0.68%   |
| EGO SYStems              | 1        | 0.68%   |
| DSEA A/S                 | 1        | 0.68%   |
| Corsair                  | 1        | 0.68%   |
| ASUSTek Computer         | 1        | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 18       | 9.57%   |
| AMD Ryzen HD Audio Controller                                                                   | 9        | 4.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 7        | 3.72%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                  | 6        | 3.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 5        | 2.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 5        | 2.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 5        | 2.66%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 5        | 2.66%   |
| Nvidia MCP61 High Definition Audio                                                              | 4        | 2.13%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 4        | 2.13%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 4        | 2.13%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 4        | 2.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 4        | 2.13%   |
| AMD Navi 31 HDMI/DP Audio                                                                       | 4        | 2.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 4        | 2.13%   |
| AMD FCH Azalia Controller                                                                       | 4        | 2.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 4        | 2.13%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 3        | 1.6%    |
| Nvidia GF108 High Definition Audio Controller                                                   | 3        | 1.6%    |
| Micro Star International USB Audio                                                              | 3        | 1.6%    |
| Intel Cannon Lake PCH cAVS                                                                      | 3        | 1.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 3        | 1.6%    |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 3        | 1.6%    |
| AMD Radeon High Definition Audio Controller                                                     | 3        | 1.6%    |
| AMD Navi 10 HDMI Audio                                                                          | 3        | 1.6%    |
| Nvidia GP104 High Definition Audio Controller                                                   | 2        | 1.06%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 2        | 1.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 2        | 1.06%   |
| Nvidia GK104 HDMI Audio Controller                                                              | 2        | 1.06%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 2        | 1.06%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 2        | 1.06%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 2        | 1.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2        | 1.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 2        | 1.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 2        | 1.06%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                                               | 2        | 1.06%   |
| C-Media Electronics USB Audio Device                                                            | 2        | 1.06%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                     | 2        | 1.06%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                     | 1        | 0.53%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 1        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 20       | 18.87%  |
| Corsair             | 17       | 16.04%  |
| Unknown             | 10       | 9.43%   |
| Samsung Electronics | 9        | 8.49%   |
| SK hynix            | 8        | 7.55%   |
| Crucial             | 8        | 7.55%   |
| G.Skill             | 7        | 6.6%    |
| Team                | 4        | 3.77%   |
| Micron Technology   | 4        | 3.77%   |
| Transcend           | 2        | 1.89%   |
| Silicon Power       | 2        | 1.89%   |
| AMD                 | 2        | 1.89%   |
| A-DATA Technology   | 2        | 1.89%   |
| Unknown             | 2        | 1.89%   |
| Strontium           | 1        | 0.94%   |
| Smart               | 1        | 0.94%   |
| Patriot             | 1        | 0.94%   |
| HPE                 | 1        | 0.94%   |
| Hewlett-Packard     | 1        | 0.94%   |
| GOODRAM             | 1        | 0.94%   |
| GLOWAY              | 1        | 0.94%   |
| CXMT                | 1        | 0.94%   |
| A Force             | 1        | 0.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 2        | 1.68%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 2        | 1.68%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s        | 2        | 1.68%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 2133MT/s       | 2        | 1.68%   |
| Corsair RAM CMZ32GX3M4X1600C10 8GB DIMM DDR3 1600MT/s     | 2        | 1.68%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s    | 2        | 1.68%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 2        | 1.68%   |
| Unknown                                                   | 2        | 1.68%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                 | 1        | 0.84%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                  | 1        | 0.84%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s             | 1        | 0.84%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                  | 1        | 0.84%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                  | 1        | 0.84%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                | 1        | 0.84%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                    | 1        | 0.84%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                | 1        | 0.84%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                    | 1        | 0.84%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s         | 1        | 0.84%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s     | 1        | 0.84%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 4000MT/s       | 1        | 0.84%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s       | 1        | 0.84%   |
| Strontium RAM SRT4G86U1-P9H 4GB DIMM DDR3 1333MT/s        | 1        | 0.84%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s       | 1        | 0.84%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1GB FB-DIMM DDR2 667MT/s  | 1        | 0.84%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1        | 0.84%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s      | 1        | 0.84%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 0.84%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 0.84%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s      | 1        | 0.84%   |
| SK hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s      | 1        | 0.84%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s   | 1        | 0.84%   |
| Silicon Power RAM Module 16GB DIMM DDR4 3600MT/s          | 1        | 0.84%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s | 1        | 0.84%   |
| Samsung RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 0.84%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1        | 0.84%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s | 1        | 0.84%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 0.84%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s      | 1        | 0.84%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s       | 1        | 0.84%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s       | 1        | 0.84%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 47       | 52.22%  |
| DDR3    | 32       | 35.56%  |
| DDR2    | 4        | 4.44%   |
| SDRAM   | 2        | 2.22%   |
| DDR5    | 2        | 2.22%   |
| DDR     | 2        | 2.22%   |
| Unknown | 1        | 1.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 85       | 93.41%  |
| SODIMM  | 4        | 4.4%    |
| RIMM    | 1        | 1.1%    |
| FB-DIMM | 1        | 1.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 40       | 39.6%   |
| 16384 | 22       | 21.78%  |
| 4096  | 20       | 19.8%   |
| 2048  | 8        | 7.92%   |
| 32768 | 7        | 6.93%   |
| 1024  | 4        | 3.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 17       | 16.35%  |
| 3600    | 11       | 10.58%  |
| 3200    | 11       | 10.58%  |
| 2400    | 8        | 7.69%   |
| 1333    | 8        | 7.69%   |
| 2133    | 7        | 6.73%   |
| 3800    | 5        | 4.81%   |
| 667     | 4        | 3.85%   |
| 2800    | 3        | 2.88%   |
| 2667    | 3        | 2.88%   |
| 2666    | 3        | 2.88%   |
| 4000    | 2        | 1.92%   |
| 3000    | 2        | 1.92%   |
| 2000    | 2        | 1.92%   |
| 1866    | 2        | 1.92%   |
| Unknown | 2        | 1.92%   |
| 65535   | 1        | 0.96%   |
| 6000    | 1        | 0.96%   |
| 4800    | 1        | 0.96%   |
| 3733    | 1        | 0.96%   |
| 3666    | 1        | 0.96%   |
| 3400    | 1        | 0.96%   |
| 2933    | 1        | 0.96%   |
| 2733    | 1        | 0.96%   |
| 2200    | 1        | 0.96%   |
| 1867    | 1        | 0.96%   |
| 1066    | 1        | 0.96%   |
| 975     | 1        | 0.96%   |
| 800     | 1        | 0.96%   |
| 533     | 1        | 0.96%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 36.36%  |
| Brother Industries  | 3        | 27.27%  |
| QinHeng Electronics | 1        | 9.09%   |
| Prolific Technology | 1        | 9.09%   |
| Dell                | 1        | 9.09%   |
| Canon               | 1        | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| QinHeng CH340S                | 1        | 9.09%   |
| Prolific PL2305 Parallel Port | 1        | 9.09%   |
| HP OfficeJet Pro 9010 series  | 1        | 9.09%   |
| HP LaserJet P1006             | 1        | 9.09%   |
| HP ENVY 4520 series           | 1        | 9.09%   |
| HP ENVY 4500 series           | 1        | 9.09%   |
| Dell 2330d Laser Printer      | 1        | 9.09%   |
| Canon LiDE 300                | 1        | 9.09%   |
| Brother Printer               | 1        | 9.09%   |
| Brother HL-L5102DW            | 1        | 9.09%   |
| Brother HL-L2320D series      | 1        | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 2        | 50%     |
| Seiko Epson     | 1        | 25%     |
| Hewlett-Packard | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 25%     |
| HP ScanJet 5590                               | 1        | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20            | 1        | 25%     |
| Canon CanoScan LIDE 25                        | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 12       | 66.67%  |
| Sunplus Innovation Technology | 2        | 11.11%  |
| Z-Star Microelectronics       | 1        | 5.56%   |
| Samsung Electronics           | 1        | 5.56%   |
| Microsoft                     | 1        | 5.56%   |
| Microdia                      | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 3        | 16.67%  |
| Z-Star Vimicro USB2.0 Camera            | 1        | 5.56%   |
| Sunplus Integrated Camera               | 1        | 5.56%   |
| Sunplus Full HD webcam                  | 1        | 5.56%   |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 5.56%   |
| Microsoft LifeCam HD-3000               | 1        | 5.56%   |
| Microdia Camera                         | 1        | 5.56%   |
| Logitech Webcam C310                    | 1        | 5.56%   |
| Logitech Webcam C300                    | 1        | 5.56%   |
| Logitech Webcam C170                    | 1        | 5.56%   |
| Logitech QuickCam Pro 9000              | 1        | 5.56%   |
| Logitech Logitech Webcam C160           | 1        | 5.56%   |
| Logitech HD Webcam C910                 | 1        | 5.56%   |
| Logitech HD Webcam C525                 | 1        | 5.56%   |
| Logitech HD Pro Webcam C920             | 1        | 5.56%   |
| Logitech C922 Pro Stream Webcam         | 1        | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| STMicroelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 61       | 61.62%  |
| 1     | 20       | 20.2%   |
| 2     | 9        | 9.09%   |
| 4     | 5        | 5.05%   |
| 3     | 3        | 3.03%   |
| 5     | 1        | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 17       | 26.98%  |
| Graphics card            | 14       | 22.22%  |
| Net/wireless             | 8        | 12.7%   |
| Communication controller | 7        | 11.11%  |
| Unassigned class         | 5        | 7.94%   |
| Bluetooth                | 3        | 4.76%   |
| Camera                   | 2        | 3.17%   |
| Storage/raid             | 1        | 1.59%   |
| Storage/ide              | 1        | 1.59%   |
| Storage/ata              | 1        | 1.59%   |
| Net/ethernet             | 1        | 1.59%   |
| Fingerprint reader       | 1        | 1.59%   |
| Chipcard                 | 1        | 1.59%   |
| Card reader              | 1        | 1.59%   |

