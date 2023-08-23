Red OS - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Red OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Red_OS/Desktop/README.md) and [notebooks](/Dist/Red_OS/Notebook/README.md).

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

Total: 440

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7d63566e0a](https://linux-hardware.org/?probe=7d63566e0a) | Aug 11, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | Desktop     | [fb99152b24](https://linux-hardware.org/?probe=fb99152b24) | Aug 10, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | Desktop     | [5aeb5ebcbf](https://linux-hardware.org/?probe=5aeb5ebcbf) | Aug 09, 2023 |
| Dell          | Precision M4700             | Notebook    | [95ac580b0d](https://linux-hardware.org/?probe=95ac580b0d) | Aug 08, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [4dc4fb1691](https://linux-hardware.org/?probe=4dc4fb1691) | Aug 08, 2023 |
| MSI           | Modern 14 C12M              | Notebook    | [aa352b05aa](https://linux-hardware.org/?probe=aa352b05aa) | Aug 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [8a2a5c6265](https://linux-hardware.org/?probe=8a2a5c6265) | Jul 30, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [b297b777be](https://linux-hardware.org/?probe=b297b777be) | Jul 25, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [ee71316b5e](https://linux-hardware.org/?probe=ee71316b5e) | Jul 17, 2023 |
| Gigabyte      | G5 ME                       | Notebook    | [eaefa9c2c6](https://linux-hardware.org/?probe=eaefa9c2c6) | Jul 17, 2023 |
| RDW           | MB-B450M V.1                | All in one  | [cc732c4e21](https://linux-hardware.org/?probe=cc732c4e21) | Jul 12, 2023 |
| Dell          | Precision M4700             | Notebook    | [7dc84c10b5](https://linux-hardware.org/?probe=7dc84c10b5) | Jul 11, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [3f5ae451c0](https://linux-hardware.org/?probe=3f5ae451c0) | Jul 09, 2023 |
| Timi          | Redmi G 2022                | Notebook    | [30e96afcdd](https://linux-hardware.org/?probe=30e96afcdd) | Jul 08, 2023 |
| Timi          | Redmi G 2022                | Notebook    | [cd2b7e13ce](https://linux-hardware.org/?probe=cd2b7e13ce) | Jul 04, 2023 |
| ICL           | Si1407                      | Notebook    | [c4c9d43042](https://linux-hardware.org/?probe=c4c9d43042) | Jul 04, 2023 |
| Biostar       | H610MH                      | Desktop     | [ba1951d1fa](https://linux-hardware.org/?probe=ba1951d1fa) | Jun 19, 2023 |
| Aquarius      | NS483                       | Notebook    | [dd5daf7f12](https://linux-hardware.org/?probe=dd5daf7f12) | Jun 18, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [a161ef52b4](https://linux-hardware.org/?probe=a161ef52b4) | Jun 18, 2023 |
| HP            | 895F                        | All in one  | [1f8ae4f41b](https://linux-hardware.org/?probe=1f8ae4f41b) | Jun 15, 2023 |
| HP            | 895F                        | All in one  | [998f1d4e21](https://linux-hardware.org/?probe=998f1d4e21) | Jun 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [2a3c6cf0ab](https://linux-hardware.org/?probe=2a3c6cf0ab) | Jun 14, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [337e4a106e](https://linux-hardware.org/?probe=337e4a106e) | Jun 13, 2023 |
| HP            | 895F                        | All in one  | [355d6e856c](https://linux-hardware.org/?probe=355d6e856c) | Jun 08, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [ac55415914](https://linux-hardware.org/?probe=ac55415914) | Jun 05, 2023 |
| Dell          | 0VNM11 A01                  | Desktop     | [df3c87a033](https://linux-hardware.org/?probe=df3c87a033) | Jun 02, 2023 |
| Dell          | 0VNM11 A01                  | Desktop     | [308b943182](https://linux-hardware.org/?probe=308b943182) | Jun 01, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [b92d2128ad](https://linux-hardware.org/?probe=b92d2128ad) | Jun 01, 2023 |
| Gigabyte      | B560M D3H                   | Desktop     | [8579e0281a](https://linux-hardware.org/?probe=8579e0281a) | May 30, 2023 |
| MSI           | MS-ACD31                    | All in one  | [d958890b05](https://linux-hardware.org/?probe=d958890b05) | May 30, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [4843789a62](https://linux-hardware.org/?probe=4843789a62) | May 30, 2023 |
| Intel         | NUC7JYB J67970-403          | Mini pc     | [8af314920e](https://linux-hardware.org/?probe=8af314920e) | May 29, 2023 |
| HP            | 83F0                        | Desktop     | [77cfad8631](https://linux-hardware.org/?probe=77cfad8631) | May 26, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a98cdfee26](https://linux-hardware.org/?probe=a98cdfee26) | May 25, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [1e1fb2110f](https://linux-hardware.org/?probe=1e1fb2110f) | May 24, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [59d36ef46d](https://linux-hardware.org/?probe=59d36ef46d) | May 22, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [3ad250d762](https://linux-hardware.org/?probe=3ad250d762) | May 22, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [c5f452ea28](https://linux-hardware.org/?probe=c5f452ea28) | May 18, 2023 |
| MTR           | DP1000T-B V2.0              | All in one  | [f607fe37d0](https://linux-hardware.org/?probe=f607fe37d0) | May 18, 2023 |
| MSI           | GL62 6QF                    | Notebook    | [6ae5c650f3](https://linux-hardware.org/?probe=6ae5c650f3) | May 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3de097b441](https://linux-hardware.org/?probe=3de097b441) | May 12, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [cf7aa805b4](https://linux-hardware.org/?probe=cf7aa805b4) | May 11, 2023 |
| Dell          | Vostro 5391                 | Notebook    | [f5342b41ec](https://linux-hardware.org/?probe=f5342b41ec) | May 06, 2023 |
| Graviton      | N14I-T                      | Notebook    | [e82c8f00d8](https://linux-hardware.org/?probe=e82c8f00d8) | May 05, 2023 |
| Aquarius      | AQH410T                     | Desktop     | [aeeb40c393](https://linux-hardware.org/?probe=aeeb40c393) | May 04, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [0c5d92ebf9](https://linux-hardware.org/?probe=0c5d92ebf9) | May 04, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [7f787e2e46](https://linux-hardware.org/?probe=7f787e2e46) | May 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [3522381ca7](https://linux-hardware.org/?probe=3522381ca7) | May 02, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [a61a9a88bc](https://linux-hardware.org/?probe=a61a9a88bc) | May 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [4ec0da1442](https://linux-hardware.org/?probe=4ec0da1442) | May 02, 2023 |
| MSI           | A520M PRO                   | Desktop     | [6d37fb0e46](https://linux-hardware.org/?probe=6d37fb0e46) | May 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8f8a912636](https://linux-hardware.org/?probe=8f8a912636) | May 01, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [41d545e4d7](https://linux-hardware.org/?probe=41d545e4d7) | Apr 28, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [387eecc18e](https://linux-hardware.org/?probe=387eecc18e) | Apr 27, 2023 |
| Acer          | Aspire C24-963              | All in one  | [7b4eeebdbc](https://linux-hardware.org/?probe=7b4eeebdbc) | Apr 27, 2023 |
| ASRock        | B365M-ITX/ac                | Desktop     | [e4c8218911](https://linux-hardware.org/?probe=e4c8218911) | Apr 27, 2023 |
| Lenovo        | 36F3 No DPK                 | All in one  | [40bd947612](https://linux-hardware.org/?probe=40bd947612) | Apr 24, 2023 |
| Lenovo        | 36F3 SDK0J40688 WIN 3424... | All in one  | [7a81eae6f1](https://linux-hardware.org/?probe=7a81eae6f1) | Apr 24, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [aca220e594](https://linux-hardware.org/?probe=aca220e594) | Apr 22, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [40aaf19667](https://linux-hardware.org/?probe=40aaf19667) | Apr 21, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [eec2055c19](https://linux-hardware.org/?probe=eec2055c19) | Apr 20, 2023 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [a9329736fb](https://linux-hardware.org/?probe=a9329736fb) | Apr 19, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [e2ed275252](https://linux-hardware.org/?probe=e2ed275252) | Apr 19, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [a6aaf5f17a](https://linux-hardware.org/?probe=a6aaf5f17a) | Apr 19, 2023 |
| HP            | 81BA 0010                   | All in one  | [b4e5d6fafb](https://linux-hardware.org/?probe=b4e5d6fafb) | Apr 12, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [d2623477d9](https://linux-hardware.org/?probe=d2623477d9) | Apr 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [c959a62e36](https://linux-hardware.org/?probe=c959a62e36) | Apr 10, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [2082d3c772](https://linux-hardware.org/?probe=2082d3c772) | Apr 08, 2023 |
| Intel         | D945GNT AAC96315-405        | Desktop     | [cdfdfbcda4](https://linux-hardware.org/?probe=cdfdfbcda4) | Apr 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [70ff15284b](https://linux-hardware.org/?probe=70ff15284b) | Apr 07, 2023 |
| 3Logic Gro... | TUNDRA                      | Server      | [51dc310024](https://linux-hardware.org/?probe=51dc310024) | Apr 07, 2023 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [49921908d1](https://linux-hardware.org/?probe=49921908d1) | Apr 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [9a068872f6](https://linux-hardware.org/?probe=9a068872f6) | Apr 06, 2023 |
| 3Logic Gro... | TUNDRA                      | Server      | [d4d160584c](https://linux-hardware.org/?probe=d4d160584c) | Apr 06, 2023 |
| HP            | ProBook 4525s               | Notebook    | [164d8993b4](https://linux-hardware.org/?probe=164d8993b4) | Apr 04, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [5fd883493a](https://linux-hardware.org/?probe=5fd883493a) | Apr 03, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [44b5c81131](https://linux-hardware.org/?probe=44b5c81131) | Apr 03, 2023 |
| MSI           | Sword 15 A12UE              | Notebook    | [3389b32105](https://linux-hardware.org/?probe=3389b32105) | Apr 01, 2023 |
| Quanta        | 2AC5 100                    | Desktop     | [7f253a82dc](https://linux-hardware.org/?probe=7f253a82dc) | Mar 31, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [36b3103f3f](https://linux-hardware.org/?probe=36b3103f3f) | Mar 31, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [7404d94ca4](https://linux-hardware.org/?probe=7404d94ca4) | Mar 31, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [3ad3c5e45c](https://linux-hardware.org/?probe=3ad3c5e45c) | Mar 30, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [8400d48ed0](https://linux-hardware.org/?probe=8400d48ed0) | Mar 29, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [ea8ce90ed5](https://linux-hardware.org/?probe=ea8ce90ed5) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [deb6990c19](https://linux-hardware.org/?probe=deb6990c19) | Mar 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [ef91ef3645](https://linux-hardware.org/?probe=ef91ef3645) | Mar 27, 2023 |
| MSI           | Modern 15 B12M              | Notebook    | [eded7b36b1](https://linux-hardware.org/?probe=eded7b36b1) | Mar 27, 2023 |
| MSI           | Modern 15 B12M              | Notebook    | [9ee3ca41c8](https://linux-hardware.org/?probe=9ee3ca41c8) | Mar 27, 2023 |
| HP            | 0AA4h                       | Desktop     | [a77b084eba](https://linux-hardware.org/?probe=a77b084eba) | Mar 25, 2023 |
| Intel         | D945GNT AAC96315-405        | Desktop     | [fcc7a18f89](https://linux-hardware.org/?probe=fcc7a18f89) | Mar 24, 2023 |
| iRU           | P231                        | All in one  | [98e5c0ba37](https://linux-hardware.org/?probe=98e5c0ba37) | Mar 23, 2023 |
| DEPO Compu... | MS-7846                     | Desktop     | [baaaef2394](https://linux-hardware.org/?probe=baaaef2394) | Mar 22, 2023 |
| MSI           | Sword 15 A12UE              | Notebook    | [f4341a491a](https://linux-hardware.org/?probe=f4341a491a) | Mar 21, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [be9b767d92](https://linux-hardware.org/?probe=be9b767d92) | Mar 20, 2023 |
| Intel         | D945GNT AAC96315-405        | Desktop     | [58c99c07a6](https://linux-hardware.org/?probe=58c99c07a6) | Mar 17, 2023 |
| Biostar       | H610MH                      | Desktop     | [6b367d747d](https://linux-hardware.org/?probe=6b367d747d) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [9e172b266b](https://linux-hardware.org/?probe=9e172b266b) | Mar 16, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [a26dff699b](https://linux-hardware.org/?probe=a26dff699b) | Mar 14, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [47b6690dc8](https://linux-hardware.org/?probe=47b6690dc8) | Mar 13, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [7c7bdc15fe](https://linux-hardware.org/?probe=7c7bdc15fe) | Mar 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [b473b68faf](https://linux-hardware.org/?probe=b473b68faf) | Mar 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [4a8589fbdf](https://linux-hardware.org/?probe=4a8589fbdf) | Mar 10, 2023 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [9442ced293](https://linux-hardware.org/?probe=9442ced293) | Mar 09, 2023 |
| HP            | 8599                        | Desktop     | [2b9bd0b4a7](https://linux-hardware.org/?probe=2b9bd0b4a7) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [ccb99906a8](https://linux-hardware.org/?probe=ccb99906a8) | Mar 06, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [a78a4114e6](https://linux-hardware.org/?probe=a78a4114e6) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [388d4b38c1](https://linux-hardware.org/?probe=388d4b38c1) | Mar 06, 2023 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [6d97e48a7e](https://linux-hardware.org/?probe=6d97e48a7e) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [8741c0e2f1](https://linux-hardware.org/?probe=8741c0e2f1) | Mar 06, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [9e1f0243d7](https://linux-hardware.org/?probe=9e1f0243d7) | Mar 06, 2023 |
| Intel         | D945GNT AAC96315-405        | Desktop     | [0d02616013](https://linux-hardware.org/?probe=0d02616013) | Mar 03, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [2485632618](https://linux-hardware.org/?probe=2485632618) | Mar 02, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [9acee9d7d4](https://linux-hardware.org/?probe=9acee9d7d4) | Mar 02, 2023 |
| Aquarius      | AQB560M                     | Desktop     | [fedd6483cd](https://linux-hardware.org/?probe=fedd6483cd) | Mar 01, 2023 |
| ASUSTek       | V241DA                      | All in one  | [0779deca8b](https://linux-hardware.org/?probe=0779deca8b) | Feb 28, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [4c3b90ede8](https://linux-hardware.org/?probe=4c3b90ede8) | Feb 28, 2023 |
| Aquarius      | AQB560M                     | Desktop     | [ee0c530562](https://linux-hardware.org/?probe=ee0c530562) | Feb 28, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [d6eb6b4839](https://linux-hardware.org/?probe=d6eb6b4839) | Feb 28, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [98eee7b827](https://linux-hardware.org/?probe=98eee7b827) | Feb 28, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [dbb3e73c89](https://linux-hardware.org/?probe=dbb3e73c89) | Feb 27, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b116afe451](https://linux-hardware.org/?probe=b116afe451) | Feb 27, 2023 |
| Kraftway      | ACCORD                      | Notebook    | [8fe15f2f2b](https://linux-hardware.org/?probe=8fe15f2f2b) | Feb 22, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [f511e61852](https://linux-hardware.org/?probe=f511e61852) | Feb 21, 2023 |
| Lenovo        | ThinkCentre M91p 4524PL4    | Desktop     | [5cda5522e8](https://linux-hardware.org/?probe=5cda5522e8) | Feb 21, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [eec6e2f905](https://linux-hardware.org/?probe=eec6e2f905) | Feb 21, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [e3156cc208](https://linux-hardware.org/?probe=e3156cc208) | Feb 20, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [243ef00f70](https://linux-hardware.org/?probe=243ef00f70) | Feb 17, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [10e9491ee4](https://linux-hardware.org/?probe=10e9491ee4) | Feb 17, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [a3b352975c](https://linux-hardware.org/?probe=a3b352975c) | Feb 17, 2023 |
| HP            | 18E7                        | Desktop     | [2c779d2395](https://linux-hardware.org/?probe=2c779d2395) | Feb 17, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [4d9144193f](https://linux-hardware.org/?probe=4d9144193f) | Feb 17, 2023 |
| iRU           | v1.0                        | Desktop     | [9d70818485](https://linux-hardware.org/?probe=9d70818485) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [9de0373acc](https://linux-hardware.org/?probe=9de0373acc) | Feb 16, 2023 |
| Lenovo        | 31A7 NOK                    | Mini pc     | [17f1e0f135](https://linux-hardware.org/?probe=17f1e0f135) | Feb 16, 2023 |
| iRU           | P231                        | All in one  | [4aa7858493](https://linux-hardware.org/?probe=4aa7858493) | Feb 14, 2023 |
| ICL           | H410SB                      | Desktop     | [e994f10643](https://linux-hardware.org/?probe=e994f10643) | Feb 14, 2023 |
| MSI           | PRO B660M-E DDR4            | Desktop     | [aab30259f8](https://linux-hardware.org/?probe=aab30259f8) | Feb 13, 2023 |
| HP            | 895F                        | All in one  | [0c23df771f](https://linux-hardware.org/?probe=0c23df771f) | Feb 13, 2023 |
| Acer          | Aspire C27-1655             | All in one  | [4fe6ca7f88](https://linux-hardware.org/?probe=4fe6ca7f88) | Feb 13, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [2512d8d9ab](https://linux-hardware.org/?probe=2512d8d9ab) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [09073fcfc8](https://linux-hardware.org/?probe=09073fcfc8) | Feb 10, 2023 |
| HP            | G62                         | Notebook    | [8bc9454fb1](https://linux-hardware.org/?probe=8bc9454fb1) | Feb 10, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [dea6a1a077](https://linux-hardware.org/?probe=dea6a1a077) | Feb 09, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [d3b63de821](https://linux-hardware.org/?probe=d3b63de821) | Feb 07, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4bc9beae71](https://linux-hardware.org/?probe=4bc9beae71) | Feb 07, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a2172caf56](https://linux-hardware.org/?probe=a2172caf56) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [77faeb6b52](https://linux-hardware.org/?probe=77faeb6b52) | Feb 06, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [395b6fa893](https://linux-hardware.org/?probe=395b6fa893) | Feb 06, 2023 |
| HP            | Pavilion 15                 | Notebook    | [eb37d7677c](https://linux-hardware.org/?probe=eb37d7677c) | Feb 06, 2023 |
| Lenovo        | 3708 NOK                    | Desktop     | [b306f4c9dc](https://linux-hardware.org/?probe=b306f4c9dc) | Feb 06, 2023 |
| Compal        | DIP00                       | Desktop     | [fc6de899ba](https://linux-hardware.org/?probe=fc6de899ba) | Feb 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [bb0481d7a8](https://linux-hardware.org/?probe=bb0481d7a8) | Feb 06, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [b2fec94855](https://linux-hardware.org/?probe=b2fec94855) | Feb 05, 2023 |
| HP            | 8599                        | Desktop     | [3ffedfbc62](https://linux-hardware.org/?probe=3ffedfbc62) | Jan 31, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [c53133f306](https://linux-hardware.org/?probe=c53133f306) | Jan 31, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [9721d24c04](https://linux-hardware.org/?probe=9721d24c04) | Jan 31, 2023 |
| HP            | 8599                        | Desktop     | [759d3a0829](https://linux-hardware.org/?probe=759d3a0829) | Jan 31, 2023 |
| Intel         | S2600WFT H48104-854         | Server      | [68791b3635](https://linux-hardware.org/?probe=68791b3635) | Jan 30, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [89d336f0b7](https://linux-hardware.org/?probe=89d336f0b7) | Jan 30, 2023 |
| DEPO Compu... | DPH410S                     | Desktop     | [d380c83ebf](https://linux-hardware.org/?probe=d380c83ebf) | Jan 28, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [13f23afb38](https://linux-hardware.org/?probe=13f23afb38) | Jan 27, 2023 |
| Aquarius      | AQB560M                     | Desktop     | [1187e4d240](https://linux-hardware.org/?probe=1187e4d240) | Jan 27, 2023 |
| Lenovo        | ThinkCentre M70e 0851RZ3    | Desktop     | [23b8d711f4](https://linux-hardware.org/?probe=23b8d711f4) | Jan 25, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [87c61b6748](https://linux-hardware.org/?probe=87c61b6748) | Jan 25, 2023 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [8a06b2350d](https://linux-hardware.org/?probe=8a06b2350d) | Jan 25, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [186aef8e0c](https://linux-hardware.org/?probe=186aef8e0c) | Jan 24, 2023 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [d5c4129361](https://linux-hardware.org/?probe=d5c4129361) | Jan 23, 2023 |
| HP            | 18E4                        | Desktop     | [9a62a59c37](https://linux-hardware.org/?probe=9a62a59c37) | Jan 20, 2023 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [86d4a0e87c](https://linux-hardware.org/?probe=86d4a0e87c) | Jan 20, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [a74a5b3b7b](https://linux-hardware.org/?probe=a74a5b3b7b) | Jan 20, 2023 |
| ASUSTek       | V241FA                      | All in one  | [24ed481783](https://linux-hardware.org/?probe=24ed481783) | Jan 20, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8472d89767](https://linux-hardware.org/?probe=8472d89767) | Jan 20, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [cbd81c917f](https://linux-hardware.org/?probe=cbd81c917f) | Jan 20, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7d95709d81](https://linux-hardware.org/?probe=7d95709d81) | Jan 19, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [4e77673e60](https://linux-hardware.org/?probe=4e77673e60) | Jan 19, 2023 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [3f185b85f5](https://linux-hardware.org/?probe=3f185b85f5) | Jan 18, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [1e6f35ceff](https://linux-hardware.org/?probe=1e6f35ceff) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [3fb3939014](https://linux-hardware.org/?probe=3fb3939014) | Jan 18, 2023 |
| Samsung       | DP300A2A-B01RU SEC_SW_RE... | All in one  | [03c97b653e](https://linux-hardware.org/?probe=03c97b653e) | Jan 18, 2023 |
| NCI           | PC BLICK101                 | Soc         | [018eb0b0bb](https://linux-hardware.org/?probe=018eb0b0bb) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [8b992a1d50](https://linux-hardware.org/?probe=8b992a1d50) | Jan 17, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [a4ee55fea9](https://linux-hardware.org/?probe=a4ee55fea9) | Jan 17, 2023 |
| Samsung       | DP300A2A-B01RU SEC_SW_RE... | All in one  | [35cae36101](https://linux-hardware.org/?probe=35cae36101) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b6e4100bc6](https://linux-hardware.org/?probe=b6e4100bc6) | Jan 17, 2023 |
| Unknown       | T310D11                     | Desktop     | [acce0e1df1](https://linux-hardware.org/?probe=acce0e1df1) | Jan 16, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [aea58aa72f](https://linux-hardware.org/?probe=aea58aa72f) | Jan 16, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [6c3f234091](https://linux-hardware.org/?probe=6c3f234091) | Jan 11, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [2e985853be](https://linux-hardware.org/?probe=2e985853be) | Jan 11, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [31ecdfb704](https://linux-hardware.org/?probe=31ecdfb704) | Jan 11, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [4f9477b846](https://linux-hardware.org/?probe=4f9477b846) | Jan 08, 2023 |
| HP            | 82DC 1000                   | All in one  | [12c8c204ff](https://linux-hardware.org/?probe=12c8c204ff) | Dec 30, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [a05251fd39](https://linux-hardware.org/?probe=a05251fd39) | Dec 29, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [fe79eba13b](https://linux-hardware.org/?probe=fe79eba13b) | Dec 29, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [f040219e23](https://linux-hardware.org/?probe=f040219e23) | Dec 26, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [b5ff4bd9d6](https://linux-hardware.org/?probe=b5ff4bd9d6) | Dec 26, 2022 |
| HP            | 895F                        | All in one  | [670e3fa0fa](https://linux-hardware.org/?probe=670e3fa0fa) | Dec 26, 2022 |
| HP            | Notebook                    | Notebook    | [10dfda9549](https://linux-hardware.org/?probe=10dfda9549) | Dec 24, 2022 |
| HP            | 895F                        | All in one  | [8e512dfec4](https://linux-hardware.org/?probe=8e512dfec4) | Dec 23, 2022 |
| HP            | 895F                        | All in one  | [0360aa0d07](https://linux-hardware.org/?probe=0360aa0d07) | Dec 23, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [f5f35c12a4](https://linux-hardware.org/?probe=f5f35c12a4) | Dec 23, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [686b84facc](https://linux-hardware.org/?probe=686b84facc) | Dec 23, 2022 |
| DEPO Compu... | DPH410S                     | Desktop     | [0ba02e46fa](https://linux-hardware.org/?probe=0ba02e46fa) | Dec 22, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [8ea27950b9](https://linux-hardware.org/?probe=8ea27950b9) | Dec 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [4c1ad2ea2e](https://linux-hardware.org/?probe=4c1ad2ea2e) | Dec 18, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [a199d930ff](https://linux-hardware.org/?probe=a199d930ff) | Dec 18, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [8babc33ab6](https://linux-hardware.org/?probe=8babc33ab6) | Dec 17, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [20ce0a7f23](https://linux-hardware.org/?probe=20ce0a7f23) | Dec 16, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [257ccc50d8](https://linux-hardware.org/?probe=257ccc50d8) | Dec 15, 2022 |
| Colorful T... | H610M-K M.2 V20             | Desktop     | [795e44f6f2](https://linux-hardware.org/?probe=795e44f6f2) | Dec 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [af9afd9f4b](https://linux-hardware.org/?probe=af9afd9f4b) | Dec 14, 2022 |
| ASUSTek       | PB62                        | Desktop     | [fb3796ceea](https://linux-hardware.org/?probe=fb3796ceea) | Dec 12, 2022 |
| ASUSTek       | PB62                        | Desktop     | [4d4a5fcc93](https://linux-hardware.org/?probe=4d4a5fcc93) | Dec 12, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [6cedae9702](https://linux-hardware.org/?probe=6cedae9702) | Dec 10, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [89e51f2eaa](https://linux-hardware.org/?probe=89e51f2eaa) | Dec 09, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [311f47baef](https://linux-hardware.org/?probe=311f47baef) | Dec 09, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [79a0f9e73a](https://linux-hardware.org/?probe=79a0f9e73a) | Dec 08, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [c1cd524970](https://linux-hardware.org/?probe=c1cd524970) | Dec 08, 2022 |
| Aquarius      | NS685U R11                  | Notebook    | [c0dff8c525](https://linux-hardware.org/?probe=c0dff8c525) | Dec 08, 2022 |
| Lenovo        | 10088                       | All in one  | [5fe857bab3](https://linux-hardware.org/?probe=5fe857bab3) | Dec 07, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [b8c52ae5cb](https://linux-hardware.org/?probe=b8c52ae5cb) | Dec 06, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [aaa5171bd6](https://linux-hardware.org/?probe=aaa5171bd6) | Dec 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [0cd3371014](https://linux-hardware.org/?probe=0cd3371014) | Dec 05, 2022 |
| MSI           | Sword 15 A12UE              | Notebook    | [32df733b5e](https://linux-hardware.org/?probe=32df733b5e) | Dec 04, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [4309758f8f](https://linux-hardware.org/?probe=4309758f8f) | Dec 02, 2022 |
| HP            | 84EE 1100                   | All in one  | [7efea8ad7f](https://linux-hardware.org/?probe=7efea8ad7f) | Dec 01, 2022 |
| Lenovo        | Aptio CRB No DPK            | Mini pc     | [eeddc09936](https://linux-hardware.org/?probe=eeddc09936) | Nov 28, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [ddb1791ff6](https://linux-hardware.org/?probe=ddb1791ff6) | Nov 28, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4b9ee0ef6a](https://linux-hardware.org/?probe=4b9ee0ef6a) | Nov 28, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [8882bfe4f8](https://linux-hardware.org/?probe=8882bfe4f8) | Nov 28, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d9ae3d1795](https://linux-hardware.org/?probe=d9ae3d1795) | Nov 27, 2022 |
| Gigabyte      | X570S UD                    | Desktop     | [381b3c892d](https://linux-hardware.org/?probe=381b3c892d) | Nov 25, 2022 |
| Lenovo        | 31900059 STD                | All in one  | [812cce763f](https://linux-hardware.org/?probe=812cce763f) | Nov 25, 2022 |
| Lenovo        | 31900059 STD                | All in one  | [bfe8939ffc](https://linux-hardware.org/?probe=bfe8939ffc) | Nov 25, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [7d6cf8c81f](https://linux-hardware.org/?probe=7d6cf8c81f) | Nov 24, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [ff3d0a1ecf](https://linux-hardware.org/?probe=ff3d0a1ecf) | Nov 24, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [f86569d54b](https://linux-hardware.org/?probe=f86569d54b) | Nov 24, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [e48d26b26f](https://linux-hardware.org/?probe=e48d26b26f) | Nov 21, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [a54f42b51e](https://linux-hardware.org/?probe=a54f42b51e) | Nov 18, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [faa0deab8f](https://linux-hardware.org/?probe=faa0deab8f) | Nov 18, 2022 |
| Unknown       | P43Twins1600                | Desktop     | [1db44f50c4](https://linux-hardware.org/?probe=1db44f50c4) | Nov 18, 2022 |
| ASRock        | H310CM-DVS                  | Desktop     | [23194fe7d9](https://linux-hardware.org/?probe=23194fe7d9) | Nov 16, 2022 |
| HP            | 2179                        | Desktop     | [3407225f33](https://linux-hardware.org/?probe=3407225f33) | Nov 14, 2022 |
| ASRock        | H310CM-DVS                  | Desktop     | [86932d2426](https://linux-hardware.org/?probe=86932d2426) | Nov 14, 2022 |
| Lenovo        | ThinkPad X220 4290RB3       | Notebook    | [37959973aa](https://linux-hardware.org/?probe=37959973aa) | Nov 11, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [ef983bc60e](https://linux-hardware.org/?probe=ef983bc60e) | Nov 11, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3fd33e6782](https://linux-hardware.org/?probe=3fd33e6782) | Nov 09, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [e525d01069](https://linux-hardware.org/?probe=e525d01069) | Nov 08, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [b74787fe62](https://linux-hardware.org/?probe=b74787fe62) | Nov 08, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [63f5fe9444](https://linux-hardware.org/?probe=63f5fe9444) | Nov 04, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [dba14315ca](https://linux-hardware.org/?probe=dba14315ca) | Nov 03, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [4776ed964f](https://linux-hardware.org/?probe=4776ed964f) | Nov 03, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [2c20efc0df](https://linux-hardware.org/?probe=2c20efc0df) | Nov 03, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [8fe13e2165](https://linux-hardware.org/?probe=8fe13e2165) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [562f466f8d](https://linux-hardware.org/?probe=562f466f8d) | Nov 02, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [38b68c6946](https://linux-hardware.org/?probe=38b68c6946) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [b68271c648](https://linux-hardware.org/?probe=b68271c648) | Nov 02, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [06bbc75ef0](https://linux-hardware.org/?probe=06bbc75ef0) | Nov 01, 2022 |
| MSI           | 0A90                        | Desktop     | [47fa407c02](https://linux-hardware.org/?probe=47fa407c02) | Nov 01, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [d653658a53](https://linux-hardware.org/?probe=d653658a53) | Oct 28, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [00766db60b](https://linux-hardware.org/?probe=00766db60b) | Oct 28, 2022 |
| MSI           | 0A90                        | Desktop     | [a15ab9db5e](https://linux-hardware.org/?probe=a15ab9db5e) | Oct 28, 2022 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [cacdacb3ad](https://linux-hardware.org/?probe=cacdacb3ad) | Oct 28, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [b9ab6b9cf2](https://linux-hardware.org/?probe=b9ab6b9cf2) | Oct 28, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [9c429fe90c](https://linux-hardware.org/?probe=9c429fe90c) | Oct 27, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [1ee47a3ab6](https://linux-hardware.org/?probe=1ee47a3ab6) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [92dbe47379](https://linux-hardware.org/?probe=92dbe47379) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [247782b262](https://linux-hardware.org/?probe=247782b262) | Oct 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [14537f243b](https://linux-hardware.org/?probe=14537f243b) | Oct 24, 2022 |
| THUNDEROBO... | 911AirD                     | Notebook    | [f471a1c9db](https://linux-hardware.org/?probe=f471a1c9db) | Oct 23, 2022 |
| Lenovo        | 3708 NOK                    | Desktop     | [f48f731517](https://linux-hardware.org/?probe=f48f731517) | Oct 21, 2022 |
| Intel         | S2600WFT H48104-854         | Server      | [4887ba4bfa](https://linux-hardware.org/?probe=4887ba4bfa) | Oct 21, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [7515d53b5d](https://linux-hardware.org/?probe=7515d53b5d) | Oct 21, 2022 |
| Gigabyte      | B360HD3                     | Desktop     | [bbbdee0883](https://linux-hardware.org/?probe=bbbdee0883) | Oct 21, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [71c9391b8b](https://linux-hardware.org/?probe=71c9391b8b) | Oct 21, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3fc175d4a0](https://linux-hardware.org/?probe=3fc175d4a0) | Oct 20, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [39838b7f39](https://linux-hardware.org/?probe=39838b7f39) | Oct 20, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [fe184c8f5b](https://linux-hardware.org/?probe=fe184c8f5b) | Oct 19, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [0db79bc085](https://linux-hardware.org/?probe=0db79bc085) | Oct 19, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [e75a8830af](https://linux-hardware.org/?probe=e75a8830af) | Oct 19, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [b8303261ad](https://linux-hardware.org/?probe=b8303261ad) | Oct 18, 2022 |
| HP            | 83EB                        | All in one  | [1011557c31](https://linux-hardware.org/?probe=1011557c31) | Oct 18, 2022 |
| HP            | 83EB                        | All in one  | [f81210f730](https://linux-hardware.org/?probe=f81210f730) | Oct 18, 2022 |
| Intel         | S2600WFT H48104-854         | Server      | [7fa3948164](https://linux-hardware.org/?probe=7fa3948164) | Oct 17, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c6958291bd](https://linux-hardware.org/?probe=c6958291bd) | Oct 14, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [1cdde90662](https://linux-hardware.org/?probe=1cdde90662) | Oct 13, 2022 |
| HP            | 1495                        | Desktop     | [b1523ff4a6](https://linux-hardware.org/?probe=b1523ff4a6) | Oct 13, 2022 |
| YADRO         | VEGMAN Motherboard MBDX8... | Server      | [97b57f8628](https://linux-hardware.org/?probe=97b57f8628) | Oct 13, 2022 |
| YADRO         | VEGMAN Motherboard MBDX8... | Server      | [f74f853f54](https://linux-hardware.org/?probe=f74f853f54) | Oct 12, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [087d1975e1](https://linux-hardware.org/?probe=087d1975e1) | Oct 12, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [1d936352ea](https://linux-hardware.org/?probe=1d936352ea) | Oct 10, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [e799b41d70](https://linux-hardware.org/?probe=e799b41d70) | Oct 09, 2022 |
| Acer          | Aspire 2920                 | Notebook    | [c588bacc95](https://linux-hardware.org/?probe=c588bacc95) | Oct 08, 2022 |
| Acer          | Aspire 2920                 | Notebook    | [34b41a4e67](https://linux-hardware.org/?probe=34b41a4e67) | Oct 08, 2022 |
| MSI           | H55M-E33                    | Desktop     | [95423ecdbe](https://linux-hardware.org/?probe=95423ecdbe) | Oct 07, 2022 |
| ASUSTek       | X540NV                      | Notebook    | [31e4464fea](https://linux-hardware.org/?probe=31e4464fea) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [9fd01561ce](https://linux-hardware.org/?probe=9fd01561ce) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [4c0bb83f01](https://linux-hardware.org/?probe=4c0bb83f01) | Oct 07, 2022 |
| MSI           | H55M-E33                    | Desktop     | [7af53a4dee](https://linux-hardware.org/?probe=7af53a4dee) | Oct 06, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7f8e650618](https://linux-hardware.org/?probe=7f8e650618) | Oct 06, 2022 |
| Acer          | Aspire 2920                 | Notebook    | [538f7a6e26](https://linux-hardware.org/?probe=538f7a6e26) | Oct 05, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [0a8238a876](https://linux-hardware.org/?probe=0a8238a876) | Oct 05, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [b90de94f3d](https://linux-hardware.org/?probe=b90de94f3d) | Oct 05, 2022 |
| THUNDEROBO... | 911AirD                     | Notebook    | [69a9650652](https://linux-hardware.org/?probe=69a9650652) | Oct 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [89b48cd98e](https://linux-hardware.org/?probe=89b48cd98e) | Oct 03, 2022 |
| Lenovo        | 32E4 NOK                    | Mini pc     | [f49f7ba847](https://linux-hardware.org/?probe=f49f7ba847) | Oct 03, 2022 |
| Digma         | EVE 11 C408                 | Notebook    | [b5c7ac8ed3](https://linux-hardware.org/?probe=b5c7ac8ed3) | Sep 30, 2022 |
| ASRock        | B360M-HDV                   | Desktop     | [fad5a877f5](https://linux-hardware.org/?probe=fad5a877f5) | Sep 30, 2022 |
| THUNDEROBO... | 911AirD                     | Notebook    | [99f1b7e253](https://linux-hardware.org/?probe=99f1b7e253) | Sep 29, 2022 |
| RDW           | MB-B450M V.1                | Desktop     | [8c3a565d43](https://linux-hardware.org/?probe=8c3a565d43) | Sep 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [1748378749](https://linux-hardware.org/?probe=1748378749) | Sep 22, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [3888b56318](https://linux-hardware.org/?probe=3888b56318) | Sep 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [66a228f8c5](https://linux-hardware.org/?probe=66a228f8c5) | Sep 21, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [0b610b66a9](https://linux-hardware.org/?probe=0b610b66a9) | Sep 20, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [fd03d25b78](https://linux-hardware.org/?probe=fd03d25b78) | Sep 15, 2022 |
| ECS           | H510H6-M7                   | Desktop     | [1275257180](https://linux-hardware.org/?probe=1275257180) | Sep 14, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [713797403a](https://linux-hardware.org/?probe=713797403a) | Sep 09, 2022 |
| IP3 Techno... | ACN30                       | Notebook    | [af9694cea8](https://linux-hardware.org/?probe=af9694cea8) | Sep 06, 2022 |
| IP3 Techno... | ACN30                       | Notebook    | [03f14a115d](https://linux-hardware.org/?probe=03f14a115d) | Sep 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [40c1fd4544](https://linux-hardware.org/?probe=40c1fd4544) | Sep 05, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [04b62ac6e3](https://linux-hardware.org/?probe=04b62ac6e3) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [a60315c259](https://linux-hardware.org/?probe=a60315c259) | Sep 04, 2022 |
| MSI           | FX610                       | Notebook    | [a822818a58](https://linux-hardware.org/?probe=a822818a58) | Sep 03, 2022 |
| ASRock        | N68-VS3 FX                  | Desktop     | [b4c043c208](https://linux-hardware.org/?probe=b4c043c208) | Sep 01, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [3b519201e2](https://linux-hardware.org/?probe=3b519201e2) | Aug 22, 2022 |
| Gigabyte      | X58-USB3                    | Desktop     | [5119bcb630](https://linux-hardware.org/?probe=5119bcb630) | Aug 19, 2022 |
| IP3 Techno... | ACN30                       | Notebook    | [e25ed534c0](https://linux-hardware.org/?probe=e25ed534c0) | Aug 18, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [a42c4dc65a](https://linux-hardware.org/?probe=a42c4dc65a) | Aug 09, 2022 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [c02a953cda](https://linux-hardware.org/?probe=c02a953cda) | Aug 01, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [14f73b6a3a](https://linux-hardware.org/?probe=14f73b6a3a) | Aug 01, 2022 |
| Digma         | EVE 15 P417 ES5063EW        | Notebook    | [a584c678b5](https://linux-hardware.org/?probe=a584c678b5) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | Notebook    | [4fd01756b2](https://linux-hardware.org/?probe=4fd01756b2) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | Notebook    | [008b02cc92](https://linux-hardware.org/?probe=008b02cc92) | Jul 26, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [5375c9c059](https://linux-hardware.org/?probe=5375c9c059) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [413949a727](https://linux-hardware.org/?probe=413949a727) | Jul 25, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [3bfcedd5c8](https://linux-hardware.org/?probe=3bfcedd5c8) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [c49282206c](https://linux-hardware.org/?probe=c49282206c) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [d598c4587d](https://linux-hardware.org/?probe=d598c4587d) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [7cc031e93b](https://linux-hardware.org/?probe=7cc031e93b) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [946610c122](https://linux-hardware.org/?probe=946610c122) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [5b1e962751](https://linux-hardware.org/?probe=5b1e962751) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [4e120b3b63](https://linux-hardware.org/?probe=4e120b3b63) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [fbff39be7e](https://linux-hardware.org/?probe=fbff39be7e) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [2d5bedf224](https://linux-hardware.org/?probe=2d5bedf224) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [297ce5144e](https://linux-hardware.org/?probe=297ce5144e) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [84b7cd1115](https://linux-hardware.org/?probe=84b7cd1115) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [a92b6c5d73](https://linux-hardware.org/?probe=a92b6c5d73) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [51ebd271c8](https://linux-hardware.org/?probe=51ebd271c8) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [0076bf5efc](https://linux-hardware.org/?probe=0076bf5efc) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [44ad7f7d47](https://linux-hardware.org/?probe=44ad7f7d47) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [49068a26b5](https://linux-hardware.org/?probe=49068a26b5) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [62ce596bf3](https://linux-hardware.org/?probe=62ce596bf3) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [812db8ad6f](https://linux-hardware.org/?probe=812db8ad6f) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [d4c2b5ffad](https://linux-hardware.org/?probe=d4c2b5ffad) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [4c0179b60e](https://linux-hardware.org/?probe=4c0179b60e) | Jul 22, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8601888983](https://linux-hardware.org/?probe=8601888983) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [1d505390d6](https://linux-hardware.org/?probe=1d505390d6) | Jul 22, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [5b3340311a](https://linux-hardware.org/?probe=5b3340311a) | Jul 20, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [154c254eac](https://linux-hardware.org/?probe=154c254eac) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | Notebook    | [60921a7ff6](https://linux-hardware.org/?probe=60921a7ff6) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | Notebook    | [c24f8b4ba6](https://linux-hardware.org/?probe=c24f8b4ba6) | Jul 19, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [4f1a1bfb2d](https://linux-hardware.org/?probe=4f1a1bfb2d) | Jul 19, 2022 |
| Gigabyte      | 970A-D3                     | Desktop     | [f2ae77cc0c](https://linux-hardware.org/?probe=f2ae77cc0c) | Jul 17, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [fe971bb8c3](https://linux-hardware.org/?probe=fe971bb8c3) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [2835672840](https://linux-hardware.org/?probe=2835672840) | Jul 07, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [24e49bc011](https://linux-hardware.org/?probe=24e49bc011) | Jun 27, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [39e3c55e89](https://linux-hardware.org/?probe=39e3c55e89) | Jun 27, 2022 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [d85cded80a](https://linux-hardware.org/?probe=d85cded80a) | Jun 20, 2022 |
| Aquarius      | NS685U                      | Notebook    | [ecedc7cbb6](https://linux-hardware.org/?probe=ecedc7cbb6) | Jun 08, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [28e8a1e19c](https://linux-hardware.org/?probe=28e8a1e19c) | Jun 07, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [df5b1991e1](https://linux-hardware.org/?probe=df5b1991e1) | Jun 07, 2022 |
| ICL           | Unknown                     | Notebook    | [4dc89fc689](https://linux-hardware.org/?probe=4dc89fc689) | Jun 07, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [8ea7efbf2e](https://linux-hardware.org/?probe=8ea7efbf2e) | Jun 07, 2022 |
| iRU           | v1.0                        | Mini pc     | [845212ce42](https://linux-hardware.org/?probe=845212ce42) | Jun 02, 2022 |
| iRU           | v1.0                        | Mini pc     | [15b125fb9e](https://linux-hardware.org/?probe=15b125fb9e) | May 31, 2022 |
| iRU           | v1.0                        | Mini pc     | [991e061d78](https://linux-hardware.org/?probe=991e061d78) | May 31, 2022 |
| MSI           | A520M PRO                   | Desktop     | [3eb8006c14](https://linux-hardware.org/?probe=3eb8006c14) | May 26, 2022 |
| MSI           | A520M PRO                   | Desktop     | [9766bbe4c0](https://linux-hardware.org/?probe=9766bbe4c0) | May 25, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [b3b2ee08af](https://linux-hardware.org/?probe=b3b2ee08af) | May 23, 2022 |
| MSI           | H510TI-S01                  | Desktop     | [efe42ef07a](https://linux-hardware.org/?probe=efe42ef07a) | May 19, 2022 |
| ASUSTek       | V241IC-R                    | All in one  | [48add8dc01](https://linux-hardware.org/?probe=48add8dc01) | May 19, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [e405d209d4](https://linux-hardware.org/?probe=e405d209d4) | May 11, 2022 |
| mtech         | MTL1578                     | Notebook    | [bf25c26ea0](https://linux-hardware.org/?probe=bf25c26ea0) | May 11, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [66bb3248d5](https://linux-hardware.org/?probe=66bb3248d5) | May 11, 2022 |
| Digma         | CITI 10 C402T CS1044EW      | Tablet      | [eefe92e281](https://linux-hardware.org/?probe=eefe92e281) | May 04, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [1c3459c038](https://linux-hardware.org/?probe=1c3459c038) | Apr 19, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e2e025dd4f](https://linux-hardware.org/?probe=e2e025dd4f) | Apr 15, 2022 |
| Acer          | TravelMate P215-53          | Notebook    | [124fdb3b64](https://linux-hardware.org/?probe=124fdb3b64) | Apr 14, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [be41efbec8](https://linux-hardware.org/?probe=be41efbec8) | Apr 05, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| Aquarius      | NS585 R32                   | Notebook    | [582389ca98](https://linux-hardware.org/?probe=582389ca98) | Mar 24, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [e76e5359b7](https://linux-hardware.org/?probe=e76e5359b7) | Mar 23, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [56f9ebba91](https://linux-hardware.org/?probe=56f9ebba91) | Mar 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [e18b80073c](https://linux-hardware.org/?probe=e18b80073c) | Mar 21, 2022 |
| 3Logic Gro... | APM Graviton A15i-K2        | Notebook    | [e93bcf2f42](https://linux-hardware.org/?probe=e93bcf2f42) | Mar 09, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [5074891336](https://linux-hardware.org/?probe=5074891336) | Mar 09, 2022 |
| Aquarius      | AQH410T                     | Desktop     | [f02c2d0259](https://linux-hardware.org/?probe=f02c2d0259) | Mar 02, 2022 |
| Aquarius      | AQB560M                     | All in one  | [4d3df118f0](https://linux-hardware.org/?probe=4d3df118f0) | Mar 01, 2022 |
| Aquarius      | AQB560M                     | Desktop     | [091fa6d697](https://linux-hardware.org/?probe=091fa6d697) | Mar 01, 2022 |
| Lenovo        | 316E SDK0J40697 WIN 3305... | Mini pc     | [bf51c93832](https://linux-hardware.org/?probe=bf51c93832) | Feb 22, 2022 |
| Lenovo        | 316E SDK0J40697 WIN 3305... | Mini pc     | [a831ba5c10](https://linux-hardware.org/?probe=a831ba5c10) | Feb 22, 2022 |
| Gigabyte      | B560M DS3H                  | Desktop     | [9db1aef186](https://linux-hardware.org/?probe=9db1aef186) | Feb 18, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [227a2658d0](https://linux-hardware.org/?probe=227a2658d0) | Feb 15, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c1f9ad0faf](https://linux-hardware.org/?probe=c1f9ad0faf) | Feb 01, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [14d2075383](https://linux-hardware.org/?probe=14d2075383) | Jan 31, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [38ddf02b60](https://linux-hardware.org/?probe=38ddf02b60) | Jan 31, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [36db0c9260](https://linux-hardware.org/?probe=36db0c9260) | Jan 17, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [7ed7e139d8](https://linux-hardware.org/?probe=7ed7e139d8) | Dec 20, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [55ab1c9ab8](https://linux-hardware.org/?probe=55ab1c9ab8) | Dec 20, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5bb21d6bf6](https://linux-hardware.org/?probe=5bb21d6bf6) | Dec 13, 2021 |
| Aquarius      | AQB560M                     | Desktop     | [ff20437ae0](https://linux-hardware.org/?probe=ff20437ae0) | Nov 25, 2021 |
| Aquarius      | AQB560M                     | Desktop     | [4656a05904](https://linux-hardware.org/?probe=4656a05904) | Nov 22, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [ef54320d4b](https://linux-hardware.org/?probe=ef54320d4b) | Oct 19, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [5a071f96dd](https://linux-hardware.org/?probe=5a071f96dd) | Oct 19, 2021 |
| ICL           | RAYbook Si1514              | Notebook    | [9ddc61deba](https://linux-hardware.org/?probe=9ddc61deba) | Sep 13, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [4f59992d0f](https://linux-hardware.org/?probe=4f59992d0f) | Sep 11, 2021 |
| ASRock        | H470M-HDV                   | Desktop     | [ba7bdac2dd](https://linux-hardware.org/?probe=ba7bdac2dd) | Sep 04, 2021 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [54a20af366](https://linux-hardware.org/?probe=54a20af366) | Aug 27, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [d8b35044ab](https://linux-hardware.org/?probe=d8b35044ab) | Jul 29, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [9b2c758081](https://linux-hardware.org/?probe=9b2c758081) | Jun 10, 2021 |
| ASUSTek       | H110-PLUS                   | Desktop     | [11e1a45e67](https://linux-hardware.org/?probe=11e1a45e67) | Jun 03, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7b4a0634ef](https://linux-hardware.org/?probe=7b4a0634ef) | Apr 26, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [b779fb9e40](https://linux-hardware.org/?probe=b779fb9e40) | Apr 09, 2021 |
| ASUSTek       | P8H61-I LX R2.0             | Desktop     | [6e0321d64f](https://linux-hardware.org/?probe=6e0321d64f) | Apr 08, 2021 |
| ASUSTek       | X75VD                       | Notebook    | [95ea9551da](https://linux-hardware.org/?probe=95ea9551da) | Apr 05, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [916d4b225b](https://linux-hardware.org/?probe=916d4b225b) | Mar 30, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [ebfafc7409](https://linux-hardware.org/?probe=ebfafc7409) | Mar 26, 2021 |
| HUAWEI        | BOHL-WXX9                   | Notebook    | [cf5559d576](https://linux-hardware.org/?probe=cf5559d576) | Mar 26, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d151197565](https://linux-hardware.org/?probe=d151197565) | Mar 26, 2021 |
| HP            | Pavilion g6                 | Notebook    | [1ca79b1950](https://linux-hardware.org/?probe=1ca79b1950) | Mar 26, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [a61243addd](https://linux-hardware.org/?probe=a61243addd) | Mar 26, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [30e7a27178](https://linux-hardware.org/?probe=30e7a27178) | Mar 22, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [da0a735a9f](https://linux-hardware.org/?probe=da0a735a9f) | Mar 18, 2021 |
| Pegatron      | A35                         | Notebook    | [9923a21e8c](https://linux-hardware.org/?probe=9923a21e8c) | Mar 04, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [5898a71c25](https://linux-hardware.org/?probe=5898a71c25) | Nov 03, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [12f125beba](https://linux-hardware.org/?probe=12f125beba) | Jan 16, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [c88331017f](https://linux-hardware.org/?probe=c88331017f) | Jan 16, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [24adf26804](https://linux-hardware.org/?probe=24adf26804) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Red OS 7.3.2 | 106       | 34.42%  |
| Red OS 7.3.1 | 100       | 32.47%  |
| Red OS 7.3   | 93        | 30.19%  |
| Red OS 7.2   | 9         | 2.92%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Red OS | 292       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.10-1.el7.x86_64   | 55        | 16.82%  |
| 5.15.72-1.el7.3.x86_64 | 48        | 14.68%  |
| 5.15.87-1.el7.3.x86_64 | 47        | 14.37%  |
| 5.10.29-1.el7.x86_64   | 36        | 11.01%  |
| 5.15.35-5.el7.3.x86_64 | 25        | 7.65%   |
| 5.15.78-2.el7.3.x86_64 | 19        | 5.81%   |
| 5.15.35-4.el7.3.x86_64 | 19        | 5.81%   |
| 5.15.35-1.el7.3.x86_64 | 17        | 5.2%    |
| 6.1.20-2.el7.3.x86_64  | 10        | 3.06%   |
| 5.14.9-1.el7.x86_64    | 8         | 2.45%   |
| 5.10.29-3.el7.x86_64   | 7         | 2.14%   |
| 4.19.79-1.el7.x86_64   | 7         | 2.14%   |
| 5.15.10-2.el7.x86_64   | 5         | 1.53%   |
| 5.15.10-3.el7.x86_64   | 4         | 1.22%   |
| 5.10.1-1.el7.x86_64    | 4         | 1.22%   |
| 5.10.24-2.el7.x86_64   | 3         | 0.92%   |
| 6.1.11-1.el7.3.x86_64  | 2         | 0.61%   |
| 5.18.1-1.el7.x86_64    | 2         | 0.61%   |
| 5.15.10-4.el7.x86_64   | 2         | 0.61%   |
| 5.4.197-1.el7.aarch64  | 1         | 0.31%   |
| 5.15.120               | 1         | 0.31%   |
| 5.13.15-1.el7.x86_64   | 1         | 0.31%   |
| 5.10.24-3.el7.x86_64   | 1         | 0.31%   |
| 5.10.24-1.el7.x86_64   | 1         | 0.31%   |
| 4.19.56-2.el7.x86_64   | 1         | 0.31%   |
| 4.19.204-1.el7.x86_64  | 1         | 0.31%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.10  | 66        | 20.43%  |
| 5.15.35  | 57        | 17.65%  |
| 5.15.72  | 48        | 14.86%  |
| 5.15.87  | 47        | 14.55%  |
| 5.10.29  | 43        | 13.31%  |
| 5.15.78  | 19        | 5.88%   |
| 6.1.20   | 10        | 3.1%    |
| 5.14.9   | 8         | 2.48%   |
| 4.19.79  | 7         | 2.17%   |
| 5.10.24  | 5         | 1.55%   |
| 5.10.1   | 4         | 1.24%   |
| 6.1.11   | 2         | 0.62%   |
| 5.18.1   | 2         | 0.62%   |
| 5.4.197  | 1         | 0.31%   |
| 5.15.120 | 1         | 0.31%   |
| 5.13.15  | 1         | 0.31%   |
| 4.19.56  | 1         | 0.31%   |
| 4.19.204 | 1         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 221       | 72.46%  |
| 5.10    | 51        | 16.72%  |
| 6.1     | 12        | 3.93%   |
| 4.19    | 9         | 2.95%   |
| 5.14    | 8         | 2.62%   |
| 5.18    | 2         | 0.66%   |
| 5.4     | 1         | 0.33%   |
| 5.13    | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 291       | 99.66%  |
| aarch64 | 1         | 0.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| MATE       | 246       | 82%     |
| Cinnamon   | 42        | 14%     |
| X-Cinnamon | 9         | 3%      |
| Unknown    | 3         | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 273       | 91.92%  |
| Wayland | 12        | 4.04%   |
| Tty     | 10        | 3.37%   |
| Unknown | 2         | 0.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 277       | 93.58%  |
| Unknown | 8         | 2.7%    |
| LightDM | 6         | 2.03%   |
| SDDM    | 5         | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 190       | 63.12%  |
| ru_RU   | 109       | 36.21%  |
| en_US   | 2         | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 226       | 76.09%  |
| BIOS | 71        | 23.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 286       | 97.28%  |
| Btrfs   | 5         | 1.7%    |
| Xfs     | 1         | 0.34%   |
| Overlay | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 223       | 75.59%  |
| MBR     | 66        | 22.37%  |
| Unknown | 6         | 2.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 270       | 91.53%  |
| Yes       | 25        | 8.47%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 223       | 75.08%  |
| Yes       | 74        | 24.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 56        | 19.18%  |
| Gigabyte Technology            | 45        | 15.41%  |
| ASUSTek Computer               | 33        | 11.3%   |
| Hewlett-Packard                | 27        | 9.25%   |
| MSI                            | 20        | 6.85%   |
| ASRock                         | 18        | 6.16%   |
| Aquarius                       | 12        | 4.11%   |
| Intel                          | 7         | 2.4%    |
| ICL                            | 7         | 2.4%    |
| DEPO Computers                 | 7         | 2.4%    |
| Dell                           | 6         | 2.05%   |
| Graviton                       | 5         | 1.71%   |
| Acer                           | 5         | 1.71%   |
| Unknown                        | 5         | 1.71%   |
| iRU                            | 4         | 1.37%   |
| HUAWEI                         | 4         | 1.37%   |
| Digma                          | 4         | 1.37%   |
| Kraftway                       | 3         | 1.03%   |
| 3Logic Group                   | 3         | 1.03%   |
| RDW                            | 2         | 0.68%   |
| IP3 Technology                 | 2         | 0.68%   |
| HONOR                          | 2         | 0.68%   |
| Biostar                        | 2         | 0.68%   |
| YADRO                          | 1         | 0.34%   |
| Timi                           | 1         | 0.34%   |
| THUNDEROBOT                    | 1         | 0.34%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.34%   |
| Quanta                         | 1         | 0.34%   |
| Pegatron                       | 1         | 0.34%   |
| NCI                            | 1         | 0.34%   |
| MTR                            | 1         | 0.34%   |
| mtech                          | 1         | 0.34%   |
| Foxconn                        | 1         | 0.34%   |
| ECS                            | 1         | 0.34%   |
| Compal                         | 1         | 0.34%   |
| Colorful Technology            | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                             | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE                              | 17        | 5.82%   |
| Unknown                                          | 6         | 2.05%   |
| Gigabyte B365M DS3H                              | 5         | 1.71%   |
| DEPO Computers DPH310T                           | 4         | 1.37%   |
| MSI MS-7D14                                      | 3         | 1.03%   |
| Lenovo ThinkCentre M70q 11DT003GRU               | 3         | 1.03%   |
| Kraftway ACCORD                                  | 3         | 1.03%   |
| Intel D945GNT AAC96315-405                       | 3         | 1.03%   |
| ICL RAYbook Si1512                               | 3         | 1.03%   |
| HP Laptop 15s-eq1xxx                             | 3         | 1.03%   |
| Graviton M52i                                    | 3         | 1.03%   |
| Gigabyte H110M-S2                                | 3         | 1.03%   |
| ASRock H61M-DGS                                  | 3         | 1.03%   |
| ASRock H510M-HVS R2.0                            | 3         | 1.03%   |
| MSI MS-7D22                                      | 2         | 0.68%   |
| Lenovo ThinkBook 15 G3 ACL 21A4                  | 2         | 0.68%   |
| iRU P2320P                                       | 2         | 0.68%   |
| IP3 ACN30                                        | 2         | 0.68%   |
| HP EliteOne 870 27 inch G9 All-in-One Desktop PC | 2         | 0.68%   |
| Gigabyte B560M DS3H                              | 2         | 0.68%   |
| Gigabyte B550 AORUS ELITE V2                     | 2         | 0.68%   |
| Gigabyte B365M H                                 | 2         | 0.68%   |
| DEPO Computers DPH410S                           | 2         | 0.68%   |
| Biostar H610MH                                   | 2         | 0.68%   |
| ASUS PRIME H510T2/CSM                            | 2         | 0.68%   |
| ASUS PRIME H310M-R R2.0                          | 2         | 0.68%   |
| ASUS PC                                          | 2         | 0.68%   |
| ASUS MINIPC PB62                                 | 2         | 0.68%   |
| ASUS All Series                                  | 2         | 0.68%   |
| Aquarius P30 K44 R53                             | 2         | 0.68%   |
| Aquarius AQB560M                                 | 2         | 0.68%   |
| YADRO VEGMAN S220 Server                         | 1         | 0.34%   |
| Timi Redmi Book Pro 15 2022                      | 1         | 0.34%   |
| THUNDEROBOT 911AirD                              | 1         | 0.34%   |
| Shanghai Zhaoxin ZXE CRB                         | 1         | 0.34%   |
| RDW RDW-MB-B450M V.1                             | 1         | 0.34%   |
| RDW Optimal 23 DG                                | 1         | 0.34%   |
| Quanta 120-1104er                                | 1         | 0.34%   |
| Pegatron A35                                     | 1         | 0.34%   |
| NCI PC BLICK101                                  | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo V15-IWL         | 17        | 5.82%   |
| Lenovo ThinkCentre     | 12        | 4.11%   |
| ASUS PRIME             | 10        | 3.42%   |
| Lenovo IdeaPad         | 8         | 2.74%   |
| Gigabyte B365M         | 7         | 2.4%    |
| Unknown                | 6         | 2.05%   |
| Lenovo ThinkBook       | 5         | 1.71%   |
| Lenovo IdeaCentre      | 5         | 1.71%   |
| HP Laptop              | 5         | 1.71%   |
| Gigabyte B560M         | 5         | 1.71%   |
| Lenovo ThinkPad        | 4         | 1.37%   |
| ICL RAYbook            | 4         | 1.37%   |
| DEPO Computers DPH310T | 4         | 1.37%   |
| Acer Aspire            | 4         | 1.37%   |
| MSI MS-7D14            | 3         | 1.03%   |
| Kraftway ACCORD        | 3         | 1.03%   |
| Intel D945GNT          | 3         | 1.03%   |
| HP ProDesk             | 3         | 1.03%   |
| HP Pavilion            | 3         | 1.03%   |
| Graviton M52i          | 3         | 1.03%   |
| Gigabyte H110M-S2      | 3         | 1.03%   |
| Gigabyte B550          | 3         | 1.03%   |
| Digma EVE              | 3         | 1.03%   |
| ASRock H61M-DGS        | 3         | 1.03%   |
| ASRock H510M-HVS       | 3         | 1.03%   |
| Aquarius Pro           | 3         | 1.03%   |
| MSI MS-7D22            | 2         | 0.68%   |
| MSI Modern             | 2         | 0.68%   |
| iRU P2320P             | 2         | 0.68%   |
| IP3 ACN30              | 2         | 0.68%   |
| HP ProOne              | 2         | 0.68%   |
| HP ProBook             | 2         | 0.68%   |
| HP EliteOne            | 2         | 0.68%   |
| HP Compaq              | 2         | 0.68%   |
| Gigabyte H510M         | 2         | 0.68%   |
| Gigabyte H410M         | 2         | 0.68%   |
| Gigabyte G5            | 2         | 0.68%   |
| Gigabyte B450          | 2         | 0.68%   |
| Gigabyte A320M-S2H     | 2         | 0.68%   |
| DEPO Computers DPH410S | 2         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 66        | 22.6%   |
| 2019 | 50        | 17.12%  |
| 2022 | 44        | 15.07%  |
| 2020 | 37        | 12.67%  |
| 2018 | 19        | 6.51%   |
| 2012 | 14        | 4.79%   |
| 2011 | 10        | 3.42%   |
| 2010 | 10        | 3.42%   |
| 2016 | 8         | 2.74%   |
| 2013 | 7         | 2.4%    |
| 2017 | 5         | 1.71%   |
| 2015 | 5         | 1.71%   |
| 2007 | 5         | 1.71%   |
| 2014 | 4         | 1.37%   |
| 2009 | 3         | 1.03%   |
| 2006 | 3         | 1.03%   |
| 2023 | 1         | 0.34%   |
| 2008 | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 149       | 51.03%  |
| Notebook       | 100       | 34.25%  |
| All in one     | 25        | 8.56%   |
| Mini pc        | 13        | 4.45%   |
| Server         | 3         | 1.03%   |
| System on chip | 1         | 0.34%   |
| Tablet         | 1         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 291       | 99.66%  |
| Enabled  | 1         | 0.34%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 292       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 134       | 45.89%  |
| 16.01-24.0      | 64        | 21.92%  |
| 3.01-4.0        | 37        | 12.67%  |
| 8.01-16.0       | 31        | 10.62%  |
| 32.01-64.0      | 8         | 2.74%   |
| 1.01-2.0        | 6         | 2.05%   |
| 2.01-3.0        | 5         | 1.71%   |
| More than 256.0 | 2         | 0.68%   |
| 24.01-32.0      | 2         | 0.68%   |
| 64.01-256.0     | 1         | 0.34%   |
| 0.51-1.0        | 1         | 0.34%   |
| Unknown         | 1         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 161       | 51.94%  |
| 2.01-3.0    | 58        | 18.71%  |
| 0.51-1.0    | 33        | 10.65%  |
| 3.01-4.0    | 25        | 8.06%   |
| 4.01-8.0    | 22        | 7.1%    |
| 8.01-16.0   | 7         | 2.26%   |
| 0.01-0.5    | 2         | 0.65%   |
| 64.01-256.0 | 1         | 0.32%   |
| Unknown     | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 221       | 73.42%  |
| 2      | 58        | 19.27%  |
| 3      | 11        | 3.65%   |
| 4      | 6         | 1.99%   |
| 12     | 1         | 0.33%   |
| 11     | 1         | 0.33%   |
| 7      | 1         | 0.33%   |
| 5      | 1         | 0.33%   |
| 0      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 215       | 73.13%  |
| Yes       | 79        | 26.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 257       | 88.01%  |
| No        | 35        | 11.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 172       | 58.31%  |
| No        | 123       | 41.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 150       | 51.02%  |
| Yes       | 144       | 48.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 291       | 99.66%  |
| Ukraine | 1         | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 63        | 20.86%  |
| Salekhard         | 45        | 14.9%   |
| Murom             | 41        | 13.58%  |
| Yekaterinburg     | 11        | 3.64%   |
| Perm              | 9         | 2.98%   |
| St Petersburg     | 8         | 2.65%   |
| Novy Urengoy      | 8         | 2.65%   |
| Krasnodar         | 6         | 1.99%   |
| Zima              | 5         | 1.66%   |
| Yuzhno-Sakhalinsk | 5         | 1.66%   |
| Volgograd         | 4         | 1.32%   |
| Ryazan            | 4         | 1.32%   |
| Novosibirsk       | 4         | 1.32%   |
| Labytnangi        | 4         | 1.32%   |
| Khabarovsk        | 4         | 1.32%   |
| Balashikha        | 4         | 1.32%   |
| Vladimir          | 3         | 0.99%   |
| Veliky Novgorod   | 3         | 0.99%   |
| Shakhtersk        | 3         | 0.99%   |
| Nizhniy Novgorod  | 3         | 0.99%   |
| Nal'chik          | 3         | 0.99%   |
| Muromskiy         | 3         | 0.99%   |
| Kursk             | 3         | 0.99%   |
| Kaluga            | 3         | 0.99%   |
| Yakutsk           | 2         | 0.66%   |
| Ulyanovsk         | 2         | 0.66%   |
| Tomsk             | 2         | 0.66%   |
| Stavropol         | 2         | 0.66%   |
| Pushkino          | 2         | 0.66%   |
| Penza             | 2         | 0.66%   |
| Kurgan            | 2         | 0.66%   |
| Krasnoyarsk       | 2         | 0.66%   |
| Bryansk           | 2         | 0.66%   |
| Baksan            | 2         | 0.66%   |
| Yaroslavl         | 1         | 0.33%   |
| Voronezh          | 1         | 0.33%   |
| Volzhskiy         | 1         | 0.33%   |
| Tyumen            | 1         | 0.33%   |
| Tver              | 1         | 0.33%   |
| Svetlograd        | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 58        | 78     | 15.34%  |
| WDC                          | 52        | 63     | 13.76%  |
| Samsung Electronics          | 45        | 68     | 11.9%   |
| Toshiba                      | 28        | 47     | 7.41%   |
| A-DATA Technology            | 22        | 23     | 5.82%   |
| Kingston                     | 20        | 21     | 5.29%   |
| SK hynix                     | 15        | 19     | 3.97%   |
| Foxline                      | 12        | 12     | 3.17%   |
| Apacer                       | 10        | 11     | 2.65%   |
| SanDisk                      | 7         | 10     | 1.85%   |
| Intel                        | 7         | 13     | 1.85%   |
| Crucial                      | 6         | 9      | 1.59%   |
| Unknown                      | 6         | 7      | 1.59%   |
| Unknown                      | 5         | 5      | 1.32%   |
| UMIS                         | 5         | 5      | 1.32%   |
| Silicon Motion               | 5         | 5      | 1.32%   |
| Patriot                      | 5         | 5      | 1.32%   |
| KingSpec                     | 5         | 5      | 1.32%   |
| Hitachi                      | 5         | 5      | 1.32%   |
| China                        | 5         | 6      | 1.32%   |
| AGI                          | 5         | 5      | 1.32%   |
| Transcend                    | 4         | 4      | 1.06%   |
| Phison                       | 4         | 4      | 1.06%   |
| Micron Technology            | 4         | 8      | 1.06%   |
| HGST                         | 4         | 4      | 1.06%   |
| AMD                          | 4         | 4      | 1.06%   |
| Gigabyte Technology          | 3         | 3      | 0.79%   |
| ExeGate                      | 3         | 4      | 0.79%   |
| Qumo                         | 2         | 2      | 0.53%   |
| Netac                        | 2         | 2      | 0.53%   |
| KIOXIA-EXCERIA               | 2         | 2      | 0.53%   |
| YMTC                         | 1         | 1      | 0.26%   |
| XPG                          | 1         | 1      | 0.26%   |
| SPCC Sol                     | 1         | 1      | 0.26%   |
| SPCC                         | 1         | 1      | 0.26%   |
| Smartbuy                     | 1         | 1      | 0.26%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.26%   |
| Plextor                      | 1         | 1      | 0.26%   |
| LIO-ORG                      | 1         | 1      | 0.26%   |
| Lenovo                       | 1         | 16     | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB       | 18        | 4.6%    |
| Toshiba HDWD110 1TB                    | 10        | 2.56%   |
| Seagate ST500DM002-1BD142 500GB        | 9         | 2.3%    |
| Kingston SA400S37240G 240GB SSD        | 8         | 2.05%   |
| Seagate ST1000DM010-2EP102 1TB         | 7         | 1.79%   |
| Seagate ST1000LM049-2GH172 1TB         | 6         | 1.53%   |
| Foxline FLSSD256M80E13TCX5 256GB       | 6         | 1.53%   |
| Unknown                                | 6         | 1.53%   |
| Apacer AS2280P4 256GB                  | 5         | 1.28%   |
| AGI AGI512G16AI198 512GB               | 5         | 1.28%   |
| Toshiba DT01ACA100 1TB                 | 4         | 1.02%   |
| Silicon Motion Wodposit NVMe SSD 256GB | 4         | 1.02%   |
| Seagate ST3160811AS 160GB              | 4         | 1.02%   |
| Crucial CT240BX500SSD1 240GB           | 4         | 1.02%   |
| A-DATA SX6000PNP 256GB                 | 4         | 1.02%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 3         | 0.77%   |
| UMIS RPIRJ256VME2MWD 256GB             | 3         | 0.77%   |
| SK hynix HFM128GDHTNG-8310B 128GB      | 3         | 0.77%   |
| Seagate ST1000DM010-2DM162 1TB         | 3         | 0.77%   |
| SanDisk SD8SBAT256G1122 256GB SSD      | 3         | 0.77%   |
| Samsung SSD 860 EVO 250GB              | 3         | 0.77%   |
| Kingston SA400S37120G 120GB SSD        | 3         | 0.77%   |
| A-DATA SU800 256GB SSD                 | 3         | 0.77%   |
| A-DATA SU650 240GB SSD                 | 3         | 0.77%   |
| WDC WD5000AAKX-60U6AA0 500GB           | 2         | 0.51%   |
| WDC WD10SPZX-00Z10T0 1TB               | 2         | 0.51%   |
| WDC WD10EZEX-22MFCA0 1TB               | 2         | 0.51%   |
| WDC WD10EZEX-00BBHA0 1TB               | 2         | 0.51%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB   | 2         | 0.51%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.51%   |
| Toshiba MK5075GSX 500GB                | 2         | 0.51%   |
| Toshiba HDWD105 500GB                  | 2         | 0.51%   |
| Toshiba DT01ACA050 500GB               | 2         | 0.51%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB | 2         | 0.51%   |
| SK hynix PC711 HFS512GDE9X073N 512GB   | 2         | 0.51%   |
| Seagate ST500LM0 30-2E717D 500GB       | 2         | 0.51%   |
| Seagate ST3500413AS 500GB              | 2         | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB         | 2         | 0.51%   |
| Seagate ST1000DM003-1SB10C 1TB         | 2         | 0.51%   |
| Samsung SSD 980 PRO 2TB                | 2         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 77     | 42.86%  |
| WDC                 | 36        | 45     | 27.07%  |
| Toshiba             | 24        | 42     | 18.05%  |
| Hitachi             | 5         | 5      | 3.76%   |
| HGST                | 4         | 4      | 3.01%   |
| Samsung Electronics | 3         | 4      | 2.26%   |
| Unknown             | 1         | 1      | 0.75%   |
| LIO-ORG             | 1         | 1      | 0.75%   |
| Lenovo              | 1         | 16     | 0.75%   |
| JMicron Technology  | 1         | 1      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 15        | 15     | 14.02%  |
| A-DATA Technology   | 12        | 12     | 11.21%  |
| WDC                 | 8         | 8      | 7.48%   |
| Samsung Electronics | 8         | 16     | 7.48%   |
| Foxline             | 6         | 6      | 5.61%   |
| SanDisk             | 5         | 8      | 4.67%   |
| KingSpec            | 5         | 5      | 4.67%   |
| Crucial             | 5         | 8      | 4.67%   |
| China               | 5         | 6      | 4.67%   |
| Apacer              | 5         | 6      | 4.67%   |
| Transcend           | 4         | 4      | 3.74%   |
| Patriot             | 4         | 4      | 3.74%   |
| Intel               | 4         | 10     | 3.74%   |
| ExeGate             | 3         | 4      | 2.8%    |
| Qumo                | 2         | 2      | 1.87%   |
| KIOXIA-EXCERIA      | 2         | 2      | 1.87%   |
| AMD                 | 2         | 2      | 1.87%   |
| Unknown             | 2         | 2      | 1.87%   |
| Toshiba             | 1         | 1      | 0.93%   |
| SPCC Sol            | 1         | 1      | 0.93%   |
| Smartbuy            | 1         | 1      | 0.93%   |
| Seagate             | 1         | 1      | 0.93%   |
| Plextor             | 1         | 1      | 0.93%   |
| Netac               | 1         | 1      | 0.93%   |
| Micron Technology   | 1         | 1      | 0.93%   |
| GOODRAM             | 1         | 1      | 0.93%   |
| Digma               | 1         | 1      | 0.93%   |
| Dahua               | 1         | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 127       | 156    | 35.47%  |
| HDD     | 120       | 196    | 33.52%  |
| SSD     | 102       | 130    | 28.49%  |
| MMC     | 7         | 9      | 1.96%   |
| Unknown | 2         | 2      | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 186       | 319    | 56.88%  |
| NVMe | 127       | 156    | 38.84%  |
| SAS  | 7         | 9      | 2.14%   |
| MMC  | 7         | 9      | 2.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 133       | 177    | 59.64%  |
| 0.51-1.0   | 76        | 109    | 34.08%  |
| 1.01-2.0   | 8         | 26     | 3.59%   |
| 3.01-4.0   | 4         | 8      | 1.79%   |
| 2.01-3.0   | 1         | 1      | 0.45%   |
| 4.01-10.0  | 1         | 5      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 129       | 42.72%  |
| 251-500        | 68        | 22.52%  |
| 501-1000       | 51        | 16.89%  |
| 1001-2000      | 23        | 7.62%   |
| 51-100         | 14        | 4.64%   |
| 21-50          | 6         | 1.99%   |
| 2001-3000      | 5         | 1.66%   |
| 1-20           | 3         | 0.99%   |
| More than 3000 | 2         | 0.66%   |
| Unknown        | 1         | 0.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 189       | 60.97%  |
| 21-50          | 54        | 17.42%  |
| 101-250        | 20        | 6.45%   |
| 51-100         | 17        | 5.48%   |
| 501-1000       | 12        | 3.87%   |
| 251-500        | 9         | 2.9%    |
| 1001-2000      | 5         | 1.61%   |
| More than 3000 | 2         | 0.65%   |
| 2001-3000      | 1         | 0.32%   |
| Unknown        | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 6         | 7      | 14.63%  |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 2      | 4.88%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 2         | 2      | 4.88%   |
| Seagate ST3500413AS 500GB           | 2         | 2      | 4.88%   |
| Seagate ST3160811AS 160GB           | 2         | 2      | 4.88%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 6      | 4.88%   |
| WDC WD5000AAKS-00V1A0 500GB         | 1         | 2      | 2.44%   |
| WDC WD5000AAKS-00D2B0 500GB         | 1         | 1      | 2.44%   |
| WDC WD3200AAKX-001CA0 320GB         | 1         | 1      | 2.44%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 2.44%   |
| WDC WD10EZEX-75ZF5A0 1TB            | 1         | 2      | 2.44%   |
| WDC WD10EZEX-00WN4A0 1TB            | 1         | 1      | 2.44%   |
| WDC WD10EARS-00Y5B1 1TB             | 1         | 1      | 2.44%   |
| Toshiba MQ01ABF050 500GB            | 1         | 9      | 2.44%   |
| Toshiba MK5075GSX 500GB             | 1         | 3      | 2.44%   |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 2.44%   |
| SPCC M.2 PCIe SSD 512GB             | 1         | 1      | 2.44%   |
| Seagate ST9500423AS 500GB           | 1         | 1      | 2.44%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 2.44%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 2.44%   |
| Seagate ST3250823AS 250GB           | 1         | 1      | 2.44%   |
| Seagate ST3250318AS 250GB           | 1         | 2      | 2.44%   |
| Seagate ST31000524NS 1TB            | 1         | 1      | 2.44%   |
| Samsung Electronics HD400LJ 400GB   | 1         | 1      | 2.44%   |
| Kingston SUV400S37120G 120GB SSD    | 1         | 1      | 2.44%   |
| Kingston SHPM2280P2H 240G SSD       | 1         | 1      | 2.44%   |
| Hitachi HTS543216L9A300 160GB       | 1         | 1      | 2.44%   |
| Hitachi HDS5C1050CLA382 500GB       | 1         | 1      | 2.44%   |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 2.44%   |
| A-DATA Technology SU800 256GB SSD   | 1         | 1      | 2.44%   |
| Unknown                             | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 24     | 45%     |
| WDC                 | 11        | 13     | 27.5%   |
| Toshiba             | 2         | 13     | 5%      |
| Kingston            | 2         | 2      | 5%      |
| Hitachi             | 2         | 2      | 5%      |
| SPCC                | 1         | 1      | 2.5%    |
| Samsung Electronics | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 1      | 2.5%    |
| Unknown             | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 24     | 54.55%  |
| WDC                 | 9         | 11     | 27.27%  |
| Toshiba             | 2         | 13     | 6.06%   |
| Hitachi             | 2         | 2      | 6.06%   |
| Samsung Electronics | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 52     | 82.86%  |
| SSD  | 5         | 6      | 14.29%  |
| NVMe | 1         | 1      | 2.86%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 260       | 405    | 83.07%  |
| Malfunc  | 35        | 59     | 11.18%  |
| Detected | 18        | 29     | 5.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 228       | 56.72%  |
| AMD                          | 37        | 9.2%    |
| Samsung Electronics          | 35        | 8.71%   |
| Phison Electronics           | 19        | 4.73%   |
| SK hynix                     | 15        | 3.73%   |
| Silicon Motion               | 12        | 2.99%   |
| SanDisk                      | 10        | 2.49%   |
| Realtek Semiconductor        | 8         | 1.99%   |
| Kingston Technology Company  | 6         | 1.49%   |
| Union Memory (Shenzhen)      | 5         | 1.24%   |
| ADATA Technology             | 4         | 1%      |
| Toshiba America Info Systems | 3         | 0.75%   |
| Nvidia                       | 3         | 0.75%   |
| Micron Technology            | 3         | 0.75%   |
| ShenZhen TIGO Semiconductor  | 2         | 0.5%    |
| LSI Logic / Symbios Logic    | 2         | 0.5%    |
| JMicron Technology           | 2         | 0.5%    |
| Zhaoxin                      | 1         | 0.25%   |
| Yangtze Memory Technologies  | 1         | 0.25%   |
| VIA Technologies             | 1         | 0.25%   |
| Shenzhen Longsys Electronics | 1         | 0.25%   |
| Netac Technology             | 1         | 0.25%   |
| Micron/Crucial Technology    | 1         | 0.25%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.25%   |
| KIOXIA                       | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 36        | 8.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 30        | 6.76%   |
| Samsung NVMe SSD Controller 980                                                | 28        | 6.31%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 22        | 4.95%   |
| Phison PS5013 E13 NVMe Controller                                              | 16        | 3.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 16        | 3.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 14        | 3.15%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 13        | 2.93%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 12        | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 11        | 2.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10        | 2.25%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 8         | 1.8%    |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 1.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 8         | 1.8%    |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 1.8%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 1.8%    |
| AMD 500 Series Chipset SATA Controller                                         | 8         | 1.8%    |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 1.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 1.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 1.58%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 1.58%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 5         | 1.13%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 0.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 0.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 0.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 0.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 0.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 0.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 0.9%    |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 256GB                          | 3         | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.68%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 0.68%   |
| Nvidia MCP61 SATA Controller                                                   | 3         | 0.68%   |
| Nvidia MCP61 IDE                                                               | 3         | 0.68%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 0.68%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 238       | 58.62%  |
| NVMe | 127       | 31.28%  |
| IDE  | 25        | 6.16%   |
| RAID | 15        | 3.69%   |
| SAS  | 1         | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 238       | 81.51%  |
| AMD          | 52        | 17.81%  |
| CentaurHauls | 1         | 0.34%   |
| ARM          | 1         | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 6.16%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 15        | 5.14%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 13        | 4.45%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 7         | 2.4%    |
| Intel Core i3-10105 CPU @ 3.70GHz             | 7         | 2.4%    |
| Intel Core i5-8279U CPU @ 2.40GHz             | 6         | 2.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 2.05%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 5         | 1.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 5         | 1.71%   |
| Intel 12th Gen Core i3-12100                  | 5         | 1.71%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 1.37%   |
| Intel 12th Gen Core i5-12400                  | 4         | 1.37%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 4         | 1.37%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.37%   |
| Intel Pentium CPU G4500 @ 3.50GHz             | 3         | 1.03%   |
| Intel Pentium 4 CPU 3.06GHz                   | 3         | 1.03%   |
| Intel Core i5-8400T CPU @ 1.70GHz             | 3         | 1.03%   |
| Intel Core i5-10500 CPU @ 3.10GHz             | 3         | 1.03%   |
| Intel Core i3-8100T CPU @ 3.10GHz             | 3         | 1.03%   |
| Intel Core i3-10100T CPU @ 3.00GHz            | 3         | 1.03%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 3         | 1.03%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 1.03%   |
| Intel 12th Gen Core i5-1235U                  | 3         | 1.03%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics    | 3         | 1.03%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.03%   |
| AMD Ryzen 3 5400U with Radeon Graphics        | 3         | 1.03%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 3         | 1.03%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 3         | 1.03%   |
| Intel Pentium Gold G7400                      | 2         | 0.68%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz        | 2         | 0.68%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 2         | 0.68%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 2         | 0.68%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 2         | 0.68%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2         | 0.68%   |
| Intel Core i5-10400T CPU @ 2.00GHz            | 2         | 0.68%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.68%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.68%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 2         | 0.68%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2         | 0.68%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 95        | 32.53%  |
| Intel Core i3      | 48        | 16.44%  |
| Other              | 43        | 14.73%  |
| AMD Ryzen 5        | 17        | 5.82%   |
| Intel Celeron      | 15        | 5.14%   |
| AMD Ryzen 3        | 13        | 4.45%   |
| Intel Pentium      | 9         | 3.08%   |
| Intel Core i7      | 9         | 3.08%   |
| Intel Pentium Gold | 7         | 2.4%    |
| Intel Core 2 Duo   | 5         | 1.71%   |
| AMD Ryzen 7        | 5         | 1.71%   |
| Intel Pentium 4    | 3         | 1.03%   |
| AMD Ryzen 5 PRO    | 3         | 1.03%   |
| AMD FX             | 3         | 1.03%   |
| AMD Ryzen 7 PRO    | 2         | 0.68%   |
| AMD Phenom II      | 2         | 0.68%   |
| AMD Athlon II X2   | 2         | 0.68%   |
| Intel Xeon Silver  | 1         | 0.34%   |
| Intel Xeon Gold    | 1         | 0.34%   |
| Intel Xeon Bronze  | 1         | 0.34%   |
| Intel Xeon         | 1         | 0.34%   |
| Intel Pentium Dual | 1         | 0.34%   |
| Intel Core 2       | 1         | 0.34%   |
| AMD Ryzen 9        | 1         | 0.34%   |
| AMD Ryzen 3 PRO    | 1         | 0.34%   |
| AMD Phenom         | 1         | 0.34%   |
| AMD Athlon         | 1         | 0.34%   |
| AMD A4             | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 136       | 46.58%  |
| 2      | 63        | 21.58%  |
| 6      | 61        | 20.89%  |
| 8      | 13        | 4.45%   |
| 12     | 6         | 2.05%   |
| 1      | 4         | 1.37%   |
| 10     | 3         | 1.03%   |
| 3      | 2         | 0.68%   |
| 36     | 1         | 0.34%   |
| 24     | 1         | 0.34%   |
| 16     | 1         | 0.34%   |
| 14     | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 289       | 98.97%  |
| 2      | 3         | 1.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 194       | 66.44%  |
| 1      | 98        | 33.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 291       | 99.66%  |
| Unknown        | 1         | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0xa0653    | 42        | 14.29%  |
| 0x806ec    | 22        | 7.48%   |
| 0x906ea    | 16        | 5.44%   |
| 0x90675    | 13        | 4.42%   |
| 0x806ea    | 12        | 4.08%   |
| 0x806c1    | 12        | 4.08%   |
| 0x306a9    | 12        | 4.08%   |
| 0x206a7    | 11        | 3.74%   |
| 0x906ed    | 10        | 3.4%    |
| 0x506e3    | 10        | 3.4%    |
| 0x08600106 | 10        | 3.4%    |
| 0x306c3    | 8         | 2.72%   |
| 0x0a50000c | 7         | 2.38%   |
| 0x08108109 | 7         | 2.38%   |
| 0x906eb    | 6         | 2.04%   |
| 0xa0671    | 5         | 1.7%    |
| Unknown    | 5         | 1.7%    |
| 0x906e9    | 4         | 1.36%   |
| 0x906a4    | 4         | 1.36%   |
| 0x906a3    | 4         | 1.36%   |
| 0x08608103 | 4         | 1.36%   |
| 0xf49      | 3         | 1.02%   |
| 0xa0655    | 3         | 1.02%   |
| 0x90672    | 3         | 1.02%   |
| 0x706a8    | 3         | 1.02%   |
| 0x50657    | 3         | 1.02%   |
| 0x1067a    | 3         | 1.02%   |
| 0x0a50000d | 3         | 1.02%   |
| 0x010000c8 | 3         | 1.02%   |
| 0x806d1    | 2         | 0.68%   |
| 0x706e5    | 2         | 0.68%   |
| 0x6fd      | 2         | 0.68%   |
| 0x506ca    | 2         | 0.68%   |
| 0x506c9    | 2         | 0.68%   |
| 0x406e3    | 2         | 0.68%   |
| 0x406c4    | 2         | 0.68%   |
| 0x40651    | 2         | 0.68%   |
| 0x20652    | 2         | 0.68%   |
| 0x08108102 | 2         | 0.68%   |
| 0x08101016 | 2         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 72        | 24.66%  |
| CometLake        | 46        | 15.75%  |
| Alderlake Hybrid | 23        | 7.88%   |
| Skylake          | 15        | 5.14%   |
| Zen 3            | 12        | 4.11%   |
| Zen 2            | 12        | 4.11%   |
| TigerLake        | 12        | 4.11%   |
| IvyBridge        | 12        | 4.11%   |
| SandyBridge      | 11        | 3.77%   |
| Unknown          | 11        | 3.77%   |
| Zen+             | 10        | 3.42%   |
| Haswell          | 10        | 3.42%   |
| Icelake          | 6         | 2.05%   |
| K10              | 5         | 1.71%   |
| Core             | 5         | 1.71%   |
| Zen              | 4         | 1.37%   |
| Westmere         | 4         | 1.37%   |
| Goldmont plus    | 4         | 1.37%   |
| Goldmont         | 4         | 1.37%   |
| Penryn           | 3         | 1.03%   |
| NetBurst         | 3         | 1.03%   |
| Silvermont       | 2         | 0.68%   |
| Nehalem          | 2         | 0.68%   |
| Bulldozer        | 2         | 0.68%   |
| Piledriver       | 1         | 0.34%   |
| Excavator        | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 212       | 66.25%  |
| AMD               | 57        | 17.81%  |
| Nvidia            | 47        | 14.69%  |
| ASPEED Technology | 3         | 0.94%   |
| Zhaoxin           | 1         | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 39        | 12.04%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 25        | 7.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 6.17%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 11        | 3.4%    |
| AMD Renoir                                                                               | 11        | 3.4%    |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 9         | 2.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 2.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 2.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.16%   |
| Intel HD Graphics 530                                                                    | 7         | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.85%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 5         | 1.54%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.23%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 1.23%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4         | 1.23%   |
| AMD Lucienne                                                                             | 4         | 1.23%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.93%   |
| Intel HD Graphics 630                                                                    | 3         | 0.93%   |
| Intel HD Graphics 500                                                                    | 3         | 0.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.93%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                                 | 3         | 0.93%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 3         | 0.93%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 3         | 0.93%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 0.93%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3         | 0.93%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.93%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 3         | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.62%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.62%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 2         | 0.62%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.62%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 2         | 0.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.62%   |
| Intel AlderLake-S GT1                                                                    | 2         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 185       | 63.36%  |
| 1 x AMD        | 47        | 16.1%   |
| 1 x Nvidia     | 26        | 8.9%    |
| Intel + Nvidia | 19        | 6.51%   |
| Intel + AMD    | 5         | 1.71%   |
| 2 x AMD        | 3         | 1.03%   |
| 1 x ASPEED     | 3         | 1.03%   |
| AMD + Nvidia   | 2         | 0.68%   |
| Other          | 1         | 0.34%   |
| 1 x Zhaoxin    | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 239       | 81.02%  |
| Unknown     | 46        | 15.59%  |
| Proprietary | 10        | 3.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 208       | 70.51%  |
| 1.01-2.0   | 34        | 11.53%  |
| 0.01-0.5   | 24        | 8.14%   |
| 0.51-1.0   | 18        | 6.1%    |
| 3.01-4.0   | 8         | 2.71%   |
| 7.01-8.0   | 2         | 0.68%   |
| 2.01-3.0   | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 46        | 17.04%  |
| Samsung Electronics  | 32        | 11.85%  |
| Philips              | 26        | 9.63%   |
| Acer                 | 20        | 7.41%   |
| ViewSonic            | 14        | 5.19%   |
| LG Display           | 14        | 5.19%   |
| Lenovo               | 13        | 4.81%   |
| Hewlett-Packard      | 11        | 4.07%   |
| Chimei Innolux       | 10        | 3.7%    |
| BenQ                 | 9         | 3.33%   |
| AU Optronics         | 9         | 3.33%   |
| AOC                  | 9         | 3.33%   |
| Goldstar             | 7         | 2.59%   |
| Dell                 | 6         | 2.22%   |
| ASUSTek Computer     | 6         | 2.22%   |
| PANDA                | 5         | 1.85%   |
| SGT                  | 4         | 1.48%   |
| Ancor Communications | 3         | 1.11%   |
| SKM                  | 2         | 0.74%   |
| NLE                  | 2         | 0.74%   |
| Iiyama               | 2         | 0.74%   |
| HUAWEI               | 2         | 0.74%   |
| XSP                  | 1         | 0.37%   |
| WYT                  | 1         | 0.37%   |
| Toshiba              | 1         | 0.37%   |
| TMX                  | 1         | 0.37%   |
| Sony                 | 1         | 0.37%   |
| RGT                  | 1         | 0.37%   |
| OOO                  | 1         | 0.37%   |
| NEC Computers        | 1         | 0.37%   |
| MSI                  | 1         | 0.37%   |
| Mi                   | 1         | 0.37%   |
| JRY                  | 1         | 0.37%   |
| ITE                  | 1         | 0.37%   |
| IPS                  | 1         | 0.37%   |
| DOY                  | 1         | 0.37%   |
| Daewoo               | 1         | 0.37%   |
| CHR                  | 1         | 0.37%   |
| CHD                  | 1         | 0.37%   |
| Unknown              | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 17        | 6.12%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 11        | 3.96%   |
| BOE LCD Monitor BOE09C5 1920x1080 345x194mm 15.6-inch                | 9         | 3.24%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch            | 5         | 1.8%    |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                      | 4         | 1.44%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 4         | 1.44%   |
| Lenovo TIO22Gen4 LEN111A 1920x1080 476x268mm 21.5-inch               | 4         | 1.44%   |
| Acer SA240Y ACR057F 1920x1080 527x296mm 23.8-inch                    | 4         | 1.44%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch              | 3         | 1.08%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch         | 3         | 1.08%   |
| Lenovo LEN-510A-B LEN1201 1920x1080 509x286mm 23.0-inch              | 3         | 1.08%   |
| Goldstar E2042 GSM4ED7 1600x900 443x249mm 20.0-inch                  | 3         | 1.08%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch     | 3         | 1.08%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 3         | 1.08%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 3         | 1.08%   |
| AU Optronics LCD Monitor AUO0100 1920x1080                           | 3         | 1.08%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch        | 2         | 0.72%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch        | 2         | 0.72%   |
| SKM LCD Monitor SKM9322 1920x1080 527x296mm 23.8-inch                | 2         | 0.72%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch | 2         | 0.72%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch    | 2         | 0.72%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch     | 2         | 0.72%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 600x340mm 27.2-inch    | 2         | 0.72%   |
| NLE Newline NLE0032 3840x2160 944x398mm 40.3-inch                    | 2         | 0.72%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.72%   |
| BOE LCD Monitor BOE0936 1920x1080 344x194mm 15.5-inch                | 2         | 0.72%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                | 2         | 0.72%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 2         | 0.72%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                    | 2         | 0.72%   |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                     | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.72%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 2         | 0.72%   |
| Acer V243HQ ACR00B0 1920x1080 521x293mm 23.5-inch                    | 2         | 0.72%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                   | 2         | 0.72%   |
| XSP Digital XSP2380 1920x1080 520x310mm 23.8-inch                    | 1         | 0.36%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                 | 1         | 0.36%   |
| ViewSonic VX510 VSC6419 1024x768 304x228mm 15.0-inch                 | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 177       | 69.96%  |
| 1280x1024 (SXGA)   | 17        | 6.72%   |
| 1366x768 (WXGA)    | 15        | 5.93%   |
| 2560x1440 (QHD)    | 11        | 4.35%   |
| 1600x900 (HD+)     | 11        | 4.35%   |
| 3840x2160 (4K)     | 6         | 2.37%   |
| 1920x1200 (WUXGA)  | 4         | 1.58%   |
| 3440x1440          | 3         | 1.19%   |
| 3200x2000          | 1         | 0.4%    |
| 2560x1080          | 1         | 0.4%    |
| 2240x1400          | 1         | 0.4%    |
| 1680x1050 (WSXGA+) | 1         | 0.4%    |
| 1600x1200          | 1         | 0.4%    |
| 1440x900 (WXGA+)   | 1         | 0.4%    |
| 1280x960           | 1         | 0.4%    |
| 1280x800 (WXGA)    | 1         | 0.4%    |
| 1024x768 (XGA)     | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 72        | 26.67%  |
| 24      | 41        | 15.19%  |
| 23      | 41        | 15.19%  |
| 21      | 26        | 9.63%   |
| 27      | 18        | 6.67%   |
| 20      | 11        | 4.07%   |
| 19      | 11        | 4.07%   |
| 17      | 9         | 3.33%   |
| 14      | 6         | 2.22%   |
| 13      | 6         | 2.22%   |
| 31      | 4         | 1.48%   |
| Unknown | 4         | 1.48%   |
| 34      | 3         | 1.11%   |
| 18      | 3         | 1.11%   |
| 84      | 2         | 0.74%   |
| 40      | 2         | 0.74%   |
| 25      | 2         | 0.74%   |
| 22      | 2         | 0.74%   |
| 12      | 2         | 0.74%   |
| 54      | 1         | 0.37%   |
| 32      | 1         | 0.37%   |
| 26      | 1         | 0.37%   |
| 16      | 1         | 0.37%   |
| 11      | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 97        | 37.02%  |
| 301-350     | 90        | 34.35%  |
| 401-500     | 40        | 15.27%  |
| 351-400     | 14        | 5.34%   |
| 701-800     | 4         | 1.53%   |
| 601-700     | 4         | 1.53%   |
| 201-300     | 4         | 1.53%   |
| Unknown     | 4         | 1.53%   |
| 1501-2000   | 2         | 0.76%   |
| 901-1000    | 2         | 0.76%   |
| 1001-1500   | 1         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 212       | 85.14%  |
| 5/4   | 17        | 6.83%   |
| 16/10 | 12        | 4.82%   |
| 21/9  | 5         | 2.01%   |
| 4/3   | 2         | 0.8%    |
| 6/5   | 1         | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 87        | 32.95%  |
| 101-110        | 72        | 27.27%  |
| 151-200        | 32        | 12.12%  |
| 301-350        | 19        | 7.2%    |
| 81-90          | 11        | 4.17%   |
| 251-300        | 10        | 3.79%   |
| 351-500        | 8         | 3.03%   |
| 141-150        | 8         | 3.03%   |
| Unknown        | 4         | 1.52%   |
| More than 1000 | 3         | 1.14%   |
| 121-130        | 3         | 1.14%   |
| 61-70          | 2         | 0.76%   |
| 501-1000       | 2         | 0.76%   |
| 71-80          | 1         | 0.38%   |
| 51-60          | 1         | 0.38%   |
| 131-140        | 1         | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 122       | 47.84%  |
| 121-160       | 72        | 28.24%  |
| 101-120       | 51        | 20%     |
| 161-240       | 4         | 1.57%   |
| Unknown       | 4         | 1.57%   |
| More than 240 | 1         | 0.39%   |
| 1-50          | 1         | 0.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 220       | 73.33%  |
| 0     | 52        | 17.33%  |
| 2     | 27        | 9%      |
| 3     | 1         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 197       | 51.3%   |
| Intel                    | 119       | 30.99%  |
| Qualcomm Atheros         | 13        | 3.39%   |
| Broadcom                 | 11        | 2.86%   |
| Xiaomi                   | 5         | 1.3%    |
| TP-Link                  | 5         | 1.3%    |
| MediaTek                 | 5         | 1.3%    |
| Samsung Electronics      | 4         | 1.04%   |
| Ralink Technology        | 3         | 0.78%   |
| Ralink                   | 3         | 0.78%   |
| Nvidia                   | 3         | 0.78%   |
| Huawei Technologies      | 3         | 0.78%   |
| Mercucys                 | 2         | 0.52%   |
| VIA Technologies         | 1         | 0.26%   |
| Qualcomm                 | 1         | 0.26%   |
| OPPO Electronics         | 1         | 0.26%   |
| OKB SAPR                 | 1         | 0.26%   |
| Metrologic Instruments   | 1         | 0.26%   |
| Mellanox Technologies    | 1         | 0.26%   |
| Marvell Technology Group | 1         | 0.26%   |
| Edimax Technology        | 1         | 0.26%   |
| Broadcom Limited         | 1         | 0.26%   |
| ASIX Electronics         | 1         | 0.26%   |
| American Megatrends      | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 143       | 30.89%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 34        | 7.34%   |
| Intel Wireless 7265                                               | 14        | 3.02%   |
| Intel Ethernet Controller I225-V                                  | 11        | 2.38%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 1.94%   |
| Intel Ethernet Connection (14) I219-V                             | 9         | 1.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 8         | 1.73%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 1.73%   |
| Intel Ethernet Connection (17) I219-V                             | 8         | 1.73%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 8         | 1.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 1.51%   |
| Intel Wireless 3165                                               | 7         | 1.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.08%   |
| Intel Ethernet Connection (11) I219-V                             | 5         | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 1.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 5         | 1.08%   |
| Intel NM10/ICH7 Family LAN Controller                             | 4         | 0.86%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 0.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 0.86%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 3         | 0.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.65%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3         | 0.65%   |
| Realtek 802.11ac NIC                                              | 3         | 0.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.65%   |
| Nvidia MCP61 Ethernet                                             | 3         | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.65%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.65%   |
| Intel Ethernet Connection (17) I219-LM                            | 3         | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.65%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2         | 0.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 75        | 42.13%  |
| Realtek Semiconductor | 69        | 38.76%  |
| Broadcom              | 9         | 5.06%   |
| Qualcomm Atheros      | 7         | 3.93%   |
| TP-Link               | 4         | 2.25%   |
| Ralink Technology     | 3         | 1.69%   |
| Ralink                | 3         | 1.69%   |
| MediaTek              | 3         | 1.69%   |
| Mercucys              | 2         | 1.12%   |
| Qualcomm              | 1         | 0.56%   |
| Edimax Technology     | 1         | 0.56%   |
| Broadcom Limited      | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 34        | 18.89%  |
| Intel Wireless 7265                                           | 14        | 7.78%   |
| Intel Wi-Fi 6 AX201                                           | 9         | 5%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 8         | 4.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 8         | 4.44%   |
| Intel Wireless 3165                                           | 7         | 3.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 5         | 2.78%   |
| Intel Comet Lake PCH CNVi WiFi                                | 5         | 2.78%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 5         | 2.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 4         | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 4         | 2.22%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 3         | 1.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 3         | 1.67%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 3         | 1.67%   |
| Realtek 802.11ac NIC                                          | 3         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 3         | 1.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 1.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 3         | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                 | 3         | 1.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 3         | 1.67%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 2         | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 2         | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 2         | 1.11%   |
| Ralink MT7601U Wireless Adapter                               | 2         | 1.11%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 2         | 1.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 1.11%   |
| Mercucys 802.11n NIC                                          | 2         | 1.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 1.11%   |
| Intel Wireless 8265 / 8275                                    | 2         | 1.11%   |
| Intel Wi-Fi 6 AX200                                           | 2         | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 1.11%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 1         | 0.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 0.56%   |
| TP-Link 802.11n NIC                                           | 1         | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 0.56%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1         | 0.56%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 0.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1         | 0.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 161       | 58.97%  |
| Intel                    | 81        | 29.67%  |
| Qualcomm Atheros         | 6         | 2.2%    |
| Xiaomi                   | 5         | 1.83%   |
| Samsung Electronics      | 3         | 1.1%    |
| Nvidia                   | 3         | 1.1%    |
| MediaTek                 | 2         | 0.73%   |
| Huawei Technologies      | 2         | 0.73%   |
| Broadcom                 | 2         | 0.73%   |
| VIA Technologies         | 1         | 0.37%   |
| TP-Link                  | 1         | 0.37%   |
| OPPO Electronics         | 1         | 0.37%   |
| OKB SAPR                 | 1         | 0.37%   |
| Mellanox Technologies    | 1         | 0.37%   |
| Marvell Technology Group | 1         | 0.37%   |
| ASIX Electronics         | 1         | 0.37%   |
| American Megatrends      | 1         | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 143       | 51.07%  |
| Intel Ethernet Controller I225-V                                  | 11        | 3.93%   |
| Intel Ethernet Connection (14) I219-V                             | 9         | 3.21%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 2.86%   |
| Intel Ethernet Connection (17) I219-V                             | 8         | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 2.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 2.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 1.79%   |
| Intel Ethernet Connection (11) I219-V                             | 5         | 1.79%   |
| Intel NM10/ICH7 Family LAN Controller                             | 4         | 1.43%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.07%   |
| Nvidia MCP61 Ethernet                                             | 3         | 1.07%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.07%   |
| Intel Ethernet Connection (17) I219-LM                            | 3         | 1.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.71%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.71%   |
| Intel Ethernet Controller I225-LM                                 | 2         | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.71%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 0.71%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.71%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.71%   |
| Huawei WLZ-AN00                                                   | 2         | 0.71%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.36%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.36%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.36%   |
| OPPO SM6375-QRD _SN:F4A23F05                                      | 1         | 0.36%   |
| OKB SAPR Ethernet controller                                      | 1         | 0.36%   |
| Mellanox MT27800 Family [ConnectX-5]                              | 1         | 0.36%   |
| MediaTek Titan pocket                                             | 1         | 0.36%   |
| MediaTek 100026191                                                | 1         | 0.36%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.36%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 258       | 59.58%  |
| WiFi     | 172       | 39.72%  |
| Modem    | 3         | 0.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 218       | 73.15%  |
| WiFi     | 80        | 26.85%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 162       | 55.48%  |
| 2     | 120       | 41.1%   |
| 0     | 5         | 1.71%   |
| 4     | 3         | 1.03%   |
| 7     | 1         | 0.34%   |
| 3     | 1         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 285       | 96.61%  |
| Yes  | 10        | 3.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 48.61%  |
| Realtek Semiconductor           | 41        | 28.47%  |
| Broadcom                        | 8         | 5.56%   |
| IMC Networks                    | 6         | 4.17%   |
| Cambridge Silicon Radio         | 3         | 2.08%   |
| Realtek                         | 2         | 1.39%   |
| Ralink                          | 2         | 1.39%   |
| Qualcomm Atheros Communications | 2         | 1.39%   |
| Lite-On Technology              | 2         | 1.39%   |
| Foxconn / Hon Hai               | 2         | 1.39%   |
| TP-Link                         | 1         | 0.69%   |
| Opticis                         | 1         | 0.69%   |
| MediaTek                        | 1         | 0.69%   |
| Hewlett-Packard                 | 1         | 0.69%   |
| Foxconn International           | 1         | 0.69%   |
| ASUSTek Computer                | 1         | 0.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 36        | 25%     |
| Intel Bluetooth wireless interface                  | 26        | 18.06%  |
| Intel AX201 Bluetooth                               | 21        | 14.58%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 7.64%   |
| Intel Bluetooth Device                              | 7         | 4.86%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 3.47%   |
| IMC Networks Bluetooth Radio                        | 4         | 2.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 2.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.08%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.39%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.39%   |
| Intel AX200 Bluetooth                               | 2         | 1.39%   |
| IMC Networks Bluetooth Device                       | 2         | 1.39%   |
| TP-Link UB500 Adapter                               | 1         | 0.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 0.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.69%   |
| Opticis Bluetooth Radio                             | 1         | 0.69%   |
| MediaTek Wireless_Device                            | 1         | 0.69%   |
| Lite-On Wireless_Device                             | 1         | 0.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.69%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.69%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.69%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 0.69%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.69%   |
| Broadcom HP Portable Valentine                      | 1         | 0.69%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.69%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1         | 0.69%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.69%   |
| Broadcom BCM20702A0 Bluetooth                       | 1         | 0.69%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.69%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.69%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 235       | 67.72%  |
| AMD                    | 57        | 16.43%  |
| Nvidia                 | 33        | 9.51%   |
| Texas Instruments      | 5         | 1.44%   |
| Lenovo                 | 5         | 1.44%   |
| C-Media Electronics    | 3         | 0.86%   |
| Logitech               | 2         | 0.58%   |
| Generalplus Technology | 2         | 0.58%   |
| Zhaoxin                | 1         | 0.29%   |
| Samson Technologies    | 1         | 0.29%   |
| Razer USA              | 1         | 0.29%   |
| MosArt Semiconductor   | 1         | 0.29%   |
| Creative Technology    | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 38        | 9.48%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 31        | 7.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 31        | 7.73%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 24        | 5.99%   |
| Intel 200 Series PCH HD Audio                                              | 18        | 4.49%   |
| Intel Alder Lake-S HD Audio Controller                                     | 15        | 3.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15        | 3.74%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 3.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 2.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 2.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 2.74%   |
| Intel Comet Lake PCH-V cAVS                                                | 9         | 2.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 2%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 2%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 1.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 1.75%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 1.5%    |
| Texas Instruments PCM2902 Audio Codec                                      | 5         | 1.25%   |
| Nvidia High Definition Audio Controller                                    | 5         | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 1%      |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1%      |
| Lenovo ThinkCentre TIO22Gen4 for USB Audio                                 | 4         | 1%      |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1%      |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 1%      |
| Nvidia MCP61 High Definition Audio                                         | 3         | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 0.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.5%    |
| Logitech 960 Headset                                                       | 2         | 0.5%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung Electronics                | 71        | 23.05%  |
| Crucial                            | 37        | 12.01%  |
| Kingston                           | 32        | 10.39%  |
| SK hynix                           | 29        | 9.42%   |
| Foxline                            | 25        | 8.12%   |
| Unknown                            | 19        | 6.17%   |
| Micron Technology                  | 12        | 3.9%    |
| Ramaxel Technology                 | 9         | 2.92%   |
| A-DATA Technology                  | 9         | 2.92%   |
| Patriot                            | 8         | 2.6%    |
| AMD                                | 8         | 2.6%    |
| Apacer                             | 7         | 2.27%   |
| Unknown (ABCD)                     | 6         | 1.95%   |
| Elpida                             | 5         | 1.62%   |
| Unknown                            | 4         | 1.3%    |
| SHARETRONIC                        | 2         | 0.65%   |
| Qumo                               | 2         | 0.65%   |
| Neo Forza                          | 2         | 0.65%   |
| HomeNet                            | 2         | 0.65%   |
| Corsair                            | 2         | 0.65%   |
| ChangXin Memory                    | 2         | 0.65%   |
| Unknown (BA8A)                     | 1         | 0.32%   |
| Unknown (89F7)                     | 1         | 0.32%   |
| Unknown (0x0080)                   | 1         | 0.32%   |
| Shenzhen Micro Innovation Industry | 1         | 0.32%   |
| Patriot Memory (PDP Systems)       | 1         | 0.32%   |
| KingSpec                           | 1         | 0.32%   |
| King Tiger                         | 1         | 0.32%   |
| Innodisk                           | 1         | 0.32%   |
| GOODRAM                            | 1         | 0.32%   |
| Good Wealth                        | 1         | 0.32%   |
| Goldkey                            | 1         | 0.32%   |
| Golden Empire                      | 1         | 0.32%   |
| Gold Key                           | 1         | 0.32%   |
| G.Skill                            | 1         | 0.32%   |
| <Invalid>                          | 1         | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s             | 17        | 5.31%   |
| Foxline RAM FL2666D4S19-8G 8192MB SODIMM DDR4 2667MT/s            | 8         | 2.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 7         | 2.19%   |
| Foxline RAM FL2666D4U19-8G 8GB DIMM DDR4 2667MT/s                 | 6         | 1.88%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s             | 5         | 1.56%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s          | 4         | 1.25%   |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s            | 4         | 1.25%   |
| Unknown                                                           | 4         | 1.25%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 3         | 0.94%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 3         | 0.94%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.94%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s          | 3         | 0.94%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s             | 3         | 0.94%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s         | 3         | 0.94%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s             | 3         | 0.94%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s              | 3         | 0.94%   |
| Foxline RAM FL3200D4S22-8G 8192MB SODIMM DDR4 3200MT/s            | 3         | 0.94%   |
| Foxline RAM FL2400D4S17S-8G 8192MB SODIMM DDR4 2400MT/s           | 3         | 0.94%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                       | 3         | 0.94%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                         | 2         | 0.63%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 2         | 0.63%   |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3 1800MT/s              | 2         | 0.63%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.63%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s            | 2         | 0.63%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s            | 2         | 0.63%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 2         | 0.63%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                          | 2         | 0.63%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s                  | 2         | 0.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s       | 2         | 0.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 2         | 0.63%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 2         | 0.63%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s             | 2         | 0.63%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s               | 2         | 0.63%   |
| Ramaxel RAM RMSA3320MR78HAF-3200 8GB SODIMM DDR4 3200MT/s         | 2         | 0.63%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                   | 2         | 0.63%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s             | 2         | 0.63%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s               | 2         | 0.63%   |
| Kingston RAM 99U5734-036.A00G 16GB DIMM DDR4 2667MT/s             | 2         | 0.63%   |
| Kingston RAM 9905711-027.A00G 4GB SODIMM DDR4 2667MT/s            | 2         | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 214       | 75.09%  |
| DDR3    | 39        | 13.68%  |
| DDR2    | 8         | 2.81%   |
| LPDDR4  | 7         | 2.46%   |
| Unknown | 7         | 2.46%   |
| SDRAM   | 6         | 2.11%   |
| LPDDR5  | 1         | 0.35%   |
| LPDDR3  | 1         | 0.35%   |
| DDR5    | 1         | 0.35%   |
| DDR     | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 142       | 48.97%  |
| DIMM         | 135       | 46.55%  |
| Row Of Chips | 13        | 4.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 164       | 54.13%  |
| 4096  | 64        | 21.12%  |
| 16384 | 34        | 11.22%  |
| 2048  | 21        | 6.93%   |
| 1024  | 11        | 3.63%   |
| 32768 | 7         | 2.31%   |
| 65536 | 1         | 0.33%   |
| 512   | 1         | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 85        | 28.52%  |
| 3200    | 79        | 26.51%  |
| 2400    | 25        | 8.39%   |
| 1600    | 19        | 6.38%   |
| 1333    | 14        | 4.7%    |
| 2666    | 7         | 2.35%   |
| 2133    | 7         | 2.35%   |
| 2933    | 5         | 1.68%   |
| 3600    | 4         | 1.34%   |
| 3266    | 4         | 1.34%   |
| 800     | 4         | 1.34%   |
| 2800    | 3         | 1.01%   |
| 1866    | 3         | 1.01%   |
| 1066    | 3         | 1.01%   |
| 667     | 3         | 1.01%   |
| 533     | 3         | 1.01%   |
| Unknown | 3         | 1.01%   |
| 4800    | 2         | 0.67%   |
| 3466    | 2         | 0.67%   |
| 2934    | 2         | 0.67%   |
| 1800    | 2         | 0.67%   |
| 1334    | 2         | 0.67%   |
| 1067    | 2         | 0.67%   |
| 333     | 2         | 0.67%   |
| 6400    | 1         | 0.34%   |
| 5200    | 1         | 0.34%   |
| 3866    | 1         | 0.34%   |
| 3800    | 1         | 0.34%   |
| 3733    | 1         | 0.34%   |
| 3533    | 1         | 0.34%   |
| 3000    | 1         | 0.34%   |
| 2866    | 1         | 0.34%   |
| 2733    | 1         | 0.34%   |
| 2187    | 1         | 0.34%   |
| 2134    | 1         | 0.34%   |
| 1648    | 1         | 0.34%   |
| 400     | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 40%     |
| Pantum          | 1         | 20%     |
| Kyocera         | 1         | 20%     |
| Canon           | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Pantum BM5100ADN series | 1         | 20%     |
| Kyocera FS-1040         | 1         | 20%     |
| HP LaserJet P2035       | 1         | 20%     |
| HP LaserJet M402dn      | 1         | 20%     |
| Canon MF3010            | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP ScanJet Pro 2000 s2  | 1         | 33.33%  |
| Canon CanoScan LIDE 25  | 1         | 33.33%  |
| Canon CanoScan LiDE 110 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 16.56%  |
| Syntek                                 | 21        | 13.91%  |
| IMC Networks                           | 13        | 8.61%   |
| Microdia                               | 9         | 5.96%   |
| Alcor Micro                            | 9         | 5.96%   |
| SunplusIT                              | 8         | 5.3%    |
| Quanta                                 | 8         | 5.3%    |
| Realtek Semiconductor                  | 7         | 4.64%   |
| Bison Electronics                      | 7         | 4.64%   |
| Acer                                   | 7         | 4.64%   |
| Sunplus Innovation Technology          | 4         | 2.65%   |
| Luxvisions Innotech Limited            | 4         | 2.65%   |
| Hopewin Electronic Material            | 4         | 2.65%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.65%   |
| Suyin                                  | 3         | 1.99%   |
| Logitech                               | 3         | 1.99%   |
| Z-Star Microelectronics                | 2         | 1.32%   |
| USB Camera CS                          | 2         | 1.32%   |
| Sonix Technology                       | 2         | 1.32%   |
| AlcorMicroCorp                         | 2         | 1.32%   |
| Lite-On Technology                     | 1         | 0.66%   |
| KYE Systems (Mouse Systems)            | 1         | 0.66%   |
| GEMBIRD                                | 1         | 0.66%   |
| Creative Technology                    | 1         | 0.66%   |
| Arkmicro Technologies                  | 1         | 0.66%   |
| Apple                                  | 1         | 0.66%   |
| Unknown                                | 1         | 0.66%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Syntek Integrated Camera                      | 18        | 11.92%  |
| Chicony USB camera                            | 10        | 6.62%   |
| SunplusIT USB Camera                          | 6         | 3.97%   |
| Alcor Micro USB 2.0 PC Camera                 | 6         | 3.97%   |
| Realtek USB Camera                            | 4         | 2.65%   |
| IMC Networks ov9734_azurewave_camera          | 4         | 2.65%   |
| IMC Networks Integrated Camera                | 4         | 2.65%   |
| Hopewin Electronic Material Integrated Camera | 4         | 2.65%   |
| Acer Integrated Camera                        | 4         | 2.65%   |
| Microdia Camera                               | 3         | 1.99%   |
| Logitech HD Webcam C615                       | 3         | 1.99%   |
| IMC Networks USB2.0 HD UVC WebCam             | 3         | 1.99%   |
| Chicony Integrated Camera                     | 3         | 1.99%   |
| Bison Integrated Camera                       | 3         | 1.99%   |
| USB Camera CS USB Camera CS                   | 2         | 1.32%   |
| Sonix USB 2.0 Camera                          | 2         | 1.32%   |
| Quanta HP TrueVision HD Camera                | 2         | 1.32%   |
| Microdia Webcam Vitade AF                     | 2         | 1.32%   |
| Microdia USB 2.0 Camera                       | 2         | 1.32%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.32%   |
| Chicony USB2.0 Camera                         | 2         | 1.32%   |
| Chicony HP High Definition 1MP Webcam         | 2         | 1.32%   |
| Chicony HD User Facing                        | 2         | 1.32%   |
| Bison Lenovo Integrated Webcam                | 2         | 1.32%   |
| AlcorMicroCorp SHUNCCM                        | 2         | 1.32%   |
| Alcor Micro USB FHD Camera                    | 2         | 1.32%   |
| Acer HD Webcam                                | 2         | 1.32%   |
| Z-Star Lenovo USB2.0 UVC Camera               | 1         | 0.66%   |
| Z-Star Lenovo IdeaCentre Web Camera           | 1         | 0.66%   |
| Syntek LENOVO LBG 720P CAM                    | 1         | 0.66%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.66%   |
| Syntek Integrated RGB Camera                  | 1         | 0.66%   |
| Suyin HP Truevision HD                        | 1         | 0.66%   |
| Suyin HP Integrated Webcam                    | 1         | 0.66%   |
| Suyin Acer CrystalEye Webcam                  | 1         | 0.66%   |
| SunplusIT XiaoMi USB 2.0 Webcam               | 1         | 0.66%   |
| SunplusIT HBT Camera                          | 1         | 0.66%   |
| Sunplus Integrated_Webcam_HD                  | 1         | 0.66%   |
| Sunplus BKX Usb FHD Camera                    | 1         | 0.66%   |
| Sunplus Asus Webcam                           | 1         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 7         | 70%     |
| Synaptics                  | 2         | 20%     |
| Validity Sensors           | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device        | 7         | 70%     |
| Synaptics UWP WBDI Device                  | 2         | 20%     |
| Validity Sensors VFS451 Fingerprint Reader | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Aladdin R.D. | 2         | 66.67%  |
| Aktiv        | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Aladdin R.D. Smart card reader JCR721 | 1         | 33.33%  |
| Aladdin R.D. JaCarta                  | 1         | 33.33%  |
| Aktiv Rutoken lite                    | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 217       | 72.82%  |
| 1     | 65        | 21.81%  |
| 2     | 11        | 3.69%   |
| 4     | 3         | 1.01%   |
| 3     | 2         | 0.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 51        | 52.04%  |
| Net/wireless             | 16        | 16.33%  |
| Fingerprint reader       | 10        | 10.2%   |
| Communication controller | 6         | 6.12%   |
| Unassigned class         | 4         | 4.08%   |
| Sound                    | 2         | 2.04%   |
| Net/ethernet             | 2         | 2.04%   |
| Multimedia controller    | 2         | 2.04%   |
| Bluetooth                | 2         | 2.04%   |
| Network                  | 1         | 1.02%   |
| Chipcard                 | 1         | 1.02%   |
| Camera                   | 1         | 1.02%   |

