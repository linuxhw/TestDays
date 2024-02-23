LMDE 5 - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for LMDE 5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 297

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Sapphire      | PI-AM3RS760G2               | [ec094665df](https://linux-hardware.org/?probe=ec094665df) | Jan 09, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [e15da7350e](https://linux-hardware.org/?probe=e15da7350e) | Jan 07, 2024 |
| Sapphire      | PI-AM3RS760G2               | [b98b78a3df](https://linux-hardware.org/?probe=b98b78a3df) | Jan 05, 2024 |
| Sapphire      | PI-AM3RS760G2               | [243e9d1b27](https://linux-hardware.org/?probe=243e9d1b27) | Jan 02, 2024 |
| Intel         | B75                         | [df9a51de80](https://linux-hardware.org/?probe=df9a51de80) | Dec 30, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9362181823](https://linux-hardware.org/?probe=9362181823) | Dec 14, 2023 |
| Sapphire      | PI-AM3RS760G2               | [e2c79fa4d1](https://linux-hardware.org/?probe=e2c79fa4d1) | Dec 13, 2023 |
| Pegatron      | 2ACF                        | [d89c55cb89](https://linux-hardware.org/?probe=d89c55cb89) | Nov 24, 2023 |
| Acer          | Aspire TC-780               | [dbce2ba706](https://linux-hardware.org/?probe=dbce2ba706) | Nov 23, 2023 |
| Pegatron      | 2ADC                        | [683e6fe69e](https://linux-hardware.org/?probe=683e6fe69e) | Nov 20, 2023 |
| Pegatron      | 2ADC                        | [ff6ee5f1e5](https://linux-hardware.org/?probe=ff6ee5f1e5) | Nov 20, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [4f2229b9fa](https://linux-hardware.org/?probe=4f2229b9fa) | Oct 21, 2023 |
| Medion        | TJ4125                      | [626065ec1b](https://linux-hardware.org/?probe=626065ec1b) | Oct 03, 2023 |
| Gigabyte      | Q87M-D2H                    | [ee49b13b77](https://linux-hardware.org/?probe=ee49b13b77) | Oct 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [bc2e88dd9c](https://linux-hardware.org/?probe=bc2e88dd9c) | Sep 30, 2023 |
| Gigabyte      | Q87M-D2H                    | [1d749b29ad](https://linux-hardware.org/?probe=1d749b29ad) | Sep 28, 2023 |
| Gigabyte      | Q87M-D2H                    | [8bdc8129ff](https://linux-hardware.org/?probe=8bdc8129ff) | Sep 25, 2023 |
| Gigabyte      | Q87M-D2H                    | [87cba2e3a2](https://linux-hardware.org/?probe=87cba2e3a2) | Sep 24, 2023 |
| Medion        | TJ4125                      | [434dd057a6](https://linux-hardware.org/?probe=434dd057a6) | Sep 23, 2023 |
| ASUSTek       | P8H61-M LX                  | [48a5b6b71d](https://linux-hardware.org/?probe=48a5b6b71d) | Sep 23, 2023 |
| HP            | 859C                        | [7de1553287](https://linux-hardware.org/?probe=7de1553287) | Sep 20, 2023 |
| Intel         | DG31PR AAD97573-206         | [da930461ec](https://linux-hardware.org/?probe=da930461ec) | Sep 18, 2023 |
| Intel         | X79                         | [e9a4f4dc51](https://linux-hardware.org/?probe=e9a4f4dc51) | Sep 13, 2023 |
| ASRock        | H110M-DVS R3.0              | [b0305f4ba4](https://linux-hardware.org/?probe=b0305f4ba4) | Sep 10, 2023 |
| Medion        | TJ4125                      | [80a4e5fbff](https://linux-hardware.org/?probe=80a4e5fbff) | Sep 09, 2023 |
| HP            | 859C                        | [c113eb162e](https://linux-hardware.org/?probe=c113eb162e) | Sep 09, 2023 |
| Gigabyte      | Q87M-D2H                    | [3389baa197](https://linux-hardware.org/?probe=3389baa197) | Sep 07, 2023 |
| Gigabyte      | Q87M-D2H                    | [f73f6d9301](https://linux-hardware.org/?probe=f73f6d9301) | Sep 05, 2023 |
| Gigabyte      | Q87M-D2H                    | [61c5e35c02](https://linux-hardware.org/?probe=61c5e35c02) | Sep 05, 2023 |
| Gigabyte      | Q87M-D2H                    | [f5e7afad66](https://linux-hardware.org/?probe=f5e7afad66) | Sep 04, 2023 |
| Medion        | TJ4125                      | [e2e111051c](https://linux-hardware.org/?probe=e2e111051c) | Sep 03, 2023 |
| ASUSTek       | G10DK                       | [d6b74ca876](https://linux-hardware.org/?probe=d6b74ca876) | Sep 03, 2023 |
| Gigabyte      | B450 AORUS M                | [e58d4f8405](https://linux-hardware.org/?probe=e58d4f8405) | Sep 03, 2023 |
| MSI           | B560M PRO-E                 | [17eed28ecb](https://linux-hardware.org/?probe=17eed28ecb) | Sep 02, 2023 |
| Acer          | Aspire X3400                | [62a78b2a16](https://linux-hardware.org/?probe=62a78b2a16) | Sep 01, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [f7a484830d](https://linux-hardware.org/?probe=f7a484830d) | Aug 30, 2023 |
| Dell          | 0D28YY A00                  | [9f2585c0aa](https://linux-hardware.org/?probe=9f2585c0aa) | Aug 29, 2023 |
| HP            | 859C                        | [978d715b29](https://linux-hardware.org/?probe=978d715b29) | Aug 25, 2023 |
| eMachines     | EL1852G                     | [68db025f09](https://linux-hardware.org/?probe=68db025f09) | Aug 25, 2023 |
| Pegatron      | 2ACF                        | [38f3df41d7](https://linux-hardware.org/?probe=38f3df41d7) | Aug 24, 2023 |
| eMachines     | EL1852G                     | [ea782989fd](https://linux-hardware.org/?probe=ea782989fd) | Aug 24, 2023 |
| HP            | 859C                        | [63f9e00825](https://linux-hardware.org/?probe=63f9e00825) | Aug 22, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [cce6cb2878](https://linux-hardware.org/?probe=cce6cb2878) | Aug 18, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [8803256d2e](https://linux-hardware.org/?probe=8803256d2e) | Aug 14, 2023 |
| Medion        | TJ4125                      | [e24dc34df5](https://linux-hardware.org/?probe=e24dc34df5) | Aug 13, 2023 |
| Gigabyte      | Q87M-D2H                    | [6289a9e628](https://linux-hardware.org/?probe=6289a9e628) | Aug 12, 2023 |
| HP            | 859C                        | [24dd090f2c](https://linux-hardware.org/?probe=24dd090f2c) | Aug 09, 2023 |
| ASRock        | B550M-ITX/ac                | [c86495f999](https://linux-hardware.org/?probe=c86495f999) | Aug 08, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7fe1ce642a](https://linux-hardware.org/?probe=7fe1ce642a) | Aug 08, 2023 |
| Gigabyte      | Q87M-D2H                    | [dbcb2c4a80](https://linux-hardware.org/?probe=dbcb2c4a80) | Aug 07, 2023 |
| Medion        | TJ4125                      | [e35dc275ce](https://linux-hardware.org/?probe=e35dc275ce) | Aug 06, 2023 |
| Medion        | TJ4125                      | [0adec5cb7e](https://linux-hardware.org/?probe=0adec5cb7e) | Aug 04, 2023 |
| Gigabyte      | Q87M-D2H                    | [d3df0e8ee1](https://linux-hardware.org/?probe=d3df0e8ee1) | Aug 04, 2023 |
| Gigabyte      | Q87M-D2H                    | [37725aaff8](https://linux-hardware.org/?probe=37725aaff8) | Aug 03, 2023 |
| Intel         | X79                         | [051316466a](https://linux-hardware.org/?probe=051316466a) | Aug 01, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [1bcc28bd33](https://linux-hardware.org/?probe=1bcc28bd33) | Jul 29, 2023 |
| Apple         | Mac-F221BEC8                | [12932af713](https://linux-hardware.org/?probe=12932af713) | Jul 29, 2023 |
| Medion        | TJ4125                      | [0882778c0a](https://linux-hardware.org/?probe=0882778c0a) | Jul 28, 2023 |
| Gigabyte      | Q87M-D2H                    | [374c405364](https://linux-hardware.org/?probe=374c405364) | Jul 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [199fe99179](https://linux-hardware.org/?probe=199fe99179) | Jul 25, 2023 |
| Gigabyte      | Q87M-D2H                    | [7aaa099507](https://linux-hardware.org/?probe=7aaa099507) | Jul 24, 2023 |
| Intel         | X79                         | [8037a9fc0e](https://linux-hardware.org/?probe=8037a9fc0e) | Jul 24, 2023 |
| Dell          | 00F82W A02                  | [53b13b667d](https://linux-hardware.org/?probe=53b13b667d) | Jul 16, 2023 |
| Dell          | 00F82W A02                  | [293fa24c88](https://linux-hardware.org/?probe=293fa24c88) | Jul 14, 2023 |
| Medion        | TJ4125                      | [88fb5ecc29](https://linux-hardware.org/?probe=88fb5ecc29) | Jul 09, 2023 |
| Medion        | TJ4125                      | [efa563ec1f](https://linux-hardware.org/?probe=efa563ec1f) | Jul 09, 2023 |
| Gigabyte      | Q87M-D2H                    | [d660aa6f35](https://linux-hardware.org/?probe=d660aa6f35) | Jul 09, 2023 |
| Gigabyte      | Q87M-D2H                    | [87872596c0](https://linux-hardware.org/?probe=87872596c0) | Jul 08, 2023 |
| Medion        | TJ4125                      | [38d2ffe2de](https://linux-hardware.org/?probe=38d2ffe2de) | Jul 08, 2023 |
| Medion        | TJ4125                      | [1de78b3365](https://linux-hardware.org/?probe=1de78b3365) | Jul 07, 2023 |
| Gigabyte      | B450M DS3H V2               | [919f65a256](https://linux-hardware.org/?probe=919f65a256) | Jul 05, 2023 |
| Gigabyte      | Q87M-D2H                    | [22a3b2defb](https://linux-hardware.org/?probe=22a3b2defb) | Jul 05, 2023 |
| Medion        | TJ4125                      | [8d8748e1dc](https://linux-hardware.org/?probe=8d8748e1dc) | Jul 02, 2023 |
| Gigabyte      | Q87M-D2H                    | [89c111d3ec](https://linux-hardware.org/?probe=89c111d3ec) | Jul 02, 2023 |
| Medion        | TJ4125                      | [e99bd03d75](https://linux-hardware.org/?probe=e99bd03d75) | Jul 01, 2023 |
| Gigabyte      | Q87M-D2H                    | [729fb2873e](https://linux-hardware.org/?probe=729fb2873e) | Jul 01, 2023 |
| Gigabyte      | Q87M-D2H                    | [633c55d4ba](https://linux-hardware.org/?probe=633c55d4ba) | Jun 30, 2023 |
| Medion        | TJ4125                      | [5cebe0a1d0](https://linux-hardware.org/?probe=5cebe0a1d0) | Jun 30, 2023 |
| Medion        | TJ4125                      | [327794cb1a](https://linux-hardware.org/?probe=327794cb1a) | Jun 30, 2023 |
| Gigabyte      | Q87M-D2H                    | [95e5472f48](https://linux-hardware.org/?probe=95e5472f48) | Jun 27, 2023 |
| Gigabyte      | Q87M-D2H                    | [67a44b0d84](https://linux-hardware.org/?probe=67a44b0d84) | Jun 20, 2023 |
| Intel         | X79                         | [8c50d3b5e8](https://linux-hardware.org/?probe=8c50d3b5e8) | Jun 20, 2023 |
| ASRock        | B450 Gaming K4              | [2344c78f90](https://linux-hardware.org/?probe=2344c78f90) | Jun 20, 2023 |
| Lenovo        | SHARKBAY NOK                | [0173559ed0](https://linux-hardware.org/?probe=0173559ed0) | Jun 19, 2023 |
| Medion        | TJ4125                      | [4c6aec7e33](https://linux-hardware.org/?probe=4c6aec7e33) | Jun 18, 2023 |
| Medion        | TJ4125                      | [fc102c077c](https://linux-hardware.org/?probe=fc102c077c) | Jun 16, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [64da6bc381](https://linux-hardware.org/?probe=64da6bc381) | Jun 14, 2023 |
| Gigabyte      | Q87M-D2H                    | [59b855f1a1](https://linux-hardware.org/?probe=59b855f1a1) | Jun 12, 2023 |
| Gigabyte      | Q87M-D2H                    | [56421d7b0f](https://linux-hardware.org/?probe=56421d7b0f) | Jun 09, 2023 |
| AZW           | GK mini                     | [d9d37cb11a](https://linux-hardware.org/?probe=d9d37cb11a) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [a8724dfd68](https://linux-hardware.org/?probe=a8724dfd68) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | [ac442da472](https://linux-hardware.org/?probe=ac442da472) | Jun 08, 2023 |
| Gigabyte      | Q87M-D2H                    | [05a3b3210a](https://linux-hardware.org/?probe=05a3b3210a) | Jun 06, 2023 |
| Gigabyte      | Q87M-D2H                    | [eeaf6dbd4c](https://linux-hardware.org/?probe=eeaf6dbd4c) | Jun 05, 2023 |
| Gigabyte      | F2A55M-DS2                  | [74b01a9071](https://linux-hardware.org/?probe=74b01a9071) | Jun 05, 2023 |
| Medion        | TJ4125                      | [3faed0102f](https://linux-hardware.org/?probe=3faed0102f) | Jun 04, 2023 |
| Gigabyte      | A520M S2H                   | [81caf6e8cf](https://linux-hardware.org/?probe=81caf6e8cf) | Jun 04, 2023 |
| Gigabyte      | A520M S2H                   | [0169222312](https://linux-hardware.org/?probe=0169222312) | Jun 03, 2023 |
| Intel         | B75                         | [2387f30645](https://linux-hardware.org/?probe=2387f30645) | Jun 03, 2023 |
| Medion        | TJ4125                      | [6244ae0e43](https://linux-hardware.org/?probe=6244ae0e43) | Jun 02, 2023 |
| Unknown       | X99                         | [0ffca5934a](https://linux-hardware.org/?probe=0ffca5934a) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | [8ededa47e6](https://linux-hardware.org/?probe=8ededa47e6) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | [7bd893ebe1](https://linux-hardware.org/?probe=7bd893ebe1) | Jun 02, 2023 |
| Gigabyte      | Q87M-D2H                    | [8f3525a119](https://linux-hardware.org/?probe=8f3525a119) | Jun 01, 2023 |
| Gigabyte      | Q87M-D2H                    | [7400ec0f1a](https://linux-hardware.org/?probe=7400ec0f1a) | May 31, 2023 |
| Gigabyte      | Q87M-D2H                    | [5e7eb5b41c](https://linux-hardware.org/?probe=5e7eb5b41c) | May 29, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bf6e9cf4d0](https://linux-hardware.org/?probe=bf6e9cf4d0) | May 26, 2023 |
| Gigabyte      | Q87M-D2H                    | [a3e5c89fe6](https://linux-hardware.org/?probe=a3e5c89fe6) | May 25, 2023 |
| Gigabyte      | Q87M-D2H                    | [3c82eec4d2](https://linux-hardware.org/?probe=3c82eec4d2) | May 23, 2023 |
| Gigabyte      | Q87M-D2H                    | [ee4eca623f](https://linux-hardware.org/?probe=ee4eca623f) | May 21, 2023 |
| MSI           | B350M BAZOOKA               | [49e536226c](https://linux-hardware.org/?probe=49e536226c) | May 19, 2023 |
| MSI           | B350M BAZOOKA               | [2abefd21ea](https://linux-hardware.org/?probe=2abefd21ea) | May 19, 2023 |
| Alienware     | 04VWF2 A00                  | [311799f80a](https://linux-hardware.org/?probe=311799f80a) | May 18, 2023 |
| Packard Be... | PT890-8237A                 | [b15e7cc105](https://linux-hardware.org/?probe=b15e7cc105) | May 18, 2023 |
| Gigabyte      | E2100N                      | [cce0e87f11](https://linux-hardware.org/?probe=cce0e87f11) | May 17, 2023 |
| Gigabyte      | Q87M-D2H                    | [98f104037a](https://linux-hardware.org/?probe=98f104037a) | May 15, 2023 |
| AZW           | MINI S                      | [72c9908514](https://linux-hardware.org/?probe=72c9908514) | May 14, 2023 |
| AZW           | MINI S                      | [788d932e58](https://linux-hardware.org/?probe=788d932e58) | May 14, 2023 |
| Gigabyte      | Q87M-D2H                    | [42db835c47](https://linux-hardware.org/?probe=42db835c47) | May 14, 2023 |
| Gigabyte      | Q87M-D2H                    | [3f4eafaf9c](https://linux-hardware.org/?probe=3f4eafaf9c) | May 13, 2023 |
| Medion        | TJ4125                      | [a0fcafbf70](https://linux-hardware.org/?probe=a0fcafbf70) | May 12, 2023 |
| Medion        | TJ4125                      | [4d7467c0bc](https://linux-hardware.org/?probe=4d7467c0bc) | May 12, 2023 |
| Gigabyte      | Q87M-D2H                    | [99c9764b7e](https://linux-hardware.org/?probe=99c9764b7e) | May 12, 2023 |
| Gigabyte      | Q87M-D2H                    | [a70e02af94](https://linux-hardware.org/?probe=a70e02af94) | May 09, 2023 |
| ASRock        | 775Dual-VSTA                | [89ccdd7262](https://linux-hardware.org/?probe=89ccdd7262) | May 08, 2023 |
| Gigabyte      | Q87M-D2H                    | [7d861acbd6](https://linux-hardware.org/?probe=7d861acbd6) | May 07, 2023 |
| Medion        | TJ4125                      | [583b49089e](https://linux-hardware.org/?probe=583b49089e) | May 07, 2023 |
| Medion        | TJ4125                      | [2255946fa5](https://linux-hardware.org/?probe=2255946fa5) | May 05, 2023 |
| ASRock        | B450M Pro4                  | [3c7546e88a](https://linux-hardware.org/?probe=3c7546e88a) | May 02, 2023 |
| Gigabyte      | Q87M-D2H                    | [ae586408c4](https://linux-hardware.org/?probe=ae586408c4) | May 02, 2023 |
| ASUSTek       | P7Q57-M DO                  | [897fc61b8c](https://linux-hardware.org/?probe=897fc61b8c) | Apr 30, 2023 |
| ASUSTek       | P7Q57-M DO                  | [4f502dcb59](https://linux-hardware.org/?probe=4f502dcb59) | Apr 30, 2023 |
| Gigabyte      | Q87M-D2H                    | [16279b3c8b](https://linux-hardware.org/?probe=16279b3c8b) | Apr 30, 2023 |
| Medion        | TJ4125                      | [ad46974b2a](https://linux-hardware.org/?probe=ad46974b2a) | Apr 29, 2023 |
| ASRock        | B450M Pro4                  | [7c8260664a](https://linux-hardware.org/?probe=7c8260664a) | Apr 29, 2023 |
| Medion        | TJ4125                      | [8f319cff50](https://linux-hardware.org/?probe=8f319cff50) | Apr 28, 2023 |
| ASRock        | B450M Pro4                  | [831cd8fa39](https://linux-hardware.org/?probe=831cd8fa39) | Apr 28, 2023 |
| Gigabyte      | Q87M-D2H                    | [6503ed5a4c](https://linux-hardware.org/?probe=6503ed5a4c) | Apr 28, 2023 |
| Gigabyte      | Q87M-D2H                    | [5827cd2604](https://linux-hardware.org/?probe=5827cd2604) | Apr 23, 2023 |
| Medion        | TJ4125                      | [faa241e4bc](https://linux-hardware.org/?probe=faa241e4bc) | Apr 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [93a6cb1a8a](https://linux-hardware.org/?probe=93a6cb1a8a) | Apr 22, 2023 |
| Gigabyte      | A520M DS3H                  | [c4b35f2a05](https://linux-hardware.org/?probe=c4b35f2a05) | Apr 16, 2023 |
| Intel         | SHARKBAY                    | [3bb10a5574](https://linux-hardware.org/?probe=3bb10a5574) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d6f8675bc9](https://linux-hardware.org/?probe=d6f8675bc9) | Apr 11, 2023 |
| Intel         | SHARKBAY                    | [4b50be64da](https://linux-hardware.org/?probe=4b50be64da) | Apr 11, 2023 |
| Gigabyte      | Q87M-D2H                    | [d041ee40cc](https://linux-hardware.org/?probe=d041ee40cc) | Apr 11, 2023 |
| Gigabyte      | Q87M-D2H                    | [2c83dbd3ef](https://linux-hardware.org/?probe=2c83dbd3ef) | Apr 08, 2023 |
| Dell          | 0KWVT8 A00                  | [d1e9eaed8b](https://linux-hardware.org/?probe=d1e9eaed8b) | Apr 08, 2023 |
| Dell          | 0KWVT8 A00                  | [82a96ca347](https://linux-hardware.org/?probe=82a96ca347) | Apr 08, 2023 |
| Gigabyte      | Q87M-D2H                    | [4552b7c999](https://linux-hardware.org/?probe=4552b7c999) | Apr 01, 2023 |
| Gigabyte      | Q87M-D2H                    | [b627db43dd](https://linux-hardware.org/?probe=b627db43dd) | Apr 01, 2023 |
| ASUSTek       | P7P55D                      | [b50f27ad05](https://linux-hardware.org/?probe=b50f27ad05) | Mar 31, 2023 |
| Dell          | 00F82W A02                  | [8bf22304e0](https://linux-hardware.org/?probe=8bf22304e0) | Mar 31, 2023 |
| ASUSTek       | P5GC-VM/SI                  | [b53d1202dc](https://linux-hardware.org/?probe=b53d1202dc) | Mar 28, 2023 |
| Gigabyte      | Q87M-D2H                    | [dd71be113d](https://linux-hardware.org/?probe=dd71be113d) | Mar 27, 2023 |
| ASUSTek       | P5GC-VM/SI                  | [e5cef530ff](https://linux-hardware.org/?probe=e5cef530ff) | Mar 27, 2023 |
| Gigabyte      | Q87M-D2H                    | [8690ae647e](https://linux-hardware.org/?probe=8690ae647e) | Mar 26, 2023 |
| BESSTAR Te... | TH50                        | [7165e2c0d0](https://linux-hardware.org/?probe=7165e2c0d0) | Mar 21, 2023 |
| Gigabyte      | A520M DS3H                  | [79104099a5](https://linux-hardware.org/?probe=79104099a5) | Mar 20, 2023 |
| Gigabyte      | Q87M-D2H                    | [fb5c67c585](https://linux-hardware.org/?probe=fb5c67c585) | Mar 19, 2023 |
| Gigabyte      | Q87M-D2H                    | [7051e25dc0](https://linux-hardware.org/?probe=7051e25dc0) | Mar 18, 2023 |
| ASRock        | B365M Pro4                  | [e237668eb2](https://linux-hardware.org/?probe=e237668eb2) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [29f50579db](https://linux-hardware.org/?probe=29f50579db) | Mar 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | [bf2b5490ba](https://linux-hardware.org/?probe=bf2b5490ba) | Mar 15, 2023 |
| Gigabyte      | Z87X-OC Force-CF            | [17deac9c67](https://linux-hardware.org/?probe=17deac9c67) | Mar 12, 2023 |
| SiYW          | V200 Series                 | [7c3751c888](https://linux-hardware.org/?probe=7c3751c888) | Mar 11, 2023 |
| ASUSTek       | PRIME A320M-K               | [93875c7518](https://linux-hardware.org/?probe=93875c7518) | Mar 09, 2023 |
| MSI           | 970A-G46                    | [8c3d20fa95](https://linux-hardware.org/?probe=8c3d20fa95) | Mar 08, 2023 |
| Dell          | 096JG8 A01                  | [fddb284e37](https://linux-hardware.org/?probe=fddb284e37) | Mar 03, 2023 |
| Gigabyte      | Z590 GAMING X               | [d39a85e759](https://linux-hardware.org/?probe=d39a85e759) | Feb 24, 2023 |
| Medion        | MS-7800                     | [2f542347f9](https://linux-hardware.org/?probe=2f542347f9) | Feb 19, 2023 |
| Dell          | 0NK70N A03                  | [3da6e11665](https://linux-hardware.org/?probe=3da6e11665) | Feb 18, 2023 |
| ASUSTek       | P7P55D                      | [bcae3260be](https://linux-hardware.org/?probe=bcae3260be) | Feb 17, 2023 |
| Foxconn       | 2ABF                        | [2c98a8340f](https://linux-hardware.org/?probe=2c98a8340f) | Feb 17, 2023 |
| Dell          | 0MF24N A03                  | [e48d83d96d](https://linux-hardware.org/?probe=e48d83d96d) | Feb 15, 2023 |
| Gigabyte      | B450M S2H                   | [20bcead0e8](https://linux-hardware.org/?probe=20bcead0e8) | Feb 11, 2023 |
| HP            | 843C                        | [02ddbb64e8](https://linux-hardware.org/?probe=02ddbb64e8) | Feb 09, 2023 |
| Gigabyte      | B450 AORUS M                | [e96f495083](https://linux-hardware.org/?probe=e96f495083) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [4df21dd9fa](https://linux-hardware.org/?probe=4df21dd9fa) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [e42e3a74b4](https://linux-hardware.org/?probe=e42e3a74b4) | Feb 05, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [1985f76677](https://linux-hardware.org/?probe=1985f76677) | Feb 05, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | [6c094e2027](https://linux-hardware.org/?probe=6c094e2027) | Jan 31, 2023 |
| ASUSTek       | P7P55D                      | [981ae95b2a](https://linux-hardware.org/?probe=981ae95b2a) | Jan 31, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [40152faf5b](https://linux-hardware.org/?probe=40152faf5b) | Jan 28, 2023 |
| Intel         | H61M-DS2V                   | [0591a32a07](https://linux-hardware.org/?probe=0591a32a07) | Jan 25, 2023 |
| ASRock        | Z87 Pro3                    | [0ab0dbb821](https://linux-hardware.org/?probe=0ab0dbb821) | Jan 23, 2023 |
| Dell          | 0C27VV A01                  | [e43d24d2b6](https://linux-hardware.org/?probe=e43d24d2b6) | Jan 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [76a4c34a41](https://linux-hardware.org/?probe=76a4c34a41) | Jan 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c5dd2e8482](https://linux-hardware.org/?probe=c5dd2e8482) | Jan 19, 2023 |
| Gigabyte      | H310M S2H                   | [9aec47cbf0](https://linux-hardware.org/?probe=9aec47cbf0) | Jan 12, 2023 |
| Gigabyte      | H310M S2H                   | [b3cccc4043](https://linux-hardware.org/?probe=b3cccc4043) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | [3a9bdd2358](https://linux-hardware.org/?probe=3a9bdd2358) | Jan 12, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [563d7aaba5](https://linux-hardware.org/?probe=563d7aaba5) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | [db0f184e3f](https://linux-hardware.org/?probe=db0f184e3f) | Jan 11, 2023 |
| Intel         | B75                         | [ec08587a4a](https://linux-hardware.org/?probe=ec08587a4a) | Jan 09, 2023 |
| MSI           | FM2-A55M-E33                | [1ce8a2718b](https://linux-hardware.org/?probe=1ce8a2718b) | Jan 07, 2023 |
| Acer          | Aspire XC-780               | [66823871a5](https://linux-hardware.org/?probe=66823871a5) | Jan 07, 2023 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [12c1c0d9a0](https://linux-hardware.org/?probe=12c1c0d9a0) | Jan 01, 2023 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | [cb55beafca](https://linux-hardware.org/?probe=cb55beafca) | Dec 30, 2022 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | [938db016a2](https://linux-hardware.org/?probe=938db016a2) | Dec 30, 2022 |
| ASUSTek       | Z170M-PLUS                  | [6b61c9a811](https://linux-hardware.org/?probe=6b61c9a811) | Dec 28, 2022 |
| Gigabyte      | GA-970A-D3                  | [82b0efdce8](https://linux-hardware.org/?probe=82b0efdce8) | Dec 25, 2022 |
| ASUSTek       | PRIME B350M-A               | [b03e4717c0](https://linux-hardware.org/?probe=b03e4717c0) | Dec 22, 2022 |
| Dell          | 0C27VV A01                  | [91c790d54e](https://linux-hardware.org/?probe=91c790d54e) | Dec 18, 2022 |
| MSI           | PRO B660M-A DDR4            | [770334f093](https://linux-hardware.org/?probe=770334f093) | Dec 16, 2022 |
| Dell          | 0T1D10 A01                  | [6988ab07fe](https://linux-hardware.org/?probe=6988ab07fe) | Dec 12, 2022 |
| Dell          | 0T1D10 A01                  | [6ec6d4563d](https://linux-hardware.org/?probe=6ec6d4563d) | Dec 12, 2022 |
| ASUSTek       | LEUCITE3                    | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [e810c5c2eb](https://linux-hardware.org/?probe=e810c5c2eb) | Dec 08, 2022 |
| ASUSTek       | P7P55D                      | [a1d27bfc48](https://linux-hardware.org/?probe=a1d27bfc48) | Dec 04, 2022 |
| SiYW          | V200 Series                 | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| HP            | 8299                        | [8f6b89bf07](https://linux-hardware.org/?probe=8f6b89bf07) | Nov 25, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [1ad4dcb28a](https://linux-hardware.org/?probe=1ad4dcb28a) | Nov 22, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [f2a00a7bb3](https://linux-hardware.org/?probe=f2a00a7bb3) | Nov 21, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [d93b2b9778](https://linux-hardware.org/?probe=d93b2b9778) | Nov 21, 2022 |
| MSI           | A320M-A PRO MAX             | [486c850cd6](https://linux-hardware.org/?probe=486c850cd6) | Nov 20, 2022 |
| Dell          | 0C27VV A01                  | [5e87654e7a](https://linux-hardware.org/?probe=5e87654e7a) | Nov 14, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [95f38cc8d9](https://linux-hardware.org/?probe=95f38cc8d9) | Nov 12, 2022 |
| Dell          | 0C27VV A01                  | [9e5c4960c3](https://linux-hardware.org/?probe=9e5c4960c3) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | [a8c3b285d0](https://linux-hardware.org/?probe=a8c3b285d0) | Nov 10, 2022 |
| Dell          | 0N826N A03                  | [2126bcff1e](https://linux-hardware.org/?probe=2126bcff1e) | Nov 06, 2022 |
| MSI           | A320M-A PRO MAX             | [774861eae7](https://linux-hardware.org/?probe=774861eae7) | Oct 21, 2022 |
| HP            | 8299                        | [2b4c3924e4](https://linux-hardware.org/?probe=2b4c3924e4) | Oct 20, 2022 |
| HP            | 8299                        | [bf86078a8f](https://linux-hardware.org/?probe=bf86078a8f) | Oct 18, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| Dell          | 0D735T A00                  | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| MSI           | B550-A PRO                  | [0526dffee9](https://linux-hardware.org/?probe=0526dffee9) | Oct 11, 2022 |
| AZW           | MINI S                      | [c5be5052a0](https://linux-hardware.org/?probe=c5be5052a0) | Oct 09, 2022 |
| ASUSTek       | Maximus VI HERO             | [2ee3173d51](https://linux-hardware.org/?probe=2ee3173d51) | Oct 08, 2022 |
| MSI           | B550-A PRO                  | [de85238b42](https://linux-hardware.org/?probe=de85238b42) | Oct 05, 2022 |
| ASRock        | A320M-HDV R4.0              | [b340ade9c9](https://linux-hardware.org/?probe=b340ade9c9) | Oct 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [bc6ad9af3e](https://linux-hardware.org/?probe=bc6ad9af3e) | Oct 03, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [f7f5368662](https://linux-hardware.org/?probe=f7f5368662) | Sep 28, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [fb983c65ac](https://linux-hardware.org/?probe=fb983c65ac) | Sep 28, 2022 |
| Dell          | 082WXT A01                  | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell          | 082WXT A01                  | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Gateway       | DX4870                      | [fd5b76e786](https://linux-hardware.org/?probe=fd5b76e786) | Sep 22, 2022 |
| Digiboard     | NM70-TI                     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Dell          | 0XC837                      | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| MSI           | B360M MORTAR                | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| ASUSTek       | PRIME H610M-E D4            | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Dell          | 0FJ030                      | [bf789b5c5f](https://linux-hardware.org/?probe=bf789b5c5f) | Sep 10, 2022 |
| MSI           | B450I GAMING PLUS AC        | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| Pegatron      | 2A9Eh                       | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| ASUSTek       | P8H77-V                     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9842cac1de](https://linux-hardware.org/?probe=9842cac1de) | Sep 04, 2022 |
| eMachines     | EL1352G                     | [2547a277f7](https://linux-hardware.org/?probe=2547a277f7) | Sep 04, 2022 |
| ASUSTek       | P5K-E                       | [632cd1e47d](https://linux-hardware.org/?probe=632cd1e47d) | Sep 03, 2022 |
| Dell          | 042P49 A00                  | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | P5QPL-AM                    | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI           | Z170A GAMING PRO            | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| MSI           | B85I                        | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Gigabyte      | H97-Gaming 3                | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| ASRock        | H61M-DGS                    | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Gigabyte      | B450 AORUS M                | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| HP            | 8433 11                     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP            | 8433 11                     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Gigabyte      | B450 AORUS M                | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| ASUSTek       | P8H77-M PRO                 | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Dell          | 0XR1GT A00                  | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| Lenovo        | 3731 NOK                    | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo        | 3731 NOK                    | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| Dell          | 0XR1GT A00                  | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo        | MAHOBAY                     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| Acer          | Seawolf                     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| Intel         | DQ77MK AAG39642-400         | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| MSI           | 970A-G43 PLUS               | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP            | 158B                        | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| HP            | 339A                        | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Gigabyte      | H110M-S2H-CF                | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| ASUSTek       | PRIME H610M-A D4            | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| ASRock        | A320M-DGS                   | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| ASUSTek       | PRIME B350M-A               | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Acer          | WG43M                       | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| ASUSTek       | P6T                         | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| ASUSTek       | PRIME H510M-D               | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| HP            | 0AE8h C                     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.0-21-amd64          | 29       | 17.37%  |
| 5.10.0-12-amd64          | 21       | 12.57%  |
| 5.10.0-23-amd64          | 18       | 10.78%  |
| 5.10.0-25-amd64          | 16       | 9.58%   |
| 5.10.0-20-amd64          | 12       | 7.19%   |
| 5.10.0-17-amd64          | 11       | 6.59%   |
| 5.10.0-14-amd64          | 10       | 5.99%   |
| 5.10.0-13-amd64          | 10       | 5.99%   |
| 5.10.0-18-amd64          | 9        | 5.39%   |
| 5.10.0-19-amd64          | 8        | 4.79%   |
| 5.10.0-22-amd64          | 5        | 2.99%   |
| 6.1.0-0.deb11.7-amd64    | 4        | 2.4%    |
| 5.10.0-26-amd64          | 4        | 2.4%    |
| 5.10.0-15-amd64          | 3        | 1.8%    |
| 5.10.0-16-amd64          | 2        | 1.2%    |
| 6.1.0-13-amd64           | 1        | 0.6%    |
| 6.1.0-0.deb11.5-amd64    | 1        | 0.6%    |
| 6.0.2-x64v2-rt11-xanmod1 | 1        | 0.6%    |
| 5.19.0-0.deb11.2-amd64   | 1        | 0.6%    |
| 5.10.0-13-686            | 1        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 138      | 94.52%  |
| 6.1.0   | 6        | 4.11%   |
| 6.0.2   | 1        | 0.68%   |
| 5.19.0  | 1        | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 138      | 94.52%  |
| 6.1     | 6        | 4.11%   |
| 6.0     | 1        | 0.68%   |
| 5.19    | 1        | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 144      | 99.31%  |
| i686   | 1        | 0.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 128      | 87.67%  |
| Cinnamon   | 13       | 8.9%    |
| MATE       | 3        | 2.05%   |
| XFCE       | 1        | 0.68%   |
| KDE5       | 1        | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 145      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 93       | 64.14%  |
| LightDM | 50       | 34.48%  |
| SDDM    | 1        | 0.69%   |
| GDM     | 1        | 0.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 53       | 36.55%  |
| de_DE | 18       | 12.41%  |
| pt_BR | 13       | 8.97%   |
| ru_RU | 10       | 6.9%    |
| en_GB | 8        | 5.52%   |
| it_IT | 7        | 4.83%   |
| fr_FR | 6        | 4.14%   |
| en_CA | 4        | 2.76%   |
| es_ES | 3        | 2.07%   |
| en_AU | 3        | 2.07%   |
| sv_SE | 2        | 1.38%   |
| ru_UA | 2        | 1.38%   |
| pl_PL | 2        | 1.38%   |
| fr_CA | 2        | 1.38%   |
| sk_SK | 1        | 0.69%   |
| it_CH | 1        | 0.69%   |
| fr_BE | 1        | 0.69%   |
| es_PA | 1        | 0.69%   |
| es_NI | 1        | 0.69%   |
| es_BO | 1        | 0.69%   |
| es_AR | 1        | 0.69%   |
| en_ZA | 1        | 0.69%   |
| en_NZ | 1        | 0.69%   |
| de_AT | 1        | 0.69%   |
| cs_CZ | 1        | 0.69%   |
| ar_EG | 1        | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 73       | 50.34%  |
| BIOS | 72       | 49.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 134      | 92.41%  |
| Tmpfs   | 4        | 2.76%   |
| Btrfs   | 4        | 2.76%   |
| Overlay | 3        | 2.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 94       | 64.83%  |
| GPT     | 36       | 24.83%  |
| MBR     | 15       | 10.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 126      | 86.9%   |
| Yes       | 19       | 13.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 123      | 84.83%  |
| Yes       | 22       | 15.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 29       | 20%     |
| Gigabyte Technology | 23       | 15.86%  |
| MSI                 | 18       | 12.41%  |
| Dell                | 15       | 10.34%  |
| ASRock              | 10       | 6.9%    |
| Intel               | 8        | 5.52%   |
| Hewlett-Packard     | 8        | 5.52%   |
| Acer                | 6        | 4.14%   |
| Lenovo              | 4        | 2.76%   |
| Pegatron            | 3        | 2.07%   |
| AZW                 | 3        | 2.07%   |
| Medion              | 2        | 1.38%   |
| Fujitsu             | 2        | 1.38%   |
| eMachines           | 2        | 1.38%   |
| Apple               | 2        | 1.38%   |
| SiYW                | 1        | 0.69%   |
| Sapphire            | 1        | 0.69%   |
| Samsung Electronics | 1        | 0.69%   |
| Packard Bell        | 1        | 0.69%   |
| Gateway             | 1        | 0.69%   |
| Foxconn             | 1        | 0.69%   |
| Digiboard           | 1        | 0.69%   |
| BESSTAR Tech        | 1        | 0.69%   |
| ADVANSUS            | 1        | 0.69%   |
| Unknown             | 1        | 0.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7C95                         | 2        | 1.38%   |
| MSI MS-7B79                         | 2        | 1.38%   |
| Intel B75                           | 2        | 1.38%   |
| HP ProDesk 400 G5 Desktop Mini      | 2        | 1.38%   |
| Gigabyte B450 AORUS M               | 2        | 1.38%   |
| AZW MINI S                          | 2        | 1.38%   |
| ASUS ROG STRIX B450-F GAMING        | 2        | 1.38%   |
| ASUS PRIME B350M-A                  | 2        | 1.38%   |
| ASUS PRIME A320M-K                  | 2        | 1.38%   |
| SiYW V200 Series                    | 1        | 0.69%   |
| Sapphire PI-AM3RS760G2              | 1        | 0.69%   |
| Samsung DeskTop System              | 1        | 0.69%   |
| Pegatron Pro 3015 Microtower PC     | 1        | 0.69%   |
| Pegatron p6-2143w                   | 1        | 0.69%   |
| Pegatron 520-1138c                  | 1        | 0.69%   |
| Packard Bell IMEDIA J9640           | 1        | 0.69%   |
| MSI MS-7D54                         | 1        | 0.69%   |
| MSI MS-7D22                         | 1        | 0.69%   |
| MSI MS-7C52                         | 1        | 0.69%   |
| MSI MS-7C02                         | 1        | 0.69%   |
| MSI MS-7B23                         | 1        | 0.69%   |
| MSI MS-7B17                         | 1        | 0.69%   |
| MSI MS-7A40                         | 1        | 0.69%   |
| MSI MS-7A38                         | 1        | 0.69%   |
| MSI MS-7984                         | 1        | 0.69%   |
| MSI MS-7977                         | 1        | 0.69%   |
| MSI MS-7974                         | 1        | 0.69%   |
| MSI MS-7851                         | 1        | 0.69%   |
| MSI MS-7721                         | 1        | 0.69%   |
| MSI MS-7693                         | 1        | 0.69%   |
| Medion S23003                       | 1        | 0.69%   |
| Medion MS-7800                      | 1        | 0.69%   |
| Lenovo V55t-15ARE 11KJ0036TX        | 1        | 0.69%   |
| Lenovo ThinkCentre M92p 3238E9U     | 1        | 0.69%   |
| Lenovo ThinkCentre M720s 10SUS9KW00 | 1        | 0.69%   |
| Lenovo H530 10130                   | 1        | 0.69%   |
| Intel X79                           | 1        | 0.69%   |
| Intel SHARKBAY                      | 1        | 0.69%   |
| Intel H61M-DS2V                     | 1        | 0.69%   |
| Intel DQ77MK AAG39642-400           | 1        | 0.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 8        | 5.52%   |
| Dell OptiPlex          | 5        | 3.45%   |
| ASUS ROG               | 5        | 3.45%   |
| Acer Aspire            | 5        | 3.45%   |
| Dell Precision         | 4        | 2.76%   |
| Gigabyte B450M         | 3        | 2.07%   |
| Gigabyte B450          | 3        | 2.07%   |
| MSI MS-7C95            | 2        | 1.38%   |
| MSI MS-7B79            | 2        | 1.38%   |
| Lenovo ThinkCentre     | 2        | 1.38%   |
| Intel B75              | 2        | 1.38%   |
| HP ProDesk             | 2        | 1.38%   |
| Gigabyte A520M         | 2        | 1.38%   |
| Dell Vostro            | 2        | 1.38%   |
| Dell Inspiron          | 2        | 1.38%   |
| AZW MINI               | 2        | 1.38%   |
| ASUS P8H61-M           | 2        | 1.38%   |
| SiYW V200              | 1        | 0.69%   |
| Sapphire PI-AM3RS760G2 | 1        | 0.69%   |
| Samsung DeskTop        | 1        | 0.69%   |
| Pegatron Pro           | 1        | 0.69%   |
| Pegatron p6-2143w      | 1        | 0.69%   |
| Pegatron 520-1138c     | 1        | 0.69%   |
| Packard Bell IMEDIA    | 1        | 0.69%   |
| MSI MS-7D54            | 1        | 0.69%   |
| MSI MS-7D22            | 1        | 0.69%   |
| MSI MS-7C52            | 1        | 0.69%   |
| MSI MS-7C02            | 1        | 0.69%   |
| MSI MS-7B23            | 1        | 0.69%   |
| MSI MS-7B17            | 1        | 0.69%   |
| MSI MS-7A40            | 1        | 0.69%   |
| MSI MS-7A38            | 1        | 0.69%   |
| MSI MS-7984            | 1        | 0.69%   |
| MSI MS-7977            | 1        | 0.69%   |
| MSI MS-7974            | 1        | 0.69%   |
| MSI MS-7851            | 1        | 0.69%   |
| MSI MS-7721            | 1        | 0.69%   |
| MSI MS-7693            | 1        | 0.69%   |
| Medion S23003          | 1        | 0.69%   |
| Medion MS-7800         | 1        | 0.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 26       | 17.93%  |
| 2012 | 17       | 11.72%  |
| 2021 | 10       | 6.9%    |
| 2017 | 9        | 6.21%   |
| 2011 | 9        | 6.21%   |
| 2020 | 8        | 5.52%   |
| 2019 | 8        | 5.52%   |
| 2015 | 8        | 5.52%   |
| 2009 | 8        | 5.52%   |
| 2022 | 7        | 4.83%   |
| 2016 | 7        | 4.83%   |
| 2013 | 7        | 4.83%   |
| 2010 | 7        | 4.83%   |
| 2014 | 4        | 2.76%   |
| 2007 | 4        | 2.76%   |
| 2006 | 4        | 2.76%   |
| 2008 | 2        | 1.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 145      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 143      | 97.95%  |
| Enabled  | 3        | 2.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 145      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 34       | 22.67%  |
| 8.01-16.0       | 30       | 20%     |
| 4.01-8.0        | 29       | 19.33%  |
| 32.01-64.0      | 27       | 18%     |
| 3.01-4.0        | 13       | 8.67%   |
| 1.01-2.0        | 6        | 4%      |
| 24.01-32.0      | 5        | 3.33%   |
| 2.01-3.0        | 2        | 1.33%   |
| 64.01-256.0     | 2        | 1.33%   |
| More than 256.0 | 1        | 0.67%   |
| 0.51-1.0        | 1        | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 55       | 34.38%  |
| 2.01-3.0   | 48       | 30%     |
| 4.01-8.0   | 25       | 15.63%  |
| 3.01-4.0   | 18       | 11.25%  |
| 8.01-16.0  | 6        | 3.75%   |
| 0.51-1.0   | 6        | 3.75%   |
| 24.01-32.0 | 1        | 0.63%   |
| 16.01-24.0 | 1        | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 41.89%  |
| 2      | 38       | 25.68%  |
| 3      | 19       | 12.84%  |
| 4      | 14       | 9.46%   |
| 5      | 9        | 6.08%   |
| 6      | 5        | 3.38%   |
| 7      | 1        | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 58.22%  |
| Yes       | 61       | 41.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 144      | 99.31%  |
| No        | 1        | 0.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 77       | 52.03%  |
| No        | 71       | 47.97%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 66.44%  |
| Yes       | 49       | 33.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 35       | 24.14%  |
| Germany      | 22       | 15.17%  |
| Brazil       | 14       | 9.66%   |
| Russia       | 11       | 7.59%   |
| Italy        | 8        | 5.52%   |
| France       | 7        | 4.83%   |
| Canada       | 7        | 4.83%   |
| UK           | 5        | 3.45%   |
| Australia    | 4        | 2.76%   |
| Sweden       | 3        | 2.07%   |
| Spain        | 3        | 2.07%   |
| Ukraine      | 2        | 1.38%   |
| South Africa | 2        | 1.38%   |
| Poland       | 2        | 1.38%   |
| Netherlands  | 2        | 1.38%   |
| Mexico       | 2        | 1.38%   |
| Kazakhstan   | 2        | 1.38%   |
| Bolivia      | 2        | 1.38%   |
| Venezuela    | 1        | 0.69%   |
| Turkey       | 1        | 0.69%   |
| Slovakia     | 1        | 0.69%   |
| Panama       | 1        | 0.69%   |
| Nicaragua    | 1        | 0.69%   |
| New Zealand  | 1        | 0.69%   |
| Latvia       | 1        | 0.69%   |
| Indonesia    | 1        | 0.69%   |
| India        | 1        | 0.69%   |
| Belgium      | 1        | 0.69%   |
| Austria      | 1        | 0.69%   |
| Argentina    | 1        | 0.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Berlin                   | 5        | 3.29%   |
| Rio de Janeiro           | 2        | 1.32%   |
| Montreal                 | 2        | 1.32%   |
| Melbourne                | 2        | 1.32%   |
| Frankfurt am Main        | 2        | 1.32%   |
| Delligsen                | 2        | 1.32%   |
| Columbia City            | 2        | 1.32%   |
| Belém                   | 2        | 1.32%   |
| Witzenhausen             | 1        | 0.66%   |
| Washington               | 1        | 0.66%   |
| Volta Redonda            | 1        | 0.66%   |
| Volgograd                | 1        | 0.66%   |
| Vitória da Conquista    | 1        | 0.66%   |
| Vincennes                | 1        | 0.66%   |
| Vicente Guerrero         | 1        | 0.66%   |
| Varese                   | 1        | 0.66%   |
| Ulyanovsk                | 1        | 0.66%   |
| Trieste                  | 1        | 0.66%   |
| Toronto                  | 1        | 0.66%   |
| Tolyatti                 | 1        | 0.66%   |
| Toledo                   | 1        | 0.66%   |
| Toccoa                   | 1        | 0.66%   |
| Tacoma                   | 1        | 0.66%   |
| Sydney                   | 1        | 0.66%   |
| Stockelsdorf             | 1        | 0.66%   |
| Stockbridge              | 1        | 0.66%   |
| Spruce Grove             | 1        | 0.66%   |
| Sollentuna               | 1        | 0.66%   |
| Solingen                 | 1        | 0.66%   |
| Semey                    | 1        | 0.66%   |
| Schwelm                  | 1        | 0.66%   |
| Schruns                  | 1        | 0.66%   |
| Sao Lourenço            | 1        | 0.66%   |
| Santa Luzia              | 1        | 0.66%   |
| Santa Ana                | 1        | 0.66%   |
| Sant Feliu de Llobregat  | 1        | 0.66%   |
| San Miguel De Abona      | 1        | 0.66%   |
| San Antonio de Los Altos | 1        | 0.66%   |
| San Antonio              | 1        | 0.66%   |
| Salisbury                | 1        | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 53       | 104    | 20.23%  |
| Seagate                   | 41       | 64     | 15.65%  |
| Samsung Electronics       | 34       | 66     | 12.98%  |
| Kingston                  | 18       | 30     | 6.87%   |
| Toshiba                   | 15       | 17     | 5.73%   |
| Crucial                   | 12       | 14     | 4.58%   |
| SanDisk                   | 10       | 11     | 3.82%   |
| Hitachi                   | 8        | 10     | 3.05%   |
| China                     | 5        | 6      | 1.91%   |
| SK hynix                  | 4        | 5      | 1.53%   |
| A-DATA Technology         | 4        | 4      | 1.53%   |
| Unknown                   | 3        | 3      | 1.15%   |
| SPCC                      | 3        | 4      | 1.15%   |
| Silicon Motion            | 3        | 4      | 1.15%   |
| ADATA Technology          | 3        | 6      | 1.15%   |
| Unknown                   | 3        | 7      | 1.15%   |
| Transcend                 | 2        | 3      | 0.76%   |
| PNY                       | 2        | 3      | 0.76%   |
| Phison                    | 2        | 7      | 0.76%   |
| Patriot                   | 2        | 3      | 0.76%   |
| Micron Technology         | 2        | 2      | 0.76%   |
| Apple                     | 2        | 2      | 0.76%   |
| Apacer                    | 2        | 2      | 0.76%   |
| XrayDisk                  | 1        | 2      | 0.38%   |
| WALRAM                    | 1        | 1      | 0.38%   |
| Vaseky                    | 1        | 4      | 0.38%   |
| V-GeN                     | 1        | 1      | 0.38%   |
| Timetec                   | 1        | 1      | 0.38%   |
| TGT                       | 1        | 1      | 0.38%   |
| Team                      | 1        | 1      | 0.38%   |
| TakeMS                    | 1        | 1      | 0.38%   |
| T-FORCE                   | 1        | 1      | 0.38%   |
| SD                        | 1        | 1      | 0.38%   |
| PNY USB                   | 1        | 1      | 0.38%   |
| Phison Electronics        | 1        | 1      | 0.38%   |
| OCZ-VERTEX                | 1        | 1      | 0.38%   |
| OCZ                       | 1        | 1      | 0.38%   |
| NGFF                      | 1        | 1      | 0.38%   |
| Netac                     | 1        | 1      | 0.38%   |
| Micron/Crucial Technology | 1        | 2      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                                       | 6        | 1.93%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 4        | 1.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB               | 4        | 1.29%   |
| Kingston SA400S37240G 240GB SSD                                 | 4        | 1.29%   |
| Kingston SA400S37120G 120GB SSD                                 | 4        | 1.29%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 480GB             | 3        | 0.96%   |
| Seagate ST500DM002-1BD142 500GB                                 | 3        | 0.96%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 3        | 0.96%   |
| Samsung SSD 970 EVO 500GB                                       | 3        | 0.96%   |
| Samsung SSD 850 EVO 500GB                                       | 3        | 0.96%   |
| Kingston SA400S37480G 480GB SSD                                 | 3        | 0.96%   |
| Crucial CT480BX500SSD1 480GB                                    | 3        | 0.96%   |
| Unknown                                                         | 3        | 0.96%   |
| WDC WD3003FZEX-00Z4SA0 3TB                                      | 2        | 0.64%   |
| WDC WD10JPVX-75JC3T0 1TB                                        | 2        | 0.64%   |
| Unknown SD/MMC/MS PRO 256GB                                     | 2        | 0.64%   |
| Toshiba HDWD110 1TB                                             | 2        | 0.64%   |
| Seagate ST3320418AS 320GB                                       | 2        | 0.64%   |
| Seagate ST3250318AS 250GB                                       | 2        | 0.64%   |
| Seagate ST2000LX001-1RG174 2TB                                  | 2        | 0.64%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 2        | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB                                  | 2        | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 2        | 0.64%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                            | 2        | 0.64%   |
| Samsung SSD 980 PRO 1TB                                         | 2        | 0.64%   |
| Samsung SSD 870 QVO 1TB                                         | 2        | 0.64%   |
| Samsung SSD 870 EVO 2TB                                         | 2        | 0.64%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB                          | 2        | 0.64%   |
| Samsung NVMe SSD Drive 500GB                                    | 2        | 0.64%   |
| Hitachi HDP725050GLA360 500GB                                   | 2        | 0.64%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 2TB | 2        | 0.64%   |
| XrayDisk 480GB                                                  | 1        | 0.32%   |
| XrayDisk 1TB                                                    | 1        | 0.32%   |
| WDC WUH721414ALE6L1 14TB                                        | 1        | 0.32%   |
| WDC WDS500G3X0C-00SJG0 500GB                                    | 1        | 0.32%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                                | 1        | 0.32%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                | 1        | 0.32%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                                | 1        | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1        | 0.32%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                                  | 1        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 47       | 91     | 37.9%   |
| Seagate             | 41       | 63     | 33.06%  |
| Toshiba             | 14       | 16     | 11.29%  |
| Hitachi             | 8        | 10     | 6.45%   |
| Samsung Electronics | 7        | 10     | 5.65%   |
| Unknown             | 2        | 2      | 1.61%   |
| Intenso             | 1        | 1      | 0.81%   |
| HGST                | 1        | 1      | 0.81%   |
| ASMT                | 1        | 2      | 0.81%   |
| ASMedia             | 1        | 1      | 0.81%   |
| Apple               | 1        | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 22       | 33     | 21.36%  |
| Kingston            | 15       | 27     | 14.56%  |
| Crucial             | 11       | 13     | 10.68%  |
| WDC                 | 7        | 12     | 6.8%    |
| SanDisk             | 5        | 5      | 4.85%   |
| China               | 5        | 6      | 4.85%   |
| A-DATA Technology   | 4        | 4      | 3.88%   |
| SPCC                | 3        | 4      | 2.91%   |
| Transcend           | 2        | 3      | 1.94%   |
| SK hynix            | 2        | 2      | 1.94%   |
| PNY                 | 2        | 3      | 1.94%   |
| Patriot             | 2        | 3      | 1.94%   |
| Apacer              | 2        | 2      | 1.94%   |
| Vaseky              | 1        | 4      | 0.97%   |
| V-GeN               | 1        | 1      | 0.97%   |
| Toshiba             | 1        | 1      | 0.97%   |
| Team                | 1        | 1      | 0.97%   |
| TakeMS              | 1        | 1      | 0.97%   |
| T-FORCE             | 1        | 1      | 0.97%   |
| SD                  | 1        | 1      | 0.97%   |
| PNY USB             | 1        | 1      | 0.97%   |
| Phison              | 1        | 6      | 0.97%   |
| OCZ-VERTEX          | 1        | 1      | 0.97%   |
| OCZ                 | 1        | 1      | 0.97%   |
| NGFF                | 1        | 1      | 0.97%   |
| Netac               | 1        | 1      | 0.97%   |
| Micron Technology   | 1        | 1      | 0.97%   |
| LITEONIT            | 1        | 1      | 0.97%   |
| Hewlett-Packard     | 1        | 1      | 0.97%   |
| GOODRAM             | 1        | 1      | 0.97%   |
| Gigabyte Technology | 1        | 2      | 0.97%   |
| Apple               | 1        | 1      | 0.97%   |
| 2.5''               | 1        | 1      | 0.97%   |
| Unknown             | 1        | 2      | 0.97%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 96       | 198    | 42.29%  |
| SSD     | 87       | 148    | 38.33%  |
| NVMe    | 36       | 55     | 15.86%  |
| Unknown | 7        | 11     | 3.08%   |
| MMC     | 1        | 1      | 0.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 134      | 338    | 72.83%  |
| NVMe | 36       | 55     | 19.57%  |
| SAS  | 13       | 19     | 7.07%   |
| MMC  | 1        | 1      | 0.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 99       | 193    | 50.51%  |
| 0.51-1.0   | 55       | 88     | 28.06%  |
| 1.01-2.0   | 19       | 25     | 9.69%   |
| 4.01-10.0  | 8        | 12     | 4.08%   |
| 2.01-3.0   | 7        | 16     | 3.57%   |
| 3.01-4.0   | 6        | 10     | 3.06%   |
| 10.01-20.0 | 2        | 2      | 1.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 39       | 25.49%  |
| 251-500        | 34       | 22.22%  |
| 1001-2000      | 21       | 13.73%  |
| 501-1000       | 21       | 13.73%  |
| More than 3000 | 15       | 9.8%    |
| 2001-3000      | 8        | 5.23%   |
| 1-20           | 7        | 4.58%   |
| 51-100         | 6        | 3.92%   |
| 21-50          | 2        | 1.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 49       | 30.82%  |
| 21-50          | 26       | 16.35%  |
| 101-250        | 20       | 12.58%  |
| 251-500        | 18       | 11.32%  |
| 51-100         | 16       | 10.06%  |
| 501-1000       | 11       | 6.92%   |
| 1001-2000      | 9        | 5.66%   |
| More than 3000 | 5        | 3.14%   |
| 2001-3000      | 5        | 3.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD10EZEX-60WN4A0 1TB            | 1        | 1      | 6.25%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 1        | 1      | 6.25%   |
| Toshiba MQ04ABF100 1TB              | 1        | 1      | 6.25%   |
| Toshiba MD04ACA400 4TB              | 1        | 1      | 6.25%   |
| Toshiba HDWD110 1TB                 | 1        | 1      | 6.25%   |
| Seagate ST500LT012-1DG142 500GB     | 1        | 1      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 6.25%   |
| Seagate ST3250318AS 250GB           | 1        | 1      | 6.25%   |
| Seagate ST2000DX001-1CM164 2TB      | 1        | 1      | 6.25%   |
| Seagate ST1000LM048-2E7172 1TB      | 1        | 1      | 6.25%   |
| Seagate ST1000DM003-9YN162 1TB      | 1        | 1      | 6.25%   |
| Samsung Electronics SSD 980 500GB   | 1        | 1      | 6.25%   |
| Samsung Electronics SSD 870 EVO 2TB | 1        | 1      | 6.25%   |
| Samsung Electronics HD153WI 1TB     | 1        | 1      | 6.25%   |
| Hitachi HDS721010KLA330 1TB         | 1        | 1      | 6.25%   |
| Hitachi HDP725050GLA360 500GB       | 1        | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 6      | 37.5%   |
| Toshiba             | 3        | 3      | 18.75%  |
| Samsung Electronics | 3        | 3      | 18.75%  |
| WDC                 | 2        | 2      | 12.5%   |
| Hitachi             | 2        | 2      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 6      | 42.86%  |
| Toshiba             | 3        | 3      | 21.43%  |
| WDC                 | 2        | 2      | 14.29%  |
| Hitachi             | 2        | 2      | 14.29%  |
| Samsung Electronics | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 14     | 85.71%  |
| NVMe | 1        | 1      | 7.14%   |
| SSD  | 1        | 1      | 7.14%   |

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
| Detected | 101      | 271    | 63.13%  |
| Works    | 46       | 126    | 28.75%  |
| Malfunc  | 13       | 16     | 8.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 91       | 45.73%  |
| AMD                         | 49       | 24.62%  |
| Samsung Electronics         | 12       | 6.03%   |
| SanDisk                     | 6        | 3.02%   |
| ASMedia Technology          | 6        | 3.02%   |
| JMicron Technology          | 5        | 2.51%   |
| Silicon Motion              | 4        | 2.01%   |
| Phison Electronics          | 3        | 1.51%   |
| Nvidia                      | 3        | 1.51%   |
| Marvell Technology Group    | 3        | 1.51%   |
| Kingston Technology Company | 3        | 1.51%   |
| Broadcom / LSI              | 3        | 1.51%   |
| ADATA Technology            | 3        | 1.51%   |
| VIA Technologies            | 2        | 1.01%   |
| SK hynix                    | 2        | 1.01%   |
| Micron/Crucial Technology   | 2        | 1.01%   |
| Micron Technology           | 1        | 0.5%    |
| LSI Logic / Symbios Logic   | 1        | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27       | 10.51%  |
| AMD 400 Series Chipset SATA Controller                                                  | 16       | 6.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 3.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 3.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 3.5%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 3.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 3.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8        | 3.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 2.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.33%   |
| AMD FCH SATA Controller D                                                               | 6        | 2.33%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 2.33%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 5        | 1.95%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.56%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.56%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 1.17%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 1.17%   |
| Intel SATA Controller [RAID Mode]                                                       | 3        | 1.17%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3        | 1.17%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 1.17%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.17%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.78%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.78%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 2        | 0.78%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 2        | 0.78%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 2        | 0.78%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 2        | 0.78%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 0.78%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.78%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 0.78%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.78%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 125      | 60.68%  |
| NVMe | 36       | 17.48%  |
| IDE  | 33       | 16.02%  |
| RAID | 8        | 3.88%   |
| SAS  | 3        | 1.46%   |
| SCSI | 1        | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 93       | 64.14%  |
| AMD    | 52       | 35.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 4.08%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 3.4%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 2.72%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 2.72%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 2.72%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 2.72%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 2.04%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 2.04%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz         | 2        | 1.36%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2        | 1.36%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 1.36%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 1.36%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 1.36%   |
| Intel Core i5-9500T CPU @ 2.20GHz           | 2        | 1.36%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.36%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 1.36%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 1.36%   |
| Intel Celeron N5095 @ 2.00GHz               | 2        | 1.36%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 1.36%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.36%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 1.36%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 2        | 1.36%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 1.36%   |
| AMD FX-4300 Quad-Core Processor             | 2        | 1.36%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1        | 0.68%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 0.68%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 0.68%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1        | 0.68%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 0.68%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 0.68%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 0.68%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 0.68%   |
| Intel Xeon CPU 3.40GHz                      | 1        | 0.68%   |
| Intel Pentium Gold G7400                    | 1        | 0.68%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.68%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.68%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 0.68%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.68%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 0.68%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 24       | 16.44%  |
| Intel Core i7           | 20       | 13.7%   |
| AMD Ryzen 5             | 16       | 10.96%  |
| Intel Xeon              | 12       | 8.22%   |
| AMD Ryzen 7             | 11       | 7.53%   |
| Intel Core i3           | 7        | 4.79%   |
| AMD Ryzen 3             | 7        | 4.79%   |
| Other                   | 5        | 3.42%   |
| Intel Celeron           | 5        | 3.42%   |
| Intel Pentium           | 4        | 2.74%   |
| Intel Core 2 Duo        | 4        | 2.74%   |
| Intel Pentium Dual-Core | 3        | 2.05%   |
| Intel Core 2 Quad       | 3        | 2.05%   |
| AMD FX                  | 3        | 2.05%   |
| AMD Athlon II X2        | 3        | 2.05%   |
| Intel Pentium Gold      | 2        | 1.37%   |
| Intel Pentium Dual      | 2        | 1.37%   |
| Intel Pentium D         | 2        | 1.37%   |
| AMD Phenom II X6        | 2        | 1.37%   |
| AMD Athlon              | 2        | 1.37%   |
| AMD A4                  | 2        | 1.37%   |
| Intel Core 2            | 1        | 0.68%   |
| AMD Ryzen 9             | 1        | 0.68%   |
| AMD Phenom II X4        | 1        | 0.68%   |
| AMD G                   | 1        | 0.68%   |
| AMD E1                  | 1        | 0.68%   |
| AMD A8                  | 1        | 0.68%   |
| AMD A6                  | 1        | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 60       | 40.82%  |
| 2      | 36       | 24.49%  |
| 6      | 21       | 14.29%  |
| 8      | 19       | 12.93%  |
| 16     | 5        | 3.4%    |
| 1      | 3        | 2.04%   |
| 12     | 2        | 1.36%   |
| 10     | 1        | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 139      | 95.86%  |
| 2      | 6        | 4.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 81       | 55.48%  |
| 1      | 65       | 44.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 145      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 14       | 9.4%    |
| 0x306c3    | 10       | 6.71%   |
| 0x206a7    | 9        | 6.04%   |
| 0x08108109 | 7        | 4.7%    |
| 0x506e3    | 6        | 4.03%   |
| 0x1067a    | 6        | 4.03%   |
| 0x0800820d | 6        | 4.03%   |
| Unknown    | 6        | 4.03%   |
| 0x08701021 | 5        | 3.36%   |
| 0x906ea    | 4        | 2.68%   |
| 0x0a50000d | 4        | 2.68%   |
| 0xa0671    | 3        | 2.01%   |
| 0x906ed    | 3        | 2.01%   |
| 0x906e9    | 3        | 2.01%   |
| 0x6fd      | 3        | 2.01%   |
| 0x206d7    | 3        | 2.01%   |
| 0x08701030 | 3        | 2.01%   |
| 0x010000c8 | 3        | 2.01%   |
| 0xa0653    | 2        | 1.34%   |
| 0x906c0    | 2        | 1.34%   |
| 0x90675    | 2        | 1.34%   |
| 0x706a8    | 2        | 1.34%   |
| 0x306e4    | 2        | 1.34%   |
| 0x206c2    | 2        | 1.34%   |
| 0x20655    | 2        | 1.34%   |
| 0x106e5    | 2        | 1.34%   |
| 0x0a201016 | 2        | 1.34%   |
| 0x08101016 | 2        | 1.34%   |
| 0x0810100b | 2        | 1.34%   |
| 0x08001138 | 2        | 1.34%   |
| 0x06001119 | 2        | 1.34%   |
| 0x06000852 | 2        | 1.34%   |
| 0xf65      | 1        | 0.67%   |
| 0xf47      | 1        | 0.67%   |
| 0xf43      | 1        | 0.67%   |
| 0xa0655    | 1        | 0.67%   |
| 0x806ea    | 1        | 0.67%   |
| 0x806c2    | 1        | 0.67%   |
| 0x6fb      | 1        | 0.67%   |
| 0x6f2      | 1        | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 18       | 12.24%  |
| Zen+          | 13       | 8.84%   |
| SandyBridge   | 13       | 8.84%   |
| KabyLake      | 11       | 7.48%   |
| Haswell       | 11       | 7.48%   |
| Zen 3         | 9        | 6.12%   |
| Zen           | 8        | 5.44%   |
| Zen 2         | 7        | 4.76%   |
| Penryn        | 7        | 4.76%   |
| Skylake       | 6        | 4.08%   |
| K10           | 6        | 4.08%   |
| Core          | 6        | 4.08%   |
| Piledriver    | 5        | 3.4%    |
| Unknown       | 5        | 3.4%    |
| Westmere      | 4        | 2.72%   |
| NetBurst      | 3        | 2.04%   |
| Nehalem       | 3        | 2.04%   |
| CometLake     | 3        | 2.04%   |
| Tremont       | 2        | 1.36%   |
| Goldmont plus | 2        | 1.36%   |
| TigerLake     | 1        | 0.68%   |
| K10 Llano     | 1        | 0.68%   |
| Jaguar        | 1        | 0.68%   |
| Bulldozer     | 1        | 0.68%   |
| Bobcat        | 1        | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 76       | 48.41%  |
| Intel  | 41       | 26.11%  |
| AMD    | 40       | 25.48%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7        | 4.35%   |
| Nvidia GK208B [GeForce GT 730]                                              | 6        | 3.73%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 3.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 3.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 3.73%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 3.11%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 3.11%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 2.48%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4        | 2.48%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 2.48%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.86%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 1.86%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.86%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.24%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.24%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 1.24%   |
| Intel HD Graphics 530                                                       | 2        | 1.24%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 1.24%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.24%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.24%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 2        | 1.24%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 1.24%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 1.24%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.62%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.62%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.62%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.62%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.62%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 0.62%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 0.62%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.62%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 0.62%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.62%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.62%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 69       | 46.62%  |
| 1 x Intel      | 35       | 23.65%  |
| 1 x AMD        | 32       | 21.62%  |
| 2 x AMD        | 4        | 2.7%    |
| Intel + Nvidia | 3        | 2.03%   |
| AMD + Nvidia   | 3        | 2.03%   |
| 2 x Nvidia     | 1        | 0.68%   |
| Intel + AMD    | 1        | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 98       | 66.67%  |
| Proprietary | 36       | 24.49%  |
| Unknown     | 13       | 8.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 50       | 33.56%  |
| 1.01-2.0   | 31       | 20.81%  |
| 0.01-0.5   | 19       | 12.75%  |
| 3.01-4.0   | 16       | 10.74%  |
| 0.51-1.0   | 14       | 9.4%    |
| 7.01-8.0   | 8        | 5.37%   |
| 5.01-6.0   | 6        | 4.03%   |
| 8.01-16.0  | 3        | 2.01%   |
| 2.01-3.0   | 1        | 0.67%   |
| 16.01-24.0 | 1        | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 26       | 18.98%  |
| Goldstar             | 15       | 10.95%  |
| Acer                 | 12       | 8.76%   |
| Dell                 | 10       | 7.3%    |
| Hewlett-Packard      | 9        | 6.57%   |
| Philips              | 8        | 5.84%   |
| BenQ                 | 8        | 5.84%   |
| Unknown              | 5        | 3.65%   |
| AOC                  | 5        | 3.65%   |
| Sony                 | 4        | 2.92%   |
| Ancor Communications | 4        | 2.92%   |
| ViewSonic            | 2        | 1.46%   |
| Iiyama               | 2        | 1.46%   |
| Fujitsu Siemens      | 2        | 1.46%   |
| ASUSTek Computer     | 2        | 1.46%   |
| ___                  | 1        | 0.73%   |
| Unknown (XXX)        | 1        | 0.73%   |
| Toshiba              | 1        | 0.73%   |
| Targa                | 1        | 0.73%   |
| SKY                  | 1        | 0.73%   |
| PLN                  | 1        | 0.73%   |
| Pioneer              | 1        | 0.73%   |
| Nixeus               | 1        | 0.73%   |
| NEC Computers        | 1        | 0.73%   |
| MStar                | 1        | 0.73%   |
| MSI                  | 1        | 0.73%   |
| Medion               | 1        | 0.73%   |
| Lenovo Group Limited | 1        | 0.73%   |
| Lenovo               | 1        | 0.73%   |
| Insignia             | 1        | 0.73%   |
| Idek Iiyama          | 1        | 0.73%   |
| HUAWEI               | 1        | 0.73%   |
| HPN                  | 1        | 0.73%   |
| HannStar             | 1        | 0.73%   |
| DENON                | 1        | 0.73%   |
| AUS                  | 1        | 0.73%   |
| Apple                | 1        | 0.73%   |
| Unknown              | 1        | 0.73%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 4        | 2.7%    |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 3        | 2.03%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2        | 1.35%   |
| Fujitsu Siemens P27-9 TS QHD FUS08D5 2560x1440 597x336mm 27.0-inch   | 2        | 1.35%   |
| ___ LCD TV ___0101 1920x1080                                         | 1        | 0.68%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch           | 1        | 0.68%   |
| ViewSonic VG2230wm-EU VSCA21E 1680x1050 474x296mm 22.0-inch          | 1        | 0.68%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                   | 1        | 0.68%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                | 1        | 0.68%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                 | 1        | 0.68%   |
| Unknown LCD Monitor SAMSUNG                                          | 1        | 0.68%   |
| Unknown LCD Monitor Dell SE2717H/HX 1920x1080                        | 1        | 0.68%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 0.68%   |
| Toshiba LCD Monitor TV 1920x1080                                     | 1        | 0.68%   |
| Targa LCD Monitor LCD TV                                             | 1        | 0.68%   |
| Sony TV SNY8E01 1360x768                                             | 1        | 0.68%   |
| Sony TV SNY8701 1440x900                                             | 1        | 0.68%   |
| Sony LCD Monitor TV 3840x1080                                        | 1        | 0.68%   |
| Sony LCD Monitor TV  *00 1920x1080                                   | 1        | 0.68%   |
| SKY TV SKY1502 3840x2160 708x398mm 32.0-inch                         | 1        | 0.68%   |
| SKY TV SKY1502 3840x2160 1150x650mm 52.0-inch                        | 1        | 0.68%   |
| SKY Toshiba TV SKY1402 3840x2160 708x398mm 32.0-inch                 | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 521x293mm 23.5-inch | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM03D0 1440x900 410x257mm 19.1-inch  | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 376x301mm 19.0-inch | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0022 1280x1024 312x234mm 15.4-inch | 1        | 0.68%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch  | 1        | 0.68%   |
| Samsung Electronics SMFX2490HD SAM074A 1920x1080 531x299mm 24.0-inch | 1        | 0.68%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch    | 1        | 0.68%   |
| Samsung Electronics SMBX1950N SAM0716 1366x768 410x230mm 18.5-inch   | 1        | 0.68%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch   | 1        | 0.68%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch | 1        | 0.68%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1        | 0.68%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch    | 1        | 0.68%   |
| Samsung Electronics S24C350 SAM0A3B 1920x1080 521x293mm 23.5-inch    | 1        | 0.68%   |
| Samsung Electronics S24B370 SAM08DD 1920x1080 531x299mm 24.0-inch    | 1        | 0.68%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch    | 1        | 0.68%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 1        | 0.68%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1        | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 63       | 47.37%  |
| 3840x2160 (4K)     | 9        | 6.77%   |
| 2560x1440 (QHD)    | 8        | 6.02%   |
| 1680x1050 (WSXGA+) | 8        | 6.02%   |
| 1280x1024 (SXGA)   | 6        | 4.51%   |
| 2560x1080          | 5        | 3.76%   |
| 1600x900 (HD+)     | 5        | 3.76%   |
| 1366x768 (WXGA)    | 5        | 3.76%   |
| 3440x1440          | 4        | 3.01%   |
| Unknown            | 4        | 3.01%   |
| 1920x1200 (WUXGA)  | 3        | 2.26%   |
| 1440x900 (WXGA+)   | 3        | 2.26%   |
| 1360x768           | 3        | 2.26%   |
| 3840x1080          | 2        | 1.5%    |
| 4480x1440          | 1        | 0.75%   |
| 3040x1050          | 1        | 0.75%   |
| 1600x1200          | 1        | 0.75%   |
| 1280x768           | 1        | 0.75%   |
| 1024x768 (XGA)     | 1        | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 27       | 19.71%  |
| 24      | 19       | 13.87%  |
| 21      | 17       | 12.41%  |
| 23      | 14       | 10.22%  |
| 27      | 13       | 9.49%   |
| 34      | 6        | 4.38%   |
| 20      | 6        | 4.38%   |
| 22      | 5        | 3.65%   |
| 18      | 5        | 3.65%   |
| 72      | 4        | 2.92%   |
| 19      | 4        | 2.92%   |
| 31      | 3        | 2.19%   |
| 52      | 2        | 1.46%   |
| 32      | 2        | 1.46%   |
| 25      | 2        | 1.46%   |
| 17      | 2        | 1.46%   |
| 15      | 2        | 1.46%   |
| 64      | 1        | 0.73%   |
| 54      | 1        | 0.73%   |
| 40      | 1        | 0.73%   |
| 28      | 1        | 0.73%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 44       | 33.85%  |
| 401-500     | 31       | 23.85%  |
| Unknown     | 27       | 20.77%  |
| 701-800     | 8        | 6.15%   |
| 601-700     | 6        | 4.62%   |
| 301-350     | 4        | 3.08%   |
| 1501-2000   | 4        | 3.08%   |
| 1001-1500   | 3        | 2.31%   |
| 351-400     | 2        | 1.54%   |
| 801-900     | 1        | 0.77%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 72       | 56.69%  |
| Unknown | 26       | 20.47%  |
| 16/10   | 13       | 10.24%  |
| 21/9    | 8        | 6.3%    |
| 5/4     | 4        | 3.15%   |
| 4/3     | 4        | 3.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 47       | 35.07%  |
| Unknown        | 27       | 20.15%  |
| 301-350        | 13       | 9.7%    |
| 351-500        | 11       | 8.21%   |
| 151-200        | 11       | 8.21%   |
| 251-300        | 8        | 5.97%   |
| More than 1000 | 7        | 5.22%   |
| 141-150        | 7        | 5.22%   |
| 111-120        | 1        | 0.75%   |
| 101-110        | 1        | 0.75%   |
| 501-1000       | 1        | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 72       | 55.38%  |
| Unknown | 27       | 20.77%  |
| 101-120 | 24       | 18.46%  |
| 1-50    | 6        | 4.62%   |
| 121-160 | 1        | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 114      | 77.03%  |
| 2     | 21       | 14.19%  |
| 0     | 11       | 7.43%   |
| 3     | 2        | 1.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 95       | 45.24%  |
| Intel                    | 60       | 28.57%  |
| Qualcomm Atheros         | 10       | 4.76%   |
| TP-Link                  | 7        | 3.33%   |
| Broadcom                 | 6        | 2.86%   |
| Ralink Technology        | 5        | 2.38%   |
| Nvidia                   | 3        | 1.43%   |
| NetGear                  | 3        | 1.43%   |
| VIA Technologies         | 2        | 0.95%   |
| Tenda                    | 2        | 0.95%   |
| Samsung Electronics      | 2        | 0.95%   |
| Ralink                   | 2        | 0.95%   |
| MediaTek                 | 2        | 0.95%   |
| Marvell Technology Group | 2        | 0.95%   |
| Huawei Technologies      | 2        | 0.95%   |
| Qualcomm                 | 1        | 0.48%   |
| Microsoft                | 1        | 0.48%   |
| Mercucys                 | 1        | 0.48%   |
| IMC Networks             | 1        | 0.48%   |
| HTC (High Tech Computer) | 1        | 0.48%   |
| Belkin Components        | 1        | 0.48%   |
| ASUSTek Computer         | 1        | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 76       | 30.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11       | 4.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 7        | 2.82%   |
| Intel I211 Gigabit Network Connection                                  | 7        | 2.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5        | 2.02%   |
| Intel Wireless 3165                                                    | 5        | 2.02%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 4        | 1.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 1.61%   |
| Intel Ethernet Connection I217-V                                       | 4        | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4        | 1.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 3        | 1.21%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 1.21%   |
| Realtek 802.11ac NIC                                                   | 3        | 1.21%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 3        | 1.21%   |
| Intel Wi-Fi 6 AX200                                                    | 3        | 1.21%   |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 1.21%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 1.21%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 1.21%   |
| Tenda U12                                                              | 2        | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.81%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 2        | 0.81%   |
| Realtek RTL8187 Wireless Adapter                                       | 2        | 0.81%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 2        | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2        | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2        | 0.81%   |
| Nvidia MCP77 Ethernet                                                  | 2        | 0.81%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2        | 0.81%   |
| Intel Wireless 8260                                                    | 2        | 0.81%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2        | 0.81%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2        | 0.81%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 0.81%   |
| Intel Ethernet Controller I225-V                                       | 2        | 0.81%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 0.81%   |
| Intel 82573L Gigabit Ethernet Controller                               | 2        | 0.81%   |
| Huawei STG-LX1                                                         | 2        | 0.81%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1        | 0.4%    |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 0.4%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 0.4%    |
| TP-Link RTL8812AU Archer T4U 802.11ac                                  | 1        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 30       | 34.88%  |
| Intel                    | 20       | 23.26%  |
| TP-Link                  | 7        | 8.14%   |
| Ralink Technology        | 5        | 5.81%   |
| Qualcomm Atheros         | 5        | 5.81%   |
| Broadcom                 | 4        | 4.65%   |
| NetGear                  | 3        | 3.49%   |
| Tenda                    | 2        | 2.33%   |
| Ralink                   | 2        | 2.33%   |
| MediaTek                 | 2        | 2.33%   |
| Microsoft                | 1        | 1.16%   |
| Mercucys                 | 1        | 1.16%   |
| Marvell Technology Group | 1        | 1.16%   |
| IMC Networks             | 1        | 1.16%   |
| Belkin Components        | 1        | 1.16%   |
| ASUSTek Computer         | 1        | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 7        | 7.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 5        | 5.56%   |
| Intel Wireless 3165                                                                           | 5        | 5.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 4        | 4.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 4        | 4.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 3        | 3.33%   |
| Realtek 802.11ac NIC                                                                          | 3        | 3.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 3.33%   |
| Intel Wi-Fi 6 AX200                                                                           | 3        | 3.33%   |
| Tenda U12                                                                                     | 2        | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 2.22%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 2        | 2.22%   |
| Realtek RTL8187 Wireless Adapter                                                              | 2        | 2.22%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 2        | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 2.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 2.22%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 2        | 2.22%   |
| Intel Wireless 8260                                                                           | 2        | 2.22%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 2        | 2.22%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 2        | 2.22%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 1.11%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                         | 1        | 1.11%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 1.11%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.11%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.11%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 1.11%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 1.11%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 1.11%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 1.11%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 1.11%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.11%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 1.11%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 1.11%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]                | 1        | 1.11%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                                           | 1        | 1.11%   |
| NetGear A6210                                                                                 | 1        | 1.11%   |
| NetGear A6150                                                                                 | 1        | 1.11%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 1        | 1.11%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 85       | 55.92%  |
| Intel                    | 47       | 30.92%  |
| Qualcomm Atheros         | 5        | 3.29%   |
| Nvidia                   | 3        | 1.97%   |
| Broadcom                 | 3        | 1.97%   |
| VIA Technologies         | 2        | 1.32%   |
| Samsung Electronics      | 2        | 1.32%   |
| Huawei Technologies      | 2        | 1.32%   |
| Qualcomm                 | 1        | 0.66%   |
| Marvell Technology Group | 1        | 0.66%   |
| HTC (High Tech Computer) | 1        | 0.66%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 76       | 48.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11       | 6.96%   |
| Intel I211 Gigabit Network Connection                                  | 7        | 4.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 2.53%   |
| Intel Ethernet Connection I217-V                                       | 4        | 2.53%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 1.9%    |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 1.9%    |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 1.9%    |
| Intel 82574L Gigabit Network Connection                                | 3        | 1.9%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 1.27%   |
| Nvidia MCP77 Ethernet                                                  | 2        | 1.27%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 1.27%   |
| Intel Ethernet Controller I225-V                                       | 2        | 1.27%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 1.27%   |
| Intel 82573L Gigabit Ethernet Controller                               | 2        | 1.27%   |
| Huawei STG-LX1                                                         | 2        | 1.27%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1        | 0.63%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 0.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.63%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.63%   |
| Qualcomm MDM9207-MTP _SN:F0565CAE                                      | 1        | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.63%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1        | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 0.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 0.63%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 0.63%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.63%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 0.63%   |
| Intel I210 Gigabit Fiber Network Connection                            | 1        | 0.63%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1        | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 0.63%   |
| Intel Ethernet Connection (17) I219-V                                  | 1        | 0.63%   |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 0.63%   |
| Intel Ethernet Connection (10) I219-V                                  | 1        | 0.63%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 0.63%   |
| Intel 82567V-2 Gigabit Network Connection                              | 1        | 0.63%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 144      | 65.16%  |
| WiFi     | 77       | 34.84%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 111      | 71.61%  |
| WiFi     | 44       | 28.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 95       | 65.07%  |
| 2     | 46       | 31.51%  |
| 3     | 4        | 2.74%   |
| 0     | 1        | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 101      | 68.24%  |
| Yes  | 47       | 31.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 20       | 39.22%  |
| Cambridge Silicon Radio | 12       | 23.53%  |
| Realtek Semiconductor   | 5        | 9.8%    |
| Broadcom                | 5        | 9.8%    |
| Lite-On Technology      | 3        | 5.88%   |
| MediaTek                | 2        | 3.92%   |
| Apple                   | 2        | 3.92%   |
| Dynex                   | 1        | 1.96%   |
| Dell                    | 1        | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 12       | 23.08%  |
| Intel Bluetooth wireless interface                       | 8        | 15.38%  |
| Intel Wireless-AC 3168 Bluetooth                         | 4        | 7.69%   |
| Realtek Bluetooth Radio                                  | 3        | 5.77%   |
| Intel AX200 Bluetooth                                    | 3        | 5.77%   |
| MediaTek Wireless_Device                                 | 2        | 3.85%   |
| Lite-On Bluetooth Device                                 | 2        | 3.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 2        | 3.85%   |
| Intel AX210 Bluetooth                                    | 2        | 3.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2        | 3.85%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1        | 1.92%   |
| Realtek 802.11ac WLAN Adapter                            | 1        | 1.92%   |
| Lite-On Bluetooth Radio                                  | 1        | 1.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1        | 1.92%   |
| Intel AX201 Bluetooth                                    | 1        | 1.92%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 1.92%   |
| Dell BT Mini-Receiver                                    | 1        | 1.92%   |
| Broadcom HP Bluethunder                                  | 1        | 1.92%   |
| Broadcom Bluetooth 3.0 Dongle                            | 1        | 1.92%   |
| Broadcom BCM92045B3 ROM                                  | 1        | 1.92%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 1        | 1.92%   |
| Apple Bluetooth Host Controller                          | 1        | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 88       | 35.34%  |
| Nvidia                               | 70       | 28.11%  |
| AMD                                  | 58       | 23.29%  |
| C-Media Electronics                  | 9        | 3.61%   |
| KTMicro                              | 3        | 1.2%    |
| VIA Technologies                     | 2        | 0.8%    |
| Thesycon Systemsoftware & Consulting | 2        | 0.8%    |
| Logitech                             | 2        | 0.8%    |
| JMTek                                | 2        | 0.8%    |
| Turtle Beach                         | 1        | 0.4%    |
| Texas Instruments                    | 1        | 0.4%    |
| Sony                                 | 1        | 0.4%    |
| SAVITECH                             | 1        | 0.4%    |
| Razer USA                            | 1        | 0.4%    |
| QinHeng Electronics                  | 1        | 0.4%    |
| Plantronics                          | 1        | 0.4%    |
| Native Instruments                   | 1        | 0.4%    |
| Micro Star International             | 1        | 0.4%    |
| GN Netcom                            | 1        | 0.4%    |
| Generalplus Technology               | 1        | 0.4%    |
| Creative Technology                  | 1        | 0.4%    |
| Apple                                | 1        | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 17       | 5.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 14       | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13       | 4.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11       | 3.83%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10       | 3.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10       | 3.48%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 3.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9        | 3.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 2.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 2.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 2.44%   |
| Nvidia High Definition Audio Controller                                    | 6        | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 2.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 2.09%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 1.74%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 1.74%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.39%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 1.39%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 1.39%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4        | 1.39%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.39%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.05%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.05%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 1.05%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 1.05%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 1.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.05%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.05%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.05%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 2        | 0.7%    |
| Thesycon Systemsoftware & Consulting D50s                                  | 2        | 0.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.7%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 2        | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.7%    |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.7%    |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 11       | 17.19%  |
| Samsung Electronics | 10       | 15.63%  |
| Corsair             | 8        | 12.5%   |
| Micron Technology   | 5        | 7.81%   |
| Kingston            | 5        | 7.81%   |
| SK hynix            | 4        | 6.25%   |
| Crucial             | 4        | 6.25%   |
| G.Skill             | 3        | 4.69%   |
| Team                | 2        | 3.13%   |
| GeIL                | 2        | 3.13%   |
| Elpida              | 2        | 3.13%   |
| Unknown (ABCD)      | 1        | 1.56%   |
| Smart               | 1        | 1.56%   |
| Nanya Technology    | 1        | 1.56%   |
| KLEVV               | 1        | 1.56%   |
| CSX                 | 1        | 1.56%   |
| AVEXIR              | 1        | 1.56%   |
| A-DATA Technology   | 1        | 1.56%   |
| Unknown             | 1        | 1.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 2        | 2.9%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 1.45%   |
| Unknown RAM Module 512MB DIMM DDR2 266MT/s                     | 1        | 1.45%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1        | 1.45%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 1.45%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 1        | 1.45%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 1.45%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 1.45%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                       | 1        | 1.45%   |
| Unknown RAM Module 1GB DIMM DDR2 266MT/s                       | 1        | 1.45%   |
| Unknown RAM Module 16MB DIMM 667MT/s                           | 1        | 1.45%   |
| Unknown RAM Module 16GB DIMM DDR4 3200MT/s                     | 1        | 1.45%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                     | 1        | 1.45%   |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s        | 1        | 1.45%   |
| Unknown RAM D4 8G 8GB DIMM DDR4 2666MT/s                       | 1        | 1.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 1.45%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s             | 1        | 1.45%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s             | 1        | 1.45%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s          | 1        | 1.45%   |
| SK hynix RAM Module 8GB DIMM DDR3 1333MT/s                     | 1        | 1.45%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 1.45%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s           | 1        | 1.45%   |
| SK hynix RAM HKNNNFBMAVAR-NEH 2GB Row Of Chips LPDDR4 3200MT/s | 1        | 1.45%   |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s                      | 1        | 1.45%   |
| Samsung RAM Module 4GB DIMM DDR4 2400MT/s                      | 1        | 1.45%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s       | 1        | 1.45%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s          | 1        | 1.45%   |
| Samsung RAM M393B5270DH0-YH9 4GB DIMM DDR3 1333MT/s            | 1        | 1.45%   |
| Samsung RAM M393B2G70DB0-CMA 16GB DIMM DDR3 1867MT/s           | 1        | 1.45%   |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1600MT/s            | 1        | 1.45%   |
| Samsung RAM M393B1G70BH0-YK0 8GB DIMM DDR3 1600MT/s            | 1        | 1.45%   |
| Samsung RAM M378B5673FH0 2GB DIMM DDR3 1333MT/s                | 1        | 1.45%   |
| Samsung RAM M378A5143DB0-CPB 4GB DIMM DDR4 2400MT/s            | 1        | 1.45%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 3200MT/s        | 1        | 1.45%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s              | 1        | 1.45%   |
| Micron RAM DDR4 8GB 2666MHz 8GB DIMM DDR4 2666MT/s             | 1        | 1.45%   |
| Micron RAM 36JSF2G72PZ-1G9E1 16GB DIMM DDR3 1866MT/s           | 1        | 1.45%   |
| Micron RAM 18KSF1G72PZ-1G4E1 8GB DIMM DDR3 1333MT/s            | 1        | 1.45%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s            | 1        | 1.45%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 1        | 1.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 24       | 43.64%  |
| DDR3    | 20       | 36.36%  |
| DDR2    | 4        | 7.27%   |
| Unknown | 3        | 5.45%   |
| SDRAM   | 2        | 3.64%   |
| LPDDR4  | 2        | 3.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 49       | 92.45%  |
| SODIMM       | 3        | 5.66%   |
| Row Of Chips | 1        | 1.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 21       | 33.87%  |
| 4096  | 17       | 27.42%  |
| 16384 | 10       | 16.13%  |
| 2048  | 7        | 11.29%  |
| 1024  | 3        | 4.84%   |
| 32768 | 2        | 3.23%   |
| 512   | 1        | 1.61%   |
| 16    | 1        | 1.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 12       | 20%     |
| 1333  | 8        | 13.33%  |
| 3600  | 5        | 8.33%   |
| 3200  | 5        | 8.33%   |
| 2667  | 5        | 8.33%   |
| 2400  | 5        | 8.33%   |
| 2133  | 3        | 5%      |
| 1866  | 3        | 5%      |
| 667   | 3        | 5%      |
| 3733  | 2        | 3.33%   |
| 3533  | 1        | 1.67%   |
| 2666  | 1        | 1.67%   |
| 1867  | 1        | 1.67%   |
| 1800  | 1        | 1.67%   |
| 1334  | 1        | 1.67%   |
| 1066  | 1        | 1.67%   |
| 800   | 1        | 1.67%   |
| 533   | 1        | 1.67%   |
| 266   | 1        | 1.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 40%     |
| Seiko Epson        | 1        | 20%     |
| Konica Minolta     | 1        | 20%     |
| Brother Industries | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson ET-2820 Series | 1        | 20%     |
| Konica Minolta 185         | 1        | 20%     |
| HP OfficeJet Pro 8730      | 1        | 20%     |
| HP DeskJet 2130 series     | 1        | 20%     |
| Brother MFC-L2685DW        | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 8        | 30.77%  |
| Sunplus Innovation Technology | 3        | 11.54%  |
| Huawei Technologies           | 2        | 7.69%   |
| Creative Technology           | 2        | 7.69%   |
| Z-Star Microelectronics       | 1        | 3.85%   |
| Samsung Electronics           | 1        | 3.85%   |
| Razer USA                     | 1        | 3.85%   |
| Pixart Imaging                | 1        | 3.85%   |
| OmniVision Technologies       | 1        | 3.85%   |
| Microsoft                     | 1        | 3.85%   |
| MacroSilicon                  | 1        | 3.85%   |
| Chicony Electronics           | 1        | 3.85%   |
| ARC International             | 1        | 3.85%   |
| Apple                         | 1        | 3.85%   |
| Alcor Micro                   | 1        | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Sunplus FHD Camera Microphone                  | 2        | 7.69%   |
| Logitech Webcam C270                           | 2        | 7.69%   |
| Huawei HiCamera                                | 2        | 7.69%   |
| Z-Star Venus USB2.0 Camera                     | 1        | 3.85%   |
| Sunplus Webcam                                 | 1        | 3.85%   |
| Samsung Galaxy series, misc. (MTP mode)        | 1        | 3.85%   |
| Razer USA Gaming Webcam [Kiyo]                 | 1        | 3.85%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro           | 1        | 3.85%   |
| OmniVision Integrated Webcam for Dell XPS 2010 | 1        | 3.85%   |
| Microsoft LifeCam HD-3000                      | 1        | 3.85%   |
| MacroSilicon USB3. 0 capture                   | 1        | 3.85%   |
| Logitech Webcam C925e                          | 1        | 3.85%   |
| Logitech Webcam C210                           | 1        | 3.85%   |
| Logitech Webcam B500                           | 1        | 3.85%   |
| Logitech StreamCam                             | 1        | 3.85%   |
| Logitech QuickCam Communicate Deluxe/S7500     | 1        | 3.85%   |
| Logitech Logi Webcam C920e                     | 1        | 3.85%   |
| Creative VF0610 Live! Cam Socialize HD         | 1        | 3.85%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 3.85%   |
| Chicony HP High Definition 1MP Webcam          | 1        | 3.85%   |
| ARC International Camera                       | 1        | 3.85%   |
| Apple iSight in LED Cinema Display             | 1        | 3.85%   |
| Alcor Micro USB 5.0M AF Camera                 | 1        | 3.85%   |

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
| 0     | 108      | 71.52%  |
| 1     | 39       | 25.83%  |
| 2     | 4        | 2.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 20       | 41.67%  |
| Graphics card            | 19       | 39.58%  |
| Multimedia controller    | 3        | 6.25%   |
| Communication controller | 2        | 4.17%   |
| Unassigned class         | 1        | 2.08%   |
| Storage/raid             | 1        | 2.08%   |
| Sound                    | 1        | 2.08%   |
| Camera                   | 1        | 2.08%   |

