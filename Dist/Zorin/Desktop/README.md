Zorin - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for Zorin.

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

Total: 2040

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | 970 Pro3 R2.0               | [592adc6c9b](https://linux-hardware.org/?probe=592adc6c9b) | Oct 01, 2022 |
| HP            | 843B                        | [b683039e3b](https://linux-hardware.org/?probe=b683039e3b) | Oct 01, 2022 |
| HP            | 1632                        | [0f9387690b](https://linux-hardware.org/?probe=0f9387690b) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| MSI           | Z97 MPOWER                  | [f16a15a5b7](https://linux-hardware.org/?probe=f16a15a5b7) | Sep 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8c116d30f9](https://linux-hardware.org/?probe=8c116d30f9) | Sep 30, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7bffcb84c2](https://linux-hardware.org/?probe=7bffcb84c2) | Sep 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [e3e6ad5c35](https://linux-hardware.org/?probe=e3e6ad5c35) | Sep 29, 2022 |
| HP            | 8055                        | [aa3bd09485](https://linux-hardware.org/?probe=aa3bd09485) | Sep 29, 2022 |
| HP            | 843C                        | [e27595d303](https://linux-hardware.org/?probe=e27595d303) | Sep 29, 2022 |
| ASUSTek       | P5K                         | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| ASUSTek       | B85M-E/BR                   | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Dell          | XPS 8700                    | [19fff8b508](https://linux-hardware.org/?probe=19fff8b508) | Sep 27, 2022 |
| Dell          | 0WN7Y6 A01                  | [356dc77824](https://linux-hardware.org/?probe=356dc77824) | Sep 27, 2022 |
| ASUSTek       | M3A78-EM                    | [34287ac52a](https://linux-hardware.org/?probe=34287ac52a) | Sep 27, 2022 |
| ASRock        | A75M-HVS                    | [75d51e6237](https://linux-hardware.org/?probe=75d51e6237) | Sep 26, 2022 |
| ASRock        | A75M-HVS                    | [fa3be9d376](https://linux-hardware.org/?probe=fa3be9d376) | Sep 25, 2022 |
| Gateway       | FMCP7AM                     | [0cb51f3e6f](https://linux-hardware.org/?probe=0cb51f3e6f) | Sep 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | [e760f06cef](https://linux-hardware.org/?probe=e760f06cef) | Sep 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | [33a0b663ea](https://linux-hardware.org/?probe=33a0b663ea) | Sep 25, 2022 |
| ASRock        | QC5000M-ITX/PH              | [571b95c201](https://linux-hardware.org/?probe=571b95c201) | Sep 25, 2022 |
| HP            | 18E7                        | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| ASRock        | B85M Pro4                   | [cd75d968d7](https://linux-hardware.org/?probe=cd75d968d7) | Sep 23, 2022 |
| ASUSTek       | P5K                         | [0ddf0a48dd](https://linux-hardware.org/?probe=0ddf0a48dd) | Sep 22, 2022 |
| Pegatron      | 2ACD                        | [d6270f88cc](https://linux-hardware.org/?probe=d6270f88cc) | Sep 22, 2022 |
| HP            | 8055                        | [c72e0ed04b](https://linux-hardware.org/?probe=c72e0ed04b) | Sep 22, 2022 |
| ASUSTek       | Benicia                     | [22bf75699c](https://linux-hardware.org/?probe=22bf75699c) | Sep 21, 2022 |
| ASRock        | A75M-HVS                    | [a2fb3b0ed7](https://linux-hardware.org/?probe=a2fb3b0ed7) | Sep 21, 2022 |
| ASRock        | A75M-HVS                    | [0f81852612](https://linux-hardware.org/?probe=0f81852612) | Sep 21, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [f49e8d08ef](https://linux-hardware.org/?probe=f49e8d08ef) | Sep 20, 2022 |
| Dell          | 0D441T A01                  | [c315329853](https://linux-hardware.org/?probe=c315329853) | Sep 20, 2022 |
| MSI           | MS-7260                     | [52d2fa8c71](https://linux-hardware.org/?probe=52d2fa8c71) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [493f68c9d6](https://linux-hardware.org/?probe=493f68c9d6) | Sep 19, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | [9022058466](https://linux-hardware.org/?probe=9022058466) | Sep 19, 2022 |
| HP            | 0AA8h                       | [c79bdb21ed](https://linux-hardware.org/?probe=c79bdb21ed) | Sep 18, 2022 |
| HP            | 0AA8h                       | [5e6f953759](https://linux-hardware.org/?probe=5e6f953759) | Sep 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a5d838868a](https://linux-hardware.org/?probe=a5d838868a) | Sep 18, 2022 |
| Lenovo        | ThinkCentre M58e 7298A76    | [4775ccd67f](https://linux-hardware.org/?probe=4775ccd67f) | Sep 18, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [875435f3f0](https://linux-hardware.org/?probe=875435f3f0) | Sep 15, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [3ff6899749](https://linux-hardware.org/?probe=3ff6899749) | Sep 15, 2022 |
| ASRock        | H61M-DGS                    | [aeac7cfb74](https://linux-hardware.org/?probe=aeac7cfb74) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
| Gigabyte      | Z77-D3H                     | [b1b929517d](https://linux-hardware.org/?probe=b1b929517d) | Sep 13, 2022 |
| ASUSTek       | PRIME Z270-A                | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| HP            | 0AA8h                       | [fc09b092c1](https://linux-hardware.org/?probe=fc09b092c1) | Sep 11, 2022 |
| Lenovo        | SDK0J40700 WIN              | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| Gigabyte      | G1.Sniper Z97               | [445e54016b](https://linux-hardware.org/?probe=445e54016b) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0701918099](https://linux-hardware.org/?probe=0701918099) | Sep 11, 2022 |
| ECS           | Iris8                       | [dcfb9e172d](https://linux-hardware.org/?probe=dcfb9e172d) | Sep 11, 2022 |
| HP            | 0A54h                       | [2c88c7fd30](https://linux-hardware.org/?probe=2c88c7fd30) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e43753d7a](https://linux-hardware.org/?probe=1e43753d7a) | Sep 10, 2022 |
| MSI           | 2AE0                        | [a2b046dd4e](https://linux-hardware.org/?probe=a2b046dd4e) | Sep 10, 2022 |
| MSI           | 2AE0                        | [df247fd9d0](https://linux-hardware.org/?probe=df247fd9d0) | Sep 10, 2022 |
| HP            | 3031h                       | [ea434d67b5](https://linux-hardware.org/?probe=ea434d67b5) | Sep 10, 2022 |
| HP            | 3031h                       | [feddf42c9f](https://linux-hardware.org/?probe=feddf42c9f) | Sep 10, 2022 |
| ECS           | Iris8                       | [29bc0560b4](https://linux-hardware.org/?probe=29bc0560b4) | Sep 10, 2022 |
| HP            | 0AA8h                       | [4e9a1e883c](https://linux-hardware.org/?probe=4e9a1e883c) | Sep 09, 2022 |
| Lenovo        | MAHOBAY                     | [2619e261d1](https://linux-hardware.org/?probe=2619e261d1) | Sep 07, 2022 |
| Intel         | SKYBAY                      | [b667cf66e8](https://linux-hardware.org/?probe=b667cf66e8) | Sep 07, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [dd20f0351c](https://linux-hardware.org/?probe=dd20f0351c) | Sep 06, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [3aca46f88b](https://linux-hardware.org/?probe=3aca46f88b) | Sep 06, 2022 |
| ASUSTek       | A88X-GAMER                  | [15fe45edd7](https://linux-hardware.org/?probe=15fe45edd7) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [92ff48d462](https://linux-hardware.org/?probe=92ff48d462) | Sep 06, 2022 |
| HP            | 2AF7                        | [9b7ccd5aa0](https://linux-hardware.org/?probe=9b7ccd5aa0) | Sep 06, 2022 |
| Dell          | 0HY9JP A02                  | [7cbf141461](https://linux-hardware.org/?probe=7cbf141461) | Sep 05, 2022 |
| ASRock        | B550M/ac                    | [b8ccaa27ef](https://linux-hardware.org/?probe=b8ccaa27ef) | Sep 04, 2022 |
| HP            | 821D                        | [459bdd177e](https://linux-hardware.org/?probe=459bdd177e) | Sep 03, 2022 |
| ASUSTek       | P8B75-V                     | [2ae6d7c950](https://linux-hardware.org/?probe=2ae6d7c950) | Sep 03, 2022 |
| HP            | 87D6 SMVB                   | [e597d54472](https://linux-hardware.org/?probe=e597d54472) | Sep 03, 2022 |
| MSI           | H97 GAMING 3                | [a5fb8d7651](https://linux-hardware.org/?probe=a5fb8d7651) | Sep 02, 2022 |
| ASRock        | H61M-DGS                    | [8b36704183](https://linux-hardware.org/?probe=8b36704183) | Sep 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | [63e2adf3a9](https://linux-hardware.org/?probe=63e2adf3a9) | Sep 02, 2022 |
| MSI           | MS-B9201                    | [7bbae05d63](https://linux-hardware.org/?probe=7bbae05d63) | Sep 01, 2022 |
| MSI           | MS-B9201                    | [0d04798699](https://linux-hardware.org/?probe=0d04798699) | Sep 01, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [f4d5b9fc69](https://linux-hardware.org/?probe=f4d5b9fc69) | Aug 31, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [82cda7dfe9](https://linux-hardware.org/?probe=82cda7dfe9) | Aug 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [194290f42c](https://linux-hardware.org/?probe=194290f42c) | Aug 31, 2022 |
| MSI           | H410M PRO                   | [e1184c4522](https://linux-hardware.org/?probe=e1184c4522) | Aug 31, 2022 |
| ASUSTek       | Benicia                     | [13454a57f9](https://linux-hardware.org/?probe=13454a57f9) | Aug 31, 2022 |
| Dell          | 0GXM1W A00                  | [b358b1d32b](https://linux-hardware.org/?probe=b358b1d32b) | Aug 31, 2022 |
| HP            | 2B38                        | [9170225d70](https://linux-hardware.org/?probe=9170225d70) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [8712171422](https://linux-hardware.org/?probe=8712171422) | Aug 30, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [eb74fdbbbc](https://linux-hardware.org/?probe=eb74fdbbbc) | Aug 30, 2022 |
| Dell          | 0R092H                      | [85871600b3](https://linux-hardware.org/?probe=85871600b3) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [f065870080](https://linux-hardware.org/?probe=f065870080) | Aug 30, 2022 |
| MSI           | B250M PRO-VD                | [d462e3b9d0](https://linux-hardware.org/?probe=d462e3b9d0) | Aug 29, 2022 |
| ASRock        | Z170 Pro4                   | [eaa574481f](https://linux-hardware.org/?probe=eaa574481f) | Aug 29, 2022 |
| HP            | 339A                        | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| ASRock        | H61M-DGS                    | [023204fa1f](https://linux-hardware.org/?probe=023204fa1f) | Aug 28, 2022 |
| WIPRO         | G31T-M                      | [51cea718eb](https://linux-hardware.org/?probe=51cea718eb) | Aug 28, 2022 |
| BESSTAR Te... | HM90                        | [134adccc85](https://linux-hardware.org/?probe=134adccc85) | Aug 27, 2022 |
| ASRock        | B550M Pro4                  | [9a05044c38](https://linux-hardware.org/?probe=9a05044c38) | Aug 27, 2022 |
| Dell          | 0T656F A01                  | [d1bb410d06](https://linux-hardware.org/?probe=d1bb410d06) | Aug 26, 2022 |
| ASUSTek       | SABERTOOTH Z87              | [02072aee33](https://linux-hardware.org/?probe=02072aee33) | Aug 25, 2022 |
| Gigabyte      | 970-GAMING                  | [dad1ede2be](https://linux-hardware.org/?probe=dad1ede2be) | Aug 25, 2022 |
| BESSTAR Te... | HM90                        | [8f13ff6ebd](https://linux-hardware.org/?probe=8f13ff6ebd) | Aug 24, 2022 |
| Gigabyte      | 970-GAMING                  | [faa79b7d62](https://linux-hardware.org/?probe=faa79b7d62) | Aug 24, 2022 |
| HP            | 2AFB                        | [ea3ce3f8dd](https://linux-hardware.org/?probe=ea3ce3f8dd) | Aug 24, 2022 |
| ASUSTek       | H81M-A/BR                   | [b9ac5d4051](https://linux-hardware.org/?probe=b9ac5d4051) | Aug 23, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [eae2c82e26](https://linux-hardware.org/?probe=eae2c82e26) | Aug 23, 2022 |
| MSI           | 2AE0                        | [beb918fbc9](https://linux-hardware.org/?probe=beb918fbc9) | Aug 23, 2022 |
| HP            | 2AF7                        | [29826a67d9](https://linux-hardware.org/?probe=29826a67d9) | Aug 22, 2022 |
| HP            | 2AF7                        | [fbc1710ad8](https://linux-hardware.org/?probe=fbc1710ad8) | Aug 22, 2022 |
| MSI           | X99S GAMING 7               | [f729654c4a](https://linux-hardware.org/?probe=f729654c4a) | Aug 22, 2022 |
| ASUSTek       | J1800I-C/BR                 | [f2f76737ad](https://linux-hardware.org/?probe=f2f76737ad) | Aug 22, 2022 |
| Dell          | 0C27VV A03                  | [4e894e1897](https://linux-hardware.org/?probe=4e894e1897) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4dc3a452d9](https://linux-hardware.org/?probe=4dc3a452d9) | Aug 19, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | [0b9e6d6ad9](https://linux-hardware.org/?probe=0b9e6d6ad9) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [6865f5ed0b](https://linux-hardware.org/?probe=6865f5ed0b) | Aug 19, 2022 |
| BESSTAR Te... | UM350                       | [c7bb6b56fb](https://linux-hardware.org/?probe=c7bb6b56fb) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | [e03daeba5f](https://linux-hardware.org/?probe=e03daeba5f) | Aug 18, 2022 |
| ASRock        | H61M-DGS                    | [ffb9dcb065](https://linux-hardware.org/?probe=ffb9dcb065) | Aug 18, 2022 |
| ASUSTek       | P8B75-V                     | [a37b0b7e18](https://linux-hardware.org/?probe=a37b0b7e18) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| ASUSTek       | PRIME H370-A                | [da477254e7](https://linux-hardware.org/?probe=da477254e7) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| ASUSTek       | J1800I-C/BR                 | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| HP            | 339A                        | [c3e5458c9a](https://linux-hardware.org/?probe=c3e5458c9a) | Aug 15, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [08fa90340d](https://linux-hardware.org/?probe=08fa90340d) | Aug 14, 2022 |
| MAXSUN        | MS-TZZ A520M                | [aa844d0dce](https://linux-hardware.org/?probe=aa844d0dce) | Aug 14, 2022 |
| Gigabyte      | 970A-DS3P                   | [47632d043c](https://linux-hardware.org/?probe=47632d043c) | Aug 14, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [58d97fbc16](https://linux-hardware.org/?probe=58d97fbc16) | Aug 14, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [0c80c167e4](https://linux-hardware.org/?probe=0c80c167e4) | Aug 13, 2022 |
| ASUSTek       | A88X-PRO                    | [399f7ec1da](https://linux-hardware.org/?probe=399f7ec1da) | Aug 12, 2022 |
| ASUSTek       | P5GC-MX                     | [346a48750b](https://linux-hardware.org/?probe=346a48750b) | Aug 12, 2022 |
| ASUSTek       | J1800I-C/BR                 | [41cd4b02f1](https://linux-hardware.org/?probe=41cd4b02f1) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [687375ec7c](https://linux-hardware.org/?probe=687375ec7c) | Aug 11, 2022 |
| ASRock        | H61M-DGS                    | [7005dd1f5f](https://linux-hardware.org/?probe=7005dd1f5f) | Aug 09, 2022 |
| HP            | 1589                        | [0519e046d2](https://linux-hardware.org/?probe=0519e046d2) | Aug 08, 2022 |
| HP            | 18E7                        | [7dd119f85e](https://linux-hardware.org/?probe=7dd119f85e) | Aug 08, 2022 |
| MSI           | Z97 GAMING 5                | [7f1e38b57b](https://linux-hardware.org/?probe=7f1e38b57b) | Aug 07, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [ab0da3a7ec](https://linux-hardware.org/?probe=ab0da3a7ec) | Aug 07, 2022 |
| ASUSTek       | P9X79 LE                    | [f8a36826db](https://linux-hardware.org/?probe=f8a36826db) | Aug 07, 2022 |
| ASUSTek       | ET2701I-W8                  | [5f9c4b50db](https://linux-hardware.org/?probe=5f9c4b50db) | Aug 07, 2022 |
| MP            | MS-7848                     | [8d4402905d](https://linux-hardware.org/?probe=8d4402905d) | Aug 06, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Pegatron      | Benicia                     | [d67d37efce](https://linux-hardware.org/?probe=d67d37efce) | Aug 05, 2022 |
| HP            | 339A                        | [53a3b6e834](https://linux-hardware.org/?probe=53a3b6e834) | Aug 05, 2022 |
| HP            | 339A                        | [8883c2cb6c](https://linux-hardware.org/?probe=8883c2cb6c) | Aug 05, 2022 |
| Gigabyte      | Z77-D3H                     | [2fd7410925](https://linux-hardware.org/?probe=2fd7410925) | Aug 04, 2022 |
| Gigabyte      | G1.Sniper Z97               | [6e5ce364b3](https://linux-hardware.org/?probe=6e5ce364b3) | Aug 03, 2022 |
| LORD ELECT... | GM965 Series                | [b60dce21e7](https://linux-hardware.org/?probe=b60dce21e7) | Aug 03, 2022 |
| Lenovo        | SDK0J40700 WIN              | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| HP            | 1589                        | [738de77596](https://linux-hardware.org/?probe=738de77596) | Aug 03, 2022 |
| MSI           | Boston                      | [32021cecf7](https://linux-hardware.org/?probe=32021cecf7) | Aug 03, 2022 |
| ASUSTek       | P7H55-M LX                  | [ad8af5c718](https://linux-hardware.org/?probe=ad8af5c718) | Aug 02, 2022 |
| ASUSTek       | P7H55-M LX                  | [b4e172e88b](https://linux-hardware.org/?probe=b4e172e88b) | Aug 02, 2022 |
| ASRock        | B450 Pro4                   | [aacc138812](https://linux-hardware.org/?probe=aacc138812) | Aug 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [cc8b9aa8f6](https://linux-hardware.org/?probe=cc8b9aa8f6) | Aug 01, 2022 |
| ASUSTek       | PRIME X570-P                | [405a75cb1d](https://linux-hardware.org/?probe=405a75cb1d) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [7c68dbe47e](https://linux-hardware.org/?probe=7c68dbe47e) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6532751d00](https://linux-hardware.org/?probe=6532751d00) | Aug 01, 2022 |
| Dell          | 0T656F A01                  | [02ae993867](https://linux-hardware.org/?probe=02ae993867) | Jul 31, 2022 |
| Gigabyte      | Z77-D3H                     | [a954bc2f31](https://linux-hardware.org/?probe=a954bc2f31) | Jul 31, 2022 |
| ASRock        | Z170 Pro4                   | [e8dba6ab7e](https://linux-hardware.org/?probe=e8dba6ab7e) | Jul 31, 2022 |
| HP            | 82F2                        | [0c2d091c2e](https://linux-hardware.org/?probe=0c2d091c2e) | Jul 31, 2022 |
| Supermicro    | C7Q67 V1.01                 | [15508d1eff](https://linux-hardware.org/?probe=15508d1eff) | Jul 30, 2022 |
| Lenovo        | SDK0J40700 WIN              | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [2bc22894c8](https://linux-hardware.org/?probe=2bc22894c8) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| ASRock        | Z170 Pro4                   | [73c8bc2ae1](https://linux-hardware.org/?probe=73c8bc2ae1) | Jul 28, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [e214df8838](https://linux-hardware.org/?probe=e214df8838) | Jul 27, 2022 |
| Gigabyte      | B450 AORUS M                | [f9b0fe48d6](https://linux-hardware.org/?probe=f9b0fe48d6) | Jul 27, 2022 |
| ASUSTek       | PRIME A520M-K               | [cea12b9c9c](https://linux-hardware.org/?probe=cea12b9c9c) | Jul 27, 2022 |
| ASRock        | Z170 Pro4                   | [876c60188f](https://linux-hardware.org/?probe=876c60188f) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e33f8c0a93](https://linux-hardware.org/?probe=e33f8c0a93) | Jul 26, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a059cf305d](https://linux-hardware.org/?probe=a059cf305d) | Jul 25, 2022 |
| Lenovo        | SDK0J40700 WIN              | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| ASUSTek       | A88X-PRO                    | [c8e578f98f](https://linux-hardware.org/?probe=c8e578f98f) | Jul 24, 2022 |
| ASUSTek       | A88X-PRO                    | [48e39039fc](https://linux-hardware.org/?probe=48e39039fc) | Jul 24, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [aa952e11aa](https://linux-hardware.org/?probe=aa952e11aa) | Jul 24, 2022 |
| Dell          | 03NVJ6 A03                  | [9c0bb64bd9](https://linux-hardware.org/?probe=9c0bb64bd9) | Jul 24, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [aa2242c51f](https://linux-hardware.org/?probe=aa2242c51f) | Jul 23, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [177a181771](https://linux-hardware.org/?probe=177a181771) | Jul 23, 2022 |
| Supermicro    | C7Q67 V1.01                 | [722f3df811](https://linux-hardware.org/?probe=722f3df811) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | [f5d81fb635](https://linux-hardware.org/?probe=f5d81fb635) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | [83cf5f7085](https://linux-hardware.org/?probe=83cf5f7085) | Jul 23, 2022 |
| Gigabyte      | M68M-S2P                    | [7d4ba4168a](https://linux-hardware.org/?probe=7d4ba4168a) | Jul 22, 2022 |
| MSI           | Z97 GAMING 5                | [89e0889e94](https://linux-hardware.org/?probe=89e0889e94) | Jul 21, 2022 |
| Dell          | 09KPNV A00                  | [711546ab63](https://linux-hardware.org/?probe=711546ab63) | Jul 21, 2022 |
| Foxconn       | 2AAF                        | [b97dc9fd47](https://linux-hardware.org/?probe=b97dc9fd47) | Jul 20, 2022 |
| MSI           | B75MA-P45                   | [89af63cf6f](https://linux-hardware.org/?probe=89af63cf6f) | Jul 19, 2022 |
| Gigabyte      | G1.Sniper Z97               | [75a19b4509](https://linux-hardware.org/?probe=75a19b4509) | Jul 17, 2022 |
| Dell          | 09KPNV A00                  | [c47ecbd03f](https://linux-hardware.org/?probe=c47ecbd03f) | Jul 16, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [0cf64c41f0](https://linux-hardware.org/?probe=0cf64c41f0) | Jul 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [e5fed36e22](https://linux-hardware.org/?probe=e5fed36e22) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | [56bd2a162b](https://linux-hardware.org/?probe=56bd2a162b) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | [ccc3bc2a39](https://linux-hardware.org/?probe=ccc3bc2a39) | Jul 15, 2022 |
| Intel         | X79 V2.72B                  | [f244f6157b](https://linux-hardware.org/?probe=f244f6157b) | Jul 15, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [66efd060ca](https://linux-hardware.org/?probe=66efd060ca) | Jul 14, 2022 |
| Unknown       | Intel X79                   | [b0bb64b9ea](https://linux-hardware.org/?probe=b0bb64b9ea) | Jul 13, 2022 |
| Gigabyte      | H87M-D3H                    | [5056c4f640](https://linux-hardware.org/?probe=5056c4f640) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [c90a0cbab7](https://linux-hardware.org/?probe=c90a0cbab7) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [87fa08ea59](https://linux-hardware.org/?probe=87fa08ea59) | Jul 13, 2022 |
| System76      | Thelio thelio-r2            | [2d990d7afe](https://linux-hardware.org/?probe=2d990d7afe) | Jul 12, 2022 |
| HP            | 3398                        | [1b964004d9](https://linux-hardware.org/?probe=1b964004d9) | Jul 12, 2022 |
| ASUSTek       | V-P8H61E                    | [f8e5b72d1c](https://linux-hardware.org/?probe=f8e5b72d1c) | Jul 12, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [42b248f049](https://linux-hardware.org/?probe=42b248f049) | Jul 11, 2022 |
| Lenovo        | ThinkCentre M91 7516AD1     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| OEM_MB        | NARRA3                      | [845bdfd72c](https://linux-hardware.org/?probe=845bdfd72c) | Jul 11, 2022 |
| Dell          | 0J3C2F A00                  | [36252f70d6](https://linux-hardware.org/?probe=36252f70d6) | Jul 10, 2022 |
| Dell          | 0J3C2F A00                  | [e3197762a9](https://linux-hardware.org/?probe=e3197762a9) | Jul 10, 2022 |
| Pegatron      | Benicia                     | [2360476ad3](https://linux-hardware.org/?probe=2360476ad3) | Jul 09, 2022 |
| Gigabyte      | H110M-A-CF                  | [42335e5c5c](https://linux-hardware.org/?probe=42335e5c5c) | Jul 09, 2022 |
| HP            | 18E4                        | [bf615fe0ae](https://linux-hardware.org/?probe=bf615fe0ae) | Jul 08, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | [b7ed1ecdf2](https://linux-hardware.org/?probe=b7ed1ecdf2) | Jul 08, 2022 |
| Gigabyte      | EP45-UD3P                   | [9118f548bb](https://linux-hardware.org/?probe=9118f548bb) | Jul 08, 2022 |
| Lenovo        | 3098 0B98401 PRO            | [830b5c1c8d](https://linux-hardware.org/?probe=830b5c1c8d) | Jul 07, 2022 |
| Acer          | E91M                        | [4e55aacdd7](https://linux-hardware.org/?probe=4e55aacdd7) | Jul 06, 2022 |
| MSI           | Boston                      | [3dfcd01115](https://linux-hardware.org/?probe=3dfcd01115) | Jul 06, 2022 |
| Gigabyte      | H77N-WIFI                   | [dc12f11117](https://linux-hardware.org/?probe=dc12f11117) | Jul 05, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [0567d5e337](https://linux-hardware.org/?probe=0567d5e337) | Jul 05, 2022 |
| OEM           | G41 775 ICH7 8712           | [4f82c838cb](https://linux-hardware.org/?probe=4f82c838cb) | Jul 04, 2022 |
| ASUSTek       | M3A78-EM                    | [426bb60e88](https://linux-hardware.org/?probe=426bb60e88) | Jul 04, 2022 |
| HP            | 8350                        | [39a8a75ebe](https://linux-hardware.org/?probe=39a8a75ebe) | Jul 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [31a8bd72d6](https://linux-hardware.org/?probe=31a8bd72d6) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | [83a3a5794d](https://linux-hardware.org/?probe=83a3a5794d) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | [7b7c8244af](https://linux-hardware.org/?probe=7b7c8244af) | Jul 02, 2022 |
| Gigabyte      | EP45-DS3                    | [bc316ca4cb](https://linux-hardware.org/?probe=bc316ca4cb) | Jul 02, 2022 |
| Dell          | 0HJ054                      | [bb9d7a3a58](https://linux-hardware.org/?probe=bb9d7a3a58) | Jun 30, 2022 |
| Gigabyte      | B360M HD3                   | [b35e9f3e5c](https://linux-hardware.org/?probe=b35e9f3e5c) | Jun 28, 2022 |
| Lenovo        | 3098 0B98401 PRO            | [9923c241d9](https://linux-hardware.org/?probe=9923c241d9) | Jun 27, 2022 |
| Dell          | 0U880P A00                  | [e14832f09c](https://linux-hardware.org/?probe=e14832f09c) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [6262e08c1f](https://linux-hardware.org/?probe=6262e08c1f) | Jun 26, 2022 |
| Pegatron      | IPPSB-DB                    | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| Dell          | 08NPPY A00                  | [3dc935ecb1](https://linux-hardware.org/?probe=3dc935ecb1) | Jun 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c78b132d02](https://linux-hardware.org/?probe=c78b132d02) | Jun 26, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [b232a434fd](https://linux-hardware.org/?probe=b232a434fd) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [0297d9c8c1](https://linux-hardware.org/?probe=0297d9c8c1) | Jun 25, 2022 |
| Gigabyte      | Z77-DS3H                    | [fbde5d214f](https://linux-hardware.org/?probe=fbde5d214f) | Jun 24, 2022 |
| Gigabyte      | EP45-UD3P                   | [05449d9e5c](https://linux-hardware.org/?probe=05449d9e5c) | Jun 24, 2022 |
| MSI           | A75A-G35                    | [9e3dd8051c](https://linux-hardware.org/?probe=9e3dd8051c) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [a24305d670](https://linux-hardware.org/?probe=a24305d670) | Jun 23, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [b21a0caebf](https://linux-hardware.org/?probe=b21a0caebf) | Jun 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ecea2bb4ad](https://linux-hardware.org/?probe=ecea2bb4ad) | Jun 22, 2022 |
| Gigabyte      | EX58-UD3R                   | [4014366c8a](https://linux-hardware.org/?probe=4014366c8a) | Jun 21, 2022 |
| Lenovo        | SDK0J40700 WIN              | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| MSI           | B85M-E45                    | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [85a022001e](https://linux-hardware.org/?probe=85a022001e) | Jun 16, 2022 |
| Dell          | 0X501H A02                  | [b9cb2a1e48](https://linux-hardware.org/?probe=b9cb2a1e48) | Jun 15, 2022 |
| Acer          | Aspire M3970                | [b966120966](https://linux-hardware.org/?probe=b966120966) | Jun 14, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [aa63e13a60](https://linux-hardware.org/?probe=aa63e13a60) | Jun 13, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [ba6786bbe8](https://linux-hardware.org/?probe=ba6786bbe8) | Jun 13, 2022 |
| ASUSTek       | P5GC-MX/1333                | [428eebd42f](https://linux-hardware.org/?probe=428eebd42f) | Jun 13, 2022 |
| MSI           | MEG Z690 UNIFY              | [4e227cff8b](https://linux-hardware.org/?probe=4e227cff8b) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2a772cecf4](https://linux-hardware.org/?probe=2a772cecf4) | Jun 12, 2022 |
| Foxconn       | Irvine HP P/N               | [551f18d133](https://linux-hardware.org/?probe=551f18d133) | Jun 11, 2022 |
| ASUSTek       | PRIME B550M-A               | [14b9e721b7](https://linux-hardware.org/?probe=14b9e721b7) | Jun 11, 2022 |
| Dell          | 0XFWHV A00                  | [4102e98034](https://linux-hardware.org/?probe=4102e98034) | Jun 09, 2022 |
| ASUSTek       | Benicia                     | [4b56f8a972](https://linux-hardware.org/?probe=4b56f8a972) | Jun 08, 2022 |
| Dell          | 0WR7PY A03                  | [902546cb45](https://linux-hardware.org/?probe=902546cb45) | Jun 06, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [e993e32a56](https://linux-hardware.org/?probe=e993e32a56) | Jun 06, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [07808a7cbf](https://linux-hardware.org/?probe=07808a7cbf) | Jun 05, 2022 |
| HP            | 8350                        | [63a9e40af6](https://linux-hardware.org/?probe=63a9e40af6) | Jun 05, 2022 |
| Biostar       | A68N-2100K                  | [480a4c12b1](https://linux-hardware.org/?probe=480a4c12b1) | Jun 05, 2022 |
| ASRock        | 970 Extreme3                | [d5648a1a95](https://linux-hardware.org/?probe=d5648a1a95) | Jun 04, 2022 |
| MSI           | B85M-G43                    | [097b308b60](https://linux-hardware.org/?probe=097b308b60) | Jun 04, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [94c2c3411a](https://linux-hardware.org/?probe=94c2c3411a) | Jun 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9404638832](https://linux-hardware.org/?probe=9404638832) | Jun 03, 2022 |
| BESSTAR Te... | TL50                        | [0455aba8a3](https://linux-hardware.org/?probe=0455aba8a3) | Jun 03, 2022 |
| HP            | 3029h                       | [d536fb8e36](https://linux-hardware.org/?probe=d536fb8e36) | Jun 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [61b90c102c](https://linux-hardware.org/?probe=61b90c102c) | Jun 03, 2022 |
| ASUSTek       | P5E-VM DO                   | [935c03cd63](https://linux-hardware.org/?probe=935c03cd63) | Jun 03, 2022 |
| Biostar       | A78MD                       | [206b04b6d8](https://linux-hardware.org/?probe=206b04b6d8) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [5c9f7b1ab9](https://linux-hardware.org/?probe=5c9f7b1ab9) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [0e1e2765fc](https://linux-hardware.org/?probe=0e1e2765fc) | Jun 01, 2022 |
| Biostar       | A78MD                       | [49ea0bd0e4](https://linux-hardware.org/?probe=49ea0bd0e4) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [951bd2ea8d](https://linux-hardware.org/?probe=951bd2ea8d) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [7bfeaeb75b](https://linux-hardware.org/?probe=7bfeaeb75b) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [3ca7484fcf](https://linux-hardware.org/?probe=3ca7484fcf) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [d078b8d5dd](https://linux-hardware.org/?probe=d078b8d5dd) | May 30, 2022 |
| Gigabyte      | H410M H V3                  | [1dbf357f4f](https://linux-hardware.org/?probe=1dbf357f4f) | May 30, 2022 |
| MSI           | Z97 XPOWER AC               | [dd5c7a981a](https://linux-hardware.org/?probe=dd5c7a981a) | May 29, 2022 |
| Gigabyte      | G1.Sniper Z97               | [2c3ba3123f](https://linux-hardware.org/?probe=2c3ba3123f) | May 29, 2022 |
| ASUSTek       | P7P55D DELUXE               | [ba2d55d308](https://linux-hardware.org/?probe=ba2d55d308) | May 29, 2022 |
| ASRock        | B450 Pro4                   | [fa0b4c98df](https://linux-hardware.org/?probe=fa0b4c98df) | May 29, 2022 |
| Dell          | 0HN7XN A01                  | [9ebd09a280](https://linux-hardware.org/?probe=9ebd09a280) | May 29, 2022 |
| Gigabyte      | F2A58M-DS2                  | [3b95da87e9](https://linux-hardware.org/?probe=3b95da87e9) | May 28, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [4e77d22694](https://linux-hardware.org/?probe=4e77d22694) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [1137f80fcd](https://linux-hardware.org/?probe=1137f80fcd) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [57dbc86807](https://linux-hardware.org/?probe=57dbc86807) | May 27, 2022 |
| ASUSTek       | H81M-A/BR                   | [5df43d2ecd](https://linux-hardware.org/?probe=5df43d2ecd) | May 26, 2022 |
| Dell          | 088DT1 A01                  | [19d760099e](https://linux-hardware.org/?probe=19d760099e) | May 25, 2022 |
| Dell          | 088DT1 A01                  | [3334efe1e7](https://linux-hardware.org/?probe=3334efe1e7) | May 25, 2022 |
| Intel         | D946GZIS AAD66165-301       | [24c058da74](https://linux-hardware.org/?probe=24c058da74) | May 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | [293f5586bd](https://linux-hardware.org/?probe=293f5586bd) | May 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [6e45ae9f7c](https://linux-hardware.org/?probe=6e45ae9f7c) | May 24, 2022 |
| MSI           | MEG Z390 GODLIKE            | [4249d49f41](https://linux-hardware.org/?probe=4249d49f41) | May 22, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [dffc3ea80a](https://linux-hardware.org/?probe=dffc3ea80a) | May 21, 2022 |
| ASUSTek       | Z97-DELUXE                  | [084bacdad3](https://linux-hardware.org/?probe=084bacdad3) | May 21, 2022 |
| MSI           | Z170A GAMING PRO            | [3a9789ed8a](https://linux-hardware.org/?probe=3a9789ed8a) | May 20, 2022 |
| ASUSTek       | PRIME B550M-A               | [1d5fec86a8](https://linux-hardware.org/?probe=1d5fec86a8) | May 20, 2022 |
| MSI           | 760GM-P21                   | [b6b5e0738c](https://linux-hardware.org/?probe=b6b5e0738c) | May 19, 2022 |
| MSI           | B85M-G43                    | [ef33bf347c](https://linux-hardware.org/?probe=ef33bf347c) | May 18, 2022 |
| Foxconn       | 2AAF                        | [dd1193f7ab](https://linux-hardware.org/?probe=dd1193f7ab) | May 18, 2022 |
| ASUSTek       | H81M-K                      | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [2b889fc85b](https://linux-hardware.org/?probe=2b889fc85b) | May 17, 2022 |
| ASUSTek       | G15DK                       | [1df44e40e2](https://linux-hardware.org/?probe=1df44e40e2) | May 17, 2022 |
| Dell          | 08HPGT A01                  | [aa8b5a4aec](https://linux-hardware.org/?probe=aa8b5a4aec) | May 17, 2022 |
| Gigabyte      | M61PME-S2P                  | [7ab57b617f](https://linux-hardware.org/?probe=7ab57b617f) | May 17, 2022 |
| Dell          | 08HPGT A01                  | [4b277b05bb](https://linux-hardware.org/?probe=4b277b05bb) | May 17, 2022 |
| HP            | 2ADE                        | [77c2ea750b](https://linux-hardware.org/?probe=77c2ea750b) | May 17, 2022 |
| Dell          | 0C27VV A01                  | [aea8e14bff](https://linux-hardware.org/?probe=aea8e14bff) | May 17, 2022 |
| Dell          | 0GTK4K A02                  | [fba6de28d9](https://linux-hardware.org/?probe=fba6de28d9) | May 16, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [ebbd363703](https://linux-hardware.org/?probe=ebbd363703) | May 16, 2022 |
| Intel         | D946GZIS AAD66165-301       | [4555cff448](https://linux-hardware.org/?probe=4555cff448) | May 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [7fcd8503ab](https://linux-hardware.org/?probe=7fcd8503ab) | May 16, 2022 |
| ASRock        | A88M-G                      | [81d094b2ec](https://linux-hardware.org/?probe=81d094b2ec) | May 15, 2022 |
| ASRock        | A88M-G                      | [8883591354](https://linux-hardware.org/?probe=8883591354) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0d9d6b919b](https://linux-hardware.org/?probe=0d9d6b919b) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [770fbfefd3](https://linux-hardware.org/?probe=770fbfefd3) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [8baee6f2e6](https://linux-hardware.org/?probe=8baee6f2e6) | May 14, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [08ba1e652c](https://linux-hardware.org/?probe=08ba1e652c) | May 14, 2022 |
| MSI           | MS-7260                     | [835ab9042d](https://linux-hardware.org/?probe=835ab9042d) | May 13, 2022 |
| Intel         | DH77EB AAG39073-304         | [f45bf21321](https://linux-hardware.org/?probe=f45bf21321) | May 12, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [86d60d0227](https://linux-hardware.org/?probe=86d60d0227) | May 12, 2022 |
| Pegatron      | 2A99h                       | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| AOpen         | i67QMx-DV R1.00BC1 55MP6... | [151db99970](https://linux-hardware.org/?probe=151db99970) | May 11, 2022 |
| Acer          | Aspire X3990                | [c6753ff37f](https://linux-hardware.org/?probe=c6753ff37f) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [8f62053ddd](https://linux-hardware.org/?probe=8f62053ddd) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [018c90008f](https://linux-hardware.org/?probe=018c90008f) | May 11, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [b1d977cd69](https://linux-hardware.org/?probe=b1d977cd69) | May 11, 2022 |
| Gigabyte      | EX58-EXTREME                | [b558000bcc](https://linux-hardware.org/?probe=b558000bcc) | May 10, 2022 |
| Dell          | 0DR845                      | [ab501b0efe](https://linux-hardware.org/?probe=ab501b0efe) | May 10, 2022 |
| Gigabyte      | X58A-UD3R                   | [838a99f17a](https://linux-hardware.org/?probe=838a99f17a) | May 10, 2022 |
| Gigabyte      | B365M GAMING HD             | [5590d9a0f3](https://linux-hardware.org/?probe=5590d9a0f3) | May 10, 2022 |
| Foxconn       | LIMA                        | [fc4662a00e](https://linux-hardware.org/?probe=fc4662a00e) | May 09, 2022 |
| Dell          | 0GXM1W A02                  | [1606b44e03](https://linux-hardware.org/?probe=1606b44e03) | May 09, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [485a4916ed](https://linux-hardware.org/?probe=485a4916ed) | May 09, 2022 |
| ASRock        | H87M                        | [9c031f1e71](https://linux-hardware.org/?probe=9c031f1e71) | May 09, 2022 |
| Dell          | 0GXM1W A02                  | [bf028580b1](https://linux-hardware.org/?probe=bf028580b1) | May 09, 2022 |
| Gateway       | SX2185                      | [ddb64bc283](https://linux-hardware.org/?probe=ddb64bc283) | May 09, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [be0cecd40a](https://linux-hardware.org/?probe=be0cecd40a) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [9a00d24f58](https://linux-hardware.org/?probe=9a00d24f58) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [3f3089216f](https://linux-hardware.org/?probe=3f3089216f) | May 09, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [5c2fec5833](https://linux-hardware.org/?probe=5c2fec5833) | May 08, 2022 |
| Gigabyte      | H410M H V3                  | [c401229392](https://linux-hardware.org/?probe=c401229392) | May 08, 2022 |
| Gigabyte      | X570 GAMING X               | [ffc6dac164](https://linux-hardware.org/?probe=ffc6dac164) | May 07, 2022 |
| Gigabyte      | H410M H V3                  | [4c6f4d04bb](https://linux-hardware.org/?probe=4c6f4d04bb) | May 07, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [79c87fe48c](https://linux-hardware.org/?probe=79c87fe48c) | May 07, 2022 |
| Gigabyte      | X570 GAMING X               | [816a78b4cd](https://linux-hardware.org/?probe=816a78b4cd) | May 06, 2022 |
| ASUSTek       | 2A73h                       | [458bf998ee](https://linux-hardware.org/?probe=458bf998ee) | May 06, 2022 |
| Intel         | H55                         | [138637d12c](https://linux-hardware.org/?probe=138637d12c) | May 06, 2022 |
| Gigabyte      | G41M-Combo                  | [9940073216](https://linux-hardware.org/?probe=9940073216) | May 05, 2022 |
| Gigabyte      | G41MT-S2                    | [fd9ed9a035](https://linux-hardware.org/?probe=fd9ed9a035) | May 05, 2022 |
| HP            | 1906                        | [6f7f0536a9](https://linux-hardware.org/?probe=6f7f0536a9) | May 05, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [31eaff1b28](https://linux-hardware.org/?probe=31eaff1b28) | May 04, 2022 |
| MSI           | B85M-G43                    | [f5deeb2d19](https://linux-hardware.org/?probe=f5deeb2d19) | May 04, 2022 |
| MSI           | Z590 PRO WIFI               | [17aad0bb78](https://linux-hardware.org/?probe=17aad0bb78) | May 03, 2022 |
| HP            | 1906                        | [60ce09d82e](https://linux-hardware.org/?probe=60ce09d82e) | May 03, 2022 |
| Gigabyte      | B365M GAMING HD             | [637890bd75](https://linux-hardware.org/?probe=637890bd75) | May 03, 2022 |
| Maxtone       | HIS-G41L V1.1               | [ce61ffd777](https://linux-hardware.org/?probe=ce61ffd777) | May 02, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [7f9e8dd9f6](https://linux-hardware.org/?probe=7f9e8dd9f6) | May 02, 2022 |
| Maxtone       | HIS-G41L V1.1               | [63fc1199bc](https://linux-hardware.org/?probe=63fc1199bc) | May 01, 2022 |
| ASUSTek       | H97I-PLUS                   | [c8e857524b](https://linux-hardware.org/?probe=c8e857524b) | May 01, 2022 |
| ASRock        | B365M-HDV                   | [51b0e7e57f](https://linux-hardware.org/?probe=51b0e7e57f) | May 01, 2022 |
| Dell          | 0M017G A01                  | [653212f53c](https://linux-hardware.org/?probe=653212f53c) | May 01, 2022 |
| HP            | 1791                        | [877270ede6](https://linux-hardware.org/?probe=877270ede6) | Apr 30, 2022 |
| Intel         | DCP847SKE G80890-105        | [45dc47c8aa](https://linux-hardware.org/?probe=45dc47c8aa) | Apr 30, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [89323fb22d](https://linux-hardware.org/?probe=89323fb22d) | Apr 30, 2022 |
| Foxconn       | 2A92                        | [298326d530](https://linux-hardware.org/?probe=298326d530) | Apr 30, 2022 |
| Foxconn       | 2A92                        | [a710d4a58f](https://linux-hardware.org/?probe=a710d4a58f) | Apr 30, 2022 |
| Gigabyte      | Z68AP-D3                    | [af8b52acd3](https://linux-hardware.org/?probe=af8b52acd3) | Apr 29, 2022 |
| Gigabyte      | P31-ES3G                    | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [965985d6f4](https://linux-hardware.org/?probe=965985d6f4) | Apr 29, 2022 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [277754d8c1](https://linux-hardware.org/?probe=277754d8c1) | Apr 29, 2022 |
| BESSTAR Te... | HM90                        | [814f90b822](https://linux-hardware.org/?probe=814f90b822) | Apr 28, 2022 |
| Gigabyte      | P31-ES3G                    | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [97a2717eb9](https://linux-hardware.org/?probe=97a2717eb9) | Apr 27, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [68fdd1e81a](https://linux-hardware.org/?probe=68fdd1e81a) | Apr 27, 2022 |
| ASUSTek       | Hematite                    | [a6eec927f0](https://linux-hardware.org/?probe=a6eec927f0) | Apr 26, 2022 |
| MSI           | MS-6701                     | [8853d92523](https://linux-hardware.org/?probe=8853d92523) | Apr 26, 2022 |
| MSI           | MS-6701                     | [0bde2af604](https://linux-hardware.org/?probe=0bde2af604) | Apr 26, 2022 |
| MSI           | B450 TOMAHAWK               | [148f1cc5e8](https://linux-hardware.org/?probe=148f1cc5e8) | Apr 25, 2022 |
| Dell          | 0HN7XN A01                  | [a282e15540](https://linux-hardware.org/?probe=a282e15540) | Apr 25, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [392c7e4d0d](https://linux-hardware.org/?probe=392c7e4d0d) | Apr 25, 2022 |
| MSI           | 760GM-P21                   | [3582362347](https://linux-hardware.org/?probe=3582362347) | Apr 24, 2022 |
| ASUSTek       | H97I-PLUS                   | [1b392b96c3](https://linux-hardware.org/?probe=1b392b96c3) | Apr 24, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [b36aa38e8a](https://linux-hardware.org/?probe=b36aa38e8a) | Apr 24, 2022 |
| Gigabyte      | A320M-H-CF                  | [da2e3a603d](https://linux-hardware.org/?probe=da2e3a603d) | Apr 23, 2022 |
| Dell          | 0GDG8Y A00                  | [a0ab7e8078](https://linux-hardware.org/?probe=a0ab7e8078) | Apr 22, 2022 |
| Acer          | Nitro N50-600 V:1.1         | [15332404e6](https://linux-hardware.org/?probe=15332404e6) | Apr 21, 2022 |
| Acer          | Nitro N50-600 V:1.1         | [b272388aa6](https://linux-hardware.org/?probe=b272388aa6) | Apr 21, 2022 |
| ASUSTek       | P5GC-MX                     | [810607b312](https://linux-hardware.org/?probe=810607b312) | Apr 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | [9b742eb785](https://linux-hardware.org/?probe=9b742eb785) | Apr 20, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [f830e867e5](https://linux-hardware.org/?probe=f830e867e5) | Apr 20, 2022 |
| Gigabyte      | Z68AP-D3                    | [76d25fd5c1](https://linux-hardware.org/?probe=76d25fd5c1) | Apr 20, 2022 |
| MSI           | 2AE0                        | [da90dbf2f2](https://linux-hardware.org/?probe=da90dbf2f2) | Apr 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [73dbb7e52a](https://linux-hardware.org/?probe=73dbb7e52a) | Apr 19, 2022 |
| HP            | 8265                        | [6a7abd0db8](https://linux-hardware.org/?probe=6a7abd0db8) | Apr 19, 2022 |
| Huanan        | X79 249PC V2.2              | [209e881793](https://linux-hardware.org/?probe=209e881793) | Apr 18, 2022 |
| ASRock        | X570 Taichi Razer Editio... | [b3f2a146ea](https://linux-hardware.org/?probe=b3f2a146ea) | Apr 18, 2022 |
| ASRock        | X570 Taichi Razer Editio... | [d597e4df9c](https://linux-hardware.org/?probe=d597e4df9c) | Apr 18, 2022 |
| Acer          | Aspire TC-115               | [16d5411ae8](https://linux-hardware.org/?probe=16d5411ae8) | Apr 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f20c2c3665](https://linux-hardware.org/?probe=f20c2c3665) | Apr 16, 2022 |
| HP            | 845A                        | [cc8c320581](https://linux-hardware.org/?probe=cc8c320581) | Apr 16, 2022 |
| MSI           | 2AE0                        | [b1059198e0](https://linux-hardware.org/?probe=b1059198e0) | Apr 15, 2022 |
| ASRock        | H170M Pro4                  | [0dd1b326c0](https://linux-hardware.org/?probe=0dd1b326c0) | Apr 15, 2022 |
| MSI           | MAG B460M MORTAR            | [eeccee9c29](https://linux-hardware.org/?probe=eeccee9c29) | Apr 15, 2022 |
| ASUSTek       | F2A85-V                     | [6200a8f946](https://linux-hardware.org/?probe=6200a8f946) | Apr 14, 2022 |
| Pegatron      | 2A99h                       | [0d208bc673](https://linux-hardware.org/?probe=0d208bc673) | Apr 13, 2022 |
| Pegatron      | 2A99h                       | [7a31392de4](https://linux-hardware.org/?probe=7a31392de4) | Apr 13, 2022 |
| Gigabyte      | Z77-D3H                     | [2ddb0d0765](https://linux-hardware.org/?probe=2ddb0d0765) | Apr 13, 2022 |
| ASRock        | B460M-ITX/ac                | [7e6604d785](https://linux-hardware.org/?probe=7e6604d785) | Apr 12, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [ba5d8c783b](https://linux-hardware.org/?probe=ba5d8c783b) | Apr 12, 2022 |
| Gigabyte      | A520 AORUS ELITE            | [a0ff638057](https://linux-hardware.org/?probe=a0ff638057) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [cadff96ec0](https://linux-hardware.org/?probe=cadff96ec0) | Apr 11, 2022 |
| ASUSTek       | H81M-A                      | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [a751b63d6b](https://linux-hardware.org/?probe=a751b63d6b) | Apr 11, 2022 |
| Dell          | 0JP3NX A01                  | [266d7d3a62](https://linux-hardware.org/?probe=266d7d3a62) | Apr 11, 2022 |
| ASRock        | B450 Steel Legend           | [b9b9565fae](https://linux-hardware.org/?probe=b9b9565fae) | Apr 10, 2022 |
| ASUSTek       | P8B75-V                     | [218db09adf](https://linux-hardware.org/?probe=218db09adf) | Apr 10, 2022 |
| Medion        | MS-7366                     | [206ab01c63](https://linux-hardware.org/?probe=206ab01c63) | Apr 10, 2022 |
| Foxconn       | 2A92                        | [d7dc8e0a2b](https://linux-hardware.org/?probe=d7dc8e0a2b) | Apr 10, 2022 |
| ASUSTek       | PRIME Z390-A                | [9f3f45d840](https://linux-hardware.org/?probe=9f3f45d840) | Apr 09, 2022 |
| ASRock        | Z87 Pro4                    | [03ee27c2ea](https://linux-hardware.org/?probe=03ee27c2ea) | Apr 09, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [73628a9025](https://linux-hardware.org/?probe=73628a9025) | Apr 09, 2022 |
| Medion        | MS-7366                     | [86884e1cf1](https://linux-hardware.org/?probe=86884e1cf1) | Apr 09, 2022 |
| ASRock        | H61M-DGS                    | [1d08a53545](https://linux-hardware.org/?probe=1d08a53545) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | [2e37b66578](https://linux-hardware.org/?probe=2e37b66578) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | [e7b1a0df67](https://linux-hardware.org/?probe=e7b1a0df67) | Apr 08, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [fe36e7827a](https://linux-hardware.org/?probe=fe36e7827a) | Apr 08, 2022 |
| ASUSTek       | PRIME Z390-A                | [8ac05d8917](https://linux-hardware.org/?probe=8ac05d8917) | Apr 07, 2022 |
| Gigabyte      | B365M GAMING HD             | [94b6fc5131](https://linux-hardware.org/?probe=94b6fc5131) | Apr 07, 2022 |
| Gigabyte      | 945PL-S3                    | [ef7f30cc40](https://linux-hardware.org/?probe=ef7f30cc40) | Apr 07, 2022 |
| Alienware     | 0H869M A00                  | [f6a1c02c3e](https://linux-hardware.org/?probe=f6a1c02c3e) | Apr 07, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1592895310](https://linux-hardware.org/?probe=1592895310) | Apr 07, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | [f76a15be2a](https://linux-hardware.org/?probe=f76a15be2a) | Apr 06, 2022 |
| Gigabyte      | Z77-DS3H                    | [a3d3ff5ac5](https://linux-hardware.org/?probe=a3d3ff5ac5) | Apr 06, 2022 |
| ECS           | Livermore                   | [afafdb72a7](https://linux-hardware.org/?probe=afafdb72a7) | Apr 06, 2022 |
| Unknown       | Unknown                     | [c8049ac14a](https://linux-hardware.org/?probe=c8049ac14a) | Apr 06, 2022 |
| ASUSTek       | P5GC-MX                     | [ce2aaa12ab](https://linux-hardware.org/?probe=ce2aaa12ab) | Apr 06, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [55eda86e20](https://linux-hardware.org/?probe=55eda86e20) | Apr 05, 2022 |
| Dell          | 09KPNV A00                  | [0a06779a5a](https://linux-hardware.org/?probe=0a06779a5a) | Apr 05, 2022 |
| Foxconn       | 2A92                        | [dd802e925f](https://linux-hardware.org/?probe=dd802e925f) | Apr 05, 2022 |
| MSI           | MS-7204                     | [e04077c3ac](https://linux-hardware.org/?probe=e04077c3ac) | Apr 05, 2022 |
| MSI           | MS-7204                     | [817c6f06bf](https://linux-hardware.org/?probe=817c6f06bf) | Apr 05, 2022 |
| Dell          | 0DR845                      | [26a919fc82](https://linux-hardware.org/?probe=26a919fc82) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | [26032ef606](https://linux-hardware.org/?probe=26032ef606) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | [fed309fdf1](https://linux-hardware.org/?probe=fed309fdf1) | Apr 04, 2022 |
| MSI           | B75A-G41                    | [80ec6aed14](https://linux-hardware.org/?probe=80ec6aed14) | Apr 04, 2022 |
| Unknown       | Unknown                     | [f6bc1c6219](https://linux-hardware.org/?probe=f6bc1c6219) | Apr 03, 2022 |
| ASUSTek       | PRIME X570-P                | [e237e56d72](https://linux-hardware.org/?probe=e237e56d72) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2315db07e2](https://linux-hardware.org/?probe=2315db07e2) | Apr 02, 2022 |
| ECS           | Livermore                   | [d801396140](https://linux-hardware.org/?probe=d801396140) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [448e59a9a6](https://linux-hardware.org/?probe=448e59a9a6) | Apr 02, 2022 |
| ASUSTek       | F2A85-V                     | [6056351804](https://linux-hardware.org/?probe=6056351804) | Apr 02, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [0d1d941941](https://linux-hardware.org/?probe=0d1d941941) | Apr 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [fc477a4cb4](https://linux-hardware.org/?probe=fc477a4cb4) | Apr 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [23b384fa80](https://linux-hardware.org/?probe=23b384fa80) | Apr 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [e94a772f2b](https://linux-hardware.org/?probe=e94a772f2b) | Apr 02, 2022 |
| ASUSTek       | P5GD1 PRO                   | [9156c67116](https://linux-hardware.org/?probe=9156c67116) | Apr 01, 2022 |
| Biostar       | X370GT5                     | [efe58d6ab1](https://linux-hardware.org/?probe=efe58d6ab1) | Mar 31, 2022 |
| MSI           | P45 Neo2-FR                 | [23fa0ec187](https://linux-hardware.org/?probe=23fa0ec187) | Mar 31, 2022 |
| Google        | Panther                     | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther                     | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| Gigabyte      | G1.Sniper B6-CF             | [17ea484809](https://linux-hardware.org/?probe=17ea484809) | Mar 29, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [99acee5d56](https://linux-hardware.org/?probe=99acee5d56) | Mar 29, 2022 |
| Intel         | DH55HC AAE70933-505         | [0a58762fd9](https://linux-hardware.org/?probe=0a58762fd9) | Mar 29, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [9cd4056356](https://linux-hardware.org/?probe=9cd4056356) | Mar 28, 2022 |
| HP            | 18E5                        | [39cb47db55](https://linux-hardware.org/?probe=39cb47db55) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | [a50c8cdd0d](https://linux-hardware.org/?probe=a50c8cdd0d) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | [5f779f4af0](https://linux-hardware.org/?probe=5f779f4af0) | Mar 27, 2022 |
| Pegatron      | Benicia                     | [cd70e5d6f6](https://linux-hardware.org/?probe=cd70e5d6f6) | Mar 27, 2022 |
| HP            | 18E5                        | [061d716ce1](https://linux-hardware.org/?probe=061d716ce1) | Mar 27, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [fc2b611797](https://linux-hardware.org/?probe=fc2b611797) | Mar 25, 2022 |
| ASRock        | H61M-HVS                    | [7ebb094ad8](https://linux-hardware.org/?probe=7ebb094ad8) | Mar 25, 2022 |
| Dell          | 0P096C A01                  | [fff71ec7de](https://linux-hardware.org/?probe=fff71ec7de) | Mar 24, 2022 |
| Gigabyte      | H67MA-USB3-B3               | [c5ad9a2c99](https://linux-hardware.org/?probe=c5ad9a2c99) | Mar 24, 2022 |
| ASUSTek       | H81M-A                      | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| ASUSTek       | H81M-CS/BR                  | [17a0a5394e](https://linux-hardware.org/?probe=17a0a5394e) | Mar 24, 2022 |
| Dell          | 0KWVT8 A00                  | [5e2b36f808](https://linux-hardware.org/?probe=5e2b36f808) | Mar 24, 2022 |
| ASRock        | B550 Steel Legend           | [5c1495ecf1](https://linux-hardware.org/?probe=5c1495ecf1) | Mar 21, 2022 |
| ASRock        | B550 Steel Legend           | [00ea7017ff](https://linux-hardware.org/?probe=00ea7017ff) | Mar 20, 2022 |
| Gigabyte      | Z690 UD DDR4                | [03bfb9a66b](https://linux-hardware.org/?probe=03bfb9a66b) | Mar 20, 2022 |
| ASUSTek       | NODUSM3                     | [14c35dc52c](https://linux-hardware.org/?probe=14c35dc52c) | Mar 20, 2022 |
| Dell          | 0GDG8Y A00                  | [1deed3b4bb](https://linux-hardware.org/?probe=1deed3b4bb) | Mar 20, 2022 |
| Biostar       | B460GTQ                     | [7c912f57c6](https://linux-hardware.org/?probe=7c912f57c6) | Mar 20, 2022 |
| HP            | 1497                        | [2aac5eaf08](https://linux-hardware.org/?probe=2aac5eaf08) | Mar 19, 2022 |
| HP            | 1497                        | [ec392b9979](https://linux-hardware.org/?probe=ec392b9979) | Mar 19, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [3ba6de8cdd](https://linux-hardware.org/?probe=3ba6de8cdd) | Mar 19, 2022 |
| Dell          | 09KPNV A00                  | [f71ac898a8](https://linux-hardware.org/?probe=f71ac898a8) | Mar 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [34fb0ae26f](https://linux-hardware.org/?probe=34fb0ae26f) | Mar 19, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7cafe0766c](https://linux-hardware.org/?probe=7cafe0766c) | Mar 18, 2022 |
| ASUSTek       | Hematite                    | [e4258e3376](https://linux-hardware.org/?probe=e4258e3376) | Mar 17, 2022 |
| ASUSTek       | M2A-VM HDMI                 | [ea35877485](https://linux-hardware.org/?probe=ea35877485) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | [0af153934b](https://linux-hardware.org/?probe=0af153934b) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | [2071129adb](https://linux-hardware.org/?probe=2071129adb) | Mar 17, 2022 |
| Shuttle       | X50V2PLUS V1.00             | [0bd650dfff](https://linux-hardware.org/?probe=0bd650dfff) | Mar 16, 2022 |
| Dell          | 0WMJ54 A01                  | [fe21b2c644](https://linux-hardware.org/?probe=fe21b2c644) | Mar 15, 2022 |
| HP            | 1791                        | [f183c3d0f0](https://linux-hardware.org/?probe=f183c3d0f0) | Mar 15, 2022 |
| HP            | 1497                        | [0aaa7bf906](https://linux-hardware.org/?probe=0aaa7bf906) | Mar 15, 2022 |
| TYAN Compu... | D2568 S26361-D2568-A11      | [fd7cbc2300](https://linux-hardware.org/?probe=fd7cbc2300) | Mar 15, 2022 |
| Dell          | 0CU409                      | [2e684afab9](https://linux-hardware.org/?probe=2e684afab9) | Mar 14, 2022 |
| MSI           | B85M-G43                    | [3869d4fdc0](https://linux-hardware.org/?probe=3869d4fdc0) | Mar 14, 2022 |
| ASUSTek       | Maximus VIII GENE           | [f264de34b1](https://linux-hardware.org/?probe=f264de34b1) | Mar 13, 2022 |
| ASUSTek       | Crosshair IV Formula        | [fd7e52fdd3](https://linux-hardware.org/?probe=fd7e52fdd3) | Mar 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [a90ce91192](https://linux-hardware.org/?probe=a90ce91192) | Mar 12, 2022 |
| ASUSTek       | P8P67                       | [33bf33cb8d](https://linux-hardware.org/?probe=33bf33cb8d) | Mar 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | [67ead34e9e](https://linux-hardware.org/?probe=67ead34e9e) | Mar 10, 2022 |
| Google        | Buddy                       | [848034437d](https://linux-hardware.org/?probe=848034437d) | Mar 09, 2022 |
| Google        | Buddy                       | [db18fd0c96](https://linux-hardware.org/?probe=db18fd0c96) | Mar 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [798e5f6c43](https://linux-hardware.org/?probe=798e5f6c43) | Mar 09, 2022 |
| MSI           | H110M PRO-VH PLUS           | [fc3707d356](https://linux-hardware.org/?probe=fc3707d356) | Mar 09, 2022 |
| ASUSTek       | P5E-VM DO                   | [876e876df1](https://linux-hardware.org/?probe=876e876df1) | Mar 09, 2022 |
| MSI           | A75A-G35                    | [8dfa30cef5](https://linux-hardware.org/?probe=8dfa30cef5) | Mar 07, 2022 |
| ASUSTek       | Z97-DELUXE                  | [7ea271a455](https://linux-hardware.org/?probe=7ea271a455) | Mar 05, 2022 |
| MSI           | B85M-G43                    | [d5e3087569](https://linux-hardware.org/?probe=d5e3087569) | Mar 04, 2022 |
| Intel         | H61                         | [86f2038ab2](https://linux-hardware.org/?probe=86f2038ab2) | Mar 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | [78089f6e8c](https://linux-hardware.org/?probe=78089f6e8c) | Mar 03, 2022 |
| Gigabyte      | Z77-DS3H                    | [16268a74aa](https://linux-hardware.org/?probe=16268a74aa) | Mar 03, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [1d01e4616b](https://linux-hardware.org/?probe=1d01e4616b) | Mar 03, 2022 |
| MSI           | A68HM-E33 V2                | [53dd60c906](https://linux-hardware.org/?probe=53dd60c906) | Mar 02, 2022 |
| ASUSTek       | PRIME X370-PRO              | [b74317d80e](https://linux-hardware.org/?probe=b74317d80e) | Mar 02, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a94729eaf7](https://linux-hardware.org/?probe=a94729eaf7) | Mar 01, 2022 |
| ASRock        | H110M-DGS R3.0              | [d7b8815296](https://linux-hardware.org/?probe=d7b8815296) | Feb 28, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | [61f8410abd](https://linux-hardware.org/?probe=61f8410abd) | Feb 28, 2022 |
| BESSTAR Te... | TL50                        | [54383b0005](https://linux-hardware.org/?probe=54383b0005) | Feb 28, 2022 |
| HP            | 821D                        | [fdfcbe172a](https://linux-hardware.org/?probe=fdfcbe172a) | Feb 28, 2022 |
| Acer          | Aspire TC-875 V:1.0         | [47018f3ae4](https://linux-hardware.org/?probe=47018f3ae4) | Feb 28, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| ASRock        | H77M                        | [e49dce2077](https://linux-hardware.org/?probe=e49dce2077) | Feb 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | [ac9099b0e4](https://linux-hardware.org/?probe=ac9099b0e4) | Feb 28, 2022 |
| Gigabyte      | GA-990FXA-D3                | [67943c7786](https://linux-hardware.org/?probe=67943c7786) | Feb 27, 2022 |
| ASUSTek       | PRIME X370-PRO              | [52c633564d](https://linux-hardware.org/?probe=52c633564d) | Feb 27, 2022 |
| Gigabyte      | GA-990FXA-D3                | [badbd8817c](https://linux-hardware.org/?probe=badbd8817c) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| MSI           | B85M-E45                    | [42fba9424e](https://linux-hardware.org/?probe=42fba9424e) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [e1ba37c64a](https://linux-hardware.org/?probe=e1ba37c64a) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [5d56069677](https://linux-hardware.org/?probe=5d56069677) | Feb 27, 2022 |
| Gigabyte      | N3160TN                     | [f080ac90fa](https://linux-hardware.org/?probe=f080ac90fa) | Feb 26, 2022 |
| ASUSTek       | PRIME H510M-D               | [5e8e80fa4c](https://linux-hardware.org/?probe=5e8e80fa4c) | Feb 25, 2022 |
| Intel         | X79M-S                      | [a175e713d6](https://linux-hardware.org/?probe=a175e713d6) | Feb 25, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [c9447d244f](https://linux-hardware.org/?probe=c9447d244f) | Feb 24, 2022 |
| Gigabyte      | Z87-HD3                     | [d1fd917c74](https://linux-hardware.org/?probe=d1fd917c74) | Feb 24, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [40de7f3fd4](https://linux-hardware.org/?probe=40de7f3fd4) | Feb 23, 2022 |
| Medion        | MS-7707                     | [563fc4ee5a](https://linux-hardware.org/?probe=563fc4ee5a) | Feb 23, 2022 |
| Medion        | MS-7707                     | [f3b9e8796b](https://linux-hardware.org/?probe=f3b9e8796b) | Feb 23, 2022 |
| IBM           | 819046G                     | [54b0798b76](https://linux-hardware.org/?probe=54b0798b76) | Feb 22, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [8efe63496f](https://linux-hardware.org/?probe=8efe63496f) | Feb 22, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [979289afcb](https://linux-hardware.org/?probe=979289afcb) | Feb 21, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [62fc974ec7](https://linux-hardware.org/?probe=62fc974ec7) | Feb 21, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [435006f81f](https://linux-hardware.org/?probe=435006f81f) | Feb 20, 2022 |
| Gigabyte      | B560M AORUS ELITE           | [9264e93f98](https://linux-hardware.org/?probe=9264e93f98) | Feb 20, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [1990e2040f](https://linux-hardware.org/?probe=1990e2040f) | Feb 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [c545739154](https://linux-hardware.org/?probe=c545739154) | Feb 18, 2022 |
| ASUSTek       | P5E-VM DO                   | [c204579cc4](https://linux-hardware.org/?probe=c204579cc4) | Feb 18, 2022 |
| Gigabyte      | H270M-DS3H-CF               | [bccc2f8988](https://linux-hardware.org/?probe=bccc2f8988) | Feb 18, 2022 |
| MSI           | B360M PRO-VDH               | [dfb03c38d4](https://linux-hardware.org/?probe=dfb03c38d4) | Feb 18, 2022 |
| Acer          | K8VM800MAE                  | [e4505f1541](https://linux-hardware.org/?probe=e4505f1541) | Feb 17, 2022 |
| Acer          | K8VM800MAE                  | [ac2f1dab87](https://linux-hardware.org/?probe=ac2f1dab87) | Feb 17, 2022 |
| ASUSTek       | A88XM-PLUS                  | [3a6147e5db](https://linux-hardware.org/?probe=3a6147e5db) | Feb 16, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| ASUSTek       | P8P67                       | [e52f9b0748](https://linux-hardware.org/?probe=e52f9b0748) | Feb 15, 2022 |
| HP            | 2B15A                       | [ca58e13d8f](https://linux-hardware.org/?probe=ca58e13d8f) | Feb 15, 2022 |
| Pegatron      | 2AC2                        | [092df404d4](https://linux-hardware.org/?probe=092df404d4) | Feb 15, 2022 |
| ASUSTek       | PRIME X370-PRO              | [54a56f3b09](https://linux-hardware.org/?probe=54a56f3b09) | Feb 15, 2022 |
| Intel         | X79M-S                      | [b655865606](https://linux-hardware.org/?probe=b655865606) | Feb 14, 2022 |
| IBM           | 81077AG                     | [934878ed63](https://linux-hardware.org/?probe=934878ed63) | Feb 14, 2022 |
| ASUSTek       | P8H61-M EVO                 | [40ed7abcc5](https://linux-hardware.org/?probe=40ed7abcc5) | Feb 14, 2022 |
| ASRock        | X299 Taichi                 | [cb4047cf07](https://linux-hardware.org/?probe=cb4047cf07) | Feb 13, 2022 |
| ASUSTek       | P8H61-M EVO                 | [94bcb91d02](https://linux-hardware.org/?probe=94bcb91d02) | Feb 13, 2022 |
| ASRock        | 970A-G                      | [7b3694013f](https://linux-hardware.org/?probe=7b3694013f) | Feb 13, 2022 |
| HP            | 0B54h D                     | [c9f9611ea4](https://linux-hardware.org/?probe=c9f9611ea4) | Feb 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | [d97414cfe4](https://linux-hardware.org/?probe=d97414cfe4) | Feb 12, 2022 |
| Dell          | 0T10XW A01                  | [a9034f065e](https://linux-hardware.org/?probe=a9034f065e) | Feb 11, 2022 |
| Dell          | 0T10XW A01                  | [c0cce21524](https://linux-hardware.org/?probe=c0cce21524) | Feb 11, 2022 |
| Intel         | H61                         | [e06357425a](https://linux-hardware.org/?probe=e06357425a) | Feb 11, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [b79b4aaf10](https://linux-hardware.org/?probe=b79b4aaf10) | Feb 11, 2022 |
| HP            | 198E                        | [f4781dd683](https://linux-hardware.org/?probe=f4781dd683) | Feb 10, 2022 |
| Dell          | 0GM819                      | [bdd485de00](https://linux-hardware.org/?probe=bdd485de00) | Feb 10, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [0c13bfa27b](https://linux-hardware.org/?probe=0c13bfa27b) | Feb 10, 2022 |
| Dell          | 096JG8 A01                  | [c56c62ab01](https://linux-hardware.org/?probe=c56c62ab01) | Feb 10, 2022 |
| Gigabyte      | Z87N-WIFI                   | [e86fa9ee02](https://linux-hardware.org/?probe=e86fa9ee02) | Feb 09, 2022 |
| Gigabyte      | Z87N-WIFI                   | [1b6aa0ce08](https://linux-hardware.org/?probe=1b6aa0ce08) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | [961be2a608](https://linux-hardware.org/?probe=961be2a608) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | [4ab26645c2](https://linux-hardware.org/?probe=4ab26645c2) | Feb 09, 2022 |
| HP            | 8350                        | [31f2f10b25](https://linux-hardware.org/?probe=31f2f10b25) | Feb 08, 2022 |
| HP            | 1906                        | [c2107ad290](https://linux-hardware.org/?probe=c2107ad290) | Feb 08, 2022 |
| HP            | 1906                        | [9f08673e43](https://linux-hardware.org/?probe=9f08673e43) | Feb 08, 2022 |
| MSI           | 2AE0                        | [7026cf0c86](https://linux-hardware.org/?probe=7026cf0c86) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [cec6148a23](https://linux-hardware.org/?probe=cec6148a23) | Feb 07, 2022 |
| MSI           | B85M-E45                    | [3653d29a0a](https://linux-hardware.org/?probe=3653d29a0a) | Feb 07, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [c5db8c7811](https://linux-hardware.org/?probe=c5db8c7811) | Feb 06, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [96e92c90a5](https://linux-hardware.org/?probe=96e92c90a5) | Feb 06, 2022 |
| Gigabyte      | G1.Sniper Z97               | [5ef683a8ed](https://linux-hardware.org/?probe=5ef683a8ed) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [81b3cfa233](https://linux-hardware.org/?probe=81b3cfa233) | Feb 06, 2022 |
| Acer          | Aspire TC-115               | [03188d20fc](https://linux-hardware.org/?probe=03188d20fc) | Feb 05, 2022 |
| ASUSTek       | H110M-CS/BR                 | [f4319bd379](https://linux-hardware.org/?probe=f4319bd379) | Feb 05, 2022 |
| Dell          | 0DN075                      | [eb385877ae](https://linux-hardware.org/?probe=eb385877ae) | Feb 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [80cf2c4065](https://linux-hardware.org/?probe=80cf2c4065) | Feb 04, 2022 |
| Gigabyte      | H81M-S2V                    | [4c9a0cdddb](https://linux-hardware.org/?probe=4c9a0cdddb) | Feb 03, 2022 |
| ASUSTek       | Maximus V GENE              | [749946734b](https://linux-hardware.org/?probe=749946734b) | Feb 03, 2022 |
| Dell          | 0HN7XN A01                  | [5bb62c21b7](https://linux-hardware.org/?probe=5bb62c21b7) | Feb 03, 2022 |
| ASUSTek       | M4A785-M                    | [421c016644](https://linux-hardware.org/?probe=421c016644) | Feb 02, 2022 |
| Unknown       | Unknown                     | [f302ce9f42](https://linux-hardware.org/?probe=f302ce9f42) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | [b76b53bf53](https://linux-hardware.org/?probe=b76b53bf53) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | [45f03f7991](https://linux-hardware.org/?probe=45f03f7991) | Jan 31, 2022 |
| Gigabyte      | B450 AORUS M                | [690eba21e0](https://linux-hardware.org/?probe=690eba21e0) | Jan 30, 2022 |
| Dell          | 0HN7XN A01                  | [af1d1e8c47](https://linux-hardware.org/?probe=af1d1e8c47) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [7450ea2cad](https://linux-hardware.org/?probe=7450ea2cad) | Jan 30, 2022 |
| ASRock        | H81M-DGS                    | [05fc3bd63b](https://linux-hardware.org/?probe=05fc3bd63b) | Jan 29, 2022 |
| Gigabyte      | M68MT-D3                    | [8818e2647a](https://linux-hardware.org/?probe=8818e2647a) | Jan 29, 2022 |
| ASUSTek       | H110M-CS/BR                 | [a3f76dfb23](https://linux-hardware.org/?probe=a3f76dfb23) | Jan 29, 2022 |
| HP            | 3047h                       | [48f624cbea](https://linux-hardware.org/?probe=48f624cbea) | Jan 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bcdcd2eeb6](https://linux-hardware.org/?probe=bcdcd2eeb6) | Jan 29, 2022 |
| ASUSTek       | M2A74-AM SE                 | [1a2d6520d3](https://linux-hardware.org/?probe=1a2d6520d3) | Jan 29, 2022 |
| MSI           | 2AE0                        | [1a55336eb9](https://linux-hardware.org/?probe=1a55336eb9) | Jan 28, 2022 |
| HP            | 0B4Ch D                     | [e498058bd8](https://linux-hardware.org/?probe=e498058bd8) | Jan 28, 2022 |
| Gigabyte      | GA-MA790GP-DS4H             | [ef8894e69d](https://linux-hardware.org/?probe=ef8894e69d) | Jan 28, 2022 |
| Wortmann      | TERRA_PC                    | [4fea20e2bf](https://linux-hardware.org/?probe=4fea20e2bf) | Jan 28, 2022 |
| Dell          | 0Y2MRG A00                  | [1a1b794c06](https://linux-hardware.org/?probe=1a1b794c06) | Jan 28, 2022 |
| Gigabyte      | Z270N-WIFI-CF               | [78f310c42a](https://linux-hardware.org/?probe=78f310c42a) | Jan 27, 2022 |
| Intel         | DH55TC AAE70932-302         | [d66879ebac](https://linux-hardware.org/?probe=d66879ebac) | Jan 27, 2022 |
| ASRock        | G31M-S                      | [e579ce1757](https://linux-hardware.org/?probe=e579ce1757) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | [2c70e74055](https://linux-hardware.org/?probe=2c70e74055) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | [6a692a4e11](https://linux-hardware.org/?probe=6a692a4e11) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [72374dc22c](https://linux-hardware.org/?probe=72374dc22c) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [78cdf0490a](https://linux-hardware.org/?probe=78cdf0490a) | Jan 26, 2022 |
| Dell          | 07KY25 A00                  | [102d10e806](https://linux-hardware.org/?probe=102d10e806) | Jan 26, 2022 |
| MSI           | H97 GAMING 3                | [75f4b47111](https://linux-hardware.org/?probe=75f4b47111) | Jan 26, 2022 |
| Dell          | 06NWYK A01                  | [dbc44c9f4a](https://linux-hardware.org/?probe=dbc44c9f4a) | Jan 25, 2022 |
| HP            | 1497                        | [a32eadf3ab](https://linux-hardware.org/?probe=a32eadf3ab) | Jan 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e521380180](https://linux-hardware.org/?probe=e521380180) | Jan 25, 2022 |
| ASUSTek       | Q87T                        | [1bcaa6dedf](https://linux-hardware.org/?probe=1bcaa6dedf) | Jan 24, 2022 |
| Foxconn       | 2ABF                        | [e5723eaa42](https://linux-hardware.org/?probe=e5723eaa42) | Jan 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a0034083eb](https://linux-hardware.org/?probe=a0034083eb) | Jan 22, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [2a8b893eb6](https://linux-hardware.org/?probe=2a8b893eb6) | Jan 22, 2022 |
| Foxconn       | 2ABF                        | [af38735785](https://linux-hardware.org/?probe=af38735785) | Jan 22, 2022 |
| MSI           | A75A-G35                    | [e2148dff19](https://linux-hardware.org/?probe=e2148dff19) | Jan 22, 2022 |
| Dell          | 0CU409                      | [8fc6c3decf](https://linux-hardware.org/?probe=8fc6c3decf) | Jan 21, 2022 |
| Dell          | 0CU409                      | [953718318f](https://linux-hardware.org/?probe=953718318f) | Jan 21, 2022 |
| Gigabyte      | M68MT-D3                    | [9f01c8b5ba](https://linux-hardware.org/?probe=9f01c8b5ba) | Jan 21, 2022 |
| Gigabyte      | F2A58M-DS2                  | [a89dd04d3a](https://linux-hardware.org/?probe=a89dd04d3a) | Jan 20, 2022 |
| Shuttle       | FB62                        | [01c9cc70b3](https://linux-hardware.org/?probe=01c9cc70b3) | Jan 20, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [586012f45e](https://linux-hardware.org/?probe=586012f45e) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | [2ab8f0375c](https://linux-hardware.org/?probe=2ab8f0375c) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | [5308c77880](https://linux-hardware.org/?probe=5308c77880) | Jan 19, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [bb0d1c1c68](https://linux-hardware.org/?probe=bb0d1c1c68) | Jan 19, 2022 |
| ASUSTek       | H81M-K                      | [637ad5d9e4](https://linux-hardware.org/?probe=637ad5d9e4) | Jan 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [ffaca9cabf](https://linux-hardware.org/?probe=ffaca9cabf) | Jan 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [940b702411](https://linux-hardware.org/?probe=940b702411) | Jan 16, 2022 |
| MSI           | H61M-P25                    | [3433cb58a1](https://linux-hardware.org/?probe=3433cb58a1) | Jan 14, 2022 |
| MSI           | MS-7053                     | [8844db2984](https://linux-hardware.org/?probe=8844db2984) | Jan 13, 2022 |
| EVGA          | 152-HR-E979                 | [669c7a3ef6](https://linux-hardware.org/?probe=669c7a3ef6) | Jan 12, 2022 |
| EVGA          | 152-HR-E979                 | [075a31a3c5](https://linux-hardware.org/?probe=075a31a3c5) | Jan 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [368df270dc](https://linux-hardware.org/?probe=368df270dc) | Jan 11, 2022 |
| Gigabyte      | F2A58M-DS2                  | [b7ee3c3e93](https://linux-hardware.org/?probe=b7ee3c3e93) | Jan 11, 2022 |
| ASUSTek       | P8H61-I R2.0                | [5b08de311b](https://linux-hardware.org/?probe=5b08de311b) | Jan 10, 2022 |
| Dell          | 06NWYK A01                  | [98c10ce544](https://linux-hardware.org/?probe=98c10ce544) | Jan 10, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [ce5b35b77b](https://linux-hardware.org/?probe=ce5b35b77b) | Jan 10, 2022 |
| Phitronics    | P33G                        | [d21245c1ea](https://linux-hardware.org/?probe=d21245c1ea) | Jan 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [6759388aa1](https://linux-hardware.org/?probe=6759388aa1) | Jan 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [6a368aefbd](https://linux-hardware.org/?probe=6a368aefbd) | Jan 09, 2022 |
| ASUSTek       | PRIME H310M-K               | [3b4d6e5abd](https://linux-hardware.org/?probe=3b4d6e5abd) | Jan 08, 2022 |
| ASRock        | G31M-S                      | [b33a983889](https://linux-hardware.org/?probe=b33a983889) | Jan 08, 2022 |
| MSI           | H61M-P25                    | [5f095c2bf8](https://linux-hardware.org/?probe=5f095c2bf8) | Jan 08, 2022 |
| Dell          | 042P49 A02                  | [b2a3538121](https://linux-hardware.org/?probe=b2a3538121) | Jan 08, 2022 |
| ASRock        | AM1B-ITX                    | [c374329271](https://linux-hardware.org/?probe=c374329271) | Jan 07, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [e51ad2ec06](https://linux-hardware.org/?probe=e51ad2ec06) | Jan 07, 2022 |
| Dell          | 0YXT71 A02                  | [682c40786b](https://linux-hardware.org/?probe=682c40786b) | Jan 07, 2022 |
| Shuttle       | FB62                        | [704df008d5](https://linux-hardware.org/?probe=704df008d5) | Jan 06, 2022 |
| Shuttle       | FB62                        | [2da02c481d](https://linux-hardware.org/?probe=2da02c481d) | Jan 06, 2022 |
| Gigabyte      | H61M-S2PV                   | [398f9ebe03](https://linux-hardware.org/?probe=398f9ebe03) | Jan 06, 2022 |
| ASUSTek       | Benicia                     | [5459dba29c](https://linux-hardware.org/?probe=5459dba29c) | Jan 06, 2022 |
| Dell          | 0GDG8Y A00                  | [e89e415451](https://linux-hardware.org/?probe=e89e415451) | Jan 05, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [fc860fdb7a](https://linux-hardware.org/?probe=fc860fdb7a) | Jan 05, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [dad1a9143d](https://linux-hardware.org/?probe=dad1a9143d) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | [5694489e55](https://linux-hardware.org/?probe=5694489e55) | Jan 05, 2022 |
| Dell          | 096JG8 A01                  | [fecf0d29c7](https://linux-hardware.org/?probe=fecf0d29c7) | Jan 05, 2022 |
| Gigabyte      | H370M D3H-CF                | [ab12119d4f](https://linux-hardware.org/?probe=ab12119d4f) | Jan 05, 2022 |
| ASUSTek       | NODUSM3                     | [88f0b2e09a](https://linux-hardware.org/?probe=88f0b2e09a) | Jan 05, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [32d0fda197](https://linux-hardware.org/?probe=32d0fda197) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | [2c3f24c851](https://linux-hardware.org/?probe=2c3f24c851) | Jan 04, 2022 |
| MSI           | H61M-P25                    | [3679d16bdb](https://linux-hardware.org/?probe=3679d16bdb) | Jan 04, 2022 |
| HP            | 3047h                       | [8faa43060a](https://linux-hardware.org/?probe=8faa43060a) | Jan 04, 2022 |
| MSI           | H61M-P25                    | [004392f0ef](https://linux-hardware.org/?probe=004392f0ef) | Jan 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [b838b1e1cc](https://linux-hardware.org/?probe=b838b1e1cc) | Jan 04, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [d2a528221c](https://linux-hardware.org/?probe=d2a528221c) | Jan 03, 2022 |
| ASRock        | B450M Steel Legend          | [81a98f588a](https://linux-hardware.org/?probe=81a98f588a) | Jan 02, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [a769ac4242](https://linux-hardware.org/?probe=a769ac4242) | Jan 01, 2022 |
| HP            | 3031h                       | [cc5f90a5be](https://linux-hardware.org/?probe=cc5f90a5be) | Jan 01, 2022 |
| Gigabyte      | H110M-H-CF                  | [4754d83d04](https://linux-hardware.org/?probe=4754d83d04) | Jan 01, 2022 |
| Acer          | Aspire M3970                | [e10ce7d132](https://linux-hardware.org/?probe=e10ce7d132) | Dec 31, 2021 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [5b97adba13](https://linux-hardware.org/?probe=5b97adba13) | Dec 31, 2021 |
| ECS           | G31T-M7                     | [8cd5d79924](https://linux-hardware.org/?probe=8cd5d79924) | Dec 31, 2021 |
| ECS           | G31T-M7                     | [9ebfb53472](https://linux-hardware.org/?probe=9ebfb53472) | Dec 31, 2021 |
| HP            | 1998                        | [07bdd01c09](https://linux-hardware.org/?probe=07bdd01c09) | Dec 31, 2021 |
| Dell          | 088DT1 A01                  | [2599126547](https://linux-hardware.org/?probe=2599126547) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | [1c32c6a027](https://linux-hardware.org/?probe=1c32c6a027) | Dec 30, 2021 |
| MSI           | H81M-P33                    | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| ASRock        | Z87 Pro4                    | [2a8588f61e](https://linux-hardware.org/?probe=2a8588f61e) | Dec 29, 2021 |
| Gigabyte      | Z97-HD3                     | [5536599b58](https://linux-hardware.org/?probe=5536599b58) | Dec 28, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [127916f66f](https://linux-hardware.org/?probe=127916f66f) | Dec 28, 2021 |
| Packard Be... | MCP73VT-PM                  | [c4f47dca10](https://linux-hardware.org/?probe=c4f47dca10) | Dec 27, 2021 |
| ASUSTek       | H81-PLUS                    | [60ba71333c](https://linux-hardware.org/?probe=60ba71333c) | Dec 27, 2021 |
| Intel         | Cherry Trail CR H91596-3... | [cb83ad3d6c](https://linux-hardware.org/?probe=cb83ad3d6c) | Dec 27, 2021 |
| Intel         | Cherry Trail CR H91596-3... | [76e7cab82a](https://linux-hardware.org/?probe=76e7cab82a) | Dec 26, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [39f562f189](https://linux-hardware.org/?probe=39f562f189) | Dec 25, 2021 |
| Dell          | 0VNP2H A00                  | [e64f51e52a](https://linux-hardware.org/?probe=e64f51e52a) | Dec 24, 2021 |
| Gigabyte      | H57M-USB3                   | [ee70d6b4b4](https://linux-hardware.org/?probe=ee70d6b4b4) | Dec 24, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [5c4ae9536f](https://linux-hardware.org/?probe=5c4ae9536f) | Dec 24, 2021 |
| Gigabyte      | EG41MFT-US2H                | [2bfb4702c3](https://linux-hardware.org/?probe=2bfb4702c3) | Dec 23, 2021 |
| Gigabyte      | EG41MFT-US2H                | [b29d64341c](https://linux-hardware.org/?probe=b29d64341c) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [69d74c89b4](https://linux-hardware.org/?probe=69d74c89b4) | Dec 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [4453e33b88](https://linux-hardware.org/?probe=4453e33b88) | Dec 22, 2021 |
| ASRock        | B450 Pro4                   | [0832f6d0fd](https://linux-hardware.org/?probe=0832f6d0fd) | Dec 22, 2021 |
| ASUSTek       | P8Z77-M                     | [667e676c78](https://linux-hardware.org/?probe=667e676c78) | Dec 21, 2021 |
| ASRock        | A320M-DVS R4.0              | [c38dcdb848](https://linux-hardware.org/?probe=c38dcdb848) | Dec 21, 2021 |
| Dell          | 03NVJ6 A02                  | [685819bc74](https://linux-hardware.org/?probe=685819bc74) | Dec 20, 2021 |
| ASRock        | B450M-HDV R4.0              | [210f1589c4](https://linux-hardware.org/?probe=210f1589c4) | Dec 20, 2021 |
| ASRock        | B450M Pro4                  | [b40c57df26](https://linux-hardware.org/?probe=b40c57df26) | Dec 20, 2021 |
| ASUSTek       | PRIME B350M-A               | [09d76b803c](https://linux-hardware.org/?probe=09d76b803c) | Dec 20, 2021 |
| Intel         | B75                         | [9178fa9053](https://linux-hardware.org/?probe=9178fa9053) | Dec 19, 2021 |
| ASRock        | B450M-HDV R4.0              | [35182a65bb](https://linux-hardware.org/?probe=35182a65bb) | Dec 19, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [717b852409](https://linux-hardware.org/?probe=717b852409) | Dec 19, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [38a4bbf8d3](https://linux-hardware.org/?probe=38a4bbf8d3) | Dec 19, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f86ed2049c](https://linux-hardware.org/?probe=f86ed2049c) | Dec 19, 2021 |
| Dell          | 0HY9JP A02                  | [063c3ec5d2](https://linux-hardware.org/?probe=063c3ec5d2) | Dec 19, 2021 |
| Unknown       | Unknown                     | [86f9e26389](https://linux-hardware.org/?probe=86f9e26389) | Dec 19, 2021 |
| Unknown       | Unknown                     | [0b6e5a76bf](https://linux-hardware.org/?probe=0b6e5a76bf) | Dec 19, 2021 |
| ASUSTek       | P5Q PRO TURBO               | [4c845a464c](https://linux-hardware.org/?probe=4c845a464c) | Dec 19, 2021 |
| Acer          | Aspire XC-330               | [1803a4622c](https://linux-hardware.org/?probe=1803a4622c) | Dec 19, 2021 |
| ASUSTek       | Benicia                     | [e572d5ceff](https://linux-hardware.org/?probe=e572d5ceff) | Dec 19, 2021 |
| Shuttle       | FH61V                       | [39d341d8be](https://linux-hardware.org/?probe=39d341d8be) | Dec 19, 2021 |
| Dell          | 0MN1TX A01                  | [312bd0bfd8](https://linux-hardware.org/?probe=312bd0bfd8) | Dec 18, 2021 |
| MSI           | MS-7053                     | [3e9330e811](https://linux-hardware.org/?probe=3e9330e811) | Dec 18, 2021 |
| MSI           | MS-7053                     | [b32db3cd18](https://linux-hardware.org/?probe=b32db3cd18) | Dec 18, 2021 |
| Unknown       | C51GM-M                     | [91386c4f7c](https://linux-hardware.org/?probe=91386c4f7c) | Dec 17, 2021 |
| Lenovo        | ThinkCentre M57e 9489W1U    | [ba5156ef68](https://linux-hardware.org/?probe=ba5156ef68) | Dec 17, 2021 |
| Dell          | 0Y2K8N A01                  | [2e29930670](https://linux-hardware.org/?probe=2e29930670) | Dec 17, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [dfbadf6708](https://linux-hardware.org/?probe=dfbadf6708) | Dec 17, 2021 |
| Unknown       | C51GM-M                     | [cd4d96fefa](https://linux-hardware.org/?probe=cd4d96fefa) | Dec 17, 2021 |
| Acer          | Aspire XC-330               | [61dd8de51b](https://linux-hardware.org/?probe=61dd8de51b) | Dec 16, 2021 |
| Dell          | 0D24M8 A01                  | [a306863279](https://linux-hardware.org/?probe=a306863279) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | [2acaeac0de](https://linux-hardware.org/?probe=2acaeac0de) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | [2c39bc3721](https://linux-hardware.org/?probe=2c39bc3721) | Dec 14, 2021 |
| HP            | 18E5                        | [88f87a7a1b](https://linux-hardware.org/?probe=88f87a7a1b) | Dec 14, 2021 |
| ASUSTek       | AM1M-A                      | [5113655631](https://linux-hardware.org/?probe=5113655631) | Dec 14, 2021 |
| HP            | 2179                        | [c2dd79384a](https://linux-hardware.org/?probe=c2dd79384a) | Dec 14, 2021 |
| ASUSTek       | VM40B                       | [c53952beab](https://linux-hardware.org/?probe=c53952beab) | Dec 14, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [788c6b0550](https://linux-hardware.org/?probe=788c6b0550) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [b471a79340](https://linux-hardware.org/?probe=b471a79340) | Dec 13, 2021 |
| Dell          | 0M5DCD A00                  | [447bffefc3](https://linux-hardware.org/?probe=447bffefc3) | Dec 13, 2021 |
| Intel         | DQ87PG AAG74154-403         | [e2a6d57861](https://linux-hardware.org/?probe=e2a6d57861) | Dec 13, 2021 |
| Intel         | B75                         | [652828f7b9](https://linux-hardware.org/?probe=652828f7b9) | Dec 13, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [6b33adaacf](https://linux-hardware.org/?probe=6b33adaacf) | Dec 13, 2021 |
| ASUSTek       | PRIME B350M-A               | [aa92a82326](https://linux-hardware.org/?probe=aa92a82326) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [8e659f2b89](https://linux-hardware.org/?probe=8e659f2b89) | Dec 12, 2021 |
| ASUSTek       | PRIME B360M-K               | [abb6a94373](https://linux-hardware.org/?probe=abb6a94373) | Dec 12, 2021 |
| Gigabyte      | H97M-D3H                    | [d9e04ee743](https://linux-hardware.org/?probe=d9e04ee743) | Dec 12, 2021 |
| Gigabyte      | H97M-D3H                    | [1d768c3c63](https://linux-hardware.org/?probe=1d768c3c63) | Dec 12, 2021 |
| ASRock        | B450M Pro4                  | [6a8480268d](https://linux-hardware.org/?probe=6a8480268d) | Dec 12, 2021 |
| Dell          | 02YYK5 A01                  | [1301218290](https://linux-hardware.org/?probe=1301218290) | Dec 11, 2021 |
| HP            | 339A                        | [7081fc45a3](https://linux-hardware.org/?probe=7081fc45a3) | Dec 11, 2021 |
| HP            | 304Ah                       | [6d87535158](https://linux-hardware.org/?probe=6d87535158) | Dec 10, 2021 |
| eMachines     | EL1850G                     | [ccd7758cbe](https://linux-hardware.org/?probe=ccd7758cbe) | Dec 10, 2021 |
| ASUSTek       | NARRA3                      | [028ad01454](https://linux-hardware.org/?probe=028ad01454) | Dec 09, 2021 |
| Biostar       | A320MH                      | [fbbe7a436a](https://linux-hardware.org/?probe=fbbe7a436a) | Dec 09, 2021 |
| Biostar       | A320MH                      | [3870a17dfe](https://linux-hardware.org/?probe=3870a17dfe) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | [0e19f8e2ae](https://linux-hardware.org/?probe=0e19f8e2ae) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | [a37d2cc42f](https://linux-hardware.org/?probe=a37d2cc42f) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | [1a5b0a8d39](https://linux-hardware.org/?probe=1a5b0a8d39) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | [f4d8f580dc](https://linux-hardware.org/?probe=f4d8f580dc) | Dec 09, 2021 |
| ASUSTek       | NARRA3                      | [c64aed90a9](https://linux-hardware.org/?probe=c64aed90a9) | Dec 08, 2021 |
| HP            | 3047h                       | [b389ca7104](https://linux-hardware.org/?probe=b389ca7104) | Dec 08, 2021 |
| ASUSTek       | M3A78-EM                    | [b041919f38](https://linux-hardware.org/?probe=b041919f38) | Dec 08, 2021 |
| HP            | 87C3                        | [16cc7e0bcb](https://linux-hardware.org/?probe=16cc7e0bcb) | Dec 07, 2021 |
| HP            | 81B4 01                     | [1477bd5a44](https://linux-hardware.org/?probe=1477bd5a44) | Dec 07, 2021 |
| Dell          | 0T656F A01                  | [552210319c](https://linux-hardware.org/?probe=552210319c) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [2ce114a1c7](https://linux-hardware.org/?probe=2ce114a1c7) | Dec 06, 2021 |
| INTELBRAS     | IE-G41T-M7                  | [ff7f8750ea](https://linux-hardware.org/?probe=ff7f8750ea) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [ce3d88a2a2](https://linux-hardware.org/?probe=ce3d88a2a2) | Dec 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [49fe509dd2](https://linux-hardware.org/?probe=49fe509dd2) | Dec 04, 2021 |
| Dell          | 0GY6Y8 A03                  | [4d2767bbdc](https://linux-hardware.org/?probe=4d2767bbdc) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [e6b7b57ea7](https://linux-hardware.org/?probe=e6b7b57ea7) | Dec 04, 2021 |
| Dell          | 0G254H A00                  | [11897b38da](https://linux-hardware.org/?probe=11897b38da) | Dec 03, 2021 |
| HP            | 2B44                        | [b62df43777](https://linux-hardware.org/?probe=b62df43777) | Dec 03, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [e39465a63b](https://linux-hardware.org/?probe=e39465a63b) | Dec 03, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [ad90caf60d](https://linux-hardware.org/?probe=ad90caf60d) | Dec 03, 2021 |
| Pegatron      | JESSE                       | [9091bacc33](https://linux-hardware.org/?probe=9091bacc33) | Dec 03, 2021 |
| ASUSTek       | LEONITE                     | [704345be69](https://linux-hardware.org/?probe=704345be69) | Dec 03, 2021 |
| Biostar       | A780L3C                     | [a50e3d0532](https://linux-hardware.org/?probe=a50e3d0532) | Dec 02, 2021 |
| Foxconn       | 2A8C                        | [8d24862bd6](https://linux-hardware.org/?probe=8d24862bd6) | Dec 02, 2021 |
| Biostar       | A780L3C                     | [497f29a343](https://linux-hardware.org/?probe=497f29a343) | Dec 02, 2021 |
| Dell          | 0WR7PY A02                  | [1255f30eea](https://linux-hardware.org/?probe=1255f30eea) | Dec 01, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [bd33efb6f7](https://linux-hardware.org/?probe=bd33efb6f7) | Dec 01, 2021 |
| HP            | 339A                        | [4a377796cf](https://linux-hardware.org/?probe=4a377796cf) | Dec 01, 2021 |
| Dell          | 0PU052                      | [a943d9f217](https://linux-hardware.org/?probe=a943d9f217) | Dec 01, 2021 |
| Dell          | 0WR7PY A02                  | [d51c794107](https://linux-hardware.org/?probe=d51c794107) | Nov 30, 2021 |
| Dell          | 0WMJ54 A01                  | [5fa96d5863](https://linux-hardware.org/?probe=5fa96d5863) | Nov 30, 2021 |
| HP            | 8299                        | [6eb5c6d54a](https://linux-hardware.org/?probe=6eb5c6d54a) | Nov 30, 2021 |
| Medion        | MS-7707                     | [3d0a46f2ef](https://linux-hardware.org/?probe=3d0a46f2ef) | Nov 30, 2021 |
| ASRock        | H67DE3                      | [d710784470](https://linux-hardware.org/?probe=d710784470) | Nov 30, 2021 |
| HP            | 8299                        | [7bd1df0e4d](https://linux-hardware.org/?probe=7bd1df0e4d) | Nov 29, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [24b15affa6](https://linux-hardware.org/?probe=24b15affa6) | Nov 29, 2021 |
| ASUSTek       | P8Z77-V LX                  | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| ECS           | GeForce6100PM-M2            | [032a2baaca](https://linux-hardware.org/?probe=032a2baaca) | Nov 28, 2021 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | [382bfc4a86](https://linux-hardware.org/?probe=382bfc4a86) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [cd296f933b](https://linux-hardware.org/?probe=cd296f933b) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [44c0cf428f](https://linux-hardware.org/?probe=44c0cf428f) | Nov 28, 2021 |
| MSI           | X370 GAMING PLUS            | [0b71d2652d](https://linux-hardware.org/?probe=0b71d2652d) | Nov 27, 2021 |
| Dell          | 0VNP2H A00                  | [803e55fd86](https://linux-hardware.org/?probe=803e55fd86) | Nov 27, 2021 |
| ASUSTek       | M4A78T-E                    | [df3010e1b8](https://linux-hardware.org/?probe=df3010e1b8) | Nov 27, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [ae57475767](https://linux-hardware.org/?probe=ae57475767) | Nov 27, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [3925ce16ae](https://linux-hardware.org/?probe=3925ce16ae) | Nov 27, 2021 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | [cd58d98b6a](https://linux-hardware.org/?probe=cd58d98b6a) | Nov 27, 2021 |
| ASRock        | B450M Pro4                  | [bb642022a6](https://linux-hardware.org/?probe=bb642022a6) | Nov 27, 2021 |
| ASRock        | ALiveNF6G-DVI               | [2761f434e8](https://linux-hardware.org/?probe=2761f434e8) | Nov 26, 2021 |
| HP            | 2179                        | [121210497a](https://linux-hardware.org/?probe=121210497a) | Nov 25, 2021 |
| Dell          | 0VNP2H A00                  | [fe9de9a896](https://linux-hardware.org/?probe=fe9de9a896) | Nov 25, 2021 |
| HP            | 18E7                        | [7385ca30d4](https://linux-hardware.org/?probe=7385ca30d4) | Nov 23, 2021 |
| Pegatron      | 2A86E01                     | [b57d9ec4a4](https://linux-hardware.org/?probe=b57d9ec4a4) | Nov 23, 2021 |
| Gigabyte      | H61N-USB3                   | [83e388363c](https://linux-hardware.org/?probe=83e388363c) | Nov 23, 2021 |
| Dell          | 0PU052                      | [a41541bab5](https://linux-hardware.org/?probe=a41541bab5) | Nov 23, 2021 |
| Gigabyte      | G41MT-S2                    | [8031417427](https://linux-hardware.org/?probe=8031417427) | Nov 23, 2021 |
| Intel         | DB65AL AAG12530-309         | [44c8025eee](https://linux-hardware.org/?probe=44c8025eee) | Nov 23, 2021 |
| MSI           | B360M PRO-VD                | [e1f68c6698](https://linux-hardware.org/?probe=e1f68c6698) | Nov 22, 2021 |
| Gigabyte      | H77M-D3H                    | [2819a870a8](https://linux-hardware.org/?probe=2819a870a8) | Nov 22, 2021 |
| HP            | 0AA4h                       | [22c6e4fffd](https://linux-hardware.org/?probe=22c6e4fffd) | Nov 22, 2021 |
| ASRock        | P67 Extreme6                | [54cd91039c](https://linux-hardware.org/?probe=54cd91039c) | Nov 22, 2021 |
| Gigabyte      | H57M-USB3                   | [97409a8d1c](https://linux-hardware.org/?probe=97409a8d1c) | Nov 22, 2021 |
| Gigabyte      | H57M-USB3                   | [e0e4ee802a](https://linux-hardware.org/?probe=e0e4ee802a) | Nov 22, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [fa922e6e20](https://linux-hardware.org/?probe=fa922e6e20) | Nov 22, 2021 |
| ASRock        | 775i945GZ                   | [8d3cfee95d](https://linux-hardware.org/?probe=8d3cfee95d) | Nov 22, 2021 |
| ASRock        | ALiveNF6G-DVI               | [23a839f917](https://linux-hardware.org/?probe=23a839f917) | Nov 21, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [ae91e01910](https://linux-hardware.org/?probe=ae91e01910) | Nov 21, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [c239a2a68f](https://linux-hardware.org/?probe=c239a2a68f) | Nov 21, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [f9ca6a2f97](https://linux-hardware.org/?probe=f9ca6a2f97) | Nov 21, 2021 |
| Dell          | 03NVJ6 A02                  | [00a8a0ab87](https://linux-hardware.org/?probe=00a8a0ab87) | Nov 21, 2021 |
| Gigabyte      | B450M GAMING                | [2355c29da1](https://linux-hardware.org/?probe=2355c29da1) | Nov 21, 2021 |
| Gigabyte      | H55M-UD2H                   | [16e0d2d71a](https://linux-hardware.org/?probe=16e0d2d71a) | Nov 21, 2021 |
| ASUSTek       | P5PL2-E                     | [00ec0123c5](https://linux-hardware.org/?probe=00ec0123c5) | Nov 20, 2021 |
| Dell          | 0KWVT8 A00                  | [a6f003d198](https://linux-hardware.org/?probe=a6f003d198) | Nov 20, 2021 |
| LattePanda    | Alpha                       | [24c2fc6f7b](https://linux-hardware.org/?probe=24c2fc6f7b) | Nov 20, 2021 |
| LattePanda    | Alpha                       | [4aa879f7ac](https://linux-hardware.org/?probe=4aa879f7ac) | Nov 20, 2021 |
| ASUSTek       | P5PL2-E                     | [12db2d9ccc](https://linux-hardware.org/?probe=12db2d9ccc) | Nov 19, 2021 |
| ASRock        | B450M Pro4 R2.0             | [8a53d67102](https://linux-hardware.org/?probe=8a53d67102) | Nov 19, 2021 |
| MSI           | 970 GAMING                  | [ac8f38525e](https://linux-hardware.org/?probe=ac8f38525e) | Nov 19, 2021 |
| ASUSTek       | P8Z77-V LX                  | [6807e3fa8c](https://linux-hardware.org/?probe=6807e3fa8c) | Nov 18, 2021 |
| Dell          | 0KWVT8 A00                  | [93b90c3da4](https://linux-hardware.org/?probe=93b90c3da4) | Nov 18, 2021 |
| ASRock        | G31M-VS2                    | [8bc6042d3f](https://linux-hardware.org/?probe=8bc6042d3f) | Nov 17, 2021 |
| ASRock        | X370M-HDV                   | [a991fee412](https://linux-hardware.org/?probe=a991fee412) | Nov 17, 2021 |
| Dell          | 0GXM1W A01                  | [7e9f638277](https://linux-hardware.org/?probe=7e9f638277) | Nov 17, 2021 |
| Gigabyte      | VM900M                      | [80536ac6e5](https://linux-hardware.org/?probe=80536ac6e5) | Nov 16, 2021 |
| Gigabyte      | VM900M                      | [7cd9a0a1ca](https://linux-hardware.org/?probe=7cd9a0a1ca) | Nov 16, 2021 |
| ASUSTek       | P5KPL-AM                    | [0cae2ebf49](https://linux-hardware.org/?probe=0cae2ebf49) | Nov 16, 2021 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [bb50b7d97c](https://linux-hardware.org/?probe=bb50b7d97c) | Nov 16, 2021 |
| MSI           | 2A9C                        | [80ef0caf18](https://linux-hardware.org/?probe=80ef0caf18) | Nov 15, 2021 |
| MSI           | 2A9C                        | [44e1dcea05](https://linux-hardware.org/?probe=44e1dcea05) | Nov 15, 2021 |
| Gigabyte      | H170-D3HP-CF                | [e90a1881c7](https://linux-hardware.org/?probe=e90a1881c7) | Nov 14, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [a92c32b60a](https://linux-hardware.org/?probe=a92c32b60a) | Nov 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [542b1538bf](https://linux-hardware.org/?probe=542b1538bf) | Nov 14, 2021 |
| Dell          | 0UY253 A00                  | [274a0a6b16](https://linux-hardware.org/?probe=274a0a6b16) | Nov 14, 2021 |
| HP            | 8653 A                      | [88b53507c9](https://linux-hardware.org/?probe=88b53507c9) | Nov 13, 2021 |
| HP            | 3048h                       | [200317605d](https://linux-hardware.org/?probe=200317605d) | Nov 13, 2021 |
| Dell          | 0GXM1W A02                  | [d446993ec9](https://linux-hardware.org/?probe=d446993ec9) | Nov 13, 2021 |
| ASUSTek       | P5G41T-M LX3                | [8977322809](https://linux-hardware.org/?probe=8977322809) | Nov 13, 2021 |
| HP            | 1790                        | [e86cdf904a](https://linux-hardware.org/?probe=e86cdf904a) | Nov 12, 2021 |
| ASUSTek       | M5A78L LE                   | [d342b54224](https://linux-hardware.org/?probe=d342b54224) | Nov 12, 2021 |
| HP            | 339A                        | [6dc037bf1f](https://linux-hardware.org/?probe=6dc037bf1f) | Nov 11, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [d0eae9ef10](https://linux-hardware.org/?probe=d0eae9ef10) | Nov 11, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [7a2464824d](https://linux-hardware.org/?probe=7a2464824d) | Nov 11, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [c8e4265515](https://linux-hardware.org/?probe=c8e4265515) | Nov 11, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [eece1d5528](https://linux-hardware.org/?probe=eece1d5528) | Nov 11, 2021 |
| ASUSTek       | H81M-P PLUS                 | [1841ab2aff](https://linux-hardware.org/?probe=1841ab2aff) | Nov 10, 2021 |
| ASUSTek       | A68HM-PLUS                  | [0e688f660f](https://linux-hardware.org/?probe=0e688f660f) | Nov 10, 2021 |
| ASUSTek       | M5A97                       | [20a705fd56](https://linux-hardware.org/?probe=20a705fd56) | Nov 10, 2021 |
| HP            | 8653 A                      | [f84c67582a](https://linux-hardware.org/?probe=f84c67582a) | Nov 09, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [e7579f2fcf](https://linux-hardware.org/?probe=e7579f2fcf) | Nov 09, 2021 |
| HP            | 1790                        | [6030cabe49](https://linux-hardware.org/?probe=6030cabe49) | Nov 09, 2021 |
| HP            | 1825                        | [7cf6c3590a](https://linux-hardware.org/?probe=7cf6c3590a) | Nov 09, 2021 |
| Dell          | 0HD5W2 A00                  | [d4c15ae33a](https://linux-hardware.org/?probe=d4c15ae33a) | Nov 08, 2021 |
| MSI           | B450M MORTAR MAX            | [84c316ee57](https://linux-hardware.org/?probe=84c316ee57) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | [886c08185e](https://linux-hardware.org/?probe=886c08185e) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | [e141b2d36a](https://linux-hardware.org/?probe=e141b2d36a) | Nov 08, 2021 |
| Foxconn       | H61M/H61M-S                 | [62ae26dca0](https://linux-hardware.org/?probe=62ae26dca0) | Nov 07, 2021 |
| Dell          | 0HY9JP A00                  | [05c38bf92c](https://linux-hardware.org/?probe=05c38bf92c) | Nov 07, 2021 |
| ASUSTek       | A68HM-PLUS                  | [384fb31833](https://linux-hardware.org/?probe=384fb31833) | Nov 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [f57575ffaf](https://linux-hardware.org/?probe=f57575ffaf) | Nov 06, 2021 |
| Dell          | 0VNP2H A02                  | [5402226d98](https://linux-hardware.org/?probe=5402226d98) | Nov 06, 2021 |
| ASUSTek       | M5A78L-M LX                 | [e6e813115f](https://linux-hardware.org/?probe=e6e813115f) | Nov 06, 2021 |
| HP            | 0A98h                       | [110c37e799](https://linux-hardware.org/?probe=110c37e799) | Nov 06, 2021 |
| ASUSTek       | A68HM-PLUS                  | [7b21a0bc71](https://linux-hardware.org/?probe=7b21a0bc71) | Nov 06, 2021 |
| Dell          | 0NKW6Y A00                  | [82a09e132d](https://linux-hardware.org/?probe=82a09e132d) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [4be9b40ea1](https://linux-hardware.org/?probe=4be9b40ea1) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [173116149c](https://linux-hardware.org/?probe=173116149c) | Nov 05, 2021 |
| Gigabyte      | F2A78M-D3H                  | [43e09b8e80](https://linux-hardware.org/?probe=43e09b8e80) | Nov 05, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | [1383828428](https://linux-hardware.org/?probe=1383828428) | Nov 05, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | [f5ee7a26d5](https://linux-hardware.org/?probe=f5ee7a26d5) | Nov 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [3e4d5dd09d](https://linux-hardware.org/?probe=3e4d5dd09d) | Nov 05, 2021 |
| Foxconn       | H61M/H61M-S                 | [7f3894059d](https://linux-hardware.org/?probe=7f3894059d) | Nov 04, 2021 |
| HP            | 18E4                        | [3069846b25](https://linux-hardware.org/?probe=3069846b25) | Nov 04, 2021 |
| MSI           | G41M-P23                    | [82e51e3f78](https://linux-hardware.org/?probe=82e51e3f78) | Nov 04, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [d7a405763d](https://linux-hardware.org/?probe=d7a405763d) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASRock        | 970M Pro3                   | [6da9b773d5](https://linux-hardware.org/?probe=6da9b773d5) | Nov 03, 2021 |
| Gigabyte      | B450 AORUS M                | [0b2266e44a](https://linux-hardware.org/?probe=0b2266e44a) | Nov 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [2d26d5b578](https://linux-hardware.org/?probe=2d26d5b578) | Nov 02, 2021 |
| ASUSTek       | P8Z77-V LX                  | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| Pegatron      | IPPCR-SS                    | [0179d16327](https://linux-hardware.org/?probe=0179d16327) | Nov 02, 2021 |
| ASUSTek       | M11AD                       | [0cb5032c53](https://linux-hardware.org/?probe=0cb5032c53) | Nov 02, 2021 |
| Gigabyte      | GA-E6010N                   | [3c81474040](https://linux-hardware.org/?probe=3c81474040) | Nov 01, 2021 |
| Gigabyte      | GA-E6010N                   | [2a2aaffd43](https://linux-hardware.org/?probe=2a2aaffd43) | Nov 01, 2021 |
| ASRock        | FM2A55M-HD+                 | [42cd4d28bd](https://linux-hardware.org/?probe=42cd4d28bd) | Nov 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | [e52e9002d0](https://linux-hardware.org/?probe=e52e9002d0) | Oct 31, 2021 |
| eMachines     | EL1850G                     | [01dbf1b5ec](https://linux-hardware.org/?probe=01dbf1b5ec) | Oct 31, 2021 |
| MSI           | P55-CD53                    | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| Unknown       | Unknown                     | [75cc8a67e9](https://linux-hardware.org/?probe=75cc8a67e9) | Oct 31, 2021 |
| ASRock        | B85M-HDS                    | [111e98ddef](https://linux-hardware.org/?probe=111e98ddef) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [6cee757cf0](https://linux-hardware.org/?probe=6cee757cf0) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [96c9053284](https://linux-hardware.org/?probe=96c9053284) | Oct 31, 2021 |
| Dell          | 06NWYK A01                  | [497c824fd5](https://linux-hardware.org/?probe=497c824fd5) | Oct 31, 2021 |
| ASRock        | B85M-HDS                    | [69dd0cf598](https://linux-hardware.org/?probe=69dd0cf598) | Oct 30, 2021 |
| Dell          | 06NWYK A01                  | [1d0625eb89](https://linux-hardware.org/?probe=1d0625eb89) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [867e533368](https://linux-hardware.org/?probe=867e533368) | Oct 30, 2021 |
| ASUSTek       | P5K SE/EPU                  | [80adff7646](https://linux-hardware.org/?probe=80adff7646) | Oct 30, 2021 |
| Dell          | 0GY6Y8 A02                  | [1a267b14d3](https://linux-hardware.org/?probe=1a267b14d3) | Oct 29, 2021 |
| Dell          | 0GY6Y8 A02                  | [5b4cea000b](https://linux-hardware.org/?probe=5b4cea000b) | Oct 29, 2021 |
| ASRock        | B450 Gaming K4              | [b67ec8af25](https://linux-hardware.org/?probe=b67ec8af25) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | [4e19df8e3c](https://linux-hardware.org/?probe=4e19df8e3c) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | [c220480b4c](https://linux-hardware.org/?probe=c220480b4c) | Oct 29, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [a73fabcd4c](https://linux-hardware.org/?probe=a73fabcd4c) | Oct 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [528cec41bc](https://linux-hardware.org/?probe=528cec41bc) | Oct 28, 2021 |
| Alienware     | 08PG26 A00                  | [bb2fd997ab](https://linux-hardware.org/?probe=bb2fd997ab) | Oct 28, 2021 |
| ASRock        | FM2A88X Extreme6+           | [b676d9030a](https://linux-hardware.org/?probe=b676d9030a) | Oct 28, 2021 |
| MSI           | MAG B550M MORTAR            | [08819513f2](https://linux-hardware.org/?probe=08819513f2) | Oct 27, 2021 |
| MSI           | MAG B550M MORTAR            | [4207c6eaac](https://linux-hardware.org/?probe=4207c6eaac) | Oct 27, 2021 |
| Intel         | DH67CL AAG10212-210         | [541092026f](https://linux-hardware.org/?probe=541092026f) | Oct 26, 2021 |
| ASUSTek       | PRIME Z270-P                | [dfb2070b53](https://linux-hardware.org/?probe=dfb2070b53) | Oct 26, 2021 |
| Alienware     | 08PG26 A00                  | [7d6b559bf8](https://linux-hardware.org/?probe=7d6b559bf8) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3862cf57e0](https://linux-hardware.org/?probe=3862cf57e0) | Oct 25, 2021 |
| ASRock        | FM2A55M-HD+                 | [a1cf5282ba](https://linux-hardware.org/?probe=a1cf5282ba) | Oct 25, 2021 |
| ASRock        | H110M-HDS R3.0              | [718ad346b7](https://linux-hardware.org/?probe=718ad346b7) | Oct 25, 2021 |
| HP            | 1850                        | [e8c750c4b9](https://linux-hardware.org/?probe=e8c750c4b9) | Oct 25, 2021 |
| MSI           | 2AE0                        | [64a3b3ae41](https://linux-hardware.org/?probe=64a3b3ae41) | Oct 24, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [cc46a59d6c](https://linux-hardware.org/?probe=cc46a59d6c) | Oct 24, 2021 |
| MSI           | Z77A-GD65                   | [947cdfd30b](https://linux-hardware.org/?probe=947cdfd30b) | Oct 24, 2021 |
| MSI           | P55-CD53                    | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [fca2aa4310](https://linux-hardware.org/?probe=fca2aa4310) | Oct 23, 2021 |
| Dell          | 0VHXCD A00                  | [7c99a6ed29](https://linux-hardware.org/?probe=7c99a6ed29) | Oct 22, 2021 |
| ASRock        | 970 Pro3 R2.0               | [915961c057](https://linux-hardware.org/?probe=915961c057) | Oct 22, 2021 |
| Biostar       | A68N-5100                   | [bc5b7a2417](https://linux-hardware.org/?probe=bc5b7a2417) | Oct 22, 2021 |
| MSI           | Z68A-G43                    | [b781916d8e](https://linux-hardware.org/?probe=b781916d8e) | Oct 22, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [baee5192b6](https://linux-hardware.org/?probe=baee5192b6) | Oct 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [666f084a0f](https://linux-hardware.org/?probe=666f084a0f) | Oct 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [395d19ae36](https://linux-hardware.org/?probe=395d19ae36) | Oct 21, 2021 |
| Dell          | 0GDG8Y A00                  | [a4bf9808a8](https://linux-hardware.org/?probe=a4bf9808a8) | Oct 21, 2021 |
| HP            | 1589                        | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| Unknown       | Phitronics G41-M3           | [a6ccedb5bd](https://linux-hardware.org/?probe=a6ccedb5bd) | Oct 20, 2021 |
| Unknown       | Phitronics G41-M3           | [fbe886aee7](https://linux-hardware.org/?probe=fbe886aee7) | Oct 20, 2021 |
| Unknown       | Unknown                     | [8c412b3b5b](https://linux-hardware.org/?probe=8c412b3b5b) | Oct 20, 2021 |
| Gigabyte      | B75M-D2V                    | [9fc60b0ba8](https://linux-hardware.org/?probe=9fc60b0ba8) | Oct 19, 2021 |
| Dell          | 0PU052                      | [1bb0034b64](https://linux-hardware.org/?probe=1bb0034b64) | Oct 19, 2021 |
| HP            | 2B38                        | [2cf327f158](https://linux-hardware.org/?probe=2cf327f158) | Oct 18, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [2f5f509752](https://linux-hardware.org/?probe=2f5f509752) | Oct 18, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | [a7ea75f7c5](https://linux-hardware.org/?probe=a7ea75f7c5) | Oct 18, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [9f22e32d08](https://linux-hardware.org/?probe=9f22e32d08) | Oct 17, 2021 |
| ASUSTek       | P6T                         | [69397b40d4](https://linux-hardware.org/?probe=69397b40d4) | Oct 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [058d7e8e3e](https://linux-hardware.org/?probe=058d7e8e3e) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [ce2e0740c8](https://linux-hardware.org/?probe=ce2e0740c8) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [a3dbbf3c03](https://linux-hardware.org/?probe=a3dbbf3c03) | Oct 17, 2021 |
| Lenovo        | SHARKBAY NOK                | [5de4ff60b0](https://linux-hardware.org/?probe=5de4ff60b0) | Oct 16, 2021 |
| Gigabyte      | H61M-S2PV                   | [e3806f5c09](https://linux-hardware.org/?probe=e3806f5c09) | Oct 16, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [a89127ff6a](https://linux-hardware.org/?probe=a89127ff6a) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [7de05cdbc3](https://linux-hardware.org/?probe=7de05cdbc3) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [66b0e77a10](https://linux-hardware.org/?probe=66b0e77a10) | Oct 15, 2021 |
| Dell          | 0VHXCD A00                  | [ccd75d2752](https://linux-hardware.org/?probe=ccd75d2752) | Oct 15, 2021 |
| HP            | 09E8h                       | [7faca26f13](https://linux-hardware.org/?probe=7faca26f13) | Oct 14, 2021 |
| HP            | 09E8h                       | [5013f5686b](https://linux-hardware.org/?probe=5013f5686b) | Oct 14, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | [c0beced761](https://linux-hardware.org/?probe=c0beced761) | Oct 14, 2021 |
| ASUSTek       | M5A78L                      | [a027b0f5ba](https://linux-hardware.org/?probe=a027b0f5ba) | Oct 12, 2021 |
| HP            | 81C7 MVB 0C                 | [23d528f392](https://linux-hardware.org/?probe=23d528f392) | Oct 12, 2021 |
| ASUSTek       | M5A78L                      | [071d7e45a0](https://linux-hardware.org/?probe=071d7e45a0) | Oct 11, 2021 |
| Unknown       | Unknown                     | [3598241674](https://linux-hardware.org/?probe=3598241674) | Oct 10, 2021 |
| Biostar       | G41-M7                      | [94efede651](https://linux-hardware.org/?probe=94efede651) | Oct 10, 2021 |
| ASUSTek       | P7H55-M PRO                 | [1892bf50b9](https://linux-hardware.org/?probe=1892bf50b9) | Oct 09, 2021 |
| HP            | 81C7 MVB 0C                 | [5bfcd88031](https://linux-hardware.org/?probe=5bfcd88031) | Oct 09, 2021 |
| Biostar       | G41-M7                      | [4f1889a1de](https://linux-hardware.org/?probe=4f1889a1de) | Oct 09, 2021 |
| Dell          | 0D28YY A02                  | [237a82041b](https://linux-hardware.org/?probe=237a82041b) | Oct 09, 2021 |
| ASUSTek       | H87M-PLUS                   | [f0a1062216](https://linux-hardware.org/?probe=f0a1062216) | Oct 09, 2021 |
| Dell          | 0VHXCD A00                  | [7a2b25ff42](https://linux-hardware.org/?probe=7a2b25ff42) | Oct 08, 2021 |
| Dell          | 04Y8V0 A01                  | [453beab8c3](https://linux-hardware.org/?probe=453beab8c3) | Oct 08, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [c9d3dce156](https://linux-hardware.org/?probe=c9d3dce156) | Oct 08, 2021 |
| eMachines     | EL1352                      | [6164e00f7a](https://linux-hardware.org/?probe=6164e00f7a) | Oct 08, 2021 |
| ASUSTek       | CM5570                      | [75b8bca0fa](https://linux-hardware.org/?probe=75b8bca0fa) | Oct 07, 2021 |
| HP            | 8591                        | [22dca8a98c](https://linux-hardware.org/?probe=22dca8a98c) | Oct 07, 2021 |
| Dell          | 0VHXCD A00                  | [7f81996b23](https://linux-hardware.org/?probe=7f81996b23) | Oct 07, 2021 |
| ASUSTek       | P7H55-M SI                  | [704043deab](https://linux-hardware.org/?probe=704043deab) | Oct 06, 2021 |
| Dell          | 0D6H9T A02                  | [42b9320d55](https://linux-hardware.org/?probe=42b9320d55) | Oct 06, 2021 |
| Gigabyte      | H61M-S2PV                   | [ed77d40eeb](https://linux-hardware.org/?probe=ed77d40eeb) | Oct 05, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [173104cfcf](https://linux-hardware.org/?probe=173104cfcf) | Oct 04, 2021 |
| ASUSTek       | PRIME B360M-K               | [163b47753d](https://linux-hardware.org/?probe=163b47753d) | Oct 03, 2021 |
| MSI           | B150M MORTAR                | [224b713b5c](https://linux-hardware.org/?probe=224b713b5c) | Oct 03, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Zorin 16 | 734      | 54.74%  |
| Zorin 15 | 531      | 39.6%   |
| Zorin 12 | 76       | 5.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Zorin | 1337     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.11.0-38-generic | 62       | 4.1%    |
| 5.11.0-27-generic | 56       | 3.7%    |
| 5.15.0-46-generic | 54       | 3.57%   |
| 5.11.0-40-generic | 50       | 3.3%    |
| 5.13.0-39-generic | 48       | 3.17%   |
| 5.11.0-41-generic | 41       | 2.71%   |
| 5.3.0-40-generic  | 40       | 2.64%   |
| 5.13.0-40-generic | 39       | 2.58%   |
| 5.11.0-43-generic | 36       | 2.38%   |
| 5.15.0-41-generic | 35       | 2.31%   |
| 5.11.0-37-generic | 35       | 2.31%   |
| 5.13.0-30-generic | 33       | 2.18%   |
| 5.4.0-42-generic  | 31       | 2.05%   |
| 5.11.0-34-generic | 31       | 2.05%   |
| 5.13.0-28-generic | 30       | 1.98%   |
| 5.13.0-35-generic | 28       | 1.85%   |
| 5.0.0-37-generic  | 27       | 1.78%   |
| 5.13.0-27-generic | 26       | 1.72%   |
| 5.13.0-41-generic | 25       | 1.65%   |
| 5.13.0-52-generic | 22       | 1.45%   |
| 5.13.0-44-generic | 22       | 1.45%   |
| 5.4.0-58-generic  | 20       | 1.32%   |
| 5.15.0-48-generic | 20       | 1.32%   |
| 5.4.0-72-generic  | 19       | 1.26%   |
| 5.4.0-47-generic  | 19       | 1.26%   |
| 5.3.0-62-generic  | 17       | 1.12%   |
| 5.3.0-51-generic  | 17       | 1.12%   |
| 5.3.0-46-generic  | 17       | 1.12%   |
| 5.13.0-51-generic | 17       | 1.12%   |
| 5.4.0-54-generic  | 16       | 1.06%   |
| 5.3.0-59-generic  | 16       | 1.06%   |
| 5.3.0-53-generic  | 16       | 1.06%   |
| 5.4.0-74-generic  | 15       | 0.99%   |
| 5.4.0-65-generic  | 15       | 0.99%   |
| 5.3.0-28-generic  | 15       | 0.99%   |
| 5.4.0-80-generic  | 14       | 0.93%   |
| 5.4.0-66-generic  | 14       | 0.93%   |
| 5.4.0-48-generic  | 14       | 0.93%   |
| 5.11.0-44-generic | 14       | 0.93%   |
| 5.3.0-42-generic  | 13       | 0.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 333      | 23.89%  |
| 5.4.0   | 302      | 21.66%  |
| 5.13.0  | 283      | 20.3%   |
| 5.3.0   | 158      | 11.33%  |
| 5.15.0  | 120      | 8.61%   |
| 4.15.0  | 75       | 5.38%   |
| 5.0.0   | 58       | 4.16%   |
| 4.18.0  | 27       | 1.94%   |
| 5.8.0   | 26       | 1.87%   |
| 5.8.5   | 1        | 0.07%   |
| 5.7.17  | 1        | 0.07%   |
| 5.7.1   | 1        | 0.07%   |
| 5.7.0   | 1        | 0.07%   |
| 5.19.6  | 1        | 0.07%   |
| 5.19.2  | 1        | 0.07%   |
| 5.17.9  | 1        | 0.07%   |
| 5.17.5  | 1        | 0.07%   |
| 5.17.1  | 1        | 0.07%   |
| 5.15.13 | 1        | 0.07%   |
| 5.14.0  | 1        | 0.07%   |
| 4.4.0   | 1        | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 333      | 23.89%  |
| 5.4     | 302      | 21.66%  |
| 5.13    | 283      | 20.3%   |
| 5.3     | 158      | 11.33%  |
| 5.15    | 121      | 8.68%   |
| 4.15    | 75       | 5.38%   |
| 5.0     | 58       | 4.16%   |
| 5.8     | 27       | 1.94%   |
| 4.18    | 27       | 1.94%   |
| 5.7     | 3        | 0.22%   |
| 5.17    | 3        | 0.22%   |
| 5.19    | 2        | 0.14%   |
| 5.14    | 1        | 0.07%   |
| 4.4     | 1        | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1240     | 92.74%  |
| i686   | 97       | 7.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 999      | 73.4%   |
| XFCE       | 239      | 17.56%  |
| Unknown    | 118      | 8.67%   |
| X-Cinnamon | 1        | 0.07%   |
| MATE       | 1        | 0.07%   |
| KDE5       | 1        | 0.07%   |
| KDE        | 1        | 0.07%   |
| Cinnamon   | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1271     | 94.22%  |
| Unknown | 67       | 4.97%   |
| Wayland | 10       | 0.74%   |
| Tty     | 1        | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1170     | 86.03%  |
| GDM3    | 87       | 6.4%    |
| GDM     | 59       | 4.34%   |
| LightDM | 39       | 2.87%   |
| TDM     | 4        | 0.29%   |
| SDDM    | 1        | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 476      | 35.31%  |
| de_DE   | 117      | 8.68%   |
| pt_BR   | 98       | 7.27%   |
| Unknown | 96       | 7.12%   |
| en_GB   | 92       | 6.82%   |
| it_IT   | 35       | 2.6%    |
| fr_FR   | 33       | 2.45%   |
| en_CA   | 32       | 2.37%   |
| es_ES   | 30       | 2.23%   |
| en_IN   | 30       | 2.23%   |
| pl_PL   | 28       | 2.08%   |
| nl_NL   | 28       | 2.08%   |
| en_AU   | 25       | 1.85%   |
| es_AR   | 20       | 1.48%   |
| es_MX   | 18       | 1.34%   |
| ru_RU   | 17       | 1.26%   |
| hu_HU   | 13       | 0.96%   |
| en_ZA   | 12       | 0.89%   |
| fr_CA   | 10       | 0.74%   |
| sv_SE   | 9        | 0.67%   |
| cs_CZ   | 8        | 0.59%   |
| pt_PT   | 7        | 0.52%   |
| C       | 7        | 0.52%   |
| tr_TR   | 6        | 0.45%   |
| es_CO   | 6        | 0.45%   |
| es_CL   | 6        | 0.45%   |
| nb_NO   | 5        | 0.37%   |
| nl_BE   | 4        | 0.3%    |
| ja_JP   | 4        | 0.3%    |
| es_PE   | 4        | 0.3%    |
| en_NZ   | 4        | 0.3%    |
| el_GR   | 4        | 0.3%    |
| de_CH   | 4        | 0.3%    |
| da_DK   | 4        | 0.3%    |
| bg_BG   | 4        | 0.3%    |
| sr_RS   | 3        | 0.22%   |
| en_PH   | 3        | 0.22%   |
| sl_SI   | 2        | 0.15%   |
| sk_SK   | 2        | 0.15%   |
| ru_UA   | 2        | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 887      | 65.8%   |
| EFI  | 461      | 34.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1257     | 93.81%  |
| Overlay  | 28       | 2.09%   |
| Zfs      | 15       | 1.12%   |
| Btrfs    | 12       | 0.9%    |
| Ext2     | 10       | 0.75%   |
| Unknown  | 10       | 0.75%   |
| Ext3     | 4        | 0.3%    |
| Xfs      | 3        | 0.22%   |
| Reiserfs | 1        | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1268     | 94.7%   |
| GPT     | 51       | 3.81%   |
| MBR     | 20       | 1.49%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1235     | 91.69%  |
| Yes       | 112      | 8.31%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1016     | 74.98%  |
| Yes       | 339      | 25.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 316      | 23.64%  |
| Gigabyte Technology | 208      | 15.56%  |
| Dell                | 141      | 10.55%  |
| ASRock              | 113      | 8.45%   |
| MSI                 | 111      | 8.3%    |
| Hewlett-Packard     | 111      | 8.3%    |
| Lenovo              | 64       | 4.79%   |
| Intel               | 42       | 3.14%   |
| Pegatron            | 26       | 1.94%   |
| Acer                | 21       | 1.57%   |
| Foxconn             | 20       | 1.5%    |
| Biostar             | 19       | 1.42%   |
| Unknown             | 18       | 1.35%   |
| Fujitsu             | 17       | 1.27%   |
| ECS                 | 16       | 1.2%    |
| Medion              | 7        | 0.52%   |
| Shuttle             | 6        | 0.45%   |
| Positivo            | 6        | 0.45%   |
| IBM                 | 4        | 0.3%    |
| Gateway             | 4        | 0.3%    |
| Apple               | 4        | 0.3%    |
| Alienware           | 4        | 0.3%    |
| Packard Bell        | 3        | 0.22%   |
| eMachines           | 3        | 0.22%   |
| BESSTAR Tech        | 3        | 0.22%   |
| ABIT                | 3        | 0.22%   |
| ZOTAC               | 2        | 0.15%   |
| WinFast             | 2        | 0.15%   |
| SiS Technology      | 2        | 0.15%   |
| Semp Toshiba        | 2        | 0.15%   |
| Google              | 2        | 0.15%   |
| Xi3                 | 1        | 0.07%   |
| Wortmann AG         | 1        | 0.07%   |
| Wistron             | 1        | 0.07%   |
| WIPRO               | 1        | 0.07%   |
| TYAN Computer       | 1        | 0.07%   |
| System76            | 1        | 0.07%   |
| Supermicro          | 1        | 0.07%   |
| Soyo                | 1        | 0.07%   |
| Sapphire            | 1        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 30       | 2.24%   |
| Unknown                          | 22       | 1.65%   |
| Dell OptiPlex 7010               | 11       | 0.82%   |
| Dell OptiPlex 790                | 9        | 0.67%   |
| Dell OptiPlex 780                | 8        | 0.6%    |
| MSI MS-7C02                      | 7        | 0.52%   |
| Gigabyte A320M-S2H               | 7        | 0.52%   |
| Dell OptiPlex 990                | 7        | 0.52%   |
| Dell OptiPlex 755                | 7        | 0.52%   |
| ASUS M5A78L-M/USB3               | 7        | 0.52%   |
| Gigabyte B450 AORUS M            | 6        | 0.45%   |
| Gigabyte 970A-DS3P               | 6        | 0.45%   |
| ASUS M5A97 R2.0                  | 6        | 0.45%   |
| MSI MS-7817                      | 5        | 0.37%   |
| HP ProDesk 600 G1 SFF            | 5        | 0.37%   |
| Gigabyte GA-78LMT-USB3 6.0       | 5        | 0.37%   |
| Gigabyte GA-78LMT-USB3           | 5        | 0.37%   |
| Dell Precision WorkStation T3500 | 5        | 0.37%   |
| Dell Inspiron 3847               | 5        | 0.37%   |
| ASUS TUF Gaming X570-PLUS        | 5        | 0.37%   |
| MSI MS-7721                      | 4        | 0.3%    |
| HP Compaq Pro 6300 SFF           | 4        | 0.3%    |
| Gigabyte B450M DS3H              | 4        | 0.3%    |
| Dell Vostro 200                  | 4        | 0.3%    |
| Dell Precision T1600             | 4        | 0.3%    |
| Dell OptiPlex 7040               | 4        | 0.3%    |
| Dell OptiPlex 380                | 4        | 0.3%    |
| Dell OptiPlex 330                | 4        | 0.3%    |
| ASUS P5G41T-M LX3                | 4        | 0.3%    |
| ASRock N68C-S UCC                | 4        | 0.3%    |
| ASRock B450M Pro4                | 4        | 0.3%    |
| ASRock B450 Pro4                 | 4        | 0.3%    |
| Pegatron NE502AV-ABA a6750t      | 3        | 0.22%   |
| MSI MS-7B85                      | 3        | 0.22%   |
| MSI MS-7A38                      | 3        | 0.22%   |
| MSI MS-7693                      | 3        | 0.22%   |
| Intel X79M-S                     | 3        | 0.22%   |
| HP Z600 Workstation              | 3        | 0.22%   |
| HP Compaq 8100 Elite SFF PC      | 3        | 0.22%   |
| HP Compaq 6200 Pro SFF PC        | 3        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 84       | 6.28%   |
| HP Compaq              | 45       | 3.37%   |
| Lenovo ThinkCentre     | 39       | 2.92%   |
| ASUS PRIME             | 37       | 2.77%   |
| ASUS All               | 30       | 2.24%   |
| ASUS ROG               | 26       | 1.94%   |
| Unknown                | 22       | 1.65%   |
| ASUS TUF               | 20       | 1.5%    |
| Dell Precision         | 15       | 1.12%   |
| HP EliteDesk           | 13       | 0.97%   |
| Fujitsu ESPRIMO        | 13       | 0.97%   |
| Gigabyte B450          | 12       | 0.9%    |
| ASUS M5A78L-M          | 12       | 0.9%    |
| Acer Aspire            | 12       | 0.9%    |
| Gigabyte GA-78LMT-USB3 | 11       | 0.82%   |
| Dell Vostro            | 11       | 0.82%   |
| Dell Inspiron          | 11       | 0.82%   |
| ASUS M5A97             | 11       | 0.82%   |
| Lenovo IdeaCentre      | 8        | 0.6%    |
| HP ProDesk             | 8        | 0.6%    |
| Gigabyte X570          | 8        | 0.6%    |
| Gigabyte A320M-S2H     | 8        | 0.6%    |
| ASRock B450            | 8        | 0.6%    |
| MSI MS-7C02            | 7        | 0.52%   |
| ASUS P8H61-M           | 7        | 0.52%   |
| ASUS P5G41T-M          | 7        | 0.52%   |
| Gigabyte B450M         | 6        | 0.45%   |
| Gigabyte 970A-DS3P     | 6        | 0.45%   |
| Dell XPS               | 6        | 0.45%   |
| ASRock B450M           | 6        | 0.45%   |
| MSI MS-7817            | 5        | 0.37%   |
| ASUS P5KPL-AM          | 5        | 0.37%   |
| ASRock N68C-S          | 5        | 0.37%   |
| Acer Veriton           | 5        | 0.37%   |
| MSI MS-7721            | 4        | 0.3%    |
| HP Pavilion            | 4        | 0.3%    |
| Dell Studio            | 4        | 0.3%    |
| ASUS P8Z77-V           | 4        | 0.3%    |
| ASUS P5K               | 4        | 0.3%    |
| ASUS P5GC-MX           | 4        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2011    | 121      | 9.05%   |
| 2012    | 119      | 8.9%    |
| 2013    | 113      | 8.45%   |
| 2018    | 111      | 8.3%    |
| 2010    | 104      | 7.78%   |
| 2009    | 99       | 7.4%    |
| 2014    | 97       | 7.26%   |
| 2008    | 92       | 6.88%   |
| 2007    | 72       | 5.39%   |
| 2020    | 63       | 4.71%   |
| 2019    | 63       | 4.71%   |
| 2017    | 54       | 4.04%   |
| 2016    | 50       | 3.74%   |
| 2021    | 47       | 3.52%   |
| 2015    | 44       | 3.29%   |
| 2006    | 38       | 2.84%   |
| 2005    | 24       | 1.8%    |
| 2004    | 10       | 0.75%   |
| 2022    | 6        | 0.45%   |
| 2003    | 6        | 0.45%   |
| Unknown | 3        | 0.22%   |
| 2002    | 1        | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1337     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1288     | 95.98%  |
| Enabled  | 54       | 4.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1335     | 99.85%  |
| Yes  | 2        | 0.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 280      | 20.62%  |
| 16.01-24.0  | 270      | 19.88%  |
| 3.01-4.0    | 268      | 19.73%  |
| 4.01-8.0    | 199      | 14.65%  |
| 32.01-64.0  | 132      | 9.72%   |
| 1.01-2.0    | 96       | 7.07%   |
| 2.01-3.0    | 42       | 3.09%   |
| 64.01-256.0 | 30       | 2.21%   |
| 0.51-1.0    | 24       | 1.77%   |
| 24.01-32.0  | 17       | 1.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 637      | 44.33%  |
| 2.01-3.0   | 356      | 24.77%  |
| 3.01-4.0   | 146      | 10.16%  |
| 4.01-8.0   | 129      | 8.98%   |
| 0.51-1.0   | 119      | 8.28%   |
| 8.01-16.0  | 29       | 2.02%   |
| 0.01-0.5   | 16       | 1.11%   |
| 16.01-24.0 | 5        | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 667      | 48.58%  |
| 2      | 378      | 27.53%  |
| 3      | 164      | 11.94%  |
| 4      | 74       | 5.39%   |
| 5      | 40       | 2.91%   |
| 6      | 23       | 1.68%   |
| 7      | 9        | 0.66%   |
| 0      | 9        | 0.66%   |
| 8      | 7        | 0.51%   |
| 11     | 1        | 0.07%   |
| 10     | 1        | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 760      | 56.51%  |
| No        | 585      | 43.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1320     | 98.73%  |
| No        | 17       | 1.27%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 702      | 52.15%  |
| Yes       | 644      | 47.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 998      | 73.82%  |
| Yes       | 354      | 26.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 331      | 24.72%  |
| Germany      | 129      | 9.63%   |
| Brazil       | 108      | 8.07%   |
| UK           | 92       | 6.87%   |
| Canada       | 51       | 3.81%   |
| Netherlands  | 47       | 3.51%   |
| Italy        | 44       | 3.29%   |
| Spain        | 35       | 2.61%   |
| France       | 33       | 2.46%   |
| India        | 32       | 2.39%   |
| Poland       | 29       | 2.17%   |
| Australia    | 28       | 2.09%   |
| Argentina    | 25       | 1.87%   |
| Mexico       | 18       | 1.34%   |
| Hungary      | 17       | 1.27%   |
| Denmark      | 15       | 1.12%   |
| Sweden       | 14       | 1.05%   |
| South Africa | 14       | 1.05%   |
| Russia       | 14       | 1.05%   |
| Norway       | 13       | 0.97%   |
| Indonesia    | 13       | 0.97%   |
| Switzerland  | 12       | 0.9%    |
| Greece       | 12       | 0.9%    |
| Czechia      | 11       | 0.82%   |
| Serbia       | 10       | 0.75%   |
| Chile        | 10       | 0.75%   |
| Portugal     | 9        | 0.67%   |
| Colombia     | 9        | 0.67%   |
| Bulgaria     | 8        | 0.6%    |
| Ukraine      | 7        | 0.52%   |
| Turkey       | 7        | 0.52%   |
| Romania      | 7        | 0.52%   |
| Japan        | 7        | 0.52%   |
| Egypt        | 7        | 0.52%   |
| Philippines  | 6        | 0.45%   |
| Malaysia     | 6        | 0.45%   |
| Belgium      | 6        | 0.45%   |
| Austria      | 6        | 0.45%   |
| Slovenia     | 5        | 0.37%   |
| Peru         | 5        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sao Paulo      | 14       | 1.02%   |
| Berlin         | 11       | 0.8%    |
| Athens         | 11       | 0.8%    |
| Rio de Janeiro | 9        | 0.65%   |
| Munich         | 8        | 0.58%   |
| Denver         | 7        | 0.51%   |
| Copenhagen     | 7        | 0.51%   |
| Buenos Aires   | 7        | 0.51%   |
| Zurich         | 6        | 0.44%   |
| Vienna         | 6        | 0.44%   |
| Toronto        | 6        | 0.44%   |
| Perth          | 6        | 0.44%   |
| Milan          | 6        | 0.44%   |
| Houston        | 6        | 0.44%   |
| Cape Town      | 6        | 0.44%   |
| Budapest       | 6        | 0.44%   |
| Bogotá        | 6        | 0.44%   |
| Belgrade       | 6        | 0.44%   |
| Warsaw         | 5        | 0.36%   |
| Sydney         | 5        | 0.36%   |
| Rome           | 5        | 0.36%   |
| London         | 5        | 0.36%   |
| Dayton         | 5        | 0.36%   |
| Dallas         | 5        | 0.36%   |
| Brasília      | 5        | 0.36%   |
| Adelaide       | 5        | 0.36%   |
| Yogyakarta     | 4        | 0.29%   |
| The Hague      | 4        | 0.29%   |
| Santiago       | 4        | 0.29%   |
| San José      | 4        | 0.29%   |
| Rotterdam      | 4        | 0.29%   |
| Richmond       | 4        | 0.29%   |
| Portland       | 4        | 0.29%   |
| Phoenix        | 4        | 0.29%   |
| Orlando        | 4        | 0.29%   |
| Mentor         | 4        | 0.29%   |
| Manchester     | 4        | 0.29%   |
| Las Vegas      | 4        | 0.29%   |
| Johannesburg   | 4        | 0.29%   |
| Fortaleza      | 4        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 479      | 702    | 21.63%  |
| WDC                       | 420      | 586    | 18.96%  |
| Samsung Electronics       | 279      | 423    | 12.6%   |
| Kingston                  | 144      | 184    | 6.5%    |
| Hitachi                   | 116      | 143    | 5.24%   |
| SanDisk                   | 108      | 132    | 4.88%   |
| Toshiba                   | 106      | 136    | 4.79%   |
| Crucial                   | 69       | 86     | 3.12%   |
| Maxtor                    | 37       | 51     | 1.67%   |
| Phison                    | 30       | 39     | 1.35%   |
| Intel                     | 27       | 33     | 1.22%   |
| A-DATA Technology         | 27       | 32     | 1.22%   |
| China                     | 25       | 28     | 1.13%   |
| Unknown                   | 23       | 43     | 1.04%   |
| Silicon Motion            | 19       | 27     | 0.86%   |
| PNY                       | 18       | 22     | 0.81%   |
| OCZ                       | 15       | 17     | 0.68%   |
| Intenso                   | 14       | 17     | 0.63%   |
| HGST                      | 14       | 20     | 0.63%   |
| SPCC                      | 11       | 13     | 0.5%    |
| SK hynix                  | 11       | 15     | 0.5%    |
| Micron Technology         | 10       | 11     | 0.45%   |
| Hewlett-Packard           | 10       | 14     | 0.45%   |
| Micron/Crucial Technology | 9        | 9      | 0.41%   |
| Gigabyte Technology       | 9        | 17     | 0.41%   |
| Corsair                   | 9        | 10     | 0.41%   |
| Patriot                   | 8        | 15     | 0.36%   |
| Leven                     | 7        | 8      | 0.32%   |
| JMicron Technology        | 7        | 11     | 0.32%   |
| XPG                       | 6        | 7      | 0.27%   |
| Transcend                 | 6        | 7      | 0.27%   |
| SABRENT                   | 6        | 6      | 0.27%   |
| Lexar                     | 6        | 6      | 0.27%   |
| KingSpec                  | 6        | 8      | 0.27%   |
| GOODRAM                   | 6        | 6      | 0.27%   |
| Apple                     | 6        | 6      | 0.27%   |
| Realtek Semiconductor     | 5        | 5      | 0.23%   |
| Apacer                    | 5        | 5      | 0.23%   |
| XrayDisk                  | 4        | 5      | 0.18%   |
| Team                      | 4        | 6      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 43       | 1.71%   |
| Kingston SA400S37240G 240GB SSD  | 38       | 1.51%   |
| Seagate ST1000DM010-2EP102 1TB   | 29       | 1.15%   |
| Seagate ST3500418AS 500GB        | 24       | 0.95%   |
| Samsung SSD 860 EVO 500GB        | 24       | 0.95%   |
| Samsung NVMe SSD Drive 1TB       | 21       | 0.83%   |
| Samsung NVMe SSD Drive 500GB     | 20       | 0.79%   |
| Kingston SA400S37120G 120GB SSD  | 20       | 0.79%   |
| Crucial CT240BX500SSD1 240GB     | 20       | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB         | 19       | 0.75%   |
| Samsung SSD 850 EVO 250GB        | 19       | 0.75%   |
| Toshiba DT01ACA100 1TB           | 18       | 0.71%   |
| Seagate ST1000DM003-1CH162 1TB   | 18       | 0.71%   |
| Kingston SA400S37480G 480GB SSD  | 18       | 0.71%   |
| Seagate ST1000DM003-1ER162 1TB   | 17       | 0.67%   |
| Kingston SV300S37A120G 120GB SSD | 17       | 0.67%   |
| SanDisk NVMe SSD Drive 500GB     | 14       | 0.56%   |
| Toshiba HDWD110 1TB              | 13       | 0.52%   |
| Seagate ST3500413AS 500GB        | 13       | 0.52%   |
| Seagate ST1000DM003-1SB102 1TB   | 13       | 0.52%   |
| Samsung SSD 850 EVO 500GB        | 13       | 0.52%   |
| Toshiba DT01ACA050 500GB         | 12       | 0.48%   |
| Samsung SSD 840 EVO 250GB        | 12       | 0.48%   |
| Seagate ST3500312CS 500GB        | 11       | 0.44%   |
| Seagate ST2000DM008-2FR102 2TB   | 11       | 0.44%   |
| SanDisk NVMe SSD Drive 1TB       | 11       | 0.44%   |
| Samsung HD103SJ 1TB              | 11       | 0.44%   |
| Crucial CT500MX500SSD1 500GB     | 11       | 0.44%   |
| Unknown SD/MMC/MS PRO 2GB        | 10       | 0.4%    |
| Seagate ST31000528AS 1TB         | 10       | 0.4%    |
| SanDisk SSD PLUS 240GB           | 10       | 0.4%    |
| Hitachi HDS721616PLA380 160GB    | 10       | 0.4%    |
| WDC WD10EZEX-00WN4A0 1TB         | 9        | 0.36%   |
| WDC WD10EZEX-00BN5A0 1TB         | 9        | 0.36%   |
| Toshiba DT01ACA200 2TB           | 9        | 0.36%   |
| Seagate ST4000DM000-1F2168 4TB   | 9        | 0.36%   |
| Seagate ST3250310AS 250GB        | 9        | 0.36%   |
| Seagate ST2000DM001-1ER164 2TB   | 9        | 0.36%   |
| Seagate ST2000DM001-1CH164 2TB   | 9        | 0.36%   |
| Seagate Expansion Desk 2TB       | 9        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 472      | 685    | 38.13%  |
| WDC                 | 397      | 547    | 32.07%  |
| Hitachi             | 116      | 143    | 9.37%   |
| Toshiba             | 94       | 124    | 7.59%   |
| Samsung Electronics | 86       | 111    | 6.95%   |
| Maxtor              | 36       | 50     | 2.91%   |
| HGST                | 14       | 20     | 1.13%   |
| Unknown             | 10       | 13     | 0.81%   |
| USB3.0              | 3        | 4      | 0.24%   |
| Hewlett-Packard     | 3        | 6      | 0.24%   |
| Apple               | 3        | 3      | 0.24%   |
| Quantum             | 1        | 1      | 0.08%   |
| Fujitsu             | 1        | 1      | 0.08%   |
| ExcelStor           | 1        | 1      | 0.08%   |
| ASMT109x            | 1        | 2      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 146      | 212    | 20.05%  |
| Kingston            | 125      | 158    | 17.17%  |
| SanDisk             | 79       | 96     | 10.85%  |
| Crucial             | 68       | 85     | 9.34%   |
| WDC                 | 31       | 36     | 4.26%   |
| A-DATA Technology   | 26       | 31     | 3.57%   |
| China               | 24       | 27     | 3.3%    |
| Intel               | 21       | 26     | 2.88%   |
| PNY                 | 18       | 22     | 2.47%   |
| OCZ                 | 14       | 16     | 1.92%   |
| Intenso             | 12       | 15     | 1.65%   |
| SPCC                | 10       | 12     | 1.37%   |
| Micron Technology   | 9        | 10     | 1.24%   |
| Patriot             | 8        | 15     | 1.1%    |
| Gigabyte Technology | 8        | 15     | 1.1%    |
| Toshiba             | 7        | 7      | 0.96%   |
| Leven               | 7        | 8      | 0.96%   |
| Hewlett-Packard     | 7        | 8      | 0.96%   |
| Corsair             | 7        | 8      | 0.96%   |
| Transcend           | 6        | 7      | 0.82%   |
| Lexar               | 6        | 6      | 0.82%   |
| KingSpec            | 6        | 8      | 0.82%   |
| SK hynix            | 5        | 5      | 0.69%   |
| GOODRAM             | 5        | 5      | 0.69%   |
| Apacer              | 5        | 5      | 0.69%   |
| Team                | 4        | 6      | 0.55%   |
| Super Talent        | 4        | 5      | 0.55%   |
| Netac               | 4        | 5      | 0.55%   |
| Seagate             | 3        | 4      | 0.41%   |
| Plextor             | 3        | 4      | 0.41%   |
| Pioneer             | 3        | 3      | 0.41%   |
| LITEON              | 3        | 4      | 0.41%   |
| Verbatim            | 2        | 2      | 0.27%   |
| TCSUNBOW            | 2        | 2      | 0.27%   |
| OWC                 | 2        | 2      | 0.27%   |
| Mushkin             | 2        | 2      | 0.27%   |
| LITEONIT            | 2        | 2      | 0.27%   |
| KIOXIA-EXCERIA      | 2        | 5      | 0.27%   |
| Drevo               | 2        | 2      | 0.27%   |
| Dogfish             | 2        | 3      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 963      | 1711   | 51.89%  |
| SSD     | 618      | 928    | 33.3%   |
| NVMe    | 219      | 308    | 11.8%   |
| Unknown | 52       | 73     | 2.8%    |
| MMC     | 4        | 5      | 0.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1264     | 2596   | 80.41%  |
| NVMe | 212      | 294    | 13.49%  |
| SAS  | 92       | 130    | 5.85%   |
| MMC  | 4        | 5      | 0.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1005     | 1620   | 59.71%  |
| 0.51-1.0   | 420      | 625    | 24.96%  |
| 1.01-2.0   | 153      | 226    | 9.09%   |
| 3.01-4.0   | 44       | 77     | 2.61%   |
| 4.01-10.0  | 32       | 45     | 1.9%    |
| 2.01-3.0   | 27       | 44     | 1.6%    |
| 10.01-20.0 | 2        | 2      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 421      | 30.42%  |
| 251-500        | 300      | 21.68%  |
| 501-1000       | 192      | 13.87%  |
| 51-100         | 122      | 8.82%   |
| 1001-2000      | 104      | 7.51%   |
| More than 3000 | 85       | 6.14%   |
| 21-50          | 64       | 4.62%   |
| 2001-3000      | 44       | 3.18%   |
| 1-20           | 41       | 2.96%   |
| Unknown        | 11       | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 643      | 44.62%  |
| 21-50          | 289      | 20.06%  |
| 51-100         | 155      | 10.76%  |
| 101-250        | 107      | 7.43%   |
| 251-500        | 81       | 5.62%   |
| 501-1000       | 58       | 4.02%   |
| 1001-2000      | 47       | 3.26%   |
| More than 3000 | 37       | 2.57%   |
| 2001-3000      | 13       | 0.9%    |
| Unknown        | 11       | 0.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Desktops | Drives | Percent |
|--------------------------------------|----------|--------|---------|
| WDC WD5000AAKS-00V1A0 500GB          | 1        | 1      | 3.85%   |
| WDC WD3200AAKS-22B3A0 320GB          | 1        | 1      | 3.85%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 1      | 3.85%   |
| WDC WD10EZEX-21M2NA0 1TB             | 1        | 2      | 3.85%   |
| WDC WD10EURX-63FH1Y0 1TB             | 1        | 1      | 3.85%   |
| Toshiba MK8046GSX 80GB               | 1        | 1      | 3.85%   |
| Toshiba MK3265GSX 320GB              | 1        | 1      | 3.85%   |
| Toshiba MG03ACA200 2TB               | 1        | 1      | 3.85%   |
| Silicon Motion Inland NVMe SSD 256GB | 1        | 1      | 3.85%   |
| Seagate ST9500420AS 500GB            | 1        | 1      | 3.85%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 1      | 3.85%   |
| Seagate ST4000DM004-2CV104 4TB       | 1        | 1      | 3.85%   |
| Seagate ST3500514NS 500GB            | 1        | 1      | 3.85%   |
| Seagate ST3500413AS 500GB            | 1        | 1      | 3.85%   |
| Seagate ST3320620AS 320GB            | 1        | 1      | 3.85%   |
| Seagate ST3250318AS 250GB            | 1        | 1      | 3.85%   |
| Seagate ST320LT012-1DG14C 320GB      | 1        | 1      | 3.85%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1        | 1      | 3.85%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 1      | 3.85%   |
| Seagate ST2000DM001-9YN164 2TB       | 1        | 1      | 3.85%   |
| Seagate ST2000DL003-9VT166 2TB       | 1        | 1      | 3.85%   |
| Seagate ST1000DM003-1ER162 1TB       | 1        | 1      | 3.85%   |
| OCZ VERTEX3 120GB SSD                | 1        | 1      | 3.85%   |
| Kingston SNS4151S316GD 16GB SSD      | 1        | 1      | 3.85%   |
| Intel SSDSC2CW060A3 64GB             | 1        | 1      | 3.85%   |
| A-DATA Technology SX8200PNP 256GB    | 1        | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 12       | 13     | 48%     |
| WDC               | 5        | 6      | 20%     |
| Toshiba           | 3        | 3      | 12%     |
| Silicon Motion    | 1        | 1      | 4%      |
| OCZ               | 1        | 1      | 4%      |
| Kingston          | 1        | 1      | 4%      |
| Intel             | 1        | 1      | 4%      |
| A-DATA Technology | 1        | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 12       | 13     | 60%     |
| WDC     | 5        | 6      | 25%     |
| Toshiba | 3        | 3      | 15%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 22     | 79.17%  |
| SSD  | 3        | 3      | 12.5%   |
| NVMe | 2        | 2      | 8.33%   |

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
| Detected | 1263     | 2841   | 92.87%  |
| Works    | 73       | 157    | 5.37%   |
| Malfunc  | 24       | 27     | 1.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 858      | 50.18%  |
| AMD                              | 381      | 22.28%  |
| Nvidia                           | 73       | 4.27%   |
| Samsung Electronics              | 72       | 4.21%   |
| JMicron Technology               | 46       | 2.69%   |
| ASMedia Technology               | 46       | 2.69%   |
| Phison Electronics               | 33       | 1.93%   |
| SanDisk                          | 31       | 1.81%   |
| Marvell Technology Group         | 29       | 1.7%    |
| VIA Technologies                 | 24       | 1.4%    |
| Kingston Technology Company      | 22       | 1.29%   |
| Silicon Motion                   | 20       | 1.17%   |
| Silicon Image                    | 12       | 0.7%    |
| Micron/Crucial Technology        | 10       | 0.58%   |
| ADATA Technology                 | 8        | 0.47%   |
| SK hynix                         | 6        | 0.35%   |
| Silicon Integrated Systems [SiS] | 6        | 0.35%   |
| Realtek Semiconductor            | 5        | 0.29%   |
| Broadcom / LSI                   | 5        | 0.29%   |
| Seagate Technology               | 4        | 0.23%   |
| Toshiba America Info Systems     | 3        | 0.18%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.12%   |
| KIOXIA                           | 2        | 0.12%   |
| Apple                            | 2        | 0.12%   |
| Union Memory (Shenzhen)          | 1        | 0.06%   |
| Promise Technology               | 1        | 0.06%   |
| OCZ Technology Group             | 1        | 0.06%   |
| Micron Technology                | 1        | 0.06%   |
| LSI Logic / Symbios Logic        | 1        | 0.06%   |
| Lite-On Technology               | 1        | 0.06%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.06%   |
| Integrated Technology Express    | 1        | 0.06%   |
| Hewlett-Packard                  | 1        | 0.06%   |
| Adaptec                          | 1        | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 191      | 8.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 118      | 5.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 106      | 4.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 97       | 4.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 84       | 3.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 84       | 3.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 68       | 2.94%   |
| AMD 400 Series Chipset SATA Controller                                                  | 66       | 2.86%   |
| Intel SATA Controller [RAID mode]                                                       | 60       | 2.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 57       | 2.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 49       | 2.12%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 42       | 1.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 41       | 1.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 41       | 1.77%   |
| Nvidia MCP61 SATA Controller                                                            | 40       | 1.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 38       | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 37       | 1.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 29       | 1.25%   |
| Nvidia MCP61 IDE                                                                        | 28       | 1.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 27       | 1.17%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 25       | 1.08%   |
| AMD 500 Series Chipset SATA Controller                                                  | 25       | 1.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 24       | 1.04%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 24       | 1.04%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 21       | 0.91%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 21       | 0.91%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 21       | 0.91%   |
| Phison E12 NVMe Controller                                                              | 19       | 0.82%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 19       | 0.82%   |
| AMD FCH SATA Controller D                                                               | 19       | 0.82%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 17       | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 17       | 0.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 17       | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 17       | 0.74%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 17       | 0.74%   |
| JMicron JMB368 IDE controller                                                           | 16       | 0.69%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 16       | 0.69%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 16       | 0.69%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 15       | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 14       | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 915      | 51.69%  |
| IDE  | 529      | 29.89%  |
| NVMe | 211      | 11.92%  |
| RAID | 104      | 5.88%   |
| SAS  | 6        | 0.34%   |
| SCSI | 5        | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 891      | 66.64%  |
| AMD    | 446      | 33.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 31       | 2.31%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 24       | 1.79%   |
| AMD Ryzen 5 3600 6-Core Processor           | 21       | 1.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 15       | 1.12%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 15       | 1.12%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 14       | 1.04%   |
| Intel Pentium 4 CPU 3.00GHz                 | 13       | 0.97%   |
| AMD FX-6300 Six-Core Processor              | 12       | 0.89%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 11       | 0.82%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 11       | 0.82%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 11       | 0.82%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 11       | 0.82%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 11       | 0.82%   |
| AMD FX-8350 Eight-Core Processor            | 11       | 0.82%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 10       | 0.75%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 10       | 0.75%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 10       | 0.75%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 10       | 0.75%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 10       | 0.75%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 10       | 0.75%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 10       | 0.75%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 10       | 0.75%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 10       | 0.75%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 9        | 0.67%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 9        | 0.67%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 9        | 0.67%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9        | 0.67%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 9        | 0.67%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 9        | 0.67%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 9        | 0.67%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 9        | 0.67%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 9        | 0.67%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 9        | 0.67%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 8        | 0.6%    |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 8        | 0.6%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 8        | 0.6%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 7        | 0.52%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 7        | 0.52%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 7        | 0.52%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 7        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 224      | 16.7%   |
| Intel Core i7           | 126      | 9.4%    |
| Intel Core i3           | 105      | 7.83%   |
| AMD Ryzen 5             | 73       | 5.44%   |
| Intel Core 2 Duo        | 71       | 5.29%   |
| Intel Xeon              | 59       | 4.4%    |
| AMD FX                  | 58       | 4.33%   |
| Intel Core 2 Quad       | 54       | 4.03%   |
| AMD Ryzen 7             | 49       | 3.65%   |
| Intel Celeron           | 42       | 3.13%   |
| Intel Pentium Dual-Core | 41       | 3.06%   |
| Intel Pentium Dual      | 39       | 2.91%   |
| Intel Pentium           | 33       | 2.46%   |
| Intel Pentium 4         | 32       | 2.39%   |
| AMD Athlon 64 X2        | 28       | 2.09%   |
| AMD Athlon II X2        | 25       | 1.86%   |
| Other                   | 22       | 1.64%   |
| AMD Ryzen 3             | 22       | 1.64%   |
| AMD Ryzen 9             | 19       | 1.42%   |
| AMD Phenom II X4        | 18       | 1.34%   |
| AMD A8                  | 17       | 1.27%   |
| Intel Core 2            | 15       | 1.12%   |
| AMD A6                  | 14       | 1.04%   |
| AMD A4                  | 14       | 1.04%   |
| AMD Athlon              | 13       | 0.97%   |
| AMD A10                 | 13       | 0.97%   |
| AMD Athlon II X4        | 12       | 0.89%   |
| AMD Sempron             | 11       | 0.82%   |
| Intel Pentium D         | 9        | 0.67%   |
| Intel Core i9           | 9        | 0.67%   |
| AMD Phenom II X6        | 9        | 0.67%   |
| AMD Athlon II X3        | 7        | 0.52%   |
| AMD Athlon 64           | 7        | 0.52%   |
| Intel Atom              | 5        | 0.37%   |
| AMD Phenom              | 5        | 0.37%   |
| Intel Pentium Gold      | 4        | 0.3%    |
| AMD Phenom II X2        | 4        | 0.3%    |
| AMD Ryzen Threadripper  | 3        | 0.22%   |
| AMD E1                  | 3        | 0.22%   |
| AMD Athlon X4           | 3        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 514      | 38.3%   |
| 2      | 469      | 34.95%  |
| 6      | 129      | 9.61%   |
| 1      | 86       | 6.41%   |
| 8      | 82       | 6.11%   |
| 3      | 27       | 2.01%   |
| 12     | 16       | 1.19%   |
| 16     | 11       | 0.82%   |
| 10     | 7        | 0.52%   |
| 20     | 1        | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1327     | 99.25%  |
| 2      | 10       | 0.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 749      | 56.02%  |
| 2      | 588      | 43.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1309     | 97.91%  |
| 32-bit         | 27       | 2.02%   |
| Unknown        | 1        | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 139      | 10.22%  |
| 0x306c3    | 129      | 9.49%   |
| 0x1067a    | 114      | 8.38%   |
| 0x206a7    | 105      | 7.72%   |
| 0x306a9    | 82       | 6.03%   |
| 0x6fd      | 47       | 3.46%   |
| 0x06000852 | 44       | 3.24%   |
| 0x506e3    | 43       | 3.16%   |
| 0x08701021 | 36       | 2.65%   |
| 0x010000c8 | 31       | 2.28%   |
| 0x6fb      | 28       | 2.06%   |
| 0x06001119 | 26       | 1.91%   |
| 0x0800820d | 22       | 1.62%   |
| 0x906ea    | 21       | 1.54%   |
| 0x906e9    | 21       | 1.54%   |
| 0x0a201016 | 17       | 1.25%   |
| 0x10676    | 16       | 1.18%   |
| 0x010000db | 15       | 1.1%    |
| 0xa0653    | 14       | 1.03%   |
| 0x0600063e | 14       | 1.03%   |
| 0xa0655    | 13       | 0.96%   |
| 0x906ed    | 13       | 0.96%   |
| 0x06003106 | 13       | 0.96%   |
| 0x20655    | 12       | 0.88%   |
| 0x106e5    | 11       | 0.81%   |
| 0x106a5    | 11       | 0.81%   |
| 0x08701013 | 11       | 0.81%   |
| 0x010000dc | 11       | 0.81%   |
| 0xa0671    | 10       | 0.74%   |
| 0x6f6      | 10       | 0.74%   |
| 0x08108109 | 10       | 0.74%   |
| 0x0700010f | 10       | 0.74%   |
| 0xf41      | 9        | 0.66%   |
| 0x906eb    | 9        | 0.66%   |
| 0x08101016 | 9        | 0.66%   |
| 0xf43      | 8        | 0.59%   |
| 0x206d7    | 8        | 0.59%   |
| 0x20652    | 8        | 0.59%   |
| 0x08001137 | 8        | 0.59%   |
| 0x03000027 | 8        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 146      | 10.9%   |
| Penryn           | 140      | 10.46%  |
| SandyBridge      | 117      | 8.74%   |
| Core             | 100      | 7.47%   |
| IvyBridge        | 91       | 6.8%    |
| K10              | 84       | 6.27%   |
| Piledriver       | 72       | 5.38%   |
| KabyLake         | 72       | 5.38%   |
| Zen 2            | 57       | 4.26%   |
| K8 Hammer        | 50       | 3.73%   |
| NetBurst         | 49       | 3.66%   |
| Skylake          | 47       | 3.51%   |
| Zen+             | 42       | 3.14%   |
| Zen 3            | 37       | 2.76%   |
| Zen              | 37       | 2.76%   |
| CometLake        | 28       | 2.09%   |
| Westmere         | 27       | 2.02%   |
| Nehalem          | 27       | 2.02%   |
| Silvermont       | 17       | 1.27%   |
| Bulldozer        | 14       | 1.05%   |
| Steamroller      | 13       | 0.97%   |
| Jaguar           | 11       | 0.82%   |
| K10 Llano        | 8        | 0.6%    |
| Excavator        | 8        | 0.6%    |
| Icelake          | 7        | 0.52%   |
| Puma             | 6        | 0.45%   |
| Alderlake Hybrid | 6        | 0.45%   |
| Unknown          | 6        | 0.45%   |
| Bonnell          | 4        | 0.3%    |
| Bobcat           | 4        | 0.3%    |
| K6               | 3        | 0.22%   |
| Goldmont plus    | 3        | 0.22%   |
| Broadwell        | 3        | 0.22%   |
| TigerLake        | 1        | 0.07%   |
| P6               | 1        | 0.07%   |
| Goldmont         | 1        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 541      | 38.23%  |
| Intel                            | 440      | 31.1%   |
| AMD                              | 422      | 29.82%  |
| VIA Technologies                 | 7        | 0.49%   |
| Silicon Integrated Systems [SiS] | 2        | 0.14%   |
| Trident Microsystems             | 1        | 0.07%   |
| Silicon Motion                   | 1        | 0.07%   |
| Matrox Electronics Systems       | 1        | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 67       | 4.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 60       | 4.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 47       | 3.24%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 46       | 3.17%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 43       | 2.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 32       | 2.21%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 27       | 1.86%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 22       | 1.52%   |
| Intel HD Graphics 530                                                                    | 22       | 1.52%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 22       | 1.52%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 20       | 1.38%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 19       | 1.31%   |
| Nvidia GT218 [GeForce 210]                                                               | 18       | 1.24%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 18       | 1.24%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 17       | 1.17%   |
| AMD RS780L [Radeon 3000]                                                                 | 17       | 1.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16       | 1.1%    |
| Intel HD Graphics 630                                                                    | 14       | 0.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14       | 0.97%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 14       | 0.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 13       | 0.9%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 13       | 0.9%    |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 12       | 0.83%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 12       | 0.83%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 11       | 0.76%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 11       | 0.76%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 11       | 0.76%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 10       | 0.69%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 10       | 0.69%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 10       | 0.69%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 10       | 0.69%   |
| AMD RS880 [Radeon HD 4200]                                                               | 10       | 0.69%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 10       | 0.69%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 10       | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9        | 0.62%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 8        | 0.55%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 8        | 0.55%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 8        | 0.55%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 8        | 0.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 513      | 38.11%  |
| 1 x Intel                | 385      | 28.6%   |
| 1 x AMD                  | 379      | 28.16%  |
| 2 x AMD                  | 23       | 1.71%   |
| Intel + Nvidia           | 14       | 1.04%   |
| Intel + AMD              | 12       | 0.89%   |
| 1 x VIA                  | 7        | 0.52%   |
| AMD + Nvidia             | 5        | 0.37%   |
| 2 x Nvidia               | 3        | 0.22%   |
| 1 x SiS                  | 2        | 0.15%   |
| 1 x Trident Microsystems | 1        | 0.07%   |
| Nvidia + Silicon Motion  | 1        | 0.07%   |
| 1 x Matrox               | 1        | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 929      | 68.76%  |
| Proprietary | 318      | 23.54%  |
| Unknown     | 104      | 7.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 538      | 39.3%   |
| 0.01-0.5   | 216      | 15.78%  |
| 1.01-2.0   | 196      | 14.32%  |
| 0.51-1.0   | 192      | 14.02%  |
| 3.01-4.0   | 89       | 6.5%    |
| 7.01-8.0   | 73       | 5.33%   |
| 5.01-6.0   | 28       | 2.05%   |
| 8.01-16.0  | 22       | 1.61%   |
| 2.01-3.0   | 10       | 0.73%   |
| 16.01-24.0 | 4        | 0.29%   |
| 4.01-5.0   | 1        | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 207      | 15.97%  |
| Dell                 | 131      | 10.11%  |
| Goldstar             | 123      | 9.49%   |
| Hewlett-Packard      | 112      | 8.64%   |
| Acer                 | 85       | 6.56%   |
| AOC                  | 70       | 5.4%    |
| Philips              | 64       | 4.94%   |
| Ancor Communications | 55       | 4.24%   |
| BenQ                 | 48       | 3.7%    |
| LG Electronics       | 35       | 2.7%    |
| ViewSonic            | 30       | 2.31%   |
| Unknown              | 23       | 1.77%   |
| Sony                 | 14       | 1.08%   |
| Unknown              | 14       | 1.08%   |
| Sceptre Tech         | 13       | 1%      |
| NEC Computers        | 13       | 1%      |
| Lenovo               | 13       | 1%      |
| Iiyama               | 13       | 1%      |
| Vizio                | 11       | 0.85%   |
| HPN                  | 9        | 0.69%   |
| Fujitsu Siemens      | 9        | 0.69%   |
| ASUSTek Computer     | 9        | 0.69%   |
| Toshiba              | 7        | 0.54%   |
| Gateway              | 7        | 0.54%   |
| Sharp                | 6        | 0.46%   |
| Medion               | 6        | 0.46%   |
| HannStar             | 6        | 0.46%   |
| Eizo                 | 6        | 0.46%   |
| Microstep            | 5        | 0.39%   |
| Idek Iiyama          | 5        | 0.39%   |
| FUS                  | 5        | 0.39%   |
| CVT                  | 5        | 0.39%   |
| AUS                  | 5        | 0.39%   |
| VIZ                  | 4        | 0.31%   |
| Panasonic            | 4        | 0.31%   |
| MSI                  | 4        | 0.31%   |
| KTC                  | 4        | 0.31%   |
| Envision             | 4        | 0.31%   |
| Vestel               | 3        | 0.23%   |
| SANYO                | 3        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown                                                                | 14       | 1.02%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                       | 7        | 0.51%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 5        | 0.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5        | 0.37%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 4        | 0.29%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch | 4        | 0.29%   |
| Philips PHL 242M8 PHLC253 1920x1080 527x296mm 23.8-inch                | 4        | 0.29%   |
| Philips LCD Monitor FTV 1920x1080                                      | 4        | 0.29%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch              | 4        | 0.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 4        | 0.29%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch              | 4        | 0.29%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                     | 4        | 0.29%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 4        | 0.29%   |
| Vizio E220VA VIZ0070 1920x1080 476x268mm 21.5-inch                     | 3        | 0.22%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                              | 3        | 0.22%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch      | 3        | 0.22%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch   | 3        | 0.22%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                   | 3        | 0.22%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 3        | 0.22%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768 700x390mm 31.5-inch   | 3        | 0.22%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 3        | 0.22%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 3        | 0.22%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 3        | 0.22%   |
| OEM 19W_LCD_TV OEM3700 1920x540                                        | 3        | 0.22%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 3        | 0.22%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                       | 3        | 0.22%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 3        | 0.22%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                    | 3        | 0.22%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 3        | 0.22%   |
| GDH PHILCO GDH0030 1920x540 708x398mm 32.0-inch                        | 3        | 0.22%   |
| Dell ST2010 DELF019 1600x900 443x249mm 20.0-inch                       | 3        | 0.22%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                     | 3        | 0.22%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                      | 3        | 0.22%   |
| Dell DEL 1908FPBLK DEL4047 1280x1024 376x301mm 19.0-inch               | 3        | 0.22%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 3        | 0.22%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch  | 3        | 0.22%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                       | 3        | 0.22%   |
| ___ LCDTV16 ___0101 1920x1080                                          | 2        | 0.15%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch              | 2        | 0.15%   |
| VIZ LCD Monitor E320VT 1920x1080                                       | 2        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 525      | 40.92%  |
| 1280x1024 (SXGA)   | 111      | 8.65%   |
| 3840x2160 (4K)     | 84       | 6.55%   |
| 1680x1050 (WSXGA+) | 78       | 6.08%   |
| 1366x768 (WXGA)    | 72       | 5.61%   |
| 1600x900 (HD+)     | 65       | 5.07%   |
| 1440x900 (WXGA+)   | 57       | 4.44%   |
| Unknown            | 54       | 4.21%   |
| 1360x768           | 39       | 3.04%   |
| 2560x1440 (QHD)    | 36       | 2.81%   |
| 1920x1200 (WUXGA)  | 26       | 2.03%   |
| 3840x1080          | 21       | 1.64%   |
| 3440x1440          | 18       | 1.4%    |
| 2560x1080          | 12       | 0.94%   |
| 1024x768 (XGA)     | 12       | 0.94%   |
| 1920x540           | 11       | 0.86%   |
| 5760x1080          | 4        | 0.31%   |
| 4480x1440          | 4        | 0.31%   |
| 1600x1200          | 4        | 0.31%   |
| 1280x720 (HD)      | 4        | 0.31%   |
| 5760x2160          | 3        | 0.23%   |
| 3840x1600          | 3        | 0.23%   |
| 2560x1600          | 3        | 0.23%   |
| 6400x1440          | 2        | 0.16%   |
| 5440x1080          | 2        | 0.16%   |
| 3600x1080          | 2        | 0.16%   |
| 3360x1080          | 2        | 0.16%   |
| 3200x1200          | 2        | 0.16%   |
| 3200x1080          | 2        | 0.16%   |
| 3120x1050          | 2        | 0.16%   |
| 2720x1024          | 2        | 0.16%   |
| 2048x1152          | 2        | 0.16%   |
| 1152x864           | 2        | 0.16%   |
| 7680x1080          | 1        | 0.08%   |
| 6400x1080          | 1        | 0.08%   |
| 5040x1050          | 1        | 0.08%   |
| 4160x1440          | 1        | 0.08%   |
| 3840x1200          | 1        | 0.08%   |
| 3780x2160          | 1        | 0.08%   |
| 3360x1050          | 1        | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 269      | 21.15%  |
| 24      | 107      | 8.41%   |
| 21      | 107      | 8.41%   |
| 23      | 106      | 8.33%   |
| 27      | 101      | 7.94%   |
| 19      | 101      | 7.94%   |
| 18      | 79       | 6.21%   |
| 20      | 64       | 5.03%   |
| 17      | 56       | 4.4%    |
| 22      | 53       | 4.17%   |
| 31      | 48       | 3.77%   |
| 34      | 22       | 1.73%   |
| 15      | 22       | 1.73%   |
| 84      | 15       | 1.18%   |
| 54      | 13       | 1.02%   |
| 40      | 13       | 1.02%   |
| 26      | 13       | 1.02%   |
| 72      | 11       | 0.86%   |
| 32      | 10       | 0.79%   |
| 52      | 6        | 0.47%   |
| 42      | 5        | 0.39%   |
| 25      | 5        | 0.39%   |
| 65      | 4        | 0.31%   |
| 36      | 4        | 0.31%   |
| 37      | 3        | 0.24%   |
| 33      | 3        | 0.24%   |
| 28      | 3        | 0.24%   |
| 74      | 2        | 0.16%   |
| 48      | 2        | 0.16%   |
| 46      | 2        | 0.16%   |
| 43      | 2        | 0.16%   |
| 41      | 2        | 0.16%   |
| 39      | 2        | 0.16%   |
| 35      | 2        | 0.16%   |
| 29      | 2        | 0.16%   |
| 16      | 2        | 0.16%   |
| 13      | 2        | 0.16%   |
| 86      | 1        | 0.08%   |
| 75      | 1        | 0.08%   |
| 60      | 1        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 345      | 27.82%  |
| 501-600     | 298      | 24.03%  |
| Unknown     | 269      | 21.69%  |
| 301-350     | 75       | 6.05%   |
| 601-700     | 62       | 5%      |
| 351-400     | 59       | 4.76%   |
| 701-800     | 39       | 3.15%   |
| 1001-1500   | 31       | 2.5%    |
| 1501-2000   | 30       | 2.42%   |
| 801-900     | 20       | 1.61%   |
| 901-1000    | 10       | 0.81%   |
| 201-300     | 2        | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 640      | 53.29%  |
| Unknown | 248      | 20.65%  |
| 16/10   | 152      | 12.66%  |
| 5/4     | 99       | 8.24%   |
| 21/9    | 27       | 2.25%   |
| 4/3     | 20       | 1.67%   |
| 32/9    | 6        | 0.5%    |
| 6/5     | 5        | 0.42%   |
| 3/2     | 4        | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 296      | 23.57%  |
| Unknown        | 269      | 21.42%  |
| 151-200        | 215      | 17.12%  |
| 141-150        | 110      | 8.76%   |
| 301-350        | 102      | 8.12%   |
| 351-500        | 91       | 7.25%   |
| More than 1000 | 55       | 4.38%   |
| 251-300        | 49       | 3.9%    |
| 501-1000       | 36       | 2.87%   |
| 101-110        | 19       | 1.51%   |
| 131-140        | 7        | 0.56%   |
| 111-120        | 3        | 0.24%   |
| 91-100         | 2        | 0.16%   |
| 81-90          | 1        | 0.08%   |
| 121-130        | 1        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 678      | 56.36%  |
| Unknown | 269      | 22.36%  |
| 101-120 | 161      | 13.38%  |
| 1-50    | 60       | 4.99%   |
| 121-160 | 23       | 1.91%   |
| 161-240 | 12       | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1096     | 80.83%  |
| 2     | 143      | 10.55%  |
| 0     | 99       | 7.3%    |
| 3     | 17       | 1.25%   |
| 4     | 1        | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 798      | 40.28%  |
| Intel                                 | 469      | 23.67%  |
| Qualcomm Atheros                      | 130      | 6.56%   |
| Ralink Technology                     | 79       | 3.99%   |
| Broadcom                              | 75       | 3.79%   |
| Nvidia                                | 63       | 3.18%   |
| TP-Link                               | 38       | 1.92%   |
| Ralink                                | 36       | 1.82%   |
| Broadcom Limited                      | 26       | 1.31%   |
| Marvell Technology Group              | 25       | 1.26%   |
| VIA Technologies                      | 19       | 0.96%   |
| D-Link                                | 19       | 0.96%   |
| NetGear                               | 17       | 0.86%   |
| D-Link System                         | 17       | 0.86%   |
| Samsung Electronics                   | 15       | 0.76%   |
| MediaTek                              | 15       | 0.76%   |
| Xiaomi                                | 11       | 0.56%   |
| Qualcomm Atheros Communications       | 10       | 0.5%    |
| Microsoft                             | 10       | 0.5%    |
| Huawei Technologies                   | 9        | 0.45%   |
| Edimax Technology                     | 7        | 0.35%   |
| ASUSTek Computer                      | 7        | 0.35%   |
| Silicon Integrated Systems [SiS]      | 5        | 0.25%   |
| Belkin Components                     | 5        | 0.25%   |
| ASIX Electronics                      | 5        | 0.25%   |
| Aquantia                              | 5        | 0.25%   |
| Motorola PCS                          | 4        | 0.2%    |
| Gemtek                                | 4        | 0.2%    |
| DisplayLink                           | 4        | 0.2%    |
| Sitecom Europe                        | 3        | 0.15%   |
| Qualcomm                              | 3        | 0.15%   |
| OPPO Electronics                      | 3        | 0.15%   |
| Linksys                               | 3        | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.15%   |
| ZTE WCDMA Technologies MSM            | 2        | 0.1%    |
| TRENDnet                              | 2        | 0.1%    |
| Sundance Technology Inc / IC Plus     | 2        | 0.1%    |
| Senao                                 | 2        | 0.1%    |
| Motorola                              | 2        | 0.1%    |
| Microchip Technology                  | 2        | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 596      | 26.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 74       | 3.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 61       | 2.75%   |
| Intel I211 Gigabit Network Connection                             | 49       | 2.21%   |
| Realtek 802.11ac NIC                                              | 46       | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 39       | 1.76%   |
| Nvidia MCP61 Ethernet                                             | 38       | 1.72%   |
| Intel Wi-Fi 6 AX200                                               | 38       | 1.72%   |
| Intel Ethernet Connection I217-LM                                 | 35       | 1.58%   |
| Ralink MT7601U Wireless Adapter                                   | 34       | 1.53%   |
| Intel Ethernet Connection (2) I219-V                              | 31       | 1.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25       | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 21       | 0.95%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 19       | 0.86%   |
| Intel Ethernet Controller I225-V                                  | 18       | 0.81%   |
| Intel Ethernet Connection I217-V                                  | 18       | 0.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 17       | 0.77%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 17       | 0.77%   |
| Intel Ethernet Connection (2) I218-V                              | 16       | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 16       | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 15       | 0.68%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 14       | 0.63%   |
| Intel Wireless-AC 9260                                            | 14       | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13       | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13       | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 13       | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 13       | 0.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 12       | 0.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 12       | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 12       | 0.54%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 12       | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 11       | 0.5%    |
| Ralink RT5370 Wireless Adapter                                    | 11       | 0.5%    |
| Intel Wireless 7265                                               | 11       | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 10       | 0.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 10       | 0.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 10       | 0.45%   |
| Intel 82574L Gigabit Network Connection                           | 10       | 0.45%   |
| Qualcomm Atheros AR9271 802.11n                                   | 9        | 0.41%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 9        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 181      | 25.28%  |
| Intel                                 | 149      | 20.81%  |
| Ralink Technology                     | 79       | 11.03%  |
| Qualcomm Atheros                      | 63       | 8.8%    |
| TP-Link                               | 37       | 5.17%   |
| Ralink                                | 36       | 5.03%   |
| Broadcom                              | 33       | 4.61%   |
| D-Link                                | 19       | 2.65%   |
| NetGear                               | 17       | 2.37%   |
| D-Link System                         | 14       | 1.96%   |
| Qualcomm Atheros Communications       | 10       | 1.4%    |
| Microsoft                             | 10       | 1.4%    |
| MediaTek                              | 9        | 1.26%   |
| Broadcom Limited                      | 9        | 1.26%   |
| Edimax Technology                     | 7        | 0.98%   |
| ASUSTek Computer                      | 6        | 0.84%   |
| Belkin Components                     | 5        | 0.7%    |
| Marvell Technology Group              | 4        | 0.56%   |
| Gemtek                                | 4        | 0.56%   |
| Sitecom Europe                        | 3        | 0.42%   |
| Linksys                               | 3        | 0.42%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.42%   |
| TRENDnet                              | 2        | 0.28%   |
| Senao                                 | 2        | 0.28%   |
| Micro Star International              | 2        | 0.28%   |
| AVM                                   | 2        | 0.28%   |
| ZyXEL Communications                  | 1        | 0.14%   |
| ZyDAS                                 | 1        | 0.14%   |
| Xiaomi                                | 1        | 0.14%   |
| Philips (or NXP)                      | 1        | 0.14%   |
| Panasonic (Matsushita)                | 1        | 0.14%   |
| IMC Networks                          | 1        | 0.14%   |
| ADMtek                                | 1        | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek 802.11ac NIC                                           | 46       | 6.37%   |
| Intel Wi-Fi 6 AX200                                            | 38       | 5.26%   |
| Ralink MT7601U Wireless Adapter                                | 34       | 4.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 21       | 2.91%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 17       | 2.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 15       | 2.08%   |
| Intel Wireless-AC 9260                                         | 14       | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 13       | 1.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 13       | 1.8%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 12       | 1.66%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 12       | 1.66%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 12       | 1.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 11       | 1.52%   |
| Ralink RT5370 Wireless Adapter                                 | 11       | 1.52%   |
| Intel Wireless 7265                                            | 11       | 1.52%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 10       | 1.39%   |
| Qualcomm Atheros AR9271 802.11n                                | 9        | 1.25%   |
| Intel Wireless 8260                                            | 9        | 1.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 8        | 1.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8        | 1.11%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 8        | 1.11%   |
| Intel Wireless 7260                                            | 8        | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8        | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7        | 0.97%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 7        | 0.97%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 7        | 0.97%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 6        | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 6        | 0.83%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 6        | 0.83%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 6        | 0.83%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 6        | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6        | 0.83%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 6        | 0.83%   |
| NetGear A6210                                                  | 6        | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6        | 0.83%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 5        | 0.69%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 5        | 0.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 5        | 0.69%   |
| Microsoft Xbox 360 Wireless Adapter                            | 5        | 0.69%   |
| MediaTek WiFi                                                  | 5        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 731      | 50.83%  |
| Intel                             | 391      | 27.19%  |
| Qualcomm Atheros                  | 70       | 4.87%   |
| Nvidia                            | 63       | 4.38%   |
| Broadcom                          | 42       | 2.92%   |
| Marvell Technology Group          | 21       | 1.46%   |
| VIA Technologies                  | 19       | 1.32%   |
| Broadcom Limited                  | 18       | 1.25%   |
| Samsung Electronics               | 15       | 1.04%   |
| Xiaomi                            | 10       | 0.7%    |
| Huawei Technologies               | 8        | 0.56%   |
| MediaTek                          | 6        | 0.42%   |
| Silicon Integrated Systems [SiS]  | 5        | 0.35%   |
| ASIX Electronics                  | 5        | 0.35%   |
| Aquantia                          | 5        | 0.35%   |
| DisplayLink                       | 4        | 0.28%   |
| Qualcomm                          | 3        | 0.21%   |
| OPPO Electronics                  | 3        | 0.21%   |
| D-Link System                     | 3        | 0.21%   |
| Sundance Technology Inc / IC Plus | 2        | 0.14%   |
| Motorola PCS                      | 2        | 0.14%   |
| JMicron Technology                | 2        | 0.14%   |
| Apple                             | 2        | 0.14%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.07%   |
| TP-Link                           | 1        | 0.07%   |
| Research In Motion                | 1        | 0.07%   |
| HMD Global                        | 1        | 0.07%   |
| Google                            | 1        | 0.07%   |
| GCT Semiconductor                 | 1        | 0.07%   |
| ASUSTek Computer                  | 1        | 0.07%   |
| 3Com                              | 1        | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 596      | 40.46%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 74       | 5.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 61       | 4.14%   |
| Intel I211 Gigabit Network Connection                             | 49       | 3.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 39       | 2.65%   |
| Nvidia MCP61 Ethernet                                             | 38       | 2.58%   |
| Intel Ethernet Connection I217-LM                                 | 35       | 2.38%   |
| Intel Ethernet Connection (2) I219-V                              | 31       | 2.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25       | 1.7%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 19       | 1.29%   |
| Intel Ethernet Controller I225-V                                  | 18       | 1.22%   |
| Intel Ethernet Connection I217-V                                  | 18       | 1.22%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 17       | 1.15%   |
| Intel Ethernet Connection (2) I218-V                              | 16       | 1.09%   |
| Intel 82579V Gigabit Network Connection                           | 16       | 1.09%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 14       | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13       | 0.88%   |
| Intel Ethernet Connection (7) I219-V                              | 13       | 0.88%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 12       | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10       | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 10       | 0.68%   |
| Intel 82574L Gigabit Network Connection                           | 10       | 0.68%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 9        | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9        | 0.61%   |
| Nvidia MCP73 Ethernet                                             | 9        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 9        | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8        | 0.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8        | 0.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 0.48%   |
| Intel NM10/ICH7 Family LAN Controller                             | 7        | 0.48%   |
| Intel 82578DM Gigabit Network Connection                          | 7        | 0.48%   |
| Intel 82578DC Gigabit Network Connection                          | 7        | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6        | 0.41%   |
| Nvidia MCP51 Ethernet Controller                                  | 6        | 0.41%   |
| Intel 82562V-2 10/100 Network Connection                          | 6        | 0.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 6        | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 5        | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5        | 0.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1320     | 66.47%  |
| WiFi     | 646      | 32.53%  |
| Modem    | 15       | 0.76%   |
| Unknown  | 5        | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 986      | 70.99%  |
| WiFi     | 401      | 28.87%  |
| Modem    | 1        | 0.07%   |
| Unknown  | 1        | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 919      | 68.43%  |
| 2     | 369      | 27.48%  |
| 3     | 42       | 3.13%   |
| 0     | 9        | 0.67%   |
| 5     | 2        | 0.15%   |
| 7     | 1        | 0.07%   |
| 4     | 1        | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1075     | 79.45%  |
| Yes  | 278      | 20.55%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 120      | 33.24%  |
| Cambridge Silicon Radio         | 91       | 25.21%  |
| Realtek Semiconductor           | 38       | 10.53%  |
| Broadcom                        | 27       | 7.48%   |
| Qualcomm Atheros Communications | 18       | 4.99%   |
| ASUSTek Computer                | 17       | 4.71%   |
| IMC Networks                    | 11       | 3.05%   |
| Apple                           | 8        | 2.22%   |
| Dynex                           | 5        | 1.39%   |
| Micro Star International        | 4        | 1.11%   |
| MediaTek                        | 3        | 0.83%   |
| Integrated System Solution      | 3        | 0.83%   |
| Belkin Components               | 3        | 0.83%   |
| TP-Link                         | 2        | 0.55%   |
| Dell                            | 2        | 0.55%   |
| Sitecom Europe                  | 1        | 0.28%   |
| National Semiconductor          | 1        | 0.28%   |
| Logitech                        | 1        | 0.28%   |
| Lite-On Technology              | 1        | 0.28%   |
| Hewlett-Packard                 | 1        | 0.28%   |
| Fujitsu                         | 1        | 0.28%   |
| Foxconn / Hon Hai               | 1        | 0.28%   |
| Edimax Technology               | 1        | 0.28%   |
| D-Link System                   | 1        | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 91       | 25.21%  |
| Realtek Bluetooth Radio                                   | 35       | 9.7%    |
| Intel Bluetooth wireless interface                        | 31       | 8.59%   |
| Intel AX200 Bluetooth                                     | 27       | 7.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 15       | 4.16%   |
| Intel Wireless-AC 3168 Bluetooth                          | 14       | 3.88%   |
| Intel AX210 Bluetooth                                     | 11       | 3.05%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 11       | 3.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 9        | 2.49%   |
| Intel AX201 Bluetooth                                     | 9        | 2.49%   |
| IMC Networks Bluetooth Radio                              | 8        | 2.22%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 8        | 2.22%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 5        | 1.39%   |
| Dynex BCM20702A0                                          | 5        | 1.39%   |
| ASUS Bluetooth Radio                                      | 5        | 1.39%   |
| Apple Bluetooth USB Host Controller                       | 5        | 1.39%   |
| Qualcomm Atheros AR3011 Bluetooth                         | 4        | 1.11%   |
| Intel Centrino Bluetooth Wireless Transceiver             | 4        | 1.11%   |
| Qualcomm Atheros  Bluetooth Device                        | 3        | 0.83%   |
| Micro Star International Bluetooth Device                 | 3        | 0.83%   |
| MediaTek Wireless_Device                                  | 3        | 0.83%   |
| Broadcom BCM43142A0 Bluetooth 4.0                         | 3        | 0.83%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter     | 3        | 0.83%   |
| TP-Link UB500 Adapter                                     | 2        | 0.55%   |
| Realtek  Bluetooth 4.2 Adapter                            | 2        | 0.55%   |
| Qualcomm Atheros Bluetooth USB Host Controller            | 2        | 0.55%   |
| Qualcomm Atheros Bluetooth                                | 2        | 0.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                     | 2        | 0.55%   |
| Integrated System Solution Bluetooth Device               | 2        | 0.55%   |
| IMC Networks Bluetooth Module                             | 2        | 0.55%   |
| Dell BT Mini-Receiver                                     | 2        | 0.55%   |
| Broadcom HP Portable Bumble Bee                           | 2        | 0.55%   |
| Broadcom BCM92045B3 ROM                                   | 2        | 0.55%   |
| Broadcom BCM2045 Bluetooth                                | 2        | 0.55%   |
| ASUS Qualcomm Bluetooth 4.1                               | 2        | 0.55%   |
| Apple Bluetooth Host Controller                           | 2        | 0.55%   |
| Sitecom Europe Sitecom bluetooth2.0 class 2 dongle CN-512 | 1        | 0.28%   |
| Realtek RTL8723B Bluetooth                                | 1        | 0.28%   |
| National Bluetooth Dongle                                 | 1        | 0.28%   |
| Micro Star International Bluetooth Dongle                 | 1        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 848      | 40.11%  |
| AMD                                  | 534      | 25.26%  |
| Nvidia                               | 487      | 23.04%  |
| C-Media Electronics                  | 55       | 2.6%    |
| Creative Labs                        | 27       | 1.28%   |
| VIA Technologies                     | 21       | 0.99%   |
| Logitech                             | 15       | 0.71%   |
| JMTek                                | 10       | 0.47%   |
| Kingston Technology                  | 9        | 0.43%   |
| Texas Instruments                    | 8        | 0.38%   |
| GN Netcom                            | 7        | 0.33%   |
| Silicon Integrated Systems [SiS]     | 6        | 0.28%   |
| Razer USA                            | 6        | 0.28%   |
| Plantronics                          | 6        | 0.28%   |
| Generalplus Technology               | 6        | 0.28%   |
| ASUSTek Computer                     | 6        | 0.28%   |
| SteelSeries ApS                      | 3        | 0.14%   |
| Realtek Semiconductor                | 3        | 0.14%   |
| Creative Technology                  | 3        | 0.14%   |
| Turtle Beach                         | 2        | 0.09%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.09%   |
| Tenx Technology                      | 2        | 0.09%   |
| Sennheiser Communications            | 2        | 0.09%   |
| Samsung Electronics                  | 2        | 0.09%   |
| Micronas                             | 2        | 0.09%   |
| Micro Star International             | 2        | 0.09%   |
| Ensoniq                              | 2        | 0.09%   |
| DigiTech                             | 2        | 0.09%   |
| Corsair                              | 2        | 0.09%   |
| XMOS                                 | 1        | 0.05%   |
| Valve Software                       | 1        | 0.05%   |
| Swissonic                            | 1        | 0.05%   |
| Silicon Labs                         | 1        | 0.05%   |
| Shenzhen Riitek Technology           | 1        | 0.05%   |
| SAVITECH                             | 1        | 0.05%   |
| RODE Microphones                     | 1        | 0.05%   |
| ROCCAT                               | 1        | 0.05%   |
| Qualcomm                             | 1        | 0.05%   |
| Philips (or NXP)                     | 1        | 0.05%   |
| Numark                               | 1        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 132      | 5.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 129      | 5.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 122      | 5.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 110      | 4.54%   |
| AMD Starship/Matisse HD Audio Controller                                          | 83       | 3.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 77       | 3.18%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 70       | 2.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 65       | 2.68%   |
| AMD FCH Azalia Controller                                                         | 65       | 2.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 49       | 2.02%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 46       | 1.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 46       | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 45       | 1.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 41       | 1.69%   |
| Nvidia MCP61 High Definition Audio                                                | 39       | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                        | 37       | 1.53%   |
| AMD Family 17h/19h HD Audio Controller                                            | 37       | 1.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 32       | 1.32%   |
| Nvidia High Definition Audio Controller                                           | 31       | 1.28%   |
| Intel 200 Series PCH HD Audio                                                     | 30       | 1.24%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 30       | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                                     | 29       | 1.2%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 27       | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 26       | 1.07%   |
| Nvidia GF119 HDMI Audio Controller                                                | 26       | 1.07%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 25       | 1.03%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 24       | 0.99%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 23       | 0.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 23       | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                                     | 22       | 0.91%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 21       | 0.87%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 20       | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                                | 18       | 0.74%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 17       | 0.7%    |
| AMD Kabini HDMI/DP Audio                                                          | 17       | 0.7%    |
| Nvidia GP104 High Definition Audio Controller                                     | 16       | 0.66%   |
| AMD Navi 10 HDMI Audio                                                            | 16       | 0.66%   |
| AMD Trinity HDMI Audio Controller                                                 | 15       | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                                     | 14       | 0.58%   |
| Nvidia GP106 High Definition Audio Controller                                     | 14       | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 50       | 23.26%  |
| Kingston            | 30       | 13.95%  |
| Samsung Electronics | 23       | 10.7%   |
| Corsair             | 21       | 9.77%   |
| G.Skill             | 20       | 9.3%    |
| SK hynix            | 18       | 8.37%   |
| Crucial             | 16       | 7.44%   |
| Micron Technology   | 11       | 5.12%   |
| Elpida              | 6        | 2.79%   |
| Team                | 3        | 1.4%    |
| Ramaxel Technology  | 3        | 1.4%    |
| Qimonda             | 2        | 0.93%   |
| Patriot             | 2        | 0.93%   |
| Nanya Technology    | 2        | 0.93%   |
| Unifosa             | 1        | 0.47%   |
| Ramos Technology    | 1        | 0.47%   |
| PNY                 | 1        | 0.47%   |
| Goldkey             | 1        | 0.47%   |
| F7852C80            | 1        | 0.47%   |
| CSX                 | 1        | 0.47%   |
| ASint Technology    | 1        | 0.47%   |
| Unknown             | 1        | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 1GB DIMM SDRAM                        | 4        | 1.72%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 3        | 1.29%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s      | 3        | 1.29%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 2        | 0.86%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 2        | 0.86%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                   | 2        | 0.86%   |
| Unknown RAM Module 4096MB DIMM                           | 2        | 0.86%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 2        | 0.86%   |
| Unknown RAM Module 1GB DIMM DDR2                         | 2        | 0.86%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s              | 2        | 0.86%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                   | 2        | 0.86%   |
| Unknown RAM Module 1024MB DIMM                           | 2        | 0.86%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 2        | 0.86%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 2        | 0.86%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s      | 2        | 0.86%   |
| Samsung RAM M378B1G73DB0-CK0 8192MB DIMM DDR3 2133MT/s   | 2        | 0.86%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 2        | 0.86%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 2        | 0.86%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s    | 2        | 0.86%   |
| Kingston RAM KCM633-ELC 1024MB DIMM DDR2 2048MT/s        | 2        | 0.86%   |
| Kingston RAM 99U5471-012.A00LF 4096MB DIMM DDR3 1600MT/s | 2        | 0.86%   |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3333MT/s    | 2        | 0.86%   |
| Elpida RAM EBJ20UF8BCF0-DJ-F 2GB DIMM DDR3 1333MT/s      | 2        | 0.86%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s    | 2        | 0.86%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s     | 2        | 0.86%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s  | 1        | 0.43%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 0.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.43%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 0.43%   |
| Unknown RAM Module 8192MB DIMM SDRAM                     | 1        | 0.43%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s             | 1        | 0.43%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 0.43%   |
| Unknown RAM Module 512MB DIMM 400MT/s                    | 1        | 0.43%   |
| Unknown RAM Module 512MB DIMM 333MT/s                    | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                 | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 0.43%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s              | 1        | 0.43%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                   | 1        | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 71       | 37.37%  |
| DDR4    | 60       | 31.58%  |
| Unknown | 23       | 12.11%  |
| DDR2    | 19       | 10%     |
| SDRAM   | 13       | 6.84%   |
| DDR     | 3        | 1.58%   |
| LPDDR4  | 1        | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 177      | 95.68%  |
| SODIMM       | 6        | 3.24%   |
| Row Of Chips | 1        | 0.54%   |
| FB-DIMM      | 1        | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 66       | 31.58%  |
| 4096  | 59       | 28.23%  |
| 2048  | 38       | 18.18%  |
| 1024  | 24       | 11.48%  |
| 16384 | 17       | 8.13%   |
| 32768 | 4        | 1.91%   |
| 512   | 1        | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 37       | 18.05%  |
| 1333    | 33       | 16.1%   |
| 3200    | 16       | 7.8%    |
| 3600    | 15       | 7.32%   |
| 800     | 15       | 7.32%   |
| Unknown | 12       | 5.85%   |
| 2133    | 7        | 3.41%   |
| 3466    | 6        | 2.93%   |
| 2400    | 6        | 2.93%   |
| 1866    | 6        | 2.93%   |
| 667     | 6        | 2.93%   |
| 3000    | 4        | 1.95%   |
| 2667    | 4        | 1.95%   |
| 1800    | 4        | 1.95%   |
| 333     | 4        | 1.95%   |
| 1867    | 3        | 1.46%   |
| 400     | 3        | 1.46%   |
| 3333    | 2        | 0.98%   |
| 2800    | 2        | 0.98%   |
| 2666    | 2        | 0.98%   |
| 2048    | 2        | 0.98%   |
| 1066    | 2        | 0.98%   |
| 49926   | 1        | 0.49%   |
| 4400    | 1        | 0.49%   |
| 4000    | 1        | 0.49%   |
| 3800    | 1        | 0.49%   |
| 3666    | 1        | 0.49%   |
| 3400    | 1        | 0.49%   |
| 3151    | 1        | 0.49%   |
| 2933    | 1        | 0.49%   |
| 2200    | 1        | 0.49%   |
| 2134    | 1        | 0.49%   |
| 1639    | 1        | 0.49%   |
| 1400    | 1        | 0.49%   |
| 976     | 1        | 0.49%   |
| 533     | 1        | 0.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 18       | 24.66%  |
| Canon               | 18       | 24.66%  |
| Brother Industries  | 14       | 19.18%  |
| Samsung Electronics | 10       | 13.7%   |
| Seiko Epson         | 8        | 10.96%  |
| Toshiba TEC         | 1        | 1.37%   |
| STMicroelectronics  | 1        | 1.37%   |
| Ricoh               | 1        | 1.37%   |
| QinHeng Electronics | 1        | 1.37%   |
| Pantum              | 1        | 1.37%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Canon TS3100 series                                       | 3        | 4.11%   |
| Canon PIXMA MG2500 Series                                 | 3        | 4.11%   |
| Seiko Epson L3110 Series                                  | 2        | 2.74%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 2.74%   |
| HP ENVY 5000 series                                       | 2        | 2.74%   |
| HP ENVY 4520 series                                       | 2        | 2.74%   |
| Canon MF4010 series                                       | 2        | 2.74%   |
| Brother HL-2130 series                                    | 2        | 2.74%   |
| Toshiba TEC e-STD120 USB                                  | 1        | 1.37%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 1.37%   |
| Seiko Epson XP-7100 Series                                | 1        | 1.37%   |
| Seiko Epson XP-202 203 206 Series                         | 1        | 1.37%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1        | 1.37%   |
| Seiko Epson L222 Series                                   | 1        | 1.37%   |
| Seiko Epson L120 Series                                   | 1        | 1.37%   |
| Seiko Epson ET-2820 Series                                | 1        | 1.37%   |
| Samsung SCX-483x 5x3x Series                              | 1        | 1.37%   |
| Samsung SCX-4200 series                                   | 1        | 1.37%   |
| Samsung SCX-3400 Series                                   | 1        | 1.37%   |
| Samsung ML-2950 Series                                    | 1        | 1.37%   |
| Samsung ML-2010P Mono Laser Printer                       | 1        | 1.37%   |
| Samsung M2070 Series                                      | 1        | 1.37%   |
| Samsung CLX-3300 Series                                   | 1        | 1.37%   |
| Samsung C460 Series                                       | 1        | 1.37%   |
| Ricoh SP C250SF                                           | 1        | 1.37%   |
| QinHeng CH340S                                            | 1        | 1.37%   |
| Pantum P2500W series                                      | 1        | 1.37%   |
| HP Smart Tank 510 series                                  | 1        | 1.37%   |
| HP OfficeJet 4650 series                                  | 1        | 1.37%   |
| HP OfficeJet 3830 series                                  | 1        | 1.37%   |
| HP LaserJet Professional P1102w                           | 1        | 1.37%   |
| HP LaserJet Professional P 1102w                          | 1        | 1.37%   |
| HP LaserJet P2014                                         | 1        | 1.37%   |
| HP LaserJet P1102                                         | 1        | 1.37%   |
| HP LaserJet 3050                                          | 1        | 1.37%   |
| HP DeskJet F2492 All-in-One                               | 1        | 1.37%   |
| HP DeskJet 930c                                           | 1        | 1.37%   |
| HP Deskjet 4620 series                                    | 1        | 1.37%   |
| HP Deskjet 3050A                                          | 1        | 1.37%   |
| HP DeskJet 2700 series                                    | 1        | 1.37%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 8        | 80%     |
| Hewlett-Packard | 2        | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan LiDE 100            | 2        | 20%     |
| HP ScanJet 2400c                   | 1        | 10%     |
| HP PSC 1200                        | 1        | 10%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 10%     |
| Canon CanoScan LiDE 60             | 1        | 10%     |
| Canon CanoScan LIDE 25             | 1        | 10%     |
| Canon CanoScan LiDE 110            | 1        | 10%     |
| Canon CanoScan D660U               | 1        | 10%     |
| Canon CanoScan 8800F               | 1        | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 48       | 26.97%  |
| Microdia                      | 18       | 10.11%  |
| Microsoft                     | 15       | 8.43%   |
| Samsung Electronics           | 9        | 5.06%   |
| Chicony Electronics           | 8        | 4.49%   |
| Apple                         | 8        | 4.49%   |
| Sunplus Innovation Technology | 6        | 3.37%   |
| ARC International             | 6        | 3.37%   |
| Generalplus Technology        | 5        | 2.81%   |
| Cubeternet                    | 5        | 2.81%   |
| Jieli Technology              | 4        | 2.25%   |
| Z-Star Microelectronics       | 3        | 1.69%   |
| IMC Networks                  | 3        | 1.69%   |
| Arkmicro Technologies         | 3        | 1.69%   |
| Xiongmai                      | 2        | 1.12%   |
| Sonix Technology              | 2        | 1.12%   |
| Realtek Semiconductor         | 2        | 1.12%   |
| Razer USA                     | 2        | 1.12%   |
| Guillemot                     | 2        | 1.12%   |
| Genesys Logic                 | 2        | 1.12%   |
| Creative Technology           | 2        | 1.12%   |
| AVerMedia Technologies        | 2        | 1.12%   |
| Aveo Technology               | 2        | 1.12%   |
| Alcor Micro                   | 2        | 1.12%   |
| 2M UVC CAMERA                 | 2        | 1.12%   |
| Unknown                       | 1        | 0.56%   |
| Tobii Technology AB           | 1        | 0.56%   |
| Teslong Camera                | 1        | 0.56%   |
| Suyin                         | 1        | 0.56%   |
| Sunplus Technology            | 1        | 0.56%   |
| Pixart Imaging                | 1        | 0.56%   |
| Novatel Wireless              | 1        | 0.56%   |
| Novatek Microelectronics      | 1        | 0.56%   |
| lihappe8                      | 1        | 0.56%   |
| LG Electronics                | 1        | 0.56%   |
| INOGENI                       | 1        | 0.56%   |
| Huawei Technologies           | 1        | 0.56%   |
| Hewlett-Packard               | 1        | 0.56%   |
| GEMBIRD                       | 1        | 0.56%   |
| A4Tech                        | 1        | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 16       | 8.89%   |
| Samsung Galaxy A5 (MTP)               | 9        | 5%      |
| Microsoft LifeCam HD-3000             | 7        | 3.89%   |
| Apple iPhone5/5C/5S/6                 | 7        | 3.89%   |
| Logitech HD Pro Webcam C920           | 6        | 3.33%   |
| ARC International Camera              | 6        | 3.33%   |
| Chicony HP High Definition 1MP Webcam | 5        | 2.78%   |
| Jieli USB PHY 2.0                     | 4        | 2.22%   |
| Generalplus GENERAL WEBCAM            | 4        | 2.22%   |
| Sunplus HD 720P webcam                | 3        | 1.67%   |
| Microdia Webcam Vitade AF             | 3        | 1.67%   |
| Logitech C922 Pro Stream Webcam       | 3        | 1.67%   |
| Cubeternet GL-UPC822 UVC WebCam       | 3        | 1.67%   |
| Xiongmai web camera                   | 2        | 1.11%   |
| Razer USA Gaming Webcam [Kiyo]        | 2        | 1.11%   |
| Microsoft LifeCam VX-2000             | 2        | 1.11%   |
| Microdia USB Live camera              | 2        | 1.11%   |
| Microdia USB 2.0 Camera               | 2        | 1.11%   |
| Microdia Integrated Camera            | 2        | 1.11%   |
| Microdia CameraA                      | 2        | 1.11%   |
| Microdia Camera                       | 2        | 1.11%   |
| Logitech Webcam C310                  | 2        | 1.11%   |
| Logitech Webcam C250                  | 2        | 1.11%   |
| Logitech QuickCam Pro 9000            | 2        | 1.11%   |
| Logitech HD Webcam C910               | 2        | 1.11%   |
| Logitech HD Webcam C615               | 2        | 1.11%   |
| Logitech HD Webcam C525               | 2        | 1.11%   |
| Logitech C920 PRO HD Webcam           | 2        | 1.11%   |
| AVerMedia Live Streamer CAM 313       | 2        | 1.11%   |
| Arkmicro USB2.0 PC CAMERA             | 2        | 1.11%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam   | 2        | 1.11%   |
| Z-Star Venus USB2.0 Camera            | 1        | 0.56%   |
| Z-Star Vega USB 2.0 Camera            | 1        | 0.56%   |
| Z-Star Integrated Camera              | 1        | 0.56%   |
| Unknown HD camera                     | 1        | 0.56%   |
| Tobii AB EyeChip                      | 1        | 0.56%   |
| Teslong Camera Teslong Camera         | 1        | 0.56%   |
| Suyin HD WebCam                       | 1        | 0.56%   |
| Sunplus General Image Device          | 1        | 0.56%   |
| Sunplus Integrated Camera             | 1        | 0.56%   |

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


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Alcor Micro               | 2        | 28.57%  |
| Reiner SCT Kartensysteme  | 1        | 14.29%  |
| Realtek Semiconductor     | 1        | 14.29%  |
| Kobil Systems             | 1        | 14.29%  |
| Fujitsu Siemens Computers | 1        | 14.29%  |
| Advanced Card Systems     | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader               | 2        | 28.57%  |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad   | 1        | 14.29%  |
| Realtek Semiconductor Smart Card Reader Interface | 1        | 14.29%  |
| Kobil Systems KOBIL Class 3 Reader                | 1        | 14.29%  |
| Fujitsu Siemens Computers SmartCard Reader 2A     | 1        | 14.29%  |
| Advanced Card Systems ACR39U                      | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1084     | 80.06%  |
| 1     | 236      | 17.43%  |
| 2     | 29       | 2.14%   |
| 3     | 4        | 0.3%    |
| 4     | 1        | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 122      | 41.22%  |
| Net/wireless             | 100      | 33.78%  |
| Communication controller | 25       | 8.45%   |
| Multimedia controller    | 15       | 5.07%   |
| Unassigned class         | 9        | 3.04%   |
| Modem                    | 6        | 2.03%   |
| Chipcard                 | 6        | 2.03%   |
| Sound                    | 3        | 1.01%   |
| Storage/raid             | 2        | 0.68%   |
| Camera                   | 2        | 0.68%   |
| Storage/nvme             | 1        | 0.34%   |
| Storage/ide              | 1        | 0.34%   |
| Storage                  | 1        | 0.34%   |
| Fingerprint reader       | 1        | 0.34%   |
| Dvb card                 | 1        | 0.34%   |
| Card reader              | 1        | 0.34%   |

