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

Total: 95

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Slackware 15.0  | 44       | 55.7%   |
| Slackware 14.2  | 32       | 40.51%  |
| Slackware 14.2+ | 2        | 2.53%   |
| Slackware 14.1  | 1        | 1.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Slackware | 77       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Desktops | Percent |
|----------------|----------|---------|
| 5.15.19        | 6        | 7.14%   |
| 5.15.63        | 5        | 5.95%   |
| 5.10.28-Unraid | 5        | 5.95%   |
| 5.19.17-Unraid | 4        | 4.76%   |
| 5.19.17        | 4        | 4.76%   |
| 4.19.80        | 4        | 4.76%   |
| 5.15.94        | 3        | 3.57%   |
| 4.4.190        | 3        | 3.57%   |
| 5.15.30-Unraid | 2        | 2.38%   |
| 5.15.27        | 2        | 2.38%   |
| 4.4.240        | 2        | 2.38%   |
| 6.6.7          | 1        | 1.19%   |
| 6.6.11         | 1        | 1.19%   |
| 6.1.61         | 1        | 1.19%   |
| 6.1.20         | 1        | 1.19%   |
| 6.1.13         | 1        | 1.19%   |
| 5.4.77         | 1        | 1.19%   |
| 5.4.53-APRL    | 1        | 1.19%   |
| 5.4.43         | 1        | 1.19%   |
| 5.4.0-rc2-vto  | 1        | 1.19%   |
| 5.19.16        | 1        | 1.19%   |
| 5.17.2         | 1        | 1.19%   |
| 5.17.0-custom  | 1        | 1.19%   |
| 5.16.18        | 1        | 1.19%   |
| 5.16.13        | 1        | 1.19%   |
| 5.16.11        | 1        | 1.19%   |
| 5.15.6         | 1        | 1.19%   |
| 5.15.50-cwl    | 1        | 1.19%   |
| 5.15.38        | 1        | 1.19%   |
| 5.15.14        | 1        | 1.19%   |
| 5.15.13        | 1        | 1.19%   |
| 5.15.118       | 1        | 1.19%   |
| 5.15.117       | 1        | 1.19%   |
| 5.15.103       | 1        | 1.19%   |
| 5.14.15-Unraid | 1        | 1.19%   |
| 5.14.15        | 1        | 1.19%   |
| 5.14.12        | 1        | 1.19%   |
| 5.14.11        | 1        | 1.19%   |
| 5.13.9-jw      | 1        | 1.19%   |
| 5.13.12        | 1        | 1.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.19.17  | 8        | 9.52%   |
| 5.15.19  | 6        | 7.14%   |
| 5.15.63  | 5        | 5.95%   |
| 5.10.28  | 5        | 5.95%   |
| 4.19.80  | 4        | 4.76%   |
| 5.15.94  | 3        | 3.57%   |
| 4.4.190  | 3        | 3.57%   |
| 5.15.30  | 2        | 2.38%   |
| 5.15.27  | 2        | 2.38%   |
| 5.14.15  | 2        | 2.38%   |
| 4.4.240  | 2        | 2.38%   |
| 6.6.7    | 1        | 1.19%   |
| 6.6.11   | 1        | 1.19%   |
| 6.1.61   | 1        | 1.19%   |
| 6.1.20   | 1        | 1.19%   |
| 6.1.13   | 1        | 1.19%   |
| 5.4.77   | 1        | 1.19%   |
| 5.4.53   | 1        | 1.19%   |
| 5.4.43   | 1        | 1.19%   |
| 5.4.0    | 1        | 1.19%   |
| 5.19.16  | 1        | 1.19%   |
| 5.17.2   | 1        | 1.19%   |
| 5.17.0   | 1        | 1.19%   |
| 5.16.18  | 1        | 1.19%   |
| 5.16.13  | 1        | 1.19%   |
| 5.16.11  | 1        | 1.19%   |
| 5.15.6   | 1        | 1.19%   |
| 5.15.50  | 1        | 1.19%   |
| 5.15.38  | 1        | 1.19%   |
| 5.15.14  | 1        | 1.19%   |
| 5.15.13  | 1        | 1.19%   |
| 5.15.118 | 1        | 1.19%   |
| 5.15.117 | 1        | 1.19%   |
| 5.15.103 | 1        | 1.19%   |
| 5.14.12  | 1        | 1.19%   |
| 5.14.11  | 1        | 1.19%   |
| 5.13.9   | 1        | 1.19%   |
| 5.13.12  | 1        | 1.19%   |
| 5.12.12  | 1        | 1.19%   |
| 5.10.44  | 1        | 1.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 26       | 31.33%  |
| 5.19    | 9        | 10.84%  |
| 5.10    | 8        | 9.64%   |
| 4.4     | 8        | 9.64%   |
| 4.19    | 8        | 9.64%   |
| 5.4     | 4        | 4.82%   |
| 5.14    | 4        | 4.82%   |
| 5.16    | 3        | 3.61%   |
| 6.6     | 2        | 2.41%   |
| 6.1     | 2        | 2.41%   |
| 5.17    | 2        | 2.41%   |
| 5.13    | 2        | 2.41%   |
| 4.9     | 2        | 2.41%   |
| 5.12    | 1        | 1.2%    |
| 4.20    | 1        | 1.2%    |
| 3.10    | 1        | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 77       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 39.74%  |
| XFCE       | 21       | 26.92%  |
| KDE5       | 19       | 24.36%  |
| FVWM       | 2        | 2.56%   |
| X-Generic  | 1        | 1.28%   |
| X-Cinnamon | 1        | 1.28%   |
| MATE       | 1        | 1.28%   |
| KDE        | 1        | 1.28%   |
| DWM        | 1        | 1.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 47       | 59.49%  |
| Tty     | 15       | 18.99%  |
| Unknown | 13       | 16.46%  |
| Wayland | 4        | 5.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 34       | 43.04%  |
| SDDM    | 20       | 25.32%  |
| XDM     | 18       | 22.78%  |
| LightDM | 4        | 5.06%   |
| SLiM    | 3        | 3.8%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 35       | 45.45%  |
| Unknown     | 25       | 32.47%  |
| it_IT       | 3        | 3.9%    |
| en_GB       | 3        | 3.9%    |
| ru_RU       | 2        | 2.6%    |
| us          | 1        | 1.3%    |
| sr_RS@latin | 1        | 1.3%    |
| pt_PT       | 1        | 1.3%    |
| pt_BR       | 1        | 1.3%    |
| es_ES.UTF8  | 1        | 1.3%    |
| es_ES       | 1        | 1.3%    |
| en_US.ASCII | 1        | 1.3%    |
| en_AU       | 1        | 1.3%    |
| C           | 1        | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 45       | 58.44%  |
| EFI  | 32       | 41.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 49       | 63.64%  |
| Btrfs    | 11       | 14.29%  |
| Xfs      | 5        | 6.49%   |
| Rootfs   | 5        | 6.49%   |
| Overlay  | 2        | 2.6%    |
| Tmpfs    | 1        | 1.3%    |
| Reiserfs | 1        | 1.3%    |
| F2fs     | 1        | 1.3%    |
| Ext3     | 1        | 1.3%    |
| Ext2     | 1        | 1.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 51       | 64.56%  |
| MBR     | 20       | 25.32%  |
| Unknown | 8        | 10.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 52.56%  |
| Yes       | 37       | 47.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 71.43%  |
| Yes       | 22       | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21       | 27.27%  |
| MSI                 | 11       | 14.29%  |
| ASRock              | 11       | 14.29%  |
| Hewlett-Packard     | 8        | 10.39%  |
| Gigabyte Technology | 8        | 10.39%  |
| Dell                | 5        | 6.49%   |
| Supermicro          | 1        | 1.3%    |
| Shuttle             | 1        | 1.3%    |
| NetGear             | 1        | 1.3%    |
| Lenovo              | 1        | 1.3%    |
| Intel               | 1        | 1.3%    |
| Huanan              | 1        | 1.3%    |
| HPE                 | 1        | 1.3%    |
| HEDYCOMPUTER        | 1        | 1.3%    |
| Fujitsu             | 1        | 1.3%    |
| Foxconn             | 1        | 1.3%    |
| Biostar             | 1        | 1.3%    |
| Acer                | 1        | 1.3%    |
| Unknown             | 1        | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS All Series                      | 4        | 5.19%   |
| MSI MS-7D76                          | 2        | 2.6%    |
| ASRock N68-S3 FX                     | 2        | 2.6%    |
| Supermicro X9DA7/E                   | 1        | 1.3%    |
| Shuttle NC03U                        | 1        | 1.3%    |
| NetGear ReadyDATA 5200               | 1        | 1.3%    |
| MSI MS-7C52                          | 1        | 1.3%    |
| MSI MS-7C02                          | 1        | 1.3%    |
| MSI MS-7B79                          | 1        | 1.3%    |
| MSI MS-7996                          | 1        | 1.3%    |
| MSI MS-7885                          | 1        | 1.3%    |
| MSI MS-7788                          | 1        | 1.3%    |
| MSI MS-7693                          | 1        | 1.3%    |
| MSI MS-7529                          | 1        | 1.3%    |
| MSI MS-7365                          | 1        | 1.3%    |
| Lenovo H50-05 90BH001WIX             | 1        | 1.3%    |
| Intel DZ77RE-75K AAG39010-302        | 1        | 1.3%    |
| Huanan X79-8D VAA31                  | 1        | 1.3%    |
| HPE ProLiant MicroServer Gen10 Plus  | 1        | 1.3%    |
| HP Z620 Workstation                  | 1        | 1.3%    |
| HP Z440 Workstation                  | 1        | 1.3%    |
| HP xw8400 Workstation                | 1        | 1.3%    |
| HP t620 Quad Core TC                 | 1        | 1.3%    |
| HP ProLiant ML110 Gen9               | 1        | 1.3%    |
| HP Pavilion Gaming Desktop TG01-2xxx | 1        | 1.3%    |
| HP Compaq dc7900 Small Form Factor   | 1        | 1.3%    |
| HP 500-515na                         | 1        | 1.3%    |
| HEDYCOMPUTER IH81MF-Q3               | 1        | 1.3%    |
| Gigabyte Z97M-DS3H                   | 1        | 1.3%    |
| Gigabyte X570 AORUS MASTER           | 1        | 1.3%    |
| Gigabyte X150M-PRO ECC               | 1        | 1.3%    |
| Gigabyte N3160TN                     | 1        | 1.3%    |
| Gigabyte M61SME-S2                   | 1        | 1.3%    |
| Gigabyte B550 AORUS ELITE AX V2      | 1        | 1.3%    |
| Gigabyte AB350-Gaming 3              | 1        | 1.3%    |
| Gigabyte 970A-DS3P                   | 1        | 1.3%    |
| Fujitsu FujitsuTP7000                | 1        | 1.3%    |
| Foxconn p6-2390                      | 1        | 1.3%    |
| Dell Precision WorkStation T3400     | 1        | 1.3%    |
| Dell Precision WorkStation 690       | 1        | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 6        | 7.79%   |
| ASUS All               | 4        | 5.19%   |
| Dell Precision         | 3        | 3.9%    |
| ASUS ROG               | 3        | 3.9%    |
| MSI MS-7D76            | 2        | 2.6%    |
| Dell OptiPlex          | 2        | 2.6%    |
| ASUS TUF               | 2        | 2.6%    |
| ASRock N68-S3          | 2        | 2.6%    |
| Supermicro X9DA7       | 1        | 1.3%    |
| Shuttle NC03U          | 1        | 1.3%    |
| NetGear ReadyDATA      | 1        | 1.3%    |
| MSI MS-7C52            | 1        | 1.3%    |
| MSI MS-7C02            | 1        | 1.3%    |
| MSI MS-7B79            | 1        | 1.3%    |
| MSI MS-7996            | 1        | 1.3%    |
| MSI MS-7885            | 1        | 1.3%    |
| MSI MS-7788            | 1        | 1.3%    |
| MSI MS-7693            | 1        | 1.3%    |
| MSI MS-7529            | 1        | 1.3%    |
| MSI MS-7365            | 1        | 1.3%    |
| Lenovo H50-05          | 1        | 1.3%    |
| Intel DZ77RE-75K       | 1        | 1.3%    |
| Huanan X79-8D          | 1        | 1.3%    |
| HPE ProLiant           | 1        | 1.3%    |
| HP Z620                | 1        | 1.3%    |
| HP Z440                | 1        | 1.3%    |
| HP xw8400              | 1        | 1.3%    |
| HP t620                | 1        | 1.3%    |
| HP ProLiant            | 1        | 1.3%    |
| HP Pavilion            | 1        | 1.3%    |
| HP Compaq              | 1        | 1.3%    |
| HP 500-515na           | 1        | 1.3%    |
| HEDYCOMPUTER IH81MF-Q3 | 1        | 1.3%    |
| Gigabyte Z97M-DS3H     | 1        | 1.3%    |
| Gigabyte X570          | 1        | 1.3%    |
| Gigabyte X150M-PRO     | 1        | 1.3%    |
| Gigabyte N3160TN       | 1        | 1.3%    |
| Gigabyte M61SME-S2     | 1        | 1.3%    |
| Gigabyte B550          | 1        | 1.3%    |
| Gigabyte AB350-Gaming  | 1        | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 11       | 14.29%  |
| 2015 | 8        | 10.39%  |
| 2018 | 7        | 9.09%   |
| 2017 | 7        | 9.09%   |
| 2014 | 6        | 7.79%   |
| 2012 | 6        | 7.79%   |
| 2011 | 6        | 7.79%   |
| 2020 | 5        | 6.49%   |
| 2022 | 4        | 5.19%   |
| 2008 | 4        | 5.19%   |
| 2016 | 3        | 3.9%    |
| 2009 | 3        | 3.9%    |
| 2013 | 2        | 2.6%    |
| 2010 | 2        | 2.6%    |
| 2007 | 2        | 2.6%    |
| 2021 | 1        | 1.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 77       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 77       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 20       | 25.64%  |
| 32.01-64.0  | 14       | 17.95%  |
| 8.01-16.0   | 12       | 15.38%  |
| 4.01-8.0    | 8        | 10.26%  |
| 64.01-256.0 | 8        | 10.26%  |
| 3.01-4.0    | 7        | 8.97%   |
| 24.01-32.0  | 6        | 7.69%   |
| 1.01-2.0    | 3        | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 20       | 24.69%  |
| 1.01-2.0    | 20       | 24.69%  |
| 2.01-3.0    | 15       | 18.52%  |
| 3.01-4.0    | 8        | 9.88%   |
| 8.01-16.0   | 4        | 4.94%   |
| 0.51-1.0    | 4        | 4.94%   |
| 16.01-24.0  | 3        | 3.7%    |
| 24.01-32.0  | 2        | 2.47%   |
| 0.01-0.5    | 2        | 2.47%   |
| 32.01-64.0  | 1        | 1.23%   |
| 64.01-256.0 | 1        | 1.23%   |
| Unknown     | 1        | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 26.25%  |
| 2      | 17       | 21.25%  |
| 3      | 15       | 18.75%  |
| 4      | 7        | 8.75%   |
| 6      | 6        | 7.5%    |
| 5      | 5        | 6.25%   |
| 0      | 2        | 2.5%    |
| 14     | 1        | 1.25%   |
| 13     | 1        | 1.25%   |
| 11     | 1        | 1.25%   |
| 10     | 1        | 1.25%   |
| 9      | 1        | 1.25%   |
| 8      | 1        | 1.25%   |
| 7      | 1        | 1.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 39       | 50%     |
| No        | 39       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 76       | 98.7%   |
| No        | 1        | 1.3%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 62.34%  |
| Yes       | 29       | 37.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 62.34%  |
| Yes       | 29       | 37.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 16       | 20.78%  |
| UK           | 11       | 14.29%  |
| Italy        | 6        | 7.79%   |
| Germany      | 5        | 6.49%   |
| Brazil       | 5        | 6.49%   |
| Russia       | 4        | 5.19%   |
| Japan        | 4        | 5.19%   |
| Spain        | 3        | 3.9%    |
| Kazakhstan   | 3        | 3.9%    |
| Hong Kong    | 3        | 3.9%    |
| Canada       | 3        | 3.9%    |
| Sweden       | 2        | 2.6%    |
| Portugal     | 2        | 2.6%    |
| France       | 2        | 2.6%    |
| Australia    | 2        | 2.6%    |
| South Africa | 1        | 1.3%    |
| Serbia       | 1        | 1.3%    |
| Poland       | 1        | 1.3%    |
| China        | 1        | 1.3%    |
| Bulgaria     | 1        | 1.3%    |
| Argentina    | 1        | 1.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Yekaterinburg     | 3        | 3.8%    |
| Ust-Kamenogorsk   | 2        | 2.53%   |
| Tokyo             | 2        | 2.53%   |
| Springfield       | 2        | 2.53%   |
| Rome              | 2        | 2.53%   |
| Paris             | 2        | 2.53%   |
| Milan             | 2        | 2.53%   |
| Lisbon            | 2        | 2.53%   |
| Winter Springs    | 1        | 1.27%   |
| Weilheim          | 1        | 1.27%   |
| Warsaw            | 1        | 1.27%   |
| Tsukuba           | 1        | 1.27%   |
| Toronto           | 1        | 1.27%   |
| Tiffin            | 1        | 1.27%   |
| Tendo             | 1        | 1.27%   |
| Tatuí            | 1        | 1.27%   |
| Stockholm         | 1        | 1.27%   |
| St Petersburg     | 1        | 1.27%   |
| Southend-on-Sea   | 1        | 1.27%   |
| Shrewsbury        | 1        | 1.27%   |
| Sham Shui Po      | 1        | 1.27%   |
| Seville           | 1        | 1.27%   |
| Senhora da Hora   | 1        | 1.27%   |
| Santa Cruz do Sul | 1        | 1.27%   |
| Saint Paul        | 1        | 1.27%   |
| Rock              | 1        | 1.27%   |
| Rio do Sul        | 1        | 1.27%   |
| Porto Alegre      | 1        | 1.27%   |
| Plovdiv           | 1        | 1.27%   |
| Penrith           | 1        | 1.27%   |
| Palma             | 1        | 1.27%   |
| Ottawa            | 1        | 1.27%   |
| Oldham            | 1        | 1.27%   |
| Naples            | 1        | 1.27%   |
| Nanping           | 1        | 1.27%   |
| Moscow            | 1        | 1.27%   |
| Milwaukee         | 1        | 1.27%   |
| Mead              | 1        | 1.27%   |
| McKinney          | 1        | 1.27%   |
| Mason             | 1        | 1.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 33       | 84     | 21.02%  |
| Seagate               | 31       | 61     | 19.75%  |
| Samsung Electronics   | 25       | 38     | 15.92%  |
| Toshiba               | 13       | 30     | 8.28%   |
| Kingston              | 8        | 11     | 5.1%    |
| Hitachi               | 8        | 11     | 5.1%    |
| Crucial               | 5        | 6      | 3.18%   |
| Intel                 | 3        | 4      | 1.91%   |
| Hewlett-Packard       | 3        | 3      | 1.91%   |
| A-DATA Technology     | 3        | 3      | 1.91%   |
| Transcend             | 2        | 2      | 1.27%   |
| SK hynix              | 2        | 2      | 1.27%   |
| Maxtor                | 2        | 2      | 1.27%   |
| HGST                  | 2        | 2      | 1.27%   |
| China                 | 2        | 3      | 1.27%   |
| ZHITAI                | 1        | 2      | 0.64%   |
| Team                  | 1        | 1      | 0.64%   |
| Silicon Motion        | 1        | 2      | 0.64%   |
| SanDisk               | 1        | 1      | 0.64%   |
| Realtek Semiconductor | 1        | 1      | 0.64%   |
| PNY                   | 1        | 1      | 0.64%   |
| Phison Electronics    | 1        | 1      | 0.64%   |
| Patriot               | 1        | 1      | 0.64%   |
| Lexar                 | 1        | 1      | 0.64%   |
| KIOXIA                | 1        | 1      | 0.64%   |
| Intenso               | 1        | 1      | 0.64%   |
| Gigabyte Technology   | 1        | 1      | 0.64%   |
| Fujitsu               | 1        | 1      | 0.64%   |
| DUEX                  | 1        | 1      | 0.64%   |
| Apple                 | 1        | 2      | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4        | 1.89%   |
| WDC WD20EFRX-68EUZN0 2TB                          | 3        | 1.42%   |
| WDC WD1003FZEX-00MK2A0 1TB                        | 3        | 1.42%   |
| Seagate ST4000DM004-2CV104 4TB                    | 3        | 1.42%   |
| Seagate ST2000DM008-2FR102 2TB                    | 3        | 1.42%   |
| Samsung SSD 970 EVO 250GB                         | 3        | 1.42%   |
| WDC WD40EZRX-00SPEB0 4TB                          | 2        | 0.94%   |
| WDC WD30EZRX-00SPEB0 3TB                          | 2        | 0.94%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 2        | 0.94%   |
| WDC WD10EZEX-00RKKA0 1TB                          | 2        | 0.94%   |
| Toshiba MQ01ABD100 1TB                            | 2        | 0.94%   |
| Toshiba HDWD110 1TB                               | 2        | 0.94%   |
| Seagate ST500DM002-1BD142 500GB                   | 2        | 0.94%   |
| Seagate ST4000VN008-2DR166 4TB                    | 2        | 0.94%   |
| Seagate ST4000VN006-3CW104 4TB                    | 2        | 0.94%   |
| Seagate ST31000524AS 1TB                          | 2        | 0.94%   |
| Seagate ST2000DX001-1NS164 2TB                    | 2        | 0.94%   |
| Seagate ST2000DM001-1CH164 2TB                    | 2        | 0.94%   |
| Seagate ST2000DL003-9VT166 2TB                    | 2        | 0.94%   |
| Seagate ST1000DM010-2EP102 1TB                    | 2        | 0.94%   |
| Seagate ST1000DM003-1SB102 1TB                    | 2        | 0.94%   |
| Seagate ST1000DM003-1ER162 1TB                    | 2        | 0.94%   |
| Seagate Expansion Desk 8TB                        | 2        | 0.94%   |
| Samsung SSD 970 EVO Plus 1TB                      | 2        | 0.94%   |
| Samsung SSD 850 PRO 256GB                         | 2        | 0.94%   |
| Kingston SA400S37240G 240GB SSD                   | 2        | 0.94%   |
| Kingston SA400S37120G 120GB SSD                   | 2        | 0.94%   |
| Crucial CT500MX500SSD1 500GB                      | 2        | 0.94%   |
| ZHITAI SC001 Active 1TB SSD                       | 1        | 0.47%   |
| ZHITAI PC005 Active 512GB                         | 1        | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1        | 0.47%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                  | 1        | 0.47%   |
| WDC WDS100T2B0C-00PXH0 1TB                        | 1        | 0.47%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1        | 0.47%   |
| WDC WD80EFZX-68UW8N0 8TB                          | 1        | 0.47%   |
| WDC WD80EFBX-68AZZN0 8TB                          | 1        | 0.47%   |
| WDC WD80EFAX-68LHPN0 8TB                          | 1        | 0.47%   |
| WDC WD80EFAX-68KNBN0 8TB                          | 1        | 0.47%   |
| WDC WD8003FFBX-68B9AN0 8TB                        | 1        | 0.47%   |
| WDC WD6003FRYZ-01F0DB0 6TB                        | 1        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 32       | 80     | 34.04%  |
| Seagate             | 31       | 57     | 32.98%  |
| Toshiba             | 12       | 25     | 12.77%  |
| Hitachi             | 8        | 11     | 8.51%   |
| Samsung Electronics | 4        | 4      | 4.26%   |
| Maxtor              | 2        | 2      | 2.13%   |
| HGST                | 2        | 2      | 2.13%   |
| Hewlett-Packard     | 2        | 2      | 2.13%   |
| Fujitsu             | 1        | 1      | 1.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 18     | 25.58%  |
| Kingston            | 7        | 10     | 16.28%  |
| Crucial             | 4        | 5      | 9.3%    |
| WDC                 | 2        | 3      | 4.65%   |
| Transcend           | 2        | 2      | 4.65%   |
| Intel               | 2        | 3      | 4.65%   |
| China               | 2        | 3      | 4.65%   |
| ZHITAI              | 1        | 1      | 2.33%   |
| Toshiba             | 1        | 3      | 2.33%   |
| Team                | 1        | 1      | 2.33%   |
| SK hynix            | 1        | 1      | 2.33%   |
| SanDisk             | 1        | 1      | 2.33%   |
| PNY                 | 1        | 1      | 2.33%   |
| Patriot             | 1        | 1      | 2.33%   |
| Lexar               | 1        | 1      | 2.33%   |
| Intenso             | 1        | 1      | 2.33%   |
| Hewlett-Packard     | 1        | 1      | 2.33%   |
| DUEX                | 1        | 1      | 2.33%   |
| Apple               | 1        | 2      | 2.33%   |
| A-DATA Technology   | 1        | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 60       | 184    | 48.78%  |
| SSD     | 38       | 60     | 30.89%  |
| NVMe    | 24       | 32     | 19.51%  |
| Unknown | 1        | 4      | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 68       | 238    | 71.58%  |
| NVMe | 24       | 32     | 25.26%  |
| SAS  | 3        | 10     | 3.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 48       | 80     | 38.4%   |
| 0.51-1.0   | 28       | 64     | 22.4%   |
| 1.01-2.0   | 18       | 26     | 14.4%   |
| 3.01-4.0   | 12       | 27     | 9.6%    |
| 2.01-3.0   | 9        | 21     | 7.2%    |
| 4.01-10.0  | 8        | 21     | 6.4%    |
| 10.01-20.0 | 2        | 5      | 1.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 15       | 18.75%  |
| Unknown        | 14       | 17.5%   |
| 101-250        | 12       | 15%     |
| 1001-2000      | 10       | 12.5%   |
| 2001-3000      | 9        | 11.25%  |
| 251-500        | 7        | 8.75%   |
| More than 3000 | 5        | 6.25%   |
| 1-20           | 5        | 6.25%   |
| 51-100         | 2        | 2.5%    |
| 21-50          | 1        | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 17       | 21.25%  |
| Unknown        | 14       | 17.5%   |
| 501-1000       | 12       | 15%     |
| 1-20           | 10       | 12.5%   |
| 251-500        | 8        | 10%     |
| 1001-2000      | 6        | 7.5%    |
| 51-100         | 6        | 7.5%    |
| More than 3000 | 4        | 5%      |
| 21-50          | 3        | 3.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1        | 1      | 2.94%   |
| WDC WD5000BPKX-60HPJT0 500GB          | 1        | 1      | 2.94%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1        | 1      | 2.94%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 2.94%   |
| WDC WD5000AAKS-00A7B2 500GB           | 1        | 1      | 2.94%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1        | 2      | 2.94%   |
| WDC WD3200AAJS-65B4A0 320GB           | 1        | 1      | 2.94%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1        | 1      | 2.94%   |
| WDC WD30EZRX-00M                      | 1        | 1      | 2.94%   |
| WDC WD30EZRX-00D8PB0 3TB              | 1        | 1      | 2.94%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1        | 4      | 2.94%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 2.94%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 2.94%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1        | 1      | 2.94%   |
| WDC WD10EALS-00Z8A0 1TB               | 1        | 2      | 2.94%   |
| WDC WD1003FZEX-00MK2A0 1TB            | 1        | 2      | 2.94%   |
| Seagate ST380011A 80GB                | 1        | 2      | 2.94%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 2.94%   |
| Seagate ST3500410AS 500GB             | 1        | 1      | 2.94%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 2.94%   |
| Seagate ST3000VX006-1HH166 3TB        | 1        | 1      | 2.94%   |
| Seagate ST2000DL003-9VT166 2TB        | 1        | 1      | 2.94%   |
| Seagate ST1000VM002-1SD102 1TB        | 1        | 1      | 2.94%   |
| Seagate ST1000NM0011 1TB              | 1        | 2      | 2.94%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 2      | 2.94%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD    | 1        | 1      | 2.94%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 2.94%   |
| Maxtor 4G120J6 128GB                  | 1        | 1      | 2.94%   |
| Intel SSDSA2M080G2GC 80GB             | 1        | 1      | 2.94%   |
| Hitachi HUA723030ALA640 3TB           | 1        | 1      | 2.94%   |
| Hitachi HDS721050CLA660 500GB         | 1        | 1      | 2.94%   |
| Hitachi HDS721016CLA382 160GB         | 1        | 1      | 2.94%   |
| HGST HDN726040ALE614 4TB              | 1        | 1      | 2.94%   |
| DUEX DX300256A5xnEMLC 256GB SSD       | 1        | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 23     | 43.33%  |
| Seagate             | 8        | 12     | 26.67%  |
| Hitachi             | 3        | 3      | 10%     |
| SanDisk             | 1        | 1      | 3.33%   |
| Samsung Electronics | 1        | 1      | 3.33%   |
| Maxtor              | 1        | 1      | 3.33%   |
| Intel               | 1        | 1      | 3.33%   |
| HGST                | 1        | 1      | 3.33%   |
| DUEX                | 1        | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 12       | 22     | 48%     |
| Seagate | 8        | 12     | 32%     |
| Hitachi | 3        | 3      | 12%     |
| Maxtor  | 1        | 1      | 4%      |
| HGST    | 1        | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 22       | 39     | 81.48%  |
| SSD  | 4        | 4      | 14.81%  |
| NVMe | 1        | 1      | 3.7%    |

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
| Works    | 62       | 196    | 61.39%  |
| Malfunc  | 27       | 44     | 26.73%  |
| Detected | 12       | 40     | 11.88%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 40       | 31.5%   |
| AMD                          | 31       | 24.41%  |
| Samsung Electronics          | 15       | 11.81%  |
| Marvell Technology Group     | 7        | 5.51%   |
| ASMedia Technology           | 7        | 5.51%   |
| Nvidia                       | 5        | 3.94%   |
| JMicron Technology           | 4        | 3.15%   |
| Realtek Semiconductor        | 3        | 2.36%   |
| Broadcom / LSI               | 2        | 1.57%   |
| Yangtze Memory Technologies  | 1        | 0.79%   |
| Toshiba America Info Systems | 1        | 0.79%   |
| SK hynix                     | 1        | 0.79%   |
| Silicon Motion               | 1        | 0.79%   |
| Silicon Image                | 1        | 0.79%   |
| SanDisk                      | 1        | 0.79%   |
| Phison Electronics           | 1        | 0.79%   |
| Micron/Crucial Technology    | 1        | 0.79%   |
| LSI Logic / Symbios Logic    | 1        | 0.79%   |
| KIOXIA                       | 1        | 0.79%   |
| Kingston Technology Company  | 1        | 0.79%   |
| Adaptec                      | 1        | 0.79%   |
| 3ware                        | 1        | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 19       | 11.45%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 11       | 6.63%   |
| AMD 400 Series Chipset SATA Controller                                        | 11       | 6.63%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                     | 6        | 3.61%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                 | 5        | 3.01%   |
| Nvidia MCP61 SATA Controller                                                  | 4        | 2.41%   |
| Nvidia MCP61 IDE                                                              | 4        | 2.41%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 4        | 2.41%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 4        | 2.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 4        | 2.41%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 3        | 1.81%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                             | 2        | 1.2%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller              | 2        | 1.2%    |
| JMicron JMB58x AHCI SATA controller                                           | 2        | 1.2%    |
| Intel SATA Controller [RAID mode]                                             | 2        | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2        | 1.2%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 2        | 1.2%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                          | 2        | 1.2%    |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode] | 2        | 1.2%    |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode] | 2        | 1.2%    |
| Intel 631xESB/632xESB IDE Controller                                          | 2        | 1.2%    |
| Intel 4 Series Chipset PT IDER Controller                                     | 2        | 1.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2        | 1.2%    |
| AMD 600 Series Chipset SATA Controller                                        | 2        | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                        | 2        | 1.2%    |
| AMD 300 Series Chipset SATA Controller                                        | 2        | 1.2%    |
| Yangtze Memory ZHITAI PC005 NVMe SSD                                          | 1        | 0.6%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1        | 0.6%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 1        | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 1        | 0.6%    |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller              | 1        | 0.6%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                     | 1        | 0.6%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                    | 1        | 0.6%    |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                            | 1        | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1        | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1        | 0.6%    |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                             | 1        | 0.6%    |
| Phison E16 PCIe4 NVMe Controller                                              | 1        | 0.6%    |
| Nvidia MCP79 AHCI Controller                                                  | 1        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 62       | 52.54%  |
| NVMe | 24       | 20.34%  |
| IDE  | 19       | 16.1%   |
| RAID | 7        | 5.93%   |
| SAS  | 4        | 3.39%   |
| SCSI | 2        | 1.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 42       | 54.55%  |
| AMD    | 35       | 45.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 5.13%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 2        | 2.56%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 2.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 2.56%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 2.56%   |
| AMD Ryzen 9 7900 12-Core Processor          | 2        | 2.56%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 2.56%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2        | 2.56%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 2.56%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 2.56%   |
| AMD Athlon II X2 250 Processor              | 2        | 2.56%   |
| Intel Xeon CPU X5355 @ 2.66GHz              | 1        | 1.28%   |
| Intel Xeon CPU X3450 @ 2.67GHz              | 1        | 1.28%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz         | 1        | 1.28%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1        | 1.28%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 1.28%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 1        | 1.28%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1        | 1.28%   |
| Intel Xeon CPU E5-1603 v3 @ 2.80GHz         | 1        | 1.28%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1        | 1.28%   |
| Intel Xeon CPU 5160 @ 3.00GHz               | 1        | 1.28%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 1.28%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 1.28%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 1        | 1.28%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 1.28%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 1.28%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.28%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.28%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.28%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.28%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 1        | 1.28%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.28%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 1.28%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1        | 1.28%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.28%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.28%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.28%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 1.28%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.28%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 12       | 15.38%  |
| Intel Core i7      | 9        | 11.54%  |
| Intel Core i5      | 9        | 11.54%  |
| AMD Ryzen 5        | 9        | 11.54%  |
| AMD Ryzen 9        | 7        | 8.97%   |
| AMD Ryzen 7        | 5        | 6.41%   |
| AMD FX             | 5        | 6.41%   |
| Intel Pentium      | 3        | 3.85%   |
| Intel Core 2 Duo   | 3        | 3.85%   |
| Intel Core 2 Quad  | 2        | 2.56%   |
| AMD Athlon II X2   | 2        | 2.56%   |
| Intel Pentium Gold | 1        | 1.28%   |
| Intel Pentium Dual | 1        | 1.28%   |
| Intel Core i3      | 1        | 1.28%   |
| Intel Celeron      | 1        | 1.28%   |
| Intel Atom         | 1        | 1.28%   |
| AMD Ryzen 7 PRO    | 1        | 1.28%   |
| AMD Ryzen 3        | 1        | 1.28%   |
| AMD GX             | 1        | 1.28%   |
| AMD Athlon 64 X2   | 1        | 1.28%   |
| AMD A8             | 1        | 1.28%   |
| AMD A4             | 1        | 1.28%   |
| AMD A10            | 1        | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 29       | 37.18%  |
| 2      | 15       | 19.23%  |
| 6      | 11       | 14.1%   |
| 8      | 9        | 11.54%  |
| 16     | 5        | 6.41%   |
| 12     | 5        | 6.41%   |
| 14     | 1        | 1.28%   |
| 10     | 1        | 1.28%   |
| 3      | 1        | 1.28%   |
| 1      | 1        | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 72       | 93.51%  |
| 2      | 5        | 6.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 51       | 66.23%  |
| 1      | 26       | 33.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 77       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 23.38%  |
| 0x306c3    | 5        | 6.49%   |
| 0x206d7    | 4        | 5.19%   |
| 0x08701021 | 4        | 5.19%   |
| 0x306f2    | 3        | 3.9%    |
| 0x1067a    | 3        | 3.9%    |
| 0x08701013 | 3        | 3.9%    |
| 0x906ed    | 2        | 2.6%    |
| 0x906ea    | 2        | 2.6%    |
| 0x306a9    | 2        | 2.6%    |
| 0x0a50000c | 2        | 2.6%    |
| 0x0a201016 | 2        | 2.6%    |
| 0x08108109 | 2        | 2.6%    |
| 0x06001119 | 2        | 2.6%    |
| 0x06000822 | 2        | 2.6%    |
| 0xa0653    | 1        | 1.3%    |
| 0x906e9    | 1        | 1.3%    |
| 0x6fd      | 1        | 1.3%    |
| 0x6fb      | 1        | 1.3%    |
| 0x506e3    | 1        | 1.3%    |
| 0x406c4    | 1        | 1.3%    |
| 0x306e4    | 1        | 1.3%    |
| 0x206a7    | 1        | 1.3%    |
| 0x20655    | 1        | 1.3%    |
| 0x106e5    | 1        | 1.3%    |
| 0x106c2    | 1        | 1.3%    |
| 0x0a20120a | 1        | 1.3%    |
| 0x0810100b | 1        | 1.3%    |
| 0x0800820d | 1        | 1.3%    |
| 0x08001138 | 1        | 1.3%    |
| 0x08001126 | 1        | 1.3%    |
| 0x07030105 | 1        | 1.3%    |
| 0x07000110 | 1        | 1.3%    |
| 0x06000852 | 1        | 1.3%    |
| 0x010000b6 | 1        | 1.3%    |
| 0x00000000 | 1        | 1.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 11       | 14.29%  |
| Zen 2       | 9        | 11.69%  |
| SandyBridge | 7        | 9.09%   |
| KabyLake    | 7        | 9.09%   |
| Piledriver  | 6        | 7.79%   |
| Zen 3       | 5        | 6.49%   |
| Zen+        | 4        | 5.19%   |
| Penryn      | 4        | 5.19%   |
| Core        | 4        | 5.19%   |
| Zen         | 3        | 3.9%    |
| IvyBridge   | 3        | 3.9%    |
| K10         | 2        | 2.6%    |
| Unknown     | 2        | 2.6%    |
| Westmere    | 1        | 1.3%    |
| Skylake     | 1        | 1.3%    |
| Silvermont  | 1        | 1.3%    |
| Puma        | 1        | 1.3%    |
| Nehalem     | 1        | 1.3%    |
| K8 Hammer   | 1        | 1.3%    |
| Jaguar      | 1        | 1.3%    |
| CometLake   | 1        | 1.3%    |
| Bulldozer   | 1        | 1.3%    |
| Bonnell     | 1        | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 30       | 38.96%  |
| Nvidia                     | 29       | 37.66%  |
| Intel                      | 15       | 19.48%  |
| Matrox Electronics Systems | 3        | 3.9%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 7.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 4.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 3.66%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 3.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.44%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 2.44%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 2.44%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 2.44%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 2        | 2.44%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.44%   |
| AMD Raphael                                                                 | 2        | 2.44%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 2.44%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 2        | 2.44%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 2.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.44%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.22%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 1.22%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.22%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.22%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.22%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.22%   |
| Nvidia GK110GL [Quadro K5200]                                               | 1        | 1.22%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.22%   |
| Nvidia GK104GL [Quadro K5000]                                               | 1        | 1.22%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.22%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.22%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 1.22%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.22%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 1        | 1.22%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 1.22%   |
| Nvidia G80GL [Quadro FX 4600]                                               | 1        | 1.22%   |
| Nvidia G71GL [Quadro FX 1500]                                               | 1        | 1.22%   |
| Nvidia C79 [ION]                                                            | 1        | 1.22%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 1        | 1.22%   |
| Matrox Electronics Systems MGA G200eH3                                      | 1        | 1.22%   |
| Matrox Electronics Systems MGA G200EH                                       | 1        | 1.22%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 1.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 27       | 35.06%  |
| 1 x AMD        | 27       | 35.06%  |
| 1 x Intel      | 14       | 18.18%  |
| 2 x AMD        | 3        | 3.9%    |
| 1 x Matrox     | 3        | 3.9%    |
| Other          | 1        | 1.3%    |
| 2 x Nvidia     | 1        | 1.3%    |
| Intel + Nvidia | 1        | 1.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 50       | 64.94%  |
| Proprietary | 18       | 23.38%  |
| Unknown     | 9        | 11.69%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 40.26%  |
| 0.51-1.0   | 11       | 14.29%  |
| 3.01-4.0   | 8        | 10.39%  |
| 1.01-2.0   | 8        | 10.39%  |
| 7.01-8.0   | 6        | 7.79%   |
| 0.01-0.5   | 5        | 6.49%   |
| 8.01-16.0  | 4        | 5.19%   |
| 5.01-6.0   | 2        | 2.6%    |
| 2.01-3.0   | 1        | 1.3%    |
| 16.01-24.0 | 1        | 1.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 11       | 14.47%  |
| Dell                    | 10       | 13.16%  |
| Hewlett-Packard         | 8        | 10.53%  |
| Goldstar                | 8        | 10.53%  |
| BenQ                    | 8        | 10.53%  |
| Ancor Communications    | 4        | 5.26%   |
| Acer                    | 4        | 5.26%   |
| ViewSonic               | 2        | 2.63%   |
| Lenovo                  | 2        | 2.63%   |
| ASUSTek Computer        | 2        | 2.63%   |
| AOC                     | 2        | 2.63%   |
| Xiaomi                  | 1        | 1.32%   |
| Wacom                   | 1        | 1.32%   |
| Unknown                 | 1        | 1.32%   |
| Toshiba                 | 1        | 1.32%   |
| ONN                     | 1        | 1.32%   |
| NEC Computers           | 1        | 1.32%   |
| JVC                     | 1        | 1.32%   |
| IOD                     | 1        | 1.32%   |
| Iiyama                  | 1        | 1.32%   |
| Gigabyte Technology     | 1        | 1.32%   |
| GDH                     | 1        | 1.32%   |
| Eizo                    | 1        | 1.32%   |
| CTC                     | 1        | 1.32%   |
| Chi Mei Optoelectronics | 1        | 1.32%   |
| Unknown                 | 1        | 1.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 2        | 2.53%   |
| Goldstar HDR WQHD GSM7756 3440x1440 820x346mm 35.0-inch               | 2        | 2.53%   |
| Xiaomi Mi TV XMD009A 2880x1800 600x340mm 27.2-inch                    | 1        | 1.27%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1        | 1.27%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                         | 1        | 1.27%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                         | 1        | 1.27%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 1.27%   |
| Toshiba TV TSB0206 1920x1080                                          | 1        | 1.27%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch  | 1        | 1.27%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                      | 1        | 1.27%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1        | 1.27%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1        | 1.27%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1        | 1.27%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1        | 1.27%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1        | 1.27%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch     | 1        | 1.27%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 1.27%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                     | 1        | 1.27%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 950x540mm 43.0-inch | 1        | 1.27%   |
| Samsung Electronics B2430L SAM0644 1920x1080 521x293mm 23.5-inch      | 1        | 1.27%   |
| ONN ONA24HB19T01 ONN0101 1920x1080 520x320mm 24.0-inch                | 1        | 1.27%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch       | 1        | 1.27%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                 | 1        | 1.27%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1        | 1.27%   |
| JVC FPDEUFT3 JVC21BE 1920x540                                         | 1        | 1.27%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                  | 1        | 1.27%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch                | 1        | 1.27%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch         | 1        | 1.27%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1        | 1.27%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch          | 1        | 1.27%   |
| Hewlett-Packard V194bz HWP3136 1366x768 410x230mm 18.5-inch           | 1        | 1.27%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 410x230mm 18.5-inch          | 1        | 1.27%   |
| Hewlett-Packard 2309 HWP2823 1920x1080 510x287mm 23.0-inch            | 1        | 1.27%   |
| Goldstar W2242 GSM5678 1680x1050 490x320mm 23.0-inch                  | 1        | 1.27%   |
| Goldstar W2242 GSM5677 1680x1050 490x320mm 23.0-inch                  | 1        | 1.27%   |
| Goldstar W1952 GSM4B77 1440x900 408x255mm 18.9-inch                   | 1        | 1.27%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                | 1        | 1.27%   |
| Goldstar E2260 GSM57DF 1920x1080 480x270mm 21.7-inch                  | 1        | 1.27%   |
| Goldstar E1641 GSM8B3E 1366x768 344x194mm 15.5-inch                   | 1        | 1.27%   |
| Goldstar BK750Y GSM5B3E 1920x1080 600x340mm 27.2-inch                 | 1        | 1.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 33       | 44%     |
| 1280x1024 (SXGA)   | 7        | 9.33%   |
| 3840x2160 (4K)     | 5        | 6.67%   |
| 1680x1050 (WSXGA+) | 5        | 6.67%   |
| 1366x768 (WXGA)    | 5        | 6.67%   |
| 3440x1440          | 4        | 5.33%   |
| 2560x1440 (QHD)    | 4        | 5.33%   |
| 1920x1200 (WUXGA)  | 4        | 5.33%   |
| 1440x900 (WXGA+)   | 2        | 2.67%   |
| 3200x1080          | 1        | 1.33%   |
| 2288x1287          | 1        | 1.33%   |
| 1920x540           | 1        | 1.33%   |
| 1600x1200          | 1        | 1.33%   |
| 1024x768 (XGA)     | 1        | 1.33%   |
| Unknown            | 1        | 1.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 13       | 16.88%  |
| 27      | 12       | 15.58%  |
| 21      | 9        | 11.69%  |
| 23      | 7        | 9.09%   |
| Unknown | 7        | 9.09%   |
| 22      | 4        | 5.19%   |
| 19      | 4        | 5.19%   |
| 18      | 4        | 5.19%   |
| 17      | 4        | 5.19%   |
| 15      | 4        | 5.19%   |
| 35      | 2        | 2.6%    |
| 20      | 2        | 2.6%    |
| 142     | 1        | 1.3%    |
| 84      | 1        | 1.3%    |
| 74      | 1        | 1.3%    |
| 52      | 1        | 1.3%    |
| 34      | 1        | 1.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 30       | 39.47%  |
| 401-500        | 20       | 26.32%  |
| 301-350        | 8        | 10.53%  |
| Unknown        | 7        | 9.21%   |
| 351-400        | 3        | 3.95%   |
| 801-900        | 2        | 2.63%   |
| 1501-2000      | 2        | 2.63%   |
| More than 2000 | 1        | 1.32%   |
| 701-800        | 1        | 1.32%   |
| 601-700        | 1        | 1.32%   |
| 1001-1500      | 1        | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 39       | 54.93%  |
| 16/10   | 12       | 16.9%   |
| 5/4     | 5        | 7.04%   |
| Unknown | 5        | 7.04%   |
| 21/9    | 3        | 4.23%   |
| 6/5     | 2        | 2.82%   |
| 4/3     | 2        | 2.82%   |
| 32/9    | 1        | 1.41%   |
| 3/2     | 1        | 1.41%   |
| 1.00    | 1        | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 26       | 34.67%  |
| 301-350        | 12       | 16%     |
| 151-200        | 7        | 9.33%   |
| 141-150        | 7        | 9.33%   |
| Unknown        | 7        | 9.33%   |
| 251-300        | 5        | 6.67%   |
| More than 1000 | 4        | 5.33%   |
| 101-110        | 4        | 5.33%   |
| 351-500        | 3        | 4%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 45       | 58.44%  |
| 101-120 | 18       | 23.38%  |
| Unknown | 7        | 9.09%   |
| 121-160 | 4        | 5.19%   |
| 1-50    | 3        | 3.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 55       | 71.43%  |
| 0     | 10       | 12.99%  |
| 2     | 9        | 11.69%  |
| 3     | 3        | 3.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 43       | 40.19%  |
| Intel                    | 33       | 30.84%  |
| Qualcomm Atheros         | 5        | 4.67%   |
| Broadcom                 | 5        | 4.67%   |
| Nvidia                   | 4        | 3.74%   |
| TP-Link                  | 3        | 2.8%    |
| Ralink Technology        | 3        | 2.8%    |
| MediaTek                 | 3        | 2.8%    |
| VIA Technologies         | 1        | 0.93%   |
| Ralink                   | 1        | 0.93%   |
| Qualcomm                 | 1        | 0.93%   |
| Micro Star International | 1        | 0.93%   |
| Mellanox Technologies    | 1        | 0.93%   |
| Dell                     | 1        | 0.93%   |
| Chelsio Communications   | 1        | 0.93%   |
| Broadcom Limited         | 1        | 0.93%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 31       | 25.2%   |
| Intel I211 Gigabit Network Connection                                      | 7        | 5.69%   |
| Realtek RTL8125 2.5GbE Controller                                          | 4        | 3.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 4        | 3.25%   |
| Intel Ethernet Connection (2) I218-V                                       | 4        | 3.25%   |
| Intel 82574L Gigabit Network Connection                                    | 4        | 3.25%   |
| Ralink MT7601U Wireless Adapter                                            | 3        | 2.44%   |
| Nvidia MCP61 Ethernet                                                      | 3        | 2.44%   |
| Intel Wi-Fi 6 AX200                                                        | 3        | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 3        | 2.44%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 2        | 1.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 1.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter              | 2        | 1.63%   |
| Intel I350 Gigabit Network Connection                                      | 2        | 1.63%   |
| Intel Ethernet Controller I225-V                                           | 2        | 1.63%   |
| Intel Ethernet Connection (7) I219-V                                       | 2        | 1.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2        | 1.63%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 1.63%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 1.63%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                    | 2        | 1.63%   |
| VIA VT6105/VT6106S [Rhine-III]                                             | 1        | 0.81%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 1        | 0.81%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                      | 1        | 0.81%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1        | 0.81%   |
| Realtek USB 10/100/1G/2.5G LAN                                             | 1        | 0.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 1        | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.81%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1        | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.81%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1        | 0.81%   |
| Qualcomm Redmi 9T                                                          | 1        | 0.81%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 1        | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 0.81%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 0.81%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.81%   |
| Nvidia MCP79 Ethernet                                                      | 1        | 0.81%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 0.81%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                      | 1        | 0.81%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                    | 1        | 0.81%   |
| Intel Wireless 7260                                                        | 1        | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 9        | 31.03%  |
| Realtek Semiconductor    | 5        | 17.24%  |
| TP-Link                  | 3        | 10.34%  |
| Ralink Technology        | 3        | 10.34%  |
| Qualcomm Atheros         | 3        | 10.34%  |
| MediaTek                 | 3        | 10.34%  |
| Ralink                   | 1        | 3.45%   |
| Micro Star International | 1        | 3.45%   |
| Dell                     | 1        | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                            | 3        | 10.34%  |
| Intel Wi-Fi 6 AX200                                                        | 3        | 10.34%  |
| Realtek RTL8188EE Wireless Network Adapter                                 | 2        | 6.9%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter              | 2        | 6.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2        | 6.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 1        | 3.45%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                      | 1        | 3.45%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1        | 3.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 1        | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 3.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1        | 3.45%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1        | 3.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 1        | 3.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 3.45%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 3.45%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 3.45%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                    | 1        | 3.45%   |
| Intel Wireless 7260                                                        | 1        | 3.45%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                  | 1        | 3.45%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                    | 1        | 3.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 1        | 3.45%   |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887]      | 1        | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Realtek Semiconductor  | 41       | 46.59%  |
| Intel                  | 30       | 34.09%  |
| Broadcom               | 5        | 5.68%   |
| Nvidia                 | 4        | 4.55%   |
| Qualcomm Atheros       | 3        | 3.41%   |
| VIA Technologies       | 1        | 1.14%   |
| Qualcomm               | 1        | 1.14%   |
| Mellanox Technologies  | 1        | 1.14%   |
| Chelsio Communications | 1        | 1.14%   |
| Broadcom Limited       | 1        | 1.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 31       | 32.98%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 7.45%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4        | 4.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 4.26%   |
| Intel Ethernet Connection (2) I218-V                                          | 4        | 4.26%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 4.26%   |
| Nvidia MCP61 Ethernet                                                         | 3        | 3.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 3.19%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 2.13%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 2.13%   |
| Intel Ethernet Controller I225-V                                              | 2        | 2.13%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 2.13%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 2.13%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 2.13%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 2        | 2.13%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 1.06%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1        | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 1.06%   |
| Qualcomm Redmi 9T                                                             | 1        | 1.06%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 1.06%   |
| Nvidia MCP79 Ethernet                                                         | 1        | 1.06%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 1.06%   |
| Intel Ethernet Connection I217-V                                              | 1        | 1.06%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 1.06%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 1.06%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 1.06%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 1.06%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.06%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 1.06%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1        | 1.06%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 1.06%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                              | 1        | 1.06%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 1        | 1.06%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 1.06%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 76       | 72.38%  |
| WiFi     | 29       | 27.62%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 63       | 81.82%  |
| WiFi     | 14       | 18.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 46       | 58.23%  |
| 2     | 21       | 26.58%  |
| 3     | 6        | 7.59%   |
| 4     | 3        | 3.8%    |
| 5     | 2        | 2.53%   |
| 0     | 1        | 1.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 69       | 87.34%  |
| Yes  | 10       | 12.66%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Cambridge Silicon Radio  | 13       | 43.33%  |
| Intel                    | 8        | 26.67%  |
| MediaTek                 | 4        | 13.33%  |
| Micro Star International | 2        | 6.67%   |
| TP-Link                  | 1        | 3.33%   |
| Realtek Semiconductor    | 1        | 3.33%   |
| Broadcom                 | 1        | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13       | 43.33%  |
| MediaTek Wireless_Device                            | 4        | 13.33%  |
| Intel AX200 Bluetooth                               | 3        | 10%     |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 6.67%   |
| TP-Link UB500 Adapter                               | 1        | 3.33%   |
| Realtek Bluetooth Radio                             | 1        | 3.33%   |
| Micro Star International Bluetooth Dongle           | 1        | 3.33%   |
| Micro Star International Bluetooth Device           | 1        | 3.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.33%   |
| Intel Bluetooth wireless interface                  | 1        | 3.33%   |
| Intel AX210 Bluetooth                               | 1        | 3.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 37       | 32.74%  |
| Intel                    | 34       | 30.09%  |
| Nvidia                   | 24       | 21.24%  |
| Creative Labs            | 7        | 6.19%   |
| Micro Star International | 2        | 1.77%   |
| VIA Technologies         | 1        | 0.88%   |
| Texas Instruments        | 1        | 0.88%   |
| RME                      | 1        | 0.88%   |
| M-Audio                  | 1        | 0.88%   |
| Kingston Technology      | 1        | 0.88%   |
| Holtek Semiconductor     | 1        | 0.88%   |
| EGO SYStems              | 1        | 0.88%   |
| C-Media Electronics      | 1        | 0.88%   |
| ASUSTek Computer         | 1        | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 12       | 8.22%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 7        | 4.79%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                  | 6        | 4.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 6        | 4.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 5        | 3.42%   |
| Nvidia MCP61 High Definition Audio                                                              | 4        | 2.74%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 4        | 2.74%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 4        | 2.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 4        | 2.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 4        | 2.74%   |
| AMD FCH Azalia Controller                                                                       | 4        | 2.74%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 3        | 2.05%   |
| Nvidia GF108 High Definition Audio Controller                                                   | 3        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 3        | 2.05%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 3        | 2.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 3        | 2.05%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 3        | 2.05%   |
| AMD Navi 10 HDMI Audio                                                                          | 3        | 2.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 3        | 2.05%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 3        | 2.05%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 2        | 1.37%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 2        | 1.37%   |
| Micro Star International USB Audio                                                              | 2        | 1.37%   |
| Intel Cannon Lake PCH cAVS                                                                      | 2        | 1.37%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 2        | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2        | 1.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 2        | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 2        | 1.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 2        | 1.37%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 2        | 1.37%   |
| AMD Navi 31 HDMI/DP Audio                                                                       | 2        | 1.37%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                     | 1        | 0.68%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 1        | 0.68%   |
| RME ADI-2 DAC (51060020)                                                                        | 1        | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 1        | 0.68%   |
| Nvidia MCP79 High Definition Audio                                                              | 1        | 0.68%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 1        | 0.68%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 1        | 0.68%   |
| Nvidia GM204 High Definition Audio Controller                                                   | 1        | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 1        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 16       | 19.51%  |
| Corsair             | 14       | 17.07%  |
| Unknown             | 8        | 9.76%   |
| SK hynix            | 7        | 8.54%   |
| Samsung Electronics | 6        | 7.32%   |
| Crucial             | 6        | 7.32%   |
| Team                | 4        | 4.88%   |
| G.Skill             | 3        | 3.66%   |
| Transcend           | 2        | 2.44%   |
| Micron Technology   | 2        | 2.44%   |
| AMD                 | 2        | 2.44%   |
| Unknown             | 2        | 2.44%   |
| Strontium           | 1        | 1.22%   |
| Smart               | 1        | 1.22%   |
| Silicon Power       | 1        | 1.22%   |
| Patriot             | 1        | 1.22%   |
| HPE                 | 1        | 1.22%   |
| Hewlett-Packard     | 1        | 1.22%   |
| GOODRAM             | 1        | 1.22%   |
| GLOWAY              | 1        | 1.22%   |
| A-DATA Technology   | 1        | 1.22%   |
| A Force             | 1        | 1.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                        | 2        | 2.15%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s         | 2        | 2.15%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s         | 2        | 2.15%   |
| Corsair RAM CMZ32GX3M4X1600C10 8GB DIMM DDR3 1600MT/s       | 2        | 2.15%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 2        | 2.15%   |
| Unknown                                                     | 2        | 2.15%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                   | 1        | 1.08%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                    | 1        | 1.08%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s               | 1        | 1.08%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                    | 1        | 1.08%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                    | 1        | 1.08%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                  | 1        | 1.08%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                      | 1        | 1.08%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1        | 1.08%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1        | 1.08%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s           | 1        | 1.08%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s       | 1        | 1.08%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s          | 1        | 1.08%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s          | 1        | 1.08%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s       | 1        | 1.08%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s         | 1        | 1.08%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s | 1        | 1.08%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1        | 1.08%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s        | 1        | 1.08%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s        | 1        | 1.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1        | 1.08%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1        | 1.08%   |
| SK hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s        | 1        | 1.08%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s   | 1        | 1.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1        | 1.08%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1        | 1.08%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s         | 1        | 1.08%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s        | 1        | 1.08%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 1.08%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 1.08%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s         | 1        | 1.08%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s             | 1        | 1.08%   |
| Micron RAM 36KSF1G72PZ-1G4K1 8GB DIMM DDR3 1333MT/s         | 1        | 1.08%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s         | 1        | 1.08%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s        | 1        | 1.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 33       | 47.14%  |
| DDR3    | 28       | 40%     |
| DDR2    | 4        | 5.71%   |
| SDRAM   | 2        | 2.86%   |
| DDR     | 2        | 2.86%   |
| Unknown | 1        | 1.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 66       | 92.96%  |
| SODIMM  | 3        | 4.23%   |
| RIMM    | 1        | 1.41%   |
| FB-DIMM | 1        | 1.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 31       | 39.24%  |
| 4096  | 18       | 22.78%  |
| 16384 | 12       | 15.19%  |
| 2048  | 8        | 10.13%  |
| 32768 | 6        | 7.59%   |
| 1024  | 4        | 5.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 17       | 21.25%  |
| 3600    | 8        | 10%     |
| 2400    | 7        | 8.75%   |
| 1333    | 6        | 7.5%    |
| 3200    | 5        | 6.25%   |
| 3800    | 4        | 5%      |
| 667     | 4        | 5%      |
| 2667    | 3        | 3.75%   |
| 2133    | 3        | 3.75%   |
| 1867    | 3        | 3.75%   |
| 3733    | 2        | 2.5%    |
| 2800    | 2        | 2.5%    |
| 2666    | 2        | 2.5%    |
| 1866    | 2        | 2.5%    |
| Unknown | 2        | 2.5%    |
| 65535   | 1        | 1.25%   |
| 3400    | 1        | 1.25%   |
| 2933    | 1        | 1.25%   |
| 2472    | 1        | 1.25%   |
| 2187    | 1        | 1.25%   |
| 2000    | 1        | 1.25%   |
| 1066    | 1        | 1.25%   |
| 975     | 1        | 1.25%   |
| 800     | 1        | 1.25%   |
| 533     | 1        | 1.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 33.33%  |
| Brother Industries  | 3        | 33.33%  |
| QinHeng Electronics | 1        | 11.11%  |
| Dell                | 1        | 11.11%  |
| Canon               | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| QinHeng CH340S               | 1        | 11.11%  |
| HP OfficeJet Pro 9010 series | 1        | 11.11%  |
| HP ENVY 4520 series          | 1        | 11.11%  |
| HP ENVY 4500 series          | 1        | 11.11%  |
| Dell 2330d Laser Printer     | 1        | 11.11%  |
| Canon CanoScan LiDE 300      | 1        | 11.11%  |
| Brother Printer              | 1        | 11.11%  |
| Brother HL-L5102DW           | 1        | 11.11%  |
| Brother HL-L2320D series     | 1        | 11.11%  |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 12       | 75%     |
| Z-Star Microelectronics | 1        | 6.25%   |
| Samsung Electronics     | 1        | 6.25%   |
| Microsoft               | 1        | 6.25%   |
| Microdia                | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 3        | 18.75%  |
| Z-Star Vimicro USB2.0 Camera            | 1        | 6.25%   |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 6.25%   |
| Microsoft LifeCam HD-3000               | 1        | 6.25%   |
| Microdia Camera                         | 1        | 6.25%   |
| Logitech Webcam C310                    | 1        | 6.25%   |
| Logitech Webcam C300                    | 1        | 6.25%   |
| Logitech Webcam C170                    | 1        | 6.25%   |
| Logitech QuickCam Pro 9000              | 1        | 6.25%   |
| Logitech Logitech Webcam C160           | 1        | 6.25%   |
| Logitech HD Webcam C910                 | 1        | 6.25%   |
| Logitech HD Webcam C525                 | 1        | 6.25%   |
| Logitech HD Pro Webcam C920             | 1        | 6.25%   |
| Logitech C922 Pro Stream Webcam         | 1        | 6.25%   |

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
| 0     | 47       | 60.26%  |
| 1     | 14       | 17.95%  |
| 2     | 8        | 10.26%  |
| 4     | 5        | 6.41%   |
| 3     | 3        | 3.85%   |
| 5     | 1        | 1.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 15       | 27.27%  |
| Graphics card            | 10       | 18.18%  |
| Communication controller | 7        | 12.73%  |
| Net/wireless             | 6        | 10.91%  |
| Unassigned class         | 5        | 9.09%   |
| Bluetooth                | 3        | 5.45%   |
| Camera                   | 2        | 3.64%   |
| Storage/raid             | 1        | 1.82%   |
| Storage/ide              | 1        | 1.82%   |
| Storage/ata              | 1        | 1.82%   |
| Net/ethernet             | 1        | 1.82%   |
| Fingerprint reader       | 1        | 1.82%   |
| Chipcard                 | 1        | 1.82%   |
| Card reader              | 1        | 1.82%   |

