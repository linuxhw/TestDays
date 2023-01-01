Pop!_OS 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

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

Total: 803

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Predator PO3-600 V:1.1      | [e5f5073bcd](https://linux-hardware.org/?probe=e5f5073bcd) | Dec 31, 2022 |
| MSI           | B250M BAZOOKA               | [5b204eade4](https://linux-hardware.org/?probe=5b204eade4) | Dec 31, 2022 |
| Dell          | 0KWVT8 A03                  | [ad32666c8c](https://linux-hardware.org/?probe=ad32666c8c) | Dec 31, 2022 |
| ASUSTek       | Z97-A                       | [6f61aac097](https://linux-hardware.org/?probe=6f61aac097) | Dec 31, 2022 |
| Dell          | 0KWVT8 A03                  | [17fc3a4abc](https://linux-hardware.org/?probe=17fc3a4abc) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [76e9829e66](https://linux-hardware.org/?probe=76e9829e66) | Dec 30, 2022 |
| ASUSTek       | Z87-PLUS                    | [85bfa942e6](https://linux-hardware.org/?probe=85bfa942e6) | Dec 30, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | [4b3cfd1d9c](https://linux-hardware.org/?probe=4b3cfd1d9c) | Dec 30, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [17f72460f6](https://linux-hardware.org/?probe=17f72460f6) | Dec 29, 2022 |
| Acer          | Aspire XC-603G              | [08dc8ac6b7](https://linux-hardware.org/?probe=08dc8ac6b7) | Dec 29, 2022 |
| ASRock        | Z790 PG Riptide             | [19c8814aba](https://linux-hardware.org/?probe=19c8814aba) | Dec 29, 2022 |
| Dell          | 0NNGP2 A00                  | [12638171d9](https://linux-hardware.org/?probe=12638171d9) | Dec 28, 2022 |
| Lenovo        | No DPK                      | [944f84567a](https://linux-hardware.org/?probe=944f84567a) | Dec 28, 2022 |
| ASRock        | Z790M-ITX WiFi              | [c1c0ab5824](https://linux-hardware.org/?probe=c1c0ab5824) | Dec 28, 2022 |
| Dell          | 00CV7F A00                  | [49a36278c4](https://linux-hardware.org/?probe=49a36278c4) | Dec 28, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [2522f716da](https://linux-hardware.org/?probe=2522f716da) | Dec 28, 2022 |
| HP            | 2B4B                        | [b07e2ecc23](https://linux-hardware.org/?probe=b07e2ecc23) | Dec 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [1522e4a536](https://linux-hardware.org/?probe=1522e4a536) | Dec 28, 2022 |
| Acer          | Aspire XC-603G              | [e8adbb63a4](https://linux-hardware.org/?probe=e8adbb63a4) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [20ca7dd779](https://linux-hardware.org/?probe=20ca7dd779) | Dec 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [dab993d989](https://linux-hardware.org/?probe=dab993d989) | Dec 27, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ee1658b320](https://linux-hardware.org/?probe=ee1658b320) | Dec 27, 2022 |
| HP            | 876C SMVB                   | [7926807626](https://linux-hardware.org/?probe=7926807626) | Dec 27, 2022 |
| ASUSTek       | Z87-K                       | [9c65749eb1](https://linux-hardware.org/?probe=9c65749eb1) | Dec 27, 2022 |
| MSI           | B450M PRO-M2                | [89d9265559](https://linux-hardware.org/?probe=89d9265559) | Dec 27, 2022 |
| ASRock        | Z390M-ITX/ac                | [23d6589918](https://linux-hardware.org/?probe=23d6589918) | Dec 27, 2022 |
| Gigabyte      | H61M-S2PV                   | [4403153e04](https://linux-hardware.org/?probe=4403153e04) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [c49123106a](https://linux-hardware.org/?probe=c49123106a) | Dec 24, 2022 |
| Gigabyte      | MJPLNBB-00                  | [17c300ac96](https://linux-hardware.org/?probe=17c300ac96) | Dec 22, 2022 |
| ASUSTek       | P7P55D PRO                  | [7402ac8671](https://linux-hardware.org/?probe=7402ac8671) | Dec 22, 2022 |
| MSI           | B85M-E45                    | [b60edb092f](https://linux-hardware.org/?probe=b60edb092f) | Dec 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [07dc9b96c1](https://linux-hardware.org/?probe=07dc9b96c1) | Dec 21, 2022 |
| Dell          | 02GDWG A00                  | [d20f5b0751](https://linux-hardware.org/?probe=d20f5b0751) | Dec 21, 2022 |
| Intel         | X99 V1.x                    | [5e961d12dc](https://linux-hardware.org/?probe=5e961d12dc) | Dec 21, 2022 |
| Supermicro    | X9DR3-F                     | [0a1557ab4a](https://linux-hardware.org/?probe=0a1557ab4a) | Dec 20, 2022 |
| HP            | 18E7                        | [c3b91e80df](https://linux-hardware.org/?probe=c3b91e80df) | Dec 20, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [03dfcb8079](https://linux-hardware.org/?probe=03dfcb8079) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1f6885ef2f](https://linux-hardware.org/?probe=1f6885ef2f) | Dec 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | [cdbf94efce](https://linux-hardware.org/?probe=cdbf94efce) | Dec 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c7b01f9875](https://linux-hardware.org/?probe=c7b01f9875) | Dec 19, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [c168fe495f](https://linux-hardware.org/?probe=c168fe495f) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d179359230](https://linux-hardware.org/?probe=d179359230) | Dec 18, 2022 |
| HP            | 8433 11                     | [4368b19d60](https://linux-hardware.org/?probe=4368b19d60) | Dec 18, 2022 |
| Gigabyte      | B550 VISION D-P             | [163b883ce2](https://linux-hardware.org/?probe=163b883ce2) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2a0f5be3bf](https://linux-hardware.org/?probe=2a0f5be3bf) | Dec 17, 2022 |
| Dell          | 02GDWG A00                  | [d7e869aded](https://linux-hardware.org/?probe=d7e869aded) | Dec 17, 2022 |
| Unknown       | Unknown                     | [988a2e80c0](https://linux-hardware.org/?probe=988a2e80c0) | Dec 17, 2022 |
| Dell          | 02GDWG A00                  | [f12e6b75b5](https://linux-hardware.org/?probe=f12e6b75b5) | Dec 16, 2022 |
| ASUSTek       | SABERTOOTH X58              | [b31e9dfa64](https://linux-hardware.org/?probe=b31e9dfa64) | Dec 16, 2022 |
| MSI           | X370 GAMING PLUS            | [893af38c43](https://linux-hardware.org/?probe=893af38c43) | Dec 16, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [90912f0bba](https://linux-hardware.org/?probe=90912f0bba) | Dec 16, 2022 |
| ASUSTek       | SABERTOOTH X58              | [9cff930a2e](https://linux-hardware.org/?probe=9cff930a2e) | Dec 16, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [0b1367de2f](https://linux-hardware.org/?probe=0b1367de2f) | Dec 16, 2022 |
| ASUSTek       | M51BC                       | [3b744c3d0c](https://linux-hardware.org/?probe=3b744c3d0c) | Dec 16, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [60848aa48e](https://linux-hardware.org/?probe=60848aa48e) | Dec 16, 2022 |
| ASUSTek       | PRIME X570-PRO              | [af4e397bbe](https://linux-hardware.org/?probe=af4e397bbe) | Dec 16, 2022 |
| System76      | Thelio thelio-r2            | [d2065497b9](https://linux-hardware.org/?probe=d2065497b9) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [1d1a225cde](https://linux-hardware.org/?probe=1d1a225cde) | Dec 15, 2022 |
| MSI           | Z170A PC MATE               | [e6f5c32627](https://linux-hardware.org/?probe=e6f5c32627) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [35ef32b165](https://linux-hardware.org/?probe=35ef32b165) | Dec 14, 2022 |
| ASRock        | B450M-HDV R4.0              | [b4d843d4c2](https://linux-hardware.org/?probe=b4d843d4c2) | Dec 14, 2022 |
| ASRock        | X670E PG Lightning          | [08e4e03d36](https://linux-hardware.org/?probe=08e4e03d36) | Dec 13, 2022 |
| ASRock        | X670E PG Lightning          | [3a6a347ff9](https://linux-hardware.org/?probe=3a6a347ff9) | Dec 13, 2022 |
| Acer          | Aspire T3-100               | [918ad73eb1](https://linux-hardware.org/?probe=918ad73eb1) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e583774bc6](https://linux-hardware.org/?probe=e583774bc6) | Dec 13, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [cdc6f36d8c](https://linux-hardware.org/?probe=cdc6f36d8c) | Dec 11, 2022 |
| ASRock        | X570 Extreme4 WiFi ax       | [8f45bcde64](https://linux-hardware.org/?probe=8f45bcde64) | Dec 11, 2022 |
| Dell          | 02GDWG A00                  | [229065f67f](https://linux-hardware.org/?probe=229065f67f) | Dec 11, 2022 |
| MSI           | A55M-E33                    | [327967e6a4](https://linux-hardware.org/?probe=327967e6a4) | Dec 11, 2022 |
| Dell          | 02GDWG A00                  | [5cea05fe88](https://linux-hardware.org/?probe=5cea05fe88) | Dec 11, 2022 |
| Apple         | Mac-F221BEC8                | [55a5f34bf0](https://linux-hardware.org/?probe=55a5f34bf0) | Dec 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [d83227cce9](https://linux-hardware.org/?probe=d83227cce9) | Dec 10, 2022 |
| ASUSTek       | PRIME B550M-A               | [05f65af47e](https://linux-hardware.org/?probe=05f65af47e) | Dec 10, 2022 |
| Supermicro    | C7Q67 V1.01                 | [8f571548fd](https://linux-hardware.org/?probe=8f571548fd) | Dec 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [8f38dcc9d4](https://linux-hardware.org/?probe=8f38dcc9d4) | Dec 10, 2022 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | [e8d8a922a2](https://linux-hardware.org/?probe=e8d8a922a2) | Dec 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [560e61c57f](https://linux-hardware.org/?probe=560e61c57f) | Dec 10, 2022 |
| Dell          | 0HY9JP A02                  | [94a6153aeb](https://linux-hardware.org/?probe=94a6153aeb) | Dec 09, 2022 |
| ASUSTek       | PRIME B550M-A               | [1b848d1587](https://linux-hardware.org/?probe=1b848d1587) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e61897fa56](https://linux-hardware.org/?probe=e61897fa56) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1280df2c5d](https://linux-hardware.org/?probe=1280df2c5d) | Dec 08, 2022 |
| MSI           | PRO Z790-A WIFI             | [9dfb20d74f](https://linux-hardware.org/?probe=9dfb20d74f) | Dec 08, 2022 |
| ASRock        | Z97 Extreme6                | [f000ea7b78](https://linux-hardware.org/?probe=f000ea7b78) | Dec 08, 2022 |
| ASUSTek       | PRIME Z390-A                | [d2c01d70df](https://linux-hardware.org/?probe=d2c01d70df) | Dec 08, 2022 |
| BESSTAR Te... | B550                        | [5471ce4bdc](https://linux-hardware.org/?probe=5471ce4bdc) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [c376825cca](https://linux-hardware.org/?probe=c376825cca) | Dec 07, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [7abcfecd34](https://linux-hardware.org/?probe=7abcfecd34) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [6abdbbb7e7](https://linux-hardware.org/?probe=6abdbbb7e7) | Dec 07, 2022 |
| Gigabyte      | A320M-S2H-CF                | [3c65af8425](https://linux-hardware.org/?probe=3c65af8425) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [6ff5feb92c](https://linux-hardware.org/?probe=6ff5feb92c) | Dec 06, 2022 |
| Gigabyte      | A320M-S2H-CF                | [d66311f833](https://linux-hardware.org/?probe=d66311f833) | Dec 06, 2022 |
| MSI           | B150M MORTAR                | [9a87b35e1c](https://linux-hardware.org/?probe=9a87b35e1c) | Dec 06, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [310ff494e7](https://linux-hardware.org/?probe=310ff494e7) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [c0f26cbe79](https://linux-hardware.org/?probe=c0f26cbe79) | Dec 06, 2022 |
| MSI           | 760GM-P23                   | [df9ebcbba6](https://linux-hardware.org/?probe=df9ebcbba6) | Dec 06, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [69cc6b3ad3](https://linux-hardware.org/?probe=69cc6b3ad3) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [b9d333782f](https://linux-hardware.org/?probe=b9d333782f) | Dec 05, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [c74d870263](https://linux-hardware.org/?probe=c74d870263) | Dec 04, 2022 |
| MSI           | B350 TOMAHAWK               | [2607a15d58](https://linux-hardware.org/?probe=2607a15d58) | Dec 03, 2022 |
| ASRock        | Z370 Pro4                   | [76cd787c24](https://linux-hardware.org/?probe=76cd787c24) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [dd1874248c](https://linux-hardware.org/?probe=dd1874248c) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [eaf129dcfe](https://linux-hardware.org/?probe=eaf129dcfe) | Dec 02, 2022 |
| MSI           | MAG B650M MORTAR WIFI       | [8e317647dc](https://linux-hardware.org/?probe=8e317647dc) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [953943c231](https://linux-hardware.org/?probe=953943c231) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | [0e0ed0822c](https://linux-hardware.org/?probe=0e0ed0822c) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | [adeb151478](https://linux-hardware.org/?probe=adeb151478) | Dec 02, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [c8d4cd1faf](https://linux-hardware.org/?probe=c8d4cd1faf) | Dec 01, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [866e8151d7](https://linux-hardware.org/?probe=866e8151d7) | Dec 01, 2022 |
| System76      | Thelio thelio-r2            | [a7ae37f43e](https://linux-hardware.org/?probe=a7ae37f43e) | Dec 01, 2022 |
| Unknown       | 1.0                         | [c8cfeaf2be](https://linux-hardware.org/?probe=c8cfeaf2be) | Dec 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [f8a7663037](https://linux-hardware.org/?probe=f8a7663037) | Dec 01, 2022 |
| MSI           | B350 GAMING PLUS            | [b840a0d02e](https://linux-hardware.org/?probe=b840a0d02e) | Dec 01, 2022 |
| ASRock        | H77M                        | [ffa3496b0d](https://linux-hardware.org/?probe=ffa3496b0d) | Nov 30, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [a42a4d6080](https://linux-hardware.org/?probe=a42a4d6080) | Nov 29, 2022 |
| MSI           | B560M PRO-VDH               | [cee0622b1f](https://linux-hardware.org/?probe=cee0622b1f) | Nov 29, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [40c84f5af9](https://linux-hardware.org/?probe=40c84f5af9) | Nov 28, 2022 |
| Gigabyte      | A520M S2H                   | [151f18b424](https://linux-hardware.org/?probe=151f18b424) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | [dee60b9f35](https://linux-hardware.org/?probe=dee60b9f35) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | [1651962e5a](https://linux-hardware.org/?probe=1651962e5a) | Nov 28, 2022 |
| Acer          | Nitro N50-610               | [1a50d26810](https://linux-hardware.org/?probe=1a50d26810) | Nov 27, 2022 |
| Acer          | Nitro N50-610               | [b924b1fdd6](https://linux-hardware.org/?probe=b924b1fdd6) | Nov 27, 2022 |
| MSI           | Z97A GAMING 7               | [74341c948b](https://linux-hardware.org/?probe=74341c948b) | Nov 27, 2022 |
| MSI           | B350 GAMING PLUS            | [1e016dcb9b](https://linux-hardware.org/?probe=1e016dcb9b) | Nov 26, 2022 |
| Dell          | 04MFRM A02                  | [43239e45b1](https://linux-hardware.org/?probe=43239e45b1) | Nov 26, 2022 |
| Gigabyte      | B650M AORUS ELITE AX        | [a8a722921c](https://linux-hardware.org/?probe=a8a722921c) | Nov 26, 2022 |
| Dell          | 06NWYK A01                  | [3afe7122f3](https://linux-hardware.org/?probe=3afe7122f3) | Nov 26, 2022 |
| Gigabyte      | Z77-HD3                     | [e3b7bbc736](https://linux-hardware.org/?probe=e3b7bbc736) | Nov 25, 2022 |
| Pegatron      | 2A9A                        | [ee74398a78](https://linux-hardware.org/?probe=ee74398a78) | Nov 25, 2022 |
| ASRock        | Z170 Gaming K6              | [de7addf17b](https://linux-hardware.org/?probe=de7addf17b) | Nov 25, 2022 |
| ASRock        | B550M-ITX/ac                | [c72c157583](https://linux-hardware.org/?probe=c72c157583) | Nov 24, 2022 |
| ASRock        | B550M-ITX/ac                | [bd50429870](https://linux-hardware.org/?probe=bd50429870) | Nov 24, 2022 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [880f8b9c45](https://linux-hardware.org/?probe=880f8b9c45) | Nov 23, 2022 |
| HP            | 8309                        | [8329dc7b8d](https://linux-hardware.org/?probe=8329dc7b8d) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [4b44aea106](https://linux-hardware.org/?probe=4b44aea106) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [1c232e6d70](https://linux-hardware.org/?probe=1c232e6d70) | Nov 23, 2022 |
| ASRock        | H310CM-HG4                  | [d4f3608765](https://linux-hardware.org/?probe=d4f3608765) | Nov 21, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | [eed1e72aba](https://linux-hardware.org/?probe=eed1e72aba) | Nov 21, 2022 |
| Gigabyte      | H110M-S2H-CF                | [412c1923c5](https://linux-hardware.org/?probe=412c1923c5) | Nov 20, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [a1b9357fc6](https://linux-hardware.org/?probe=a1b9357fc6) | Nov 20, 2022 |
| Gigabyte      | B550M DS3H                  | [884474637c](https://linux-hardware.org/?probe=884474637c) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | [0b7bd42177](https://linux-hardware.org/?probe=0b7bd42177) | Nov 18, 2022 |
| Gigabyte      | H81M-S1                     | [4498bc64bc](https://linux-hardware.org/?probe=4498bc64bc) | Nov 18, 2022 |
| Gigabyte      | 990FXA-UD3                  | [078e04eb73](https://linux-hardware.org/?probe=078e04eb73) | Nov 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [33f2716179](https://linux-hardware.org/?probe=33f2716179) | Nov 17, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [478fa166bd](https://linux-hardware.org/?probe=478fa166bd) | Nov 17, 2022 |
| HP            | 805D                        | [cb811984e0](https://linux-hardware.org/?probe=cb811984e0) | Nov 17, 2022 |
| Dell          | 0KWVT8 A03                  | [b696d9eae7](https://linux-hardware.org/?probe=b696d9eae7) | Nov 16, 2022 |
| Huanan        | X99-8M-F V1.1               | [0a623c060a](https://linux-hardware.org/?probe=0a623c060a) | Nov 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [c6f5c91413](https://linux-hardware.org/?probe=c6f5c91413) | Nov 16, 2022 |
| Dell          | 04MFRM A02                  | [677ab8eb16](https://linux-hardware.org/?probe=677ab8eb16) | Nov 16, 2022 |
| Foxconn       | 2ABF                        | [9b870d8287](https://linux-hardware.org/?probe=9b870d8287) | Nov 16, 2022 |
| Foxconn       | 2ABF                        | [2f6204153a](https://linux-hardware.org/?probe=2f6204153a) | Nov 15, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [a7e5419c89](https://linux-hardware.org/?probe=a7e5419c89) | Nov 15, 2022 |
| Dell          | 0KWVT8 A03                  | [965a35d0b0](https://linux-hardware.org/?probe=965a35d0b0) | Nov 15, 2022 |
| HP            | 1998                        | [ddcba37929](https://linux-hardware.org/?probe=ddcba37929) | Nov 14, 2022 |
| HP            | 1998                        | [5249f1cdd7](https://linux-hardware.org/?probe=5249f1cdd7) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | [e1f2995c6f](https://linux-hardware.org/?probe=e1f2995c6f) | Nov 14, 2022 |
| Gigabyte      | B75M-D3H                    | [7de064ae3a](https://linux-hardware.org/?probe=7de064ae3a) | Nov 13, 2022 |
| ASUSTek       | M4N72-E                     | [092c39d271](https://linux-hardware.org/?probe=092c39d271) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | [bf79743ff5](https://linux-hardware.org/?probe=bf79743ff5) | Nov 13, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [8104152607](https://linux-hardware.org/?probe=8104152607) | Nov 13, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [e6ad281519](https://linux-hardware.org/?probe=e6ad281519) | Nov 11, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [dc1c83bed5](https://linux-hardware.org/?probe=dc1c83bed5) | Nov 11, 2022 |
| System76      | Thelio thelio-r2            | [1ce532916f](https://linux-hardware.org/?probe=1ce532916f) | Nov 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [fd835d99e7](https://linux-hardware.org/?probe=fd835d99e7) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b4aa454d9a](https://linux-hardware.org/?probe=b4aa454d9a) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | [485568beb7](https://linux-hardware.org/?probe=485568beb7) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | [e5fa54bf6f](https://linux-hardware.org/?probe=e5fa54bf6f) | Nov 10, 2022 |
| MSI           | H61M-P31/W8                 | [933683bc04](https://linux-hardware.org/?probe=933683bc04) | Nov 10, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [4ff6488cb2](https://linux-hardware.org/?probe=4ff6488cb2) | Nov 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [fcd0449df8](https://linux-hardware.org/?probe=fcd0449df8) | Nov 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | [e7fb74c85e](https://linux-hardware.org/?probe=e7fb74c85e) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | [3928df6d1f](https://linux-hardware.org/?probe=3928df6d1f) | Nov 08, 2022 |
| System76      | Thelio thelio-r2            | [0c282237ab](https://linux-hardware.org/?probe=0c282237ab) | Nov 08, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [fa94f8afc5](https://linux-hardware.org/?probe=fa94f8afc5) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | [97e9d1458f](https://linux-hardware.org/?probe=97e9d1458f) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | [581ff62688](https://linux-hardware.org/?probe=581ff62688) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | [a0a7ef6e3a](https://linux-hardware.org/?probe=a0a7ef6e3a) | Nov 07, 2022 |
| Dell          | 0200DY A02                  | [43db111de5](https://linux-hardware.org/?probe=43db111de5) | Nov 07, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [29c3e37808](https://linux-hardware.org/?probe=29c3e37808) | Nov 06, 2022 |
| ASUSTek       | H97M-PLUS                   | [cb778b5593](https://linux-hardware.org/?probe=cb778b5593) | Nov 06, 2022 |
| Intel         | P61A-D3                     | [5561c81cf4](https://linux-hardware.org/?probe=5561c81cf4) | Nov 06, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [cd2a716a60](https://linux-hardware.org/?probe=cd2a716a60) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bad7b9a014](https://linux-hardware.org/?probe=bad7b9a014) | Nov 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [4abe56ea2e](https://linux-hardware.org/?probe=4abe56ea2e) | Nov 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [5b939b71c7](https://linux-hardware.org/?probe=5b939b71c7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518RS8    | [00fc5e3a1b](https://linux-hardware.org/?probe=00fc5e3a1b) | Nov 05, 2022 |
| ASRock        | X399 Taichi                 | [99f51ff157](https://linux-hardware.org/?probe=99f51ff157) | Nov 04, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [4be0967ca1](https://linux-hardware.org/?probe=4be0967ca1) | Nov 04, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [42edcc018a](https://linux-hardware.org/?probe=42edcc018a) | Nov 03, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [77f847ca29](https://linux-hardware.org/?probe=77f847ca29) | Nov 02, 2022 |
| MSI           | X399 SLI PLUS               | [4191ce8788](https://linux-hardware.org/?probe=4191ce8788) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4e97493141](https://linux-hardware.org/?probe=4e97493141) | Nov 02, 2022 |
| HP            | 212A                        | [80abe48959](https://linux-hardware.org/?probe=80abe48959) | Nov 02, 2022 |
| ASUSTek       | H110M-D                     | [248b9533a3](https://linux-hardware.org/?probe=248b9533a3) | Nov 01, 2022 |
| Intel         | DH61DL AAG14066-205         | [0f62f6f3b1](https://linux-hardware.org/?probe=0f62f6f3b1) | Nov 01, 2022 |
| MSI           | MEG X570 UNIFY              | [11de150949](https://linux-hardware.org/?probe=11de150949) | Nov 01, 2022 |
| ASUSTek       | H97-PRO                     | [bae404d45c](https://linux-hardware.org/?probe=bae404d45c) | Oct 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [87187c0e23](https://linux-hardware.org/?probe=87187c0e23) | Oct 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4c3ae53c16](https://linux-hardware.org/?probe=4c3ae53c16) | Oct 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [43a99f49f8](https://linux-hardware.org/?probe=43a99f49f8) | Oct 31, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [56ee27b737](https://linux-hardware.org/?probe=56ee27b737) | Oct 31, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [e638ed7bd3](https://linux-hardware.org/?probe=e638ed7bd3) | Oct 30, 2022 |
| HP            | 3048h                       | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [4bc0220a01](https://linux-hardware.org/?probe=4bc0220a01) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [bd18c2b33d](https://linux-hardware.org/?probe=bd18c2b33d) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| ASRock        | B450M Pro4                  | [0616272661](https://linux-hardware.org/?probe=0616272661) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | [1c5d979ba1](https://linux-hardware.org/?probe=1c5d979ba1) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [77ef1a661c](https://linux-hardware.org/?probe=77ef1a661c) | Oct 29, 2022 |
| Intel         | B75                         | [59cc97d6c7](https://linux-hardware.org/?probe=59cc97d6c7) | Oct 28, 2022 |
| Pegatron      | TRUCKEE                     | [2a6fe2bcd1](https://linux-hardware.org/?probe=2a6fe2bcd1) | Oct 28, 2022 |
| Intel         | DH61DL AAG14066-205         | [9031f7b82b](https://linux-hardware.org/?probe=9031f7b82b) | Oct 27, 2022 |
| MSI           | B85-G43                     | [48ac016cd9](https://linux-hardware.org/?probe=48ac016cd9) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9e7c028b0b](https://linux-hardware.org/?probe=9e7c028b0b) | Oct 27, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [97d2bacb5d](https://linux-hardware.org/?probe=97d2bacb5d) | Oct 26, 2022 |
| ASUSTek       | Maximus VIII HERO           | [cb657f604d](https://linux-hardware.org/?probe=cb657f604d) | Oct 26, 2022 |
| Pegatron      | 2AD5                        | [daf7975ca0](https://linux-hardware.org/?probe=daf7975ca0) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [58af9b9a77](https://linux-hardware.org/?probe=58af9b9a77) | Oct 26, 2022 |
| Gigabyte      | B450 AORUS M                | [1603f6064b](https://linux-hardware.org/?probe=1603f6064b) | Oct 26, 2022 |
| Gigabyte      | Z690 UD DDR4                | [c838769296](https://linux-hardware.org/?probe=c838769296) | Oct 25, 2022 |
| MSI           | H61M-P31/W8                 | [7ba2ecf5f0](https://linux-hardware.org/?probe=7ba2ecf5f0) | Oct 25, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [3cd266dbbb](https://linux-hardware.org/?probe=3cd266dbbb) | Oct 25, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c77d3dfeba](https://linux-hardware.org/?probe=c77d3dfeba) | Oct 25, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [df05c11ff4](https://linux-hardware.org/?probe=df05c11ff4) | Oct 24, 2022 |
| MSI           | B560M PRO-VDH               | [0a2cbff604](https://linux-hardware.org/?probe=0a2cbff604) | Oct 24, 2022 |
| Gigabyte      | H310M H                     | [3a8627fb53](https://linux-hardware.org/?probe=3a8627fb53) | Oct 24, 2022 |
| MSI           | 970A-G46                    | [38541ac772](https://linux-hardware.org/?probe=38541ac772) | Oct 24, 2022 |
| ASUSTek       | A88X-PLUS                   | [7435d326b7](https://linux-hardware.org/?probe=7435d326b7) | Oct 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [04ea0c7dd2](https://linux-hardware.org/?probe=04ea0c7dd2) | Oct 23, 2022 |
| Lenovo        | SHARKBAY NOK                | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [cfb362baf3](https://linux-hardware.org/?probe=cfb362baf3) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e14654d246](https://linux-hardware.org/?probe=e14654d246) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c0867dfce4](https://linux-hardware.org/?probe=c0867dfce4) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6199e2daaa](https://linux-hardware.org/?probe=6199e2daaa) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [dc48a995c4](https://linux-hardware.org/?probe=dc48a995c4) | Oct 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | [32cd9cd246](https://linux-hardware.org/?probe=32cd9cd246) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | [b2cc208474](https://linux-hardware.org/?probe=b2cc208474) | Oct 22, 2022 |
| MSI           | PRO Z690-A DDR4             | [1056e456bc](https://linux-hardware.org/?probe=1056e456bc) | Oct 22, 2022 |
| ASRock        | A320M-HD                    | [d8f21a8ec6](https://linux-hardware.org/?probe=d8f21a8ec6) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | [9f293160d5](https://linux-hardware.org/?probe=9f293160d5) | Oct 22, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [624b9f3b57](https://linux-hardware.org/?probe=624b9f3b57) | Oct 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [15c764f6fa](https://linux-hardware.org/?probe=15c764f6fa) | Oct 21, 2022 |
| ASRock        | B450M Steel Legend          | [2a9b4f61c6](https://linux-hardware.org/?probe=2a9b4f61c6) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [fb86c213ca](https://linux-hardware.org/?probe=fb86c213ca) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [02b0d2ded2](https://linux-hardware.org/?probe=02b0d2ded2) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [86950688ac](https://linux-hardware.org/?probe=86950688ac) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [ede27fb1d0](https://linux-hardware.org/?probe=ede27fb1d0) | Oct 19, 2022 |
| Gigabyte      | X79-UP4                     | [c6e10b3bcb](https://linux-hardware.org/?probe=c6e10b3bcb) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [c84509fb21](https://linux-hardware.org/?probe=c84509fb21) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [e3ce426450](https://linux-hardware.org/?probe=e3ce426450) | Oct 18, 2022 |
| HP            | 339A                        | [e168e3b75b](https://linux-hardware.org/?probe=e168e3b75b) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [e8e5ae4784](https://linux-hardware.org/?probe=e8e5ae4784) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | [40c27af11f](https://linux-hardware.org/?probe=40c27af11f) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | [25fdbfba33](https://linux-hardware.org/?probe=25fdbfba33) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [0a30a79788](https://linux-hardware.org/?probe=0a30a79788) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [a4f5a5b0be](https://linux-hardware.org/?probe=a4f5a5b0be) | Oct 17, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | [dfdde1675c](https://linux-hardware.org/?probe=dfdde1675c) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [e2991c4619](https://linux-hardware.org/?probe=e2991c4619) | Oct 17, 2022 |
| MSI           | MEG X570 UNIFY              | [0ec570b33c](https://linux-hardware.org/?probe=0ec570b33c) | Oct 16, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [def577cdb8](https://linux-hardware.org/?probe=def577cdb8) | Oct 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [bf7cebc10e](https://linux-hardware.org/?probe=bf7cebc10e) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0e0a3b9cf0](https://linux-hardware.org/?probe=0e0a3b9cf0) | Oct 16, 2022 |
| ASUSTek       | PRIME H270-PRO              | [3c2eef945d](https://linux-hardware.org/?probe=3c2eef945d) | Oct 16, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | [d91f9fb542](https://linux-hardware.org/?probe=d91f9fb542) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [daaa9d8dcc](https://linux-hardware.org/?probe=daaa9d8dcc) | Oct 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [b7ebef4e11](https://linux-hardware.org/?probe=b7ebef4e11) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M90 5536A76     | [d6f13cdb14](https://linux-hardware.org/?probe=d6f13cdb14) | Oct 15, 2022 |
| ASRock        | B450 Steel Legend           | [b1de0617da](https://linux-hardware.org/?probe=b1de0617da) | Oct 15, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2e1434c4ff](https://linux-hardware.org/?probe=2e1434c4ff) | Oct 14, 2022 |
| ASRock        | X570 Taichi                 | [6b78ca11b4](https://linux-hardware.org/?probe=6b78ca11b4) | Oct 14, 2022 |
| Pegatron      | 2AD5                        | [512238de46](https://linux-hardware.org/?probe=512238de46) | Oct 12, 2022 |
| MSI           | B450M MORTAR MAX            | [c82722f056](https://linux-hardware.org/?probe=c82722f056) | Oct 12, 2022 |
| ASRock        | B450 Gaming K4              | [4b0116a8c6](https://linux-hardware.org/?probe=4b0116a8c6) | Oct 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3462676a1d](https://linux-hardware.org/?probe=3462676a1d) | Oct 10, 2022 |
| Dell          | 0GM819                      | [e0266a8468](https://linux-hardware.org/?probe=e0266a8468) | Oct 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [e26fca4929](https://linux-hardware.org/?probe=e26fca4929) | Oct 09, 2022 |
| Dell          | 0J3C2F A01                  | [d1001275c6](https://linux-hardware.org/?probe=d1001275c6) | Oct 09, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | [324f177fa7](https://linux-hardware.org/?probe=324f177fa7) | Oct 08, 2022 |
| ASUSTek       | PRIME B450M-K               | [53ca822dcd](https://linux-hardware.org/?probe=53ca822dcd) | Oct 07, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [8ad48ccaec](https://linux-hardware.org/?probe=8ad48ccaec) | Oct 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [9525ea0de3](https://linux-hardware.org/?probe=9525ea0de3) | Oct 07, 2022 |
| ASUSTek       | PRIME X570-PRO              | [83a49e76b9](https://linux-hardware.org/?probe=83a49e76b9) | Oct 06, 2022 |
| ASRock        | B450M/ac                    | [af66fef71a](https://linux-hardware.org/?probe=af66fef71a) | Oct 06, 2022 |
| HP            | 3398                        | [c70e10b68b](https://linux-hardware.org/?probe=c70e10b68b) | Oct 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [512c095e83](https://linux-hardware.org/?probe=512c095e83) | Oct 06, 2022 |
| ASUSTek       | Maximus VII HERO            | [d4a282a4b8](https://linux-hardware.org/?probe=d4a282a4b8) | Oct 06, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [9232451f1a](https://linux-hardware.org/?probe=9232451f1a) | Oct 06, 2022 |
| HP            | 3398                        | [7dd62dded1](https://linux-hardware.org/?probe=7dd62dded1) | Oct 05, 2022 |
| Intel         | DQ35JO AAD82085-801         | [4056c37c50](https://linux-hardware.org/?probe=4056c37c50) | Oct 04, 2022 |
| ASUSTek       | Maximus VII HERO            | [7fbccd3f20](https://linux-hardware.org/?probe=7fbccd3f20) | Oct 03, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [54c3aa5cc5](https://linux-hardware.org/?probe=54c3aa5cc5) | Oct 02, 2022 |
| Dell          | 0KWVT8 A03                  | [ae706e478d](https://linux-hardware.org/?probe=ae706e478d) | Oct 02, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [692b59019a](https://linux-hardware.org/?probe=692b59019a) | Oct 01, 2022 |
| ASUSTek       | GRYPHON Z87                 | [3f01bbaa12](https://linux-hardware.org/?probe=3f01bbaa12) | Sep 30, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [7a2f334861](https://linux-hardware.org/?probe=7a2f334861) | Sep 29, 2022 |
| ASUSTek       | Maximus VII HERO            | [d23d86be40](https://linux-hardware.org/?probe=d23d86be40) | Sep 28, 2022 |
| Dell          | 0NDYHG A01                  | [7a5df20f28](https://linux-hardware.org/?probe=7a5df20f28) | Sep 28, 2022 |
| Dell          | 09M8Y8 A01                  | [f129c4da4a](https://linux-hardware.org/?probe=f129c4da4a) | Sep 28, 2022 |
| HP            | 83E9                        | [c24faa3c5b](https://linux-hardware.org/?probe=c24faa3c5b) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2c52de3e56](https://linux-hardware.org/?probe=2c52de3e56) | Sep 27, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | [fbc760a09c](https://linux-hardware.org/?probe=fbc760a09c) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9fff405744](https://linux-hardware.org/?probe=9fff405744) | Sep 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | [34035b63b6](https://linux-hardware.org/?probe=34035b63b6) | Sep 25, 2022 |
| ASRock        | H97M Anniversary            | [289532b8bb](https://linux-hardware.org/?probe=289532b8bb) | Sep 24, 2022 |
| MSI           | Z97-G55 SLI                 | [dc60d66502](https://linux-hardware.org/?probe=dc60d66502) | Sep 24, 2022 |
| System76      | Thelio Mira                 | [2e9601d2a2](https://linux-hardware.org/?probe=2e9601d2a2) | Sep 24, 2022 |
| ASRock        | X570M Pro4                  | [9e8207dfb7](https://linux-hardware.org/?probe=9e8207dfb7) | Sep 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [59c4a7e761](https://linux-hardware.org/?probe=59c4a7e761) | Sep 23, 2022 |
| MSI           | Z97-G55 SLI                 | [27b47d5592](https://linux-hardware.org/?probe=27b47d5592) | Sep 23, 2022 |
| Dell          | 0HHV7N A00                  | [cda6d76f04](https://linux-hardware.org/?probe=cda6d76f04) | Sep 22, 2022 |
| ASRock        | 4X4-V1000                   | [e73062fe01](https://linux-hardware.org/?probe=e73062fe01) | Sep 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [dc49b2baf4](https://linux-hardware.org/?probe=dc49b2baf4) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [07dd388834](https://linux-hardware.org/?probe=07dd388834) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [2c7466119d](https://linux-hardware.org/?probe=2c7466119d) | Sep 21, 2022 |
| HP            | 1589                        | [da376a40a1](https://linux-hardware.org/?probe=da376a40a1) | Sep 20, 2022 |
| Gigabyte      | EX58-UD4P                   | [394aad4be9](https://linux-hardware.org/?probe=394aad4be9) | Sep 20, 2022 |
| ASRock        | AB350 Pro4                  | [61a4ab7c20](https://linux-hardware.org/?probe=61a4ab7c20) | Sep 20, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [df0348739e](https://linux-hardware.org/?probe=df0348739e) | Sep 20, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a0d6f208fb](https://linux-hardware.org/?probe=a0d6f208fb) | Sep 19, 2022 |
| Gigabyte      | B450 AORUS M                | [136eca7e32](https://linux-hardware.org/?probe=136eca7e32) | Sep 19, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [83b0a59729](https://linux-hardware.org/?probe=83b0a59729) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [fa4082533e](https://linux-hardware.org/?probe=fa4082533e) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [a418c3e997](https://linux-hardware.org/?probe=a418c3e997) | Sep 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [bd7ddbf9f7](https://linux-hardware.org/?probe=bd7ddbf9f7) | Sep 18, 2022 |
| Alienware     | 0CPDXD A00                  | [f65bdb053d](https://linux-hardware.org/?probe=f65bdb053d) | Sep 18, 2022 |
| ASUSTek       | PRIME A520M-A II            | [0bec316a0b](https://linux-hardware.org/?probe=0bec316a0b) | Sep 17, 2022 |
| Minix         | NEO Z83-4 V1.1              | [545552c43e](https://linux-hardware.org/?probe=545552c43e) | Sep 16, 2022 |
| NZXT          | N7 B550                     | [7deb3849db](https://linux-hardware.org/?probe=7deb3849db) | Sep 16, 2022 |
| ASRock        | Z97 Extreme6                | [2c90f58ae4](https://linux-hardware.org/?probe=2c90f58ae4) | Sep 16, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [3f9fc3fc62](https://linux-hardware.org/?probe=3f9fc3fc62) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6de8f25119](https://linux-hardware.org/?probe=6de8f25119) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9c97b9e2c1](https://linux-hardware.org/?probe=9c97b9e2c1) | Sep 14, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [64795f6f69](https://linux-hardware.org/?probe=64795f6f69) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cacc85ca2e](https://linux-hardware.org/?probe=cacc85ca2e) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0c6d5b57dd](https://linux-hardware.org/?probe=0c6d5b57dd) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | [1b5e2c2e0a](https://linux-hardware.org/?probe=1b5e2c2e0a) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | [649c5fb453](https://linux-hardware.org/?probe=649c5fb453) | Sep 13, 2022 |
| ASUSTek       | P8P67 DELUXE                | [89fb49d843](https://linux-hardware.org/?probe=89fb49d843) | Sep 13, 2022 |
| ASUSTek       | P8P67 DELUXE                | [a385e1220b](https://linux-hardware.org/?probe=a385e1220b) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [4fbc7a765f](https://linux-hardware.org/?probe=4fbc7a765f) | Sep 12, 2022 |
| ECS           | Nettle3                     | [23f7f8708c](https://linux-hardware.org/?probe=23f7f8708c) | Sep 12, 2022 |
| System76      | Thelio thelio-r2            | [2f6745bad5](https://linux-hardware.org/?probe=2f6745bad5) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ce4fc6576c](https://linux-hardware.org/?probe=ce4fc6576c) | Sep 11, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [29da7835e4](https://linux-hardware.org/?probe=29da7835e4) | Sep 10, 2022 |
| ASUSTek       | M4N72-E                     | [83be030771](https://linux-hardware.org/?probe=83be030771) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b3aa7bd9ca](https://linux-hardware.org/?probe=b3aa7bd9ca) | Sep 09, 2022 |
| Unknown       | Unknown                     | [87f754ac29](https://linux-hardware.org/?probe=87f754ac29) | Sep 09, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [1be1b9b040](https://linux-hardware.org/?probe=1be1b9b040) | Sep 09, 2022 |
| Intel         | X99                         | [9ebaa38244](https://linux-hardware.org/?probe=9ebaa38244) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | [dbfdcae895](https://linux-hardware.org/?probe=dbfdcae895) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | [4167167e38](https://linux-hardware.org/?probe=4167167e38) | Sep 08, 2022 |
| Dell          | 0TTDMJ A00                  | [66aa958693](https://linux-hardware.org/?probe=66aa958693) | Sep 08, 2022 |
| ASRock        | B450M/ac                    | [efb78c5d25](https://linux-hardware.org/?probe=efb78c5d25) | Sep 07, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [483a414289](https://linux-hardware.org/?probe=483a414289) | Sep 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0efcfb2037](https://linux-hardware.org/?probe=0efcfb2037) | Sep 07, 2022 |
| Acer          | 1.0                         | [b81c44ff15](https://linux-hardware.org/?probe=b81c44ff15) | Sep 06, 2022 |
| Gigabyte      | Z77-D3H                     | [47d065ed5c](https://linux-hardware.org/?probe=47d065ed5c) | Sep 06, 2022 |
| Dell          | 088DT1 A01                  | [c17c4d475f](https://linux-hardware.org/?probe=c17c4d475f) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [8b964572d7](https://linux-hardware.org/?probe=8b964572d7) | Sep 04, 2022 |
| Alienware     | 0NWN7M A00                  | [e254b049c3](https://linux-hardware.org/?probe=e254b049c3) | Sep 04, 2022 |
| Dell          | 0KWVT8 A03                  | [bd0c518002](https://linux-hardware.org/?probe=bd0c518002) | Sep 03, 2022 |
| ASUSTek       | PRIME B550M-A               | [81eb6e9f4e](https://linux-hardware.org/?probe=81eb6e9f4e) | Sep 03, 2022 |
| ASUSTek       | M5A97                       | [de7dc826b0](https://linux-hardware.org/?probe=de7dc826b0) | Sep 03, 2022 |
| Intel         | DX58SO AAE29331-702         | [24c48ddc3e](https://linux-hardware.org/?probe=24c48ddc3e) | Sep 03, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [7b914b0347](https://linux-hardware.org/?probe=7b914b0347) | Sep 03, 2022 |
| HP            | 1497                        | [a8566c45a9](https://linux-hardware.org/?probe=a8566c45a9) | Sep 03, 2022 |
| MSI           | MEG Z390 ACE                | [1f702cfc06](https://linux-hardware.org/?probe=1f702cfc06) | Sep 03, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [39cb364d6f](https://linux-hardware.org/?probe=39cb364d6f) | Sep 03, 2022 |
| MSI           | B450 GAMING PLUS            | [3561723d92](https://linux-hardware.org/?probe=3561723d92) | Sep 02, 2022 |
| Gigabyte      | H61M-S1                     | [b54a09966b](https://linux-hardware.org/?probe=b54a09966b) | Sep 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [d664029076](https://linux-hardware.org/?probe=d664029076) | Sep 02, 2022 |
| HP            | 87D6 SMVB                   | [8efd1ba4e0](https://linux-hardware.org/?probe=8efd1ba4e0) | Sep 02, 2022 |
| Gigabyte      | B85M-HD3                    | [4f4717cb85](https://linux-hardware.org/?probe=4f4717cb85) | Sep 02, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [fb12fe29dd](https://linux-hardware.org/?probe=fb12fe29dd) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [e311938d4a](https://linux-hardware.org/?probe=e311938d4a) | Sep 01, 2022 |
| ASRock        | B450M/ac                    | [393a08345e](https://linux-hardware.org/?probe=393a08345e) | Sep 01, 2022 |
| Acer          | Aspire X3400                | [705a3242ae](https://linux-hardware.org/?probe=705a3242ae) | Sep 01, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [1dd7a06125](https://linux-hardware.org/?probe=1dd7a06125) | Aug 31, 2022 |
| Acer          | Aspire X3400                | [cb5288e92d](https://linux-hardware.org/?probe=cb5288e92d) | Aug 31, 2022 |
| Acer          | Aspire X3400                | [5e9e5dd1ce](https://linux-hardware.org/?probe=5e9e5dd1ce) | Aug 31, 2022 |
| Lenovo        | MAHOBAY                     | [53af4f5de7](https://linux-hardware.org/?probe=53af4f5de7) | Aug 30, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d0ca11a18a](https://linux-hardware.org/?probe=d0ca11a18a) | Aug 29, 2022 |
| ASRock        | B450M Pro4 R2.0             | [fb155ef3bd](https://linux-hardware.org/?probe=fb155ef3bd) | Aug 29, 2022 |
| Dell          | 0KWVT8 A03                  | [b91ce43523](https://linux-hardware.org/?probe=b91ce43523) | Aug 29, 2022 |
| HP            | 1497                        | [625185d1db](https://linux-hardware.org/?probe=625185d1db) | Aug 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [281360b58a](https://linux-hardware.org/?probe=281360b58a) | Aug 29, 2022 |
| BESSTAR Te... | UM700                       | [13fdf5ef5e](https://linux-hardware.org/?probe=13fdf5ef5e) | Aug 29, 2022 |
| MSI           | B450M MORTAR MAX            | [2d89536f80](https://linux-hardware.org/?probe=2d89536f80) | Aug 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a328df0016](https://linux-hardware.org/?probe=a328df0016) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | [3a448c33f9](https://linux-hardware.org/?probe=3a448c33f9) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | [4210c6a219](https://linux-hardware.org/?probe=4210c6a219) | Aug 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [f07bd2b99b](https://linux-hardware.org/?probe=f07bd2b99b) | Aug 28, 2022 |
| Lenovo        | Bantry CRB 31900058 STD     | [d0c37f7188](https://linux-hardware.org/?probe=d0c37f7188) | Aug 28, 2022 |
| Gigabyte      | H67A-USB3-B3                | [b04fc1333e](https://linux-hardware.org/?probe=b04fc1333e) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [a90735a9e9](https://linux-hardware.org/?probe=a90735a9e9) | Aug 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [704ce84e6a](https://linux-hardware.org/?probe=704ce84e6a) | Aug 27, 2022 |
| ASRock        | B560 Steel Legend           | [55ebdff357](https://linux-hardware.org/?probe=55ebdff357) | Aug 26, 2022 |
| HP            | 1850                        | [85b5eedc40](https://linux-hardware.org/?probe=85b5eedc40) | Aug 26, 2022 |
| ASRock        | X570 Creator                | [612ada6405](https://linux-hardware.org/?probe=612ada6405) | Aug 26, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [d988a14a82](https://linux-hardware.org/?probe=d988a14a82) | Aug 26, 2022 |
| Acer          | Aspire X3400                | [81acff75f6](https://linux-hardware.org/?probe=81acff75f6) | Aug 25, 2022 |
| Dell          | 0KWVT8 A03                  | [967ff51388](https://linux-hardware.org/?probe=967ff51388) | Aug 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [18102e8a9a](https://linux-hardware.org/?probe=18102e8a9a) | Aug 24, 2022 |
| ASRock        | B660-ITX                    | [316ae22af8](https://linux-hardware.org/?probe=316ae22af8) | Aug 24, 2022 |
| HP            | 3647h                       | [dc17a52501](https://linux-hardware.org/?probe=dc17a52501) | Aug 23, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [8118d6f78c](https://linux-hardware.org/?probe=8118d6f78c) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [beb3c92510](https://linux-hardware.org/?probe=beb3c92510) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [8e57e188c9](https://linux-hardware.org/?probe=8e57e188c9) | Aug 23, 2022 |
| ASUSTek       | P9X79 LE                    | [1fbde15177](https://linux-hardware.org/?probe=1fbde15177) | Aug 22, 2022 |
| ASRock        | X470 Taichi                 | [8f7d642c46](https://linux-hardware.org/?probe=8f7d642c46) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e8bee7737a](https://linux-hardware.org/?probe=e8bee7737a) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b182084c88](https://linux-hardware.org/?probe=b182084c88) | Aug 22, 2022 |
| MSI           | FM2-A55M-E33                | [fac0116bf7](https://linux-hardware.org/?probe=fac0116bf7) | Aug 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [23c07b5d2b](https://linux-hardware.org/?probe=23c07b5d2b) | Aug 21, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [c717f7c6d5](https://linux-hardware.org/?probe=c717f7c6d5) | Aug 21, 2022 |
| MSI           | Z170A PC MATE               | [8df71394cd](https://linux-hardware.org/?probe=8df71394cd) | Aug 20, 2022 |
| Gigabyte      | B550M DS3H                  | [774796ffbd](https://linux-hardware.org/?probe=774796ffbd) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [3a7a62f6f8](https://linux-hardware.org/?probe=3a7a62f6f8) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [93c5d7b0f9](https://linux-hardware.org/?probe=93c5d7b0f9) | Aug 19, 2022 |
| Dell          | 0KWVT8 A03                  | [7af77fd850](https://linux-hardware.org/?probe=7af77fd850) | Aug 18, 2022 |
| Gigabyte      | X299 AORUS MASTER           | [8d76a030ca](https://linux-hardware.org/?probe=8d76a030ca) | Aug 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8a1a495053](https://linux-hardware.org/?probe=8a1a495053) | Aug 18, 2022 |
| ASUSTek       | B150M-C/BR                  | [b15c721e4c](https://linux-hardware.org/?probe=b15c721e4c) | Aug 18, 2022 |
| Acer          | Predator PO5-600s V:1.0     | [6e8b922033](https://linux-hardware.org/?probe=6e8b922033) | Aug 18, 2022 |
| MSI           | B450-A PRO MAX              | [9a1a049600](https://linux-hardware.org/?probe=9a1a049600) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [169469e8b6](https://linux-hardware.org/?probe=169469e8b6) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d98e5c8b5e](https://linux-hardware.org/?probe=d98e5c8b5e) | Aug 17, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [1e4e125d11](https://linux-hardware.org/?probe=1e4e125d11) | Aug 17, 2022 |
| HP            | 2215                        | [71a33dc713](https://linux-hardware.org/?probe=71a33dc713) | Aug 17, 2022 |
| HP            | 2215                        | [aa386126ad](https://linux-hardware.org/?probe=aa386126ad) | Aug 17, 2022 |
| MSI           | H110M PRO-VH PLUS           | [e6e4efd93a](https://linux-hardware.org/?probe=e6e4efd93a) | Aug 17, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [8441adcca9](https://linux-hardware.org/?probe=8441adcca9) | Aug 17, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [5c2c3d81ef](https://linux-hardware.org/?probe=5c2c3d81ef) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [0a5775d3a8](https://linux-hardware.org/?probe=0a5775d3a8) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e75de6c205](https://linux-hardware.org/?probe=e75de6c205) | Aug 15, 2022 |
| Gigabyte      | Z77X-UD5H                   | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| HP            | 8054                        | [75e3136f50](https://linux-hardware.org/?probe=75e3136f50) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [5a5538ce52](https://linux-hardware.org/?probe=5a5538ce52) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [5ef85261aa](https://linux-hardware.org/?probe=5ef85261aa) | Aug 13, 2022 |
| Gigabyte      | H97N-WIFI                   | [966a3e1593](https://linux-hardware.org/?probe=966a3e1593) | Aug 13, 2022 |
| BESSTAR Te... | UM700                       | [81a59240ea](https://linux-hardware.org/?probe=81a59240ea) | Aug 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | [29e8c10282](https://linux-hardware.org/?probe=29e8c10282) | Aug 13, 2022 |
| MSI           | Z87-G45 GAMING              | [2f541727e1](https://linux-hardware.org/?probe=2f541727e1) | Aug 12, 2022 |
| ASRock        | A320M                       | [1e0a574078](https://linux-hardware.org/?probe=1e0a574078) | Aug 12, 2022 |
| ASUSTek       | H97-PLUS                    | [4ca1b1050d](https://linux-hardware.org/?probe=4ca1b1050d) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A               | [230d7247c0](https://linux-hardware.org/?probe=230d7247c0) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| HP            | 3397                        | [9beccd0ca8](https://linux-hardware.org/?probe=9beccd0ca8) | Aug 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [d0b0186eb9](https://linux-hardware.org/?probe=d0b0186eb9) | Aug 09, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [80bb75a792](https://linux-hardware.org/?probe=80bb75a792) | Aug 07, 2022 |
| ASUSTek       | Z87-K                       | [d1954b42ae](https://linux-hardware.org/?probe=d1954b42ae) | Aug 06, 2022 |
| HP            | 1998                        | [5164a156e2](https://linux-hardware.org/?probe=5164a156e2) | Aug 05, 2022 |
| Intel         | D955XBK AAC96732-501        | [d6463d7629](https://linux-hardware.org/?probe=d6463d7629) | Aug 05, 2022 |
| MSI           | 970A-G43                    | [a77e1878ae](https://linux-hardware.org/?probe=a77e1878ae) | Aug 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [56b0b42020](https://linux-hardware.org/?probe=56b0b42020) | Aug 04, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [585bf3495e](https://linux-hardware.org/?probe=585bf3495e) | Aug 04, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [2d017b110e](https://linux-hardware.org/?probe=2d017b110e) | Aug 04, 2022 |
| Gigabyte      | AX370-Gaming K7             | [14447cf212](https://linux-hardware.org/?probe=14447cf212) | Aug 04, 2022 |
| ASUSTek       | P8Z77-V LK                  | [9878a3365c](https://linux-hardware.org/?probe=9878a3365c) | Aug 03, 2022 |
| Intel         | D955XBK AAC96732-501        | [ed4b3ec577](https://linux-hardware.org/?probe=ed4b3ec577) | Aug 03, 2022 |
| Intel         | DP55WB AAE64798-208         | [0c66cac06d](https://linux-hardware.org/?probe=0c66cac06d) | Aug 03, 2022 |
| ASUSTek       | PRIME B550M-A               | [3f1ccf427a](https://linux-hardware.org/?probe=3f1ccf427a) | Aug 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [73b2c51a7e](https://linux-hardware.org/?probe=73b2c51a7e) | Aug 02, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | [6127d6e7a3](https://linux-hardware.org/?probe=6127d6e7a3) | Aug 02, 2022 |
| Gigabyte      | A520I AC                    | [0bf3f1a8a2](https://linux-hardware.org/?probe=0bf3f1a8a2) | Jul 31, 2022 |
| EVGA          | 134-KS-E377                 | [2624cfe274](https://linux-hardware.org/?probe=2624cfe274) | Jul 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [cc3deb0a17](https://linux-hardware.org/?probe=cc3deb0a17) | Jul 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| MSI           | MEG Z690 UNIFY              | [571f500e5e](https://linux-hardware.org/?probe=571f500e5e) | Jul 30, 2022 |
| Dell          | 0TP412                      | [c6138574f4](https://linux-hardware.org/?probe=c6138574f4) | Jul 30, 2022 |
| Gigabyte      | A520I AC                    | [f0d27ae2f0](https://linux-hardware.org/?probe=f0d27ae2f0) | Jul 30, 2022 |
| MSI           | B450M MORTAR MAX            | [1316e90024](https://linux-hardware.org/?probe=1316e90024) | Jul 30, 2022 |
| HP            | 2215                        | [6e351e6da3](https://linux-hardware.org/?probe=6e351e6da3) | Jul 30, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [31b2d82a52](https://linux-hardware.org/?probe=31b2d82a52) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | [622aa6421e](https://linux-hardware.org/?probe=622aa6421e) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | [d8c0404bad](https://linux-hardware.org/?probe=d8c0404bad) | Jul 29, 2022 |
| MACHINIST     | X79 V2.82H                  | [29694e2098](https://linux-hardware.org/?probe=29694e2098) | Jul 29, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [b25ca31168](https://linux-hardware.org/?probe=b25ca31168) | Jul 27, 2022 |
| MSI           | PRO Z690-A DDR4             | [2d81f40aad](https://linux-hardware.org/?probe=2d81f40aad) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| Dell          | 0F896N A02                  | [ede9425ed8](https://linux-hardware.org/?probe=ede9425ed8) | Jul 27, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [4812de622f](https://linux-hardware.org/?probe=4812de622f) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| ASUSTek       | PRIME Z390-A                | [b8e8d2b6c4](https://linux-hardware.org/?probe=b8e8d2b6c4) | Jul 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [567addf380](https://linux-hardware.org/?probe=567addf380) | Jul 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [221bb14fbd](https://linux-hardware.org/?probe=221bb14fbd) | Jul 24, 2022 |
| MSI           | MEG X570 ACE                | [f13fde648e](https://linux-hardware.org/?probe=f13fde648e) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8f131b55b9](https://linux-hardware.org/?probe=8f131b55b9) | Jul 22, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [9689ac8020](https://linux-hardware.org/?probe=9689ac8020) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5a52692425](https://linux-hardware.org/?probe=5a52692425) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f524dac3fa](https://linux-hardware.org/?probe=f524dac3fa) | Jul 20, 2022 |
| MSI           | Z590-A PRO                  | [9500cfd7e1](https://linux-hardware.org/?probe=9500cfd7e1) | Jul 19, 2022 |
| Dell          | 02YYK5 A01                  | [94b2dc99fa](https://linux-hardware.org/?probe=94b2dc99fa) | Jul 19, 2022 |
| Lenovo        | MAHOBAY                     | [c1c146a0f9](https://linux-hardware.org/?probe=c1c146a0f9) | Jul 18, 2022 |
| Gigabyte      | B75M-D3H                    | [1c0d0a79d1](https://linux-hardware.org/?probe=1c0d0a79d1) | Jul 17, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | [3c55557131](https://linux-hardware.org/?probe=3c55557131) | Jul 17, 2022 |
| Gigabyte      | H97M-Gaming 3               | [a72ad8ba14](https://linux-hardware.org/?probe=a72ad8ba14) | Jul 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [36ad4a7384](https://linux-hardware.org/?probe=36ad4a7384) | Jul 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [a23b73c3ff](https://linux-hardware.org/?probe=a23b73c3ff) | Jul 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [2e73a9947c](https://linux-hardware.org/?probe=2e73a9947c) | Jul 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c9ff108124](https://linux-hardware.org/?probe=c9ff108124) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M90p 5864A1U    | [406232d6c2](https://linux-hardware.org/?probe=406232d6c2) | Jul 15, 2022 |
| MSI           | Z170A GAMING M5             | [16d2d7469b](https://linux-hardware.org/?probe=16d2d7469b) | Jul 15, 2022 |
| Gigabyte      | H310M S2 x.x                | [a55538b651](https://linux-hardware.org/?probe=a55538b651) | Jul 14, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [608d209fe5](https://linux-hardware.org/?probe=608d209fe5) | Jul 14, 2022 |
| ASRock        | Z77 Pro4-M                  | [69b486ea31](https://linux-hardware.org/?probe=69b486ea31) | Jul 14, 2022 |
| Dell          | 02YYK5 A01                  | [ca4bfe598b](https://linux-hardware.org/?probe=ca4bfe598b) | Jul 14, 2022 |
| ASUSTek       | M4A79XTD EVO                | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| ASRock        | B450M Steel Legend          | [3732c0ad0c](https://linux-hardware.org/?probe=3732c0ad0c) | Jul 13, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [a6d5a615d0](https://linux-hardware.org/?probe=a6d5a615d0) | Jul 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [97b45f9af7](https://linux-hardware.org/?probe=97b45f9af7) | Jul 12, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [d7e4d34816](https://linux-hardware.org/?probe=d7e4d34816) | Jul 12, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [a3c14e06c9](https://linux-hardware.org/?probe=a3c14e06c9) | Jul 11, 2022 |
| MSI           | P67A-C43                    | [c76725f62c](https://linux-hardware.org/?probe=c76725f62c) | Jul 11, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [84e5c2ab51](https://linux-hardware.org/?probe=84e5c2ab51) | Jul 11, 2022 |
| ASUSTek       | P5Q-PRO                     | [ad6eedb5e5](https://linux-hardware.org/?probe=ad6eedb5e5) | Jul 10, 2022 |
| ASUSTek       | Z170-A                      | [1ac13f76b1](https://linux-hardware.org/?probe=1ac13f76b1) | Jul 10, 2022 |
| Dell          | 042P49 A02                  | [1b8b98b54d](https://linux-hardware.org/?probe=1b8b98b54d) | Jul 10, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [0e0d93b899](https://linux-hardware.org/?probe=0e0d93b899) | Jul 10, 2022 |
| ASUSTek       | P5Q-PRO                     | [9860ca66f6](https://linux-hardware.org/?probe=9860ca66f6) | Jul 09, 2022 |
| Gigabyte      | B450 AORUS M                | [5d50b40871](https://linux-hardware.org/?probe=5d50b40871) | Jul 09, 2022 |
| HP            | 1495                        | [3e67bd3405](https://linux-hardware.org/?probe=3e67bd3405) | Jul 09, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [a374367376](https://linux-hardware.org/?probe=a374367376) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [fe383d7488](https://linux-hardware.org/?probe=fe383d7488) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [786c9e341c](https://linux-hardware.org/?probe=786c9e341c) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [833f3df27a](https://linux-hardware.org/?probe=833f3df27a) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [199e7db55a](https://linux-hardware.org/?probe=199e7db55a) | Jul 09, 2022 |
| Gigabyte      | B550 AORUS PRO AX           | [9ad45447d4](https://linux-hardware.org/?probe=9ad45447d4) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6ebe4f89b7](https://linux-hardware.org/?probe=6ebe4f89b7) | Jul 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [3458084b51](https://linux-hardware.org/?probe=3458084b51) | Jul 08, 2022 |
| HP            | 3398                        | [fb1290d5b3](https://linux-hardware.org/?probe=fb1290d5b3) | Jul 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8b1a622249](https://linux-hardware.org/?probe=8b1a622249) | Jul 07, 2022 |
| ASUSTek       | PRIME Z390-A                | [0e7b73b341](https://linux-hardware.org/?probe=0e7b73b341) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [9c2efc454e](https://linux-hardware.org/?probe=9c2efc454e) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [eb5d4499aa](https://linux-hardware.org/?probe=eb5d4499aa) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [e068e197b4](https://linux-hardware.org/?probe=e068e197b4) | Jul 06, 2022 |
| Dell          | 0200DY A00                  | [442b0c2a46](https://linux-hardware.org/?probe=442b0c2a46) | Jul 06, 2022 |
| Soyo          | SY-A68M FS V2.0             | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [7a6f484b16](https://linux-hardware.org/?probe=7a6f484b16) | Jul 06, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [bfa2b2f092](https://linux-hardware.org/?probe=bfa2b2f092) | Jul 05, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [161f8c2665](https://linux-hardware.org/?probe=161f8c2665) | Jul 03, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [15118ef9fd](https://linux-hardware.org/?probe=15118ef9fd) | Jul 03, 2022 |
| HP            | 18E7                        | [8f2b2cb5e5](https://linux-hardware.org/?probe=8f2b2cb5e5) | Jul 02, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7da3547526](https://linux-hardware.org/?probe=7da3547526) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d979555615](https://linux-hardware.org/?probe=d979555615) | Jul 01, 2022 |
| ASRock        | B450 Gaming K4              | [2bdfc5f472](https://linux-hardware.org/?probe=2bdfc5f472) | Jul 01, 2022 |
| MSI           | B250M PRO-VD                | [b48e88849b](https://linux-hardware.org/?probe=b48e88849b) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [8c29343495](https://linux-hardware.org/?probe=8c29343495) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [2631bf2ae1](https://linux-hardware.org/?probe=2631bf2ae1) | Jul 01, 2022 |
| HP            | 18E7                        | [1808b6dee4](https://linux-hardware.org/?probe=1808b6dee4) | Jul 01, 2022 |
| Dell          | 0HHV7N A00                  | [41255f7150](https://linux-hardware.org/?probe=41255f7150) | Jun 30, 2022 |
| ASRock        | X399 Taichi                 | [caea75035f](https://linux-hardware.org/?probe=caea75035f) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | [b85b1f9277](https://linux-hardware.org/?probe=b85b1f9277) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | [67dc174a62](https://linux-hardware.org/?probe=67dc174a62) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | [f01192b57e](https://linux-hardware.org/?probe=f01192b57e) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [0a66ce61c6](https://linux-hardware.org/?probe=0a66ce61c6) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [f2b790de57](https://linux-hardware.org/?probe=f2b790de57) | Jun 29, 2022 |
| HP            | 3647h                       | [3227f38f98](https://linux-hardware.org/?probe=3227f38f98) | Jun 28, 2022 |
| Gigabyte      | Z170-Gaming K3              | [70dc9ba605](https://linux-hardware.org/?probe=70dc9ba605) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | [8efb1d3556](https://linux-hardware.org/?probe=8efb1d3556) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | [5b239d8bba](https://linux-hardware.org/?probe=5b239d8bba) | Jun 28, 2022 |
| ASRock        | B450 Gaming K4              | [6ecc609381](https://linux-hardware.org/?probe=6ecc609381) | Jun 27, 2022 |
| ASRock        | B450 Steel Legend           | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| ASUSTek       | VM40B                       | [35f67bace1](https://linux-hardware.org/?probe=35f67bace1) | Jun 26, 2022 |
| Dell          | 0D6H9T A00                  | [fd65f44d25](https://linux-hardware.org/?probe=fd65f44d25) | Jun 26, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [01fcd4495e](https://linux-hardware.org/?probe=01fcd4495e) | Jun 25, 2022 |
| Dell          | 040DDP A00                  | [02721926a7](https://linux-hardware.org/?probe=02721926a7) | Jun 25, 2022 |
| MSI           | MAG Z690 TORPEDO            | [44700880cf](https://linux-hardware.org/?probe=44700880cf) | Jun 24, 2022 |
| ASUSTek       | LEUCITE                     | [c4d2ed5723](https://linux-hardware.org/?probe=c4d2ed5723) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | [517a155f9b](https://linux-hardware.org/?probe=517a155f9b) | Jun 24, 2022 |
| Dell          | 0WMJ54 A01                  | [ee865231c1](https://linux-hardware.org/?probe=ee865231c1) | Jun 24, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [055977bdee](https://linux-hardware.org/?probe=055977bdee) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [1e7e58ae1d](https://linux-hardware.org/?probe=1e7e58ae1d) | Jun 23, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [0bd1e7d592](https://linux-hardware.org/?probe=0bd1e7d592) | Jun 23, 2022 |
| ASUSTek       | PRIME B550M-A               | [d4492d1e5d](https://linux-hardware.org/?probe=d4492d1e5d) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ae30cadddf](https://linux-hardware.org/?probe=ae30cadddf) | Jun 22, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [21d1dc43e6](https://linux-hardware.org/?probe=21d1dc43e6) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [27bc9defca](https://linux-hardware.org/?probe=27bc9defca) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [941b96e6ab](https://linux-hardware.org/?probe=941b96e6ab) | Jun 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d5fd58e3b0](https://linux-hardware.org/?probe=d5fd58e3b0) | Jun 21, 2022 |
| ASUSTek       | PRIME Z370-A                | [8dca736a46](https://linux-hardware.org/?probe=8dca736a46) | Jun 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [f747d1bfd3](https://linux-hardware.org/?probe=f747d1bfd3) | Jun 21, 2022 |
| System76      | Thelio thelio-r2            | [b9b9d5ffda](https://linux-hardware.org/?probe=b9b9d5ffda) | Jun 21, 2022 |
| MSI           | B550M-A PRO                 | [1765b91360](https://linux-hardware.org/?probe=1765b91360) | Jun 21, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [eb61c79793](https://linux-hardware.org/?probe=eb61c79793) | Jun 21, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [6ddca91c97](https://linux-hardware.org/?probe=6ddca91c97) | Jun 21, 2022 |
| Biostar       | N68S3+                      | [efe83d16ac](https://linux-hardware.org/?probe=efe83d16ac) | Jun 21, 2022 |
| Intel         | MAHOBAY                     | [f615165669](https://linux-hardware.org/?probe=f615165669) | Jun 21, 2022 |
| ASRock        | B450 Gaming K4              | [230bdf84a1](https://linux-hardware.org/?probe=230bdf84a1) | Jun 20, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [ec3bc83e7a](https://linux-hardware.org/?probe=ec3bc83e7a) | Jun 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [d5af99ece6](https://linux-hardware.org/?probe=d5af99ece6) | Jun 20, 2022 |
| ASUSTek       | P8Z77-V LX                  | [ad271e0eec](https://linux-hardware.org/?probe=ad271e0eec) | Jun 19, 2022 |
| Gigabyte      | Z590 AORUS ELITE AX         | [3d4d492e9d](https://linux-hardware.org/?probe=3d4d492e9d) | Jun 19, 2022 |
| Dell          | 0YXT71 A03                  | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| HP            | 158B                        | [b66a2770e7](https://linux-hardware.org/?probe=b66a2770e7) | Jun 18, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [6ba04b0f37](https://linux-hardware.org/?probe=6ba04b0f37) | Jun 18, 2022 |
| BESSTAR Te... | UM700                       | [d0c247db91](https://linux-hardware.org/?probe=d0c247db91) | Jun 17, 2022 |
| Intel         | MAHOBAY                     | [755ead951d](https://linux-hardware.org/?probe=755ead951d) | Jun 17, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [5241a60357](https://linux-hardware.org/?probe=5241a60357) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f4178c276d](https://linux-hardware.org/?probe=f4178c276d) | Jun 16, 2022 |
| Intel         | MAHOBAY                     | [91039940ea](https://linux-hardware.org/?probe=91039940ea) | Jun 16, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [24140a62de](https://linux-hardware.org/?probe=24140a62de) | Jun 16, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [f5af934210](https://linux-hardware.org/?probe=f5af934210) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [7cebf6f4c1](https://linux-hardware.org/?probe=7cebf6f4c1) | Jun 16, 2022 |
| MSI           | B450 TOMAHAWK               | [e11d001f52](https://linux-hardware.org/?probe=e11d001f52) | Jun 15, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [29cfeda814](https://linux-hardware.org/?probe=29cfeda814) | Jun 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [b12643d9ac](https://linux-hardware.org/?probe=b12643d9ac) | Jun 15, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d4e4001c4c](https://linux-hardware.org/?probe=d4e4001c4c) | Jun 15, 2022 |
| Medion        | MS-7728                     | [ae02539c17](https://linux-hardware.org/?probe=ae02539c17) | Jun 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [5be4039515](https://linux-hardware.org/?probe=5be4039515) | Jun 15, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [507c214577](https://linux-hardware.org/?probe=507c214577) | Jun 15, 2022 |
| MSI           | B550-A PRO                  | [f7201ee1de](https://linux-hardware.org/?probe=f7201ee1de) | Jun 14, 2022 |
| HP            | 1905                        | [b3d0170095](https://linux-hardware.org/?probe=b3d0170095) | Jun 14, 2022 |
| HP            | 18E7                        | [9f82638329](https://linux-hardware.org/?probe=9f82638329) | Jun 14, 2022 |
| Lenovo        | 0B98401 PRO                 | [23de86aa97](https://linux-hardware.org/?probe=23de86aa97) | Jun 14, 2022 |
| Alienware     | 0R3FWM A00                  | [6690a39447](https://linux-hardware.org/?probe=6690a39447) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f9e74fdcd3](https://linux-hardware.org/?probe=f9e74fdcd3) | Jun 13, 2022 |
| Dell          | 073MMW A03                  | [3e206d2462](https://linux-hardware.org/?probe=3e206d2462) | Jun 13, 2022 |
| ASUSTek       | Z87-K                       | [cafc34944d](https://linux-hardware.org/?probe=cafc34944d) | Jun 13, 2022 |
| MSI           | B350 PC MATE                | [baf792ad50](https://linux-hardware.org/?probe=baf792ad50) | Jun 12, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [a332c946a2](https://linux-hardware.org/?probe=a332c946a2) | Jun 11, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [d02f89642d](https://linux-hardware.org/?probe=d02f89642d) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | [a4277bcba9](https://linux-hardware.org/?probe=a4277bcba9) | Jun 11, 2022 |
| MSI           | MEG X570 ACE                | [d88374c06d](https://linux-hardware.org/?probe=d88374c06d) | Jun 11, 2022 |
| Unknown       | Unknown                     | [19d1362c66](https://linux-hardware.org/?probe=19d1362c66) | Jun 10, 2022 |
| Gigabyte      | H87M-HD3                    | [eadd724efa](https://linux-hardware.org/?probe=eadd724efa) | Jun 10, 2022 |
| MSI           | H97 GAMING 3                | [839bbee3fa](https://linux-hardware.org/?probe=839bbee3fa) | Jun 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [1fef4f1cf3](https://linux-hardware.org/?probe=1fef4f1cf3) | Jun 10, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [9c7b34c996](https://linux-hardware.org/?probe=9c7b34c996) | Jun 09, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [70254d6e4d](https://linux-hardware.org/?probe=70254d6e4d) | Jun 08, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [44a6f3e33d](https://linux-hardware.org/?probe=44a6f3e33d) | Jun 07, 2022 |
| Gigabyte      | Z390 UD                     | [cd4b8b609f](https://linux-hardware.org/?probe=cd4b8b609f) | Jun 07, 2022 |
| Dell          | 0JW6C6 A01                  | [34d9fc3968](https://linux-hardware.org/?probe=34d9fc3968) | Jun 06, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [a0c155ffb9](https://linux-hardware.org/?probe=a0c155ffb9) | Jun 05, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [816b4e757d](https://linux-hardware.org/?probe=816b4e757d) | Jun 05, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [e92e195362](https://linux-hardware.org/?probe=e92e195362) | Jun 05, 2022 |
| ASUSTek       | P8Z68-V LX                  | [e7e3608105](https://linux-hardware.org/?probe=e7e3608105) | Jun 04, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [a65dd5834e](https://linux-hardware.org/?probe=a65dd5834e) | Jun 04, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [81bfe17cb5](https://linux-hardware.org/?probe=81bfe17cb5) | Jun 04, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [95db56a864](https://linux-hardware.org/?probe=95db56a864) | Jun 03, 2022 |
| ASUSTek       | Z87-K                       | [915e2819c0](https://linux-hardware.org/?probe=915e2819c0) | Jun 02, 2022 |
| ASRock        | Z390 Phantom Gaming SLI/... | [5f40da7ae9](https://linux-hardware.org/?probe=5f40da7ae9) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5348dd6576](https://linux-hardware.org/?probe=5348dd6576) | Jun 01, 2022 |
| ASUSTek       | PRIME Z590-A                | [fa29e357fa](https://linux-hardware.org/?probe=fa29e357fa) | Jun 01, 2022 |
| ASUSTek       | F2A85-M                     | [82b4935292](https://linux-hardware.org/?probe=82b4935292) | Jun 01, 2022 |
| MSI           | Z170A MPOWER GAMING TITA... | [538feade4f](https://linux-hardware.org/?probe=538feade4f) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [bee74ec003](https://linux-hardware.org/?probe=bee74ec003) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| System76      | Thelio Major thelio-majo... | [291730a3bb](https://linux-hardware.org/?probe=291730a3bb) | May 31, 2022 |
| Dell          | 0Y2MRG A00                  | [013e0da975](https://linux-hardware.org/?probe=013e0da975) | May 30, 2022 |
| Dell          | 0D02VH A01                  | [fc97b0a5bf](https://linux-hardware.org/?probe=fc97b0a5bf) | May 30, 2022 |
| ASUSTek       | PRIME Z590-A                | [1058cdf867](https://linux-hardware.org/?probe=1058cdf867) | May 30, 2022 |
| HP            | 8266                        | [d0e35451ab](https://linux-hardware.org/?probe=d0e35451ab) | May 29, 2022 |
| Gigabyte      | H270-Gaming 3               | [c28c21c4d8](https://linux-hardware.org/?probe=c28c21c4d8) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [5d899f8fc5](https://linux-hardware.org/?probe=5d899f8fc5) | May 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d1923db949](https://linux-hardware.org/?probe=d1923db949) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b78390767c](https://linux-hardware.org/?probe=b78390767c) | May 28, 2022 |
| MSI           | MS-7717                     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| MSI           | MS-7717                     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| ASRock        | B450 Steel Legend           | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Dell          | 040DDP A01                  | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| HP            | 158B                        | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [bdf54228e5](https://linux-hardware.org/?probe=bdf54228e5) | May 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f5195788f8](https://linux-hardware.org/?probe=f5195788f8) | May 27, 2022 |
| ASUSTek       | PRIME Z270-A                | [5d1ee4048a](https://linux-hardware.org/?probe=5d1ee4048a) | May 27, 2022 |
| ASUSTek       | P5KPL-SE                    | [c4b27d79ef](https://linux-hardware.org/?probe=c4b27d79ef) | May 26, 2022 |
| ASUSTek       | P5QPL-AM                    | [938ab3ec5c](https://linux-hardware.org/?probe=938ab3ec5c) | May 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ae0ada290a](https://linux-hardware.org/?probe=ae0ada290a) | May 26, 2022 |
| ASRock        | H670M-ITX/ax                | [b3f7ff3d98](https://linux-hardware.org/?probe=b3f7ff3d98) | May 25, 2022 |
| ASUSTek       | M5A78L/USB3                 | [852a292ba3](https://linux-hardware.org/?probe=852a292ba3) | May 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [4738560555](https://linux-hardware.org/?probe=4738560555) | May 25, 2022 |
| HP            | 8703                        | [14af29c571](https://linux-hardware.org/?probe=14af29c571) | May 24, 2022 |
| ASRock        | H470M-ITX/ac                | [181f7decc6](https://linux-hardware.org/?probe=181f7decc6) | May 24, 2022 |
| Dell          | 0Y2MRG A00                  | [08527b166e](https://linux-hardware.org/?probe=08527b166e) | May 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [1122022ae1](https://linux-hardware.org/?probe=1122022ae1) | May 24, 2022 |
| SIEMENS       | A5E02122237 ES010           | [3d7173e7a3](https://linux-hardware.org/?probe=3d7173e7a3) | May 24, 2022 |
| Lenovo        | MAHOBAY                     | [dbfb736222](https://linux-hardware.org/?probe=dbfb736222) | May 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [78bb2ba75c](https://linux-hardware.org/?probe=78bb2ba75c) | May 23, 2022 |
| Foxconn       | 2ABF                        | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [21818b99b4](https://linux-hardware.org/?probe=21818b99b4) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [f1db82519f](https://linux-hardware.org/?probe=f1db82519f) | May 22, 2022 |
| MSI           | MEG Z390 ACE                | [0065576586](https://linux-hardware.org/?probe=0065576586) | May 22, 2022 |
| Gigabyte      | H67N-USB3-B3                | [382f206597](https://linux-hardware.org/?probe=382f206597) | May 21, 2022 |
| ASRock        | B450 Steel Legend           | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| ASUSTek       | P7P55D-E LX                 | [358e85c524](https://linux-hardware.org/?probe=358e85c524) | May 21, 2022 |
| MSI           | B250M PRO-VD                | [540e0831b1](https://linux-hardware.org/?probe=540e0831b1) | May 20, 2022 |
| ASRock        | TRX40 Creator               | [a810336f3f](https://linux-hardware.org/?probe=a810336f3f) | May 20, 2022 |
| ASRock        | TRX40 Creator               | [6993400976](https://linux-hardware.org/?probe=6993400976) | May 20, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [2211d5c2a2](https://linux-hardware.org/?probe=2211d5c2a2) | May 20, 2022 |
| ASUSTek       | H110M-R                     | [7cae58580a](https://linux-hardware.org/?probe=7cae58580a) | May 20, 2022 |
| ASRock        | Z390 Phantom Gaming 4-IB    | [543ab770e8](https://linux-hardware.org/?probe=543ab770e8) | May 20, 2022 |
| Positivo      | POS-MI945AA                 | [0f9875e8fc](https://linux-hardware.org/?probe=0f9875e8fc) | May 19, 2022 |
| Lenovo        | MAHOBAY                     | [fa1f318919](https://linux-hardware.org/?probe=fa1f318919) | May 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [d94f4b0a43](https://linux-hardware.org/?probe=d94f4b0a43) | May 19, 2022 |
| Gigabyte      | B450 AORUS M                | [5ddfbf547b](https://linux-hardware.org/?probe=5ddfbf547b) | May 19, 2022 |
| Supermicro    | X8SIL                       | [66e8a4001f](https://linux-hardware.org/?probe=66e8a4001f) | May 18, 2022 |
| MSI           | B350M MORTAR                | [fd66fd9a5a](https://linux-hardware.org/?probe=fd66fd9a5a) | May 18, 2022 |
| Supermicro    | X8SIL                       | [5cb6f1067b](https://linux-hardware.org/?probe=5cb6f1067b) | May 18, 2022 |
| HP            | 8054                        | [725f204fd0](https://linux-hardware.org/?probe=725f204fd0) | May 18, 2022 |
| ASUSTek       | GA15DH                      | [ca68812bf2](https://linux-hardware.org/?probe=ca68812bf2) | May 17, 2022 |
| MSI           | Z270-A PRO                  | [f005623f03](https://linux-hardware.org/?probe=f005623f03) | May 17, 2022 |
| ASUSTek       | AM1M-A/BR                   | [e23e8291e0](https://linux-hardware.org/?probe=e23e8291e0) | May 17, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | [2f7a99c28b](https://linux-hardware.org/?probe=2f7a99c28b) | May 17, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [ee4e4a7bc7](https://linux-hardware.org/?probe=ee4e4a7bc7) | May 17, 2022 |
| Dell          | 040DDP A00                  | [4806ca2a7e](https://linux-hardware.org/?probe=4806ca2a7e) | May 17, 2022 |
| Gigabyte      | H310M S2H x.x               | [4d76b03e66](https://linux-hardware.org/?probe=4d76b03e66) | May 17, 2022 |
| ASUSTek       | Z87-K                       | [2daea316b2](https://linux-hardware.org/?probe=2daea316b2) | May 16, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [91d8b47a30](https://linux-hardware.org/?probe=91d8b47a30) | May 15, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [608664ce7a](https://linux-hardware.org/?probe=608664ce7a) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a049c51989](https://linux-hardware.org/?probe=a049c51989) | May 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [cb7b6b9cde](https://linux-hardware.org/?probe=cb7b6b9cde) | May 14, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [0cc824e2a5](https://linux-hardware.org/?probe=0cc824e2a5) | May 13, 2022 |
| NZXT          | N7 B550                     | [73441bbfc4](https://linux-hardware.org/?probe=73441bbfc4) | May 12, 2022 |
| Unknown       | BTC79X5                     | [42b222eb65](https://linux-hardware.org/?probe=42b222eb65) | May 12, 2022 |
| Gigabyte      | Z170-Gaming K3              | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| AZW           | BT3 X                       | [a17cb64acb](https://linux-hardware.org/?probe=a17cb64acb) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | [ee225906fc](https://linux-hardware.org/?probe=ee225906fc) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | [16911d5e64](https://linux-hardware.org/?probe=16911d5e64) | May 11, 2022 |
| Gigabyte      | B660 AORUS MASTER DDR4      | [e5981a9f20](https://linux-hardware.org/?probe=e5981a9f20) | May 11, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [1d4364ac51](https://linux-hardware.org/?probe=1d4364ac51) | May 10, 2022 |
| NZXT          | N7 B550                     | [147247dfb6](https://linux-hardware.org/?probe=147247dfb6) | May 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [396a39e5a6](https://linux-hardware.org/?probe=396a39e5a6) | May 10, 2022 |
| ASRock        | X370 Professional Gaming    | [1e22ba0468](https://linux-hardware.org/?probe=1e22ba0468) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [0b3cda16db](https://linux-hardware.org/?probe=0b3cda16db) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [90190717eb](https://linux-hardware.org/?probe=90190717eb) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| ASUSTek       | Z97-AR                      | [29c93ea162](https://linux-hardware.org/?probe=29c93ea162) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| ASRock        | X299 Taichi CLX             | [47a45fca48](https://linux-hardware.org/?probe=47a45fca48) | May 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [8964a4c5ec](https://linux-hardware.org/?probe=8964a4c5ec) | May 08, 2022 |
| ECS           | Nettle3                     | [36f8cde007](https://linux-hardware.org/?probe=36f8cde007) | May 08, 2022 |
| ASUSTek       | PRIME X570-P                | [65d94c8458](https://linux-hardware.org/?probe=65d94c8458) | May 08, 2022 |
| ECS           | Nettle3                     | [646fb53a2c](https://linux-hardware.org/?probe=646fb53a2c) | May 07, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [61a4daec98](https://linux-hardware.org/?probe=61a4daec98) | May 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [180dd73bd6](https://linux-hardware.org/?probe=180dd73bd6) | May 07, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f71ca35596](https://linux-hardware.org/?probe=f71ca35596) | May 06, 2022 |
| MSI           | B450-A PRO                  | [5b5ceb0f53](https://linux-hardware.org/?probe=5b5ceb0f53) | May 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [4fe934e84d](https://linux-hardware.org/?probe=4fe934e84d) | May 06, 2022 |
| ASRock        | 970M Pro3                   | [2853128cd0](https://linux-hardware.org/?probe=2853128cd0) | May 05, 2022 |
| ASRock        | 970M Pro3                   | [5f51fd4cf8](https://linux-hardware.org/?probe=5f51fd4cf8) | May 05, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [7b7f29e504](https://linux-hardware.org/?probe=7b7f29e504) | May 05, 2022 |
| ASRock        | X470 Taichi                 | [e133868179](https://linux-hardware.org/?probe=e133868179) | May 05, 2022 |
| ASRock        | X470 Taichi                 | [93d6fb1610](https://linux-hardware.org/?probe=93d6fb1610) | May 05, 2022 |
| ASRock        | A320M-HDV R4.0              | [36cabd86ba](https://linux-hardware.org/?probe=36cabd86ba) | May 04, 2022 |
| ASUSTek       | B85M-E                      | [2b6338d755](https://linux-hardware.org/?probe=2b6338d755) | May 04, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [7196bf2ec6](https://linux-hardware.org/?probe=7196bf2ec6) | May 03, 2022 |
| ASRock        | 970M Pro3                   | [f20f31b107](https://linux-hardware.org/?probe=f20f31b107) | May 03, 2022 |
| ASRock        | 970M Pro3                   | [73a563257a](https://linux-hardware.org/?probe=73a563257a) | May 03, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [65a2309744](https://linux-hardware.org/?probe=65a2309744) | May 03, 2022 |
| Alienware     | 0CPDXD A00                  | [17da14a17d](https://linux-hardware.org/?probe=17da14a17d) | May 03, 2022 |
| ASUSTek       | B85M-E                      | [9645231d87](https://linux-hardware.org/?probe=9645231d87) | May 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [c0ef0738b5](https://linux-hardware.org/?probe=c0ef0738b5) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [4a09f5d3f3](https://linux-hardware.org/?probe=4a09f5d3f3) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [ab716981c3](https://linux-hardware.org/?probe=ab716981c3) | May 02, 2022 |
| Alienware     | 0P0JWX A00                  | [e6e1548aa1](https://linux-hardware.org/?probe=e6e1548aa1) | May 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [a456619489](https://linux-hardware.org/?probe=a456619489) | May 02, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [925447d7e9](https://linux-hardware.org/?probe=925447d7e9) | May 01, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b1e331055f](https://linux-hardware.org/?probe=b1e331055f) | May 01, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [dec71580c4](https://linux-hardware.org/?probe=dec71580c4) | May 01, 2022 |
| Gigabyte      | X570S AERO G                | [ab6b8eaa71](https://linux-hardware.org/?probe=ab6b8eaa71) | May 01, 2022 |
| MSI           | 970 GAMING                  | [32052450db](https://linux-hardware.org/?probe=32052450db) | May 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [8db041a1e4](https://linux-hardware.org/?probe=8db041a1e4) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| MSI           | B450M GAMING PLUS           | [0929d58de7](https://linux-hardware.org/?probe=0929d58de7) | Apr 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [3edd5f05f7](https://linux-hardware.org/?probe=3edd5f05f7) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | [d45e1e88db](https://linux-hardware.org/?probe=d45e1e88db) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | [41cec63ac6](https://linux-hardware.org/?probe=41cec63ac6) | Apr 30, 2022 |
| EVGA          | X58 SLI Classified Tyler... | [07254f2dbb](https://linux-hardware.org/?probe=07254f2dbb) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [bce425f138](https://linux-hardware.org/?probe=bce425f138) | Apr 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [e37bc471b1](https://linux-hardware.org/?probe=e37bc471b1) | Apr 29, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [2b7167b16e](https://linux-hardware.org/?probe=2b7167b16e) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [aed5ee3ded](https://linux-hardware.org/?probe=aed5ee3ded) | Apr 28, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ab83eedd1f](https://linux-hardware.org/?probe=ab83eedd1f) | Apr 28, 2022 |
| MSI           | H55M-E23                    | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [46430e1117](https://linux-hardware.org/?probe=46430e1117) | Apr 28, 2022 |
| Dell          | 09KPNV A00                  | [5046e0575b](https://linux-hardware.org/?probe=5046e0575b) | Apr 28, 2022 |
| Dell          | 0NW73C A00                  | [344e2b816e](https://linux-hardware.org/?probe=344e2b816e) | Apr 28, 2022 |
| Dell          | 088DT1 A01                  | [b664b8720e](https://linux-hardware.org/?probe=b664b8720e) | Apr 28, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [19e0445e6f](https://linux-hardware.org/?probe=19e0445e6f) | Apr 27, 2022 |
| Dell          | 0R1PCR A00                  | [feec38a0f5](https://linux-hardware.org/?probe=feec38a0f5) | Apr 27, 2022 |
| Unknown       | Unknown                     | [82ad7e86b5](https://linux-hardware.org/?probe=82ad7e86b5) | Apr 27, 2022 |
| ASUSTek       | GA15DH                      | [30a22d7be3](https://linux-hardware.org/?probe=30a22d7be3) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| System76      | Thelio thelio-r2            | [aae937be8b](https://linux-hardware.org/?probe=aae937be8b) | Apr 25, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [fabaa5b3ab](https://linux-hardware.org/?probe=fabaa5b3ab) | Apr 24, 2022 |
| MSI           | B250M BAZOOKA               | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.17.5-76051705-generic   | 155      | 23.52%  |
| 5.19.0-76051900-generic   | 141      | 21.4%   |
| 6.0.6-76060006-generic    | 96       | 14.57%  |
| 5.18.10-76051810-generic  | 70       | 10.62%  |
| 5.17.15-76051715-generic  | 65       | 9.86%   |
| 5.16.19-76051619-generic  | 40       | 6.07%   |
| 6.0.2-76060002-generic    | 24       | 3.64%   |
| 6.0.12-76060006-generic   | 22       | 3.34%   |
| 5.19.16-76051916-generic  | 18       | 2.73%   |
| 6.0.3-76060003-generic    | 13       | 1.97%   |
| 6.1.0-x64v1-xanmod1       | 2        | 0.3%    |
| 6.1.0-060100rc5-generic   | 1        | 0.15%   |
| 6.0.9-060009-generic      | 1        | 0.15%   |
| 6.0.8-x64v1-xanmod1       | 1        | 0.15%   |
| 6.0.6-060006-generic      | 1        | 0.15%   |
| 6.0.2-x64v1-xanmod1       | 1        | 0.15%   |
| 6.0.12-x64v1-xanmod1      | 1        | 0.15%   |
| 5.4.210-whitehax0r        | 1        | 0.15%   |
| 5.19.6-xanmod1-x64v2      | 1        | 0.15%   |
| 5.18.0-9.1-liquorix-amd64 | 1        | 0.15%   |
| 5.17.4-051704-generic     | 1        | 0.15%   |
| 5.17.14-xanmod1           | 1        | 0.15%   |
| 5.16.15-76051615-generic  | 1        | 0.15%   |
| 5.15.15-76051515-generic  | 1        | 0.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.5  | 155      | 23.52%  |
| 5.19.0  | 141      | 21.4%   |
| 6.0.6   | 97       | 14.72%  |
| 5.18.10 | 70       | 10.62%  |
| 5.17.15 | 65       | 9.86%   |
| 5.16.19 | 40       | 6.07%   |
| 6.0.2   | 25       | 3.79%   |
| 6.0.12  | 23       | 3.49%   |
| 5.19.16 | 18       | 2.73%   |
| 6.0.3   | 13       | 1.97%   |
| 6.1.0   | 3        | 0.46%   |
| 6.0.9   | 1        | 0.15%   |
| 6.0.8   | 1        | 0.15%   |
| 5.4.210 | 1        | 0.15%   |
| 5.19.6  | 1        | 0.15%   |
| 5.18.0  | 1        | 0.15%   |
| 5.17.4  | 1        | 0.15%   |
| 5.17.14 | 1        | 0.15%   |
| 5.16.15 | 1        | 0.15%   |
| 5.15.15 | 1        | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17    | 215      | 33.18%  |
| 5.19    | 159      | 24.54%  |
| 6.0     | 157      | 24.23%  |
| 5.18    | 71       | 10.96%  |
| 5.16    | 41       | 6.33%   |
| 6.1     | 3        | 0.46%   |
| 5.4     | 1        | 0.15%   |
| 5.15    | 1        | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 605      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 582      | 95.88%  |
| KDE5            | 15       | 2.47%   |
| X-Cinnamon      | 5        | 0.82%   |
| Unknown         | 2        | 0.33%   |
| LXQt            | 1        | 0.16%   |
| GNOME Flashback | 1        | 0.16%   |
| Cinnamon        | 1        | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 591      | 97.52%  |
| Wayland | 13       | 2.15%   |
| Tty     | 1        | 0.17%   |
| Unknown | 1        | 0.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 507      | 83.53%  |
| GDM3    | 93       | 15.32%  |
| SDDM    | 4        | 0.66%   |
| GDM     | 2        | 0.33%   |
| LightDM | 1        | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 362      | 59.44%  |
| en_GB   | 40       | 6.57%   |
| pt_BR   | 34       | 5.58%   |
| C       | 26       | 4.27%   |
| de_DE   | 25       | 4.11%   |
| en_CA   | 18       | 2.96%   |
| fr_FR   | 13       | 2.13%   |
| en_AU   | 13       | 2.13%   |
| it_IT   | 11       | 1.81%   |
| pl_PL   | 9        | 1.48%   |
| es_ES   | 6        | 0.99%   |
| fi_FI   | 5        | 0.82%   |
| sv_SE   | 4        | 0.66%   |
| nl_NL   | 4        | 0.66%   |
| es_CL   | 4        | 0.66%   |
| en_IN   | 3        | 0.49%   |
| Unknown | 3        | 0.49%   |
| zh_TW   | 2        | 0.33%   |
| ru_RU   | 2        | 0.33%   |
| pt_PT   | 2        | 0.33%   |
| ja_JP   | 2        | 0.33%   |
| en_DK   | 2        | 0.33%   |
| de_AT   | 2        | 0.33%   |
| da_DK   | 2        | 0.33%   |
| cs_CZ   | 2        | 0.33%   |
| ro_RO   | 1        | 0.16%   |
| nl_BE   | 1        | 0.16%   |
| nb_NO   | 1        | 0.16%   |
| hu_HU   | 1        | 0.16%   |
| fr_CH   | 1        | 0.16%   |
| fr_BE   | 1        | 0.16%   |
| es_UY   | 1        | 0.16%   |
| es_DO   | 1        | 0.16%   |
| es_AR   | 1        | 0.16%   |
| en_ZA   | 1        | 0.16%   |
| en_IL   | 1        | 0.16%   |
| en_IE   | 1        | 0.16%   |
| en_FI   | 1        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 519      | 85.5%   |
| EFI  | 88       | 14.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 572      | 94.55%  |
| Overlay | 17       | 2.81%   |
| Btrfs   | 14       | 2.31%   |
| Xfs     | 2        | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 505      | 83.2%   |
| GPT     | 94       | 15.49%  |
| MBR     | 8        | 1.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 584      | 96.21%  |
| Yes       | 23       | 3.79%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 543      | 89.6%   |
| Yes       | 63       | 10.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 184      | 30.41%  |
| Gigabyte Technology | 106      | 17.52%  |
| MSI                 | 95       | 15.7%   |
| ASRock              | 58       | 9.59%   |
| Dell                | 39       | 6.45%   |
| Hewlett-Packard     | 31       | 5.12%   |
| Lenovo              | 21       | 3.47%   |
| Intel               | 10       | 1.65%   |
| System76            | 7        | 1.16%   |
| Acer                | 7        | 1.16%   |
| Unknown             | 6        | 0.99%   |
| Alienware           | 5        | 0.83%   |
| BESSTAR Tech        | 4        | 0.66%   |
| Supermicro          | 3        | 0.5%    |
| Pegatron            | 3        | 0.5%    |
| MACHINIST           | 3        | 0.5%    |
| Fujitsu             | 3        | 0.5%    |
| Foxconn             | 3        | 0.5%    |
| NZXT                | 2        | 0.33%   |
| EVGA                | 2        | 0.33%   |
| ECS                 | 2        | 0.33%   |
| Apple               | 2        | 0.33%   |
| Soyo                | 1        | 0.17%   |
| SIEMENS             | 1        | 0.17%   |
| Positivo            | 1        | 0.17%   |
| Minix               | 1        | 0.17%   |
| Medion              | 1        | 0.17%   |
| LattePanda          | 1        | 0.17%   |
| Biostar             | 1        | 0.17%   |
| AZW                 | 1        | 0.17%   |
| Acidanthera         | 1        | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 13       | 2.15%   |
| ASUS TUF Gaming B550-PLUS         | 8        | 1.32%   |
| ASUS ROG STRIX B550-F GAMING      | 8        | 1.32%   |
| Gigabyte B450 AORUS M             | 6        | 0.99%   |
| ASUS ROG STRIX B550-I GAMING      | 6        | 0.99%   |
| Unknown                           | 6        | 0.99%   |
| System76 Thelio                   | 5        | 0.83%   |
| MSI MS-7D54                       | 5        | 0.83%   |
| Gigabyte X570 AORUS ELITE         | 5        | 0.83%   |
| ASUS ROG STRIX B450-F GAMING      | 5        | 0.83%   |
| MSI MS-7B86                       | 4        | 0.66%   |
| Gigabyte B450M DS3H               | 4        | 0.66%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 4        | 0.66%   |
| ASUS PRIME B550M-A                | 4        | 0.66%   |
| ASUS PRIME B450M-A                | 4        | 0.66%   |
| MSI MS-7D25                       | 3        | 0.5%    |
| MSI MS-7C56                       | 3        | 0.5%    |
| MSI MS-7C37                       | 3        | 0.5%    |
| MSI MS-7C35                       | 3        | 0.5%    |
| MSI MS-7C02                       | 3        | 0.5%    |
| MSI MS-7A34                       | 3        | 0.5%    |
| MSI MS-7693                       | 3        | 0.5%    |
| HP ProDesk 600 G1 SFF             | 3        | 0.5%    |
| HP Compaq Elite 8300 USDT         | 3        | 0.5%    |
| Gigabyte X570 AORUS MASTER        | 3        | 0.5%    |
| Gigabyte B550M DS3H               | 3        | 0.5%    |
| Gigabyte B550 AORUS ELITE V2      | 3        | 0.5%    |
| Gigabyte B450 I AORUS PRO WIFI    | 3        | 0.5%    |
| Dell XPS 8700                     | 3        | 0.5%    |
| Dell OptiPlex 790                 | 3        | 0.5%    |
| Dell OptiPlex 3020                | 3        | 0.5%    |
| ASUS TUF Gaming X570-PLUS         | 3        | 0.5%    |
| ASUS TUF Gaming B550M-PLUS        | 3        | 0.5%    |
| ASUS ROG Maximus XI HERO          | 3        | 0.5%    |
| ASUS ROG CROSSHAIR VIII HERO      | 3        | 0.5%    |
| ASUS PRIME Z390-A                 | 3        | 0.5%    |
| ASUS PRIME X570-PRO               | 3        | 0.5%    |
| ASUS PRIME A320M-K                | 3        | 0.5%    |
| ASUS P6X58D PREMIUM               | 3        | 0.5%    |
| ASRock B450 Gaming K4             | 3        | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 61       | 10.08%  |
| ASUS PRIME             | 34       | 5.62%   |
| ASUS TUF               | 28       | 4.63%   |
| Dell OptiPlex          | 15       | 2.48%   |
| Lenovo ThinkCentre     | 14       | 2.31%   |
| ASUS All               | 13       | 2.15%   |
| Gigabyte X570          | 12       | 1.98%   |
| Gigabyte B450          | 12       | 1.98%   |
| Dell Precision         | 11       | 1.82%   |
| HP Compaq              | 10       | 1.65%   |
| System76 Thelio        | 7        | 1.16%   |
| HP EliteDesk           | 7        | 1.16%   |
| Gigabyte B550          | 7        | 1.16%   |
| Gigabyte B450M         | 6        | 0.99%   |
| Dell Inspiron          | 6        | 0.99%   |
| ASRock X570            | 6        | 0.99%   |
| Unknown                | 6        | 0.99%   |
| MSI MS-7D54            | 5        | 0.83%   |
| Dell XPS               | 5        | 0.83%   |
| ASRock B450            | 5        | 0.83%   |
| Alienware Aurora       | 5        | 0.83%   |
| MSI MS-7B86            | 4        | 0.66%   |
| HP ProDesk             | 4        | 0.66%   |
| Gigabyte B550M         | 4        | 0.66%   |
| ASRock B450M           | 4        | 0.66%   |
| MSI MS-7D25            | 3        | 0.5%    |
| MSI MS-7C56            | 3        | 0.5%    |
| MSI MS-7C37            | 3        | 0.5%    |
| MSI MS-7C35            | 3        | 0.5%    |
| MSI MS-7C02            | 3        | 0.5%    |
| MSI MS-7A34            | 3        | 0.5%    |
| MSI MS-7693            | 3        | 0.5%    |
| Lenovo IdeaCentre      | 3        | 0.5%    |
| Gigabyte H310M         | 3        | 0.5%    |
| Gigabyte GA-78LMT-USB3 | 3        | 0.5%    |
| Gigabyte AB350-Gaming  | 3        | 0.5%    |
| Fujitsu ESPRIMO        | 3        | 0.5%    |
| ASUS P6X58D            | 3        | 0.5%    |
| ASUS Maximus           | 3        | 0.5%    |
| Acer Aspire            | 3        | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 99       | 16.36%  |
| 2018 | 86       | 14.21%  |
| 2019 | 67       | 11.07%  |
| 2021 | 58       | 9.59%   |
| 2013 | 38       | 6.28%   |
| 2012 | 38       | 6.28%   |
| 2017 | 35       | 5.79%   |
| 2014 | 35       | 5.79%   |
| 2022 | 30       | 4.96%   |
| 2016 | 27       | 4.46%   |
| 2011 | 27       | 4.46%   |
| 2010 | 20       | 3.31%   |
| 2015 | 18       | 2.98%   |
| 2009 | 15       | 2.48%   |
| 2008 | 6        | 0.99%   |
| 2007 | 5        | 0.83%   |
| 2006 | 1        | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 605      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 604      | 99.83%  |
| Enabled  | 1        | 0.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 605      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 209      | 34.15%  |
| 32.01-64.0      | 160      | 26.14%  |
| 8.01-16.0       | 87       | 14.22%  |
| 64.01-256.0     | 58       | 9.48%   |
| 4.01-8.0        | 51       | 8.33%   |
| 3.01-4.0        | 27       | 4.41%   |
| 24.01-32.0      | 15       | 2.45%   |
| More than 256.0 | 3        | 0.49%   |
| 2.01-3.0        | 1        | 0.16%   |
| 1.01-2.0        | 1        | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 183      | 28.07%  |
| 2.01-3.0    | 178      | 27.3%   |
| 3.01-4.0    | 165      | 25.31%  |
| 1.01-2.0    | 69       | 10.58%  |
| 8.01-16.0   | 41       | 6.29%   |
| 16.01-24.0  | 10       | 1.53%   |
| 32.01-64.0  | 4        | 0.61%   |
| 24.01-32.0  | 1        | 0.15%   |
| 64.01-256.0 | 1        | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 196      | 32.13%  |
| 1      | 172      | 28.2%   |
| 3      | 122      | 20%     |
| 4      | 54       | 8.85%   |
| 5      | 29       | 4.75%   |
| 6      | 18       | 2.95%   |
| 7      | 8        | 1.31%   |
| 0      | 4        | 0.66%   |
| 9      | 3        | 0.49%   |
| 10     | 2        | 0.33%   |
| 19     | 1        | 0.16%   |
| 11     | 1        | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 444      | 73.27%  |
| Yes       | 162      | 26.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 598      | 98.84%  |
| No        | 7        | 1.16%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 338      | 55.59%  |
| No        | 270      | 44.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 330      | 54.28%  |
| Yes       | 278      | 45.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 224      | 36.84%  |
| Germany      | 39       | 6.41%   |
| Brazil       | 38       | 6.25%   |
| Canada       | 37       | 6.09%   |
| UK           | 27       | 4.44%   |
| Italy        | 24       | 3.95%   |
| France       | 19       | 3.13%   |
| Australia    | 19       | 3.13%   |
| Netherlands  | 13       | 2.14%   |
| Poland       | 12       | 1.97%   |
| Finland      | 11       | 1.81%   |
| Norway       | 10       | 1.64%   |
| Sweden       | 9        | 1.48%   |
| Greece       | 9        | 1.48%   |
| Spain        | 8        | 1.32%   |
| Portugal     | 7        | 1.15%   |
| Austria      | 7        | 1.15%   |
| Switzerland  | 6        | 0.99%   |
| South Africa | 5        | 0.82%   |
| Russia       | 5        | 0.82%   |
| Romania      | 5        | 0.82%   |
| Ireland      | 5        | 0.82%   |
| India        | 5        | 0.82%   |
| Mexico       | 4        | 0.66%   |
| Japan        | 4        | 0.66%   |
| Hong Kong    | 4        | 0.66%   |
| Denmark      | 4        | 0.66%   |
| Chile        | 4        | 0.66%   |
| Belgium      | 4        | 0.66%   |
| Thailand     | 3        | 0.49%   |
| Philippines  | 3        | 0.49%   |
| Hungary      | 3        | 0.49%   |
| Czechia      | 3        | 0.49%   |
| Slovakia     | 2        | 0.33%   |
| Serbia       | 2        | 0.33%   |
| Lithuania    | 2        | 0.33%   |
| Indonesia    | 2        | 0.33%   |
| Argentina    | 2        | 0.33%   |
| Uruguay      | 1        | 0.16%   |
| UAE          | 1        | 0.16%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Berlin            | 7        | 1.13%   |
| Seattle           | 6        | 0.97%   |
| Rio de Janeiro    | 6        | 0.97%   |
| Vienna            | 5        | 0.81%   |
| Sao Paulo         | 5        | 0.81%   |
| San Francisco     | 5        | 0.81%   |
| Milan             | 5        | 0.81%   |
| Helsinki          | 5        | 0.81%   |
| Miami             | 4        | 0.65%   |
| Brisbane          | 4        | 0.65%   |
| Zurich            | 3        | 0.49%   |
| Weimar            | 3        | 0.49%   |
| Virginia Beach    | 3        | 0.49%   |
| Sydney            | 3        | 0.49%   |
| Paris             | 3        | 0.49%   |
| Melbourne         | 3        | 0.49%   |
| Mannheim          | 3        | 0.49%   |
| Madrid            | 3        | 0.49%   |
| Lisbon            | 3        | 0.49%   |
| Johannesburg      | 3        | 0.49%   |
| Dublin            | 3        | 0.49%   |
| Cleveland         | 3        | 0.49%   |
| Central           | 3        | 0.49%   |
| Cambridge         | 3        | 0.49%   |
| Bedford           | 3        | 0.49%   |
| Bargo             | 3        | 0.49%   |
| Athens            | 3        | 0.49%   |
| Amsterdam         | 3        | 0.49%   |
| Adelaide          | 3        | 0.49%   |
| Weston-super-Mare | 2        | 0.32%   |
| Valparaiso        | 2        | 0.32%   |
| Turku             | 2        | 0.32%   |
| Trondheim         | 2        | 0.32%   |
| Toronto           | 2        | 0.32%   |
| Springfield       | 2        | 0.32%   |
| Sapporo           | 2        | 0.32%   |
| San Antonio       | 2        | 0.32%   |
| Rome              | 2        | 0.32%   |
| Richmond          | 2        | 0.32%   |
| Regina            | 2        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 227      | 357    | 18.46%  |
| Seagate                   | 197      | 298    | 16.02%  |
| WDC                       | 190      | 277    | 15.45%  |
| Sandisk                   | 80       | 94     | 6.5%    |
| Crucial                   | 74       | 112    | 6.02%   |
| Kingston                  | 64       | 79     | 5.2%    |
| Toshiba                   | 55       | 61     | 4.47%   |
| Hitachi                   | 24       | 32     | 1.95%   |
| Phison                    | 22       | 31     | 1.79%   |
| Intel                     | 20       | 23     | 1.63%   |
| A-DATA Technology         | 19       | 20     | 1.54%   |
| Micron/Crucial Technology | 18       | 21     | 1.46%   |
| Phison Electronics        | 17       | 26     | 1.38%   |
| Silicon Motion            | 15       | 21     | 1.22%   |
| PNY                       | 13       | 18     | 1.06%   |
| Unknown                   | 12       | 24     | 0.98%   |
| China                     | 12       | 15     | 0.98%   |
| SPCC                      | 11       | 16     | 0.89%   |
| SK hynix                  | 10       | 12     | 0.81%   |
| OCZ                       | 8        | 10     | 0.65%   |
| Micron Technology         | 8        | 10     | 0.65%   |
| Patriot                   | 7        | 9      | 0.57%   |
| HGST                      | 7        | 10     | 0.57%   |
| XPG                       | 6        | 8      | 0.49%   |
| Realtek Semiconductor     | 5        | 5      | 0.41%   |
| Netac                     | 5        | 5      | 0.41%   |
| Lexar                     | 5        | 5      | 0.41%   |
| Intenso                   | 5        | 5      | 0.41%   |
| Team                      | 4        | 6      | 0.33%   |
| JMicron Technology        | 4        | 13     | 0.33%   |
| Hewlett-Packard           | 4        | 4      | 0.33%   |
| GOODRAM                   | 4        | 4      | 0.33%   |
| Corsair                   | 4        | 8      | 0.33%   |
| Apple                     | 4        | 4      | 0.33%   |
| Maxtor                    | 3        | 3      | 0.24%   |
| LaCie                     | 3        | 3      | 0.24%   |
| WALRAM                    | 2        | 2      | 0.16%   |
| TO Exter                  | 2        | 2      | 0.16%   |
| T-FORCE                   | 2        | 3      | 0.16%   |
| Mushkin                   | 2        | 3      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB                          | 25       | 1.72%   |
| Seagate ST2000DM008-2FR102 2TB                      | 24       | 1.65%   |
| Samsung SSD 860 EVO 1TB                             | 19       | 1.31%   |
| Samsung NVMe SSD Drive 500GB                        | 18       | 1.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 17       | 1.17%   |
| Seagate ST1000DM010-2EP102 1TB                      | 16       | 1.1%    |
| Samsung SSD 850 EVO 500GB                           | 15       | 1.03%   |
| Kingston SA400S37240G 240GB SSD                     | 15       | 1.03%   |
| SanDisk NVMe SSD Drive 1TB                          | 14       | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 14       | 0.96%   |
| Samsung SSD 850 EVO 250GB                           | 13       | 0.89%   |
| Crucial CT1000MX500SSD1 1TB                         | 13       | 0.89%   |
| Seagate ST1000DM003-1ER162 1TB                      | 12       | 0.82%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 11       | 0.76%   |
| Samsung SSD 860 EVO 500GB                           | 11       | 0.76%   |
| Seagate ST4000DM004-2CV104 4TB                      | 10       | 0.69%   |
| Seagate ST1000DM003-1CH162 1TB                      | 10       | 0.69%   |
| Samsung NVMe SSD Drive 2TB                          | 10       | 0.69%   |
| Kingston SA400S37480G 480GB SSD                     | 10       | 0.69%   |
| Crucial CT500MX500SSD1 500GB                        | 10       | 0.69%   |
| Seagate ST500DM002-1BD142 500GB                     | 9        | 0.62%   |
| Phison E12 NVMe Controller 1TB                      | 9        | 0.62%   |
| Crucial CT1000BX500SSD1 1TB                         | 9        | 0.62%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 8        | 0.55%   |
| Sandisk WD Blue SN550 NVMe SSD 500GB                | 8        | 0.55%   |
| SanDisk NVMe SSD Drive 500GB                        | 8        | 0.55%   |
| Kingston SV300S37A120G 120GB SSD                    | 8        | 0.55%   |
| Kingston SA400S37120G 120GB SSD                     | 8        | 0.55%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 7        | 0.48%   |
| Toshiba DT01ACA200 2TB                              | 7        | 0.48%   |
| Toshiba DT01ACA100 1TB                              | 7        | 0.48%   |
| Seagate Expansion 4TB                               | 7        | 0.48%   |
| Samsung SSD 850 EVO 1TB                             | 7        | 0.48%   |
| Phison NVMe SSD Drive 1TB                           | 7        | 0.48%   |
| Micron/Crucial NVMe SSD Drive 1TB                   | 7        | 0.48%   |
| Crucial CT2000MX500SSD1 2TB                         | 7        | 0.48%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 6        | 0.41%   |
| Seagate ST8000DM004-2CX188 8TB                      | 6        | 0.41%   |
| Samsung SSD 970 EVO Plus 1TB                        | 6        | 0.41%   |
| Phison E16 PCIe4 NVMe Controller 512GB              | 6        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 189      | 282    | 41.54%  |
| WDC                 | 155      | 221    | 34.07%  |
| Toshiba             | 49       | 55     | 10.77%  |
| Hitachi             | 24       | 32     | 5.27%   |
| Samsung Electronics | 16       | 22     | 3.52%   |
| HGST                | 7        | 10     | 1.54%   |
| Unknown             | 4        | 8      | 0.88%   |
| Apple               | 4        | 4      | 0.88%   |
| Maxtor              | 2        | 2      | 0.44%   |
| JMicron Technology  | 2        | 7      | 0.44%   |
| RSH-339             | 1        | 1      | 0.22%   |
| Fujitsu             | 1        | 2      | 0.22%   |
| ASMT                | 1        | 1      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 114      | 168    | 25.91%  |
| Crucial             | 68       | 100    | 15.45%  |
| Kingston            | 54       | 65     | 12.27%  |
| WDC                 | 35       | 44     | 7.95%   |
| SanDisk             | 29       | 32     | 6.59%   |
| A-DATA Technology   | 16       | 17     | 3.64%   |
| PNY                 | 13       | 18     | 2.95%   |
| China               | 11       | 14     | 2.5%    |
| SPCC                | 9        | 10     | 2.05%   |
| OCZ                 | 8        | 10     | 1.82%   |
| Intel               | 8        | 8      | 1.82%   |
| Patriot             | 7        | 9      | 1.59%   |
| SK hynix            | 6        | 7      | 1.36%   |
| Netac               | 5        | 5      | 1.14%   |
| Team                | 4        | 6      | 0.91%   |
| Lexar               | 4        | 4      | 0.91%   |
| GOODRAM             | 4        | 4      | 0.91%   |
| Toshiba             | 3        | 3      | 0.68%   |
| Micron Technology   | 3        | 3      | 0.68%   |
| Hewlett-Packard     | 3        | 3      | 0.68%   |
| TO Exter            | 2        | 2      | 0.45%   |
| Seagate             | 2        | 2      | 0.45%   |
| Mushkin             | 2        | 3      | 0.45%   |
| Intenso             | 2        | 2      | 0.45%   |
| Corsair             | 2        | 3      | 0.45%   |
| Yeyian              | 1        | 1      | 0.23%   |
| Verbatim            | 1        | 2      | 0.23%   |
| TrekStor            | 1        | 1      | 0.23%   |
| Transcend           | 1        | 2      | 0.23%   |
| TCSUNBOW            | 1        | 1      | 0.23%   |
| RZX                 | 1        | 1      | 0.23%   |
| PNY USB             | 1        | 1      | 0.23%   |
| Plextor             | 1        | 1      | 0.23%   |
| Maxtor              | 1        | 1      | 0.23%   |
| LITEON              | 1        | 2      | 0.23%   |
| LaCie               | 1        | 1      | 0.23%   |
| KingSpec            | 1        | 1      | 0.23%   |
| KingDian            | 1        | 2      | 0.23%   |
| JMicron Technology  | 1        | 1      | 0.23%   |
| HS-SSD-E100N        | 1        | 1      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 358      | 574    | 34.62%  |
| HDD     | 352      | 647    | 34.04%  |
| NVMe    | 283      | 446    | 27.37%  |
| Unknown | 37       | 57     | 3.58%   |
| MMC     | 4        | 5      | 0.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 515      | 1188   | 59.81%  |
| NVMe | 283      | 445    | 32.87%  |
| SAS  | 59       | 91     | 6.85%   |
| MMC  | 4        | 5      | 0.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 340      | 533    | 41.98%  |
| 0.51-1.0   | 250      | 366    | 30.86%  |
| 1.01-2.0   | 122      | 162    | 15.06%  |
| 3.01-4.0   | 41       | 67     | 5.06%   |
| 4.01-10.0  | 32       | 52     | 3.95%   |
| 2.01-3.0   | 23       | 33     | 2.84%   |
| 10.01-20.0 | 2        | 8      | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 140      | 22.51%  |
| 251-500        | 112      | 18.01%  |
| 101-250        | 109      | 17.52%  |
| 1001-2000      | 99       | 15.92%  |
| More than 3000 | 73       | 11.74%  |
| 2001-3000      | 44       | 7.07%   |
| 1-20           | 20       | 3.22%   |
| 51-100         | 13       | 2.09%   |
| 21-50          | 8        | 1.29%   |
| Unknown        | 4        | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 148      | 22.98%  |
| 21-50          | 111      | 17.24%  |
| 101-250        | 92       | 14.29%  |
| 251-500        | 76       | 11.8%   |
| 51-100         | 74       | 11.49%  |
| 501-1000       | 52       | 8.07%   |
| 1001-2000      | 43       | 6.68%   |
| More than 3000 | 29       | 4.5%    |
| 2001-3000      | 15       | 2.33%   |
| Unknown        | 4        | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB                     | 1        | 1      | 3.85%   |
| WDC WD5001AALS-00J7B1 500GB                  | 1        | 1      | 3.85%   |
| WDC WD5000AADS-00S9B0 500GB                  | 1        | 1      | 3.85%   |
| WDC WD20EFRX-68AX9N0 2TB                     | 1        | 4      | 3.85%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1        | 1      | 3.85%   |
| WDC WD10EZEX-60WN4A0 1TB                     | 1        | 1      | 3.85%   |
| WDC WD1001FALS-00E8B0 1TB                    | 1        | 1      | 3.85%   |
| Seagate ST5000LM000-2AN170 5TB               | 1        | 1      | 3.85%   |
| Seagate ST320LM001 HN-M320MBB 320GB          | 1        | 1      | 3.85%   |
| Seagate ST2000DM008-2FR102 2TB               | 1        | 1      | 3.85%   |
| Seagate ST2000DM006-2DM164 2TB               | 1        | 1      | 3.85%   |
| Seagate Expansion Desk 5TB                   | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 850 PRO 256GB        | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 850 EVO 250GB        | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 1        | 1      | 3.85%   |
| Samsung Electronics MZVKW512HMJP-00000 512GB | 1        | 1      | 3.85%   |
| Samsung Electronics HD103SI 1TB              | 1        | 1      | 3.85%   |
| SABRENT Disk 1TB                             | 1        | 1      | 3.85%   |
| Plextor PX-128M6M 128GB SSD                  | 1        | 1      | 3.85%   |
| Kingston SV300S37A240G 240GB SSD             | 1        | 1      | 3.85%   |
| Hitachi HDP725050GLA360 500GB                | 1        | 1      | 3.85%   |
| HGST HTS725050A7E630 500GB                   | 1        | 1      | 3.85%   |
| Crucial CT525MX300SSD1 528GB                 | 1        | 1      | 3.85%   |
| Crucial CT500MX500SSD1 500GB                 | 1        | 1      | 3.85%   |
| BAITITON BT58SSD08M 128GB                    | 1        | 1      | 3.85%   |
| A-DATA Technology SU800 512GB SSD            | 1        | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 10     | 28%     |
| Samsung Electronics | 5        | 5      | 20%     |
| Seagate             | 4        | 5      | 16%     |
| Crucial             | 2        | 2      | 8%      |
| SABRENT             | 1        | 1      | 4%      |
| Plextor             | 1        | 1      | 4%      |
| Kingston            | 1        | 1      | 4%      |
| Hitachi             | 1        | 1      | 4%      |
| HGST                | 1        | 1      | 4%      |
| BAITITON            | 1        | 1      | 4%      |
| A-DATA Technology   | 1        | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 10     | 50%     |
| Seagate             | 4        | 5      | 28.57%  |
| Samsung Electronics | 1        | 1      | 7.14%   |
| Hitachi             | 1        | 1      | 7.14%   |
| HGST                | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 18     | 56%     |
| SSD  | 9        | 9      | 36%     |
| NVMe | 2        | 2      | 8%      |

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
| Detected | 518      | 1445   | 80.06%  |
| Works    | 107      | 255    | 16.54%  |
| Malfunc  | 22       | 29     | 3.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 305      | 30.23%  |
| AMD                            | 298      | 29.53%  |
| Samsung Electronics            | 135      | 13.38%  |
| SanDisk                        | 60       | 5.95%   |
| Phison Electronics             | 42       | 4.16%   |
| ASMedia Technology             | 35       | 3.47%   |
| Micron/Crucial Technology      | 25       | 2.48%   |
| Silicon Motion                 | 17       | 1.68%   |
| Marvell Technology Group       | 14       | 1.39%   |
| Kingston Technology Company    | 13       | 1.29%   |
| JMicron Technology             | 8        | 0.79%   |
| ADATA Technology               | 8        | 0.79%   |
| Realtek Semiconductor          | 7        | 0.69%   |
| Nvidia                         | 7        | 0.69%   |
| Seagate Technology             | 6        | 0.59%   |
| Micron Technology              | 5        | 0.5%    |
| Toshiba America Info Systems   | 4        | 0.4%    |
| SK hynix                       | 4        | 0.4%    |
| Broadcom / LSI                 | 4        | 0.4%    |
| Silicon Image                  | 2        | 0.2%    |
| LSI Logic / Symbios Logic      | 2        | 0.2%    |
| Lite-On Technology             | 2        | 0.2%    |
| KIOXIA                         | 2        | 0.2%    |
| INNOGRIT                       | 2        | 0.2%    |
| VIA Technologies               | 1        | 0.1%    |
| Solid State Storage Technology | 1        | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 185      | 15.4%   |
| AMD 400 Series Chipset SATA Controller                                                  | 75       | 6.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 69       | 5.75%   |
| AMD 500 Series Chipset SATA Controller                                                  | 68       | 5.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 38       | 3.16%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 33       | 2.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 31       | 2.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 27       | 2.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 26       | 2.16%   |
| Phison E12 NVMe Controller                                                              | 21       | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 21       | 1.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 19       | 1.58%   |
| Samsung NVMe SSD Controller 980                                                         | 18       | 1.5%    |
| Intel SATA Controller [RAID mode]                                                       | 18       | 1.5%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 18       | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 18       | 1.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 17       | 1.42%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 17       | 1.42%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 17       | 1.42%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 15       | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 15       | 1.25%   |
| AMD 300 Series Chipset SATA Controller                                                  | 15       | 1.25%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 12       | 1%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 12       | 1%      |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 11       | 0.92%   |
| SanDisk Non-Volatile memory controller                                                  | 10       | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 10       | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 10       | 0.83%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 10       | 0.83%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 8        | 0.67%   |
| Intel SSD 660P Series                                                                   | 8        | 0.67%   |
| AMD X370 Series Chipset SATA Controller                                                 | 8        | 0.67%   |
| AMD FCH SATA Controller D                                                               | 8        | 0.67%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 7        | 0.58%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 0.58%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 7        | 0.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 0.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 539      | 57.34%  |
| NVMe | 284      | 30.21%  |
| IDE  | 74       | 7.87%   |
| RAID | 35       | 3.72%   |
| SAS  | 8        | 0.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 306      | 50.58%  |
| Intel  | 299      | 49.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 28       | 4.62%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 23       | 3.8%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 18       | 2.97%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 15       | 2.48%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 14       | 2.31%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 13       | 2.15%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 13       | 2.15%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 11       | 1.82%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 10       | 1.65%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 10       | 1.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 9        | 1.49%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 9        | 1.49%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 8        | 1.32%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 7        | 1.16%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 7        | 1.16%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 7        | 1.16%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 7        | 1.16%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 7        | 1.16%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 6        | 0.99%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 6        | 0.99%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 6        | 0.99%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 6        | 0.99%   |
| AMD FX-6300 Six-Core Processor              | 6        | 0.99%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 5        | 0.83%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5        | 0.83%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 5        | 0.83%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 5        | 0.83%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 5        | 0.83%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 5        | 0.83%   |
| AMD Ryzen 7 1800X Eight-Core Processor      | 5        | 0.83%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 5        | 0.83%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 5        | 0.83%   |
| AMD FX-8350 Eight-Core Processor            | 5        | 0.83%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 4        | 0.66%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 4        | 0.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 0.66%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 0.66%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 0.66%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 0.66%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 4        | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 111      | 18.32%  |
| Intel Core i7           | 96       | 15.84%  |
| Intel Core i5           | 84       | 13.86%  |
| AMD Ryzen 7             | 79       | 13.04%  |
| AMD Ryzen 9             | 48       | 7.92%   |
| Other                   | 29       | 4.79%   |
| Intel Xeon              | 25       | 4.13%   |
| Intel Core i3           | 23       | 3.8%    |
| AMD FX                  | 19       | 3.14%   |
| Intel Core i9           | 10       | 1.65%   |
| AMD Ryzen 3             | 8        | 1.32%   |
| Intel Celeron           | 7        | 1.16%   |
| AMD Ryzen Threadripper  | 7        | 1.16%   |
| Intel Core 2 Quad       | 6        | 0.99%   |
| Intel Pentium Gold      | 4        | 0.66%   |
| Intel Pentium           | 4        | 0.66%   |
| AMD A8                  | 4        | 0.66%   |
| Intel Core 2 Duo        | 3        | 0.5%    |
| AMD Phenom              | 3        | 0.5%    |
| AMD Athlon              | 3        | 0.5%    |
| AMD A4                  | 3        | 0.5%    |
| AMD A10                 | 3        | 0.5%    |
| Intel Pentium Dual      | 2        | 0.33%   |
| Intel Pentium D         | 2        | 0.33%   |
| Intel Core 2            | 2        | 0.33%   |
| AMD Phenom II X6        | 2        | 0.33%   |
| AMD Phenom II X4        | 2        | 0.33%   |
| AMD Athlon II X4        | 2        | 0.33%   |
| AMD Athlon II X2        | 2        | 0.33%   |
| Intel Pentium Silver    | 1        | 0.17%   |
| Intel Pentium Dual-Core | 1        | 0.17%   |
| Intel Atom              | 1        | 0.17%   |
| AMD Sempron             | 1        | 0.17%   |
| AMD Ryzen Embedded      | 1        | 0.17%   |
| AMD Ryzen 5 PRO         | 1        | 0.17%   |
| AMD Ryzen 3 PRO         | 1        | 0.17%   |
| AMD PRO A10             | 1        | 0.17%   |
| AMD Phenom II X3        | 1        | 0.17%   |
| AMD Athlon X4           | 1        | 0.17%   |
| AMD Athlon II X3        | 1        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 198      | 32.67%  |
| 6      | 144      | 23.76%  |
| 8      | 104      | 17.16%  |
| 2      | 60       | 9.9%    |
| 12     | 36       | 5.94%   |
| 16     | 31       | 5.12%   |
| 3      | 10       | 1.65%   |
| 10     | 9        | 1.49%   |
| 24     | 4        | 0.66%   |
| 1      | 4        | 0.66%   |
| 32     | 2        | 0.33%   |
| 14     | 2        | 0.33%   |
| 64     | 1        | 0.17%   |
| 18     | 1        | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 599      | 99.01%  |
| 2      | 6        | 0.99%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 455      | 75.21%  |
| 1      | 150      | 24.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 605      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 501      | 82%     |
| 0x08701021 | 14       | 2.29%   |
| 0x0800820d | 11       | 1.8%    |
| 0x0a201016 | 8        | 1.31%   |
| 0x506e3    | 6        | 0.98%   |
| 0x906ec    | 5        | 0.82%   |
| 0x306a9    | 5        | 0.82%   |
| 0x206a7    | 5        | 0.82%   |
| 0x906e9    | 4        | 0.65%   |
| 0x90672    | 4        | 0.65%   |
| 0x306c3    | 4        | 0.65%   |
| 0x08701013 | 4        | 0.65%   |
| 0x08108109 | 4        | 0.65%   |
| 0x906ea    | 3        | 0.49%   |
| 0x08001138 | 3        | 0.49%   |
| 0x06003106 | 3        | 0.49%   |
| 0xa0671    | 2        | 0.33%   |
| 0xa0653    | 2        | 0.33%   |
| 0x50657    | 2        | 0.33%   |
| 0x0a50000c | 2        | 0.33%   |
| 0x0a201205 | 2        | 0.33%   |
| 0x08001137 | 2        | 0.33%   |
| 0xb0671    | 1        | 0.16%   |
| 0xa0655    | 1        | 0.16%   |
| 0x906ed    | 1        | 0.16%   |
| 0x906c0    | 1        | 0.16%   |
| 0x306e4    | 1        | 0.16%   |
| 0x0a601203 | 1        | 0.16%   |
| 0x0a601201 | 1        | 0.16%   |
| 0x0a20120a | 1        | 0.16%   |
| 0x0a201006 | 1        | 0.16%   |
| 0x08301039 | 1        | 0.16%   |
| 0x08101016 | 1        | 0.16%   |
| 0x08001129 | 1        | 0.16%   |
| 0x07013005 | 1        | 0.16%   |
| 0x0600611a | 1        | 0.16%   |
| 0x06000852 | 1        | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 100      | 16.5%   |
| Zen 2            | 81       | 13.37%  |
| Haswell          | 58       | 9.57%   |
| KabyLake         | 51       | 8.42%   |
| Zen+             | 43       | 7.1%    |
| Unknown          | 35       | 5.78%   |
| IvyBridge        | 34       | 5.61%   |
| Skylake          | 33       | 5.45%   |
| SandyBridge      | 30       | 4.95%   |
| Zen              | 27       | 4.46%   |
| Piledriver       | 23       | 3.8%    |
| Nehalem          | 15       | 2.48%   |
| K10              | 13       | 2.15%   |
| CometLake        | 13       | 2.15%   |
| Penryn           | 10       | 1.65%   |
| Westmere         | 7        | 1.16%   |
| Steamroller      | 6        | 0.99%   |
| Core             | 5        | 0.83%   |
| Alderlake Hybrid | 5        | 0.83%   |
| Broadwell        | 4        | 0.66%   |
| Silvermont       | 3        | 0.5%    |
| NetBurst         | 2        | 0.33%   |
| Goldmont         | 2        | 0.33%   |
| Excavator        | 2        | 0.33%   |
| K8 Hammer        | 1        | 0.17%   |
| K10 Llano        | 1        | 0.17%   |
| Jaguar           | 1        | 0.17%   |
| Icelake          | 1        | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 304      | 47.13%  |
| AMD                        | 241      | 37.36%  |
| Intel                      | 99       | 15.35%  |
| Matrox Electronics Systems | 1        | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 28       | 4.21%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 23       | 3.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 19       | 2.86%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 18       | 2.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 17       | 2.56%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 17       | 2.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 17       | 2.56%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 14       | 2.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 13       | 1.95%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 12       | 1.8%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 11       | 1.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 11       | 1.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11       | 1.65%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 10       | 1.5%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 10       | 1.5%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 10       | 1.5%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 9        | 1.35%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 9        | 1.35%   |
| Intel HD Graphics 530                                                       | 9        | 1.35%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 8        | 1.2%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 8        | 1.2%    |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 8        | 1.2%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 8        | 1.2%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 8        | 1.2%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 7        | 1.05%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 7        | 1.05%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 7        | 1.05%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 7        | 1.05%   |
| Intel AlderLake-S GT1                                                       | 7        | 1.05%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 7        | 1.05%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 6        | 0.9%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 6        | 0.9%    |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 0.9%    |
| Nvidia GF108 [GeForce GT 730]                                               | 6        | 0.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 0.9%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 5        | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 0.75%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 5        | 0.75%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 5        | 0.75%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 5        | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 282      | 46.08%  |
| 1 x AMD              | 220      | 35.95%  |
| 1 x Intel            | 70       | 11.44%  |
| 2 x AMD              | 12       | 1.96%   |
| Intel + Nvidia       | 9        | 1.47%   |
| 2 x Nvidia           | 6        | 0.98%   |
| AMD + Nvidia         | 5        | 0.82%   |
| Intel + AMD          | 4        | 0.65%   |
| Other                | 1        | 0.16%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.16%   |
| 1 x Matrox           | 1        | 0.16%   |
| AMD + 2 x Nvidia     | 1        | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 325      | 53.1%   |
| Proprietary | 261      | 42.65%  |
| Unknown     | 26       | 4.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 403      | 65.21%  |
| 7.01-8.0   | 60       | 9.71%   |
| 1.01-2.0   | 37       | 5.99%   |
| 8.01-16.0  | 34       | 5.5%    |
| 3.01-4.0   | 33       | 5.34%   |
| 5.01-6.0   | 32       | 5.18%   |
| 2.01-3.0   | 8        | 1.29%   |
| 0.51-1.0   | 5        | 0.81%   |
| 0.01-0.5   | 3        | 0.49%   |
| 16.01-24.0 | 2        | 0.32%   |
| 32.01-64.0 | 1        | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 118      | 17.56%  |
| Goldstar             | 83       | 12.35%  |
| Dell                 | 73       | 10.86%  |
| Hewlett-Packard      | 46       | 6.85%   |
| Acer                 | 43       | 6.4%    |
| AOC                  | 39       | 5.8%    |
| Ancor Communications | 38       | 5.65%   |
| ASUSTek Computer     | 36       | 5.36%   |
| BenQ                 | 33       | 4.91%   |
| Philips              | 14       | 2.08%   |
| MSI                  | 12       | 1.79%   |
| Lenovo               | 12       | 1.79%   |
| Iiyama               | 10       | 1.49%   |
| Sceptre Tech         | 8        | 1.19%   |
| NEC Computers        | 6        | 0.89%   |
| Gigabyte Technology  | 6        | 0.89%   |
| ViewSonic            | 5        | 0.74%   |
| Sony                 | 5        | 0.74%   |
| Unknown              | 4        | 0.6%    |
| Eizo                 | 4        | 0.6%    |
| Vizio                | 3        | 0.45%   |
| Viotek               | 3        | 0.45%   |
| Sharp                | 3        | 0.45%   |
| Pioneer              | 3        | 0.45%   |
| Vestel Elektronik    | 2        | 0.3%    |
| Valve                | 2        | 0.3%    |
| Toshiba              | 2        | 0.3%    |
| SKY                  | 2        | 0.3%    |
| Plain Tree Systems   | 2        | 0.3%    |
| Pixio                | 2        | 0.3%    |
| NCS                  | 2        | 0.3%    |
| Mi                   | 2        | 0.3%    |
| LLL                  | 2        | 0.3%    |
| LG Electronics       | 2        | 0.3%    |
| ITE                  | 2        | 0.3%    |
| HUAWEI               | 2        | 0.3%    |
| GDH                  | 2        | 0.3%    |
| Fujitsu Siemens      | 2        | 0.3%    |
| Arnos Instruments    | 2        | 0.3%    |
| ___                  | 1        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 7        | 0.99%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5        | 0.71%   |
| Ancor Communications VE247 ACI2493 1920x1080 530x300mm 24.0-inch      | 5        | 0.71%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 4        | 0.56%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 4        | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 0.56%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 4        | 0.56%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 4        | 0.56%   |
| AOC 2460G5 AOC0001 1920x1080 531x299mm 24.0-inch                      | 4        | 0.56%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 4        | 0.56%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch    | 3        | 0.42%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch     | 3        | 0.42%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 0.42%   |
| Hewlett-Packard E231 HWP3063 1920x1080 509x286mm 23.0-inch            | 3        | 0.42%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch           | 3        | 0.42%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 3        | 0.42%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 3        | 0.42%   |
| Dell AW3821DW DELA17F 3840x1600 880x367mm 37.5-inch                   | 3        | 0.42%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                    | 3        | 0.42%   |
| BenQ G2420HD BNQ7840 1920x1080 530x300mm 24.0-inch                    | 3        | 0.42%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch          | 3        | 0.42%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 3        | 0.42%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch      | 3        | 0.42%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 521x293mm 23.5-inch | 3        | 0.42%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 2        | 0.28%   |
| Valve Index HMD VLV91A8 0x17                                          | 2        | 0.28%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 2        | 0.28%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch     | 2        | 0.28%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 2        | 0.28%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch   | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 950x540mm 43.0-inch | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 2        | 0.28%   |
| Samsung Electronics LC34G55T SAM711A 3440x1440 798x334mm 34.1-inch    | 2        | 0.28%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 2        | 0.28%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 2        | 0.28%   |
| Samsung Electronics C32JG5x SAM0F55 2560x1440 697x392mm 31.5-inch     | 2        | 0.28%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 2        | 0.28%   |
| Philips PHL 322E1 PHLC20F 1920x1080 698x393mm 31.5-inch               | 2        | 0.28%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 2        | 0.28%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 2        | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 305      | 47.43%  |
| 3840x2160 (4K)     | 93       | 14.46%  |
| 2560x1440 (QHD)    | 68       | 10.58%  |
| 3440x1440          | 29       | 4.51%   |
| 2560x1080          | 21       | 3.27%   |
| 1680x1050 (WSXGA+) | 21       | 3.27%   |
| 1366x768 (WXGA)    | 18       | 2.8%    |
| 1920x1200 (WUXGA)  | 16       | 2.49%   |
| 1280x1024 (SXGA)   | 16       | 2.49%   |
| 1600x900 (HD+)     | 12       | 1.87%   |
| 3840x1080          | 9        | 1.4%    |
| 1920x540           | 6        | 0.93%   |
| 1440x900 (WXGA+)   | 5        | 0.78%   |
| 1360x768           | 5        | 0.78%   |
| 3840x1600          | 4        | 0.62%   |
| 1024x768 (XGA)     | 3        | 0.47%   |
| Unknown            | 3        | 0.47%   |
| 2560x1600          | 2        | 0.31%   |
| 1600x1200          | 2        | 0.31%   |
| 3280x1080          | 1        | 0.16%   |
| 3040x900           | 1        | 0.16%   |
| 2880x1600          | 1        | 0.16%   |
| 1280x800 (WXGA)    | 1        | 0.16%   |
| 1280x720 (HD)      | 1        | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 130      | 19.46%  |
| 24      | 105      | 15.72%  |
| 23      | 84       | 12.57%  |
| 21      | 54       | 8.08%   |
| 31      | 50       | 7.49%   |
| 34      | 46       | 6.89%   |
| Unknown | 23       | 3.44%   |
| 22      | 17       | 2.54%   |
| 19      | 15       | 2.25%   |
| 18      | 15       | 2.25%   |
| 32      | 14       | 2.1%    |
| 17      | 12       | 1.8%    |
| 72      | 11       | 1.65%   |
| 84      | 10       | 1.5%    |
| 20      | 10       | 1.5%    |
| 48      | 8        | 1.2%    |
| 25      | 7        | 1.05%   |
| 28      | 6        | 0.9%    |
| 15      | 6        | 0.9%    |
| 37      | 5        | 0.75%   |
| 54      | 4        | 0.6%    |
| 46      | 4        | 0.6%    |
| 26      | 4        | 0.6%    |
| 35      | 3        | 0.45%   |
| 65      | 2        | 0.3%    |
| 52      | 2        | 0.3%    |
| 49      | 2        | 0.3%    |
| 47      | 2        | 0.3%    |
| 44      | 2        | 0.3%    |
| 42      | 2        | 0.3%    |
| 33      | 2        | 0.3%    |
| 29      | 2        | 0.3%    |
| 12      | 2        | 0.3%    |
| 75      | 1        | 0.15%   |
| 69      | 1        | 0.15%   |
| 61      | 1        | 0.15%   |
| 57      | 1        | 0.15%   |
| 40      | 1        | 0.15%   |
| 36      | 1        | 0.15%   |
| 30      | 1        | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 288      | 45%     |
| 401-500     | 102      | 15.94%  |
| 601-700     | 75       | 11.72%  |
| 701-800     | 62       | 9.69%   |
| 1001-1500   | 26       | 4.06%   |
| 1501-2000   | 23       | 3.59%   |
| Unknown     | 23       | 3.59%   |
| 301-350     | 18       | 2.81%   |
| 801-900     | 10       | 1.56%   |
| 351-400     | 7        | 1.09%   |
| 901-1000    | 4        | 0.63%   |
| 201-300     | 2        | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 453      | 74.51%  |
| 21/9    | 55       | 9.05%   |
| 16/10   | 52       | 8.55%   |
| 5/4     | 18       | 2.96%   |
| 32/9    | 12       | 1.97%   |
| Unknown | 11       | 1.81%   |
| 4/3     | 7        | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 198      | 30.51%  |
| 301-350        | 134      | 20.65%  |
| 351-500        | 117      | 18.03%  |
| 251-300        | 42       | 6.47%   |
| 151-200        | 41       | 6.32%   |
| More than 1000 | 33       | 5.08%   |
| 501-1000       | 27       | 4.16%   |
| 141-150        | 26       | 4.01%   |
| Unknown        | 23       | 3.54%   |
| 101-110        | 6        | 0.92%   |
| 71-80          | 2        | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 372      | 61.18%  |
| 101-120       | 131      | 21.55%  |
| 121-160       | 36       | 5.92%   |
| 1-50          | 27       | 4.44%   |
| Unknown       | 23       | 3.78%   |
| 161-240       | 18       | 2.96%   |
| More than 240 | 1        | 0.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 442      | 72.46%  |
| 2     | 118      | 19.34%  |
| 0     | 28       | 4.59%   |
| 3     | 18       | 2.95%   |
| 4     | 3        | 0.49%   |
| 6     | 1        | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 348      | 39.37%  |
| Intel                           | 324      | 36.65%  |
| Qualcomm Atheros                | 51       | 5.77%   |
| Broadcom                        | 29       | 3.28%   |
| TP-Link                         | 15       | 1.7%    |
| MediaTek                        | 13       | 1.47%   |
| Ralink Technology               | 12       | 1.36%   |
| NetGear                         | 10       | 1.13%   |
| Microsoft                       | 8        | 0.9%    |
| InterBiometrics                 | 7        | 0.79%   |
| Aquantia                        | 7        | 0.79%   |
| Ralink                          | 6        | 0.68%   |
| Nvidia                          | 6        | 0.68%   |
| Xiaomi                          | 5        | 0.57%   |
| Samsung Electronics             | 5        | 0.57%   |
| D-Link                          | 5        | 0.57%   |
| Qualcomm Atheros Communications | 3        | 0.34%   |
| ASUSTek Computer                | 3        | 0.34%   |
| Mellanox Technologies           | 2        | 0.23%   |
| Huawei Technologies             | 2        | 0.23%   |
| Google                          | 2        | 0.23%   |
| Broadcom Limited                | 2        | 0.23%   |
| STMicroelectronics              | 1        | 0.11%   |
| Sitecom Europe                  | 1        | 0.11%   |
| SIEMENS                         | 1        | 0.11%   |
| Qualcomm                        | 1        | 0.11%   |
| OPPO Electronics                | 1        | 0.11%   |
| Micro Star International        | 1        | 0.11%   |
| Marvell Technology Group        | 1        | 0.11%   |
| Manta                           | 1        | 0.11%   |
| Lenovo                          | 1        | 0.11%   |
| IMC Networks                    | 1        | 0.11%   |
| Hyperkin                        | 1        | 0.11%   |
| Gemtek                          | 1        | 0.11%   |
| Edimax Technology               | 1        | 0.11%   |
| DisplayLink                     | 1        | 0.11%   |
| D-Link System                   | 1        | 0.11%   |
| Belkin Components               | 1        | 0.11%   |
| AVM                             | 1        | 0.11%   |
| ASIX Electronics                | 1        | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 247      | 23.52%  |
| Intel Wi-Fi 6 AX200                                               | 82       | 7.81%   |
| Intel I211 Gigabit Network Connection                             | 79       | 7.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 68       | 6.48%   |
| Intel Ethernet Controller I225-V                                  | 47       | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25       | 2.38%   |
| Intel Ethernet Connection (2) I219-V                              | 22       | 2.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 22       | 2.1%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 15       | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 15       | 1.43%   |
| Intel Ethernet Connection (7) I219-V                              | 15       | 1.43%   |
| Realtek 802.11ac NIC                                              | 14       | 1.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 14       | 1.33%   |
| Intel Ethernet Connection (2) I218-V                              | 12       | 1.14%   |
| Intel Wireless-AC 9260                                            | 11       | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 10       | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 9        | 0.86%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 9        | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7        | 0.67%   |
| InterBiometrics Io                                                | 7        | 0.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 6        | 0.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 0.57%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 6        | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 6        | 0.57%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6        | 0.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 5        | 0.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5        | 0.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 0.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 0.48%   |
| Ralink MT7601U Wireless Adapter                                   | 5        | 0.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5        | 0.48%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 5        | 0.48%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 0.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4        | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4        | 0.38%   |
| Nvidia MCP61 Ethernet                                             | 4        | 0.38%   |
| NetGear A6210                                                     | 4        | 0.38%   |
| Microsoft XBOX ACC                                                | 4        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 172      | 48.18%  |
| Realtek Semiconductor           | 59       | 16.53%  |
| Qualcomm Atheros                | 25       | 7%      |
| Broadcom                        | 21       | 5.88%   |
| TP-Link                         | 13       | 3.64%   |
| MediaTek                        | 13       | 3.64%   |
| Ralink Technology               | 12       | 3.36%   |
| NetGear                         | 10       | 2.8%    |
| Microsoft                       | 8        | 2.24%   |
| Ralink                          | 6        | 1.68%   |
| D-Link                          | 4        | 1.12%   |
| Qualcomm Atheros Communications | 3        | 0.84%   |
| ASUSTek Computer                | 3        | 0.84%   |
| Sitecom Europe                  | 1        | 0.28%   |
| Micro Star International        | 1        | 0.28%   |
| IMC Networks                    | 1        | 0.28%   |
| Gemtek                          | 1        | 0.28%   |
| Edimax Technology               | 1        | 0.28%   |
| D-Link System                   | 1        | 0.28%   |
| Belkin Components               | 1        | 0.28%   |
| AVM                             | 1        | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 82       | 22.65%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 22       | 6.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 15       | 4.14%   |
| Realtek 802.11ac NIC                                                                          | 14       | 3.87%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 14       | 3.87%   |
| Intel Wireless-AC 9260                                                                        | 11       | 3.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 10       | 2.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 9        | 2.49%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 9        | 2.49%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 6        | 1.66%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                                   | 6        | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 6        | 1.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 5        | 1.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 5        | 1.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 5        | 1.38%   |
| Ralink MT7601U Wireless Adapter                                                               | 5        | 1.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5        | 1.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 5        | 1.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 4        | 1.1%    |
| NetGear A6210                                                                                 | 4        | 1.1%    |
| Microsoft XBOX ACC                                                                            | 4        | 1.1%    |
| Microsoft Xbox 360 Wireless Adapter                                                           | 4        | 1.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 4        | 1.1%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 4        | 1.1%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 3        | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 0.83%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 0.83%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 3        | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 3        | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 3        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 3        | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3        | 0.83%   |
| Intel Wireless Gigabit 17265                                                                  | 3        | 0.83%   |
| Intel Wireless 7265                                                                           | 3        | 0.83%   |
| Intel Wireless 7260                                                                           | 3        | 0.83%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 2        | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2        | 0.55%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 2        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 323      | 49.09%  |
| Intel                    | 258      | 39.21%  |
| Qualcomm Atheros         | 28       | 4.26%   |
| Broadcom                 | 9        | 1.37%   |
| Aquantia                 | 7        | 1.06%   |
| Nvidia                   | 6        | 0.91%   |
| Xiaomi                   | 5        | 0.76%   |
| Samsung Electronics      | 5        | 0.76%   |
| TP-Link                  | 2        | 0.3%    |
| Mellanox Technologies    | 2        | 0.3%    |
| Huawei Technologies      | 2        | 0.3%    |
| Google                   | 2        | 0.3%    |
| Broadcom Limited         | 2        | 0.3%    |
| Qualcomm                 | 1        | 0.15%   |
| OPPO Electronics         | 1        | 0.15%   |
| Marvell Technology Group | 1        | 0.15%   |
| Lenovo                   | 1        | 0.15%   |
| DisplayLink              | 1        | 0.15%   |
| D-Link                   | 1        | 0.15%   |
| ASIX Electronics         | 1        | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 247      | 36.59%  |
| Intel I211 Gigabit Network Connection                             | 79       | 11.7%   |
| Realtek RTL8125 2.5GbE Controller                                 | 68       | 10.07%  |
| Intel Ethernet Controller I225-V                                  | 47       | 6.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25       | 3.7%    |
| Intel Ethernet Connection (2) I219-V                              | 22       | 3.26%   |
| Intel Ethernet Connection I217-LM                                 | 15       | 2.22%   |
| Intel Ethernet Connection (7) I219-V                              | 15       | 2.22%   |
| Intel Ethernet Connection (2) I218-V                              | 12       | 1.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 1.19%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7        | 1.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 6        | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 0.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4        | 0.59%   |
| Nvidia MCP61 Ethernet                                             | 4        | 0.59%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 0.59%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 0.59%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.44%   |
| Intel Ethernet Connection (17) I219-V                             | 3        | 0.44%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.44%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 3        | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2        | 0.3%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2        | 0.3%    |
| Realtek Killer E3000 2.5GbE Controller                            | 2        | 0.3%    |
| Nvidia MCP77 Ethernet                                             | 2        | 0.3%    |
| Mellanox MT27500 Family [ConnectX-3]                              | 2        | 0.3%    |
| Intel Ethernet Controller X550                                    | 2        | 0.3%    |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.3%    |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 0.3%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.3%    |
| Huawei STK-L21                                                    | 2        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 599      | 62.99%  |
| WiFi     | 339      | 35.65%  |
| Modem    | 9        | 0.95%   |
| Unknown  | 4        | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 454      | 71.84%  |
| WiFi     | 178      | 28.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 320      | 52.72%  |
| 2     | 235      | 38.71%  |
| 3     | 42       | 6.92%   |
| 0     | 7        | 1.15%   |
| 4     | 3        | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 418      | 68.52%  |
| Yes  | 192      | 31.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 156      | 54.93%  |
| Cambridge Silicon Radio         | 52       | 18.31%  |
| Realtek Semiconductor           | 16       | 5.63%   |
| ASUSTek Computer                | 15       | 5.28%   |
| Qualcomm Atheros Communications | 9        | 3.17%   |
| Broadcom                        | 8        | 2.82%   |
| MediaTek                        | 6        | 2.11%   |
| Foxconn / Hon Hai               | 5        | 1.76%   |
| Apple                           | 5        | 1.76%   |
| TP-Link                         | 3        | 1.06%   |
| Dynex                           | 2        | 0.7%    |
| SINO WEALTH                     | 1        | 0.35%   |
| Micro Star International        | 1        | 0.35%   |
| Lite-On Technology              | 1        | 0.35%   |
| IMC Networks                    | 1        | 0.35%   |
| HTC (High Tech Computer)        | 1        | 0.35%   |
| Edimax Technology               | 1        | 0.35%   |
| Belkin Components               | 1        | 0.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 75       | 26.41%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 52       | 18.31%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 21       | 7.39%   |
| Intel AX201 Bluetooth                                                | 16       | 5.63%   |
| Intel AX210 Bluetooth                                                | 11       | 3.87%   |
| Realtek Bluetooth Radio                                              | 10       | 3.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 10       | 3.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 10       | 3.52%   |
| Intel Bluetooth wireless interface                                   | 9        | 3.17%   |
| MediaTek Wireless_Device                                             | 6        | 2.11%   |
| ASUS Bluetooth Device                                                | 6        | 2.11%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5        | 1.76%   |
| ASUS Bluetooth Radio                                                 | 5        | 1.76%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4        | 1.41%   |
| Qualcomm Atheros  Bluetooth Device                                   | 4        | 1.41%   |
| Intel Bluetooth Device                                               | 4        | 1.41%   |
| TP-Link UB500 Adapter                                                | 3        | 1.06%   |
| Foxconn / Hon Hai Wireless_Device                                    | 3        | 1.06%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 2        | 0.7%    |
| Qualcomm Atheros AR9462 Bluetooth                                    | 2        | 0.7%    |
| Foxconn / Hon Hai Bluetooth Device                                   | 2        | 0.7%    |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 2        | 0.7%    |
| Broadcom BCM43142 Bluetooth 4.0                                      | 2        | 0.7%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 2        | 0.7%    |
| Apple Bluetooth USB Host Controller                                  | 2        | 0.7%    |
| SINO WEALTH RK Bluetooth Keyboar                                     | 1        | 0.35%   |
| Realtek RTL8821A Bluetooth                                           | 1        | 0.35%   |
| Realtek Bluetooth 5.1 Radio                                          | 1        | 0.35%   |
| Qualcomm Atheros Bluetooth                                           | 1        | 0.35%   |
| Micro Star International Bluetooth Device                            | 1        | 0.35%   |
| Lite-On Bluetooth Device                                             | 1        | 0.35%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.35%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.35%   |
| Edimax Bluetooth Adapter                                             | 1        | 0.35%   |
| Broadcom BCM2035 Bluetooth dongle                                    | 1        | 0.35%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.35%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 0.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1        | 0.35%   |
| Apple Bluetooth Host Controller                                      | 1        | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 366      | 30.27%  |
| Nvidia                               | 299      | 24.73%  |
| Intel                                | 284      | 23.49%  |
| C-Media Electronics                  | 31       | 2.56%   |
| Logitech                             | 20       | 1.65%   |
| Razer USA                            | 16       | 1.32%   |
| Kingston Technology                  | 15       | 1.24%   |
| Focusrite-Novation                   | 13       | 1.08%   |
| ASUSTek Computer                     | 12       | 0.99%   |
| JMTek                                | 11       | 0.91%   |
| Creative Labs                        | 11       | 0.91%   |
| Micro Star International             | 10       | 0.83%   |
| Blue Microphones                     | 7        | 0.58%   |
| Generalplus Technology               | 6        | 0.5%    |
| Corsair                              | 6        | 0.5%    |
| Texas Instruments                    | 5        | 0.41%   |
| SteelSeries ApS                      | 5        | 0.41%   |
| Creative Technology                  | 5        | 0.41%   |
| Tenx Technology                      | 4        | 0.33%   |
| Sony                                 | 3        | 0.25%   |
| Mackie Designs                       | 3        | 0.25%   |
| GN Netcom                            | 3        | 0.25%   |
| Valve Software                       | 2        | 0.17%   |
| Trust                                | 2        | 0.17%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.17%   |
| SAVITECH                             | 2        | 0.17%   |
| Plantronics                          | 2        | 0.17%   |
| Nordic Semiconductor ASA             | 2        | 0.17%   |
| Native Instruments                   | 2        | 0.17%   |
| M-Audio                              | 2        | 0.17%   |
| Lenovo                               | 2        | 0.17%   |
| KTMicro                              | 2        | 0.17%   |
| FiiO Electronics Technology          | 2        | 0.17%   |
| DSEA A/S                             | 2        | 0.17%   |
| BR25                                 | 2        | 0.17%   |
| Bose                                 | 2        | 0.17%   |
| BEHRINGER International              | 2        | 0.17%   |
| Barco Display Systems                | 2        | 0.17%   |
| Astro Gaming                         | 2        | 0.17%   |
| Arturia                              | 2        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 150      | 10.53%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 67       | 4.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 52       | 3.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 50       | 3.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 35       | 2.46%   |
| Nvidia GP104 High Definition Audio Controller                              | 30       | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 29       | 2.04%   |
| Intel 200 Series PCH HD Audio                                              | 29       | 2.04%   |
| Nvidia TU116 High Definition Audio Controller                              | 28       | 1.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 28       | 1.96%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 28       | 1.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 28       | 1.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 26       | 1.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 25       | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 24       | 1.68%   |
| Intel Cannon Lake PCH cAVS                                                 | 24       | 1.68%   |
| Nvidia GA102 High Definition Audio Controller                              | 23       | 1.61%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 23       | 1.61%   |
| Nvidia GP106 High Definition Audio Controller                              | 22       | 1.54%   |
| Nvidia GA104 High Definition Audio Controller                              | 21       | 1.47%   |
| Nvidia TU104 HD Audio Controller                                           | 20       | 1.4%    |
| AMD Navi 10 HDMI Audio                                                     | 20       | 1.4%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 19       | 1.33%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 18       | 1.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 18       | 1.26%   |
| Nvidia TU106 High Definition Audio Controller                              | 16       | 1.12%   |
| Nvidia GA106 High Definition Audio Controller                              | 16       | 1.12%   |
| Intel Alder Lake-S HD Audio Controller                                     | 16       | 1.12%   |
| AMD FCH Azalia Controller                                                  | 13       | 0.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 12       | 0.84%   |
| Kingston Technology HyperX 7.1 Audio                                       | 11       | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 11       | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                              | 10       | 0.7%    |
| Micro Star International USB Audio                                         | 10       | 0.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10       | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9        | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                         | 9        | 0.63%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 9        | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8        | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 35       | 29.17%  |
| Kingston                     | 20       | 16.67%  |
| G.Skill                      | 19       | 15.83%  |
| Team                         | 9        | 7.5%    |
| Samsung Electronics          | 9        | 7.5%    |
| Unknown                      | 6        | 5%      |
| Crucial                      | 6        | 5%      |
| Micron Technology            | 5        | 4.17%   |
| SK hynix                     | 4        | 3.33%   |
| Unknown                      | 2        | 1.67%   |
| Teikon                       | 1        | 0.83%   |
| Patriot Memory (PDP Systems) | 1        | 0.83%   |
| Patriot Memory               | 1        | 0.83%   |
| Patriot                      | 1        | 0.83%   |
| Avant                        | 1        | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                   | 8        | 6.4%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s                   | 5        | 4%      |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s                     | 4        | 3.2%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s                      | 2        | 1.6%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s                     | 2        | 1.6%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                     | 2        | 1.6%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                     | 2        | 1.6%    |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s                   | 2        | 1.6%    |
| G.Skill RAM F4-3600C18-8GVK 8GB DIMM DDR4 3600MT/s                      | 2        | 1.6%    |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s                    | 2        | 1.6%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s                     | 2        | 1.6%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                    | 2        | 1.6%    |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3200MT/s                | 2        | 1.6%    |
| Corsair RAM CMK64GX5M2B5200C40 32GB DIMM DDR5 4800MT/s                  | 2        | 1.6%    |
| Unknown                                                                 | 2        | 1.6%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                               | 1        | 0.8%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                                    | 1        | 0.8%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 1        | 0.8%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 1        | 0.8%    |
| Unknown RAM Module 16GB DIMM DDR4 3600MT/s                              | 1        | 0.8%    |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s                     | 1        | 0.8%    |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s                      | 1        | 0.8%    |
| Teikon RAM TMT451U6BFR8C-PBHJ 4GB DIMM DDR3 1600MT/s                    | 1        | 0.8%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s                     | 1        | 0.8%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s                      | 1        | 0.8%    |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s                      | 1        | 0.8%    |
| SK hynix RAM HMT42GR7AFR4A 16GB DIMM DDR3 1600MT/s                      | 1        | 0.8%    |
| SK hynix RAM HMT351U6CFR8C-PBA 2GB DIMM DDR3 1600MT/s                   | 1        | 0.8%    |
| SK hynix RAM HMA82GU6DJR8N-WM 16GB DIMM DDR4 2933MT/s                   | 1        | 0.8%    |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s                    | 1        | 0.8%    |
| Samsung RAM Module 8GB Row Of Chips LPDDR4 2933MT/s                     | 1        | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                   | 1        | 0.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                   | 1        | 0.8%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                   | 1        | 0.8%    |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                     | 1        | 0.8%    |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s                     | 1        | 0.8%    |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s                         | 1        | 0.8%    |
| Patriot Memory RAM 4400 C19 Series 8GB DIMM DDR4 3000MT/s               | 1        | 0.8%    |
| Patriot Memory (PDP Systems) RAM 3200 C18 Series 8GB DIMM DDR4 3333MT/s | 1        | 0.8%    |
| Micron RAM M378A1K43BB2G3A141 8GB DIMM DDR4 2400MT/s                    | 1        | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 88       | 78.57%  |
| DDR3    | 18       | 16.07%  |
| DDR5    | 3        | 2.68%   |
| Unknown | 2        | 1.79%   |
| LPDDR4  | 1        | 0.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 107      | 95.54%  |
| SODIMM       | 4        | 3.57%   |
| Row Of Chips | 1        | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 56       | 47.46%  |
| 16384 | 31       | 26.27%  |
| 4096  | 19       | 16.1%   |
| 32768 | 11       | 9.32%   |
| 2048  | 1        | 0.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 28       | 23.73%  |
| 3200  | 18       | 15.25%  |
| 1600  | 14       | 11.86%  |
| 2400  | 7        | 5.93%   |
| 3466  | 6        | 5.08%   |
| 3800  | 5        | 4.24%   |
| 1333  | 5        | 4.24%   |
| 3000  | 4        | 3.39%   |
| 2667  | 4        | 3.39%   |
| 3733  | 3        | 2.54%   |
| 2933  | 3        | 2.54%   |
| 2133  | 3        | 2.54%   |
| 4800  | 2        | 1.69%   |
| 3866  | 2        | 1.69%   |
| 2800  | 2        | 1.69%   |
| 2666  | 2        | 1.69%   |
| 1866  | 2        | 1.69%   |
| 6400  | 1        | 0.85%   |
| 4000  | 1        | 0.85%   |
| 3666  | 1        | 0.85%   |
| 3400  | 1        | 0.85%   |
| 3333  | 1        | 0.85%   |
| 3100  | 1        | 0.85%   |
| 3066  | 1        | 0.85%   |
| 2733  | 1        | 0.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 7        | 30.43%  |
| Hewlett-Packard     | 4        | 17.39%  |
| Canon               | 4        | 17.39%  |
| Samsung Electronics | 3        | 13.04%  |
| Seiko Epson         | 2        | 8.7%    |
| QinHeng Electronics | 1        | 4.35%   |
| Prolific Technology | 1        | 4.35%   |
| Dymo-CoStar         | 1        | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Brother HL-2130 series                 | 3        | 12.5%   |
| Seiko Epson WF-4830 Series             | 1        | 4.17%   |
| Seiko Epson ET-2800 Series             | 1        | 4.17%   |
| Samsung SCX-3400 Series                | 1        | 4.17%   |
| Samsung ML-191x/ML-252x Laser Printer  | 1        | 4.17%   |
| Samsung M2070 Series                   | 1        | 4.17%   |
| QinHeng CH340S                         | 1        | 4.17%   |
| Prolific PL2305 Parallel Port          | 1        | 4.17%   |
| HP PSC-1315/PSC-1317                   | 1        | 4.17%   |
| HP LaserJet Professional P1102w        | 1        | 4.17%   |
| HP LaserJet P2035                      | 1        | 4.17%   |
| HP ENVY Pro 6400 series                | 1        | 4.17%   |
| Dymo-CoStar DYMO LabelWriter 4XL       | 1        | 4.17%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 4.17%   |
| Canon TR8500 series                    | 1        | 4.17%   |
| Canon Pro9000II series                 | 1        | 4.17%   |
| Canon PIXMA MP240                      | 1        | 4.17%   |
| Canon PIXMA MG2500 Series              | 1        | 4.17%   |
| Brother MFC-L2700DW                    | 1        | 4.17%   |
| Brother MFC-5440CN                     | 1        | 4.17%   |
| Brother HL-3140CW series               | 1        | 4.17%   |
| Brother HL-2270DW Laser Printer        | 1        | 4.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 3        | 75%     |
| Mustek Systems | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1        | 25%     |
| Canon CanoScan N650U/N656U         | 1        | 25%     |
| Canon CanoScan LiDE 60             | 1        | 25%     |
| Canon CanoScan LiDE 200            | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 60       | 38.71%  |
| Microdia                      | 10       | 6.45%   |
| Sunplus Innovation Technology | 9        | 5.81%   |
| Microsoft                     | 9        | 5.81%   |
| Samsung Electronics           | 5        | 3.23%   |
| Realtek Semiconductor         | 5        | 3.23%   |
| Razer USA                     | 4        | 2.58%   |
| MacroSilicon                  | 4        | 2.58%   |
| Jieli Technology              | 4        | 2.58%   |
| ARC International             | 4        | 2.58%   |
| Apple                         | 4        | 2.58%   |
| Cubeternet                    | 3        | 1.94%   |
| Valve Software                | 2        | 1.29%   |
| Sunplus IT                    | 2        | 1.29%   |
| LG Electronics                | 2        | 1.29%   |
| Generalplus Technology        | 2        | 1.29%   |
| Creative Technology           | 2        | 1.29%   |
| AVerMedia Technologies        | 2        | 1.29%   |
| Z-Star Microelectronics       | 1        | 0.65%   |
| YGTek                         | 1        | 0.65%   |
| Xiaomi                        | 1        | 0.65%   |
| XHT-210518                    | 1        | 0.65%   |
| WaveRider Communications      | 1        | 0.65%   |
| USB Camera                    | 1        | 0.65%   |
| Trust                         | 1        | 0.65%   |
| SN0002                        | 1        | 0.65%   |
| Owon                          | 1        | 0.65%   |
| Novatek Microelectronics      | 1        | 0.65%   |
| Lenovo                        | 1        | 0.65%   |
| KYE Systems (Mouse Systems)   | 1        | 0.65%   |
| HTC (High Tech Computer)      | 1        | 0.65%   |
| Hewlett-Packard               | 1        | 0.65%   |
| HD 2MP WEBCAM                 | 1        | 0.65%   |
| GenesysLogic Technology       | 1        | 0.65%   |
| Genesys Logic                 | 1        | 0.65%   |
| eMeet                         | 1        | 0.65%   |
| Elgato Systems                | 1        | 0.65%   |
| Chicony Electronics           | 1        | 0.65%   |
| Celestron                     | 1        | 0.65%   |
| Anker PowerConf C200          | 1        | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 17       | 10.97%  |
| Logitech HD Pro Webcam C920                           | 11       | 7.1%    |
| Logitech C922 Pro Stream Webcam                       | 6        | 3.87%   |
| Samsung Galaxy A5 (MTP)                               | 5        | 3.23%   |
| Microdia USB 2.0 Camera                               | 5        | 3.23%   |
| Razer USA Gaming Webcam [Kiyo]                        | 4        | 2.58%   |
| MacroSilicon USB Video                                | 4        | 2.58%   |
| Logitech Webcam C925e                                 | 4        | 2.58%   |
| Jieli USB PHY 2.0                                     | 4        | 2.58%   |
| ARC International Camera                              | 4        | 2.58%   |
| Apple iPhone5/5C/5S/6                                 | 4        | 2.58%   |
| Microsoft LifeCam HD-3000                             | 3        | 1.94%   |
| Microsoft LifeCam Cinema                              | 3        | 1.94%   |
| Microdia Webcam Vitade AF                             | 3        | 1.94%   |
| Logitech HD Webcam C525                               | 3        | 1.94%   |
| Logitech C920 PRO HD Webcam                           | 3        | 1.94%   |
| Logitech BRIO Ultra HD Webcam                         | 3        | 1.94%   |
| Valve Software 3D Camera                              | 2        | 1.29%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                    | 2        | 1.29%   |
| Sunplus SPCA2650 AV Camera                            | 2        | 1.29%   |
| Sunplus SPCA2281 Web Camera                           | 2        | 1.29%   |
| Realtek Full HD webcam                                | 2        | 1.29%   |
| Logitech Webcam C930e                                 | 2        | 1.29%   |
| Logitech StreamCam                                    | 2        | 1.29%   |
| Logitech HD Webcam C615                               | 2        | 1.29%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 2        | 1.29%   |
| AVerMedia Live Streamer CAM 313                       | 2        | 1.29%   |
| Z-Star Vimicro USB Camera (Altair)                    | 1        | 0.65%   |
| YGTek Webcam                                          | 1        | 0.65%   |
| Xiaomi POCO X3 Pro                                    | 1        | 0.65%   |
| XHT-210518 EC500X                                     | 1        | 0.65%   |
| WaveRider USB 2.0 Camera                              | 1        | 0.65%   |
| USB Camera USB Camera                                 | 1        | 0.65%   |
| Trust USB Camera                                      | 1        | 0.65%   |
| Sunplus USB 2.0 Camera                                | 1        | 0.65%   |
| Sunplus NexiGo N930AF FHD Webcam                      | 1        | 0.65%   |
| Sunplus MYPIN HD Capture                              | 1        | 0.65%   |
| Sunplus HD 720P webcam                                | 1        | 0.65%   |
| Sunplus Full HD webcam                                | 1        | 0.65%   |
| SN0002 1080P Web Camera                               | 1        | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 1        | 33.33%  |
| Alcor Micro           | 1        | 33.33%  |
| Advanced Card Systems | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 33.33%  |
| Advanced Card Systems ACR1252 Dual Reader              | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 498      | 81.11%  |
| 1     | 104      | 16.94%  |
| 2     | 11       | 1.79%   |
| 3     | 1        | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 44       | 35.48%  |
| Graphics card            | 30       | 24.19%  |
| Bluetooth                | 12       | 9.68%   |
| Unassigned class         | 7        | 5.65%   |
| Sound                    | 7        | 5.65%   |
| Net/ethernet             | 6        | 4.84%   |
| Multimedia controller    | 4        | 3.23%   |
| Communication controller | 4        | 3.23%   |
| Network                  | 3        | 2.42%   |
| Chipcard                 | 3        | 2.42%   |
| Camera                   | 2        | 1.61%   |
| Storage/ide              | 1        | 0.81%   |
| Fingerprint reader       | 1        | 0.81%   |

