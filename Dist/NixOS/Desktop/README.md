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

Total: 135

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Biostar       | TZ590-BTC DUO               | [86684436da](https://linux-hardware.org/?probe=86684436da) | Jan 27, 2024 |
| Biostar       | TZ590-BTC DUO               | [68df04d154](https://linux-hardware.org/?probe=68df04d154) | Jan 27, 2024 |
| MSI           | MS-B1831                    | [45dd2bc3a1](https://linux-hardware.org/?probe=45dd2bc3a1) | Jan 25, 2024 |
| Gigabyte      | B650M GAMING X AX           | [655122ef53](https://linux-hardware.org/?probe=655122ef53) | Jan 14, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [268e37f04e](https://linux-hardware.org/?probe=268e37f04e) | Jan 14, 2024 |
| ASUSTek       | P8Z77-V LE                  | [929c108f73](https://linux-hardware.org/?probe=929c108f73) | Jan 13, 2024 |
| ASUSTek       | STRIX Z270H GAMING          | [c5eb936632](https://linux-hardware.org/?probe=c5eb936632) | Jan 13, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | [bdc05e8e4e](https://linux-hardware.org/?probe=bdc05e8e4e) | Jan 11, 2024 |
| MSI           | Z170A SLI                   | [e58029e4a2](https://linux-hardware.org/?probe=e58029e4a2) | Jan 08, 2024 |
| Dell          | 0FXD80 A00                  | [628772fa2d](https://linux-hardware.org/?probe=628772fa2d) | Jan 07, 2024 |
| ASUSTek       | PRIME H410M-E               | [3e11f092ef](https://linux-hardware.org/?probe=3e11f092ef) | Jan 07, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | [fb05620dfd](https://linux-hardware.org/?probe=fb05620dfd) | Jan 05, 2024 |
| ASUSTek       | Pro WS TRX50-SAGE WIFI      | [cfba81369c](https://linux-hardware.org/?probe=cfba81369c) | Jan 05, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [527cc7c1d4](https://linux-hardware.org/?probe=527cc7c1d4) | Jan 05, 2024 |
| HP            | 1790                        | [e554a0f029](https://linux-hardware.org/?probe=e554a0f029) | Jan 04, 2024 |
| Gigabyte      | Z390 AORUS PRO-CF           | [91b39eb7b5](https://linux-hardware.org/?probe=91b39eb7b5) | Jan 03, 2024 |
| Gigabyte      | B450 AORUS M                | [733b1e64b3](https://linux-hardware.org/?probe=733b1e64b3) | Jan 03, 2024 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [f96513dd00](https://linux-hardware.org/?probe=f96513dd00) | Jan 02, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [c6c9c3c74e](https://linux-hardware.org/?probe=c6c9c3c74e) | Jan 01, 2024 |
| AZW           | EQ                          | [f27e8ec7a4](https://linux-hardware.org/?probe=f27e8ec7a4) | Dec 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | [f8483f02ab](https://linux-hardware.org/?probe=f8483f02ab) | Dec 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a953876b2c](https://linux-hardware.org/?probe=a953876b2c) | Dec 23, 2023 |
| ASRock        | X670E PG Lightning          | [b6aa52f693](https://linux-hardware.org/?probe=b6aa52f693) | Dec 17, 2023 |
| AZW           | EQ                          | [b6aa615ccf](https://linux-hardware.org/?probe=b6aa615ccf) | Dec 14, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [2982c2a2c6](https://linux-hardware.org/?probe=2982c2a2c6) | Dec 14, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [8617acecda](https://linux-hardware.org/?probe=8617acecda) | Dec 11, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [62c4dde3a6](https://linux-hardware.org/?probe=62c4dde3a6) | Dec 07, 2023 |
| AZW           | EQ                          | [c2dedbf2f3](https://linux-hardware.org/?probe=c2dedbf2f3) | Dec 04, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [7273cc93a9](https://linux-hardware.org/?probe=7273cc93a9) | Dec 02, 2023 |
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
| ASUSTek       | ROG CROSSHAIR X670E GENE    | [a9a56ae120](https://linux-hardware.org/?probe=a9a56ae120) | Aug 22, 2023 |
| AZW           | EQ                          | [4a9aad33f3](https://linux-hardware.org/?probe=4a9aad33f3) | Aug 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | [1abcf2ad6f](https://linux-hardware.org/?probe=1abcf2ad6f) | Aug 04, 2023 |
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
| NixOS 23.05                      | 26       | 23.21%  |
| NixOS 23.11                      | 23       | 20.54%  |
| NixOS 22.11                      | 13       | 11.61%  |
| NixOS 22.05                      | 13       | 11.61%  |
| NixOS 24.05                      | 12       | 10.71%  |
| NixOS 21.11                      | 7        | 6.25%   |
| NixOS                            | 3        | 2.68%   |
| NixOS 21.05pre-git               | 2        | 1.79%   |
| NixOS 21.11.20210528.540dccb     | 1        | 0.89%   |
| NixOS 21.05.993.93963c27b93      | 1        | 0.89%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1        | 0.89%   |
| NixOS 21.05.20210929.ee90403     | 1        | 0.89%   |
| NixOS 21.05.20210430.c8dff32     | 1        | 0.89%   |
| NixOS 21.05.20210224.f6b5bfd     | 1        | 0.89%   |
| NixOS 21.05.1471.a7512bb64b1     | 1        | 0.89%   |
| NixOS 21.03pre246062.420f89ceb26 | 1        | 0.89%   |
| NixOS 21.03.git.b4349c13a6d      | 1        | 0.89%   |
| NixOS 21.03.20201007.420f89c     | 1        | 0.89%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1        | 0.89%   |
| NixOS 20.09pre-git               | 1        | 0.89%   |
| NixOS 20.09.git.4a361b06a93      | 1        | 0.89%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| NixOS | 107      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Desktops | Percent |
|----------------|----------|---------|
| 6.1.55         | 5        | 4.24%   |
| 6.6.8          | 3        | 2.54%   |
| 6.6.0          | 3        | 2.54%   |
| 6.1.69         | 3        | 2.54%   |
| 6.1.37         | 3        | 2.54%   |
| 6.7.0          | 2        | 1.69%   |
| 6.4.7          | 2        | 1.69%   |
| 6.4.0          | 2        | 1.69%   |
| 6.1.71         | 2        | 1.69%   |
| 6.1.61         | 2        | 1.69%   |
| 6.1.60         | 2        | 1.69%   |
| 5.8.1-zen1     | 2        | 1.69%   |
| 5.15.86        | 2        | 1.69%   |
| 5.15.85        | 2        | 1.69%   |
| 5.15.47        | 2        | 1.69%   |
| 5.10.102       | 2        | 1.69%   |
| 6.7.0-rc7      | 1        | 0.85%   |
| 6.6.6          | 1        | 0.85%   |
| 6.6.5-xanmod1  | 1        | 0.85%   |
| 6.6.3          | 1        | 0.85%   |
| 6.6.11         | 1        | 0.85%   |
| 6.6.1          | 1        | 0.85%   |
| 6.5.9-xanmod1  | 1        | 0.85%   |
| 6.5.7          | 1        | 0.85%   |
| 6.5.5          | 1        | 0.85%   |
| 6.5.2          | 1        | 0.85%   |
| 6.5.13         | 1        | 0.85%   |
| 6.5.10-xanmod1 | 1        | 0.85%   |
| 6.5.1          | 1        | 0.85%   |
| 6.4.9          | 1        | 0.85%   |
| 6.4.4          | 1        | 0.85%   |
| 6.3.3          | 1        | 0.85%   |
| 6.2.11         | 1        | 0.85%   |
| 6.2.10         | 1        | 0.85%   |
| 6.1.68         | 1        | 0.85%   |
| 6.1.67         | 1        | 0.85%   |
| 6.1.65         | 1        | 0.85%   |
| 6.1.64         | 1        | 0.85%   |
| 6.1.63         | 1        | 0.85%   |
| 6.1.62         | 1        | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 6.1.55   | 6        | 5.08%   |
| 6.7.0    | 3        | 2.54%   |
| 6.6.8    | 3        | 2.54%   |
| 6.6.0    | 3        | 2.54%   |
| 6.1.69   | 3        | 2.54%   |
| 6.1.37   | 3        | 2.54%   |
| 6.4.7    | 2        | 1.69%   |
| 6.4.0    | 2        | 1.69%   |
| 6.1.71   | 2        | 1.69%   |
| 6.1.61   | 2        | 1.69%   |
| 6.1.60   | 2        | 1.69%   |
| 6.1.31   | 2        | 1.69%   |
| 5.8.1    | 2        | 1.69%   |
| 5.15.86  | 2        | 1.69%   |
| 5.15.85  | 2        | 1.69%   |
| 5.15.47  | 2        | 1.69%   |
| 5.11.16  | 2        | 1.69%   |
| 5.10.102 | 2        | 1.69%   |
| 6.6.6    | 1        | 0.85%   |
| 6.6.5    | 1        | 0.85%   |
| 6.6.3    | 1        | 0.85%   |
| 6.6.11   | 1        | 0.85%   |
| 6.6.1    | 1        | 0.85%   |
| 6.5.9    | 1        | 0.85%   |
| 6.5.7    | 1        | 0.85%   |
| 6.5.5    | 1        | 0.85%   |
| 6.5.2    | 1        | 0.85%   |
| 6.5.13   | 1        | 0.85%   |
| 6.5.10   | 1        | 0.85%   |
| 6.5.1    | 1        | 0.85%   |
| 6.4.9    | 1        | 0.85%   |
| 6.4.4    | 1        | 0.85%   |
| 6.3.3    | 1        | 0.85%   |
| 6.2.11   | 1        | 0.85%   |
| 6.2.10   | 1        | 0.85%   |
| 6.1.68   | 1        | 0.85%   |
| 6.1.67   | 1        | 0.85%   |
| 6.1.65   | 1        | 0.85%   |
| 6.1.64   | 1        | 0.85%   |
| 6.1.63   | 1        | 0.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 34       | 29.57%  |
| 5.15    | 23       | 20%     |
| 6.6     | 11       | 9.57%   |
| 5.10    | 9        | 7.83%   |
| 6.5     | 7        | 6.09%   |
| 5.4     | 5        | 4.35%   |
| 6.4     | 4        | 3.48%   |
| 6.7     | 3        | 2.61%   |
| 5.8     | 3        | 2.61%   |
| 6.2     | 2        | 1.74%   |
| 6.0     | 2        | 1.74%   |
| 5.18    | 2        | 1.74%   |
| 5.11    | 2        | 1.74%   |
| 6.3     | 1        | 0.87%   |
| 5.7     | 1        | 0.87%   |
| 5.19    | 1        | 0.87%   |
| 5.17    | 1        | 0.87%   |
| 5.16    | 1        | 0.87%   |
| 5.14    | 1        | 0.87%   |
| 5.13    | 1        | 0.87%   |
| 5.12    | 1        | 0.87%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 107      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Unknown      | 43       | 39.81%  |
| KDE5         | 22       | 20.37%  |
| GNOME        | 12       | 11.11%  |
| Hyprland     | 7        | 6.48%   |
| sway         | 5        | 4.63%   |
| KDE          | 5        | 4.63%   |
| XFCE         | 4        | 3.7%    |
| none+i3      | 3        | 2.78%   |
| none+awesome | 2        | 1.85%   |
| xsession     | 1        | 0.93%   |
| X-Generic    | 1        | 0.93%   |
| MATE         | 1        | 0.93%   |
| LXQt         | 1        | 0.93%   |
| KDE6         | 1        | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 42       | 38.89%  |
| X11     | 33       | 30.56%  |
| Wayland | 23       | 21.3%   |
| Tty     | 10       | 9.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 48       | 44.44%  |
| SDDM    | 30       | 27.78%  |
| LightDM | 15       | 13.89%  |
| GDM     | 15       | 13.89%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 61       | 57.01%  |
| Unknown | 21       | 19.63%  |
| en_GB   | 9        | 8.41%   |
| en_AU   | 4        | 3.74%   |
| ru_RU   | 3        | 2.8%    |
| en_DK   | 2        | 1.87%   |
| de_DE   | 2        | 1.87%   |
| sv_SE   | 1        | 0.93%   |
| pt_BR   | 1        | 0.93%   |
| it_IT   | 1        | 0.93%   |
| en_NZ   | 1        | 0.93%   |
| de_CH   | 1        | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 89       | 82.41%  |
| BIOS | 19       | 17.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 66       | 61.68%  |
| Btrfs   | 16       | 14.95%  |
| Tmpfs   | 8        | 7.48%   |
| Zfs     | 7        | 6.54%   |
| Xfs     | 5        | 4.67%   |
| Unknown | 3        | 2.8%    |
| F2fs    | 1        | 0.93%   |
| Ext2    | 1        | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 101      | 94.39%  |
| MBR     | 4        | 3.74%   |
| Unknown | 2        | 1.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 74.31%  |
| Yes       | 28       | 25.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 59.26%  |
| Yes       | 44       | 40.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 42       | 39.25%  |
| Gigabyte Technology                  | 18       | 16.82%  |
| MSI                                  | 16       | 14.95%  |
| ASRock                               | 11       | 10.28%  |
| Hewlett-Packard                      | 6        | 5.61%   |
| Acer                                 | 3        | 2.8%    |
| Dell                                 | 2        | 1.87%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.93%   |
| Nvidia                               | 1        | 0.93%   |
| LattePanda                           | 1        | 0.93%   |
| Hardkernel                           | 1        | 0.93%   |
| EVGA                                 | 1        | 0.93%   |
| ECS                                  | 1        | 0.93%   |
| Biostar                              | 1        | 0.93%   |
| AZW                                  | 1        | 0.93%   |
| Unknown                              | 1        | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| MSI MS-7C37                                | 3        | 2.8%    |
| ASUS All Series                            | 3        | 2.8%    |
| MSI MS-7C56                                | 2        | 1.87%   |
| Gigabyte B450M DS3H                        | 2        | 1.87%   |
| ASUS ROG STRIX B550-F GAMING               | 2        | 1.87%   |
| ASUS PRIME X370-PRO                        | 2        | 1.87%   |
| ASRock Z87 Extreme4                        | 2        | 1.87%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.93%   |
| Nvidia 680iLT                              | 1        | 0.93%   |
| MSI MS-7E12                                | 1        | 0.93%   |
| MSI MS-7C95                                | 1        | 0.93%   |
| MSI MS-7C91                                | 1        | 0.93%   |
| MSI MS-7C84                                | 1        | 0.93%   |
| MSI MS-7C35                                | 1        | 0.93%   |
| MSI MS-7B89                                | 1        | 0.93%   |
| MSI MS-7B09                                | 1        | 0.93%   |
| MSI MS-7998                                | 1        | 0.93%   |
| MSI MS-7758                                | 1        | 0.93%   |
| MSI MS-7681                                | 1        | 0.93%   |
| MSI CML-U PRO Cubi 5 (MS-B183)             | 1        | 0.93%   |
| LattePanda Sigma                           | 1        | 0.93%   |
| HP Z220 CMT Workstation                    | 1        | 0.93%   |
| HP Pavilion Gaming Desktop TG01-1xxx       | 1        | 0.93%   |
| HP EliteDesk 800 G4 SFF                    | 1        | 0.93%   |
| HP EliteDesk 800 G2 DM 35W                 | 1        | 0.93%   |
| HP EliteDesk 800 G1 SFF                    | 1        | 0.93%   |
| HP Compaq Elite 8300 SFF                   | 1        | 0.93%   |
| Hardkernel ODROID-H2                       | 1        | 0.93%   |
| Gigabyte Z790 GAMING X AX                  | 1        | 0.93%   |
| Gigabyte Z690 AORUS MASTER                 | 1        | 0.93%   |
| Gigabyte Z390 AORUS PRO                    | 1        | 0.93%   |
| Gigabyte X570 I AORUS PRO WIFI             | 1        | 0.93%   |
| Gigabyte X570 AORUS PRO                    | 1        | 0.93%   |
| Gigabyte X570 AORUS ELITE WIFI             | 1        | 0.93%   |
| Gigabyte X570 AORUS ELITE                  | 1        | 0.93%   |
| Gigabyte X470 AORUS ULTRA GAMING           | 1        | 0.93%   |
| Gigabyte TRX40 AORUS MASTER                | 1        | 0.93%   |
| Gigabyte H97M-D3H                          | 1        | 0.93%   |
| Gigabyte GA-78LMT-USB3 6.0                 | 1        | 0.93%   |
| Gigabyte B760 GAMING X DDR4                | 1        | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 12       | 11.21%  |
| ASUS ROG                                   | 10       | 9.35%   |
| ASUS TUF                                   | 5        | 4.67%   |
| Gigabyte X570                              | 4        | 3.74%   |
| MSI MS-7C37                                | 3        | 2.8%    |
| HP EliteDesk                               | 3        | 2.8%    |
| Gigabyte B450M                             | 3        | 2.8%    |
| ASUS Pro                                   | 3        | 2.8%    |
| ASUS All                                   | 3        | 2.8%    |
| MSI MS-7C56                                | 2        | 1.87%   |
| ASUS P8Z77-V                               | 2        | 1.87%   |
| ASRock Z87                                 | 2        | 1.87%   |
| Acer Aspire                                | 2        | 1.87%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.93%   |
| Nvidia 680iLT                              | 1        | 0.93%   |
| MSI MS-7E12                                | 1        | 0.93%   |
| MSI MS-7C95                                | 1        | 0.93%   |
| MSI MS-7C91                                | 1        | 0.93%   |
| MSI MS-7C84                                | 1        | 0.93%   |
| MSI MS-7C35                                | 1        | 0.93%   |
| MSI MS-7B89                                | 1        | 0.93%   |
| MSI MS-7B09                                | 1        | 0.93%   |
| MSI MS-7998                                | 1        | 0.93%   |
| MSI MS-7758                                | 1        | 0.93%   |
| MSI MS-7681                                | 1        | 0.93%   |
| MSI CML-U                                  | 1        | 0.93%   |
| LattePanda Sigma                           | 1        | 0.93%   |
| HP Z220                                    | 1        | 0.93%   |
| HP Pavilion                                | 1        | 0.93%   |
| HP Compaq                                  | 1        | 0.93%   |
| Hardkernel ODROID-H2                       | 1        | 0.93%   |
| Gigabyte Z790                              | 1        | 0.93%   |
| Gigabyte Z690                              | 1        | 0.93%   |
| Gigabyte Z390                              | 1        | 0.93%   |
| Gigabyte X470                              | 1        | 0.93%   |
| Gigabyte TRX40                             | 1        | 0.93%   |
| Gigabyte H97M-D3H                          | 1        | 0.93%   |
| Gigabyte GA-78LMT-USB3                     | 1        | 0.93%   |
| Gigabyte B760                              | 1        | 0.93%   |
| Gigabyte B650M                             | 1        | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 22       | 20.56%  |
| 2019 | 16       | 14.95%  |
| 2018 | 13       | 12.15%  |
| 2023 | 8        | 7.48%   |
| 2012 | 8        | 7.48%   |
| 2022 | 7        | 6.54%   |
| 2017 | 6        | 5.61%   |
| 2016 | 6        | 5.61%   |
| 2021 | 5        | 4.67%   |
| 2014 | 5        | 4.67%   |
| 2013 | 4        | 3.74%   |
| 2015 | 2        | 1.87%   |
| 2011 | 2        | 1.87%   |
| 2008 | 2        | 1.87%   |
| 2010 | 1        | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 107      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 105      | 98.13%  |
| Enabled  | 2        | 1.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 107      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 31       | 28.97%  |
| 64.01-256.0     | 28       | 26.17%  |
| 16.01-24.0      | 25       | 23.36%  |
| 24.01-32.0      | 9        | 8.41%   |
| 8.01-16.0       | 7        | 6.54%   |
| 4.01-8.0        | 4        | 3.74%   |
| More than 256.0 | 2        | 1.87%   |
| 3.01-4.0        | 1        | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 27       | 24.77%  |
| 8.01-16.0  | 23       | 21.1%   |
| 2.01-3.0   | 16       | 14.68%  |
| 1.01-2.0   | 14       | 12.84%  |
| 3.01-4.0   | 10       | 9.17%   |
| 16.01-24.0 | 9        | 8.26%   |
| 32.01-64.0 | 7        | 6.42%   |
| 0.51-1.0   | 2        | 1.83%   |
| 24.01-32.0 | 1        | 0.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 33       | 29.2%   |
| 1      | 32       | 28.32%  |
| 3      | 24       | 21.24%  |
| 4      | 9        | 7.96%   |
| 5      | 6        | 5.31%   |
| 6      | 4        | 3.54%   |
| 8      | 2        | 1.77%   |
| 23     | 1        | 0.88%   |
| 7      | 1        | 0.88%   |
| 0      | 1        | 0.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 80.56%  |
| Yes       | 21       | 19.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 107      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 55.96%  |
| Yes       | 48       | 44.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 55       | 50.93%  |
| No        | 53       | 49.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 27       | 25.23%  |
| Germany     | 15       | 14.02%  |
| Russia      | 8        | 7.48%   |
| UK          | 7        | 6.54%   |
| Netherlands | 4        | 3.74%   |
| Australia   | 4        | 3.74%   |
| Poland      | 3        | 2.8%    |
| Italy       | 3        | 2.8%    |
| France      | 3        | 2.8%    |
| Canada      | 3        | 2.8%    |
| Belgium     | 3        | 2.8%    |
| Austria     | 3        | 2.8%    |
| Ukraine     | 2        | 1.87%   |
| Sweden      | 2        | 1.87%   |
| Finland     | 2        | 1.87%   |
| Denmark     | 2        | 1.87%   |
| Brazil      | 2        | 1.87%   |
| Turkey      | 1        | 0.93%   |
| Taiwan      | 1        | 0.93%   |
| Switzerland | 1        | 0.93%   |
| Slovenia    | 1        | 0.93%   |
| Serbia      | 1        | 0.93%   |
| Romania     | 1        | 0.93%   |
| Portugal    | 1        | 0.93%   |
| Philippines | 1        | 0.93%   |
| Norway      | 1        | 0.93%   |
| New Zealand | 1        | 0.93%   |
| Mexico      | 1        | 0.93%   |
| Ireland     | 1        | 0.93%   |
| India       | 1        | 0.93%   |
| Hungary     | 1        | 0.93%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Vienna            | 3        | 2.75%   |
| Hamburg           | 3        | 2.75%   |
| Amsterdam         | 3        | 2.75%   |
| Schaafheim        | 2        | 1.83%   |
| Santa Clara       | 2        | 1.83%   |
| Salt Lake City    | 2        | 1.83%   |
| Ramenskoye        | 2        | 1.83%   |
| Plymouth          | 2        | 1.83%   |
| Perth             | 2        | 1.83%   |
| Moscow            | 2        | 1.83%   |
| Marki             | 2        | 1.83%   |
| Kharkiv           | 2        | 1.83%   |
| Duffel            | 2        | 1.83%   |
| Darmstadt         | 2        | 1.83%   |
| Bochum            | 2        | 1.83%   |
| Austin            | 2        | 1.83%   |
| Winchester        | 1        | 0.92%   |
| Wellington        | 1        | 0.92%   |
| Vila Nova de Gaia | 1        | 0.92%   |
| Umeå             | 1        | 0.92%   |
| Troisdorf         | 1        | 0.92%   |
| Tobercurry        | 1        | 0.92%   |
| Taichung          | 1        | 0.92%   |
| Székesfehérvár | 1        | 0.92%   |
| Svenljunga        | 1        | 0.92%   |
| St Petersburg     | 1        | 0.92%   |
| Southampton       | 1        | 0.92%   |
| South Deerfield   | 1        | 0.92%   |
| Sindelfingen      | 1        | 0.92%   |
| San Juan          | 1        | 0.92%   |
| San Gabriel       | 1        | 0.92%   |
| Saarbrücken      | 1        | 0.92%   |
| Rochester         | 1        | 0.92%   |
| Richardson        | 1        | 0.92%   |
| Redwood City      | 1        | 0.92%   |
| Rapid City        | 1        | 0.92%   |
| Pisa              | 1        | 0.92%   |
| Paris             | 1        | 0.92%   |
| Palm Bay          | 1        | 0.92%   |
| Oulu              | 1        | 0.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 60       | 104    | 28.44%  |
| WDC                         | 27       | 49     | 12.8%   |
| Seagate                     | 27       | 40     | 12.8%   |
| SanDisk                     | 16       | 21     | 7.58%   |
| Toshiba                     | 13       | 24     | 6.16%   |
| Crucial                     | 11       | 12     | 5.21%   |
| Phison Electronics          | 7        | 10     | 3.32%   |
| Kingston                    | 7        | 7      | 3.32%   |
| Intel                       | 5        | 7      | 2.37%   |
| HGST                        | 4        | 7      | 1.9%    |
| Realtek Semiconductor       | 3        | 3      | 1.42%   |
| SK hynix                    | 2        | 2      | 0.95%   |
| MAXIO Technology (Hangzhou) | 2        | 4      | 0.95%   |
| Kingston Technology Company | 2        | 2      | 0.95%   |
| Hitachi                     | 2        | 4      | 0.95%   |
| Corsair                     | 2        | 2      | 0.95%   |
| ZHITAI                      | 1        | 1      | 0.47%   |
| Yangtze Memory Technologies | 1        | 2      | 0.47%   |
| Unknown                     | 1        | 1      | 0.47%   |
| Team                        | 1        | 1      | 0.47%   |
| SPCC                        | 1        | 1      | 0.47%   |
| Silicon Motion              | 1        | 1      | 0.47%   |
| PNY                         | 1        | 1      | 0.47%   |
| Plextor                     | 1        | 1      | 0.47%   |
| Phison                      | 1        | 1      | 0.47%   |
| Patriot                     | 1        | 1      | 0.47%   |
| OCZ                         | 1        | 1      | 0.47%   |
| Micron/Crucial Technology   | 1        | 1      | 0.47%   |
| Micron Technology           | 1        | 1      | 0.47%   |
| MBED                        | 1        | 1      | 0.47%   |
| Lexar                       | 1        | 1      | 0.47%   |
| KingFast                    | 1        | 1      | 0.47%   |
| Intenso                     | 1        | 1      | 0.47%   |
| China                       | 1        | 1      | 0.47%   |
| ASMT                        | 1        | 1      | 0.47%   |
| A-DATA Technology           | 1        | 1      | 0.47%   |
| Unknown                     | 1        | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 12       | 4.56%   |
| Samsung SSD 860 EVO 1TB                            | 7        | 2.66%   |
| Samsung SSD 860 EVO 500GB                          | 6        | 2.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 6        | 2.28%   |
| Samsung SSD 860 QVO 1TB                            | 4        | 1.52%   |
| Seagate ST3000DM001-1ER166 3TB                     | 3        | 1.14%   |
| Seagate ST3000DM001-1CH166 3TB                     | 3        | 1.14%   |
| SanDisk SSD PLUS 240GB                             | 3        | 1.14%   |
| Samsung SSD 970 EVO Plus 2TB                       | 3        | 1.14%   |
| Phison E16 PCIe4 NVMe Controller 2TB               | 3        | 1.14%   |
| WDC WD80EMAZ-00WJTA0 8TB                           | 2        | 0.76%   |
| WDC WD10EZEX-60ZF5A0 1TB                           | 2        | 0.76%   |
| Toshiba DT01ACA300 3TB                             | 2        | 0.76%   |
| Seagate ST4000DM004-2CV104 4TB                     | 2        | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2        | 0.76%   |
| Seagate ST1000DM003-1CH162 1TB                     | 2        | 0.76%   |
| Sandisk WD_BLACK SN850X 2000GB                     | 2        | 0.76%   |
| Sandisk WD_BLACK SN770 500GB                       | 2        | 0.76%   |
| Samsung SSD 990 PRO 1TB                            | 2        | 0.76%   |
| Samsung SSD 980 PRO 1TB                            | 2        | 0.76%   |
| Samsung SSD 980 1TB                                | 2        | 0.76%   |
| Samsung SSD 970 EVO Plus 1TB                       | 2        | 0.76%   |
| Samsung SSD 970 EVO 500GB                          | 2        | 0.76%   |
| Samsung SSD 970 EVO 1TB                            | 2        | 0.76%   |
| Samsung SSD 870 QVO 8TB                            | 2        | 0.76%   |
| Samsung SSD 860 EVO 2TB                            | 2        | 0.76%   |
| Samsung SSD 860 EVO 250GB                          | 2        | 0.76%   |
| Samsung SSD 850 EVO 500GB                          | 2        | 0.76%   |
| Samsung NVMe SSD Drive 1TB                         | 2        | 0.76%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB | 2        | 0.76%   |
| Kingston SA400S37960G 960GB SSD                    | 2        | 0.76%   |
| Crucial CT250MX500SSD1 250GB                       | 2        | 0.76%   |
| Crucial CT1000MX500SSD1 1TB                        | 2        | 0.76%   |
| ZHITAI SC001 Active 512GB SSD                      | 1        | 0.38%   |
| Yangtze Memory ZHITAI TiPro7000 1TB                | 1        | 0.38%   |
| Yangtze Memory ZHITAI TiPlus7100 1TB               | 1        | 0.38%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 1        | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                   | 1        | 0.38%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                     | 1        | 0.38%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                     | 1        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 27       | 40     | 38.03%  |
| WDC                 | 25       | 44     | 35.21%  |
| Toshiba             | 11       | 19     | 15.49%  |
| HGST                | 4        | 7      | 5.63%   |
| Samsung Electronics | 2        | 2      | 2.82%   |
| Hitachi             | 2        | 4      | 2.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 31       | 46     | 39.24%  |
| Crucial             | 11       | 12     | 13.92%  |
| SanDisk             | 6        | 9      | 7.59%   |
| Kingston            | 6        | 6      | 7.59%   |
| WDC                 | 4        | 5      | 5.06%   |
| Intel               | 4        | 6      | 5.06%   |
| Corsair             | 2        | 2      | 2.53%   |
| ZHITAI              | 1        | 1      | 1.27%   |
| Toshiba             | 1        | 1      | 1.27%   |
| Team                | 1        | 1      | 1.27%   |
| SPCC                | 1        | 1      | 1.27%   |
| SK hynix            | 1        | 1      | 1.27%   |
| PNY                 | 1        | 1      | 1.27%   |
| Patriot             | 1        | 1      | 1.27%   |
| OCZ                 | 1        | 1      | 1.27%   |
| Micron Technology   | 1        | 1      | 1.27%   |
| KingFast            | 1        | 1      | 1.27%   |
| Intenso             | 1        | 1      | 1.27%   |
| China               | 1        | 1      | 1.27%   |
| ASMT                | 1        | 1      | 1.27%   |
| A-DATA Technology   | 1        | 1      | 1.27%   |
| Unknown             | 1        | 1      | 1.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 69       | 102    | 37.5%   |
| SSD     | 66       | 101    | 35.87%  |
| HDD     | 48       | 116    | 26.09%  |
| Unknown | 1        | 1      | 0.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 84       | 214    | 53.5%   |
| NVMe | 69       | 102    | 43.95%  |
| SAS  | 4        | 4      | 2.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 49       | 70     | 35.77%  |
| 0.51-1.0   | 43       | 68     | 31.39%  |
| 1.01-2.0   | 14       | 20     | 10.22%  |
| 4.01-10.0  | 13       | 28     | 9.49%   |
| 2.01-3.0   | 10       | 16     | 7.3%    |
| 3.01-4.0   | 6        | 12     | 4.38%   |
| 10.01-20.0 | 2        | 3      | 1.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 26       | 23.64%  |
| 501-1000       | 16       | 14.55%  |
| More than 3000 | 15       | 13.64%  |
| 1-20           | 14       | 12.73%  |
| 251-500        | 12       | 10.91%  |
| 1001-2000      | 12       | 10.91%  |
| 101-250        | 9        | 8.18%   |
| 2001-3000      | 6        | 5.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 26       | 23.42%  |
| 1-20           | 22       | 19.82%  |
| 101-250        | 15       | 13.51%  |
| More than 3000 | 9        | 8.11%   |
| 51-100         | 9        | 8.11%   |
| 501-1000       | 8        | 7.21%   |
| 1001-2000      | 7        | 6.31%   |
| 21-50          | 6        | 5.41%   |
| 2001-3000      | 5        | 4.5%    |
| 251-500        | 4        | 3.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                          | Desktops | Drives | Percent |
|----------------------------------------------------------------|----------|--------|---------|
| WDC WD30EZRX-00SPEB0 3TB                                       | 1        | 1      | 4.76%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                       | 1        | 1      | 4.76%   |
| WDC WD20EARX-008FB0 2TB                                        | 1        | 1      | 4.76%   |
| WDC WD1600JS-00NCB1 160GB                                      | 1        | 1      | 4.76%   |
| WDC WD10EZEX-60ZF5A0 1TB                                       | 1        | 1      | 4.76%   |
| Toshiba HDWQ140 4TB                                            | 1        | 1      | 4.76%   |
| SK hynix HFS250G32TND-N1A2A 250GB SSD                          | 1        | 1      | 4.76%   |
| Seagate ST8000VN0022-2EL112 8TB                                | 1        | 1      | 4.76%   |
| Seagate ST3500418AS 500GB                                      | 1        | 1      | 4.76%   |
| SanDisk SSD PLUS 240GB                                         | 1        | 1      | 4.76%   |
| Samsung Electronics SSD 970 EVO 1TB                            | 1        | 1      | 4.76%   |
| Samsung Electronics SSD 870 EVO 1TB                            | 1        | 1      | 4.76%   |
| Samsung Electronics SSD 850 EVO 1TB                            | 1        | 1      | 4.76%   |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 1        | 1      | 4.76%   |
| Micron Technology C400 RealSSD 2.5 7mm 512GB                   | 1        | 1      | 4.76%   |
| Intel SSDSC2BW240A4 240GB                                      | 1        | 1      | 4.76%   |
| Hitachi HDS722020ALA330 2TB                                    | 1        | 1      | 4.76%   |
| HGST HTS545050A7E680 500GB                                     | 1        | 1      | 4.76%   |
| Crucial CT240M500SSD1 240GB                                    | 1        | 1      | 4.76%   |
| Corsair Neutron XT SSD 240GB                                   | 1        | 1      | 4.76%   |
| ASMT 2115 2TB                                                  | 1        | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 23.81%  |
| Samsung Electronics | 4        | 4      | 19.05%  |
| Seagate             | 2        | 2      | 9.52%   |
| Toshiba             | 1        | 1      | 4.76%   |
| SK hynix            | 1        | 1      | 4.76%   |
| SanDisk             | 1        | 1      | 4.76%   |
| Micron Technology   | 1        | 1      | 4.76%   |
| Intel               | 1        | 1      | 4.76%   |
| Hitachi             | 1        | 1      | 4.76%   |
| HGST                | 1        | 1      | 4.76%   |
| Crucial             | 1        | 1      | 4.76%   |
| Corsair             | 1        | 1      | 4.76%   |
| ASMT                | 1        | 1      | 4.76%   |

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
| SSD  | 9        | 9      | 45%     |
| HDD  | 9        | 10     | 45%     |
| NVMe | 2        | 2      | 10%     |

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
| Works    | 102      | 274    | 77.86%  |
| Malfunc  | 16       | 21     | 12.21%  |
| Detected | 10       | 19     | 7.63%   |
| Failed   | 3        | 6      | 2.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 56       | 28.87%  |
| Intel                        | 48       | 24.74%  |
| Samsung Electronics          | 38       | 19.59%  |
| ASMedia Technology           | 11       | 5.67%   |
| SanDisk                      | 10       | 5.15%   |
| Phison Electronics           | 8        | 4.12%   |
| Realtek Semiconductor        | 3        | 1.55%   |
| Kingston Technology Company  | 3        | 1.55%   |
| Toshiba America Info Systems | 2        | 1.03%   |
| MAXIO Technology (Hangzhou)  | 2        | 1.03%   |
| Marvell Technology Group     | 2        | 1.03%   |
| LSI Logic / Symbios Logic    | 2        | 1.03%   |
| Yangtze Memory Technologies  | 1        | 0.52%   |
| SK hynix                     | 1        | 0.52%   |
| Silicon Motion               | 1        | 0.52%   |
| Shenzhen Longsys Electronics | 1        | 0.52%   |
| Nvidia                       | 1        | 0.52%   |
| Micron/Crucial Technology    | 1        | 0.52%   |
| Lite-On Technology           | 1        | 0.52%   |
| INNOGRIT                     | 1        | 0.52%   |
| Broadcom / LSI               | 1        | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 29       | 13.36%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 24       | 11.06%  |
| AMD 500 Series Chipset SATA Controller                                         | 13       | 5.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9        | 4.15%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 9        | 4.15%   |
| AMD 600 Series Chipset SATA Controller                                         | 8        | 3.69%   |
| AMD 400 Series Chipset SATA Controller                                         | 8        | 3.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6        | 2.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5        | 2.3%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4        | 1.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 1.84%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 1.84%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 3        | 1.38%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3        | 1.38%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3        | 1.38%   |
| Phison E12 NVMe Controller                                                     | 3        | 1.38%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 1.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 1.38%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3        | 1.38%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 2        | 0.92%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2        | 0.92%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 2        | 0.92%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 2        | 0.92%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 2        | 0.92%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 0.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 0.92%   |
| AMD X399 Series Chipset SATA Controller                                        | 2        | 0.92%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 0.92%   |
| Yangtze Memory ZHITAI TiPro7000                                                | 1        | 0.46%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 1        | 0.46%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1        | 0.46%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 1        | 0.46%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1        | 0.46%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.46%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 1        | 0.46%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1        | 0.46%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1        | 0.46%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1        | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 101      | 55.19%  |
| NVMe | 69       | 37.7%   |
| IDE  | 6        | 3.28%   |
| RAID | 4        | 2.19%   |
| SAS  | 3        | 1.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 57       | 53.27%  |
| Intel  | 50       | 46.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 8        | 7.48%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 5        | 4.67%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 4        | 3.74%   |
| AMD Ryzen 9 7950X 16-Core Processor            | 3        | 2.8%    |
| AMD Ryzen 9 5900X 12-Core Processor            | 3        | 2.8%    |
| AMD Ryzen 5 5600G with Radeon Graphics         | 3        | 2.8%    |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 1.87%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 2        | 1.87%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 2        | 1.87%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 2        | 1.87%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 2        | 1.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 2        | 1.87%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 2        | 1.87%   |
| AMD Ryzen 7 7700X 8-Core Processor             | 2        | 1.87%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 2        | 1.87%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 2        | 1.87%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 1.87%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 1.87%   |
| AMD FX-8320 Eight-Core Processor               | 2        | 1.87%   |
| Intel Xeon W-1290P CPU @ 3.70GHz               | 1        | 0.93%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz            | 1        | 0.93%   |
| Intel Pentium D CPU 3.73GHz                    | 1        | 0.93%   |
| Intel Core i9-9900X CPU @ 3.50GHz              | 1        | 0.93%   |
| Intel Core i7-9700K CPU @ 3.60GHz              | 1        | 0.93%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 0.93%   |
| Intel Core i7-6850K CPU @ 3.60GHz              | 1        | 0.93%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1        | 0.93%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 0.93%   |
| Intel Core i7-4770K CPU @ 3.50GHz              | 1        | 0.93%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 1        | 0.93%   |
| Intel Core i7-10700F CPU @ 2.90GHz             | 1        | 0.93%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 0.93%   |
| Intel Core i5-8600 CPU @ 3.10GHz               | 1        | 0.93%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 1        | 0.93%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 0.93%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 0.93%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1        | 0.93%   |
| Intel Core i5-4570S CPU @ 2.90GHz              | 1        | 0.93%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 0.93%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 1        | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 19       | 17.76%  |
| AMD Ryzen 5            | 18       | 16.82%  |
| Intel Core i5          | 15       | 14.02%  |
| AMD Ryzen 9            | 15       | 14.02%  |
| AMD Ryzen 7            | 15       | 14.02%  |
| Other                  | 9        | 8.41%   |
| AMD Ryzen Threadripper | 5        | 4.67%   |
| Intel Xeon             | 2        | 1.87%   |
| Intel Core i3          | 2        | 1.87%   |
| AMD FX                 | 2        | 1.87%   |
| Intel Pentium D        | 1        | 0.93%   |
| Intel Core i9          | 1        | 0.93%   |
| Intel Celeron          | 1        | 0.93%   |
| AMD Ryzen 3            | 1        | 0.93%   |
| AMD Athlon II X4       | 1        | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 27       | 25.23%  |
| 4      | 27       | 25.23%  |
| 8      | 22       | 20.56%  |
| 16     | 11       | 10.28%  |
| 12     | 8        | 7.48%   |
| 24     | 3        | 2.8%    |
| 10     | 3        | 2.8%    |
| 2      | 3        | 2.8%    |
| 64     | 1        | 0.93%   |
| 32     | 1        | 0.93%   |
| 14     | 1        | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 106      | 99.07%  |
| 2      | 1        | 0.93%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 91       | 85.05%  |
| 1      | 16       | 14.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 107      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 17.43%  |
| 0x08701021 | 10       | 9.17%   |
| 0x306a9    | 8        | 7.34%   |
| 0x306c3    | 7        | 6.42%   |
| 0x906ea    | 5        | 4.59%   |
| 0x0a601203 | 5        | 4.59%   |
| 0x08701013 | 5        | 4.59%   |
| 0x0a50000d | 3        | 2.75%   |
| 0x08001138 | 3        | 2.75%   |
| 0xa0653    | 2        | 1.83%   |
| 0x906e9    | 2        | 1.83%   |
| 0x506e3    | 2        | 1.83%   |
| 0x0a50000c | 2        | 1.83%   |
| 0x0a20120a | 2        | 1.83%   |
| 0x0a201204 | 2        | 1.83%   |
| 0x0a20102b | 2        | 1.83%   |
| 0x0a201016 | 2        | 1.83%   |
| 0x0a201009 | 2        | 1.83%   |
| 0x08001137 | 2        | 1.83%   |
| 0xf64      | 1        | 0.92%   |
| 0xb06a2    | 1        | 0.92%   |
| 0xb0671    | 1        | 0.92%   |
| 0xa0655    | 1        | 0.92%   |
| 0x906ec    | 1        | 0.92%   |
| 0x90672    | 1        | 0.92%   |
| 0x806ec    | 1        | 0.92%   |
| 0x406f1    | 1        | 0.92%   |
| 0x306f2    | 1        | 0.92%   |
| 0x206a7    | 1        | 0.92%   |
| 0x106e5    | 1        | 0.92%   |
| 0x0a601201 | 1        | 0.92%   |
| 0x0a404102 | 1        | 0.92%   |
| 0x0a20120e | 1        | 0.92%   |
| 0x0a201025 | 1        | 0.92%   |
| 0x08701030 | 1        | 0.92%   |
| 0x08301055 | 1        | 0.92%   |
| 0x08301025 | 1        | 0.92%   |
| 0x08108109 | 1        | 0.92%   |
| 0x08101016 | 1        | 0.92%   |
| 0x0800820d | 1        | 0.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 19       | 17.76%  |
| Zen 3            | 17       | 15.89%  |
| KabyLake         | 10       | 9.35%   |
| Unknown          | 9        | 8.41%   |
| IvyBridge        | 8        | 7.48%   |
| Haswell          | 8        | 7.48%   |
| Alderlake Hybrid | 7        | 6.54%   |
| Zen              | 6        | 5.61%   |
| CometLake        | 5        | 4.67%   |
| Skylake          | 4        | 3.74%   |
| Zen+             | 3        | 2.8%    |
| Piledriver       | 2        | 1.87%   |
| Icelake          | 2        | 1.87%   |
| SandyBridge      | 1        | 0.93%   |
| NetBurst         | 1        | 0.93%   |
| Nehalem          | 1        | 0.93%   |
| K10 Llano        | 1        | 0.93%   |
| Gracemont        | 1        | 0.93%   |
| Goldmont plus    | 1        | 0.93%   |
| Broadwell        | 1        | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 54       | 44.26%  |
| Nvidia | 44       | 36.07%  |
| Intel  | 24       | 19.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]           | 10       | 7.81%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]           | 9        | 7.03%   |
| AMD Raphael                                                       | 6        | 4.69%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]     | 5        | 3.91%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                        | 4        | 3.13%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                    | 4        | 3.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]      | 4        | 3.13%   |
| Nvidia TU106 [GeForce RTX 2070]                                   | 3        | 2.34%   |
| Nvidia GM204 [GeForce GTX 970]                                    | 3        | 2.34%   |
| Nvidia GK104 [GeForce GTX 760]                                    | 3        | 2.34%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                            | 3        | 2.34%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                    | 3        | 2.34%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                             | 2        | 1.56%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                             | 2        | 1.56%   |
| Nvidia GP108 [GeForce GT 1030]                                    | 2        | 1.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                               | 2        | 1.56%   |
| Nvidia GP104 [GeForce GTX 1080]                                   | 2        | 1.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                   | 2        | 1.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller  | 2        | 1.56%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                         | 2        | 1.56%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                        | 2        | 1.56%   |
| Intel HD Graphics 630                                             | 2        | 1.56%   |
| Intel HD Graphics 530                                             | 2        | 1.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                         | 2        | 1.56%   |
| Intel AlderLake-S GT1                                             | 2        | 1.56%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                          | 2        | 1.56%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM] | 2        | 1.56%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                         | 2        | 1.56%   |
| Nvidia TU117 [GeForce GTX 1650]                                   | 1        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                | 1        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                             | 1        | 0.78%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                            | 1        | 0.78%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                             | 1        | 0.78%   |
| Nvidia GP107GL [Quadro P1000]                                     | 1        | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050]                                   | 1        | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                | 1        | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                               | 1        | 0.78%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                | 1        | 0.78%   |
| Nvidia GM206 [GeForce GTX 960]                                    | 1        | 0.78%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                 | 1        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 41       | 38.32%  |
| 1 x Nvidia      | 33       | 30.84%  |
| 1 x Intel       | 13       | 12.15%  |
| Intel + Nvidia  | 6        | 5.61%   |
| 2 x AMD         | 5        | 4.67%   |
| AMD + Nvidia    | 5        | 4.67%   |
| Intel + AMD     | 2        | 1.87%   |
| Other           | 1        | 0.93%   |
| Intel + 2 x AMD | 1        | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 68       | 63.55%  |
| Proprietary | 33       | 30.84%  |
| Unknown     | 6        | 5.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 57       | 52.78%  |
| 7.01-8.0   | 20       | 18.52%  |
| 8.01-16.0  | 11       | 10.19%  |
| 1.01-2.0   | 6        | 5.56%   |
| 0.01-0.5   | 5        | 4.63%   |
| 16.01-24.0 | 4        | 3.7%    |
| 3.01-4.0   | 2        | 1.85%   |
| 0.51-1.0   | 2        | 1.85%   |
| 5.01-6.0   | 1        | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 21       | 18.92%  |
| Goldstar             | 18       | 16.22%  |
| Acer                 | 13       | 11.71%  |
| Samsung Electronics  | 9        | 8.11%   |
| Ancor Communications | 8        | 7.21%   |
| Iiyama               | 5        | 4.5%    |
| Hewlett-Packard      | 5        | 4.5%    |
| Lenovo               | 4        | 3.6%    |
| BenQ                 | 4        | 3.6%    |
| ViewSonic            | 3        | 2.7%    |
| AOC                  | 3        | 2.7%    |
| Vizio                | 2        | 1.8%    |
| Philips              | 2        | 1.8%    |
| MSI                  | 2        | 1.8%    |
| Gigabyte Technology  | 2        | 1.8%    |
| Valve                | 1        | 0.9%    |
| Unknown (AAA)        | 1        | 0.9%    |
| Sceptre Tech         | 1        | 0.9%    |
| RTK                  | 1        | 0.9%    |
| NEC Computers        | 1        | 0.9%    |
| MPI                  | 1        | 0.9%    |
| Insignia             | 1        | 0.9%    |
| HVR                  | 1        | 0.9%    |
| Hitachi              | 1        | 0.9%    |
| ASUSTek Computer     | 1        | 0.9%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Vizio E32-C1 VIZ1004 1920x1080 698x392mm 31.5-inch                     | 2        | 1.68%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2        | 1.68%   |
| Goldstar HDR WQHD GSM772E 3440x1440 800x335mm 34.1-inch                | 2        | 1.68%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 2        | 1.68%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                       | 2        | 1.68%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                      | 2        | 1.68%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                    | 2        | 1.68%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 2        | 1.68%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                   | 2        | 1.68%   |
| ViewSonic VX2758-SERIES VSCA738 2560x1440 598x336mm 27.0-inch          | 1        | 0.84%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch          | 1        | 0.84%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch               | 1        | 0.84%   |
| Valve Index HMD VLV91A8                                                | 1        | 0.84%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch            | 1        | 0.84%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch         | 1        | 0.84%   |
| Samsung Electronics SyncMaster SAM0613 1920x1080                       | 1        | 0.84%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch   | 1        | 0.84%   |
| Samsung Electronics SMT27A550 SAM07B8 1920x1080 598x336mm 27.0-inch    | 1        | 0.84%   |
| Samsung Electronics LS49A950U SAM71CC 3840x1080 1192x336mm 48.8-inch   | 1        | 0.84%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 1020x570mm 46.0-inch | 1        | 0.84%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 698x393mm 31.5-inch     | 1        | 0.84%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1        | 0.84%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                      | 1        | 0.84%   |
| Philips PHL BDM4065 PHL08E1 3840x2160 880x490mm 39.7-inch              | 1        | 0.84%   |
| Philips PHL 272V8 PHLC21A 1920x1080 600x340mm 27.2-inch                | 1        | 0.84%   |
| NEC Computers 90GX2 NEC6692 1280x1024 376x301mm 19.0-inch              | 1        | 0.84%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 797x333mm 34.0-inch                   | 1        | 0.84%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                         | 1        | 0.84%   |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                       | 1        | 0.84%   |
| Lenovo P34w-20 LEN62CC 3440x1440 800x335mm 34.1-inch                   | 1        | 0.84%   |
| Lenovo LEN G24-10 LEN65FD 1920x1080 521x293mm 23.5-inch                | 1        | 0.84%   |
| Lenovo L27q-35 LEN66D5 2560x1440 597x336mm 27.0-inch                   | 1        | 0.84%   |
| Lenovo G27q-20 LEN66C3 2560x1440 597x336mm 27.0-inch                   | 1        | 0.84%   |
| Insignia NS-32F202NA22 BBY3292 1920x1080 697x392mm 31.5-inch           | 1        | 0.84%   |
| Iiyama PLX2481H IVM611D 1920x1080 521x293mm 23.5-inch                  | 1        | 0.84%   |
| Iiyama PLG2888UH IVM710B 3840x2160                                     | 1        | 0.84%   |
| Iiyama PLE481 IVM480A 1280x1024 376x301mm 19.0-inch                    | 1        | 0.84%   |
| Iiyama PLE2208HDS IVM560A 1920x1080 477x268mm 21.5-inch                | 1        | 0.84%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x330mm 34.1-inch                  | 1        | 0.84%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                   | 1        | 0.84%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 43       | 40.19%  |
| 2560x1440 (QHD)    | 20       | 18.69%  |
| 3840x2160 (4K)     | 18       | 16.82%  |
| 1280x1024 (SXGA)   | 7        | 6.54%   |
| 3440x1440          | 5        | 4.67%   |
| 2560x1080          | 4        | 3.74%   |
| 1680x1050 (WSXGA+) | 2        | 1.87%   |
| 3840x1080          | 1        | 0.93%   |
| 2560x2880          | 1        | 0.93%   |
| 2560x1600          | 1        | 0.93%   |
| 2160x1200          | 1        | 0.93%   |
| 1920x1200 (WUXGA)  | 1        | 0.93%   |
| 1600x900 (HD+)     | 1        | 0.93%   |
| 1280x720 (HD)      | 1        | 0.93%   |
| Unknown            | 1        | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 28       | 25.69%  |
| 24      | 18       | 16.51%  |
| 23      | 14       | 12.84%  |
| 34      | 11       | 10.09%  |
| 31      | 6        | 5.5%    |
| 21      | 6        | 5.5%    |
| 19      | 5        | 4.59%   |
| 25      | 3        | 2.75%   |
| 84      | 2        | 1.83%   |
| 54      | 2        | 1.83%   |
| 20      | 2        | 1.83%   |
| 17      | 2        | 1.83%   |
| Unknown | 2        | 1.83%   |
| 48      | 1        | 0.92%   |
| 40      | 1        | 0.92%   |
| 39      | 1        | 0.92%   |
| 38      | 1        | 0.92%   |
| 32      | 1        | 0.92%   |
| 26      | 1        | 0.92%   |
| 22      | 1        | 0.92%   |
| 14      | 1        | 0.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 56       | 53.85%  |
| 701-800     | 12       | 11.54%  |
| 401-500     | 10       | 9.62%   |
| 601-700     | 8        | 7.69%   |
| 351-400     | 5        | 4.81%   |
| 801-900     | 3        | 2.88%   |
| 1001-1500   | 3        | 2.88%   |
| 301-350     | 2        | 1.92%   |
| 1501-2000   | 2        | 1.92%   |
| Unknown     | 2        | 1.92%   |
| 201-300     | 1        | 0.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 69       | 71.13%  |
| 21/9    | 11       | 11.34%  |
| 5/4     | 6        | 6.19%   |
| 16/10   | 6        | 6.19%   |
| 6/5     | 1        | 1.03%   |
| 32/9    | 1        | 1.03%   |
| 1.00    | 1        | 1.03%   |
| 0.89    | 1        | 1.03%   |
| Unknown | 1        | 1.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 30       | 28.04%  |
| 301-350        | 28       | 26.17%  |
| 351-500        | 18       | 16.82%  |
| 151-200        | 10       | 9.35%   |
| 251-300        | 8        | 7.48%   |
| More than 1000 | 4        | 3.74%   |
| 501-1000       | 4        | 3.74%   |
| 141-150        | 2        | 1.87%   |
| Unknown        | 2        | 1.87%   |
| 101-110        | 1        | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 54       | 53.47%  |
| 101-120 | 32       | 31.68%  |
| 161-240 | 7        | 6.93%   |
| 121-160 | 4        | 3.96%   |
| 1-50    | 2        | 1.98%   |
| Unknown | 2        | 1.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 65       | 60.19%  |
| 2     | 24       | 22.22%  |
| 0     | 14       | 12.96%  |
| 3     | 5        | 4.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 66       | 41.77%  |
| Realtek Semiconductor | 60       | 37.97%  |
| MediaTek              | 8        | 5.06%   |
| Aquantia              | 7        | 4.43%   |
| Qualcomm Atheros      | 3        | 1.9%    |
| Ralink Technology     | 2        | 1.27%   |
| Microsoft             | 2        | 1.27%   |
| D-Link System         | 2        | 1.27%   |
| TP-Link               | 1        | 0.63%   |
| Texas Instruments     | 1        | 0.63%   |
| Ralink                | 1        | 0.63%   |
| Oculus VR             | 1        | 0.63%   |
| Nvidia                | 1        | 0.63%   |
| Google                | 1        | 0.63%   |
| Broadcom              | 1        | 0.63%   |
| ASUSTek Computer      | 1        | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 39       | 21.2%   |
| Intel I211 Gigabit Network Connection                                          | 16       | 8.7%    |
| Realtek RTL8125 2.5GbE Controller                                              | 14       | 7.61%   |
| Intel Ethernet Controller I225-V                                               | 12       | 6.52%   |
| Intel Wi-Fi 6 AX200                                                            | 11       | 5.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6        | 3.26%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 5        | 2.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 4        | 2.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 4        | 2.17%   |
| Intel Ethernet Connection (7) I219-V                                           | 4        | 2.17%   |
| Intel Ethernet Connection (2) I219-V                                           | 4        | 2.17%   |
| Intel Ethernet Connection I217-V                                               | 3        | 1.63%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 3        | 1.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3        | 1.63%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2        | 1.09%   |
| Intel Ethernet Connection I217-LM                                              | 2        | 1.09%   |
| Intel Ethernet Connection (2) I218-V                                           | 2        | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2        | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2        | 1.09%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 1.09%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 1        | 0.54%   |
| Texas Instruments CC2538 USB CDC                                               | 1        | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.54%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1        | 0.54%   |
| Realtek 802.11ac NIC                                                           | 1        | 0.54%   |
| Ralink RT5572 Wireless Adapter                                                 | 1        | 0.54%   |
| Ralink RT5370 Wireless Adapter                                                 | 1        | 0.54%   |
| Ralink RT2800 802.11n PCI                                                      | 1        | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1        | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 1        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1        | 0.54%   |
| Oculus VR Rift S                                                               | 1        | 0.54%   |
| Nvidia MCP55 Ethernet                                                          | 1        | 0.54%   |
| Microsoft Xbox Wireless Adapter for Windows                                    | 1        | 0.54%   |
| Microsoft Xbox 360 Wireless Adapter                                            | 1        | 0.54%   |
| Intel Wireless 8260                                                            | 1        | 0.54%   |
| Intel Wireless 7265                                                            | 1        | 0.54%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 1        | 0.54%   |
| Intel Raptor Lake PCH CNVi WiFi                                                | 1        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 29       | 58%     |
| MediaTek              | 8        | 16%     |
| Realtek Semiconductor | 4        | 8%      |
| Ralink Technology     | 2        | 4%      |
| Microsoft             | 2        | 4%      |
| TP-Link               | 1        | 2%      |
| Ralink                | 1        | 2%      |
| Qualcomm Atheros      | 1        | 2%      |
| D-Link System         | 1        | 2%      |
| ASUSTek Computer      | 1        | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                               | 11       | 22%     |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]         | 5        | 10%     |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4        | 8%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4        | 8%      |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3        | 6%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 4%      |
| Intel Comet Lake PCH CNVi WiFi                                    | 2        | 4%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 2%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 2%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 2%      |
| Realtek 802.11ac NIC                                              | 1        | 2%      |
| Ralink RT5572 Wireless Adapter                                    | 1        | 2%      |
| Ralink RT5370 Wireless Adapter                                    | 1        | 2%      |
| Ralink RT2800 802.11n PCI                                         | 1        | 2%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 2%      |
| Microsoft Xbox Wireless Adapter for Windows                       | 1        | 2%      |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 2%      |
| Intel Wireless 8260                                               | 1        | 2%      |
| Intel Wireless 7265                                               | 1        | 2%      |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]           | 1        | 2%      |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1        | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1        | 2%      |
| Intel CNVi: Wi-Fi                                                 | 1        | 2%      |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W] | 1        | 2%      |
| ASUS USB-N53 802.11abgn Network Adapter [Ralink RT3572]           | 1        | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 59       | 45.74%  |
| Intel                 | 57       | 44.19%  |
| Aquantia              | 7        | 5.43%   |
| Qualcomm Atheros      | 2        | 1.55%   |
| Nvidia                | 1        | 0.78%   |
| Google                | 1        | 0.78%   |
| D-Link System         | 1        | 0.78%   |
| Broadcom              | 1        | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller            | 39       | 29.55%  |
| Intel I211 Gigabit Network Connection                                             | 16       | 12.12%  |
| Realtek RTL8125 2.5GbE Controller                                                 | 14       | 10.61%  |
| Intel Ethernet Controller I225-V                                                  | 12       | 9.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                          | 6        | 4.55%   |
| Intel Ethernet Connection (7) I219-V                                              | 4        | 3.03%   |
| Intel Ethernet Connection (2) I219-V                                              | 4        | 3.03%   |
| Intel Ethernet Connection I217-V                                                  | 3        | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 3        | 2.27%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                 | 2        | 1.52%   |
| Intel Ethernet Connection I217-LM                                                 | 2        | 1.52%   |
| Intel Ethernet Connection (2) I218-V                                              | 2        | 1.52%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]    | 2        | 1.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                         | 1        | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                          | 1        | 0.76%   |
| Nvidia MCP55 Ethernet                                                             | 1        | 0.76%   |
| Intel Ethernet Controller I226-LM                                                 | 1        | 0.76%   |
| Intel Ethernet Controller I225-LM                                                 | 1        | 0.76%   |
| Intel Ethernet Connection (7) I219-LM                                             | 1        | 0.76%   |
| Intel Ethernet Connection (6) I219-V                                              | 1        | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                                             | 1        | 0.76%   |
| Intel Ethernet Connection (17) I219-V                                             | 1        | 0.76%   |
| Intel Ethernet Connection (14) I219-V                                             | 1        | 0.76%   |
| Intel Ethernet Connection (14) I219-LM                                            | 1        | 0.76%   |
| Intel Ethernet Connection (11) I219-V                                             | 1        | 0.76%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                              | 1        | 0.76%   |
| Intel 82579V Gigabit Network Connection                                           | 1        | 0.76%   |
| Intel 82576 Gigabit Network Connection                                            | 1        | 0.76%   |
| Google Nexus/Pixel Device (tether)                                                | 1        | 0.76%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                   | 1        | 0.76%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                                | 1        | 0.76%   |
| Aquantia AQtion AQC113 NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G]     | 1        | 0.76%   |
| Aquantia AQtion AQC100 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]    | 1        | 0.76%   |
| Aquantia AQC113C NBase-T/IEEE 802.3an Ethernet Controller [Marvell Scalable mGig] | 1        | 0.76%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                 | 1        | 0.76%   |
| Aquantia 5G USB Ethernet Adapter                                                  | 1        | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 107      | 68.15%  |
| WiFi     | 48       | 30.57%  |
| Modem    | 2        | 1.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 91       | 81.98%  |
| WiFi     | 20       | 18.02%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 54       | 49.54%  |
| 2     | 44       | 40.37%  |
| 3     | 9        | 8.26%   |
| 4     | 1        | 0.92%   |
| 0     | 1        | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 71       | 65.74%  |
| Yes  | 37       | 34.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 24       | 41.38%  |
| Cambridge Silicon Radio  | 10       | 17.24%  |
| ASUSTek Computer         | 6        | 10.34%  |
| Realtek Semiconductor    | 5        | 8.62%   |
| MediaTek                 | 4        | 6.9%    |
| Broadcom                 | 4        | 6.9%    |
| Foxconn / Hon Hai        | 2        | 3.45%   |
| IMC Networks             | 1        | 1.72%   |
| HTC (High Tech Computer) | 1        | 1.72%   |
| Belkin Components        | 1        | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 10       | 17.24%  |
| Intel AX200 Bluetooth                                                | 9        | 15.52%  |
| Intel AX201 Bluetooth                                                | 5        | 8.62%   |
| Realtek Bluetooth Radio                                              | 4        | 6.9%    |
| MediaTek Wireless_Device                                             | 4        | 6.9%    |
| Intel AX210 Bluetooth                                                | 4        | 6.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 4        | 6.9%    |
| ASUS ASUS USB-BT500                                                  | 3        | 5.17%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 2        | 3.45%   |
| Intel Bluetooth Device                                               | 2        | 3.45%   |
| Foxconn / Hon Hai Wireless_Device                                    | 2        | 3.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2        | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 1.72%   |
| Intel Bluetooth wireless interface                                   | 1        | 1.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 1.72%   |
| IMC Networks Wireless_Device                                         | 1        | 1.72%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 1.72%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 1.72%   |
| ASUS Bluetooth Device                                                | 1        | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 69       | 29.87%  |
| Intel                                | 49       | 21.21%  |
| Nvidia                               | 45       | 19.48%  |
| C-Media Electronics                  | 7        | 3.03%   |
| RODE Microphones                     | 6        | 2.6%    |
| Razer USA                            | 5        | 2.16%   |
| Texas Instruments                    | 4        | 1.73%   |
| Focusrite-Novation                   | 4        | 1.73%   |
| ASUSTek Computer                     | 4        | 1.73%   |
| Schiit Audio                         | 3        | 1.3%    |
| Kingston Technology                  | 3        | 1.3%    |
| Blue Microphones                     | 3        | 1.3%    |
| Sennheiser Communications            | 2        | 0.87%   |
| Logitech                             | 2        | 0.87%   |
| Yamaha                               | 1        | 0.43%   |
| Valve Software                       | 1        | 0.43%   |
| Thomann                              | 1        | 0.43%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.43%   |
| SteelSeries ApS                      | 1        | 0.43%   |
| Sony                                 | 1        | 0.43%   |
| Shure                                | 1        | 0.43%   |
| Samson Technologies                  | 1        | 0.43%   |
| PreSonus Audio Electronics           | 1        | 0.43%   |
| Mark of the Unicorn                  | 1        | 0.43%   |
| Huawei Technologies                  | 1        | 0.43%   |
| Hewlett-Packard                      | 1        | 0.43%   |
| GYROCOM C&C                          | 1        | 0.43%   |
| Giga-Byte Technology                 | 1        | 0.43%   |
| Elgato Systems                       | 1        | 0.43%   |
| Edifier Technology                   | 1        | 0.43%   |
| Dell                                 | 1        | 0.43%   |
| Creative Technology                  | 1        | 0.43%   |
| Creative Labs                        | 1        | 0.43%   |
| Corsair                              | 1        | 0.43%   |
| Conexant Systems                     | 1        | 0.43%   |
| AudioQuest                           | 1        | 0.43%   |
| ASRock                               | 1        | 0.43%   |
| Apogee Electronics                   | 1        | 0.43%   |
| Antlion Audio                        | 1        | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 29       | 10.51%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 13       | 4.71%   |
| AMD Family 17h/19h HD Audio Controller                                     | 12       | 4.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10       | 3.62%   |
| AMD Navi 10 HDMI Audio                                                     | 9        | 3.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 2.54%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 7        | 2.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 2.17%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 6        | 2.17%   |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 1.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 1.81%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5        | 1.81%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.45%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 1.45%   |
| Nvidia GK104 HDMI Audio Controller                                         | 4        | 1.45%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 1.45%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4        | 1.45%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 1.45%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 1.45%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3        | 1.09%   |
| Schiit Audio Schiit Modi 3+                                                | 3        | 1.09%   |
| RODE Microphones RODE NT-USB Mini                                          | 3        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.09%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.09%   |
| Focusrite-Novation Scarlett 2i2 3rd Gen                                    | 3        | 1.09%   |
| ASUSTek Computer USB Audio                                                 | 3        | 1.09%   |
| RODE Microphones RODE NT-USB                                               | 2        | 0.72%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.72%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 0.72%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.72%   |
| Kingston Technology HyperX 7.1 Audio                                       | 2        | 0.72%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 0.72%   |
| Intel Raptor Lake High Definition Audio Controller                         | 2        | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 0.72%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 35       | 29.66%  |
| Kingston            | 21       | 17.8%   |
| G.Skill             | 20       | 16.95%  |
| Samsung Electronics | 9        | 7.63%   |
| Crucial             | 8        | 6.78%   |
| Unknown             | 7        | 5.93%   |
| SK hynix            | 3        | 2.54%   |
| Micron Technology   | 3        | 2.54%   |
| A-DATA Technology   | 3        | 2.54%   |
| Team                | 2        | 1.69%   |
| Unknown (ABCD)      | 1        | 0.85%   |
| Transcend           | 1        | 0.85%   |
| Strontium           | 1        | 0.85%   |
| Patriot             | 1        | 0.85%   |
| Goodram             | 1        | 0.85%   |
| GLOWAY              | 1        | 0.85%   |
| AMD                 | 1        | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s         | 4        | 3.08%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 3        | 2.31%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 3        | 2.31%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s         | 3        | 2.31%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 2        | 1.54%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 2        | 1.54%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 2        | 1.54%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s            | 2        | 1.54%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 2        | 1.54%   |
| Corsair RAM Module 16GB DIMM DDR4 2133MT/s                     | 2        | 1.54%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s         | 2        | 1.54%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 2        | 1.54%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.77%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 1        | 0.77%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 0.77%   |
| Unknown RAM Module 2GB DIMM DRAM 800MT/s                       | 1        | 0.77%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                       | 1        | 0.77%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                  | 1        | 0.77%   |
| Unknown RAM 3733 C17 Series 8192MB DIMM DDR4 2133MT/s          | 1        | 0.77%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.77%   |
| Transcend RAM JM4800ALE-16G 16GB DIMM DDR5 4800MT/s            | 1        | 0.77%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s            | 1        | 0.77%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s             | 1        | 0.77%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3200MT/s            | 1        | 0.77%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s             | 1        | 0.77%   |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                     | 1        | 0.77%   |
| SK hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s        | 1        | 0.77%   |
| SK hynix RAM HMAA2GU6CJR8N-XN 16GB DIMM DDR4 3200MT/s          | 1        | 0.77%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                      | 1        | 0.77%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR5 6400MT/s            | 1        | 0.77%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                 | 1        | 0.77%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1        | 0.77%   |
| Samsung RAM M393A4K40BB0-CPB 32GB RIMM DDR4 2133MT/s           | 1        | 0.77%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3600MT/s           | 1        | 0.77%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s            | 1        | 0.77%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 1        | 0.77%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 1        | 0.77%   |
| Patriot RAM 3400 C16 Series 8GB DIMM DDR4 3200MT/s             | 1        | 0.77%   |
| Micron RAM 4ATF1G64AZ-3G2E1 8GB DIMM DDR4 3200MT/s             | 1        | 0.77%   |
| Micron RAM 36ASF4G72PZ-2G1A1 32GB RIMM DDR4 2133MT/s           | 1        | 0.77%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 71       | 67.62%  |
| DDR3    | 17       | 16.19%  |
| DDR5    | 12       | 11.43%  |
| LPDDR5  | 1        | 0.95%   |
| LPDDR4  | 1        | 0.95%   |
| DRAM    | 1        | 0.95%   |
| DDR     | 1        | 0.95%   |
| Unknown | 1        | 0.95%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 98       | 93.33%  |
| SODIMM       | 5        | 4.76%   |
| Row Of Chips | 1        | 0.95%   |
| RIMM         | 1        | 0.95%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 42       | 35.59%  |
| 16384 | 39       | 33.05%  |
| 32768 | 22       | 18.64%  |
| 4096  | 12       | 10.17%  |
| 2048  | 2        | 1.69%   |
| 65536 | 1        | 0.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 23       | 19.17%  |
| 3600  | 13       | 10.83%  |
| 1600  | 11       | 9.17%   |
| 2133  | 8        | 6.67%   |
| 3733  | 7        | 5.83%   |
| 2400  | 6        | 5%      |
| 3000  | 5        | 4.17%   |
| 2667  | 5        | 4.17%   |
| 1333  | 5        | 4.17%   |
| 6000  | 4        | 3.33%   |
| 5200  | 3        | 2.5%    |
| 4800  | 3        | 2.5%    |
| 3533  | 3        | 2.5%    |
| 3866  | 2        | 1.67%   |
| 3800  | 2        | 1.67%   |
| 3534  | 2        | 1.67%   |
| 3334  | 2        | 1.67%   |
| 2933  | 2        | 1.67%   |
| 1867  | 2        | 1.67%   |
| 6400  | 1        | 0.83%   |
| 5600  | 1        | 0.83%   |
| 4000  | 1        | 0.83%   |
| 3666  | 1        | 0.83%   |
| 3400  | 1        | 0.83%   |
| 2800  | 1        | 0.83%   |
| 2666  | 1        | 0.83%   |
| 2134  | 1        | 0.83%   |
| 2132  | 1        | 0.83%   |
| 1866  | 1        | 0.83%   |
| 1800  | 1        | 0.83%   |
| 800   | 1        | 0.83%   |

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
| Logitech                      | 22       | 66.67%  |
| MacroSilicon                  | 4        | 12.12%  |
| Microdia                      | 2        | 6.06%   |
| webcamvendor                  | 1        | 3.03%   |
| Valve Software                | 1        | 3.03%   |
| Sunplus Innovation Technology | 1        | 3.03%   |
| Razer USA                     | 1        | 3.03%   |
| Apple                         | 1        | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| MacroSilicon USB3. 0 capture       | 4        | 12.12%  |
| Logitech Webcam C270               | 4        | 12.12%  |
| Logitech StreamCam                 | 4        | 12.12%  |
| Logitech Webcam C930e              | 2        | 6.06%   |
| Logitech HD Pro Webcam C920        | 2        | 6.06%   |
| Logitech C922 Pro Stream Webcam    | 2        | 6.06%   |
| webcamvendor webcamproduct         | 1        | 3.03%   |
| Valve Software 3D Camera           | 1        | 3.03%   |
| Sunplus FHD Camera Microphone      | 1        | 3.03%   |
| Razer USA Razer Kiyo Pro           | 1        | 3.03%   |
| Microdia USB Camera                | 1        | 3.03%   |
| Microdia Camera                    | 1        | 3.03%   |
| Logitech Webcam Pro 9000           | 1        | 3.03%   |
| Logitech Webcam C925e              | 1        | 3.03%   |
| Logitech Webcam C120               | 1        | 3.03%   |
| Logitech HD Webcam C615            | 1        | 3.03%   |
| Logitech HD Webcam C525            | 1        | 3.03%   |
| Logitech C930c                     | 1        | 3.03%   |
| Logitech C920 PRO HD Webcam        | 1        | 3.03%   |
| Logitech BRIO 4K Stream Edition    | 1        | 3.03%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR | 1        | 3.03%   |

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


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 50%     |
| OmniKey          | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 50%     |
| OmniKey CardMan Smart@Link                             | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 84       | 76.36%  |
| 1     | 21       | 19.09%  |
| 2     | 5        | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 10       | 35.71%  |
| Net/wireless          | 5        | 17.86%  |
| Unassigned class      | 3        | 10.71%  |
| Multimedia controller | 3        | 10.71%  |
| Chipcard              | 2        | 7.14%   |
| Bluetooth             | 2        | 7.14%   |
| Net/ethernet          | 1        | 3.57%   |
| Dvb card              | 1        | 3.57%   |
| Camera                | 1        | 3.57%   |

