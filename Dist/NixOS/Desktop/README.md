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

Total: 118

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a953876b2c](https://linux-hardware.org/?probe=a953876b2c) | Dec 23, 2023 |
| ASRock        | X670E PG Lightning          | [b6aa52f693](https://linux-hardware.org/?probe=b6aa52f693) | Dec 17, 2023 |
| AZW           | EQ                          | [b6aa615ccf](https://linux-hardware.org/?probe=b6aa615ccf) | Dec 14, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [2982c2a2c6](https://linux-hardware.org/?probe=2982c2a2c6) | Dec 14, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [8617acecda](https://linux-hardware.org/?probe=8617acecda) | Dec 11, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [62c4dde3a6](https://linux-hardware.org/?probe=62c4dde3a6) | Dec 07, 2023 |
| AZW           | EQ                          | [c2dedbf2f3](https://linux-hardware.org/?probe=c2dedbf2f3) | Dec 04, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [7273cc93a9](https://linux-hardware.org/?probe=7273cc93a9) | Dec 02, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [07e6828b2e](https://linux-hardware.org/?probe=07e6828b2e) | Nov 23, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [34b2b48e8c](https://linux-hardware.org/?probe=34b2b48e8c) | Nov 19, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0820ebd908](https://linux-hardware.org/?probe=0820ebd908) | Nov 16, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [a263ed1c12](https://linux-hardware.org/?probe=a263ed1c12) | Nov 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [67938dee90](https://linux-hardware.org/?probe=67938dee90) | Nov 12, 2023 |
| ASRock        | Z690M-ITX/ax                | [503d3690b0](https://linux-hardware.org/?probe=503d3690b0) | Nov 11, 2023 |
| ASUSTek       | PRIME X399-A                | [e0883e3bd0](https://linux-hardware.org/?probe=e0883e3bd0) | Nov 11, 2023 |
| Nvidia        | snc302eeh                   | [2b0a14caec](https://linux-hardware.org/?probe=2b0a14caec) | Nov 10, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d9cad8ffde](https://linux-hardware.org/?probe=d9cad8ffde) | Nov 09, 2023 |
| ASUSTek       | PRIME X570-PRO              | [1786e4735e](https://linux-hardware.org/?probe=1786e4735e) | Nov 07, 2023 |
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
| NixOS 23.05                      | 26       | 27.08%  |
| NixOS 23.11                      | 16       | 16.67%  |
| NixOS 22.05                      | 13       | 13.54%  |
| NixOS 22.11                      | 12       | 12.5%   |
| NixOS 21.11                      | 7        | 7.29%   |
| NixOS 24.05                      | 4        | 4.17%   |
| NixOS                            | 3        | 3.13%   |
| NixOS 21.05pre-git               | 2        | 2.08%   |
| NixOS 21.11.20210528.540dccb     | 1        | 1.04%   |
| NixOS 21.05.993.93963c27b93      | 1        | 1.04%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1        | 1.04%   |
| NixOS 21.05.20210929.ee90403     | 1        | 1.04%   |
| NixOS 21.05.20210430.c8dff32     | 1        | 1.04%   |
| NixOS 21.05.20210224.f6b5bfd     | 1        | 1.04%   |
| NixOS 21.05.1471.a7512bb64b1     | 1        | 1.04%   |
| NixOS 21.03pre246062.420f89ceb26 | 1        | 1.04%   |
| NixOS 21.03.git.b4349c13a6d      | 1        | 1.04%   |
| NixOS 21.03.20201007.420f89c     | 1        | 1.04%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1        | 1.04%   |
| NixOS 20.09pre-git               | 1        | 1.04%   |
| NixOS 20.09.git.4a361b06a93      | 1        | 1.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| NixOS | 90       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Desktops | Percent |
|----------------|----------|---------|
| 6.1.55         | 5        | 4.81%   |
| 6.6.0          | 3        | 2.88%   |
| 6.1.37         | 3        | 2.88%   |
| 6.4.7          | 2        | 1.92%   |
| 6.4.0          | 2        | 1.92%   |
| 6.1.60         | 2        | 1.92%   |
| 5.8.1-zen1     | 2        | 1.92%   |
| 5.15.86        | 2        | 1.92%   |
| 5.15.85        | 2        | 1.92%   |
| 5.15.47        | 2        | 1.92%   |
| 5.10.102       | 2        | 1.92%   |
| 6.6.6          | 1        | 0.96%   |
| 6.6.5-xanmod1  | 1        | 0.96%   |
| 6.6.3          | 1        | 0.96%   |
| 6.6.2-cachyos  | 1        | 0.96%   |
| 6.6.1          | 1        | 0.96%   |
| 6.5.9-xanmod1  | 1        | 0.96%   |
| 6.5.7          | 1        | 0.96%   |
| 6.5.5          | 1        | 0.96%   |
| 6.5.2          | 1        | 0.96%   |
| 6.5.10-xanmod1 | 1        | 0.96%   |
| 6.5.1          | 1        | 0.96%   |
| 6.4.9          | 1        | 0.96%   |
| 6.4.4-cachyos  | 1        | 0.96%   |
| 6.4.4          | 1        | 0.96%   |
| 6.4.11-cachyos | 1        | 0.96%   |
| 6.3.3          | 1        | 0.96%   |
| 6.2.11-lqx3    | 1        | 0.96%   |
| 6.2.11         | 1        | 0.96%   |
| 6.2.10         | 1        | 0.96%   |
| 6.1.67         | 1        | 0.96%   |
| 6.1.64         | 1        | 0.96%   |
| 6.1.63         | 1        | 0.96%   |
| 6.1.62         | 1        | 0.96%   |
| 6.1.61         | 1        | 0.96%   |
| 6.1.59         | 1        | 0.96%   |
| 6.1.55-xanmod1 | 1        | 0.96%   |
| 6.1.51         | 1        | 0.96%   |
| 6.1.45         | 1        | 0.96%   |
| 6.1.42         | 1        | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 6.1.55   | 6        | 5.77%   |
| 6.6.0    | 3        | 2.88%   |
| 6.1.37   | 3        | 2.88%   |
| 6.4.7    | 2        | 1.92%   |
| 6.4.4    | 2        | 1.92%   |
| 6.4.0    | 2        | 1.92%   |
| 6.2.11   | 2        | 1.92%   |
| 6.1.60   | 2        | 1.92%   |
| 6.1.31   | 2        | 1.92%   |
| 5.8.1    | 2        | 1.92%   |
| 5.15.86  | 2        | 1.92%   |
| 5.15.85  | 2        | 1.92%   |
| 5.15.47  | 2        | 1.92%   |
| 5.11.16  | 2        | 1.92%   |
| 5.10.102 | 2        | 1.92%   |
| 6.6.6    | 1        | 0.96%   |
| 6.6.5    | 1        | 0.96%   |
| 6.6.3    | 1        | 0.96%   |
| 6.6.2    | 1        | 0.96%   |
| 6.6.1    | 1        | 0.96%   |
| 6.5.9    | 1        | 0.96%   |
| 6.5.7    | 1        | 0.96%   |
| 6.5.5    | 1        | 0.96%   |
| 6.5.2    | 1        | 0.96%   |
| 6.5.10   | 1        | 0.96%   |
| 6.5.1    | 1        | 0.96%   |
| 6.4.9    | 1        | 0.96%   |
| 6.4.11   | 1        | 0.96%   |
| 6.3.3    | 1        | 0.96%   |
| 6.2.10   | 1        | 0.96%   |
| 6.1.67   | 1        | 0.96%   |
| 6.1.64   | 1        | 0.96%   |
| 6.1.63   | 1        | 0.96%   |
| 6.1.62   | 1        | 0.96%   |
| 6.1.61   | 1        | 0.96%   |
| 6.1.59   | 1        | 0.96%   |
| 6.1.51   | 1        | 0.96%   |
| 6.1.45   | 1        | 0.96%   |
| 6.1.42   | 1        | 0.96%   |
| 6.1.39   | 1        | 0.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 25       | 25%     |
| 5.15    | 22       | 22%     |
| 5.10    | 9        | 9%      |
| 6.6     | 8        | 8%      |
| 6.5     | 6        | 6%      |
| 6.4     | 5        | 5%      |
| 5.4     | 5        | 5%      |
| 6.2     | 3        | 3%      |
| 5.8     | 3        | 3%      |
| 6.0     | 2        | 2%      |
| 5.18    | 2        | 2%      |
| 5.11    | 2        | 2%      |
| 6.3     | 1        | 1%      |
| 5.7     | 1        | 1%      |
| 5.19    | 1        | 1%      |
| 5.17    | 1        | 1%      |
| 5.16    | 1        | 1%      |
| 5.14    | 1        | 1%      |
| 5.13    | 1        | 1%      |
| 5.12    | 1        | 1%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 90       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Unknown      | 39       | 42.86%  |
| KDE5         | 15       | 16.48%  |
| GNOME        | 12       | 13.19%  |
| Hyprland     | 7        | 7.69%   |
| sway         | 4        | 4.4%    |
| KDE          | 4        | 4.4%    |
| XFCE         | 3        | 3.3%    |
| none+awesome | 2        | 2.2%    |
| xsession     | 1        | 1.1%    |
| X-Generic    | 1        | 1.1%    |
| none+i3      | 1        | 1.1%    |
| MATE         | 1        | 1.1%    |
| LXQt         | 1        | 1.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 36       | 39.13%  |
| X11     | 26       | 28.26%  |
| Wayland | 22       | 23.91%  |
| Tty     | 8        | 8.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 45       | 49.45%  |
| SDDM    | 21       | 23.08%  |
| GDM     | 13       | 14.29%  |
| LightDM | 12       | 13.19%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 46       | 51.11%  |
| Unknown    | 21       | 23.33%  |
| en_GB      | 8        | 8.89%   |
| en_AU      | 4        | 4.44%   |
| ru_RU      | 2        | 2.22%   |
| en_DK      | 2        | 2.22%   |
| de_DE      | 2        | 2.22%   |
| pt_BR      | 1        | 1.11%   |
| it_IT      | 1        | 1.11%   |
| en_NZ      | 1        | 1.11%   |
| en_IE.UTF8 | 1        | 1.11%   |
| de_CH      | 1        | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 75       | 82.42%  |
| BIOS | 16       | 17.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 53       | 58.89%  |
| Btrfs   | 15       | 16.67%  |
| Zfs     | 7        | 7.78%   |
| Tmpfs   | 7        | 7.78%   |
| Xfs     | 4        | 4.44%   |
| Unknown | 3        | 3.33%   |
| Ext2    | 1        | 1.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 84       | 93.33%  |
| MBR     | 4        | 4.44%   |
| Unknown | 2        | 2.22%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 73.91%  |
| Yes       | 24       | 26.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 58.7%   |
| Yes       | 38       | 41.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 33       | 36.67%  |
| Gigabyte Technology                  | 15       | 16.67%  |
| MSI                                  | 14       | 15.56%  |
| ASRock                               | 11       | 12.22%  |
| Hewlett-Packard                      | 5        | 5.56%   |
| Acer                                 | 3        | 3.33%   |
| Shenzhen Meigao Electronic Equipment | 1        | 1.11%   |
| Nvidia                               | 1        | 1.11%   |
| LattePanda                           | 1        | 1.11%   |
| Hardkernel                           | 1        | 1.11%   |
| EVGA                                 | 1        | 1.11%   |
| ECS                                  | 1        | 1.11%   |
| Dell                                 | 1        | 1.11%   |
| AZW                                  | 1        | 1.11%   |
| Unknown                              | 1        | 1.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| MSI MS-7C37                                | 3        | 3.33%   |
| ASUS All Series                            | 3        | 3.33%   |
| MSI MS-7C56                                | 2        | 2.22%   |
| Gigabyte B550I AORUS PRO AX                | 2        | 2.22%   |
| Gigabyte B450M DS3H                        | 2        | 2.22%   |
| ASUS ROG STRIX B550-F GAMING               | 2        | 2.22%   |
| ASRock Z87 Extreme4                        | 2        | 2.22%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.11%   |
| Nvidia 680iLT                              | 1        | 1.11%   |
| MSI MS-7E12                                | 1        | 1.11%   |
| MSI MS-7C95                                | 1        | 1.11%   |
| MSI MS-7C91                                | 1        | 1.11%   |
| MSI MS-7C84                                | 1        | 1.11%   |
| MSI MS-7C35                                | 1        | 1.11%   |
| MSI MS-7B89                                | 1        | 1.11%   |
| MSI MS-7B09                                | 1        | 1.11%   |
| MSI MS-7758                                | 1        | 1.11%   |
| MSI MS-7681                                | 1        | 1.11%   |
| LattePanda Sigma                           | 1        | 1.11%   |
| HP Pavilion Gaming Desktop TG01-1xxx       | 1        | 1.11%   |
| HP EliteDesk 800 G4 SFF                    | 1        | 1.11%   |
| HP EliteDesk 800 G2 DM 35W                 | 1        | 1.11%   |
| HP EliteDesk 800 G1 SFF                    | 1        | 1.11%   |
| HP Compaq Elite 8300 SFF                   | 1        | 1.11%   |
| Hardkernel ODROID-H2                       | 1        | 1.11%   |
| Gigabyte Z790 GAMING X AX                  | 1        | 1.11%   |
| Gigabyte X570 I AORUS PRO WIFI             | 1        | 1.11%   |
| Gigabyte X570 AORUS PRO                    | 1        | 1.11%   |
| Gigabyte X570 AORUS ELITE WIFI             | 1        | 1.11%   |
| Gigabyte X570 AORUS ELITE                  | 1        | 1.11%   |
| Gigabyte X470 AORUS ULTRA GAMING           | 1        | 1.11%   |
| Gigabyte TRX40 AORUS MASTER                | 1        | 1.11%   |
| Gigabyte H97M-D3H                          | 1        | 1.11%   |
| Gigabyte GA-78LMT-USB3 6.0                 | 1        | 1.11%   |
| Gigabyte B760 GAMING X DDR4                | 1        | 1.11%   |
| Gigabyte B450M DS3H V2                     | 1        | 1.11%   |
| EVGA X299 FTW K                            | 1        | 1.11%   |
| ECS A55F-M3                                | 1        | 1.11%   |
| Dell Precision Tower 7810                  | 1        | 1.11%   |
| AZW EQ                                     | 1        | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 10       | 11.11%  |
| ASUS ROG                                   | 9        | 10%     |
| Gigabyte X570                              | 4        | 4.44%   |
| MSI MS-7C37                                | 3        | 3.33%   |
| HP EliteDesk                               | 3        | 3.33%   |
| Gigabyte B450M                             | 3        | 3.33%   |
| ASUS TUF                                   | 3        | 3.33%   |
| ASUS All                                   | 3        | 3.33%   |
| MSI MS-7C56                                | 2        | 2.22%   |
| Gigabyte B550I                             | 2        | 2.22%   |
| ASRock Z87                                 | 2        | 2.22%   |
| Acer Aspire                                | 2        | 2.22%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 1.11%   |
| Nvidia 680iLT                              | 1        | 1.11%   |
| MSI MS-7E12                                | 1        | 1.11%   |
| MSI MS-7C95                                | 1        | 1.11%   |
| MSI MS-7C91                                | 1        | 1.11%   |
| MSI MS-7C84                                | 1        | 1.11%   |
| MSI MS-7C35                                | 1        | 1.11%   |
| MSI MS-7B89                                | 1        | 1.11%   |
| MSI MS-7B09                                | 1        | 1.11%   |
| MSI MS-7758                                | 1        | 1.11%   |
| MSI MS-7681                                | 1        | 1.11%   |
| LattePanda Sigma                           | 1        | 1.11%   |
| HP Pavilion                                | 1        | 1.11%   |
| HP Compaq                                  | 1        | 1.11%   |
| Hardkernel ODROID-H2                       | 1        | 1.11%   |
| Gigabyte Z790                              | 1        | 1.11%   |
| Gigabyte X470                              | 1        | 1.11%   |
| Gigabyte TRX40                             | 1        | 1.11%   |
| Gigabyte H97M-D3H                          | 1        | 1.11%   |
| Gigabyte GA-78LMT-USB3                     | 1        | 1.11%   |
| Gigabyte B760                              | 1        | 1.11%   |
| EVGA X299                                  | 1        | 1.11%   |
| ECS A55F-M3                                | 1        | 1.11%   |
| Dell Precision                             | 1        | 1.11%   |
| AZW EQ                                     | 1        | 1.11%   |
| ASUS Z170-P                                | 1        | 1.11%   |
| ASUS SABERTOOTH                            | 1        | 1.11%   |
| ASUS PRO602617                             | 1        | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 19       | 21.11%  |
| 2019 | 15       | 16.67%  |
| 2018 | 11       | 12.22%  |
| 2023 | 7        | 7.78%   |
| 2012 | 6        | 6.67%   |
| 2022 | 5        | 5.56%   |
| 2017 | 5        | 5.56%   |
| 2014 | 5        | 5.56%   |
| 2016 | 4        | 4.44%   |
| 2013 | 4        | 4.44%   |
| 2021 | 2        | 2.22%   |
| 2015 | 2        | 2.22%   |
| 2011 | 2        | 2.22%   |
| 2008 | 2        | 2.22%   |
| 2010 | 1        | 1.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 90       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 88       | 97.78%  |
| Enabled  | 2        | 2.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 90       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 28       | 31.11%  |
| 64.01-256.0     | 25       | 27.78%  |
| 16.01-24.0      | 18       | 20%     |
| 24.01-32.0      | 7        | 7.78%   |
| 8.01-16.0       | 6        | 6.67%   |
| 4.01-8.0        | 4        | 4.44%   |
| More than 256.0 | 1        | 1.11%   |
| 3.01-4.0        | 1        | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 26       | 27.66%  |
| 8.01-16.0  | 18       | 19.15%  |
| 2.01-3.0   | 11       | 11.7%   |
| 1.01-2.0   | 11       | 11.7%   |
| 3.01-4.0   | 10       | 10.64%  |
| 16.01-24.0 | 9        | 9.57%   |
| 32.01-64.0 | 7        | 7.45%   |
| 24.01-32.0 | 1        | 1.06%   |
| 0.51-1.0   | 1        | 1.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 28       | 28.87%  |
| 1      | 28       | 28.87%  |
| 3      | 21       | 21.65%  |
| 4      | 6        | 6.19%   |
| 5      | 5        | 5.15%   |
| 6      | 4        | 4.12%   |
| 8      | 2        | 2.06%   |
| 23     | 1        | 1.03%   |
| 7      | 1        | 1.03%   |
| 0      | 1        | 1.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 81.32%  |
| Yes       | 17       | 18.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 90       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 53.26%  |
| Yes       | 43       | 46.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 46       | 50.55%  |
| No        | 45       | 49.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 20       | 22.22%  |
| Germany     | 14       | 15.56%  |
| UK          | 7        | 7.78%   |
| Russia      | 6        | 6.67%   |
| Australia   | 4        | 4.44%   |
| Poland      | 3        | 3.33%   |
| Italy       | 3        | 3.33%   |
| France      | 3        | 3.33%   |
| Canada      | 3        | 3.33%   |
| Austria     | 3        | 3.33%   |
| Ukraine     | 2        | 2.22%   |
| Netherlands | 2        | 2.22%   |
| Finland     | 2        | 2.22%   |
| Denmark     | 2        | 2.22%   |
| Brazil      | 2        | 2.22%   |
| Taiwan      | 1        | 1.11%   |
| Switzerland | 1        | 1.11%   |
| Sweden      | 1        | 1.11%   |
| Slovenia    | 1        | 1.11%   |
| Serbia      | 1        | 1.11%   |
| Portugal    | 1        | 1.11%   |
| Philippines | 1        | 1.11%   |
| Norway      | 1        | 1.11%   |
| New Zealand | 1        | 1.11%   |
| Mexico      | 1        | 1.11%   |
| Ireland     | 1        | 1.11%   |
| India       | 1        | 1.11%   |
| Hungary     | 1        | 1.11%   |
| Belgium     | 1        | 1.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Vienna            | 3        | 3.26%   |
| Schaafheim        | 2        | 2.17%   |
| Ramenskoye        | 2        | 2.17%   |
| Plymouth          | 2        | 2.17%   |
| Perth             | 2        | 2.17%   |
| Marki             | 2        | 2.17%   |
| Kharkiv           | 2        | 2.17%   |
| Hamburg           | 2        | 2.17%   |
| Darmstadt         | 2        | 2.17%   |
| Bochum            | 2        | 2.17%   |
| Austin            | 2        | 2.17%   |
| Wellington        | 1        | 1.09%   |
| Vila Nova de Gaia | 1        | 1.09%   |
| Umeå             | 1        | 1.09%   |
| Troisdorf         | 1        | 1.09%   |
| Tobercurry        | 1        | 1.09%   |
| Taichung          | 1        | 1.09%   |
| Székesfehérvár | 1        | 1.09%   |
| Southampton       | 1        | 1.09%   |
| South Deerfield   | 1        | 1.09%   |
| Sorocaba          | 1        | 1.09%   |
| Sindelfingen      | 1        | 1.09%   |
| Santa Clara       | 1        | 1.09%   |
| San Juan          | 1        | 1.09%   |
| San Gabriel       | 1        | 1.09%   |
| Saarbrücken      | 1        | 1.09%   |
| Richardson        | 1        | 1.09%   |
| Redwood City      | 1        | 1.09%   |
| Pisa              | 1        | 1.09%   |
| Paris             | 1        | 1.09%   |
| Palm Bay          | 1        | 1.09%   |
| Oulu              | 1        | 1.09%   |
| Oslo              | 1        | 1.09%   |
| Osasco            | 1        | 1.09%   |
| Oakville          | 1        | 1.09%   |
| Norwich           | 1        | 1.09%   |
| North Andover     | 1        | 1.09%   |
| Noardburgum       | 1        | 1.09%   |
| Moscow            | 1        | 1.09%   |
| Montreal          | 1        | 1.09%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 50       | 88     | 28.09%  |
| WDC                         | 23       | 42     | 12.92%  |
| Seagate                     | 23       | 35     | 12.92%  |
| SanDisk                     | 15       | 20     | 8.43%   |
| Toshiba                     | 10       | 21     | 5.62%   |
| Crucial                     | 10       | 11     | 5.62%   |
| Phison Electronics          | 6        | 8      | 3.37%   |
| Kingston                    | 5        | 5      | 2.81%   |
| Intel                       | 5        | 7      | 2.81%   |
| HGST                        | 4        | 7      | 2.25%   |
| Realtek Semiconductor       | 2        | 7      | 1.12%   |
| MAXIO Technology (Hangzhou) | 2        | 4      | 1.12%   |
| Hitachi                     | 2        | 4      | 1.12%   |
| Corsair                     | 2        | 2      | 1.12%   |
| ZHITAI                      | 1        | 1      | 0.56%   |
| Yangtze Memory Technologies | 1        | 2      | 0.56%   |
| Team                        | 1        | 1      | 0.56%   |
| SPCC                        | 1        | 1      | 0.56%   |
| SK hynix                    | 1        | 1      | 0.56%   |
| Silicon Motion              | 1        | 1      | 0.56%   |
| PNY                         | 1        | 1      | 0.56%   |
| Plextor                     | 1        | 1      | 0.56%   |
| Phison                      | 1        | 1      | 0.56%   |
| OCZ                         | 1        | 1      | 0.56%   |
| Micron/Crucial Technology   | 1        | 1      | 0.56%   |
| Micron Technology           | 1        | 1      | 0.56%   |
| MBED                        | 1        | 1      | 0.56%   |
| Lexar                       | 1        | 1      | 0.56%   |
| Kingston Technology Company | 1        | 1      | 0.56%   |
| Intenso                     | 1        | 1      | 0.56%   |
| China                       | 1        | 1      | 0.56%   |
| ASMT                        | 1        | 1      | 0.56%   |
| A-DATA Technology           | 1        | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB                             | 7        | 3.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 7        | 3.13%   |
| Samsung SSD 860 EVO 500GB                           | 5        | 2.23%   |
| Samsung SSD 860 QVO 1TB                             | 4        | 1.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 4        | 1.79%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3        | 1.34%   |
| Seagate ST3000DM001-1CH166 3TB                      | 3        | 1.34%   |
| SanDisk SSD PLUS 240GB                              | 3        | 1.34%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3        | 1.34%   |
| Phison E16 PCIe4 NVMe Controller 500GB              | 3        | 1.34%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 2        | 0.89%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2        | 0.89%   |
| Seagate ST1000DM003-1CH162 1TB                      | 2        | 0.89%   |
| Sandisk WD_BLACK SN850X 2000GB                      | 2        | 0.89%   |
| Sandisk WD_BLACK SN770 500GB                        | 2        | 0.89%   |
| Samsung SSD 990 PRO 1TB                             | 2        | 0.89%   |
| Samsung SSD 980 PRO 1TB                             | 2        | 0.89%   |
| Samsung SSD 980 1TB                                 | 2        | 0.89%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2        | 0.89%   |
| Samsung SSD 970 EVO 500GB                           | 2        | 0.89%   |
| Samsung SSD 970 EVO 1TB                             | 2        | 0.89%   |
| Samsung SSD 870 QVO 8TB                             | 2        | 0.89%   |
| Samsung SSD 860 EVO 2TB                             | 2        | 0.89%   |
| Samsung SSD 860 EVO 250GB                           | 2        | 0.89%   |
| Samsung NVMe SSD Drive 1TB                          | 2        | 0.89%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 1024GB | 2        | 0.89%   |
| Crucial CT1000MX500SSD1 1TB                         | 2        | 0.89%   |
| ZHITAI SC001 Active 512GB SSD                       | 1        | 0.45%   |
| Yangtze Memory ZHITAI TiPro7000 1TB                 | 1        | 0.45%   |
| Yangtze Memory ZHITAI TiPlus7100 1TB                | 1        | 0.45%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1        | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 1        | 0.45%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 0.45%   |
| WDC WD80EDAZ-11TA3A0 8TB                            | 1        | 0.45%   |
| WDC WD50EZRX-00MVLB1 5TB                            | 1        | 0.45%   |
| WDC WD40EFRX-68N32N0 4TB                            | 1        | 0.45%   |
| WDC WD4003FFBX-68MU3N0 4TB                          | 1        | 0.45%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1        | 0.45%   |
| WDC WD30EZRX-00SPEB0 3TB                            | 1        | 0.45%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 35     | 37.1%   |
| WDC                 | 22       | 38     | 35.48%  |
| Toshiba             | 9        | 17     | 14.52%  |
| HGST                | 4        | 7      | 6.45%   |
| Samsung Electronics | 2        | 2      | 3.23%   |
| Hitachi             | 2        | 4      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 25       | 40     | 38.46%  |
| Crucial             | 10       | 11     | 15.38%  |
| SanDisk             | 6        | 9      | 9.23%   |
| Kingston            | 4        | 4      | 6.15%   |
| Intel               | 4        | 6      | 6.15%   |
| WDC                 | 3        | 4      | 4.62%   |
| Corsair             | 2        | 2      | 3.08%   |
| ZHITAI              | 1        | 1      | 1.54%   |
| Toshiba             | 1        | 1      | 1.54%   |
| Team                | 1        | 1      | 1.54%   |
| SPCC                | 1        | 1      | 1.54%   |
| PNY                 | 1        | 1      | 1.54%   |
| OCZ                 | 1        | 1      | 1.54%   |
| Micron Technology   | 1        | 1      | 1.54%   |
| Intenso             | 1        | 1      | 1.54%   |
| China               | 1        | 1      | 1.54%   |
| ASMT                | 1        | 1      | 1.54%   |
| A-DATA Technology   | 1        | 1      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 57       | 90     | 37.25%  |
| SSD     | 55       | 87     | 35.95%  |
| HDD     | 40       | 103    | 26.14%  |
| Unknown | 1        | 1      | 0.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 69       | 188    | 53.49%  |
| NVMe | 57       | 90     | 44.19%  |
| SAS  | 3        | 3      | 2.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 38       | 56     | 33.33%  |
| 0.51-1.0   | 37       | 62     | 32.46%  |
| 1.01-2.0   | 13       | 19     | 11.4%   |
| 4.01-10.0  | 13       | 28     | 11.4%   |
| 2.01-3.0   | 8        | 14     | 7.02%   |
| 3.01-4.0   | 5        | 11     | 4.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 25       | 26.88%  |
| More than 3000 | 13       | 13.98%  |
| 501-1000       | 13       | 13.98%  |
| 251-500        | 11       | 11.83%  |
| 1-20           | 10       | 10.75%  |
| 1001-2000      | 9        | 9.68%   |
| 101-250        | 8        | 8.6%    |
| 2001-3000      | 4        | 4.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 25       | 26.6%   |
| 1-20           | 17       | 18.09%  |
| 101-250        | 12       | 12.77%  |
| 51-100         | 9        | 9.57%   |
| More than 3000 | 8        | 8.51%   |
| 501-1000       | 6        | 6.38%   |
| 1001-2000      | 5        | 5.32%   |
| 251-500        | 4        | 4.26%   |
| 21-50          | 4        | 4.26%   |
| 2001-3000      | 4        | 4.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                          | Desktops | Drives | Percent |
|----------------------------------------------------------------|----------|--------|---------|
| WDC WD30EZRX-00SPEB0 3TB                                       | 1        | 1      | 5.26%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                       | 1        | 1      | 5.26%   |
| WDC WD20EARX-008FB0 2TB                                        | 1        | 1      | 5.26%   |
| WDC WD1600JS-00NCB1 160GB                                      | 1        | 1      | 5.26%   |
| WDC WD10EZEX-60ZF5A0 1TB                                       | 1        | 1      | 5.26%   |
| Toshiba HDWQ140 4TB                                            | 1        | 1      | 5.26%   |
| Seagate ST8000VN0022-2EL112 8TB                                | 1        | 1      | 5.26%   |
| Seagate ST3500418AS 500GB                                      | 1        | 1      | 5.26%   |
| SanDisk SSD PLUS 240GB                                         | 1        | 1      | 5.26%   |
| Samsung Electronics SSD 970 EVO 1TB                            | 1        | 1      | 5.26%   |
| Samsung Electronics SSD 870 EVO 1TB                            | 1        | 1      | 5.26%   |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 1        | 1      | 5.26%   |
| Micron Technology C400 RealSSD 2.5 7mm 512GB                   | 1        | 1      | 5.26%   |
| Intel SSDSC2BW240A4 240GB                                      | 1        | 1      | 5.26%   |
| Hitachi HDS722020ALA330 2TB                                    | 1        | 1      | 5.26%   |
| HGST HTS545050A7E680 500GB                                     | 1        | 1      | 5.26%   |
| Crucial CT240M500SSD1 240GB                                    | 1        | 1      | 5.26%   |
| Corsair Neutron XT SSD 240GB                                   | 1        | 1      | 5.26%   |
| ASMT 2115 1TB                                                  | 1        | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 26.32%  |
| Samsung Electronics | 3        | 3      | 15.79%  |
| Seagate             | 2        | 2      | 10.53%  |
| Toshiba             | 1        | 1      | 5.26%   |
| SanDisk             | 1        | 1      | 5.26%   |
| Micron Technology   | 1        | 1      | 5.26%   |
| Intel               | 1        | 1      | 5.26%   |
| Hitachi             | 1        | 1      | 5.26%   |
| HGST                | 1        | 1      | 5.26%   |
| Crucial             | 1        | 1      | 5.26%   |
| Corsair             | 1        | 1      | 5.26%   |
| ASMT                | 1        | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 5      | 50%     |
| Seagate | 2        | 2      | 20%     |
| Toshiba | 1        | 1      | 10%     |
| Hitachi | 1        | 1      | 10%     |
| HGST    | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 10     | 50%     |
| SSD  | 7        | 7      | 38.89%  |
| NVMe | 2        | 2      | 11.11%  |

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
| Works    | 86       | 239    | 77.48%  |
| Malfunc  | 14       | 19     | 12.61%  |
| Detected | 8        | 17     | 7.21%   |
| Failed   | 3        | 6      | 2.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 50       | 30.86%  |
| Intel                        | 37       | 22.84%  |
| Samsung Electronics          | 31       | 19.14%  |
| ASMedia Technology           | 10       | 6.17%   |
| SanDisk                      | 9        | 5.56%   |
| Phison Electronics           | 7        | 4.32%   |
| Realtek Semiconductor        | 2        | 1.23%   |
| MAXIO Technology (Hangzhou)  | 2        | 1.23%   |
| LSI Logic / Symbios Logic    | 2        | 1.23%   |
| Kingston Technology Company  | 2        | 1.23%   |
| Yangtze Memory Technologies  | 1        | 0.62%   |
| Toshiba America Info Systems | 1        | 0.62%   |
| SK hynix                     | 1        | 0.62%   |
| Silicon Motion               | 1        | 0.62%   |
| Shenzhen Longsys Electronics | 1        | 0.62%   |
| Nvidia                       | 1        | 0.62%   |
| Micron/Crucial Technology    | 1        | 0.62%   |
| Marvell Technology Group     | 1        | 0.62%   |
| Lite-On Technology           | 1        | 0.62%   |
| Broadcom / LSI               | 1        | 0.62%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 31       | 16.94%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 19       | 10.38%  |
| AMD 500 Series Chipset SATA Controller                                         | 13       | 7.1%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 9        | 4.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7        | 3.83%   |
| AMD 400 Series Chipset SATA Controller                                         | 7        | 3.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5        | 2.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 2.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 2.19%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 3        | 1.64%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3        | 1.64%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3        | 1.64%   |
| Phison E12 NVMe Controller                                                     | 3        | 1.64%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3        | 1.64%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 1.64%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 2        | 1.09%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2        | 1.09%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 2        | 1.09%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 2        | 1.09%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 1.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.09%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 1.09%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                           | 2        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 1.09%   |
| AMD X399 Series Chipset SATA Controller                                        | 2        | 1.09%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 1.09%   |
| Yangtze Memory ZHITAI TiPro7000                                                | 1        | 0.55%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 1        | 0.55%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 1        | 0.55%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1        | 0.55%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.55%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 1        | 0.55%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1        | 0.55%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1        | 0.55%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1        | 0.55%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1        | 0.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.55%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1        | 0.55%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 1        | 0.55%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 85       | 55.19%  |
| NVMe | 57       | 37.01%  |
| IDE  | 6        | 3.9%    |
| RAID | 3        | 1.95%   |
| SAS  | 3        | 1.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 51       | 56.67%  |
| Intel  | 39       | 43.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 7        | 7.78%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 4        | 4.44%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 4        | 4.44%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 4        | 4.44%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 3        | 3.33%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 2.22%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 2        | 2.22%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 2        | 2.22%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 2        | 2.22%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 2        | 2.22%   |
| AMD Ryzen 7 7700X 8-Core Processor             | 2        | 2.22%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 2        | 2.22%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 2        | 2.22%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 2.22%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 2.22%   |
| AMD FX-8320 Eight-Core Processor               | 2        | 2.22%   |
| Intel Xeon W-1290P CPU @ 3.70GHz               | 1        | 1.11%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz            | 1        | 1.11%   |
| Intel Pentium D CPU 3.73GHz                    | 1        | 1.11%   |
| Intel Core i9-9900X CPU @ 3.50GHz              | 1        | 1.11%   |
| Intel Core i7-6850K CPU @ 3.60GHz              | 1        | 1.11%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 1.11%   |
| Intel Core i7-4770K CPU @ 3.50GHz              | 1        | 1.11%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 1        | 1.11%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 1.11%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 1        | 1.11%   |
| Intel Core i5-8600 CPU @ 3.10GHz               | 1        | 1.11%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 1        | 1.11%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 1.11%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 1.11%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1        | 1.11%   |
| Intel Core i5-4570S CPU @ 2.90GHz              | 1        | 1.11%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.11%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 1        | 1.11%   |
| Intel Core i5-3470T CPU @ 2.90GHz              | 1        | 1.11%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1        | 1.11%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 1        | 1.11%   |
| Intel Core i5 CPU 760 @ 2.80GHz                | 1        | 1.11%   |
| Intel Core i3-N305                             | 1        | 1.11%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1        | 1.11%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 17       | 18.89%  |
| Intel Core i5          | 14       | 15.56%  |
| AMD Ryzen 7            | 14       | 15.56%  |
| AMD Ryzen 9            | 13       | 14.44%  |
| Intel Core i7          | 12       | 13.33%  |
| Other                  | 6        | 6.67%   |
| AMD Ryzen Threadripper | 4        | 4.44%   |
| Intel Xeon             | 2        | 2.22%   |
| Intel Core i3          | 2        | 2.22%   |
| AMD FX                 | 2        | 2.22%   |
| Intel Pentium D        | 1        | 1.11%   |
| Intel Core i9          | 1        | 1.11%   |
| Intel Celeron          | 1        | 1.11%   |
| AMD Athlon II X4       | 1        | 1.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 25       | 27.78%  |
| 4      | 21       | 23.33%  |
| 8      | 17       | 18.89%  |
| 16     | 8        | 8.89%   |
| 12     | 8        | 8.89%   |
| 24     | 3        | 3.33%   |
| 10     | 3        | 3.33%   |
| 2      | 3        | 3.33%   |
| 32     | 1        | 1.11%   |
| 14     | 1        | 1.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 89       | 98.89%  |
| 2      | 1        | 1.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 76       | 84.44%  |
| 1      | 14       | 15.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 90       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 13.04%  |
| 0x08701021 | 9        | 9.78%   |
| 0x306c3    | 7        | 7.61%   |
| 0x306a9    | 6        | 6.52%   |
| 0x906ea    | 5        | 5.43%   |
| 0x08701013 | 5        | 5.43%   |
| 0x0a601203 | 4        | 4.35%   |
| 0x0a50000d | 3        | 3.26%   |
| 0xa0653    | 2        | 2.17%   |
| 0x506e3    | 2        | 2.17%   |
| 0x0a50000c | 2        | 2.17%   |
| 0x0a20120a | 2        | 2.17%   |
| 0x0a201204 | 2        | 2.17%   |
| 0x0a201025 | 2        | 2.17%   |
| 0x0a201016 | 2        | 2.17%   |
| 0x0a201009 | 2        | 2.17%   |
| 0x08001138 | 2        | 2.17%   |
| 0x08001137 | 2        | 2.17%   |
| 0xf64      | 1        | 1.09%   |
| 0xb06a2    | 1        | 1.09%   |
| 0xb0671    | 1        | 1.09%   |
| 0x906e9    | 1        | 1.09%   |
| 0x90672    | 1        | 1.09%   |
| 0x406f1    | 1        | 1.09%   |
| 0x306f2    | 1        | 1.09%   |
| 0x206a7    | 1        | 1.09%   |
| 0x106e5    | 1        | 1.09%   |
| 0x0a601201 | 1        | 1.09%   |
| 0x0a404102 | 1        | 1.09%   |
| 0x0a20120e | 1        | 1.09%   |
| 0x0a20102b | 1        | 1.09%   |
| 0x08701030 | 1        | 1.09%   |
| 0x08301055 | 1        | 1.09%   |
| 0x08301025 | 1        | 1.09%   |
| 0x08108109 | 1        | 1.09%   |
| 0x0800820d | 1        | 1.09%   |
| 0x06000852 | 1        | 1.09%   |
| 0x06000822 | 1        | 1.09%   |
| 0x03000027 | 1        | 1.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 18       | 20%     |
| Zen 3            | 17       | 18.89%  |
| Haswell          | 8        | 8.89%   |
| KabyLake         | 7        | 7.78%   |
| IvyBridge        | 6        | 6.67%   |
| Alderlake Hybrid | 6        | 6.67%   |
| Unknown          | 6        | 6.67%   |
| Zen              | 4        | 4.44%   |
| Zen+             | 3        | 3.33%   |
| Skylake          | 3        | 3.33%   |
| CometLake        | 3        | 3.33%   |
| Piledriver       | 2        | 2.22%   |
| SandyBridge      | 1        | 1.11%   |
| NetBurst         | 1        | 1.11%   |
| Nehalem          | 1        | 1.11%   |
| K10 Llano        | 1        | 1.11%   |
| Gracemont        | 1        | 1.11%   |
| Goldmont plus    | 1        | 1.11%   |
| Broadwell        | 1        | 1.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 46       | 46%     |
| Nvidia | 36       | 36%     |
| Intel  | 18       | 18%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]           | 9        | 8.65%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]           | 8        | 7.69%   |
| AMD Raphael                                                       | 4        | 3.85%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]     | 4        | 3.85%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                    | 4        | 3.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]      | 4        | 3.85%   |
| Nvidia TU106 [GeForce RTX 2070]                                   | 3        | 2.88%   |
| Nvidia GK104 [GeForce GTX 760]                                    | 3        | 2.88%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                          | 3        | 2.88%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                        | 3        | 2.88%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                             | 2        | 1.92%   |
| Nvidia GP108 [GeForce GT 1030]                                    | 2        | 1.92%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                               | 2        | 1.92%   |
| Nvidia GP104 [GeForce GTX 1080]                                   | 2        | 1.92%   |
| Nvidia GP104 [GeForce GTX 1070]                                   | 2        | 1.92%   |
| Nvidia GM204 [GeForce GTX 970]                                    | 2        | 1.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller  | 2        | 1.92%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                        | 2        | 1.92%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                            | 2        | 1.92%   |
| Intel HD Graphics 530                                             | 2        | 1.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                         | 2        | 1.92%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                          | 2        | 1.92%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM] | 2        | 1.92%   |
| Nvidia TU117 [GeForce GTX 1650]                                   | 1        | 0.96%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                | 1        | 0.96%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                             | 1        | 0.96%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                             | 1        | 0.96%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                             | 1        | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050]                                   | 1        | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                | 1        | 0.96%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                               | 1        | 0.96%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                | 1        | 0.96%   |
| Nvidia GM206 [GeForce GTX 960]                                    | 1        | 0.96%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                 | 1        | 0.96%   |
| Nvidia GK107 [NVS 510]                                            | 1        | 0.96%   |
| Nvidia GK106 [GeForce GTX 660]                                    | 1        | 0.96%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                 | 1        | 0.96%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                    | 1        | 0.96%   |
| Nvidia GA104 [GeForce RTX 3070]                                   | 1        | 0.96%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                 | 1        | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 36       | 40%     |
| 1 x Nvidia     | 28       | 31.11%  |
| 1 x Intel      | 11       | 12.22%  |
| 2 x AMD        | 4        | 4.44%   |
| Intel + Nvidia | 4        | 4.44%   |
| AMD + Nvidia   | 4        | 4.44%   |
| Intel + AMD    | 2        | 2.22%   |
| Other          | 1        | 1.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 57       | 63.33%  |
| Proprietary | 28       | 31.11%  |
| Unknown     | 5        | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 52.75%  |
| 7.01-8.0   | 18       | 19.78%  |
| 8.01-16.0  | 9        | 9.89%   |
| 1.01-2.0   | 4        | 4.4%    |
| 0.01-0.5   | 4        | 4.4%    |
| 16.01-24.0 | 3        | 3.3%    |
| 3.01-4.0   | 2        | 2.2%    |
| 0.51-1.0   | 2        | 2.2%    |
| 5.01-6.0   | 1        | 1.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 19       | 20.43%  |
| Goldstar             | 15       | 16.13%  |
| Acer                 | 10       | 10.75%  |
| Samsung Electronics  | 7        | 7.53%   |
| Ancor Communications | 6        | 6.45%   |
| Iiyama               | 5        | 5.38%   |
| Lenovo               | 4        | 4.3%    |
| Hewlett-Packard      | 4        | 4.3%    |
| ViewSonic            | 3        | 3.23%   |
| AOC                  | 3        | 3.23%   |
| Vizio                | 2        | 2.15%   |
| Philips              | 2        | 2.15%   |
| MSI                  | 2        | 2.15%   |
| Gigabyte Technology  | 2        | 2.15%   |
| BenQ                 | 2        | 2.15%   |
| Valve                | 1        | 1.08%   |
| Unknown (AAA)        | 1        | 1.08%   |
| Sceptre Tech         | 1        | 1.08%   |
| RTK                  | 1        | 1.08%   |
| NEC Computers        | 1        | 1.08%   |
| MPI                  | 1        | 1.08%   |
| HVR                  | 1        | 1.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vizio E480i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                  | 2        | 2.02%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2        | 2.02%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2        | 2.02%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 2        | 2.02%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2        | 2.02%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 2        | 2.02%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 480x270mm 21.7-inch | 2        | 2.02%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2        | 2.02%   |
| ViewSonic VX2758-SERIES VSCA738 2560x1440 598x336mm 27.0-inch         | 1        | 1.01%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch         | 1        | 1.01%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1        | 1.01%   |
| Valve Index HMD VLV91A8                                               | 1        | 1.01%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1        | 1.01%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 520x320mm 24.0-inch        | 1        | 1.01%   |
| Samsung Electronics SyncMaster SAM0613 1920x1080                      | 1        | 1.01%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1        | 1.01%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch     | 1        | 1.01%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 698x393mm 31.5-inch    | 1        | 1.01%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 1.01%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                     | 1        | 1.01%   |
| Philips PHL BDM4065 PHL08E1 3840x2160 878x485mm 39.5-inch             | 1        | 1.01%   |
| Philips PHL 272V8 PHLC21A 1920x1080 598x336mm 27.0-inch               | 1        | 1.01%   |
| NEC Computers 90GX2 NEC6692 1280x1024 376x301mm 19.0-inch             | 1        | 1.01%   |
| MSI MAG342CQR MSI3DB6 3440x1440 797x333mm 34.0-inch                   | 1        | 1.01%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                        | 1        | 1.01%   |
| MPI WIMAXIT MPI7002 1920x1080 180x130mm 8.7-inch                      | 1        | 1.01%   |
| Lenovo P34w-20 LEN62CC 3440x1440 800x335mm 34.1-inch                  | 1        | 1.01%   |
| Lenovo LEN G24-10 LEN65FD 1920x1080 521x293mm 23.5-inch               | 1        | 1.01%   |
| Lenovo L27q-35 LEN66D5 2560x1440 597x336mm 27.0-inch                  | 1        | 1.01%   |
| Lenovo G27q-20 LEN66C3 2560x1440 597x336mm 27.0-inch                  | 1        | 1.01%   |
| Iiyama PLX2481H IVM611D 1920x1080 521x293mm 23.5-inch                 | 1        | 1.01%   |
| Iiyama PLG2888UH IVM710B 3840x2160                                    | 1        | 1.01%   |
| Iiyama PLE481 IVM480A 1280x1024 376x301mm 19.0-inch                   | 1        | 1.01%   |
| Iiyama PLE2208HDS IVM560A 1920x1080 477x268mm 21.5-inch               | 1        | 1.01%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x330mm 34.1-inch                 | 1        | 1.01%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                  | 1        | 1.01%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 1        | 1.01%   |
| Hewlett-Packard X34 HPN3728 3440x1440 800x335mm 34.1-inch             | 1        | 1.01%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 1        | 1.01%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1        | 1.01%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 35       | 39.77%  |
| 3840x2160 (4K)     | 15       | 17.05%  |
| 2560x1440 (QHD)    | 15       | 17.05%  |
| 1280x1024 (SXGA)   | 6        | 6.82%   |
| 3440x1440          | 5        | 5.68%   |
| 2560x1080          | 4        | 4.55%   |
| 1680x1050 (WSXGA+) | 2        | 2.27%   |
| 2560x1600          | 1        | 1.14%   |
| 2160x1200          | 1        | 1.14%   |
| 1920x1200 (WUXGA)  | 1        | 1.14%   |
| 1600x900 (HD+)     | 1        | 1.14%   |
| 1280x720 (HD)      | 1        | 1.14%   |
| Unknown            | 1        | 1.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 22       | 24.44%  |
| 24      | 14       | 15.56%  |
| 23      | 14       | 15.56%  |
| 34      | 9        | 10%     |
| 21      | 5        | 5.56%   |
| 19      | 4        | 4.44%   |
| 31      | 3        | 3.33%   |
| 25      | 3        | 3.33%   |
| 54      | 2        | 2.22%   |
| 20      | 2        | 2.22%   |
| 17      | 2        | 2.22%   |
| Unknown | 2        | 2.22%   |
| 40      | 1        | 1.11%   |
| 39      | 1        | 1.11%   |
| 38      | 1        | 1.11%   |
| 32      | 1        | 1.11%   |
| 28      | 1        | 1.11%   |
| 26      | 1        | 1.11%   |
| 22      | 1        | 1.11%   |
| 14      | 1        | 1.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 48       | 56.47%  |
| 701-800     | 10       | 11.76%  |
| 401-500     | 8        | 9.41%   |
| 601-700     | 5        | 5.88%   |
| 351-400     | 4        | 4.71%   |
| 801-900     | 3        | 3.53%   |
| 301-350     | 2        | 2.35%   |
| 1001-1500   | 2        | 2.35%   |
| Unknown     | 2        | 2.35%   |
| 201-300     | 1        | 1.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 57       | 71.25%  |
| 21/9    | 9        | 11.25%  |
| 16/10   | 6        | 7.5%    |
| 5/4     | 5        | 6.25%   |
| 6/5     | 1        | 1.25%   |
| 1.00    | 1        | 1.25%   |
| Unknown | 1        | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 27       | 30.34%  |
| 301-350        | 23       | 25.84%  |
| 351-500        | 14       | 15.73%  |
| 151-200        | 8        | 8.99%   |
| 251-300        | 7        | 7.87%   |
| 501-1000       | 3        | 3.37%   |
| More than 1000 | 2        | 2.25%   |
| 141-150        | 2        | 2.25%   |
| Unknown        | 2        | 2.25%   |
| 101-110        | 1        | 1.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 43       | 51.19%  |
| 101-120 | 26       | 30.95%  |
| 161-240 | 7        | 8.33%   |
| 121-160 | 4        | 4.76%   |
| 1-50    | 2        | 2.38%   |
| Unknown | 2        | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 54       | 59.34%  |
| 2     | 21       | 23.08%  |
| 0     | 12       | 13.19%  |
| 3     | 4        | 4.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 54       | 40.3%   |
| Realtek Semiconductor | 52       | 38.81%  |
| MediaTek              | 6        | 4.48%   |
| Aquantia              | 5        | 3.73%   |
| Qualcomm Atheros      | 3        | 2.24%   |
| Ralink Technology     | 2        | 1.49%   |
| Microsoft             | 2        | 1.49%   |
| TP-Link               | 1        | 0.75%   |
| Texas Instruments     | 1        | 0.75%   |
| STMicroelectronics    | 1        | 0.75%   |
| Ralink                | 1        | 0.75%   |
| Oculus VR             | 1        | 0.75%   |
| Nvidia                | 1        | 0.75%   |
| Google                | 1        | 0.75%   |
| D-Link System         | 1        | 0.75%   |
| Broadcom              | 1        | 0.75%   |
| ASUSTek Computer      | 1        | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36       | 22.93%  |
| Intel I211 Gigabit Network Connection                             | 14       | 8.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13       | 8.28%   |
| Intel Wi-Fi 6 AX200                                               | 12       | 7.64%   |
| Intel Ethernet Controller I225-V                                  | 11       | 7.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 2.55%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4        | 2.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 2.55%   |
| Intel Ethernet Connection I217-V                                  | 3        | 1.91%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.91%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3        | 1.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2        | 1.27%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.27%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.27%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.27%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 1.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.64%   |
| Texas Instruments CC2538 USB CDC                                  | 1        | 0.64%   |
| STMicroelectronics Virtual COM Port                               | 1        | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.64%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.64%   |
| Realtek 802.11ac NIC                                              | 1        | 0.64%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.64%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.64%   |
| Ralink RT2800 802.11n PCI                                         | 1        | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.64%   |
| Oculus VR Rift S                                                  | 1        | 0.64%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.64%   |
| Microsoft XBOX ACC                                                | 1        | 0.64%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 0.64%   |
| Intel Wireless-AC 9260                                            | 1        | 0.64%   |
| Intel Wireless 7265                                               | 1        | 0.64%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1        | 0.64%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 26       | 57.78%  |
| MediaTek              | 6        | 13.33%  |
| Realtek Semiconductor | 4        | 8.89%   |
| Ralink Technology     | 2        | 4.44%   |
| Microsoft             | 2        | 4.44%   |
| TP-Link               | 1        | 2.22%   |
| Ralink                | 1        | 2.22%   |
| Qualcomm Atheros      | 1        | 2.22%   |
| D-Link System         | 1        | 2.22%   |
| ASUSTek Computer      | 1        | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                               | 12       | 26.67%  |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4        | 8.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 8.89%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3        | 6.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2        | 4.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 4.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 2.22%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 2.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 2.22%   |
| Realtek 802.11ac NIC                                              | 1        | 2.22%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 2.22%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 2.22%   |
| Ralink RT2800 802.11n PCI                                         | 1        | 2.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 2.22%   |
| Microsoft XBOX ACC                                                | 1        | 2.22%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 2.22%   |
| Intel Wireless-AC 9260                                            | 1        | 2.22%   |
| Intel Wireless 7265                                               | 1        | 2.22%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1        | 2.22%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 2.22%   |
| Intel CNVi: Wi-Fi                                                 | 1        | 2.22%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W] | 1        | 2.22%   |
| ASUS USB-N53 802.11abgn Network Adapter [Ralink RT3572]           | 1        | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 51       | 48.11%  |
| Intel                 | 45       | 42.45%  |
| Aquantia              | 5        | 4.72%   |
| Qualcomm Atheros      | 2        | 1.89%   |
| Nvidia                | 1        | 0.94%   |
| Google                | 1        | 0.94%   |
| Broadcom              | 1        | 0.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36       | 33.03%  |
| Intel I211 Gigabit Network Connection                             | 14       | 12.84%  |
| Realtek RTL8125 2.5GbE Controller                                 | 13       | 11.93%  |
| Intel Ethernet Controller I225-V                                  | 11       | 10.09%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 3.67%   |
| Intel Ethernet Connection I217-V                                  | 3        | 2.75%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.75%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.83%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.83%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.83%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 1.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.92%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.92%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 0.92%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.92%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.92%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.92%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.92%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.92%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 0.92%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 0.92%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.92%   |
| Aquantia AQC100 10G Ethernet MAC controller [AQtion]              | 1        | 0.92%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1        | 0.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 90       | 66.18%  |
| WiFi     | 43       | 31.62%  |
| Modem    | 3        | 2.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 74       | 79.57%  |
| WiFi     | 19       | 20.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 45       | 48.91%  |
| 2     | 37       | 40.22%  |
| 3     | 8        | 8.7%    |
| 4     | 1        | 1.09%   |
| 0     | 1        | 1.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 59       | 64.13%  |
| Yes  | 33       | 35.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 21       | 43.75%  |
| Cambridge Silicon Radio  | 8        | 16.67%  |
| ASUSTek Computer         | 5        | 10.42%  |
| Realtek Semiconductor    | 4        | 8.33%   |
| MediaTek                 | 4        | 8.33%   |
| Broadcom                 | 4        | 8.33%   |
| HTC (High Tech Computer) | 1        | 2.08%   |
| Foxconn / Hon Hai        | 1        | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 10       | 20.83%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 8        | 16.67%  |
| MediaTek Wireless_Device                                             | 4        | 8.33%   |
| Intel AX201 Bluetooth                                                | 4        | 8.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 4        | 8.33%   |
| Realtek Bluetooth Radio                                              | 3        | 6.25%   |
| Intel AX210 Bluetooth                                                | 3        | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 2        | 4.17%   |
| Intel Bluetooth Device                                               | 2        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2        | 4.17%   |
| ASUS ASUS USB-BT500                                                  | 2        | 4.17%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 2.08%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 2.08%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1        | 2.08%   |
| ASUS Bluetooth Device                                                | 1        | 2.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 60       | 31.25%  |
| Intel                                | 38       | 19.79%  |
| Nvidia                               | 37       | 19.27%  |
| C-Media Electronics                  | 6        | 3.13%   |
| Texas Instruments                    | 4        | 2.08%   |
| Razer USA                            | 4        | 2.08%   |
| Focusrite-Novation                   | 4        | 2.08%   |
| Kingston Technology                  | 3        | 1.56%   |
| ASUSTek Computer                     | 3        | 1.56%   |
| Schiit Audio                         | 2        | 1.04%   |
| RODE Microphones                     | 2        | 1.04%   |
| Blue Microphones                     | 2        | 1.04%   |
| Yamaha                               | 1        | 0.52%   |
| Valve Software                       | 1        | 0.52%   |
| Thomann                              | 1        | 0.52%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.52%   |
| Sony                                 | 1        | 0.52%   |
| Shure                                | 1        | 0.52%   |
| Sennheiser Communications            | 1        | 0.52%   |
| Samson Technologies                  | 1        | 0.52%   |
| PreSonus Audio Electronics           | 1        | 0.52%   |
| Mark of the Unicorn                  | 1        | 0.52%   |
| Logitech                             | 1        | 0.52%   |
| Huawei Technologies                  | 1        | 0.52%   |
| Hewlett-Packard                      | 1        | 0.52%   |
| GYROCOM C&C                          | 1        | 0.52%   |
| Giga-Byte Technology                 | 1        | 0.52%   |
| Elgato Systems                       | 1        | 0.52%   |
| Edifier Technology                   | 1        | 0.52%   |
| DSEA A/S                             | 1        | 0.52%   |
| Dell                                 | 1        | 0.52%   |
| Creative Technology                  | 1        | 0.52%   |
| Creative Labs                        | 1        | 0.52%   |
| Corsair                              | 1        | 0.52%   |
| Conexant Systems                     | 1        | 0.52%   |
| AudioQuest                           | 1        | 0.52%   |
| ASRock                               | 1        | 0.52%   |
| Apogee Electronics                   | 1        | 0.52%   |
| Antlion Audio                        | 1        | 0.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 29       | 12.55%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11       | 4.76%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9        | 3.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 3.9%    |
| AMD Navi 10 HDMI Audio                                                     | 8        | 3.46%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 2.6%    |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 2.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 2.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 2.16%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5        | 2.16%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5        | 2.16%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.73%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 1.73%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 1.73%   |
| Nvidia GK104 HDMI Audio Controller                                         | 4        | 1.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 1.73%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 4        | 1.73%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3        | 1.3%    |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.3%    |
| Intel Comet Lake PCH cAVS                                                  | 3        | 1.3%    |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 1.3%    |
| Intel 200 Series PCH HD Audio                                              | 3        | 1.3%    |
| ASUSTek Computer USB Audio                                                 | 3        | 1.3%    |
| Schiit Audio Schiit Modi 3+                                                | 2        | 0.87%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 0.87%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 0.87%   |
| Kingston Technology HyperX 7.1 Audio                                       | 2        | 0.87%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 0.87%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 0.87%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 2        | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 0.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 0.87%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                | 2        | 0.87%   |
| Focusrite-Novation Scarlett 2i2 Camera                                     | 2        | 0.87%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 0.87%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 0.87%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 0.87%   |
| Yamaha AG06/AG03                                                           | 1        | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 29       | 28.71%  |
| G.Skill             | 20       | 19.8%   |
| Kingston            | 17       | 16.83%  |
| Crucial             | 8        | 7.92%   |
| Unknown             | 7        | 6.93%   |
| Samsung Electronics | 7        | 6.93%   |
| Micron Technology   | 3        | 2.97%   |
| Team                | 2        | 1.98%   |
| A-DATA Technology   | 2        | 1.98%   |
| Unknown (ABCD)      | 1        | 0.99%   |
| Strontium           | 1        | 0.99%   |
| SK hynix            | 1        | 0.99%   |
| GOODRAM             | 1        | 0.99%   |
| GLOWAY              | 1        | 0.99%   |
| AMD                 | 1        | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s            | 4        | 3.57%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s              | 3        | 2.68%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s              | 2        | 1.79%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s            | 2        | 1.79%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s               | 2        | 1.79%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s               | 2        | 1.79%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s            | 2        | 1.79%   |
| Corsair RAM Module 16GB DIMM DDR4 2133MT/s                        | 2        | 1.79%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s            | 2        | 1.79%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s            | 2        | 1.79%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s            | 2        | 1.79%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1        | 0.89%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                              | 1        | 0.89%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 1        | 0.89%   |
| Unknown RAM Module 2GB DIMM DRAM 800MT/s                          | 1        | 0.89%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                          | 1        | 0.89%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                     | 1        | 0.89%   |
| Unknown RAM 3733 C17 Series 8192MB DIMM DDR4 2133MT/s             | 1        | 0.89%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1        | 0.89%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s                | 1        | 0.89%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s                | 1        | 0.89%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s                | 1        | 0.89%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s                | 1        | 0.89%   |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                        | 1        | 0.89%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                         | 1        | 0.89%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR5 6400MT/s               | 1        | 0.89%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                    | 1        | 0.89%   |
| Samsung RAM M393A4K40BB0-CPB 32GB RIMM DDR4 2133MT/s              | 1        | 0.89%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s               | 1        | 0.89%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s               | 1        | 0.89%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 1        | 0.89%   |
| Micron RAM 4ATF1G64AZ-3G2E1 8192MB DIMM DDR4 3200MT/s             | 1        | 0.89%   |
| Micron RAM 36ASF4G72PZ-2G1A1 32GB RIMM DDR4 2133MT/s              | 1        | 0.89%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s              | 1        | 0.89%   |
| Kingston RAM Module 4GB DIMM DDR3 1600MT/s                        | 1        | 0.89%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s            | 1        | 0.89%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s               | 1        | 0.89%   |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s              | 1        | 0.89%   |
| Kingston RAM KHX1600C10D3L/8GX 8GB DIMM DDR3 1600MT/s             | 1        | 0.89%   |
| Kingston RAM KF548S38-16 16GB SODIMM DDR5 4800MT/s                | 1        | 0.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 60       | 68.18%  |
| DDR3    | 15       | 17.05%  |
| DDR5    | 8        | 9.09%   |
| LPDDR5  | 1        | 1.14%   |
| LPDDR4  | 1        | 1.14%   |
| DRAM    | 1        | 1.14%   |
| DDR     | 1        | 1.14%   |
| Unknown | 1        | 1.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 82       | 93.18%  |
| SODIMM       | 4        | 4.55%   |
| Row Of Chips | 1        | 1.14%   |
| RIMM         | 1        | 1.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 34       | 34%     |
| 8192  | 34       | 34%     |
| 32768 | 20       | 20%     |
| 4096  | 10       | 10%     |
| 2048  | 2        | 2%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 21       | 20.59%  |
| 3600  | 11       | 10.78%  |
| 1600  | 10       | 9.8%    |
| 2133  | 8        | 7.84%   |
| 3733  | 7        | 6.86%   |
| 2400  | 5        | 4.9%    |
| 1333  | 5        | 4.9%    |
| 6000  | 4        | 3.92%   |
| 3000  | 4        | 3.92%   |
| 5200  | 2        | 1.96%   |
| 4800  | 2        | 1.96%   |
| 3866  | 2        | 1.96%   |
| 3534  | 2        | 1.96%   |
| 3400  | 2        | 1.96%   |
| 3334  | 2        | 1.96%   |
| 2933  | 2        | 1.96%   |
| 2667  | 2        | 1.96%   |
| 6400  | 1        | 0.98%   |
| 4000  | 1        | 0.98%   |
| 3800  | 1        | 0.98%   |
| 3666  | 1        | 0.98%   |
| 2800  | 1        | 0.98%   |
| 2666  | 1        | 0.98%   |
| 2134  | 1        | 0.98%   |
| 2132  | 1        | 0.98%   |
| 1867  | 1        | 0.98%   |
| 1866  | 1        | 0.98%   |
| 800   | 1        | 0.98%   |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 18       | 66.67%  |
| MacroSilicon                  | 3        | 11.11%  |
| Microdia                      | 2        | 7.41%   |
| Valve Software                | 1        | 3.7%    |
| Sunplus Innovation Technology | 1        | 3.7%    |
| HDR webcam                    | 1        | 3.7%    |
| Apple                         | 1        | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Logitech StreamCam                 | 4        | 14.81%  |
| MacroSilicon USB Video             | 3        | 11.11%  |
| Logitech Webcam C270               | 3        | 11.11%  |
| Logitech HD Pro Webcam C920        | 2        | 7.41%   |
| Valve Software 3D Camera           | 1        | 3.7%    |
| Sunplus FHD Camera Microphone      | 1        | 3.7%    |
| Microdia USB Camera                | 1        | 3.7%    |
| Microdia Camera                    | 1        | 3.7%    |
| Logitech Webcam Pro 9000           | 1        | 3.7%    |
| Logitech Webcam C930e              | 1        | 3.7%    |
| Logitech Webcam C120               | 1        | 3.7%    |
| Logitech Logitech Webcam C925e     | 1        | 3.7%    |
| Logitech HD Webcam C615            | 1        | 3.7%    |
| Logitech HD Webcam C525            | 1        | 3.7%    |
| Logitech C930c                     | 1        | 3.7%    |
| Logitech C922 Pro Stream Webcam    | 1        | 3.7%    |
| Logitech BRIO 4K Stream Edition    | 1        | 3.7%    |
| HDR webcam HDR webcam              | 1        | 3.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR | 1        | 3.7%    |

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
| 0     | 73       | 78.49%  |
| 1     | 16       | 17.2%   |
| 2     | 4        | 4.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 6        | 27.27%  |
| Net/wireless          | 5        | 22.73%  |
| Unassigned class      | 3        | 13.64%  |
| Multimedia controller | 3        | 13.64%  |
| Bluetooth             | 2        | 9.09%   |
| Dvb card              | 1        | 4.55%   |
| Chipcard              | 1        | 4.55%   |
| Camera                | 1        | 4.55%   |

