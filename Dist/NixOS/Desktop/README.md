NixOS - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for NixOS.

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
| AZW           | EQ                          | [4a9aad33f3](https://linux-hardware.org/?probe=4a9aad33f3) | Aug 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | [1abcf2ad6f](https://linux-hardware.org/?probe=1abcf2ad6f) | Aug 04, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [959f3b36df](https://linux-hardware.org/?probe=959f3b36df) | Jul 26, 2023 |
| HP            | 1998                        | [ef5201611b](https://linux-hardware.org/?probe=ef5201611b) | Jul 24, 2023 |
| HP            | 1998                        | [5a95ac128d](https://linux-hardware.org/?probe=5a95ac128d) | Jul 24, 2023 |
| AZW           | EQ                          | [e065c16f2c](https://linux-hardware.org/?probe=e065c16f2c) | Jul 23, 2023 |
| AZW           | EQ                          | [46a76eeb81](https://linux-hardware.org/?probe=46a76eeb81) | Jul 23, 2023 |
| ASUSTek       | Z87-EXPERT                  | [1e8eeb8513](https://linux-hardware.org/?probe=1e8eeb8513) | Jul 16, 2023 |
| ASUSTek       | Z87-EXPERT                  | [8efa3cf99d](https://linux-hardware.org/?probe=8efa3cf99d) | Jul 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d7afc91d12](https://linux-hardware.org/?probe=d7afc91d12) | Jul 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [a2dc9efa21](https://linux-hardware.org/?probe=a2dc9efa21) | Jul 06, 2023 |
| Gigabyte      | TRX40 AORUS MASTER          | [f1c343e2c2](https://linux-hardware.org/?probe=f1c343e2c2) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [f15cf1d31b](https://linux-hardware.org/?probe=f15cf1d31b) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [85902981fd](https://linux-hardware.org/?probe=85902981fd) | Jun 11, 2023 |
| Acer          | Aspire XC600 v1.0           | [754d228b9b](https://linux-hardware.org/?probe=754d228b9b) | Jun 09, 2023 |
| Gigabyte      | X570 AORUS PRO              | [309d09ae8c](https://linux-hardware.org/?probe=309d09ae8c) | Jun 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c9c4e5ddb5](https://linux-hardware.org/?probe=c9c4e5ddb5) | May 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | [cc8e36e75a](https://linux-hardware.org/?probe=cc8e36e75a) | May 26, 2023 |
| ASUSTek       | PRIME Z370-P II             | [4d84deed6b](https://linux-hardware.org/?probe=4d84deed6b) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [29b2378b4b](https://linux-hardware.org/?probe=29b2378b4b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [62b28b69dc](https://linux-hardware.org/?probe=62b28b69dc) | May 08, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | [6ee65c19d2](https://linux-hardware.org/?probe=6ee65c19d2) | May 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [493bc0b894](https://linux-hardware.org/?probe=493bc0b894) | Apr 29, 2023 |
| ASUSTek       | PRIME B350M-A               | [b8b51b29ef](https://linux-hardware.org/?probe=b8b51b29ef) | Apr 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [bbbc9206b4](https://linux-hardware.org/?probe=bbbc9206b4) | Apr 17, 2023 |
| MSI           | B550-A PRO                  | [c4f08a9fc3](https://linux-hardware.org/?probe=c4f08a9fc3) | Mar 04, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c4d51ca1b8](https://linux-hardware.org/?probe=c4d51ca1b8) | Mar 04, 2023 |
| MSI           | Z77A-G43                    | [eb768bf205](https://linux-hardware.org/?probe=eb768bf205) | Feb 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [75a3416ebc](https://linux-hardware.org/?probe=75a3416ebc) | Jan 31, 2023 |
| ASRock        | Z87 Extreme4                | [b795f7c940](https://linux-hardware.org/?probe=b795f7c940) | Jan 19, 2023 |
| ASRock        | B550M Pro4                  | [0e4ba05b0f](https://linux-hardware.org/?probe=0e4ba05b0f) | Jan 15, 2023 |
| Shenzhen M... | F7BFC                       | [6a53c626dd](https://linux-hardware.org/?probe=6a53c626dd) | Jan 02, 2023 |
| ASUSTek       | Z87-C                       | [4929f6a6c9](https://linux-hardware.org/?probe=4929f6a6c9) | Dec 28, 2022 |
| MSI           | B550-A PRO                  | [db7b91ac2f](https://linux-hardware.org/?probe=db7b91ac2f) | Dec 17, 2022 |
| ASUSTek       | PRIME B550M-A               | [3c18fca709](https://linux-hardware.org/?probe=3c18fca709) | Dec 09, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| ASUSTek       | PRIME B550M-A               | [c203d7c388](https://linux-hardware.org/?probe=c203d7c388) | Oct 07, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| ASUSTek       | PRIME B550M-A               | [98fd9b974e](https://linux-hardware.org/?probe=98fd9b974e) | Sep 09, 2022 |
| ASRock        | AB350 Pro4                  | [ce872c873e](https://linux-hardware.org/?probe=ce872c873e) | Aug 24, 2022 |
| ASUSTek       | H97I-PLUS                   | [982df0dba9](https://linux-hardware.org/?probe=982df0dba9) | Jun 22, 2022 |
| MSI           | MEG X570 UNIFY              | [6d5fdb800a](https://linux-hardware.org/?probe=6d5fdb800a) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| MSI           | MEG X570 UNIFY              | [d26f08ea88](https://linux-hardware.org/?probe=d26f08ea88) | Jun 12, 2022 |
| MSI           | MEG X570 UNIFY              | [0123caa2f3](https://linux-hardware.org/?probe=0123caa2f3) | Jun 11, 2022 |
| ASUSTek       | PRIME A520M-K               | [ab13de0478](https://linux-hardware.org/?probe=ab13de0478) | May 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [96b24b0640](https://linux-hardware.org/?probe=96b24b0640) | May 20, 2022 |
| ASUSTek       | PRIME X570-P                | [50d2e86de8](https://linux-hardware.org/?probe=50d2e86de8) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | [46b46c842f](https://linux-hardware.org/?probe=46b46c842f) | Apr 13, 2022 |
| ASUSTek       | P8Q77-M                     | [6cd75b6762](https://linux-hardware.org/?probe=6cd75b6762) | Mar 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [815cb9ab49](https://linux-hardware.org/?probe=815cb9ab49) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | [1d6563ada3](https://linux-hardware.org/?probe=1d6563ada3) | Mar 11, 2022 |
| ASUSTek       | P8Z77-V LK                  | [5c984c6d9a](https://linux-hardware.org/?probe=5c984c6d9a) | Mar 09, 2022 |
| ASUSTek       | P8Z77-V LK                  | [40d2eced72](https://linux-hardware.org/?probe=40d2eced72) | Mar 09, 2022 |
| EVGA          | X299 FTW K                  | [6f9489b2e6](https://linux-hardware.org/?probe=6f9489b2e6) | Mar 09, 2022 |
| Dell          | 0KJCC5 A00                  | [524b675e7e](https://linux-hardware.org/?probe=524b675e7e) | Mar 09, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f38279e396](https://linux-hardware.org/?probe=f38279e396) | Mar 09, 2022 |
| MSI           | X399 SLI PLUS               | [a1d172dbc0](https://linux-hardware.org/?probe=a1d172dbc0) | Feb 16, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [c84b603f92](https://linux-hardware.org/?probe=c84b603f92) | Jan 04, 2022 |
| ASUSTek       | Z170-P                      | [d4bac456d1](https://linux-hardware.org/?probe=d4bac456d1) | Dec 16, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| ASUSTek       | PRIME Z390-A                | [af887c3f7b](https://linux-hardware.org/?probe=af887c3f7b) | Nov 29, 2021 |
| Gigabyte      | H97M-D3H                    | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| MSI           | X399 SLI PLUS               | [128ae965a7](https://linux-hardware.org/?probe=128ae965a7) | Aug 06, 2021 |
| ASRock        | X570 Taichi                 | [d93a80d973](https://linux-hardware.org/?probe=d93a80d973) | Jul 14, 2021 |
| ASRock        | X570 Taichi                 | [59a699d357](https://linux-hardware.org/?probe=59a699d357) | Jul 14, 2021 |
| ASUSTek       | SABERTOOTH X99              | [60eed45305](https://linux-hardware.org/?probe=60eed45305) | Jun 18, 2021 |
| MSI           | X570-A PRO                  | [0619809b36](https://linux-hardware.org/?probe=0619809b36) | Jun 01, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f03b19461f](https://linux-hardware.org/?probe=f03b19461f) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [529e915984](https://linux-hardware.org/?probe=529e915984) | May 16, 2021 |
| ASUSTek       | Pro WS W480-ACE             | [3825190816](https://linux-hardware.org/?probe=3825190816) | Mar 11, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d55d51a3e2](https://linux-hardware.org/?probe=d55d51a3e2) | Feb 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [188755ebc7](https://linux-hardware.org/?probe=188755ebc7) | Oct 25, 2020 |
| Hardkernel    | ODROID-H2                   | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b85fb81c59](https://linux-hardware.org/?probe=b85fb81c59) | Sep 28, 2020 |
| MSI           | MAG B550M BAZOOKA           | [5f7f2db973](https://linux-hardware.org/?probe=5f7f2db973) | Aug 21, 2020 |
| ASUSTek       | PRIME Z270-K                | [cc8de41afd](https://linux-hardware.org/?probe=cc8de41afd) | Aug 21, 2020 |
| HP            | 8055                        | [1165b457fa](https://linux-hardware.org/?probe=1165b457fa) | Jul 08, 2020 |
| HP            | 8055                        | [a5c65e8d4a](https://linux-hardware.org/?probe=a5c65e8d4a) | Jul 08, 2020 |
| ASRock        | TRX40 Creator               | [2cefd65bfb](https://linux-hardware.org/?probe=2cefd65bfb) | Jun 29, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| NixOS 22.05                      | 13       | 19.4%   |
| NixOS 23.05                      | 12       | 17.91%  |
| NixOS 22.11                      | 12       | 17.91%  |
| NixOS 21.11                      | 7        | 10.45%  |
| NixOS 23.11                      | 5        | 7.46%   |
| NixOS                            | 3        | 4.48%   |
| NixOS 21.05pre-git               | 2        | 2.99%   |
| NixOS 21.11.20210528.540dccb     | 1        | 1.49%   |
| NixOS 21.05.993.93963c27b93      | 1        | 1.49%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1        | 1.49%   |
| NixOS 21.05.20210929.ee90403     | 1        | 1.49%   |
| NixOS 21.05.20210430.c8dff32     | 1        | 1.49%   |
| NixOS 21.05.20210224.f6b5bfd     | 1        | 1.49%   |
| NixOS 21.05.1471.a7512bb64b1     | 1        | 1.49%   |
| NixOS 21.03pre246062.420f89ceb26 | 1        | 1.49%   |
| NixOS 21.03.git.b4349c13a6d      | 1        | 1.49%   |
| NixOS 21.03.20201007.420f89c     | 1        | 1.49%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1        | 1.49%   |
| NixOS 20.09pre-git               | 1        | 1.49%   |
| NixOS 20.09.git.4a361b06a93      | 1        | 1.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| NixOS | 62       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Desktops | Percent |
|----------------|----------|---------|
| 6.4.7          | 2        | 2.86%   |
| 6.4.0          | 2        | 2.86%   |
| 6.1.37         | 2        | 2.86%   |
| 5.8.1-zen1     | 2        | 2.86%   |
| 5.15.86        | 2        | 2.86%   |
| 5.15.85        | 2        | 2.86%   |
| 5.15.47        | 2        | 2.86%   |
| 5.10.102       | 2        | 2.86%   |
| 6.4.4-cachyos  | 1        | 1.43%   |
| 6.4.4          | 1        | 1.43%   |
| 6.3.3          | 1        | 1.43%   |
| 6.2.11-lqx3    | 1        | 1.43%   |
| 6.2.11         | 1        | 1.43%   |
| 6.2.10         | 1        | 1.43%   |
| 6.1.39         | 1        | 1.43%   |
| 6.1.31-xanmod1 | 1        | 1.43%   |
| 6.1.31         | 1        | 1.43%   |
| 6.1.27         | 1        | 1.43%   |
| 6.1.24         | 1        | 1.43%   |
| 6.1.14         | 1        | 1.43%   |
| 6.0.12         | 1        | 1.43%   |
| 6.0.11         | 1        | 1.43%   |
| 5.8.10         | 1        | 1.43%   |
| 5.7.19         | 1        | 1.43%   |
| 5.4.94         | 1        | 1.43%   |
| 5.4.72         | 1        | 1.43%   |
| 5.4.69         | 1        | 1.43%   |
| 5.4.50         | 1        | 1.43%   |
| 5.4.47         | 1        | 1.43%   |
| 5.19.14        | 1        | 1.43%   |
| 5.18.19        | 1        | 1.43%   |
| 5.18.14-lqx2   | 1        | 1.43%   |
| 5.17.1         | 1        | 1.43%   |
| 5.16.8-zen1    | 1        | 1.43%   |
| 5.15.95        | 1        | 1.43%   |
| 5.15.90        | 1        | 1.43%   |
| 5.15.83        | 1        | 1.43%   |
| 5.15.74        | 1        | 1.43%   |
| 5.15.7         | 1        | 1.43%   |
| 5.15.50        | 1        | 1.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 6.4.7    | 2        | 2.86%   |
| 6.4.4    | 2        | 2.86%   |
| 6.4.0    | 2        | 2.86%   |
| 6.2.11   | 2        | 2.86%   |
| 6.1.37   | 2        | 2.86%   |
| 6.1.31   | 2        | 2.86%   |
| 5.8.1    | 2        | 2.86%   |
| 5.15.86  | 2        | 2.86%   |
| 5.15.85  | 2        | 2.86%   |
| 5.15.47  | 2        | 2.86%   |
| 5.11.16  | 2        | 2.86%   |
| 5.10.102 | 2        | 2.86%   |
| 6.3.3    | 1        | 1.43%   |
| 6.2.10   | 1        | 1.43%   |
| 6.1.39   | 1        | 1.43%   |
| 6.1.27   | 1        | 1.43%   |
| 6.1.24   | 1        | 1.43%   |
| 6.1.14   | 1        | 1.43%   |
| 6.0.12   | 1        | 1.43%   |
| 6.0.11   | 1        | 1.43%   |
| 5.8.10   | 1        | 1.43%   |
| 5.7.19   | 1        | 1.43%   |
| 5.4.94   | 1        | 1.43%   |
| 5.4.72   | 1        | 1.43%   |
| 5.4.69   | 1        | 1.43%   |
| 5.4.50   | 1        | 1.43%   |
| 5.4.47   | 1        | 1.43%   |
| 5.19.14  | 1        | 1.43%   |
| 5.18.19  | 1        | 1.43%   |
| 5.18.14  | 1        | 1.43%   |
| 5.17.1   | 1        | 1.43%   |
| 5.16.8   | 1        | 1.43%   |
| 5.15.95  | 1        | 1.43%   |
| 5.15.90  | 1        | 1.43%   |
| 5.15.83  | 1        | 1.43%   |
| 5.15.74  | 1        | 1.43%   |
| 5.15.7   | 1        | 1.43%   |
| 5.15.50  | 1        | 1.43%   |
| 5.15.43  | 1        | 1.43%   |
| 5.15.39  | 1        | 1.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 22       | 32.35%  |
| 5.10    | 9        | 13.24%  |
| 6.1     | 8        | 11.76%  |
| 5.4     | 5        | 7.35%   |
| 6.4     | 4        | 5.88%   |
| 6.2     | 3        | 4.41%   |
| 5.8     | 3        | 4.41%   |
| 6.0     | 2        | 2.94%   |
| 5.18    | 2        | 2.94%   |
| 5.11    | 2        | 2.94%   |
| 6.3     | 1        | 1.47%   |
| 5.7     | 1        | 1.47%   |
| 5.19    | 1        | 1.47%   |
| 5.17    | 1        | 1.47%   |
| 5.16    | 1        | 1.47%   |
| 5.14    | 1        | 1.47%   |
| 5.13    | 1        | 1.47%   |
| 5.12    | 1        | 1.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 62       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Unknown      | 33       | 52.38%  |
| GNOME        | 8        | 12.7%   |
| KDE5         | 6        | 9.52%   |
| XFCE         | 3        | 4.76%   |
| sway         | 3        | 4.76%   |
| KDE          | 3        | 4.76%   |
| Hyprland     | 3        | 4.76%   |
| none+awesome | 2        | 3.17%   |
| none+i3      | 1        | 1.59%   |
| MATE         | 1        | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 32       | 50.79%  |
| X11     | 17       | 26.98%  |
| Wayland | 10       | 15.87%  |
| Tty     | 4        | 6.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 37       | 58.73%  |
| LightDM | 10       | 15.87%  |
| SDDM    | 8        | 12.7%   |
| GDM     | 8        | 12.7%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 26       | 41.94%  |
| Unknown    | 21       | 33.87%  |
| en_GB      | 4        | 6.45%   |
| en_AU      | 3        | 4.84%   |
| en_DK      | 2        | 3.23%   |
| ru_RU      | 1        | 1.61%   |
| pt_BR      | 1        | 1.61%   |
| it_IT      | 1        | 1.61%   |
| en_IE.UTF8 | 1        | 1.61%   |
| de_DE      | 1        | 1.61%   |
| de_CH      | 1        | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 53       | 84.13%  |
| BIOS | 10       | 15.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 35       | 56.45%  |
| Btrfs   | 8        | 12.9%   |
| Zfs     | 6        | 9.68%   |
| Tmpfs   | 5        | 8.06%   |
| Xfs     | 4        | 6.45%   |
| Unknown | 3        | 4.84%   |
| Ext2    | 1        | 1.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 59       | 95.16%  |
| Unknown | 2        | 3.23%   |
| MBR     | 1        | 1.61%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 70.31%  |
| Yes       | 19       | 29.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 57.14%  |
| Yes       | 27       | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 24       | 38.71%  |
| MSI                                  | 11       | 17.74%  |
| Gigabyte Technology                  | 11       | 17.74%  |
| ASRock                               | 6        | 9.68%   |
| Acer                                 | 3        | 4.84%   |
| Hewlett-Packard                      | 2        | 3.23%   |
| Shenzhen Meigao Electronic Equipment | 1        | 1.61%   |
| Hardkernel                           | 1        | 1.61%   |
| EVGA                                 | 1        | 1.61%   |
| Dell                                 | 1        | 1.61%   |
| AZW                                  | 1        | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 3        | 4.84%   |
| MSI MS-7C56                                | 2        | 3.23%   |
| MSI MS-7C37                                | 2        | 3.23%   |
| Gigabyte B550I AORUS PRO AX                | 2        | 3.23%   |
| Gigabyte B450M DS3H                        | 2        | 3.23%   |
| ASUS ROG STRIX B550-F GAMING               | 2        | 3.23%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.61%   |
| MSI MS-7C95                                | 1        | 1.61%   |
| MSI MS-7C91                                | 1        | 1.61%   |
| MSI MS-7C84                                | 1        | 1.61%   |
| MSI MS-7C35                                | 1        | 1.61%   |
| MSI MS-7B89                                | 1        | 1.61%   |
| MSI MS-7B09                                | 1        | 1.61%   |
| MSI MS-7758                                | 1        | 1.61%   |
| HP EliteDesk 800 G2 DM 35W                 | 1        | 1.61%   |
| HP EliteDesk 800 G1 SFF                    | 1        | 1.61%   |
| Hardkernel ODROID-H2                       | 1        | 1.61%   |
| Gigabyte X570 AORUS PRO                    | 1        | 1.61%   |
| Gigabyte X570 AORUS ELITE                  | 1        | 1.61%   |
| Gigabyte X470 AORUS ULTRA GAMING           | 1        | 1.61%   |
| Gigabyte TRX40 AORUS MASTER                | 1        | 1.61%   |
| Gigabyte H97M-D3H                          | 1        | 1.61%   |
| Gigabyte B760 GAMING X DDR4                | 1        | 1.61%   |
| Gigabyte B450M DS3H V2                     | 1        | 1.61%   |
| EVGA X299 FTW K                            | 1        | 1.61%   |
| Dell Precision Tower 7810                  | 1        | 1.61%   |
| AZW EQ                                     | 1        | 1.61%   |
| ASUS Z170-P                                | 1        | 1.61%   |
| ASUS TUF Gaming X570-PLUS                  | 1        | 1.61%   |
| ASUS TUF Gaming B660-PLUS WIFI D4          | 1        | 1.61%   |
| ASUS SABERTOOTH 990FX R2.0                 | 1        | 1.61%   |
| ASUS ROG STRIX Z390-F GAMING               | 1        | 1.61%   |
| ASUS ROG STRIX B650E-F GAMING WIFI         | 1        | 1.61%   |
| ASUS ROG STRIX B550-I GAMING               | 1        | 1.61%   |
| ASUS PRO602617                             | 1        | 1.61%   |
| ASUS PRO-Q77 IU                            | 1        | 1.61%   |
| ASUS Pro WS W480-ACE                       | 1        | 1.61%   |
| ASUS PRIME Z390-A                          | 1        | 1.61%   |
| ASUS PRIME Z370-P II                       | 1        | 1.61%   |
| ASUS PRIME Z270-K                          | 1        | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 8        | 12.9%   |
| ASUS ROG                                   | 5        | 8.06%   |
| Gigabyte B450M                             | 3        | 4.84%   |
| ASUS All                                   | 3        | 4.84%   |
| MSI MS-7C56                                | 2        | 3.23%   |
| MSI MS-7C37                                | 2        | 3.23%   |
| HP EliteDesk                               | 2        | 3.23%   |
| Gigabyte X570                              | 2        | 3.23%   |
| Gigabyte B550I                             | 2        | 3.23%   |
| ASUS TUF                                   | 2        | 3.23%   |
| Acer Aspire                                | 2        | 3.23%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.61%   |
| MSI MS-7C95                                | 1        | 1.61%   |
| MSI MS-7C91                                | 1        | 1.61%   |
| MSI MS-7C84                                | 1        | 1.61%   |
| MSI MS-7C35                                | 1        | 1.61%   |
| MSI MS-7B89                                | 1        | 1.61%   |
| MSI MS-7B09                                | 1        | 1.61%   |
| MSI MS-7758                                | 1        | 1.61%   |
| Hardkernel ODROID-H2                       | 1        | 1.61%   |
| Gigabyte X470                              | 1        | 1.61%   |
| Gigabyte TRX40                             | 1        | 1.61%   |
| Gigabyte H97M-D3H                          | 1        | 1.61%   |
| Gigabyte B760                              | 1        | 1.61%   |
| EVGA X299                                  | 1        | 1.61%   |
| Dell Precision                             | 1        | 1.61%   |
| AZW EQ                                     | 1        | 1.61%   |
| ASUS Z170-P                                | 1        | 1.61%   |
| ASUS SABERTOOTH                            | 1        | 1.61%   |
| ASUS PRO602617                             | 1        | 1.61%   |
| ASUS PRO-Q77                               | 1        | 1.61%   |
| ASUS Pro                                   | 1        | 1.61%   |
| ASUS P8Z77-V                               | 1        | 1.61%   |
| ASRock Z87                                 | 1        | 1.61%   |
| ASRock X570                                | 1        | 1.61%   |
| ASRock TRX40                               | 1        | 1.61%   |
| ASRock B550M                               | 1        | 1.61%   |
| ASRock B450                                | 1        | 1.61%   |
| ASRock AB350                               | 1        | 1.61%   |
| Acer Nitro                                 | 1        | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 17       | 27.42%  |
| 2019 | 11       | 17.74%  |
| 2018 | 9        | 14.52%  |
| 2022 | 4        | 6.45%   |
| 2017 | 4        | 6.45%   |
| 2016 | 4        | 6.45%   |
| 2012 | 4        | 6.45%   |
| 2014 | 3        | 4.84%   |
| 2013 | 3        | 4.84%   |
| 2015 | 2        | 3.23%   |
| 2023 | 1        | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 62       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 62       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 62       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 19       | 30.65%  |
| 64.01-256.0     | 17       | 27.42%  |
| 16.01-24.0      | 13       | 20.97%  |
| 24.01-32.0      | 6        | 9.68%   |
| 4.01-8.0        | 3        | 4.84%   |
| 8.01-16.0       | 3        | 4.84%   |
| More than 256.0 | 1        | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 22       | 33.85%  |
| 8.01-16.0  | 13       | 20%     |
| 3.01-4.0   | 8        | 12.31%  |
| 32.01-64.0 | 6        | 9.23%   |
| 1.01-2.0   | 6        | 9.23%   |
| 16.01-24.0 | 5        | 7.69%   |
| 2.01-3.0   | 3        | 4.62%   |
| 24.01-32.0 | 1        | 1.54%   |
| 0.51-1.0   | 1        | 1.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 23       | 34.33%  |
| 1      | 16       | 23.88%  |
| 3      | 12       | 17.91%  |
| 6      | 4        | 5.97%   |
| 5      | 4        | 5.97%   |
| 4      | 4        | 5.97%   |
| 23     | 1        | 1.49%   |
| 8      | 1        | 1.49%   |
| 7      | 1        | 1.49%   |
| 0      | 1        | 1.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 80.95%  |
| Yes       | 12       | 19.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 62       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 59.38%  |
| Yes       | 26       | 40.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 55.56%  |
| Yes       | 28       | 44.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 13       | 20.97%  |
| Germany     | 10       | 16.13%  |
| UK          | 5        | 8.06%   |
| Russia      | 3        | 4.84%   |
| Poland      | 3        | 4.84%   |
| Italy       | 3        | 4.84%   |
| Canada      | 3        | 4.84%   |
| Australia   | 3        | 4.84%   |
| Ukraine     | 2        | 3.23%   |
| France      | 2        | 3.23%   |
| Denmark     | 2        | 3.23%   |
| Brazil      | 2        | 3.23%   |
| Austria     | 2        | 3.23%   |
| Taiwan      | 1        | 1.61%   |
| Switzerland | 1        | 1.61%   |
| Serbia      | 1        | 1.61%   |
| New Zealand | 1        | 1.61%   |
| Netherlands | 1        | 1.61%   |
| Ireland     | 1        | 1.61%   |
| India       | 1        | 1.61%   |
| Hungary     | 1        | 1.61%   |
| Belgium     | 1        | 1.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Vienna            | 2        | 3.13%   |
| Schaafheim        | 2        | 3.13%   |
| Plymouth          | 2        | 3.13%   |
| Marki             | 2        | 3.13%   |
| Kharkiv           | 2        | 3.13%   |
| Darmstadt         | 2        | 3.13%   |
| Austin            | 2        | 3.13%   |
| Wellington        | 1        | 1.56%   |
| Tobercurry        | 1        | 1.56%   |
| Taichung          | 1        | 1.56%   |
| Székesfehérvár | 1        | 1.56%   |
| Southampton       | 1        | 1.56%   |
| South Deerfield   | 1        | 1.56%   |
| Sorocaba          | 1        | 1.56%   |
| Sindelfingen      | 1        | 1.56%   |
| San Gabriel       | 1        | 1.56%   |
| Saarbrücken      | 1        | 1.56%   |
| Richardson        | 1        | 1.56%   |
| Redwood City      | 1        | 1.56%   |
| Ramenskoye        | 1        | 1.56%   |
| Pisa              | 1        | 1.56%   |
| Perth             | 1        | 1.56%   |
| Osasco            | 1        | 1.56%   |
| Oakville          | 1        | 1.56%   |
| Norwich           | 1        | 1.56%   |
| North Andover     | 1        | 1.56%   |
| Montreal          | 1        | 1.56%   |
| Melrose           | 1        | 1.56%   |
| Melbourne         | 1        | 1.56%   |
| Lille             | 1        | 1.56%   |
| Landorthe         | 1        | 1.56%   |
| Lamont            | 1        | 1.56%   |
| Kuybyshev         | 1        | 1.56%   |
| Krasnodar         | 1        | 1.56%   |
| Karlsruhe         | 1        | 1.56%   |
| Hobart            | 1        | 1.56%   |
| Heusweiler        | 1        | 1.56%   |
| Heidelberg        | 1        | 1.56%   |
| Hasselt           | 1        | 1.56%   |
| Hamburg           | 1        | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 36       | 67     | 29.51%  |
| WDC                         | 14       | 31     | 11.48%  |
| Seagate                     | 14       | 23     | 11.48%  |
| SanDisk                     | 10       | 14     | 8.2%    |
| Toshiba                     | 9        | 20     | 7.38%   |
| Crucial                     | 8        | 9      | 6.56%   |
| Kingston                    | 5        | 5      | 4.1%    |
| Intel                       | 4        | 6      | 3.28%   |
| Realtek Semiconductor       | 2        | 3      | 1.64%   |
| Phison Electronics          | 2        | 4      | 1.64%   |
| Hitachi                     | 2        | 4      | 1.64%   |
| HGST                        | 2        | 4      | 1.64%   |
| ZHITAI                      | 1        | 1      | 0.82%   |
| Yangtze Memory Technologies | 1        | 2      | 0.82%   |
| SPCC                        | 1        | 1      | 0.82%   |
| Silicon Motion              | 1        | 1      | 0.82%   |
| Plextor                     | 1        | 1      | 0.82%   |
| Phison                      | 1        | 1      | 0.82%   |
| OCZ                         | 1        | 1      | 0.82%   |
| MBED                        | 1        | 1      | 0.82%   |
| MAXIO Technology (Hangzhou) | 1        | 2      | 0.82%   |
| Lexar                       | 1        | 1      | 0.82%   |
| Kingston Technology Company | 1        | 1      | 0.82%   |
| Corsair                     | 1        | 1      | 0.82%   |
| China                       | 1        | 1      | 0.82%   |
| ASMT                        | 1        | 1      | 0.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 860 QVO 1TB                             | 4        | 2.48%   |
| Samsung SSD 860 EVO 500GB                           | 4        | 2.48%   |
| Samsung SSD 860 EVO 1TB                             | 4        | 2.48%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3        | 1.86%   |
| SanDisk SSD PLUS 240GB                              | 3        | 1.86%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3        | 1.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3        | 1.86%   |
| Seagate ST3000DM001-1CH166 3TB                      | 2        | 1.24%   |
| Samsung SSD 980 PRO 1TB                             | 2        | 1.24%   |
| Samsung SSD 980 1TB                                 | 2        | 1.24%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2        | 1.24%   |
| Samsung SSD 970 EVO 500GB                           | 2        | 1.24%   |
| Samsung SSD 970 EVO 1TB                             | 2        | 1.24%   |
| Samsung SSD 860 EVO 2TB                             | 2        | 1.24%   |
| Samsung NVMe SSD Drive 1TB                          | 2        | 1.24%   |
| Crucial CT1000MX500SSD1 1TB                         | 2        | 1.24%   |
| ZHITAI SC001 Active 512GB SSD                       | 1        | 0.62%   |
| Yangtze Memory ZHITAI TiPro7000 1TB                 | 1        | 0.62%   |
| Yangtze Memory ZHITAI TiPlus7100 1TB                | 1        | 0.62%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1        | 0.62%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 1        | 0.62%   |
| WDC WD80EDAZ-11TA3A0 8TB                            | 1        | 0.62%   |
| WDC WD50EZRX-00MVLB1 5TB                            | 1        | 0.62%   |
| WDC WD40EFRX-68N32N0 4TB                            | 1        | 0.62%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1        | 0.62%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1        | 0.62%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 1        | 0.62%   |
| WDC WD20EZBX-00AYRA0 2TB                            | 1        | 0.62%   |
| WDC WD20EARX-008FB0 2TB                             | 1        | 0.62%   |
| WDC WD1600AAJS-62B4A0 160GB                         | 1        | 0.62%   |
| WDC WD10EZEX-60ZF5A0 1TB                            | 1        | 0.62%   |
| WDC WD10EZEX-21WN4A0 1TB                            | 1        | 0.62%   |
| WDC WD10EZEX-00RKKA0 1TB                            | 1        | 0.62%   |
| WDC WD10EZEX-00KUWA0 1TB                            | 1        | 0.62%   |
| WDC WD10EAVS-32D7B1 1TB                             | 1        | 0.62%   |
| WDC WD10EAVS-00D7B0 1TB                             | 1        | 0.62%   |
| WDC WD10EARS-00Y5B1 1TB                             | 1        | 0.62%   |
| WDC WD10EADS-00M2B0 1TB                             | 1        | 0.62%   |
| WDC WD101KRYZ-01JPDB1 10TB                          | 1        | 0.62%   |
| Toshiba TR150 960GB SSD                             | 1        | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 29     | 32.56%  |
| Seagate             | 14       | 23     | 32.56%  |
| Toshiba             | 8        | 16     | 18.6%   |
| Samsung Electronics | 2        | 2      | 4.65%   |
| Hitachi             | 2        | 4      | 4.65%   |
| HGST                | 2        | 4      | 4.65%   |
| ASMT                | 1        | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 18       | 29     | 38.3%   |
| Crucial             | 8        | 9      | 17.02%  |
| SanDisk             | 6        | 9      | 12.77%  |
| Kingston            | 4        | 4      | 8.51%   |
| Intel               | 4        | 6      | 8.51%   |
| ZHITAI              | 1        | 1      | 2.13%   |
| WDC                 | 1        | 2      | 2.13%   |
| Toshiba             | 1        | 1      | 2.13%   |
| SPCC                | 1        | 1      | 2.13%   |
| OCZ                 | 1        | 1      | 2.13%   |
| Corsair             | 1        | 1      | 2.13%   |
| China               | 1        | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 40       | 65     | 37.38%  |
| NVMe    | 38       | 61     | 35.51%  |
| HDD     | 28       | 79     | 26.17%  |
| Unknown | 1        | 1      | 0.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 51       | 142    | 55.43%  |
| NVMe | 38       | 61     | 41.3%   |
| SAS  | 3        | 3      | 3.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 29       | 44     | 36.25%  |
| 0.51-1.0   | 25       | 46     | 31.25%  |
| 1.01-2.0   | 10       | 15     | 12.5%   |
| 4.01-10.0  | 8        | 23     | 10%     |
| 2.01-3.0   | 6        | 12     | 7.5%    |
| 3.01-4.0   | 2        | 4      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 25       | 39.68%  |
| 1-20           | 8        | 12.7%   |
| 501-1000       | 8        | 12.7%   |
| 101-250        | 6        | 9.52%   |
| More than 3000 | 4        | 6.35%   |
| 251-500        | 4        | 6.35%   |
| 2001-3000      | 4        | 6.35%   |
| 1001-2000      | 4        | 6.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 25       | 39.06%  |
| 1-20           | 13       | 20.31%  |
| 101-250        | 6        | 9.38%   |
| 501-1000       | 5        | 7.81%   |
| 51-100         | 4        | 6.25%   |
| More than 3000 | 3        | 4.69%   |
| 1001-2000      | 3        | 4.69%   |
| 251-500        | 2        | 3.13%   |
| 21-50          | 2        | 3.13%   |
| 2001-3000      | 1        | 1.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD20EZRZ-00Z5HB0 2TB            | 1        | 1      | 8.33%   |
| WDC WD20EARX-008FB0 2TB             | 1        | 1      | 8.33%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 1        | 1      | 8.33%   |
| Seagate ST3500418AS 500GB           | 1        | 1      | 8.33%   |
| SanDisk SSD PLUS 240GB              | 1        | 1      | 8.33%   |
| Samsung Electronics SSD 970 EVO 1TB | 1        | 1      | 8.33%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 8.33%   |
| Intel SSDSC2BW240A4 240GB           | 1        | 1      | 8.33%   |
| Hitachi HDS722020ALA330 2TB         | 1        | 1      | 8.33%   |
| HGST HTS545050A7E680 500GB          | 1        | 1      | 8.33%   |
| Crucial CT240M500SSD1 240GB         | 1        | 1      | 8.33%   |
| ASMT 2115 64GB                      | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 25%     |
| Samsung Electronics | 2        | 2      | 16.67%  |
| Seagate             | 1        | 1      | 8.33%   |
| SanDisk             | 1        | 1      | 8.33%   |
| Intel               | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |
| HGST                | 1        | 1      | 8.33%   |
| Crucial             | 1        | 1      | 8.33%   |
| ASMT                | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 42.86%  |
| Seagate | 1        | 1      | 14.29%  |
| Hitachi | 1        | 1      | 14.29%  |
| HGST    | 1        | 1      | 14.29%  |
| ASMT    | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 7      | 54.55%  |
| SSD  | 4        | 4      | 36.36%  |
| NVMe | 1        | 1      | 9.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Desktops | Drives | Percent |
|------------------------|----------|--------|---------|
| Toshiba MG03ACA300 3TB | 1        | 1      | 50%     |
| Toshiba HDWG180 8TB    | 1        | 4      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 2        | 5      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 61       | 176    | 77.22%  |
| Malfunc  | 9        | 12     | 11.39%  |
| Detected | 7        | 13     | 8.86%   |
| Failed   | 2        | 5      | 2.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 35       | 32.11%  |
| Intel                        | 25       | 22.94%  |
| Samsung Electronics          | 23       | 21.1%   |
| ASMedia Technology           | 6        | 5.5%    |
| Sandisk                      | 4        | 3.67%   |
| Phison Electronics           | 3        | 2.75%   |
| Realtek Semiconductor        | 2        | 1.83%   |
| LSI Logic / Symbios Logic    | 2        | 1.83%   |
| Kingston Technology Company  | 2        | 1.83%   |
| Yangtze Memory Technologies  | 1        | 0.92%   |
| Toshiba America Info Systems | 1        | 0.92%   |
| Silicon Motion               | 1        | 0.92%   |
| Shenzhen Longsys Electronics | 1        | 0.92%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.92%   |
| Lite-On Technology           | 1        | 0.92%   |
| Broadcom / LSI               | 1        | 0.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 20       | 16.53%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15       | 12.4%   |
| AMD 500 Series Chipset SATA Controller                                         | 12       | 9.92%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 6        | 4.96%   |
| AMD 400 Series Chipset SATA Controller                                         | 6        | 4.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4        | 3.31%   |
| Samsung NVMe SSD Controller 980                                                | 3        | 2.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 2.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 2.48%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 2.48%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 2.48%   |
| Phison E12 NVMe Controller                                                     | 2        | 1.65%   |
| Kingston Company A2000 NVMe SSD                                                | 2        | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.65%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 1.65%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 1.65%   |
| Yangtze Memory ZHITAI TiPro7000                                                | 1        | 0.83%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 1        | 0.83%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1        | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.83%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 1        | 0.83%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 1        | 0.83%   |
| SanDisk WD Green SN350 NVMe SSD 240GB (DRAM-less)                              | 1        | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 0.83%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.83%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1        | 0.83%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1        | 0.83%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.83%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1        | 0.83%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                 | 1        | 0.83%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1        | 0.83%   |
| Lite-On Non-Volatile memory controller                                         | 1        | 0.83%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 0.83%   |
| Intel SATA controller                                                          | 1        | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 0.83%   |
| Intel Comet Lake PCH-H RAID                                                    | 1        | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 0.83%   |
| Intel C610/X99 series chipset IDE-r Controller                                 | 1        | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 59       | 57.28%  |
| NVMe | 38       | 36.89%  |
| SAS  | 3        | 2.91%   |
| RAID | 2        | 1.94%   |
| IDE  | 1        | 0.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 36       | 58.06%  |
| Intel  | 26       | 41.94%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 5        | 8.06%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 4        | 6.45%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 3        | 4.84%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 3        | 4.84%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 3.23%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 2        | 3.23%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 2        | 3.23%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 2        | 3.23%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 3.23%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 3.23%   |
| Intel Xeon W-1290P CPU @ 3.70GHz               | 1        | 1.61%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz            | 1        | 1.61%   |
| Intel Core i9-9900X CPU @ 3.50GHz              | 1        | 1.61%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 1.61%   |
| Intel Core i7-6850K CPU @ 3.60GHz              | 1        | 1.61%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 1.61%   |
| Intel Core i7-4770K CPU @ 3.50GHz              | 1        | 1.61%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 1.61%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 1        | 1.61%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 1.61%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 1.61%   |
| Intel Core i5-4570S CPU @ 2.90GHz              | 1        | 1.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.61%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 1        | 1.61%   |
| Intel Core i5-3470T CPU @ 2.90GHz              | 1        | 1.61%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 1.61%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1        | 1.61%   |
| Intel Core i3-N305                             | 1        | 1.61%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1        | 1.61%   |
| Intel Celeron J4105 CPU @ 1.50GHz              | 1        | 1.61%   |
| Intel 13th Gen Core i9-13900K                  | 1        | 1.61%   |
| Intel 13th Gen Core i5-13600KF                 | 1        | 1.61%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1        | 1.61%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 1.61%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 1.61%   |
| AMD Ryzen 9 6900HX with Radeon Graphics        | 1        | 1.61%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 1.61%   |
| AMD Ryzen 7 7800X3D 8-Core Processor           | 1        | 1.61%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 1.61%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 15       | 24.19%  |
| Intel Core i7          | 9        | 14.52%  |
| Intel Core i5          | 9        | 14.52%  |
| AMD Ryzen 7            | 9        | 14.52%  |
| AMD Ryzen 9            | 8        | 12.9%   |
| AMD Ryzen Threadripper | 3        | 4.84%   |
| Other                  | 2        | 3.23%   |
| Intel Xeon             | 2        | 3.23%   |
| Intel Core i3          | 2        | 3.23%   |
| Intel Core i9          | 1        | 1.61%   |
| Intel Celeron          | 1        | 1.61%   |
| AMD FX                 | 1        | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 20       | 32.26%  |
| 4      | 14       | 22.58%  |
| 8      | 11       | 17.74%  |
| 16     | 4        | 6.45%   |
| 12     | 4        | 6.45%   |
| 24     | 3        | 4.84%   |
| 10     | 2        | 3.23%   |
| 2      | 2        | 3.23%   |
| 32     | 1        | 1.61%   |
| 14     | 1        | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 61       | 98.39%  |
| 2      | 1        | 1.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 53       | 85.48%  |
| 1      | 9        | 14.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 62       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 14.29%  |
| 0x08701021 | 7        | 11.11%  |
| 0x306c3    | 6        | 9.52%   |
| 0x906ea    | 4        | 6.35%   |
| 0x306a9    | 4        | 6.35%   |
| 0x08701013 | 4        | 6.35%   |
| 0x0a50000d | 3        | 4.76%   |
| 0x506e3    | 2        | 3.17%   |
| 0x0a201204 | 2        | 3.17%   |
| 0x0a201025 | 2        | 3.17%   |
| 0x0a201016 | 2        | 3.17%   |
| 0x0a201009 | 2        | 3.17%   |
| 0x08001138 | 2        | 3.17%   |
| 0xa0653    | 1        | 1.59%   |
| 0x906e9    | 1        | 1.59%   |
| 0x406f1    | 1        | 1.59%   |
| 0x306f2    | 1        | 1.59%   |
| 0x0a601203 | 1        | 1.59%   |
| 0x0a50000c | 1        | 1.59%   |
| 0x0a404102 | 1        | 1.59%   |
| 0x0a20120a | 1        | 1.59%   |
| 0x08301055 | 1        | 1.59%   |
| 0x08301025 | 1        | 1.59%   |
| 0x08108109 | 1        | 1.59%   |
| 0x0800820d | 1        | 1.59%   |
| 0x08001137 | 1        | 1.59%   |
| 0x06000852 | 1        | 1.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 14       | 22.58%  |
| Zen 3            | 13       | 20.97%  |
| Haswell          | 7        | 11.29%  |
| KabyLake         | 5        | 8.06%   |
| IvyBridge        | 4        | 6.45%   |
| Zen+             | 3        | 4.84%   |
| Zen              | 3        | 4.84%   |
| Skylake          | 3        | 4.84%   |
| CometLake        | 2        | 3.23%   |
| Alderlake Hybrid | 2        | 3.23%   |
| Unknown          | 2        | 3.23%   |
| Piledriver       | 1        | 1.61%   |
| Gracemont        | 1        | 1.61%   |
| Goldmont plus    | 1        | 1.61%   |
| Broadwell        | 1        | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 32       | 46.38%  |
| AMD    | 26       | 37.68%  |
| Intel  | 11       | 15.94%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 9.86%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 8.45%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 3        | 4.23%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 4.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 4.23%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 2.82%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 2.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.82%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 2.82%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 2.82%   |
| Intel HD Graphics 530                                                       | 2        | 2.82%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 2.82%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2        | 2.82%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.41%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.41%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.41%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.41%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.41%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.41%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.41%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.41%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.41%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.41%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.41%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.41%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 1.41%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                           | 1        | 1.41%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.41%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.41%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.41%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 1        | 1.41%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.41%   |
| Intel HD Graphics 630                                                       | 1        | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.41%   |
| Intel Comet Lake-S GT2 [UHD Graphics P630]                                  | 1        | 1.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.41%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 1        | 1.41%   |
| AMD Rembrandt [Radeon 680M]                                                 | 1        | 1.41%   |
| AMD Raphael                                                                 | 1        | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 25       | 40.32%  |
| 1 x AMD        | 20       | 32.26%  |
| 1 x Intel      | 7        | 11.29%  |
| AMD + Nvidia   | 4        | 6.45%   |
| Intel + Nvidia | 3        | 4.84%   |
| 2 x AMD        | 2        | 3.23%   |
| Other          | 1        | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 35       | 56.45%  |
| Proprietary | 24       | 38.71%  |
| Unknown     | 3        | 4.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 38       | 60.32%  |
| 7.01-8.0   | 14       | 22.22%  |
| 8.01-16.0  | 4        | 6.35%   |
| 3.01-4.0   | 2        | 3.17%   |
| 1.01-2.0   | 2        | 3.17%   |
| 0.01-0.5   | 2        | 3.17%   |
| 16.01-24.0 | 1        | 1.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 13       | 22.41%  |
| Goldstar             | 9        | 15.52%  |
| Acer                 | 7        | 12.07%  |
| Samsung Electronics  | 5        | 8.62%   |
| Ancor Communications | 4        | 6.9%    |
| Iiyama               | 3        | 5.17%   |
| AOC                  | 3        | 5.17%   |
| Hewlett-Packard      | 2        | 3.45%   |
| BenQ                 | 2        | 3.45%   |
| Vizio                | 1        | 1.72%   |
| ViewSonic            | 1        | 1.72%   |
| Unknown (AAA)        | 1        | 1.72%   |
| RTK                  | 1        | 1.72%   |
| Philips              | 1        | 1.72%   |
| NEC Computers        | 1        | 1.72%   |
| MSI                  | 1        | 1.72%   |
| MPI                  | 1        | 1.72%   |
| HVR                  | 1        | 1.72%   |
| Gigabyte Technology  | 1        | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2        | 3.23%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                     | 2        | 3.23%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                    | 2        | 3.23%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                 | 2        | 3.23%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                | 1        | 1.61%   |
| ViewSonic VX2758-SERIES VSCA738 2560x1440 598x336mm 27.0-inch        | 1        | 1.61%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch          | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch | 1        | 1.61%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch    | 1        | 1.61%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 597x336mm 27.0-inch   | 1        | 1.61%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                    | 1        | 1.61%   |
| Philips PHL 272V8 PHLC21A 1920x1080 598x336mm 27.0-inch              | 1        | 1.61%   |
| NEC Computers 90GX2 NEC6692 1280x1024 376x301mm 19.0-inch            | 1        | 1.61%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                       | 1        | 1.61%   |
| MPI WIMAXIT MPI7002 1920x1080 180x130mm 8.7-inch                     | 1        | 1.61%   |
| Iiyama PLX2481H IVM611D 1920x1080 520x290mm 23.4-inch                | 1        | 1.61%   |
| Iiyama PLE2208HDS IVM560A 1920x1080 477x268mm 21.5-inch              | 1        | 1.61%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                | 1        | 1.61%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                 | 1        | 1.61%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                       | 1        | 1.61%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch         | 1        | 1.61%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch           | 1        | 1.61%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch             | 1        | 1.61%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch             | 1        | 1.61%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 1        | 1.61%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 1        | 1.61%   |
| Goldstar M228WA GSM563D 1680x1050 434x270mm 20.1-inch                | 1        | 1.61%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 1        | 1.61%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                | 1        | 1.61%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 1        | 1.61%   |
| Goldstar FULL HD GSM5BDF 1920x1080 480x270mm 21.7-inch               | 1        | 1.61%   |
| Gigabyte Technology G24F GBT2402 1920x1080 527x296mm 23.8-inch       | 1        | 1.61%   |
| Dell U2719DC DEL417C 2560x1440 597x336mm 27.0-inch                   | 1        | 1.61%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                    | 1        | 1.61%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                    | 1        | 1.61%   |
| Dell U2717D DEL40EA 2560x1440 597x336mm 27.0-inch                    | 1        | 1.61%   |
| Dell U2715H DELD067 2560x1440 600x340mm 27.2-inch                    | 1        | 1.61%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                    | 1        | 1.61%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                    | 1        | 1.61%   |
| Dell U2415 DELA0B9 1920x1200 520x320mm 24.0-inch                     | 1        | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 21       | 39.62%  |
| 3840x2160 (4K)     | 10       | 18.87%  |
| 2560x1440 (QHD)    | 8        | 15.09%  |
| 2560x1080          | 4        | 7.55%   |
| 1280x1024 (SXGA)   | 3        | 5.66%   |
| 3440x1440          | 1        | 1.89%   |
| 2560x1600          | 1        | 1.89%   |
| 2160x1200          | 1        | 1.89%   |
| 1920x1200 (WUXGA)  | 1        | 1.89%   |
| 1680x1050 (WSXGA+) | 1        | 1.89%   |
| 1600x900 (HD+)     | 1        | 1.89%   |
| 1280x720 (HD)      | 1        | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 13       | 23.21%  |
| 23      | 11       | 19.64%  |
| 24      | 10       | 17.86%  |
| 34      | 5        | 8.93%   |
| 21      | 3        | 5.36%   |
| 31      | 2        | 3.57%   |
| 25      | 2        | 3.57%   |
| 19      | 2        | 3.57%   |
| 49      | 1        | 1.79%   |
| 38      | 1        | 1.79%   |
| 28      | 1        | 1.79%   |
| 22      | 1        | 1.79%   |
| 20      | 1        | 1.79%   |
| 17      | 1        | 1.79%   |
| 14      | 1        | 1.79%   |
| Unknown | 1        | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 32       | 61.54%  |
| 701-800     | 5        | 9.62%   |
| 401-500     | 5        | 9.62%   |
| 601-700     | 3        | 5.77%   |
| 351-400     | 2        | 3.85%   |
| 801-900     | 1        | 1.92%   |
| 301-350     | 1        | 1.92%   |
| 201-300     | 1        | 1.92%   |
| 1001-1500   | 1        | 1.92%   |
| Unknown     | 1        | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 35       | 71.43%  |
| 21/9  | 5        | 10.2%   |
| 16/10 | 5        | 10.2%   |
| 5/4   | 3        | 6.12%   |
| 1.00  | 1        | 2.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18       | 32.73%  |
| 301-350        | 13       | 23.64%  |
| 351-500        | 8        | 14.55%  |
| 251-300        | 6        | 10.91%  |
| 151-200        | 5        | 9.09%   |
| More than 1000 | 1        | 1.82%   |
| 141-150        | 1        | 1.82%   |
| 101-110        | 1        | 1.82%   |
| 501-1000       | 1        | 1.82%   |
| Unknown        | 1        | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 31       | 59.62%  |
| 101-120 | 12       | 23.08%  |
| 161-240 | 5        | 9.62%   |
| 121-160 | 2        | 3.85%   |
| 1-50    | 1        | 1.92%   |
| Unknown | 1        | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 35       | 56.45%  |
| 2     | 14       | 22.58%  |
| 0     | 11       | 17.74%  |
| 3     | 2        | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 38       | 40%     |
| Intel                 | 36       | 37.89%  |
| Aquantia              | 5        | 5.26%   |
| MediaTek              | 3        | 3.16%   |
| Ralink Technology     | 2        | 2.11%   |
| Qualcomm Atheros      | 2        | 2.11%   |
| TP-Link               | 1        | 1.05%   |
| Texas Instruments     | 1        | 1.05%   |
| STMicroelectronics    | 1        | 1.05%   |
| Ralink                | 1        | 1.05%   |
| Oculus VR             | 1        | 1.05%   |
| Microsoft             | 1        | 1.05%   |
| Google                | 1        | 1.05%   |
| D-Link System         | 1        | 1.05%   |
| Broadcom              | 1        | 1.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 28.57%  |
| Intel Wi-Fi 6 AX200                                               | 9        | 8.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 7.62%   |
| Intel I211 Gigabit Network Connection                             | 8        | 7.62%   |
| Intel Ethernet Controller I225-V                                  | 6        | 5.71%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 1.9%    |
| Intel Ethernet Connection I217-V                                  | 2        | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.9%    |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.9%    |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.9%    |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.9%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 1.9%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.95%   |
| Texas Instruments CC2538 USB CDC                                  | 1        | 0.95%   |
| STMicroelectronics Virtual COM Port                               | 1        | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.95%   |
| Realtek 802.11ac NIC                                              | 1        | 0.95%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.95%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.95%   |
| Ralink RT2800 802.11n PCI                                         | 1        | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.95%   |
| Oculus VR Rift S                                                  | 1        | 0.95%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 0.95%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1        | 0.95%   |
| Intel Wireless 7265                                               | 1        | 0.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.95%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 0.95%   |
| Intel CNVi: Wi-Fi                                                 | 1        | 0.95%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 0.95%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.95%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 0.95%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W] | 1        | 0.95%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 0.95%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.95%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 15       | 57.69%  |
| MediaTek              | 3        | 11.54%  |
| Ralink Technology     | 2        | 7.69%   |
| TP-Link               | 1        | 3.85%   |
| Realtek Semiconductor | 1        | 3.85%   |
| Ralink                | 1        | 3.85%   |
| Qualcomm Atheros      | 1        | 3.85%   |
| Microsoft             | 1        | 3.85%   |
| D-Link System         | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                               | 9        | 34.62%  |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 7.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 3.85%   |
| Realtek 802.11ac NIC                                              | 1        | 3.85%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 3.85%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 3.85%   |
| Ralink RT2800 802.11n PCI                                         | 1        | 3.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 3.85%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 3.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1        | 3.85%   |
| Intel Wireless 7265                                               | 1        | 3.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 3.85%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 3.85%   |
| Intel CNVi: Wi-Fi                                                 | 1        | 3.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 3.85%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W] | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 38       | 50.67%  |
| Intel                 | 29       | 38.67%  |
| Aquantia              | 5        | 6.67%   |
| Qualcomm Atheros      | 1        | 1.33%   |
| Google                | 1        | 1.33%   |
| Broadcom              | 1        | 1.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 39.47%  |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 10.53%  |
| Intel I211 Gigabit Network Connection                             | 8        | 10.53%  |
| Intel Ethernet Controller I225-V                                  | 6        | 7.89%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.63%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.63%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 2.63%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.63%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.63%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 2.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.32%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 1.32%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.32%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.32%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.32%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 1.32%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 1.32%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.32%   |
| Aquantia AQC100 10G Ethernet MAC controller [AQtion]              | 1        | 1.32%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1        | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 62       | 68.13%  |
| WiFi     | 26       | 28.57%  |
| Modem    | 3        | 3.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 50       | 81.97%  |
| WiFi     | 11       | 18.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 52.38%  |
| 2     | 24       | 38.1%   |
| 3     | 5        | 7.94%   |
| 0     | 1        | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 43       | 68.25%  |
| Yes  | 20       | 31.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 11       | 36.67%  |
| Cambridge Silicon Radio  | 6        | 20%     |
| ASUSTek Computer         | 4        | 13.33%  |
| Realtek Semiconductor    | 3        | 10%     |
| MediaTek                 | 2        | 6.67%   |
| Broadcom                 | 2        | 6.67%   |
| HTC (High Tech Computer) | 1        | 3.33%   |
| Foxconn / Hon Hai        | 1        | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 7        | 23.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 6        | 20%     |
| Realtek Bluetooth Radio                                              | 3        | 10%     |
| Intel AX201 Bluetooth                                                | 3        | 10%     |
| MediaTek Wireless_Device                                             | 2        | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 6.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 1        | 3.33%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 3.33%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1        | 3.33%   |
| ASUS Bluetooth Device                                                | 1        | 3.33%   |
| ASUS ASUS USB-BT500                                                  | 1        | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 40       | 30.3%   |
| Nvidia                               | 32       | 24.24%  |
| Intel                                | 26       | 19.7%   |
| C-Media Electronics                  | 4        | 3.03%   |
| Texas Instruments                    | 3        | 2.27%   |
| Razer USA                            | 3        | 2.27%   |
| Sennheiser Communications            | 2        | 1.52%   |
| Kingston Technology                  | 2        | 1.52%   |
| Thomann                              | 1        | 0.76%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.76%   |
| Sony                                 | 1        | 0.76%   |
| Shure                                | 1        | 0.76%   |
| Schiit Audio                         | 1        | 0.76%   |
| Scarlett                             | 1        | 0.76%   |
| RODE Microphones                     | 1        | 0.76%   |
| PreSonus Audio Electronics           | 1        | 0.76%   |
| GYROCOM C&C                          | 1        | 0.76%   |
| Giga-Byte Technology                 | 1        | 0.76%   |
| Focusrite-Novation                   | 1        | 0.76%   |
| Edifier Technology                   | 1        | 0.76%   |
| Dell                                 | 1        | 0.76%   |
| Creative Technology                  | 1        | 0.76%   |
| Creative Labs                        | 1        | 0.76%   |
| Conexant Systems                     | 1        | 0.76%   |
| ASUSTek Computer                     | 1        | 0.76%   |
| ASRock                               | 1        | 0.76%   |
| Apogee Electronics                   | 1        | 0.76%   |
| Antlion Audio                        | 1        | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 22       | 14.19%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 7        | 4.52%   |
| AMD Navi 10 HDMI Audio                                              | 6        | 3.87%   |
| AMD Family 17h/19h HD Audio Controller                              | 5        | 3.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 5        | 3.23%   |
| Nvidia TU116 High Definition Audio Controller                       | 4        | 2.58%   |
| Nvidia TU106 High Definition Audio Controller                       | 4        | 2.58%   |
| Nvidia GK104 HDMI Audio Controller                                  | 4        | 2.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 4        | 2.58%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 4        | 2.58%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 4        | 2.58%   |
| Nvidia GP106 High Definition Audio Controller                       | 3        | 1.94%   |
| Nvidia GP104 High Definition Audio Controller                       | 3        | 1.94%   |
| Intel Cannon Lake PCH cAVS                                          | 3        | 1.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 3        | 1.94%   |
| Intel 200 Series PCH HD Audio                                       | 3        | 1.94%   |
| Texas Instruments PCM2902 Audio Codec                               | 2        | 1.29%   |
| Nvidia GP108 High Definition Audio Controller                       | 2        | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                     | 2        | 1.29%   |
| Nvidia GM204 High Definition Audio Controller                       | 2        | 1.29%   |
| Intel Comet Lake PCH cAVS                                           | 2        | 1.29%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2        | 1.29%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 2        | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2        | 1.29%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                          | 2        | 1.29%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 2        | 1.29%   |
| Thomann SC450USB                                                    | 1        | 0.65%   |
| Thesycon Systemsoftware & Consulting D10                            | 1        | 0.65%   |
| Texas Instruments PCM2902C Audio CODEC                              | 1        | 0.65%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1        | 0.65%   |
| Shure MV7                                                           | 1        | 0.65%   |
| Sennheiser Communications Sennheiser SC630 for Lync                 | 1        | 0.65%   |
| Sennheiser Communications Headset [PC 8]                            | 1        | 0.65%   |
| Schiit Audio Schiit Modi 3+                                         | 1        | 0.65%   |
| Scarlett Scarlett 2i2 Camera                                        | 1        | 0.65%   |
| RODE Microphones RODE NT-USB Mini                                   | 1        | 0.65%   |
| Razer USA Razer BlackShark V2 Pro                                   | 1        | 0.65%   |
| Razer USA Razer Barracuda 2.4                                       | 1        | 0.65%   |
| Razer USA Kraken 7.1 V2                                             | 1        | 0.65%   |
| PreSonus Audio Electronics AudioBox                                 | 1        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 20       | 28.17%  |
| Kingston            | 15       | 21.13%  |
| G.Skill             | 13       | 18.31%  |
| Crucial             | 6        | 8.45%   |
| Samsung Electronics | 4        | 5.63%   |
| Micron Technology   | 3        | 4.23%   |
| Unknown             | 2        | 2.82%   |
| Team                | 2        | 2.82%   |
| Unknown (ABCD)      | 1        | 1.41%   |
| Strontium           | 1        | 1.41%   |
| Goodram             | 1        | 1.41%   |
| GLOWAY              | 1        | 1.41%   |
| AMD                 | 1        | 1.41%   |
| A-DATA Technology   | 1        | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s              | 3        | 3.85%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s            | 3        | 3.85%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s            | 2        | 2.56%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s               | 2        | 2.56%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s               | 2        | 2.56%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s               | 2        | 2.56%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s            | 2        | 2.56%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1        | 1.28%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                     | 1        | 1.28%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1        | 1.28%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s               | 1        | 1.28%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s                | 1        | 1.28%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2933MT/s               | 1        | 1.28%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s                | 1        | 1.28%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                    | 1        | 1.28%   |
| Samsung RAM M393A4K40BB0-CPB 32GB RIMM DDR4 2133MT/s              | 1        | 1.28%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s               | 1        | 1.28%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 1        | 1.28%   |
| Micron RAM 4ATF1G64AZ-3G2E1 8GB DIMM DDR4 3200MT/s                | 1        | 1.28%   |
| Micron RAM 36ASF4G72PZ-2G1A1 32GB RIMM DDR4 2133MT/s              | 1        | 1.28%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16384MB DIMM DDR4 3200MT/s           | 1        | 1.28%   |
| Kingston RAM Module 4GB DIMM DDR3 1600MT/s                        | 1        | 1.28%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 1        | 1.28%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s            | 1        | 1.28%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s               | 1        | 1.28%   |
| Kingston RAM KHX1600C10D3L/8GX 8GB DIMM DDR3 1600MT/s             | 1        | 1.28%   |
| Kingston RAM KF548S38-16 16GB SODIMM DDR5 4800MT/s                | 1        | 1.28%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s               | 1        | 1.28%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s             | 1        | 1.28%   |
| Kingston RAM 99U5471-034.A00LF 4GB DIMM DDR3 1600MT/s             | 1        | 1.28%   |
| Kingston RAM 99U5403-123.A00LF 8GB DIMM DDR3 1600MT/s             | 1        | 1.28%   |
| Kingston RAM 99U5403-036.A00LF 4GB DIMM DDR3 1600MT/s             | 1        | 1.28%   |
| Kingston RAM 9965745-021.A00G 32GB DIMM DDR4 2933MT/s             | 1        | 1.28%   |
| Kingston RAM 9965684-028.A00G 8GB DIMM DDR4 3200MT/s              | 1        | 1.28%   |
| Kingston RAM 9965669-008.A03G 16GB DIMM DDR4 2134MT/s             | 1        | 1.28%   |
| Goodram RAM GR1600D364L9/4G 4096MB DIMM DDR3 1333MT/s             | 1        | 1.28%   |
| Goodram RAM GR1600D364L11/4G 4GB DIMM DDR3 1600MT/s               | 1        | 1.28%   |
| GLOWAY RAM VGM4UX32C18BG-DTACW 32GB DIMM DDR4 3200MT/s            | 1        | 1.28%   |
| G.Skill RAM F4-4000C18-16GTZN 16GB DIMM DDR4 4000MT/s             | 1        | 1.28%   |
| G.Skill RAM F4-3600C18-32GVK 32GB DIMM DDR4 3600MT/s              | 1        | 1.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 46       | 75.41%  |
| DDR3   | 11       | 18.03%  |
| DDR5   | 3        | 4.92%   |
| LPDDR4 | 1        | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 57       | 93.44%  |
| SODIMM | 3        | 4.92%   |
| RIMM   | 1        | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 29       | 42.03%  |
| 8192  | 22       | 31.88%  |
| 32768 | 12       | 17.39%  |
| 4096  | 6        | 8.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 15       | 21.13%  |
| 3600  | 9        | 12.68%  |
| 1600  | 9        | 12.68%  |
| 2133  | 6        | 8.45%   |
| 3000  | 5        | 7.04%   |
| 2400  | 5        | 7.04%   |
| 3733  | 4        | 5.63%   |
| 4800  | 2        | 2.82%   |
| 3400  | 2        | 2.82%   |
| 3334  | 2        | 2.82%   |
| 2933  | 2        | 2.82%   |
| 1333  | 2        | 2.82%   |
| 6000  | 1        | 1.41%   |
| 4000  | 1        | 1.41%   |
| 3866  | 1        | 1.41%   |
| 3666  | 1        | 1.41%   |
| 3534  | 1        | 1.41%   |
| 2800  | 1        | 1.41%   |
| 2134  | 1        | 1.41%   |
| 2132  | 1        | 1.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Xerox  | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Xerox Phaser 6125N | 1        | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Logitech     | 11       | 68.75%  |
| MacroSilicon | 3        | 18.75%  |
| Microdia     | 1        | 6.25%   |
| Apple        | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| MacroSilicon USB Video          | 3        | 18.75%  |
| Logitech Webcam C270            | 2        | 12.5%   |
| Logitech StreamCam              | 2        | 12.5%   |
| Microdia Camera                 | 1        | 6.25%   |
| Logitech Webcam Pro 9000        | 1        | 6.25%   |
| Logitech Webcam C930e           | 1        | 6.25%   |
| Logitech Webcam C120            | 1        | 6.25%   |
| Logitech HD Webcam C615         | 1        | 6.25%   |
| Logitech HD Pro Webcam C920     | 1        | 6.25%   |
| Logitech C930c                  | 1        | 6.25%   |
| Logitech C922 Pro Stream Webcam | 1        | 6.25%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X | 1        | 6.25%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| OmniKey | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| OmniKey CardMan Smart@Link | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 50       | 76.92%  |
| 1     | 11       | 16.92%  |
| 2     | 4        | 6.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 4        | 23.53%  |
| Graphics card         | 4        | 23.53%  |
| Unassigned class      | 3        | 17.65%  |
| Bluetooth             | 2        | 11.76%  |
| Multimedia controller | 1        | 5.88%   |
| Dvb card              | 1        | 5.88%   |
| Chipcard              | 1        | 5.88%   |
| Camera                | 1        | 5.88%   |

