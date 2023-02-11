Linux in Slovakia - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovakia.

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

Total: 418

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MS-7513                     | [3953f1b447](https://linux-hardware.org/?probe=3953f1b447) | Jan 28, 2023 |
| Gigabyte      | Z490M                       | [a53147a5e7](https://linux-hardware.org/?probe=a53147a5e7) | Jan 25, 2023 |
| Gigabyte      | H61M-S1                     | [7a3b58d6a7](https://linux-hardware.org/?probe=7a3b58d6a7) | Jan 24, 2023 |
| HP            | 3397                        | [03c53827b5](https://linux-hardware.org/?probe=03c53827b5) | Jan 17, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [8d5796c907](https://linux-hardware.org/?probe=8d5796c907) | Jan 15, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [b10c786457](https://linux-hardware.org/?probe=b10c786457) | Jan 14, 2023 |
| Gigabyte      | B75M-D3H                    | [cfa8ec5fcb](https://linux-hardware.org/?probe=cfa8ec5fcb) | Jan 13, 2023 |
| Gigabyte      | EP45-DS3                    | [5bf59df74c](https://linux-hardware.org/?probe=5bf59df74c) | Jan 10, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [b39213e4d0](https://linux-hardware.org/?probe=b39213e4d0) | Jan 09, 2023 |
| Dell          | 0654JC A01                  | [c3016e1823](https://linux-hardware.org/?probe=c3016e1823) | Jan 09, 2023 |
| Acer          | H57M01                      | [41ee28ae4b](https://linux-hardware.org/?probe=41ee28ae4b) | Jan 09, 2023 |
| MSI           | MS-7513                     | [6e63c2139f](https://linux-hardware.org/?probe=6e63c2139f) | Jan 08, 2023 |
| MSI           | PRO Z690-A DDR4             | [0b9a54a591](https://linux-hardware.org/?probe=0b9a54a591) | Jan 06, 2023 |
| Dell          | 00V62H A00                  | [dde339b7c9](https://linux-hardware.org/?probe=dde339b7c9) | Dec 26, 2022 |
| MSI           | G41M4                       | [b651925b13](https://linux-hardware.org/?probe=b651925b13) | Dec 21, 2022 |
| MSI           | 790GX-G65                   | [7ad3c8f807](https://linux-hardware.org/?probe=7ad3c8f807) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | [5e77ec1117](https://linux-hardware.org/?probe=5e77ec1117) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | [e497bf2ce3](https://linux-hardware.org/?probe=e497bf2ce3) | Dec 17, 2022 |
| HP            | 1905                        | [21f639657c](https://linux-hardware.org/?probe=21f639657c) | Dec 13, 2022 |
| ASUSTek       | PRIME B460M-K               | [ceff27eeef](https://linux-hardware.org/?probe=ceff27eeef) | Dec 07, 2022 |
| Gigabyte      | Z790 AERO G                 | [b779cd6c2f](https://linux-hardware.org/?probe=b779cd6c2f) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX                  | [cd75a3e13f](https://linux-hardware.org/?probe=cd75a3e13f) | Dec 03, 2022 |
| ASUSTek       | PRIME B460M-K               | [c8dd66d6de](https://linux-hardware.org/?probe=c8dd66d6de) | Dec 01, 2022 |
| ASUSTek       | PRIME B460M-K               | [7df334aaa0](https://linux-hardware.org/?probe=7df334aaa0) | Nov 26, 2022 |
| Shuttle       | FS61                        | [7a940c8fa3](https://linux-hardware.org/?probe=7a940c8fa3) | Nov 19, 2022 |
| ASUSTek       | PRIME B460M-K               | [19663894ff](https://linux-hardware.org/?probe=19663894ff) | Nov 18, 2022 |
| ASUSTek       | PRIME B460M-K               | [99a32a02ce](https://linux-hardware.org/?probe=99a32a02ce) | Nov 18, 2022 |
| MSI           | A78-G41 PC Mate             | [8487f5d19c](https://linux-hardware.org/?probe=8487f5d19c) | Nov 08, 2022 |
| MSI           | GF615M-P33                  | [8aec7634ab](https://linux-hardware.org/?probe=8aec7634ab) | Nov 05, 2022 |
| MSI           | Z77A-GD65                   | [a7bc380726](https://linux-hardware.org/?probe=a7bc380726) | Oct 30, 2022 |
| Gigabyte      | 970A-DS3P                   | [995f7abb0c](https://linux-hardware.org/?probe=995f7abb0c) | Oct 25, 2022 |
| MSI           | H310M PRO-VD                | [9ce99513bc](https://linux-hardware.org/?probe=9ce99513bc) | Oct 21, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| ASRock        | X570 Taichi                 | [6b78ca11b4](https://linux-hardware.org/?probe=6b78ca11b4) | Oct 14, 2022 |
| Techvision    | TVI7309X B0                 | [a12d335502](https://linux-hardware.org/?probe=a12d335502) | Oct 06, 2022 |
| Techvision    | TVI7309X B0                 | [fd49fda31a](https://linux-hardware.org/?probe=fd49fda31a) | Oct 06, 2022 |
| ASUSTek       | P5E WS Pro                  | [241e42fa0a](https://linux-hardware.org/?probe=241e42fa0a) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b0cc9bee74](https://linux-hardware.org/?probe=b0cc9bee74) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [45d676584c](https://linux-hardware.org/?probe=45d676584c) | Oct 02, 2022 |
| ASUSTek       | Z170-P                      | [996d72bd1e](https://linux-hardware.org/?probe=996d72bd1e) | Sep 30, 2022 |
| ASUSTek       | Z170-P                      | [8394fca38a](https://linux-hardware.org/?probe=8394fca38a) | Sep 30, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [e35b86c3b7](https://linux-hardware.org/?probe=e35b86c3b7) | Sep 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [f9e71e7e05](https://linux-hardware.org/?probe=f9e71e7e05) | Sep 28, 2022 |
| MSI           | X570-A PRO                  | [345959e0ed](https://linux-hardware.org/?probe=345959e0ed) | Sep 28, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| ASUSTek       | Z87-A                       | [3cdcc8b18d](https://linux-hardware.org/?probe=3cdcc8b18d) | Sep 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [d166d32749](https://linux-hardware.org/?probe=d166d32749) | Sep 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [bce9addcca](https://linux-hardware.org/?probe=bce9addcca) | Sep 26, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [98e8df2d3d](https://linux-hardware.org/?probe=98e8df2d3d) | Sep 21, 2022 |
| ASUSTek       | P5G41T-M LX                 | [50647a7656](https://linux-hardware.org/?probe=50647a7656) | Sep 17, 2022 |
| ASUSTek       | Z97-A                       | [9de0254ab0](https://linux-hardware.org/?probe=9de0254ab0) | Sep 13, 2022 |
| ASRock        | Z170 Gaming K6+             | [39027cdb44](https://linux-hardware.org/?probe=39027cdb44) | Sep 13, 2022 |
| ASUSTek       | Z170-P                      | [bec58f880f](https://linux-hardware.org/?probe=bec58f880f) | Sep 13, 2022 |
| ASUSTek       | Z170-P                      | [182bb36928](https://linux-hardware.org/?probe=182bb36928) | Sep 13, 2022 |
| ASUSTek       | Benicia                     | [13454a57f9](https://linux-hardware.org/?probe=13454a57f9) | Aug 31, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [a6d3642195](https://linux-hardware.org/?probe=a6d3642195) | Aug 24, 2022 |
| ASUSTek       | PRIME B460M-K               | [f5f3761418](https://linux-hardware.org/?probe=f5f3761418) | Aug 19, 2022 |
| Gigabyte      | P43-ES3G                    | [de6e02672c](https://linux-hardware.org/?probe=de6e02672c) | Aug 18, 2022 |
| Lenovo        | 3098 0B98401 WIN            | [769802c689](https://linux-hardware.org/?probe=769802c689) | Aug 15, 2022 |
| Gigabyte      | P43-ES3G                    | [2b0691bddd](https://linux-hardware.org/?probe=2b0691bddd) | Aug 15, 2022 |
| Packard Be... | P5N-E SLI                   | [6f2bf70c0b](https://linux-hardware.org/?probe=6f2bf70c0b) | Aug 09, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [93bd067b5d](https://linux-hardware.org/?probe=93bd067b5d) | Aug 09, 2022 |
| Packard Be... | P5N-E SLI                   | [cdc88569bc](https://linux-hardware.org/?probe=cdc88569bc) | Aug 07, 2022 |
| ASRock        | B550M Steel Legend          | [0ac4f27d0f](https://linux-hardware.org/?probe=0ac4f27d0f) | Jul 31, 2022 |
| ASRock        | FM2A55M-VG3+                | [5d4a26735e](https://linux-hardware.org/?probe=5d4a26735e) | Jul 28, 2022 |
| Gigabyte      | 970A-DS3P                   | [210b75c48e](https://linux-hardware.org/?probe=210b75c48e) | Jul 21, 2022 |
| Gigabyte      | 970A-DS3P                   | [17befc2dd5](https://linux-hardware.org/?probe=17befc2dd5) | Jul 20, 2022 |
| HP            | 8455                        | [9954a77308](https://linux-hardware.org/?probe=9954a77308) | Jul 07, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [779bc20f77](https://linux-hardware.org/?probe=779bc20f77) | Jul 05, 2022 |
| MSI           | A88XM-E35                   | [8767210da3](https://linux-hardware.org/?probe=8767210da3) | Jul 04, 2022 |
| Shuttle       | FH61V                       | [465dc41fdb](https://linux-hardware.org/?probe=465dc41fdb) | Jun 08, 2022 |
| MSI           | Z390-A PRO                  | [8baf319c52](https://linux-hardware.org/?probe=8baf319c52) | May 21, 2022 |
| Intel         | DG41KR AAE62839-304         | [d6fa39e82f](https://linux-hardware.org/?probe=d6fa39e82f) | May 16, 2022 |
| Foxconn       | 2ADA                        | [215ded6566](https://linux-hardware.org/?probe=215ded6566) | May 16, 2022 |
| Acer          | H57M01                      | [9116ecebcb](https://linux-hardware.org/?probe=9116ecebcb) | May 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [52c0b4a6e0](https://linux-hardware.org/?probe=52c0b4a6e0) | May 14, 2022 |
| Acer          | H57M01                      | [42100344af](https://linux-hardware.org/?probe=42100344af) | May 14, 2022 |
| Gigabyte      | H55M-S2H                    | [0b3c6ab0f7](https://linux-hardware.org/?probe=0b3c6ab0f7) | May 14, 2022 |
| ASRock        | H61M-VG4                    | [92f92ef4ee](https://linux-hardware.org/?probe=92f92ef4ee) | Apr 28, 2022 |
| ASRock        | H61M-VG4                    | [fff58f97e8](https://linux-hardware.org/?probe=fff58f97e8) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| Unknown       | RS780-SB700                 | [eb3aa5fa60](https://linux-hardware.org/?probe=eb3aa5fa60) | Apr 20, 2022 |
| Gigabyte      | Z490M                       | [2138ce9310](https://linux-hardware.org/?probe=2138ce9310) | Apr 18, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [e6aa0c6166](https://linux-hardware.org/?probe=e6aa0c6166) | Apr 09, 2022 |
| Acer          | Revo RL80                   | [414f1870b3](https://linux-hardware.org/?probe=414f1870b3) | Apr 04, 2022 |
| Gigabyte      | H61M-S1                     | [a10a00d2f1](https://linux-hardware.org/?probe=a10a00d2f1) | Apr 03, 2022 |
| Lenovo        | MAHOBAY NOK                 | [ba7b7abd34](https://linux-hardware.org/?probe=ba7b7abd34) | Apr 02, 2022 |
| HP            | 18E5                        | [39cb47db55](https://linux-hardware.org/?probe=39cb47db55) | Mar 28, 2022 |
| HP            | 18E5                        | [061d716ce1](https://linux-hardware.org/?probe=061d716ce1) | Mar 27, 2022 |
| Shuttle       | FH61V                       | [9b18d7b2ed](https://linux-hardware.org/?probe=9b18d7b2ed) | Mar 23, 2022 |
| VIA Techno... | KM266-8235                  | [ad3f9e9e12](https://linux-hardware.org/?probe=ad3f9e9e12) | Mar 20, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [e508dbbb0f](https://linux-hardware.org/?probe=e508dbbb0f) | Mar 05, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [455f94f1d3](https://linux-hardware.org/?probe=455f94f1d3) | Mar 04, 2022 |
| HP            | 339A                        | [820ebf5859](https://linux-hardware.org/?probe=820ebf5859) | Feb 26, 2022 |
| HP            | 339A                        | [118fee2993](https://linux-hardware.org/?probe=118fee2993) | Feb 26, 2022 |
| Dell          | 0773VG A00                  | [d24a3aebe9](https://linux-hardware.org/?probe=d24a3aebe9) | Feb 23, 2022 |
| Gigabyte      | H61M-S1                     | [e667cfc4cf](https://linux-hardware.org/?probe=e667cfc4cf) | Feb 20, 2022 |
| Gigabyte      | H55M-S2H                    | [3031d8a880](https://linux-hardware.org/?probe=3031d8a880) | Feb 20, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | [2734c5a939](https://linux-hardware.org/?probe=2734c5a939) | Feb 19, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | [7baecb9fce](https://linux-hardware.org/?probe=7baecb9fce) | Feb 19, 2022 |
| HP            | 339A                        | [d35aeac271](https://linux-hardware.org/?probe=d35aeac271) | Feb 16, 2022 |
| HP            | 339A                        | [aac8acdafe](https://linux-hardware.org/?probe=aac8acdafe) | Feb 16, 2022 |
| Gigabyte      | Z77-HD3                     | [c72849033f](https://linux-hardware.org/?probe=c72849033f) | Feb 15, 2022 |
| Dell          | 02YYK5 A01                  | [bfeed2f132](https://linux-hardware.org/?probe=bfeed2f132) | Feb 14, 2022 |
| ASUSTek       | P8H77-M                     | [b6851e2e2d](https://linux-hardware.org/?probe=b6851e2e2d) | Feb 13, 2022 |
| ASUSTek       | P6T                         | [5084dfc411](https://linux-hardware.org/?probe=5084dfc411) | Feb 12, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [4a136af33b](https://linux-hardware.org/?probe=4a136af33b) | Feb 12, 2022 |
| ASUSTek       | P6T                         | [10a6e04458](https://linux-hardware.org/?probe=10a6e04458) | Feb 10, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | [843210cfb0](https://linux-hardware.org/?probe=843210cfb0) | Feb 06, 2022 |
| Dell          | 0WR7PY A02                  | [2b3c148135](https://linux-hardware.org/?probe=2b3c148135) | Feb 06, 2022 |
| Gigabyte      | 970A-DS3P                   | [ed2a250420](https://linux-hardware.org/?probe=ed2a250420) | Feb 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [d598fc04e1](https://linux-hardware.org/?probe=d598fc04e1) | Feb 04, 2022 |
| Lenovo        | 3176 NOK                    | [d3a3d5276b](https://linux-hardware.org/?probe=d3a3d5276b) | Feb 02, 2022 |
| Gigabyte      | B250M-D3H-CF                | [5b4a8e5bc4](https://linux-hardware.org/?probe=5b4a8e5bc4) | Jan 29, 2022 |
| Shuttle       | FH61V                       | [6d6980d0bb](https://linux-hardware.org/?probe=6d6980d0bb) | Jan 18, 2022 |
| ASUSTek       | H81M-K                      | [637ad5d9e4](https://linux-hardware.org/?probe=637ad5d9e4) | Jan 18, 2022 |
| ASRock        | AM1H-ITX                    | [0a01195a57](https://linux-hardware.org/?probe=0a01195a57) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| ASUSTek       | P5GC-MX                     | [2126180fa9](https://linux-hardware.org/?probe=2126180fa9) | Jan 06, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3867022c38](https://linux-hardware.org/?probe=3867022c38) | Dec 25, 2021 |
| Gigabyte      | Z77-HD3                     | [a9eceeac28](https://linux-hardware.org/?probe=a9eceeac28) | Dec 14, 2021 |
| Shuttle       | FH61V                       | [b4c8a91d0f](https://linux-hardware.org/?probe=b4c8a91d0f) | Dec 13, 2021 |
| Dell          | 0HN7XN A01                  | [f17f39439e](https://linux-hardware.org/?probe=f17f39439e) | Dec 13, 2021 |
| Gigabyte      | Z77-HD3                     | [75755e4033](https://linux-hardware.org/?probe=75755e4033) | Dec 12, 2021 |
| Gigabyte      | Z77-HD3                     | [7d3626d44d](https://linux-hardware.org/?probe=7d3626d44d) | Dec 12, 2021 |
| ASUSTek       | Z170-K                      | [eb723f5cb0](https://linux-hardware.org/?probe=eb723f5cb0) | Dec 09, 2021 |
| Gigabyte      | H410M S2H                   | [8b917483ef](https://linux-hardware.org/?probe=8b917483ef) | Nov 30, 2021 |
| ASUSTek       | P5QL PRO                    | [ad0c0d07cf](https://linux-hardware.org/?probe=ad0c0d07cf) | Nov 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [77a39f82ff](https://linux-hardware.org/?probe=77a39f82ff) | Nov 28, 2021 |
| ASUSTek       | M4A77T/USB3                 | [e23dea02cf](https://linux-hardware.org/?probe=e23dea02cf) | Nov 26, 2021 |
| Gigabyte      | 970A-DS3P                   | [b718c829fa](https://linux-hardware.org/?probe=b718c829fa) | Nov 24, 2021 |
| Intel         | DH77EB AAG39073-304         | [bf7d34f5c1](https://linux-hardware.org/?probe=bf7d34f5c1) | Nov 15, 2021 |
| Intel         | DH77EB AAG39073-304         | [d1e04ead11](https://linux-hardware.org/?probe=d1e04ead11) | Nov 15, 2021 |
| Acer          | EM61SM/EM61PM               | [6a42469739](https://linux-hardware.org/?probe=6a42469739) | Nov 13, 2021 |
| ASRock        | B550M Steel Legend          | [fada2e4c02](https://linux-hardware.org/?probe=fada2e4c02) | Nov 06, 2021 |
| Gigabyte      | GA-M56S-S3                  | [d6285c81a2](https://linux-hardware.org/?probe=d6285c81a2) | Nov 05, 2021 |
| Gigabyte      | H61M-S1                     | [17d03d73f7](https://linux-hardware.org/?probe=17d03d73f7) | Oct 30, 2021 |
| ASRock        | N68C-S UCC                  | [c74421666a](https://linux-hardware.org/?probe=c74421666a) | Oct 20, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [cdc6d847a7](https://linux-hardware.org/?probe=cdc6d847a7) | Oct 18, 2021 |
| Gigabyte      | H310M S2H x.x               | [d0b704d0ff](https://linux-hardware.org/?probe=d0b704d0ff) | Oct 06, 2021 |
| Gigabyte      | H81M-S2V                    | [ef8dfe0673](https://linux-hardware.org/?probe=ef8dfe0673) | Oct 02, 2021 |
| ASUSTek       | Maximus VIII HERO           | [1fce457ac6](https://linux-hardware.org/?probe=1fce457ac6) | Oct 01, 2021 |
| MSI           | E3M WORKSTATION V5          | [6924705831](https://linux-hardware.org/?probe=6924705831) | Sep 20, 2021 |
| Gigabyte      | H61M-S1                     | [6207dd28b2](https://linux-hardware.org/?probe=6207dd28b2) | Sep 09, 2021 |
| MSI           | E3M WORKSTATION V5          | [fa6adf65a6](https://linux-hardware.org/?probe=fa6adf65a6) | Aug 23, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9bf7d4afd7](https://linux-hardware.org/?probe=9bf7d4afd7) | Aug 14, 2021 |
| Dell          | 08HPGT A01                  | [d827460e02](https://linux-hardware.org/?probe=d827460e02) | Aug 04, 2021 |
| ASUSTek       | PRIME B450M-A               | [dc8f396ad8](https://linux-hardware.org/?probe=dc8f396ad8) | Aug 02, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | [30b94a4a43](https://linux-hardware.org/?probe=30b94a4a43) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [925ddff018](https://linux-hardware.org/?probe=925ddff018) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | [756bb76029](https://linux-hardware.org/?probe=756bb76029) | Jul 25, 2021 |
| ASUSTek       | Z87-K                       | [f548a06642](https://linux-hardware.org/?probe=f548a06642) | Jul 23, 2021 |
| MSI           | B450I GAMING PLUS AC        | [04bf0287f0](https://linux-hardware.org/?probe=04bf0287f0) | Jul 21, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [39037104b7](https://linux-hardware.org/?probe=39037104b7) | Jul 17, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [a82245240b](https://linux-hardware.org/?probe=a82245240b) | Jul 15, 2021 |
| Intel         | S3000AHLX D40858-208        | [2acfd9617b](https://linux-hardware.org/?probe=2acfd9617b) | Jul 10, 2021 |
| HP            | 843C                        | [01dc34eeb4](https://linux-hardware.org/?probe=01dc34eeb4) | Jul 07, 2021 |
| HP            | 0A54h                       | [10aa52cef5](https://linux-hardware.org/?probe=10aa52cef5) | Jul 06, 2021 |
| ASUSTek       | H81M-K                      | [9d12a5bba7](https://linux-hardware.org/?probe=9d12a5bba7) | Jul 05, 2021 |
| ASRock        | X570M Pro4                  | [a00aea4331](https://linux-hardware.org/?probe=a00aea4331) | Jul 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [e649a4f85c](https://linux-hardware.org/?probe=e649a4f85c) | Jun 30, 2021 |
| MSI           | H110M PRO-VD                | [83b2318c6a](https://linux-hardware.org/?probe=83b2318c6a) | Jun 26, 2021 |
| Foxconn       | 945 7AD Series              | [9a763d1e1e](https://linux-hardware.org/?probe=9a763d1e1e) | Jun 25, 2021 |
| MSI           | H110M PRO-VD                | [856b9bc825](https://linux-hardware.org/?probe=856b9bc825) | Jun 24, 2021 |
| Intel         | X99                         | [436dda258b](https://linux-hardware.org/?probe=436dda258b) | Jun 21, 2021 |
| Gigabyte      | GA-K8NF-9-RH                | [0cfd20f720](https://linux-hardware.org/?probe=0cfd20f720) | Jun 16, 2021 |
| Gigabyte      | GA-K8NF-9-RH                | [e33a8c0c69](https://linux-hardware.org/?probe=e33a8c0c69) | Jun 16, 2021 |
| ASUSTek       | B85M-G                      | [a390d934b1](https://linux-hardware.org/?probe=a390d934b1) | Jun 13, 2021 |
| Intel         | S3000AHLX D40858-208        | [ab61e363eb](https://linux-hardware.org/?probe=ab61e363eb) | Jun 12, 2021 |
| HP            | 3397                        | [e171bcda3f](https://linux-hardware.org/?probe=e171bcda3f) | Jun 11, 2021 |
| MSI           | B450I GAMING PLUS AC        | [74201da57b](https://linux-hardware.org/?probe=74201da57b) | Jun 11, 2021 |
| HP            | ProLiant ML350 G5           | [297ef6b999](https://linux-hardware.org/?probe=297ef6b999) | Jun 06, 2021 |
| ASRock        | B550 Phantom Gaming-ITX/... | [7c519c91ca](https://linux-hardware.org/?probe=7c519c91ca) | Jun 02, 2021 |
| ASUSTek       | F2A85-V PRO                 | [7950140465](https://linux-hardware.org/?probe=7950140465) | Jun 02, 2021 |
| ASUSTek       | PRIME A320M-K 2020-03-20    | [500976e7d1](https://linux-hardware.org/?probe=500976e7d1) | May 30, 2021 |
| Lenovo        | 0.1                         | [77d8358e26](https://linux-hardware.org/?probe=77d8358e26) | May 28, 2021 |
| Lenovo        | 0.1                         | [d0fbef90ca](https://linux-hardware.org/?probe=d0fbef90ca) | May 27, 2021 |
| Gigabyte      | X58A-UD3R                   | [0b27475327](https://linux-hardware.org/?probe=0b27475327) | May 26, 2021 |
| Pegatron      | 2AD5                        | [794531a511](https://linux-hardware.org/?probe=794531a511) | May 25, 2021 |
| Lenovo        | Tiger Hill                  | [3f61f1be35](https://linux-hardware.org/?probe=3f61f1be35) | May 25, 2021 |
| HP            | 3047h                       | [4fce80ed03](https://linux-hardware.org/?probe=4fce80ed03) | May 20, 2021 |
| MSI           | A75A-G55                    | [f9773bff22](https://linux-hardware.org/?probe=f9773bff22) | May 17, 2021 |
| Intel         | DH87RL AAG74240-402         | [cdb24d5d69](https://linux-hardware.org/?probe=cdb24d5d69) | May 16, 2021 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [e311ba55e3](https://linux-hardware.org/?probe=e311ba55e3) | May 13, 2021 |
| HP            | 843C                        | [e69ec57276](https://linux-hardware.org/?probe=e69ec57276) | May 10, 2021 |
| HP            | 3048h                       | [74f738bae1](https://linux-hardware.org/?probe=74f738bae1) | May 01, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [b4ef2db7c1](https://linux-hardware.org/?probe=b4ef2db7c1) | May 01, 2021 |
| MSI           | E3M WORKSTATION V5          | [995ec93eb1](https://linux-hardware.org/?probe=995ec93eb1) | Apr 27, 2021 |
| MSI           | E3M WORKSTATION V5          | [228ac8147b](https://linux-hardware.org/?probe=228ac8147b) | Apr 24, 2021 |
| ASUSTek       | PRIME Z370-A                | [19b23587fa](https://linux-hardware.org/?probe=19b23587fa) | Apr 20, 2021 |
| ASUSTek       | PRIME Z370-A                | [80fac11897](https://linux-hardware.org/?probe=80fac11897) | Apr 20, 2021 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [c6ed3bc2f4](https://linux-hardware.org/?probe=c6ed3bc2f4) | Apr 18, 2021 |
| ASRock        | N68C-S UCC                  | [79c0025946](https://linux-hardware.org/?probe=79c0025946) | Apr 04, 2021 |
| MSI           | 760GM-P23                   | [aef62f4f18](https://linux-hardware.org/?probe=aef62f4f18) | Apr 02, 2021 |
| ASUSTek       | PRIME A320M-K 2020-03-20    | [19aaa9b56e](https://linux-hardware.org/?probe=19aaa9b56e) | Mar 30, 2021 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [b72dc7a1c6](https://linux-hardware.org/?probe=b72dc7a1c6) | Mar 29, 2021 |
| ASUSTek       | A8R-MVP                     | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| ASUSTek       | A8R-MVP                     | [6daa2a372c](https://linux-hardware.org/?probe=6daa2a372c) | Mar 27, 2021 |
| MSI           | E3M WORKSTATION V5          | [0ee0070622](https://linux-hardware.org/?probe=0ee0070622) | Mar 27, 2021 |
| ASUSTek       | P5Q SE2                     | [bcc4de28fb](https://linux-hardware.org/?probe=bcc4de28fb) | Mar 26, 2021 |
| ASRock        | K8A780LM                    | [b8f4c7c2cb](https://linux-hardware.org/?probe=b8f4c7c2cb) | Mar 22, 2021 |
| ASUSTek       | AM1M-A                      | [c3909a14fe](https://linux-hardware.org/?probe=c3909a14fe) | Mar 22, 2021 |
| Gigabyte      | B450M S2H                   | [285b5b2d08](https://linux-hardware.org/?probe=285b5b2d08) | Mar 17, 2021 |
| ASRock        | K8A780LM                    | [d95a56d80f](https://linux-hardware.org/?probe=d95a56d80f) | Mar 15, 2021 |
| Shuttle       | FH61V                       | [3e811ec55d](https://linux-hardware.org/?probe=3e811ec55d) | Mar 13, 2021 |
| ASRock        | H81M-ITX                    | [0f5f41e1ca](https://linux-hardware.org/?probe=0f5f41e1ca) | Mar 08, 2021 |
| ASRock        | H81M-ITX                    | [8599b883d6](https://linux-hardware.org/?probe=8599b883d6) | Mar 08, 2021 |
| ASRock        | FM2A68M-HD+                 | [a9a3d7da6f](https://linux-hardware.org/?probe=a9a3d7da6f) | Mar 05, 2021 |
| ASRock        | B550M Steel Legend          | [4c28c6d22c](https://linux-hardware.org/?probe=4c28c6d22c) | Mar 03, 2021 |
| Shuttle       | FH61V                       | [70d3424aad](https://linux-hardware.org/?probe=70d3424aad) | Mar 02, 2021 |
| ASUSTek       | Rampage II GENE             | [02ec8d4fff](https://linux-hardware.org/?probe=02ec8d4fff) | Mar 01, 2021 |
| Gigabyte      | X58A-UD3R                   | [323b7be7ea](https://linux-hardware.org/?probe=323b7be7ea) | Feb 27, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [3c402e56a5](https://linux-hardware.org/?probe=3c402e56a5) | Feb 26, 2021 |
| Dell          | 0F8096                      | [307334b9d5](https://linux-hardware.org/?probe=307334b9d5) | Feb 24, 2021 |
| Shuttle       | FH61V                       | [f4fe921fe3](https://linux-hardware.org/?probe=f4fe921fe3) | Feb 24, 2021 |
| ASRock        | H81M-ITX                    | [d58331ce9b](https://linux-hardware.org/?probe=d58331ce9b) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [94f0202173](https://linux-hardware.org/?probe=94f0202173) | Feb 23, 2021 |
| ASUSTek       | A8R-MVP                     | [ce881d4659](https://linux-hardware.org/?probe=ce881d4659) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | [6543fc448e](https://linux-hardware.org/?probe=6543fc448e) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| ASUSTek       | PRIME B250M-A               | [e33b6a55d2](https://linux-hardware.org/?probe=e33b6a55d2) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401        | [248565d49c](https://linux-hardware.org/?probe=248565d49c) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401        | [3acc2f0b1e](https://linux-hardware.org/?probe=3acc2f0b1e) | Feb 20, 2021 |
| Gigabyte      | F2A78M-HD2                  | [b8e8be8f5e](https://linux-hardware.org/?probe=b8e8be8f5e) | Feb 20, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | [bfbf37268c](https://linux-hardware.org/?probe=bfbf37268c) | Feb 17, 2021 |
| Gigabyte      | X58A-UD3R                   | [f16fabf13a](https://linux-hardware.org/?probe=f16fabf13a) | Feb 16, 2021 |
| MSI           | Z97S SLI Krait Edition      | [9f04601c65](https://linux-hardware.org/?probe=9f04601c65) | Feb 14, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [abdd5f9208](https://linux-hardware.org/?probe=abdd5f9208) | Feb 14, 2021 |
| Gigabyte      | G31M-S2L                    | [b664ab9762](https://linux-hardware.org/?probe=b664ab9762) | Feb 11, 2021 |
| Gigabyte      | G31M-S2L                    | [aa7f6024cf](https://linux-hardware.org/?probe=aa7f6024cf) | Feb 10, 2021 |
| ASUSTek       | PRIME X470-PRO              | [715d706afe](https://linux-hardware.org/?probe=715d706afe) | Feb 10, 2021 |
| Dell          | 0PU052                      | [8e0d1be6bf](https://linux-hardware.org/?probe=8e0d1be6bf) | Feb 09, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASUSTek       | P5KPL-SE                    | [83be789e3c](https://linux-hardware.org/?probe=83be789e3c) | Feb 07, 2021 |
| ASUSTek       | P5KPL-SE                    | [ca67f71815](https://linux-hardware.org/?probe=ca67f71815) | Feb 06, 2021 |
| ASRock        | H81M-ITX                    | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| Dell          | 0PU052                      | [cc4b4c54d6](https://linux-hardware.org/?probe=cc4b4c54d6) | Feb 01, 2021 |
| MSI           | MS-7388                     | [6fc9a5690d](https://linux-hardware.org/?probe=6fc9a5690d) | Feb 01, 2021 |
| Gigabyte      | B360M H 2019-01-02          | [6b2b3ee651](https://linux-hardware.org/?probe=6b2b3ee651) | Jan 28, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [845de5bee0](https://linux-hardware.org/?probe=845de5bee0) | Jan 22, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [a875950ed5](https://linux-hardware.org/?probe=a875950ed5) | Jan 22, 2021 |
| ASUSTek       | PRIME X470-PRO              | [b28f7278cd](https://linux-hardware.org/?probe=b28f7278cd) | Jan 21, 2021 |
| Dell          | 0F8096                      | [27186bb8eb](https://linux-hardware.org/?probe=27186bb8eb) | Jan 18, 2021 |
| Intel         | DH87RL AAG74240-402         | [926473c2ac](https://linux-hardware.org/?probe=926473c2ac) | Jan 16, 2021 |
| Intel         | S3000AHLX D40858-208        | [8508696f16](https://linux-hardware.org/?probe=8508696f16) | Jan 16, 2021 |
| ASRock        | K8A780LM                    | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| ASRock        | H81M-ITX                    | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | [62ab746796](https://linux-hardware.org/?probe=62ab746796) | Jan 14, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [f6a8e9eaf5](https://linux-hardware.org/?probe=f6a8e9eaf5) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | [00e4deffa2](https://linux-hardware.org/?probe=00e4deffa2) | Jan 14, 2021 |
| Intel         | DH87RL AAG74240-402         | [dcbc8e3b20](https://linux-hardware.org/?probe=dcbc8e3b20) | Jan 14, 2021 |
| Intel         | DH87RL AAG74240-402         | [4877506709](https://linux-hardware.org/?probe=4877506709) | Jan 14, 2021 |
| MSI           | E3M WORKSTATION V5          | [67805433c0](https://linux-hardware.org/?probe=67805433c0) | Jan 13, 2021 |
| Intel         | DH87RL AAG74240-402         | [5e67f36f68](https://linux-hardware.org/?probe=5e67f36f68) | Jan 12, 2021 |
| HP            | 1495                        | [ffb9d2f433](https://linux-hardware.org/?probe=ffb9d2f433) | Jan 08, 2021 |
| ASRock        | B550M Steel Legend          | [a6b6bbef69](https://linux-hardware.org/?probe=a6b6bbef69) | Jan 07, 2021 |
| ASUSTek       | B85M-G                      | [5e66fb7f43](https://linux-hardware.org/?probe=5e66fb7f43) | Jan 07, 2021 |
| ASUSTek       | B85M-G                      | [e7c1c02ce7](https://linux-hardware.org/?probe=e7c1c02ce7) | Jan 07, 2021 |
| Gigabyte      | 970A-DS3P                   | [fa54fc6400](https://linux-hardware.org/?probe=fa54fc6400) | Jan 05, 2021 |
| HP            | 843C                        | [e6c805f9dd](https://linux-hardware.org/?probe=e6c805f9dd) | Jan 04, 2021 |
| Gigabyte      | M4HM87P-00                  | [3523a7845f](https://linux-hardware.org/?probe=3523a7845f) | Jan 04, 2021 |
| Gigabyte      | P35-DS3R                    | [af4f72e797](https://linux-hardware.org/?probe=af4f72e797) | Jan 04, 2021 |
| ASUSTek       | Z170-K                      | [1cdae8bcc1](https://linux-hardware.org/?probe=1cdae8bcc1) | Jan 01, 2021 |
| Gigabyte      | B250M-D3H-CF                | [192fd63a7c](https://linux-hardware.org/?probe=192fd63a7c) | Dec 27, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [e9db8f5ca6](https://linux-hardware.org/?probe=e9db8f5ca6) | Dec 23, 2020 |
| ASRock        | B550M Steel Legend          | [a733d01196](https://linux-hardware.org/?probe=a733d01196) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [bd927d4e12](https://linux-hardware.org/?probe=bd927d4e12) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [a41b1e7e12](https://linux-hardware.org/?probe=a41b1e7e12) | Dec 22, 2020 |
| ASUSTek       | M4A88T-V EVO/USB3           | [7a5a80d939](https://linux-hardware.org/?probe=7a5a80d939) | Dec 20, 2020 |
| MSI           | B85-G43 GAMING              | [915d83d090](https://linux-hardware.org/?probe=915d83d090) | Dec 19, 2020 |
| Gigabyte      | F2A68HM-DS2                 | [7746ff0cda](https://linux-hardware.org/?probe=7746ff0cda) | Dec 15, 2020 |
| Gigabyte      | GA-MA78GM-US2H              | [0719c37bbd](https://linux-hardware.org/?probe=0719c37bbd) | Dec 13, 2020 |
| ASUSTek       | P5QL-E                      | [b74c06cc19](https://linux-hardware.org/?probe=b74c06cc19) | Dec 03, 2020 |
| ASUSTek       | P5QL-E                      | [c3770ada06](https://linux-hardware.org/?probe=c3770ada06) | Dec 03, 2020 |
| ASUSTek       | Rampage II GENE             | [53d482a443](https://linux-hardware.org/?probe=53d482a443) | Nov 17, 2020 |
| ASUSTek       | Rampage II GENE             | [1ab17cdc86](https://linux-hardware.org/?probe=1ab17cdc86) | Nov 15, 2020 |
| HP            | 3646h                       | [747ede17e0](https://linux-hardware.org/?probe=747ede17e0) | Nov 12, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [8a6ca29d49](https://linux-hardware.org/?probe=8a6ca29d49) | Nov 08, 2020 |
| ASUSTek       | P5LD2-X/1333                | [fec864df41](https://linux-hardware.org/?probe=fec864df41) | Nov 01, 2020 |
| HP            | 3396                        | [73bbba4a08](https://linux-hardware.org/?probe=73bbba4a08) | Oct 29, 2020 |
| HP            | 0AA8h                       | [49ed8250dd](https://linux-hardware.org/?probe=49ed8250dd) | Oct 27, 2020 |
| Gigabyte      | P67X-UD3-B3                 | [67dbb5a0d2](https://linux-hardware.org/?probe=67dbb5a0d2) | Oct 18, 2020 |
| Gigabyte      | P67X-UD3-B3                 | [9f49d2fb4f](https://linux-hardware.org/?probe=9f49d2fb4f) | Oct 18, 2020 |
| Dell          | 0RN474                      | [766ce09345](https://linux-hardware.org/?probe=766ce09345) | Oct 17, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | [1457975a9b](https://linux-hardware.org/?probe=1457975a9b) | Oct 12, 2020 |
| Gigabyte      | Z270X-Gaming 5              | [152291e032](https://linux-hardware.org/?probe=152291e032) | Oct 07, 2020 |
| MSI           | B360 GAMING PLUS            | [a75b777bc2](https://linux-hardware.org/?probe=a75b777bc2) | Oct 04, 2020 |
| Insyde        | SugarBay                    | [ec1ec65380](https://linux-hardware.org/?probe=ec1ec65380) | Oct 01, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [e77ec16bac](https://linux-hardware.org/?probe=e77ec16bac) | Sep 29, 2020 |
| Dell          | 0T10XW A00                  | [78018fdd06](https://linux-hardware.org/?probe=78018fdd06) | Sep 20, 2020 |
| HP            | 86FB MVB A                  | [71e7c31b65](https://linux-hardware.org/?probe=71e7c31b65) | Sep 15, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [cad15a6d4c](https://linux-hardware.org/?probe=cad15a6d4c) | Sep 04, 2020 |
| ASUSTek       | PRIME A320M-K               | [d968666b2d](https://linux-hardware.org/?probe=d968666b2d) | Sep 03, 2020 |
| Gigabyte      | H61M-S1                     | [afc3f83ad0](https://linux-hardware.org/?probe=afc3f83ad0) | Sep 02, 2020 |
| Gigabyte      | G31M-S2L                    | [b2fd45876a](https://linux-hardware.org/?probe=b2fd45876a) | Aug 30, 2020 |
| ASUSTek       | P5GC-MX/1333                | [566417bef1](https://linux-hardware.org/?probe=566417bef1) | Aug 30, 2020 |
| ASUSTek       | M5A78L-M LX                 | [2fbe460b8a](https://linux-hardware.org/?probe=2fbe460b8a) | Aug 16, 2020 |
| ASUSTek       | P8Z68-V PRO                 | [5ffffc7647](https://linux-hardware.org/?probe=5ffffc7647) | Aug 06, 2020 |
| Intel         | D945GCCR AAD78647-300       | [c0beab131f](https://linux-hardware.org/?probe=c0beab131f) | Jul 25, 2020 |
| Intel         | D945GCCR AAD78647-300       | [153c0aab66](https://linux-hardware.org/?probe=153c0aab66) | Jul 25, 2020 |
| Gigabyte      | GC330UD                     | [bdfbe25730](https://linux-hardware.org/?probe=bdfbe25730) | Jul 25, 2020 |
| ASUSTek       | H110M-A/M.2                 | [c570792811](https://linux-hardware.org/?probe=c570792811) | Jul 24, 2020 |
| ASUSTek       | H110M-A/M.2                 | [a3dc30f185](https://linux-hardware.org/?probe=a3dc30f185) | Jul 21, 2020 |
| ASUSTek       | H110M-A/M.2                 | [ef6922214a](https://linux-hardware.org/?probe=ef6922214a) | Jul 20, 2020 |
| ASUSTek       | M5A78L-M LX                 | [332ddc42d4](https://linux-hardware.org/?probe=332ddc42d4) | Jul 16, 2020 |
| ASUSTek       | PRIME Z270-A                | [dc205c9f7e](https://linux-hardware.org/?probe=dc205c9f7e) | Jul 13, 2020 |
| ASUSTek       | PRIME Z270-A                | [b02e3bb9e8](https://linux-hardware.org/?probe=b02e3bb9e8) | Jul 13, 2020 |
| ASRock        | H61M-VG4                    | [2f9520527b](https://linux-hardware.org/?probe=2f9520527b) | Jul 11, 2020 |
| ASRock        | H61M-VG4                    | [b36bc5f47e](https://linux-hardware.org/?probe=b36bc5f47e) | Jul 11, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | [08f2adba8a](https://linux-hardware.org/?probe=08f2adba8a) | Jul 11, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | [c6ed1cd30d](https://linux-hardware.org/?probe=c6ed1cd30d) | Jul 11, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [6ab55c2cfa](https://linux-hardware.org/?probe=6ab55c2cfa) | Jul 03, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [a4b6a8dfb6](https://linux-hardware.org/?probe=a4b6a8dfb6) | Jul 02, 2020 |
| ASUSTek       | M4N78-AM V2                 | [ce2c44ec00](https://linux-hardware.org/?probe=ce2c44ec00) | Jun 16, 2020 |
| ASUSTek       | P7P55D                      | [eeef655b1c](https://linux-hardware.org/?probe=eeef655b1c) | Jun 07, 2020 |
| ASUSTek       | P5P43TD PRO                 | [bdafad0c82](https://linux-hardware.org/?probe=bdafad0c82) | Jun 06, 2020 |
| MSI           | B150M MORTAR                | [7cdf6f047d](https://linux-hardware.org/?probe=7cdf6f047d) | Jun 01, 2020 |
| ASUSTek       | P5P43TD PRO                 | [38acad164f](https://linux-hardware.org/?probe=38acad164f) | May 25, 2020 |
| Pegatron      | 2A73h                       | [0161ecea31](https://linux-hardware.org/?probe=0161ecea31) | May 19, 2020 |
| Pegatron      | 2A73h                       | [42d74e715d](https://linux-hardware.org/?probe=42d74e715d) | May 15, 2020 |
| ASUSTek       | Maximus IX APEX             | [0725349aa7](https://linux-hardware.org/?probe=0725349aa7) | May 11, 2020 |
| Gigabyte      | H61M-S1                     | [b14767e270](https://linux-hardware.org/?probe=b14767e270) | May 07, 2020 |
| ASUSTek       | P5QL-E                      | [d1b8d74839](https://linux-hardware.org/?probe=d1b8d74839) | May 05, 2020 |
| ASUSTek       | M2N-CM DVI                  | [723d371342](https://linux-hardware.org/?probe=723d371342) | Apr 27, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [ebd71cc64d](https://linux-hardware.org/?probe=ebd71cc64d) | Apr 18, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [bbd20923db](https://linux-hardware.org/?probe=bbd20923db) | Apr 18, 2020 |
| Gigabyte      | EP35-DS3                    | [686cd298e3](https://linux-hardware.org/?probe=686cd298e3) | Apr 13, 2020 |
| HP            | 3646h                       | [96421cb602](https://linux-hardware.org/?probe=96421cb602) | Apr 06, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [e6c9f406df](https://linux-hardware.org/?probe=e6c9f406df) | Apr 04, 2020 |
| HP            | 86FB MVB A                  | [91e5642800](https://linux-hardware.org/?probe=91e5642800) | Apr 02, 2020 |
| HP            | 86FB MVB A                  | [95ece68ba4](https://linux-hardware.org/?probe=95ece68ba4) | Apr 02, 2020 |
| ASRock        | 960GC-GS FX                 | [a450257a10](https://linux-hardware.org/?probe=a450257a10) | Mar 31, 2020 |
| Lenovo        | SHARKBAY 31900058 STD       | [92917041c1](https://linux-hardware.org/?probe=92917041c1) | Mar 31, 2020 |
| MSI           | B150M MORTAR                | [99a354df1f](https://linux-hardware.org/?probe=99a354df1f) | Mar 31, 2020 |
| ASUSTek       | VM42                        | [29c87fb102](https://linux-hardware.org/?probe=29c87fb102) | Mar 25, 2020 |
| Intel         | DH87RL AAG74240-402         | [fce111bb71](https://linux-hardware.org/?probe=fce111bb71) | Mar 19, 2020 |
| ASUSTek       | P5LD2-X/1333                | [d278f46944](https://linux-hardware.org/?probe=d278f46944) | Mar 19, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4af2951135](https://linux-hardware.org/?probe=4af2951135) | Mar 02, 2020 |
| Gigabyte      | X58A-UD3R                   | [58c69a16ec](https://linux-hardware.org/?probe=58c69a16ec) | Feb 29, 2020 |
| Gigabyte      | H61M-S1                     | [b5ef9a6442](https://linux-hardware.org/?probe=b5ef9a6442) | Feb 28, 2020 |
| Gigabyte      | X58A-UD3R                   | [4e592e37d9](https://linux-hardware.org/?probe=4e592e37d9) | Feb 28, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [b0a4a95414](https://linux-hardware.org/?probe=b0a4a95414) | Feb 22, 2020 |
| ASUSTek       | M2N-CM DVI                  | [e808fea491](https://linux-hardware.org/?probe=e808fea491) | Feb 14, 2020 |
| MSI           | MS-6702                     | [86b96afa86](https://linux-hardware.org/?probe=86b96afa86) | Feb 07, 2020 |
| Lenovo        | ThinkCentre M58p 7484WHT    | [69debaef8a](https://linux-hardware.org/?probe=69debaef8a) | Feb 06, 2020 |
| MSI           | MS-6702                     | [16256584cd](https://linux-hardware.org/?probe=16256584cd) | Jan 29, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [b839b04f7b](https://linux-hardware.org/?probe=b839b04f7b) | Jan 24, 2020 |
| Intel         | Bearlake Fab D              | [6c46de300b](https://linux-hardware.org/?probe=6c46de300b) | Jan 20, 2020 |
| ASRock        | K8A780LM                    | [e0d3030787](https://linux-hardware.org/?probe=e0d3030787) | Jan 18, 2020 |
| ASRock        | K8A780LM                    | [83dca94e72](https://linux-hardware.org/?probe=83dca94e72) | Jan 17, 2020 |
| ASRock        | K8A780LM                    | [a5e0479887](https://linux-hardware.org/?probe=a5e0479887) | Jan 16, 2020 |
| MSI           | MS-6702                     | [e78238313a](https://linux-hardware.org/?probe=e78238313a) | Jan 13, 2020 |
| Gigabyte      | P31-ES3G                    | [57ed00d8a8](https://linux-hardware.org/?probe=57ed00d8a8) | Jan 08, 2020 |
| ASUSTek       | P5QL-E                      | [6949452f0e](https://linux-hardware.org/?probe=6949452f0e) | Dec 25, 2019 |
| ASUSTek       | P5LD2-X/1333                | [e643b8ed58](https://linux-hardware.org/?probe=e643b8ed58) | Dec 25, 2019 |
| Unknown       | Unknown                     | [4050b2d0d1](https://linux-hardware.org/?probe=4050b2d0d1) | Dec 25, 2019 |
| Unknown       | Unknown                     | [ca23ab1ec8](https://linux-hardware.org/?probe=ca23ab1ec8) | Dec 25, 2019 |
| ASRock        | H81M-ITX                    | [c51735ee45](https://linux-hardware.org/?probe=c51735ee45) | Dec 21, 2019 |
| MSI           | MS-7199                     | [8fe7e9e6a6](https://linux-hardware.org/?probe=8fe7e9e6a6) | Dec 21, 2019 |
| ASUSTek       | VM42                        | [66ad05d5ab](https://linux-hardware.org/?probe=66ad05d5ab) | Dec 12, 2019 |
| Intel         | DZ77GA-70K AAG39009-401     | [44917a35a9](https://linux-hardware.org/?probe=44917a35a9) | Dec 12, 2019 |
| MSI           | MS-6702                     | [792cf869f8](https://linux-hardware.org/?probe=792cf869f8) | Nov 26, 2019 |
| MSI           | 09AC                        | [9188878c2a](https://linux-hardware.org/?probe=9188878c2a) | Nov 19, 2019 |
| ASUSTek       | M2N-E                       | [bb3948f168](https://linux-hardware.org/?probe=bb3948f168) | Nov 15, 2019 |
| ASUSTek       | M2N-E                       | [dc0d15703c](https://linux-hardware.org/?probe=dc0d15703c) | Nov 15, 2019 |
| ASUSTek       | M2N-E                       | [8a49a38575](https://linux-hardware.org/?probe=8a49a38575) | Nov 14, 2019 |
| ASUSTek       | M2N-E                       | [6522851ca9](https://linux-hardware.org/?probe=6522851ca9) | Nov 14, 2019 |
| MSI           | MS-6702                     | [05aa9bf00f](https://linux-hardware.org/?probe=05aa9bf00f) | Nov 13, 2019 |
| Gigabyte      | B360M D3H-CF                | [1c1d5c438a](https://linux-hardware.org/?probe=1c1d5c438a) | Nov 11, 2019 |
| Acer          | Aspire TC-705               | [b732ce4528](https://linux-hardware.org/?probe=b732ce4528) | Nov 04, 2019 |
| ASUSTek       | A8N-E                       | [16b128fafe](https://linux-hardware.org/?probe=16b128fafe) | Nov 04, 2019 |
| ASRock        | H81M-ITX                    | [431ea0cbed](https://linux-hardware.org/?probe=431ea0cbed) | Oct 25, 2019 |
| Dell          | 0F8096                      | [d1f6910c12](https://linux-hardware.org/?probe=d1f6910c12) | Oct 20, 2019 |
| ASUSTek       | M2N-MX SE Plus              | [f4fcd6e28c](https://linux-hardware.org/?probe=f4fcd6e28c) | Oct 20, 2019 |
| ASRock        | H81M-ITX                    | [c5f47f2f27](https://linux-hardware.org/?probe=c5f47f2f27) | Oct 20, 2019 |
| ASUSTek       | M2N-E                       | [96f3d49886](https://linux-hardware.org/?probe=96f3d49886) | Oct 11, 2019 |
| ASUSTek       | M2N-E                       | [5d2552d841](https://linux-hardware.org/?probe=5d2552d841) | Oct 11, 2019 |
| ASUSTek       | M2N-E                       | [c7128161ce](https://linux-hardware.org/?probe=c7128161ce) | Sep 22, 2019 |
| MSI           | MS-6702                     | [72a17e9871](https://linux-hardware.org/?probe=72a17e9871) | Sep 17, 2019 |
| ASUSTek       | H97-PLUS                    | [fc8496dd5a](https://linux-hardware.org/?probe=fc8496dd5a) | Sep 07, 2019 |
| MSI           | MS-6702                     | [3049044a80](https://linux-hardware.org/?probe=3049044a80) | Aug 26, 2019 |
| MSI           | MS-6702                     | [ab947df2c3](https://linux-hardware.org/?probe=ab947df2c3) | Aug 18, 2019 |
| MSI           | MS-6702                     | [3f6b808c8b](https://linux-hardware.org/?probe=3f6b808c8b) | Aug 14, 2019 |
| Dell          | 0DN075                      | [07c3b02228](https://linux-hardware.org/?probe=07c3b02228) | Aug 09, 2019 |
| ASUSTek       | H110M-C                     | [75e32af34d](https://linux-hardware.org/?probe=75e32af34d) | Jul 13, 2019 |
| ASUSTek       | P5L-MX                      | [0c62c4c191](https://linux-hardware.org/?probe=0c62c4c191) | Jun 23, 2019 |
| ASUSTek       | H81M-PLUS                   | [068460eef5](https://linux-hardware.org/?probe=068460eef5) | Jun 15, 2019 |
| MSI           | MS-7407 100                 | [245e00b979](https://linux-hardware.org/?probe=245e00b979) | May 31, 2019 |
| MSI           | MS-6702                     | [1ed53a3a07](https://linux-hardware.org/?probe=1ed53a3a07) | May 05, 2019 |
| ASUSTek       | H110M-C                     | [49d390f38b](https://linux-hardware.org/?probe=49d390f38b) | Apr 14, 2019 |
| ASUSTek       | H110M-C                     | [f48d00866d](https://linux-hardware.org/?probe=f48d00866d) | Apr 10, 2019 |
| Intel         | D925XECV2 AAC83685-205      | [8987ff9068](https://linux-hardware.org/?probe=8987ff9068) | Apr 06, 2019 |
| ASUSTek       | P8Z77-V LX2                 | [6266e950d1](https://linux-hardware.org/?probe=6266e950d1) | Apr 05, 2019 |
| ASUSTek       | M2N-E                       | [59375f9231](https://linux-hardware.org/?probe=59375f9231) | Apr 03, 2019 |
| MSI           | MS-6702                     | [dc92061311](https://linux-hardware.org/?probe=dc92061311) | Apr 02, 2019 |
| MSI           | MS-6702                     | [d62caac198](https://linux-hardware.org/?probe=d62caac198) | Apr 01, 2019 |
| Lenovo        | Tiger Hill                  | [edb984c4e6](https://linux-hardware.org/?probe=edb984c4e6) | Mar 05, 2019 |
| Gigabyte      | F2A68HM-DS2                 | [0ca153c41c](https://linux-hardware.org/?probe=0ca153c41c) | Feb 02, 2019 |
| Dell          | Precision WorkStation 39... | [6040d653c3](https://linux-hardware.org/?probe=6040d653c3) | Jan 09, 2019 |
| Gigabyte      | GA-MA78GM-US2H              | [505cff22f1](https://linux-hardware.org/?probe=505cff22f1) | Nov 11, 2018 |
| Gigabyte      | Z77X-D3H                    | [d9fcab9ba7](https://linux-hardware.org/?probe=d9fcab9ba7) | Nov 03, 2018 |
| HP            | 3047h                       | [bd13661f57](https://linux-hardware.org/?probe=bd13661f57) | Oct 26, 2018 |
| HP            | 3047h                       | [64f2865562](https://linux-hardware.org/?probe=64f2865562) | Oct 26, 2018 |
| Dell          | 0DN075                      | [2951e393ca](https://linux-hardware.org/?probe=2951e393ca) | Jun 02, 2018 |
| MSI           | G41TM-P33                   | [1622e88ef5](https://linux-hardware.org/?probe=1622e88ef5) | Apr 25, 2018 |
| MSI           | G41TM-P33                   | [e05768e40a](https://linux-hardware.org/?probe=e05768e40a) | Apr 12, 2018 |
| MSI           | A88X-G45 GAMING             | [985c8f6bb3](https://linux-hardware.org/?probe=985c8f6bb3) | Jan 25, 2018 |
| MSI           | G41TM-P33                   | [3175c5de11](https://linux-hardware.org/?probe=3175c5de11) | Nov 13, 2017 |
| Gigabyte      | P41-ES3G                    | [f6a2b721dc](https://linux-hardware.org/?probe=f6a2b721dc) | Oct 12, 2017 |
| ASUSTek       | N3700T                      | [175b0f5a5d](https://linux-hardware.org/?probe=175b0f5a5d) | Oct 01, 2017 |
| ASUSTek       | TUF Z270 MARK 1             | [2308897059](https://linux-hardware.org/?probe=2308897059) | Jul 03, 2017 |
| MSI           | G41TM-P33                   | [54f6608d0d](https://linux-hardware.org/?probe=54f6608d0d) | Mar 29, 2017 |
| Gigabyte      | P41-ES3G                    | [f2e7fc2411](https://linux-hardware.org/?probe=f2e7fc2411) | Mar 13, 2017 |
| MSI           | G41TM-P33                   | [f585f0a037](https://linux-hardware.org/?probe=f585f0a037) | Feb 22, 2017 |
| MSI           | G41TM-P33                   | [a14f2598e7](https://linux-hardware.org/?probe=a14f2598e7) | Feb 22, 2017 |
| Gigabyte      | M61PME-S2P                  | [f27dd0a73e](https://linux-hardware.org/?probe=f27dd0a73e) | Feb 15, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 36       | 13.28%  |
| Ubuntu 18.04       | 18       | 6.64%   |
| Ubuntu 22.04       | 13       | 4.8%    |
| OpenMandriva 4.2   | 13       | 4.8%    |
| BlackPanther 18.1  | 13       | 4.8%    |
| OpenMandriva 4.3   | 9        | 3.32%   |
| ROSA R10           | 6        | 2.21%   |
| Linux Mint 20.1    | 6        | 2.21%   |
| Zorin 16           | 5        | 1.85%   |
| Ubuntu 19.10       | 5        | 1.85%   |
| ROSA R9            | 5        | 1.85%   |
| Linux Mint 20.2    | 5        | 1.85%   |
| OpenMandriva 4.50  | 4        | 1.48%   |
| MX 19              | 4        | 1.48%   |
| Linux Mint 20.3    | 4        | 1.48%   |
| Linux Mint 20      | 4        | 1.48%   |
| Xubuntu 18.04      | 3        | 1.11%   |
| Ubuntu 18.10       | 3        | 1.11%   |
| ROSA R11           | 3        | 1.11%   |
| Pop!_OS 22.04      | 3        | 1.11%   |
| Pop!_OS 21.10      | 3        | 1.11%   |
| Pop!_OS 20.04      | 3        | 1.11%   |
| OpenMandriva 23.01 | 3        | 1.11%   |
| MX 18              | 3        | 1.11%   |
| Manjaro 20.1       | 3        | 1.11%   |
| Linux Mint 21      | 3        | 1.11%   |
| Linux Mint 19.3    | 3        | 1.11%   |
| Fedora 34          | 3        | 1.11%   |
| Fedora 33          | 3        | 1.11%   |
| Debian 11          | 3        | 1.11%   |
| Debian 10          | 3        | 1.11%   |
| Ubuntu 20.10       | 2        | 0.74%   |
| ROSA R8            | 2        | 0.74%   |
| Pop!_OS 20.10      | 2        | 0.74%   |
| openSUSE Leap-15.3 | 2        | 0.74%   |
| OpenMandriva 4.90  | 2        | 0.74%   |
| Manjaro            | 2        | 0.74%   |
| Linux Mint 19.1    | 2        | 0.74%   |
| Linux Mint 19      | 2        | 0.74%   |
| Kubuntu 20.04      | 2        | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 76       | 30.04%  |
| OpenMandriva | 32       | 12.65%  |
| Linux Mint   | 26       | 10.28%  |
| ROSA         | 15       | 5.93%   |
| BlackPanther | 14       | 5.53%   |
| Fedora       | 12       | 4.74%   |
| Pop!_OS      | 11       | 4.35%   |
| MX           | 7        | 2.77%   |
| Manjaro      | 7        | 2.77%   |
| Debian       | 7        | 2.77%   |
| Xubuntu      | 6        | 2.37%   |
| Zorin        | 5        | 1.98%   |
| Arch         | 4        | 1.58%   |
| openSUSE     | 3        | 1.19%   |
| Kubuntu      | 3        | 1.19%   |
| Gentoo       | 3        | 1.19%   |
| Devuan       | 3        | 1.19%   |
| ArcoLinux    | 3        | 1.19%   |
| Ubuntu Unity | 2        | 0.79%   |
| Lubuntu      | 2        | 0.79%   |
| LMDE         | 2        | 0.79%   |
| KDE neon     | 2        | 0.79%   |
| Q4OS         | 1        | 0.4%    |
| Nobara       | 1        | 0.4%    |
| Garuda Linux | 1        | 0.4%    |
| Endless      | 1        | 0.4%    |
| CentOS       | 1        | 0.4%    |
| BunsenLabs   | 1        | 0.4%    |
| Archcraft    | 1        | 0.4%    |
| antiX        | 1        | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 4.18.16-desktop-1bP             | 13       | 4.15%   |
| 5.10.14-desktop-1omv4002        | 12       | 3.83%   |
| 5.16.7-desktop-1omv4003         | 9        | 2.88%   |
| 5.4.0-58-generic                | 6        | 1.92%   |
| 5.15.0-43-generic               | 6        | 1.92%   |
| 4.19.0-14-amd64                 | 5        | 1.6%    |
| 4.19.0-13-amd64                 | 5        | 1.6%    |
| 5.8.0-44-generic                | 4        | 1.28%   |
| 6.1.1-desktop-1omv2290          | 3        | 0.96%   |
| 5.4.0-90-generic                | 3        | 0.96%   |
| 5.4.0-77-generic                | 3        | 0.96%   |
| 5.4.0-65-generic                | 3        | 0.96%   |
| 5.4.0-52-generic                | 3        | 0.96%   |
| 5.4.0-26-generic                | 3        | 0.96%   |
| 5.3.0-40-generic                | 3        | 0.96%   |
| 5.15.0-48-generic               | 3        | 0.96%   |
| 5.15.0-46-generic               | 3        | 0.96%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3        | 0.96%   |
| 4.18.0-17-generic               | 3        | 0.96%   |
| 4.15.0-66-generic               | 3        | 0.96%   |
| 5.8.0-43-generic                | 2        | 0.64%   |
| 5.8.0-41-generic                | 2        | 0.64%   |
| 5.4.0-7634-generic              | 2        | 0.64%   |
| 5.4.0-74-generic                | 2        | 0.64%   |
| 5.4.0-73-generic                | 2        | 0.64%   |
| 5.4.0-66-generic                | 2        | 0.64%   |
| 5.4.0-42-generic                | 2        | 0.64%   |
| 5.4.0-33-generic                | 2        | 0.64%   |
| 5.3.0-42-generic                | 2        | 0.64%   |
| 5.3.0-26-generic                | 2        | 0.64%   |
| 5.3.0-24-generic                | 2        | 0.64%   |
| 5.18.12-desktop-3omv4090        | 2        | 0.64%   |
| 5.16.11-76051611-generic        | 2        | 0.64%   |
| 5.15.0-58-generic               | 2        | 0.64%   |
| 5.15.0-56-generic               | 2        | 0.64%   |
| 5.15.0-27-generic               | 2        | 0.64%   |
| 5.13.0-37-generic               | 2        | 0.64%   |
| 5.13.0-30-generic               | 2        | 0.64%   |
| 5.13.0-28-generic               | 2        | 0.64%   |
| 5.12.4-desktop-1omv4050         | 2        | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 46       | 16.14%  |
| 5.15.0  | 23       | 8.07%   |
| 4.15.0  | 20       | 7.02%   |
| 5.8.0   | 17       | 5.96%   |
| 4.18.16 | 14       | 4.91%   |
| 5.3.0   | 13       | 4.56%   |
| 5.10.14 | 12       | 4.21%   |
| 5.16.7  | 9        | 3.16%   |
| 5.13.0  | 9        | 3.16%   |
| 5.11.0  | 9        | 3.16%   |
| 4.18.0  | 8        | 2.81%   |
| 4.19.0  | 7        | 2.46%   |
| 5.10.0  | 4        | 1.4%    |
| 6.1.1   | 3        | 1.05%   |
| 4.9.60  | 3        | 1.05%   |
| 5.9.16  | 2        | 0.7%    |
| 5.8.18  | 2        | 0.7%    |
| 5.3.18  | 2        | 0.7%    |
| 5.19.0  | 2        | 0.7%    |
| 5.18.12 | 2        | 0.7%    |
| 5.16.11 | 2        | 0.7%    |
| 5.13.4  | 2        | 0.7%    |
| 5.12.4  | 2        | 0.7%    |
| 5.0.0   | 2        | 0.7%    |
| 4.9.9   | 2        | 0.7%    |
| 4.9.20  | 2        | 0.7%    |
| 4.9.124 | 2        | 0.7%    |
| 4.9.0   | 2        | 0.7%    |
| 6.1.0   | 1        | 0.35%   |
| 6.0.2   | 1        | 0.35%   |
| 6.0.15  | 1        | 0.35%   |
| 6.0.12  | 1        | 0.35%   |
| 6.0.10  | 1        | 0.35%   |
| 5.9.15  | 1        | 0.35%   |
| 5.9.14  | 1        | 0.35%   |
| 5.8.3   | 1        | 0.35%   |
| 5.7.9   | 1        | 0.35%   |
| 5.7.19  | 1        | 0.35%   |
| 5.7.17  | 1        | 0.35%   |
| 5.7.15  | 1        | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 49       | 17.69%  |
| 5.15    | 27       | 9.75%   |
| 4.18    | 22       | 7.94%   |
| 5.8     | 20       | 7.22%   |
| 5.10    | 20       | 7.22%   |
| 4.15    | 20       | 7.22%   |
| 5.3     | 16       | 5.78%   |
| 5.16    | 14       | 5.05%   |
| 5.13    | 12       | 4.33%   |
| 4.9     | 12       | 4.33%   |
| 5.11    | 11       | 3.97%   |
| 4.19    | 8        | 2.89%   |
| 5.7     | 6        | 2.17%   |
| 5.18    | 5        | 1.81%   |
| 5.12    | 5        | 1.81%   |
| 6.1     | 4        | 1.44%   |
| 6.0     | 4        | 1.44%   |
| 5.19    | 4        | 1.44%   |
| 5.9     | 3        | 1.08%   |
| 5.14    | 3        | 1.08%   |
| 5.5     | 2        | 0.72%   |
| 5.0     | 2        | 0.72%   |
| 4.1     | 2        | 0.72%   |
| 5.6     | 1        | 0.36%   |
| 5.2     | 1        | 0.36%   |
| 5.1     | 1        | 0.36%   |
| 4.7     | 1        | 0.36%   |
| 4.4     | 1        | 0.36%   |
| 4.11    | 1        | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 225      | 93.36%  |
| i686   | 16       | 6.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 94       | 37.75%  |
| KDE5       | 63       | 25.3%   |
| XFCE       | 26       | 10.44%  |
| Unknown    | 23       | 9.24%   |
| X-Cinnamon | 16       | 6.43%   |
| MATE       | 7        | 2.81%   |
| KDE4       | 6        | 2.41%   |
| KDE        | 4        | 1.61%   |
| Cinnamon   | 3        | 1.2%    |
| Unity      | 2        | 0.8%    |
| LXQt       | 2        | 0.8%    |
| Trinity    | 1        | 0.4%    |
| LXDE       | 1        | 0.4%    |
| bspwm      | 1        | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 208      | 83.53%  |
| Wayland | 25       | 10.04%  |
| Unknown | 14       | 5.62%   |
| Tty     | 2        | 0.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 110      | 43.82%  |
| SDDM    | 64       | 25.5%   |
| GDM3    | 26       | 10.36%  |
| LightDM | 17       | 6.77%   |
| GDM     | 16       | 6.37%   |
| TDM     | 9        | 3.59%   |
| KDM     | 6        | 2.39%   |
| SLiM    | 3        | 1.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| sk_SK   | 90       | 36.29%  |
| en_US   | 81       | 32.66%  |
| Unknown | 54       | 21.77%  |
| cs_CZ   | 11       | 4.44%   |
| en_GB   | 4        | 1.61%   |
| C       | 4        | 1.61%   |
| hu_HU   | 2        | 0.81%   |
| POSIX   | 1        | 0.4%    |
| en_AU   | 1        | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 182      | 75.83%  |
| EFI  | 58       | 24.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 166      | 66.67%  |
| Overlay | 47       | 18.88%  |
| Btrfs   | 20       | 8.03%   |
| Unknown | 10       | 4.02%   |
| Xfs     | 3        | 1.2%    |
| Zfs     | 2        | 0.8%    |
| Ext2    | 1        | 0.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 126      | 51.01%  |
| MBR     | 69       | 27.94%  |
| GPT     | 52       | 21.05%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 193      | 75.69%  |
| Yes       | 62       | 24.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 162      | 65.32%  |
| Yes       | 86       | 34.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 78       | 32.64%  |
| Gigabyte Technology | 43       | 17.99%  |
| MSI                 | 30       | 12.55%  |
| Hewlett-Packard     | 19       | 7.95%   |
| ASRock              | 17       | 7.11%   |
| Dell                | 13       | 5.44%   |
| Intel               | 10       | 4.18%   |
| Lenovo              | 8        | 3.35%   |
| Acer                | 5        | 2.09%   |
| Foxconn             | 4        | 1.67%   |
| Shuttle             | 2        | 0.84%   |
| Pegatron            | 2        | 0.84%   |
| Unknown             | 2        | 0.84%   |
| VIA Technologies    | 1        | 0.42%   |
| Techvision          | 1        | 0.42%   |
| Samsung Electronics | 1        | 0.42%   |
| Packard Bell        | 1        | 0.42%   |
| Insyde              | 1        | 0.42%   |
| Fujitsu Siemens     | 1        | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS All Series                      | 11       | 4.6%    |
| Gigabyte F2A68HM-DS2                 | 3        | 1.26%   |
| MSI MS-7C02                          | 2        | 0.84%   |
| MSI MS-7592                          | 2        | 0.84%   |
| Lenovo IdeaCentre Q180 10087&3110    | 2        | 0.84%   |
| HP Compaq Elite 8300 SFF             | 2        | 0.84%   |
| HP Compaq 8000 Elite SFF PC          | 2        | 0.84%   |
| HP Compaq 6005 Pro SFF PC            | 2        | 0.84%   |
| Gigabyte P43-ES3G                    | 2        | 0.84%   |
| Gigabyte H61M-S1                     | 2        | 0.84%   |
| Gigabyte GA-MA78GM-US2H              | 2        | 0.84%   |
| Gigabyte AB350-Gaming 3              | 2        | 0.84%   |
| Gigabyte 970A-DS3P                   | 2        | 0.84%   |
| Foxconn G41MX/G41MX-K 2.0 1.0        | 2        | 0.84%   |
| Dell Precision WorkStation 390       | 2        | 0.84%   |
| Dell OptiPlex 7010                   | 2        | 0.84%   |
| ASUS TUF Gaming B550M-PLUS           | 2        | 0.84%   |
| ASUS ROG STRIX X570-E GAMING         | 2        | 0.84%   |
| ASUS P5QL-E                          | 2        | 0.84%   |
| ASUS M5A78L-M/USB3                   | 2        | 0.84%   |
| ASUS M4A88T-V EVO/USB3               | 2        | 0.84%   |
| ASUS F2A55-M LK2 PLUS                | 2        | 0.84%   |
| ASRock N68C-S UCC                    | 2        | 0.84%   |
| ASRock K8A780LM                      | 2        | 0.84%   |
| Acer Aspire M5811                    | 2        | 0.84%   |
| Unknown                              | 2        | 0.84%   |
| VIA KM266-8235                       | 1        | 0.42%   |
| Techvision TVI7309X                  | 1        | 0.42%   |
| Shuttle XH61V                        | 1        | 0.42%   |
| Shuttle TERRA_PC                     | 1        | 0.42%   |
| Samsung DeskTop System               | 1        | 0.42%   |
| Pegatron Elite 7500 Series MT        | 1        | 0.42%   |
| Pegatron Compaq dx2400 Microtower PC | 1        | 0.42%   |
| Packard Bell IPOWER X9093            | 1        | 0.42%   |
| MSI MS-7D54                          | 1        | 0.42%   |
| MSI MS-7D25                          | 1        | 0.42%   |
| MSI MS-7C37                          | 1        | 0.42%   |
| MSI MS-7B98                          | 1        | 0.42%   |
| MSI MS-7B33                          | 1        | 0.42%   |
| MSI MS-7B22                          | 1        | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| HP Compaq               | 12       | 5.02%   |
| ASUS All                | 11       | 4.6%    |
| Dell OptiPlex           | 9        | 3.77%   |
| ASUS ROG                | 7        | 2.93%   |
| ASUS PRIME              | 7        | 2.93%   |
| ASUS TUF                | 4        | 1.67%   |
| Acer Aspire             | 4        | 1.67%   |
| Lenovo ThinkCentre      | 3        | 1.26%   |
| Gigabyte F2A68HM-DS2    | 3        | 1.26%   |
| Dell Precision          | 3        | 1.26%   |
| ASUS M5A78L-M           | 3        | 1.26%   |
| MSI MS-7C02             | 2        | 0.84%   |
| MSI MS-7592             | 2        | 0.84%   |
| Lenovo IdeaCentre       | 2        | 0.84%   |
| HP ProLiant             | 2        | 0.84%   |
| Gigabyte P43-ES3G       | 2        | 0.84%   |
| Gigabyte H61M-S1        | 2        | 0.84%   |
| Gigabyte GA-MA78GM-US2H | 2        | 0.84%   |
| Gigabyte AB350-Gaming   | 2        | 0.84%   |
| Gigabyte 970A-DS3P      | 2        | 0.84%   |
| Foxconn G41MX           | 2        | 0.84%   |
| ASUS P5QL-E             | 2        | 0.84%   |
| ASUS P5KPL-AM           | 2        | 0.84%   |
| ASUS P5GC-MX            | 2        | 0.84%   |
| ASUS Maximus            | 2        | 0.84%   |
| ASUS M5A97              | 2        | 0.84%   |
| ASUS M4A88T-V           | 2        | 0.84%   |
| ASUS F2A55-M            | 2        | 0.84%   |
| ASRock N68C-S           | 2        | 0.84%   |
| ASRock K8A780LM         | 2        | 0.84%   |
| Unknown                 | 2        | 0.84%   |
| VIA KM266-8235          | 1        | 0.42%   |
| Techvision TVI7309X     | 1        | 0.42%   |
| Shuttle XH61V           | 1        | 0.42%   |
| Shuttle TERRA           | 1        | 0.42%   |
| Samsung DeskTop         | 1        | 0.42%   |
| Pegatron Elite          | 1        | 0.42%   |
| Pegatron Compaq         | 1        | 0.42%   |
| Packard Bell IPOWER     | 1        | 0.42%   |
| MSI MS-7D54             | 1        | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 31       | 12.97%  |
| 2009 | 26       | 10.88%  |
| 2013 | 22       | 9.21%   |
| 2008 | 21       | 8.79%   |
| 2014 | 17       | 7.11%   |
| 2019 | 15       | 6.28%   |
| 2018 | 15       | 6.28%   |
| 2006 | 13       | 5.44%   |
| 2020 | 12       | 5.02%   |
| 2011 | 12       | 5.02%   |
| 2007 | 12       | 5.02%   |
| 2010 | 11       | 4.6%    |
| 2015 | 9        | 3.77%   |
| 2016 | 8        | 3.35%   |
| 2017 | 5        | 2.09%   |
| 2021 | 3        | 1.26%   |
| 2022 | 2        | 0.84%   |
| 2005 | 2        | 0.84%   |
| 2002 | 1        | 0.42%   |
| 2001 | 1        | 0.42%   |
| 2000 | 1        | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 239      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 234      | 97.91%  |
| Enabled  | 5        | 2.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 239      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 59       | 23.6%   |
| 8.01-16.0   | 54       | 21.6%   |
| 4.01-8.0    | 48       | 19.2%   |
| 16.01-24.0  | 39       | 15.6%   |
| 32.01-64.0  | 19       | 7.6%    |
| 1.01-2.0    | 11       | 4.4%    |
| 2.01-3.0    | 6        | 2.4%    |
| 64.01-256.0 | 6        | 2.4%    |
| 0.51-1.0    | 4        | 1.6%    |
| 24.01-32.0  | 3        | 1.2%    |
| 0.01-0.5    | 1        | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 102      | 36.82%  |
| 2.01-3.0   | 57       | 20.58%  |
| 0.51-1.0   | 34       | 12.27%  |
| 3.01-4.0   | 27       | 9.75%   |
| 0.01-0.5   | 22       | 7.94%   |
| 4.01-8.0   | 20       | 7.22%   |
| 8.01-16.0  | 13       | 4.69%   |
| 24.01-32.0 | 1        | 0.36%   |
| 16.01-24.0 | 1        | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 107      | 40.68%  |
| 2      | 82       | 31.18%  |
| 3      | 33       | 12.55%  |
| 4      | 18       | 6.84%   |
| 5      | 12       | 4.56%   |
| 0      | 6        | 2.28%   |
| 6      | 3        | 1.14%   |
| 17     | 1        | 0.38%   |
| 7      | 1        | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 133      | 54.07%  |
| No        | 113      | 45.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 233      | 97.08%  |
| No        | 7        | 2.92%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 169      | 69.55%  |
| Yes       | 74       | 30.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 202      | 83.47%  |
| Yes       | 40       | 16.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Slovakia | 239      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Bratislava             | 74       | 28.14%  |
| Košice                | 29       | 11.03%  |
| Nitra                  | 11       | 4.18%   |
| Nové Zámky           | 7        | 2.66%   |
| Poprad                 | 6        | 2.28%   |
| Banská Bystrica       | 6        | 2.28%   |
| Zvolen                 | 4        | 1.52%   |
| Žilina                | 4        | 1.52%   |
| Trnava                 | 3        | 1.14%   |
| Tornaľa               | 3        | 1.14%   |
| Ružomberok            | 3        | 1.14%   |
| Rimavská Sobota       | 3        | 1.14%   |
| Prešov                | 3        | 1.14%   |
| Nitrianske Hrnciarovce | 3        | 1.14%   |
| Liptovský Mikuláš   | 3        | 1.14%   |
| Levice                 | 3        | 1.14%   |
| Trenčín              | 2        | 0.76%   |
| Soblahov               | 2        | 0.76%   |
| Smizany                | 2        | 0.76%   |
| Skalica                | 2        | 0.76%   |
| Senica                 | 2        | 0.76%   |
| Šaľa                 | 2        | 0.76%   |
| PetrЕѕalka           | 2        | 0.76%   |
| Modra                  | 2        | 0.76%   |
| Miloslavov             | 2        | 0.76%   |
| Martin                 | 2        | 0.76%   |
| Malacky                | 2        | 0.76%   |
| Lučenec               | 2        | 0.76%   |
| Kostolne Kracany       | 2        | 0.76%   |
| Kmetovce               | 2        | 0.76%   |
| Kalna                  | 2        | 0.76%   |
| Humenné               | 2        | 0.76%   |
| Cechynce               | 2        | 0.76%   |
| Bardejov               | 2        | 0.76%   |
| Zlate Moravce          | 1        | 0.38%   |
| Ziar nad Hronom        | 1        | 0.38%   |
| Zahradne               | 1        | 0.38%   |
| Vysoké Tatry          | 1        | 0.38%   |
| Vrable                 | 1        | 0.38%   |
| Vinicne                | 1        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 102      | 196    | 24.17%  |
| Seagate                   | 89       | 140    | 21.09%  |
| Samsung Electronics       | 66       | 115    | 15.64%  |
| Hitachi                   | 23       | 34     | 5.45%   |
| A-DATA Technology         | 17       | 26     | 4.03%   |
| Toshiba                   | 15       | 23     | 3.55%   |
| Kingston                  | 15       | 16     | 3.55%   |
| Patriot                   | 14       | 21     | 3.32%   |
| Intel                     | 11       | 18     | 2.61%   |
| Maxtor                    | 7        | 12     | 1.66%   |
| SanDisk                   | 6        | 7      | 1.42%   |
| Crucial                   | 6        | 7      | 1.42%   |
| KingDian                  | 4        | 4      | 0.95%   |
| HGST                      | 4        | 5      | 0.95%   |
| Unknown                   | 3        | 4      | 0.71%   |
| Phison                    | 3        | 3      | 0.71%   |
| OCZ                       | 3        | 3      | 0.71%   |
| Gigabyte Technology       | 3        | 5      | 0.71%   |
| Silicon Motion            | 2        | 3      | 0.47%   |
| Realtek Semiconductor     | 2        | 2      | 0.47%   |
| IBM/Hitachi               | 2        | 2      | 0.47%   |
| Corsair                   | 2        | 3      | 0.47%   |
| China                     | 2        | 4      | 0.47%   |
| Apacer                    | 2        | 2      | 0.47%   |
| XPG                       | 1        | 1      | 0.24%   |
| Verbatim                  | 1        | 1      | 0.24%   |
| USB3.0                    | 1        | 2      | 0.24%   |
| ULTIMATE                  | 1        | 2      | 0.24%   |
| PNY                       | 1        | 2      | 0.24%   |
| Micron/Crucial Technology | 1        | 1      | 0.24%   |
| Micron Technology         | 1        | 2      | 0.24%   |
| LITEONIT                  | 1        | 1      | 0.24%   |
| Intenso                   | 1        | 2      | 0.24%   |
| HS-SSD-E100               | 1        | 1      | 0.24%   |
| HS-SSD-C100               | 1        | 3      | 0.24%   |
| HGST HTS                  | 1        | 1      | 0.24%   |
| Hewlett-Packard           | 1        | 3      | 0.24%   |
| GOODRAM                   | 1        | 3      | 0.24%   |
| Fujitsu                   | 1        | 2      | 0.24%   |
| FORESEE                   | 1        | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB         | 6        | 1.2%    |
| Seagate ST2000DM008-2FR102 2TB   | 6        | 1.2%    |
| Samsung SSD 860 EVO 250GB        | 6        | 1.2%    |
| Samsung SSD 850 EVO 250GB        | 6        | 1.2%    |
| Patriot Burst 120GB SSD          | 6        | 1.2%    |
| Seagate ST3500418AS 500GB        | 5        | 1%      |
| Toshiba DT01ACA100 1TB           | 4        | 0.8%    |
| Seagate ST500DM002-1BD142 500GB  | 4        | 0.8%    |
| Seagate ST3320311CS 320GB        | 4        | 0.8%    |
| Seagate ST2000DM001-1CH164 2TB   | 4        | 0.8%    |
| Seagate ST1000DM003-1CH162 1TB   | 4        | 0.8%    |
| Samsung SSD 850 EVO 500GB        | 4        | 0.8%    |
| Kingston SV300S37A120G 120GB SSD | 4        | 0.8%    |
| WDC WDS500G2B0A-00SM50 500GB SSD | 3        | 0.6%    |
| WDC WD5000AAKX-75U6AA0 500GB     | 3        | 0.6%    |
| WDC WD10EZEX-00KUWA0 1TB         | 3        | 0.6%    |
| Seagate ST380815AS 80GB          | 3        | 0.6%    |
| Seagate ST3808110AS 80GB         | 3        | 0.6%    |
| Seagate ST1000DM003-1SB102 1TB   | 3        | 0.6%    |
| Samsung SSD 980 PRO 1TB          | 3        | 0.6%    |
| Samsung SSD 860 EVO 500GB        | 3        | 0.6%    |
| Samsung SSD 860 EVO 1TB          | 3        | 0.6%    |
| Patriot Burst 240GB SSD          | 3        | 0.6%    |
| Hitachi HTS543232A7A384 320GB    | 3        | 0.6%    |
| Hitachi HDS722020ALA330 2TB      | 3        | 0.6%    |
| Hitachi HDP725050GLA360 500GB    | 3        | 0.6%    |
| A-DATA SU700 120GB SSD           | 3        | 0.6%    |
| A-DATA SP600 32GB SSD            | 3        | 0.6%    |
| WDC WD6400AAKS-22A7B0 640GB      | 2        | 0.4%    |
| WDC WD5000AZRX-00L4HB0 500GB     | 2        | 0.4%    |
| WDC WD5000AAKX-22ERMA0 500GB     | 2        | 0.4%    |
| WDC WD5000AADS-00S9B0 500GB      | 2        | 0.4%    |
| WDC WD40EZRZ-00GXCB0 4TB         | 2        | 0.4%    |
| WDC WD400JB-00JJC0 40GB          | 2        | 0.4%    |
| WDC WD4005FZBX-00K5WB0 4TB       | 2        | 0.4%    |
| WDC WD3200BB-00KEA0 320GB        | 2        | 0.4%    |
| WDC WD3200AAKS-00VYA0 320GB      | 2        | 0.4%    |
| WDC WD2502ABYS-01B7A0 256GB      | 2        | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB         | 2        | 0.4%    |
| WDC WD20EZRX-00D8PB0 2TB         | 2        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 101      | 189    | 38.4%   |
| Seagate             | 87       | 137    | 33.08%  |
| Hitachi             | 23       | 34     | 8.75%   |
| Samsung Electronics | 20       | 30     | 7.6%    |
| Toshiba             | 13       | 19     | 4.94%   |
| Maxtor              | 7        | 12     | 2.66%   |
| HGST                | 4        | 5      | 1.52%   |
| IBM/Hitachi         | 2        | 2      | 0.76%   |
| USB3.0              | 1        | 2      | 0.38%   |
| Unknown             | 1        | 1      | 0.38%   |
| HGST HTS            | 1        | 1      | 0.38%   |
| Hewlett-Packard     | 1        | 3      | 0.38%   |
| Fujitsu             | 1        | 2      | 0.38%   |
| ExcelStor           | 1        | 1      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 35       | 50     | 28.69%  |
| A-DATA Technology   | 16       | 25     | 13.11%  |
| Patriot             | 13       | 20     | 10.66%  |
| Kingston            | 11       | 12     | 9.02%   |
| Intel               | 9        | 16     | 7.38%   |
| Crucial             | 6        | 7      | 4.92%   |
| WDC                 | 5        | 6      | 4.1%    |
| SanDisk             | 3        | 3      | 2.46%   |
| OCZ                 | 3        | 3      | 2.46%   |
| Gigabyte Technology | 3        | 5      | 2.46%   |
| KingDian            | 2        | 2      | 1.64%   |
| China               | 2        | 4      | 1.64%   |
| Apacer              | 2        | 2      | 1.64%   |
| Verbatim            | 1        | 1      | 0.82%   |
| ULTIMATE            | 1        | 2      | 0.82%   |
| Toshiba             | 1        | 1      | 0.82%   |
| PNY                 | 1        | 2      | 0.82%   |
| Micron Technology   | 1        | 2      | 0.82%   |
| LITEONIT            | 1        | 1      | 0.82%   |
| Intenso             | 1        | 2      | 0.82%   |
| HS-SSD-C100         | 1        | 3      | 0.82%   |
| GOODRAM             | 1        | 3      | 0.82%   |
| FORESEE             | 1        | 2      | 0.82%   |
| Corsair             | 1        | 1      | 0.82%   |
| AMD                 | 1        | 1      | 0.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 190      | 438    | 56.21%  |
| SSD     | 106      | 176    | 31.36%  |
| NVMe    | 36       | 66     | 10.65%  |
| Unknown | 6        | 7      | 1.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 222      | 608    | 83.46%  |
| NVMe | 36       | 66     | 13.53%  |
| SAS  | 8        | 13     | 3.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 192      | 386    | 59.44%  |
| 0.51-1.0   | 74       | 130    | 22.91%  |
| 1.01-2.0   | 33       | 53     | 10.22%  |
| 3.01-4.0   | 13       | 23     | 4.02%   |
| 2.01-3.0   | 8        | 14     | 2.48%   |
| 4.01-10.0  | 2        | 7      | 0.62%   |
| 10.01-20.0 | 1        | 1      | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 64       | 23.36%  |
| 251-500        | 50       | 18.25%  |
| 1-20           | 41       | 14.96%  |
| 501-1000       | 34       | 12.41%  |
| Unknown        | 23       | 8.39%   |
| 1001-2000      | 19       | 6.93%   |
| 51-100         | 18       | 6.57%   |
| 21-50          | 10       | 3.65%   |
| More than 3000 | 8        | 2.92%   |
| 2001-3000      | 7        | 2.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 110      | 40%     |
| 21-50          | 43       | 15.64%  |
| 101-250        | 31       | 11.27%  |
| Unknown        | 23       | 8.36%   |
| 51-100         | 20       | 7.27%   |
| 501-1000       | 18       | 6.55%   |
| 251-500        | 17       | 6.18%   |
| 1001-2000      | 8        | 2.91%   |
| More than 3000 | 3        | 1.09%   |
| 2001-3000      | 2        | 0.73%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST9500325AS 500GB             | 2        | 3      | 4.35%   |
| Seagate ST3320413CS 320GB             | 2        | 2      | 4.35%   |
| Kingston SV300S37A60G 64GB SSD        | 2        | 2      | 4.35%   |
| WDC WD800JD-60LSA0 80GB               | 1        | 1      | 2.17%   |
| WDC WD7500BPVT-24HXZT3 752GB          | 1        | 1      | 2.17%   |
| WDC WD3200AAJS-56B4A0 320GB           | 1        | 2      | 2.17%   |
| WDC WD2500AAKX-753CA1 250GB           | 1        | 1      | 2.17%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1        | 1      | 2.17%   |
| WDC WD20EURS-63S48Y0 2TB              | 1        | 1      | 2.17%   |
| WDC WD1600JS-61MHB1 160GB             | 1        | 1      | 2.17%   |
| WDC WD10EZEX-75WN4A0 1TB              | 1        | 2      | 2.17%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 2.17%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1        | 1      | 2.17%   |
| WDC WD10EZEX-00KUWA0 1TB              | 1        | 1      | 2.17%   |
| WDC WD10EALX-009BA0 1TB               | 1        | 1      | 2.17%   |
| Toshiba MK7575GSX 752GB               | 1        | 2      | 2.17%   |
| Seagate ST980811AS 80GB               | 1        | 1      | 2.17%   |
| Seagate ST9250315AS 250GB             | 1        | 1      | 2.17%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 2.17%   |
| Seagate ST3500312CS 500GB             | 1        | 1      | 2.17%   |
| Seagate ST3402111A 40GB               | 1        | 1      | 2.17%   |
| Seagate ST320LT007-9ZV142 320GB       | 1        | 1      | 2.17%   |
| Seagate ST31000322CS 1TB              | 1        | 2      | 2.17%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 2.17%   |
| Seagate ST2000VX000-1CU164 2TB        | 1        | 1      | 2.17%   |
| Seagate ST1000LM035-1RK172 1TB        | 1        | 1      | 2.17%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 2.17%   |
| Samsung Electronics HD753LJ 752GB     | 1        | 4      | 2.17%   |
| Samsung Electronics HD320KJ 320GB     | 1        | 1      | 2.17%   |
| Samsung Electronics HD154UI 1TB       | 1        | 1      | 2.17%   |
| OCZ VERTEX4 256GB SSD                 | 1        | 1      | 2.17%   |
| OCZ AGILITY3 240GB SSD                | 1        | 1      | 2.17%   |
| Maxtor 6L200M0 208GB                  | 1        | 1      | 2.17%   |
| Maxtor 6L080P0 81GB                   | 1        | 1      | 2.17%   |
| Maxtor 6E040L0 41GB                   | 1        | 1      | 2.17%   |
| IBM/Hitachi IC25N030ATCS04-0 32GB     | 1        | 1      | 2.17%   |
| Hitachi HTS543232A7A384 320GB         | 1        | 1      | 2.17%   |
| Hitachi HDP725032GLA360 320GB         | 1        | 1      | 2.17%   |
| Hitachi HDP725025GLA380 250GB         | 1        | 1      | 2.17%   |
| Fujitsu MHV2060BH PL 64GB             | 1        | 2      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 16     | 31.11%  |
| WDC                 | 11       | 14     | 24.44%  |
| Samsung Electronics | 4        | 7      | 8.89%   |
| Maxtor              | 3        | 3      | 6.67%   |
| Hitachi             | 3        | 3      | 6.67%   |
| OCZ                 | 2        | 2      | 4.44%   |
| Kingston            | 2        | 2      | 4.44%   |
| Toshiba             | 1        | 2      | 2.22%   |
| IBM/Hitachi         | 1        | 1      | 2.22%   |
| Fujitsu             | 1        | 2      | 2.22%   |
| ExcelStor           | 1        | 1      | 2.22%   |
| Crucial             | 1        | 1      | 2.22%   |
| A-DATA Technology   | 1        | 1      | 2.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 16     | 36.84%  |
| WDC                 | 11       | 14     | 28.95%  |
| Samsung Electronics | 3        | 6      | 7.89%   |
| Maxtor              | 3        | 3      | 7.89%   |
| Hitachi             | 3        | 3      | 7.89%   |
| Toshiba             | 1        | 2      | 2.63%   |
| IBM/Hitachi         | 1        | 1      | 2.63%   |
| Fujitsu             | 1        | 2      | 2.63%   |
| ExcelStor           | 1        | 1      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 35       | 48     | 83.33%  |
| SSD  | 6        | 6      | 14.29%  |
| NVMe | 1        | 1      | 2.38%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba MK5065GSX 500GB           | 2        | 2      | 40%     |
| Seagate ST3500418AS 500GB         | 1        | 2      | 20%     |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 20%     |
| Samsung Electronics HD321HJ 320GB | 1        | 2      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 2        | 2      | 40%     |
| Seagate             | 2        | 3      | 40%     |
| Samsung Electronics | 1        | 2      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 131      | 339    | 47.29%  |
| Works    | 102      | 286    | 36.82%  |
| Malfunc  | 39       | 55     | 14.08%  |
| Failed   | 5        | 7      | 1.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 154      | 49.2%   |
| AMD                          | 66       | 21.09%  |
| Samsung Electronics          | 18       | 5.75%   |
| JMicron Technology           | 17       | 5.43%   |
| Nvidia                       | 13       | 4.15%   |
| ASMedia Technology           | 10       | 3.19%   |
| Marvell Technology Group     | 6        | 1.92%   |
| VIA Technologies             | 5        | 1.6%    |
| Phison Electronics           | 5        | 1.6%    |
| SanDisk                      | 4        | 1.28%   |
| Kingston Technology Company  | 4        | 1.28%   |
| Silicon Motion               | 2        | 0.64%   |
| Realtek Semiconductor        | 2        | 0.64%   |
| ADATA Technology             | 2        | 0.64%   |
| ULi Electronics              | 1        | 0.32%   |
| Toshiba America Info Systems | 1        | 0.32%   |
| Micron/Crucial Technology    | 1        | 0.32%   |
| LSI Logic / Symbios Logic    | 1        | 0.32%   |
| Hewlett-Packard              | 1        | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 33       | 7.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26       | 6.12%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 23       | 5.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 3.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 16       | 3.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15       | 3.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 12       | 2.82%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 11       | 2.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11       | 2.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10       | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 2.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 2.35%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 2.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 2.12%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 8        | 1.88%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 8        | 1.88%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 1.88%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 1.41%   |
| Nvidia MCP61 IDE                                                                        | 6        | 1.41%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 1.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.18%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 1.18%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 1.18%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 1.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.94%   |
| JMicron JMB368 IDE controller                                                           | 4        | 0.94%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.94%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 0.94%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 0.94%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3        | 0.71%   |
| Phison E12 NVMe Controller                                                              | 3        | 0.71%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 3        | 0.71%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.71%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 0.71%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 0.71%   |
| AMD FCH SATA Controller D                                                               | 3        | 0.71%   |
| AMD FCH IDE Controller                                                                  | 3        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 161      | 51.44%  |
| IDE  | 102      | 32.59%  |
| NVMe | 36       | 11.5%   |
| RAID | 13       | 4.15%   |
| SCSI | 1        | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 156      | 65.27%  |
| AMD          | 82       | 34.31%  |
| CentaurHauls | 1        | 0.42%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 7        | 2.89%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz   | 6        | 2.48%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 4        | 1.65%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 4        | 1.65%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 4        | 1.65%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 3        | 1.24%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 3        | 1.24%   |
| Intel Core i3-9100 CPU @ 3.60GHz        | 3        | 1.24%   |
| Intel Core i3-8100 CPU @ 3.60GHz        | 3        | 1.24%   |
| Intel Core i3-4170 CPU @ 3.70GHz        | 3        | 1.24%   |
| Intel Core i3-10100 CPU @ 3.60GHz       | 3        | 1.24%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 3        | 1.24%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 3        | 1.24%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 3        | 1.24%   |
| Intel Xeon CPU X5450 @ 3.00GHz          | 2        | 0.83%   |
| Intel Pentium 4 CPU 3.00GHz             | 2        | 0.83%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 2        | 0.83%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 2        | 0.83%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2        | 0.83%   |
| Intel Core i7 CPU 920 @ 2.67GHz         | 2        | 0.83%   |
| Intel Core i5-6600 CPU @ 3.30GHz        | 2        | 0.83%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 2        | 0.83%   |
| Intel Core i5-4670K CPU @ 3.40GHz       | 2        | 0.83%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 2        | 0.83%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 2        | 0.83%   |
| Intel Core i5 CPU 750 @ 2.67GHz         | 2        | 0.83%   |
| Intel Core i3-3225 CPU @ 3.30GHz        | 2        | 0.83%   |
| Intel Core i3-3220 CPU @ 3.30GHz        | 2        | 0.83%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz    | 2        | 0.83%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz    | 2        | 0.83%   |
| Intel Celeron CPU G1610 @ 2.60GHz       | 2        | 0.83%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 2        | 0.83%   |
| AMD Ryzen 7 2700 Eight-Core Processor   | 2        | 0.83%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 2        | 0.83%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2        | 0.83%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 2        | 0.83%   |
| AMD Phenom II X2 555 Processor          | 2        | 0.83%   |
| AMD Athlon Dual Core Processor 4850e    | 2        | 0.83%   |
| AMD Athlon 64 Processor 3200+           | 2        | 0.83%   |
| AMD A4-5300 APU with Radeon HD Graphics | 2        | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 37       | 15.29%  |
| Intel Core i3           | 22       | 9.09%   |
| Intel Core i7           | 19       | 7.85%   |
| Intel Core 2 Duo        | 17       | 7.02%   |
| Intel Core 2 Quad       | 16       | 6.61%   |
| Intel Celeron           | 11       | 4.55%   |
| AMD Ryzen 5             | 11       | 4.55%   |
| Intel Xeon              | 10       | 4.13%   |
| AMD Ryzen 7             | 9        | 3.72%   |
| AMD Athlon 64 X2        | 7        | 2.89%   |
| Intel Pentium           | 6        | 2.48%   |
| AMD Ryzen 9             | 6        | 2.48%   |
| AMD Athlon II X2        | 5        | 2.07%   |
| AMD Sempron             | 4        | 1.65%   |
| AMD Phenom II X4        | 4        | 1.65%   |
| AMD FX                  | 4        | 1.65%   |
| AMD Athlon 64           | 4        | 1.65%   |
| Other                   | 3        | 1.24%   |
| Intel Pentium Dual-Core | 3        | 1.24%   |
| Intel Pentium 4         | 3        | 1.24%   |
| Intel Core 2            | 3        | 1.24%   |
| Intel Atom              | 3        | 1.24%   |
| AMD Phenom              | 3        | 1.24%   |
| AMD Athlon X4           | 3        | 1.24%   |
| AMD A8                  | 3        | 1.24%   |
| AMD A10                 | 3        | 1.24%   |
| Intel Pentium Dual      | 2        | 0.83%   |
| AMD Phenom II X6        | 2        | 0.83%   |
| AMD Phenom II X2        | 2        | 0.83%   |
| AMD Athlon Dual Core    | 2        | 0.83%   |
| AMD Athlon              | 2        | 0.83%   |
| AMD A6                  | 2        | 0.83%   |
| AMD A4                  | 2        | 0.83%   |
| Intel Pentium D         | 1        | 0.41%   |
| Intel Genuine           | 1        | 0.41%   |
| Intel Core i9           | 1        | 0.41%   |
| CentaurHauls VIA Esther | 1        | 0.41%   |
| AMD Ryzen 5 PRO         | 1        | 0.41%   |
| AMD Ryzen 3             | 1        | 0.41%   |
| AMD Athlon XP           | 1        | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 103      | 42.39%  |
| 2       | 84       | 34.57%  |
| 6       | 16       | 6.58%   |
| 1       | 15       | 6.17%   |
| 8       | 13       | 5.35%   |
| 12      | 5        | 2.06%   |
| Unknown | 2        | 0.82%   |
| 24      | 1        | 0.41%   |
| 20      | 1        | 0.41%   |
| 16      | 1        | 0.41%   |
| 10      | 1        | 0.41%   |
| 3       | 1        | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 238      | 99.58%  |
| 2      | 1        | 0.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 147      | 61.25%  |
| 2       | 91       | 37.92%  |
| Unknown | 2        | 0.83%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 235      | 98.33%  |
| 32-bit         | 3        | 1.26%   |
| 64-bit         | 1        | 0.42%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 56       | 22.49%  |
| 0x1067a    | 21       | 8.43%   |
| 0x306a9    | 19       | 7.63%   |
| 0x306c3    | 18       | 7.23%   |
| 0x6fb      | 13       | 5.22%   |
| 0x906e9    | 7        | 2.81%   |
| 0x206a7    | 7        | 2.81%   |
| 0x506e3    | 6        | 2.41%   |
| 0x06001119 | 6        | 2.41%   |
| 0x010000c8 | 6        | 2.41%   |
| 0x6fd      | 5        | 2.01%   |
| 0x906eb    | 4        | 1.61%   |
| 0x6f2      | 4        | 1.61%   |
| 0x08701021 | 4        | 1.61%   |
| 0xa0653    | 3        | 1.2%    |
| 0x906ea    | 3        | 1.2%    |
| 0x0a201016 | 3        | 1.2%    |
| 0x08108109 | 3        | 1.2%    |
| 0x0800820d | 3        | 1.2%    |
| 0x01000083 | 3        | 1.2%    |
| 0xf43      | 2        | 0.8%    |
| 0x406c3    | 2        | 0.8%    |
| 0x30661    | 2        | 0.8%    |
| 0x20652    | 2        | 0.8%    |
| 0x106a5    | 2        | 0.8%    |
| 0x0a201009 | 2        | 0.8%    |
| 0x08701013 | 2        | 0.8%    |
| 0x08001138 | 2        | 0.8%    |
| 0x0700010f | 2        | 0.8%    |
| 0x06003106 | 2        | 0.8%    |
| 0x010000c7 | 2        | 0.8%    |
| 0x01000086 | 2        | 0.8%    |
| 0xf64      | 1        | 0.4%    |
| 0xf4a      | 1        | 0.4%    |
| 0xb0671    | 1        | 0.4%    |
| 0x906ed    | 1        | 0.4%    |
| 0x906ec    | 1        | 0.4%    |
| 0x906c0    | 1        | 0.4%    |
| 0x90672    | 1        | 0.4%    |
| 0x6f6      | 1        | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 25       | 10.42%  |
| Haswell          | 24       | 10%     |
| Core             | 23       | 9.58%   |
| IvyBridge        | 22       | 9.17%   |
| KabyLake         | 20       | 8.33%   |
| K10              | 20       | 8.33%   |
| K8 Hammer        | 15       | 6.25%   |
| SandyBridge      | 10       | 4.17%   |
| Zen 2            | 9        | 3.75%   |
| Piledriver       | 9        | 3.75%   |
| Zen+             | 8        | 3.33%   |
| Zen 3            | 7        | 2.92%   |
| Skylake          | 7        | 2.92%   |
| Steamroller      | 5        | 2.08%   |
| Zen              | 4        | 1.67%   |
| NetBurst         | 4        | 1.67%   |
| Nehalem          | 4        | 1.67%   |
| Westmere         | 3        | 1.25%   |
| CometLake        | 3        | 1.25%   |
| Bonnell          | 3        | 1.25%   |
| Unknown          | 3        | 1.25%   |
| Silvermont       | 2        | 0.83%   |
| Jaguar           | 2        | 0.83%   |
| Tremont          | 1        | 0.42%   |
| P6               | 1        | 0.42%   |
| K6               | 1        | 0.42%   |
| K10 Llano        | 1        | 0.42%   |
| Excavator        | 1        | 0.42%   |
| Bulldozer        | 1        | 0.42%   |
| Broadwell        | 1        | 0.42%   |
| Alderlake Hybrid | 1        | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 95       | 36.54%  |
| AMD                        | 92       | 35.38%  |
| Intel                      | 70       | 26.92%  |
| VIA Technologies           | 1        | 0.38%   |
| S3 Graphics                | 1        | 0.38%   |
| Matrox Electronics Systems | 1        | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                                                           | 11       | 3.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 3.97%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 8        | 2.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7        | 2.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7        | 2.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7        | 2.53%   |
| AMD RS780L [Radeon 3000]                                                                 | 6        | 2.17%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5        | 1.81%   |
| Intel HD Graphics 530                                                                    | 5        | 1.81%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5        | 1.81%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 1.44%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 4        | 1.44%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 1.44%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4        | 1.44%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 4        | 1.44%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 3        | 1.08%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 3        | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3        | 1.08%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 3        | 1.08%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3        | 1.08%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 3        | 1.08%   |
| Intel HD Graphics 630                                                                    | 3        | 1.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 1.08%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3        | 1.08%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 3        | 1.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 1.08%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                                       | 2        | 0.72%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 0.72%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 2        | 0.72%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2        | 0.72%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 2        | 0.72%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 2        | 0.72%   |
| Nvidia G92 [GeForce 9800 GT]                                                             | 2        | 0.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 0.72%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.72%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2        | 0.72%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 0.72%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 2        | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 84       | 34.15%  |
| 1 x AMD         | 77       | 31.3%   |
| 1 x Intel       | 60       | 24.39%  |
| 2 x AMD         | 10       | 4.07%   |
| AMD + Nvidia    | 5        | 2.03%   |
| Intel + Nvidia  | 4        | 1.63%   |
| 3 x AMD         | 1        | 0.41%   |
| 2 x Nvidia      | 1        | 0.41%   |
| 1 x VIA         | 1        | 0.41%   |
| 1 x S3 Graphics | 1        | 0.41%   |
| 1 x Matrox      | 1        | 0.41%   |
| Intel + AMD     | 1        | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 195      | 77.69%  |
| Proprietary | 41       | 16.33%  |
| Unknown     | 15       | 5.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 94       | 36.43%  |
| 0.01-0.5   | 47       | 18.22%  |
| 0.51-1.0   | 46       | 17.83%  |
| 1.01-2.0   | 29       | 11.24%  |
| 3.01-4.0   | 15       | 5.81%   |
| 7.01-8.0   | 11       | 4.26%   |
| 5.01-6.0   | 9        | 3.49%   |
| 8.01-16.0  | 3        | 1.16%   |
| 2.01-3.0   | 2        | 0.78%   |
| 16.01-24.0 | 2        | 0.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 37       | 14.74%  |
| Dell                 | 25       | 9.96%   |
| Goldstar             | 23       | 9.16%   |
| BenQ                 | 23       | 9.16%   |
| Philips              | 22       | 8.76%   |
| Hewlett-Packard      | 21       | 8.37%   |
| Ancor Communications | 16       | 6.37%   |
| AOC                  | 11       | 4.38%   |
| NEC Computers        | 10       | 3.98%   |
| Acer                 | 10       | 3.98%   |
| Iiyama               | 6        | 2.39%   |
| Fujitsu Siemens      | 5        | 1.99%   |
| Unknown              | 4        | 1.59%   |
| LG Electronics       | 4        | 1.59%   |
| Eizo                 | 4        | 1.59%   |
| Sony                 | 2        | 0.8%    |
| RTD                  | 2        | 0.8%    |
| MiTAC                | 2        | 0.8%    |
| Lenovo               | 2        | 0.8%    |
| FUS                  | 2        | 0.8%    |
| CVT                  | 2        | 0.8%    |
| Vestel Elektronik    | 1        | 0.4%    |
| Valve                | 1        | 0.4%    |
| S2-Tek               | 1        | 0.4%    |
| PTC                  | 1        | 0.4%    |
| Pioneer              | 1        | 0.4%    |
| Onkyo                | 1        | 0.4%    |
| MSI                  | 1        | 0.4%    |
| Lite-On              | 1        | 0.4%    |
| Jean                 | 1        | 0.4%    |
| InfoVision           | 1        | 0.4%    |
| IBM                  | 1        | 0.4%    |
| FZC                  | 1        | 0.4%    |
| Elo Touch            | 1        | 0.4%    |
| DENON                | 1        | 0.4%    |
| D&T                  | 1        | 0.4%    |
| ASUSTek Computer     | 1        | 0.4%    |
| Arnos Instruments    | 1        | 0.4%    |
| ADV                  | 1        | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 6        | 2.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 6        | 2.21%   |
| NEC Computers LCD19WV NEC671C 1440x900 410x256mm 19.0-inch             | 4        | 1.48%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 4        | 1.48%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch      | 3        | 1.11%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 3        | 1.11%   |
| Unknown 1780 07E7 1280x1024 337x270mm 17.0-inch                        | 2        | 0.74%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch   | 2        | 0.74%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch   | 2        | 0.74%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch      | 2        | 0.74%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2        | 0.74%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2        | 0.74%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch  | 2        | 0.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2        | 0.74%   |
| RTD LR762 RTD2023 1280x1024 307x230mm 15.1-inch                        | 2        | 0.74%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 2        | 0.74%   |
| Philips 241BLPY PHL08B3 1920x1080 531x299mm 24.0-inch                  | 2        | 0.74%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                     | 2        | 0.74%   |
| MiTAC DSGi TV SZM0308 1920x540 708x398mm 32.0-inch                     | 2        | 0.74%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch           | 2        | 0.74%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                      | 2        | 0.74%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                      | 2        | 0.74%   |
| CVT CVTE TV CVT0003 1360x768 575x323mm 26.0-inch                       | 2        | 0.74%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                      | 2        | 0.74%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                      | 2        | 0.74%   |
| AOC 24B1W1G5 AOC2401 1920x1080 527x296mm 23.8-inch                     | 2        | 0.74%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                        | 2        | 0.74%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 2        | 0.74%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch       | 2        | 0.74%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch  | 2        | 0.74%   |
| Ancor Communications ASUS MK241 ACI24A1 1920x1200 550x350mm 25.7-inch  | 2        | 0.74%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch  | 1        | 0.37%   |
| Valve Index HMD VLV91A8 0x17                                           | 1        | 0.37%   |
| Unknown LCD Monitor XXX Beyond TV 3840x2160                            | 1        | 0.37%   |
| Unknown LCD Monitor BenQG2222HDL 1920x1080                             | 1        | 0.37%   |
| Sony TV *00 SNY8404 3840x2160 1218x685mm 55.0-inch                     | 1        | 0.37%   |
| Sony TV  *00 SNY4904 3840x2160                                         | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch    | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch   | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM049C 1920x1080 477x268mm 21.5-inch   | 1        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 102      | 40.96%  |
| 1280x1024 (SXGA)   | 30       | 12.05%  |
| 1920x1200 (WUXGA)  | 20       | 8.03%   |
| 1680x1050 (WSXGA+) | 17       | 6.83%   |
| 3840x2160 (4K)     | 15       | 6.02%   |
| 2560x1440 (QHD)    | 15       | 6.02%   |
| 1440x900 (WXGA+)   | 15       | 6.02%   |
| 1366x768 (WXGA)    | 9        | 3.61%   |
| 1600x1200          | 7        | 2.81%   |
| 1600x900 (HD+)     | 6        | 2.41%   |
| 3440x1440          | 3        | 1.2%    |
| 1360x768           | 3        | 1.2%    |
| 1920x540           | 2        | 0.8%    |
| 1024x768 (XGA)     | 2        | 0.8%    |
| 1280x960           | 1        | 0.4%    |
| 1280x720 (HD)      | 1        | 0.4%    |
| Unknown            | 1        | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 43       | 16.73%  |
| 23      | 34       | 13.23%  |
| 21      | 28       | 10.89%  |
| 19      | 26       | 10.12%  |
| 27      | 22       | 8.56%   |
| Unknown | 20       | 7.78%   |
| 17      | 17       | 6.61%   |
| 22      | 9        | 3.5%    |
| 20      | 9        | 3.5%    |
| 18      | 9        | 3.5%    |
| 25      | 7        | 2.72%   |
| 84      | 4        | 1.56%   |
| 31      | 4        | 1.56%   |
| 26      | 4        | 1.56%   |
| 72      | 2        | 0.78%   |
| 65      | 2        | 0.78%   |
| 54      | 2        | 0.78%   |
| 48      | 2        | 0.78%   |
| 46      | 2        | 0.78%   |
| 39      | 2        | 0.78%   |
| 34      | 2        | 0.78%   |
| 15      | 2        | 0.78%   |
| 42      | 1        | 0.39%   |
| 35      | 1        | 0.39%   |
| 32      | 1        | 0.39%   |
| 14      | 1        | 0.39%   |
| 11      | 1        | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 95       | 38.62%  |
| 401-500     | 72       | 29.27%  |
| Unknown     | 20       | 8.13%   |
| 301-350     | 19       | 7.72%   |
| 351-400     | 12       | 4.88%   |
| 1001-1500   | 8        | 3.25%   |
| 1501-2000   | 6        | 2.44%   |
| 601-700     | 5        | 2.03%   |
| 801-900     | 3        | 1.22%   |
| 701-800     | 3        | 1.22%   |
| 201-300     | 2        | 0.81%   |
| 901-1000    | 1        | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 128      | 52.67%  |
| 16/10   | 52       | 21.4%   |
| 5/4     | 28       | 11.52%  |
| Unknown | 16       | 6.58%   |
| 4/3     | 12       | 4.94%   |
| 3/2     | 3        | 1.23%   |
| 21/9    | 3        | 1.23%   |
| 6/5     | 1        | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 85       | 33.46%  |
| 151-200        | 45       | 17.72%  |
| 251-300        | 30       | 11.81%  |
| 141-150        | 24       | 9.45%   |
| 301-350        | 22       | 8.66%   |
| Unknown        | 20       | 7.87%   |
| More than 1000 | 11       | 4.33%   |
| 351-500        | 8        | 3.15%   |
| 501-1000       | 5        | 1.97%   |
| 101-110        | 2        | 0.79%   |
| 51-60          | 1        | 0.39%   |
| 111-120        | 1        | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 168      | 70.29%  |
| 101-120 | 35       | 14.64%  |
| Unknown | 20       | 8.37%   |
| 1-50    | 9        | 3.77%   |
| 121-160 | 4        | 1.67%   |
| 161-240 | 3        | 1.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 200      | 80.65%  |
| 2     | 34       | 13.71%  |
| 0     | 11       | 4.44%   |
| 3     | 3        | 1.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 138      | 45.1%   |
| Intel                                  | 70       | 22.88%  |
| Qualcomm Atheros                       | 19       | 6.21%   |
| Ralink Technology                      | 13       | 4.25%   |
| TP-Link                                | 11       | 3.59%   |
| Nvidia                                 | 11       | 3.59%   |
| Qualcomm Atheros Communications        | 9        | 2.94%   |
| Broadcom                               | 8        | 2.61%   |
| Marvell Technology Group               | 5        | 1.63%   |
| Broadcom Limited                       | 4        | 1.31%   |
| Edimax Technology                      | 2        | 0.65%   |
| ASUSTek Computer                       | 2        | 0.65%   |
| WiseGroup                              | 1        | 0.33%   |
| VIA Technologies                       | 1        | 0.33%   |
| ULi Electronics                        | 1        | 0.33%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.33%   |
| Samsung Electronics                    | 1        | 0.33%   |
| Pulse-Eight                            | 1        | 0.33%   |
| Prestigio                              | 1        | 0.33%   |
| National Semiconductor                 | 1        | 0.33%   |
| Microsoft                              | 1        | 0.33%   |
| Micro Star International               | 1        | 0.33%   |
| Huawei Technologies                    | 1        | 0.33%   |
| D-Link                                 | 1        | 0.33%   |
| ASIX Electronics                       | 1        | 0.33%   |
| Accton Technology                      | 1        | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 114      | 33.83%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11       | 3.26%   |
| Intel I211 Gigabit Network Connection                             | 11       | 3.26%   |
| Qualcomm Atheros AR9271 802.11n                                   | 9        | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 2.67%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 2.37%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 1.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 6        | 1.78%   |
| Intel Wi-Fi 6 AX200                                               | 6        | 1.78%   |
| Nvidia MCP61 Ethernet                                             | 5        | 1.48%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.48%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 4        | 1.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.19%   |
| Intel Ethernet Controller I225-V                                  | 4        | 1.19%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.19%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.19%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.89%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 0.89%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.89%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.89%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.89%   |
| Intel Wireless 8260                                               | 3        | 0.89%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 0.89%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                             | 2        | 0.59%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 0.59%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.59%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 2        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.59%   |
| Intel 82578DC Gigabit Network Connection                          | 2        | 0.59%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.59%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.59%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.59%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 2        | 0.59%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 2        | 0.59%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]   | 2        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 17       | 22.37%  |
| Realtek Semiconductor           | 13       | 17.11%  |
| Ralink Technology               | 13       | 17.11%  |
| TP-Link                         | 11       | 14.47%  |
| Qualcomm Atheros Communications | 9        | 11.84%  |
| Qualcomm Atheros                | 3        | 3.95%   |
| Edimax Technology               | 2        | 2.63%   |
| Broadcom                        | 2        | 2.63%   |
| ASUSTek Computer                | 2        | 2.63%   |
| Microsoft                       | 1        | 1.32%   |
| Micro Star International        | 1        | 1.32%   |
| D-Link                          | 1        | 1.32%   |
| Accton Technology               | 1        | 1.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                               | 9        | 11.84%  |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 6        | 7.89%   |
| Intel Wi-Fi 6 AX200                                                           | 6        | 7.89%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 4        | 5.26%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 3        | 3.95%   |
| Ralink RT5370 Wireless Adapter                                                | 3        | 3.95%   |
| Ralink MT7601U Wireless Adapter                                               | 3        | 3.95%   |
| Intel Wireless 8260                                                           | 3        | 3.95%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 2        | 2.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 2.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2        | 2.63%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 2        | 2.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2        | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 2.63%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]               | 2        | 2.63%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 1.32%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                     | 1        | 1.32%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 1.32%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 1.32%   |
| TP-Link 802.11ac NIC                                                          | 1        | 1.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 1.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1        | 1.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1        | 1.32%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 1.32%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1        | 1.32%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1        | 1.32%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 1        | 1.32%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 1.32%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 1.32%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]    | 1        | 1.32%   |
| Intel WLAN controller                                                         | 1        | 1.32%   |
| Intel Wireless-AC 9260                                                        | 1        | 1.32%   |
| Intel Centrino Wireless-N 2230                                                | 1        | 1.32%   |
| Intel Centrino Advanced-N 6235                                                | 1        | 1.32%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                      | 1        | 1.32%   |
| Edimax AC600 USB                                                              | 1        | 1.32%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]                 | 1        | 1.32%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 1.32%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller           | 1        | 1.32%   |
| Accton SMCWUSB-G 802.11bg                                                     | 1        | 1.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 136      | 55.06%  |
| Intel                                  | 62       | 25.1%   |
| Qualcomm Atheros                       | 16       | 6.48%   |
| Nvidia                                 | 11       | 4.45%   |
| Broadcom                               | 6        | 2.43%   |
| Marvell Technology Group               | 5        | 2.02%   |
| Broadcom Limited                       | 4        | 1.62%   |
| VIA Technologies                       | 1        | 0.4%    |
| Sony Ericsson Mobile Communications AB | 1        | 0.4%    |
| Samsung Electronics                    | 1        | 0.4%    |
| Prestigio                              | 1        | 0.4%    |
| National Semiconductor                 | 1        | 0.4%    |
| Huawei Technologies                    | 1        | 0.4%    |
| ASIX Electronics                       | 1        | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 114      | 44.19%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11       | 4.26%   |
| Intel I211 Gigabit Network Connection                             | 11       | 4.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 3.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 3.1%    |
| Intel Ethernet Connection (2) I219-V                              | 7        | 2.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 2.33%   |
| Nvidia MCP61 Ethernet                                             | 5        | 1.94%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.55%   |
| Intel Ethernet Controller I225-V                                  | 4        | 1.55%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.16%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 1.16%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 1.16%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.16%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.78%   |
| Intel 82578DC Gigabit Network Connection                          | 2        | 0.78%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.78%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.78%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.78%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 2        | 0.78%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 2        | 0.78%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.39%   |
| Sony Ericsson Mobile AB E5823                                     | 1        | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.39%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.39%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.39%   |
| Prestigio PSP5453DUO                                              | 1        | 0.39%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.39%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.39%   |
| Nvidia MCP65 Ethernet                                             | 1        | 0.39%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 233      | 75.16%  |
| WiFi     | 74       | 23.87%  |
| Modem    | 2        | 0.65%   |
| Unknown  | 1        | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 196      | 82.35%  |
| WiFi     | 42       | 17.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 184      | 76.03%  |
| 2     | 42       | 17.36%  |
| 3     | 8        | 3.31%   |
| 0     | 6        | 2.48%   |
| 4     | 2        | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 232      | 96.67%  |
| Yes  | 8        | 3.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 18       | 45%     |
| Cambridge Silicon Radio         | 6        | 15%     |
| Realtek Semiconductor           | 4        | 10%     |
| ASUSTek Computer                | 3        | 7.5%    |
| Micro Star International        | 2        | 5%      |
| HTC (High Tech Computer)        | 2        | 5%      |
| Qualcomm Atheros Communications | 1        | 2.5%    |
| Integrated System Solution      | 1        | 2.5%    |
| IMC Networks                    | 1        | 2.5%    |
| Broadcom                        | 1        | 2.5%    |
| Belkin Components               | 1        | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 6        | 15%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 6        | 15%     |
| Intel Bluetooth wireless interface                                   | 3        | 7.5%    |
| Intel AX210 Bluetooth                                                | 3        | 7.5%    |
| Realtek Bluetooth Radio                                              | 2        | 5%      |
| Micro Star International Bluetooth Device                            | 2        | 5%      |
| Intel Wireless-AC 3168 Bluetooth                                     | 2        | 5%      |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2        | 5%      |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 5%      |
| ASUS Bluetooth Radio                                                 | 2        | 5%      |
| Realtek RTL8821A Bluetooth                                           | 1        | 2.5%    |
| Realtek RTL8723B Bluetooth                                           | 1        | 2.5%    |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 2.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 2.5%    |
| Intel Bluetooth Device                                               | 1        | 2.5%    |
| Integrated System Solution Bluetooth Device                          | 1        | 2.5%    |
| IMC Networks Bluetooth Radio                                         | 1        | 2.5%    |
| Broadcom BCM2045 Bluetooth                                           | 1        | 2.5%    |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 2.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 146      | 38.62%  |
| AMD                      | 99       | 26.19%  |
| Nvidia                   | 91       | 24.07%  |
| C-Media Electronics      | 10       | 2.65%   |
| Creative Labs            | 8        | 2.12%   |
| VIA Technologies         | 4        | 1.06%   |
| Creative Technology      | 4        | 1.06%   |
| Blue Microphones         | 2        | 0.53%   |
| ASUSTek Computer         | 2        | 0.53%   |
| Valve Software           | 1        | 0.26%   |
| ULi Electronics          | 1        | 0.26%   |
| SteelSeries ApS          | 1        | 0.26%   |
| Nordic Semiconductor ASA | 1        | 0.26%   |
| Micro Star International | 1        | 0.26%   |
| Logitech                 | 1        | 0.26%   |
| Lenovo                   | 1        | 0.26%   |
| GN Netcom                | 1        | 0.26%   |
| Fortemedia               | 1        | 0.26%   |
| Barco Display Systems    | 1        | 0.26%   |
| AKAI Professional M.I.   | 1        | 0.26%   |
| A4Tech                   | 1        | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 24       | 5.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 22       | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 18       | 4.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 17       | 3.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 15       | 3.41%   |
| AMD FCH Azalia Controller                                                                       | 15       | 3.41%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 13       | 2.95%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 12       | 2.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 11       | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 11       | 2.5%    |
| Intel 200 Series PCH HD Audio                                                                   | 9        | 2.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 9        | 2.05%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 8        | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                                      | 8        | 1.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 8        | 1.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 8        | 1.82%   |
| Nvidia High Definition Audio Controller                                                         | 7        | 1.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 7        | 1.59%   |
| Nvidia MCP61 High Definition Audio                                                              | 6        | 1.36%   |
| Nvidia GF108 High Definition Audio Controller                                                   | 6        | 1.36%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 6        | 1.36%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 5        | 1.14%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                  | 5        | 1.14%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 5        | 1.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 5        | 1.14%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 4        | 0.91%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 4        | 0.91%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 4        | 0.91%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 4        | 0.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 4        | 0.91%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 4        | 0.91%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                   | 4        | 0.91%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                  | 4        | 0.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 4        | 0.91%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]               | 4        | 0.91%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                       | 3        | 0.68%   |
| Nvidia TU104 HD Audio Controller                                                                | 3        | 0.68%   |
| Nvidia GT216 HDMI Audio Controller                                                              | 3        | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 3        | 0.68%   |
| Nvidia GP102 HDMI Audio Controller                                                              | 3        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 39       | 28.26%  |
| Kingston            | 38       | 27.54%  |
| Crucial             | 10       | 7.25%   |
| Samsung Electronics | 9        | 6.52%   |
| Corsair             | 9        | 6.52%   |
| SK hynix            | 8        | 5.8%    |
| Patriot             | 6        | 4.35%   |
| G.Skill             | 5        | 3.62%   |
| Micron Technology   | 4        | 2.9%    |
| Elpida              | 4        | 2.9%    |
| Unknown             | 2        | 1.45%   |
| Unknown (8AC8)      | 1        | 0.72%   |
| Transcend           | 1        | 0.72%   |
| Hewlett-Packard     | 1        | 0.72%   |
| A-DATA Technology   | 1        | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 4        | 2.44%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 3        | 1.83%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 3        | 1.83%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 3        | 1.83%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 3        | 1.83%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 2        | 1.22%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s              | 2        | 1.22%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 2        | 1.22%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s               | 2        | 1.22%   |
| Unknown RAM Module 1024MB DIMM 533MT/s                   | 2        | 1.22%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 2        | 1.22%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 2        | 1.22%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s      | 2        | 1.22%   |
| Samsung RAM M378B2873EH1-CH9 1GB DIMM DDR3 1334MT/s      | 2        | 1.22%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 2        | 1.22%   |
| Kingston RAM KHX1600C9D3/2GX 2GB DIMM DDR3 1600MT/s      | 2        | 1.22%   |
| Kingston RAM 99U5584-001.A00LF 4096MB DIMM DDR3 1600MT/s | 2        | 1.22%   |
| Kingston RAM 2G-UDIMM 512MB DIMM DDR 800MT/s             | 2        | 1.22%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s      | 2        | 1.22%   |
| Unknown                                                  | 2        | 1.22%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                | 1        | 0.61%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                | 1        | 0.61%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                | 1        | 0.61%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s                | 1        | 0.61%   |
| Unknown RAM Module 512MB DIMM 533MT/s                    | 1        | 0.61%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s              | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1        | 0.61%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 0.61%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 0.61%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                  | 1        | 0.61%   |
| Unknown RAM Module 2GB FB-DIMM DDR2 667MT/s              | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM SDRAM 667MT/s                | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                  | 1        | 0.61%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s               | 1        | 0.61%   |
| Unknown RAM Module 256MB DIMM DDR 333MT/s                | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s             | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s             | 1        | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 41       | 32.54%  |
| DDR4    | 36       | 28.57%  |
| DDR2    | 16       | 12.7%   |
| Unknown | 14       | 11.11%  |
| SDRAM   | 12       | 9.52%   |
| DDR     | 5        | 3.97%   |
| DRAM    | 1        | 0.79%   |
| DDR5    | 1        | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 117      | 95.9%   |
| SODIMM  | 4        | 3.28%   |
| FB-DIMM | 1        | 0.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 38       | 26.76%  |
| 4096  | 35       | 24.65%  |
| 8192  | 33       | 23.24%  |
| 1024  | 14       | 9.86%   |
| 16384 | 10       | 7.04%   |
| 512   | 5        | 3.52%   |
| 32768 | 3        | 2.11%   |
| 256   | 2        | 1.41%   |
| 128   | 1        | 0.7%    |
| 64    | 1        | 0.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 29       | 20%     |
| 800     | 15       | 10.34%  |
| 1333    | 13       | 8.97%   |
| 667     | 10       | 6.9%    |
| 2667    | 7        | 4.83%   |
| 2400    | 7        | 4.83%   |
| 3200    | 6        | 4.14%   |
| 3600    | 5        | 3.45%   |
| 1867    | 5        | 3.45%   |
| 333     | 5        | 3.45%   |
| 3466    | 4        | 2.76%   |
| 2133    | 4        | 2.76%   |
| 1334    | 3        | 2.07%   |
| 533     | 3        | 2.07%   |
| 400     | 3        | 2.07%   |
| Unknown | 3        | 2.07%   |
| 3800    | 2        | 1.38%   |
| 3733    | 2        | 1.38%   |
| 1800    | 2        | 1.38%   |
| 1066    | 2        | 1.38%   |
| 57535   | 1        | 0.69%   |
| 6400    | 1        | 0.69%   |
| 4400    | 1        | 0.69%   |
| 4000    | 1        | 0.69%   |
| 3400    | 1        | 0.69%   |
| 3333    | 1        | 0.69%   |
| 3266    | 1        | 0.69%   |
| 3000    | 1        | 0.69%   |
| 2666    | 1        | 0.69%   |
| 1866    | 1        | 0.69%   |
| 1639    | 1        | 0.69%   |
| 1067    | 1        | 0.69%   |
| 266     | 1        | 0.69%   |
| 200     | 1        | 0.69%   |
| 100     | 1        | 0.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 12       | 80%     |
| Star Micronics      | 1        | 6.67%   |
| Samsung Electronics | 1        | 6.67%   |
| Canon               | 1        | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| HP LaserJet 1020                                | 4        | 26.67%  |
| HP Deskjet 1050 J410                            | 2        | 13.33%  |
| Star Micronics IP1000 Printer USB001            | 1        | 6.67%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 1        | 6.67%   |
| HP OfficeJet 6950                               | 1        | 6.67%   |
| HP LaserJet M14-M17                             | 1        | 6.67%   |
| HP LaserJet M101-M106                           | 1        | 6.67%   |
| HP LaserJet 1150                                | 1        | 6.67%   |
| HP DeskJet 2700 series                          | 1        | 6.67%   |
| HP Deskjet 1510                                 | 1        | 6.67%   |
| Canon PIXMA MP230                               | 1        | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Canon   | 2        | 66.67%  |
| Minolta | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Minolta Dimage Scan Dual III AF-2840 (2889) | 1        | 33.33%  |
| Canon CanoScan LiDE 90                      | 1        | 33.33%  |
| Canon CanoScan LIDE 25                      | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 8        | 23.53%  |
| Microsoft                   | 7        | 20.59%  |
| Microdia                    | 5        | 14.71%  |
| Creative Technology         | 3        | 8.82%   |
| Z-Star Microelectronics     | 2        | 5.88%   |
| Valve Software              | 1        | 2.94%   |
| Unknown                     | 1        | 2.94%   |
| Syntek                      | 1        | 2.94%   |
| MacroSilicon                | 1        | 2.94%   |
| KYE Systems (Mouse Systems) | 1        | 2.94%   |
| Generalplus Technology      | 1        | 2.94%   |
| Cubeternet                  | 1        | 2.94%   |
| Apple                       | 1        | 2.94%   |
| Alcor Micro                 | 1        | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Microdia Sonix USB 2.0 Camera             | 3        | 8.57%   |
| Microsoft LifeCam Cinema                  | 2        | 5.71%   |
| Creative Live! Cam Sync HD [VF0770]       | 2        | 5.71%   |
| Z-Star Vega USB 2.0 Camera                | 1        | 2.86%   |
| Z-Star A4 TECH HD PC Camera               | 1        | 2.86%   |
| Valve Software 3D Camera                  | 1        | 2.86%   |
| Unknown HD camera                         | 1        | 2.86%   |
| Syntek Integrated RGB Camera              | 1        | 2.86%   |
| Microsoft MicrosoftÂ LifeCam VX-5500     | 1        | 2.86%   |
| Microsoft LifeCam VX-800                  | 1        | 2.86%   |
| Microsoft LifeCam VX-700                  | 1        | 2.86%   |
| Microsoft LifeCam VX-500 [1357]           | 1        | 2.86%   |
| Microsoft LifeCam HD-3000                 | 1        | 2.86%   |
| Microdia USB 2.0 Camera                   | 1        | 2.86%   |
| Microdia Camera                           | 1        | 2.86%   |
| MacroSilicon USB Video                    | 1        | 2.86%   |
| Logitech Webcam C930e                     | 1        | 2.86%   |
| Logitech Webcam C925e                     | 1        | 2.86%   |
| Logitech Webcam C270                      | 1        | 2.86%   |
| Logitech Webcam C200                      | 1        | 2.86%   |
| Logitech Webcam C110                      | 1        | 2.86%   |
| Logitech QuickCam Pro 9000                | 1        | 2.86%   |
| Logitech HD Webcam C525                   | 1        | 2.86%   |
| Logitech HD Pro Webcam C920               | 1        | 2.86%   |
| Logitech C505e HD Webcam                  | 1        | 2.86%   |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1        | 2.86%   |
| Generalplus 808 Camera #9 (web-cam mode)  | 1        | 2.86%   |
| Cubeternet HDMI to U3 capture             | 1        | 2.86%   |
| Creative Live! Cam Chat HD [VF0700]       | 1        | 2.86%   |
| Apple iPhone 5/5C/5S/6/SE                 | 1        | 2.86%   |
| Alcor Micro USB 2.0 PC Camera             | 1        | 2.86%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 209      | 83.94%  |
| 1     | 36       | 14.46%  |
| 2     | 3        | 1.2%    |
| 3     | 1        | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 24       | 55.81%  |
| Net/wireless             | 7        | 16.28%  |
| Sound                    | 2        | 4.65%   |
| Communication controller | 2        | 4.65%   |
| Bluetooth                | 2        | 4.65%   |
| Unassigned class         | 1        | 2.33%   |
| Network                  | 1        | 2.33%   |
| Net/ethernet             | 1        | 2.33%   |
| Multimedia controller    | 1        | 2.33%   |
| Chipcard                 | 1        | 2.33%   |
| Card reader              | 1        | 2.33%   |

