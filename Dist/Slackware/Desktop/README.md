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

Total: 83

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Slackware 15.0  | 37       | 52.11%  |
| Slackware 14.2  | 32       | 45.07%  |
| Slackware 14.2+ | 2        | 2.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Slackware | 69       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.15.19              | 6        | 8%      |
| 5.10.28-Unraid       | 5        | 6.67%   |
| 5.19.17              | 4        | 5.33%   |
| 5.15.63              | 4        | 5.33%   |
| 4.19.80              | 4        | 5.33%   |
| 5.19.17-Unraid       | 3        | 4%      |
| 4.4.190              | 3        | 4%      |
| 5.15.94              | 2        | 2.67%   |
| 5.15.30-Unraid       | 2        | 2.67%   |
| 5.15.27              | 2        | 2.67%   |
| 4.4.240              | 2        | 2.67%   |
| 6.1.20               | 1        | 1.33%   |
| 6.1.13               | 1        | 1.33%   |
| 5.4.77               | 1        | 1.33%   |
| 5.4.53-APRL          | 1        | 1.33%   |
| 5.4.43               | 1        | 1.33%   |
| 5.4.0-rc2-vto        | 1        | 1.33%   |
| 5.19.16              | 1        | 1.33%   |
| 5.17.2               | 1        | 1.33%   |
| 5.17.0-custom        | 1        | 1.33%   |
| 5.16.18              | 1        | 1.33%   |
| 5.16.13              | 1        | 1.33%   |
| 5.16.11              | 1        | 1.33%   |
| 5.15.6               | 1        | 1.33%   |
| 5.15.50-cwl          | 1        | 1.33%   |
| 5.15.38              | 1        | 1.33%   |
| 5.15.14              | 1        | 1.33%   |
| 5.15.13              | 1        | 1.33%   |
| 5.15.103             | 1        | 1.33%   |
| 5.14.15-Unraid       | 1        | 1.33%   |
| 5.14.15              | 1        | 1.33%   |
| 5.14.12              | 1        | 1.33%   |
| 5.14.11              | 1        | 1.33%   |
| 5.13.9-jw            | 1        | 1.33%   |
| 5.13.12              | 1        | 1.33%   |
| 5.12.12              | 1        | 1.33%   |
| 5.10.44-slack64-host | 1        | 1.33%   |
| 5.10.40              | 1        | 1.33%   |
| 5.10.3               | 1        | 1.33%   |
| 4.9.248.a            | 1        | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.19.17  | 7        | 9.33%   |
| 5.15.19  | 6        | 8%      |
| 5.10.28  | 5        | 6.67%   |
| 5.15.63  | 4        | 5.33%   |
| 4.19.80  | 4        | 5.33%   |
| 4.4.190  | 3        | 4%      |
| 5.15.94  | 2        | 2.67%   |
| 5.15.30  | 2        | 2.67%   |
| 5.15.27  | 2        | 2.67%   |
| 5.14.15  | 2        | 2.67%   |
| 4.4.240  | 2        | 2.67%   |
| 6.1.20   | 1        | 1.33%   |
| 6.1.13   | 1        | 1.33%   |
| 5.4.77   | 1        | 1.33%   |
| 5.4.53   | 1        | 1.33%   |
| 5.4.43   | 1        | 1.33%   |
| 5.4.0    | 1        | 1.33%   |
| 5.19.16  | 1        | 1.33%   |
| 5.17.2   | 1        | 1.33%   |
| 5.17.0   | 1        | 1.33%   |
| 5.16.18  | 1        | 1.33%   |
| 5.16.13  | 1        | 1.33%   |
| 5.16.11  | 1        | 1.33%   |
| 5.15.6   | 1        | 1.33%   |
| 5.15.50  | 1        | 1.33%   |
| 5.15.38  | 1        | 1.33%   |
| 5.15.14  | 1        | 1.33%   |
| 5.15.13  | 1        | 1.33%   |
| 5.15.103 | 1        | 1.33%   |
| 5.14.12  | 1        | 1.33%   |
| 5.14.11  | 1        | 1.33%   |
| 5.13.9   | 1        | 1.33%   |
| 5.13.12  | 1        | 1.33%   |
| 5.12.12  | 1        | 1.33%   |
| 5.10.44  | 1        | 1.33%   |
| 5.10.40  | 1        | 1.33%   |
| 5.10.3   | 1        | 1.33%   |
| 4.9.248  | 1        | 1.33%   |
| 4.9.118  | 1        | 1.33%   |
| 4.4.261  | 1        | 1.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 22       | 29.73%  |
| 5.19    | 8        | 10.81%  |
| 5.10    | 8        | 10.81%  |
| 4.4     | 8        | 10.81%  |
| 4.19    | 8        | 10.81%  |
| 5.4     | 4        | 5.41%   |
| 5.14    | 4        | 5.41%   |
| 5.16    | 3        | 4.05%   |
| 5.17    | 2        | 2.7%    |
| 5.13    | 2        | 2.7%    |
| 4.9     | 2        | 2.7%    |
| 6.1     | 1        | 1.35%   |
| 5.12    | 1        | 1.35%   |
| 4.20    | 1        | 1.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 69       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 28       | 40%     |
| XFCE       | 20       | 28.57%  |
| KDE5       | 16       | 22.86%  |
| FVWM       | 2        | 2.86%   |
| X-Generic  | 1        | 1.43%   |
| X-Cinnamon | 1        | 1.43%   |
| MATE       | 1        | 1.43%   |
| KDE        | 1        | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 42       | 59.15%  |
| Tty     | 15       | 21.13%  |
| Unknown | 11       | 15.49%  |
| Wayland | 3        | 4.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 42.25%  |
| SDDM    | 19       | 26.76%  |
| XDM     | 16       | 22.54%  |
| SLiM    | 3        | 4.23%   |
| LightDM | 3        | 4.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 29       | 42.03%  |
| Unknown     | 25       | 36.23%  |
| en_GB       | 3        | 4.35%   |
| ru_RU       | 2        | 2.9%    |
| it_IT       | 2        | 2.9%    |
| sr_RS@latin | 1        | 1.45%   |
| pt_PT       | 1        | 1.45%   |
| pt_BR       | 1        | 1.45%   |
| es_ES.UTF8  | 1        | 1.45%   |
| es_ES       | 1        | 1.45%   |
| en_US.ASCII | 1        | 1.45%   |
| en_AU       | 1        | 1.45%   |
| C           | 1        | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 40       | 57.97%  |
| EFI  | 29       | 42.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 43       | 62.32%  |
| Btrfs    | 10       | 14.49%  |
| Xfs      | 5        | 7.25%   |
| Rootfs   | 4        | 5.8%    |
| Overlay  | 2        | 2.9%    |
| Tmpfs    | 1        | 1.45%   |
| Reiserfs | 1        | 1.45%   |
| F2fs     | 1        | 1.45%   |
| Ext3     | 1        | 1.45%   |
| Ext2     | 1        | 1.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 46       | 64.79%  |
| MBR     | 20       | 28.17%  |
| Unknown | 5        | 7.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 35       | 50%     |
| No        | 35       | 50%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 68.12%  |
| Yes       | 22       | 31.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 19       | 27.54%  |
| ASRock              | 11       | 15.94%  |
| MSI                 | 8        | 11.59%  |
| Hewlett-Packard     | 7        | 10.14%  |
| Gigabyte Technology | 6        | 8.7%    |
| Dell                | 5        | 7.25%   |
| Supermicro          | 1        | 1.45%   |
| Shuttle             | 1        | 1.45%   |
| NetGear             | 1        | 1.45%   |
| Lenovo              | 1        | 1.45%   |
| Intel               | 1        | 1.45%   |
| Huanan              | 1        | 1.45%   |
| HPE                 | 1        | 1.45%   |
| HEDYCOMPUTER        | 1        | 1.45%   |
| Fujitsu             | 1        | 1.45%   |
| Foxconn             | 1        | 1.45%   |
| Biostar             | 1        | 1.45%   |
| Acer                | 1        | 1.45%   |
| Unknown             | 1        | 1.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS All Series                      | 4        | 5.8%    |
| ASRock N68-S3 FX                     | 2        | 2.9%    |
| Supermicro X9DA7/E                   | 1        | 1.45%   |
| Shuttle NC03U                        | 1        | 1.45%   |
| NetGear ReadyDATA 5200               | 1        | 1.45%   |
| MSI MS-7C52                          | 1        | 1.45%   |
| MSI MS-7C02                          | 1        | 1.45%   |
| MSI MS-7996                          | 1        | 1.45%   |
| MSI MS-7885                          | 1        | 1.45%   |
| MSI MS-7788                          | 1        | 1.45%   |
| MSI MS-7693                          | 1        | 1.45%   |
| MSI MS-7529                          | 1        | 1.45%   |
| MSI MS-7365                          | 1        | 1.45%   |
| Lenovo H50-05 90BH001WIX             | 1        | 1.45%   |
| Intel DZ77RE-75K AAG39010-302        | 1        | 1.45%   |
| Huanan X79-8D VAA31                  | 1        | 1.45%   |
| HPE ProLiant MicroServer Gen10 Plus  | 1        | 1.45%   |
| HP Z620 Workstation                  | 1        | 1.45%   |
| HP Z440 Workstation                  | 1        | 1.45%   |
| HP xw8400 Workstation                | 1        | 1.45%   |
| HP t620 Quad Core TC                 | 1        | 1.45%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 1        | 1.45%   |
| HP Compaq dc7900 Small Form Factor   | 1        | 1.45%   |
| HP 500-515na                         | 1        | 1.45%   |
| HEDYCOMPUTER IH81MF-Q3               | 1        | 1.45%   |
| Gigabyte X570 AORUS MASTER           | 1        | 1.45%   |
| Gigabyte X150M-PRO ECC               | 1        | 1.45%   |
| Gigabyte N3160TN                     | 1        | 1.45%   |
| Gigabyte M61SME-S2                   | 1        | 1.45%   |
| Gigabyte AB350-Gaming 3              | 1        | 1.45%   |
| Gigabyte 970A-DS3P                   | 1        | 1.45%   |
| Fujitsu FujitsuTP7000                | 1        | 1.45%   |
| Foxconn p6-2390                      | 1        | 1.45%   |
| Dell Precision WorkStation T3400     | 1        | 1.45%   |
| Dell Precision WorkStation 690       | 1        | 1.45%   |
| Dell Precision T3600                 | 1        | 1.45%   |
| Dell OptiPlex 780                    | 1        | 1.45%   |
| Dell OptiPlex 3020                   | 1        | 1.45%   |
| Biostar X470GTA                      | 1        | 1.45%   |
| ASUS TUF Gaming B450-PLUS II         | 1        | 1.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 5        | 7.25%   |
| ASUS All               | 4        | 5.8%    |
| Dell Precision         | 3        | 4.35%   |
| ASUS ROG               | 3        | 4.35%   |
| Dell OptiPlex          | 2        | 2.9%    |
| ASUS TUF               | 2        | 2.9%    |
| ASRock N68-S3          | 2        | 2.9%    |
| Supermicro X9DA7       | 1        | 1.45%   |
| Shuttle NC03U          | 1        | 1.45%   |
| NetGear ReadyDATA      | 1        | 1.45%   |
| MSI MS-7C52            | 1        | 1.45%   |
| MSI MS-7C02            | 1        | 1.45%   |
| MSI MS-7996            | 1        | 1.45%   |
| MSI MS-7885            | 1        | 1.45%   |
| MSI MS-7788            | 1        | 1.45%   |
| MSI MS-7693            | 1        | 1.45%   |
| MSI MS-7529            | 1        | 1.45%   |
| MSI MS-7365            | 1        | 1.45%   |
| Lenovo H50-05          | 1        | 1.45%   |
| Intel DZ77RE-75K       | 1        | 1.45%   |
| Huanan X79-8D          | 1        | 1.45%   |
| HPE ProLiant           | 1        | 1.45%   |
| HP Z620                | 1        | 1.45%   |
| HP Z440                | 1        | 1.45%   |
| HP xw8400              | 1        | 1.45%   |
| HP t620                | 1        | 1.45%   |
| HP Pavilion            | 1        | 1.45%   |
| HP Compaq              | 1        | 1.45%   |
| HP 500-515na           | 1        | 1.45%   |
| HEDYCOMPUTER IH81MF-Q3 | 1        | 1.45%   |
| Gigabyte X570          | 1        | 1.45%   |
| Gigabyte X150M-PRO     | 1        | 1.45%   |
| Gigabyte N3160TN       | 1        | 1.45%   |
| Gigabyte M61SME-S2     | 1        | 1.45%   |
| Gigabyte AB350-Gaming  | 1        | 1.45%   |
| Gigabyte 970A-DS3P     | 1        | 1.45%   |
| Fujitsu FujitsuTP7000  | 1        | 1.45%   |
| Foxconn p6-2390        | 1        | 1.45%   |
| Biostar X470GTA        | 1        | 1.45%   |
| ASUS SABERTOOTH        | 1        | 1.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 10       | 14.49%  |
| 2018 | 7        | 10.14%  |
| 2017 | 6        | 8.7%    |
| 2015 | 6        | 8.7%    |
| 2012 | 6        | 8.7%    |
| 2011 | 6        | 8.7%    |
| 2020 | 5        | 7.25%   |
| 2014 | 5        | 7.25%   |
| 2008 | 4        | 5.8%    |
| 2016 | 3        | 4.35%   |
| 2009 | 3        | 4.35%   |
| 2022 | 2        | 2.9%    |
| 2013 | 2        | 2.9%    |
| 2007 | 2        | 2.9%    |
| 2021 | 1        | 1.45%   |
| 2010 | 1        | 1.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 69       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 69       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 69       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 19       | 27.14%  |
| 32.01-64.0  | 12       | 17.14%  |
| 8.01-16.0   | 10       | 14.29%  |
| 64.01-256.0 | 8        | 11.43%  |
| 4.01-8.0    | 7        | 10%     |
| 3.01-4.0    | 7        | 10%     |
| 24.01-32.0  | 4        | 5.71%   |
| 1.01-2.0    | 3        | 4.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 18       | 25%     |
| 4.01-8.0    | 17       | 23.61%  |
| 2.01-3.0    | 14       | 19.44%  |
| 3.01-4.0    | 7        | 9.72%   |
| 8.01-16.0   | 4        | 5.56%   |
| 0.51-1.0    | 4        | 5.56%   |
| 24.01-32.0  | 2        | 2.78%   |
| 16.01-24.0  | 2        | 2.78%   |
| 0.01-0.5    | 2        | 2.78%   |
| 32.01-64.0  | 1        | 1.39%   |
| 64.01-256.0 | 1        | 1.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 23.61%  |
| 3      | 15       | 20.83%  |
| 2      | 15       | 20.83%  |
| 4      | 7        | 9.72%   |
| 6      | 6        | 8.33%   |
| 5      | 5        | 6.94%   |
| 0      | 2        | 2.78%   |
| 13     | 1        | 1.39%   |
| 11     | 1        | 1.39%   |
| 9      | 1        | 1.39%   |
| 8      | 1        | 1.39%   |
| 7      | 1        | 1.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 38       | 54.29%  |
| No        | 32       | 45.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 69       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 62.86%  |
| Yes       | 26       | 37.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 63.77%  |
| Yes       | 25       | 36.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 16       | 23.19%  |
| UK           | 9        | 13.04%  |
| Germany      | 5        | 7.25%   |
| Russia       | 4        | 5.8%    |
| Italy        | 4        | 5.8%    |
| Brazil       | 4        | 5.8%    |
| Spain        | 3        | 4.35%   |
| Kazakhstan   | 3        | 4.35%   |
| Hong Kong    | 3        | 4.35%   |
| Canada       | 3        | 4.35%   |
| Sweden       | 2        | 2.9%    |
| Portugal     | 2        | 2.9%    |
| Japan        | 2        | 2.9%    |
| France       | 2        | 2.9%    |
| Australia    | 2        | 2.9%    |
| South Africa | 1        | 1.45%   |
| Serbia       | 1        | 1.45%   |
| China        | 1        | 1.45%   |
| Bulgaria     | 1        | 1.45%   |
| Argentina    | 1        | 1.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Yekaterinburg     | 3        | 4.23%   |
| Ust-Kamenogorsk   | 2        | 2.82%   |
| Springfield       | 2        | 2.82%   |
| Paris             | 2        | 2.82%   |
| Lisbon            | 2        | 2.82%   |
| Winter Springs    | 1        | 1.41%   |
| Weilheim          | 1        | 1.41%   |
| Tsukuba           | 1        | 1.41%   |
| Toronto           | 1        | 1.41%   |
| Tiffin            | 1        | 1.41%   |
| Tendo             | 1        | 1.41%   |
| Tatuí            | 1        | 1.41%   |
| Stockholm         | 1        | 1.41%   |
| St Petersburg     | 1        | 1.41%   |
| Southend-on-Sea   | 1        | 1.41%   |
| Shrewsbury        | 1        | 1.41%   |
| Sham Shui Po      | 1        | 1.41%   |
| Seville           | 1        | 1.41%   |
| Senhora da Hora   | 1        | 1.41%   |
| Santa Cruz do Sul | 1        | 1.41%   |
| Saint Paul        | 1        | 1.41%   |
| Rome              | 1        | 1.41%   |
| Rock              | 1        | 1.41%   |
| Porto Alegre      | 1        | 1.41%   |
| Plovdiv           | 1        | 1.41%   |
| Palma             | 1        | 1.41%   |
| Ottawa            | 1        | 1.41%   |
| Oldham            | 1        | 1.41%   |
| Naples            | 1        | 1.41%   |
| Nanping           | 1        | 1.41%   |
| Moscow            | 1        | 1.41%   |
| Milwaukee         | 1        | 1.41%   |
| Milan             | 1        | 1.41%   |
| Mead              | 1        | 1.41%   |
| McKinney          | 1        | 1.41%   |
| Mason             | 1        | 1.41%   |
| Luton             | 1        | 1.41%   |
| London            | 1        | 1.41%   |
| Lexington         | 1        | 1.41%   |
| Leipzig           | 1        | 1.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 31       | 71     | 21.99%  |
| Seagate             | 28       | 54     | 19.86%  |
| Samsung Electronics | 20       | 32     | 14.18%  |
| Toshiba             | 12       | 29     | 8.51%   |
| Hitachi             | 8        | 11     | 5.67%   |
| Kingston            | 6        | 9      | 4.26%   |
| Crucial             | 5        | 6      | 3.55%   |
| Intel               | 3        | 4      | 2.13%   |
| A-DATA Technology   | 3        | 3      | 2.13%   |
| Transcend           | 2        | 2      | 1.42%   |
| SK hynix            | 2        | 2      | 1.42%   |
| Maxtor              | 2        | 2      | 1.42%   |
| HGST                | 2        | 2      | 1.42%   |
| Hewlett-Packard     | 2        | 2      | 1.42%   |
| China               | 2        | 3      | 1.42%   |
| ZHITAI              | 1        | 2      | 0.71%   |
| Team                | 1        | 1      | 0.71%   |
| SanDisk             | 1        | 1      | 0.71%   |
| PNY                 | 1        | 1      | 0.71%   |
| Phison Electronics  | 1        | 1      | 0.71%   |
| Patriot             | 1        | 1      | 0.71%   |
| Lexar               | 1        | 1      | 0.71%   |
| KIOXIA              | 1        | 1      | 0.71%   |
| Intenso             | 1        | 1      | 0.71%   |
| Gigabyte Technology | 1        | 1      | 0.71%   |
| Fujitsu             | 1        | 1      | 0.71%   |
| DUEX                | 1        | 1      | 0.71%   |
| Apple               | 1        | 2      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD20EFRX-68EUZN0 2TB         | 3        | 1.6%    |
| WDC WD1003FZEX-00MK2A0 1TB       | 3        | 1.6%    |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 1.6%    |
| Samsung SSD 970 EVO 250GB        | 3        | 1.6%    |
| WDC WD30EZRX-00SPEB0 3TB         | 2        | 1.07%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 1.07%   |
| WDC WD10EZEX-00RKKA0 1TB         | 2        | 1.07%   |
| Toshiba MQ01ABD100 1TB           | 2        | 1.07%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 1.07%   |
| Seagate ST4000VN008-2DR166 4TB   | 2        | 1.07%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 1.07%   |
| Seagate ST31000524AS 1TB         | 2        | 1.07%   |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 1.07%   |
| Seagate ST2000DL003-9VT166 2TB   | 2        | 1.07%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 1.07%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 1.07%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 1.07%   |
| Seagate Expansion Desk 5TB       | 2        | 1.07%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 1.07%   |
| Kingston SA400S37240G 240GB SSD  | 2        | 1.07%   |
| Crucial CT500MX500SSD1 500GB     | 2        | 1.07%   |
| ZHITAI SC001 Active 1TB SSD      | 1        | 0.53%   |
| ZHITAI PC005 Active 512GB        | 1        | 0.53%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.53%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.53%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1        | 0.53%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 0.53%   |
| WDC WD5000BPVT-2 500GB           | 1        | 0.53%   |
| WDC WD5000BPKX-60HPJT0 500GB     | 1        | 0.53%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 1        | 0.53%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 0.53%   |
| WDC WD5000AAKS-00V0A0 500GB      | 1        | 0.53%   |
| WDC WD5000AAKS-00A7B2 500GB      | 1        | 0.53%   |
| WDC WD5000AAKS-007AA0 500GB      | 1        | 0.53%   |
| WDC WD5000AADS-00S9B0 500GB      | 1        | 0.53%   |
| WDC WD40EZRX-00SPEB0 4TB         | 1        | 0.53%   |
| WDC WD40EJRX-89T1XY0 4TB         | 1        | 0.53%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.53%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 0.53%   |
| WDC WD400BD-60LTA0 40GB          | 1        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 67     | 34.48%  |
| Seagate             | 28       | 50     | 32.18%  |
| Toshiba             | 11       | 24     | 12.64%  |
| Hitachi             | 8        | 11     | 9.2%    |
| Samsung Electronics | 4        | 4      | 4.6%    |
| Maxtor              | 2        | 2      | 2.3%    |
| HGST                | 2        | 2      | 2.3%    |
| Hewlett-Packard     | 1        | 1      | 1.15%   |
| Fujitsu             | 1        | 1      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 17     | 24.39%  |
| Kingston            | 6        | 9      | 14.63%  |
| Crucial             | 4        | 5      | 9.76%   |
| WDC                 | 2        | 3      | 4.88%   |
| Transcend           | 2        | 2      | 4.88%   |
| Intel               | 2        | 3      | 4.88%   |
| China               | 2        | 3      | 4.88%   |
| ZHITAI              | 1        | 1      | 2.44%   |
| Toshiba             | 1        | 3      | 2.44%   |
| Team                | 1        | 1      | 2.44%   |
| SK hynix            | 1        | 1      | 2.44%   |
| SanDisk             | 1        | 1      | 2.44%   |
| PNY                 | 1        | 1      | 2.44%   |
| Patriot             | 1        | 1      | 2.44%   |
| Lexar               | 1        | 1      | 2.44%   |
| Intenso             | 1        | 1      | 2.44%   |
| Hewlett-Packard     | 1        | 1      | 2.44%   |
| DUEX                | 1        | 1      | 2.44%   |
| Apple               | 1        | 2      | 2.44%   |
| A-DATA Technology   | 1        | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 55       | 162    | 49.55%  |
| SSD     | 36       | 58     | 32.43%  |
| NVMe    | 19       | 23     | 17.12%  |
| Unknown | 1        | 4      | 0.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 63       | 214    | 74.12%  |
| NVMe | 19       | 23     | 22.35%  |
| SAS  | 3        | 10     | 3.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 46       | 78     | 39.66%  |
| 0.51-1.0   | 27       | 63     | 23.28%  |
| 1.01-2.0   | 17       | 24     | 14.66%  |
| 3.01-4.0   | 10       | 23     | 8.62%   |
| 2.01-3.0   | 8        | 19     | 6.9%    |
| 4.01-10.0  | 6        | 8      | 5.17%   |
| 10.01-20.0 | 2        | 5      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 14       | 19.44%  |
| 501-1000       | 12       | 16.67%  |
| 101-250        | 11       | 15.28%  |
| 2001-3000      | 8        | 11.11%  |
| 1001-2000      | 8        | 11.11%  |
| 251-500        | 7        | 9.72%   |
| 1-20           | 5        | 6.94%   |
| More than 3000 | 4        | 5.56%   |
| 51-100         | 2        | 2.78%   |
| 21-50          | 1        | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 15       | 21.13%  |
| Unknown        | 14       | 19.72%  |
| 501-1000       | 11       | 15.49%  |
| 1-20           | 9        | 12.68%  |
| 251-500        | 6        | 8.45%   |
| 1001-2000      | 5        | 7.04%   |
| 51-100         | 5        | 7.04%   |
| More than 3000 | 3        | 4.23%   |
| 21-50          | 3        | 4.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1        | 1      | 3.03%   |
| WDC WD5000BPKX-60HPJT0 500GB          | 1        | 1      | 3.03%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1        | 1      | 3.03%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 3.03%   |
| WDC WD5000AAKS-00A7B2 500GB           | 1        | 1      | 3.03%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1        | 2      | 3.03%   |
| WDC WD3200AAJS-65B4A0 320GB           | 1        | 1      | 3.03%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1        | 1      | 3.03%   |
| WDC WD30EZRX-00M                      | 1        | 1      | 3.03%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1        | 4      | 3.03%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 3.03%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 3.03%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1        | 1      | 3.03%   |
| WDC WD10EALS-00Z8A0 1TB               | 1        | 2      | 3.03%   |
| WDC WD1003FZEX-00MK2A0 1TB            | 1        | 2      | 3.03%   |
| Seagate ST380011A 80GB                | 1        | 2      | 3.03%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 3.03%   |
| Seagate ST3500410AS 500GB             | 1        | 1      | 3.03%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 3.03%   |
| Seagate ST3000VX006-1HH166 3TB        | 1        | 1      | 3.03%   |
| Seagate ST2000DL003-9VT166 2TB        | 1        | 1      | 3.03%   |
| Seagate ST1000VM002-1SD102 1TB        | 1        | 1      | 3.03%   |
| Seagate ST1000NM0011 1TB              | 1        | 2      | 3.03%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 2      | 3.03%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD    | 1        | 1      | 3.03%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 3.03%   |
| Maxtor 4G120J6 128GB                  | 1        | 1      | 3.03%   |
| Intel SSDSA2M080G2GC 80GB             | 1        | 1      | 3.03%   |
| Hitachi HUA723030ALA640 3TB           | 1        | 1      | 3.03%   |
| Hitachi HDS721050CLA660 500GB         | 1        | 1      | 3.03%   |
| Hitachi HDS721016CLA382 160GB         | 1        | 1      | 3.03%   |
| HGST HDN726040ALE614 4TB              | 1        | 1      | 3.03%   |
| DUEX DX300256A5xnEMLC 256GB SSD       | 1        | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 22     | 41.38%  |
| Seagate             | 8        | 12     | 27.59%  |
| Hitachi             | 3        | 3      | 10.34%  |
| SanDisk             | 1        | 1      | 3.45%   |
| Samsung Electronics | 1        | 1      | 3.45%   |
| Maxtor              | 1        | 1      | 3.45%   |
| Intel               | 1        | 1      | 3.45%   |
| HGST                | 1        | 1      | 3.45%   |
| DUEX                | 1        | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 11       | 21     | 45.83%  |
| Seagate | 8        | 12     | 33.33%  |
| Hitachi | 3        | 3      | 12.5%   |
| Maxtor  | 1        | 1      | 4.17%   |
| HGST    | 1        | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 38     | 80.77%  |
| SSD  | 4        | 4      | 15.38%  |
| NVMe | 1        | 1      | 3.85%   |

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
| Works    | 56       | 166    | 60.87%  |
| Malfunc  | 26       | 43     | 28.26%  |
| Detected | 10       | 38     | 10.87%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 37       | 34.26%  |
| AMD                          | 26       | 24.07%  |
| Samsung Electronics          | 11       | 10.19%  |
| Marvell Technology Group     | 6        | 5.56%   |
| Nvidia                       | 5        | 4.63%   |
| ASMedia Technology           | 5        | 4.63%   |
| JMicron Technology           | 3        | 2.78%   |
| Realtek Semiconductor        | 2        | 1.85%   |
| Broadcom / LSI               | 2        | 1.85%   |
| Yangtze Memory Technologies  | 1        | 0.93%   |
| Toshiba America Info Systems | 1        | 0.93%   |
| SK hynix                     | 1        | 0.93%   |
| Silicon Image                | 1        | 0.93%   |
| SanDisk                      | 1        | 0.93%   |
| Phison Electronics           | 1        | 0.93%   |
| Micron/Crucial Technology    | 1        | 0.93%   |
| LSI Logic / Symbios Logic    | 1        | 0.93%   |
| KIOXIA                       | 1        | 0.93%   |
| Adaptec                      | 1        | 0.93%   |
| 3ware                        | 1        | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 17       | 11.89%  |
| AMD 400 Series Chipset SATA Controller                                        | 10       | 6.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 8        | 5.59%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                     | 6        | 4.2%    |
| Nvidia MCP61 SATA Controller                                                  | 4        | 2.8%    |
| Nvidia MCP61 IDE                                                              | 4        | 2.8%    |
| ASMedia ASM1062 Serial ATA Controller                                         | 4        | 2.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 4        | 2.8%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 3        | 2.1%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 3        | 2.1%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 3        | 2.1%    |
| Realtek NVMe Controller                                                       | 2        | 1.4%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller              | 2        | 1.4%    |
| JMicron JMB58x AHCI SATA controller                                           | 2        | 1.4%    |
| Intel SATA Controller [RAID mode]                                             | 2        | 1.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 1.4%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2        | 1.4%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 2        | 1.4%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                          | 2        | 1.4%    |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode] | 2        | 1.4%    |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode] | 2        | 1.4%    |
| Intel 631xESB/632xESB IDE Controller                                          | 2        | 1.4%    |
| Intel 4 Series Chipset PT IDER Controller                                     | 2        | 1.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2        | 1.4%    |
| AMD 500 Series Chipset SATA Controller                                        | 2        | 1.4%    |
| AMD 300 Series Chipset SATA Controller                                        | 2        | 1.4%    |
| Yangtze Memory Non-Volatile memory controller                                 | 1        | 0.7%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1        | 0.7%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 1        | 0.7%    |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller              | 1        | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1        | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1        | 0.7%    |
| Samsung Electronics SATA controller                                           | 1        | 0.7%    |
| Samsung Apple PCIe SSD                                                        | 1        | 0.7%    |
| Phison E16 PCIe4 NVMe Controller                                              | 1        | 0.7%    |
| Nvidia MCP79 AHCI Controller                                                  | 1        | 0.7%    |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1        | 0.7%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                  | 1        | 0.7%    |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo         | 1        | 0.7%    |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                       | 1        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 56       | 54.37%  |
| NVMe | 19       | 18.45%  |
| IDE  | 17       | 16.5%   |
| RAID | 5        | 4.85%   |
| SAS  | 4        | 3.88%   |
| SCSI | 2        | 1.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 39       | 56.52%  |
| AMD    | 30       | 43.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 4        | 5.71%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz     | 2        | 2.86%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 2        | 2.86%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2        | 2.86%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 2        | 2.86%   |
| AMD Ryzen 7 3800X 8-Core Processor     | 2        | 2.86%   |
| AMD FX-8350 Eight-Core Processor       | 2        | 2.86%   |
| AMD Athlon II X2 250 Processor         | 2        | 2.86%   |
| Intel Xeon CPU X5355 @ 2.66GHz         | 1        | 1.43%   |
| Intel Xeon CPU X3450 @ 2.67GHz         | 1        | 1.43%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz    | 1        | 1.43%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz    | 1        | 1.43%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz    | 1        | 1.43%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz     | 1        | 1.43%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz     | 1        | 1.43%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz    | 1        | 1.43%   |
| Intel Xeon CPU 5160 @ 3.00GHz          | 1        | 1.43%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz | 1        | 1.43%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz | 1        | 1.43%   |
| Intel Pentium CPU G640 @ 2.80GHz       | 1        | 1.43%   |
| Intel Pentium CPU G4560 @ 3.50GHz      | 1        | 1.43%   |
| Intel Pentium CPU G3250 @ 3.20GHz      | 1        | 1.43%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 1        | 1.43%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 1        | 1.43%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 1        | 1.43%   |
| Intel Core i7-3930K CPU @ 3.20GHz      | 1        | 1.43%   |
| Intel Core i5-9400 CPU @ 2.90GHz       | 1        | 1.43%   |
| Intel Core i5-8600K CPU @ 3.60GHz      | 1        | 1.43%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 1        | 1.43%   |
| Intel Core i5-4690 CPU @ 3.50GHz       | 1        | 1.43%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 1        | 1.43%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 1        | 1.43%   |
| Intel Core i5-3330 CPU @ 3.00GHz       | 1        | 1.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 1        | 1.43%   |
| Intel Core i3-10105 CPU @ 3.70GHz      | 1        | 1.43%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz  | 1        | 1.43%   |
| Intel Core 2 Quad CPU Q6700 @ 2.66GHz  | 1        | 1.43%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz   | 1        | 1.43%   |
| Intel Celeron CPU N3160 @ 1.60GHz      | 1        | 1.43%   |
| Intel Atom CPU 330 @ 1.60GHz           | 1        | 1.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 11       | 15.71%  |
| Intel Core i7      | 8        | 11.43%  |
| Intel Core i5      | 8        | 11.43%  |
| AMD Ryzen 5        | 8        | 11.43%  |
| AMD FX             | 5        | 7.14%   |
| AMD Ryzen 9        | 4        | 5.71%   |
| AMD Ryzen 7        | 4        | 5.71%   |
| Intel Pentium      | 3        | 4.29%   |
| Intel Core 2 Duo   | 3        | 4.29%   |
| Intel Core 2 Quad  | 2        | 2.86%   |
| AMD Athlon II X2   | 2        | 2.86%   |
| Intel Pentium Gold | 1        | 1.43%   |
| Intel Pentium Dual | 1        | 1.43%   |
| Intel Core i3      | 1        | 1.43%   |
| Intel Celeron      | 1        | 1.43%   |
| Intel Atom         | 1        | 1.43%   |
| AMD Ryzen 7 PRO    | 1        | 1.43%   |
| AMD Ryzen 3        | 1        | 1.43%   |
| AMD GX             | 1        | 1.43%   |
| AMD Athlon 64 X2   | 1        | 1.43%   |
| AMD A8             | 1        | 1.43%   |
| AMD A4             | 1        | 1.43%   |
| AMD A10            | 1        | 1.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 26       | 37.14%  |
| 2      | 14       | 20%     |
| 6      | 11       | 15.71%  |
| 8      | 8        | 11.43%  |
| 16     | 4        | 5.71%   |
| 12     | 3        | 4.29%   |
| 14     | 1        | 1.43%   |
| 10     | 1        | 1.43%   |
| 3      | 1        | 1.43%   |
| 1      | 1        | 1.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 64       | 92.75%  |
| 2      | 5        | 7.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 44       | 63.77%  |
| 1      | 25       | 36.23%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 69       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 21.74%  |
| 0x306c3    | 4        | 5.8%    |
| 0x206d7    | 4        | 5.8%    |
| 0x08701021 | 4        | 5.8%    |
| 0x306f2    | 3        | 4.35%   |
| 0x1067a    | 3        | 4.35%   |
| 0x08701013 | 3        | 4.35%   |
| 0x906ed    | 2        | 2.9%    |
| 0x906ea    | 2        | 2.9%    |
| 0x306a9    | 2        | 2.9%    |
| 0x0a50000c | 2        | 2.9%    |
| 0x0a201016 | 2        | 2.9%    |
| 0x06001119 | 2        | 2.9%    |
| 0x06000822 | 2        | 2.9%    |
| 0xa0653    | 1        | 1.45%   |
| 0x906e9    | 1        | 1.45%   |
| 0x6fd      | 1        | 1.45%   |
| 0x6fb      | 1        | 1.45%   |
| 0x506e3    | 1        | 1.45%   |
| 0x406c4    | 1        | 1.45%   |
| 0x306e4    | 1        | 1.45%   |
| 0x206a7    | 1        | 1.45%   |
| 0x106e5    | 1        | 1.45%   |
| 0x106c2    | 1        | 1.45%   |
| 0x08108109 | 1        | 1.45%   |
| 0x0810100b | 1        | 1.45%   |
| 0x08001138 | 1        | 1.45%   |
| 0x08001126 | 1        | 1.45%   |
| 0x07030105 | 1        | 1.45%   |
| 0x07000110 | 1        | 1.45%   |
| 0x06000852 | 1        | 1.45%   |
| 0x010000b6 | 1        | 1.45%   |
| 0x00000000 | 1        | 1.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 9        | 13.04%  |
| Haswell     | 9        | 13.04%  |
| SandyBridge | 7        | 10.14%  |
| KabyLake    | 7        | 10.14%  |
| Piledriver  | 6        | 8.7%    |
| Zen 3       | 4        | 5.8%    |
| Penryn      | 4        | 5.8%    |
| Core        | 4        | 5.8%    |
| Zen         | 3        | 4.35%   |
| IvyBridge   | 3        | 4.35%   |
| Zen+        | 2        | 2.9%    |
| K10         | 2        | 2.9%    |
| Skylake     | 1        | 1.45%   |
| Silvermont  | 1        | 1.45%   |
| Puma        | 1        | 1.45%   |
| Nehalem     | 1        | 1.45%   |
| K8 Hammer   | 1        | 1.45%   |
| Jaguar      | 1        | 1.45%   |
| CometLake   | 1        | 1.45%   |
| Bulldozer   | 1        | 1.45%   |
| Bonnell     | 1        | 1.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 28       | 40.58%  |
| AMD                        | 25       | 36.23%  |
| Intel                      | 14       | 20.29%  |
| Matrox Electronics Systems | 2        | 2.9%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6        | 8.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 4.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 2.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 2.78%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 2.78%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 2.78%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 2.78%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2        | 2.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 2.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 2.78%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2        | 2.78%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2        | 2.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 2.78%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 1.39%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1        | 1.39%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.39%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.39%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.39%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.39%   |
| Nvidia GK110GL [Quadro K5200]                                                            | 1        | 1.39%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 1.39%   |
| Nvidia GK104GL [Quadro K5000]                                                            | 1        | 1.39%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1        | 1.39%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1        | 1.39%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1        | 1.39%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1        | 1.39%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1        | 1.39%   |
| Nvidia G80GL [Quadro FX 4600]                                                            | 1        | 1.39%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1        | 1.39%   |
| Nvidia C79 [ION]                                                                         | 1        | 1.39%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 1.39%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1        | 1.39%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1        | 1.39%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.39%   |
| Intel HD Graphics 620                                                                    | 1        | 1.39%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.39%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.39%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 26       | 37.68%  |
| 1 x AMD        | 24       | 34.78%  |
| 1 x Intel      | 13       | 18.84%  |
| 1 x Matrox     | 2        | 2.9%    |
| Other          | 1        | 1.45%   |
| 2 x Nvidia     | 1        | 1.45%   |
| 2 x AMD        | 1        | 1.45%   |
| Intel + Nvidia | 1        | 1.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 43       | 62.32%  |
| Proprietary | 18       | 26.09%  |
| Unknown     | 8        | 11.59%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 39.13%  |
| 0.51-1.0   | 10       | 14.49%  |
| 3.01-4.0   | 8        | 11.59%  |
| 1.01-2.0   | 7        | 10.14%  |
| 7.01-8.0   | 6        | 8.7%    |
| 0.01-0.5   | 4        | 5.8%    |
| 8.01-16.0  | 3        | 4.35%   |
| 5.01-6.0   | 2        | 2.9%    |
| 2.01-3.0   | 1        | 1.45%   |
| 16.01-24.0 | 1        | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 10       | 14.71%  |
| Dell                    | 10       | 14.71%  |
| Hewlett-Packard         | 6        | 8.82%   |
| BenQ                    | 6        | 8.82%   |
| Goldstar                | 5        | 7.35%   |
| Ancor Communications    | 4        | 5.88%   |
| Acer                    | 4        | 5.88%   |
| ViewSonic               | 2        | 2.94%   |
| Lenovo                  | 2        | 2.94%   |
| ASUSTek Computer        | 2        | 2.94%   |
| AOC                     | 2        | 2.94%   |
| Xiaomi                  | 1        | 1.47%   |
| Wacom                   | 1        | 1.47%   |
| Unknown                 | 1        | 1.47%   |
| Toshiba                 | 1        | 1.47%   |
| ONN                     | 1        | 1.47%   |
| NEC Computers           | 1        | 1.47%   |
| JVC                     | 1        | 1.47%   |
| IOD                     | 1        | 1.47%   |
| Iiyama                  | 1        | 1.47%   |
| Gigabyte Technology     | 1        | 1.47%   |
| GDH                     | 1        | 1.47%   |
| Eizo                    | 1        | 1.47%   |
| CTC                     | 1        | 1.47%   |
| Chi Mei Optoelectronics | 1        | 1.47%   |
| Unknown                 | 1        | 1.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                   | 1        | 1.41%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch             | 1        | 1.41%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                        | 1        | 1.41%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                        | 1        | 1.41%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1        | 1.41%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 1        | 1.41%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch | 1        | 1.41%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                     | 1        | 1.41%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch | 1        | 1.41%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch | 1        | 1.41%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch | 1        | 1.41%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch   | 1        | 1.41%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch    | 1        | 1.41%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch    | 1        | 1.41%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch    | 1        | 1.41%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                    | 1        | 1.41%   |
| Samsung Electronics B2430L SAM0644 1920x1080 521x293mm 23.5-inch     | 1        | 1.41%   |
| ONN 100002480 ONN0101 1920x1080 470x290mm 21.7-inch                  | 1        | 1.41%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch      | 1        | 1.41%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                | 1        | 1.41%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 1        | 1.41%   |
| JVC FPDEUFT3 JVC21BE 1920x540                                        | 1        | 1.41%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                 | 1        | 1.41%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch               | 1        | 1.41%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch        | 1        | 1.41%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch           | 1        | 1.41%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch         | 1        | 1.41%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch         | 1        | 1.41%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch            | 1        | 1.41%   |
| Hewlett-Packard 2309 HWP2823 1920x1080 510x287mm 23.0-inch           | 1        | 1.41%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                 | 1        | 1.41%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                 | 1        | 1.41%   |
| Goldstar W1952 GSM4B77 1440x900 408x255mm 18.9-inch                  | 1        | 1.41%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch               | 1        | 1.41%   |
| Goldstar E1641 GSM8B3E 1366x768 344x194mm 15.5-inch                  | 1        | 1.41%   |
| Goldstar BK750Y GSM5B3E 1920x1080 600x340mm 27.2-inch                | 1        | 1.41%   |
| Goldstar BK750Y GSM5B3D 1920x1080 480x270mm 21.7-inch                | 1        | 1.41%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 600x330mm 27.0-inch       | 1        | 1.41%   |
| GDH Digital TV GDH0030 1440x900 1150x650mm 52.0-inch                 | 1        | 1.41%   |
| Eizo M1700 ENC1788 1280x1024 340x280mm 17.3-inch                     | 1        | 1.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 29       | 43.28%  |
| 1280x1024 (SXGA)   | 7        | 10.45%  |
| 2560x1440 (QHD)    | 5        | 7.46%   |
| 1680x1050 (WSXGA+) | 5        | 7.46%   |
| 1920x1200 (WUXGA)  | 4        | 5.97%   |
| 1366x768 (WXGA)    | 4        | 5.97%   |
| 3840x2160 (4K)     | 3        | 4.48%   |
| 3440x1440          | 2        | 2.99%   |
| 1440x900 (WXGA+)   | 2        | 2.99%   |
| 3200x1080          | 1        | 1.49%   |
| 2288x1287          | 1        | 1.49%   |
| 1920x540           | 1        | 1.49%   |
| 1600x1200          | 1        | 1.49%   |
| 1024x768 (XGA)     | 1        | 1.49%   |
| Unknown            | 1        | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 12       | 17.39%  |
| 27      | 10       | 14.49%  |
| 21      | 8        | 11.59%  |
| 23      | 7        | 10.14%  |
| Unknown | 7        | 10.14%  |
| 22      | 4        | 5.8%    |
| 19      | 4        | 5.8%    |
| 17      | 4        | 5.8%    |
| 15      | 4        | 5.8%    |
| 18      | 3        | 4.35%   |
| 20      | 2        | 2.9%    |
| 142     | 1        | 1.45%   |
| 74      | 1        | 1.45%   |
| 52      | 1        | 1.45%   |
| 34      | 1        | 1.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 27       | 39.71%  |
| 401-500        | 18       | 26.47%  |
| 301-350        | 8        | 11.76%  |
| Unknown        | 7        | 10.29%  |
| 351-400        | 3        | 4.41%   |
| More than 2000 | 1        | 1.47%   |
| 701-800        | 1        | 1.47%   |
| 601-700        | 1        | 1.47%   |
| 1501-2000      | 1        | 1.47%   |
| 1001-1500      | 1        | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 33       | 52.38%  |
| 16/10   | 12       | 19.05%  |
| 5/4     | 5        | 7.94%   |
| Unknown | 5        | 7.94%   |
| 6/5     | 2        | 3.17%   |
| 4/3     | 2        | 3.17%   |
| 32/9    | 1        | 1.59%   |
| 3/2     | 1        | 1.59%   |
| 21/9    | 1        | 1.59%   |
| 1.00    | 1        | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 24       | 35.82%  |
| 301-350        | 10       | 14.93%  |
| 151-200        | 7        | 10.45%  |
| Unknown        | 7        | 10.45%  |
| 141-150        | 6        | 8.96%   |
| 251-300        | 5        | 7.46%   |
| 101-110        | 4        | 5.97%   |
| More than 1000 | 3        | 4.48%   |
| 351-500        | 1        | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 40       | 57.97%  |
| 101-120 | 15       | 21.74%  |
| Unknown | 7        | 10.14%  |
| 121-160 | 4        | 5.8%    |
| 1-50    | 3        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 47       | 68.12%  |
| 0     | 10       | 14.49%  |
| 2     | 9        | 13.04%  |
| 3     | 3        | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 36       | 37.5%   |
| Intel                    | 33       | 34.38%  |
| Qualcomm Atheros         | 5        | 5.21%   |
| Nvidia                   | 4        | 4.17%   |
| Broadcom                 | 4        | 4.17%   |
| TP-Link                  | 3        | 3.13%   |
| Ralink Technology        | 3        | 3.13%   |
| VIA Technologies         | 1        | 1.04%   |
| Ralink                   | 1        | 1.04%   |
| Qualcomm                 | 1        | 1.04%   |
| Micro Star International | 1        | 1.04%   |
| Mellanox Technologies    | 1        | 1.04%   |
| Dell                     | 1        | 1.04%   |
| Chelsio Communications   | 1        | 1.04%   |
| Broadcom Limited         | 1        | 1.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 26       | 23.21%  |
| Intel I211 Gigabit Network Connection                                      | 7        | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 4        | 3.57%   |
| Intel Ethernet Connection (2) I218-V                                       | 4        | 3.57%   |
| Intel 82574L Gigabit Network Connection                                    | 4        | 3.57%   |
| Ralink MT7601U Wireless Adapter                                            | 3        | 2.68%   |
| Nvidia MCP61 Ethernet                                                      | 3        | 2.68%   |
| Intel Wi-Fi 6 AX200                                                        | 3        | 2.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 3        | 2.68%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 2        | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                          | 2        | 1.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 1.79%   |
| Intel I350 Gigabit Network Connection                                      | 2        | 1.79%   |
| Intel Ethernet Controller I225-V                                           | 2        | 1.79%   |
| Intel Ethernet Connection (7) I219-V                                       | 2        | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2        | 1.79%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 1.79%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 1.79%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                    | 2        | 1.79%   |
| VIA VT6105/VT6106S [Rhine-III]                                             | 1        | 0.89%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 1        | 0.89%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                      | 1        | 0.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1        | 0.89%   |
| Realtek USB 10/100/1G/2.5G LAN                                             | 1        | 0.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 1        | 0.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.89%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1        | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.89%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1        | 0.89%   |
| Qualcomm Nokia G400 5G                                                     | 1        | 0.89%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 1        | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 0.89%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 0.89%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.89%   |
| Nvidia MCP79 Ethernet                                                      | 1        | 0.89%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 0.89%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                      | 1        | 0.89%   |
| Intel Wireless-AC 9260                                                     | 1        | 0.89%   |
| Intel Wireless 7260                                                        | 1        | 0.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 1        | 0.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 9        | 34.62%  |
| Realtek Semiconductor    | 5        | 19.23%  |
| TP-Link                  | 3        | 11.54%  |
| Ralink Technology        | 3        | 11.54%  |
| Qualcomm Atheros         | 3        | 11.54%  |
| Ralink                   | 1        | 3.85%   |
| Micro Star International | 1        | 3.85%   |
| Dell                     | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                            | 3        | 11.54%  |
| Intel Wi-Fi 6 AX200                                                        | 3        | 11.54%  |
| Realtek RTL8188EE Wireless Network Adapter                                 | 2        | 7.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2        | 7.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 1        | 3.85%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                      | 1        | 3.85%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1        | 3.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 1        | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 3.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1        | 3.85%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1        | 3.85%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 1        | 3.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 3.85%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 3.85%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 3.85%   |
| Intel Wireless-AC 9260                                                     | 1        | 3.85%   |
| Intel Wireless 7260                                                        | 1        | 3.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 1        | 3.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 1        | 3.85%   |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887]      | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Realtek Semiconductor  | 34       | 42.5%   |
| Intel                  | 30       | 37.5%   |
| Nvidia                 | 4        | 5%      |
| Broadcom               | 4        | 5%      |
| Qualcomm Atheros       | 3        | 3.75%   |
| VIA Technologies       | 1        | 1.25%   |
| Qualcomm               | 1        | 1.25%   |
| Mellanox Technologies  | 1        | 1.25%   |
| Chelsio Communications | 1        | 1.25%   |
| Broadcom Limited       | 1        | 1.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 26       | 30.23%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 8.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 4.65%   |
| Intel Ethernet Connection (2) I218-V                                          | 4        | 4.65%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 4.65%   |
| Nvidia MCP61 Ethernet                                                         | 3        | 3.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 3.49%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 2.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 2.33%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 2.33%   |
| Intel Ethernet Controller I225-V                                              | 2        | 2.33%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 2.33%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 2.33%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 2.33%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 2        | 2.33%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 1.16%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1        | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 1.16%   |
| Qualcomm Nokia G400 5G                                                        | 1        | 1.16%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 1.16%   |
| Nvidia MCP79 Ethernet                                                         | 1        | 1.16%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 1.16%   |
| Intel Ethernet Connection I217-V                                              | 1        | 1.16%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 1.16%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 1.16%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 1.16%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 1.16%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 1.16%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.16%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 1.16%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1        | 1.16%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 1.16%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 1        | 1.16%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 1.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 69       | 72.63%  |
| WiFi     | 26       | 27.37%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 57       | 83.82%  |
| WiFi     | 11       | 16.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 41       | 57.75%  |
| 2     | 19       | 26.76%  |
| 3     | 5        | 7.04%   |
| 4     | 3        | 4.23%   |
| 5     | 2        | 2.82%   |
| 0     | 1        | 1.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 62       | 87.32%  |
| Yes  | 9        | 12.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Cambridge Silicon Radio  | 12       | 46.15%  |
| Intel                    | 8        | 30.77%  |
| Micro Star International | 2        | 7.69%   |
| TP-Link                  | 1        | 3.85%   |
| Realtek Semiconductor    | 1        | 3.85%   |
| MediaTek                 | 1        | 3.85%   |
| Broadcom                 | 1        | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12       | 46.15%  |
| Intel AX200 Bluetooth                               | 3        | 11.54%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 7.69%   |
| TP-Link UB500 Adapter                               | 1        | 3.85%   |
| Realtek Bluetooth Radio                             | 1        | 3.85%   |
| Micro Star International Bluetooth Dongle           | 1        | 3.85%   |
| Micro Star International Bluetooth Device           | 1        | 3.85%   |
| MediaTek Wireless_Device                            | 1        | 3.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.85%   |
| Intel Bluetooth wireless interface                  | 1        | 3.85%   |
| Intel AX210 Bluetooth                               | 1        | 3.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Intel                | 32       | 30.77%  |
| AMD                  | 32       | 30.77%  |
| Nvidia               | 24       | 23.08%  |
| Creative Labs        | 7        | 6.73%   |
| VIA Technologies     | 1        | 0.96%   |
| Texas Instruments    | 1        | 0.96%   |
| RME                  | 1        | 0.96%   |
| M-Audio              | 1        | 0.96%   |
| Kingston Technology  | 1        | 0.96%   |
| Holtek Semiconductor | 1        | 0.96%   |
| EGO SYStems          | 1        | 0.96%   |
| C-Media Electronics  | 1        | 0.96%   |
| ASUSTek Computer     | 1        | 0.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 11       | 8.53%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                  | 6        | 4.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 6        | 4.65%   |
| Nvidia MCP61 High Definition Audio                                                              | 4        | 3.1%    |
| Nvidia GP106 High Definition Audio Controller                                                   | 4        | 3.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 4        | 3.1%    |
| AMD FCH Azalia Controller                                                                       | 4        | 3.1%    |
| AMD Family 17h/19h HD Audio Controller                                                          | 4        | 3.1%    |
| Nvidia GP107GL High Definition Audio Controller                                                 | 3        | 2.33%   |
| Nvidia GF108 High Definition Audio Controller                                                   | 3        | 2.33%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 3        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 3        | 2.33%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 3        | 2.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 3        | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 3        | 2.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 3        | 2.33%   |
| AMD Navi 10 HDMI Audio                                                                          | 3        | 2.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 3        | 2.33%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 2        | 1.55%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 2        | 1.55%   |
| Intel Cannon Lake PCH cAVS                                                                      | 2        | 1.55%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 2        | 1.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2        | 1.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 2        | 1.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 2        | 1.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 2        | 1.55%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 2        | 1.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 2        | 1.55%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                     | 1        | 0.78%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 1        | 0.78%   |
| RME ADI-2 DAC (58825307)                                                                        | 1        | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 1        | 0.78%   |
| Nvidia MCP79 High Definition Audio                                                              | 1        | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 1        | 0.78%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 1        | 0.78%   |
| Nvidia GM204 High Definition Audio Controller                                                   | 1        | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 1        | 0.78%   |
| Nvidia GK110 High Definition Audio Controller                                                   | 1        | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 1        | 0.78%   |
| Nvidia GK104 HDMI Audio Controller                                                              | 1        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 15       | 20%     |
| Corsair             | 12       | 16%     |
| Unknown             | 7        | 9.33%   |
| SK hynix            | 7        | 9.33%   |
| Samsung Electronics | 6        | 8%      |
| Crucial             | 6        | 8%      |
| Team                | 4        | 5.33%   |
| G.Skill             | 3        | 4%      |
| Transcend           | 2        | 2.67%   |
| Micron Technology   | 2        | 2.67%   |
| Unknown             | 2        | 2.67%   |
| Strontium           | 1        | 1.33%   |
| Smart               | 1        | 1.33%   |
| Silicon Power       | 1        | 1.33%   |
| Patriot             | 1        | 1.33%   |
| HPE                 | 1        | 1.33%   |
| GLOWAY              | 1        | 1.33%   |
| AMD                 | 1        | 1.33%   |
| A-DATA Technology   | 1        | 1.33%   |
| A Force             | 1        | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                        | 2        | 2.41%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s          | 2        | 2.41%   |
| Corsair RAM CMZ32GX3M4X1600C10 8GB DIMM DDR3 1600MT/s       | 2        | 2.41%   |
| Unknown                                                     | 2        | 2.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                   | 1        | 1.2%    |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s               | 1        | 1.2%    |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                    | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                  | 1        | 1.2%    |
| Unknown RAM Module 2048MB DIMM 667MT/s                      | 1        | 1.2%    |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1        | 1.2%    |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1        | 1.2%    |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s           | 1        | 1.2%    |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s       | 1        | 1.2%    |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s          | 1        | 1.2%    |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s          | 1        | 1.2%    |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s       | 1        | 1.2%    |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s         | 1        | 1.2%    |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s | 1        | 1.2%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1        | 1.2%    |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s        | 1        | 1.2%    |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s        | 1        | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1        | 1.2%    |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1        | 1.2%    |
| SK hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s        | 1        | 1.2%    |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s   | 1        | 1.2%    |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s    | 1        | 1.2%    |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1        | 1.2%    |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s         | 1        | 1.2%    |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s        | 1        | 1.2%    |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 1.2%    |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s         | 1        | 1.2%    |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s         | 1        | 1.2%    |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s             | 1        | 1.2%    |
| Micron RAM 36KSF1G72PZ-1G4K1 8GB DIMM DDR3 1333MT/s         | 1        | 1.2%    |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s         | 1        | 1.2%    |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s        | 1        | 1.2%    |
| Kingston RAM Module 2048MB FB-DIMM DDR2 667MT/s             | 1        | 1.2%    |
| Kingston RAM KHX3600C17D4/8GX 8GB DIMM DDR4 3600MT/s        | 1        | 1.2%    |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s        | 1        | 1.2%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s        | 1        | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 29       | 45.31%  |
| DDR3    | 27       | 42.19%  |
| DDR2    | 4        | 6.25%   |
| SDRAM   | 2        | 3.13%   |
| DDR     | 1        | 1.56%   |
| Unknown | 1        | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 60       | 92.31%  |
| SODIMM  | 3        | 4.62%   |
| RIMM    | 1        | 1.54%   |
| FB-DIMM | 1        | 1.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 27       | 38.57%  |
| 4096  | 17       | 24.29%  |
| 16384 | 9        | 12.86%  |
| 2048  | 7        | 10%     |
| 32768 | 6        | 8.57%   |
| 1024  | 4        | 5.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 22.54%  |
| 3600    | 8        | 11.27%  |
| 2400    | 6        | 8.45%   |
| 1333    | 5        | 7.04%   |
| 3200    | 4        | 5.63%   |
| 667     | 4        | 5.63%   |
| 3800    | 3        | 4.23%   |
| 2800    | 2        | 2.82%   |
| 2667    | 2        | 2.82%   |
| 2666    | 2        | 2.82%   |
| 2133    | 2        | 2.82%   |
| 1867    | 2        | 2.82%   |
| 1866    | 2        | 2.82%   |
| Unknown | 2        | 2.82%   |
| 65535   | 1        | 1.41%   |
| 3733    | 1        | 1.41%   |
| 3400    | 1        | 1.41%   |
| 2933    | 1        | 1.41%   |
| 2472    | 1        | 1.41%   |
| 2187    | 1        | 1.41%   |
| 2000    | 1        | 1.41%   |
| 1066    | 1        | 1.41%   |
| 975     | 1        | 1.41%   |
| 800     | 1        | 1.41%   |
| 533     | 1        | 1.41%   |

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
| Seiko Epson     | 1        | 33.33%  |
| Hewlett-Packard | 1        | 33.33%  |
| Canon           | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 33.33%  |
| HP ScanJet 5590                               | 1        | 33.33%  |
| Canon CanoScan LIDE 25                        | 1        | 33.33%  |

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


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech Webcam C270            | 3        | 18.75%  |
| Z-Star Vimicro USB2.0 Camera    | 1        | 6.25%   |
| Samsung Galaxy A5 (MTP)         | 1        | 6.25%   |
| Microsoft LifeCam HD-3000       | 1        | 6.25%   |
| Microdia Camera                 | 1        | 6.25%   |
| Logitech Webcam C310            | 1        | 6.25%   |
| Logitech Webcam C300            | 1        | 6.25%   |
| Logitech Webcam C170            | 1        | 6.25%   |
| Logitech QuickCam Pro 9000      | 1        | 6.25%   |
| Logitech Logitech Webcam C160   | 1        | 6.25%   |
| Logitech HD Webcam C910         | 1        | 6.25%   |
| Logitech HD Webcam C525         | 1        | 6.25%   |
| Logitech HD Pro Webcam C920     | 1        | 6.25%   |
| Logitech C922 Pro Stream Webcam | 1        | 6.25%   |

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
| 0     | 44       | 63.77%  |
| 1     | 12       | 17.39%  |
| 4     | 5        | 7.25%   |
| 2     | 4        | 5.8%    |
| 3     | 3        | 4.35%   |
| 5     | 1        | 1.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 13       | 27.08%  |
| Graphics card            | 9        | 18.75%  |
| Communication controller | 7        | 14.58%  |
| Net/wireless             | 5        | 10.42%  |
| Unassigned class         | 4        | 8.33%   |
| Camera                   | 2        | 4.17%   |
| Bluetooth                | 2        | 4.17%   |
| Storage/ide              | 1        | 2.08%   |
| Storage/ata              | 1        | 2.08%   |
| Net/ethernet             | 1        | 2.08%   |
| Fingerprint reader       | 1        | 2.08%   |
| Chipcard                 | 1        | 2.08%   |
| Card reader              | 1        | 2.08%   |

