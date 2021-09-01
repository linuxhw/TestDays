Debian 11 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Pegatron      | TRUCKEE                     | [68f16e9542](https://linux-hardware.org/?probe=68f16e9542) | Sep 01, 2021 |
| ASRock        | H61M-VG4                    | [6521e0d6be](https://linux-hardware.org/?probe=6521e0d6be) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [9c31643811](https://linux-hardware.org/?probe=9c31643811) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [37c3e457bc](https://linux-hardware.org/?probe=37c3e457bc) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [0d38048f46](https://linux-hardware.org/?probe=0d38048f46) | Aug 31, 2021 |
| Intel         | DH77KC AAG39641-400         | [d7eaf975a0](https://linux-hardware.org/?probe=d7eaf975a0) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [df9b303eec](https://linux-hardware.org/?probe=df9b303eec) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [d9af23fb86](https://linux-hardware.org/?probe=d9af23fb86) | Aug 31, 2021 |
| AOpen         | D1001 C26361-D1001          | [e27239d870](https://linux-hardware.org/?probe=e27239d870) | Aug 31, 2021 |
| ASUSTek       | B85M-G                      | [1470c8cc7f](https://linux-hardware.org/?probe=1470c8cc7f) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [ba7144c0dc](https://linux-hardware.org/?probe=ba7144c0dc) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [7204a77b38](https://linux-hardware.org/?probe=7204a77b38) | Aug 31, 2021 |
| ASRock        | H470M-HVS                   | [c6a754129a](https://linux-hardware.org/?probe=c6a754129a) | Aug 30, 2021 |
| ASRock        | H470M-HVS                   | [a251dca266](https://linux-hardware.org/?probe=a251dca266) | Aug 30, 2021 |
| Intel         | DH67BL AAG10189-206         | [b7b3f489f2](https://linux-hardware.org/?probe=b7b3f489f2) | Aug 30, 2021 |
| Gigabyte      | H81M-S2V                    | [d255f48a39](https://linux-hardware.org/?probe=d255f48a39) | Aug 30, 2021 |
| ASRock        | H61M-VG4                    | [dc0abe4fcd](https://linux-hardware.org/?probe=dc0abe4fcd) | Aug 30, 2021 |
| ASRock        | H61M-VG4                    | [fc61c24624](https://linux-hardware.org/?probe=fc61c24624) | Aug 30, 2021 |
| Gigabyte      | H81M-S2V                    | [9d1b86643e](https://linux-hardware.org/?probe=9d1b86643e) | Aug 30, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [b9595196ea](https://linux-hardware.org/?probe=b9595196ea) | Aug 28, 2021 |
| NC9VL         | 1.0                         | [9c4b8ad466](https://linux-hardware.org/?probe=9c4b8ad466) | Aug 28, 2021 |
| MSI           | B150A GAMING PRO            | [06de6cd826](https://linux-hardware.org/?probe=06de6cd826) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | [46eacf8d5c](https://linux-hardware.org/?probe=46eacf8d5c) | Aug 27, 2021 |
| Intel         | DN2820FYK H24582-201        | [06f4334a82](https://linux-hardware.org/?probe=06f4334a82) | Aug 27, 2021 |
| ASUSTek       | WS X299 SAGE                | [7f3a68dd2a](https://linux-hardware.org/?probe=7f3a68dd2a) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | [2737cfb67d](https://linux-hardware.org/?probe=2737cfb67d) | Aug 27, 2021 |
| ASRock        | H470M-HVS                   | [dc9428d8b4](https://linux-hardware.org/?probe=dc9428d8b4) | Aug 27, 2021 |
| HP            | 0B0Ch                       | [b5933fde35](https://linux-hardware.org/?probe=b5933fde35) | Aug 26, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [f26ade88cd](https://linux-hardware.org/?probe=f26ade88cd) | Aug 26, 2021 |
| Dell          | 0WR7PY A00                  | [cb25b1811b](https://linux-hardware.org/?probe=cb25b1811b) | Aug 26, 2021 |
| Dell          | 0X8DXD A00                  | [8dd8862b4b](https://linux-hardware.org/?probe=8dd8862b4b) | Aug 26, 2021 |
| ASRock        | H470M-HVS                   | [d37f13917f](https://linux-hardware.org/?probe=d37f13917f) | Aug 25, 2021 |
| ASRock        | C2750D4I                    | [6daa3c26bf](https://linux-hardware.org/?probe=6daa3c26bf) | Aug 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0a79171c9e](https://linux-hardware.org/?probe=0a79171c9e) | Aug 25, 2021 |
| ASUSTek       | P5KPL-CM                    | [feed9e2921](https://linux-hardware.org/?probe=feed9e2921) | Aug 25, 2021 |
| Biostar       | Hi-Fi A85W                  | [ffb66dafd4](https://linux-hardware.org/?probe=ffb66dafd4) | Aug 25, 2021 |
| AAEON         | MF-001 V1.0                 | [b06c4079a7](https://linux-hardware.org/?probe=b06c4079a7) | Aug 25, 2021 |
| Dell          | 040DDP A01                  | [557d74beb9](https://linux-hardware.org/?probe=557d74beb9) | Aug 25, 2021 |
| ASRock        | H470M-HVS                   | [e5c92fe4ad](https://linux-hardware.org/?probe=e5c92fe4ad) | Aug 24, 2021 |
| ASRock        | H470M-HVS                   | [441b8b892e](https://linux-hardware.org/?probe=441b8b892e) | Aug 24, 2021 |
| ASRock        | P4i65G                      | [43ce3e711f](https://linux-hardware.org/?probe=43ce3e711f) | Aug 24, 2021 |
| ASRock        | H77 Pro4/MVP                | [c2179206a9](https://linux-hardware.org/?probe=c2179206a9) | Aug 24, 2021 |
| Unknown       | 1.0                         | [5e638360a8](https://linux-hardware.org/?probe=5e638360a8) | Aug 24, 2021 |
| ASUSTek       | GA35DX                      | [3843ea048e](https://linux-hardware.org/?probe=3843ea048e) | Aug 24, 2021 |
| ASRock        | H470M-HVS                   | [e92004f46a](https://linux-hardware.org/?probe=e92004f46a) | Aug 23, 2021 |
| ASRock        | H470M-HVS                   | [06c9a1ed3a](https://linux-hardware.org/?probe=06c9a1ed3a) | Aug 23, 2021 |
| ASUSTek       | P5KPL-CM                    | [06234ebe05](https://linux-hardware.org/?probe=06234ebe05) | Aug 23, 2021 |
| MSI           | Z270-A PRO                  | [73b14ecca0](https://linux-hardware.org/?probe=73b14ecca0) | Aug 23, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [eea45758b7](https://linux-hardware.org/?probe=eea45758b7) | Aug 22, 2021 |
| HP            | 085Ch                       | [2e649d07a0](https://linux-hardware.org/?probe=2e649d07a0) | Aug 21, 2021 |
| HP            | 085Ch                       | [c5b36c5187](https://linux-hardware.org/?probe=c5b36c5187) | Aug 21, 2021 |
| ASRock        | Z97 Pro3                    | [0f9abf9c63](https://linux-hardware.org/?probe=0f9abf9c63) | Aug 21, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [7f83e1b3c8](https://linux-hardware.org/?probe=7f83e1b3c8) | Aug 21, 2021 |
| ASUSTek       | P5B SE                      | [81634fcb22](https://linux-hardware.org/?probe=81634fcb22) | Aug 21, 2021 |
| MSI           | Z270-A PRO                  | [e59c9482f6](https://linux-hardware.org/?probe=e59c9482f6) | Aug 21, 2021 |
| ASRock        | H470M-HVS                   | [cba7d82942](https://linux-hardware.org/?probe=cba7d82942) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | [62068f391f](https://linux-hardware.org/?probe=62068f391f) | Aug 20, 2021 |
| ASRock        | H470M-HVS                   | [c980f2d201](https://linux-hardware.org/?probe=c980f2d201) | Aug 20, 2021 |
| Dell          | 0Y2K8N A01                  | [6b0fd02c91](https://linux-hardware.org/?probe=6b0fd02c91) | Aug 20, 2021 |
| Intel         | DG33BU AAD79951-407         | [17c70c7886](https://linux-hardware.org/?probe=17c70c7886) | Aug 19, 2021 |
| HP            | 339A                        | [57d5bbd1e4](https://linux-hardware.org/?probe=57d5bbd1e4) | Aug 19, 2021 |
| Gigabyte      | A320M-S2H-CF                | [2151b5cdae](https://linux-hardware.org/?probe=2151b5cdae) | Aug 19, 2021 |
| HP            | 1587h                       | [3ddbdb3101](https://linux-hardware.org/?probe=3ddbdb3101) | Aug 19, 2021 |
| ASRock        | H470M-HVS                   | [0489699bc4](https://linux-hardware.org/?probe=0489699bc4) | Aug 19, 2021 |
| MSI           | B450M PRO-M2 MAX            | [cc54b8955c](https://linux-hardware.org/?probe=cc54b8955c) | Aug 19, 2021 |
| ASRock        | H470M-HVS                   | [757e261c56](https://linux-hardware.org/?probe=757e261c56) | Aug 19, 2021 |
| Lenovo        | MAHOBAY                     | [df15656fce](https://linux-hardware.org/?probe=df15656fce) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6f5485edfc](https://linux-hardware.org/?probe=6f5485edfc) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [1fce0ab0e8](https://linux-hardware.org/?probe=1fce0ab0e8) | Aug 18, 2021 |
| Lenovo        | Board                       | [3de8569fe7](https://linux-hardware.org/?probe=3de8569fe7) | Aug 18, 2021 |
| ASUSTek       | H81M-R                      | [8598ad2248](https://linux-hardware.org/?probe=8598ad2248) | Aug 18, 2021 |
| ASUSTek       | B150M-K                     | [3f706a2a69](https://linux-hardware.org/?probe=3f706a2a69) | Aug 18, 2021 |
| ASUSTek       | P7H55-M SI                  | [9f3381d34c](https://linux-hardware.org/?probe=9f3381d34c) | Aug 18, 2021 |
| ASRock        | B460 Phantom Gaming 4       | [85cfabd795](https://linux-hardware.org/?probe=85cfabd795) | Aug 18, 2021 |
| ASUSTek       | P7H55-M SI                  | [765f5d340e](https://linux-hardware.org/?probe=765f5d340e) | Aug 18, 2021 |
| ASRock        | J4205-ITX                   | [30de75d2c8](https://linux-hardware.org/?probe=30de75d2c8) | Aug 18, 2021 |
| ASUSTek       | A68HM-PLUS                  | [b2ed4bc6fe](https://linux-hardware.org/?probe=b2ed4bc6fe) | Aug 18, 2021 |
| Gigabyte      | Z97N-WIFI                   | [be9383850e](https://linux-hardware.org/?probe=be9383850e) | Aug 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [7911fbd6a6](https://linux-hardware.org/?probe=7911fbd6a6) | Aug 17, 2021 |
| MSI           | FM2-A55M-E33                | [6972c43e80](https://linux-hardware.org/?probe=6972c43e80) | Aug 17, 2021 |
| ASUSTek       | P5KC                        | [5e2f61d652](https://linux-hardware.org/?probe=5e2f61d652) | Aug 16, 2021 |
| Intel         | DN2820FYK H24582-201        | [86cf4755a0](https://linux-hardware.org/?probe=86cf4755a0) | Aug 16, 2021 |
| ASRock        | B460 Phantom Gaming 4       | [51f9388874](https://linux-hardware.org/?probe=51f9388874) | Aug 15, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [88160f850f](https://linux-hardware.org/?probe=88160f850f) | Aug 15, 2021 |
| ASUSTek       | M5A99X EVO                  | [53aff8d681](https://linux-hardware.org/?probe=53aff8d681) | Aug 15, 2021 |
| ECS           | KBN-I                       | [bbfe1ba1a2](https://linux-hardware.org/?probe=bbfe1ba1a2) | Aug 15, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [987ab1f3bf](https://linux-hardware.org/?probe=987ab1f3bf) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | [a6e0859eac](https://linux-hardware.org/?probe=a6e0859eac) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | [5ce5d800d3](https://linux-hardware.org/?probe=5ce5d800d3) | Aug 14, 2021 |
| ASUSTek       | PRIME Z390-P                | [dfe51161fe](https://linux-hardware.org/?probe=dfe51161fe) | Aug 14, 2021 |
| ASRock        | Z97 Pro3                    | [0e5746a060](https://linux-hardware.org/?probe=0e5746a060) | Aug 14, 2021 |
| Dell          | 0X9M3X A01                  | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| HP            | 3397                        | [a3425b956c](https://linux-hardware.org/?probe=a3425b956c) | Aug 14, 2021 |
| ASUSTek       | X99-DELUXE                  | [f59179a579](https://linux-hardware.org/?probe=f59179a579) | Aug 13, 2021 |
| ASUSTek       | Z170-PRO                    | [7f9b5606a5](https://linux-hardware.org/?probe=7f9b5606a5) | Aug 13, 2021 |
| HP            | 3048h                       | [894950911f](https://linux-hardware.org/?probe=894950911f) | Aug 11, 2021 |
| Gigabyte      | 970A-DS3P                   | [9b62457757](https://linux-hardware.org/?probe=9b62457757) | Aug 11, 2021 |
| ASUSTek       | PRIME A320M-K               | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [78223998b6](https://linux-hardware.org/?probe=78223998b6) | Aug 10, 2021 |
| MSI           | B250M PRO-VDH               | [d6be998202](https://linux-hardware.org/?probe=d6be998202) | Aug 10, 2021 |
| ASUSTek       | PRIME A320M-K               | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Dell          | 04MFRM A01                  | [c0094def97](https://linux-hardware.org/?probe=c0094def97) | Aug 09, 2021 |
| MSI           | B450 TOMAHAWK               | [58b4f52cc0](https://linux-hardware.org/?probe=58b4f52cc0) | Aug 09, 2021 |
| Gigabyte      | H470M DS3H                  | [29de4693d8](https://linux-hardware.org/?probe=29de4693d8) | Aug 09, 2021 |
| ASRock        | 970A-G                      | [f1e9959894](https://linux-hardware.org/?probe=f1e9959894) | Aug 09, 2021 |
| Toshiba       | STI 910090 STIJ             | [389ebd7675](https://linux-hardware.org/?probe=389ebd7675) | Aug 08, 2021 |
| ASRock        | X370 Killer SLI             | [8a0885afb6](https://linux-hardware.org/?probe=8a0885afb6) | Aug 08, 2021 |
| MSI           | Z490-A PRO                  | [eac37d633f](https://linux-hardware.org/?probe=eac37d633f) | Aug 08, 2021 |
| ASRock        | Z97 Pro4                    | [090d12a96f](https://linux-hardware.org/?probe=090d12a96f) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [39eb5a1578](https://linux-hardware.org/?probe=39eb5a1578) | Aug 08, 2021 |
| Toshiba       | STI 005038 G31T-M7          | [faa8f15725](https://linux-hardware.org/?probe=faa8f15725) | Aug 08, 2021 |
| Gigabyte      | Z77-D3H                     | [9dafe47483](https://linux-hardware.org/?probe=9dafe47483) | Aug 07, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [da833ac33e](https://linux-hardware.org/?probe=da833ac33e) | Aug 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [80c7711147](https://linux-hardware.org/?probe=80c7711147) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | [4ff5966d22](https://linux-hardware.org/?probe=4ff5966d22) | Aug 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | [5839492cd8](https://linux-hardware.org/?probe=5839492cd8) | Aug 07, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [733a3e325c](https://linux-hardware.org/?probe=733a3e325c) | Aug 07, 2021 |
| Dell          | 08WKV3 A01                  | [8ab0ff9442](https://linux-hardware.org/?probe=8ab0ff9442) | Aug 07, 2021 |
| MSI           | MEG X399 CREATION           | [7cada9aaed](https://linux-hardware.org/?probe=7cada9aaed) | Aug 07, 2021 |
| MSI           | B250M PRO-VDH               | [187e4dd872](https://linux-hardware.org/?probe=187e4dd872) | Aug 07, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [31d159af99](https://linux-hardware.org/?probe=31d159af99) | Aug 06, 2021 |
| Lenovo        | Board                       | [18138486db](https://linux-hardware.org/?probe=18138486db) | Aug 05, 2021 |
| Intel         | DN2820FYK H24582-201        | [7caf949908](https://linux-hardware.org/?probe=7caf949908) | Aug 05, 2021 |
| Unknown       | Intel X79                   | [fc0dedbb3c](https://linux-hardware.org/?probe=fc0dedbb3c) | Aug 05, 2021 |
| AMD           | 970A-D3                     | [91825066e0](https://linux-hardware.org/?probe=91825066e0) | Aug 04, 2021 |
| HP            | 3047h                       | [6294617672](https://linux-hardware.org/?probe=6294617672) | Aug 03, 2021 |
| ASRock        | FM2A68M-HD+                 | [a7bdbd8ebe](https://linux-hardware.org/?probe=a7bdbd8ebe) | Aug 03, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [55cd593df1](https://linux-hardware.org/?probe=55cd593df1) | Aug 03, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| MSI           | 760GM-P23                   | [93b6f212af](https://linux-hardware.org/?probe=93b6f212af) | Aug 02, 2021 |
| Supermicro    | X11SSH-F                    | [641e4fd8ce](https://linux-hardware.org/?probe=641e4fd8ce) | Aug 02, 2021 |
| ASRock        | H310CM-DVS                  | [f84e5eba5a](https://linux-hardware.org/?probe=f84e5eba5a) | Aug 02, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [e90a873ad0](https://linux-hardware.org/?probe=e90a873ad0) | Aug 02, 2021 |
| ASUSTek       | P5QL-E                      | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| ASUSTek       | A88X-PRO                    | [ed95430eec](https://linux-hardware.org/?probe=ed95430eec) | Aug 02, 2021 |
| HP            | 2187 A01                    | [16bfdd86e3](https://linux-hardware.org/?probe=16bfdd86e3) | Aug 02, 2021 |
| Gigabyte      | 970A-DS3P                   | [61886d812f](https://linux-hardware.org/?probe=61886d812f) | Aug 01, 2021 |
| ASRock        | J1900D2Y                    | [0dc4afc8c4](https://linux-hardware.org/?probe=0dc4afc8c4) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| Dell          | 0WVYMC A00                  | [4d2aa42e3c](https://linux-hardware.org/?probe=4d2aa42e3c) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [159ff0ba7f](https://linux-hardware.org/?probe=159ff0ba7f) | Jul 31, 2021 |
| ASRock        | Z370M-ITX/ac                | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [3f0c3901f6](https://linux-hardware.org/?probe=3f0c3901f6) | Jul 30, 2021 |
| MSI           | Z490-A PRO                  | [b882a9cf0d](https://linux-hardware.org/?probe=b882a9cf0d) | Jul 29, 2021 |
| MSI           | Q45MDO                      | [ab547f0047](https://linux-hardware.org/?probe=ab547f0047) | Jul 29, 2021 |
| MSI           | Q45MDO                      | [6b5aaa6969](https://linux-hardware.org/?probe=6b5aaa6969) | Jul 29, 2021 |
| Dell          | 0TY915                      | [9cb5aed659](https://linux-hardware.org/?probe=9cb5aed659) | Jul 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| ASUSTek       | LEONITE                     | [3bf9048839](https://linux-hardware.org/?probe=3bf9048839) | Jul 29, 2021 |
| Foxconn       | 2AA9                        | [920a813aaf](https://linux-hardware.org/?probe=920a813aaf) | Jul 29, 2021 |
| ASRock        | B85M Pro4                   | [32e615b538](https://linux-hardware.org/?probe=32e615b538) | Jul 29, 2021 |
| ASRock        | FM2A88X Extreme6+           | [f449b8ce85](https://linux-hardware.org/?probe=f449b8ce85) | Jul 29, 2021 |
| ECS           | H61H2-M12                   | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| MSI           | B450M PRO-VDH PLUS          | [cccaebb483](https://linux-hardware.org/?probe=cccaebb483) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f96bcc3ab2](https://linux-hardware.org/?probe=f96bcc3ab2) | Jul 28, 2021 |
| Shuttle       | FX79R                       | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| ASRockRack    | X570D4U-2L2T                | [7bb34c9dec](https://linux-hardware.org/?probe=7bb34c9dec) | Jul 27, 2021 |
| ASUSTek       | A88X-PLUS/USB               | [57b54cc925](https://linux-hardware.org/?probe=57b54cc925) | Jul 27, 2021 |
| ASRock        | N68C-GS FX                  | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| ASUSTek       | PRIME Z490-P                | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| Dell          | 0X8DXD A00                  | [7821dfc370](https://linux-hardware.org/?probe=7821dfc370) | Jul 27, 2021 |
| ASUSTek       | M4A785D-M PRO               | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| Foxconn       | 915MH Series                | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [dc4a709a3b](https://linux-hardware.org/?probe=dc4a709a3b) | Jul 27, 2021 |
| Dell          | 0WMJ54 A01                  | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [1e69873301](https://linux-hardware.org/?probe=1e69873301) | Jul 27, 2021 |
| Dell          | 0M863N A00                  | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| ASRock        | Z97 Pro3                    | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| MSI           | Z370 SLI PLUS               | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock        | B450 Pro4                   | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP            | 2B38                        | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | 970 Pro3 R2.0               | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASRock        | X570 Steel Legend           | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell          | 0D28YY A02                  | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock        | H470M-ITX/ac                | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Gigabyte      | H110M-S2H-CF                | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell          | 0PTTT9 A00                  | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte      | Z170M-D3H-CF                | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| ASRock        | P67 Pro3                    | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte      | H87-HD3                     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| Dell          | 0Y1057                      | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP            | 1495                        | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| HP            | 158A                        | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| HP            | 158A                        | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP            | 2129                        | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Protectli     | FW6                         | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| HP            | ProLiant MicroServer        | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| MSI           | A68HM-E33 V2                | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Huanan        | X99-F8 V2.0                 | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| HP            | 2215                        | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| MSI           | MS-6712                     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| ASRock        | H77 Pro4-M                  | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| Gigabyte      | AX370-Gaming K7             | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| MSI           | B85M-G43                    | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| Huanan        | X99-8M-F V1.1               | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| MSI           | B450M MORTAR MAX            | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| ASUSTek       | PRIME B450M-A               | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| Dell          | 0Y7WYT A00                  | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| ASRock        | B450M Pro4                  | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| ASUSTek       | PRIME A320M-K               | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| ASRock        | B450M Pro4                  | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| ASUSTek       | M4A88T-M/USB3               | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Dell          | 0YXT71 A02                  | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| ASUSTek       | P5B-Deluxe                  | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI           | B250M BAZOOKA               | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| MSI           | B450I GAMING PLUS AC        | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Gigabyte      | Z170X-GamingG1              | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| Gigabyte      | Z77-D3H                     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Lenovo        | MAHOBAY                     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| Biostar       | B450MH                      | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| Gigabyte      | EG41MF-US2H                 | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.10.0-8-amd64                 | 147      | 56.76%  |
| 5.10.0-7-amd64                 | 75       | 28.96%  |
| 5.10.0-6-amd64                 | 9        | 3.47%   |
| 5.11.22-1-pve                  | 3        | 1.16%   |
| 5.10.0-8-686-pae               | 3        | 1.16%   |
| 5.11.22-2-pve                  | 2        | 0.77%   |
| 5.10.0-8-rt-amd64              | 2        | 0.77%   |
| 5.10.0-8-686                   | 2        | 0.77%   |
| 5.8.0-3-amd64                  | 1        | 0.39%   |
| 5.13.8-gnu                     | 1        | 0.39%   |
| 5.13.4                         | 1        | 0.39%   |
| 5.13.1a                        | 1        | 0.39%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1        | 0.39%   |
| 5.11.22-3-pve                  | 1        | 0.39%   |
| 5.11.0-21.1-liquorix-amd64     | 1        | 0.39%   |
| 5.11.0-16.1-liquorix-amd64     | 1        | 0.39%   |
| 5.10.46custom                  | 1        | 0.39%   |
| 5.10.42+truenas                | 1        | 0.39%   |
| 5.10.38-falcot                 | 1        | 0.39%   |
| 5.10.0-7-686-pae               | 1        | 0.39%   |
| 5.10.0-5-amd64                 | 1        | 0.39%   |
| 5.10.0-3-amd64                 | 1        | 0.39%   |
| 5.10.0-2-amd64                 | 1        | 0.39%   |
| 4.19.0-9-686-pae               | 1        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 237      | 93.31%  |
| 5.11.22 | 6        | 2.36%   |
| 5.11.0  | 2        | 0.79%   |
| 5.8.0   | 1        | 0.39%   |
| 5.13.8  | 1        | 0.39%   |
| 5.13.4  | 1        | 0.39%   |
| 5.13.1  | 1        | 0.39%   |
| 5.13.0  | 1        | 0.39%   |
| 5.10.46 | 1        | 0.39%   |
| 5.10.42 | 1        | 0.39%   |
| 5.10.38 | 1        | 0.39%   |
| 4.19.0  | 1        | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 240      | 94.49%  |
| 5.11    | 8        | 3.15%   |
| 5.13    | 4        | 1.57%   |
| 5.8     | 1        | 0.39%   |
| 4.19    | 1        | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 247      | 97.24%  |
| i686   | 7        | 2.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 67       | 26.07%  |
| GNOME            | 52       | 20.23%  |
| KDE5             | 41       | 15.95%  |
| XFCE             | 26       | 10.12%  |
| MATE             | 19       | 7.39%   |
| Cinnamon         | 11       | 4.28%   |
| X-Cinnamon       | 6        | 2.33%   |
| Trinity          | 6        | 2.33%   |
| LXQt             | 6        | 2.33%   |
| i3               | 6        | 2.33%   |
| LXDE             | 5        | 1.95%   |
| KDE              | 4        | 1.56%   |
| lightdm-xsession | 2        | 0.78%   |
| GNOME Flashback  | 2        | 0.78%   |
| sway             | 1        | 0.39%   |
| openbox          | 1        | 0.39%   |
| GNUstep          | 1        | 0.39%   |
| Budgie           | 1        | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 155      | 60.78%  |
| Unknown | 44       | 17.25%  |
| Tty     | 31       | 12.16%  |
| Wayland | 25       | 9.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 84       | 32.94%  |
| TDM     | 71       | 27.84%  |
| GDM     | 42       | 16.47%  |
| SDDM    | 39       | 15.29%  |
| LightDM | 14       | 5.49%   |
| SLiM    | 3        | 1.18%   |
| XDM     | 1        | 0.39%   |
| GDM3    | 1        | 0.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 105      | 41.34%  |
| ru_RU   | 48       | 18.9%   |
| en_GB   | 16       | 6.3%    |
| fr_FR   | 14       | 5.51%   |
| de_DE   | 9        | 3.54%   |
| Unknown | 8        | 3.15%   |
| pt_BR   | 7        | 2.76%   |
| es_ES   | 6        | 2.36%   |
| en_AU   | 4        | 1.57%   |
| C       | 4        | 1.57%   |
| pl_PL   | 3        | 1.18%   |
| nl_BE   | 3        | 1.18%   |
| en_CA   | 3        | 1.18%   |
| ja_JP   | 2        | 0.79%   |
| uk_UA   | 1        | 0.39%   |
| tr_TR   | 1        | 0.39%   |
| sv_SE   | 1        | 0.39%   |
| sr_RS   | 1        | 0.39%   |
| ru_UA   | 1        | 0.39%   |
| ro_RO   | 1        | 0.39%   |
| nl_NL   | 1        | 0.39%   |
| it_IT   | 1        | 0.39%   |
| hu_HU   | 1        | 0.39%   |
| hr_HR   | 1        | 0.39%   |
| es_VE   | 1        | 0.39%   |
| es_US   | 1        | 0.39%   |
| es_MX   | 1        | 0.39%   |
| es_AR   | 1        | 0.39%   |
| en_PH   | 1        | 0.39%   |
| en_NZ   | 1        | 0.39%   |
| en_IN   | 1        | 0.39%   |
| en_IE   | 1        | 0.39%   |
| en_HK   | 1        | 0.39%   |
| de_CH   | 1        | 0.39%   |
| cs_CZ   | 1        | 0.39%   |
| bg_BG   | 1        | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 130      | 50.98%  |
| BIOS | 125      | 49.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 167      | 65.75%  |
| Overlay | 54       | 21.26%  |
| Btrfs   | 18       | 7.09%   |
| Zfs     | 5        | 1.97%   |
| Ext3    | 5        | 1.97%   |
| Xfs     | 4        | 1.57%   |
| Unknown | 1        | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 159      | 62.35%  |
| MBR     | 74       | 29.02%  |
| Unknown | 22       | 8.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 195      | 76.77%  |
| Yes       | 59       | 23.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 160      | 62.75%  |
| Yes       | 95       | 37.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 65       | 25.59%  |
| ASRock              | 51       | 20.08%  |
| Gigabyte Technology | 40       | 15.75%  |
| MSI                 | 27       | 10.63%  |
| Dell                | 20       | 7.87%   |
| Hewlett-Packard     | 16       | 6.3%    |
| Intel               | 7        | 2.76%   |
| Lenovo              | 4        | 1.57%   |
| Supermicro          | 2        | 0.79%   |
| Semp Toshiba        | 2        | 0.79%   |
| Huanan              | 2        | 0.79%   |
| Foxconn             | 2        | 0.79%   |
| ECS                 | 2        | 0.79%   |
| Biostar             | 2        | 0.79%   |
| Unknown             | 2        | 0.79%   |
| Shuttle             | 1        | 0.39%   |
| Protectli           | 1        | 0.39%   |
| Pegatron            | 1        | 0.39%   |
| NC9VL               | 1        | 0.39%   |
| HARDKERNEL          | 1        | 0.39%   |
| Fujitsu Siemens     | 1        | 0.39%   |
| Fujitsu             | 1        | 0.39%   |
| ASRockRack          | 1        | 0.39%   |
| AOpen               | 1        | 0.39%   |
| AAEON               | 1        | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASRock H470M-HVS                  | 19       | 7.48%   |
| ASUS All Series                   | 7        | 2.76%   |
| Gigabyte Z77-D3H                  | 3        | 1.18%   |
| Gigabyte B550I AORUS PRO AX       | 3        | 1.18%   |
| ASRock B450M Pro4                 | 3        | 1.18%   |
| Semp Toshiba STI                  | 2        | 0.79%   |
| MSI MS-7A71                       | 2        | 0.79%   |
| MSI MS-7A70                       | 2        | 0.79%   |
| MSI MS-7721                       | 2        | 0.79%   |
| Intel DN2820FYK H24582-201        | 2        | 0.79%   |
| HP Z620 Workstation               | 2        | 0.79%   |
| Gigabyte Z370 AORUS Gaming 5      | 2        | 0.79%   |
| Gigabyte X570 I AORUS PRO WIFI    | 2        | 0.79%   |
| Gigabyte 970A-DS3P                | 2        | 0.79%   |
| Dell OptiPlex 760                 | 2        | 0.79%   |
| Dell OptiPlex 7010                | 2        | 0.79%   |
| Dell OptiPlex 3020                | 2        | 0.79%   |
| ASUS TUF GAMING X570-PRO          | 2        | 0.79%   |
| ASUS ROG STRIX B450-F GAMING      | 2        | 0.79%   |
| ASUS PRIME B550-PLUS              | 2        | 0.79%   |
| ASUS PRIME B450M-A                | 2        | 0.79%   |
| ASUS PRIME A320M-K                | 2        | 0.79%   |
| ASUS P5KPL-CM                     | 2        | 0.79%   |
| ASRock H61M-VG4                   | 2        | 0.79%   |
| Unknown                           | 2        | 0.79%   |
| Supermicro SYS-5038MA-H24TRF      | 1        | 0.39%   |
| Supermicro SYS-5019S-MR           | 1        | 0.39%   |
| Shuttle SX79R                     | 1        | 0.39%   |
| Protectli FW6                     | 1        | 0.39%   |
| Pegatron NP267AA-A2L e9180f       | 1        | 0.39%   |
| NC9VL 1.0                         | 1        | 0.39%   |
| MSI MS-7C94                       | 1        | 0.39%   |
| MSI MS-7C84                       | 1        | 0.39%   |
| MSI MS-7C75                       | 1        | 0.39%   |
| MSI MS-7C56                       | 1        | 0.39%   |
| MSI MS-7C35                       | 1        | 0.39%   |
| MSI MS-7C02                       | 1        | 0.39%   |
| MSI MS-7B92                       | 1        | 0.39%   |
| MSI MS-7B89                       | 1        | 0.39%   |
| MSI MS-7B84                       | 1        | 0.39%   |
| MSI MS-7B79                       | 1        | 0.39%   |
| MSI MS-7B46                       | 1        | 0.39%   |
| MSI MS-7B09                       | 1        | 0.39%   |
| MSI MS-7A40                       | 1        | 0.39%   |
| MSI MS-7A38                       | 1        | 0.39%   |
| MSI MS-7995                       | 1        | 0.39%   |
| MSI MS-7978                       | 1        | 0.39%   |
| MSI MS-7823                       | 1        | 0.39%   |
| MSI MS-7759                       | 1        | 0.39%   |
| MSI MS-7641                       | 1        | 0.39%   |
| MSI MS-7562                       | 1        | 0.39%   |
| MSI MS-6712                       | 1        | 0.39%   |
| Lenovo ThinkCentre M92p 3209EK4   | 1        | 0.39%   |
| Lenovo ThinkCentre M73 10B00005US | 1        | 0.39%   |
| Lenovo ThinkCentre M55p 8808D8U   | 1        | 0.39%   |
| Lenovo H330                       | 1        | 0.39%   |
| Intel Pro, Std, Elt Series        | 1        | 0.39%   |
| Intel DP55WG AAE57269-407         | 1        | 0.39%   |
| Intel DP55WB AAE64798-206         | 1        | 0.39%   |
| Intel DH77KC AAG39641-400         | 1        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASRock H470M-HVS             | 19       | 7.48%   |
| ASUS PRIME                   | 18       | 7.09%   |
| Dell OptiPlex                | 13       | 5.12%   |
| ASUS ROG                     | 10       | 3.94%   |
| ASUS All                     | 7        | 2.76%   |
| Dell Precision               | 6        | 2.36%   |
| HP Compaq                    | 5        | 1.97%   |
| Lenovo ThinkCentre           | 3        | 1.18%   |
| Gigabyte Z77-D3H             | 3        | 1.18%   |
| Gigabyte B550I               | 3        | 1.18%   |
| ASUS TUF                     | 3        | 1.18%   |
| ASRock Z97                   | 3        | 1.18%   |
| ASRock B450M                 | 3        | 1.18%   |
| Semp Toshiba STI             | 2        | 0.79%   |
| MSI MS-7A71                  | 2        | 0.79%   |
| MSI MS-7A70                  | 2        | 0.79%   |
| MSI MS-7721                  | 2        | 0.79%   |
| Intel DN2820FYK              | 2        | 0.79%   |
| HP Z620                      | 2        | 0.79%   |
| HP ProLiant                  | 2        | 0.79%   |
| Gigabyte Z370                | 2        | 0.79%   |
| Gigabyte X570                | 2        | 0.79%   |
| Gigabyte 970A-DS3P           | 2        | 0.79%   |
| ASUS Pro                     | 2        | 0.79%   |
| ASUS P5KPL-CM                | 2        | 0.79%   |
| ASRock H77                   | 2        | 0.79%   |
| ASRock H61M-VG4              | 2        | 0.79%   |
| Unknown                      | 2        | 0.79%   |
| Supermicro SYS-5038MA-H24TRF | 1        | 0.39%   |
| Supermicro SYS-5019S-MR      | 1        | 0.39%   |
| Shuttle SX79R                | 1        | 0.39%   |
| Protectli FW6                | 1        | 0.39%   |
| Pegatron NP267AA-A2L         | 1        | 0.39%   |
| NC9VL 1.0                    | 1        | 0.39%   |
| MSI MS-7C94                  | 1        | 0.39%   |
| MSI MS-7C84                  | 1        | 0.39%   |
| MSI MS-7C75                  | 1        | 0.39%   |
| MSI MS-7C56                  | 1        | 0.39%   |
| MSI MS-7C35                  | 1        | 0.39%   |
| MSI MS-7C02                  | 1        | 0.39%   |
| MSI MS-7B92                  | 1        | 0.39%   |
| MSI MS-7B89                  | 1        | 0.39%   |
| MSI MS-7B84                  | 1        | 0.39%   |
| MSI MS-7B79                  | 1        | 0.39%   |
| MSI MS-7B46                  | 1        | 0.39%   |
| MSI MS-7B09                  | 1        | 0.39%   |
| MSI MS-7A40                  | 1        | 0.39%   |
| MSI MS-7A38                  | 1        | 0.39%   |
| MSI MS-7995                  | 1        | 0.39%   |
| MSI MS-7978                  | 1        | 0.39%   |
| MSI MS-7823                  | 1        | 0.39%   |
| MSI MS-7759                  | 1        | 0.39%   |
| MSI MS-7641                  | 1        | 0.39%   |
| MSI MS-7562                  | 1        | 0.39%   |
| MSI MS-6712                  | 1        | 0.39%   |
| Lenovo H330                  | 1        | 0.39%   |
| Intel Pro                    | 1        | 0.39%   |
| Intel DP55WG                 | 1        | 0.39%   |
| Intel DP55WB                 | 1        | 0.39%   |
| Intel DH77KC                 | 1        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 43       | 16.93%  |
| 2020 | 36       | 14.17%  |
| 2018 | 33       | 12.99%  |
| 2019 | 32       | 12.6%   |
| 2016 | 14       | 5.51%   |
| 2015 | 14       | 5.51%   |
| 2014 | 13       | 5.12%   |
| 2013 | 12       | 4.72%   |
| 2012 | 12       | 4.72%   |
| 2010 | 11       | 4.33%   |
| 2009 | 10       | 3.94%   |
| 2017 | 6        | 2.36%   |
| 2011 | 6        | 2.36%   |
| 2008 | 4        | 1.57%   |
| 2007 | 3        | 1.18%   |
| 2006 | 3        | 1.18%   |
| 2004 | 1        | 0.39%   |
| 2001 | 1        | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 254      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 251      | 98.82%  |
| Enabled  | 3        | 1.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 253      | 99.61%  |
| Yes  | 1        | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 68       | 26.77%  |
| 32.01-64.0      | 58       | 22.83%  |
| 8.01-16.0       | 46       | 18.11%  |
| 64.01-256.0     | 23       | 9.06%   |
| 4.01-8.0        | 22       | 8.66%   |
| 3.01-4.0        | 15       | 5.91%   |
| 1.01-2.0        | 10       | 3.94%   |
| 24.01-32.0      | 5        | 1.97%   |
| 2.01-3.0        | 3        | 1.18%   |
| 0.51-1.0        | 2        | 0.79%   |
| More than 256.0 | 1        | 0.39%   |
| 0.01-0.5        | 1        | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.51-1.0    | 54       | 20.93%  |
| 1.01-2.0    | 43       | 16.67%  |
| 3.01-4.0    | 40       | 15.5%   |
| 4.01-8.0    | 38       | 14.73%  |
| 2.01-3.0    | 36       | 13.95%  |
| 0.01-0.5    | 16       | 6.2%    |
| 8.01-16.0   | 15       | 5.81%   |
| 16.01-24.0  | 7        | 2.71%   |
| 24.01-32.0  | 4        | 1.55%   |
| 32.01-64.0  | 3        | 1.16%   |
| 64.01-256.0 | 2        | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 83       | 32.68%  |
| 2      | 80       | 31.5%   |
| 3      | 37       | 14.57%  |
| 4      | 23       | 9.06%   |
| 5      | 12       | 4.72%   |
| 8      | 5        | 1.97%   |
| 6      | 5        | 1.97%   |
| 9      | 3        | 1.18%   |
| 10     | 2        | 0.79%   |
| 0      | 2        | 0.79%   |
| 13     | 1        | 0.39%   |
| 12     | 1        | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 148      | 58.27%  |
| Yes       | 106      | 41.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 252      | 99.21%  |
| No        | 2        | 0.79%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 181      | 71.26%  |
| Yes       | 73       | 28.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 190      | 74.8%   |
| Yes       | 64       | 25.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 55       | 21.65%  |
| Russia                 | 49       | 19.29%  |
| France                 | 17       | 6.69%   |
| UK                     | 15       | 5.91%   |
| Germany                | 15       | 5.91%   |
| Ukraine                | 12       | 4.72%   |
| Spain                  | 10       | 3.94%   |
| Brazil                 | 7        | 2.76%   |
| Poland                 | 6        | 2.36%   |
| Belgium                | 5        | 1.97%   |
| Australia              | 5        | 1.97%   |
| Netherlands            | 4        | 1.57%   |
| Mexico                 | 4        | 1.57%   |
| Canada                 | 4        | 1.57%   |
| Bulgaria               | 4        | 1.57%   |
| Sweden                 | 3        | 1.18%   |
| Czechia                | 3        | 1.18%   |
| Argentina              | 3        | 1.18%   |
| Venezuela              | 2        | 0.79%   |
| Switzerland            | 2        | 0.79%   |
| Romania                | 2        | 0.79%   |
| Norway                 | 2        | 0.79%   |
| Japan                  | 2        | 0.79%   |
| Italy                  | 2        | 0.79%   |
| Hungary                | 2        | 0.79%   |
| Finland                | 2        | 0.79%   |
| Austria                | 2        | 0.79%   |
| Turkey                 | 1        | 0.39%   |
| Syria                  | 1        | 0.39%   |
| Singapore              | 1        | 0.39%   |
| Serbia                 | 1        | 0.39%   |
| Portugal               | 1        | 0.39%   |
| New Zealand            | 1        | 0.39%   |
| New Caledonia          | 1        | 0.39%   |
| Madagascar             | 1        | 0.39%   |
| Ireland                | 1        | 0.39%   |
| India                  | 1        | 0.39%   |
| Hong Kong              | 1        | 0.39%   |
| Greece                 | 1        | 0.39%   |
| Ecuador                | 1        | 0.39%   |
| Croatia                | 1        | 0.39%   |
| Bosnia and Herzegovina | 1        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Voronezh             | 30       | 11.72%  |
| Portland             | 6        | 2.34%   |
| Ocala                | 6        | 2.34%   |
| Kyiv                 | 6        | 2.34%   |
| Lyon                 | 5        | 1.95%   |
| London               | 5        | 1.95%   |
| Sofia                | 4        | 1.56%   |
| Moscow               | 3        | 1.17%   |
| Kalamazoo            | 3        | 1.17%   |
| Frankfort            | 3        | 1.17%   |
| Ensenada             | 3        | 1.17%   |
| Warsaw               | 2        | 0.78%   |
| Vienna               | 2        | 0.78%   |
| Stockholm            | 2        | 0.78%   |
| S??o Paulo           | 2        | 0.78%   |
| Saint-Denis          | 2        | 0.78%   |
| Perm                 | 2        | 0.78%   |
| Paris                | 2        | 0.78%   |
| New York             | 2        | 0.78%   |
| Las Vegas            | 2        | 0.78%   |
| Kharkiv              | 2        | 0.78%   |
| Iasi                 | 2        | 0.78%   |
| Herndon              | 2        | 0.78%   |
| Clitheroe            | 2        | 0.78%   |
| Barcelona            | 2        | 0.78%   |
| Athens               | 2        | 0.78%   |
| Amsterdam            | 2        | 0.78%   |
| Érd                 | 1        | 0.39%   |
| Zastavka             | 1        | 0.39%   |
| Zagreb               | 1        | 0.39%   |
| Yuncos               | 1        | 0.39%   |
| Ypres                | 1        | 0.39%   |
| Yekaterinburg        | 1        | 0.39%   |
| Wroclaw              | 1        | 0.39%   |
| Woolloongabba        | 1        | 0.39%   |
| Woodstock            | 1        | 0.39%   |
| Wenatchee            | 1        | 0.39%   |
| Waregem              | 1        | 0.39%   |
| Voerde               | 1        | 0.39%   |
| Vladivostok          | 1        | 0.39%   |
| Vladimir             | 1        | 0.39%   |
| V?�nissieux          | 1        | 0.39%   |
| Vandoeuvre-les-Nancy | 1        | 0.39%   |
| Vancouver            | 1        | 0.39%   |
| Valladolid           | 1        | 0.39%   |
| Valera               | 1        | 0.39%   |
| Vaasa                | 1        | 0.39%   |
| Ulyanovsk            | 1        | 0.39%   |
| Ufa                  | 1        | 0.39%   |
| Turku                | 1        | 0.39%   |
| Toulouse             | 1        | 0.39%   |
| Torrox Costa         | 1        | 0.39%   |
| Thionville           | 1        | 0.39%   |
| Tai Kok Tsui         | 1        | 0.39%   |
| Stroud               | 1        | 0.39%   |
| Strasbourg           | 1        | 0.39%   |
| Stockelsdorf         | 1        | 0.39%   |
| Stavanger            | 1        | 0.39%   |
| St Petersburg        | 1        | 0.39%   |
| Springfield          | 1        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 92       | 152    | 19.74%  |
| WDC                 | 80       | 132    | 17.17%  |
| Samsung Electronics | 67       | 100    | 14.38%  |
| Toshiba             | 42       | 60     | 9.01%   |
| Kingston            | 29       | 34     | 6.22%   |
| Crucial             | 28       | 33     | 6.01%   |
| Netac               | 19       | 19     | 4.08%   |
| SanDisk             | 15       | 18     | 3.22%   |
| Hitachi             | 15       | 16     | 3.22%   |
| Intel               | 11       | 18     | 2.36%   |
| HGST                | 7        | 9      | 1.5%    |
| PNY                 | 6        | 6      | 1.29%   |
| A-DATA Technology   | 6        | 9      | 1.29%   |
| SPCC                | 5        | 5      | 1.07%   |
| Unknown             | 4        | 4      | 0.86%   |
| OCZ                 | 3        | 3      | 0.64%   |
| Gigabyte Technology | 3        | 3      | 0.64%   |
| Transcend           | 2        | 3      | 0.43%   |
| SABRENT             | 2        | 2      | 0.43%   |
| Phison Electronics  | 2        | 2      | 0.43%   |
| Phison              | 2        | 2      | 0.43%   |
| Micron Technology   | 2        | 2      | 0.43%   |
| MAXTOR              | 2        | 2      | 0.43%   |
| Hewlett-Packard     | 2        | 3      | 0.43%   |
| Corsair             | 2        | 2      | 0.43%   |
| China               | 2        | 2      | 0.43%   |
| Team                | 1        | 1      | 0.21%   |
| T-FORCE             | 1        | 1      | 0.21%   |
| SK Hynix            | 1        | 4      | 0.21%   |
| PNY USB             | 1        | 1      | 0.21%   |
| PLEXTOR             | 1        | 2      | 0.21%   |
| Patriot             | 1        | 1      | 0.21%   |
| NAS                 | 1        | 5      | 0.21%   |
| Mushkin             | 1        | 1      | 0.21%   |
| MaxDigital          | 1        | 2      | 0.21%   |
| LITEON              | 1        | 1      | 0.21%   |
| Lexar               | 1        | 1      | 0.21%   |
| KingDian            | 1        | 1      | 0.21%   |
| Intenso             | 1        | 2      | 0.21%   |
| GOODRAM             | 1        | 1      | 0.21%   |
| DOGFISH             | 1        | 1      | 0.21%   |
| 128MB               | 1        | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Toshiba HDWD110 1TB                          | 22       | 3.96%   |
| Netac SSD 240GB                              | 19       | 3.42%   |
| Samsung SSD 860 EVO 1TB                      | 9        | 1.62%   |
| Seagate ST1000DM010-2EP102 1TB               | 8        | 1.44%   |
| Seagate ST500DM002-1BD142 500GB              | 7        | 1.26%   |
| Kingston SA400S37120G 120GB SSD              | 7        | 1.26%   |
| Samsung SSD 850 EVO 250GB                    | 6        | 1.08%   |
| Kingston SV300S37A120G 120GB SSD             | 6        | 1.08%   |
| Seagate ST4000DM004-2CV104 4TB               | 5        | 0.9%    |
| Seagate ST2000DM001-1ER164 2TB               | 5        | 0.9%    |
| Samsung SSD 970 EVO Plus 500GB               | 5        | 0.9%    |
| Samsung SSD 970 EVO Plus 1TB                 | 5        | 0.9%    |
| Samsung SSD 970 EVO 500GB                    | 5        | 0.9%    |
| Samsung SSD 850 EVO 500GB                    | 5        | 0.9%    |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 4        | 0.72%   |
| Toshiba DT01ACA300 3TB                       | 4        | 0.72%   |
| Toshiba DT01ACA200 2TB                       | 4        | 0.72%   |
| Seagate ST2000DM008-2FR102 2TB               | 4        | 0.72%   |
| Samsung SSD 980 PRO 1TB                      | 4        | 0.72%   |
| Kingston SA400S37240G 240GB SSD              | 4        | 0.72%   |
| Crucial CT500MX500SSD1 500GB                 | 4        | 0.72%   |
| WDC WDS500G3X0C-00SJG0 500GB                 | 3        | 0.54%   |
| WDC WDS120G2G0A-00JH30 120GB SSD             | 3        | 0.54%   |
| WDC WD40EFRX-68N32N0 4TB                     | 3        | 0.54%   |
| WDC WD10EZEX-08WN4A0 1TB                     | 3        | 0.54%   |
| WDC WD10EZEX-00BN5A0 1TB                     | 3        | 0.54%   |
| Seagate ST3000DM001-1CH166 3TB               | 3        | 0.54%   |
| Seagate Backup+ Hub BK 10TB                  | 3        | 0.54%   |
| SanDisk SD8SBAT128G1122 128GB SSD            | 3        | 0.54%   |
| Samsung SSD 860 EVO 250GB                    | 3        | 0.54%   |
| Kingston SV300S37A240G 240GB SSD             | 3        | 0.54%   |
| Hitachi HUS724040ALE641 4TB                  | 3        | 0.54%   |
| Crucial CT500P1SSD8 500GB                    | 3        | 0.54%   |
| Crucial CT240BX500SSD1 240GB                 | 3        | 0.54%   |
| Crucial CT1000MX500SSD1 1TB                  | 3        | 0.54%   |
| WDC WDS500G2B0C-00PXH0 500GB                 | 2        | 0.36%   |
| WDC WD5000AADS-00S9B0 500GB                  | 2        | 0.36%   |
| WDC WD40EZRZ-00GXCB0 4TB                     | 2        | 0.36%   |
| WDC WD20EZAZ-00GGJB0 2TB                     | 2        | 0.36%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 2        | 0.36%   |
| WDC WD20EARX-00PASB0 2TB                     | 2        | 0.36%   |
| WDC WD20EARS-00MVWB0 2TB                     | 2        | 0.36%   |
| WDC WD10EFRX-68FYTN0 1TB                     | 2        | 0.36%   |
| WDC WD1003FZEX-00MK2A0 1TB                   | 2        | 0.36%   |
| Toshiba DT01ACA100 1TB                       | 2        | 0.36%   |
| Seagate ST4000DM000-1F2168 4TB               | 2        | 0.36%   |
| Seagate ST3320620A 320GB                     | 2        | 0.36%   |
| Seagate ST3160815AS 160GB                    | 2        | 0.36%   |
| Seagate ST3160813AS 160GB                    | 2        | 0.36%   |
| Seagate ST3120811AS 120GB                    | 2        | 0.36%   |
| Seagate ST2000DM006-2DM164 2TB               | 2        | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB               | 2        | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB               | 2        | 0.36%   |
| Seagate Expansion 2TB                        | 2        | 0.36%   |
| Seagate BUP Slim BL 2TB                      | 2        | 0.36%   |
| Seagate BarraCuda 120 SSD ZA250CM10003 250GB | 2        | 0.36%   |
| SanDisk SSD PLUS 240GB                       | 2        | 0.36%   |
| Sandisk NVMe SSD Drive 1TB                   | 2        | 0.36%   |
| Samsung SSD 960 EVO 250GB                    | 2        | 0.36%   |
| Samsung SSD 860 EVO 500GB                    | 2        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 88       | 136    | 38.1%   |
| WDC                 | 66       | 109    | 28.57%  |
| Toshiba             | 40       | 56     | 17.32%  |
| Hitachi             | 15       | 16     | 6.49%   |
| Samsung Electronics | 10       | 11     | 4.33%   |
| HGST                | 7        | 9      | 3.03%   |
| Maxtor              | 2        | 2      | 0.87%   |
| NAS                 | 1        | 5      | 0.43%   |
| MaxDigital          | 1        | 2      | 0.43%   |
| 128MB               | 1        | 1      | 0.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 37       | 53     | 21.64%  |
| Kingston            | 28       | 32     | 16.37%  |
| Crucial             | 22       | 24     | 12.87%  |
| Netac               | 19       | 19     | 11.11%  |
| SanDisk             | 12       | 14     | 7.02%   |
| WDC                 | 11       | 12     | 6.43%   |
| A-DATA Technology   | 6        | 8      | 3.51%   |
| SPCC                | 4        | 4      | 2.34%   |
| PNY                 | 4        | 4      | 2.34%   |
| OCZ                 | 3        | 3      | 1.75%   |
| Unknown             | 2        | 2      | 1.17%   |
| Transcend           | 2        | 3      | 1.17%   |
| Toshiba             | 2        | 4      | 1.17%   |
| Seagate             | 2        | 2      | 1.17%   |
| SABRENT             | 2        | 2      | 1.17%   |
| China               | 2        | 2      | 1.17%   |
| Team                | 1        | 1      | 0.58%   |
| T-FORCE             | 1        | 1      | 0.58%   |
| PNY USB             | 1        | 1      | 0.58%   |
| PLEXTOR             | 1        | 2      | 0.58%   |
| Patriot             | 1        | 1      | 0.58%   |
| Mushkin             | 1        | 1      | 0.58%   |
| Micron Technology   | 1        | 1      | 0.58%   |
| Lexar               | 1        | 1      | 0.58%   |
| KingDian            | 1        | 1      | 0.58%   |
| Intel               | 1        | 1      | 0.58%   |
| GOODRAM             | 1        | 1      | 0.58%   |
| Gigabyte Technology | 1        | 1      | 0.58%   |
| DOGFISH             | 1        | 1      | 0.58%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 181      | 347    | 43.51%  |
| SSD     | 154      | 202    | 37.02%  |
| NVMe    | 72       | 100    | 17.31%  |
| Unknown | 7        | 16     | 1.68%   |
| MMC     | 2        | 2      | 0.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 231      | 538    | 71.74%  |
| NVMe | 72       | 100    | 22.36%  |
| SAS  | 17       | 27     | 5.28%   |
| MMC  | 2        | 2      | 0.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 169      | 245    | 46.05%  |
| 0.51-1.0   | 104      | 130    | 28.34%  |
| 1.01-2.0   | 44       | 62     | 11.99%  |
| 3.01-4.0   | 20       | 47     | 5.45%   |
| 4.01-10.0  | 14       | 30     | 3.81%   |
| 2.01-3.0   | 12       | 19     | 3.27%   |
| 10.01-20.0 | 4        | 16     | 1.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 40       | 15.75%  |
| Unknown        | 39       | 15.35%  |
| 251-500        | 33       | 12.99%  |
| 101-250        | 33       | 12.99%  |
| 501-1000       | 28       | 11.02%  |
| 1001-2000      | 24       | 9.45%   |
| 1-20           | 24       | 9.45%   |
| 2001-3000      | 14       | 5.51%   |
| 51-100         | 13       | 5.12%   |
| 21-50          | 6        | 2.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 62       | 24.31%  |
| Unknown        | 39       | 15.29%  |
| 101-250        | 27       | 10.59%  |
| 501-1000       | 24       | 9.41%   |
| 51-100         | 21       | 8.24%   |
| 21-50          | 20       | 7.84%   |
| More than 3000 | 19       | 7.45%   |
| 251-500        | 19       | 7.45%   |
| 1001-2000      | 16       | 6.27%   |
| 2001-3000      | 7        | 2.75%   |
| 0              | 1        | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 3.17%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 3.17%   |
| Seagate ST3160813AS 160GB             | 2        | 2      | 3.17%   |
| Kingston SV300S37A120G 120GB SSD      | 2        | 2      | 3.17%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1        | 1      | 1.59%   |
| WDC WD5003ABYX-18WERA0 500GB          | 1        | 2      | 1.59%   |
| WDC WD5000AAKX-00U6AA0 500GB          | 1        | 1      | 1.59%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 1.59%   |
| WDC WD5000AAKS-22V1A0 500GB           | 1        | 1      | 1.59%   |
| WDC WD5000AAJS-22A8B0 500GB           | 1        | 1      | 1.59%   |
| WDC WD40EFZX-68AWUN0 4TB              | 1        | 6      | 1.59%   |
| WDC WD400BB-00DEA0 40GB               | 1        | 1      | 1.59%   |
| WDC WD30EZRX-00AZ6B0 3TB              | 1        | 1      | 1.59%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 1.59%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 1.59%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1        | 1      | 1.59%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1        | 1      | 1.59%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 1.59%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 1.59%   |
| WDC WD1001FALS-75J7B0 1TB             | 1        | 1      | 1.59%   |
| Toshiba MK2565GSX 250GB               | 1        | 1      | 1.59%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 1.59%   |
| SK Hynix PC401 NVMe 512GB             | 1        | 4      | 1.59%   |
| Seagate ST9500325AS 500GB             | 1        | 2      | 1.59%   |
| Seagate ST340014A 40GB                | 1        | 1      | 1.59%   |
| Seagate ST3320620A 320GB              | 1        | 1      | 1.59%   |
| Seagate ST3200827AS 200GB             | 1        | 2      | 1.59%   |
| Seagate ST32000542AS 2TB              | 1        | 1      | 1.59%   |
| Seagate ST31500341AS 1TB              | 1        | 1      | 1.59%   |
| Seagate ST3120827AS 120GB             | 1        | 2      | 1.59%   |
| Seagate ST3120811AS 120GB             | 1        | 1      | 1.59%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 1.59%   |
| Seagate ST31000333AS 1TB              | 1        | 1      | 1.59%   |
| Seagate ST3000DM001-9YN166 320GB      | 1        | 1      | 1.59%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 1.59%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 1.59%   |
| Seagate ST1000DM003-9YN162 1TB        | 1        | 1      | 1.59%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 1.59%   |
| Seagate ST10000NE0004-1ZF101 10TB     | 1        | 1      | 1.59%   |
| SanDisk SSD PLUS 120 GB               | 1        | 1      | 1.59%   |
| Samsung Electronics SSD 970 EVO 250GB | 1        | 1      | 1.59%   |
| Samsung Electronics SP0842N 80GB      | 1        | 1      | 1.59%   |
| Samsung Electronics HD161GJ 160GB     | 1        | 1      | 1.59%   |
| Samsung Electronics HD103SI 1TB       | 1        | 1      | 1.59%   |
| PNY SSD2SC240G3LC709B121-460P 240GB   | 1        | 1      | 1.59%   |
| Maxtor 6B300S0 304GB                  | 1        | 1      | 1.59%   |
| Kingston SE100S3100G 100GB SSD        | 1        | 1      | 1.59%   |
| KingDian S280 240GB                   | 1        | 1      | 1.59%   |
| Intel SSDPEKKW010T7 1TB               | 1        | 2      | 1.59%   |
| Hitachi HUA722020ALA331 2TB           | 1        | 1      | 1.59%   |
| Hitachi HUA722010ALA330 1TB           | 1        | 1      | 1.59%   |
| Hitachi HTS547575A9E384 752GB         | 1        | 1      | 1.59%   |
| Hitachi HDS722525VLAT80 250GB         | 1        | 1      | 1.59%   |
| Crucial CT128MX100SSD1 128GB          | 1        | 1      | 1.59%   |
| China SATA SSD 120GB                  | 1        | 1      | 1.59%   |
| A-DATA Technology SU800 256GB SSD     | 1        | 2      | 1.59%   |
| A-DATA Technology SU650 480GB SSD     | 1        | 1      | 1.59%   |
| A-DATA Technology SSD DP900 128GB-DL3 | 1        | 1      | 1.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 24     | 31.15%  |
| WDC                 | 18       | 25     | 29.51%  |
| Samsung Electronics | 4        | 4      | 6.56%   |
| Hitachi             | 4        | 4      | 6.56%   |
| Kingston            | 3        | 3      | 4.92%   |
| A-DATA Technology   | 3        | 4      | 4.92%   |
| Toshiba             | 2        | 2      | 3.28%   |
| SK Hynix            | 1        | 4      | 1.64%   |
| SanDisk             | 1        | 1      | 1.64%   |
| PNY                 | 1        | 1      | 1.64%   |
| Maxtor              | 1        | 1      | 1.64%   |
| KingDian            | 1        | 1      | 1.64%   |
| Intel               | 1        | 2      | 1.64%   |
| Crucial             | 1        | 1      | 1.64%   |
| China               | 1        | 1      | 1.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 24     | 40.43%  |
| WDC                 | 18       | 25     | 38.3%   |
| Hitachi             | 4        | 4      | 8.51%   |
| Samsung Electronics | 3        | 3      | 6.38%   |
| Toshiba             | 2        | 2      | 4.26%   |
| Maxtor              | 1        | 1      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 42       | 59     | 75%     |
| SSD  | 11       | 12     | 19.64%  |
| NVMe | 3        | 7      | 5.36%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM005 HD502HJ 500GB | 1        | 1      | 50%     |
| Seagate ST3500830AS 500GB        | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 220      | 512    | 72.13%  |
| Malfunc  | 51       | 78     | 16.72%  |
| Detected | 32       | 75     | 10.49%  |
| Failed   | 2        | 2      | 0.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 161      | 45.22%  |
| AMD                         | 88       | 24.72%  |
| Samsung Electronics         | 32       | 8.99%   |
| ASMedia Technology          | 11       | 3.09%   |
| Sandisk                     | 10       | 2.81%   |
| Phison Electronics          | 10       | 2.81%   |
| Marvell Technology Group    | 10       | 2.81%   |
| JMicron Technology          | 8        | 2.25%   |
| Micron/Crucial Technology   | 7        | 1.97%   |
| VIA Technologies            | 3        | 0.84%   |
| Broadcom / LSI              | 3        | 0.84%   |
| Silicon Motion              | 2        | 0.56%   |
| Nvidia                      | 2        | 0.56%   |
| Kingston Technology Company | 2        | 0.56%   |
| SK Hynix                    | 1        | 0.28%   |
| Silicon Image               | 1        | 0.28%   |
| Seagate Technology          | 1        | 0.28%   |
| Micron Technology           | 1        | 0.28%   |
| Lite-On Technology          | 1        | 0.28%   |
| ADATA Technology            | 1        | 0.28%   |
| Adaptec                     | 1        | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 58       | 12.95%  |
| Intel Comet Lake SATA AHCI Controller                                                   | 24       | 5.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 22       | 4.91%   |
| AMD 400 Series Chipset SATA Controller                                                  | 21       | 4.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18       | 4.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 16       | 3.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12       | 2.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12       | 2.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11       | 2.46%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 2.23%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 10       | 2.23%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 2.01%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 1.79%   |
| Phison E12 NVMe Controller                                                              | 6        | 1.34%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 1.34%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 1.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 1.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 1.12%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 5        | 1.12%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 1.12%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4        | 0.89%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 4        | 0.89%   |
| AMD X399 Series Chipset SATA Controller                                                 | 4        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 0.89%   |
| AMD FCH SATA Controller D                                                               | 4        | 0.89%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.67%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 3        | 0.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 0.67%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 0.67%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3        | 0.67%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 0.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 0.67%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 3        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.67%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 0.67%   |
| AMD X370 Series Chipset SATA Controller                                                 | 3        | 0.67%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.45%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.45%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.45%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.45%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.45%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.45%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.45%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2        | 0.45%   |
| Intel SSD 660P Series                                                                   | 2        | 0.45%   |
| Intel SSD 600P Series                                                                   | 2        | 0.45%   |
| Intel NVMe Optane Memory Series                                                         | 2        | 0.45%   |
| Intel Non-Volatile memory controller                                                    | 2        | 0.45%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.45%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.45%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 0.45%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                        | 2        | 0.45%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 0.45%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 0.45%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 2        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 216      | 60.5%   |
| NVMe | 72       | 20.17%  |
| IDE  | 48       | 13.45%  |
| RAID | 15       | 4.2%    |
| SAS  | 6        | 1.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 162      | 63.78%  |
| AMD          | 91       | 35.83%  |
| CentaurHauls | 1        | 0.39%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-10700 CPU @ 2.90GHz              | 21       | 8.27%   |
| AMD Ryzen 5 3600 6-Core Processor              | 10       | 3.94%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 5        | 1.97%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 4        | 1.57%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 4        | 1.57%   |
| Intel Core i7-7700 CPU @ 3.60GHz               | 3        | 1.18%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 3        | 1.18%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 3        | 1.18%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 3        | 1.18%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 3        | 1.18%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 3        | 1.18%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 3        | 1.18%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 3        | 1.18%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 3        | 1.18%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 3        | 1.18%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz         | 2        | 0.79%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 0.79%   |
| Intel Core i7-8086K CPU @ 4.00GHz              | 2        | 0.79%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 2        | 0.79%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 2        | 0.79%   |
| Intel Core i5-6600 CPU @ 3.30GHz               | 2        | 0.79%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 2        | 0.79%   |
| Intel Core i5-4460 CPU @ 3.20GHz               | 2        | 0.79%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 2        | 0.79%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 2        | 0.79%   |
| Intel Core i5 CPU 650 @ 3.20GHz                | 2        | 0.79%   |
| Intel Core i3-3210 CPU @ 3.20GHz               | 2        | 0.79%   |
| Intel Core i3-10100 CPU @ 3.60GHz              | 2        | 0.79%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 2        | 0.79%   |
| Intel Celeron CPU N2820 @ 2.13GHz              | 2        | 0.79%   |
| Intel Atom CPU C2750 @ 2.40GHz                 | 2        | 0.79%   |
| AMD Ryzen Threadripper 2950X 16-Core Processor | 2        | 0.79%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 2        | 0.79%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 2        | 0.79%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 0.79%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 2        | 0.79%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 2        | 0.79%   |
| AMD Ryzen 3 1200 Quad-Core Processor           | 2        | 0.79%   |
| AMD Phenom II X4 965 Processor                 | 2        | 0.79%   |
| AMD FX-8350 Eight-Core Processor               | 2        | 0.79%   |
| AMD FX-8120 Eight-Core Processor               | 2        | 0.79%   |
| AMD FX-4300 Quad-Core Processor                | 2        | 0.79%   |
| Intel Xeon W-2145 CPU @ 3.70GHz                | 1        | 0.39%   |
| Intel Xeon CPU W3503 @ 2.40GHz                 | 1        | 0.39%   |
| Intel Xeon CPU E5-2699 v4 @ 2.20GHz            | 1        | 0.39%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz            | 1        | 0.39%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz             | 1        | 0.39%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz            | 1        | 0.39%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz             | 1        | 0.39%   |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz            | 1        | 0.39%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz             | 1        | 0.39%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz             | 1        | 0.39%   |
| Intel Xeon CPU E3-1230 v6 @ 3.50GHz            | 1        | 0.39%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz            | 1        | 0.39%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz    | 1        | 0.39%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 1        | 0.39%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1        | 0.39%   |
| Intel Pentium CPU N3700 @ 1.60GHz              | 1        | 0.39%   |
| Intel Pentium CPU J4205 @ 1.50GHz              | 1        | 0.39%   |
| Intel Pentium CPU G630 @ 2.70GHz               | 1        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 48       | 18.9%   |
| Intel Core i5           | 41       | 16.14%  |
| AMD Ryzen 5             | 25       | 9.84%   |
| AMD Ryzen 7             | 18       | 7.09%   |
| Intel Core i3           | 13       | 5.12%   |
| Intel Xeon              | 12       | 4.72%   |
| Intel Core 2 Duo        | 10       | 3.94%   |
| Intel Pentium           | 9        | 3.54%   |
| AMD FX                  | 9        | 3.54%   |
| Intel Celeron           | 8        | 3.15%   |
| AMD Ryzen Threadripper  | 6        | 2.36%   |
| AMD Ryzen 9             | 6        | 2.36%   |
| AMD Ryzen 3             | 5        | 1.97%   |
| Intel Pentium 4         | 4        | 1.57%   |
| AMD Phenom II X4        | 4        | 1.57%   |
| Intel Pentium Dual-Core | 3        | 1.18%   |
| Intel Core i9           | 3        | 1.18%   |
| Intel Core 2 Quad       | 3        | 1.18%   |
| Intel Atom              | 3        | 1.18%   |
| AMD A10                 | 3        | 1.18%   |
| Intel Pentium Gold      | 2        | 0.79%   |
| Intel Core 2            | 2        | 0.79%   |
| AMD Athlon X4           | 2        | 0.79%   |
| AMD A8                  | 2        | 0.79%   |
| Other                   | 1        | 0.39%   |
| CentaurHauls VIA Eden   | 1        | 0.39%   |
| AMD Sempron             | 1        | 0.39%   |
| AMD PRO A8              | 1        | 0.39%   |
| AMD Phenom II X3        | 1        | 0.39%   |
| AMD GX                  | 1        | 0.39%   |
| AMD E1                  | 1        | 0.39%   |
| AMD Athlon XP           | 1        | 0.39%   |
| AMD Athlon II X2        | 1        | 0.39%   |
| AMD Athlon II Neo       | 1        | 0.39%   |
| AMD Athlon Dual Core    | 1        | 0.39%   |
| AMD A6                  | 1        | 0.39%   |
| AMD A4                  | 1        | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 84       | 33.07%  |
| 2      | 60       | 23.62%  |
| 8      | 48       | 18.9%   |
| 6      | 34       | 13.39%  |
| 1      | 10       | 3.94%   |
| 16     | 6        | 2.36%   |
| 12     | 6        | 2.36%   |
| 44     | 1        | 0.39%   |
| 32     | 1        | 0.39%   |
| 28     | 1        | 0.39%   |
| 24     | 1        | 0.39%   |
| 14     | 1        | 0.39%   |
| 3      | 1        | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 251      | 98.82%  |
| 2      | 3        | 1.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 153      | 60.24%  |
| 1      | 101      | 39.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 249      | 98.03%  |
| 32-bit         | 5        | 1.97%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 39       | 15.29%  |
| 0xa0655    | 22       | 8.63%   |
| 0x306c3    | 20       | 7.84%   |
| 0x08701021 | 17       | 6.67%   |
| 0x306a9    | 13       | 5.1%    |
| 0x506e3    | 9        | 3.53%   |
| 0x206a7    | 9        | 3.53%   |
| 0x1067a    | 9        | 3.53%   |
| 0x906e9    | 8        | 3.14%   |
| 0x0800820d | 6        | 2.35%   |
| 0x06003106 | 6        | 2.35%   |
| 0x906ea    | 5        | 1.96%   |
| 0x0a201009 | 5        | 1.96%   |
| 0x206d7    | 4        | 1.57%   |
| 0x0a201016 | 4        | 1.57%   |
| 0x06000852 | 4        | 1.57%   |
| 0xf29      | 3        | 1.18%   |
| 0x906ed    | 3        | 1.18%   |
| 0x306f2    | 3        | 1.18%   |
| 0x08108109 | 3        | 1.18%   |
| 0x08001138 | 3        | 1.18%   |
| 0x010000c8 | 3        | 1.18%   |
| 0x010000b6 | 3        | 1.18%   |
| 0xa0653    | 2        | 0.78%   |
| 0x6fd      | 2        | 0.78%   |
| 0x6fb      | 2        | 0.78%   |
| 0x50654    | 2        | 0.78%   |
| 0x30673    | 2        | 0.78%   |
| 0x20655    | 2        | 0.78%   |
| 0x08701013 | 2        | 0.78%   |
| 0x08001137 | 2        | 0.78%   |
| 0x0700010f | 2        | 0.78%   |
| 0x06001119 | 2        | 0.78%   |
| 0x0600063e | 2        | 0.78%   |
| 0xf49      | 1        | 0.39%   |
| 0xf41      | 1        | 0.39%   |
| 0xa0671    | 1        | 0.39%   |
| 0xa0660    | 1        | 0.39%   |
| 0x906ec    | 1        | 0.39%   |
| 0x906eb    | 1        | 0.39%   |
| 0x806e9    | 1        | 0.39%   |
| 0x706a1    | 1        | 0.39%   |
| 0x6f6      | 1        | 0.39%   |
| 0x6f2      | 1        | 0.39%   |
| 0x506c9    | 1        | 0.39%   |
| 0x406f1    | 1        | 0.39%   |
| 0x406e3    | 1        | 0.39%   |
| 0x406d8    | 1        | 0.39%   |
| 0x406c4    | 1        | 0.39%   |
| 0x406c3    | 1        | 0.39%   |
| 0x40651    | 1        | 0.39%   |
| 0x306e4    | 1        | 0.39%   |
| 0x30678    | 1        | 0.39%   |
| 0x106e5    | 1        | 0.39%   |
| 0x106a5    | 1        | 0.39%   |
| 0x106a4    | 1        | 0.39%   |
| 0x10676    | 1        | 0.39%   |
| 0x0830104d | 1        | 0.39%   |
| 0x08301039 | 1        | 0.39%   |
| 0x08101016 | 1        | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 28       | 11.02%  |
| Zen 2         | 27       | 10.63%  |
| CometLake     | 25       | 9.84%   |
| KabyLake      | 23       | 9.06%   |
| IvyBridge     | 17       | 6.69%   |
| Zen+          | 15       | 5.91%   |
| Skylake       | 14       | 5.51%   |
| SandyBridge   | 14       | 5.51%   |
| Penryn        | 12       | 4.72%   |
| Zen 3         | 10       | 3.94%   |
| Zen           | 8        | 3.15%   |
| Piledriver    | 8        | 3.15%   |
| K10           | 8        | 3.15%   |
| Steamroller   | 7        | 2.76%   |
| Silvermont    | 7        | 2.76%   |
| Core          | 7        | 2.76%   |
| NetBurst      | 5        | 1.97%   |
| Westmere      | 3        | 1.18%   |
| Nehalem       | 3        | 1.18%   |
| Bulldozer     | 3        | 1.18%   |
| Jaguar        | 2        | 0.79%   |
| Unknown       | 2        | 0.79%   |
| K8 Hammer     | 1        | 0.39%   |
| K6            | 1        | 0.39%   |
| Goldmont plus | 1        | 0.39%   |
| Goldmont      | 1        | 0.39%   |
| Excavator     | 1        | 0.39%   |
| Broadwell     | 1        | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 117      | 43.82%  |
| Intel                      | 73       | 27.34%  |
| AMD                        | 68       | 25.47%  |
| ASPEED Technology          | 6        | 2.25%   |
| VIA Technologies           | 2        | 0.75%   |
| Matrox Electronics Systems | 1        | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 20       | 7.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 17       | 6.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 4.07%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8        | 2.96%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 8        | 2.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8        | 2.96%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 8        | 2.96%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 7        | 2.59%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 6        | 2.22%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5        | 1.85%   |
| Intel HD Graphics 530                                                                    | 5        | 1.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 1.85%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5        | 1.85%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4        | 1.48%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 4        | 1.48%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 4        | 1.48%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 4        | 1.48%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4        | 1.48%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 1.48%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4        | 1.48%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 1.11%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 3        | 1.11%   |
| Intel HD Graphics 630                                                                    | 3        | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 1.11%   |
| Intel 82865G Integrated Graphics Controller                                              | 3        | 1.11%   |
| AMD Picasso                                                                              | 3        | 1.11%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 1.11%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 0.74%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2        | 0.74%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 0.74%   |
| Nvidia GK104 [GeForce GTX 670]                                                           | 2        | 0.74%   |
| Nvidia GF119 [NVS 310]                                                                   | 2        | 0.74%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                    | 2        | 0.74%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 2        | 0.74%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2        | 0.74%   |
| Nvidia G98 [Quadro NVS 295]                                                              | 2        | 0.74%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 2        | 0.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 0.74%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.74%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 0.74%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 0.74%   |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 0.74%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2        | 0.74%   |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                            | 1        | 0.37%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro]            | 1        | 0.37%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.37%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.37%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 0.37%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1        | 0.37%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.37%   |
| Nvidia NV44 [GeForce 6200 LE]                                                            | 1        | 0.37%   |
| Nvidia GV100GL [Quadro GV100]                                                            | 1        | 0.37%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.37%   |
| Nvidia GP107GL [Quadro P400]                                                             | 1        | 0.37%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1        | 0.37%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.37%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.37%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1        | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 109      | 42.91%  |
| 1 x AMD            | 65       | 25.59%  |
| 1 x Intel          | 62       | 24.41%  |
| Intel + Nvidia     | 5        | 1.97%   |
| 1 x ASPEED         | 5        | 1.97%   |
| 1 x VIA            | 2        | 0.79%   |
| Intel + 2 x Nvidia | 2        | 0.79%   |
| 2 x AMD            | 1        | 0.39%   |
| 1 x Matrox         | 1        | 0.39%   |
| AMD + Nvidia       | 1        | 0.39%   |
| AMD + ASPEED       | 1        | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 156      | 61.42%  |
| Proprietary | 57       | 22.44%  |
| Unknown     | 41       | 16.14%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 131      | 51.17%  |
| 7.01-8.0   | 27       | 10.55%  |
| 1.01-2.0   | 25       | 9.77%   |
| 3.01-4.0   | 21       | 8.2%    |
| 0.51-1.0   | 20       | 7.81%   |
| 0.01-0.5   | 16       | 6.25%   |
| 5.01-6.0   | 8        | 3.13%   |
| 8.01-16.0  | 3        | 1.17%   |
| 2.01-3.0   | 2        | 0.78%   |
| 16.01-24.0 | 2        | 0.78%   |
| 24.01-32.0 | 1        | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Dell                    | 32       | 13.28%  |
| Samsung Electronics     | 31       | 12.86%  |
| Goldstar                | 27       | 11.2%   |
| Acer                    | 20       | 8.3%    |
| Ancor Communications    | 18       | 7.47%   |
| BenQ                    | 17       | 7.05%   |
| Hewlett-Packard         | 15       | 6.22%   |
| Philips                 | 12       | 4.98%   |
| AOC                     | 10       | 4.15%   |
| ViewSonic               | 5        | 2.07%   |
| Eizo                    | 5        | 2.07%   |
| ASUSTek Computer        | 5        | 2.07%   |
| Unknown                 | 4        | 1.66%   |
| Sony                    | 4        | 1.66%   |
| NEC Computers           | 3        | 1.24%   |
| Lenovo                  | 3        | 1.24%   |
| Iiyama                  | 3        | 1.24%   |
| Vizio                   | 2        | 0.83%   |
| MSI                     | 2        | 0.83%   |
| LG Electronics          | 2        | 0.83%   |
| WTC                     | 1        | 0.41%   |
| VMO                     | 1        | 0.41%   |
| Vestel Elektronik       | 1        | 0.41%   |
| SGT                     | 1        | 0.41%   |
| Prestigio               | 1        | 0.41%   |
| ODH                     | 1        | 0.41%   |
| Mitsubishi              | 1        | 0.41%   |
| MIT                     | 1        | 0.41%   |
| Mi                      | 1        | 0.41%   |
| Medion                  | 1        | 0.41%   |
| JVC                     | 1        | 0.41%   |
| INFOTRONIC              | 1        | 0.41%   |
| Idek Iiyama             | 1        | 0.41%   |
| Hyundai ImageQuest      | 1        | 0.41%   |
| HKC                     | 1        | 0.41%   |
| Hitachi                 | 1        | 0.41%   |
| HannStar Display        | 1        | 0.41%   |
| Fujitsu Siemens         | 1        | 0.41%   |
| COBY                    | 1        | 0.41%   |
| Chi Mei Optoelectronics | 1        | 0.41%   |
| Belinea                 | 1        | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 3        | 1.18%   |
| Philips 220WS PHL0851 1680x1050 474x296mm 22.0-inch                    | 3        | 1.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 3        | 1.18%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 3        | 1.18%   |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3        | 1.18%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 3        | 1.18%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 2        | 0.78%   |
| Sony TV *00 SNY8004 3840x2160 1085x610mm 49.0-inch                     | 2        | 0.78%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch   | 2        | 0.78%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch     | 2        | 0.78%   |
| Lenovo L2251x Wide LEN0A12 1680x1050 474x296mm 22.0-inch               | 2        | 0.78%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2        | 0.78%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 0.78%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 2        | 0.78%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2        | 0.78%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2        | 0.78%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                      | 2        | 0.78%   |
| Acer K272HUL ACR0524 2560x1440 598x336mm 27.0-inch                     | 2        | 0.78%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2        | 0.78%   |
| WTC FW1420S WTC1400 1024x768 304x228mm 15.0-inch                       | 1        | 0.39%   |
| VMO WQX DP VMO1507 2560x1600 1600x1000mm 74.3-inch                     | 1        | 0.39%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                     | 1        | 0.39%   |
| Vizio D32f-F1 VIZ1027 1920x1080 698x392mm 31.5-inch                    | 1        | 0.39%   |
| ViewSonic VG2860 SERIES VSC1F30 3840x2160 621x341mm 27.9-inch          | 1        | 0.39%   |
| ViewSonic VA926 Series VSC7D20 1280x1024 376x301mm 19.0-inch           | 1        | 0.39%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch              | 1        | 0.39%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.39%   |
| Unknown LCD Monitor TCT DP1080P60 1920x1080                            | 1        | 0.39%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.39%   |
| Sony TV *00 SNY3F05 3840x2160 952x535mm 43.0-inch                      | 1        | 0.39%   |
| SGT LCD Monitor SGT1900 1440x900 400x270mm 19.0-inch                   | 1        | 0.39%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch      | 1        | 0.39%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.39%   |
| Samsung Electronics U24E850 SAM0CCF 3840x2160 521x293mm 23.5-inch      | 1        | 0.39%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch      | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch    | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 304x228mm 15.0-inch    | 1        | 0.39%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch   | 1        | 0.39%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1        | 0.39%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 598x336mm 27.0-inch      | 1        | 0.39%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch      | 1        | 0.39%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1        | 0.39%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 0.39%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch      | 1        | 0.39%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch       | 1        | 0.39%   |
| Samsung Electronics Monitor SAM1057 1280x1024 306x230mm 15.1-inch      | 1        | 0.39%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 0.39%   |
| Samsung Electronics LF27T850 SAM704F 2560x1440 597x336mm 27.0-inch     | 1        | 0.39%   |
| Samsung Electronics LCD Monitor SyncMaster 5760x1080                   | 1        | 0.39%   |
| Samsung Electronics LCD Monitor SMB2430L                               | 1        | 0.39%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch   | 1        | 0.39%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch  | 1        | 0.39%   |
| Samsung Electronics LCD Monitor SAM0BC9 1920x1080 600x340mm 27.2-inch  | 1        | 0.39%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 0.39%   |
| Samsung Electronics LCD Monitor C24F390 3360x1080                      | 1        | 0.39%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch     | 1        | 0.39%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1        | 0.39%   |
| Samsung Electronics C24FG70 SAM0D58 1920x1080 532x304mm 24.1-inch      | 1        | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 96       | 40.17%  |
| 2560x1440 (QHD)    | 23       | 9.62%   |
| 3840x2160 (4K)     | 21       | 8.79%   |
| 1280x1024 (SXGA)   | 19       | 7.95%   |
| 1680x1050 (WSXGA+) | 17       | 7.11%   |
| 1920x1200 (WUXGA)  | 9        | 3.77%   |
| 1366x768 (WXGA)    | 7        | 2.93%   |
| Unknown            | 7        | 2.93%   |
| 2560x1080          | 5        | 2.09%   |
| 1600x900 (HD+)     | 5        | 2.09%   |
| 1440x900 (WXGA+)   | 5        | 2.09%   |
| 1024x768 (XGA)     | 5        | 2.09%   |
| 3840x1080          | 3        | 1.26%   |
| 2560x1600          | 3        | 1.26%   |
| 2288x1287          | 3        | 1.26%   |
| 1600x1200          | 3        | 1.26%   |
| 3440x1440          | 2        | 0.84%   |
| 7680x4320          | 1        | 0.42%   |
| 5760x1080          | 1        | 0.42%   |
| 4480x1440          | 1        | 0.42%   |
| 3360x1080          | 1        | 0.42%   |
| 1920x540           | 1        | 0.42%   |
| 1024x600           | 1        | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 39       | 16.53%  |
| 27      | 37       | 15.68%  |
| 23      | 34       | 14.41%  |
| 21      | 17       | 7.2%    |
| Unknown | 17       | 7.2%    |
| 22      | 12       | 5.08%   |
| 17      | 11       | 4.66%   |
| 19      | 10       | 4.24%   |
| 31      | 9        | 3.81%   |
| 15      | 8        | 3.39%   |
| 20      | 7        | 2.97%   |
| 18      | 7        | 2.97%   |
| 34      | 5        | 2.12%   |
| 142     | 3        | 1.27%   |
| 28      | 3        | 1.27%   |
| 84      | 2        | 0.85%   |
| 65      | 2        | 0.85%   |
| 29      | 2        | 0.85%   |
| 74      | 1        | 0.42%   |
| 72      | 1        | 0.42%   |
| 55      | 1        | 0.42%   |
| 49      | 1        | 0.42%   |
| 48      | 1        | 0.42%   |
| 38      | 1        | 0.42%   |
| 32      | 1        | 0.42%   |
| 26      | 1        | 0.42%   |
| 25      | 1        | 0.42%   |
| 16      | 1        | 0.42%   |
| 10      | 1        | 0.42%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 101      | 43.72%  |
| 401-500        | 48       | 20.78%  |
| 301-350        | 20       | 8.66%   |
| 601-700        | 18       | 7.79%   |
| Unknown        | 17       | 7.36%   |
| 351-400        | 7        | 3.03%   |
| 701-800        | 6        | 2.6%    |
| 1001-1500      | 5        | 2.16%   |
| 1501-2000      | 4        | 1.73%   |
| More than 2000 | 3        | 1.3%    |
| 801-900        | 1        | 0.43%   |
| 201-300        | 1        | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 135      | 59.47%  |
| 16/10   | 33       | 14.54%  |
| 5/4     | 16       | 7.05%   |
| Unknown | 16       | 7.05%   |
| 4/3     | 11       | 4.85%   |
| 21/9    | 7        | 3.08%   |
| 1.00    | 4        | 1.76%   |
| 3/2     | 3        | 1.32%   |
| 6/5     | 1        | 0.44%   |
| 1.96    | 1        | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 80       | 34.63%  |
| 301-350        | 37       | 16.02%  |
| 151-200        | 23       | 9.96%   |
| 351-500        | 19       | 8.23%   |
| 251-300        | 17       | 7.36%   |
| Unknown        | 17       | 7.36%   |
| 141-150        | 15       | 6.49%   |
| More than 1000 | 10       | 4.33%   |
| 101-110        | 7        | 3.03%   |
| 131-140        | 2        | 0.87%   |
| 501-1000       | 2        | 0.87%   |
| 41-50          | 1        | 0.43%   |
| 111-120        | 1        | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 142      | 63.39%  |
| 101-120 | 38       | 16.96%  |
| Unknown | 17       | 7.59%   |
| 121-160 | 11       | 4.91%   |
| 1-50    | 8        | 3.57%   |
| 161-240 | 8        | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 162      | 63.78%  |
| 0     | 46       | 18.11%  |
| 2     | 40       | 15.75%  |
| 3     | 5        | 1.97%   |
| 4     | 1        | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 141      | 43.79%  |
| Intel                           | 116      | 36.02%  |
| Qualcomm Atheros                | 23       | 7.14%   |
| Broadcom                        | 10       | 3.11%   |
| Ralink Technology               | 6        | 1.86%   |
| Ralink                          | 3        | 0.93%   |
| Microsoft                       | 3        | 0.93%   |
| VIA Technologies                | 2        | 0.62%   |
| TP-Link                         | 2        | 0.62%   |
| Nvidia                          | 2        | 0.62%   |
| Mellanox Technologies           | 2        | 0.62%   |
| Broadcom Limited                | 2        | 0.62%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.31%   |
| Xiaomi                          | 1        | 0.31%   |
| Qualcomm Atheros Communications | 1        | 0.31%   |
| NetGear                         | 1        | 0.31%   |
| Marvell Technology Group        | 1        | 0.31%   |
| Edimax Technology               | 1        | 0.31%   |
| D-Link                          | 1        | 0.31%   |
| ASIX Electronics                | 1        | 0.31%   |
| Aquantia                        | 1        | 0.31%   |
| American Megatrends             | 1        | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 116      | 32.31%  |
| Intel I211 Gigabit Network Connection                             | 21       | 5.85%   |
| Intel Wi-Fi 6 AX200                                               | 15       | 4.18%   |
| Intel Ethernet Connection (2) I219-V                              | 14       | 3.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12       | 3.34%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11       | 3.06%   |
| Intel I210 Gigabit Network Connection                             | 10       | 2.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6        | 1.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 1.39%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.39%   |
| Intel Wireless 7260                                               | 4        | 1.11%   |
| Intel Ethernet Connection I217-V                                  | 4        | 1.11%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.11%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.11%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.84%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.84%   |
| Intel Ethernet Controller I225-V                                  | 3        | 0.84%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 0.84%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 0.56%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2        | 0.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.56%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.56%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.56%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2        | 0.56%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2        | 0.56%   |
| Intel Wireless 8260                                               | 2        | 0.56%   |
| Intel Wireless 3165                                               | 2        | 0.56%   |
| Intel Ethernet Controller 10G X550T                               | 2        | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.56%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 0.56%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1        | 0.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.28%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1        | 0.28%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.28%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1        | 0.28%   |
| TP-Link Archer T4U ver.3                                          | 1        | 0.28%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.28%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.28%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.28%   |
| Realtek 802.11ac NIC                                              | 1        | 0.28%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.28%   |
| Ralink RT5372 Wireless Adapter                                    | 1        | 0.28%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.28%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1        | 0.28%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 1        | 0.28%   |
| Ralink RT2800 802.11n PCI                                         | 1        | 0.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 33       | 45.21%  |
| Realtek Semiconductor           | 10       | 13.7%   |
| Qualcomm Atheros                | 8        | 10.96%  |
| Ralink Technology               | 6        | 8.22%   |
| Broadcom                        | 4        | 5.48%   |
| Ralink                          | 3        | 4.11%   |
| Microsoft                       | 3        | 4.11%   |
| TP-Link                         | 2        | 2.74%   |
| Qualcomm Atheros Communications | 1        | 1.37%   |
| NetGear                         | 1        | 1.37%   |
| Edimax Technology               | 1        | 1.37%   |
| D-Link                          | 1        | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 15       | 20.55%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6        | 8.22%   |
| Intel Wireless 7260                                                     | 4        | 5.48%   |
| Ralink MT7601U Wireless Adapter                                         | 3        | 4.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2        | 2.74%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2        | 2.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2        | 2.74%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2        | 2.74%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 2        | 2.74%   |
| Intel Wireless 8260                                                     | 2        | 2.74%   |
| Intel Wireless 3165                                                     | 2        | 2.74%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2        | 2.74%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 1        | 1.37%   |
| TP-Link Archer T4U ver.3                                                | 1        | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.37%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.37%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1        | 1.37%   |
| Realtek 802.11ac NIC                                                    | 1        | 1.37%   |
| Ralink RT5572 Wireless Adapter                                          | 1        | 1.37%   |
| Ralink RT5372 Wireless Adapter                                          | 1        | 1.37%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 1.37%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1        | 1.37%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 1        | 1.37%   |
| Ralink RT2800 802.11n PCI                                               | 1        | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 1.37%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 1.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1        | 1.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 1.37%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1        | 1.37%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1        | 1.37%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                 | 1        | 1.37%   |
| Microsoft Wireless XBox Controller Dongle                               | 1        | 1.37%   |
| Intel Wireless-AC 9260                                                  | 1        | 1.37%   |
| Intel Wireless 8265 / 8275                                              | 1        | 1.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 1.37%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1        | 1.37%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS] | 1        | 1.37%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1        | 1.37%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1        | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 136      | 50%     |
| Intel                      | 100      | 36.76%  |
| Qualcomm Atheros           | 16       | 5.88%   |
| Broadcom                   | 6        | 2.21%   |
| VIA Technologies           | 2        | 0.74%   |
| Nvidia                     | 2        | 0.74%   |
| Mellanox Technologies      | 2        | 0.74%   |
| Broadcom Limited           | 2        | 0.74%   |
| ZTE WCDMA Technologies MSM | 1        | 0.37%   |
| Xiaomi                     | 1        | 0.37%   |
| Marvell Technology Group   | 1        | 0.37%   |
| ASIX Electronics           | 1        | 0.37%   |
| Aquantia                   | 1        | 0.37%   |
| American Megatrends        | 1        | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 116      | 40.56%  |
| Intel I211 Gigabit Network Connection                             | 21       | 7.34%   |
| Intel Ethernet Connection (2) I219-V                              | 14       | 4.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12       | 4.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 11       | 3.85%   |
| Intel I210 Gigabit Network Connection                             | 10       | 3.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 1.75%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.75%   |
| Intel Ethernet Connection I217-V                                  | 4        | 1.4%    |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.4%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 1.05%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 1.05%   |
| Intel Ethernet Controller I225-V                                  | 3        | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.05%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.05%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.7%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.7%    |
| Nvidia MCP61 Ethernet                                             | 2        | 0.7%    |
| Mellanox MT27500 Family [ConnectX-3]                              | 2        | 0.7%    |
| Intel Ethernet Controller 10G X550T                               | 2        | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.7%    |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.7%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.7%    |
| ZTE WCDMA MSM ZTE MSM                                             | 1        | 0.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.35%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1        | 0.35%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.35%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.35%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.35%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.35%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.35%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.35%   |
| Intel Ethernet Virtual Function 700 Series                        | 1        | 0.35%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 0.35%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.35%   |
| Intel Ethernet Connection I354                                    | 1        | 0.35%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 0.35%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.35%   |
| Intel Ethernet Connection (6) I219-V                              | 1        | 0.35%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.35%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.35%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.35%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.35%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.35%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.35%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 0.35%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 0.35%   |
| Intel 82567LF Gigabit Network Connection                          | 1        | 0.35%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.35%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 252      | 77.54%  |
| WiFi     | 73       | 22.46%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 232      | 82.86%  |
| WiFi     | 48       | 17.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 169      | 66.54%  |
| 2     | 68       | 26.77%  |
| 3     | 11       | 4.33%   |
| 4     | 2        | 0.79%   |
| 13    | 1        | 0.39%   |
| 6     | 1        | 0.39%   |
| 5     | 1        | 0.39%   |
| 0     | 1        | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 210      | 82.68%  |
| Yes  | 44       | 17.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 31       | 47.69%  |
| Cambridge Silicon Radio         | 15       | 23.08%  |
| Broadcom                        | 7        | 10.77%  |
| ASUSTek Computer                | 5        | 7.69%   |
| Realtek Semiconductor           | 2        | 3.08%   |
| Qualcomm Atheros Communications | 2        | 3.08%   |
| Sitecom Europe                  | 1        | 1.54%   |
| IMC Networks                    | 1        | 1.54%   |
| Belkin Components               | 1        | 1.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                     | 15       | 23.08%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 15       | 23.08%  |
| Intel Bluetooth wireless interface                        | 7        | 10.77%  |
| Intel Wireless-AC 3168 Bluetooth                          | 5        | 7.69%   |
| Intel Bluetooth Device                                    | 3        | 4.62%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 3        | 4.62%   |
| Realtek Bluetooth Radio                                   | 2        | 3.08%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 2        | 3.08%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521 | 1        | 1.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 1        | 1.54%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                     | 1        | 1.54%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 1        | 1.54%   |
| IMC Networks Bluetooth Radio                              | 1        | 1.54%   |
| Broadcom Bluetooth 3.0 Device                             | 1        | 1.54%   |
| Broadcom BCM43142A0 Bluetooth 4.0                         | 1        | 1.54%   |
| Broadcom BCM2045 Bluetooth                                | 1        | 1.54%   |
| Broadcom BCM2035 Bluetooth dongle                         | 1        | 1.54%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter     | 1        | 1.54%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE     | 1        | 1.54%   |
| ASUS Bluetooth Radio                                      | 1        | 1.54%   |
| ASUS Bluetooth Device                                     | 1        | 1.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 146      | 34.76%  |
| Nvidia                     | 109      | 25.95%  |
| AMD                        | 98       | 23.33%  |
| C-Media Electronics        | 11       | 2.62%   |
| Logitech                   | 5        | 1.19%   |
| Creative Labs              | 5        | 1.19%   |
| VIA Technologies           | 4        | 0.95%   |
| GYROCOM C&C                | 4        | 0.95%   |
| Generalplus Technology     | 3        | 0.71%   |
| XMOS                       | 2        | 0.48%   |
| Samson Technologies        | 2        | 0.48%   |
| RODE Microphones           | 2        | 0.48%   |
| GN Netcom                  | 2        | 0.48%   |
| Cambridge Silicon Radio    | 2        | 0.48%   |
| BEHRINGER International    | 2        | 0.48%   |
| ASUSTek Computer           | 2        | 0.48%   |
| Yamaha                     | 1        | 0.24%   |
| Unknown                    | 1        | 0.24%   |
| Texas Instruments          | 1        | 0.24%   |
| TerraTec Electronic        | 1        | 0.24%   |
| TEAC                       | 1        | 0.24%   |
| SteelSeries ApS            | 1        | 0.24%   |
| ROCCAT                     | 1        | 0.24%   |
| PreSonus Audio Electronics | 1        | 0.24%   |
| Micronas                   | 1        | 0.24%   |
| M-Audio                    | 1        | 0.24%   |
| Kingston Technology        | 1        | 0.24%   |
| JMTek                      | 1        | 0.24%   |
| Hangzhou Worlde            | 1        | 0.24%   |
| Focusrite-Novation         | 1        | 0.24%   |
| Dell                       | 1        | 0.24%   |
| Creative Technology        | 1        | 0.24%   |
| Blue Microphones           | 1        | 0.24%   |
| AXELVOX                    | 1        | 0.24%   |
| AVID Technology            | 1        | 0.24%   |
| Audioengine                | 1        | 0.24%   |
| Alesis                     | 1        | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 35       | 7.31%   |
| Intel Comet Lake PCH cAVS                                                  | 23       | 4.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 21       | 4.38%   |
| Intel 200 Series PCH HD Audio                                              | 17       | 3.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 17       | 3.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16       | 3.34%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15       | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14       | 2.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13       | 2.71%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12       | 2.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12       | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 2.51%   |
| AMD FCH Azalia Controller                                                  | 12       | 2.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11       | 2.3%    |
| AMD Navi 10 HDMI Audio                                                     | 10       | 2.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 9        | 1.88%   |
| Nvidia GP104 High Definition Audio Controller                              | 7        | 1.46%   |
| Nvidia GF108 High Definition Audio Controller                              | 7        | 1.46%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6        | 1.25%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 1.25%   |
| Nvidia GP108 High Definition Audio Controller                              | 5        | 1.04%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 1.04%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 1.04%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 5        | 1.04%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 5        | 1.04%   |
| Nvidia High Definition Audio Controller                                    | 4        | 0.84%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 0.84%   |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 0.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 0.84%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 4        | 0.84%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 0.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 0.63%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3        | 0.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 0.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 0.63%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3        | 0.63%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                       | 3        | 0.63%   |
| GYROCOM C&C Fiio E10                                                       | 3        | 0.63%   |
| Generalplus Technology USB Audio Device                                    | 3        | 0.63%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 0.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 0.63%   |
| AMD Kabini HDMI/DP Audio                                                   | 3        | 0.63%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 2        | 0.42%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.42%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.42%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.42%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.42%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.42%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.42%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.42%   |
| Nvidia GF116 High Definition Audio Controller                              | 2        | 0.42%   |
| Nvidia GF104 High Definition Audio Controller                              | 2        | 0.42%   |
| Logitech G430 Surround Sound Gaming Headset                                | 2        | 0.42%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2        | 0.42%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                         | 2        | 0.42%   |
| Cambridge Silicon Radio CSR8645                                            | 2        | 0.42%   |
| C-Media Electronics USB Audio Device                                       | 2        | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Kingston                | 50       | 18.87%  |
| Corsair                 | 37       | 13.96%  |
| Unknown                 | 34       | 12.83%  |
| SK Hynix                | 23       | 8.68%   |
| Samsung Electronics     | 23       | 8.68%   |
| Crucial                 | 21       | 7.92%   |
| G.Skill                 | 20       | 7.55%   |
| Hikvision               | 19       | 7.17%   |
| Micron Technology       | 7        | 2.64%   |
| Patriot                 | 6        | 2.26%   |
| A-DATA Technology       | 3        | 1.13%   |
| Team                    | 2        | 0.75%   |
| Kllisre                 | 2        | 0.75%   |
| Elpida                  | 2        | 0.75%   |
| AMD                     | 2        | 0.75%   |
| V-Color                 | 1        | 0.38%   |
| Unknown (ABCD)          | 1        | 0.38%   |
| Unknown (000000000FE02) | 1        | 0.38%   |
| Unknown (0000000002C80) | 1        | 0.38%   |
| Smart                   | 1        | 0.38%   |
| Ramaxel Technology      | 1        | 0.38%   |
| OCZ                     | 1        | 0.38%   |
| Nanya Technology        | 1        | 0.38%   |
| Kingmax                 | 1        | 0.38%   |
| KETECH                  | 1        | 0.38%   |
| Infineon                | 1        | 0.38%   |
| GOODRAM                 | 1        | 0.38%   |
| GeIL                    | 1        | 0.38%   |
| Apacer                  | 1        | 0.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Hikvision RAM HKED4161DAA1D0MA1 16384MB DIMM DDR4 2667MT/s       | 19       | 6.44%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 5        | 1.69%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s            | 5        | 1.69%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s           | 4        | 1.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 3        | 1.02%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                | 3        | 1.02%   |
| Kingston RAM KHX2133C14D4/8G 8192MB DIMM DDR4 2667MT/s           | 3        | 1.02%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 3        | 1.02%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s         | 3        | 1.02%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3        | 1.02%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 2        | 0.68%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 2        | 0.68%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2        | 0.68%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 2        | 0.68%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                         | 2        | 0.68%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                       | 2        | 0.68%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                      | 2        | 0.68%   |
| Unknown RAM 99[2/7/4]164(F/R) 4GB DIMM DDR3 1600MT/s             | 2        | 0.68%   |
| SK Hynix RAM HMAA2GU6AJR8N-XN 16GB DIMM DDR4 3200MT/s            | 2        | 0.68%   |
| Samsung RAM M378B5273CH0-CK0 4096MB DIMM DDR3 2000MT/s           | 2        | 0.68%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s              | 2        | 0.68%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s               | 2        | 0.68%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                | 2        | 0.68%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s              | 2        | 0.68%   |
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1866MT/s           | 2        | 0.68%   |
| Kingston RAM 99U5584-010.A00LF 4096MB DIMM DDR3 1600MT/s         | 2        | 0.68%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s           | 2        | 0.68%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s           | 2        | 0.68%   |
| Crucial RAM CT51264BD160B.C16F 4096MB DIMM DDR3 1600MT/s         | 2        | 0.68%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s            | 2        | 0.68%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s           | 2        | 0.68%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s            | 2        | 0.68%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s            | 2        | 0.68%   |
| AMD RAM R748G2400U2S 8GB DIMM DDR4 2400MT/s                      | 2        | 0.68%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s                 | 1        | 0.34%   |
| Unknown RAM V02D4LF8GB5285282400 8192MB DIMM DDR4 2400MT/s       | 1        | 0.34%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1        | 0.34%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1        | 0.34%   |
| Unknown RAM Module 512MB DIMM SDRAM 400MT/s                      | 1        | 0.34%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                       | 1        | 0.34%   |
| Unknown RAM Module 4GB DIMM 800MT/s                              | 1        | 0.34%   |
| Unknown RAM Module 4GB DIMM 400MT/s                              | 1        | 0.34%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s                       | 1        | 0.34%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                        | 1        | 0.34%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1        | 0.34%   |
| Unknown RAM Module 2GB DIMM 400MT/s                              | 1        | 0.34%   |
| Unknown RAM Module 256MB DIMM SDRAM 400MT/s                      | 1        | 0.34%   |
| Unknown RAM Module 256MB DIMM                                    | 1        | 0.34%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                      | 1        | 0.34%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1        | 0.34%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1        | 0.34%   |
| Unknown RAM Module 1GB DIMM                                      | 1        | 0.34%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                       | 1        | 0.34%   |
| Unknown RAM 7EH64AA# 8GB DIMM DDR4 2667MT/s                      | 1        | 0.34%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s            | 1        | 0.34%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1        | 0.34%   |
| Unknown (000000000FE02) RAM EBJ10UE8BBF0-DJ-F 1GB DIMM 1066MT/s  | 1        | 0.34%   |
| Unknown (0000000002C80) RAM 16JTF25664AY-1G4D1 2GB DIMM 1066MT/s | 1        | 0.34%   |
| Team RAM TEAMGROUP-UD3-1333 8GB DIMM DDR3 1333MT/s               | 1        | 0.34%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                       | 1        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 119      | 50.42%  |
| DDR3    | 83       | 35.17%  |
| Unknown | 12       | 5.08%   |
| DDR2    | 10       | 4.24%   |
| SDRAM   | 9        | 3.81%   |
| DDR     | 2        | 0.85%   |
| LPDDR4  | 1        | 0.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 225      | 95.74%  |
| SODIMM | 9        | 3.83%   |
| RIMM   | 1        | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 93       | 36.05%  |
| 16384 | 57       | 22.09%  |
| 4096  | 49       | 18.99%  |
| 2048  | 28       | 10.85%  |
| 32768 | 12       | 4.65%   |
| 1024  | 12       | 4.65%   |
| 512   | 3        | 1.16%   |
| 256   | 3        | 1.16%   |
| 65536 | 1        | 0.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 57       | 21.51%  |
| 2667    | 35       | 13.21%  |
| 1333    | 31       | 11.7%   |
| 3200    | 24       | 9.06%   |
| 2400    | 17       | 6.42%   |
| 3600    | 14       | 5.28%   |
| 800     | 11       | 4.15%   |
| 2133    | 8        | 3.02%   |
| 2666    | 7        | 2.64%   |
| 2933    | 6        | 2.26%   |
| 1867    | 6        | 2.26%   |
| 1866    | 6        | 2.26%   |
| 3466    | 5        | 1.89%   |
| 3000    | 5        | 1.89%   |
| 667     | 4        | 1.51%   |
| Unknown | 4        | 1.51%   |
| 400     | 3        | 1.13%   |
| 3500    | 2        | 0.75%   |
| 3400    | 2        | 0.75%   |
| 3100    | 2        | 0.75%   |
| 2000    | 2        | 0.75%   |
| 1067    | 2        | 0.75%   |
| 3866    | 1        | 0.38%   |
| 3733    | 1        | 0.38%   |
| 3533    | 1        | 0.38%   |
| 3066    | 1        | 0.38%   |
| 2866    | 1        | 0.38%   |
| 2465    | 1        | 0.38%   |
| 2048    | 1        | 0.38%   |
| 1800    | 1        | 0.38%   |
| 1400    | 1        | 0.38%   |
| 1367    | 1        | 0.38%   |
| 1066    | 1        | 0.38%   |
| 333     | 1        | 0.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 70%     |
| Samsung Electronics | 1        | 10%     |
| Konica Minolta      | 1        | 10%     |
| Canon               | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP LaserJet 1200            | 2        | 20%     |
| Samsung ML-1660 Series      | 1        | 10%     |
| Konica Minolta bizhub 4402P | 1        | 10%     |
| HP LaserJet P1006           | 1        | 10%     |
| HP LaserJet M101-M106       | 1        | 10%     |
| HP LaserJet 1150            | 1        | 10%     |
| HP ENVY 5000 series         | 1        | 10%     |
| HP ENVY 4520 series         | 1        | 10%     |
| Canon iP2700 series         | 1        | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 50%     |
| Canon       | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 50%     |
| Canon CanoScan N670U/N676U/LiDE 20                       | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 15       | 31.91%  |
| Microdia                      | 8        | 17.02%  |
| Samsung Electronics           | 3        | 6.38%   |
| Generalplus Technology        | 3        | 6.38%   |
| Sunplus Innovation Technology | 2        | 4.26%   |
| Genesys Logic                 | 2        | 4.26%   |
| Z-Star Microelectronics       | 1        | 2.13%   |
| Xiongmai                      | 1        | 2.13%   |
| Unknown                       | 1        | 2.13%   |
| SiGma Micro                   | 1        | 2.13%   |
| Razer USA                     | 1        | 2.13%   |
| Microsoft                     | 1        | 2.13%   |
| Lenovo                        | 1        | 2.13%   |
| Huawei Technologies           | 1        | 2.13%   |
| Hewlett-Packard               | 1        | 2.13%   |
| eMPIA Technology              | 1        | 2.13%   |
| Creative Technology           | 1        | 2.13%   |
| AVerMedia Technologies        | 1        | 2.13%   |
| ARC International             | 1        | 2.13%   |
| Apple                         | 1        | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Microdia Webcam Vitade AF               | 4        | 8.51%   |
| Samsung Galaxy series, misc. (MTP mode) | 3        | 6.38%   |
| Logitech Webcam C270                    | 3        | 6.38%   |
| Logitech HD Pro Webcam C920             | 3        | 6.38%   |
| Microdia HDP Webcam USB                 | 2        | 4.26%   |
| Logitech HD Webcam C910                 | 2        | 4.26%   |
| Logitech HD Webcam C615                 | 2        | 4.26%   |
| Generalplus GENERAL WEBCAM              | 2        | 4.26%   |
| Z-Star Venus USB2.0 Camera              | 1        | 2.13%   |
| Xiongmai web camera                     | 1        | 2.13%   |
| Unknown Konftel Cam20                   | 1        | 2.13%   |
| Sunplus HD USB Camaer 4K                | 1        | 2.13%   |
| Sunplus HD 720P webcam                  | 1        | 2.13%   |
| SiGma Micro WebCam SiGma Micro          | 1        | 2.13%   |
| Razer USA Razer Kiyo                    | 1        | 2.13%   |
| Microsoft LifeCam HD-3000               | 1        | 2.13%   |
| Microdia Integrated Camera              | 1        | 2.13%   |
| Microdia Camera                         | 1        | 2.13%   |
| Logitech Webcam C925e                   | 1        | 2.13%   |
| Logitech Webcam C260                    | 1        | 2.13%   |
| Logitech Webcam C170                    | 1        | 2.13%   |
| Logitech Quickcam 3000 For Business     | 1        | 2.13%   |
| Logitech BRIO Ultra HD Webcam           | 1        | 2.13%   |
| Lenovo FHD Webcam                       | 1        | 2.13%   |
| Huawei HiCamera                         | 1        | 2.13%   |
| HP Webcam 3110                          | 1        | 2.13%   |
| Genesys Logic USB2.0 Digital Camera     | 1        | 2.13%   |
| Genesys Logic Camera                    | 1        | 2.13%   |
| Generalplus 808 Camera                  | 1        | 2.13%   |
| eMPIA M035 Compact Web Cam              | 1        | 2.13%   |
| Creative Live! Cam Chat HD [VF0700]     | 1        | 2.13%   |
| AVerMedia Live Gamer Ultra-Video        | 1        | 2.13%   |
| ARC International Camera                | 1        | 2.13%   |
| Apple iPhone 5/5C/5S/6/SE               | 1        | 2.13%   |

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
| Yubico.com            | 1        | 50%     |
| Gemalto (was Gemplus) | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Yubico.com Yubikey 4 CCID                         | 1        | 50%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 197      | 77.56%  |
| 1     | 53       | 20.87%  |
| 2     | 3        | 1.18%   |
| 5     | 1        | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 45       | 78.95%  |
| Unassigned class         | 4        | 7.02%   |
| Net/wireless             | 2        | 3.51%   |
| Communication controller | 2        | 3.51%   |
| Sound                    | 1        | 1.75%   |
| Network                  | 1        | 1.75%   |
| Multimedia controller    | 1        | 1.75%   |
| Bluetooth                | 1        | 1.75%   |

