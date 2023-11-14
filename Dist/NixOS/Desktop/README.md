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

Total: 100

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | X570-A PRO                  | [30416c0355](https://linux-hardware.org/?probe=30416c0355) | Nov 04, 2023 |
| HP            | 83E1                        | [c82d34ebac](https://linux-hardware.org/?probe=c82d34ebac) | Nov 04, 2023 |
| LattePanda    | Sigma                       | [d287cf2d8a](https://linux-hardware.org/?probe=d287cf2d8a) | Oct 26, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [387c91f530](https://linux-hardware.org/?probe=387c91f530) | Oct 26, 2023 |
| ECS           | A55F-M3                     | [6da483b400](https://linux-hardware.org/?probe=6da483b400) | Oct 25, 2023 |
| Unknown       | HX90                        | [f247716ab0](https://linux-hardware.org/?probe=f247716ab0) | Oct 13, 2023 |
| ASUSTek       | P7H55                       | [89472bd2f3](https://linux-hardware.org/?probe=89472bd2f3) | Oct 07, 2023 |
| ASRock        | Z87 Extreme4                | [642a2f5a9b](https://linux-hardware.org/?probe=642a2f5a9b) | Oct 04, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [007bb33fbf](https://linux-hardware.org/?probe=007bb33fbf) | Oct 01, 2023 |
| MSI           | Z68A-GD65                   | [c0f968740b](https://linux-hardware.org/?probe=c0f968740b) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [0177e96165](https://linux-hardware.org/?probe=0177e96165) | Sep 28, 2023 |
| HP            | 3397                        | [5c1b3bed0b](https://linux-hardware.org/?probe=5c1b3bed0b) | Sep 28, 2023 |
| ASUSTek       | P8H77-V                     | [24ff983f95](https://linux-hardware.org/?probe=24ff983f95) | Sep 28, 2023 |
| HP            | 1998                        | [4af6b915c2](https://linux-hardware.org/?probe=4af6b915c2) | Sep 17, 2023 |
| HP            | 8767 A                      | [ce91ccf3a9](https://linux-hardware.org/?probe=ce91ccf3a9) | Sep 09, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [ac09f27b9d](https://linux-hardware.org/?probe=ac09f27b9d) | Aug 22, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | [a9a56ae120](https://linux-hardware.org/?probe=a9a56ae120) | Aug 22, 2023 |
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
| NixOS 23.05                      | 22       | 26.83%  |
| NixOS 22.05                      | 13       | 15.85%  |
| NixOS 22.11                      | 12       | 14.63%  |
| NixOS 23.11                      | 10       | 12.2%   |
| NixOS 21.11                      | 7        | 8.54%   |
| NixOS                            | 3        | 3.66%   |
| NixOS 21.05pre-git               | 2        | 2.44%   |
| NixOS 21.11.20210528.540dccb     | 1        | 1.22%   |
| NixOS 21.05.993.93963c27b93      | 1        | 1.22%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1        | 1.22%   |
| NixOS 21.05.20210929.ee90403     | 1        | 1.22%   |
| NixOS 21.05.20210430.c8dff32     | 1        | 1.22%   |
| NixOS 21.05.20210224.f6b5bfd     | 1        | 1.22%   |
| NixOS 21.05.1471.a7512bb64b1     | 1        | 1.22%   |
| NixOS 21.03pre246062.420f89ceb26 | 1        | 1.22%   |
| NixOS 21.03.git.b4349c13a6d      | 1        | 1.22%   |
| NixOS 21.03.20201007.420f89c     | 1        | 1.22%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1        | 1.22%   |
| NixOS 20.09pre-git               | 1        | 1.22%   |
| NixOS 20.09.git.4a361b06a93      | 1        | 1.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| NixOS | 77       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Desktops | Percent |
|----------------|----------|---------|
| 6.1.55         | 4        | 4.6%    |
| 6.1.37         | 3        | 3.45%   |
| 6.4.7          | 2        | 2.3%    |
| 6.4.0          | 2        | 2.3%    |
| 5.8.1-zen1     | 2        | 2.3%    |
| 5.15.86        | 2        | 2.3%    |
| 5.15.85        | 2        | 2.3%    |
| 5.15.47        | 2        | 2.3%    |
| 5.10.102       | 2        | 2.3%    |
| 6.5.9-xanmod1  | 1        | 1.15%   |
| 6.5.7          | 1        | 1.15%   |
| 6.5.2          | 1        | 1.15%   |
| 6.5.1          | 1        | 1.15%   |
| 6.4.9          | 1        | 1.15%   |
| 6.4.4-cachyos  | 1        | 1.15%   |
| 6.4.4          | 1        | 1.15%   |
| 6.4.11-cachyos | 1        | 1.15%   |
| 6.3.3          | 1        | 1.15%   |
| 6.2.11-lqx3    | 1        | 1.15%   |
| 6.2.11         | 1        | 1.15%   |
| 6.2.10         | 1        | 1.15%   |
| 6.1.60         | 1        | 1.15%   |
| 6.1.59         | 1        | 1.15%   |
| 6.1.55-xanmod1 | 1        | 1.15%   |
| 6.1.51         | 1        | 1.15%   |
| 6.1.45         | 1        | 1.15%   |
| 6.1.42         | 1        | 1.15%   |
| 6.1.39         | 1        | 1.15%   |
| 6.1.31-xanmod1 | 1        | 1.15%   |
| 6.1.31         | 1        | 1.15%   |
| 6.1.27         | 1        | 1.15%   |
| 6.1.24         | 1        | 1.15%   |
| 6.1.14         | 1        | 1.15%   |
| 6.0.12         | 1        | 1.15%   |
| 6.0.11         | 1        | 1.15%   |
| 5.8.10         | 1        | 1.15%   |
| 5.7.19         | 1        | 1.15%   |
| 5.4.94         | 1        | 1.15%   |
| 5.4.72         | 1        | 1.15%   |
| 5.4.69         | 1        | 1.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 6.1.55   | 5        | 5.75%   |
| 6.1.37   | 3        | 3.45%   |
| 6.4.7    | 2        | 2.3%    |
| 6.4.4    | 2        | 2.3%    |
| 6.4.0    | 2        | 2.3%    |
| 6.2.11   | 2        | 2.3%    |
| 6.1.31   | 2        | 2.3%    |
| 5.8.1    | 2        | 2.3%    |
| 5.15.86  | 2        | 2.3%    |
| 5.15.85  | 2        | 2.3%    |
| 5.15.47  | 2        | 2.3%    |
| 5.11.16  | 2        | 2.3%    |
| 5.10.102 | 2        | 2.3%    |
| 6.5.9    | 1        | 1.15%   |
| 6.5.7    | 1        | 1.15%   |
| 6.5.2    | 1        | 1.15%   |
| 6.5.1    | 1        | 1.15%   |
| 6.4.9    | 1        | 1.15%   |
| 6.4.11   | 1        | 1.15%   |
| 6.3.3    | 1        | 1.15%   |
| 6.2.10   | 1        | 1.15%   |
| 6.1.60   | 1        | 1.15%   |
| 6.1.59   | 1        | 1.15%   |
| 6.1.51   | 1        | 1.15%   |
| 6.1.45   | 1        | 1.15%   |
| 6.1.42   | 1        | 1.15%   |
| 6.1.39   | 1        | 1.15%   |
| 6.1.27   | 1        | 1.15%   |
| 6.1.24   | 1        | 1.15%   |
| 6.1.14   | 1        | 1.15%   |
| 6.0.12   | 1        | 1.15%   |
| 6.0.11   | 1        | 1.15%   |
| 5.8.10   | 1        | 1.15%   |
| 5.7.19   | 1        | 1.15%   |
| 5.4.94   | 1        | 1.15%   |
| 5.4.72   | 1        | 1.15%   |
| 5.4.69   | 1        | 1.15%   |
| 5.4.50   | 1        | 1.15%   |
| 5.4.47   | 1        | 1.15%   |
| 5.19.14  | 1        | 1.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 22       | 26.19%  |
| 6.1     | 19       | 22.62%  |
| 5.10    | 9        | 10.71%  |
| 6.4     | 5        | 5.95%   |
| 5.4     | 5        | 5.95%   |
| 6.5     | 4        | 4.76%   |
| 6.2     | 3        | 3.57%   |
| 5.8     | 3        | 3.57%   |
| 6.0     | 2        | 2.38%   |
| 5.18    | 2        | 2.38%   |
| 5.11    | 2        | 2.38%   |
| 6.3     | 1        | 1.19%   |
| 5.7     | 1        | 1.19%   |
| 5.19    | 1        | 1.19%   |
| 5.17    | 1        | 1.19%   |
| 5.16    | 1        | 1.19%   |
| 5.14    | 1        | 1.19%   |
| 5.13    | 1        | 1.19%   |
| 5.12    | 1        | 1.19%   |

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


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Unknown      | 38       | 48.72%  |
| KDE5         | 11       | 14.1%   |
| GNOME        | 11       | 14.1%   |
| KDE          | 4        | 5.13%   |
| XFCE         | 3        | 3.85%   |
| sway         | 3        | 3.85%   |
| Hyprland     | 3        | 3.85%   |
| none+awesome | 2        | 2.56%   |
| none+i3      | 1        | 1.28%   |
| MATE         | 1        | 1.28%   |
| LXQt         | 1        | 1.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 44.3%   |
| X11     | 22       | 27.85%  |
| Wayland | 15       | 18.99%  |
| Tty     | 7        | 8.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 41       | 52.56%  |
| SDDM    | 15       | 19.23%  |
| LightDM | 11       | 14.1%   |
| GDM     | 11       | 14.1%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 34       | 44.16%  |
| Unknown    | 21       | 27.27%  |
| en_GB      | 8        | 10.39%  |
| en_AU      | 4        | 5.19%   |
| ru_RU      | 2        | 2.6%    |
| en_DK      | 2        | 2.6%    |
| pt_BR      | 1        | 1.3%    |
| it_IT      | 1        | 1.3%    |
| en_NZ      | 1        | 1.3%    |
| en_IE.UTF8 | 1        | 1.3%    |
| de_DE      | 1        | 1.3%    |
| de_CH      | 1        | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 65       | 83.33%  |
| BIOS | 13       | 16.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 46       | 59.74%  |
| Btrfs   | 11       | 14.29%  |
| Zfs     | 6        | 7.79%   |
| Tmpfs   | 6        | 7.79%   |
| Xfs     | 4        | 5.19%   |
| Unknown | 3        | 3.9%    |
| Ext2    | 1        | 1.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 73       | 94.81%  |
| MBR     | 2        | 2.6%    |
| Unknown | 2        | 2.6%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 72.15%  |
| Yes       | 22       | 27.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 60.26%  |
| Yes       | 31       | 39.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 28       | 36.36%  |
| MSI                                  | 13       | 16.88%  |
| Gigabyte Technology                  | 12       | 15.58%  |
| ASRock                               | 8        | 10.39%  |
| Hewlett-Packard                      | 5        | 6.49%   |
| Acer                                 | 3        | 3.9%    |
| Shenzhen Meigao Electronic Equipment | 1        | 1.3%    |
| LattePanda                           | 1        | 1.3%    |
| Hardkernel                           | 1        | 1.3%    |
| EVGA                                 | 1        | 1.3%    |
| ECS                                  | 1        | 1.3%    |
| Dell                                 | 1        | 1.3%    |
| AZW                                  | 1        | 1.3%    |
| Unknown                              | 1        | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| MSI MS-7C37                                | 3        | 3.9%    |
| ASUS All Series                            | 3        | 3.9%    |
| MSI MS-7C56                                | 2        | 2.6%    |
| Gigabyte B550I AORUS PRO AX                | 2        | 2.6%    |
| Gigabyte B450M DS3H                        | 2        | 2.6%    |
| ASUS ROG STRIX B550-F GAMING               | 2        | 2.6%    |
| ASRock Z87 Extreme4                        | 2        | 2.6%    |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.3%    |
| MSI MS-7C95                                | 1        | 1.3%    |
| MSI MS-7C91                                | 1        | 1.3%    |
| MSI MS-7C84                                | 1        | 1.3%    |
| MSI MS-7C35                                | 1        | 1.3%    |
| MSI MS-7B89                                | 1        | 1.3%    |
| MSI MS-7B09                                | 1        | 1.3%    |
| MSI MS-7758                                | 1        | 1.3%    |
| MSI MS-7681                                | 1        | 1.3%    |
| LattePanda Sigma                           | 1        | 1.3%    |
| HP Pavilion Gaming Desktop TG01-1xxx       | 1        | 1.3%    |
| HP EliteDesk 800 G4 SFF                    | 1        | 1.3%    |
| HP EliteDesk 800 G2 DM 35W                 | 1        | 1.3%    |
| HP EliteDesk 800 G1 SFF                    | 1        | 1.3%    |
| HP Compaq Elite 8300 SFF                   | 1        | 1.3%    |
| Hardkernel ODROID-H2                       | 1        | 1.3%    |
| Gigabyte X570 AORUS PRO                    | 1        | 1.3%    |
| Gigabyte X570 AORUS ELITE WIFI             | 1        | 1.3%    |
| Gigabyte X570 AORUS ELITE                  | 1        | 1.3%    |
| Gigabyte X470 AORUS ULTRA GAMING           | 1        | 1.3%    |
| Gigabyte TRX40 AORUS MASTER                | 1        | 1.3%    |
| Gigabyte H97M-D3H                          | 1        | 1.3%    |
| Gigabyte B760 GAMING X DDR4                | 1        | 1.3%    |
| Gigabyte B450M DS3H V2                     | 1        | 1.3%    |
| EVGA X299 FTW K                            | 1        | 1.3%    |
| ECS A55F-M3                                | 1        | 1.3%    |
| Dell Precision Tower 7810                  | 1        | 1.3%    |
| AZW EQ                                     | 1        | 1.3%    |
| ASUS Z170-P                                | 1        | 1.3%    |
| ASUS TUF Gaming X570-PLUS                  | 1        | 1.3%    |
| ASUS TUF Gaming B660-PLUS WIFI D4          | 1        | 1.3%    |
| ASUS SABERTOOTH 990FX R2.0                 | 1        | 1.3%    |
| ASUS ROG STRIX Z690-A GAMING WIFI D4       | 1        | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 8        | 10.39%  |
| ASUS ROG                                   | 7        | 9.09%   |
| MSI MS-7C37                                | 3        | 3.9%    |
| HP EliteDesk                               | 3        | 3.9%    |
| Gigabyte X570                              | 3        | 3.9%    |
| Gigabyte B450M                             | 3        | 3.9%    |
| ASUS All                                   | 3        | 3.9%    |
| MSI MS-7C56                                | 2        | 2.6%    |
| Gigabyte B550I                             | 2        | 2.6%    |
| ASUS TUF                                   | 2        | 2.6%    |
| ASRock Z87                                 | 2        | 2.6%    |
| Acer Aspire                                | 2        | 2.6%    |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.3%    |
| MSI MS-7C95                                | 1        | 1.3%    |
| MSI MS-7C91                                | 1        | 1.3%    |
| MSI MS-7C84                                | 1        | 1.3%    |
| MSI MS-7C35                                | 1        | 1.3%    |
| MSI MS-7B89                                | 1        | 1.3%    |
| MSI MS-7B09                                | 1        | 1.3%    |
| MSI MS-7758                                | 1        | 1.3%    |
| MSI MS-7681                                | 1        | 1.3%    |
| LattePanda Sigma                           | 1        | 1.3%    |
| HP Pavilion                                | 1        | 1.3%    |
| HP Compaq                                  | 1        | 1.3%    |
| Hardkernel ODROID-H2                       | 1        | 1.3%    |
| Gigabyte X470                              | 1        | 1.3%    |
| Gigabyte TRX40                             | 1        | 1.3%    |
| Gigabyte H97M-D3H                          | 1        | 1.3%    |
| Gigabyte B760                              | 1        | 1.3%    |
| EVGA X299                                  | 1        | 1.3%    |
| ECS A55F-M3                                | 1        | 1.3%    |
| Dell Precision                             | 1        | 1.3%    |
| AZW EQ                                     | 1        | 1.3%    |
| ASUS Z170-P                                | 1        | 1.3%    |
| ASUS SABERTOOTH                            | 1        | 1.3%    |
| ASUS PRO602617                             | 1        | 1.3%    |
| ASUS PRO-Q77                               | 1        | 1.3%    |
| ASUS Pro                                   | 1        | 1.3%    |
| ASUS P8Z77-V                               | 1        | 1.3%    |
| ASUS P8H77-V                               | 1        | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 18       | 23.38%  |
| 2019 | 12       | 15.58%  |
| 2018 | 10       | 12.99%  |
| 2012 | 6        | 7.79%   |
| 2022 | 4        | 5.19%   |
| 2017 | 4        | 5.19%   |
| 2016 | 4        | 5.19%   |
| 2014 | 4        | 5.19%   |
| 2013 | 4        | 5.19%   |
| 2023 | 3        | 3.9%    |
| 2021 | 2        | 2.6%    |
| 2015 | 2        | 2.6%    |
| 2011 | 2        | 2.6%    |
| 2010 | 1        | 1.3%    |
| 2008 | 1        | 1.3%    |

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


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 25       | 32.47%  |
| 64.01-256.0     | 20       | 25.97%  |
| 16.01-24.0      | 15       | 19.48%  |
| 24.01-32.0      | 6        | 7.79%   |
| 8.01-16.0       | 5        | 6.49%   |
| 4.01-8.0        | 4        | 5.19%   |
| More than 256.0 | 1        | 1.3%    |
| 3.01-4.0        | 1        | 1.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 23       | 28.4%   |
| 8.01-16.0  | 18       | 22.22%  |
| 1.01-2.0   | 11       | 13.58%  |
| 3.01-4.0   | 9        | 11.11%  |
| 32.01-64.0 | 6        | 7.41%   |
| 2.01-3.0   | 6        | 7.41%   |
| 16.01-24.0 | 6        | 7.41%   |
| 24.01-32.0 | 1        | 1.23%   |
| 0.51-1.0   | 1        | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 24       | 28.92%  |
| 1      | 24       | 28.92%  |
| 3      | 17       | 20.48%  |
| 5      | 5        | 6.02%   |
| 4      | 5        | 6.02%   |
| 6      | 4        | 4.82%   |
| 23     | 1        | 1.2%    |
| 8      | 1        | 1.2%    |
| 7      | 1        | 1.2%    |
| 0      | 1        | 1.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 82.05%  |
| Yes       | 14       | 17.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 77       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 55.7%   |
| Yes       | 35       | 44.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 52.56%  |
| Yes       | 37       | 47.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 15       | 19.48%  |
| Germany     | 12       | 15.58%  |
| UK          | 7        | 9.09%   |
| Russia      | 6        | 7.79%   |
| Australia   | 4        | 5.19%   |
| Poland      | 3        | 3.9%    |
| Italy       | 3        | 3.9%    |
| France      | 3        | 3.9%    |
| Canada      | 3        | 3.9%    |
| Ukraine     | 2        | 2.6%    |
| Denmark     | 2        | 2.6%    |
| Brazil      | 2        | 2.6%    |
| Austria     | 2        | 2.6%    |
| Taiwan      | 1        | 1.3%    |
| Switzerland | 1        | 1.3%    |
| Slovenia    | 1        | 1.3%    |
| Serbia      | 1        | 1.3%    |
| Philippines | 1        | 1.3%    |
| Norway      | 1        | 1.3%    |
| New Zealand | 1        | 1.3%    |
| Netherlands | 1        | 1.3%    |
| Mexico      | 1        | 1.3%    |
| Ireland     | 1        | 1.3%    |
| India       | 1        | 1.3%    |
| Hungary     | 1        | 1.3%    |
| Belgium     | 1        | 1.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Vienna            | 2        | 2.53%   |
| Schaafheim        | 2        | 2.53%   |
| Ramenskoye        | 2        | 2.53%   |
| Plymouth          | 2        | 2.53%   |
| Perth             | 2        | 2.53%   |
| Marki             | 2        | 2.53%   |
| Kharkiv           | 2        | 2.53%   |
| Hamburg           | 2        | 2.53%   |
| Darmstadt         | 2        | 2.53%   |
| Bochum            | 2        | 2.53%   |
| Austin            | 2        | 2.53%   |
| Wellington        | 1        | 1.27%   |
| Tobercurry        | 1        | 1.27%   |
| Taichung          | 1        | 1.27%   |
| Székesfehérvár | 1        | 1.27%   |
| Southampton       | 1        | 1.27%   |
| South Deerfield   | 1        | 1.27%   |
| Sorocaba          | 1        | 1.27%   |
| Sindelfingen      | 1        | 1.27%   |
| San Juan          | 1        | 1.27%   |
| San Gabriel       | 1        | 1.27%   |
| Saarbrücken      | 1        | 1.27%   |
| Richardson        | 1        | 1.27%   |
| Redwood City      | 1        | 1.27%   |
| Pisa              | 1        | 1.27%   |
| Paris             | 1        | 1.27%   |
| Palm Bay          | 1        | 1.27%   |
| Oslo              | 1        | 1.27%   |
| Osasco            | 1        | 1.27%   |
| Oakville          | 1        | 1.27%   |
| Norwich           | 1        | 1.27%   |
| North Andover     | 1        | 1.27%   |
| Moscow            | 1        | 1.27%   |
| Montreal          | 1        | 1.27%   |
| Mexico City       | 1        | 1.27%   |
| Melrose           | 1        | 1.27%   |
| Melbourne         | 1        | 1.27%   |
| Los Angeles       | 1        | 1.27%   |
| Ljubljana         | 1        | 1.27%   |
| Lille             | 1        | 1.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 42       | 75     | 28%     |
| WDC                         | 20       | 38     | 13.33%  |
| Seagate                     | 20       | 30     | 13.33%  |
| SanDisk                     | 11       | 15     | 7.33%   |
| Toshiba                     | 9        | 20     | 6%      |
| Crucial                     | 9        | 10     | 6%      |
| Phison Electronics          | 5        | 7      | 3.33%   |
| Kingston                    | 5        | 5      | 3.33%   |
| Intel                       | 5        | 7      | 3.33%   |
| Realtek Semiconductor       | 2        | 5      | 1.33%   |
| Hitachi                     | 2        | 4      | 1.33%   |
| HGST                        | 2        | 4      | 1.33%   |
| Corsair                     | 2        | 2      | 1.33%   |
| ZHITAI                      | 1        | 1      | 0.67%   |
| Yangtze Memory Technologies | 1        | 2      | 0.67%   |
| Team                        | 1        | 1      | 0.67%   |
| SPCC                        | 1        | 1      | 0.67%   |
| SK hynix                    | 1        | 1      | 0.67%   |
| Silicon Motion              | 1        | 1      | 0.67%   |
| Plextor                     | 1        | 1      | 0.67%   |
| Phison                      | 1        | 1      | 0.67%   |
| OCZ                         | 1        | 1      | 0.67%   |
| MBED                        | 1        | 1      | 0.67%   |
| MAXIO Technology (Hangzhou) | 1        | 2      | 0.67%   |
| Lexar                       | 1        | 1      | 0.67%   |
| Kingston Technology Company | 1        | 1      | 0.67%   |
| China                       | 1        | 1      | 0.67%   |
| ASMT                        | 1        | 1      | 0.67%   |
| A-DATA Technology           | 1        | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB                          | 5        | 2.63%   |
| Samsung SSD 860 QVO 1TB                            | 4        | 2.11%   |
| Samsung SSD 860 EVO 1TB                            | 4        | 2.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4        | 2.11%   |
| Seagate ST3000DM001-1ER166 3TB                     | 3        | 1.58%   |
| SanDisk SSD PLUS 240GB                             | 3        | 1.58%   |
| Samsung SSD 970 EVO Plus 2TB                       | 3        | 1.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3        | 1.58%   |
| Seagate ST3000DM001-1CH166 3TB                     | 2        | 1.05%   |
| Seagate ST1000DM003-1CH162 1TB                     | 2        | 1.05%   |
| Sandisk WD_BLACK SN770 500GB                       | 2        | 1.05%   |
| Samsung SSD 990 PRO 1TB                            | 2        | 1.05%   |
| Samsung SSD 980 PRO 1TB                            | 2        | 1.05%   |
| Samsung SSD 980 1TB                                | 2        | 1.05%   |
| Samsung SSD 970 EVO Plus 1TB                       | 2        | 1.05%   |
| Samsung SSD 970 EVO 500GB                          | 2        | 1.05%   |
| Samsung SSD 970 EVO 1TB                            | 2        | 1.05%   |
| Samsung SSD 860 EVO 2TB                            | 2        | 1.05%   |
| Samsung SSD 860 EVO 250GB                          | 2        | 1.05%   |
| Samsung NVMe SSD Drive 1TB                         | 2        | 1.05%   |
| Phison E16 PCIe4 NVMe Controller 500GB             | 2        | 1.05%   |
| Crucial CT1000MX500SSD1 1TB                        | 2        | 1.05%   |
| ZHITAI SC001 Active 512GB SSD                      | 1        | 0.53%   |
| Yangtze Memory ZHITAI TiPro7000 1TB                | 1        | 0.53%   |
| Yangtze Memory ZHITAI TiPlus7100 1TB               | 1        | 0.53%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 1        | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                   | 1        | 0.53%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                     | 1        | 0.53%   |
| WDC WD80EMAZ-00WJTA0 8TB                           | 1        | 0.53%   |
| WDC WD80EDAZ-11TA3A0 8TB                           | 1        | 0.53%   |
| WDC WD50EZRX-00MVLB1 5TB                           | 1        | 0.53%   |
| WDC WD40EFRX-68N32N0 4TB                           | 1        | 0.53%   |
| WDC WD3200BPVT-22JJ5T0 320GB                       | 1        | 0.53%   |
| WDC WD30EZRX-00SPEB0 3TB                           | 1        | 0.53%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 1        | 0.53%   |
| WDC WD20EZRX-00D8PB0 2TB                           | 1        | 0.53%   |
| WDC WD20EZBX-00AYRA0 2TB                           | 1        | 0.53%   |
| WDC WD20EARX-00PASB0 2TB                           | 1        | 0.53%   |
| WDC WD20EARX-008FB0 2TB                            | 1        | 0.53%   |
| WDC WD1600AAJS-62B4A0 160GB                        | 1        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 30     | 37.74%  |
| WDC                 | 19       | 34     | 35.85%  |
| Toshiba             | 8        | 16     | 15.09%  |
| Samsung Electronics | 2        | 2      | 3.77%   |
| Hitachi             | 2        | 4      | 3.77%   |
| HGST                | 2        | 4      | 3.77%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 20       | 33     | 35.71%  |
| Crucial             | 9        | 10     | 16.07%  |
| SanDisk             | 6        | 9      | 10.71%  |
| Kingston            | 4        | 4      | 7.14%   |
| Intel               | 4        | 6      | 7.14%   |
| WDC                 | 3        | 4      | 5.36%   |
| Corsair             | 2        | 2      | 3.57%   |
| ZHITAI              | 1        | 1      | 1.79%   |
| Toshiba             | 1        | 1      | 1.79%   |
| Team                | 1        | 1      | 1.79%   |
| SPCC                | 1        | 1      | 1.79%   |
| OCZ                 | 1        | 1      | 1.79%   |
| China               | 1        | 1      | 1.79%   |
| ASMT                | 1        | 1      | 1.79%   |
| A-DATA Technology   | 1        | 1      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 48       | 73     | 36.64%  |
| SSD     | 47       | 76     | 35.88%  |
| HDD     | 35       | 90     | 26.72%  |
| Unknown | 1        | 1      | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 59       | 164    | 53.64%  |
| NVMe | 48       | 73     | 43.64%  |
| SAS  | 3        | 3      | 2.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 35       | 51     | 36.46%  |
| 0.51-1.0   | 30       | 55     | 31.25%  |
| 1.01-2.0   | 11       | 16     | 11.46%  |
| 4.01-10.0  | 10       | 25     | 10.42%  |
| 2.01-3.0   | 7        | 13     | 7.29%   |
| 3.01-4.0   | 3        | 6      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 25       | 32.05%  |
| 1-20           | 9        | 11.54%  |
| 501-1000       | 9        | 11.54%  |
| More than 3000 | 8        | 10.26%  |
| 251-500        | 8        | 10.26%  |
| 101-250        | 8        | 10.26%  |
| 1001-2000      | 7        | 8.97%   |
| 2001-3000      | 4        | 5.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 25       | 31.25%  |
| 1-20           | 15       | 18.75%  |
| 101-250        | 9        | 11.25%  |
| 51-100         | 7        | 8.75%   |
| 501-1000       | 6        | 7.5%    |
| More than 3000 | 4        | 5%      |
| 251-500        | 4        | 5%      |
| 1001-2000      | 4        | 5%      |
| 21-50          | 3        | 3.75%   |
| 2001-3000      | 3        | 3.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                          | Desktops | Drives | Percent |
|----------------------------------------------------------------|----------|--------|---------|
| WDC WD30EZRX-00SPEB0 3TB                                       | 1        | 1      | 6.25%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                       | 1        | 1      | 6.25%   |
| WDC WD20EARX-008FB0 2TB                                        | 1        | 1      | 6.25%   |
| WDC WD10EZEX-60ZF5A0 1TB                                       | 1        | 1      | 6.25%   |
| Seagate ST8000VN0022-2EL112 8TB                                | 1        | 1      | 6.25%   |
| Seagate ST3500418AS 500GB                                      | 1        | 1      | 6.25%   |
| SanDisk SSD PLUS 240GB                                         | 1        | 1      | 6.25%   |
| Samsung Electronics SSD 970 EVO 1TB                            | 1        | 1      | 6.25%   |
| Samsung Electronics SSD 870 EVO 1TB                            | 1        | 1      | 6.25%   |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1        | 1      | 6.25%   |
| Intel SSDSC2BW240A4 240GB                                      | 1        | 1      | 6.25%   |
| Hitachi HDS722020ALA330 2TB                                    | 1        | 1      | 6.25%   |
| HGST HTS545050A7E680 500GB                                     | 1        | 1      | 6.25%   |
| Crucial CT240M500SSD1 240GB                                    | 1        | 1      | 6.25%   |
| Corsair Neutron XT SSD 240GB                                   | 1        | 1      | 6.25%   |
| ASMT 2115 1TB                                                  | 1        | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 25%     |
| Samsung Electronics | 3        | 3      | 18.75%  |
| Seagate             | 2        | 2      | 12.5%   |
| SanDisk             | 1        | 1      | 6.25%   |
| Intel               | 1        | 1      | 6.25%   |
| Hitachi             | 1        | 1      | 6.25%   |
| HGST                | 1        | 1      | 6.25%   |
| Crucial             | 1        | 1      | 6.25%   |
| Corsair             | 1        | 1      | 6.25%   |
| ASMT                | 1        | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 4      | 50%     |
| Seagate | 2        | 2      | 25%     |
| Hitachi | 1        | 1      | 12.5%   |
| HGST    | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 8      | 46.67%  |
| SSD  | 6        | 6      | 40%     |
| NVMe | 2        | 2      | 13.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                       | Desktops | Drives | Percent |
|---------------------------------------------|----------|--------|---------|
| Toshiba MG03ACA300 3TB                      | 1        | 1      | 33.33%  |
| Toshiba HDWG180 8TB                         | 1        | 4      | 33.33%  |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Toshiba  | 2        | 5      | 66.67%  |
| SK hynix | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 73       | 201    | 76.84%  |
| Malfunc  | 11       | 16     | 11.58%  |
| Detected | 8        | 17     | 8.42%   |
| Failed   | 3        | 6      | 3.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 41       | 29.93%  |
| Intel                        | 34       | 24.82%  |
| Samsung Electronics          | 27       | 19.71%  |
| ASMedia Technology           | 9        | 6.57%   |
| Phison Electronics           | 6        | 4.38%   |
| SanDisk                      | 5        | 3.65%   |
| Realtek Semiconductor        | 2        | 1.46%   |
| LSI Logic / Symbios Logic    | 2        | 1.46%   |
| Kingston Technology Company  | 2        | 1.46%   |
| Yangtze Memory Technologies  | 1        | 0.73%   |
| Toshiba America Info Systems | 1        | 0.73%   |
| SK hynix                     | 1        | 0.73%   |
| Silicon Motion               | 1        | 0.73%   |
| Shenzhen Longsys Electronics | 1        | 0.73%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.73%   |
| Marvell Technology Group     | 1        | 0.73%   |
| Lite-On Technology           | 1        | 0.73%   |
| Broadcom / LSI               | 1        | 0.73%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 25       | 16.13%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 16       | 10.32%  |
| AMD 500 Series Chipset SATA Controller                                         | 12       | 7.74%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 9        | 5.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6        | 3.87%   |
| AMD 400 Series Chipset SATA Controller                                         | 6        | 3.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 2.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 2.58%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 2.58%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3        | 1.94%   |
| Phison E12 NVMe Controller                                                     | 3        | 1.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 1.94%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2        | 1.29%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2        | 1.29%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 1.29%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 2        | 1.29%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 1.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.29%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 1.29%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 1.29%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 1.29%   |
| Yangtze Memory ZHITAI TiPro7000                                                | 1        | 0.65%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 1        | 0.65%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 1        | 0.65%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1        | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.65%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 1        | 0.65%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1        | 0.65%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1        | 0.65%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1        | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.65%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1        | 0.65%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 1        | 0.65%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1        | 0.65%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1        | 0.65%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                     | 1        | 0.65%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.65%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                 | 1        | 0.65%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 72       | 54.96%  |
| NVMe | 48       | 36.64%  |
| RAID | 4        | 3.05%   |
| IDE  | 4        | 3.05%   |
| SAS  | 3        | 2.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 42       | 54.55%  |
| Intel  | 35       | 45.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 6        | 7.79%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 4        | 5.19%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 3        | 3.9%    |
| AMD Ryzen 7 3800X 8-Core Processor             | 3        | 3.9%    |
| AMD Ryzen 5 5600G with Radeon Graphics         | 3        | 3.9%    |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 2.6%    |
| Intel Core i7-8700 CPU @ 3.20GHz               | 2        | 2.6%    |
| Intel Core i7-4770 CPU @ 3.40GHz               | 2        | 2.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz               | 2        | 2.6%    |
| AMD Ryzen 5 5600X 6-Core Processor             | 2        | 2.6%    |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 2.6%    |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 2.6%    |
| Intel Xeon W-1290P CPU @ 3.70GHz               | 1        | 1.3%    |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz            | 1        | 1.3%    |
| Intel Core i9-9900X CPU @ 3.50GHz              | 1        | 1.3%    |
| Intel Core i7-6850K CPU @ 3.60GHz              | 1        | 1.3%    |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 1.3%    |
| Intel Core i7-4770K CPU @ 3.50GHz              | 1        | 1.3%    |
| Intel Core i7-3770K CPU @ 3.50GHz              | 1        | 1.3%    |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 1.3%    |
| Intel Core i7-2600K CPU @ 3.40GHz              | 1        | 1.3%    |
| Intel Core i5-8400 CPU @ 2.80GHz               | 1        | 1.3%    |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 1.3%    |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 1.3%    |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1        | 1.3%    |
| Intel Core i5-4570S CPU @ 2.90GHz              | 1        | 1.3%    |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.3%    |
| Intel Core i5-3570K CPU @ 3.40GHz              | 1        | 1.3%    |
| Intel Core i5-3470T CPU @ 2.90GHz              | 1        | 1.3%    |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1        | 1.3%    |
| Intel Core i5-10400 CPU @ 2.90GHz              | 1        | 1.3%    |
| Intel Core i5 CPU 760 @ 2.80GHz                | 1        | 1.3%    |
| Intel Core i3-N305                             | 1        | 1.3%    |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1        | 1.3%    |
| Intel Celeron J4105 CPU @ 1.50GHz              | 1        | 1.3%    |
| Intel 13th Gen Core i9-13900K                  | 1        | 1.3%    |
| Intel 13th Gen Core i5-13600KF                 | 1        | 1.3%    |
| Intel 13th Gen Core i5-1340P                   | 1        | 1.3%    |
| Intel 12th Gen Core i9-12900K                  | 1        | 1.3%    |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1        | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 16       | 20.78%  |
| Intel Core i5          | 13       | 16.88%  |
| Intel Core i7          | 12       | 15.58%  |
| AMD Ryzen 9            | 11       | 14.29%  |
| AMD Ryzen 7            | 10       | 12.99%  |
| Other                  | 4        | 5.19%   |
| AMD Ryzen Threadripper | 3        | 3.9%    |
| Intel Xeon             | 2        | 2.6%    |
| Intel Core i3          | 2        | 2.6%    |
| Intel Core i9          | 1        | 1.3%    |
| Intel Celeron          | 1        | 1.3%    |
| AMD FX                 | 1        | 1.3%    |
| AMD Athlon II X4       | 1        | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 23       | 29.87%  |
| 4      | 20       | 25.97%  |
| 8      | 13       | 16.88%  |
| 16     | 6        | 7.79%   |
| 12     | 6        | 7.79%   |
| 24     | 3        | 3.9%    |
| 10     | 2        | 2.6%    |
| 2      | 2        | 2.6%    |
| 32     | 1        | 1.3%    |
| 14     | 1        | 1.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 76       | 98.7%   |
| 2      | 1        | 1.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 64       | 83.12%  |
| 1      | 13       | 16.88%  |

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
| Unknown    | 11       | 13.92%  |
| 0x08701021 | 8        | 10.13%  |
| 0x306c3    | 7        | 8.86%   |
| 0x306a9    | 6        | 7.59%   |
| 0x906ea    | 4        | 5.06%   |
| 0x08701013 | 4        | 5.06%   |
| 0x0a50000d | 3        | 3.8%    |
| 0xa0653    | 2        | 2.53%   |
| 0x506e3    | 2        | 2.53%   |
| 0x0a601203 | 2        | 2.53%   |
| 0x0a50000c | 2        | 2.53%   |
| 0x0a20120a | 2        | 2.53%   |
| 0x0a201204 | 2        | 2.53%   |
| 0x0a201025 | 2        | 2.53%   |
| 0x0a201016 | 2        | 2.53%   |
| 0x0a201009 | 2        | 2.53%   |
| 0x08001138 | 2        | 2.53%   |
| 0xb06a2    | 1        | 1.27%   |
| 0x906e9    | 1        | 1.27%   |
| 0x90672    | 1        | 1.27%   |
| 0x406f1    | 1        | 1.27%   |
| 0x306f2    | 1        | 1.27%   |
| 0x206a7    | 1        | 1.27%   |
| 0x106e5    | 1        | 1.27%   |
| 0x0a601201 | 1        | 1.27%   |
| 0x0a404102 | 1        | 1.27%   |
| 0x08301055 | 1        | 1.27%   |
| 0x08301025 | 1        | 1.27%   |
| 0x08108109 | 1        | 1.27%   |
| 0x0800820d | 1        | 1.27%   |
| 0x08001137 | 1        | 1.27%   |
| 0x06000852 | 1        | 1.27%   |
| 0x03000027 | 1        | 1.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 15       | 19.48%  |
| Zen 2            | 15       | 19.48%  |
| Haswell          | 8        | 10.39%  |
| KabyLake         | 6        | 7.79%   |
| IvyBridge        | 6        | 7.79%   |
| Alderlake Hybrid | 4        | 5.19%   |
| Unknown          | 4        | 5.19%   |
| Zen+             | 3        | 3.9%    |
| Zen              | 3        | 3.9%    |
| Skylake          | 3        | 3.9%    |
| CometLake        | 3        | 3.9%    |
| SandyBridge      | 1        | 1.3%    |
| Piledriver       | 1        | 1.3%    |
| Nehalem          | 1        | 1.3%    |
| K10 Llano        | 1        | 1.3%    |
| Gracemont        | 1        | 1.3%    |
| Goldmont plus    | 1        | 1.3%    |
| Broadwell        | 1        | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 36       | 42.35%  |
| AMD    | 33       | 38.82%  |
| Intel  | 16       | 18.82%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 8.05%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 6.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 4.6%    |
| Nvidia TU106 [GeForce RTX 2070]                                             | 3        | 3.45%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 3.45%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 3.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 2.3%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 2.3%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.3%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.3%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 2.3%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 2.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.3%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 2.3%    |
| Intel HD Graphics 530                                                       | 2        | 2.3%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 2.3%    |
| AMD Raphael                                                                 | 2        | 2.3%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 2.3%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.15%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.15%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.15%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.15%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.15%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.15%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.15%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.15%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 1.15%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.15%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                           | 1        | 1.15%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.15%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.15%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.15%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.15%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 1        | 1.15%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 1        | 1.15%   |
| Intel HD Graphics 630                                                       | 1        | 1.15%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 28       | 36.36%  |
| 1 x AMD        | 27       | 35.06%  |
| 1 x Intel      | 11       | 14.29%  |
| Intel + Nvidia | 4        | 5.19%   |
| AMD + Nvidia   | 4        | 5.19%   |
| 2 x AMD        | 2        | 2.6%    |
| Other          | 1        | 1.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 45       | 58.44%  |
| Proprietary | 28       | 36.36%  |
| Unknown     | 4        | 5.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 47       | 60.26%  |
| 7.01-8.0   | 14       | 17.95%  |
| 8.01-16.0  | 6        | 7.69%   |
| 0.01-0.5   | 4        | 5.13%   |
| 1.01-2.0   | 3        | 3.85%   |
| 3.01-4.0   | 2        | 2.56%   |
| 16.01-24.0 | 1        | 1.28%   |
| 0.51-1.0   | 1        | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 16       | 20.51%  |
| Goldstar             | 14       | 17.95%  |
| Acer                 | 9        | 11.54%  |
| Samsung Electronics  | 6        | 7.69%   |
| Iiyama               | 4        | 5.13%   |
| Hewlett-Packard      | 4        | 5.13%   |
| Ancor Communications | 4        | 5.13%   |
| ViewSonic            | 3        | 3.85%   |
| AOC                  | 3        | 3.85%   |
| Philips              | 2        | 2.56%   |
| Gigabyte Technology  | 2        | 2.56%   |
| BenQ                 | 2        | 2.56%   |
| Vizio                | 1        | 1.28%   |
| Valve                | 1        | 1.28%   |
| Unknown (AAA)        | 1        | 1.28%   |
| RTK                  | 1        | 1.28%   |
| NEC Computers        | 1        | 1.28%   |
| MSI                  | 1        | 1.28%   |
| MPI                  | 1        | 1.28%   |
| Lenovo               | 1        | 1.28%   |
| HVR                  | 1        | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2        | 2.44%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 2        | 2.44%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                     | 2        | 2.44%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                    | 2        | 2.44%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                 | 2        | 2.44%   |
| Vizio E550i-B2 VIZ1004 1920x1080 477x268mm 21.5-inch                 | 1        | 1.22%   |
| ViewSonic VX2758-SERIES VSCA738 2560x1440 598x336mm 27.0-inch        | 1        | 1.22%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch        | 1        | 1.22%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch             | 1        | 1.22%   |
| Valve Index HMD VLV91A8                                              | 1        | 1.22%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch          | 1        | 1.22%   |
| Samsung Electronics SyncMaster SAM0613 1920x1080                     | 1        | 1.22%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch | 1        | 1.22%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch    | 1        | 1.22%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 698x393mm 31.5-inch   | 1        | 1.22%   |
| RTK TYPE C RTKBC32 2560x1600 347x215mm 16.1-inch                     | 1        | 1.22%   |
| Philips PHL BDM4065 PHL08E1 3840x2160 878x485mm 39.5-inch            | 1        | 1.22%   |
| Philips PHL 272V8 PHLC21A 1920x1080 598x336mm 27.0-inch              | 1        | 1.22%   |
| NEC Computers 90GX2 NEC6692 1280x1024 376x301mm 19.0-inch            | 1        | 1.22%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                       | 1        | 1.22%   |
| MPI WIMAXIT MPI7002 1920x1080 180x130mm 8.7-inch                     | 1        | 1.22%   |
| Lenovo L27q-35 LEN66D5 2560x1440 597x336mm 27.0-inch                 | 1        | 1.22%   |
| Iiyama PLX2481H IVM611D 1920x1080 521x293mm 23.5-inch                | 1        | 1.22%   |
| Iiyama PLE481 IVM480A 1280x1024 376x301mm 19.0-inch                  | 1        | 1.22%   |
| Iiyama PLE2208HDS IVM560A 1920x1080 477x268mm 21.5-inch              | 1        | 1.22%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x330mm 34.1-inch                | 1        | 1.22%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                 | 1        | 1.22%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                       | 1        | 1.22%   |
| Hewlett-Packard X34 HPN3728 3440x1440 800x335mm 34.1-inch            | 1        | 1.22%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch         | 1        | 1.22%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch           | 1        | 1.22%   |
| Hewlett-Packard 27xq HPN3582 2560x1440 597x336mm 27.0-inch           | 1        | 1.22%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch             | 1        | 1.22%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 677x290mm 29.0-inch             | 1        | 1.22%   |
| Goldstar ULTRAGEAR+ GSM5C34 2560x1440 590x333mm 26.7-inch            | 1        | 1.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 1        | 1.22%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 1.22%   |
| Goldstar M228WA GSM563D 1680x1050 434x270mm 20.1-inch                | 1        | 1.22%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch          | 1        | 1.22%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 1        | 1.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 26       | 36.11%  |
| 3840x2160 (4K)     | 14       | 19.44%  |
| 2560x1440 (QHD)    | 11       | 15.28%  |
| 1280x1024 (SXGA)   | 6        | 8.33%   |
| 2560x1080          | 4        | 5.56%   |
| 3440x1440          | 3        | 4.17%   |
| 1680x1050 (WSXGA+) | 2        | 2.78%   |
| 2560x1600          | 1        | 1.39%   |
| 2160x1200          | 1        | 1.39%   |
| 1920x1200 (WUXGA)  | 1        | 1.39%   |
| 1600x900 (HD+)     | 1        | 1.39%   |
| 1280x720 (HD)      | 1        | 1.39%   |
| Unknown            | 1        | 1.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 18       | 24.32%  |
| 23      | 12       | 16.22%  |
| 24      | 11       | 14.86%  |
| 34      | 7        | 9.46%   |
| 21      | 4        | 5.41%   |
| 19      | 4        | 5.41%   |
| 31      | 3        | 4.05%   |
| 25      | 2        | 2.7%    |
| 20      | 2        | 2.7%    |
| 17      | 2        | 2.7%    |
| Unknown | 2        | 2.7%    |
| 54      | 1        | 1.35%   |
| 39      | 1        | 1.35%   |
| 38      | 1        | 1.35%   |
| 28      | 1        | 1.35%   |
| 26      | 1        | 1.35%   |
| 22      | 1        | 1.35%   |
| 14      | 1        | 1.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 40       | 57.14%  |
| 701-800     | 7        | 10%     |
| 401-500     | 7        | 10%     |
| 601-700     | 4        | 5.71%   |
| 351-400     | 4        | 5.71%   |
| 801-900     | 2        | 2.86%   |
| 301-350     | 2        | 2.86%   |
| Unknown     | 2        | 2.86%   |
| 201-300     | 1        | 1.43%   |
| 1001-1500   | 1        | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 46       | 68.66%  |
| 21/9    | 7        | 10.45%  |
| 16/10   | 6        | 8.96%   |
| 5/4     | 5        | 7.46%   |
| 6/5     | 1        | 1.49%   |
| 1.00    | 1        | 1.49%   |
| Unknown | 1        | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 28.77%  |
| 301-350        | 19       | 26.03%  |
| 351-500        | 11       | 15.07%  |
| 151-200        | 8        | 10.96%  |
| 251-300        | 6        | 8.22%   |
| 141-150        | 2        | 2.74%   |
| 501-1000       | 2        | 2.74%   |
| Unknown        | 2        | 2.74%   |
| More than 1000 | 1        | 1.37%   |
| 101-110        | 1        | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 36       | 52.94%  |
| 101-120 | 19       | 27.94%  |
| 161-240 | 7        | 10.29%  |
| 121-160 | 3        | 4.41%   |
| Unknown | 2        | 2.94%   |
| 1-50    | 1        | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 46       | 59.74%  |
| 2     | 16       | 20.78%  |
| 0     | 11       | 14.29%  |
| 3     | 4        | 5.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 45       | 39.47%  |
| Realtek Semiconductor | 44       | 38.6%   |
| MediaTek              | 5        | 4.39%   |
| Aquantia              | 5        | 4.39%   |
| Qualcomm Atheros      | 3        | 2.63%   |
| Ralink Technology     | 2        | 1.75%   |
| TP-Link               | 1        | 0.88%   |
| Texas Instruments     | 1        | 0.88%   |
| STMicroelectronics    | 1        | 0.88%   |
| Ralink                | 1        | 0.88%   |
| Oculus VR             | 1        | 0.88%   |
| Microsoft             | 1        | 0.88%   |
| Google                | 1        | 0.88%   |
| D-Link System         | 1        | 0.88%   |
| Broadcom              | 1        | 0.88%   |
| ASUSTek Computer      | 1        | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35       | 26.92%  |
| Intel Ethernet Controller I225-V                                  | 10       | 7.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 6.92%   |
| Intel Wi-Fi 6 AX200                                               | 9        | 6.92%   |
| Intel I211 Gigabit Network Connection                             | 9        | 6.92%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4        | 3.08%   |
| Intel Ethernet Connection I217-V                                  | 3        | 2.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 1.54%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.54%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.54%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.54%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.54%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.54%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 1.54%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.77%   |
| Texas Instruments CC2538 USB CDC                                  | 1        | 0.77%   |
| STMicroelectronics Virtual COM Port                               | 1        | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.77%   |
| Realtek 802.11ac NIC                                              | 1        | 0.77%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.77%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.77%   |
| Ralink RT2800 802.11n PCI                                         | 1        | 0.77%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.77%   |
| Oculus VR Rift S                                                  | 1        | 0.77%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 0.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1        | 0.77%   |
| Intel Wireless-AC 9260                                            | 1        | 0.77%   |
| Intel Wireless 7265                                               | 1        | 0.77%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1        | 0.77%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 0.77%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 0.77%   |
| Intel CNVi: Wi-Fi                                                 | 1        | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 20       | 57.14%  |
| MediaTek              | 5        | 14.29%  |
| Realtek Semiconductor | 2        | 5.71%   |
| Ralink Technology     | 2        | 5.71%   |
| TP-Link               | 1        | 2.86%   |
| Ralink                | 1        | 2.86%   |
| Qualcomm Atheros      | 1        | 2.86%   |
| Microsoft             | 1        | 2.86%   |
| D-Link System         | 1        | 2.86%   |
| ASUSTek Computer      | 1        | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                               | 9        | 25.71%  |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4        | 11.43%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 5.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 5.71%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 5.71%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 2.86%   |
| Realtek 802.11ac NIC                                              | 1        | 2.86%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 2.86%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 2.86%   |
| Ralink RT2800 802.11n PCI                                         | 1        | 2.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 2.86%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 2.86%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1        | 2.86%   |
| Intel Wireless-AC 9260                                            | 1        | 2.86%   |
| Intel Wireless 7265                                               | 1        | 2.86%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1        | 2.86%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 2.86%   |
| Intel CNVi: Wi-Fi                                                 | 1        | 2.86%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W] | 1        | 2.86%   |
| ASUS USB-N53 802.11abgn Network Adapter [Ralink RT3572]           | 1        | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 44       | 48.89%  |
| Intel                 | 37       | 41.11%  |
| Aquantia              | 5        | 5.56%   |
| Qualcomm Atheros      | 2        | 2.22%   |
| Google                | 1        | 1.11%   |
| Broadcom              | 1        | 1.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35       | 38.04%  |
| Intel Ethernet Controller I225-V                                  | 10       | 10.87%  |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 9.78%   |
| Intel I211 Gigabit Network Connection                             | 9        | 9.78%   |
| Intel Ethernet Connection I217-V                                  | 3        | 3.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 2.17%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.17%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 2.17%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.17%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.17%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 2.17%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.09%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 1.09%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.09%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.09%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.09%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 1.09%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 1.09%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.09%   |
| Aquantia AQC100 10G Ethernet MAC controller [AQtion]              | 1        | 1.09%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1        | 1.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 77       | 66.96%  |
| WiFi     | 35       | 30.43%  |
| Modem    | 3        | 2.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 61       | 78.21%  |
| WiFi     | 17       | 21.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 40       | 51.28%  |
| 2     | 31       | 39.74%  |
| 3     | 6        | 7.69%   |
| 0     | 1        | 1.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 54       | 69.23%  |
| Yes  | 24       | 30.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 15       | 38.46%  |
| Cambridge Silicon Radio  | 7        | 17.95%  |
| Realtek Semiconductor    | 4        | 10.26%  |
| Broadcom                 | 4        | 10.26%  |
| ASUSTek Computer         | 4        | 10.26%  |
| MediaTek                 | 3        | 7.69%   |
| HTC (High Tech Computer) | 1        | 2.56%   |
| Foxconn / Hon Hai        | 1        | 2.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 7        | 17.95%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 7        | 17.95%  |
| Intel AX201 Bluetooth                                                | 4        | 10.26%  |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 4        | 10.26%  |
| Realtek Bluetooth Radio                                              | 3        | 7.69%   |
| MediaTek Wireless_Device                                             | 3        | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 2        | 5.13%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2        | 5.13%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 2.56%   |
| Intel Bluetooth Device                                               | 1        | 2.56%   |
| Intel AX210 Bluetooth                                                | 1        | 2.56%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 2.56%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1        | 2.56%   |
| ASUS Bluetooth Device                                                | 1        | 2.56%   |
| ASUS ASUS USB-BT500                                                  | 1        | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 47       | 28.83%  |
| Nvidia                               | 36       | 22.09%  |
| Intel                                | 35       | 21.47%  |
| C-Media Electronics                  | 5        | 3.07%   |
| Texas Instruments                    | 4        | 2.45%   |
| Razer USA                            | 3        | 1.84%   |
| Kingston Technology                  | 3        | 1.84%   |
| ASUSTek Computer                     | 3        | 1.84%   |
| Sennheiser Communications            | 2        | 1.23%   |
| RODE Microphones                     | 2        | 1.23%   |
| Focusrite-Novation                   | 2        | 1.23%   |
| Yamaha                               | 1        | 0.61%   |
| Valve Software                       | 1        | 0.61%   |
| Thomann                              | 1        | 0.61%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.61%   |
| Sony                                 | 1        | 0.61%   |
| Shure                                | 1        | 0.61%   |
| Schiit Audio                         | 1        | 0.61%   |
| PreSonus Audio Electronics           | 1        | 0.61%   |
| Huawei Technologies                  | 1        | 0.61%   |
| Hewlett-Packard                      | 1        | 0.61%   |
| GYROCOM C&C                          | 1        | 0.61%   |
| Giga-Byte Technology                 | 1        | 0.61%   |
| Edifier Technology                   | 1        | 0.61%   |
| Dell                                 | 1        | 0.61%   |
| Creative Technology                  | 1        | 0.61%   |
| Creative Labs                        | 1        | 0.61%   |
| Conexant Systems                     | 1        | 0.61%   |
| Blue Microphones                     | 1        | 0.61%   |
| ASRock                               | 1        | 0.61%   |
| Apogee Electronics                   | 1        | 0.61%   |
| Antlion Audio                        | 1        | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 24       | 12.57%  |
| AMD Family 17h/19h HD Audio Controller                                     | 7        | 3.66%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 3.66%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6        | 3.14%   |
| AMD Navi 10 HDMI Audio                                                     | 6        | 3.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 2.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 2.62%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5        | 2.62%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 2.62%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 2.09%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 2.09%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 2.09%   |
| Nvidia GK104 HDMI Audio Controller                                         | 4        | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 2.09%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3        | 1.57%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.57%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 1.57%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 1.57%   |
| ASUSTek Computer USB Audio                                                 | 3        | 1.57%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3        | 1.57%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.57%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.05%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 1.05%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 1.05%   |
| Kingston Technology HyperX 7.1 Audio                                       | 2        | 1.05%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.05%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.05%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.05%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 1.05%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 1.05%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 2        | 1.05%   |
| Yamaha AG06/AG03                                                           | 1        | 0.52%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 1        | 0.52%   |
| Thomann SC450USB                                                           | 1        | 0.52%   |
| Thesycon Systemsoftware & Consulting DX3 Pro+                              | 1        | 0.52%   |
| Texas Instruments PCM2902C Audio CODEC                                     | 1        | 0.52%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 24       | 27.27%  |
| Kingston            | 16       | 18.18%  |
| G.Skill             | 16       | 18.18%  |
| Samsung Electronics | 7        | 7.95%   |
| Crucial             | 7        | 7.95%   |
| Unknown             | 5        | 5.68%   |
| Micron Technology   | 3        | 3.41%   |
| Team                | 2        | 2.27%   |
| A-DATA Technology   | 2        | 2.27%   |
| Unknown (ABCD)      | 1        | 1.14%   |
| Strontium           | 1        | 1.14%   |
| SK hynix            | 1        | 1.14%   |
| Goodram             | 1        | 1.14%   |
| GLOWAY              | 1        | 1.14%   |
| AMD                 | 1        | 1.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 3        | 3.13%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s         | 3        | 3.13%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 2        | 2.08%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 2        | 2.08%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s            | 2        | 2.08%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 2        | 2.08%   |
| Corsair RAM Module 16GB DIMM DDR4 2133MT/s                     | 2        | 2.08%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s         | 2        | 2.08%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 1.04%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                       | 1        | 1.04%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                  | 1        | 1.04%   |
| Unknown RAM 3733 C17 Series 8192MB DIMM DDR4 2133MT/s          | 1        | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 1.04%   |
| Team RAM TEAMGROUP-UD4-3200 8192MB DIMM DDR4 3733MT/s          | 1        | 1.04%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s             | 1        | 1.04%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2933MT/s            | 1        | 1.04%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s             | 1        | 1.04%   |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                     | 1        | 1.04%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                      | 1        | 1.04%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR5 6400MT/s            | 1        | 1.04%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                 | 1        | 1.04%   |
| Samsung RAM M393A4K40BB0-CPB 32GB RIMM DDR4 2133MT/s           | 1        | 1.04%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s            | 1        | 1.04%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 1        | 1.04%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 1        | 1.04%   |
| Micron RAM 4ATF1G64AZ-3G2E1 8192MB DIMM DDR4 3200MT/s          | 1        | 1.04%   |
| Micron RAM 36ASF4G72PZ-2G1A1 32GB RIMM DDR4 2133MT/s           | 1        | 1.04%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16384MB DIMM DDR4 3200MT/s        | 1        | 1.04%   |
| Kingston RAM Module 4GB DIMM DDR3 1600MT/s                     | 1        | 1.04%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 1        | 1.04%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 1        | 1.04%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s            | 1        | 1.04%   |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s           | 1        | 1.04%   |
| Kingston RAM KHX1600C10D3L/8GX 8GB DIMM DDR3 1600MT/s          | 1        | 1.04%   |
| Kingston RAM KF548S38-16 16GB SODIMM DDR5 4800MT/s             | 1        | 1.04%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s            | 1        | 1.04%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s          | 1        | 1.04%   |
| Kingston RAM 99U5471-034.A00LF 4GB DIMM DDR3 1600MT/s          | 1        | 1.04%   |
| Kingston RAM 99U5403-123.A00LF 8GB DIMM DDR3 1600MT/s          | 1        | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 52       | 69.33%  |
| DDR3   | 15       | 20%     |
| DDR5   | 5        | 6.67%   |
| LPDDR5 | 1        | 1.33%   |
| LPDDR4 | 1        | 1.33%   |
| DDR    | 1        | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 69       | 92%     |
| SODIMM       | 4        | 5.33%   |
| Row Of Chips | 1        | 1.33%   |
| RIMM         | 1        | 1.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 30       | 35.29%  |
| 8192  | 30       | 35.29%  |
| 32768 | 15       | 17.65%  |
| 4096  | 9        | 10.59%  |
| 2048  | 1        | 1.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 20       | 22.73%  |
| 3600  | 10       | 11.36%  |
| 1600  | 9        | 10.23%  |
| 2133  | 7        | 7.95%   |
| 3733  | 6        | 6.82%   |
| 2400  | 5        | 5.68%   |
| 1333  | 5        | 5.68%   |
| 3000  | 4        | 4.55%   |
| 6000  | 2        | 2.27%   |
| 4800  | 2        | 2.27%   |
| 3400  | 2        | 2.27%   |
| 3334  | 2        | 2.27%   |
| 2933  | 2        | 2.27%   |
| 6400  | 1        | 1.14%   |
| 5200  | 1        | 1.14%   |
| 4000  | 1        | 1.14%   |
| 3866  | 1        | 1.14%   |
| 3666  | 1        | 1.14%   |
| 3534  | 1        | 1.14%   |
| 2800  | 1        | 1.14%   |
| 2667  | 1        | 1.14%   |
| 2134  | 1        | 1.14%   |
| 2132  | 1        | 1.14%   |
| 1867  | 1        | 1.14%   |
| 1866  | 1        | 1.14%   |

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


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Logitech       | 16       | 72.73%  |
| MacroSilicon   | 3        | 13.64%  |
| Valve Software | 1        | 4.55%   |
| Microdia       | 1        | 4.55%   |
| Apple          | 1        | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech StreamCam              | 4        | 18.18%  |
| MacroSilicon USB Video          | 3        | 13.64%  |
| Logitech Webcam C270            | 2        | 9.09%   |
| Logitech HD Pro Webcam C920     | 2        | 9.09%   |
| Valve Software 3D Camera        | 1        | 4.55%   |
| Microdia Camera                 | 1        | 4.55%   |
| Logitech Webcam Pro 9000        | 1        | 4.55%   |
| Logitech Webcam C930e           | 1        | 4.55%   |
| Logitech Webcam C925e           | 1        | 4.55%   |
| Logitech Webcam C120            | 1        | 4.55%   |
| Logitech HD Webcam C615         | 1        | 4.55%   |
| Logitech C930c                  | 1        | 4.55%   |
| Logitech C922 Pro Stream Webcam | 1        | 4.55%   |
| Logitech BRIO 4K Stream Edition | 1        | 4.55%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X | 1        | 4.55%   |

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
| 0     | 62       | 77.5%   |
| 1     | 14       | 17.5%   |
| 2     | 4        | 5%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 5        | 25%     |
| Net/wireless          | 4        | 20%     |
| Unassigned class      | 3        | 15%     |
| Multimedia controller | 3        | 15%     |
| Bluetooth             | 2        | 10%     |
| Dvb card              | 1        | 5%      |
| Chipcard              | 1        | 5%      |
| Camera                | 1        | 5%      |

