LMDE - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for LMDE.

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

Total: 562

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | B75MA-P45                   | [bfe1423965](https://linux-hardware.org/?probe=bfe1423965) | Nov 06, 2023 |
| Gigabyte      | Q87M-D2H                    | [62a888f71c](https://linux-hardware.org/?probe=62a888f71c) | Nov 05, 2023 |
| Medion        | TJ4125                      | [65a059325e](https://linux-hardware.org/?probe=65a059325e) | Nov 05, 2023 |
| Gigabyte      | MZBSWAP-K4                  | [ef6c15830d](https://linux-hardware.org/?probe=ef6c15830d) | Nov 05, 2023 |
| ASUSTek       | P5G41T-M LX                 | [ae6c835796](https://linux-hardware.org/?probe=ae6c835796) | Nov 02, 2023 |
| ASRock        | Z97 Pro4                    | [6fa2a70f99](https://linux-hardware.org/?probe=6fa2a70f99) | Nov 01, 2023 |
| HP            | 18EB                        | [83596ab9d9](https://linux-hardware.org/?probe=83596ab9d9) | Oct 31, 2023 |
| ASUSTek       | P5G41T-M LX                 | [e741e073e0](https://linux-hardware.org/?probe=e741e073e0) | Oct 30, 2023 |
| ASRock        | Z690M-ITX/ax                | [810297d46b](https://linux-hardware.org/?probe=810297d46b) | Oct 30, 2023 |
| Gigabyte      | MZBSWAP-K4                  | [aed94a16c1](https://linux-hardware.org/?probe=aed94a16c1) | Oct 30, 2023 |
| Trigkey       | Green G4 10                 | [bb72f6af02](https://linux-hardware.org/?probe=bb72f6af02) | Oct 29, 2023 |
| Medion        | TJ4125                      | [f791cf88cb](https://linux-hardware.org/?probe=f791cf88cb) | Oct 27, 2023 |
| Dell          | 0HH807                      | [7f15d65c22](https://linux-hardware.org/?probe=7f15d65c22) | Oct 27, 2023 |
| Unknown       | P4M800CE-8237               | [bf22b887f8](https://linux-hardware.org/?probe=bf22b887f8) | Oct 26, 2023 |
| ASRock        | Z97 Pro4                    | [bcf737a9cd](https://linux-hardware.org/?probe=bcf737a9cd) | Oct 25, 2023 |
| Gigabyte      | Q87M-D2H                    | [74d5de2172](https://linux-hardware.org/?probe=74d5de2172) | Oct 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [4f2229b9fa](https://linux-hardware.org/?probe=4f2229b9fa) | Oct 21, 2023 |
| Gigabyte      | Q87M-D2H                    | [4633508fb0](https://linux-hardware.org/?probe=4633508fb0) | Oct 20, 2023 |
| Acer          | Predator G3-605             | [d3b59b34a0](https://linux-hardware.org/?probe=d3b59b34a0) | Oct 19, 2023 |
| Intel         | DG31PR AAD97573-206         | [5064906065](https://linux-hardware.org/?probe=5064906065) | Oct 18, 2023 |
| HP            | 843B                        | [0e5a69e3ab](https://linux-hardware.org/?probe=0e5a69e3ab) | Oct 17, 2023 |
| ASRock        | H310M-STX                   | [b0bc91de7a](https://linux-hardware.org/?probe=b0bc91de7a) | Oct 14, 2023 |
| Medion        | TJ4125                      | [e60adf45ac](https://linux-hardware.org/?probe=e60adf45ac) | Oct 10, 2023 |
| Gigabyte      | A520M S2H                   | [d71ced0f1d](https://linux-hardware.org/?probe=d71ced0f1d) | Oct 08, 2023 |
| Dell          | 0WR7PY A03                  | [7bd89c0f18](https://linux-hardware.org/?probe=7bd89c0f18) | Oct 07, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | [04473f37e9](https://linux-hardware.org/?probe=04473f37e9) | Oct 07, 2023 |
| Gigabyte      | G31M-ES2L                   | [bfed98df15](https://linux-hardware.org/?probe=bfed98df15) | Oct 04, 2023 |
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
| Gigabyte      | GA-880GM-UD2H               | [5fa6a632ae](https://linux-hardware.org/?probe=5fa6a632ae) | Sep 18, 2023 |
| HP            | 158B                        | [d56ff45f03](https://linux-hardware.org/?probe=d56ff45f03) | Sep 17, 2023 |
| ASRock        | X670E Pro RS                | [11d9d55772](https://linux-hardware.org/?probe=11d9d55772) | Sep 17, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [807a40b618](https://linux-hardware.org/?probe=807a40b618) | Sep 15, 2023 |
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
| ASUSTek       | H81M-K                      | [d946977ec8](https://linux-hardware.org/?probe=d946977ec8) | Aug 04, 2023 |
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
| ASUSTek       | A8N-E                       | [2baf5b889b](https://linux-hardware.org/?probe=2baf5b889b) | May 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bf6e9cf4d0](https://linux-hardware.org/?probe=bf6e9cf4d0) | May 26, 2023 |
| Gigabyte      | Q87M-D2H                    | [a3e5c89fe6](https://linux-hardware.org/?probe=a3e5c89fe6) | May 25, 2023 |
| Gigabyte      | Q87M-D2H                    | [3c82eec4d2](https://linux-hardware.org/?probe=3c82eec4d2) | May 23, 2023 |
| Gigabyte      | Q87M-D2H                    | [ee4eca623f](https://linux-hardware.org/?probe=ee4eca623f) | May 21, 2023 |
| MSI           | B350M BAZOOKA               | [49e536226c](https://linux-hardware.org/?probe=49e536226c) | May 19, 2023 |
| MSI           | B350M BAZOOKA               | [2abefd21ea](https://linux-hardware.org/?probe=2abefd21ea) | May 19, 2023 |
| Alienware     | 04VWF2 A00                  | [311799f80a](https://linux-hardware.org/?probe=311799f80a) | May 18, 2023 |
| Packard Be... | PT890-8237A                 | [b15e7cc105](https://linux-hardware.org/?probe=b15e7cc105) | May 18, 2023 |
| Gigabyte      | E2100N                      | [cce0e87f11](https://linux-hardware.org/?probe=cce0e87f11) | May 17, 2023 |
| Pegatron      | VIOLET                      | [197ec890d6](https://linux-hardware.org/?probe=197ec890d6) | May 16, 2023 |
| Pegatron      | VIOLET                      | [fa6dc417d4](https://linux-hardware.org/?probe=fa6dc417d4) | May 16, 2023 |
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
| Gigabyte      | X570 AORUS MASTER           | [2d26056501](https://linux-hardware.org/?probe=2d26056501) | Feb 13, 2023 |
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
| ASRock        | G41M-S3                     | [2cdcaebd43](https://linux-hardware.org/?probe=2cdcaebd43) | Sep 10, 2022 |
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
| ASUSTek       | P5B                         | [149ab02b84](https://linux-hardware.org/?probe=149ab02b84) | Jul 06, 2022 |
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
| ASUSTek       | P5QL PRO                    | [9ea782b1d2](https://linux-hardware.org/?probe=9ea782b1d2) | May 08, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP            | 158B                        | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| HP            | 339A                        | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Gigabyte      | H110M-S2H-CF                | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| ASUSTek       | PRIME H610M-A D4            | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| Dell          | 0XR1GT A00                  | [2a3b9ad6cf](https://linux-hardware.org/?probe=2a3b9ad6cf) | Apr 24, 2022 |
| ASRock        | A320M-DGS                   | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| Foxconn       | Cinema Series FAB           | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [eb751efc1f](https://linux-hardware.org/?probe=eb751efc1f) | Apr 09, 2022 |
| Acer          | WG43M                       | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| ASUSTek       | P6T                         | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| Acer          | EG43M                       | [28b4dd5236](https://linux-hardware.org/?probe=28b4dd5236) | Mar 31, 2022 |
| ASUSTek       | PRIME H510M-D               | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [346857be22](https://linux-hardware.org/?probe=346857be22) | Mar 24, 2022 |
| ASUSTek       | P4P800                      | [0cb6a89491](https://linux-hardware.org/?probe=0cb6a89491) | Mar 19, 2022 |
| HP            | 0AA8h                       | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| HP            | 0AE8h C                     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Dell          | 0HR330                      | [3533cd70af](https://linux-hardware.org/?probe=3533cd70af) | Feb 26, 2022 |
| Dell          | 0HR330                      | [e587783731](https://linux-hardware.org/?probe=e587783731) | Feb 26, 2022 |
| HP            | 0AA8h                       | [21de71cf71](https://linux-hardware.org/?probe=21de71cf71) | Feb 25, 2022 |
| Gigabyte      | Z77-D3H                     | [a0d52488b2](https://linux-hardware.org/?probe=a0d52488b2) | Feb 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [0731118682](https://linux-hardware.org/?probe=0731118682) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [5026ea812a](https://linux-hardware.org/?probe=5026ea812a) | Feb 15, 2022 |
| Dell          | 0Y2K8N A01                  | [e3922aecf0](https://linux-hardware.org/?probe=e3922aecf0) | Feb 04, 2022 |
| EVGA          | 131-HE-E095                 | [6d45d47131](https://linux-hardware.org/?probe=6d45d47131) | Jan 31, 2022 |
| ASUSTek       | A68HM-K                     | [00cd805015](https://linux-hardware.org/?probe=00cd805015) | Jan 23, 2022 |
| MSI           | Z97 PC Mate                 | [be068c5a3a](https://linux-hardware.org/?probe=be068c5a3a) | Jan 21, 2022 |
| Dell          | 0XR1GT A00                  | [a988797ac9](https://linux-hardware.org/?probe=a988797ac9) | Jan 16, 2022 |
| eMachines     | EMCP73VT-PM                 | [1d55cceee4](https://linux-hardware.org/?probe=1d55cceee4) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | [43b421ad06](https://linux-hardware.org/?probe=43b421ad06) | Jan 08, 2022 |
| ASRock        | N68-S3 UCC                  | [bfcf287c09](https://linux-hardware.org/?probe=bfcf287c09) | Jan 08, 2022 |
| OEM           | Unknown                     | [6adc4b5659](https://linux-hardware.org/?probe=6adc4b5659) | Jan 01, 2022 |
| Unknown       | K7VM2                       | [06f13210ad](https://linux-hardware.org/?probe=06f13210ad) | Dec 29, 2021 |
| Unknown       | K7VM2                       | [be785b672c](https://linux-hardware.org/?probe=be785b672c) | Dec 29, 2021 |
| HP            | 2AE3                        | [fb02077f16](https://linux-hardware.org/?probe=fb02077f16) | Dec 14, 2021 |
| HP            | 2AE3                        | [18efa559b9](https://linux-hardware.org/?probe=18efa559b9) | Dec 14, 2021 |
| ECS           | G41T-M7                     | [5a8641a9aa](https://linux-hardware.org/?probe=5a8641a9aa) | Dec 13, 2021 |
| Acer          | RS880M05                    | [2ce9c25975](https://linux-hardware.org/?probe=2ce9c25975) | Nov 25, 2021 |
| NEC Comput... | GA-8I945PM                  | [3d3711b8cc](https://linux-hardware.org/?probe=3d3711b8cc) | Nov 22, 2021 |
| ASUSTek       | A68HM-K                     | [b4b709eb1b](https://linux-hardware.org/?probe=b4b709eb1b) | Nov 18, 2021 |
| ASUSTek       | A68HM-K                     | [18236d5a16](https://linux-hardware.org/?probe=18236d5a16) | Nov 18, 2021 |
| Intel         | H61                         | [51f383b050](https://linux-hardware.org/?probe=51f383b050) | Nov 04, 2021 |
| HP            | 843C                        | [e7df8fecdd](https://linux-hardware.org/?probe=e7df8fecdd) | Oct 30, 2021 |
| ASUSTek       | P7F-M                       | [f0983027ee](https://linux-hardware.org/?probe=f0983027ee) | Oct 26, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | [48187accde](https://linux-hardware.org/?probe=48187accde) | Oct 21, 2021 |
| ASUSTek       | Z97-K                       | [f1fcb9d1db](https://linux-hardware.org/?probe=f1fcb9d1db) | Oct 17, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | [a1820d8f0c](https://linux-hardware.org/?probe=a1820d8f0c) | Oct 17, 2021 |
| Gigabyte      | H61M-D2-B3                  | [138df954cb](https://linux-hardware.org/?probe=138df954cb) | Oct 15, 2021 |
| Gigabyte      | H61M-D2-B3                  | [dabe5d459a](https://linux-hardware.org/?probe=dabe5d459a) | Oct 15, 2021 |
| ASUSTek       | Z97-K                       | [940a27249a](https://linux-hardware.org/?probe=940a27249a) | Oct 12, 2021 |
| ASUSTek       | Z97-K                       | [012056e32d](https://linux-hardware.org/?probe=012056e32d) | Sep 28, 2021 |
| Biostar       | G41D3C                      | [16eb676e0c](https://linux-hardware.org/?probe=16eb676e0c) | Sep 25, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [9c0ade7c9c](https://linux-hardware.org/?probe=9c0ade7c9c) | Sep 20, 2021 |
| ASUSTek       | P5VD2-VM                    | [9eec34a3f2](https://linux-hardware.org/?probe=9eec34a3f2) | Sep 13, 2021 |
| Foxconn       | 945 7MC Series              | [623cb095f2](https://linux-hardware.org/?probe=623cb095f2) | Sep 12, 2021 |
| Pegatron      | 2AB5                        | [3c335b37fa](https://linux-hardware.org/?probe=3c335b37fa) | Sep 10, 2021 |
| ASUSTek       | UN62                        | [0702f80222](https://linux-hardware.org/?probe=0702f80222) | Sep 09, 2021 |
| ASUSTek       | P5VD2-VM                    | [305d566f57](https://linux-hardware.org/?probe=305d566f57) | Sep 07, 2021 |
| Gigabyte      | H61M-S1                     | [d1773b3e3d](https://linux-hardware.org/?probe=d1773b3e3d) | Sep 06, 2021 |
| Gigabyte      | H61M-S1                     | [5d2cc7f4ca](https://linux-hardware.org/?probe=5d2cc7f4ca) | Sep 06, 2021 |
| Intel         | DG31PR AAD97573-302         | [7122e4bd16](https://linux-hardware.org/?probe=7122e4bd16) | Sep 04, 2021 |
| Gigabyte      | M52LT-D3P                   | [09cbb5b50e](https://linux-hardware.org/?probe=09cbb5b50e) | Sep 03, 2021 |
| Gigabyte      | M52LT-D3P                   | [949b2062ea](https://linux-hardware.org/?probe=949b2062ea) | Sep 03, 2021 |
| ASRock        | G41M-S3                     | [c34caa75e2](https://linux-hardware.org/?probe=c34caa75e2) | Aug 23, 2021 |
| MSI           | MS-7142                     | [2700c74bd9](https://linux-hardware.org/?probe=2700c74bd9) | Aug 21, 2021 |
| MSI           | MS-7142                     | [18ae0c1bb3](https://linux-hardware.org/?probe=18ae0c1bb3) | Aug 21, 2021 |
| HP            | 0AA8h                       | [d9a8fd3722](https://linux-hardware.org/?probe=d9a8fd3722) | Aug 15, 2021 |
| ASUSTek       | A7N8X-LA                    | [0e9fd81caf](https://linux-hardware.org/?probe=0e9fd81caf) | Aug 11, 2021 |
| ASUSTek       | A7N8X-LA                    | [f14c99bbce](https://linux-hardware.org/?probe=f14c99bbce) | Aug 11, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [b937ce5e88](https://linux-hardware.org/?probe=b937ce5e88) | Aug 10, 2021 |
| ASUSTek       | P7F-M                       | [cff87306ab](https://linux-hardware.org/?probe=cff87306ab) | Aug 07, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | [a1768aa578](https://linux-hardware.org/?probe=a1768aa578) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | [52aa712b0c](https://linux-hardware.org/?probe=52aa712b0c) | Aug 05, 2021 |
| ASUSTek       | PRIME Z370-A                | [05c1703574](https://linux-hardware.org/?probe=05c1703574) | Aug 03, 2021 |
| ASUSTek       | PRIME Z370-A                | [faf304d157](https://linux-hardware.org/?probe=faf304d157) | Aug 02, 2021 |
| OEM           | 45CMX/45GMX/45CMX-K         | [65d8eb687e](https://linux-hardware.org/?probe=65d8eb687e) | Jul 30, 2021 |
| ASUSTek       | P7F-M                       | [33a6186148](https://linux-hardware.org/?probe=33a6186148) | Jul 30, 2021 |
| Intel         | BTC-T37                     | [bb5051b598](https://linux-hardware.org/?probe=bb5051b598) | Jul 27, 2021 |
| ASRock        | FM2A85X Extreme4-M          | [aa0030f094](https://linux-hardware.org/?probe=aa0030f094) | Jul 26, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [763cb39ac0](https://linux-hardware.org/?probe=763cb39ac0) | Jul 25, 2021 |
| Gigabyte      | X570 AORUS PRO              | [932c4de6ce](https://linux-hardware.org/?probe=932c4de6ce) | Jul 18, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [39037104b7](https://linux-hardware.org/?probe=39037104b7) | Jul 17, 2021 |
| Dell          | 08HPGT A01                  | [64d562d6ef](https://linux-hardware.org/?probe=64d562d6ef) | Jul 16, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [a82245240b](https://linux-hardware.org/?probe=a82245240b) | Jul 15, 2021 |
| ASUSTek       | P7F-M                       | [3007b813c6](https://linux-hardware.org/?probe=3007b813c6) | Jul 13, 2021 |
| ASUSTek       | P7F-M                       | [5cfa1dcb4f](https://linux-hardware.org/?probe=5cfa1dcb4f) | Jul 12, 2021 |
| MSI           | H81M-E34                    | [14c2f8a49d](https://linux-hardware.org/?probe=14c2f8a49d) | Jul 05, 2021 |
| MSI           | A320M-A PRO                 | [9d356e787a](https://linux-hardware.org/?probe=9d356e787a) | Jul 01, 2021 |
| HP            | 0A98h                       | [40990f73a5](https://linux-hardware.org/?probe=40990f73a5) | Jun 22, 2021 |
| HP            | 0AA8h                       | [43103b39a5](https://linux-hardware.org/?probe=43103b39a5) | Jun 17, 2021 |
| HP            | 0AA8h                       | [9154911bc9](https://linux-hardware.org/?probe=9154911bc9) | Jun 13, 2021 |
| ASUSTek       | Maximus VI HERO             | [699d10613e](https://linux-hardware.org/?probe=699d10613e) | Jun 11, 2021 |
| Unknown       | Unknown                     | [3e408e9ead](https://linux-hardware.org/?probe=3e408e9ead) | May 31, 2021 |
| Unknown       | Unknown                     | [39b2780acf](https://linux-hardware.org/?probe=39b2780acf) | May 31, 2021 |
| Dell          | 0HY9JP A01                  | [3f6ddbd81d](https://linux-hardware.org/?probe=3f6ddbd81d) | May 30, 2021 |
| ASUSTek       | H61M-A/BR                   | [7d2b37e6e1](https://linux-hardware.org/?probe=7d2b37e6e1) | May 29, 2021 |
| ASRock        | G41M-S3                     | [adc801308b](https://linux-hardware.org/?probe=adc801308b) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | [d03d2796a0](https://linux-hardware.org/?probe=d03d2796a0) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | [200072e2a7](https://linux-hardware.org/?probe=200072e2a7) | May 29, 2021 |
| ASRock        | G41M-S3                     | [47f6c3e962](https://linux-hardware.org/?probe=47f6c3e962) | May 28, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | [cd3697bd15](https://linux-hardware.org/?probe=cd3697bd15) | May 25, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | [7c520b0d6e](https://linux-hardware.org/?probe=7c520b0d6e) | May 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [55d981b2ed](https://linux-hardware.org/?probe=55d981b2ed) | May 23, 2021 |
| Intel         | H61                         | [1954634de4](https://linux-hardware.org/?probe=1954634de4) | May 22, 2021 |
| Foxconn       | 945 7MC Series              | [f4634ec470](https://linux-hardware.org/?probe=f4634ec470) | May 17, 2021 |
| Dell          | 0FM586 A00                  | [8a955d2c5a](https://linux-hardware.org/?probe=8a955d2c5a) | May 16, 2021 |
| ASUSTek       | B150M-A                     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| Dell          | 0XR1GT A00                  | [a502e8842e](https://linux-hardware.org/?probe=a502e8842e) | May 12, 2021 |
| ASUSTek       | V-P7H55E                    | [3c0a297ede](https://linux-hardware.org/?probe=3c0a297ede) | May 08, 2021 |
| ASUSTek       | Crosshair V Formula         | [0fd87c485e](https://linux-hardware.org/?probe=0fd87c485e) | May 07, 2021 |
| ASUSTek       | P5KC                        | [80549acbba](https://linux-hardware.org/?probe=80549acbba) | May 03, 2021 |
| ASUSTek       | P5KC                        | [f2313ee72b](https://linux-hardware.org/?probe=f2313ee72b) | May 03, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [46b0bab7d8](https://linux-hardware.org/?probe=46b0bab7d8) | Apr 27, 2021 |
| Unknown       | Phitronics N68C-M           | [3076a5bae3](https://linux-hardware.org/?probe=3076a5bae3) | Apr 24, 2021 |
| Unknown       | Phitronics N68C-M           | [d3a56832d9](https://linux-hardware.org/?probe=d3a56832d9) | Apr 23, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [761a9ce0e9](https://linux-hardware.org/?probe=761a9ce0e9) | Apr 21, 2021 |
| ASUSTek       | P5Q DELUXE                  | [8ab143ec6b](https://linux-hardware.org/?probe=8ab143ec6b) | Apr 20, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [2813977a91](https://linux-hardware.org/?probe=2813977a91) | Apr 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [d6c3daff43](https://linux-hardware.org/?probe=d6c3daff43) | Apr 19, 2021 |
| ASUSTek       | V-P7H55E                    | [fb3b69b074](https://linux-hardware.org/?probe=fb3b69b074) | Apr 18, 2021 |
| Gigabyte      | M68MT-S2P                   | [47deff8a39](https://linux-hardware.org/?probe=47deff8a39) | Apr 17, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [16d03cb92f](https://linux-hardware.org/?probe=16d03cb92f) | Apr 12, 2021 |
| Dell          | 0KP561                      | [3579bff9c4](https://linux-hardware.org/?probe=3579bff9c4) | Apr 08, 2021 |
| DFI           | LP BI P45-T2S Elite         | [01f0babd70](https://linux-hardware.org/?probe=01f0babd70) | Apr 08, 2021 |
| ASUSTek       | PRIME Z390-P                | [055066b50a](https://linux-hardware.org/?probe=055066b50a) | Apr 08, 2021 |
| ASUSTek       | P5KC                        | [b687d3a64f](https://linux-hardware.org/?probe=b687d3a64f) | Apr 06, 2021 |
| Pegatron      | 2ADC                        | [e4bfddb8d9](https://linux-hardware.org/?probe=e4bfddb8d9) | Apr 04, 2021 |
| MSI           | MS-7267                     | [d16e8a4364](https://linux-hardware.org/?probe=d16e8a4364) | Apr 03, 2021 |
| Intel         | H61                         | [d7c3f87e52](https://linux-hardware.org/?probe=d7c3f87e52) | Mar 26, 2021 |
| Gigabyte      | Z77-D3H                     | [6ab1c423db](https://linux-hardware.org/?probe=6ab1c423db) | Mar 25, 2021 |
| MSI           | Z77A-GD65                   | [a9c3672597](https://linux-hardware.org/?probe=a9c3672597) | Mar 25, 2021 |
| ASUSTek       | M5A97 PRO                   | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| MSI           | MS-6785                     | [303c1ac636](https://linux-hardware.org/?probe=303c1ac636) | Mar 17, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | [f8503ecc3b](https://linux-hardware.org/?probe=f8503ecc3b) | Mar 10, 2021 |
| ECS           | A740GM-M                    | [442aa41981](https://linux-hardware.org/?probe=442aa41981) | Mar 08, 2021 |
| ASUSTek       | P7F-M                       | [a8d2e4fa56](https://linux-hardware.org/?probe=a8d2e4fa56) | Mar 07, 2021 |
| MSI           | B450M PRO-VDH MAX           | [79e6e8bbfc](https://linux-hardware.org/?probe=79e6e8bbfc) | Mar 06, 2021 |
| ASRock        | G31M-GS                     | [ea6fbcd94e](https://linux-hardware.org/?probe=ea6fbcd94e) | Mar 02, 2021 |
| Acer          | EG43LMK                     | [249967a21a](https://linux-hardware.org/?probe=249967a21a) | Feb 28, 2021 |
| ASRock        | A320M-HDV R4.0              | [527b138b70](https://linux-hardware.org/?probe=527b138b70) | Feb 22, 2021 |
| Acer          | EG43LMK                     | [1c1fdf43c0](https://linux-hardware.org/?probe=1c1fdf43c0) | Feb 17, 2021 |
| MSI           | MS-7267                     | [6bf114a22f](https://linux-hardware.org/?probe=6bf114a22f) | Feb 15, 2021 |
| MSI           | MS-7267                     | [78e4d03c89](https://linux-hardware.org/?probe=78e4d03c89) | Feb 15, 2021 |
| Intel         | DP55WB AAE64798-206         | [4b2befb0d2](https://linux-hardware.org/?probe=4b2befb0d2) | Feb 14, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c8e67a7d41](https://linux-hardware.org/?probe=c8e67a7d41) | Feb 07, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [6e605fd64d](https://linux-hardware.org/?probe=6e605fd64d) | Feb 06, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [ec667e7b35](https://linux-hardware.org/?probe=ec667e7b35) | Feb 05, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [b71d20e5de](https://linux-hardware.org/?probe=b71d20e5de) | Feb 05, 2021 |
| ASUSTek       | Z97-K                       | [3adb6d9dc1](https://linux-hardware.org/?probe=3adb6d9dc1) | Feb 05, 2021 |
| ASRock        | X570 Taichi                 | [9f77a9eea6](https://linux-hardware.org/?probe=9f77a9eea6) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | [9b6ea4cda5](https://linux-hardware.org/?probe=9b6ea4cda5) | Feb 04, 2021 |
| ASRock        | H61M-HVS                    | [05c23c4247](https://linux-hardware.org/?probe=05c23c4247) | Feb 02, 2021 |
| ASRock        | H61M-HVS                    | [8c45cfc073](https://linux-hardware.org/?probe=8c45cfc073) | Feb 02, 2021 |
| ASUSTek       | P5E3 Deluxe                 | [47324765ec](https://linux-hardware.org/?probe=47324765ec) | Feb 02, 2021 |
| Unknown       | Unknown                     | [94d77e9dd0](https://linux-hardware.org/?probe=94d77e9dd0) | Feb 02, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [9761a3446c](https://linux-hardware.org/?probe=9761a3446c) | Jan 30, 2021 |
| Dell          | 03NVJ6 A02                  | [9c930ede42](https://linux-hardware.org/?probe=9c930ede42) | Jan 28, 2021 |
| MSI           | B450M-A PRO MAX             | [e5bc80f882](https://linux-hardware.org/?probe=e5bc80f882) | Jan 26, 2021 |
| Dell          | 0TT708 A01                  | [d04b2d493f](https://linux-hardware.org/?probe=d04b2d493f) | Jan 20, 2021 |
| Dell          | 0TT708 A01                  | [08ac15e868](https://linux-hardware.org/?probe=08ac15e868) | Jan 15, 2021 |
| Dell          | 0TT708 A01                  | [d0da7a44f7](https://linux-hardware.org/?probe=d0da7a44f7) | Jan 14, 2021 |
| Alienware     | 06G6JW A00                  | [992089d02a](https://linux-hardware.org/?probe=992089d02a) | Jan 12, 2021 |
| Intel         | DP55WB AAE64798-206         | [51ec8a1510](https://linux-hardware.org/?probe=51ec8a1510) | Jan 06, 2021 |
| ASUSTek       | P5K                         | [22a568db8e](https://linux-hardware.org/?probe=22a568db8e) | Jan 02, 2021 |
| ASUSTek       | P5K                         | [4233bd7b15](https://linux-hardware.org/?probe=4233bd7b15) | Jan 02, 2021 |
| MSI           | MS-6570                     | [f6bdec1638](https://linux-hardware.org/?probe=f6bdec1638) | Dec 28, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8396553751](https://linux-hardware.org/?probe=8396553751) | Dec 26, 2020 |
| MSI           | Z87 MPOWER MAX              | [5db0b2dedf](https://linux-hardware.org/?probe=5db0b2dedf) | Dec 23, 2020 |
| MSI           | MS-7541                     | [a6e134920c](https://linux-hardware.org/?probe=a6e134920c) | Dec 22, 2020 |
| MSI           | MS-7541                     | [a44769cfd2](https://linux-hardware.org/?probe=a44769cfd2) | Dec 22, 2020 |
| ASUSTek       | Maximus VI HERO             | [862b159eb2](https://linux-hardware.org/?probe=862b159eb2) | Dec 19, 2020 |
| Toshiba       | STI 910123                  | [f9f7a69232](https://linux-hardware.org/?probe=f9f7a69232) | Dec 18, 2020 |
| Toshiba       | STI 910123                  | [ae79e069f3](https://linux-hardware.org/?probe=ae79e069f3) | Dec 18, 2020 |
| ASUSTek       | B150 PRO GAMING/AURA        | [fdc26c9f6d](https://linux-hardware.org/?probe=fdc26c9f6d) | Dec 18, 2020 |
| ASUSTek       | P8B75-V                     | [edb814f54a](https://linux-hardware.org/?probe=edb814f54a) | Dec 15, 2020 |
| ASUSTek       | Z97-K                       | [5b78a6b7ee](https://linux-hardware.org/?probe=5b78a6b7ee) | Dec 13, 2020 |
| ASUSTek       | Z97-K                       | [e1afb118e5](https://linux-hardware.org/?probe=e1afb118e5) | Dec 12, 2020 |
| Acer          | Aspire XC600 v1.0           | [5a3c92338e](https://linux-hardware.org/?probe=5a3c92338e) | Dec 08, 2020 |
| EVGA          | 131-HE-E095                 | [8fca80343b](https://linux-hardware.org/?probe=8fca80343b) | Dec 08, 2020 |
| HP            | 1496                        | [61eeea25ed](https://linux-hardware.org/?probe=61eeea25ed) | Dec 04, 2020 |
| Dell          | 0XPDFK A01                  | [02ffa180c8](https://linux-hardware.org/?probe=02ffa180c8) | Nov 30, 2020 |
| ASRock        | X370 Taichi                 | [a229c68d0e](https://linux-hardware.org/?probe=a229c68d0e) | Nov 27, 2020 |
| Gigabyte      | 945GM-S2                    | [1bbf0f874b](https://linux-hardware.org/?probe=1bbf0f874b) | Nov 26, 2020 |
| MSI           | B85M-G43                    | [dee4fcacb7](https://linux-hardware.org/?probe=dee4fcacb7) | Nov 26, 2020 |
| Gigabyte      | H81M-S2PV                   | [1c5cc4c12e](https://linux-hardware.org/?probe=1c5cc4c12e) | Nov 25, 2020 |
| Dell          | 0F6X5P A00                  | [458d498ed4](https://linux-hardware.org/?probe=458d498ed4) | Nov 24, 2020 |
| ASUSTek       | M4A785TD-V EVO              | [c03bf04e1e](https://linux-hardware.org/?probe=c03bf04e1e) | Nov 15, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [2fe3e165eb](https://linux-hardware.org/?probe=2fe3e165eb) | Oct 31, 2020 |
| Dell          | 0DR845                      | [958876c9d6](https://linux-hardware.org/?probe=958876c9d6) | Oct 27, 2020 |
| HP            | 843B                        | [cf9214c9e8](https://linux-hardware.org/?probe=cf9214c9e8) | Oct 25, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [c637e2732a](https://linux-hardware.org/?probe=c637e2732a) | Oct 22, 2020 |
| Gigabyte      | G33M-S2                     | [d5b1adf1cc](https://linux-hardware.org/?probe=d5b1adf1cc) | Oct 21, 2020 |
| MSI           | Z97 GAMING 3                | [d70dc5679f](https://linux-hardware.org/?probe=d70dc5679f) | Oct 15, 2020 |
| ASUSTek       | P7F-M                       | [a931f70b33](https://linux-hardware.org/?probe=a931f70b33) | Oct 14, 2020 |
| HP            | 304Ah                       | [720e05d59c](https://linux-hardware.org/?probe=720e05d59c) | Oct 04, 2020 |
| HP            | 304Ah                       | [e8bf5f6700](https://linux-hardware.org/?probe=e8bf5f6700) | Oct 04, 2020 |
| HP            | 304Ah                       | [11dc9e4238](https://linux-hardware.org/?probe=11dc9e4238) | Sep 28, 2020 |
| ASUSTek       | P8H61-MX USB3               | [2def8c0128](https://linux-hardware.org/?probe=2def8c0128) | Sep 19, 2020 |
| ASUSTek       | P5E3 Deluxe                 | [694576f25f](https://linux-hardware.org/?probe=694576f25f) | Sep 14, 2020 |
| ASUSTek       | B150 PRO GAMING/AURA        | [e5260021d2](https://linux-hardware.org/?probe=e5260021d2) | Sep 06, 2020 |
| Dell          | 0DR845                      | [f9dfefaf63](https://linux-hardware.org/?probe=f9dfefaf63) | Aug 31, 2020 |
| Gigabyte      | EP45C-DS3R                  | [3baa06afa2](https://linux-hardware.org/?probe=3baa06afa2) | Aug 24, 2020 |
| ECS           | KAM1-I                      | [cef51c9cd7](https://linux-hardware.org/?probe=cef51c9cd7) | Aug 15, 2020 |
| MSI           | D2414 S26361-D2414-A10      | [a0ea23eae8](https://linux-hardware.org/?probe=a0ea23eae8) | Aug 10, 2020 |
| Unknown       | P4M800Pro-8237              | [e632211d18](https://linux-hardware.org/?probe=e632211d18) | Aug 04, 2020 |
| Gigabyte      | Z77-D3H                     | [05331a0b70](https://linux-hardware.org/?probe=05331a0b70) | Aug 04, 2020 |
| Intel         | DG33FB AAD81072-309         | [217bfd48bd](https://linux-hardware.org/?probe=217bfd48bd) | Aug 04, 2020 |
| Dell          | 0DR845                      | [a70d949ebc](https://linux-hardware.org/?probe=a70d949ebc) | Jul 30, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | [4af42f19bb](https://linux-hardware.org/?probe=4af42f19bb) | Jul 14, 2020 |
| HP            | 3396                        | [53167bce1a](https://linux-hardware.org/?probe=53167bce1a) | Jul 09, 2020 |
| ASUSTek       | G11DF                       | [73ddfc32aa](https://linux-hardware.org/?probe=73ddfc32aa) | Jun 23, 2020 |
| ASUSTek       | G11DF                       | [497ebd9b60](https://linux-hardware.org/?probe=497ebd9b60) | Jun 23, 2020 |
| Biostar       | NF61S-M2A                   | [c071fa24d8](https://linux-hardware.org/?probe=c071fa24d8) | Jun 21, 2020 |
| PCWare        | IPMH81G1                    | [416c3e2997](https://linux-hardware.org/?probe=416c3e2997) | Jun 07, 2020 |
| Dell          | 0200DY A03                  | [aebb17da40](https://linux-hardware.org/?probe=aebb17da40) | Jun 01, 2020 |
| Dell          | 0DR845                      | [4b8a511c08](https://linux-hardware.org/?probe=4b8a511c08) | May 29, 2020 |
| Dell          | 042P49 A00                  | [aca1fb8ea1](https://linux-hardware.org/?probe=aca1fb8ea1) | May 21, 2020 |
| Dell          | 042P49 A00                  | [8e547a1414](https://linux-hardware.org/?probe=8e547a1414) | May 20, 2020 |
| ASRock        | EP2C602-4L/D16              | [cf5fe3dbce](https://linux-hardware.org/?probe=cf5fe3dbce) | May 17, 2020 |
| ASRock        | B75M R2.0                   | [efd3354b61](https://linux-hardware.org/?probe=efd3354b61) | May 10, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | [1a79fa9925](https://linux-hardware.org/?probe=1a79fa9925) | May 03, 2020 |
| ASRock        | J4205-ITX                   | [4fc5d5a325](https://linux-hardware.org/?probe=4fc5d5a325) | Apr 22, 2020 |
| ECS           | Nettle2                     | [ababaf523c](https://linux-hardware.org/?probe=ababaf523c) | Apr 19, 2020 |
| ASUSTek       | A88XM-A                     | [12c198a6f5](https://linux-hardware.org/?probe=12c198a6f5) | Apr 18, 2020 |
| ASUSTek       | A88XM-A                     | [0d1b40e847](https://linux-hardware.org/?probe=0d1b40e847) | Apr 14, 2020 |
| ASRock        | N68-GS3 UCC                 | [3cc8e9e496](https://linux-hardware.org/?probe=3cc8e9e496) | Apr 12, 2020 |
| ASRock        | N68-GS3 UCC                 | [8822c3378d](https://linux-hardware.org/?probe=8822c3378d) | Apr 12, 2020 |
| HP            | 8526 MVB, A                 | [30e90998e1](https://linux-hardware.org/?probe=30e90998e1) | Apr 08, 2020 |
| Gigabyte      | B450M DS3H-CF               | [b660991573](https://linux-hardware.org/?probe=b660991573) | Mar 29, 2020 |
| MSI           | G31M2                       | [7534350893](https://linux-hardware.org/?probe=7534350893) | Mar 28, 2020 |
| Acer          | Aspire TC-605               | [495fffaa63](https://linux-hardware.org/?probe=495fffaa63) | Mar 26, 2020 |
| Gigabyte      | Z370 AORUS Gaming 7         | [fb006f397c](https://linux-hardware.org/?probe=fb006f397c) | Mar 24, 2020 |
| Dell          | 018D1Y A01                  | [5c7e0a86df](https://linux-hardware.org/?probe=5c7e0a86df) | Mar 24, 2020 |
| Dell          | 018D1Y A01                  | [c6a5cf98ee](https://linux-hardware.org/?probe=c6a5cf98ee) | Mar 24, 2020 |
| Gigabyte      | Z370 AORUS Gaming 7         | [0c52aebe31](https://linux-hardware.org/?probe=0c52aebe31) | Mar 23, 2020 |
| Intel         | D34010WYK H14771-303        | [0c19bbe87a](https://linux-hardware.org/?probe=0c19bbe87a) | Feb 18, 2020 |
| HP            | ProLiant MicroServer        | [363851a935](https://linux-hardware.org/?probe=363851a935) | Dec 19, 2019 |
| HP            | ProLiant MicroServer        | [708dff507f](https://linux-hardware.org/?probe=708dff507f) | Dec 19, 2019 |
| Dell          | OptiPlex GX620              | [21f221a304](https://linux-hardware.org/?probe=21f221a304) | May 17, 2019 |
| Dell          | OptiPlex GX620              | [3e9258a7c5](https://linux-hardware.org/?probe=3e9258a7c5) | Apr 15, 2019 |
| Dell          | OptiPlex GX620              | [87babb0fa3](https://linux-hardware.org/?probe=87babb0fa3) | Apr 15, 2019 |
| Gigabyte      | 945GCM-S2L                  | [d950de89e7](https://linux-hardware.org/?probe=d950de89e7) | Mar 26, 2019 |
| Gigabyte      | 970A-UD3P                   | [d425ca175b](https://linux-hardware.org/?probe=d425ca175b) | Oct 11, 2018 |
| Intel         | DG31PR AAD97573-205         | [693096a808](https://linux-hardware.org/?probe=693096a808) | Sep 06, 2018 |
| ASUSTek       | P8Z77-V                     | [bcdb9633d9](https://linux-hardware.org/?probe=bcdb9633d9) | Sep 05, 2018 |
| Foxconn       | 945 7MA Series              | [95d9e1dba9](https://linux-hardware.org/?probe=95d9e1dba9) | Nov 14, 2017 |
| ASUSTek       | H61M-K                      | [78a1c15c22](https://linux-hardware.org/?probe=78a1c15c22) | Sep 09, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/LMDE/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| LMDE 4 | 151      | 46.46%  |
| LMDE 5 | 141      | 43.38%  |
| LMDE 6 | 23       | 7.08%   |
| LMDE 3 | 8        | 2.46%   |
| LMDE 2 | 2        | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| LMDE | 318      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.0-21-amd64          | 28       | 7.69%   |
| 4.19.0-16-amd64          | 23       | 6.32%   |
| 5.10.0-12-amd64          | 21       | 5.77%   |
| 4.19.0-17-amd64          | 20       | 5.49%   |
| 4.19.0-18-amd64          | 19       | 5.22%   |
| 5.10.0-23-amd64          | 18       | 4.95%   |
| 4.19.0-14-amd64          | 18       | 4.95%   |
| 4.19.0-13-amd64          | 17       | 4.67%   |
| 5.10.0-25-amd64          | 16       | 4.4%    |
| 4.19.0-8-amd64           | 15       | 4.12%   |
| 6.1.0-13-amd64           | 13       | 3.57%   |
| 5.10.0-20-amd64          | 12       | 3.3%    |
| 5.10.0-17-amd64          | 11       | 3.02%   |
| 5.10.0-14-amd64          | 10       | 2.75%   |
| 5.10.0-13-amd64          | 10       | 2.75%   |
| 5.10.0-18-amd64          | 9        | 2.47%   |
| 4.19.0-12-amd64          | 9        | 2.47%   |
| 6.1.0-12-amd64           | 8        | 2.2%    |
| 5.10.0-19-amd64          | 8        | 2.2%    |
| 4.19.0-9-amd64           | 8        | 2.2%    |
| 4.19.0-10-amd64          | 8        | 2.2%    |
| 5.10.0-22-amd64          | 5        | 1.37%   |
| 6.1.0-0.deb11.7-amd64    | 4        | 1.1%    |
| 4.9.0-8-amd64            | 4        | 1.1%    |
| 4.19.0-11-amd64          | 4        | 1.1%    |
| 5.10.0-15-amd64          | 3        | 0.82%   |
| 4.19.0-17-686            | 3        | 0.82%   |
| 4.19.0-16-686            | 3        | 0.82%   |
| 4.19.0-14-686            | 3        | 0.82%   |
| 5.10.0-16-amd64          | 2        | 0.55%   |
| 4.19.0-8-686             | 2        | 0.55%   |
| 4.19.0-20-amd64          | 2        | 0.55%   |
| 4.19.0-19-686            | 2        | 0.55%   |
| 4.19.0-18-686            | 2        | 0.55%   |
| 4.19.0-13-686            | 2        | 0.55%   |
| 3.16.0-4-amd64           | 2        | 0.55%   |
| 6.1.0-12-686             | 1        | 0.27%   |
| 6.1.0-11-amd64           | 1        | 0.27%   |
| 6.1.0-0.deb11.5-amd64    | 1        | 0.27%   |
| 6.0.2-x64v2-rt11-xanmod1 | 1        | 0.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 147      | 45.09%  |
| 5.10.0  | 136      | 41.72%  |
| 6.1.0   | 28       | 8.59%   |
| 4.9.0   | 7        | 2.15%   |
| 3.16.0  | 2        | 0.61%   |
| 6.0.2   | 1        | 0.31%   |
| 5.8.0   | 1        | 0.31%   |
| 5.6.0   | 1        | 0.31%   |
| 5.4.0   | 1        | 0.31%   |
| 5.19.0  | 1        | 0.31%   |
| 4.17.0  | 1        | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 147      | 45.09%  |
| 5.10    | 136      | 41.72%  |
| 6.1     | 28       | 8.59%   |
| 4.9     | 7        | 2.15%   |
| 3.16    | 2        | 0.61%   |
| 6.0     | 1        | 0.31%   |
| 5.8     | 1        | 0.31%   |
| 5.6     | 1        | 0.31%   |
| 5.4     | 1        | 0.31%   |
| 5.19    | 1        | 0.31%   |
| 4.17    | 1        | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 297      | 93.4%   |
| i686   | 21       | 6.6%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 277      | 86.29%  |
| Cinnamon   | 26       | 8.1%    |
| MATE       | 7        | 2.18%   |
| Unknown    | 3        | 0.93%   |
| XFCE       | 2        | 0.62%   |
| KDE5       | 2        | 0.62%   |
| GNOME      | 2        | 0.62%   |
| LXQt       | 1        | 0.31%   |
| LXDE       | 1        | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 318      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 238      | 74.61%  |
| LightDM | 61       | 19.12%  |
| TDM     | 15       | 4.7%    |
| MDM     | 2        | 0.63%   |
| GDM     | 2        | 0.63%   |
| SDDM    | 1        | 0.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 97       | 30.5%   |
| de_DE   | 40       | 12.58%  |
| pt_BR   | 28       | 8.81%   |
| fr_FR   | 18       | 5.66%   |
| en_GB   | 16       | 5.03%   |
| ru_RU   | 14       | 4.4%    |
| pl_PL   | 11       | 3.46%   |
| it_IT   | 11       | 3.46%   |
| Unknown | 9        | 2.83%   |
| en_CA   | 8        | 2.52%   |
| es_ES   | 6        | 1.89%   |
| en_AU   | 6        | 1.89%   |
| sv_SE   | 5        | 1.57%   |
| es_AR   | 5        | 1.57%   |
| cs_CZ   | 4        | 1.26%   |
| nl_BE   | 3        | 0.94%   |
| fr_CA   | 3        | 0.94%   |
| sk_SK   | 2        | 0.63%   |
| ru_UA   | 2        | 0.63%   |
| pt_PT   | 2        | 0.63%   |
| hu_HU   | 2        | 0.63%   |
| en_ZA   | 2        | 0.63%   |
| de_AT   | 2        | 0.63%   |
| ar_EG   | 2        | 0.63%   |
| unm_US  | 1        | 0.31%   |
| uk_UA   | 1        | 0.31%   |
| tr_TR   | 1        | 0.31%   |
| nb_NO   | 1        | 0.31%   |
| it_CH   | 1        | 0.31%   |
| fr_BE   | 1        | 0.31%   |
| fi_FI   | 1        | 0.31%   |
| et_EE   | 1        | 0.31%   |
| es_UY   | 1        | 0.31%   |
| es_PA   | 1        | 0.31%   |
| es_NI   | 1        | 0.31%   |
| es_MX   | 1        | 0.31%   |
| es_EC   | 1        | 0.31%   |
| es_CO   | 1        | 0.31%   |
| es_CL   | 1        | 0.31%   |
| es_BO   | 1        | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 197      | 61.76%  |
| EFI  | 122      | 38.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 294      | 92.16%  |
| Btrfs   | 9        | 2.82%   |
| Tmpfs   | 5        | 1.57%   |
| Overlay | 5        | 1.57%   |
| Unknown | 5        | 1.57%   |
| Ext3    | 1        | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 238      | 74.14%  |
| GPT     | 51       | 15.89%  |
| MBR     | 32       | 9.97%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 292      | 91.25%  |
| Yes       | 28       | 8.75%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 282      | 88.4%   |
| Yes       | 37       | 11.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 68       | 21.38%  |
| Gigabyte Technology | 50       | 15.72%  |
| MSI                 | 36       | 11.32%  |
| Dell                | 32       | 10.06%  |
| ASRock              | 26       | 8.18%   |
| Hewlett-Packard     | 22       | 6.92%   |
| Intel               | 15       | 4.72%   |
| Acer                | 11       | 3.46%   |
| Unknown             | 7        | 2.2%    |
| Lenovo              | 6        | 1.89%   |
| Pegatron            | 5        | 1.57%   |
| Foxconn             | 4        | 1.26%   |
| ECS                 | 4        | 1.26%   |
| eMachines           | 3        | 0.94%   |
| AZW                 | 3        | 0.94%   |
| OEM                 | 2        | 0.63%   |
| Medion              | 2        | 0.63%   |
| Fujitsu             | 2        | 0.63%   |
| EVGA                | 2        | 0.63%   |
| Biostar             | 2        | 0.63%   |
| Trigkey             | 1        | 0.31%   |
| SiYW                | 1        | 0.31%   |
| Semp Toshiba        | 1        | 0.31%   |
| Samsung Electronics | 1        | 0.31%   |
| Positivo            | 1        | 0.31%   |
| PCWare              | 1        | 0.31%   |
| Packard Bell        | 1        | 0.31%   |
| NEC Computers       | 1        | 0.31%   |
| Gateway             | 1        | 0.31%   |
| Fujitsu Siemens     | 1        | 0.31%   |
| Digiboard           | 1        | 0.31%   |
| DFI                 | 1        | 0.31%   |
| BESSTAR Tech        | 1        | 0.31%   |
| Apple               | 1        | 0.31%   |
| Alienware           | 1        | 0.31%   |
| ADVANSUS            | 1        | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 8        | 2.52%   |
| ASUS All Series                 | 4        | 1.26%   |
| HP Pavilion Desktop 590-p0xxx   | 3        | 0.94%   |
| Dell OptiPlex 780               | 3        | 0.94%   |
| MSI MS-7C95                     | 2        | 0.63%   |
| MSI MS-7C52                     | 2        | 0.63%   |
| MSI MS-7B79                     | 2        | 0.63%   |
| MSI MS-7A38                     | 2        | 0.63%   |
| Intel B75                       | 2        | 0.63%   |
| HP Z820 Workstation             | 2        | 0.63%   |
| HP ProDesk 400 G5 Desktop Mini  | 2        | 0.63%   |
| HP 290 G2 MT Business PC        | 2        | 0.63%   |
| Gigabyte X570 AORUS ULTRA       | 2        | 0.63%   |
| Gigabyte GA-880GM-UD2H          | 2        | 0.63%   |
| Gigabyte B450M DS3H             | 2        | 0.63%   |
| Gigabyte B450 AORUS M           | 2        | 0.63%   |
| Dell OptiPlex GX620             | 2        | 0.63%   |
| Dell OptiPlex 790               | 2        | 0.63%   |
| Dell OptiPlex 3010              | 2        | 0.63%   |
| AZW MINI S                      | 2        | 0.63%   |
| ASUS ROG STRIX B450-F GAMING    | 2        | 0.63%   |
| ASUS PRIME B350M-A              | 2        | 0.63%   |
| ASUS PRIME A320M-K              | 2        | 0.63%   |
| ASRock A320M-HDV R4.0           | 2        | 0.63%   |
| Trigkey Green G4                | 1        | 0.31%   |
| SiYW V200 Series                | 1        | 0.31%   |
| Semp Toshiba STI                | 1        | 0.31%   |
| Samsung DeskTop System          | 1        | 0.31%   |
| Positivo POS-EIH61CE            | 1        | 0.31%   |
| Pegatron Pro 3015 Microtower PC | 1        | 0.31%   |
| Pegatron p6-2143w               | 1        | 0.31%   |
| Pegatron FQ574AA-ABA m9517c     | 1        | 0.31%   |
| Pegatron Elite 7300 Series MT   | 1        | 0.31%   |
| Pegatron 520-1188la             | 1        | 0.31%   |
| PCWare IPMH81G1                 | 1        | 0.31%   |
| Packard Bell IMEDIA J9640       | 1        | 0.31%   |
| OEM 45CMX/45GMX/45CMX-K         | 1        | 0.31%   |
| NEC Computers IMEDIA S9509      | 1        | 0.31%   |
| MSI PX714AA-ABH t3040.nl        | 1        | 0.31%   |
| MSI MS-7D54                     | 1        | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 17       | 5.35%   |
| ASUS PRIME             | 11       | 3.46%   |
| ASUS ROG               | 8        | 2.52%   |
| Unknown                | 8        | 2.52%   |
| Dell Precision         | 7        | 2.2%    |
| Acer Aspire            | 7        | 2.2%    |
| HP Compaq              | 6        | 1.89%   |
| Gigabyte X570          | 4        | 1.26%   |
| Gigabyte B450M         | 4        | 1.26%   |
| Gigabyte B450          | 4        | 1.26%   |
| Dell Inspiron          | 4        | 1.26%   |
| ASUS All               | 4        | 1.26%   |
| Lenovo ThinkCentre     | 3        | 0.94%   |
| HP ProDesk             | 3        | 0.94%   |
| HP Pavilion            | 3        | 0.94%   |
| Acer Veriton           | 3        | 0.94%   |
| MSI MS-7C95            | 2        | 0.63%   |
| MSI MS-7C52            | 2        | 0.63%   |
| MSI MS-7B79            | 2        | 0.63%   |
| MSI MS-7A38            | 2        | 0.63%   |
| Intel DG31PR           | 2        | 0.63%   |
| Intel B75              | 2        | 0.63%   |
| HP Z820                | 2        | 0.63%   |
| HP 290                 | 2        | 0.63%   |
| Gigabyte Z390          | 2        | 0.63%   |
| Gigabyte GA-880GM-UD2H | 2        | 0.63%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.63%   |
| Gigabyte A520M         | 2        | 0.63%   |
| Foxconn 945            | 2        | 0.63%   |
| Dell Vostro            | 2        | 0.63%   |
| AZW MINI               | 2        | 0.63%   |
| ASUS P8H61-M           | 2        | 0.63%   |
| ASUS P5KPL-AM          | 2        | 0.63%   |
| ASUS P5G41T-M          | 2        | 0.63%   |
| ASRock A320M-HDV       | 2        | 0.63%   |
| Trigkey Green          | 1        | 0.31%   |
| SiYW V200              | 1        | 0.31%   |
| Semp Toshiba STI       | 1        | 0.31%   |
| Samsung DeskTop        | 1        | 0.31%   |
| Positivo POS-EIH61CE   | 1        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 37       | 11.64%  |
| 2018 | 35       | 11.01%  |
| 2009 | 24       | 7.55%   |
| 2019 | 21       | 6.6%    |
| 2010 | 21       | 6.6%    |
| 2013 | 20       | 6.29%   |
| 2011 | 19       | 5.97%   |
| 2007 | 19       | 5.97%   |
| 2014 | 18       | 5.66%   |
| 2017 | 15       | 4.72%   |
| 2008 | 14       | 4.4%    |
| 2006 | 13       | 4.09%   |
| 2021 | 12       | 3.77%   |
| 2020 | 12       | 3.77%   |
| 2015 | 10       | 3.14%   |
| 2016 | 8        | 2.52%   |
| 2022 | 7        | 2.2%    |
| 2023 | 4        | 1.26%   |
| 2005 | 4        | 1.26%   |
| 2003 | 4        | 1.26%   |
| 2004 | 1        | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 318      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 314      | 98.13%  |
| Enabled  | 6        | 1.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 318      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 73       | 22.26%  |
| 16.01-24.0      | 63       | 19.21%  |
| 3.01-4.0        | 56       | 17.07%  |
| 4.01-8.0        | 49       | 14.94%  |
| 32.01-64.0      | 39       | 11.89%  |
| 1.01-2.0        | 14       | 4.27%   |
| 2.01-3.0        | 13       | 3.96%   |
| 64.01-256.0     | 8        | 2.44%   |
| 24.01-32.0      | 7        | 2.13%   |
| 0.51-1.0        | 5        | 1.52%   |
| More than 256.0 | 1        | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 140      | 39.89%  |
| 2.01-3.0   | 89       | 25.36%  |
| 3.01-4.0   | 47       | 13.39%  |
| 4.01-8.0   | 39       | 11.11%  |
| 0.51-1.0   | 27       | 7.69%   |
| 8.01-16.0  | 6        | 1.71%   |
| 32.01-64.0 | 1        | 0.28%   |
| 24.01-32.0 | 1        | 0.28%   |
| 16.01-24.0 | 1        | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 149      | 45.15%  |
| 2      | 92       | 27.88%  |
| 3      | 36       | 10.91%  |
| 4      | 27       | 8.18%   |
| 5      | 12       | 3.64%   |
| 6      | 7        | 2.12%   |
| 7      | 5        | 1.52%   |
| 10     | 1        | 0.3%    |
| 8      | 1        | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 164      | 50.77%  |
| Yes       | 159      | 49.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 317      | 99.69%  |
| No        | 1        | 0.31%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 182      | 55.83%  |
| Yes       | 144      | 44.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 238      | 73.91%  |
| Yes       | 84       | 26.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 54       | 16.98%  |
| Germany      | 48       | 15.09%  |
| Brazil       | 30       | 9.43%   |
| Russia       | 19       | 5.97%   |
| France       | 18       | 5.66%   |
| Italy        | 16       | 5.03%   |
| Canada       | 14       | 4.4%    |
| UK           | 10       | 3.14%   |
| Poland       | 9        | 2.83%   |
| Spain        | 8        | 2.52%   |
| Ukraine      | 7        | 2.2%    |
| Netherlands  | 7        | 2.2%    |
| Australia    | 7        | 2.2%    |
| Sweden       | 5        | 1.57%   |
| Argentina    | 5        | 1.57%   |
| Belgium      | 4        | 1.26%   |
| South Africa | 3        | 0.94%   |
| Mexico       | 3        | 0.94%   |
| Czechia      | 3        | 0.94%   |
| Bulgaria     | 3        | 0.94%   |
| Austria      | 3        | 0.94%   |
| Turkey       | 2        | 0.63%   |
| Slovakia     | 2        | 0.63%   |
| Puerto Rico  | 2        | 0.63%   |
| Portugal     | 2        | 0.63%   |
| Indonesia    | 2        | 0.63%   |
| India        | 2        | 0.63%   |
| Hungary      | 2        | 0.63%   |
| Greece       | 2        | 0.63%   |
| Finland      | 2        | 0.63%   |
| Ecuador      | 2        | 0.63%   |
| Bolivia      | 2        | 0.63%   |
| Venezuela    | 1        | 0.31%   |
| Uruguay      | 1        | 0.31%   |
| Serbia       | 1        | 0.31%   |
| Romania      | 1        | 0.31%   |
| Philippines  | 1        | 0.31%   |
| Panama       | 1        | 0.31%   |
| Pakistan     | 1        | 0.31%   |
| Norway       | 1        | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Berlin            | 6        | 1.76%   |
| Rio de Janeiro    | 4        | 1.18%   |
| Hamburg           | 4        | 1.18%   |
| Warsaw            | 3        | 0.88%   |
| Paris             | 3        | 0.88%   |
| Montreal          | 3        | 0.88%   |
| Melbourne         | 3        | 0.88%   |
| Frankfurt am Main | 3        | 0.88%   |
| Toronto           | 2        | 0.59%   |
| Sofia             | 2        | 0.59%   |
| San Antonio       | 2        | 0.59%   |
| Perth             | 2        | 0.59%   |
| Parma             | 2        | 0.59%   |
| Nitra             | 2        | 0.59%   |
| Munich            | 2        | 0.59%   |
| Moscow            | 2        | 0.59%   |
| Milan             | 2        | 0.59%   |
| Marseille         | 2        | 0.59%   |
| Helsinki          | 2        | 0.59%   |
| Guayaquil         | 2        | 0.59%   |
| Gothenburg        | 2        | 0.59%   |
| Florianópolis    | 2        | 0.59%   |
| Delligsen         | 2        | 0.59%   |
| Dallas            | 2        | 0.59%   |
| Columbia City     | 2        | 0.59%   |
| Braunschweig      | 2        | 0.59%   |
| Belo Horizonte    | 2        | 0.59%   |
| Belém            | 2        | 0.59%   |
| Bayamón          | 2        | 0.59%   |
| Athens            | 2        | 0.59%   |
| Amsterdam         | 2        | 0.59%   |
| Zaporozhe         | 1        | 0.29%   |
| Zaandam           | 1        | 0.29%   |
| Wroclaw           | 1        | 0.29%   |
| Witzenhausen      | 1        | 0.29%   |
| Wijchen           | 1        | 0.29%   |
| Weiden            | 1        | 0.29%   |
| Washington        | 1        | 0.29%   |
| Warmsen           | 1        | 0.29%   |
| Voronezh          | 1        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 123      | 228    | 22.61%  |
| Seagate             | 87       | 145    | 15.99%  |
| Samsung Electronics | 76       | 128    | 13.97%  |
| Kingston            | 35       | 54     | 6.43%   |
| Toshiba             | 28       | 37     | 5.15%   |
| Crucial             | 22       | 28     | 4.04%   |
| SanDisk             | 19       | 23     | 3.49%   |
| Hitachi             | 19       | 24     | 3.49%   |
| A-DATA Technology   | 11       | 11     | 2.02%   |
| China               | 10       | 11     | 1.84%   |
| Phison              | 8        | 16     | 1.47%   |
| Intel               | 6        | 6      | 1.1%    |
| Silicon Motion      | 5        | 6      | 0.92%   |
| Micron Technology   | 5        | 5      | 0.92%   |
| SK hynix            | 4        | 5      | 0.74%   |
| OCZ                 | 4        | 6      | 0.74%   |
| Intenso             | 4        | 5      | 0.74%   |
| Unknown             | 4        | 9      | 0.74%   |
| Unknown             | 3        | 4      | 0.55%   |
| Transcend           | 3        | 4      | 0.55%   |
| SPCC                | 3        | 4      | 0.55%   |
| PNY                 | 3        | 5      | 0.55%   |
| Patriot             | 3        | 4      | 0.55%   |
| Maxtor              | 3        | 5      | 0.55%   |
| ADATA Technology    | 3        | 7      | 0.55%   |
| Team                | 2        | 4      | 0.37%   |
| TCSUNBOW            | 2        | 2      | 0.37%   |
| HGST                | 2        | 2      | 0.37%   |
| Gigabyte Technology | 2        | 3      | 0.37%   |
| Fujitsu             | 2        | 2      | 0.37%   |
| CT500MX5            | 2        | 3      | 0.37%   |
| Apple               | 2        | 2      | 0.37%   |
| Apacer              | 2        | 2      | 0.37%   |
| XrayDisk            | 1        | 2      | 0.18%   |
| WALRAM              | 1        | 1      | 0.18%   |
| Verbatim            | 1        | 2      | 0.18%   |
| Vaseky              | 1        | 4      | 0.18%   |
| V-GeN               | 1        | 1      | 0.18%   |
| TO Exter            | 1        | 1      | 0.18%   |
| TGT                 | 1        | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                         | 9        | 1.4%    |
| Kingston SA400S37480G 480GB SSD                   | 7        | 1.09%   |
| Kingston SA400S37240G 240GB SSD                   | 7        | 1.09%   |
| Kingston SA400S37120G 120GB SSD                   | 7        | 1.09%   |
| Toshiba DT01ACA100 1TB                            | 6        | 0.93%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 5        | 0.78%   |
| Seagate ST500DM002-1BD142 500GB                   | 5        | 0.78%   |
| Seagate ST1000DM010-2EP102 1TB                    | 5        | 0.78%   |
| Samsung SSD 850 EVO 500GB                         | 5        | 0.78%   |
| Toshiba HDWD110 1TB                               | 4        | 0.62%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 2TB | 4        | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB                    | 4        | 0.62%   |
| Seagate ST2000DM001-1ER164 2TB                    | 4        | 0.62%   |
| Seagate ST1000DM003-1CH162 1TB                    | 4        | 0.62%   |
| Samsung SSD 860 EVO 500GB                         | 4        | 0.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4        | 0.62%   |
| Crucial CT240BX500SSD1 240GB                      | 4        | 0.62%   |
| Unknown                                           | 4        | 0.62%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 3        | 0.47%   |
| WDC WD10EZEX-60WN4A0 1TB                          | 3        | 0.47%   |
| Seagate ST3500418AS 500GB                         | 3        | 0.47%   |
| Seagate ST2000LX001-1RG174 2TB                    | 3        | 0.47%   |
| Seagate ST1000DM003-1ER162 1TB                    | 3        | 0.47%   |
| Seagate Expansion 1TB                             | 3        | 0.47%   |
| Samsung SSD 970 EVO 500GB                         | 3        | 0.47%   |
| Samsung SSD 870 QVO 2TB                           | 3        | 0.47%   |
| Samsung SSD 850 PRO 256GB                         | 3        | 0.47%   |
| Samsung NVMe SSD Drive 500GB                      | 3        | 0.47%   |
| Samsung HD322HJ 320GB                             | 3        | 0.47%   |
| Samsung HD161HJ 160GB                             | 3        | 0.47%   |
| Samsung HD103SJ 1TB                               | 3        | 0.47%   |
| Crucial CT480BX500SSD1 480GB                      | 3        | 0.47%   |
| Crucial CT250MX500SSD1 250GB                      | 3        | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 2        | 0.31%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 2        | 0.31%   |
| WDC WD5000AAKX-00U6AA0 500GB                      | 2        | 0.31%   |
| WDC WD5000AAKX-001CA0 500GB                       | 2        | 0.31%   |
| WDC WD40EZAZ-00SF3B0 4TB                          | 2        | 0.31%   |
| WDC WD40EFRX-68N32N0 4TB                          | 2        | 0.31%   |
| WDC WD3200AAKS-00L9A0 320GB                       | 2        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 109      | 206    | 37.98%  |
| Seagate             | 87       | 144    | 30.31%  |
| Samsung Electronics | 30       | 41     | 10.45%  |
| Toshiba             | 24       | 29     | 8.36%   |
| Hitachi             | 19       | 24     | 6.62%   |
| Maxtor              | 3        | 5      | 1.05%   |
| Unknown             | 2        | 2      | 0.7%    |
| HGST                | 2        | 2      | 0.7%    |
| Fujitsu             | 2        | 2      | 0.7%    |
| KESU                | 1        | 2      | 0.35%   |
| Intenso             | 1        | 1      | 0.35%   |
| IBM/Hitachi         | 1        | 1      | 0.35%   |
| HPE                 | 1        | 4      | 0.35%   |
| ExcelStor           | 1        | 1      | 0.35%   |
| ASMT                | 1        | 2      | 0.35%   |
| ASMedia             | 1        | 1      | 0.35%   |
| Apple               | 1        | 1      | 0.35%   |
| Unknown             | 1        | 1      | 0.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 37       | 53     | 18.14%  |
| Kingston            | 30       | 46     | 14.71%  |
| Crucial             | 21       | 27     | 10.29%  |
| WDC                 | 14       | 19     | 6.86%   |
| SanDisk             | 14       | 17     | 6.86%   |
| A-DATA Technology   | 11       | 11     | 5.39%   |
| China               | 10       | 11     | 4.9%    |
| Toshiba             | 4        | 8      | 1.96%   |
| OCZ                 | 4        | 6      | 1.96%   |
| Micron Technology   | 4        | 4      | 1.96%   |
| Intel               | 4        | 4      | 1.96%   |
| Transcend           | 3        | 4      | 1.47%   |
| SPCC                | 3        | 4      | 1.47%   |
| PNY                 | 3        | 5      | 1.47%   |
| Patriot             | 3        | 4      | 1.47%   |
| Intenso             | 3        | 4      | 1.47%   |
| Team                | 2        | 4      | 0.98%   |
| TCSUNBOW            | 2        | 2      | 0.98%   |
| SK hynix            | 2        | 2      | 0.98%   |
| Gigabyte Technology | 2        | 3      | 0.98%   |
| CT500MX5            | 2        | 3      | 0.98%   |
| Apacer              | 2        | 2      | 0.98%   |
| Verbatim            | 1        | 2      | 0.49%   |
| Vaseky              | 1        | 4      | 0.49%   |
| V-GeN               | 1        | 1      | 0.49%   |
| Unknown             | 1        | 1      | 0.49%   |
| TO Exter            | 1        | 1      | 0.49%   |
| TakeMS              | 1        | 1      | 0.49%   |
| T-FORCE             | 1        | 1      | 0.49%   |
| Smartbuy            | 1        | 1      | 0.49%   |
| SD                  | 1        | 1      | 0.49%   |
| SABRENT             | 1        | 1      | 0.49%   |
| Plextor             | 1        | 2      | 0.49%   |
| Phison              | 1        | 8      | 0.49%   |
| OCZ-VERTEX          | 1        | 1      | 0.49%   |
| NGFF                | 1        | 1      | 0.49%   |
| Netac               | 1        | 1      | 0.49%   |
| LITEONIT            | 1        | 1      | 0.49%   |
| KingSpec            | 1        | 1      | 0.49%   |
| Kingmax             | 1        | 1      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 228      | 469    | 49.57%  |
| SSD     | 168      | 280    | 36.52%  |
| NVMe    | 56       | 88     | 12.17%  |
| Unknown | 7        | 11     | 1.52%   |
| MMC     | 1        | 1      | 0.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 299      | 722    | 78.68%  |
| NVMe | 56       | 88     | 14.74%  |
| SAS  | 24       | 38     | 6.32%   |
| MMC  | 1        | 1      | 0.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 239      | 455    | 56.37%  |
| 0.51-1.0   | 107      | 164    | 25.24%  |
| 1.01-2.0   | 39       | 58     | 9.2%    |
| 3.01-4.0   | 15       | 28     | 3.54%   |
| 2.01-3.0   | 12       | 26     | 2.83%   |
| 4.01-10.0  | 10       | 16     | 2.36%   |
| 10.01-20.0 | 2        | 2      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 97       | 28.96%  |
| 251-500        | 70       | 20.9%   |
| 1001-2000      | 43       | 12.84%  |
| 501-1000       | 36       | 10.75%  |
| More than 3000 | 33       | 9.85%   |
| 51-100         | 19       | 5.67%   |
| 2001-3000      | 17       | 5.07%   |
| 21-50          | 11       | 3.28%   |
| 1-20           | 9        | 2.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 110      | 31.61%  |
| 21-50          | 70       | 20.11%  |
| 51-100         | 39       | 11.21%  |
| 101-250        | 34       | 9.77%   |
| 251-500        | 32       | 9.2%    |
| 501-1000       | 22       | 6.32%   |
| 1001-2000      | 19       | 5.46%   |
| More than 3000 | 12       | 3.45%   |
| 2001-3000      | 10       | 2.87%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Desktops | Drives | Percent |
|-----------------------------------------------------|----------|--------|---------|
| WDC WD2500BEVT-24A23T0 250GB                        | 1        | 1      | 4.55%   |
| WDC WD10EZRZ-00HTKB0 1TB                            | 1        | 1      | 4.55%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 1        | 1      | 4.55%   |
| WDC WD1002FAEX-00Y9A0 1TB                           | 1        | 1      | 4.55%   |
| Toshiba MQ04ABF100 1TB                              | 1        | 1      | 4.55%   |
| Toshiba MD04ACA400 4TB                              | 1        | 1      | 4.55%   |
| Toshiba HDWD110 1TB                                 | 1        | 1      | 4.55%   |
| Seagate ST9320325AS 320GB                           | 1        | 1      | 4.55%   |
| Seagate ST500LT012-1DG142 500GB                     | 1        | 1      | 4.55%   |
| Seagate ST500DM002-1BD142 500GB                     | 1        | 1      | 4.55%   |
| Seagate ST3250318AS 250GB                           | 1        | 1      | 4.55%   |
| Seagate ST2000DX001-1CM164 2TB                      | 1        | 1      | 4.55%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1        | 1      | 4.55%   |
| Samsung Electronics SSD 980 500GB                   | 1        | 1      | 4.55%   |
| Samsung Electronics SSD 870 EVO 2TB                 | 1        | 1      | 4.55%   |
| Samsung Electronics SP2004C 200GB                   | 1        | 1      | 4.55%   |
| Samsung Electronics HM500JI 500GB                   | 1        | 1      | 4.55%   |
| Samsung Electronics HD153WI 1TB                     | 1        | 1      | 4.55%   |
| Samsung Electronics HD103SJ 1TB                     | 1        | 1      | 4.55%   |
| Micron Technology MTFDDAK512MAY-1AE1ZABHA 512GB SSD | 1        | 1      | 4.55%   |
| IBM/Hitachi IC35L040AVER07-0 41GB                   | 1        | 1      | 4.55%   |
| Hitachi HDS721010KLA330 1TB                         | 1        | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 6      | 27.27%  |
| Samsung Electronics | 6        | 6      | 27.27%  |
| WDC                 | 4        | 4      | 18.18%  |
| Toshiba             | 3        | 3      | 13.64%  |
| Micron Technology   | 1        | 1      | 4.55%   |
| IBM/Hitachi         | 1        | 1      | 4.55%   |
| Hitachi             | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 6      | 31.58%  |
| WDC                 | 4        | 4      | 21.05%  |
| Samsung Electronics | 4        | 4      | 21.05%  |
| Toshiba             | 3        | 3      | 15.79%  |
| IBM/Hitachi         | 1        | 1      | 5.26%   |
| Hitachi             | 1        | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 19     | 85.71%  |
| SSD  | 2        | 2      | 9.52%   |
| NVMe | 1        | 1      | 4.76%   |

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
| Detected | 249      | 630    | 71.76%  |
| Works    | 78       | 197    | 22.48%  |
| Malfunc  | 20       | 22     | 5.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 212      | 49.65%  |
| AMD                              | 82       | 19.2%   |
| Samsung Electronics              | 20       | 4.68%   |
| Nvidia                           | 16       | 3.75%   |
| ASMedia Technology               | 15       | 3.51%   |
| JMicron Technology               | 14       | 3.28%   |
| VIA Technologies                 | 9        | 2.11%   |
| Phison Electronics               | 9        | 2.11%   |
| SanDisk                          | 8        | 1.87%   |
| Marvell Technology Group         | 8        | 1.87%   |
| Silicon Motion                   | 6        | 1.41%   |
| Kingston Technology Company      | 6        | 1.41%   |
| Broadcom / LSI                   | 5        | 1.17%   |
| ADATA Technology                 | 3        | 0.7%    |
| SK hynix                         | 2        | 0.47%   |
| Silicon Integrated Systems [SiS] | 2        | 0.47%   |
| Silicon Image                    | 2        | 0.47%   |
| Micron/Crucial Technology        | 2        | 0.47%   |
| Micron Technology                | 1        | 0.23%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.23%   |
| LSI Logic / Symbios Logic        | 1        | 0.23%   |
| KIOXIA                           | 1        | 0.23%   |
| Integrated Technology Express    | 1        | 0.23%   |
| INNOGRIT                         | 1        | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 44       | 7.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 28       | 4.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26       | 4.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 24       | 4.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21       | 3.68%   |
| AMD 400 Series Chipset SATA Controller                                                  | 20       | 3.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 16       | 2.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14       | 2.46%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 14       | 2.46%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 2.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 12       | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10       | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 1.58%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 9        | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 1.58%   |
| AMD FCH SATA Controller D                                                               | 9        | 1.58%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 8        | 1.4%    |
| Nvidia MCP61 SATA Controller                                                            | 8        | 1.4%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 8        | 1.4%    |
| Intel SATA Controller [RAID mode]                                                       | 7        | 1.23%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 7        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7        | 1.23%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 1.23%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 1.23%   |
| Nvidia MCP61 IDE                                                                        | 6        | 1.05%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 1.05%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 1.05%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 5        | 0.88%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 5        | 0.88%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 0.88%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 4        | 0.7%    |
| Phison E12 NVMe Controller                                                              | 4        | 0.7%    |
| JMicron JMB368 IDE controller                                                           | 4        | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4        | 0.7%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 4        | 0.7%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 4        | 0.7%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 4        | 0.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 236      | 54.5%   |
| IDE  | 111      | 25.64%  |
| NVMe | 56       | 12.93%  |
| RAID | 22       | 5.08%   |
| SAS  | 6        | 1.39%   |
| SCSI | 2        | 0.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 218      | 68.55%  |
| AMD    | 100      | 31.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 8        | 2.5%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 7        | 2.19%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 1.56%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 5        | 1.56%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 5        | 1.56%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 5        | 1.56%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 5        | 1.56%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 5        | 1.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 1.25%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 1.25%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 4        | 1.25%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.25%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 4        | 1.25%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3        | 0.94%   |
| Intel Pentium D CPU 3.00GHz                 | 3        | 0.94%   |
| Intel Pentium D CPU 2.80GHz                 | 3        | 0.94%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 3        | 0.94%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 0.94%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 0.94%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.94%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 0.94%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 3        | 0.94%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 0.94%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 0.94%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 0.94%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 3        | 0.94%   |
| AMD FX-4300 Quad-Core Processor             | 3        | 0.94%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2        | 0.63%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 2        | 0.63%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 0.63%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 0.63%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 0.63%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 0.63%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 0.63%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.63%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.63%   |
| Intel Core i5-9500T CPU @ 2.20GHz           | 2        | 0.63%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 0.63%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.63%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 42       | 13.17%  |
| Intel Core i7           | 40       | 12.54%  |
| AMD Ryzen 5             | 23       | 7.21%   |
| Intel Core 2 Duo        | 22       | 6.9%    |
| Intel Xeon              | 20       | 6.27%   |
| Intel Core i3           | 20       | 6.27%   |
| AMD Ryzen 7             | 16       | 5.02%   |
| Intel Celeron           | 14       | 4.39%   |
| Intel Core 2 Quad       | 12       | 3.76%   |
| Intel Pentium           | 10       | 3.13%   |
| Other                   | 8        | 2.51%   |
| Intel Pentium Dual-Core | 8        | 2.51%   |
| Intel Pentium D         | 8        | 2.51%   |
| AMD Ryzen 3             | 8        | 2.51%   |
| AMD FX                  | 8        | 2.51%   |
| AMD Phenom II X4        | 5        | 1.57%   |
| AMD Athlon 64 X2        | 5        | 1.57%   |
| Intel Core 2            | 4        | 1.25%   |
| AMD Sempron             | 4        | 1.25%   |
| AMD Phenom II X6        | 4        | 1.25%   |
| Intel Pentium Dual      | 3        | 0.94%   |
| Intel Pentium 4         | 3        | 0.94%   |
| Intel Core i9           | 3        | 0.94%   |
| AMD Ryzen 9             | 3        | 0.94%   |
| AMD Athlon XP           | 3        | 0.94%   |
| AMD Athlon II X2        | 3        | 0.94%   |
| AMD Athlon              | 3        | 0.94%   |
| AMD A4                  | 3        | 0.94%   |
| Intel Pentium Gold      | 2        | 0.63%   |
| AMD E1                  | 2        | 0.63%   |
| AMD Athlon II X4        | 2        | 0.63%   |
| AMD Turion II Neo       | 1        | 0.31%   |
| AMD Ryzen 5 PRO         | 1        | 0.31%   |
| AMD Phenom II X2        | 1        | 0.31%   |
| AMD Phenom              | 1        | 0.31%   |
| AMD G                   | 1        | 0.31%   |
| AMD A8                  | 1        | 0.31%   |
| AMD A6                  | 1        | 0.31%   |
| AMD A10                 | 1        | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 124      | 38.75%  |
| 2      | 103      | 32.19%  |
| 6      | 32       | 10%     |
| 8      | 29       | 9.06%   |
| 1      | 16       | 5%      |
| 16     | 7        | 2.19%   |
| 12     | 3        | 0.94%   |
| 10     | 2        | 0.63%   |
| 3      | 2        | 0.63%   |
| 24     | 1        | 0.31%   |
| 14     | 1        | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 309      | 97.17%  |
| 2      | 9        | 2.83%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 174      | 54.55%  |
| 2      | 145      | 45.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 311      | 97.8%   |
| 32-bit         | 7        | 2.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 26       | 8%      |
| 0x306a9    | 25       | 7.69%   |
| 0x1067a    | 25       | 7.69%   |
| Unknown    | 24       | 7.38%   |
| 0x206a7    | 21       | 6.46%   |
| 0x08108109 | 10       | 3.08%   |
| 0x6fd      | 9        | 2.77%   |
| 0x506e3    | 8        | 2.46%   |
| 0x0800820d | 8        | 2.46%   |
| 0x010000c8 | 8        | 2.46%   |
| 0x906ed    | 7        | 2.15%   |
| 0x906ea    | 7        | 2.15%   |
| 0x08701021 | 7        | 2.15%   |
| 0x6fb      | 6        | 1.85%   |
| 0x106e5    | 5        | 1.54%   |
| 0x10677    | 5        | 1.54%   |
| 0xf65      | 4        | 1.23%   |
| 0x906eb    | 4        | 1.23%   |
| 0x206d7    | 4        | 1.23%   |
| 0x0a50000d | 4        | 1.23%   |
| 0x06001119 | 4        | 1.23%   |
| 0x06000852 | 4        | 1.23%   |
| 0xf64      | 3        | 0.92%   |
| 0xf29      | 3        | 0.92%   |
| 0xa0671    | 3        | 0.92%   |
| 0x706a8    | 3        | 0.92%   |
| 0x6f2      | 3        | 0.92%   |
| 0x306e4    | 3        | 0.92%   |
| 0x20655    | 3        | 0.92%   |
| 0x106a5    | 3        | 0.92%   |
| 0x10676    | 3        | 0.92%   |
| 0x08701030 | 3        | 0.92%   |
| 0x08101016 | 3        | 0.92%   |
| 0x0810100b | 3        | 0.92%   |
| 0x010000dc | 3        | 0.92%   |
| 0xa0655    | 2        | 0.62%   |
| 0xa0653    | 2        | 0.62%   |
| 0x906e9    | 2        | 0.62%   |
| 0x906c0    | 2        | 0.62%   |
| 0x90675    | 2        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 33       | 10.31%  |
| Haswell          | 30       | 9.38%   |
| SandyBridge      | 29       | 9.06%   |
| IvyBridge        | 29       | 9.06%   |
| KabyLake         | 22       | 6.88%   |
| Core             | 21       | 6.56%   |
| Zen+             | 18       | 5.63%   |
| K10              | 17       | 5.31%   |
| NetBurst         | 14       | 4.38%   |
| Zen              | 13       | 4.06%   |
| Zen 3            | 11       | 3.44%   |
| Zen 2            | 11       | 3.44%   |
| Piledriver       | 10       | 3.13%   |
| Skylake          | 8        | 2.5%    |
| Nehalem          | 8        | 2.5%    |
| K8 Hammer        | 8        | 2.5%    |
| Unknown          | 6        | 1.88%   |
| Westmere         | 5        | 1.56%   |
| CometLake        | 4        | 1.25%   |
| K6               | 3        | 0.94%   |
| Goldmont plus    | 3        | 0.94%   |
| Bulldozer        | 3        | 0.94%   |
| Tremont          | 2        | 0.63%   |
| Jaguar           | 2        | 0.63%   |
| Bobcat           | 2        | 0.63%   |
| Alderlake Hybrid | 2        | 0.63%   |
| TigerLake        | 1        | 0.31%   |
| Silvermont       | 1        | 0.31%   |
| K10 Llano        | 1        | 0.31%   |
| Gracemont        | 1        | 0.31%   |
| Goldmont         | 1        | 0.31%   |
| Broadwell        | 1        | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 150      | 43.48%  |
| Intel                      | 106      | 30.72%  |
| AMD                        | 82       | 23.77%  |
| VIA Technologies           | 4        | 1.16%   |
| S3 Graphics                | 1        | 0.29%   |
| Matrox Electronics Systems | 1        | 0.29%   |
| ASPEED Technology          | 1        | 0.29%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 19       | 5.32%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 12       | 3.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 3.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 11       | 3.08%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 10       | 2.8%    |
| Nvidia GK208B [GeForce GT 710]                                              | 10       | 2.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 2.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 10       | 2.8%    |
| Nvidia GT218 [GeForce 210]                                                  | 9        | 2.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 2.52%   |
| Nvidia GK208B [GeForce GT 730]                                              | 7        | 1.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 1.68%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.4%    |
| Nvidia GK104 [GeForce GTX 760]                                              | 5        | 1.4%    |
| AMD RV710 [Radeon HD 4350/4550]                                             | 5        | 1.4%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 1.4%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 5        | 1.4%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.12%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.12%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 4        | 1.12%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 1.12%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 0.84%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 0.84%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 3        | 0.84%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3        | 0.84%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.56%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.56%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 0.56%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 2        | 0.56%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 2        | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.56%   |
| Nvidia GM204GL [Quadro M4000]                                               | 2        | 0.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.56%   |
| Nvidia GF119 [NVS 310]                                                      | 2        | 0.56%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 2        | 0.56%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 0.56%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 0.56%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 2        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 138      | 42.86%  |
| 1 x Intel       | 86       | 26.71%  |
| 1 x AMD         | 70       | 21.74%  |
| 2 x AMD         | 8        | 2.48%   |
| Intel + Nvidia  | 7        | 2.17%   |
| 1 x VIA         | 4        | 1.24%   |
| AMD + Nvidia    | 3        | 0.93%   |
| 2 x Nvidia      | 2        | 0.62%   |
| 1 x S3 Graphics | 1        | 0.31%   |
| 1 x Matrox      | 1        | 0.31%   |
| Intel + AMD     | 1        | 0.31%   |
| 1 x ASPEED      | 1        | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 219      | 67.8%   |
| Proprietary | 67       | 20.74%  |
| Unknown     | 37       | 11.46%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 126      | 38.53%  |
| 1.01-2.0   | 51       | 15.6%   |
| 0.51-1.0   | 42       | 12.84%  |
| 0.01-0.5   | 42       | 12.84%  |
| 3.01-4.0   | 32       | 9.79%   |
| 7.01-8.0   | 17       | 5.2%    |
| 5.01-6.0   | 7        | 2.14%   |
| 2.01-3.0   | 4        | 1.22%   |
| 8.01-16.0  | 4        | 1.22%   |
| 16.01-24.0 | 2        | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 61       | 18.77%  |
| Goldstar                | 34       | 10.46%  |
| Acer                    | 29       | 8.92%   |
| Dell                    | 27       | 8.31%   |
| Hewlett-Packard         | 17       | 5.23%   |
| Philips                 | 16       | 4.92%   |
| BenQ                    | 15       | 4.62%   |
| AOC                     | 15       | 4.62%   |
| Ancor Communications    | 13       | 4%      |
| Unknown                 | 11       | 3.38%   |
| Sony                    | 7        | 2.15%   |
| Lenovo                  | 6        | 1.85%   |
| Iiyama                  | 6        | 1.85%   |
| Fujitsu Siemens         | 6        | 1.85%   |
| Eizo                    | 4        | 1.23%   |
| NEC Computers           | 3        | 0.92%   |
| ASUSTek Computer        | 3        | 0.92%   |
| ___                     | 2        | 0.62%   |
| ViewSonic               | 2        | 0.62%   |
| Toshiba                 | 2        | 0.62%   |
| Sceptre Tech            | 2        | 0.62%   |
| Medion                  | 2        | 0.62%   |
| LG Electronics          | 2        | 0.62%   |
| eMachines               | 2        | 0.62%   |
| DENON                   | 2        | 0.62%   |
| Chi Mei Optoelectronics | 2        | 0.62%   |
| AUS                     | 2        | 0.62%   |
| Vestel                  | 1        | 0.31%   |
| Unknown (XXX)           | 1        | 0.31%   |
| Targa Visionary         | 1        | 0.31%   |
| Targa                   | 1        | 0.31%   |
| SKY                     | 1        | 0.31%   |
| RGT                     | 1        | 0.31%   |
| PLN                     | 1        | 0.31%   |
| Pioneer                 | 1        | 0.31%   |
| OEM                     | 1        | 0.31%   |
| Nixeus                  | 1        | 0.31%   |
| NCS                     | 1        | 0.31%   |
| MStar                   | 1        | 0.31%   |
| MSI                     | 1        | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 4        | 1.17%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch             | 3        | 0.87%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch    | 3        | 0.87%   |
| Acer V246HQL ACR0424 1920x1080 521x293mm 23.5-inch                  | 3        | 0.87%   |
| Unknown LCD Monitor SAMSUNG                                         | 2        | 0.58%   |
| Toshiba LCD Monitor TV 1920x1080                                    | 2        | 0.58%   |
| Sony LCD Monitor TV 3840x1080                                       | 2        | 0.58%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 300x230mm 14.9-inch | 2        | 0.58%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch   | 2        | 0.58%   |
| Lenovo L24i-10 LEN65D6 1920x1080 527x296mm 23.8-inch                | 2        | 0.58%   |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch           | 2        | 0.58%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                 | 2        | 0.58%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch        | 2        | 0.58%   |
| Fujitsu Siemens P27-9 TS QHD FUS08D5 2560x1440 597x336mm 27.0-inch  | 2        | 0.58%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch               | 2        | 0.58%   |
| Dell P190S DEL405B 1280x1024 380x300mm 19.1-inch                    | 2        | 0.58%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                   | 2        | 0.58%   |
| AOC 2036 AOC2036 1600x900 443x249mm 20.0-inch                       | 2        | 0.58%   |
| Acer T272HL ACR013B 1920x1080 598x336mm 27.0-inch                   | 2        | 0.58%   |
| ___ LCDTV16 ___0101 1920x1080                                       | 1        | 0.29%   |
| ___ LCD Monitor ___A995 1600x1200 360x270mm 17.7-inch               | 1        | 0.29%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch          | 1        | 0.29%   |
| ViewSonic VG2230wm-EU VSCA21E 1680x1050 474x296mm 22.0-inch         | 1        | 0.29%   |
| Vestel LCD Monitor 58UHD_LCD_TV 3840x2160                           | 1        | 0.29%   |
| Unknown Monitor A995 1280x1024 360x270mm 17.7-inch                  | 1        | 0.29%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                  | 1        | 0.29%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                               | 1        | 0.29%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                               | 1        | 0.29%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                | 1        | 0.29%   |
| Unknown LCD Monitor Mitsubishi NXM76LCD 1280x1024                   | 1        | 0.29%   |
| Unknown LCD Monitor GBT G34WQC 3440x1440                            | 1        | 0.29%   |
| Unknown LCD Monitor Dell SE2717H/HX 1920x1080                       | 1        | 0.29%   |
| Unknown HV-734TB ___1770 1280x1024 338x270mm 17.0-inch              | 1        | 0.29%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch       | 1        | 0.29%   |
| Targa Visionary LCD19-4 TARA194 1280x1024 376x301mm 19.0-inch       | 1        | 0.29%   |
| Targa LCD Monitor LCD TV                                            | 1        | 0.29%   |
| Sony TV SNY8E01 1360x768                                            | 1        | 0.29%   |
| Sony TV SNY8701 1440x900                                            | 1        | 0.29%   |
| Sony TV SNY4C03 1920x1080 1063x598mm 48.0-inch                      | 1        | 0.29%   |
| Sony TV SNY1B02 1360x768                                            | 1        | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 142      | 45.22%  |
| 1280x1024 (SXGA)   | 41       | 13.06%  |
| 1680x1050 (WSXGA+) | 20       | 6.37%   |
| 3840x2160 (4K)     | 16       | 5.1%    |
| 1440x900 (WXGA+)   | 13       | 4.14%   |
| 1366x768 (WXGA)    | 12       | 3.82%   |
| 2560x1440 (QHD)    | 10       | 3.18%   |
| 1600x900 (HD+)     | 10       | 3.18%   |
| 1920x1200 (WUXGA)  | 8        | 2.55%   |
| 1360x768           | 8        | 2.55%   |
| 3440x1440          | 7        | 2.23%   |
| Unknown            | 7        | 2.23%   |
| 2560x1080          | 5        | 1.59%   |
| 1024x768 (XGA)     | 5        | 1.59%   |
| 3840x1080          | 3        | 0.96%   |
| 1600x1200          | 2        | 0.64%   |
| 7680x2160          | 1        | 0.32%   |
| 4480x1440          | 1        | 0.32%   |
| 4240x1440          | 1        | 0.32%   |
| 3040x1050          | 1        | 0.32%   |
| 1280x768           | 1        | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 49       | 15.26%  |
| 21      | 39       | 12.15%  |
| 24      | 38       | 11.84%  |
| 23      | 30       | 9.35%   |
| 27      | 25       | 7.79%   |
| 19      | 25       | 7.79%   |
| 18      | 18       | 5.61%   |
| 17      | 18       | 5.61%   |
| 22      | 13       | 4.05%   |
| 20      | 12       | 3.74%   |
| 15      | 10       | 3.12%   |
| 34      | 7        | 2.18%   |
| 31      | 7        | 2.18%   |
| 72      | 5        | 1.56%   |
| 32      | 4        | 1.25%   |
| 54      | 3        | 0.93%   |
| 52      | 3        | 0.93%   |
| 25      | 2        | 0.62%   |
| 84      | 1        | 0.31%   |
| 65      | 1        | 0.31%   |
| 64      | 1        | 0.31%   |
| 48      | 1        | 0.31%   |
| 46      | 1        | 0.31%   |
| 40      | 1        | 0.31%   |
| 33      | 1        | 0.31%   |
| 28      | 1        | 0.31%   |
| 26      | 1        | 0.31%   |
| 16      | 1        | 0.31%   |
| 14      | 1        | 0.31%   |
| 13      | 1        | 0.31%   |
| 12      | 1        | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 87       | 27.97%  |
| 401-500     | 86       | 27.65%  |
| Unknown     | 49       | 15.76%  |
| 301-350     | 28       | 9%      |
| 351-400     | 20       | 6.43%   |
| 701-800     | 12       | 3.86%   |
| 601-700     | 11       | 3.54%   |
| 1001-1500   | 9        | 2.89%   |
| 1501-2000   | 6        | 1.93%   |
| 201-300     | 2        | 0.64%   |
| 801-900     | 1        | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 161      | 52.79%  |
| Unknown | 48       | 15.74%  |
| 16/10   | 37       | 12.13%  |
| 5/4     | 34       | 11.15%  |
| 4/3     | 14       | 4.59%   |
| 21/9    | 10       | 3.28%   |
| 3/2     | 1        | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 99       | 31.33%  |
| Unknown        | 49       | 15.51%  |
| 151-200        | 48       | 15.19%  |
| 141-150        | 31       | 9.81%   |
| 301-350        | 26       | 8.23%   |
| 351-500        | 19       | 6.01%   |
| 251-300        | 14       | 4.43%   |
| More than 1000 | 13       | 4.11%   |
| 101-110        | 8        | 2.53%   |
| 111-120        | 4        | 1.27%   |
| 501-1000       | 3        | 0.95%   |
| 81-90          | 1        | 0.32%   |
| 71-80          | 1        | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 189      | 61.97%  |
| 101-120 | 50       | 16.39%  |
| Unknown | 49       | 16.07%  |
| 1-50    | 12       | 3.93%   |
| 121-160 | 4        | 1.31%   |
| 161-240 | 1        | 0.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 260      | 79.75%  |
| 2     | 46       | 14.11%  |
| 0     | 17       | 5.21%   |
| 3     | 3        | 0.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 197      | 43.49%  |
| Intel                            | 112      | 24.72%  |
| Qualcomm Atheros                 | 33       | 7.28%   |
| Ralink Technology                | 16       | 3.53%   |
| Nvidia                           | 14       | 3.09%   |
| Broadcom                         | 14       | 3.09%   |
| TP-Link                          | 11       | 2.43%   |
| VIA Technologies                 | 6        | 1.32%   |
| Marvell Technology Group         | 5        | 1.1%    |
| Ralink                           | 4        | 0.88%   |
| Samsung Electronics              | 3        | 0.66%   |
| NetGear                          | 3        | 0.66%   |
| Microsoft                        | 3        | 0.66%   |
| MediaTek                         | 3        | 0.66%   |
| Huawei Technologies              | 3        | 0.66%   |
| Broadcom Limited                 | 3        | 0.66%   |
| Tenda                            | 2        | 0.44%   |
| Sitecom Europe                   | 2        | 0.44%   |
| AVM                              | 2        | 0.44%   |
| ASUSTek Computer                 | 2        | 0.44%   |
| ZTE WCDMA Technologies MSM       | 1        | 0.22%   |
| Silicon Integrated Systems [SiS] | 1        | 0.22%   |
| Qualcomm                         | 1        | 0.22%   |
| Mercucys                         | 1        | 0.22%   |
| Mellanox Technologies            | 1        | 0.22%   |
| LSI                              | 1        | 0.22%   |
| JMicron Technology               | 1        | 0.22%   |
| IMC Networks                     | 1        | 0.22%   |
| HTC (High Tech Computer)         | 1        | 0.22%   |
| Edimax Technology                | 1        | 0.22%   |
| DisplayLink                      | 1        | 0.22%   |
| D-Link System                    | 1        | 0.22%   |
| Belkin Components                | 1        | 0.22%   |
| ADMtek                           | 1        | 0.22%   |
| 3Com                             | 1        | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 146      | 28.24%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17       | 3.29%   |
| Intel I211 Gigabit Network Connection                             | 15       | 2.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12       | 2.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 8        | 1.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 8        | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 1.55%   |
| Nvidia MCP61 Ethernet                                             | 8        | 1.55%   |
| Intel Wi-Fi 6 AX200                                               | 7        | 1.35%   |
| Intel Ethernet Connection I217-V                                  | 7        | 1.35%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 6        | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 1.16%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 1.16%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5        | 0.97%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 5        | 0.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 5        | 0.97%   |
| Ralink MT7601U Wireless Adapter                                   | 5        | 0.97%   |
| Intel Wireless 3165                                               | 5        | 0.97%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5        | 0.97%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 0.97%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 4        | 0.77%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4        | 0.77%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.58%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 3        | 0.58%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.58%   |
| Realtek 802.11ac NIC                                              | 3        | 0.58%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3        | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3        | 0.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.58%   |
| Nvidia MCP77 Ethernet                                             | 3        | 0.58%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 0.58%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.58%   |
| Intel Wireless-AC 9260                                            | 3        | 0.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 0.58%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 52       | 32.3%   |
| Intel                    | 35       | 21.74%  |
| Ralink Technology        | 16       | 9.94%   |
| Qualcomm Atheros         | 14       | 8.7%    |
| TP-Link                  | 11       | 6.83%   |
| Broadcom                 | 5        | 3.11%   |
| Ralink                   | 4        | 2.48%   |
| NetGear                  | 3        | 1.86%   |
| Microsoft                | 3        | 1.86%   |
| MediaTek                 | 3        | 1.86%   |
| Tenda                    | 2        | 1.24%   |
| Sitecom Europe           | 2        | 1.24%   |
| AVM                      | 2        | 1.24%   |
| ASUSTek Computer         | 2        | 1.24%   |
| Mercucys                 | 1        | 0.62%   |
| Marvell Technology Group | 1        | 0.62%   |
| IMC Networks             | 1        | 0.62%   |
| Edimax Technology        | 1        | 0.62%   |
| D-Link System            | 1        | 0.62%   |
| Broadcom Limited         | 1        | 0.62%   |
| Belkin Components        | 1        | 0.62%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 8        | 4.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 8        | 4.85%   |
| Intel Wi-Fi 6 AX200                                                                           | 7        | 4.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 5        | 3.03%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 5        | 3.03%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 5        | 3.03%   |
| Ralink MT7601U Wireless Adapter                                                               | 5        | 3.03%   |
| Intel Wireless 3165                                                                           | 5        | 3.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 5        | 3.03%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 4        | 2.42%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 3        | 1.82%   |
| Realtek 802.11ac NIC                                                                          | 3        | 1.82%   |
| Ralink RT5370 Wireless Adapter                                                                | 3        | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 3        | 1.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 3        | 1.82%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 3        | 1.82%   |
| Intel Wireless-AC 9260                                                                        | 3        | 1.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 3        | 1.82%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 2        | 1.21%   |
| Tenda U12                                                                                     | 2        | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 1.21%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 2        | 1.21%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 2        | 1.21%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 2        | 1.21%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 2        | 1.21%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 2        | 1.21%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 1.21%   |
| Realtek RTL8187 Wireless Adapter                                                              | 2        | 1.21%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 1.21%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 2        | 1.21%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 2        | 1.21%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2        | 1.21%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 2        | 1.21%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 2        | 1.21%   |
| Intel Wireless 8260                                                                           | 2        | 1.21%   |
| Intel Wireless 7265                                                                           | 2        | 1.21%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.61%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 0.61%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                         | 1        | 0.61%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 1        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 176      | 51.92%  |
| Intel                            | 95       | 28.02%  |
| Qualcomm Atheros                 | 19       | 5.6%    |
| Nvidia                           | 14       | 4.13%   |
| Broadcom                         | 9        | 2.65%   |
| VIA Technologies                 | 6        | 1.77%   |
| Marvell Technology Group         | 4        | 1.18%   |
| Samsung Electronics              | 3        | 0.88%   |
| Huawei Technologies              | 3        | 0.88%   |
| Broadcom Limited                 | 2        | 0.59%   |
| ZTE WCDMA Technologies MSM       | 1        | 0.29%   |
| Silicon Integrated Systems [SiS] | 1        | 0.29%   |
| Qualcomm                         | 1        | 0.29%   |
| JMicron Technology               | 1        | 0.29%   |
| HTC (High Tech Computer)         | 1        | 0.29%   |
| DisplayLink                      | 1        | 0.29%   |
| ADMtek                           | 1        | 0.29%   |
| 3Com                             | 1        | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 146      | 41.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17       | 4.86%   |
| Intel I211 Gigabit Network Connection                             | 15       | 4.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12       | 3.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 2.29%   |
| Nvidia MCP61 Ethernet                                             | 8        | 2.29%   |
| Intel Ethernet Connection I217-V                                  | 7        | 2%      |
| VIA VT6102/VT6103 [Rhine-II]                                      | 6        | 1.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 1.71%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 1.71%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 1.71%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 1.43%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.43%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4        | 1.14%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.86%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 0.86%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.86%   |
| Nvidia MCP77 Ethernet                                             | 3        | 0.86%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.86%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 0.86%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 0.86%   |
| Huawei ALP-AL00                                                   | 3        | 0.86%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.57%   |
| Nvidia nForce2 Ethernet Controller                                | 2        | 0.57%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 0.57%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.57%   |
| Intel Ethernet Controller I225-V                                  | 2        | 0.57%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.57%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 0.57%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.57%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.57%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 0.57%   |
| Intel 82567V-2 Gigabit Network Connection                         | 2        | 0.57%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 2        | 0.57%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.57%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 2        | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 317      | 68.47%  |
| WiFi     | 144      | 31.1%   |
| Modem    | 1        | 0.22%   |
| Unknown  | 1        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 255      | 76.58%  |
| WiFi     | 78       | 23.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 218      | 68.13%  |
| 2     | 91       | 28.44%  |
| 3     | 9        | 2.81%   |
| 4     | 1        | 0.31%   |
| 0     | 1        | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 245      | 74.7%   |
| Yes  | 83       | 25.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 34       | 39.08%  |
| Cambridge Silicon Radio         | 21       | 24.14%  |
| Realtek Semiconductor           | 9        | 10.34%  |
| Broadcom                        | 5        | 5.75%   |
| MediaTek                        | 4        | 4.6%    |
| Lite-On Technology              | 3        | 3.45%   |
| Qualcomm Atheros Communications | 2        | 2.3%    |
| ASUSTek Computer                | 2        | 2.3%    |
| Apple                           | 2        | 2.3%    |
| ISSC                            | 1        | 1.15%   |
| IMC Networks                    | 1        | 1.15%   |
| Dynex                           | 1        | 1.15%   |
| Dell                            | 1        | 1.15%   |
| Unknown                         | 1        | 1.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 21       | 23.86%  |
| Intel Bluetooth wireless interface                       | 10       | 11.36%  |
| Intel AX200 Bluetooth                                    | 7        | 7.95%   |
| Realtek Bluetooth Radio                                  | 5        | 5.68%   |
| Intel Wireless-AC 3168 Bluetooth                         | 5        | 5.68%   |
| Realtek  Bluetooth 4.2 Adapter                           | 4        | 4.55%   |
| MediaTek Wireless_Device                                 | 4        | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 3        | 3.41%   |
| Intel AX210 Bluetooth                                    | 3        | 3.41%   |
| Intel AX201 Bluetooth                                    | 3        | 3.41%   |
| Lite-On Bluetooth Device                                 | 2        | 2.27%   |
| Intel Bluetooth Device                                   | 2        | 2.27%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2        | 2.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 2        | 2.27%   |
| Qualcomm Atheros  Bluetooth Device                       | 1        | 1.14%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 1.14%   |
| Lite-On Bluetooth Radio                                  | 1        | 1.14%   |
| ISSC Bluetooth Device                                    | 1        | 1.14%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 1.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1        | 1.14%   |
| IMC Networks Bluetooth Radio                             | 1        | 1.14%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 1.14%   |
| Dell BT Mini-Receiver                                    | 1        | 1.14%   |
| Broadcom HP Bluethunder                                  | 1        | 1.14%   |
| Broadcom Bluetooth 3.0 USB Dongle                        | 1        | 1.14%   |
| Broadcom BCM2045 Bluetooth                               | 1        | 1.14%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 1        | 1.14%   |
| Apple Bluetooth USB Host Controller                      | 1        | 1.14%   |
| Unknown                                                  | 1        | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 198      | 37.93%  |
| Nvidia                               | 135      | 25.86%  |
| AMD                                  | 107      | 20.5%   |
| C-Media Electronics                  | 20       | 3.83%   |
| VIA Technologies                     | 11       | 2.11%   |
| GN Netcom                            | 5        | 0.96%   |
| Generalplus Technology               | 5        | 0.96%   |
| Creative Labs                        | 5        | 0.96%   |
| Logitech                             | 4        | 0.77%   |
| JMTek                                | 3        | 0.57%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.38%   |
| Silicon Integrated Systems [SiS]     | 2        | 0.38%   |
| Plantronics                          | 2        | 0.38%   |
| KTMicro                              | 2        | 0.38%   |
| Creative Technology                  | 2        | 0.38%   |
| Yamaha                               | 1        | 0.19%   |
| Xilinx                               | 1        | 0.19%   |
| Turtle Beach                         | 1        | 0.19%   |
| Texas Instruments                    | 1        | 0.19%   |
| Tenx Technology                      | 1        | 0.19%   |
| Sony                                 | 1        | 0.19%   |
| SAVITECH                             | 1        | 0.19%   |
| Razer USA                            | 1        | 0.19%   |
| QinHeng Electronics                  | 1        | 0.19%   |
| Native Instruments                   | 1        | 0.19%   |
| Micro Star International             | 1        | 0.19%   |
| M-Audio                              | 1        | 0.19%   |
| Jieli Technology                     | 1        | 0.19%   |
| GYROCOM C&C                          | 1        | 0.19%   |
| Focusrite-Novation                   | 1        | 0.19%   |
| Evolution Electronics                | 1        | 0.19%   |
| DCMT Technology                      | 1        | 0.19%   |
| Blue Microphones                     | 1        | 0.19%   |
| ASUSTek Computer                     | 1        | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 30       | 5.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 27       | 4.58%   |
| AMD Family 17h/19h HD Audio Controller                                     | 23       | 3.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20       | 3.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 19       | 3.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 19       | 3.22%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 19       | 3.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 16       | 2.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 15       | 2.54%   |
| AMD Starship/Matisse HD Audio Controller                                   | 15       | 2.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13       | 2.2%    |
| Nvidia High Definition Audio Controller                                    | 12       | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 2.03%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 12       | 2.03%   |
| Nvidia GM206 High Definition Audio Controller                              | 11       | 1.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10       | 1.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10       | 1.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 1.53%   |
| Nvidia MCP61 High Definition Audio                                         | 8        | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 1.36%   |
| AMD FCH Azalia Controller                                                  | 8        | 1.36%   |
| Nvidia TU106 High Definition Audio Controller                              | 7        | 1.19%   |
| Nvidia GM204 High Definition Audio Controller                              | 7        | 1.19%   |
| Nvidia GK104 HDMI Audio Controller                                         | 7        | 1.19%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 7        | 1.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7        | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 1.02%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 6        | 1.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 1.02%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 1.02%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 5        | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 0.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5        | 0.85%   |
| Generalplus Technology USB Audio Device                                    | 5        | 0.85%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 5        | 0.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 5        | 0.85%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 0.68%   |
| Nvidia GF116 High Definition Audio Controller                              | 4        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 26       | 24.53%  |
| Samsung Electronics | 14       | 13.21%  |
| Kingston            | 13       | 12.26%  |
| Crucial             | 9        | 8.49%   |
| SK hynix            | 8        | 7.55%   |
| Corsair             | 8        | 7.55%   |
| Micron Technology   | 6        | 5.66%   |
| G.Skill             | 4        | 3.77%   |
| Team                | 3        | 2.83%   |
| Unknown             | 2        | 1.89%   |
| Unknown (ABCD)      | 1        | 0.94%   |
| Smart               | 1        | 0.94%   |
| PLEXHD              | 1        | 0.94%   |
| Patriot             | 1        | 0.94%   |
| Nanya Technology    | 1        | 0.94%   |
| KLEVV               | 1        | 0.94%   |
| Kingmax             | 1        | 0.94%   |
| GeIL                | 1        | 0.94%   |
| Exceleram           | 1        | 0.94%   |
| Elpida              | 1        | 0.94%   |
| CSX                 | 1        | 0.94%   |
| AVEXIR              | 1        | 0.94%   |
| A-DATA Technology   | 1        | 0.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2        | 1.72%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 2        | 1.72%   |
| Unknown                                                        | 2        | 1.72%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.86%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                        | 1        | 0.86%   |
| Unknown RAM Module 512MB DIMM DDR2 266MT/s                     | 1        | 0.86%   |
| Unknown RAM Module 512MB DIMM 667MT/s                          | 1        | 0.86%   |
| Unknown RAM Module 512MB DIMM                                  | 1        | 0.86%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1        | 0.86%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.86%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 1        | 0.86%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 1        | 0.86%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.86%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 0.86%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                        | 1        | 0.86%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                       | 1        | 0.86%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.86%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 1        | 0.86%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                    | 1        | 0.86%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                    | 1        | 0.86%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                     | 1        | 0.86%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                     | 1        | 0.86%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                         | 1        | 0.86%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                       | 1        | 0.86%   |
| Unknown RAM Module 1GB DIMM DDR2 266MT/s                       | 1        | 0.86%   |
| Unknown RAM Module 1GB DIMM                                    | 1        | 0.86%   |
| Unknown RAM Module 16GB DIMM DDR4 3200MT/s                     | 1        | 0.86%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                     | 1        | 0.86%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1        | 0.86%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                         | 1        | 0.86%   |
| Unknown RAM Module 1024MB DIMM                                 | 1        | 0.86%   |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s        | 1        | 0.86%   |
| Unknown RAM D4 8G 8GB DIMM DDR4 2666MT/s                       | 1        | 0.86%   |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s             | 1        | 0.86%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.86%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s             | 1        | 0.86%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s             | 1        | 0.86%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s          | 1        | 0.86%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s          | 1        | 0.86%   |
| SK hynix RAM Module 8GB DIMM DDR3 1333MT/s                     | 1        | 0.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 34       | 35.79%  |
| DDR3    | 32       | 33.68%  |
| DDR2    | 10       | 10.53%  |
| Unknown | 7        | 7.37%   |
| SDRAM   | 5        | 5.26%   |
| DDR     | 5        | 5.26%   |
| LPDDR4  | 2        | 2.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 82       | 90.11%  |
| SODIMM       | 8        | 8.79%   |
| Row Of Chips | 1        | 1.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 31       | 30.39%  |
| 4096  | 24       | 23.53%  |
| 2048  | 18       | 17.65%  |
| 16384 | 14       | 13.73%  |
| 1024  | 8        | 7.84%   |
| 512   | 4        | 3.92%   |
| 32768 | 3        | 2.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 20       | 19.8%   |
| 1333    | 11       | 10.89%  |
| 2667    | 8        | 7.92%   |
| 667     | 8        | 7.92%   |
| 3200    | 7        | 6.93%   |
| 2400    | 7        | 6.93%   |
| 800     | 6        | 5.94%   |
| 3600    | 5        | 4.95%   |
| 2133    | 5        | 4.95%   |
| 533     | 3        | 2.97%   |
| Unknown | 3        | 2.97%   |
| 3733    | 2        | 1.98%   |
| 1867    | 2        | 1.98%   |
| 1866    | 2        | 1.98%   |
| 1800    | 2        | 1.98%   |
| 4266    | 1        | 0.99%   |
| 3800    | 1        | 0.99%   |
| 3533    | 1        | 0.99%   |
| 3500    | 1        | 0.99%   |
| 2666    | 1        | 0.99%   |
| 1334    | 1        | 0.99%   |
| 1067    | 1        | 0.99%   |
| 1066    | 1        | 0.99%   |
| 400     | 1        | 0.99%   |
| 266     | 1        | 0.99%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 9        | 42.86%  |
| Brother Industries  | 3        | 14.29%  |
| Seiko Epson         | 2        | 9.52%   |
| Samsung Electronics | 2        | 9.52%   |
| Canon               | 2        | 9.52%   |
| Ricoh               | 1        | 4.76%   |
| Minolta             | 1        | 4.76%   |
| Konica Minolta      | 1        | 4.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| HP DeskJet F4200 series          | 2        | 9.52%   |
| Brother MFC-L2685DW              | 2        | 9.52%   |
| Seiko Epson ET-2820 Series       | 1        | 4.76%   |
| Seiko Epson ET-1810 Series       | 1        | 4.76%   |
| Samsung SCX-3400 Series          | 1        | 4.76%   |
| Samsung ML-1670 Series           | 1        | 4.76%   |
| Ricoh SP C260SFNw                | 1        | 4.76%   |
| Minolta PagePro 1200W            | 1        | 4.76%   |
| Konica Minolta 185               | 1        | 4.76%   |
| HP OfficeJet Pro 8730            | 1        | 4.76%   |
| HP LaserJet Pro M404-M405        | 1        | 4.76%   |
| HP LaserJet P1006                | 1        | 4.76%   |
| HP LaserJet 3050                 | 1        | 4.76%   |
| HP Deskjet 2540 series           | 1        | 4.76%   |
| HP DeskJet 2130 series           | 1        | 4.76%   |
| HP Deskjet 1050 J410             | 1        | 4.76%   |
| Canon LaserShot LBP-1120 Printer | 1        | 4.76%   |
| Canon iP4200                     | 1        | 4.76%   |
| Brother HL-L2300D series         | 1        | 4.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 2        | 50%     |
| Hewlett-Packard | 1        | 25%     |
| Canon           | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 1        | 25%     |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 25%     |
| HP ScanJet 3800c                              | 1        | 25%     |
| Canon CanoScan LiDE 110                       | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 20       | 40.82%  |
| Sunplus Innovation Technology | 4        | 8.16%   |
| Microsoft                     | 4        | 8.16%   |
| Z-Star Microelectronics       | 2        | 4.08%   |
| MacroSilicon                  | 2        | 4.08%   |
| Huawei Technologies           | 2        | 4.08%   |
| Creative Technology           | 2        | 4.08%   |
| Xiongmai                      | 1        | 2.04%   |
| WCM_USB                       | 1        | 2.04%   |
| Service & Quality Technology  | 1        | 2.04%   |
| Samsung Electronics           | 1        | 2.04%   |
| Pixart Imaging                | 1        | 2.04%   |
| OmniVision Technologies       | 1        | 2.04%   |
| Nintendo                      | 1        | 2.04%   |
| Microdia                      | 1        | 2.04%   |
| KYE Systems (Mouse Systems)   | 1        | 2.04%   |
| Generalplus Technology        | 1        | 2.04%   |
| Chicony Electronics           | 1        | 2.04%   |
| ARC International             | 1        | 2.04%   |
| Alcor Micro                   | 1        | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Logitech Webcam C270                               | 6        | 12.24%  |
| Microsoft LifeCam HD-3000                          | 3        | 6.12%   |
| Logitech Webcam C310                               | 3        | 6.12%   |
| Z-Star Venus USB2.0 Camera                         | 2        | 4.08%   |
| Sunplus MTD Camera                                 | 2        | 4.08%   |
| Logitech HD Pro Webcam C920                        | 2        | 4.08%   |
| Huawei UVC Camera                                  | 2        | 4.08%   |
| Xiongmai web camera                                | 1        | 2.04%   |
| WCM_USB WEB CAM                                    | 1        | 2.04%   |
| Sunplus Webcam                                     | 1        | 2.04%   |
| Sunplus Full HD webcam                             | 1        | 2.04%   |
| Service & Quality USB PC Camera                    | 1        | 2.04%   |
| Samsung Galaxy series, misc. (MTP mode)            | 1        | 2.04%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro               | 1        | 2.04%   |
| OmniVision Integrated Webcam for Dell XPS 2010     | 1        | 2.04%   |
| Nintendo USB Camera                                | 1        | 2.04%   |
| Microsoft MicrosoftÂ LifeCam VX-5500              | 1        | 2.04%   |
| Microdia Webcam Vitade AF                          | 1        | 2.04%   |
| MacroSilicon USB Video                             | 1        | 2.04%   |
| MacroSilicon ClearClick                            | 1        | 2.04%   |
| Logitech Webcam Pro 9000                           | 1        | 2.04%   |
| Logitech Webcam C930e                              | 1        | 2.04%   |
| Logitech Webcam C925e                              | 1        | 2.04%   |
| Logitech Webcam C210                               | 1        | 2.04%   |
| Logitech Webcam B500                               | 1        | 2.04%   |
| Logitech StreamCam                                 | 1        | 2.04%   |
| Logitech QuickCam Communicate Deluxe/S7500         | 1        | 2.04%   |
| Logitech Logi Webcam C920e                         | 1        | 2.04%   |
| Logitech HD Webcam C615                            | 1        | 2.04%   |
| KYE Systems (Mouse Systems) Genius iSlim 2000AF V2 | 1        | 2.04%   |
| Generalplus 808 Camera #9 (web-cam mode)           | 1        | 2.04%   |
| Creative VF0610 Live! Cam Socialize HD             | 1        | 2.04%   |
| Creative Live! Cam Sync HD [VF0770]                | 1        | 2.04%   |
| Chicony HP High Definition 1MP Webcam              | 1        | 2.04%   |
| ARC International Camera                           | 1        | 2.04%   |
| Alcor Micro USB 5.0M AF Camera                     | 1        | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| VASCO Data Security International | 1        | 33.33%  |
| OmniKey                           | 1        | 33.33%  |
| Jing-Mold Enterprise              | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| VASCO Data Security International DIGIPASS 870                    | 1        | 33.33%  |
| OmniKey CardMan 1021                                              | 1        | 33.33%  |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 230      | 70.12%  |
| 1     | 85       | 25.91%  |
| 2     | 9        | 2.74%   |
| 3     | 3        | 0.91%   |
| 4     | 1        | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 51       | 45.95%  |
| Net/wireless             | 34       | 30.63%  |
| Communication controller | 8        | 7.21%   |
| Multimedia controller    | 4        | 3.6%    |
| Unassigned class         | 3        | 2.7%    |
| Network                  | 2        | 1.8%    |
| Net/ethernet             | 2        | 1.8%    |
| Storage/raid             | 1        | 0.9%    |
| Storage/ide              | 1        | 0.9%    |
| Sound                    | 1        | 0.9%    |
| Modem                    | 1        | 0.9%    |
| Fingerprint reader       | 1        | 0.9%    |
| Chipcard                 | 1        | 0.9%    |
| Camera                   | 1        | 0.9%    |

