Pop!_OS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 4613

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
| Intel         | DP55WB AAE64798-206         | [2373b5141b](https://linux-hardware.org/?probe=2373b5141b) | Dec 29, 2022 |
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
| Gigabyte      | B550I AORUS PRO AX          | [33fce09f33](https://linux-hardware.org/?probe=33fce09f33) | Dec 20, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [858931394a](https://linux-hardware.org/?probe=858931394a) | Dec 20, 2022 |
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
| Intel         | X79M-S                      | [f99b1f2b67](https://linux-hardware.org/?probe=f99b1f2b67) | Dec 16, 2022 |
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
| ASUSTek       | PRIME B450M-K               | [7e82777792](https://linux-hardware.org/?probe=7e82777792) | Dec 06, 2022 |
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
| MSI           | 2AE0                        | [cfb41eba48](https://linux-hardware.org/?probe=cfb41eba48) | Nov 19, 2022 |
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
| Positivo      | POS-EIH61CR POSITIVO        | [81bd40e949](https://linux-hardware.org/?probe=81bd40e949) | Nov 10, 2022 |
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
| Colorful T... | A320M-K PRO YV14            | [cf54f0dbf3](https://linux-hardware.org/?probe=cf54f0dbf3) | Nov 03, 2022 |
| Colorful T... | A320M-K PRO YV14            | [5059f2f52e](https://linux-hardware.org/?probe=5059f2f52e) | Nov 03, 2022 |
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
| Gigabyte      | TRX40 DESIGNARE             | [a2962588fa](https://linux-hardware.org/?probe=a2962588fa) | Sep 04, 2022 |
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
| System76      | Thelio thelio-r2            | [6eb968883d](https://linux-hardware.org/?probe=6eb968883d) | Aug 22, 2022 |
| ASRock        | X470 Taichi                 | [8f7d642c46](https://linux-hardware.org/?probe=8f7d642c46) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e8bee7737a](https://linux-hardware.org/?probe=e8bee7737a) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b182084c88](https://linux-hardware.org/?probe=b182084c88) | Aug 22, 2022 |
| Unknown       | GSUO H61V10C                | [1e7ccd0999](https://linux-hardware.org/?probe=1e7ccd0999) | Aug 22, 2022 |
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
| MSI           | B360-A PRO                  | [a5505919b5](https://linux-hardware.org/?probe=a5505919b5) | Aug 14, 2022 |
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
| ASUSTek       | ROG STRIX B450-F GAMING     | [e3dc0a4c49](https://linux-hardware.org/?probe=e3dc0a4c49) | Jul 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [36e0686495](https://linux-hardware.org/?probe=36e0686495) | Jul 28, 2022 |
| MSI           | X370 GAMING PLUS            | [a39ccd24ff](https://linux-hardware.org/?probe=a39ccd24ff) | Jul 27, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [b25ca31168](https://linux-hardware.org/?probe=b25ca31168) | Jul 27, 2022 |
| MSI           | PRO Z690-A DDR4             | [2d81f40aad](https://linux-hardware.org/?probe=2d81f40aad) | Jul 27, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [71f25aa9f5](https://linux-hardware.org/?probe=71f25aa9f5) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| Dell          | 0F896N A02                  | [ede9425ed8](https://linux-hardware.org/?probe=ede9425ed8) | Jul 27, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| MSI           | Z490-A PRO                  | [fe48f1e5cd](https://linux-hardware.org/?probe=fe48f1e5cd) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-A               | [4812de622f](https://linux-hardware.org/?probe=4812de622f) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| ASUSTek       | PRIME Z390-A                | [b8e8d2b6c4](https://linux-hardware.org/?probe=b8e8d2b6c4) | Jul 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [567addf380](https://linux-hardware.org/?probe=567addf380) | Jul 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [221bb14fbd](https://linux-hardware.org/?probe=221bb14fbd) | Jul 24, 2022 |
| HP            | 8433 11                     | [a66fb85e77](https://linux-hardware.org/?probe=a66fb85e77) | Jul 23, 2022 |
| MSI           | MEG X570 ACE                | [f13fde648e](https://linux-hardware.org/?probe=f13fde648e) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8f131b55b9](https://linux-hardware.org/?probe=8f131b55b9) | Jul 22, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [9689ac8020](https://linux-hardware.org/?probe=9689ac8020) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5a52692425](https://linux-hardware.org/?probe=5a52692425) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f524dac3fa](https://linux-hardware.org/?probe=f524dac3fa) | Jul 20, 2022 |
| Positivo      | POS-PIQ77CL                 | [ce9a0fdbbc](https://linux-hardware.org/?probe=ce9a0fdbbc) | Jul 20, 2022 |
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
| Gigabyte      | A320M-S2H V2-CF             | [618141855c](https://linux-hardware.org/?probe=618141855c) | Jul 11, 2022 |
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
| Positivo      | POS-PIQ77CL                 | [1a40c954fc](https://linux-hardware.org/?probe=1a40c954fc) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6ebe4f89b7](https://linux-hardware.org/?probe=6ebe4f89b7) | Jul 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [3458084b51](https://linux-hardware.org/?probe=3458084b51) | Jul 08, 2022 |
| HP            | 3398                        | [fb1290d5b3](https://linux-hardware.org/?probe=fb1290d5b3) | Jul 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8b1a622249](https://linux-hardware.org/?probe=8b1a622249) | Jul 07, 2022 |
| ASUSTek       | PRIME Z390-A                | [0e7b73b341](https://linux-hardware.org/?probe=0e7b73b341) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [9c2efc454e](https://linux-hardware.org/?probe=9c2efc454e) | Jul 06, 2022 |
| MSI           | B360-A PRO                  | [4534101418](https://linux-hardware.org/?probe=4534101418) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [eb5d4499aa](https://linux-hardware.org/?probe=eb5d4499aa) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [e068e197b4](https://linux-hardware.org/?probe=e068e197b4) | Jul 06, 2022 |
| Dell          | 0200DY A00                  | [442b0c2a46](https://linux-hardware.org/?probe=442b0c2a46) | Jul 06, 2022 |
| Soyo          | SY-A68M FS V2.0             | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [7a6f484b16](https://linux-hardware.org/?probe=7a6f484b16) | Jul 06, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [bfa2b2f092](https://linux-hardware.org/?probe=bfa2b2f092) | Jul 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [82fe9f31c7](https://linux-hardware.org/?probe=82fe9f31c7) | Jul 04, 2022 |
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
| ASUSTek       | B85M-E/BR                   | [adfbbd03b6](https://linux-hardware.org/?probe=adfbbd03b6) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [3bceb0a396](https://linux-hardware.org/?probe=3bceb0a396) | Jun 29, 2022 |
| Gigabyte      | B450 AORUS M                | [67dc174a62](https://linux-hardware.org/?probe=67dc174a62) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | [f01192b57e](https://linux-hardware.org/?probe=f01192b57e) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [0a66ce61c6](https://linux-hardware.org/?probe=0a66ce61c6) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [f2b790de57](https://linux-hardware.org/?probe=f2b790de57) | Jun 29, 2022 |
| ASRock        | N68-S                       | [cf9108c19a](https://linux-hardware.org/?probe=cf9108c19a) | Jun 28, 2022 |
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
| ASUSTek       | TUF Gaming X570-PRO         | [c5a5527f1d](https://linux-hardware.org/?probe=c5a5527f1d) | Jun 23, 2022 |
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
| ASUSTek       | ROG STRIX X570-E GAMING     | [cc2e6a1605](https://linux-hardware.org/?probe=cc2e6a1605) | Jun 17, 2022 |
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
| ASUSTek       | M5A97 R2.0                  | [e92127f694](https://linux-hardware.org/?probe=e92127f694) | Jun 10, 2022 |
| MSI           | H97 GAMING 3                | [839bbee3fa](https://linux-hardware.org/?probe=839bbee3fa) | Jun 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [1fef4f1cf3](https://linux-hardware.org/?probe=1fef4f1cf3) | Jun 10, 2022 |
| PCWare        | IPX4105G Pro                | [72ac2cedad](https://linux-hardware.org/?probe=72ac2cedad) | Jun 10, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [9c7b34c996](https://linux-hardware.org/?probe=9c7b34c996) | Jun 09, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [70254d6e4d](https://linux-hardware.org/?probe=70254d6e4d) | Jun 08, 2022 |
| PCWare        | IPX4105G Pro                | [ffccee6734](https://linux-hardware.org/?probe=ffccee6734) | Jun 07, 2022 |
| ASRock        | B365M Pro4                  | [ef5b8100ce](https://linux-hardware.org/?probe=ef5b8100ce) | Jun 07, 2022 |
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
| Dell          | 0R790T A00                  | [f9388b2163](https://linux-hardware.org/?probe=f9388b2163) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [5d899f8fc5](https://linux-hardware.org/?probe=5d899f8fc5) | May 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d1923db949](https://linux-hardware.org/?probe=d1923db949) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b78390767c](https://linux-hardware.org/?probe=b78390767c) | May 28, 2022 |
| MSI           | MS-7717                     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | [57a20bde9f](https://linux-hardware.org/?probe=57a20bde9f) | May 28, 2022 |
| MSI           | MS-7717                     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| ASRock        | B450 Steel Legend           | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Dell          | 040DDP A01                  | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| HP            | 158B                        | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [bdf54228e5](https://linux-hardware.org/?probe=bdf54228e5) | May 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f5195788f8](https://linux-hardware.org/?probe=f5195788f8) | May 27, 2022 |
| ASUSTek       | PRIME Z270-A                | [5d1ee4048a](https://linux-hardware.org/?probe=5d1ee4048a) | May 27, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [084dab5bd4](https://linux-hardware.org/?probe=084dab5bd4) | May 26, 2022 |
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
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [5ebbcedcc1](https://linux-hardware.org/?probe=5ebbcedcc1) | May 22, 2022 |
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
| ASUSTek       | H110M-A/DP                  | [9e2c754ed6](https://linux-hardware.org/?probe=9e2c754ed6) | May 19, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [3f9a21ddc1](https://linux-hardware.org/?probe=3f9a21ddc1) | May 19, 2022 |
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
| ASUSTek       | H170M-PLUS                  | [c1f5cb662f](https://linux-hardware.org/?probe=c1f5cb662f) | May 15, 2022 |
| ASUSTek       | Z87-K                       | [bb296e5f39](https://linux-hardware.org/?probe=bb296e5f39) | May 15, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [91d8b47a30](https://linux-hardware.org/?probe=91d8b47a30) | May 15, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [608664ce7a](https://linux-hardware.org/?probe=608664ce7a) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| MSI           | CSM-B85M-E45                | [85abf64cf5](https://linux-hardware.org/?probe=85abf64cf5) | May 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a049c51989](https://linux-hardware.org/?probe=a049c51989) | May 14, 2022 |
| ASRock        | B450M Pro4-F                | [423fbd3a54](https://linux-hardware.org/?probe=423fbd3a54) | May 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [cb7b6b9cde](https://linux-hardware.org/?probe=cb7b6b9cde) | May 14, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [0cc824e2a5](https://linux-hardware.org/?probe=0cc824e2a5) | May 13, 2022 |
| NZXT          | N7 B550                     | [73441bbfc4](https://linux-hardware.org/?probe=73441bbfc4) | May 12, 2022 |
| Unknown       | BTC79X5                     | [42b222eb65](https://linux-hardware.org/?probe=42b222eb65) | May 12, 2022 |
| Gigabyte      | Z170-Gaming K3              | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| AZW           | BT3 X                       | [a17cb64acb](https://linux-hardware.org/?probe=a17cb64acb) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | [ee225906fc](https://linux-hardware.org/?probe=ee225906fc) | May 12, 2022 |
| Gigabyte      | B75M-D3H                    | [cfae917826](https://linux-hardware.org/?probe=cfae917826) | May 11, 2022 |
| Lenovo        | 0B98401 PRO                 | [16911d5e64](https://linux-hardware.org/?probe=16911d5e64) | May 11, 2022 |
| Gigabyte      | B660 AORUS MASTER DDR4      | [e5981a9f20](https://linux-hardware.org/?probe=e5981a9f20) | May 11, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [1d4364ac51](https://linux-hardware.org/?probe=1d4364ac51) | May 10, 2022 |
| NZXT          | N7 B550                     | [147247dfb6](https://linux-hardware.org/?probe=147247dfb6) | May 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [396a39e5a6](https://linux-hardware.org/?probe=396a39e5a6) | May 10, 2022 |
| ASRock        | X370 Professional Gaming    | [1e22ba0468](https://linux-hardware.org/?probe=1e22ba0468) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [0b3cda16db](https://linux-hardware.org/?probe=0b3cda16db) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [90190717eb](https://linux-hardware.org/?probe=90190717eb) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| Acer          | RS780HVF                    | [431353b969](https://linux-hardware.org/?probe=431353b969) | May 09, 2022 |
| ASUSTek       | Z97-AR                      | [29c93ea162](https://linux-hardware.org/?probe=29c93ea162) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| ASRock        | X299 Taichi CLX             | [47a45fca48](https://linux-hardware.org/?probe=47a45fca48) | May 08, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [17e7dcafe2](https://linux-hardware.org/?probe=17e7dcafe2) | May 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [8964a4c5ec](https://linux-hardware.org/?probe=8964a4c5ec) | May 08, 2022 |
| ECS           | Nettle3                     | [36f8cde007](https://linux-hardware.org/?probe=36f8cde007) | May 08, 2022 |
| HP            | 0AE8h C                     | [bc0fa7f9b8](https://linux-hardware.org/?probe=bc0fa7f9b8) | May 08, 2022 |
| HP            | 0AE8h C                     | [fdf9e3acd8](https://linux-hardware.org/?probe=fdf9e3acd8) | May 08, 2022 |
| Acer          | RS780HVF                    | [1f30630929](https://linux-hardware.org/?probe=1f30630929) | May 08, 2022 |
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
| Gigabyte      | H110M-S2V-CF                | [f2de7ca21b](https://linux-hardware.org/?probe=f2de7ca21b) | May 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [c0ef0738b5](https://linux-hardware.org/?probe=c0ef0738b5) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [4a09f5d3f3](https://linux-hardware.org/?probe=4a09f5d3f3) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [ab716981c3](https://linux-hardware.org/?probe=ab716981c3) | May 02, 2022 |
| Alienware     | 0P0JWX A00                  | [e6e1548aa1](https://linux-hardware.org/?probe=e6e1548aa1) | May 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [a456619489](https://linux-hardware.org/?probe=a456619489) | May 02, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [0e40616573](https://linux-hardware.org/?probe=0e40616573) | May 02, 2022 |
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
| MSI           | B450 TOMAHAWK MAX II        | [6db8017245](https://linux-hardware.org/?probe=6db8017245) | Apr 30, 2022 |
| EVGA          | X58 SLI Classified Tyler... | [07254f2dbb](https://linux-hardware.org/?probe=07254f2dbb) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| MSI           | H110M PRO-VH PLUS           | [876baf36d7](https://linux-hardware.org/?probe=876baf36d7) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [bce425f138](https://linux-hardware.org/?probe=bce425f138) | Apr 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [e37bc471b1](https://linux-hardware.org/?probe=e37bc471b1) | Apr 29, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [2b7167b16e](https://linux-hardware.org/?probe=2b7167b16e) | Apr 29, 2022 |
| HP            | 8704                        | [41d896b51d](https://linux-hardware.org/?probe=41d896b51d) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [aed5ee3ded](https://linux-hardware.org/?probe=aed5ee3ded) | Apr 28, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ab83eedd1f](https://linux-hardware.org/?probe=ab83eedd1f) | Apr 28, 2022 |
| MSI           | H55M-E23                    | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| Gigabyte      | X570 AORUS PRO              | [44e25caaa1](https://linux-hardware.org/?probe=44e25caaa1) | Apr 28, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [46430e1117](https://linux-hardware.org/?probe=46430e1117) | Apr 28, 2022 |
| Dell          | 09KPNV A00                  | [5046e0575b](https://linux-hardware.org/?probe=5046e0575b) | Apr 28, 2022 |
| Dell          | 0NW73C A00                  | [344e2b816e](https://linux-hardware.org/?probe=344e2b816e) | Apr 28, 2022 |
| Dell          | 088DT1 A01                  | [b664b8720e](https://linux-hardware.org/?probe=b664b8720e) | Apr 28, 2022 |
| ASUSTek       | P9X79 LE                    | [ad35094812](https://linux-hardware.org/?probe=ad35094812) | Apr 28, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [19e0445e6f](https://linux-hardware.org/?probe=19e0445e6f) | Apr 27, 2022 |
| Dell          | 0R1PCR A00                  | [feec38a0f5](https://linux-hardware.org/?probe=feec38a0f5) | Apr 27, 2022 |
| ASUSTek       | SABERTOOTH Z170 S           | [21663dc8b3](https://linux-hardware.org/?probe=21663dc8b3) | Apr 27, 2022 |
| Unknown       | Unknown                     | [82ad7e86b5](https://linux-hardware.org/?probe=82ad7e86b5) | Apr 27, 2022 |
| ASUSTek       | GA15DH                      | [30a22d7be3](https://linux-hardware.org/?probe=30a22d7be3) | Apr 27, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [31b5451ae1](https://linux-hardware.org/?probe=31b5451ae1) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [486215d495](https://linux-hardware.org/?probe=486215d495) | Apr 26, 2022 |
| ASUSTek       | ROG Maximus XI CODE         | [8cca49b0ee](https://linux-hardware.org/?probe=8cca49b0ee) | Apr 25, 2022 |
| System76      | Thelio thelio-r2            | [aae937be8b](https://linux-hardware.org/?probe=aae937be8b) | Apr 25, 2022 |
| ASRock        | A320M-HD                    | [f99a1a0591](https://linux-hardware.org/?probe=f99a1a0591) | Apr 25, 2022 |
| ASUSTek       | G20AJ                       | [ed023008e4](https://linux-hardware.org/?probe=ed023008e4) | Apr 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9236e9bc93](https://linux-hardware.org/?probe=9236e9bc93) | Apr 25, 2022 |
| ASUSTek       | PRIME B460M-A               | [d1d705c163](https://linux-hardware.org/?probe=d1d705c163) | Apr 25, 2022 |
| ASUSTek       | PRIME B460M-A               | [97ff7b7591](https://linux-hardware.org/?probe=97ff7b7591) | Apr 25, 2022 |
| MSI           | G31TM-P35                   | [711f26a820](https://linux-hardware.org/?probe=711f26a820) | Apr 24, 2022 |
| MSI           | G31TM-P35                   | [2c1b91769f](https://linux-hardware.org/?probe=2c1b91769f) | Apr 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [fabaa5b3ab](https://linux-hardware.org/?probe=fabaa5b3ab) | Apr 24, 2022 |
| ASUSTek       | PRIME Z270-P                | [6cc8c69a6c](https://linux-hardware.org/?probe=6cc8c69a6c) | Apr 23, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [0534d32a13](https://linux-hardware.org/?probe=0534d32a13) | Apr 23, 2022 |
| ASRock        | B450 Pro4                   | [61ab02b4e8](https://linux-hardware.org/?probe=61ab02b4e8) | Apr 23, 2022 |
| ECS           | Iris8                       | [1cff4313c1](https://linux-hardware.org/?probe=1cff4313c1) | Apr 23, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [8ae54427ca](https://linux-hardware.org/?probe=8ae54427ca) | Apr 23, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | [037284e799](https://linux-hardware.org/?probe=037284e799) | Apr 23, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [3cb8eac116](https://linux-hardware.org/?probe=3cb8eac116) | Apr 23, 2022 |
| ASUSTek       | PRIME TRX40-PRO S           | [017717599c](https://linux-hardware.org/?probe=017717599c) | Apr 22, 2022 |
| Lenovo        | 31900058 STD                | [0e3c909996](https://linux-hardware.org/?probe=0e3c909996) | Apr 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [3a052b2111](https://linux-hardware.org/?probe=3a052b2111) | Apr 21, 2022 |
| Dell          | 040DDP A01                  | [6e37f18366](https://linux-hardware.org/?probe=6e37f18366) | Apr 21, 2022 |
| Gigabyte      | Z270XP-SLI-CF               | [f1a2e57e22](https://linux-hardware.org/?probe=f1a2e57e22) | Apr 21, 2022 |
| Gigabyte      | AB350M-HD3-CF               | [dd16ab4768](https://linux-hardware.org/?probe=dd16ab4768) | Apr 21, 2022 |
| ASUSTek       | Z87-K                       | [480a64a95a](https://linux-hardware.org/?probe=480a64a95a) | Apr 21, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c568c44d81](https://linux-hardware.org/?probe=c568c44d81) | Apr 20, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [7beb17ef96](https://linux-hardware.org/?probe=7beb17ef96) | Apr 20, 2022 |
| ASUSTek       | P8H67-M LE                  | [0d5a9fcacc](https://linux-hardware.org/?probe=0d5a9fcacc) | Apr 20, 2022 |
| ASUSTek       | PRIME Z390-P                | [c9ef889715](https://linux-hardware.org/?probe=c9ef889715) | Apr 20, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [61ca629904](https://linux-hardware.org/?probe=61ca629904) | Apr 20, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [c722e417a1](https://linux-hardware.org/?probe=c722e417a1) | Apr 20, 2022 |
| ASUSTek       | PRIME A520M-E               | [0aa2639b59](https://linux-hardware.org/?probe=0aa2639b59) | Apr 20, 2022 |
| ASUSTek       | Q87M-E                      | [e409d7a8df](https://linux-hardware.org/?probe=e409d7a8df) | Apr 20, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [fd661468b9](https://linux-hardware.org/?probe=fd661468b9) | Apr 19, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [dc42beaa8d](https://linux-hardware.org/?probe=dc42beaa8d) | Apr 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [49d51ee541](https://linux-hardware.org/?probe=49d51ee541) | Apr 18, 2022 |
| MSI           | Z370-A PRO                  | [9f5287d8cb](https://linux-hardware.org/?probe=9f5287d8cb) | Apr 18, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [e269a6b9b8](https://linux-hardware.org/?probe=e269a6b9b8) | Apr 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [59bc74a946](https://linux-hardware.org/?probe=59bc74a946) | Apr 18, 2022 |
| MSI           | Z590-A PRO                  | [ebe60e3c9e](https://linux-hardware.org/?probe=ebe60e3c9e) | Apr 18, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f727388ac8](https://linux-hardware.org/?probe=f727388ac8) | Apr 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c1102c77ec](https://linux-hardware.org/?probe=c1102c77ec) | Apr 17, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [7b61fb0ba4](https://linux-hardware.org/?probe=7b61fb0ba4) | Apr 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [f7008a1e16](https://linux-hardware.org/?probe=f7008a1e16) | Apr 17, 2022 |
| Unknown       | Unknown                     | [f5deab7689](https://linux-hardware.org/?probe=f5deab7689) | Apr 17, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [49c981ee41](https://linux-hardware.org/?probe=49c981ee41) | Apr 17, 2022 |
| MSI           | Z590-A PRO                  | [52a97f186f](https://linux-hardware.org/?probe=52a97f186f) | Apr 17, 2022 |
| Gigabyte      | GA-990FX-GAMING             | [dc1e145cf3](https://linux-hardware.org/?probe=dc1e145cf3) | Apr 16, 2022 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [9a5d59c375](https://linux-hardware.org/?probe=9a5d59c375) | Apr 16, 2022 |
| ASUSTek       | Maximus VI HERO             | [923a82e975](https://linux-hardware.org/?probe=923a82e975) | Apr 16, 2022 |
| ASUSTek       | G20AJ                       | [f83ee2cc17](https://linux-hardware.org/?probe=f83ee2cc17) | Apr 16, 2022 |
| ASUSTek       | G20AJ                       | [eef3c69fcd](https://linux-hardware.org/?probe=eef3c69fcd) | Apr 16, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | [76a5225b83](https://linux-hardware.org/?probe=76a5225b83) | Apr 16, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [b0a5b307c9](https://linux-hardware.org/?probe=b0a5b307c9) | Apr 16, 2022 |
| ASUSTek       | M5A78L/USB3                 | [48deb234f0](https://linux-hardware.org/?probe=48deb234f0) | Apr 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | [37e172faec](https://linux-hardware.org/?probe=37e172faec) | Apr 14, 2022 |
| ASRock        | B550M Pro4                  | [0bd7facf9b](https://linux-hardware.org/?probe=0bd7facf9b) | Apr 14, 2022 |
| ASRock        | X570 Steel Legend           | [17622a538e](https://linux-hardware.org/?probe=17622a538e) | Apr 14, 2022 |
| NZXT          | N7 B550                     | [71e92a4807](https://linux-hardware.org/?probe=71e92a4807) | Apr 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [843c3d4758](https://linux-hardware.org/?probe=843c3d4758) | Apr 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [c372810f3f](https://linux-hardware.org/?probe=c372810f3f) | Apr 14, 2022 |
| Dell          | 0H7TGR A00                  | [70bdc97d85](https://linux-hardware.org/?probe=70bdc97d85) | Apr 14, 2022 |
| MSI           | B550-A PRO                  | [d0933b6a76](https://linux-hardware.org/?probe=d0933b6a76) | Apr 14, 2022 |
| ASUSTek       | PRIME B450M-A               | [d4295c9a47](https://linux-hardware.org/?probe=d4295c9a47) | Apr 14, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [645c74ef90](https://linux-hardware.org/?probe=645c74ef90) | Apr 13, 2022 |
| Gigabyte      | B150M-D3H-CF                | [e3a8701de2](https://linux-hardware.org/?probe=e3a8701de2) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [392f621ca6](https://linux-hardware.org/?probe=392f621ca6) | Apr 13, 2022 |
| Gigabyte      | X570 GAMING X               | [b089bb9293](https://linux-hardware.org/?probe=b089bb9293) | Apr 13, 2022 |
| System76      | Thelio Major thelio-majo... | [5924b8c844](https://linux-hardware.org/?probe=5924b8c844) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e05e4dc47b](https://linux-hardware.org/?probe=e05e4dc47b) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [ace1daa3ff](https://linux-hardware.org/?probe=ace1daa3ff) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [92e810b1dd](https://linux-hardware.org/?probe=92e810b1dd) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [c77d1618d1](https://linux-hardware.org/?probe=c77d1618d1) | Apr 13, 2022 |
| Dell          | 0JP3NX A00                  | [c76114b4b3](https://linux-hardware.org/?probe=c76114b4b3) | Apr 13, 2022 |
| MSI           | B250M PRO-VD                | [e5744a1f58](https://linux-hardware.org/?probe=e5744a1f58) | Apr 12, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [47404cf177](https://linux-hardware.org/?probe=47404cf177) | Apr 12, 2022 |
| ASUSTek       | P8H61 PRO                   | [82d8b5968f](https://linux-hardware.org/?probe=82d8b5968f) | Apr 12, 2022 |
| ASUSTek       | PRIME B450M-A               | [921b858e18](https://linux-hardware.org/?probe=921b858e18) | Apr 11, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [8c6cc15607](https://linux-hardware.org/?probe=8c6cc15607) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [3ddf8a6825](https://linux-hardware.org/?probe=3ddf8a6825) | Apr 11, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [5c247da651](https://linux-hardware.org/?probe=5c247da651) | Apr 10, 2022 |
| MSI           | B360-A PRO                  | [cb8b648eac](https://linux-hardware.org/?probe=cb8b648eac) | Apr 10, 2022 |
| eMachines     | EL1850G                     | [cfa8d1c8d5](https://linux-hardware.org/?probe=cfa8d1c8d5) | Apr 10, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [28114b7924](https://linux-hardware.org/?probe=28114b7924) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [117eded7f8](https://linux-hardware.org/?probe=117eded7f8) | Apr 10, 2022 |
| Gigabyte      | Z77-DS3H                    | [88fba1bae6](https://linux-hardware.org/?probe=88fba1bae6) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [1c57ef464e](https://linux-hardware.org/?probe=1c57ef464e) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [e641889a70](https://linux-hardware.org/?probe=e641889a70) | Apr 09, 2022 |
| NZXT          | N7 B550                     | [e3f895a70b](https://linux-hardware.org/?probe=e3f895a70b) | Apr 09, 2022 |
| ASUSTek       | P8H67-V                     | [a2ae5eb5b9](https://linux-hardware.org/?probe=a2ae5eb5b9) | Apr 09, 2022 |
| ASUSTek       | P5QPL-AM                    | [1d0d38c7c8](https://linux-hardware.org/?probe=1d0d38c7c8) | Apr 09, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [e6aa0c6166](https://linux-hardware.org/?probe=e6aa0c6166) | Apr 09, 2022 |
| MSI           | B250M BAZOOKA               | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ed6ff884fc](https://linux-hardware.org/?probe=ed6ff884fc) | Apr 08, 2022 |
| MSI           | B450M MORTAR MAX            | [bde8b0ab3c](https://linux-hardware.org/?probe=bde8b0ab3c) | Apr 07, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [dd2c447b48](https://linux-hardware.org/?probe=dd2c447b48) | Apr 07, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [d1f213c4f0](https://linux-hardware.org/?probe=d1f213c4f0) | Apr 07, 2022 |
| Gigabyte      | B450 AORUS M                | [714baddf6f](https://linux-hardware.org/?probe=714baddf6f) | Apr 06, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [f5106f79ee](https://linux-hardware.org/?probe=f5106f79ee) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [27825828c9](https://linux-hardware.org/?probe=27825828c9) | Apr 05, 2022 |
| Gigabyte      | H87M-HD3                    | [76eb57cf5e](https://linux-hardware.org/?probe=76eb57cf5e) | Apr 05, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c95df20756](https://linux-hardware.org/?probe=c95df20756) | Apr 05, 2022 |
| MSI           | B360-A PRO                  | [aa22c203eb](https://linux-hardware.org/?probe=aa22c203eb) | Apr 05, 2022 |
| ASUSTek       | Z87-K                       | [8d1d44d764](https://linux-hardware.org/?probe=8d1d44d764) | Apr 04, 2022 |
| Gigabyte      | H110M-H-CF                  | [9ca082be16](https://linux-hardware.org/?probe=9ca082be16) | Apr 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | [7a354d771f](https://linux-hardware.org/?probe=7a354d771f) | Apr 04, 2022 |
| Pegatron      | 2AC2                        | [f6d4a4c17e](https://linux-hardware.org/?probe=f6d4a4c17e) | Apr 03, 2022 |
| ASUSTek       | PRIME H510M-R               | [6736f1afa6](https://linux-hardware.org/?probe=6736f1afa6) | Apr 03, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [40077b3761](https://linux-hardware.org/?probe=40077b3761) | Apr 03, 2022 |
| Dell          | 0K240Y A03                  | [7e3ad9ce02](https://linux-hardware.org/?probe=7e3ad9ce02) | Apr 02, 2022 |
| Gigabyte      | H410M H V3                  | [48f0951752](https://linux-hardware.org/?probe=48f0951752) | Apr 02, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [62bdba9365](https://linux-hardware.org/?probe=62bdba9365) | Apr 02, 2022 |
| Intel         | DG41WV AAE90316-101         | [5d3d268c96](https://linux-hardware.org/?probe=5d3d268c96) | Apr 02, 2022 |
| Intel         | DG41WV AAE90316-101         | [3dac9f017e](https://linux-hardware.org/?probe=3dac9f017e) | Apr 02, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [4e2f534de0](https://linux-hardware.org/?probe=4e2f534de0) | Apr 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [625d6cc105](https://linux-hardware.org/?probe=625d6cc105) | Apr 01, 2022 |
| Foxconn       | 2ABF                        | [3e5267891f](https://linux-hardware.org/?probe=3e5267891f) | Apr 01, 2022 |
| ASUSTek       | Z87-K                       | [616258c6a5](https://linux-hardware.org/?probe=616258c6a5) | Apr 01, 2022 |
| MSI           | B450-A PRO MAX              | [254b38e98f](https://linux-hardware.org/?probe=254b38e98f) | Apr 01, 2022 |
| Medion        | H81H3-EM2                   | [4c887e357d](https://linux-hardware.org/?probe=4c887e357d) | Mar 31, 2022 |
| Acer          | Aspire X3400                | [47097032fd](https://linux-hardware.org/?probe=47097032fd) | Mar 31, 2022 |
| ASUSTek       | M5A97 R2.0                  | [069ce7ef8f](https://linux-hardware.org/?probe=069ce7ef8f) | Mar 31, 2022 |
| Gigabyte      | H77N-WIFI                   | [a8c1be0abd](https://linux-hardware.org/?probe=a8c1be0abd) | Mar 31, 2022 |
| MSI           | H410M PRO-VH                | [e4ef535529](https://linux-hardware.org/?probe=e4ef535529) | Mar 31, 2022 |
| ECS           | A55F-M4                     | [0d29bdddde](https://linux-hardware.org/?probe=0d29bdddde) | Mar 31, 2022 |
| ASUSTek       | M5A78L/USB3                 | [92eae45686](https://linux-hardware.org/?probe=92eae45686) | Mar 30, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d5b2536b95](https://linux-hardware.org/?probe=d5b2536b95) | Mar 30, 2022 |
| ASUSTek       | P8H67-M LX                  | [a30f5893f6](https://linux-hardware.org/?probe=a30f5893f6) | Mar 30, 2022 |
| ASUSTek       | PRIME X570-P                | [eeef359646](https://linux-hardware.org/?probe=eeef359646) | Mar 30, 2022 |
| System76      | Thelio thelio-r2            | [426cd0671d](https://linux-hardware.org/?probe=426cd0671d) | Mar 29, 2022 |
| Gigabyte      | EX58-UD4P                   | [b3a7b518b6](https://linux-hardware.org/?probe=b3a7b518b6) | Mar 29, 2022 |
| Intel         | DQ77MK AAG39642-400         | [29e7a23412](https://linux-hardware.org/?probe=29e7a23412) | Mar 28, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [6335525127](https://linux-hardware.org/?probe=6335525127) | Mar 28, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [6f66a7137f](https://linux-hardware.org/?probe=6f66a7137f) | Mar 28, 2022 |
| MSI           | P67A-C43                    | [fb5d1f7bc1](https://linux-hardware.org/?probe=fb5d1f7bc1) | Mar 28, 2022 |
| Dell          | 0200DY A03                  | [acb42fe25a](https://linux-hardware.org/?probe=acb42fe25a) | Mar 28, 2022 |
| Dell          | 0200DY A03                  | [d39c4f7d2b](https://linux-hardware.org/?probe=d39c4f7d2b) | Mar 28, 2022 |
| MSI           | P67A-C43                    | [dac91a1c12](https://linux-hardware.org/?probe=dac91a1c12) | Mar 28, 2022 |
| Dell          | 0D6H9T A00                  | [48ab5aae1e](https://linux-hardware.org/?probe=48ab5aae1e) | Mar 27, 2022 |
| MSI           | Z170A PC MATE               | [546a66dcf1](https://linux-hardware.org/?probe=546a66dcf1) | Mar 27, 2022 |
| Gigabyte      | B450M S2H                   | [aa02b40ff7](https://linux-hardware.org/?probe=aa02b40ff7) | Mar 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [756231c2f0](https://linux-hardware.org/?probe=756231c2f0) | Mar 27, 2022 |
| MSI           | B450M PRO-M2                | [e269e3b44e](https://linux-hardware.org/?probe=e269e3b44e) | Mar 27, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Pop!_OS 20.04 | 857      | 25.99%  |
| Pop!_OS 21.04 | 718      | 21.78%  |
| Pop!_OS 20.10 | 671      | 20.35%  |
| Pop!_OS 22.04 | 605      | 18.35%  |
| Pop!_OS 21.10 | 420      | 12.74%  |
| Pop!_OS 19.10 | 15       | 0.45%   |
| Pop!_OS 19.04 | 6        | 0.18%   |
| Pop!_OS 18.04 | 4        | 0.12%   |
| Pop!_OS 18.10 | 1        | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Pop!_OS | 3095     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.11.0-7620-generic      | 340      | 9.57%   |
| 5.8.0-7630-generic       | 315      | 8.87%   |
| 5.4.0-7634-generic       | 281      | 7.91%   |
| 5.8.0-7642-generic       | 203      | 5.72%   |
| 5.13.0-7614-generic      | 203      | 5.72%   |
| 5.4.0-7642-generic       | 187      | 5.26%   |
| 5.11.0-7614-generic      | 180      | 5.07%   |
| 5.17.5-76051705-generic  | 175      | 4.93%   |
| 5.13.0-7620-generic      | 171      | 4.81%   |
| 5.19.0-76051900-generic  | 141      | 3.97%   |
| 5.16.11-76051611-generic | 111      | 3.13%   |
| 5.15.15-76051515-generic | 109      | 3.07%   |
| 6.0.6-76060006-generic   | 96       | 2.7%    |
| 5.15.5-76051505-generic  | 92       | 2.59%   |
| 5.11.0-7612-generic      | 87       | 2.45%   |
| 5.8.0-7625-generic       | 77       | 2.17%   |
| 5.18.10-76051810-generic | 73       | 2.06%   |
| 5.11.0-7633-generic      | 71       | 2%      |
| 5.17.15-76051715-generic | 68       | 1.91%   |
| 5.16.19-76051619-generic | 65       | 1.83%   |
| 5.15.8-76051508-generic  | 63       | 1.77%   |
| 5.16.15-76051615-generic | 56       | 1.58%   |
| 5.15.11-76051511-generic | 47       | 1.32%   |
| 5.4.0-7626-generic       | 43       | 1.21%   |
| 5.15.23-76051523-generic | 29       | 0.82%   |
| 6.0.2-76060002-generic   | 24       | 0.68%   |
| 5.4.0-7625-generic       | 24       | 0.68%   |
| 6.0.12-76060006-generic  | 22       | 0.62%   |
| 5.4.0-7629-generic       | 21       | 0.59%   |
| 5.19.16-76051916-generic | 18       | 0.51%   |
| 6.0.3-76060003-generic   | 13       | 0.37%   |
| 5.3.0-7629-generic       | 5        | 0.14%   |
| 5.3.0-7625-generic       | 5        | 0.14%   |
| 5.8.5-xanmod1            | 4        | 0.11%   |
| 5.8.5-050805-generic     | 4        | 0.11%   |
| 5.8.12-xanmod1           | 4        | 0.11%   |
| 5.7.8-050708-generic     | 3        | 0.08%   |
| 5.4.0-7624-generic       | 3        | 0.08%   |
| 5.3.0-7648-generic       | 3        | 0.08%   |
| 5.3.0-22-generic         | 3        | 0.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 650      | 18.78%  |
| 5.8.0   | 567      | 16.38%  |
| 5.4.0   | 537      | 15.51%  |
| 5.13.0  | 371      | 10.72%  |
| 5.17.5  | 175      | 5.05%   |
| 5.19.0  | 141      | 4.07%   |
| 5.16.11 | 111      | 3.21%   |
| 5.15.15 | 110      | 3.18%   |
| 6.0.6   | 97       | 2.8%    |
| 5.15.5  | 92       | 2.66%   |
| 5.18.10 | 73       | 2.11%   |
| 5.17.15 | 68       | 1.96%   |
| 5.16.19 | 65       | 1.88%   |
| 5.15.8  | 63       | 1.82%   |
| 5.16.15 | 56       | 1.62%   |
| 5.15.11 | 47       | 1.36%   |
| 5.15.23 | 29       | 0.84%   |
| 6.0.2   | 25       | 0.72%   |
| 6.0.12  | 23       | 0.66%   |
| 5.19.16 | 18       | 0.52%   |
| 5.3.0   | 17       | 0.49%   |
| 6.0.3   | 13       | 0.38%   |
| 5.8.5   | 8        | 0.23%   |
| 5.0.0   | 6        | 0.17%   |
| 5.8.12  | 5        | 0.14%   |
| 6.1.0   | 3        | 0.09%   |
| 5.7.8   | 3        | 0.09%   |
| 5.7.0   | 3        | 0.09%   |
| 5.6.16  | 3        | 0.09%   |
| 5.15.0  | 3        | 0.09%   |
| 5.9.1   | 2        | 0.06%   |
| 5.8.6   | 2        | 0.06%   |
| 5.8.18  | 2        | 0.06%   |
| 5.7.16  | 2        | 0.06%   |
| 5.7.12  | 2        | 0.06%   |
| 5.16.0  | 2        | 0.06%   |
| 5.15.7  | 2        | 0.06%   |
| 5.15.22 | 2        | 0.06%   |
| 5.13.12 | 2        | 0.06%   |
| 5.10.23 | 2        | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 652      | 19.03%  |
| 5.8     | 589      | 17.19%  |
| 5.4     | 539      | 15.73%  |
| 5.13    | 376      | 10.97%  |
| 5.15    | 343      | 10.01%  |
| 5.17    | 241      | 7.03%   |
| 5.16    | 223      | 6.51%   |
| 5.19    | 159      | 4.64%   |
| 6.0     | 157      | 4.58%   |
| 5.18    | 75       | 2.19%   |
| 5.3     | 17       | 0.5%    |
| 5.7     | 14       | 0.41%   |
| 5.6     | 8        | 0.23%   |
| 5.10    | 8        | 0.23%   |
| 5.0     | 6        | 0.18%   |
| 5.9     | 5        | 0.15%   |
| 5.14    | 5        | 0.15%   |
| 5.12    | 4        | 0.12%   |
| 6.1     | 3        | 0.09%   |
| 4.18    | 1        | 0.03%   |
| 4.15    | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 3095     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 2989     | 96.02%  |
| KDE             | 33       | 1.06%   |
| KDE5            | 28       | 0.9%    |
| X-Cinnamon      | 16       | 0.51%   |
| Unknown         | 14       | 0.45%   |
| MATE            | 9        | 0.29%   |
| XFCE            | 7        | 0.22%   |
| Cinnamon        | 5        | 0.16%   |
| GNOME Flashback | 4        | 0.13%   |
| LXQt            | 2        | 0.06%   |
| i3              | 2        | 0.06%   |
| Budgie          | 2        | 0.06%   |
| Unity           | 1        | 0.03%   |
| Pantheon        | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 3047     | 98.13%  |
| Wayland | 47       | 1.51%   |
| Tty     | 6        | 0.19%   |
| Unknown | 5        | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2667     | 85.56%  |
| GDM     | 342      | 10.97%  |
| GDM3    | 96       | 3.08%   |
| SDDM    | 7        | 0.22%   |
| TDM     | 3        | 0.1%    |
| LightDM | 2        | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1744     | 55.95%  |
| en_GB   | 243      | 7.8%    |
| pt_BR   | 232      | 7.44%   |
| de_DE   | 159      | 5.1%    |
| C       | 110      | 3.53%   |
| en_AU   | 97       | 3.11%   |
| en_CA   | 91       | 2.92%   |
| fr_FR   | 62       | 1.99%   |
| it_IT   | 40       | 1.28%   |
| ru_RU   | 38       | 1.22%   |
| es_ES   | 37       | 1.19%   |
| pl_PL   | 30       | 0.96%   |
| nl_NL   | 27       | 0.87%   |
| sv_SE   | 21       | 0.67%   |
| Unknown | 18       | 0.58%   |
| fi_FI   | 13       | 0.42%   |
| pt_PT   | 12       | 0.38%   |
| fr_CA   | 8        | 0.26%   |
| es_AR   | 8        | 0.26%   |
| zh_TW   | 7        | 0.22%   |
| es_CL   | 7        | 0.22%   |
| en_DK   | 7        | 0.22%   |
| nl_BE   | 6        | 0.19%   |
| en_ZA   | 6        | 0.19%   |
| en_NZ   | 6        | 0.19%   |
| en_IN   | 6        | 0.19%   |
| da_DK   | 6        | 0.19%   |
| sk_SK   | 5        | 0.16%   |
| ja_JP   | 5        | 0.16%   |
| es_MX   | 5        | 0.16%   |
| cs_CZ   | 5        | 0.16%   |
| tr_TR   | 4        | 0.13%   |
| hu_HU   | 4        | 0.13%   |
| hr_HR   | 4        | 0.13%   |
| fr_CH   | 4        | 0.13%   |
| zh_CN   | 3        | 0.1%    |
| uk_UA   | 3        | 0.1%    |
| nb_NO   | 3        | 0.1%    |
| en_IL   | 3        | 0.1%    |
| ro_RO   | 2        | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2523     | 80.58%  |
| EFI  | 608      | 19.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 2979     | 95.94%  |
| Overlay | 58       | 1.87%   |
| Btrfs   | 52       | 1.67%   |
| Xfs     | 7        | 0.23%   |
| Unknown | 5        | 0.16%   |
| Zfs     | 4        | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2658     | 85.33%  |
| GPT     | 390      | 12.52%  |
| MBR     | 67       | 2.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3009     | 96.75%  |
| Yes       | 101      | 3.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2841     | 91.29%  |
| Yes       | 271      | 8.71%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 874      | 28.24%  |
| Gigabyte Technology | 606      | 19.58%  |
| MSI                 | 464      | 14.99%  |
| ASRock              | 318      | 10.27%  |
| Dell                | 238      | 7.69%   |
| Hewlett-Packard     | 156      | 5.04%   |
| Lenovo              | 76       | 2.46%   |
| Intel               | 57       | 1.84%   |
| System76            | 30       | 0.97%   |
| Acer                | 26       | 0.84%   |
| Pegatron            | 24       | 0.78%   |
| Unknown             | 20       | 0.65%   |
| Foxconn             | 16       | 0.52%   |
| Biostar             | 16       | 0.52%   |
| Alienware           | 16       | 0.52%   |
| ECS                 | 15       | 0.48%   |
| Fujitsu             | 13       | 0.42%   |
| Apple               | 11       | 0.36%   |
| Medion              | 10       | 0.32%   |
| Supermicro          | 9        | 0.29%   |
| Positivo            | 9        | 0.29%   |
| Huanan              | 9        | 0.29%   |
| PCWare              | 8        | 0.26%   |
| Gateway             | 6        | 0.19%   |
| Minix               | 5        | 0.16%   |
| EVGA                | 5        | 0.16%   |
| BESSTAR Tech        | 5        | 0.16%   |
| OEM                 | 3        | 0.1%    |
| MACHINIST           | 3        | 0.1%    |
| TYAN Computer       | 2        | 0.06%   |
| T-bao               | 2        | 0.06%   |
| Shuttle             | 2        | 0.06%   |
| NZXT                | 2        | 0.06%   |
| Megaware            | 2        | 0.06%   |
| MAXSUN              | 2        | 0.06%   |
| Login Informatica   | 2        | 0.06%   |
| Google              | 2        | 0.06%   |
| Fujitsu Siemens     | 2        | 0.06%   |
| eMachines           | 2        | 0.06%   |
| Colorful Technology | 2        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 81       | 2.62%   |
| ASUS TUF Gaming X570-PLUS      | 36       | 1.16%   |
| Gigabyte B450M DS3H            | 33       | 1.07%   |
| MSI MS-7C02                    | 29       | 0.94%   |
| MSI MS-7C37                    | 26       | 0.84%   |
| MSI MS-7B86                    | 25       | 0.81%   |
| ASUS ROG STRIX B450-F GAMING   | 25       | 0.81%   |
| ASUS ROG STRIX B550-F GAMING   | 22       | 0.71%   |
| ASUS PRIME B450M-A             | 21       | 0.68%   |
| Unknown                        | 21       | 0.68%   |
| System76 Thelio                | 20       | 0.65%   |
| Dell OptiPlex 9020             | 20       | 0.65%   |
| Gigabyte X570 AORUS ELITE      | 18       | 0.58%   |
| ASRock B450M Pro4              | 16       | 0.52%   |
| Dell OptiPlex 7010             | 15       | 0.48%   |
| ASRock B450M Steel Legend      | 15       | 0.48%   |
| Gigabyte B450 I AORUS PRO WIFI | 13       | 0.42%   |
| Gigabyte A320M-S2H             | 13       | 0.42%   |
| MSI MS-7C91                    | 12       | 0.39%   |
| Gigabyte X570 AORUS MASTER     | 12       | 0.39%   |
| Gigabyte B450 AORUS M          | 12       | 0.39%   |
| ASUS PRIME B450M-GAMING/BR     | 12       | 0.39%   |
| MSI MS-7B89                    | 11       | 0.36%   |
| MSI MS-7B79                    | 11       | 0.36%   |
| Gigabyte B75M-D3H              | 11       | 0.36%   |
| Dell OptiPlex 3010             | 11       | 0.36%   |
| ASUS TUF Gaming X570-PRO       | 11       | 0.36%   |
| ASUS TUF Gaming B550-PLUS      | 11       | 0.36%   |
| MSI MS-7C84                    | 10       | 0.32%   |
| Gigabyte B450 AORUS PRO WIFI   | 10       | 0.32%   |
| Dell OptiPlex 790              | 10       | 0.32%   |
| ASUS ROG STRIX B550-I GAMING   | 10       | 0.32%   |
| ASUS ROG STRIX B350-F GAMING   | 10       | 0.32%   |
| System76 Thelio Major          | 9        | 0.29%   |
| MSI MS-7B85                    | 9        | 0.29%   |
| MSI MS-7A34                    | 9        | 0.29%   |
| MSI MS-7817                    | 9        | 0.29%   |
| MSI MS-7693                    | 9        | 0.29%   |
| HP Compaq 8200 Elite SFF PC    | 9        | 0.29%   |
| Dell OptiPlex 3020             | 9        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 192      | 6.2%    |
| ASUS PRIME             | 166      | 5.36%   |
| Dell OptiPlex          | 131      | 4.23%   |
| ASUS TUF               | 109      | 3.52%   |
| ASUS All               | 81       | 2.62%   |
| Gigabyte X570          | 66       | 2.13%   |
| HP Compaq              | 51       | 1.65%   |
| Gigabyte B450          | 47       | 1.52%   |
| Gigabyte B450M         | 45       | 1.45%   |
| Lenovo ThinkCentre     | 44       | 1.42%   |
| Dell Precision         | 41       | 1.32%   |
| ASRock B450M           | 37       | 1.2%    |
| ASRock X570            | 32       | 1.03%   |
| System76 Thelio        | 30       | 0.97%   |
| MSI MS-7C02            | 29       | 0.94%   |
| Gigabyte B550          | 27       | 0.87%   |
| MSI MS-7C37            | 26       | 0.84%   |
| Dell Inspiron          | 26       | 0.84%   |
| MSI MS-7B86            | 25       | 0.81%   |
| ASRock B450            | 21       | 0.68%   |
| Unknown                | 21       | 0.68%   |
| ASUS SABERTOOTH        | 20       | 0.65%   |
| Dell XPS               | 18       | 0.58%   |
| HP EliteDesk           | 17       | 0.55%   |
| Gigabyte Z390          | 16       | 0.52%   |
| Gigabyte GA-78LMT-USB3 | 16       | 0.52%   |
| Gigabyte A320M-S2H     | 16       | 0.52%   |
| Acer Aspire            | 16       | 0.52%   |
| ASUS P8Z77-V           | 15       | 0.48%   |
| ASUS M5A97             | 14       | 0.45%   |
| ASUS M5A78L-M          | 14       | 0.45%   |
| MSI MS-7C91            | 12       | 0.39%   |
| HP ProDesk             | 12       | 0.39%   |
| ASUS Maximus           | 12       | 0.39%   |
| ASUS CROSSHAIR         | 12       | 0.39%   |
| MSI MS-7B89            | 11       | 0.36%   |
| MSI MS-7B79            | 11       | 0.36%   |
| Lenovo IdeaCentre      | 11       | 0.36%   |
| Gigabyte X470          | 11       | 0.36%   |
| Gigabyte B75M-D3H      | 11       | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 505      | 16.32%  |
| 2019 | 382      | 12.34%  |
| 2020 | 349      | 11.28%  |
| 2012 | 258      | 8.34%   |
| 2017 | 234      | 7.56%   |
| 2013 | 217      | 7.01%   |
| 2011 | 189      | 6.11%   |
| 2014 | 183      | 5.91%   |
| 2021 | 139      | 4.49%   |
| 2015 | 129      | 4.17%   |
| 2016 | 127      | 4.1%    |
| 2010 | 121      | 3.91%   |
| 2009 | 106      | 3.42%   |
| 2008 | 62       | 2%      |
| 2007 | 51       | 1.65%   |
| 2022 | 31       | 1%      |
| 2006 | 12       | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3095     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3093     | 99.94%  |
| Enabled  | 2        | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3093     | 99.94%  |
| Yes  | 2        | 0.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1034     | 32.75%  |
| 32.01-64.0      | 646      | 20.46%  |
| 8.01-16.0       | 587      | 18.59%  |
| 4.01-8.0        | 305      | 9.66%   |
| 3.01-4.0        | 247      | 7.82%   |
| 64.01-256.0     | 192      | 6.08%   |
| 24.01-32.0      | 97       | 3.07%   |
| 1.01-2.0        | 29       | 0.92%   |
| 2.01-3.0        | 11       | 0.35%   |
| More than 256.0 | 8        | 0.25%   |
| 0.51-1.0        | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 963      | 28.32%  |
| 1.01-2.0    | 906      | 26.64%  |
| 4.01-8.0    | 699      | 20.55%  |
| 3.01-4.0    | 614      | 18.05%  |
| 8.01-16.0   | 157      | 4.62%   |
| 16.01-24.0  | 29       | 0.85%   |
| 32.01-64.0  | 12       | 0.35%   |
| 24.01-32.0  | 11       | 0.32%   |
| 0.51-1.0    | 7        | 0.21%   |
| 64.01-256.0 | 3        | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1044     | 32.66%  |
| 2      | 955      | 29.87%  |
| 3      | 580      | 18.14%  |
| 4      | 337      | 10.54%  |
| 5      | 143      | 4.47%   |
| 6      | 64       | 2%      |
| 7      | 25       | 0.78%   |
| 0      | 18       | 0.56%   |
| 8      | 8        | 0.25%   |
| 11     | 7        | 0.22%   |
| 9      | 7        | 0.22%   |
| 10     | 3        | 0.09%   |
| 23     | 1        | 0.03%   |
| 20     | 1        | 0.03%   |
| 19     | 1        | 0.03%   |
| 14     | 1        | 0.03%   |
| 13     | 1        | 0.03%   |
| 12     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2087     | 66.83%  |
| Yes       | 1036     | 33.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3056     | 98.71%  |
| No        | 40       | 1.29%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1641     | 52.43%  |
| No        | 1489     | 47.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1905     | 60.8%   |
| Yes       | 1228     | 39.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1062     | 34.14%  |
| Brazil       | 288      | 9.26%   |
| Germany      | 217      | 6.98%   |
| UK           | 173      | 5.56%   |
| Canada       | 170      | 5.46%   |
| Australia    | 114      | 3.66%   |
| Netherlands  | 76       | 2.44%   |
| Italy        | 70       | 2.25%   |
| France       | 66       | 2.12%   |
| Sweden       | 58       | 1.86%   |
| Poland       | 52       | 1.67%   |
| Russia       | 44       | 1.41%   |
| South Africa | 37       | 1.19%   |
| Spain        | 36       | 1.16%   |
| India        | 34       | 1.09%   |
| Finland      | 33       | 1.06%   |
| Switzerland  | 29       | 0.93%   |
| Romania      | 27       | 0.87%   |
| Norway       | 25       | 0.8%    |
| New Zealand  | 24       | 0.77%   |
| Austria      | 24       | 0.77%   |
| Portugal     | 23       | 0.74%   |
| Mexico       | 23       | 0.74%   |
| Greece       | 22       | 0.71%   |
| Denmark      | 21       | 0.68%   |
| Argentina    | 21       | 0.68%   |
| Philippines  | 20       | 0.64%   |
| Belgium      | 20       | 0.64%   |
| Czechia      | 16       | 0.51%   |
| Chile        | 14       | 0.45%   |
| Bulgaria     | 14       | 0.45%   |
| Ireland      | 13       | 0.42%   |
| Japan        | 12       | 0.39%   |
| Hungary      | 12       | 0.39%   |
| Ukraine      | 11       | 0.35%   |
| Serbia       | 11       | 0.35%   |
| Slovakia     | 10       | 0.32%   |
| Lithuania    | 10       | 0.32%   |
| Israel       | 10       | 0.32%   |
| Turkey       | 9        | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sao Paulo      | 38       | 1.18%   |
| Sydney         | 32       | 1%      |
| Berlin         | 25       | 0.78%   |
| Melbourne      | 22       | 0.68%   |
| Miami          | 19       | 0.59%   |
| Brisbane       | 19       | 0.59%   |
| Rio de Janeiro | 18       | 0.56%   |
| Helsinki       | 16       | 0.5%    |
| Vienna         | 15       | 0.47%   |
| Browning       | 15       | 0.47%   |
| Warsaw         | 14       | 0.44%   |
| Seattle        | 13       | 0.4%    |
| Milan          | 13       | 0.4%    |
| Denver         | 13       | 0.4%    |
| Chicago        | 13       | 0.4%    |
| Phoenix        | 12       | 0.37%   |
| Perth          | 12       | 0.37%   |
| London         | 12       | 0.37%   |
| Auckland       | 12       | 0.37%   |
| Amsterdam      | 12       | 0.37%   |
| Moscow         | 11       | 0.34%   |
| Dallas         | 11       | 0.34%   |
| Calgary        | 11       | 0.34%   |
| Athens         | 11       | 0.34%   |
| Adelaide       | 11       | 0.34%   |
| Toronto        | 10       | 0.31%   |
| Montreal       | 10       | 0.31%   |
| Edmonton       | 10       | 0.31%   |
| Cape Town      | 10       | 0.31%   |
| Washington     | 9        | 0.28%   |
| St Louis       | 9        | 0.28%   |
| Sofia          | 9        | 0.28%   |
| Paris          | 9        | 0.28%   |
| Johannesburg   | 9        | 0.28%   |
| Atlanta        | 9        | 0.28%   |
| Rome           | 8        | 0.25%   |
| New York       | 8        | 0.25%   |
| Madrid         | 8        | 0.25%   |
| Lisbon         | 8        | 0.25%   |
| Las Vegas      | 8        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 1083     | 1702   | 17.87%  |
| Samsung Electronics       | 1049     | 1788   | 17.3%   |
| WDC                       | 1041     | 1581   | 17.17%  |
| Kingston                  | 375      | 495    | 6.19%   |
| SanDisk                   | 366      | 487    | 6.04%   |
| Crucial                   | 279      | 392    | 4.6%    |
| Toshiba                   | 265      | 335    | 4.37%   |
| Hitachi                   | 152      | 197    | 2.51%   |
| Phison                    | 147      | 220    | 2.42%   |
| Intel                     | 129      | 178    | 2.13%   |
| A-DATA Technology         | 92       | 119    | 1.52%   |
| PNY                       | 71       | 94     | 1.17%   |
| Silicon Motion            | 69       | 98     | 1.14%   |
| Micron/Crucial Technology | 67       | 86     | 1.11%   |
| China                     | 65       | 95     | 1.07%   |
| Unknown                   | 53       | 82     | 0.87%   |
| HGST                      | 43       | 59     | 0.71%   |
| OCZ                       | 42       | 57     | 0.69%   |
| SK hynix                  | 39       | 53     | 0.64%   |
| XPG                       | 36       | 49     | 0.59%   |
| Micron Technology         | 31       | 46     | 0.51%   |
| SPCC                      | 30       | 40     | 0.49%   |
| Maxtor                    | 30       | 31     | 0.49%   |
| Corsair                   | 30       | 41     | 0.49%   |
| Patriot                   | 28       | 41     | 0.46%   |
| Realtek Semiconductor     | 26       | 31     | 0.43%   |
| Team                      | 22       | 26     | 0.36%   |
| Phison Electronics        | 21       | 30     | 0.35%   |
| Intenso                   | 18       | 20     | 0.3%    |
| Lexar                     | 15       | 16     | 0.25%   |
| Hewlett-Packard           | 14       | 19     | 0.23%   |
| JMicron Technology        | 12       | 22     | 0.2%    |
| Goodram                   | 12       | 13     | 0.2%    |
| KingSpec                  | 11       | 14     | 0.18%   |
| Gigabyte Technology       | 11       | 11     | 0.18%   |
| Transcend                 | 10       | 12     | 0.16%   |
| T-FORCE                   | 9        | 11     | 0.15%   |
| SABRENT                   | 9        | 9      | 0.15%   |
| Apacer                    | 9        | 12     | 0.15%   |
| Mushkin                   | 8        | 10     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB        | 131      | 1.85%   |
| Samsung NVMe SSD Drive 500GB      | 117      | 1.65%   |
| Kingston SA400S37240G 240GB SSD   | 99       | 1.4%    |
| Seagate ST2000DM008-2FR102 2TB    | 93       | 1.32%   |
| Seagate ST1000DM010-2EP102 1TB    | 88       | 1.24%   |
| Samsung SSD 850 EVO 250GB         | 79       | 1.12%   |
| Seagate ST500DM002-1BD142 500GB   | 73       | 1.03%   |
| Samsung SSD 850 EVO 500GB         | 72       | 1.02%   |
| Samsung SSD 860 EVO 500GB         | 69       | 0.98%   |
| SanDisk NVMe SSD Drive 500GB      | 65       | 0.92%   |
| Samsung SSD 860 EVO 1TB           | 65       | 0.92%   |
| WDC WD10EZEX-08WN4A0 1TB          | 64       | 0.9%    |
| SanDisk NVMe SSD Drive 1TB        | 63       | 0.89%   |
| Kingston SA400S37120G 120GB SSD   | 57       | 0.81%   |
| Samsung NVMe SSD Drive 250GB      | 47       | 0.66%   |
| Kingston SA400S37480G 480GB SSD   | 47       | 0.66%   |
| Crucial CT1000MX500SSD1 1TB       | 46       | 0.65%   |
| Seagate ST1000DM003-1CH162 1TB    | 45       | 0.64%   |
| Phison NVMe SSD Drive 1TB         | 43       | 0.61%   |
| Toshiba DT01ACA100 1TB            | 40       | 0.57%   |
| Seagate ST4000DM004-2CV104 4TB    | 40       | 0.57%   |
| Kingston SV300S37A120G 120GB SSD  | 38       | 0.54%   |
| Crucial CT500MX500SSD1 500GB      | 38       | 0.54%   |
| Micron/Crucial NVMe SSD Drive 1TB | 37       | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB    | 35       | 0.49%   |
| Samsung SSD 860 EVO 250GB         | 33       | 0.47%   |
| Crucial CT240BX500SSD1 240GB      | 31       | 0.44%   |
| Samsung NVMe SSD Drive 2TB        | 29       | 0.41%   |
| Seagate ST2000DM006-2DM164 2TB    | 28       | 0.4%    |
| Samsung SSD 840 EVO 250GB         | 28       | 0.4%    |
| WDC WD10EZEX-00BN5A0 1TB          | 27       | 0.38%   |
| Toshiba HDWD110 1TB               | 27       | 0.38%   |
| Seagate ST2000DM001-1CH164 2TB    | 27       | 0.38%   |
| Samsung SSD 970 EVO Plus 1TB      | 27       | 0.38%   |
| Samsung SSD 860 QVO 1TB           | 27       | 0.38%   |
| Phison NVMe SSD Drive 2TB         | 27       | 0.38%   |
| Toshiba DT01ACA200 2TB            | 26       | 0.37%   |
| Seagate ST3500418AS 500GB         | 26       | 0.37%   |
| Seagate ST2000DM001-1ER164 2TB    | 25       | 0.35%   |
| Intel NVMe SSD Drive 1024GB       | 25       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1053     | 1620   | 40.88%  |
| WDC                 | 903      | 1338   | 35.05%  |
| Toshiba             | 236      | 297    | 9.16%   |
| Hitachi             | 152      | 197    | 5.9%    |
| Samsung Electronics | 103      | 125    | 4%      |
| HGST                | 43       | 59     | 1.67%   |
| Maxtor              | 26       | 27     | 1.01%   |
| Unknown             | 18       | 26     | 0.7%    |
| ASMT                | 7        | 8      | 0.27%   |
| Apple               | 7        | 9      | 0.27%   |
| Fujitsu             | 4        | 5      | 0.16%   |
| USB                 | 3        | 4      | 0.12%   |
| JMicron Technology  | 3        | 8      | 0.12%   |
| Hewlett-Packard     | 3        | 5      | 0.12%   |
| ExcelStor           | 3        | 3      | 0.12%   |
| Magnetic Data       | 2        | 2      | 0.08%   |
| SABRENT             | 1        | 1      | 0.04%   |
| RSH-339             | 1        | 1      | 0.04%   |
| Quantum             | 1        | 1      | 0.04%   |
| OEM                 | 1        | 1      | 0.04%   |
| MARVELL             | 1        | 2      | 0.04%   |
| LaCie               | 1        | 1      | 0.04%   |
| HGST HTS            | 1        | 1      | 0.04%   |
| H/W                 | 1        | 1      | 0.04%   |
| Glyph               | 1        | 2      | 0.04%   |
| ASMT109x            | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 596      | 935    | 26.69%  |
| Kingston            | 320      | 419    | 14.33%  |
| Crucial             | 261      | 364    | 11.69%  |
| SanDisk             | 197      | 257    | 8.82%   |
| WDC                 | 162      | 209    | 7.25%   |
| A-DATA Technology   | 81       | 106    | 3.63%   |
| PNY                 | 70       | 93     | 3.13%   |
| China               | 64       | 94     | 2.87%   |
| Intel               | 56       | 71     | 2.51%   |
| OCZ                 | 41       | 53     | 1.84%   |
| Patriot             | 28       | 41     | 1.25%   |
| SPCC                | 27       | 32     | 1.21%   |
| SK hynix            | 23       | 34     | 1.03%   |
| Corsair             | 23       | 29     | 1.03%   |
| Team                | 21       | 25     | 0.94%   |
| Micron Technology   | 19       | 23     | 0.85%   |
| Toshiba             | 17       | 18     | 0.76%   |
| Seagate             | 16       | 29     | 0.72%   |
| Lexar               | 14       | 15     | 0.63%   |
| KingSpec            | 11       | 14     | 0.49%   |
| Intenso             | 11       | 13     | 0.49%   |
| Transcend           | 10       | 12     | 0.45%   |
| Hewlett-Packard     | 10       | 13     | 0.45%   |
| GOODRAM             | 10       | 11     | 0.45%   |
| Apacer              | 9        | 12     | 0.4%    |
| Gigabyte Technology | 8        | 8      | 0.36%   |
| Plextor             | 7        | 9      | 0.31%   |
| LITEONIT            | 7        | 7      | 0.31%   |
| TO Exter            | 6        | 9      | 0.27%   |
| Netac               | 6        | 6      | 0.27%   |
| Mushkin             | 6        | 8      | 0.27%   |
| LITEON              | 5        | 9      | 0.22%   |
| KingDian            | 5        | 6      | 0.22%   |
| Maxtor              | 4        | 4      | 0.18%   |
| JMicron Technology  | 4        | 4      | 0.18%   |
| PNY USB             | 3        | 10     | 0.13%   |
| OWC                 | 3        | 12     | 0.13%   |
| Dogfish             | 3        | 3      | 0.13%   |
| XPG                 | 2        | 3      | 0.09%   |
| Verbatim            | 2        | 3      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2011     | 3745   | 39.41%  |
| SSD     | 1809     | 3105   | 35.45%  |
| NVMe    | 1148     | 1898   | 22.5%   |
| Unknown | 120      | 178    | 2.35%   |
| MMC     | 15       | 19     | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2744     | 6655   | 66.2%   |
| NVMe | 1144     | 1883   | 27.6%   |
| SAS  | 242      | 388    | 5.84%   |
| MMC  | 15       | 19     | 0.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2032     | 3495   | 48.44%  |
| 0.51-1.0   | 1192     | 1844   | 28.41%  |
| 1.01-2.0   | 515      | 751    | 12.28%  |
| 3.01-4.0   | 198      | 323    | 4.72%   |
| 2.01-3.0   | 129      | 187    | 3.08%   |
| 4.01-10.0  | 114      | 210    | 2.72%   |
| 10.01-20.0 | 15       | 40     | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 756      | 23.27%  |
| 251-500        | 655      | 20.16%  |
| 501-1000       | 628      | 19.33%  |
| 1001-2000      | 441      | 13.57%  |
| More than 3000 | 324      | 9.97%   |
| 2001-3000      | 184      | 5.66%   |
| 51-100         | 109      | 3.35%   |
| 1-20           | 77       | 2.37%   |
| 21-50          | 54       | 1.66%   |
| Unknown        | 21       | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1101     | 32.55%  |
| 21-50          | 567      | 16.76%  |
| 101-250        | 407      | 12.03%  |
| 51-100         | 353      | 10.43%  |
| 251-500        | 316      | 9.34%   |
| 501-1000       | 244      | 7.21%   |
| 1001-2000      | 188      | 5.56%   |
| More than 3000 | 119      | 3.52%   |
| 2001-3000      | 67       | 1.98%   |
| Unknown        | 21       | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 4        | 4      | 2.99%   |
| Seagate ST500DM002-1BD142 500GB    | 3        | 3      | 2.24%   |
| Seagate ST1500DL003-9VT16L 1TB     | 3        | 3      | 2.24%   |
| Seagate ST1000DM003-9YN162 1TB     | 3        | 3      | 2.24%   |
| Samsung Electronics HD502HI 500GB  | 3        | 3      | 2.24%   |
| Kingston SV300S37A120G 120GB SSD   | 3        | 5      | 2.24%   |
| WDC WD3200AAKS-75B3A0 320GB        | 2        | 2      | 1.49%   |
| WDC WD10EZEX-60WN4A0 1TB           | 2        | 2      | 1.49%   |
| Toshiba HDWD110 1TB                | 2        | 2      | 1.49%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 2      | 1.49%   |
| Samsung Electronics HD103SJ 1TB    | 2        | 2      | 1.49%   |
| Kingston SA400S37120G 120GB SSD    | 2        | 3      | 1.49%   |
| Hitachi HDP725050GLA360 500GB      | 2        | 2      | 1.49%   |
| Crucial CT525MX300SSD1 528GB       | 2        | 2      | 1.49%   |
| WDC WD7500BPVT-60HXZT1 752GB       | 1        | 1      | 0.75%   |
| WDC WD7500BPKT-75PK4T0 752GB       | 1        | 1      | 0.75%   |
| WDC WD6400AAKS-22A7B2 640GB        | 1        | 1      | 0.75%   |
| WDC WD60EFRX-68L0BN1 6TB           | 1        | 1      | 0.75%   |
| WDC WD5001AALS-00J7B1 500GB        | 1        | 1      | 0.75%   |
| WDC WD5000LPLX-00ZNTT0 500GB       | 1        | 2      | 0.75%   |
| WDC WD5000BEVT-75A0RT0 500GB       | 1        | 2      | 0.75%   |
| WDC WD5000AVVS-63H0B1 500GB        | 1        | 1      | 0.75%   |
| WDC WD5000AAKX-753CA1 500GB        | 1        | 1      | 0.75%   |
| WDC WD5000AAKS-41YGA1 500GB        | 1        | 1      | 0.75%   |
| WDC WD5000AADS-00S9B0 500GB        | 1        | 1      | 0.75%   |
| WDC WD5000AADS-00M2B0 500GB        | 1        | 1      | 0.75%   |
| WDC WD3200AAJS-56M0A0 320GB        | 1        | 1      | 0.75%   |
| WDC WD30EZRX-00SPEB0 3TB           | 1        | 1      | 0.75%   |
| WDC WD2500AAKX-75U6AA0 250GB       | 1        | 1      | 0.75%   |
| WDC WD20EFRX-68AX9N0 2TB           | 1        | 5      | 0.75%   |
| WDC WD2003FYYS-05T9B0 2TB          | 1        | 1      | 0.75%   |
| WDC WD15EVDS-73V9B0 1TB            | 1        | 1      | 0.75%   |
| WDC WD15EADS-11P8B1 1TB            | 1        | 1      | 0.75%   |
| WDC WD10JPVX-60JC3T0 1TB           | 1        | 1      | 0.75%   |
| WDC WD10JPCX-24UE4T0 1TB           | 1        | 1      | 0.75%   |
| WDC WD10EZRX-00A8LB0 1TB           | 1        | 2      | 0.75%   |
| WDC WD10EZEX-60M2NA0 1TB           | 1        | 1      | 0.75%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1        | 1      | 0.75%   |
| WDC WD10EZEX-00WN4A0 1TB           | 1        | 1      | 0.75%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 2      | 0.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 37       | 43     | 28.46%  |
| WDC                 | 34       | 42     | 26.15%  |
| Samsung Electronics | 19       | 23     | 14.62%  |
| Kingston            | 7        | 10     | 5.38%   |
| Toshiba             | 6        | 6      | 4.62%   |
| HGST                | 5        | 5      | 3.85%   |
| Hitachi             | 4        | 5      | 3.08%   |
| Crucial             | 4        | 4      | 3.08%   |
| Intel               | 2        | 2      | 1.54%   |
| SPCC                | 1        | 1      | 0.77%   |
| SanDisk             | 1        | 1      | 0.77%   |
| SABRENT             | 1        | 1      | 0.77%   |
| S3+                 | 1        | 1      | 0.77%   |
| Plextor             | 1        | 1      | 0.77%   |
| Micron Technology   | 1        | 1      | 0.77%   |
| Maxtor              | 1        | 1      | 0.77%   |
| Intenso             | 1        | 1      | 0.77%   |
| China               | 1        | 1      | 0.77%   |
| BAITITON            | 1        | 1      | 0.77%   |
| ASMT                | 1        | 1      | 0.77%   |
| A-DATA Technology   | 1        | 1      | 0.77%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 37       | 43     | 37.76%  |
| WDC                 | 34       | 42     | 34.69%  |
| Samsung Electronics | 10       | 10     | 10.2%   |
| Toshiba             | 6        | 6      | 6.12%   |
| HGST                | 5        | 5      | 5.1%    |
| Hitachi             | 4        | 5      | 4.08%   |
| Maxtor              | 1        | 1      | 1.02%   |
| ASMT                | 1        | 1      | 1.02%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 87       | 113    | 73.11%  |
| SSD  | 28       | 35     | 23.53%  |
| NVMe | 4        | 4      | 3.36%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Desktops | Drives | Percent |
|------------------------|----------|--------|---------|
| Patriot Pyro SSD 120GB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Patriot | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2684     | 7656   | 82.21%  |
| Works    | 468      | 1134   | 14.33%  |
| Malfunc  | 111      | 152    | 3.4%    |
| Failed   | 1        | 2      | 0.03%   |
| Limited  | 1        | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1690     | 35.22%  |
| AMD                              | 1379     | 28.74%  |
| Samsung Electronics              | 518      | 10.79%  |
| SanDisk                          | 194      | 4.04%   |
| ASMedia Technology               | 183      | 3.81%   |
| Phison Electronics               | 177      | 3.69%   |
| Micron/Crucial Technology        | 85       | 1.77%   |
| Marvell Technology Group         | 80       | 1.67%   |
| JMicron Technology               | 77       | 1.6%    |
| Silicon Motion                   | 75       | 1.56%   |
| Kingston Technology Company      | 62       | 1.29%   |
| Nvidia                           | 59       | 1.23%   |
| ADATA Technology                 | 46       | 0.96%   |
| Realtek Semiconductor            | 31       | 0.65%   |
| Broadcom / LSI                   | 20       | 0.42%   |
| SK hynix                         | 16       | 0.33%   |
| Toshiba America Info Systems     | 15       | 0.31%   |
| Micron Technology                | 14       | 0.29%   |
| LSI Logic / Symbios Logic        | 14       | 0.29%   |
| Seagate Technology               | 13       | 0.27%   |
| VIA Technologies                 | 10       | 0.21%   |
| Lite-On Technology               | 8        | 0.17%   |
| Silicon Image                    | 6        | 0.13%   |
| Shenzhen Longsys Electronics     | 4        | 0.08%   |
| INNOGRIT                         | 4        | 0.08%   |
| Adaptec                          | 4        | 0.08%   |
| HighPoint Technologies           | 3        | 0.06%   |
| Silicon Integrated Systems [SiS] | 2        | 0.04%   |
| KIOXIA                           | 2        | 0.04%   |
| Hewlett-Packard                  | 2        | 0.04%   |
| Union Memory (Shenzhen)          | 1        | 0.02%   |
| Solid State Storage Technology   | 1        | 0.02%   |
| OCZ Technology Group             | 1        | 0.02%   |
| Integrated Technology Express    | 1        | 0.02%   |
| Beijing Starblaze Technology     | 1        | 0.02%   |
| Apple                            | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 922      | 15.56%  |
| AMD 400 Series Chipset SATA Controller                                                  | 416      | 7.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 332      | 5.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 186      | 3.14%   |
| AMD 500 Series Chipset SATA Controller                                                  | 184      | 3.11%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 176      | 2.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 150      | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 150      | 2.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 138      | 2.33%   |
| Intel SATA Controller [RAID mode]                                                       | 137      | 2.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 117      | 1.98%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 99       | 1.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 97       | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 97       | 1.64%   |
| Phison E12 NVMe Controller                                                              | 89       | 1.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 76       | 1.28%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 73       | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 73       | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 72       | 1.22%   |
| AMD 300 Series Chipset SATA Controller                                                  | 72       | 1.22%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 65       | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 64       | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 64       | 1.08%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 63       | 1.06%   |
| AMD FCH SATA Controller D                                                               | 63       | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 61       | 1.03%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 54       | 0.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 49       | 0.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 45       | 0.76%   |
| Intel SSD 660P Series                                                                   | 45       | 0.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 44       | 0.74%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 42       | 0.71%   |
| Nvidia MCP61 SATA Controller                                                            | 41       | 0.69%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 41       | 0.69%   |
| Kingston Company A2000 NVMe SSD                                                         | 40       | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 38       | 0.64%   |
| Samsung NVMe SSD Controller 980                                                         | 37       | 0.62%   |
| AMD X370 Series Chipset SATA Controller                                                 | 37       | 0.62%   |
| Nvidia MCP61 IDE                                                                        | 33       | 0.56%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 32       | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2629     | 57.72%  |
| NVMe | 1147     | 25.18%  |
| IDE  | 517      | 11.35%  |
| RAID | 220      | 4.83%   |
| SAS  | 31       | 0.68%   |
| SCSI | 11       | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1663     | 53.73%  |
| AMD    | 1432     | 46.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 142      | 4.56%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 109      | 3.5%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 65       | 2.09%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 60       | 1.93%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 52       | 1.67%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 52       | 1.67%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 49       | 1.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 45       | 1.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 40       | 1.28%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 40       | 1.28%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 40       | 1.28%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 40       | 1.28%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 37       | 1.19%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 36       | 1.16%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 35       | 1.12%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 34       | 1.09%   |
| AMD FX-6300 Six-Core Processor              | 32       | 1.03%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 31       | 1%      |
| AMD FX-8350 Eight-Core Processor            | 31       | 1%      |
| Intel Core i7-4790K CPU @ 4.00GHz           | 30       | 0.96%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 30       | 0.96%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 29       | 0.93%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 29       | 0.93%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 27       | 0.87%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 26       | 0.84%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 23       | 0.74%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 23       | 0.74%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 23       | 0.74%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 23       | 0.74%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 22       | 0.71%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 22       | 0.71%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 22       | 0.71%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 20       | 0.64%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 20       | 0.64%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 19       | 0.61%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 19       | 0.61%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 18       | 0.58%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 18       | 0.58%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 18       | 0.58%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 18       | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 522      | 16.8%   |
| AMD Ryzen 5             | 497      | 15.99%  |
| Intel Core i7           | 485      | 15.6%   |
| AMD Ryzen 7             | 318      | 10.23%  |
| AMD Ryzen 9             | 163      | 5.24%   |
| Intel Core i3           | 158      | 5.08%   |
| Intel Xeon              | 142      | 4.57%   |
| AMD FX                  | 111      | 3.57%   |
| AMD Ryzen 3             | 60       | 1.93%   |
| Other                   | 57       | 1.83%   |
| Intel Core i9           | 53       | 1.71%   |
| Intel Core 2 Duo        | 49       | 1.58%   |
| Intel Core 2 Quad       | 46       | 1.48%   |
| AMD Ryzen Threadripper  | 45       | 1.45%   |
| Intel Pentium           | 43       | 1.38%   |
| Intel Celeron           | 38       | 1.22%   |
| AMD Phenom II X4        | 31       | 1%      |
| Intel Pentium Dual-Core | 29       | 0.93%   |
| AMD A10                 | 27       | 0.87%   |
| AMD A8                  | 25       | 0.8%    |
| AMD Athlon II X2        | 19       | 0.61%   |
| AMD Athlon              | 17       | 0.55%   |
| Intel Core 2            | 16       | 0.51%   |
| AMD A6                  | 14       | 0.45%   |
| AMD Phenom II X6        | 12       | 0.39%   |
| AMD Athlon II X4        | 12       | 0.39%   |
| AMD A4                  | 12       | 0.39%   |
| AMD Athlon 64 X2        | 10       | 0.32%   |
| Intel Atom              | 9        | 0.29%   |
| AMD Phenom              | 9        | 0.29%   |
| Intel Pentium Dual      | 8        | 0.26%   |
| AMD Ryzen 5 PRO         | 8        | 0.26%   |
| Intel Pentium Gold      | 6        | 0.19%   |
| AMD Athlon X4           | 6        | 0.19%   |
| Intel Pentium D         | 5        | 0.16%   |
| AMD Sempron             | 5        | 0.16%   |
| AMD Ryzen 7 PRO         | 4        | 0.13%   |
| AMD Ryzen 3 PRO         | 4        | 0.13%   |
| AMD Athlon II X3        | 4        | 0.13%   |
| AMD Athlon 64           | 4        | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1192     | 38.36%  |
| 6      | 655      | 21.08%  |
| 2      | 453      | 14.58%  |
| 8      | 441      | 14.19%  |
| 12     | 143      | 4.6%    |
| 16     | 70       | 2.25%   |
| 3      | 49       | 1.58%   |
| 10     | 31       | 1%      |
| 1      | 30       | 0.97%   |
| 24     | 17       | 0.55%   |
| 32     | 16       | 0.51%   |
| 64     | 4        | 0.13%   |
| 14     | 4        | 0.13%   |
| 28     | 1        | 0.03%   |
| 18     | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3062     | 98.93%  |
| 2      | 33       | 1.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2094     | 67.53%  |
| 1      | 1007     | 32.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3091     | 99.87%  |
| Unknown        | 4        | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2218     | 69.95%  |
| 0x08701021 | 98       | 3.09%   |
| 0x306c3    | 75       | 2.37%   |
| 0x0800820d | 73       | 2.3%    |
| 0x08701013 | 72       | 2.27%   |
| 0x306a9    | 61       | 1.92%   |
| 0x206a7    | 50       | 1.58%   |
| 0x506e3    | 41       | 1.29%   |
| 0x906ea    | 38       | 1.2%    |
| 0x906e9    | 30       | 0.95%   |
| 0x1067a    | 27       | 0.85%   |
| 0x08001138 | 27       | 0.85%   |
| 0x08108109 | 24       | 0.76%   |
| 0x06000852 | 23       | 0.73%   |
| 0x0a201016 | 20       | 0.63%   |
| 0x906ec    | 15       | 0.47%   |
| 0x906ed    | 14       | 0.44%   |
| 0x0a201009 | 13       | 0.41%   |
| 0x08301039 | 13       | 0.41%   |
| 0x06001119 | 11       | 0.35%   |
| 0x08001137 | 10       | 0.32%   |
| 0x010000c8 | 10       | 0.32%   |
| 0xa0655    | 9        | 0.28%   |
| 0x306f2    | 9        | 0.28%   |
| 0x106a5    | 9        | 0.28%   |
| 0x06003106 | 9        | 0.28%   |
| 0xa0653    | 8        | 0.25%   |
| 0x206c2    | 8        | 0.25%   |
| 0xa0671    | 7        | 0.22%   |
| 0x906eb    | 7        | 0.22%   |
| 0x6fd      | 6        | 0.19%   |
| 0x206d7    | 6        | 0.19%   |
| 0x20655    | 6        | 0.19%   |
| 0x0a50000c | 6        | 0.19%   |
| 0x90672    | 5        | 0.16%   |
| 0x6fb      | 5        | 0.16%   |
| 0x08101016 | 5        | 0.16%   |
| 0x010000dc | 5        | 0.16%   |
| 0x50654    | 4        | 0.13%   |
| 0x306e4    | 4        | 0.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 474      | 15.27%  |
| Haswell          | 323      | 10.4%   |
| KabyLake         | 285      | 9.18%   |
| Zen+             | 255      | 8.21%   |
| IvyBridge        | 225      | 7.25%   |
| Zen 3            | 218      | 7.02%   |
| SandyBridge      | 208      | 6.7%    |
| Zen              | 159      | 5.12%   |
| Skylake          | 159      | 5.12%   |
| Piledriver       | 136      | 4.38%   |
| Penryn           | 105      | 3.38%   |
| K10              | 97       | 3.12%   |
| CometLake        | 78       | 2.51%   |
| Nehalem          | 69       | 2.22%   |
| Unknown          | 56       | 1.8%    |
| Westmere         | 54       | 1.74%   |
| Core             | 54       | 1.74%   |
| Steamroller      | 23       | 0.74%   |
| Silvermont       | 21       | 0.68%   |
| K8 Hammer        | 18       | 0.58%   |
| Excavator        | 15       | 0.48%   |
| K10 Llano        | 13       | 0.42%   |
| Bulldozer        | 11       | 0.35%   |
| NetBurst         | 8        | 0.26%   |
| Goldmont plus    | 7        | 0.23%   |
| Jaguar           | 6        | 0.19%   |
| Icelake          | 6        | 0.19%   |
| Broadwell        | 6        | 0.19%   |
| Alderlake Hybrid | 6        | 0.19%   |
| Bobcat           | 4        | 0.13%   |
| Goldmont         | 3        | 0.1%    |
| Bonnell          | 2        | 0.06%   |
| Puma             | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 1610     | 48.45%  |
| AMD                              | 1125     | 33.85%  |
| Intel                            | 581      | 17.48%  |
| Matrox Electronics Systems       | 5        | 0.15%   |
| Silicon Integrated Systems [SiS] | 2        | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 230      | 6.69%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 110      | 3.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 109      | 3.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 99       | 2.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 75       | 2.18%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 73       | 2.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 71       | 2.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 63       | 1.83%   |
| Nvidia GK208B [GeForce GT 710]                                              | 62       | 1.8%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 62       | 1.8%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 61       | 1.78%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 52       | 1.51%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 52       | 1.51%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 46       | 1.34%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 44       | 1.28%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 44       | 1.28%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 44       | 1.28%   |
| Intel HD Graphics 530                                                       | 41       | 1.19%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 40       | 1.16%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 39       | 1.14%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 38       | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 37       | 1.08%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 34       | 0.99%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 32       | 0.93%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 30       | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 30       | 0.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 30       | 0.87%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 29       | 0.84%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 29       | 0.84%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 29       | 0.84%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 29       | 0.84%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 28       | 0.81%   |
| Nvidia GT218 [GeForce 210]                                                  | 28       | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 26       | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 26       | 0.76%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 26       | 0.76%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 26       | 0.76%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 25       | 0.73%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 24       | 0.7%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 23       | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 1493     | 47.49%  |
| 1 x AMD              | 1028     | 32.7%   |
| 1 x Intel            | 430      | 13.68%  |
| 2 x AMD              | 45       | 1.43%   |
| Intel + Nvidia       | 45       | 1.43%   |
| 2 x Nvidia           | 33       | 1.05%   |
| AMD + Nvidia         | 33       | 1.05%   |
| Intel + AMD          | 23       | 0.73%   |
| 1 x Matrox           | 4        | 0.13%   |
| 1 x SiS              | 2        | 0.06%   |
| Other                | 1        | 0.03%   |
| 5 x Nvidia           | 1        | 0.03%   |
| 4 x Nvidia           | 1        | 0.03%   |
| 3 x Nvidia           | 1        | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.03%   |
| Intel + 2 x Nvidia   | 1        | 0.03%   |
| AMD + 2 x Nvidia     | 1        | 0.03%   |
| AMD + Matrox         | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1641     | 52.23%  |
| Proprietary | 1309     | 41.66%  |
| Unknown     | 192      | 6.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1628     | 51.34%  |
| 7.01-8.0   | 436      | 13.75%  |
| 1.01-2.0   | 283      | 8.92%   |
| 3.01-4.0   | 271      | 8.55%   |
| 5.01-6.0   | 231      | 7.28%   |
| 8.01-16.0  | 126      | 3.97%   |
| 0.51-1.0   | 83       | 2.62%   |
| 2.01-3.0   | 48       | 1.51%   |
| 0.01-0.5   | 43       | 1.36%   |
| 16.01-24.0 | 17       | 0.54%   |
| 4.01-5.0   | 3        | 0.09%   |
| 32.01-64.0 | 1        | 0.03%   |
| 24.01-32.0 | 1        | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 570      | 16.55%  |
| Goldstar             | 406      | 11.79%  |
| Dell                 | 379      | 11%     |
| Acer                 | 304      | 8.83%   |
| Hewlett-Packard      | 212      | 6.16%   |
| AOC                  | 195      | 5.66%   |
| Ancor Communications | 177      | 5.14%   |
| BenQ                 | 161      | 4.67%   |
| ASUSTek Computer     | 115      | 3.34%   |
| Philips              | 100      | 2.9%    |
| ViewSonic            | 60       | 1.74%   |
| Lenovo               | 55       | 1.6%    |
| Iiyama               | 52       | 1.51%   |
| Sony                 | 47       | 1.36%   |
| MSI                  | 43       | 1.25%   |
| Sceptre Tech         | 36       | 1.05%   |
| Vizio                | 26       | 0.75%   |
| Toshiba              | 22       | 0.64%   |
| Unknown              | 21       | 0.61%   |
| Gigabyte Technology  | 21       | 0.61%   |
| Panasonic            | 16       | 0.46%   |
| Eizo                 | 16       | 0.46%   |
| Fujitsu Siemens      | 14       | 0.41%   |
| NEC Computers        | 13       | 0.38%   |
| LG Electronics       | 13       | 0.38%   |
| Insignia             | 13       | 0.38%   |
| MStar                | 12       | 0.35%   |
| Hitachi              | 11       | 0.32%   |
| Vestel Elektronik    | 10       | 0.29%   |
| HannStar             | 9        | 0.26%   |
| Videoseven           | 8        | 0.23%   |
| Pixio                | 8        | 0.23%   |
| ONN                  | 8        | 0.23%   |
| Mi                   | 8        | 0.23%   |
| Viotek               | 7        | 0.2%    |
| CVT                  | 7        | 0.2%    |
| ___                  | 6        | 0.17%   |
| Valve                | 6        | 0.17%   |
| Sharp                | 6        | 0.17%   |
| Seiki                | 6        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 41       | 1.12%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 27       | 0.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 23       | 0.63%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch           | 22       | 0.6%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 17       | 0.47%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 15       | 0.41%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                | 14       | 0.38%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 13       | 0.36%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 13       | 0.36%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 12       | 0.33%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 12       | 0.33%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 12       | 0.33%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 11       | 0.3%    |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 11       | 0.3%    |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                       | 11       | 0.3%    |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 10       | 0.27%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 10       | 0.27%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 10       | 0.27%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch      | 10       | 0.27%   |
| Ancor Communications VE247 ACI2493 1920x1080 530x300mm 24.0-inch      | 10       | 0.27%   |
| Acer V246HQL ACR0424 1920x1080 521x293mm 23.5-inch                    | 10       | 0.27%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 9        | 0.25%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 9        | 0.25%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 9        | 0.25%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 9        | 0.25%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 9        | 0.25%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch               | 8        | 0.22%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 8        | 0.22%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 8        | 0.22%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 8        | 0.22%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 8        | 0.22%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 8        | 0.22%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 8        | 0.22%   |
| AOC 2460G5 AOC0001 1920x1080 531x299mm 24.0-inch                      | 8        | 0.22%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch      | 8        | 0.22%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 8        | 0.22%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 7        | 0.19%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 7        | 0.19%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 7        | 0.19%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 7        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1519     | 46.4%   |
| 3840x2160 (4K)     | 404      | 12.34%  |
| 2560x1440 (QHD)    | 327      | 9.99%   |
| 1680x1050 (WSXGA+) | 136      | 4.15%   |
| 1280x1024 (SXGA)   | 127      | 3.88%   |
| 3440x1440          | 119      | 3.63%   |
| 1366x768 (WXGA)    | 110      | 3.36%   |
| 2560x1080          | 103      | 3.15%   |
| 1920x1200 (WUXGA)  | 77       | 2.35%   |
| 1440x900 (WXGA+)   | 77       | 2.35%   |
| 1600x900 (HD+)     | 69       | 2.11%   |
| 1360x768           | 40       | 1.22%   |
| 3840x1080          | 30       | 0.92%   |
| 1920x540           | 29       | 0.89%   |
| Unknown            | 24       | 0.73%   |
| 3840x1600          | 11       | 0.34%   |
| 1600x1200          | 10       | 0.31%   |
| 1280x720 (HD)      | 10       | 0.31%   |
| 1024x768 (XGA)     | 10       | 0.31%   |
| 2560x1600          | 7        | 0.21%   |
| 2048x1152          | 4        | 0.12%   |
| 5120x1440          | 2        | 0.06%   |
| 4480x1440          | 2        | 0.06%   |
| 3840x1200          | 2        | 0.06%   |
| 9840x3840          | 1        | 0.03%   |
| 8320x2160          | 1        | 0.03%   |
| 8160x4627          | 1        | 0.03%   |
| 7680x2160          | 1        | 0.03%   |
| 6400x1440          | 1        | 0.03%   |
| 5280x1080          | 1        | 0.03%   |
| 5200x2160          | 1        | 0.03%   |
| 4096x2160          | 1        | 0.03%   |
| 4080x2030          | 1        | 0.03%   |
| 4080x2026          | 1        | 0.03%   |
| 3360x1080          | 1        | 0.03%   |
| 3280x2048          | 1        | 0.03%   |
| 3280x1080          | 1        | 0.03%   |
| 3040x900           | 1        | 0.03%   |
| 2960x1050          | 1        | 0.03%   |
| 2880x1600          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 615      | 17.96%  |
| 24      | 522      | 15.25%  |
| 23      | 415      | 12.12%  |
| 21      | 331      | 9.67%   |
| 31      | 201      | 5.87%   |
| 34      | 185      | 5.4%    |
| 19      | 138      | 4.03%   |
| Unknown | 116      | 3.39%   |
| 22      | 101      | 2.95%   |
| 18      | 100      | 2.92%   |
| 20      | 78       | 2.28%   |
| 17      | 67       | 1.96%   |
| 84      | 66       | 1.93%   |
| 32      | 55       | 1.61%   |
| 72      | 54       | 1.58%   |
| 15      | 46       | 1.34%   |
| 54      | 30       | 0.88%   |
| 26      | 27       | 0.79%   |
| 25      | 26       | 0.76%   |
| 48      | 21       | 0.61%   |
| 49      | 20       | 0.58%   |
| 35      | 20       | 0.58%   |
| 28      | 17       | 0.5%    |
| 65      | 16       | 0.47%   |
| 52      | 15       | 0.44%   |
| 40      | 15       | 0.44%   |
| 46      | 12       | 0.35%   |
| 37      | 12       | 0.35%   |
| 29      | 12       | 0.35%   |
| 33      | 8        | 0.23%   |
| 47      | 7        | 0.2%    |
| 42      | 7        | 0.2%    |
| 43      | 6        | 0.18%   |
| 74      | 5        | 0.15%   |
| 55      | 5        | 0.15%   |
| 36      | 5        | 0.15%   |
| 41      | 4        | 0.12%   |
| 38      | 4        | 0.12%   |
| 12      | 4        | 0.12%   |
| 11      | 4        | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1387     | 42.33%  |
| 401-500        | 661      | 20.17%  |
| 601-700        | 315      | 9.61%   |
| 701-800        | 248      | 7.57%   |
| 1001-1500      | 142      | 4.33%   |
| 1501-2000      | 128      | 3.91%   |
| Unknown        | 116      | 3.54%   |
| 301-350        | 103      | 3.14%   |
| 351-400        | 88       | 2.69%   |
| 801-900        | 58       | 1.77%   |
| 901-1000       | 18       | 0.55%   |
| 201-300        | 12       | 0.37%   |
| More than 2000 | 1        | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2190     | 72.04%  |
| 16/10   | 340      | 11.18%  |
| 21/9    | 226      | 7.43%   |
| 5/4     | 124      | 4.08%   |
| Unknown | 70       | 2.3%    |
| 32/9    | 34       | 1.12%   |
| 4/3     | 31       | 1.02%   |
| 3/2     | 10       | 0.33%   |
| 6/5     | 7        | 0.23%   |
| 1.96    | 5        | 0.16%   |
| 3.20    | 2        | 0.07%   |
| 1.00    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1070     | 32.06%  |
| 301-350        | 629      | 18.84%  |
| 351-500        | 474      | 14.2%   |
| 151-200        | 319      | 9.56%   |
| More than 1000 | 217      | 6.5%    |
| 251-300        | 201      | 6.02%   |
| 141-150        | 135      | 4.04%   |
| Unknown        | 116      | 3.48%   |
| 501-1000       | 111      | 3.33%   |
| 101-110        | 36       | 1.08%   |
| 131-140        | 7        | 0.21%   |
| 71-80          | 6        | 0.18%   |
| 91-100         | 6        | 0.18%   |
| 51-60          | 4        | 0.12%   |
| 111-120        | 4        | 0.12%   |
| 121-130        | 3        | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1912     | 61.18%  |
| 101-120       | 684      | 21.89%  |
| 1-50          | 173      | 5.54%   |
| 121-160       | 166      | 5.31%   |
| Unknown       | 116      | 3.71%   |
| 161-240       | 73       | 2.34%   |
| More than 240 | 1        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2201     | 69.43%  |
| 2     | 656      | 20.69%  |
| 0     | 221      | 6.97%   |
| 3     | 81       | 2.56%   |
| 4     | 9        | 0.28%   |
| 6     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 1835     | 40.19%  |
| Intel                           | 1498     | 32.81%  |
| Qualcomm Atheros                | 271      | 5.94%   |
| Broadcom                        | 162      | 3.55%   |
| Ralink Technology               | 93       | 2.04%   |
| TP-Link                         | 87       | 1.91%   |
| Microsoft                       | 63       | 1.38%   |
| Nvidia                          | 48       | 1.05%   |
| Ralink                          | 43       | 0.94%   |
| Samsung Electronics             | 40       | 0.88%   |
| Qualcomm Atheros Communications | 33       | 0.72%   |
| NetGear                         | 33       | 0.72%   |
| InterBiometrics                 | 32       | 0.7%    |
| Aquantia                        | 28       | 0.61%   |
| MediaTek                        | 22       | 0.48%   |
| Xiaomi                          | 21       | 0.46%   |
| Marvell Technology Group        | 20       | 0.44%   |
| D-Link                          | 17       | 0.37%   |
| Huawei Technologies             | 16       | 0.35%   |
| Google                          | 16       | 0.35%   |
| Linksys                         | 14       | 0.31%   |
| Broadcom Limited                | 13       | 0.28%   |
| ASUSTek Computer                | 13       | 0.28%   |
| ASIX Electronics                | 10       | 0.22%   |
| Edimax Technology               | 9        | 0.2%    |
| Belkin Components               | 8        | 0.18%   |
| OnePlus Technology (Shenzhen)   | 7        | 0.15%   |
| Motorola PCS                    | 7        | 0.15%   |
| D-Link System                   | 7        | 0.15%   |
| OPPO Electronics                | 6        | 0.13%   |
| DisplayLink                     | 6        | 0.13%   |
| AVM                             | 6        | 0.13%   |
| Sitecom Europe                  | 5        | 0.11%   |
| Gemtek                          | 5        | 0.11%   |
| VIA Technologies                | 4        | 0.09%   |
| Mercucys                        | 4        | 0.09%   |
| Mellanox Technologies           | 4        | 0.09%   |
| Qualcomm                        | 3        | 0.07%   |
| Microchip Technology            | 3        | 0.07%   |
| IMC Networks                    | 3        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1442     | 27.18%  |
| Intel I211 Gigabit Network Connection                             | 368      | 6.94%   |
| Intel Wi-Fi 6 AX200                                               | 312      | 5.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 188      | 3.54%   |
| Intel Ethernet Connection (2) I219-V                              | 139      | 2.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 120      | 2.26%   |
| Intel Ethernet Controller I225-V                                  | 105      | 1.98%   |
| Intel Wireless-AC 9260                                            | 94       | 1.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 90       | 1.7%    |
| Intel Ethernet Connection (7) I219-V                              | 84       | 1.58%   |
| Intel Ethernet Connection I217-LM                                 | 68       | 1.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 56       | 1.06%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 51       | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 49       | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 47       | 0.89%   |
| Realtek 802.11ac NIC                                              | 45       | 0.85%   |
| Intel Ethernet Connection (2) I218-V                              | 45       | 0.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40       | 0.75%   |
| Ralink MT7601U Wireless Adapter                                   | 40       | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 40       | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 39       | 0.74%   |
| Nvidia MCP61 Ethernet                                             | 35       | 0.66%   |
| Intel Ethernet Connection I217-V                                  | 35       | 0.66%   |
| InterBiometrics Io                                                | 31       | 0.58%   |
| Microsoft XBOX ACC                                                | 30       | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28       | 0.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 28       | 0.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 28       | 0.53%   |
| Qualcomm Atheros AR9271 802.11n                                   | 27       | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 25       | 0.47%   |
| Intel Wireless 7265                                               | 25       | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 24       | 0.45%   |
| Microsoft Xbox 360 Wireless Adapter                               | 24       | 0.45%   |
| Intel 82574L Gigabit Network Connection                           | 24       | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23       | 0.43%   |
| Intel Wireless 8265 / 8275                                        | 23       | 0.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 22       | 0.41%   |
| Intel Wireless 8260                                               | 22       | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 21       | 0.4%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 21       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 718      | 40.5%   |
| Realtek Semiconductor                 | 355      | 20.02%  |
| Qualcomm Atheros                      | 139      | 7.84%   |
| Broadcom                              | 95       | 5.36%   |
| Ralink Technology                     | 93       | 5.25%   |
| TP-Link                               | 83       | 4.68%   |
| Microsoft                             | 63       | 3.55%   |
| Ralink                                | 43       | 2.43%   |
| Qualcomm Atheros Communications       | 33       | 1.86%   |
| NetGear                               | 33       | 1.86%   |
| MediaTek                              | 18       | 1.02%   |
| D-Link                                | 16       | 0.9%    |
| Linksys                               | 13       | 0.73%   |
| ASUSTek Computer                      | 13       | 0.73%   |
| Edimax Technology                     | 9        | 0.51%   |
| Belkin Components                     | 8        | 0.45%   |
| AVM                                   | 6        | 0.34%   |
| Sitecom Europe                        | 5        | 0.28%   |
| Gemtek                                | 5        | 0.28%   |
| Mercucys                              | 4        | 0.23%   |
| Broadcom Limited                      | 4        | 0.23%   |
| IMC Networks                          | 3        | 0.17%   |
| D-Link System                         | 3        | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.11%   |
| ZyDAS                                 | 1        | 0.06%   |
| Wilocity                              | 1        | 0.06%   |
| TRENDnet                              | 1        | 0.06%   |
| Texas Instruments                     | 1        | 0.06%   |
| Samsung Electronics                   | 1        | 0.06%   |
| Ovislink                              | 1        | 0.06%   |
| Micro Star International              | 1        | 0.06%   |
| BUFFALO                               | 1        | 0.06%   |
| Accton Technology                     | 1        | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 312      | 17.41%  |
| Intel Wireless-AC 9260                                         | 94       | 5.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 90       | 5.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 56       | 3.13%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 51       | 2.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 47       | 2.62%   |
| Realtek 802.11ac NIC                                           | 45       | 2.51%   |
| Ralink MT7601U Wireless Adapter                                | 40       | 2.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 39       | 2.18%   |
| Microsoft XBOX ACC                                             | 30       | 1.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 28       | 1.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 28       | 1.56%   |
| Qualcomm Atheros AR9271 802.11n                                | 27       | 1.51%   |
| Intel Wireless 7265                                            | 25       | 1.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 24       | 1.34%   |
| Microsoft Xbox 360 Wireless Adapter                            | 24       | 1.34%   |
| Intel Wireless 8265 / 8275                                     | 23       | 1.28%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 22       | 1.23%   |
| Intel Wireless 8260                                            | 22       | 1.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 20       | 1.12%   |
| Intel Wireless 7260                                            | 20       | 1.12%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 19       | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 19       | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 17       | 0.95%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 17       | 0.95%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 15       | 0.84%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 15       | 0.84%   |
| Ralink RT5370 Wireless Adapter                                 | 15       | 0.84%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 15       | 0.84%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 15       | 0.84%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 13       | 0.73%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 13       | 0.73%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 13       | 0.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13       | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 13       | 0.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 13       | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12       | 0.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 12       | 0.67%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 11       | 0.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11       | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1692     | 50.31%  |
| Intel                            | 1184     | 35.21%  |
| Qualcomm Atheros                 | 142      | 4.22%   |
| Broadcom                         | 72       | 2.14%   |
| Nvidia                           | 48       | 1.43%   |
| Samsung Electronics              | 39       | 1.16%   |
| Aquantia                         | 28       | 0.83%   |
| Xiaomi                           | 21       | 0.62%   |
| Marvell Technology Group         | 20       | 0.59%   |
| Huawei Technologies              | 16       | 0.48%   |
| Google                           | 16       | 0.48%   |
| ASIX Electronics                 | 10       | 0.3%    |
| Broadcom Limited                 | 9        | 0.27%   |
| OPPO Electronics                 | 6        | 0.18%   |
| DisplayLink                      | 6        | 0.18%   |
| OnePlus Technology (Shenzhen)    | 5        | 0.15%   |
| Motorola PCS                     | 5        | 0.15%   |
| VIA Technologies                 | 4        | 0.12%   |
| TP-Link                          | 4        | 0.12%   |
| MediaTek                         | 4        | 0.12%   |
| D-Link System                    | 4        | 0.12%   |
| Qualcomm                         | 3        | 0.09%   |
| Mellanox Technologies            | 3        | 0.09%   |
| ZTE WCDMA Technologies MSM       | 2        | 0.06%   |
| Lenovo                           | 2        | 0.06%   |
| ICS Advent                       | 2        | 0.06%   |
| 3Com                             | 2        | 0.06%   |
| Tehuti Networks                  | 1        | 0.03%   |
| Solarflare Communications        | 1        | 0.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.03%   |
| QLogic                           | 1        | 0.03%   |
| Netchip Technology               | 1        | 0.03%   |
| Linksys                          | 1        | 0.03%   |
| LG Electronics                   | 1        | 0.03%   |
| JMicron Technology               | 1        | 0.03%   |
| HMD Global                       | 1        | 0.03%   |
| Hangzhou Silan Microelectronics  | 1        | 0.03%   |
| Emulex                           | 1        | 0.03%   |
| D-Link                           | 1        | 0.03%   |
| Corega K.K.                      | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1442     | 41.8%   |
| Intel I211 Gigabit Network Connection                             | 368      | 10.67%  |
| Realtek RTL8125 2.5GbE Controller                                 | 188      | 5.45%   |
| Intel Ethernet Connection (2) I219-V                              | 139      | 4.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 120      | 3.48%   |
| Intel Ethernet Controller I225-V                                  | 105      | 3.04%   |
| Intel Ethernet Connection (7) I219-V                              | 84       | 2.43%   |
| Intel Ethernet Connection I217-LM                                 | 68       | 1.97%   |
| Intel 82579V Gigabit Network Connection                           | 49       | 1.42%   |
| Intel Ethernet Connection (2) I218-V                              | 45       | 1.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40       | 1.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 40       | 1.16%   |
| Nvidia MCP61 Ethernet                                             | 35       | 1.01%   |
| Intel Ethernet Connection I217-V                                  | 35       | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28       | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 25       | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 24       | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23       | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 21       | 0.61%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 21       | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 20       | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19       | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 18       | 0.52%   |
| Intel I210 Gigabit Network Connection                             | 18       | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 16       | 0.46%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 15       | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 14       | 0.41%   |
| Huawei STK-L21                                                    | 14       | 0.41%   |
| Google Nexus/Pixel Device (tether)                                | 14       | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13       | 0.38%   |
| Intel Ethernet Connection (14) I219-V                             | 11       | 0.32%   |
| Intel 82578DM Gigabit Network Connection                          | 11       | 0.32%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 11       | 0.32%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 11       | 0.32%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 9        | 0.26%   |
| Intel 82583V Gigabit Network Connection                           | 9        | 0.26%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 8        | 0.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 8        | 0.23%   |
| Intel Ethernet Connection (2) I218-LM                             | 8        | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3057     | 64.18%  |
| WiFi     | 1644     | 34.52%  |
| Modem    | 50       | 1.05%   |
| Unknown  | 12       | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2332     | 71.42%  |
| WiFi     | 931      | 28.51%  |
| Unknown  | 2        | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1837     | 58.93%  |
| 2     | 1068     | 34.26%  |
| 3     | 151      | 4.84%   |
| 0     | 31       | 0.99%   |
| 4     | 22       | 0.71%   |
| 5     | 4        | 0.13%   |
| 10    | 2        | 0.06%   |
| 6     | 2        | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2496     | 79.29%  |
| Yes  | 652      | 20.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 665      | 53.16%  |
| Cambridge Silicon Radio         | 265      | 21.18%  |
| ASUSTek Computer                | 77       | 6.16%   |
| Realtek Semiconductor           | 61       | 4.88%   |
| Broadcom                        | 60       | 4.8%    |
| Qualcomm Atheros Communications | 39       | 3.12%   |
| Apple                           | 21       | 1.68%   |
| Foxconn / Hon Hai               | 9        | 0.72%   |
| IMC Networks                    | 8        | 0.64%   |
| MediaTek                        | 7        | 0.56%   |
| TP-Link                         | 6        | 0.48%   |
| HTC (High Tech Computer)        | 4        | 0.32%   |
| Dynex                           | 4        | 0.32%   |
| Lite-On Technology              | 3        | 0.24%   |
| SINO WEALTH                     | 2        | 0.16%   |
| Realtek                         | 2        | 0.16%   |
| Ralink                          | 2        | 0.16%   |
| Integrated System Solution      | 2        | 0.16%   |
| Hewlett-Packard                 | 2        | 0.16%   |
| Dell                            | 2        | 0.16%   |
| Creative Technology             | 2        | 0.16%   |
| Conwise Technology              | 2        | 0.16%   |
| Belkin Components               | 2        | 0.16%   |
| Primax Electronics              | 1        | 0.08%   |
| Micro Star International        | 1        | 0.08%   |
| Logitech                        | 1        | 0.08%   |
| Edimax Technology               | 1        | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 291      | 23.21%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 265      | 21.13%  |
| Intel Bluetooth wireless interface                                   | 90       | 7.18%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 89       | 7.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 88       | 7.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 45       | 3.59%   |
| Realtek Bluetooth Radio                                              | 42       | 3.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 41       | 3.27%   |
| Intel AX201 Bluetooth                                                | 34       | 2.71%   |
| Intel AX210 Bluetooth                                                | 24       | 1.91%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 24       | 1.91%   |
| ASUS Bluetooth Radio                                                 | 21       | 1.67%   |
| Qualcomm Atheros  Bluetooth Device                                   | 19       | 1.52%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 14       | 1.12%   |
| ASUS Bluetooth Device                                                | 12       | 0.96%   |
| Apple Bluetooth USB Host Controller                                  | 11       | 0.88%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 7        | 0.56%   |
| MediaTek Wireless_Device                                             | 7        | 0.56%   |
| TP-Link UB500 Adapter                                                | 6        | 0.48%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 6        | 0.48%   |
| Intel Bluetooth Device                                               | 6        | 0.48%   |
| IMC Networks Bluetooth Radio                                         | 6        | 0.48%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 6        | 0.48%   |
| ASUS BCM20702A0                                                      | 6        | 0.48%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 5        | 0.4%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 5        | 0.4%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 5        | 0.4%    |
| Realtek RTL8821A Bluetooth                                           | 4        | 0.32%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 4        | 0.32%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 0.32%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 4        | 0.32%   |
| Apple Bluetooth HCI                                                  | 4        | 0.32%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 0.24%   |
| Foxconn / Hon Hai Wireless_Device                                    | 3        | 0.24%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 3        | 0.24%   |
| ASUS Bluetooth Adapter                                               | 3        | 0.24%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 2        | 0.16%   |
| Realtek Bluetooth Radio                                              | 2        | 0.16%   |
| Ralink RT3290 Bluetooth                                              | 2        | 0.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 2        | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 1713     | 28.95%  |
| Intel                                           | 1576     | 26.64%  |
| Nvidia                                          | 1553     | 26.25%  |
| C-Media Electronics                             | 166      | 2.81%   |
| Logitech                                        | 83       | 1.4%    |
| Creative Labs                                   | 60       | 1.01%   |
| Razer USA                                       | 48       | 0.81%   |
| Kingston Technology                             | 46       | 0.78%   |
| JMTek                                           | 44       | 0.74%   |
| Corsair                                         | 44       | 0.74%   |
| Texas Instruments                               | 36       | 0.61%   |
| SteelSeries ApS                                 | 35       | 0.59%   |
| Focusrite-Novation                              | 35       | 0.59%   |
| ASUSTek Computer                                | 30       | 0.51%   |
| Blue Microphones                                | 26       | 0.44%   |
| Creative Technology                             | 25       | 0.42%   |
| Generalplus Technology                          | 20       | 0.34%   |
| Sony                                            | 15       | 0.25%   |
| Giga-Byte Technology                            | 14       | 0.24%   |
| Astro Gaming                                    | 14       | 0.24%   |
| GN Netcom                                       | 13       | 0.22%   |
| Micro Star International                        | 12       | 0.2%    |
| Turtle Beach                                    | 11       | 0.19%   |
| Tenx Technology                                 | 11       | 0.19%   |
| Samson Technologies                             | 11       | 0.19%   |
| Plantronics                                     | 11       | 0.19%   |
| SAVITECH                                        | 10       | 0.17%   |
| M-Audio                                         | 10       | 0.17%   |
| Yamaha                                          | 9        | 0.15%   |
| Valve Software                                  | 9        | 0.15%   |
| Sennheiser Communications                       | 9        | 0.15%   |
| Realtek Semiconductor                           | 9        | 0.15%   |
| Thesycon Systemsoftware & Consulting            | 8        | 0.14%   |
| Licensed by Sony Computer Entertainment America | 8        | 0.14%   |
| FiiO Electronics Technology                     | 8        | 0.14%   |
| Audio-Technica                                  | 7        | 0.12%   |
| Unknown                                         | 6        | 0.1%    |
| BEHRINGER International                         | 6        | 0.1%    |
| VIA Technologies                                | 5        | 0.08%   |
| Trust                                           | 4        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 621      | 9%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 280      | 4.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 230      | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 216      | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 204      | 2.96%   |
| AMD Family 17h/19h HD Audio Controller                                     | 179      | 2.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 170      | 2.46%   |
| Nvidia GP104 High Definition Audio Controller                              | 166      | 2.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 156      | 2.26%   |
| Intel 200 Series PCH HD Audio                                              | 154      | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 151      | 2.19%   |
| AMD Navi 10 HDMI Audio                                                     | 134      | 1.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 131      | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 121      | 1.75%   |
| Nvidia TU116 High Definition Audio Controller                              | 119      | 1.72%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 117      | 1.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 116      | 1.68%   |
| Nvidia GP106 High Definition Audio Controller                              | 111      | 1.61%   |
| Nvidia TU104 HD Audio Controller                                           | 100      | 1.45%   |
| Nvidia TU106 High Definition Audio Controller                              | 96       | 1.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 92       | 1.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 89       | 1.29%   |
| AMD FCH Azalia Controller                                                  | 82       | 1.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 80       | 1.16%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 78       | 1.13%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 77       | 1.12%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 75       | 1.09%   |
| Nvidia GM204 High Definition Audio Controller                              | 66       | 0.96%   |
| Nvidia GA104 High Definition Audio Controller                              | 62       | 0.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 61       | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 56       | 0.81%   |
| Nvidia GA102 High Definition Audio Controller                              | 55       | 0.8%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 55       | 0.8%    |
| Nvidia GM206 High Definition Audio Controller                              | 51       | 0.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 48       | 0.7%    |
| Nvidia GP102 HDMI Audio Controller                                         | 47       | 0.68%   |
| Nvidia GK104 HDMI Audio Controller                                         | 47       | 0.68%   |
| Nvidia MCP61 High Definition Audio                                         | 41       | 0.59%   |
| Nvidia GP108 High Definition Audio Controller                              | 39       | 0.57%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 39       | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 129      | 22.28%  |
| Kingston                     | 105      | 18.13%  |
| G.Skill                      | 86       | 14.85%  |
| Crucial                      | 57       | 9.84%   |
| Unknown                      | 51       | 8.81%   |
| Samsung Electronics          | 33       | 5.7%    |
| SK hynix                     | 27       | 4.66%   |
| Team                         | 21       | 3.63%   |
| Micron Technology            | 18       | 3.11%   |
| A-DATA Technology            | 14       | 2.42%   |
| Patriot                      | 8        | 1.38%   |
| Ramaxel Technology           | 3        | 0.52%   |
| Patriot Memory               | 2        | 0.35%   |
| OLOY                         | 2        | 0.35%   |
| Avant                        | 2        | 0.35%   |
| Unknown                      | 2        | 0.35%   |
| Unifosa                      | 1        | 0.17%   |
| Transcend                    | 1        | 0.17%   |
| Toshiba                      | 1        | 0.17%   |
| Teikon                       | 1        | 0.17%   |
| Smart                        | 1        | 0.17%   |
| Silicon Power                | 1        | 0.17%   |
| Patriot Memory (PDP Systems) | 1        | 0.17%   |
| Neo Forza                    | 1        | 0.17%   |
| Nanya Technology             | 1        | 0.17%   |
| HMD                          | 1        | 0.17%   |
| Goodram                      | 1        | 0.17%   |
| Goldkey                      | 1        | 0.17%   |
| GLOWAY                       | 1        | 0.17%   |
| EVGA                         | 1        | 0.17%   |
| Elpida                       | 1        | 0.17%   |
| CSX                          | 1        | 0.17%   |
| ASint Technology             | 1        | 0.17%   |
| Apacer                       | 1        | 0.17%   |
| AMD                          | 1        | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 20       | 3.26%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s       | 12       | 1.95%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s     | 10       | 1.63%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 8        | 1.3%    |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s    | 8        | 1.3%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s       | 6        | 0.98%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 6        | 0.98%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 5        | 0.81%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 5        | 0.81%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 5        | 0.81%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s    | 5        | 0.81%   |
| Team RAM TEAMGROUP-UD4-2666 32GB DIMM DDR4 3000MT/s       | 4        | 0.65%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 4        | 0.65%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s      | 4        | 0.65%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s     | 4        | 0.65%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s    | 4        | 0.65%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s      | 4        | 0.65%   |
| Corsair RAM CMK32GX4M2E3200C16 16384MB DIMM DDR4 3200MT/s | 4        | 0.65%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s    | 4        | 0.65%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s     | 4        | 0.65%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3400MT/s              | 4        | 0.65%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 3        | 0.49%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s        | 3        | 0.49%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s   | 3        | 0.49%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 3        | 0.49%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 3        | 0.49%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s       | 3        | 0.49%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s   | 3        | 0.49%   |
| G.Skill RAM F4-3600C18-8GVK 8GB DIMM DDR4 3600MT/s        | 3        | 0.49%   |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s      | 3        | 0.49%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s      | 3        | 0.49%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 3        | 0.49%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s       | 3        | 0.49%   |
| Crucial RAM BLS8G4D26BFSEK.8FD 8GB DIMM DDR4 3000MT/s     | 3        | 0.49%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s     | 3        | 0.49%   |
| A-DATA RAM DDR4 3000 16384MB DIMM DDR4 3600MT/s           | 3        | 0.49%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s              | 2        | 0.33%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 2        | 0.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 2        | 0.33%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 2        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 380      | 71.43%  |
| DDR3    | 114      | 21.43%  |
| Unknown | 15       | 2.82%   |
| DDR2    | 10       | 1.88%   |
| SDRAM   | 7        | 1.32%   |
| DDR5    | 3        | 0.56%   |
| DDR     | 2        | 0.38%   |
| LPDDR4  | 1        | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 511      | 96.78%  |
| SODIMM       | 15       | 2.84%   |
| Row Of Chips | 1        | 0.19%   |
| RIMM         | 1        | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 269      | 47.61%  |
| 16384 | 125      | 22.12%  |
| 4096  | 97       | 17.17%  |
| 32768 | 38       | 6.73%   |
| 2048  | 25       | 4.42%   |
| 1024  | 9        | 1.59%   |
| 512   | 2        | 0.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 104      | 18.12%  |
| 3200    | 77       | 13.41%  |
| 1600    | 60       | 10.45%  |
| 1333    | 44       | 7.67%   |
| 2400    | 43       | 7.49%   |
| 3000    | 25       | 4.36%   |
| 2133    | 21       | 3.66%   |
| 2667    | 20       | 3.48%   |
| 3400    | 17       | 2.96%   |
| 3866    | 15       | 2.61%   |
| 3466    | 15       | 2.61%   |
| 1867    | 13       | 2.26%   |
| 3800    | 11       | 1.92%   |
| 2933    | 10       | 1.74%   |
| 3733    | 9        | 1.57%   |
| 2666    | 9        | 1.57%   |
| 2800    | 8        | 1.39%   |
| 800     | 8        | 1.39%   |
| 1866    | 7        | 1.22%   |
| 667     | 6        | 1.05%   |
| Unknown | 5        | 0.87%   |
| 1800    | 4        | 0.7%    |
| 4400    | 3        | 0.52%   |
| 4000    | 3        | 0.52%   |
| 3666    | 3        | 0.52%   |
| 3333    | 3        | 0.52%   |
| 4800    | 2        | 0.35%   |
| 4266    | 2        | 0.35%   |
| 3533    | 2        | 0.35%   |
| 3334    | 2        | 0.35%   |
| 3151    | 2        | 0.35%   |
| 3100    | 2        | 0.35%   |
| 3066    | 2        | 0.35%   |
| 2733    | 2        | 0.35%   |
| 2472    | 2        | 0.35%   |
| 2134    | 2        | 0.35%   |
| 1066    | 2        | 0.35%   |
| 49926   | 1        | 0.17%   |
| 8400    | 1        | 0.17%   |
| 6400    | 1        | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 40       | 29.85%  |
| Brother Industries    | 28       | 20.9%   |
| Canon                 | 21       | 15.67%  |
| Samsung Electronics   | 16       | 11.94%  |
| Seiko Epson           | 13       | 9.7%    |
| Dymo-CoStar           | 4        | 2.99%   |
| Fuji Xerox            | 3        | 2.24%   |
| QinHeng Electronics   | 2        | 1.49%   |
| Xerox                 | 1        | 0.75%   |
| STMicroelectronics    | 1        | 0.75%   |
| Prolific Technology   | 1        | 0.75%   |
| Oki Data              | 1        | 0.75%   |
| Lexmark International | 1        | 0.75%   |
| Kyocera               | 1        | 0.75%   |
| Apple                 | 1        | 0.75%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| HP Deskjet 3050 J610 series                                | 4        | 2.96%   |
| Samsung SCX-3400 Series                                    | 3        | 2.22%   |
| Brother Printer                                            | 3        | 2.22%   |
| Brother HL-2130 series                                     | 3        | 2.22%   |
| Seiko Epson L4150 Series                                   | 2        | 1.48%   |
| Seiko Epson L355 Series                                    | 2        | 1.48%   |
| Seiko Epson ET-2600 Series                                 | 2        | 1.48%   |
| Samsung ML-1640 Series Laser Printer                       | 2        | 1.48%   |
| Samsung M2070 Series                                       | 2        | 1.48%   |
| Samsung M2020 Series                                       | 2        | 1.48%   |
| QinHeng CH340S                                             | 2        | 1.48%   |
| HP LaserJet Professional P 1102w                           | 2        | 1.48%   |
| HP ENVY Photo 6200 series                                  | 2        | 1.48%   |
| HP ENVY 4500 series                                        | 2        | 1.48%   |
| HP DeskJet F4100 Printer series                            | 2        | 1.48%   |
| HP Deskjet 1000 J110 series                                | 2        | 1.48%   |
| Fuji Xerox DocuPrint CM315/318 z                           | 2        | 1.48%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                     | 2        | 1.48%   |
| Canon PIXMA MX920 Series                                   | 2        | 1.48%   |
| Canon PIXMA MG2500 Series                                  | 2        | 1.48%   |
| Brother HL-L3230CDW series                                 | 2        | 1.48%   |
| Brother HL-2270DW Laser Printer                            | 2        | 1.48%   |
| Brother HL-1110 series                                     | 2        | 1.48%   |
| Xerox Phaser 6000B                                         | 1        | 0.74%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 1        | 0.74%   |
| Seiko Epson WF-4830 Series                                 | 1        | 0.74%   |
| Seiko Epson WF-3520 Series                                 | 1        | 0.74%   |
| Seiko Epson L365 Series                                    | 1        | 0.74%   |
| Seiko Epson L3110 Series                                   | 1        | 0.74%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1        | 0.74%   |
| Seiko Epson ET-3760 Series                                 | 1        | 0.74%   |
| Seiko Epson ET-2800 Series                                 | 1        | 0.74%   |
| Samsung SCX-4200 series                                    | 1        | 0.74%   |
| Samsung ML-2540 Series Laser Printer                       | 1        | 0.74%   |
| Samsung ML-191x/ML-252x Laser Printer                      | 1        | 0.74%   |
| Samsung ML-1670 Series                                     | 1        | 0.74%   |
| Samsung ML-1660 Series                                     | 1        | 0.74%   |
| Samsung Composite Device                                   | 1        | 0.74%   |
| Samsung C43x Series                                        | 1        | 0.74%   |
| Prolific PL2305 Parallel Port                              | 1        | 0.74%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 10       | 66.67%  |
| Seiko Epson     | 2        | 13.33%  |
| Hewlett-Packard | 2        | 13.33%  |
| Mustek Systems  | 1        | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30          | 2        | 13.33%  |
| Canon CanoScan LiDE 210                | 2        | 13.33%  |
| Seiko Epson Scanner                    | 1        | 6.67%   |
| Seiko Epson GT-X700 [Perfection 4870]  | 1        | 6.67%   |
| Mustek Systems ScanExpress 1200 UB     | 1        | 6.67%   |
| HP Scanjet 300                         | 1        | 6.67%   |
| HP ScanJet 2400c                       | 1        | 6.67%   |
| Canon CanoScan N650U/N656U             | 1        | 6.67%   |
| Canon CanoScan LiDE 60                 | 1        | 6.67%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1        | 6.67%   |
| Canon CanoScan LiDE 220                | 1        | 6.67%   |
| Canon CanoScan LiDE 200                | 1        | 6.67%   |
| Canon CanoScan LiDE 110                | 1        | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 262      | 45.02%  |
| Microdia                      | 44       | 7.56%   |
| Microsoft                     | 33       | 5.67%   |
| Sunplus Innovation Technology | 18       | 3.09%   |
| Generalplus Technology        | 17       | 2.92%   |
| ARC International             | 14       | 2.41%   |
| Apple                         | 14       | 2.41%   |
| Samsung Electronics           | 12       | 2.06%   |
| Realtek Semiconductor         | 12       | 2.06%   |
| Z-Star Microelectronics       | 10       | 1.72%   |
| Razer USA                     | 10       | 1.72%   |
| MacroSilicon                  | 10       | 1.72%   |
| Chicony Electronics           | 10       | 1.72%   |
| Valve Software                | 9        | 1.55%   |
| KYE Systems (Mouse Systems)   | 8        | 1.37%   |
| Jieli Technology              | 8        | 1.37%   |
| Cubeternet                    | 6        | 1.03%   |
| Creative Technology           | 6        | 1.03%   |
| AVerMedia Technologies        | 5        | 0.86%   |
| LG Electronics                | 4        | 0.69%   |
| Huawei Technologies           | 4        | 0.69%   |
| Hewlett-Packard               | 4        | 0.69%   |
| Aveo Technology               | 4        | 0.69%   |
| HD 2MP WEBCAM                 | 3        | 0.52%   |
| A4Tech                        | 3        | 0.52%   |
| WCM_USB                       | 2        | 0.34%   |
| Unknown                       | 2        | 0.34%   |
| Trust                         | 2        | 0.34%   |
| Sunplus IT                    | 2        | 0.34%   |
| Novatek Microelectronics      | 2        | 0.34%   |
| Intel                         | 2        | 0.34%   |
| HTC (High Tech Computer)      | 2        | 0.34%   |
| GenesysLogic Technology       | 2        | 0.34%   |
| Genesys Logic                 | 2        | 0.34%   |
| GEMBIRD                       | 2        | 0.34%   |
| Alcor Micro                   | 2        | 0.34%   |
| Acer                          | 2        | 0.34%   |
| YSD-2053--200409              | 1        | 0.17%   |
| YGTek                         | 1        | 0.17%   |
| Yealink Network Technology    | 1        | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920           | 60       | 10.29%  |
| Logitech Webcam C270                  | 52       | 8.92%   |
| Logitech C922 Pro Stream Webcam       | 22       | 3.77%   |
| Microdia Webcam Vitade AF             | 17       | 2.92%   |
| Logitech BRIO Ultra HD Webcam         | 14       | 2.4%    |
| ARC International Camera              | 14       | 2.4%    |
| Microsoft LifeCam HD-3000             | 13       | 2.23%   |
| Generalplus GENERAL WEBCAM            | 13       | 2.23%   |
| Apple iPhone5/5C/5S/6                 | 13       | 2.23%   |
| Samsung Galaxy A5 (MTP)               | 12       | 2.06%   |
| Logitech HD Webcam C525               | 12       | 2.06%   |
| Microdia USB 2.0 Camera               | 11       | 1.89%   |
| Logitech HD Webcam C615               | 11       | 1.89%   |
| Valve Software 3D Camera              | 9        | 1.54%   |
| Razer USA Gaming Webcam [Kiyo]        | 9        | 1.54%   |
| Logitech Webcam C310                  | 9        | 1.54%   |
| MacroSilicon USB Video                | 8        | 1.37%   |
| Logitech Webcam Pro 9000              | 8        | 1.37%   |
| Logitech Webcam C925e                 | 8        | 1.37%   |
| Jieli USB PHY 2.0                     | 8        | 1.37%   |
| Microsoft LifeCam Cinema              | 7        | 1.2%    |
| Logitech Webcam C930e                 | 7        | 1.2%    |
| Logitech Webcam C170                  | 7        | 1.2%    |
| Microdia Integrated Camera            | 6        | 1.03%   |
| Logitech StreamCam                    | 6        | 1.03%   |
| Logitech C920 PRO HD Webcam           | 6        | 1.03%   |
| Realtek Full HD webcam                | 5        | 0.86%   |
| Chicony HP High Definition 1MP Webcam | 5        | 0.86%   |
| AVerMedia Live Streamer CAM 313       | 5        | 0.86%   |
| Sunplus USB 2.0 Camera                | 4        | 0.69%   |
| Microdia Sonix USB 2.0 Camera         | 4        | 0.69%   |
| Logitech HD Webcam C910               | 4        | 0.69%   |
| Logitech HD Webcam C510               | 4        | 0.69%   |
| Huawei UVC Camera                     | 4        | 0.69%   |
| Z-Star Venus USB2.0 Camera            | 3        | 0.51%   |
| Sunplus SPCA2281 Web Camera           | 3        | 0.51%   |
| Microsoft MicrosoftÂ LifeCam Studio  | 3        | 0.51%   |
| Microsoft LifeCam VX-2000             | 3        | 0.51%   |
| Microdia Camera                       | 3        | 0.51%   |
| Logitech QuickCam Pro 9000            | 3        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Synaptics             | 2        | 33.33%  |
| Validity Sensors      | 1        | 16.67%  |
| Elan Microelectronics | 1        | 16.67%  |
| DigitalPersona        | 1        | 16.67%  |
| AuthenTec             | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052                | 2        | 33.33%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1        | 16.67%  |
| Elan fingerprint sensor [FeinTech FPS00200]                 | 1        | 16.67%  |
| DigitalPersona Fingerprint Reader                           | 1        | 16.67%  |
| AuthenTec Fingerprint Sensor                                | 1        | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 6        | 40%     |
| OmniKey               | 3        | 20%     |
| Realtek Semiconductor | 2        | 13.33%  |
| Alcor Micro           | 2        | 13.33%  |
| Chicony Electronics   | 1        | 6.67%   |
| Advanced Card Systems | 1        | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 4        | 26.67%  |
| Realtek Semiconductor Smart Card Reader Interface      | 2        | 13.33%  |
| OmniKey CardMan 3021 / 3121                            | 2        | 13.33%  |
| SCM Microsystems SCR3500 A Contact Reader              | 1        | 6.67%   |
| SCM Microsystems SCR331 SmartCard Reader               | 1        | 6.67%   |
| OmniKey CardMan 1021                                   | 1        | 6.67%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 1        | 6.67%   |
| Alcor Micro Watchdata W 1981                           | 1        | 6.67%   |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 6.67%   |
| Advanced Card Systems ACR1252 Dual Reader              | 1        | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2541     | 80.28%  |
| 1     | 558      | 17.63%  |
| 2     | 56       | 1.77%   |
| 3     | 7        | 0.22%   |
| 7     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |
| 4     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 253      | 37.21%  |
| Graphics card            | 236      | 34.71%  |
| Unassigned class         | 40       | 5.88%   |
| Sound                    | 22       | 3.24%   |
| Multimedia controller    | 19       | 2.79%   |
| Communication controller | 19       | 2.79%   |
| Bluetooth                | 19       | 2.79%   |
| Net/ethernet             | 13       | 1.91%   |
| Network                  | 12       | 1.76%   |
| Chipcard                 | 12       | 1.76%   |
| Storage/raid             | 11       | 1.62%   |
| Fingerprint reader       | 6        | 0.88%   |
| Camera                   | 6        | 0.88%   |
| Storage/ide              | 4        | 0.59%   |
| Card reader              | 4        | 0.59%   |
| Firewire controller      | 2        | 0.29%   |
| Storage/nvme             | 1        | 0.15%   |
| Dvb card                 | 1        | 0.15%   |

