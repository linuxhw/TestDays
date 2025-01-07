Linux in Colombia - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Colombia.

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

Total: 564

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 1497                        | [256c3def88](https://linux-hardware.org/?probe=256c3def88) | Dec 29, 2024 |
| JGINYUE       | X99 TITANIUM D3             | [bb9134a8a6](https://linux-hardware.org/?probe=bb9134a8a6) | Dec 11, 2024 |
| ASUSTek       | PRIME B460M-A               | [275b70a9b3](https://linux-hardware.org/?probe=275b70a9b3) | Dec 09, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [22bfeaf18d](https://linux-hardware.org/?probe=22bfeaf18d) | Dec 08, 2024 |
| ASUSTek       | PRIME B460M-A               | [422c8408b1](https://linux-hardware.org/?probe=422c8408b1) | Dec 07, 2024 |
| HP            | 3398                        | [3be901c90e](https://linux-hardware.org/?probe=3be901c90e) | Dec 06, 2024 |
| Dell          | 0HD5W2 A01                  | [f02fe6c8da](https://linux-hardware.org/?probe=f02fe6c8da) | Dec 03, 2024 |
| Dell          | 0HD5W2 A01                  | [f9aa503983](https://linux-hardware.org/?probe=f9aa503983) | Dec 03, 2024 |
| Gigabyte      | B450M DS3H-CF               | [cb0e4decea](https://linux-hardware.org/?probe=cb0e4decea) | Dec 02, 2024 |
| Gigabyte      | H97M-DS3P                   | [0d1e9eec2d](https://linux-hardware.org/?probe=0d1e9eec2d) | Nov 20, 2024 |
| MSI           | A520M-A PRO                 | [70aebceb5e](https://linux-hardware.org/?probe=70aebceb5e) | Nov 18, 2024 |
| Gigabyte      | B450M DS3H-CF               | [1e4f8fa6f5](https://linux-hardware.org/?probe=1e4f8fa6f5) | Nov 16, 2024 |
| Lenovo        | 0B98401 PRO                 | [2f5cd15407](https://linux-hardware.org/?probe=2f5cd15407) | Nov 14, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [60639f7365](https://linux-hardware.org/?probe=60639f7365) | Nov 14, 2024 |
| MSI           | MPG B550I GAMING EDGE MA... | [62bd667a99](https://linux-hardware.org/?probe=62bd667a99) | Oct 26, 2024 |
| Gigabyte      | A320M-S2H-CF                | [26bd161f46](https://linux-hardware.org/?probe=26bd161f46) | Oct 21, 2024 |
| Quanta        | 2AC7 011                    | [36d655acf6](https://linux-hardware.org/?probe=36d655acf6) | Oct 16, 2024 |
| Intel         | H81                         | [6a28d6befb](https://linux-hardware.org/?probe=6a28d6befb) | Oct 10, 2024 |
| MSI           | B150A GAMING PRO            | [4d5f7679d0](https://linux-hardware.org/?probe=4d5f7679d0) | Oct 06, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [37e187d1c9](https://linux-hardware.org/?probe=37e187d1c9) | Oct 06, 2024 |
| Compumax C... | AMD Ryzen 5000U             | [9f694c0c87](https://linux-hardware.org/?probe=9f694c0c87) | Oct 02, 2024 |
| ECS           | H61H2-MV                    | [29d29072da](https://linux-hardware.org/?probe=29d29072da) | Oct 01, 2024 |
| MSI           | A520M-A PRO                 | [d6ed4a9deb](https://linux-hardware.org/?probe=d6ed4a9deb) | Sep 29, 2024 |
| MSI           | H81M-E33                    | [358f1f3405](https://linux-hardware.org/?probe=358f1f3405) | Sep 28, 2024 |
| ASUSTek       | B150 PRO GAMING D3          | [9342e97a46](https://linux-hardware.org/?probe=9342e97a46) | Sep 28, 2024 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [2b248e2664](https://linux-hardware.org/?probe=2b248e2664) | Sep 28, 2024 |
| ASUSTek       | M4A79T Deluxe               | [cef2225be4](https://linux-hardware.org/?probe=cef2225be4) | Sep 19, 2024 |
| MSI           | PRO H510M-B                 | [020620e4c2](https://linux-hardware.org/?probe=020620e4c2) | Sep 18, 2024 |
| MSI           | PRO H510M-B                 | [892b66d32f](https://linux-hardware.org/?probe=892b66d32f) | Sep 18, 2024 |
| MSI           | H81M-E33                    | [c91a805424](https://linux-hardware.org/?probe=c91a805424) | Sep 18, 2024 |
| ASUSTek       | P8H61-M LX3                 | [fef809274c](https://linux-hardware.org/?probe=fef809274c) | Sep 12, 2024 |
| Intel         | H61                         | [26ad2a6fdf](https://linux-hardware.org/?probe=26ad2a6fdf) | Sep 10, 2024 |
| Foxconn       | G31MV/G31MV-K FAB           | [cdd64926ef](https://linux-hardware.org/?probe=cdd64926ef) | Sep 06, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8fe595fe5f](https://linux-hardware.org/?probe=8fe595fe5f) | Sep 05, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [c679b1e522](https://linux-hardware.org/?probe=c679b1e522) | Sep 03, 2024 |
| Gigabyte      | B250M-DS3H-CF               | [21851ce5cc](https://linux-hardware.org/?probe=21851ce5cc) | Sep 02, 2024 |
| ECS           | H81H3-M4                    | [a1a53ea4b7](https://linux-hardware.org/?probe=a1a53ea4b7) | Aug 29, 2024 |
| ECS           | H81H3-M4                    | [07bf45f673](https://linux-hardware.org/?probe=07bf45f673) | Aug 29, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [6bfb0ed86d](https://linux-hardware.org/?probe=6bfb0ed86d) | Aug 24, 2024 |
| MSI           | MS-7253                     | [024d2de5c9](https://linux-hardware.org/?probe=024d2de5c9) | Aug 24, 2024 |
| Intel         | DH61BF AAG81311-101         | [a099b50209](https://linux-hardware.org/?probe=a099b50209) | Aug 23, 2024 |
| Intel         | DH61BF AAG81311-101         | [b235f2f382](https://linux-hardware.org/?probe=b235f2f382) | Aug 23, 2024 |
| HP            | 2129                        | [1eb65765a8](https://linux-hardware.org/?probe=1eb65765a8) | Aug 22, 2024 |
| HP            | 2129                        | [23ae96f746](https://linux-hardware.org/?probe=23ae96f746) | Aug 20, 2024 |
| ASRock        | H61M-VG3                    | [bd7e312add](https://linux-hardware.org/?probe=bd7e312add) | Aug 18, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | [accba7b6c9](https://linux-hardware.org/?probe=accba7b6c9) | Aug 18, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | [dbda8656d2](https://linux-hardware.org/?probe=dbda8656d2) | Aug 18, 2024 |
| ASRock        | B450M-HDV R4.0              | [befe3e1358](https://linux-hardware.org/?probe=befe3e1358) | Aug 15, 2024 |
| MSI           | Z77A-G41                    | [85eb1d0f02](https://linux-hardware.org/?probe=85eb1d0f02) | Aug 09, 2024 |
| ECS           | H81H3-M4                    | [64dcbcc2da](https://linux-hardware.org/?probe=64dcbcc2da) | Aug 06, 2024 |
| MSI           | MS-7253                     | [89164c8b71](https://linux-hardware.org/?probe=89164c8b71) | Jul 25, 2024 |
| ASUSTek       | TUF X470-PLUS GAMING        | [027ce3ae0f](https://linux-hardware.org/?probe=027ce3ae0f) | Jul 21, 2024 |
| Dell          | 08NPPY A01                  | [03c5024ab6](https://linux-hardware.org/?probe=03c5024ab6) | Jul 19, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [67f8fcdd69](https://linux-hardware.org/?probe=67f8fcdd69) | Jul 19, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [ea7ab46b40](https://linux-hardware.org/?probe=ea7ab46b40) | Jul 17, 2024 |
| ASRock        | A320M-HDV R4.0              | [ab1d6d4f02](https://linux-hardware.org/?probe=ab1d6d4f02) | Jul 11, 2024 |
| Dell          | 0KYJ8C A00                  | [0cda74adb5](https://linux-hardware.org/?probe=0cda74adb5) | Jun 25, 2024 |
| ASUSTek       | PRIME X670-P                | [157fc29a20](https://linux-hardware.org/?probe=157fc29a20) | Jun 21, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [53d5c7cd29](https://linux-hardware.org/?probe=53d5c7cd29) | Jun 19, 2024 |
| ASUSTek       | PRIME Z690-P D4             | [02e64270cf](https://linux-hardware.org/?probe=02e64270cf) | Jun 09, 2024 |
| MACHINIST     | E5-MR9A PRO V1.2            | [decba51c01](https://linux-hardware.org/?probe=decba51c01) | Jun 08, 2024 |
| Gigabyte      | X670E AORUS PRO X           | [fd6dc7b85b](https://linux-hardware.org/?probe=fd6dc7b85b) | Jun 06, 2024 |
| Gigabyte      | A520M DS3H                  | [e555435a07](https://linux-hardware.org/?probe=e555435a07) | Jun 05, 2024 |
| Intel         | DG41RQ AAE54511-203         | [5cd9b65fe2](https://linux-hardware.org/?probe=5cd9b65fe2) | Jun 05, 2024 |
| Dell          | 0D883F A06                  | [b05d49d4c6](https://linux-hardware.org/?probe=b05d49d4c6) | Jun 03, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [8e3332a712](https://linux-hardware.org/?probe=8e3332a712) | May 31, 2024 |
| Intel         | D945GCPE AAD97209-201       | [4b5c79152f](https://linux-hardware.org/?probe=4b5c79152f) | May 29, 2024 |
| Dell          | 08NPPY A01                  | [30ae7d8cc1](https://linux-hardware.org/?probe=30ae7d8cc1) | May 27, 2024 |
| ASUSTek       | H61M-K                      | [ed0fb6e87d](https://linux-hardware.org/?probe=ed0fb6e87d) | May 24, 2024 |
| Dell          | 0D883F A06                  | [d979b83929](https://linux-hardware.org/?probe=d979b83929) | May 16, 2024 |
| ASRock        | Z590 Steel Legend WiFi 6... | [9afb28537a](https://linux-hardware.org/?probe=9afb28537a) | May 16, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | [0fdd6d8d04](https://linux-hardware.org/?probe=0fdd6d8d04) | May 12, 2024 |
| Biostar       | G41D3B                      | [3f88596c99](https://linux-hardware.org/?probe=3f88596c99) | May 12, 2024 |
| PCSMART       | 7.0                         | [66d6082bf4](https://linux-hardware.org/?probe=66d6082bf4) | May 07, 2024 |
| Gigabyte      | H410M H V3                  | [486c191884](https://linux-hardware.org/?probe=486c191884) | May 07, 2024 |
| PCSMART       | 7.0                         | [18ea3d8d19](https://linux-hardware.org/?probe=18ea3d8d19) | May 05, 2024 |
| ASRock        | Wolfdale1333-D667           | [15e7baeeb3](https://linux-hardware.org/?probe=15e7baeeb3) | May 03, 2024 |
| ASRock        | Wolfdale1333-D667           | [9cfa5ae2c5](https://linux-hardware.org/?probe=9cfa5ae2c5) | May 03, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [c8e2add151](https://linux-hardware.org/?probe=c8e2add151) | May 03, 2024 |
| Intel         | X79G V2.x                   | [00807bfaa6](https://linux-hardware.org/?probe=00807bfaa6) | May 02, 2024 |
| Biostar       | G41D3B                      | [748e0749c5](https://linux-hardware.org/?probe=748e0749c5) | Apr 30, 2024 |
| ASRock        | N68-S                       | [a099ad6775](https://linux-hardware.org/?probe=a099ad6775) | Apr 30, 2024 |
| Gigabyte      | X670E AORUS PRO X           | [ac94661695](https://linux-hardware.org/?probe=ac94661695) | Apr 24, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [07cede8279](https://linux-hardware.org/?probe=07cede8279) | Apr 17, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [be0f54854d](https://linux-hardware.org/?probe=be0f54854d) | Apr 10, 2024 |
| MSI           | NF725M-P43                  | [9fc3ac2e10](https://linux-hardware.org/?probe=9fc3ac2e10) | Apr 07, 2024 |
| MSI           | A320M PRO-VH PLUS           | [943c2e486a](https://linux-hardware.org/?probe=943c2e486a) | Apr 05, 2024 |
| ASUSTek       | PRIME B550M-A AC            | [61f8f4ee36](https://linux-hardware.org/?probe=61f8f4ee36) | Apr 03, 2024 |
| MSI           | 760GM-P21                   | [9ea00e6ebb](https://linux-hardware.org/?probe=9ea00e6ebb) | Mar 22, 2024 |
| Acer          | Predator G3-710             | [81423396ff](https://linux-hardware.org/?probe=81423396ff) | Mar 16, 2024 |
| Acer          | Predator G3-710             | [4a28c9273f](https://linux-hardware.org/?probe=4a28c9273f) | Mar 16, 2024 |
| ASUSTek       | PRIME B450M-A II            | [903192b99a](https://linux-hardware.org/?probe=903192b99a) | Mar 09, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [27e68f4135](https://linux-hardware.org/?probe=27e68f4135) | Mar 07, 2024 |
| ASUSTek       | PRIME A520M-A II            | [6e87e2444b](https://linux-hardware.org/?probe=6e87e2444b) | Mar 05, 2024 |
| HP            | 1495                        | [ee01c60448](https://linux-hardware.org/?probe=ee01c60448) | Feb 29, 2024 |
| Intel         | X79G V2.x                   | [077f5b4397](https://linux-hardware.org/?probe=077f5b4397) | Feb 15, 2024 |
| Lenovo        | ThinkStation D30 4223AU4    | [bd10aa2839](https://linux-hardware.org/?probe=bd10aa2839) | Feb 13, 2024 |
| ASUSTek       | PRIME A320M-A               | [f85fa50f25](https://linux-hardware.org/?probe=f85fa50f25) | Feb 08, 2024 |
| Biostar       | A58ML                       | [207acb5012](https://linux-hardware.org/?probe=207acb5012) | Feb 07, 2024 |
| ASRock        | X670E Pro RS                | [b5f16b7125](https://linux-hardware.org/?probe=b5f16b7125) | Feb 03, 2024 |
| ASRock        | X670E Pro RS                | [fd02477c14](https://linux-hardware.org/?probe=fd02477c14) | Feb 02, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6dbdc40268](https://linux-hardware.org/?probe=6dbdc40268) | Jan 22, 2024 |
| Lenovo        | ThinkCentre A62 9486E4S     | [426fe50b95](https://linux-hardware.org/?probe=426fe50b95) | Jan 21, 2024 |
| Lenovo        | ThinkCentre A62 9486E4S     | [9712c9e135](https://linux-hardware.org/?probe=9712c9e135) | Jan 21, 2024 |
| ASUSTek       | PRIME H610M-E D4            | [409e7e4e42](https://linux-hardware.org/?probe=409e7e4e42) | Jan 17, 2024 |
| HP            | 18E5                        | [4fb3a76631](https://linux-hardware.org/?probe=4fb3a76631) | Jan 15, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [23c4e3e208](https://linux-hardware.org/?probe=23c4e3e208) | Jan 13, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b98091e5e6](https://linux-hardware.org/?probe=b98091e5e6) | Jan 13, 2024 |
| Intel         | X79G V2.x                   | [cf61b1759b](https://linux-hardware.org/?probe=cf61b1759b) | Jan 12, 2024 |
| MSI           | GF615M-P33                  | [7d32db9104](https://linux-hardware.org/?probe=7d32db9104) | Jan 12, 2024 |
| ASRock        | X670E Pro RS                | [2f899514f8](https://linux-hardware.org/?probe=2f899514f8) | Jan 12, 2024 |
| MSI           | A320M PRO-VH PLUS           | [3ff7f414fe](https://linux-hardware.org/?probe=3ff7f414fe) | Jan 07, 2024 |
| MSI           | H81M-E33                    | [cced2d2e95](https://linux-hardware.org/?probe=cced2d2e95) | Jan 07, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [f10936a9f7](https://linux-hardware.org/?probe=f10936a9f7) | Jan 02, 2024 |
| MSI           | PRO Z790-A WIFI             | [40362f198b](https://linux-hardware.org/?probe=40362f198b) | Dec 31, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [863f0b5c06](https://linux-hardware.org/?probe=863f0b5c06) | Dec 29, 2023 |
| Gigabyte      | H61M-S1                     | [6b98d84cb0](https://linux-hardware.org/?probe=6b98d84cb0) | Dec 28, 2023 |
| HP            | 339A                        | [49cb574539](https://linux-hardware.org/?probe=49cb574539) | Dec 27, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | [3c0ecabaa3](https://linux-hardware.org/?probe=3c0ecabaa3) | Dec 27, 2023 |
| MSI           | A320M PRO-VH PLUS           | [53fae0e708](https://linux-hardware.org/?probe=53fae0e708) | Dec 25, 2023 |
| MSI           | A320M PRO-VH PLUS           | [0a5b67d3f4](https://linux-hardware.org/?probe=0a5b67d3f4) | Dec 24, 2023 |
| MSI           | PRO Z790-A WIFI             | [8becdfe1a4](https://linux-hardware.org/?probe=8becdfe1a4) | Dec 23, 2023 |
| MSI           | PRO Z790-A WIFI             | [ff13629db9](https://linux-hardware.org/?probe=ff13629db9) | Dec 23, 2023 |
| ASUSTek       | PRIME B460M-A               | [1c7f9648af](https://linux-hardware.org/?probe=1c7f9648af) | Dec 14, 2023 |
| MSI           | A88XM GAMING                | [1f17749a2e](https://linux-hardware.org/?probe=1f17749a2e) | Dec 12, 2023 |
| Gigabyte      | Z77-DS3H                    | [03c91234ae](https://linux-hardware.org/?probe=03c91234ae) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c71a153915](https://linux-hardware.org/?probe=c71a153915) | Dec 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [31943290a3](https://linux-hardware.org/?probe=31943290a3) | Dec 09, 2023 |
| ASUSTek       | PRIME A320M-K               | [74512675b8](https://linux-hardware.org/?probe=74512675b8) | Dec 09, 2023 |
| ASUSTek       | PRIME A320M-K               | [0c4e850e29](https://linux-hardware.org/?probe=0c4e850e29) | Dec 08, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [46a43fa59d](https://linux-hardware.org/?probe=46a43fa59d) | Dec 02, 2023 |
| Intel         | DG41RQ AAE54511-205         | [8646f4d21b](https://linux-hardware.org/?probe=8646f4d21b) | Dec 01, 2023 |
| Dell          | 0478VN A00                  | [9673d66df0](https://linux-hardware.org/?probe=9673d66df0) | Nov 28, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [ee5fe89209](https://linux-hardware.org/?probe=ee5fe89209) | Nov 28, 2023 |
| ASUSTek       | PRIME B450M-A II            | [e05084a6aa](https://linux-hardware.org/?probe=e05084a6aa) | Nov 26, 2023 |
| Dell          | 0F373D A00                  | [653b4e617f](https://linux-hardware.org/?probe=653b4e617f) | Nov 25, 2023 |
| Dell          | 0F373D A00                  | [92392e304b](https://linux-hardware.org/?probe=92392e304b) | Nov 24, 2023 |
| HP            | 1495                        | [c03adda1fa](https://linux-hardware.org/?probe=c03adda1fa) | Nov 20, 2023 |
| HP            | 8105                        | [d77d0abf96](https://linux-hardware.org/?probe=d77d0abf96) | Nov 15, 2023 |
| HP            | 198E                        | [f1d1b6839f](https://linux-hardware.org/?probe=f1d1b6839f) | Nov 05, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [4236902f3d](https://linux-hardware.org/?probe=4236902f3d) | Nov 03, 2023 |
| Dell          | 0200DY A02                  | [f07206a75c](https://linux-hardware.org/?probe=f07206a75c) | Nov 02, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [385c30cad6](https://linux-hardware.org/?probe=385c30cad6) | Oct 31, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [e3db582993](https://linux-hardware.org/?probe=e3db582993) | Oct 31, 2023 |
| Dell          | 08NPPY A01                  | [62bc2b3e7a](https://linux-hardware.org/?probe=62bc2b3e7a) | Oct 28, 2023 |
| Lenovo        | 0B98409 STD                 | [b89f42b23f](https://linux-hardware.org/?probe=b89f42b23f) | Oct 24, 2023 |
| MSI           | A320M PRO-VH PLUS           | [92dbf8615b](https://linux-hardware.org/?probe=92dbf8615b) | Oct 24, 2023 |
| Intel         | X79G V2.x                   | [49d37b87cf](https://linux-hardware.org/?probe=49d37b87cf) | Oct 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | [b552badf93](https://linux-hardware.org/?probe=b552badf93) | Oct 17, 2023 |
| Intel         | DG41RQ AAE54511-203         | [64738e1724](https://linux-hardware.org/?probe=64738e1724) | Oct 15, 2023 |
| ASUSTek       | H81M-A                      | [0702e52c02](https://linux-hardware.org/?probe=0702e52c02) | Oct 14, 2023 |
| ASUSTek       | PRIME B450M-A II            | [4ba8548e96](https://linux-hardware.org/?probe=4ba8548e96) | Oct 14, 2023 |
| Lenovo        | ThinkCentre M90 5485AK7     | [02e02dbca5](https://linux-hardware.org/?probe=02e02dbca5) | Oct 11, 2023 |
| MACHINIST     | E5-MR9A PRO V1.2            | [668d09e797](https://linux-hardware.org/?probe=668d09e797) | Oct 07, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [6ff82127e5](https://linux-hardware.org/?probe=6ff82127e5) | Oct 05, 2023 |
| Intel         | DG41RQ AAE54511-202         | [5d2ec27525](https://linux-hardware.org/?probe=5d2ec27525) | Oct 03, 2023 |
| ASUSTek       | NAGAMI2                     | [c0e4ce344f](https://linux-hardware.org/?probe=c0e4ce344f) | Sep 14, 2023 |
| Gigabyte      | H61M-S1                     | [c0bbe7d2b4](https://linux-hardware.org/?probe=c0bbe7d2b4) | Sep 09, 2023 |
| MSI           | A320M PRO-VH PLUS           | [9614656d9b](https://linux-hardware.org/?probe=9614656d9b) | Sep 05, 2023 |
| HP            | 82E0                        | [a86ac881df](https://linux-hardware.org/?probe=a86ac881df) | Sep 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | [3e2b7d52c5](https://linux-hardware.org/?probe=3e2b7d52c5) | Sep 05, 2023 |
| Intel         | DG31PR AAD97573-301         | [359e7817c3](https://linux-hardware.org/?probe=359e7817c3) | Sep 03, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [c972b65ed6](https://linux-hardware.org/?probe=c972b65ed6) | Sep 02, 2023 |
| Intel         | X79G V2.x                   | [658431c5b8](https://linux-hardware.org/?probe=658431c5b8) | Aug 22, 2023 |
| ASUSTek       | Pro B550M-C                 | [0af0e7a958](https://linux-hardware.org/?probe=0af0e7a958) | Aug 17, 2023 |
| MSI           | A320M PRO-VH PLUS           | [65a1f155c0](https://linux-hardware.org/?probe=65a1f155c0) | Aug 17, 2023 |
| Intel         | DH61CR AAG14064-207         | [25d122723f](https://linux-hardware.org/?probe=25d122723f) | Aug 15, 2023 |
| Intel         | DH61CR AAG14064-207         | [ae4eca1596](https://linux-hardware.org/?probe=ae4eca1596) | Aug 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [7637f0d91d](https://linux-hardware.org/?probe=7637f0d91d) | Aug 06, 2023 |
| MSI           | PRO H610M-G WIFI DDR4       | [d8b172537e](https://linux-hardware.org/?probe=d8b172537e) | Aug 04, 2023 |
| MSI           | A320M PRO-VH PLUS           | [f5cc7a2d00](https://linux-hardware.org/?probe=f5cc7a2d00) | Jul 30, 2023 |
| ASRock        | B85M                        | [d69487eb8d](https://linux-hardware.org/?probe=d69487eb8d) | Jul 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | [d8d58cb5fb](https://linux-hardware.org/?probe=d8d58cb5fb) | Jul 21, 2023 |
| MSI           | A320M PRO-VH PLUS           | [689b191bae](https://linux-hardware.org/?probe=689b191bae) | Jul 21, 2023 |
| Intel X79     | Unknown                     | [360facd1fb](https://linux-hardware.org/?probe=360facd1fb) | Jul 19, 2023 |
| MSI           | 970A-G46                    | [09496b3221](https://linux-hardware.org/?probe=09496b3221) | Jul 12, 2023 |
| MSI           | A320M PRO-VH PLUS           | [e99992afd5](https://linux-hardware.org/?probe=e99992afd5) | Jul 12, 2023 |
| HP            | 2820h                       | [ecbafa25c0](https://linux-hardware.org/?probe=ecbafa25c0) | Jul 10, 2023 |
| HP            | 2820h                       | [9d4f48820d](https://linux-hardware.org/?probe=9d4f48820d) | Jul 10, 2023 |
| HP            | 304Ah                       | [029412ce85](https://linux-hardware.org/?probe=029412ce85) | Jul 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | [a7c8848746](https://linux-hardware.org/?probe=a7c8848746) | Jul 03, 2023 |
| Intel         | SHARKBAY                    | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| Gigabyte      | H61M-HD2                    | [404728f350](https://linux-hardware.org/?probe=404728f350) | Jun 29, 2023 |
| Gigabyte      | B560M DS3H V2               | [aa24aa071b](https://linux-hardware.org/?probe=aa24aa071b) | Jun 28, 2023 |
| ASRock        | H55M                        | [cb9e89e20e](https://linux-hardware.org/?probe=cb9e89e20e) | Jun 24, 2023 |
| ASUSTek       | PRIME H410M-E               | [cc8a15081a](https://linux-hardware.org/?probe=cc8a15081a) | Jun 22, 2023 |
| Acer          | Veriton X490G               | [a181339180](https://linux-hardware.org/?probe=a181339180) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [5ff46d41fd](https://linux-hardware.org/?probe=5ff46d41fd) | Jun 18, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ddb9fc5a43](https://linux-hardware.org/?probe=ddb9fc5a43) | Jun 14, 2023 |
| Gigabyte      | B560M DS3H V2               | [1b8ad811e0](https://linux-hardware.org/?probe=1b8ad811e0) | Jun 12, 2023 |
| HP            | 82C9                        | [b696990030](https://linux-hardware.org/?probe=b696990030) | Jun 09, 2023 |
| HP            | 18EA                        | [d6e48a99e7](https://linux-hardware.org/?probe=d6e48a99e7) | Jun 08, 2023 |
| Acer          | Predator G3-710             | [7193d24262](https://linux-hardware.org/?probe=7193d24262) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [96834ea12b](https://linux-hardware.org/?probe=96834ea12b) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [c200dbb9cf](https://linux-hardware.org/?probe=c200dbb9cf) | Jun 04, 2023 |
| MSI           | A320M PRO-VH PLUS           | [8ba76b1e88](https://linux-hardware.org/?probe=8ba76b1e88) | Jun 03, 2023 |
| Gigabyte      | H61M-HD2                    | [7c57f43d4a](https://linux-hardware.org/?probe=7c57f43d4a) | May 29, 2023 |
| ASRock        | B450M-HDV R4.0              | [063077bd52](https://linux-hardware.org/?probe=063077bd52) | May 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [87a75f9dd9](https://linux-hardware.org/?probe=87a75f9dd9) | May 16, 2023 |
| Gigabyte      | GA-990FX-GAMING             | [d7503c22b2](https://linux-hardware.org/?probe=d7503c22b2) | May 16, 2023 |
| Gigabyte      | GA-990FX-GAMING             | [cc42c4e227](https://linux-hardware.org/?probe=cc42c4e227) | May 15, 2023 |
| ASUSTek       | PRIME A320M-K               | [a375533daa](https://linux-hardware.org/?probe=a375533daa) | May 05, 2023 |
| Gigabyte      | Z590 VISION G               | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [2dffd7bed6](https://linux-hardware.org/?probe=2dffd7bed6) | Apr 30, 2023 |
| Pegatron      | 2A73h                       | [f4578519ad](https://linux-hardware.org/?probe=f4578519ad) | Apr 21, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [c4d3eabb55](https://linux-hardware.org/?probe=c4d3eabb55) | Apr 17, 2023 |
| ASUSTek       | PRIME X570-P                | [337102cd4c](https://linux-hardware.org/?probe=337102cd4c) | Apr 15, 2023 |
| Gigabyte      | H61M-HD2                    | [ea4bae8ef7](https://linux-hardware.org/?probe=ea4bae8ef7) | Apr 13, 2023 |
| ASUSTek       | M4N98TD EVO                 | [a2423b5193](https://linux-hardware.org/?probe=a2423b5193) | Apr 07, 2023 |
| ASUSTek       | M4N98TD EVO                 | [8a2a2cf1ce](https://linux-hardware.org/?probe=8a2a2cf1ce) | Apr 07, 2023 |
| Gigabyte      | H310M H x.x                 | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| Lenovo        | ThinkServer TS130           | [2a36fc5043](https://linux-hardware.org/?probe=2a36fc5043) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [5c811e496f](https://linux-hardware.org/?probe=5c811e496f) | Mar 24, 2023 |
| ASUSTek       | M4N98TD EVO                 | [9cb4b84924](https://linux-hardware.org/?probe=9cb4b84924) | Mar 24, 2023 |
| ASRock        | X670E Pro RS                | [8437e47a82](https://linux-hardware.org/?probe=8437e47a82) | Mar 24, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [592d9de1cb](https://linux-hardware.org/?probe=592d9de1cb) | Mar 23, 2023 |
| HP            | 18E9                        | [2cc6071591](https://linux-hardware.org/?probe=2cc6071591) | Mar 20, 2023 |
| Lenovo        | MAHOBAY NOK                 | [04ba5a6790](https://linux-hardware.org/?probe=04ba5a6790) | Mar 18, 2023 |
| Lenovo        | MAHOBAY NOK                 | [fcbb054633](https://linux-hardware.org/?probe=fcbb054633) | Mar 18, 2023 |
| HP            | 1850                        | [c805a3a08f](https://linux-hardware.org/?probe=c805a3a08f) | Mar 17, 2023 |
| Gigabyte      | B550 AORUS PRO              | [b72b91fd00](https://linux-hardware.org/?probe=b72b91fd00) | Mar 16, 2023 |
| MSI           | H81M-P33                    | [cb3d11f591](https://linux-hardware.org/?probe=cb3d11f591) | Mar 15, 2023 |
| HP            | 1850                        | [c5439b2fea](https://linux-hardware.org/?probe=c5439b2fea) | Mar 15, 2023 |
| ASRock        | G31M-S                      | [7672cc15a2](https://linux-hardware.org/?probe=7672cc15a2) | Mar 13, 2023 |
| Biostar       | H61MHV                      | [9f184e6e93](https://linux-hardware.org/?probe=9f184e6e93) | Mar 11, 2023 |
| Intel         | DH61BF AAG81311-101         | [b960fb0ebf](https://linux-hardware.org/?probe=b960fb0ebf) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Acer          | Aspire X1400                | [195337bbc6](https://linux-hardware.org/?probe=195337bbc6) | Mar 07, 2023 |
| Gigabyte      | B460M AORUS PRO             | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| HP            | 806A                        | [66c29ddd8a](https://linux-hardware.org/?probe=66c29ddd8a) | Mar 03, 2023 |
| HP            | 2ADE                        | [b4309c2b06](https://linux-hardware.org/?probe=b4309c2b06) | Feb 23, 2023 |
| ASRock        | X670E Pro RS                | [906d11e2a3](https://linux-hardware.org/?probe=906d11e2a3) | Feb 19, 2023 |
| HP            | 18E9                        | [e3461fcb74](https://linux-hardware.org/?probe=e3461fcb74) | Feb 16, 2023 |
| HP            | 1497                        | [b27560d384](https://linux-hardware.org/?probe=b27560d384) | Feb 14, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [e4496f3ff8](https://linux-hardware.org/?probe=e4496f3ff8) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [5fe8eef781](https://linux-hardware.org/?probe=5fe8eef781) | Feb 09, 2023 |
| Unknown       | X79A                        | [eedea973ca](https://linux-hardware.org/?probe=eedea973ca) | Feb 05, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [edbd391f2d](https://linux-hardware.org/?probe=edbd391f2d) | Feb 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0c65146f4c](https://linux-hardware.org/?probe=0c65146f4c) | Jan 21, 2023 |
| Intel         | DH61BF AAG81311-101         | [d6ea5bde87](https://linux-hardware.org/?probe=d6ea5bde87) | Jan 21, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| ASRock        | G965M-S                     | [c1a6d7685b](https://linux-hardware.org/?probe=c1a6d7685b) | Jan 17, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [d569a3f698](https://linux-hardware.org/?probe=d569a3f698) | Jan 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d26bcd74b2](https://linux-hardware.org/?probe=d26bcd74b2) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | [faf7e2eae9](https://linux-hardware.org/?probe=faf7e2eae9) | Jan 10, 2023 |
| Gigabyte      | A520M DS3H                  | [e7107ee8b4](https://linux-hardware.org/?probe=e7107ee8b4) | Jan 06, 2023 |
| Gigabyte      | A520M DS3H                  | [e351ff5e1d](https://linux-hardware.org/?probe=e351ff5e1d) | Jan 05, 2023 |
| Intel         | DH61BF AAG81311-101         | [db8d3007ee](https://linux-hardware.org/?probe=db8d3007ee) | Jan 03, 2023 |
| MSI           | 880GM-E41                   | [2880803d71](https://linux-hardware.org/?probe=2880803d71) | Dec 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | [fe4ef75450](https://linux-hardware.org/?probe=fe4ef75450) | Dec 21, 2022 |
| Lenovo        | ThinkCentre A62 9486E4S     | [cb7cb7b7d7](https://linux-hardware.org/?probe=cb7cb7b7d7) | Dec 21, 2022 |
| Lenovo        | ThinkCentre A62 9486E4S     | [fcd0306cd3](https://linux-hardware.org/?probe=fcd0306cd3) | Dec 19, 2022 |
| ASUSTek       | M3N78-VM                    | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| HP            | 18E9                        | [9086d1a1e5](https://linux-hardware.org/?probe=9086d1a1e5) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [80b8b349f8](https://linux-hardware.org/?probe=80b8b349f8) | Nov 30, 2022 |
| Dell          | 0TP406                      | [3eceea61d2](https://linux-hardware.org/?probe=3eceea61d2) | Nov 30, 2022 |
| Dell          | 0TP406                      | [d22689331c](https://linux-hardware.org/?probe=d22689331c) | Nov 30, 2022 |
| HP            | 339A                        | [ea5cacd50e](https://linux-hardware.org/?probe=ea5cacd50e) | Nov 29, 2022 |
| Dell          | 0HJ054                      | [0e3d082d5a](https://linux-hardware.org/?probe=0e3d082d5a) | Nov 22, 2022 |
| Lenovo        | ThinkCentre M70e 0830AC4    | [8eb9b40274](https://linux-hardware.org/?probe=8eb9b40274) | Nov 10, 2022 |
| MSI           | GF615M-P33                  | [1a298da454](https://linux-hardware.org/?probe=1a298da454) | Nov 09, 2022 |
| Intel         | D33217GKE G76540-207        | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [a5d58af861](https://linux-hardware.org/?probe=a5d58af861) | Oct 31, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [b132f4c4e9](https://linux-hardware.org/?probe=b132f4c4e9) | Oct 30, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [7e1df59daa](https://linux-hardware.org/?probe=7e1df59daa) | Oct 30, 2022 |
| Biostar       | H61MH                       | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6edc8b1444](https://linux-hardware.org/?probe=6edc8b1444) | Oct 06, 2022 |
| Gigabyte      | G41MT-S2                    | [c0b1c8ad8f](https://linux-hardware.org/?probe=c0b1c8ad8f) | Sep 27, 2022 |
| HP            | 18E7                        | [710a40851e](https://linux-hardware.org/?probe=710a40851e) | Sep 18, 2022 |
| ASRock        | A520M-HDV                   | [9e4267bcc6](https://linux-hardware.org/?probe=9e4267bcc6) | Sep 15, 2022 |
| ASRock        | A520M-HDV                   | [bd9b94b7f8](https://linux-hardware.org/?probe=bd9b94b7f8) | Sep 15, 2022 |
| HP            | 1494                        | [0faa06cff4](https://linux-hardware.org/?probe=0faa06cff4) | Sep 12, 2022 |
| ECS           | H61H2-M2                    | [9735a8ef90](https://linux-hardware.org/?probe=9735a8ef90) | Sep 01, 2022 |
| Pegatron      | 2AB6                        | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [04474401fc](https://linux-hardware.org/?probe=04474401fc) | Aug 26, 2022 |
| ECS           | H61H2-M2                    | [72ebc08e0c](https://linux-hardware.org/?probe=72ebc08e0c) | Aug 26, 2022 |
| ASUSTek       | TUF B365-PLUS GAMING        | [83e59cf9a5](https://linux-hardware.org/?probe=83e59cf9a5) | Aug 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ECS           | H61H2-M2                    | [97ec1c67e8](https://linux-hardware.org/?probe=97ec1c67e8) | Aug 21, 2022 |
| BESSTAR Te... | TH50                        | [03159c112c](https://linux-hardware.org/?probe=03159c112c) | Aug 12, 2022 |
| ASRock        | B550M Pro4                  | [7fa92e1cb6](https://linux-hardware.org/?probe=7fa92e1cb6) | Aug 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [08b891334e](https://linux-hardware.org/?probe=08b891334e) | Aug 08, 2022 |
| HP            | ProLiant ML310e Gen8        | [7a12318176](https://linux-hardware.org/?probe=7a12318176) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [68d8843883](https://linux-hardware.org/?probe=68d8843883) | Jul 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [057b18a904](https://linux-hardware.org/?probe=057b18a904) | Jul 16, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [97b45f9af7](https://linux-hardware.org/?probe=97b45f9af7) | Jul 12, 2022 |
| Dell          | 054KM3 A01                  | [149f746382](https://linux-hardware.org/?probe=149f746382) | Jul 02, 2022 |
| ASRock        | A320M-HDV                   | [ec991b1524](https://linux-hardware.org/?probe=ec991b1524) | Jun 27, 2022 |
| MSI           | H81M-E33                    | [d79b11186c](https://linux-hardware.org/?probe=d79b11186c) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | [8caff7e62e](https://linux-hardware.org/?probe=8caff7e62e) | Jun 25, 2022 |
| Dell          | 0J2J3Y A00                  | [50f015312c](https://linux-hardware.org/?probe=50f015312c) | Jun 23, 2022 |
| MSI           | H81M-E33                    | [0d2ace0dde](https://linux-hardware.org/?probe=0d2ace0dde) | Jun 16, 2022 |
| MSI           | H81M-E33                    | [52dbd6f482](https://linux-hardware.org/?probe=52dbd6f482) | Jun 16, 2022 |
| Gigabyte      | H61M-HD2                    | [d6e6a17072](https://linux-hardware.org/?probe=d6e6a17072) | Jun 13, 2022 |
| MSI           | G31TM-P21                   | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| HP            | 8054                        | [7d7b7577db](https://linux-hardware.org/?probe=7d7b7577db) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2bd8d64c3b](https://linux-hardware.org/?probe=2bd8d64c3b) | May 22, 2022 |
| Gigabyte      | 990FXA-UD3                  | [4bc8f93383](https://linux-hardware.org/?probe=4bc8f93383) | May 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | [89b16a89c5](https://linux-hardware.org/?probe=89b16a89c5) | May 16, 2022 |
| ASUSTek       | H81M-K                      | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [af01f27647](https://linux-hardware.org/?probe=af01f27647) | Apr 30, 2022 |
| Pegatron      | 2A73h                       | [a756a0148d](https://linux-hardware.org/?probe=a756a0148d) | Apr 27, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [7b24feb14a](https://linux-hardware.org/?probe=7b24feb14a) | Apr 21, 2022 |
| ASUSTek       | PRIME Z390-A                | [81d7ace164](https://linux-hardware.org/?probe=81d7ace164) | Apr 18, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [65a5442605](https://linux-hardware.org/?probe=65a5442605) | Apr 04, 2022 |
| HP            | ProLiant ML150 Gen9         | [50114897cc](https://linux-hardware.org/?probe=50114897cc) | Apr 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [066fb2b2b9](https://linux-hardware.org/?probe=066fb2b2b9) | Mar 30, 2022 |
| ASRock        | G41M-VS3                    | [34ccbe7db2](https://linux-hardware.org/?probe=34ccbe7db2) | Mar 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| ASUSTek       | PRIME H410M-E               | [1f267ffe6e](https://linux-hardware.org/?probe=1f267ffe6e) | Mar 11, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [d068227c07](https://linux-hardware.org/?probe=d068227c07) | Mar 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ac671d5e38](https://linux-hardware.org/?probe=ac671d5e38) | Mar 05, 2022 |
| Supermicro    | X7DA8                       | [fcf69abc8f](https://linux-hardware.org/?probe=fcf69abc8f) | Feb 25, 2022 |
| Gigabyte      | H410M H V3                  | [4c58660705](https://linux-hardware.org/?probe=4c58660705) | Feb 22, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [217c73c9a6](https://linux-hardware.org/?probe=217c73c9a6) | Feb 11, 2022 |
| ASRock        | Z77 Extreme4                | [95b7145bd2](https://linux-hardware.org/?probe=95b7145bd2) | Feb 06, 2022 |
| HP            | 1587h                       | [92625959b4](https://linux-hardware.org/?probe=92625959b4) | Feb 02, 2022 |
| ASUSTek       | H61M-K                      | [c7a35398d0](https://linux-hardware.org/?probe=c7a35398d0) | Feb 02, 2022 |
| ASUSTek       | PRIME H410M-E               | [876f78e96c](https://linux-hardware.org/?probe=876f78e96c) | Feb 01, 2022 |
| Intel         | DH61HO AAG62445-102         | [e0cbedce41](https://linux-hardware.org/?probe=e0cbedce41) | Jan 30, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [9b0853e1e9](https://linux-hardware.org/?probe=9b0853e1e9) | Jan 29, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [f967c472e5](https://linux-hardware.org/?probe=f967c472e5) | Jan 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [e92de9ab2e](https://linux-hardware.org/?probe=e92de9ab2e) | Jan 27, 2022 |
| Gigabyte      | H410M H                     | [1ca8a84549](https://linux-hardware.org/?probe=1ca8a84549) | Jan 25, 2022 |
| ASUSTek       | Maximus IX CODE             | [32c7db26bd](https://linux-hardware.org/?probe=32c7db26bd) | Jan 08, 2022 |
| ASRock        | H110M-HDV R3.0              | [90fe76c900](https://linux-hardware.org/?probe=90fe76c900) | Jan 03, 2022 |
| MSI           | H81M-E33                    | [a7e25b05e2](https://linux-hardware.org/?probe=a7e25b05e2) | Dec 27, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [258369e6dc](https://linux-hardware.org/?probe=258369e6dc) | Dec 24, 2021 |
| MSI           | B150A GAMING PRO            | [475ea42f9a](https://linux-hardware.org/?probe=475ea42f9a) | Dec 11, 2021 |
| HP            | 3047h                       | [b389ca7104](https://linux-hardware.org/?probe=b389ca7104) | Dec 08, 2021 |
| MSI           | 760GM-P23                   | [cbe2fcd79d](https://linux-hardware.org/?probe=cbe2fcd79d) | Nov 26, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [92d9d82670](https://linux-hardware.org/?probe=92d9d82670) | Nov 25, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [e3a6c887f6](https://linux-hardware.org/?probe=e3a6c887f6) | Nov 25, 2021 |
| ASRock        | G41M-VS3                    | [35277b1155](https://linux-hardware.org/?probe=35277b1155) | Nov 22, 2021 |
| ASUSTek       | PRIME X570-P                | [abd0cfab6b](https://linux-hardware.org/?probe=abd0cfab6b) | Nov 12, 2021 |
| ASUSTek       | PRIME X570-P                | [27aa14962f](https://linux-hardware.org/?probe=27aa14962f) | Nov 12, 2021 |
| ASUSTek       | PRIME B550M-K               | [de9d0e2b40](https://linux-hardware.org/?probe=de9d0e2b40) | Nov 08, 2021 |
| ASRock        | G41M-VS3                    | [bf54c2ee53](https://linux-hardware.org/?probe=bf54c2ee53) | Nov 04, 2021 |
| ASRock        | G41M-VS3                    | [2ee1cbdc82](https://linux-hardware.org/?probe=2ee1cbdc82) | Nov 03, 2021 |
| Gigabyte      | P67A-UD3-B3                 | [c196661531](https://linux-hardware.org/?probe=c196661531) | Nov 01, 2021 |
| MSI           | 2A9Ch                       | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Gigabyte      | H81M-H                      | [eb596b1774](https://linux-hardware.org/?probe=eb596b1774) | Oct 25, 2021 |
| ASUSTek       | PRIME H310-PLUS             | [cdd35d634d](https://linux-hardware.org/?probe=cdd35d634d) | Oct 24, 2021 |
| ASUSTek       | PRIME B550M-K               | [d9c192ea8c](https://linux-hardware.org/?probe=d9c192ea8c) | Oct 23, 2021 |
| ASRock        | G41M-VS3                    | [267bee9221](https://linux-hardware.org/?probe=267bee9221) | Oct 21, 2021 |
| HP            | 0B4Ch D                     | [d0b6443f5b](https://linux-hardware.org/?probe=d0b6443f5b) | Oct 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | [05c0fc8d29](https://linux-hardware.org/?probe=05c0fc8d29) | Oct 10, 2021 |
| ASUSTek       | PRIME B550M-K               | [d034cd0b4a](https://linux-hardware.org/?probe=d034cd0b4a) | Oct 07, 2021 |
| Foxconn       | H61MXE                      | [f684b8da61](https://linux-hardware.org/?probe=f684b8da61) | Oct 06, 2021 |
| ASRock        | G41M-VS3                    | [9c4f3417d4](https://linux-hardware.org/?probe=9c4f3417d4) | Oct 04, 2021 |
| ASRock        | G41M-VS3                    | [3e695d6744](https://linux-hardware.org/?probe=3e695d6744) | Oct 04, 2021 |
| Pegatron      | 2AE2                        | [0309cddc66](https://linux-hardware.org/?probe=0309cddc66) | Oct 02, 2021 |
| ASUSTek       | Z97-A                       | [6476a95a04](https://linux-hardware.org/?probe=6476a95a04) | Sep 27, 2021 |
| Biostar       | G41D3C                      | [16eb676e0c](https://linux-hardware.org/?probe=16eb676e0c) | Sep 25, 2021 |
| ASUSTek       | PRIME B550M-K               | [b30800b2f9](https://linux-hardware.org/?probe=b30800b2f9) | Sep 24, 2021 |
| Gigabyte      | H81M-H                      | [f214b7efbe](https://linux-hardware.org/?probe=f214b7efbe) | Sep 22, 2021 |
| ECS           | G31T-M7                     | [60bf966d06](https://linux-hardware.org/?probe=60bf966d06) | Sep 18, 2021 |
| ASRock        | G41M-VS3                    | [7922da571d](https://linux-hardware.org/?probe=7922da571d) | Sep 16, 2021 |
| ASRock        | G41M-VS3                    | [e7afe651d3](https://linux-hardware.org/?probe=e7afe651d3) | Sep 16, 2021 |
| HP            | 18E9                        | [7a7dd34d6d](https://linux-hardware.org/?probe=7a7dd34d6d) | Sep 13, 2021 |
| MSI           | B350M GAMING PRO            | [052bfbd512](https://linux-hardware.org/?probe=052bfbd512) | Sep 09, 2021 |
| MSI           | B350M GAMING PRO            | [a3b7774236](https://linux-hardware.org/?probe=a3b7774236) | Sep 09, 2021 |
| Intel         | D945GCLF2D AAE59323-101     | [d6808fecbf](https://linux-hardware.org/?probe=d6808fecbf) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| Gigabyte      | G31M-S2C                    | [15d48710db](https://linux-hardware.org/?probe=15d48710db) | Aug 24, 2021 |
| Pegatron      | 2AEE                        | [a3e6da7d21](https://linux-hardware.org/?probe=a3e6da7d21) | Aug 22, 2021 |
| Pegatron      | 2AEE                        | [0b0cf520ba](https://linux-hardware.org/?probe=0b0cf520ba) | Aug 22, 2021 |
| Gigabyte      | G31M-S2C                    | [a8d5b4ff89](https://linux-hardware.org/?probe=a8d5b4ff89) | Aug 22, 2021 |
| HP            | 18E9                        | [9ee974d2df](https://linux-hardware.org/?probe=9ee974d2df) | Aug 21, 2021 |
| HP            | 18E9                        | [838f27241e](https://linux-hardware.org/?probe=838f27241e) | Aug 21, 2021 |
| HP            | 304Ah                       | [4760a65d2f](https://linux-hardware.org/?probe=4760a65d2f) | Aug 20, 2021 |
| HP            | 304Ah                       | [67e7cc53c1](https://linux-hardware.org/?probe=67e7cc53c1) | Aug 18, 2021 |
| Intel         | DB75EN AAG39650-303         | [321af82bbf](https://linux-hardware.org/?probe=321af82bbf) | Aug 09, 2021 |
| Gigabyte      | B550M DS3H                  | [418d6ee68f](https://linux-hardware.org/?probe=418d6ee68f) | Jul 23, 2021 |
| Intel         | DH55HC AAE70933-505         | [e8b5870e50](https://linux-hardware.org/?probe=e8b5870e50) | Jul 19, 2021 |
| MSI           | MS-7309                     | [8b431e8b6f](https://linux-hardware.org/?probe=8b431e8b6f) | Jul 10, 2021 |
| ASRock        | Wolfdale1333-D667           | [7b71d5854c](https://linux-hardware.org/?probe=7b71d5854c) | Jul 01, 2021 |
| ASUSTek       | PRIME Z590-P                | [5530b28aa3](https://linux-hardware.org/?probe=5530b28aa3) | Jun 30, 2021 |
| ASUSTek       | PRIME Z590-P                | [582e4795cf](https://linux-hardware.org/?probe=582e4795cf) | Jun 30, 2021 |
| Intel         | H61                         | [50b0503c3c](https://linux-hardware.org/?probe=50b0503c3c) | Jun 07, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [2a6868991a](https://linux-hardware.org/?probe=2a6868991a) | May 27, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [33c1ecc56e](https://linux-hardware.org/?probe=33c1ecc56e) | May 19, 2021 |
| Gigabyte      | Z68X-UD7-B3                 | [22eae98fb5](https://linux-hardware.org/?probe=22eae98fb5) | May 13, 2021 |
| ECS           | H81H3-M4                    | [6889e28bfd](https://linux-hardware.org/?probe=6889e28bfd) | May 09, 2021 |
| ECS           | H81H3-M4                    | [0ef93e6291](https://linux-hardware.org/?probe=0ef93e6291) | May 09, 2021 |
| ASRock        | G965M-S                     | [dd116582af](https://linux-hardware.org/?probe=dd116582af) | May 03, 2021 |
| Intel         | H61                         | [cca60711c8](https://linux-hardware.org/?probe=cca60711c8) | May 01, 2021 |
| ASUSTek       | M4A77T/USB3                 | [ae115d5ca8](https://linux-hardware.org/?probe=ae115d5ca8) | Apr 29, 2021 |
| ASUSTek       | M4A77T/USB3                 | [34733fe16f](https://linux-hardware.org/?probe=34733fe16f) | Apr 29, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [037a465656](https://linux-hardware.org/?probe=037a465656) | Apr 28, 2021 |
| MSI           | 970A-G46                    | [f1035827e0](https://linux-hardware.org/?probe=f1035827e0) | Apr 26, 2021 |
| Unknown       | 4CoreDX90-VSTA              | [6410827a2f](https://linux-hardware.org/?probe=6410827a2f) | Apr 25, 2021 |
| Unknown       | 4CoreDX90-VSTA              | [a8c42b2d94](https://linux-hardware.org/?probe=a8c42b2d94) | Apr 25, 2021 |
| MSI           | 970A-G46                    | [9aa4264419](https://linux-hardware.org/?probe=9aa4264419) | Apr 22, 2021 |
| MSI           | K9A2 Platinum               | [fc4fd8ba0e](https://linux-hardware.org/?probe=fc4fd8ba0e) | Apr 19, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [7585c05b18](https://linux-hardware.org/?probe=7585c05b18) | Apr 19, 2021 |
| MSI           | K9A2 Platinum               | [ef223aa1d5](https://linux-hardware.org/?probe=ef223aa1d5) | Apr 16, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [48ab0d2acd](https://linux-hardware.org/?probe=48ab0d2acd) | Apr 14, 2021 |
| ASRock        | N68-VS3 UCC                 | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [cc61b2b6a7](https://linux-hardware.org/?probe=cc61b2b6a7) | Apr 04, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [c079cb8fac](https://linux-hardware.org/?probe=c079cb8fac) | Apr 01, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [26427e6d23](https://linux-hardware.org/?probe=26427e6d23) | Mar 29, 2021 |
| Dell          | 0G3HR7 A00                  | [f2760185e3](https://linux-hardware.org/?probe=f2760185e3) | Mar 26, 2021 |
| Intel         | DH55HC AAE70933-505         | [2ebfc03ce7](https://linux-hardware.org/?probe=2ebfc03ce7) | Mar 20, 2021 |
| Dell          | 0G3HR7 A00                  | [29c1565b42](https://linux-hardware.org/?probe=29c1565b42) | Mar 10, 2021 |
| Gigabyte      | H61M-S1                     | [98d2580d9e](https://linux-hardware.org/?probe=98d2580d9e) | Mar 06, 2021 |
| Gigabyte      | H61M-S1                     | [91cd908a95](https://linux-hardware.org/?probe=91cd908a95) | Mar 05, 2021 |
| HP            | 2B09                        | [44e3728303](https://linux-hardware.org/?probe=44e3728303) | Mar 05, 2021 |
| ASRock        | Wolfdale1333-D667           | [4cb354b544](https://linux-hardware.org/?probe=4cb354b544) | Mar 02, 2021 |
| Intel         | DP67DE AAG10217-205         | [4b376912e1](https://linux-hardware.org/?probe=4b376912e1) | Feb 23, 2021 |
| Intel         | DP67DE AAG10217-205         | [497e0558af](https://linux-hardware.org/?probe=497e0558af) | Feb 23, 2021 |
| ASRock        | Wolfdale1333-D667           | [ed29a42a57](https://linux-hardware.org/?probe=ed29a42a57) | Feb 23, 2021 |
| MSI           | A320M-A PRO MAX             | [fb6179a8ee](https://linux-hardware.org/?probe=fb6179a8ee) | Feb 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| Dell          | 0HN7XN A01                  | [909121ec95](https://linux-hardware.org/?probe=909121ec95) | Feb 03, 2021 |
| ASRock        | G41M-VS3                    | [b7460ea1e6](https://linux-hardware.org/?probe=b7460ea1e6) | Feb 02, 2021 |
| ECS           | H81H3-M4                    | [b452e9e060](https://linux-hardware.org/?probe=b452e9e060) | Jan 27, 2021 |
| ASUSTek       | PRIME H310M-E               | [cb63800c0d](https://linux-hardware.org/?probe=cb63800c0d) | Jan 24, 2021 |
| ASUSTek       | PRIME H310M-E               | [eb46844f3e](https://linux-hardware.org/?probe=eb46844f3e) | Jan 24, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [8dcbe2b63e](https://linux-hardware.org/?probe=8dcbe2b63e) | Jan 15, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [c969271698](https://linux-hardware.org/?probe=c969271698) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [9bd74368f0](https://linux-hardware.org/?probe=9bd74368f0) | Jan 15, 2021 |
| Intel         | H61                         | [d8489ff473](https://linux-hardware.org/?probe=d8489ff473) | Jan 11, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [81ab4a6cc7](https://linux-hardware.org/?probe=81ab4a6cc7) | Jan 11, 2021 |
| MSI           | B450M BAZOOKA V2            | [d68301770d](https://linux-hardware.org/?probe=d68301770d) | Jan 05, 2021 |
| Biostar       | H61MHV                      | [60f41299a7](https://linux-hardware.org/?probe=60f41299a7) | Jan 04, 2021 |
| Gigabyte      | 970A-UD3                    | [4de6e16ced](https://linux-hardware.org/?probe=4de6e16ced) | Dec 30, 2020 |
| Dell          | 0G3HR7 A00                  | [1c8f1911c4](https://linux-hardware.org/?probe=1c8f1911c4) | Dec 29, 2020 |
| PCSMART       | Unknown                     | [5c91c760a5](https://linux-hardware.org/?probe=5c91c760a5) | Dec 28, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [69e3d131e9](https://linux-hardware.org/?probe=69e3d131e9) | Dec 16, 2020 |
| ASRock        | G41M-VS3                    | [7633d83de8](https://linux-hardware.org/?probe=7633d83de8) | Dec 08, 2020 |
| ECS           | G31T-M7                     | [da86a0de6d](https://linux-hardware.org/?probe=da86a0de6d) | Dec 06, 2020 |
| ECS           | H81H3-M4                    | [324e08922c](https://linux-hardware.org/?probe=324e08922c) | Nov 23, 2020 |
| ASRock        | B450M Pro4                  | [63124c698a](https://linux-hardware.org/?probe=63124c698a) | Nov 22, 2020 |
| Foxconn       | 2ABF                        | [fa95d7cd22](https://linux-hardware.org/?probe=fa95d7cd22) | Nov 21, 2020 |
| ASRock        | AB350M-HDV                  | [4a503972bc](https://linux-hardware.org/?probe=4a503972bc) | Nov 18, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [a802e86d43](https://linux-hardware.org/?probe=a802e86d43) | Nov 07, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [a39151865e](https://linux-hardware.org/?probe=a39151865e) | Nov 06, 2020 |
| ASRock        | 960GM-VGS3 FX               | [5c51163253](https://linux-hardware.org/?probe=5c51163253) | Nov 05, 2020 |
| ASRock        | A320M-HDV                   | [c4f1aaa3bb](https://linux-hardware.org/?probe=c4f1aaa3bb) | Nov 02, 2020 |
| ASRock        | A320M-HDV                   | [a283f0ab00](https://linux-hardware.org/?probe=a283f0ab00) | Nov 01, 2020 |
| Foxconn       | 2ABF                        | [98e0846229](https://linux-hardware.org/?probe=98e0846229) | Oct 28, 2020 |
| ASRock        | G31M-GS                     | [ed0373efb3](https://linux-hardware.org/?probe=ed0373efb3) | Oct 22, 2020 |
| MSI           | H81M-E33                    | [dc82b20825](https://linux-hardware.org/?probe=dc82b20825) | Oct 20, 2020 |
| MSI           | H81M-E33                    | [21a8676b32](https://linux-hardware.org/?probe=21a8676b32) | Oct 20, 2020 |
| ASRock        | B450M-HDV R4.0              | [d1e0bb32d7](https://linux-hardware.org/?probe=d1e0bb32d7) | Oct 19, 2020 |
| Lenovo        | ThinkCentre A58 7515A18     | [6d228ca955](https://linux-hardware.org/?probe=6d228ca955) | Oct 05, 2020 |
| Gigabyte      | B450M DS3H-CF               | [309b4ecbe6](https://linux-hardware.org/?probe=309b4ecbe6) | Oct 02, 2020 |
| Gigabyte      | G31M-ES2C                   | [41c9698c88](https://linux-hardware.org/?probe=41c9698c88) | Oct 01, 2020 |
| Intel         | 945GCT-M                    | [c0ad55286f](https://linux-hardware.org/?probe=c0ad55286f) | Sep 26, 2020 |
| Dell          | 0MM599                      | [bf8a1f8434](https://linux-hardware.org/?probe=bf8a1f8434) | Sep 22, 2020 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [b178b5269a](https://linux-hardware.org/?probe=b178b5269a) | Sep 18, 2020 |
| ASUSTek       | M4A87TD EVO                 | [4b2b8ed64f](https://linux-hardware.org/?probe=4b2b8ed64f) | Sep 06, 2020 |
| ASRock        | X570 Steel Legend           | [fcc32617ab](https://linux-hardware.org/?probe=fcc32617ab) | Sep 06, 2020 |
| Gigabyte      | AM1M-S2H                    | [8f57e5d722](https://linux-hardware.org/?probe=8f57e5d722) | Sep 05, 2020 |
| PCSMART       | 6.0                         | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| ASRock        | H110M-HDV R3.0              | [b641263269](https://linux-hardware.org/?probe=b641263269) | Sep 04, 2020 |
| ASUSTek       | M4A87TD/USB3                | [3c21577bc4](https://linux-hardware.org/?probe=3c21577bc4) | Sep 03, 2020 |
| ASUSTek       | PRIME A320M-K               | [131299dd43](https://linux-hardware.org/?probe=131299dd43) | Sep 02, 2020 |
| ASUSTek       | PRIME A320M-K               | [c7c173a4d6](https://linux-hardware.org/?probe=c7c173a4d6) | Aug 28, 2020 |
| ASUSTek       | PRIME H310M-E               | [07445986db](https://linux-hardware.org/?probe=07445986db) | Aug 24, 2020 |
| Dell          | 0D6H9T A01                  | [9c13b5e775](https://linux-hardware.org/?probe=9c13b5e775) | Aug 20, 2020 |
| Dell          | 0D6H9T A01                  | [40b95dab91](https://linux-hardware.org/?probe=40b95dab91) | Aug 20, 2020 |
| ECS           | H81H3-M4                    | [2a6af22359](https://linux-hardware.org/?probe=2a6af22359) | Aug 18, 2020 |
| Foxconn       | 2ABF                        | [24c499fe18](https://linux-hardware.org/?probe=24c499fe18) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | [1fbfbf3d96](https://linux-hardware.org/?probe=1fbfbf3d96) | Aug 17, 2020 |
| ECS           | H81H3-M4                    | [6edc3d456f](https://linux-hardware.org/?probe=6edc3d456f) | Aug 16, 2020 |
| MSI           | A68HM-E33                   | [819dd19a0e](https://linux-hardware.org/?probe=819dd19a0e) | Aug 14, 2020 |
| ASUSTek       | H110-PLUS                   | [28a6907d78](https://linux-hardware.org/?probe=28a6907d78) | Aug 14, 2020 |
| ASUSTek       | PRIME H310M-E               | [a10db0a0f1](https://linux-hardware.org/?probe=a10db0a0f1) | Aug 13, 2020 |
| ASUSTek       | M4A87TD/USB3                | [76ee87fa06](https://linux-hardware.org/?probe=76ee87fa06) | Aug 07, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | [c27cdabb7b](https://linux-hardware.org/?probe=c27cdabb7b) | Aug 02, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | [67b506f12f](https://linux-hardware.org/?probe=67b506f12f) | Jul 16, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | [65d309fa0f](https://linux-hardware.org/?probe=65d309fa0f) | Jul 16, 2020 |
| Gigabyte      | X570 UD                     | [dffcf158e7](https://linux-hardware.org/?probe=dffcf158e7) | Jul 12, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [f24093f04f](https://linux-hardware.org/?probe=f24093f04f) | Jul 09, 2020 |
| HP            | ProLiant ML310e Gen8 v2     | [b97d60900c](https://linux-hardware.org/?probe=b97d60900c) | Jul 07, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [a57a22212c](https://linux-hardware.org/?probe=a57a22212c) | Jul 06, 2020 |
| ECS           | G31T-M7                     | [95cb3298ec](https://linux-hardware.org/?probe=95cb3298ec) | Jul 05, 2020 |
| ECS           | G31T-M7                     | [56b5cd6eac](https://linux-hardware.org/?probe=56b5cd6eac) | Jul 05, 2020 |
| Pegatron      | 2A73h                       | [58e16275bc](https://linux-hardware.org/?probe=58e16275bc) | Jul 04, 2020 |
| ECS           | H81H3-M4                    | [ed75f47aa0](https://linux-hardware.org/?probe=ed75f47aa0) | Jun 30, 2020 |
| Hardkernel    | ODROID-H2                   | [3cda40d161](https://linux-hardware.org/?probe=3cda40d161) | Jun 28, 2020 |
| ASRock        | N68C-S UCC                  | [19c8257ed1](https://linux-hardware.org/?probe=19c8257ed1) | Jun 26, 2020 |
| ASRock        | N68C-S UCC                  | [a56bd9dd64](https://linux-hardware.org/?probe=a56bd9dd64) | Jun 26, 2020 |
| ECS           | H81H3-M4                    | [9dfcf2f0cb](https://linux-hardware.org/?probe=9dfcf2f0cb) | Jun 23, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [f90ccba28d](https://linux-hardware.org/?probe=f90ccba28d) | Jun 23, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [c8a9bbbaa0](https://linux-hardware.org/?probe=c8a9bbbaa0) | Jun 20, 2020 |
| Biostar       | N68S3+                      | [3d289fd6d2](https://linux-hardware.org/?probe=3d289fd6d2) | Jun 15, 2020 |
| Dell          | 054KM3 A00                  | [3e9f988a30](https://linux-hardware.org/?probe=3e9f988a30) | Jun 11, 2020 |
| ASRock        | G41M-VS3                    | [8143bab4c5](https://linux-hardware.org/?probe=8143bab4c5) | May 30, 2020 |
| MSI           | A55M-P35                    | [1816e90106](https://linux-hardware.org/?probe=1816e90106) | May 22, 2020 |
| ASRock        | G41M-VS3                    | [a0a6bd1e26](https://linux-hardware.org/?probe=a0a6bd1e26) | May 22, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [dc1d621a65](https://linux-hardware.org/?probe=dc1d621a65) | May 15, 2020 |
| MSI           | H110M PRO-VH PLUS           | [c54d7ef6ee](https://linux-hardware.org/?probe=c54d7ef6ee) | May 10, 2020 |
| MSI           | H110M PRO-VH PLUS           | [cbf18515b3](https://linux-hardware.org/?probe=cbf18515b3) | May 10, 2020 |
| ASRock        | G965M-S                     | [9d4cff9871](https://linux-hardware.org/?probe=9d4cff9871) | May 05, 2020 |
| PCChips       | P17G ECS                    | [8220dc9d9a](https://linux-hardware.org/?probe=8220dc9d9a) | May 04, 2020 |
| ECS           | H81H3-M4                    | [c8dd8d2166](https://linux-hardware.org/?probe=c8dd8d2166) | May 02, 2020 |
| Gigabyte      | H170-Gaming 3 DDR3          | [b6540749a2](https://linux-hardware.org/?probe=b6540749a2) | May 01, 2020 |
| MSI           | 970A-G43 PLUS               | [50a3cd26c8](https://linux-hardware.org/?probe=50a3cd26c8) | Apr 25, 2020 |
| Gigabyte      | G31M-S2C                    | [2392a43f27](https://linux-hardware.org/?probe=2392a43f27) | Apr 14, 2020 |
| Gigabyte      | G31M-S2C                    | [50809e26ed](https://linux-hardware.org/?probe=50809e26ed) | Apr 14, 2020 |
| MSI           | MS-7309                     | [598ba6983d](https://linux-hardware.org/?probe=598ba6983d) | Apr 14, 2020 |
| Unknown       | Unknown                     | [6e2105feb5](https://linux-hardware.org/?probe=6e2105feb5) | Apr 03, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [b3c0d80908](https://linux-hardware.org/?probe=b3c0d80908) | Mar 26, 2020 |
| HP            | 3048h                       | [6b07a41174](https://linux-hardware.org/?probe=6b07a41174) | Mar 22, 2020 |
| ASRock        | H61M-VG4                    | [9a17b3a770](https://linux-hardware.org/?probe=9a17b3a770) | Mar 21, 2020 |
| MSI           | K9N6PGM2-V2                 | [68013dac14](https://linux-hardware.org/?probe=68013dac14) | Mar 16, 2020 |
| MSI           | K9N6PGM2-V2                 | [df4df13e54](https://linux-hardware.org/?probe=df4df13e54) | Mar 16, 2020 |
| MSI           | K9N6PGM2-V2                 | [12b38c9ebd](https://linux-hardware.org/?probe=12b38c9ebd) | Mar 16, 2020 |
| Intel         | DH61WW AAG23116-302         | [239a155579](https://linux-hardware.org/?probe=239a155579) | Feb 22, 2020 |
| ASUSTek       | PRIME H310-PLUS             | [c59fbe99a2](https://linux-hardware.org/?probe=c59fbe99a2) | Feb 02, 2020 |
| ASUSTek       | PRIME X570-PRO              | [8f38f0a1e3](https://linux-hardware.org/?probe=8f38f0a1e3) | Jan 20, 2020 |
| Dell          | 0P301D A00                  | [298fac1e53](https://linux-hardware.org/?probe=298fac1e53) | Jan 03, 2020 |
| ASRock        | G41M-VS3                    | [c4c975b9f9](https://linux-hardware.org/?probe=c4c975b9f9) | Dec 29, 2019 |
| Unknown       | GSUO H61V10C                | [96d964a1d9](https://linux-hardware.org/?probe=96d964a1d9) | Dec 23, 2019 |
| Pegatron      | 2AAE                        | [04a6d42a9c](https://linux-hardware.org/?probe=04a6d42a9c) | Dec 16, 2019 |
| Pegatron      | 2AAE                        | [e142be5f58](https://linux-hardware.org/?probe=e142be5f58) | Dec 16, 2019 |
| ASRock        | H55M                        | [a199be0d97](https://linux-hardware.org/?probe=a199be0d97) | Nov 12, 2019 |
| ASRock        | H55M                        | [7202462c60](https://linux-hardware.org/?probe=7202462c60) | Nov 12, 2019 |
| MSI           | MS-7309                     | [2e6203af14](https://linux-hardware.org/?probe=2e6203af14) | Oct 09, 2019 |
| ASUSTek       | H110M-R                     | [d98faab3bc](https://linux-hardware.org/?probe=d98faab3bc) | Oct 09, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3181aa4496](https://linux-hardware.org/?probe=3181aa4496) | Sep 02, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f063afeba7](https://linux-hardware.org/?probe=f063afeba7) | Aug 28, 2019 |
| HP            | ProLiant ML115 G1           | [8f0d70a883](https://linux-hardware.org/?probe=8f0d70a883) | Jul 29, 2019 |
| Dell          | OptiPlex GX260              | [6c061a7a15](https://linux-hardware.org/?probe=6c061a7a15) | Jul 23, 2019 |
| ASUSTek       | H81M-K                      | [b124f401f6](https://linux-hardware.org/?probe=b124f401f6) | Jul 17, 2019 |
| Intel         | DH55HC AAE70933-501         | [3462cd0ccd](https://linux-hardware.org/?probe=3462cd0ccd) | Jul 07, 2019 |
| MSI           | MS-7191                     | [d753273d7b](https://linux-hardware.org/?probe=d753273d7b) | Jul 03, 2019 |
| Dell          | 0RY206                      | [aed7ab6e58](https://linux-hardware.org/?probe=aed7ab6e58) | Jun 28, 2019 |
| Gigabyte      | H81M-H                      | [bebf195e43](https://linux-hardware.org/?probe=bebf195e43) | Jun 18, 2019 |
| ASRock        | K8Upgrade-VM800             | [83cccbaf1a](https://linux-hardware.org/?probe=83cccbaf1a) | Jun 03, 2019 |
| ASRock        | G965M-S                     | [30b8a56200](https://linux-hardware.org/?probe=30b8a56200) | May 30, 2019 |
| Dell          | 0TT708 A01                  | [b732db0128](https://linux-hardware.org/?probe=b732db0128) | May 24, 2019 |
| Dell          | 0TT708 A01                  | [fbe3c00bb0](https://linux-hardware.org/?probe=fbe3c00bb0) | May 24, 2019 |
| Unknown       | 775i65G                     | [0b6fd94458](https://linux-hardware.org/?probe=0b6fd94458) | May 19, 2019 |
| Unknown       | 775i65G                     | [2b8a659310](https://linux-hardware.org/?probe=2b8a659310) | May 18, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [29cf71291b](https://linux-hardware.org/?probe=29cf71291b) | Apr 21, 2019 |
| Biostar       | A55MLV                      | [38fd682351](https://linux-hardware.org/?probe=38fd682351) | Apr 19, 2019 |
| HP            | 0A60h                       | [c59eb70baf](https://linux-hardware.org/?probe=c59eb70baf) | Apr 11, 2019 |
| HP            | 0A60h                       | [bd74dccea9](https://linux-hardware.org/?probe=bd74dccea9) | Apr 10, 2019 |
| ASUSTek       | H81M-K                      | [c5178f5550](https://linux-hardware.org/?probe=c5178f5550) | Apr 04, 2019 |
| ASUSTek       | H81M-K                      | [ef3d04377e](https://linux-hardware.org/?probe=ef3d04377e) | Apr 01, 2019 |
| ASUSTek       | H81M-K                      | [be751979a7](https://linux-hardware.org/?probe=be751979a7) | Apr 01, 2019 |
| ASUSTek       | H81M-K                      | [b9c1d97ec1](https://linux-hardware.org/?probe=b9c1d97ec1) | Apr 01, 2019 |
| Biostar       | A55MLV                      | [138e3baa2d](https://linux-hardware.org/?probe=138e3baa2d) | Mar 29, 2019 |
| ASUSTek       | H81M-K                      | [d3f5c5ac28](https://linux-hardware.org/?probe=d3f5c5ac28) | Mar 29, 2019 |
| Intel         | DH61CR AAG14064-207         | [2c44dea441](https://linux-hardware.org/?probe=2c44dea441) | Mar 17, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [8d9fa49be1](https://linux-hardware.org/?probe=8d9fa49be1) | Feb 09, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [5dcbf55671](https://linux-hardware.org/?probe=5dcbf55671) | Feb 09, 2019 |
| ASRock        | Wolfdale1333-D667           | [f67c3262d4](https://linux-hardware.org/?probe=f67c3262d4) | Dec 10, 2018 |
| ASRock        | Wolfdale1333-D667           | [06bcad286b](https://linux-hardware.org/?probe=06bcad286b) | Nov 18, 2018 |
| Pegatron      | 2A73h                       | [9ab888ea4f](https://linux-hardware.org/?probe=9ab888ea4f) | Jun 19, 2018 |
| HP            | 2ADE                        | [af28bb9a2f](https://linux-hardware.org/?probe=af28bb9a2f) | Dec 01, 2017 |
| HP            | 2ADE                        | [a2ab5f4392](https://linux-hardware.org/?probe=a2ab5f4392) | Dec 01, 2017 |
| HP            | 0A54h                       | [1f795e5896](https://linux-hardware.org/?probe=1f795e5896) | Jun 29, 2017 |
| HP            | 0A54h                       | [ef67a7d651](https://linux-hardware.org/?probe=ef67a7d651) | Feb 05, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Colombia/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 34       | 8.33%   |
| Ubuntu 18.04       | 31       | 7.6%    |
| Ubuntu 22.04       | 26       | 6.37%   |
| OpenMandriva 4.3   | 14       | 3.43%   |
| OpenMandriva 23.08 | 11       | 2.7%    |
| Fedora 38          | 11       | 2.7%    |
| Arch Rolling       | 11       | 2.7%    |
| Linux Mint 20.3    | 10       | 2.45%   |
| Fedora 40          | 10       | 2.45%   |
| Linux Mint 20.2    | 8        | 1.96%   |
| ArcoLinux Rolling  | 8        | 1.96%   |
| OpenMandriva 4.2   | 7        | 1.72%   |
| KDE neon 20.04     | 7        | 1.72%   |
| Zorin 17           | 6        | 1.47%   |
| Zorin 15           | 6        | 1.47%   |
| Ubuntu 24.04       | 6        | 1.47%   |
| Manjaro            | 6        | 1.47%   |
| Fedora 37          | 6        | 1.47%   |
| Linux Mint 21.2    | 5        | 1.23%   |
| Linux Mint 19.3    | 5        | 1.23%   |
| KDE neon 22.04     | 5        | 1.23%   |
| Fedora 39          | 5        | 1.23%   |
| Fedora 35          | 5        | 1.23%   |
| Debian 12          | 5        | 1.23%   |
| Debian 11          | 5        | 1.23%   |
| Zorin 16           | 4        | 0.98%   |
| Xubuntu 22.04      | 4        | 0.98%   |
| Xubuntu 20.04      | 4        | 0.98%   |
| OpenMandriva 23.03 | 4        | 0.98%   |
| Fedora 41          | 4        | 0.98%   |
| Fedora 36          | 4        | 0.98%   |
| Zorin 12           | 3        | 0.74%   |
| Ubuntu Unity 16.04 | 3        | 0.74%   |
| Ubuntu 19.04       | 3        | 0.74%   |
| ROSA R11           | 3        | 0.74%   |
| ROSA 12.2          | 3        | 0.74%   |
| OpenMandriva 23.01 | 3        | 0.74%   |
| Nobara 39          | 3        | 0.74%   |
| Nobara 36          | 3        | 0.74%   |
| Linux Mint 21.1    | 3        | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 102      | 26.7%   |
| Fedora        | 45       | 11.78%  |
| OpenMandriva  | 43       | 11.26%  |
| Linux Mint    | 38       | 9.95%   |
| Zorin         | 19       | 4.97%   |
| Arch          | 14       | 3.66%   |
| KDE neon      | 12       | 3.14%   |
| Debian        | 12       | 3.14%   |
| ROSA          | 10       | 2.62%   |
| Xubuntu       | 9        | 2.36%   |
| Manjaro       | 9        | 2.36%   |
| ArcoLinux     | 8        | 2.09%   |
| Nobara        | 7        | 1.83%   |
| Kubuntu       | 7        | 1.83%   |
| Ubuntu Unity  | 4        | 1.05%   |
| Pop!_OS       | 4        | 1.05%   |
| openSUSE      | 4        | 1.05%   |
| Elementary    | 4        | 1.05%   |
| Lubuntu       | 3        | 0.79%   |
| Endless       | 3        | 0.79%   |
| Deepin        | 3        | 0.79%   |
| Ubuntu Budgie | 2        | 0.52%   |
| Kali          | 2        | 0.52%   |
| BlackPanther  | 2        | 0.52%   |
| Xero          | 1        | 0.26%   |
| Rocky Linux   | 1        | 0.26%   |
| Reborn OS     | 1        | 0.26%   |
| Peppermint    | 1        | 0.26%   |
| Parrot        | 1        | 0.26%   |
| MX            | 1        | 0.26%   |
| Mageia        | 1        | 0.26%   |
| LMDE          | 1        | 0.26%   |
| LinuxFX       | 1        | 0.26%   |
| Linux Lite    | 1        | 0.26%   |
| Gentoo        | 1        | 0.26%   |
| Garuda Linux  | 1        | 0.26%   |
| EndeavourOS   | 1        | 0.26%   |
| CentOS        | 1        | 0.26%   |
| BigLinux      | 1        | 0.26%   |
| Bazzite       | 1        | 0.26%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003            | 13       | 2.87%   |
| 6.4.11-desktop-1omv2390            | 10       | 2.21%   |
| 5.4.0-42-generic                   | 7        | 1.55%   |
| 5.10.14-desktop-1omv4002           | 7        | 1.55%   |
| 5.19.0-35-generic                  | 5        | 1.1%    |
| 5.15.0-56-generic                  | 5        | 1.1%    |
| 6.2.6-desktop-1omv2390             | 4        | 0.88%   |
| 5.4.0-72-generic                   | 4        | 0.88%   |
| 5.4.0-58-generic                   | 4        | 0.88%   |
| 5.0.0-32-generic                   | 4        | 0.88%   |
| 6.8.11-300.fc40.x86_64             | 3        | 0.66%   |
| 6.8.0-45-generic                   | 3        | 0.66%   |
| 6.8.0-41-generic                   | 3        | 0.66%   |
| 6.8.0-40-generic                   | 3        | 0.66%   |
| 6.6.9-200.fc39.x86_64              | 3        | 0.66%   |
| 6.5.0-35-generic                   | 3        | 0.66%   |
| 6.5.0-14-generic                   | 3        | 0.66%   |
| 6.2.0-35-generic                   | 3        | 0.66%   |
| 6.1.1-desktop-1omv2290             | 3        | 0.66%   |
| 5.4.0-48-generic                   | 3        | 0.66%   |
| 5.4.0-45-generic                   | 3        | 0.66%   |
| 5.4.0-122-generic                  | 3        | 0.66%   |
| 5.19.0-41-generic                  | 3        | 0.66%   |
| 5.15.0-67-generic                  | 3        | 0.66%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 3        | 0.66%   |
| 4.18.0-16-generic                  | 3        | 0.66%   |
| 4.15.0-54-generic                  | 3        | 0.66%   |
| 6.8.7-201.fsync.fc39.x86_64        | 2        | 0.44%   |
| 6.8.0-49-generic                   | 2        | 0.44%   |
| 6.8.0-48-generic                   | 2        | 0.44%   |
| 6.8.0-35-generic                   | 2        | 0.44%   |
| 6.6.2-desktop-1omv2390             | 2        | 0.44%   |
| 6.5.0-10-generic                   | 2        | 0.44%   |
| 6.4.13-200.fc38.x86_64             | 2        | 0.44%   |
| 6.4.10-200.fc38.x86_64             | 2        | 0.44%   |
| 6.3.8-200.fc38.x86_64              | 2        | 0.44%   |
| 6.2.0-33-generic                   | 2        | 0.44%   |
| 6.11.4-301.fc41.x86_64             | 2        | 0.44%   |
| 6.11.10-300.fc41.x86_64            | 2        | 0.44%   |
| 6.1.18-200.fc37.x86_64             | 2        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 65       | 15.15%  |
| 5.15.0  | 35       | 8.16%   |
| 4.15.0  | 18       | 4.2%    |
| 6.8.0   | 17       | 3.96%   |
| 6.5.0   | 14       | 3.26%   |
| 5.16.7  | 13       | 3.03%   |
| 5.19.0  | 12       | 2.8%    |
| 5.0.0   | 11       | 2.56%   |
| 6.4.11  | 10       | 2.33%   |
| 5.3.0   | 10       | 2.33%   |
| 5.13.0  | 10       | 2.33%   |
| 6.2.0   | 9        | 2.1%    |
| 5.8.0   | 8        | 1.86%   |
| 4.18.0  | 8        | 1.86%   |
| 6.1.0   | 7        | 1.63%   |
| 5.10.14 | 7        | 1.63%   |
| 5.11.0  | 6        | 1.4%    |
| 6.8.7   | 4        | 0.93%   |
| 6.2.6   | 4        | 0.93%   |
| 6.1.1   | 4        | 0.93%   |
| 5.10.0  | 4        | 0.93%   |
| 6.8.11  | 3        | 0.7%    |
| 6.6.9   | 3        | 0.7%    |
| 6.6.2   | 3        | 0.7%    |
| 5.8.5   | 3        | 0.7%    |
| 5.8.18  | 3        | 0.7%    |
| 5.12.4  | 3        | 0.7%    |
| 5.10.74 | 3        | 0.7%    |
| 6.9.12  | 2        | 0.47%   |
| 6.6.7   | 2        | 0.47%   |
| 6.5.7   | 2        | 0.47%   |
| 6.4.13  | 2        | 0.47%   |
| 6.4.10  | 2        | 0.47%   |
| 6.3.8   | 2        | 0.47%   |
| 6.2.15  | 2        | 0.47%   |
| 6.11.4  | 2        | 0.47%   |
| 6.11.10 | 2        | 0.47%   |
| 6.10.8  | 2        | 0.47%   |
| 6.10.4  | 2        | 0.47%   |
| 6.1.18  | 2        | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 68       | 16.27%  |
| 5.15    | 41       | 9.81%   |
| 6.8     | 26       | 6.22%   |
| 6.1     | 22       | 5.26%   |
| 5.10    | 20       | 4.78%   |
| 6.5     | 18       | 4.31%   |
| 4.15    | 18       | 4.31%   |
| 5.16    | 17       | 4.07%   |
| 6.4     | 16       | 3.83%   |
| 6.2     | 16       | 3.83%   |
| 5.8     | 15       | 3.59%   |
| 6.6     | 12       | 2.87%   |
| 5.19    | 12       | 2.87%   |
| 5.13    | 12       | 2.87%   |
| 5.3     | 11       | 2.63%   |
| 5.0     | 11       | 2.63%   |
| 4.18    | 10       | 2.39%   |
| 6.3     | 7        | 1.67%   |
| 5.14    | 7        | 1.67%   |
| 5.11    | 7        | 1.67%   |
| 6.10    | 6        | 1.44%   |
| 6.9     | 5        | 1.2%    |
| 6.7     | 5        | 1.2%    |
| 6.0     | 5        | 1.2%    |
| 5.12    | 5        | 1.2%    |
| 6.11    | 4        | 0.96%   |
| 5.17    | 4        | 0.96%   |
| 4.9     | 4        | 0.96%   |
| 5.9     | 2        | 0.48%   |
| 5.6     | 2        | 0.48%   |
| 5.18    | 2        | 0.48%   |
| 4.19    | 2        | 0.48%   |
| 6.12    | 1        | 0.24%   |
| 5.7     | 1        | 0.24%   |
| 5.2     | 1        | 0.24%   |
| 4.12    | 1        | 0.24%   |
| 4.10    | 1        | 0.24%   |
| 4.1     | 1        | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 364      | 98.11%  |
| i686   | 7        | 1.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 159      | 40.98%  |
| KDE5            | 79       | 20.36%  |
| X-Cinnamon      | 29       | 7.47%   |
| Unknown         | 29       | 7.47%   |
| XFCE            | 27       | 6.96%   |
| KDE             | 10       | 2.58%   |
| KDE6            | 9        | 2.32%   |
| MATE            | 7        | 1.8%    |
| KDE4            | 5        | 1.29%   |
| Unity           | 4        | 1.03%   |
| Pantheon        | 4        | 1.03%   |
| LXQt            | 4        | 1.03%   |
| Cinnamon        | 4        | 1.03%   |
| i3              | 3        | 0.77%   |
| Deepin          | 3        | 0.77%   |
| LXDE            | 2        | 0.52%   |
| GNOME Classic   | 2        | 0.52%   |
| Budgie          | 2        | 0.52%   |
| ubuntu=GNOME    | 1        | 0.26%   |
| GNOME Flashback | 1        | 0.26%   |
| Enlightenment   | 1        | 0.26%   |
| Endless:GNOME   | 1        | 0.26%   |
| DDE             | 1        | 0.26%   |
| awesome         | 1        | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 269      | 69.33%  |
| Wayland | 98       | 25.26%  |
| Unknown | 15       | 3.87%   |
| Tty     | 6        | 1.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 187      | 48.7%   |
| SDDM    | 70       | 18.23%  |
| GDM3    | 42       | 10.94%  |
| GDM     | 38       | 9.9%    |
| LightDM | 36       | 9.38%   |
| TDM     | 5        | 1.3%    |
| KDM     | 4        | 1.04%   |
| SLiM    | 1        | 0.26%   |
| LXDM    | 1        | 0.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_CO   | 195      | 50.91%  |
| en_US   | 105      | 27.42%  |
| Unknown | 35       | 9.14%   |
| es_ES   | 28       | 7.31%   |
| es_MX   | 6        | 1.57%   |
| C       | 5        | 1.31%   |
| pt_BR   | 3        | 0.78%   |
| en_GB   | 2        | 0.52%   |
| es_VE   | 1        | 0.26%   |
| es_DO   | 1        | 0.26%   |
| es_AR   | 1        | 0.26%   |
| C.UTF8  | 1        | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 231      | 61.11%  |
| EFI  | 147      | 38.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 246      | 64.57%  |
| Btrfs   | 62       | 16.27%  |
| Overlay | 40       | 10.5%   |
| Tmpfs   | 20       | 5.25%   |
| Xfs     | 6        | 1.57%   |
| Unknown | 5        | 1.31%   |
| Zfs     | 1        | 0.26%   |
| Ext2    | 1        | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 184      | 48.81%  |
| GPT     | 132      | 35.01%  |
| MBR     | 61       | 16.18%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 316      | 82.08%  |
| Yes       | 69       | 17.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 233      | 61.32%  |
| Yes       | 147      | 38.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 81       | 21.83%  |
| Gigabyte Technology | 66       | 17.79%  |
| MSI                 | 46       | 12.4%   |
| Hewlett-Packard     | 38       | 10.24%  |
| ASRock              | 37       | 9.97%   |
| Intel               | 23       | 6.2%    |
| Dell                | 20       | 5.39%   |
| Lenovo              | 14       | 3.77%   |
| Biostar             | 8        | 2.16%   |
| ECS                 | 7        | 1.89%   |
| Pegatron            | 5        | 1.35%   |
| Foxconn             | 5        | 1.35%   |
| Unknown             | 5        | 1.35%   |
| PCSMART             | 3        | 0.81%   |
| Acer                | 3        | 0.81%   |
| Supermicro          | 1        | 0.27%   |
| Quanta              | 1        | 0.27%   |
| PCChips             | 1        | 0.27%   |
| MACHINIST           | 1        | 0.27%   |
| JGINYUE             | 1        | 0.27%   |
| Intel X79           | 1        | 0.27%   |
| Hardkernel          | 1        | 0.27%   |
| Compumax Computer   | 1        | 0.27%   |
| BESSTAR Tech        | 1        | 0.27%   |
| Apple               | 1        | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte B450M DS3H                | 8        | 2.16%   |
| Unknown                            | 7        | 1.89%   |
| MSI MS-7817                        | 6        | 1.62%   |
| ASUS All Series                    | 5        | 1.35%   |
| MSI MS-7309                        | 4        | 1.08%   |
| Gigabyte H81M-H                    | 4        | 1.08%   |
| ASUS PRIME B450M-A II              | 4        | 1.08%   |
| ASUS PRIME A320M-K                 | 4        | 1.08%   |
| ASRock Wolfdale1333-D667           | 4        | 1.08%   |
| MSI MS-7597                        | 3        | 0.81%   |
| Intel H61                          | 3        | 0.81%   |
| HP ProDesk 400 G1 SFF              | 3        | 0.81%   |
| Gigabyte H61M-S1                   | 3        | 0.81%   |
| Gigabyte H61M-HD2                  | 3        | 0.81%   |
| Gigabyte GA-78LMT-USB3             | 3        | 0.81%   |
| Gigabyte G31M-ES2C                 | 3        | 0.81%   |
| Gigabyte A520M DS3H                | 3        | 0.81%   |
| ECS G31T-M7                        | 3        | 0.81%   |
| ASUS ROG STRIX B550-F GAMING       | 3        | 0.81%   |
| ASUS M5A78L-M/USB3                 | 3        | 0.81%   |
| ASRock G965M-S                     | 3        | 0.81%   |
| ASRock G41M-VS3                    | 3        | 0.81%   |
| MSI MS-7C96                        | 2        | 0.54%   |
| MSI MS-7C37                        | 2        | 0.54%   |
| MSI MS-7641                        | 2        | 0.54%   |
| Intel DH61CR AAG14064-207          | 2        | 0.54%   |
| HP Compaq Pro 4300 SFF PC          | 2        | 0.54%   |
| HP Compaq dc7700 Small Form Factor | 2        | 0.54%   |
| HP Compaq 8200 Elite SFF PC        | 2        | 0.54%   |
| Gigabyte X399 AORUS PRO            | 2        | 0.54%   |
| Gigabyte B550 AORUS PRO AC         | 2        | 0.54%   |
| Gigabyte A320M-S2H                 | 2        | 0.54%   |
| ECS H81H3-M4                       | 2        | 0.54%   |
| Dell Vostro 430                    | 2        | 0.54%   |
| Biostar H61MHV                     | 2        | 0.54%   |
| ASUS TUF Gaming X570-PLUS          | 2        | 0.54%   |
| ASUS TUF B450M-PLUS GAMING         | 2        | 0.54%   |
| ASUS SABERTOOTH 990FX R2.0         | 2        | 0.54%   |
| ASUS ROG STRIX B450-F GAMING       | 2        | 0.54%   |
| ASUS PRIME X570-P                  | 2        | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| ASUS PRIME               | 31       | 8.36%   |
| HP Compaq                | 18       | 4.85%   |
| Lenovo ThinkCentre       | 11       | 2.96%   |
| Dell OptiPlex            | 11       | 2.96%   |
| ASUS TUF                 | 11       | 2.96%   |
| Gigabyte B450M           | 9        | 2.43%   |
| ASUS ROG                 | 9        | 2.43%   |
| HP ProDesk               | 7        | 1.89%   |
| Unknown                  | 7        | 1.89%   |
| MSI MS-7817              | 6        | 1.62%   |
| ASUS All                 | 5        | 1.35%   |
| MSI MS-7309              | 4        | 1.08%   |
| HP ProLiant              | 4        | 1.08%   |
| Gigabyte H81M-H          | 4        | 1.08%   |
| Gigabyte B550            | 4        | 1.08%   |
| ASRock Wolfdale1333-D667 | 4        | 1.08%   |
| MSI MS-7597              | 3        | 0.81%   |
| Intel H61                | 3        | 0.81%   |
| Intel DG41RQ             | 3        | 0.81%   |
| Gigabyte X570            | 3        | 0.81%   |
| Gigabyte X399            | 3        | 0.81%   |
| Gigabyte H61M-S1         | 3        | 0.81%   |
| Gigabyte H61M-HD2        | 3        | 0.81%   |
| Gigabyte GA-78LMT-USB3   | 3        | 0.81%   |
| Gigabyte G31M-ES2C       | 3        | 0.81%   |
| Gigabyte A520M           | 3        | 0.81%   |
| ECS G31T-M7              | 3        | 0.81%   |
| Dell Vostro              | 3        | 0.81%   |
| ASUS M5A78L-M            | 3        | 0.81%   |
| ASRock G965M-S           | 3        | 0.81%   |
| ASRock G41M-VS3          | 3        | 0.81%   |
| MSI MS-7C96              | 2        | 0.54%   |
| MSI MS-7C37              | 2        | 0.54%   |
| MSI MS-7641              | 2        | 0.54%   |
| Intel DH61CR             | 2        | 0.54%   |
| Intel DH55HC             | 2        | 0.54%   |
| HP EliteDesk             | 2        | 0.54%   |
| Gigabyte X670E           | 2        | 0.54%   |
| Gigabyte B550M           | 2        | 0.54%   |
| Gigabyte A320M-S2H       | 2        | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 41       | 11.05%  |
| 2013 | 35       | 9.43%   |
| 2020 | 34       | 9.16%   |
| 2010 | 34       | 9.16%   |
| 2018 | 33       | 8.89%   |
| 2011 | 26       | 7.01%   |
| 2021 | 20       | 5.39%   |
| 2019 | 20       | 5.39%   |
| 2017 | 20       | 5.39%   |
| 2009 | 19       | 5.12%   |
| 2008 | 17       | 4.58%   |
| 2007 | 14       | 3.77%   |
| 2015 | 13       | 3.5%    |
| 2016 | 10       | 2.7%    |
| 2006 | 10       | 2.7%    |
| 2014 | 9        | 2.43%   |
| 2023 | 7        | 1.89%   |
| 2022 | 6        | 1.62%   |
| 2005 | 2        | 0.54%   |
| 2003 | 1        | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 371      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 363      | 97.06%  |
| Enabled  | 11       | 2.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 371      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 81       | 21.54%  |
| 4.01-8.0    | 71       | 18.88%  |
| 3.01-4.0    | 67       | 17.82%  |
| 16.01-24.0  | 61       | 16.22%  |
| 32.01-64.0  | 46       | 12.23%  |
| 1.01-2.0    | 22       | 5.85%   |
| 64.01-256.0 | 14       | 3.72%   |
| 24.01-32.0  | 7        | 1.86%   |
| 2.01-3.0    | 5        | 1.33%   |
| 0.51-1.0    | 2        | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 132      | 31.81%  |
| 2.01-3.0   | 96       | 23.13%  |
| 3.01-4.0   | 67       | 16.14%  |
| 4.01-8.0   | 66       | 15.9%   |
| 0.51-1.0   | 27       | 6.51%   |
| 8.01-16.0  | 21       | 5.06%   |
| 16.01-24.0 | 3        | 0.72%   |
| 0.01-0.5   | 3        | 0.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 182      | 47.03%  |
| 2      | 108      | 27.91%  |
| 3      | 55       | 14.21%  |
| 4      | 18       | 4.65%   |
| 5      | 12       | 3.1%    |
| 6      | 6        | 1.55%   |
| 8      | 3        | 0.78%   |
| 9      | 1        | 0.26%   |
| 7      | 1        | 0.26%   |
| 0      | 1        | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 237      | 63.37%  |
| Yes       | 137      | 36.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 370      | 99.73%  |
| No        | 1        | 0.27%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 220      | 58.51%  |
| Yes       | 156      | 41.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 292      | 77.66%  |
| Yes       | 84       | 22.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Colombia | 371      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Bogotá          | 150      | 38.86%  |
| Medellín        | 67       | 17.36%  |
| Santiago de Cali | 31       | 8.03%   |
| Bucaramanga      | 17       | 4.4%    |
| Barranquilla     | 17       | 4.4%    |
| Pereira          | 8        | 2.07%   |
| Pasto            | 7        | 1.81%   |
| Ibague           | 7        | 1.81%   |
| Cúcuta          | 6        | 1.55%   |
| Valledupar       | 5        | 1.3%    |
| Santa Marta      | 5        | 1.3%    |
| Villavicencio    | 4        | 1.04%   |
| Chia             | 4        | 1.04%   |
| Armenia          | 4        | 1.04%   |
| Tunja            | 3        | 0.78%   |
| Palmira          | 3        | 0.78%   |
| Montería        | 3        | 0.78%   |
| Tuluá           | 2        | 0.52%   |
| Soledad          | 2        | 0.52%   |
| Piedecuesta      | 2        | 0.52%   |
| Neiva            | 2        | 0.52%   |
| Manizales        | 2        | 0.52%   |
| Duitama          | 2        | 0.52%   |
| Cartagena        | 2        | 0.52%   |
| Calarcá         | 2        | 0.52%   |
| Buenaventura     | 2        | 0.52%   |
| Bello            | 2        | 0.52%   |
| Zipacon          | 1        | 0.26%   |
| Yotoco           | 1        | 0.26%   |
| Villagarzon      | 1        | 0.26%   |
| Tocancipa        | 1        | 0.26%   |
| Soacha           | 1        | 0.26%   |
| Rionegro         | 1        | 0.26%   |
| Puerto Carreño  | 1        | 0.26%   |
| Popayán         | 1        | 0.26%   |
| Pitalito         | 1        | 0.26%   |
| Ocaña           | 1        | 0.26%   |
| Mompos           | 1        | 0.26%   |
| La Loma          | 1        | 0.26%   |
| Jamundi          | 1        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 114      | 170    | 17.01%  |
| Seagate                     | 99       | 147    | 14.78%  |
| Toshiba                     | 82       | 114    | 12.24%  |
| Hitachi                     | 58       | 73     | 8.66%   |
| Kingston                    | 52       | 105    | 7.76%   |
| Samsung Electronics         | 45       | 76     | 6.72%   |
| A-DATA Technology           | 29       | 36     | 4.33%   |
| Crucial                     | 24       | 28     | 3.58%   |
| Maxtor                      | 20       | 22     | 2.99%   |
| Sandisk                     | 17       | 28     | 2.54%   |
| Patriot                     | 8        | 9      | 1.19%   |
| HGST                        | 8        | 9      | 1.19%   |
| Realtek Semiconductor       | 7        | 7      | 1.04%   |
| PNY                         | 7        | 10     | 1.04%   |
| Unknown                     | 6        | 10     | 0.9%    |
| Team                        | 6        | 6      | 0.9%    |
| ADATA Technology            | 6        | 7      | 0.9%    |
| Phison                      | 5        | 9      | 0.75%   |
| Micron/Crucial Technology   | 5        | 8      | 0.75%   |
| Lexar                       | 5        | 5      | 0.75%   |
| Gigabyte Technology         | 5        | 6      | 0.75%   |
| XrayDisk                    | 4        | 4      | 0.6%    |
| XPG                         | 4        | 5      | 0.6%    |
| JMicron Technology          | 4        | 4      | 0.6%    |
| Hewlett-Packard             | 4        | 5      | 0.6%    |
| Silicon Motion              | 3        | 3      | 0.45%   |
| Corsair                     | 3        | 6      | 0.45%   |
| China                       | 3        | 4      | 0.45%   |
| Transcend                   | 2        | 3      | 0.3%    |
| SPCC                        | 2        | 2      | 0.3%    |
| SK hynix                    | 2        | 4      | 0.3%    |
| Phison Electronics          | 2        | 2      | 0.3%    |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.3%    |
| KingSpec                    | 2        | 2      | 0.3%    |
| Fujitsu                     | 2        | 2      | 0.3%    |
| Fanxiang                    | 2        | 2      | 0.3%    |
| Biwin Storage Technology    | 2        | 2      | 0.3%    |
| Unknown                     | 2        | 3      | 0.3%    |
| XSTAR                       | 1        | 1      | 0.15%   |
| SUPERSONIC                  | 1        | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                | 35       | 4.78%   |
| Kingston SA400S37240G 240GB SSD                       | 15       | 2.05%   |
| Toshiba HDWD110 1TB                                   | 11       | 1.5%    |
| Toshiba DT01ACA200 2TB                                | 10       | 1.37%   |
| Toshiba DT01ACA050 500GB                              | 10       | 1.37%   |
| Seagate ST1000DM010-2EP102 1TB                        | 9        | 1.23%   |
| Kingston SA400S37120G 120GB SSD                       | 9        | 1.23%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 8        | 1.09%   |
| Seagate ST3500413AS 500GB                             | 7        | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 7        | 0.96%   |
| Kingston SV300S37A120G 120GB SSD                      | 7        | 0.96%   |
| Hitachi HDS721050CLA362 500GB                         | 7        | 0.96%   |
| Crucial CT240BX500SSD1 240GB                          | 7        | 0.96%   |
| Seagate ST500DM002-1BD142 500GB                       | 6        | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 6        | 0.82%   |
| Kingston SA400S37480G 480GB SSD                       | 6        | 0.82%   |
| A-DATA SU630 240GB SSD                                | 6        | 0.82%   |
| Seagate ST500LT012-1DG142 500GB                       | 5        | 0.68%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 5        | 0.68%   |
| Hitachi HDS721616PLA380 160GB                         | 5        | 0.68%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                        | 4        | 0.55%   |
| WDC WD5000AAKX-60U6AA0 500GB                          | 4        | 0.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB                   | 4        | 0.55%   |
| Seagate ST2000DM008-2FR102 2TB                        | 4        | 0.55%   |
| Seagate ST1000DM003-1ER162 1TB                        | 4        | 0.55%   |
| Lexar 128GB SSD                                       | 4        | 0.55%   |
| Kingston SNVS250G 250GB                               | 4        | 0.55%   |
| Kingston SA400S37960G 960GB SSD                       | 4        | 0.55%   |
| A-DATA SU650 120GB SSD                                | 4        | 0.55%   |
| WDC WD5000AAKX-001CA0 500GB                           | 3        | 0.41%   |
| WDC WD3200AAJS-00L7A0 320GB                           | 3        | 0.41%   |
| Unknown SD/MMC/MS PRO 128GB                           | 3        | 0.41%   |
| Toshiba MQ04ABF100 1TB                                | 3        | 0.41%   |
| Toshiba MQ01ABD100 1TB                                | 3        | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 3        | 0.41%   |
| Seagate ST4000DM004-2CV104 4TB                        | 3        | 0.41%   |
| Seagate ST3500418AS 500GB                             | 3        | 0.41%   |
| Seagate ST2000DX002-2DV164 2TB                        | 3        | 0.41%   |
| Seagate ST1500DL003-9VT16L 1TB                        | 3        | 0.41%   |
| Seagate ST1000DM003-1SB102 1TB                        | 3        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives  | Percent |
|---------------------|----------|---------|---------|
| WDC                 | 99       | 140     | 25.06%  |
| Seagate             | 97       | 144     | 24.56%  |
| Toshiba             | 81       | 113     | 20.51%  |
| Hitachi             | 58       | 73      | 14.68%  |
| Maxtor              | 20       | 22      | 5.06%   |
| Samsung Electronics | 17       | 23      | 4.3%    |
| HGST                | 8        | 9       | 2.03%   |
| Unknown             | 3        | 4       | 0.76%   |
| JMicron Technology  | 3        | 3       | 0.76%   |
| Hewlett-Packard     | 2        | 3       | 0.51%   |
| Fujitsu             | 2        | 2       | 0.51%   |
| XrayDisk            | 1        | 1       | 0.25%   |
| SAGE                | 1        | Unknown | 0.25%   |
| IBM/Hitachi         | 1        | 1       | 0.25%   |
| ExcelStor           | 1        | 1       | 0.25%   |
| Apple               | 1        | 1       | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 45       | 89     | 25.71%  |
| A-DATA Technology   | 25       | 32     | 14.29%  |
| Crucial             | 21       | 24     | 12%     |
| WDC                 | 15       | 27     | 8.57%   |
| Samsung Electronics | 10       | 12     | 5.71%   |
| Patriot             | 7        | 8      | 4%      |
| SanDisk             | 6        | 8      | 3.43%   |
| PNY                 | 6        | 9      | 3.43%   |
| Team                | 5        | 5      | 2.86%   |
| Lexar               | 5        | 5      | 2.86%   |
| Gigabyte Technology | 4        | 5      | 2.29%   |
| China               | 3        | 4      | 1.71%   |
| Transcend           | 2        | 3      | 1.14%   |
| SPCC                | 2        | 2      | 1.14%   |
| SK hynix            | 2        | 4      | 1.14%   |
| KingSpec            | 2        | 2      | 1.14%   |
| Corsair             | 2        | 5      | 1.14%   |
| XSTAR               | 1        | 1      | 0.57%   |
| XrayDisk            | 1        | 1      | 0.57%   |
| Unknown             | 1        | 1      | 0.57%   |
| Toshiba             | 1        | 1      | 0.57%   |
| Seagate             | 1        | 1      | 0.57%   |
| Micron Technology   | 1        | 1      | 0.57%   |
| LITEON              | 1        | 1      | 0.57%   |
| KingFast            | 1        | 1      | 0.57%   |
| KingDian            | 1        | 1      | 0.57%   |
| Hewlett-Packard     | 1        | 1      | 0.57%   |
| EAGET               | 1        | 1      | 0.57%   |
| DTECHCO             | 1        | 3      | 0.57%   |
| Unknown             | 1        | 1      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 286      | 540    | 53.96%  |
| SSD     | 152      | 259    | 28.68%  |
| NVMe    | 85       | 148    | 16.04%  |
| Unknown | 7        | 10     | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 336      | 787    | 76.54%  |
| NVMe | 85       | 148    | 19.36%  |
| SAS  | 18       | 22     | 4.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 251      | 438    | 53.98%  |
| 0.51-1.0   | 161      | 266    | 34.62%  |
| 1.01-2.0   | 34       | 55     | 7.31%   |
| 3.01-4.0   | 6        | 15     | 1.29%   |
| 2.01-3.0   | 6        | 11     | 1.29%   |
| 4.01-10.0  | 5        | 9      | 1.08%   |
| 10.01-20.0 | 2        | 5      | 0.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 85       | 21.14%  |
| 251-500        | 75       | 18.66%  |
| 501-1000       | 72       | 17.91%  |
| 1001-2000      | 46       | 11.44%  |
| 1-20           | 37       | 9.2%    |
| 51-100         | 28       | 6.97%   |
| More than 3000 | 23       | 5.72%   |
| 2001-3000      | 17       | 4.23%   |
| Unknown        | 12       | 2.99%   |
| 21-50          | 7        | 1.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 145      | 35.02%  |
| 21-50          | 61       | 14.73%  |
| 101-250        | 58       | 14.01%  |
| 51-100         | 44       | 10.63%  |
| 501-1000       | 35       | 8.45%   |
| 251-500        | 27       | 6.52%   |
| 1001-2000      | 16       | 3.86%   |
| Unknown        | 12       | 2.9%    |
| More than 3000 | 10       | 2.42%   |
| 2001-3000      | 4        | 0.97%   |
| 0              | 2        | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                     | Desktops | Drives | Percent |
|-----------------------------------------------------------|----------|--------|---------|
| Hitachi HDS721050CLA362 500GB                             | 3        | 3      | 2.97%   |
| A-DATA Technology SU630 240GB SSD                         | 3        | 3      | 2.97%   |
| WDC WD3200AAJS-56M0A0 320GB                               | 2        | 2      | 1.98%   |
| Toshiba DT01ACA100 1TB                                    | 2        | 2      | 1.98%   |
| Seagate ST500LT012-1DG142 500GB                           | 2        | 2      | 1.98%   |
| Seagate ST500DM002-1BD142 500GB                           | 2        | 2      | 1.98%   |
| Seagate ST1000DM003-1ER162 1TB                            | 2        | 2      | 1.98%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 256GB | 2        | 2      | 1.98%   |
| Hitachi HDP725032GLA360 320GB                             | 2        | 2      | 1.98%   |
| XrayDisk SSD 256GB                                        | 1        | 1      | 0.99%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                            | 1        | 2      | 0.99%   |
| WDC WD800JD-75MSA3 80GB                                   | 1        | 1      | 0.99%   |
| WDC WD800JD-60LSA0 80GB                                   | 1        | 1      | 0.99%   |
| WDC WD800BD-22MRA1 80GB                                   | 1        | 1      | 0.99%   |
| WDC WD6400AAKS-65Z7B0 640GB                               | 1        | 1      | 0.99%   |
| WDC WD5000LPLX-66ZNTT1 500GB                              | 1        | 1      | 0.99%   |
| WDC WD5000AAKX-60U6AA0 500GB                              | 1        | 1      | 0.99%   |
| WDC WD5000AAKS-08V0A0 500GB                               | 1        | 1      | 0.99%   |
| WDC WD3200BEVT-22ZCT0 320GB                               | 1        | 1      | 0.99%   |
| WDC WD3200AVJS-63B6A0 320GB                               | 1        | 1      | 0.99%   |
| WDC WD3200AAJS-65M0A0 320GB                               | 1        | 1      | 0.99%   |
| WDC WD3200AAJS-60Z0A0 320GB                               | 1        | 1      | 0.99%   |
| WDC WD3200AAJS-56B4A0 320GB                               | 1        | 1      | 0.99%   |
| WDC WD3200AAJS-08B4A0 320GB                               | 1        | 1      | 0.99%   |
| WDC WD2500BEVT-60ZCT1 250GB                               | 1        | 1      | 0.99%   |
| WDC WD20PURZ-85GU6Y0 2TB                                  | 1        | 1      | 0.99%   |
| WDC WD20PURZ-85AKKY0 2TB                                  | 1        | 1      | 0.99%   |
| WDC WD20EZRX-00DC0B0 2TB                                  | 1        | 1      | 0.99%   |
| WDC WD2003FYPS-27W9B0 2TB                                 | 1        | 1      | 0.99%   |
| WDC WD1600AAJS-75M0A0 160GB                               | 1        | 1      | 0.99%   |
| WDC WD10EZEX-08WN4A0 1TB                                  | 1        | 1      | 0.99%   |
| WDC WD10EURX-73FH1Y0 1TB                                  | 1        | 1      | 0.99%   |
| WDC WD10EALX-008EA0 1TB                                   | 1        | 2      | 0.99%   |
| WDC WD10EACS-00D6B1 1TB                                   | 1        | 1      | 0.99%   |
| WDC WD1001FAES-75W7A0 1TB                                 | 1        | 1      | 0.99%   |
| Toshiba MQ04ABF100 1TB                                    | 1        | 1      | 0.99%   |
| Toshiba MQ01ABF032 320GB                                  | 1        | 1      | 0.99%   |
| Toshiba MQ01ABD075 752GB                                  | 1        | 1      | 0.99%   |
| Toshiba MK2555GSXF 250GB                                  | 1        | 1      | 0.99%   |
| Toshiba HDWD110 1TB                                       | 1        | 1      | 0.99%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 21       | 29     | 23.33%  |
| Seagate               | 19       | 27     | 21.11%  |
| Hitachi               | 17       | 19     | 18.89%  |
| Toshiba               | 9        | 9      | 10%     |
| Samsung Electronics   | 6        | 6      | 6.67%   |
| Maxtor                | 6        | 7      | 6.67%   |
| A-DATA Technology     | 3        | 3      | 3.33%   |
| Realtek Semiconductor | 2        | 2      | 2.22%   |
| HGST                  | 2        | 2      | 2.22%   |
| XrayDisk              | 1        | 1      | 1.11%   |
| SK hynix              | 1        | 2      | 1.11%   |
| Kingston              | 1        | 1      | 1.11%   |
| Fujitsu               | 1        | 1      | 1.11%   |
| Crucial               | 1        | 1      | 1.11%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 27     | 25.64%  |
| Seagate             | 19       | 27     | 24.36%  |
| Hitachi             | 17       | 19     | 21.79%  |
| Toshiba             | 9        | 9      | 11.54%  |
| Maxtor              | 6        | 7      | 7.69%   |
| Samsung Electronics | 4        | 4      | 5.13%   |
| HGST                | 2        | 2      | 2.56%   |
| Fujitsu             | 1        | 1      | 1.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 66       | 96     | 84.62%  |
| SSD  | 8        | 10     | 10.26%  |
| NVMe | 4        | 4      | 5.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Desktops | Drives | Percent |
|-------------------------|----------|--------|---------|
| Maxtor STM380211AS 80GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| Maxtor | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 222      | 582    | 51.75%  |
| Works    | 130      | 264    | 30.3%   |
| Malfunc  | 76       | 110    | 17.72%  |
| Failed   | 1        | 1      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 221      | 45.38%  |
| AMD                         | 127      | 26.08%  |
| Samsung Electronics         | 21       | 4.31%   |
| Nvidia                      | 18       | 3.7%    |
| SanDisk                     | 14       | 2.87%   |
| Kingston Technology Company | 11       | 2.26%   |
| Realtek Semiconductor       | 10       | 2.05%   |
| ADATA Technology            | 10       | 2.05%   |
| Phison Electronics          | 9        | 1.85%   |
| ASMedia Technology          | 9        | 1.85%   |
| VIA Technologies            | 6        | 1.23%   |
| Silicon Motion              | 6        | 1.23%   |
| Micron/Crucial Technology   | 6        | 1.23%   |
| MAXIO Technology (Hangzhou) | 5        | 1.03%   |
| JMicron Technology          | 3        | 0.62%   |
| Seagate Technology          | 2        | 0.41%   |
| Marvell Technology Group    | 2        | 0.41%   |
| INNOGRIT                    | 2        | 0.41%   |
| Biwin Storage Technology    | 2        | 0.41%   |
| Micron Technology           | 1        | 0.21%   |
| Hewlett-Packard             | 1        | 0.21%   |
| Broadcom / LSI              | 1        | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 54       | 8.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 35       | 5.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 31       | 4.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 30       | 4.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 29       | 4.43%   |
| AMD 500 Series Chipset SATA Controller                                                  | 27       | 4.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 27       | 4.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 19       | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 19       | 2.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 18       | 2.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14       | 2.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14       | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 14       | 2.14%   |
| Nvidia MCP61 SATA Controller                                                            | 13       | 1.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 13       | 1.99%   |
| Intel SATA Controller [RAID mode]                                                       | 12       | 1.83%   |
| Nvidia MCP61 IDE                                                                        | 11       | 1.68%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 11       | 1.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 9        | 1.38%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 9        | 1.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 1.22%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 7        | 1.07%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 1.07%   |
| Phison E12 NVMe Controller                                                              | 6        | 0.92%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 6        | 0.92%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                                    | 6        | 0.92%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6        | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6        | 0.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 0.92%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 0.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 0.76%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 5        | 0.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 0.76%   |
| AMD 600 Series Chipset SATA Controller                                                  | 5        | 0.76%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 4        | 0.61%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 4        | 0.61%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 0.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.61%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.61%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 4        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 259      | 52.54%  |
| IDE  | 123      | 24.95%  |
| NVMe | 85       | 17.24%  |
| RAID | 23       | 4.67%   |
| SAS  | 3        | 0.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 223      | 60.11%  |
| AMD    | 148      | 39.89%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 10       | 2.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 9        | 2.41%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 8        | 2.14%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 8        | 2.14%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 8        | 2.14%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 7        | 1.87%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 7        | 1.87%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 7        | 1.87%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 7        | 1.87%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 6        | 1.6%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 6        | 1.6%    |
| AMD FX-8320 Eight-Core Processor            | 6        | 1.6%    |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 5        | 1.34%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 5        | 1.34%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 5        | 1.34%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4        | 1.07%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 1.07%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 4        | 1.07%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 4        | 1.07%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 1.07%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 1.07%   |
| Intel Celeron CPU G1610 @ 2.60GHz           | 4        | 1.07%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 1.07%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 1.07%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 1.07%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 1.07%   |
| AMD Athlon 64 X2 Dual Core Processor 5200+  | 4        | 1.07%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 3        | 0.8%    |
| Intel Pentium CPU G3250 @ 3.20GHz           | 3        | 0.8%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 0.8%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.8%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.8%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 0.8%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 0.8%    |
| AMD Phenom II X6 1100T Processor            | 3        | 0.8%    |
| AMD FX-8350 Eight-Core Processor            | 3        | 0.8%    |
| AMD Athlon II X2 250 Processor              | 3        | 0.8%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.53%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.53%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 63       | 16.84%  |
| AMD Ryzen 5             | 46       | 12.3%   |
| Intel Core i7           | 36       | 9.63%   |
| Intel Core i3           | 30       | 8.02%   |
| AMD Ryzen 7             | 19       | 5.08%   |
| Intel Xeon              | 15       | 4.01%   |
| AMD FX                  | 15       | 4.01%   |
| Other                   | 13       | 3.48%   |
| Intel Core 2 Duo        | 13       | 3.48%   |
| Intel Pentium Dual-Core | 12       | 3.21%   |
| Intel Celeron           | 12       | 3.21%   |
| Intel Pentium Dual      | 9        | 2.41%   |
| AMD Ryzen 3             | 9        | 2.41%   |
| AMD Ryzen 9             | 8        | 2.14%   |
| AMD Athlon II X2        | 8        | 2.14%   |
| Intel Pentium           | 7        | 1.87%   |
| AMD Athlon 64 X2        | 6        | 1.6%    |
| Intel Core 2 Quad       | 5        | 1.34%   |
| AMD Sempron             | 5        | 1.34%   |
| AMD Phenom II X6        | 5        | 1.34%   |
| Intel Core 2            | 4        | 1.07%   |
| AMD Athlon              | 4        | 1.07%   |
| AMD Ryzen Threadripper  | 3        | 0.8%    |
| AMD Phenom II X4        | 3        | 0.8%    |
| AMD Phenom              | 3        | 0.8%    |
| AMD A10                 | 3        | 0.8%    |
| Intel Pentium D         | 2        | 0.53%   |
| Intel Pentium 4         | 2        | 0.53%   |
| AMD Ryzen 5 PRO         | 2        | 0.53%   |
| AMD A8                  | 2        | 0.53%   |
| AMD A4                  | 2        | 0.53%   |
| Intel Core i9           | 1        | 0.27%   |
| Intel Celeron D         | 1        | 0.27%   |
| Intel Atom              | 1        | 0.27%   |
| AMD Ryzen 7 PRO         | 1        | 0.27%   |
| AMD E                   | 1        | 0.27%   |
| AMD Athlon II X3        | 1        | 0.27%   |
| AMD Athlon 64           | 1        | 0.27%   |
| AMD A6                  | 1        | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 119      | 31.9%   |
| 2      | 118      | 31.64%  |
| 6      | 63       | 16.89%  |
| 8      | 27       | 7.24%   |
| 1      | 14       | 3.75%   |
| 12     | 13       | 3.49%   |
| 3      | 8        | 2.14%   |
| 16     | 6        | 1.61%   |
| 10     | 3        | 0.8%    |
| 14     | 2        | 0.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 365      | 98.38%  |
| 2      | 6        | 1.62%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 200      | 53.62%  |
| 1      | 172      | 46.11%  |
| 4      | 1        | 0.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 367      | 98.92%  |
| Unknown        | 2        | 0.54%   |
| 64-bit         | 1        | 0.27%   |
| 32-bit         | 1        | 0.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 130      | 33.77%  |
| 0x306c3    | 23       | 5.97%   |
| 0x206a7    | 19       | 4.94%   |
| 0x306a9    | 17       | 4.42%   |
| 0x1067a    | 15       | 3.9%    |
| 0x08108109 | 12       | 3.12%   |
| 0x08701021 | 11       | 2.86%   |
| 0x6fd      | 10       | 2.6%    |
| 0x06000852 | 10       | 2.6%    |
| 0x010000c8 | 9        | 2.34%   |
| 0x906e9    | 7        | 1.82%   |
| 0x506e3    | 7        | 1.82%   |
| 0x10676    | 6        | 1.56%   |
| 0x0a50000c | 6        | 1.56%   |
| 0xa0653    | 5        | 1.3%    |
| 0x0800820d | 5        | 1.3%    |
| 0x010000dc | 5        | 1.3%    |
| 0x906ea    | 4        | 1.04%   |
| 0xf65      | 3        | 0.78%   |
| 0xa0671    | 3        | 0.78%   |
| 0xa0655    | 3        | 0.78%   |
| 0x6fb      | 3        | 0.78%   |
| 0x20655    | 3        | 0.78%   |
| 0x20652    | 3        | 0.78%   |
| 0x106e5    | 3        | 0.78%   |
| 0x08001138 | 3        | 0.78%   |
| 0x06001119 | 3        | 0.78%   |
| 0x90672    | 2        | 0.52%   |
| 0x6f6      | 2        | 0.52%   |
| 0x6f2      | 2        | 0.52%   |
| 0x206d7    | 2        | 0.52%   |
| 0x0a601203 | 2        | 0.52%   |
| 0x0a50000d | 2        | 0.52%   |
| 0x0a20120a | 2        | 0.52%   |
| 0x0a201009 | 2        | 0.52%   |
| 0x08701013 | 2        | 0.52%   |
| 0x08001137 | 2        | 0.52%   |
| 0x06000822 | 2        | 0.52%   |
| 0x03000027 | 2        | 0.52%   |
| 0x01000083 | 2        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 35       | 9.41%   |
| Haswell          | 35       | 9.41%   |
| SandyBridge      | 29       | 7.8%    |
| Zen 2            | 27       | 7.26%   |
| Penryn           | 26       | 6.99%   |
| Zen+             | 23       | 6.18%   |
| Zen 3            | 23       | 6.18%   |
| K10              | 23       | 6.18%   |
| Core             | 21       | 5.65%   |
| KabyLake         | 19       | 5.11%   |
| Piledriver       | 18       | 4.84%   |
| CometLake        | 14       | 3.76%   |
| K8 Hammer        | 11       | 2.96%   |
| Unknown          | 11       | 2.96%   |
| Zen              | 10       | 2.69%   |
| Westmere         | 9        | 2.42%   |
| Skylake          | 9        | 2.42%   |
| NetBurst         | 7        | 1.88%   |
| Nehalem          | 4        | 1.08%   |
| Icelake          | 3        | 0.81%   |
| Alderlake Hybrid | 3        | 0.81%   |
| K10 Llano        | 2        | 0.54%   |
| Bulldozer        | 2        | 0.54%   |
| Broadwell        | 2        | 0.54%   |
| TigerLake        | 1        | 0.27%   |
| Steamroller      | 1        | 0.27%   |
| Jaguar           | 1        | 0.27%   |
| Goldmont plus    | 1        | 0.27%   |
| Bonnell          | 1        | 0.27%   |
| Bobcat           | 1        | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 143      | 35.57%  |
| AMD                        | 129      | 32.09%  |
| Nvidia                     | 123      | 30.6%   |
| Matrox Electronics Systems | 4        | 1%      |
| VIA Technologies           | 3        | 0.75%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 18       | 4.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 16       | 3.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 16       | 3.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 15       | 3.65%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 14       | 3.41%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 12       | 2.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 11       | 2.68%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 10       | 2.43%   |
| Nvidia GT218 [GeForce 210]                                                  | 8        | 1.95%   |
| Nvidia GK208B [GeForce GT 710]                                              | 8        | 1.95%   |
| Intel HD Graphics 530                                                       | 8        | 1.95%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 8        | 1.95%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 8        | 1.95%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 7        | 1.7%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 7        | 1.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 1.7%    |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 6        | 1.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 1.46%   |
| Intel HD Graphics 630                                                       | 6        | 1.46%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 6        | 1.46%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 6        | 1.46%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 1.22%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 5        | 1.22%   |
| AMD RS780L [Radeon 3000]                                                    | 5        | 1.22%   |
| AMD Raphael                                                                 | 5        | 1.22%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 0.97%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 4        | 0.97%   |
| Intel Core Processor Integrated Graphics Controller                         | 4        | 0.97%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 4        | 0.97%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 4        | 0.97%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 0.73%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 3        | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 0.73%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 0.73%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 0.73%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.73%   |
| Matrox Electronics Systems MGA G200EH                                       | 3        | 0.73%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 3        | 0.73%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 3        | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 129      | 33.86%  |
| 1 x AMD         | 114      | 29.92%  |
| 1 x Nvidia      | 112      | 29.4%   |
| 2 x AMD         | 6        | 1.57%   |
| AMD + Nvidia    | 6        | 1.57%   |
| Intel + AMD     | 4        | 1.05%   |
| 1 x VIA         | 3        | 0.79%   |
| 1 x Matrox      | 3        | 0.79%   |
| Intel + Nvidia  | 3        | 0.79%   |
| Nvidia + Matrox | 1        | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 306      | 80.74%  |
| Proprietary | 54       | 14.25%  |
| Unknown     | 19       | 5.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 192      | 50.13%  |
| 1.01-2.0   | 50       | 13.05%  |
| 0.51-1.0   | 43       | 11.23%  |
| 0.01-0.5   | 42       | 10.97%  |
| 7.01-8.0   | 20       | 5.22%   |
| 3.01-4.0   | 18       | 4.7%    |
| 5.01-6.0   | 8        | 2.09%   |
| 8.01-16.0  | 6        | 1.57%   |
| 2.01-3.0   | 4        | 1.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 100      | 28.25%  |
| Goldstar             | 70       | 19.77%  |
| Hewlett-Packard      | 45       | 12.71%  |
| Dell                 | 25       | 7.06%   |
| Acer                 | 19       | 5.37%   |
| AOC                  | 11       | 3.11%   |
| ASUSTek Computer     | 8        | 2.26%   |
| ViewSonic            | 7        | 1.98%   |
| RTK                  | 6        | 1.69%   |
| LG Electronics       | 6        | 1.69%   |
| Lenovo               | 6        | 1.69%   |
| SAC                  | 5        | 1.41%   |
| MSI                  | 5        | 1.41%   |
| SANYO                | 4        | 1.13%   |
| Unknown              | 3        | 0.85%   |
| Sceptre Tech         | 3        | 0.85%   |
| BenQ                 | 3        | 0.85%   |
| Ancor Communications | 3        | 0.85%   |
| NCS                  | 2        | 0.56%   |
| HKC                  | 2        | 0.56%   |
| Envision             | 2        | 0.56%   |
| YSP                  | 1        | 0.28%   |
| Westinghouse         | 1        | 0.28%   |
| Unknown (XXX)        | 1        | 0.28%   |
| SMC                  | 1        | 0.28%   |
| SKG                  | 1        | 0.28%   |
| PEGA                 | 1        | 0.28%   |
| MStar                | 1        | 0.28%   |
| MSD                  | 1        | 0.28%   |
| LG Display           | 1        | 0.28%   |
| KON                  | 1        | 0.28%   |
| KOA                  | 1        | 0.28%   |
| JRY                  | 1        | 0.28%   |
| ITE                  | 1        | 0.28%   |
| HIC                  | 1        | 0.28%   |
| HannStar             | 1        | 0.28%   |
| Estecom              | 1        | 0.28%   |
| DENON                | 1        | 0.28%   |
| CVT                  | 1        | 0.28%   |
| AGO                  | 1        | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 7        | 1.9%    |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 6        | 1.63%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 6        | 1.63%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6        | 1.63%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 4        | 1.09%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 1.09%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                 | 4        | 1.09%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 4        | 1.09%   |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                 | 4        | 1.09%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 4        | 1.09%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                   | 4        | 1.09%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 3        | 0.82%   |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch   | 3        | 0.82%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch     | 3        | 0.82%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 3        | 0.82%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 480x270mm 21.7-inch     | 3        | 0.82%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch      | 3        | 0.82%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 3        | 0.82%   |
| RTK Verbatim M14 RTK0001 1920x1080                                    | 3        | 0.82%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                 | 3        | 0.82%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 3        | 0.82%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 3        | 0.82%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 3        | 0.82%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                  | 3        | 0.82%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.54%   |
| SANYO LCD TV SAN0523 1920x1080 443x249mm 20.0-inch                    | 2        | 0.54%   |
| SANYO LCD MONITOR SAN2213 1600x900 477x268mm 21.5-inch                | 2        | 0.54%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 2        | 0.54%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch      | 2        | 0.54%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 2        | 0.54%   |
| RTK '' RTK1920 1920x1080 698x393mm 31.5-inch                          | 2        | 0.54%   |
| NCS LCD Monitor NCS2275 1920x1080 256x192mm 12.6-inch                 | 2        | 0.54%   |
| MSI G271CQR MSI6CC3 2560x1440 600x330mm 27.0-inch                     | 2        | 0.54%   |
| LG Electronics LCD Monitor E2241 1920x1080                            | 2        | 0.54%   |
| Hewlett-Packard Compaq S1922 HWP290B 1366x768 413x234mm 18.7-inch     | 2        | 0.54%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 2        | 0.54%   |
| Goldstar ULTRAWIDE GSM5BF8 2560x1080 673x284mm 28.8-inch              | 2        | 0.54%   |
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch              | 2        | 0.54%   |
| Goldstar HDR WFHD GSM5B9F 2560x1080 798x334mm 34.1-inch               | 2        | 0.54%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                      | 2        | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 123      | 35.24%  |
| 1366x768 (WXGA)    | 45       | 12.89%  |
| 1600x900 (HD+)     | 29       | 8.31%   |
| 1440x900 (WXGA+)   | 29       | 8.31%   |
| 1280x1024 (SXGA)   | 25       | 7.16%   |
| 3840x2160 (4K)     | 24       | 6.88%   |
| 2560x1440 (QHD)    | 14       | 4.01%   |
| 1360x768           | 13       | 3.72%   |
| 1680x1050 (WSXGA+) | 12       | 3.44%   |
| 2560x1080          | 10       | 2.87%   |
| 1024x768 (XGA)     | 5        | 1.43%   |
| 1920x1200 (WUXGA)  | 4        | 1.15%   |
| Unknown            | 4        | 1.15%   |
| 3840x1080          | 2        | 0.57%   |
| 1280x960           | 2        | 0.57%   |
| 1280x720 (HD)      | 2        | 0.57%   |
| 6400x2160          | 1        | 0.29%   |
| 3440x1440          | 1        | 0.29%   |
| 3200x1080          | 1        | 0.29%   |
| 2288x1287          | 1        | 0.29%   |
| 1920x540           | 1        | 0.29%   |
| 1152x864           | 1        | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 50       | 14.01%  |
| 21      | 48       | 13.45%  |
| 19      | 48       | 13.45%  |
| 23      | 32       | 8.96%   |
| 31      | 26       | 7.28%   |
| 27      | 23       | 6.44%   |
| 20      | 21       | 5.88%   |
| 17      | 19       | 5.32%   |
| Unknown | 19       | 5.32%   |
| 24      | 15       | 4.2%    |
| 22      | 10       | 2.8%    |
| 15      | 9        | 2.52%   |
| 34      | 7        | 1.96%   |
| 72      | 4        | 1.12%   |
| 28      | 4        | 1.12%   |
| 84      | 3        | 0.84%   |
| 54      | 3        | 0.84%   |
| 12      | 3        | 0.84%   |
| 48      | 2        | 0.56%   |
| 32      | 2        | 0.56%   |
| 16      | 2        | 0.56%   |
| 60      | 1        | 0.28%   |
| 58      | 1        | 0.28%   |
| 52      | 1        | 0.28%   |
| 46      | 1        | 0.28%   |
| 40      | 1        | 0.28%   |
| 29      | 1        | 0.28%   |
| 13      | 1        | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 165      | 47.83%  |
| 501-600     | 60       | 17.39%  |
| 601-700     | 33       | 9.57%   |
| 301-350     | 27       | 7.83%   |
| Unknown     | 19       | 5.51%   |
| 351-400     | 11       | 3.19%   |
| 701-800     | 9        | 2.61%   |
| 1001-1500   | 9        | 2.61%   |
| 1501-2000   | 7        | 2.03%   |
| 201-300     | 4        | 1.16%   |
| 801-900     | 1        | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 225      | 67.57%  |
| 16/10   | 41       | 12.31%  |
| 5/4     | 25       | 7.51%   |
| Unknown | 18       | 5.41%   |
| 21/9    | 11       | 3.3%    |
| 4/3     | 10       | 3%      |
| 32/9    | 2        | 0.6%    |
| 3/2     | 1        | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 84       | 23.86%  |
| 151-200        | 84       | 23.86%  |
| 141-150        | 63       | 17.9%   |
| 351-500        | 35       | 9.94%   |
| 301-350        | 24       | 6.82%   |
| Unknown        | 19       | 5.4%    |
| More than 1000 | 14       | 3.98%   |
| 251-300        | 9        | 2.56%   |
| 101-110        | 7        | 1.99%   |
| 71-80          | 3        | 0.85%   |
| 131-140        | 3        | 0.85%   |
| 501-1000       | 3        | 0.85%   |
| 111-120        | 2        | 0.57%   |
| 81-90          | 1        | 0.28%   |
| 121-130        | 1        | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 226      | 67.26%  |
| 101-120 | 62       | 18.45%  |
| Unknown | 19       | 5.65%   |
| 1-50    | 16       | 4.76%   |
| 121-160 | 8        | 2.38%   |
| 161-240 | 5        | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 308      | 81.27%  |
| 2     | 42       | 11.08%  |
| 0     | 24       | 6.33%   |
| 3     | 5        | 1.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 248      | 48.34%  |
| Intel                             | 96       | 18.71%  |
| Qualcomm Atheros                  | 38       | 7.41%   |
| Ralink Technology                 | 28       | 5.46%   |
| TP-Link                           | 18       | 3.51%   |
| Broadcom                          | 16       | 3.12%   |
| Nvidia                            | 13       | 2.53%   |
| MediaTek                          | 7        | 1.36%   |
| Ralink                            | 6        | 1.17%   |
| Broadcom Limited                  | 6        | 1.17%   |
| Qualcomm Atheros Communications   | 5        | 0.97%   |
| Marvell Technology Group          | 4        | 0.78%   |
| Xiaomi                            | 3        | 0.58%   |
| VIA Technologies                  | 3        | 0.58%   |
| Samsung Electronics               | 3        | 0.58%   |
| Mercucys                          | 3        | 0.58%   |
| Sundance Technology Inc / IC Plus | 2        | 0.39%   |
| Motorola PCS                      | 2        | 0.39%   |
| ICS Advent                        | 2        | 0.39%   |
| D-Link System                     | 2        | 0.39%   |
| Wistron NeWeb                     | 1        | 0.19%   |
| Qualcomm                          | 1        | 0.19%   |
| OPPO Electronics                  | 1        | 0.19%   |
| Mellanox Technologies             | 1        | 0.19%   |
| LG Electronics                    | 1        | 0.19%   |
| Huawei Technologies               | 1        | 0.19%   |
| Encore Electronics                | 1        | 0.19%   |
| Aquantia                          | 1        | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 179      | 31.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 27       | 4.79%   |
| Realtek RTL8125 2.5GbE Controller                                      | 20       | 3.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 13       | 2.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12       | 2.13%   |
| Ralink MT7601U Wireless Adapter                                        | 11       | 1.95%   |
| Intel Wi-Fi 6 AX200                                                    | 11       | 1.95%   |
| Intel I211 Gigabit Network Connection                                  | 11       | 1.95%   |
| Intel Ethernet Controller I225-V                                       | 11       | 1.95%   |
| Nvidia MCP61 Ethernet                                                  | 10       | 1.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 8        | 1.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 8        | 1.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 7        | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7        | 1.24%   |
| Realtek 802.11ac NIC                                                   | 6        | 1.06%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6        | 1.06%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 1.06%   |
| TP-Link 802.11n NIC                                                    | 5        | 0.89%   |
| Qualcomm Atheros AR9271 802.11n                                        | 5        | 0.89%   |
| Intel Wireless 7260                                                    | 5        | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 5        | 0.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 4        | 0.71%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 4        | 0.71%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 0.71%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 4        | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3        | 0.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 3        | 0.53%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                  | 3        | 0.53%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3        | 0.53%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 3        | 0.53%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller              | 3        | 0.53%   |
| Ralink RT5370 Wireless Adapter                                         | 3        | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3        | 0.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3        | 0.53%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 3        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3        | 0.53%   |
| Mercucys 802.11n NIC                                                   | 3        | 0.53%   |
| Intel Ethernet Connection I217-V                                       | 3        | 0.53%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 0.53%   |
| Intel 82578DC Gigabit Network Connection                               | 3        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 41       | 24.4%   |
| Realtek Semiconductor           | 39       | 23.21%  |
| Ralink Technology               | 28       | 16.67%  |
| TP-Link                         | 18       | 10.71%  |
| Qualcomm Atheros                | 17       | 10.12%  |
| Ralink                          | 6        | 3.57%   |
| Qualcomm Atheros Communications | 5        | 2.98%   |
| MediaTek                        | 5        | 2.98%   |
| Mercucys                        | 3        | 1.79%   |
| Wistron NeWeb                   | 1        | 0.6%    |
| LG Electronics                  | 1        | 0.6%    |
| Encore Electronics              | 1        | 0.6%    |
| D-Link System                   | 1        | 0.6%    |
| Broadcom Limited                | 1        | 0.6%    |
| Broadcom                        | 1        | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Ralink RT2870/RT3070 Wireless Adapter                          | 13       | 7.74%   |
| Ralink MT7601U Wireless Adapter                                | 11       | 6.55%   |
| Intel Wi-Fi 6 AX200                                            | 11       | 6.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 8        | 4.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7        | 4.17%   |
| Realtek 802.11ac NIC                                           | 6        | 3.57%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 6        | 3.57%   |
| TP-Link 802.11n NIC                                            | 5        | 2.98%   |
| Qualcomm Atheros AR9271 802.11n                                | 5        | 2.98%   |
| Intel Wireless 7260                                            | 5        | 2.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5        | 2.98%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 4        | 2.38%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 4        | 2.38%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 3        | 1.79%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 3        | 1.79%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 3        | 1.79%   |
| Ralink RT5370 Wireless Adapter                                 | 3        | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3        | 1.79%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 3        | 1.79%   |
| Mercucys 802.11n NIC                                           | 3        | 1.79%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2        | 1.19%   |
| TP-Link 802.11ac WLAN Adapter                                  | 2        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 1.19%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2        | 1.19%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter           | 2        | 1.19%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 2        | 1.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2        | 1.19%   |
| Intel Wireless 7265                                            | 2        | 1.19%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 2        | 1.19%   |
| Intel Centrino Wireless-N 2230                                 | 2        | 1.19%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 2        | 1.19%   |
| Wistron NeWeb AR9170+AR9104 802.11abgn Wireless Adapter        | 1        | 0.6%    |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                        | 1        | 0.6%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1        | 0.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 0.6%    |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller    | 1        | 0.6%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1        | 0.6%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 0.6%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 0.6%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 232      | 60.1%   |
| Intel                             | 77       | 19.95%  |
| Qualcomm Atheros                  | 21       | 5.44%   |
| Broadcom                          | 15       | 3.89%   |
| Nvidia                            | 13       | 3.37%   |
| Broadcom Limited                  | 5        | 1.3%    |
| Marvell Technology Group          | 4        | 1.04%   |
| Xiaomi                            | 3        | 0.78%   |
| VIA Technologies                  | 3        | 0.78%   |
| Sundance Technology Inc / IC Plus | 2        | 0.52%   |
| Motorola PCS                      | 2        | 0.52%   |
| ICS Advent                        | 2        | 0.52%   |
| Qualcomm                          | 1        | 0.26%   |
| OPPO Electronics                  | 1        | 0.26%   |
| Mellanox Technologies             | 1        | 0.26%   |
| MediaTek                          | 1        | 0.26%   |
| Huawei Technologies               | 1        | 0.26%   |
| D-Link System                     | 1        | 0.26%   |
| Aquantia                          | 1        | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 179      | 45.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 27       | 6.89%   |
| Realtek RTL8125 2.5GbE Controller                                          | 20       | 5.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 12       | 3.06%   |
| Intel I211 Gigabit Network Connection                                      | 11       | 2.81%   |
| Intel Ethernet Controller I225-V                                           | 11       | 2.81%   |
| Nvidia MCP61 Ethernet                                                      | 10       | 2.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 8        | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 7        | 1.79%   |
| Intel 82579V Gigabit Network Connection                                    | 6        | 1.53%   |
| Intel Ethernet Connection (2) I219-V                                       | 4        | 1.02%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 4        | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 0.77%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3        | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 3        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3        | 0.77%   |
| Intel Ethernet Connection I217-V                                           | 3        | 0.77%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 0.77%   |
| Intel 82578DC Gigabit Network Connection                                   | 3        | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 3        | 0.77%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 2        | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 2        | 0.51%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 2        | 0.51%   |
| Nvidia MCP77 Ethernet                                                      | 2        | 0.51%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 2        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 0.51%   |
| Intel Ethernet Connection (12) I219-V                                      | 2        | 0.51%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 0.51%   |
| Intel 82566DM Gigabit Network Connection                                   | 2        | 0.51%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 2        | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 2        | 0.51%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 0.51%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                           | 2        | 0.51%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 0.51%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                    | 2        | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.26%   |
| Qualcomm POCO F3                                                           | 1        | 0.26%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.26%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 1        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 370      | 69.94%  |
| WiFi     | 155      | 29.3%   |
| Modem    | 3        | 0.57%   |
| Unknown  | 1        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 294      | 76.76%  |
| WiFi     | 88       | 22.98%  |
| Modem    | 1        | 0.26%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 268      | 71.66%  |
| 2     | 99       | 26.47%  |
| 3     | 3        | 0.8%    |
| 0     | 3        | 0.8%    |
| 7     | 1        | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 320      | 84.66%  |
| Yes  | 58       | 15.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 37       | 42.05%  |
| Cambridge Silicon Radio | 33       | 37.5%   |
| Realtek Semiconductor   | 4        | 4.55%   |
| MediaTek                | 3        | 3.41%   |
| IMC Networks            | 3        | 3.41%   |
| Foxconn / Hon Hai       | 2        | 2.27%   |
| ASUSTek Computer        | 2        | 2.27%   |
| TP-Link                 | 1        | 1.14%   |
| Dell                    | 1        | 1.14%   |
| Broadcom                | 1        | 1.14%   |
| Apple                   | 1        | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 33       | 37.5%   |
| Intel AX200 Bluetooth                               | 11       | 12.5%   |
| Intel Bluetooth wireless interface                  | 6        | 6.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5        | 5.68%   |
| Intel AX210 Bluetooth                               | 5        | 5.68%   |
| Realtek Bluetooth Radio                             | 3        | 3.41%   |
| MediaTek Wireless_Device                            | 3        | 3.41%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3        | 3.41%   |
| Intel AX211 Bluetooth                               | 3        | 3.41%   |
| Intel AX201 Bluetooth                               | 2        | 2.27%   |
| IMC Networks Wireless_Device                        | 2        | 2.27%   |
| Foxconn / Hon Hai Wireless_Device                   | 2        | 2.27%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 1        | 1.14%   |
| Realtek Bluetooth 5.3 Radio                         | 1        | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.14%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.14%   |
| Dell Wireless 365 Bluetooth                         | 1        | 1.14%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 1.14%   |
| ASUS Bluetooth Radio                                | 1        | 1.14%   |
| ASUS ASUS USB-BT500                                 | 1        | 1.14%   |
| Apple Bluetooth HCI                                 | 1        | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 216      | 37.83%  |
| AMD                                  | 169      | 29.6%   |
| Nvidia                               | 120      | 21.02%  |
| C-Media Electronics                  | 12       | 2.1%    |
| Generalplus Technology               | 7        | 1.23%   |
| VIA Technologies                     | 5        | 0.88%   |
| Logitech                             | 5        | 0.88%   |
| JMTek                                | 4        | 0.7%    |
| Creative Labs                        | 4        | 0.7%    |
| M-Audio                              | 3        | 0.53%   |
| Blue Microphones                     | 3        | 0.53%   |
| Texas Instruments                    | 2        | 0.35%   |
| Kingston Technology                  | 2        | 0.35%   |
| Turtle Beach                         | 1        | 0.18%   |
| Trust                                | 1        | 0.18%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.18%   |
| SteelSeries ApS                      | 1        | 0.18%   |
| Realtek Semiconductor                | 1        | 0.18%   |
| Razer USA                            | 1        | 0.18%   |
| Plantronics                          | 1        | 0.18%   |
| Micro Star International             | 1        | 0.18%   |
| KTMicro                              | 1        | 0.18%   |
| Jieli Technology                     | 1        | 0.18%   |
| HiBy                                 | 1        | 0.18%   |
| GN Netcom                            | 1        | 0.18%   |
| Giga-Byte Technology                 | 1        | 0.18%   |
| Earth Computer Technologies          | 1        | 0.18%   |
| Drop                                 | 1        | 0.18%   |
| Creative Technology                  | 1        | 0.18%   |
| Corsair                              | 1        | 0.18%   |
| Avid Technology                      | 1        | 0.18%   |
| AOKEO                                | 1        | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 48       | 7.01%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 42       | 6.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 35       | 5.11%   |
| AMD Starship/Matisse HD Audio Controller                                   | 32       | 4.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 31       | 4.53%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 29       | 4.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 19       | 2.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 19       | 2.77%   |
| Nvidia High Definition Audio Controller                                    | 15       | 2.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15       | 2.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15       | 2.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13       | 1.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 13       | 1.9%    |
| Nvidia MCP61 High Definition Audio                                         | 12       | 1.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 12       | 1.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 11       | 1.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11       | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11       | 1.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10       | 1.46%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 1.31%   |
| AMD Navi 10 HDMI Audio                                                     | 9        | 1.31%   |
| AMD FCH Azalia Controller                                                  | 9        | 1.31%   |
| Intel Comet Lake PCH-V cAVS                                                | 8        | 1.17%   |
| Intel 200 Series PCH HD Audio                                              | 8        | 1.17%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 8        | 1.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7        | 1.02%   |
| Generalplus Technology USB Audio Device                                    | 7        | 1.02%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 7        | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 0.88%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6        | 0.88%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6        | 0.88%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 0.88%   |
| Nvidia GP108 High Definition Audio Controller                              | 5        | 0.73%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5        | 0.73%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 0.73%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 5        | 0.73%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5        | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 0.58%   |
| Intel USB PnP Sound Device                                                 | 4        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 42       | 18.34%  |
| Samsung Electronics          | 26       | 11.35%  |
| Corsair                      | 25       | 10.92%  |
| A-DATA Technology            | 23       | 10.04%  |
| Kingston                     | 18       | 7.86%   |
| SK hynix                     | 13       | 5.68%   |
| Crucial                      | 11       | 4.8%    |
| Micron Technology            | 9        | 3.93%   |
| Team                         | 7        | 3.06%   |
| G.Skill                      | 7        | 3.06%   |
| Super Talent                 | 6        | 2.62%   |
| Patriot                      | 5        | 2.18%   |
| Ramaxel Technology           | 4        | 1.75%   |
| Hewlett-Packard              | 4        | 1.75%   |
| GeIL                         | 4        | 1.75%   |
| Nanya Technology             | 3        | 1.31%   |
| PNY                          | 2        | 0.87%   |
| Kreton                       | 2        | 0.87%   |
| Avant                        | 2        | 0.87%   |
| Unknown                      | 2        | 0.87%   |
| Unknown (AD8A)               | 1        | 0.44%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1        | 0.44%   |
| Unknown (0B85)               | 1        | 0.44%   |
| Transcend                    | 1        | 0.44%   |
| Sesame                       | 1        | 0.44%   |
| Ramos Technology             | 1        | 0.44%   |
| PUSKILL                      | 1        | 0.44%   |
| Patriot Memory (PDP Systems) | 1        | 0.44%   |
| Kllisre                      | 1        | 0.44%   |
| Golden Empire                | 1        | 0.44%   |
| Elpida                       | 1        | 0.44%   |
| CSX                          | 1        | 0.44%   |
| Atermiter                    | 1        | 0.44%   |
| Apacer                       | 1        | 0.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                      | 6        | 2.34%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s  | 6        | 2.34%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 5        | 1.95%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s            | 5        | 1.95%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s     | 3        | 1.17%   |
| Patriot RAM 3200 C16 Series 4GB DIMM DDR4 3600MT/s     | 3        | 1.17%   |
| GeIL RAM CL11-11-11 D3-1600 8GB DIMM DDR3 1600MT/s     | 3        | 1.17%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s   | 3        | 1.17%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 3        | 1.17%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s            | 3        | 1.17%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 0.78%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 2        | 0.78%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 2        | 0.78%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s               | 2        | 0.78%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s     | 2        | 0.78%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s     | 2        | 0.78%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s             | 2        | 0.78%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s         | 2        | 0.78%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s              | 2        | 0.78%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s    | 2        | 0.78%   |
| Samsung RAM M3 78T2953EZ3-CF7 1GB DIMM DDR2 800MT/s    | 2        | 0.78%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 2        | 0.78%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s    | 2        | 0.78%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s  | 2        | 0.78%   |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s | 2        | 0.78%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s  | 2        | 0.78%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 0.78%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3200MT/s            | 2        | 0.78%   |
| A-DATA RAM DDR4 2400 2OZ 4GB DIMM DDR4 3000MT/s        | 2        | 0.78%   |
| Unknown                                                | 2        | 0.78%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s              | 1        | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s              | 1        | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 0.39%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s           | 1        | 0.39%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s           | 1        | 0.39%   |
| Unknown RAM Module 8192MB DIMM DDR 1333MT/s            | 1        | 0.39%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s              | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 1        | 0.39%   |
| Unknown RAM Module 4096MB DIMM SDRAM                   | 1        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 79       | 42.02%  |
| DDR3    | 62       | 32.98%  |
| SDRAM   | 16       | 8.51%   |
| DDR2    | 14       | 7.45%   |
| Unknown | 8        | 4.26%   |
| DDR     | 5        | 2.66%   |
| DDR5    | 2        | 1.06%   |
| LPDDR4  | 1        | 0.53%   |
| DRAM    | 1        | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 174      | 95.6%   |
| SODIMM       | 7        | 3.85%   |
| Row Of Chips | 1        | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 68       | 31.63%  |
| 4096  | 48       | 22.33%  |
| 2048  | 43       | 20%     |
| 16384 | 30       | 13.95%  |
| 32768 | 18       | 8.37%   |
| 1024  | 7        | 3.26%   |
| 512   | 1        | 0.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 40       | 18.69%  |
| 1333    | 29       | 13.55%  |
| 3600    | 24       | 11.21%  |
| 3200    | 14       | 6.54%   |
| Unknown | 13       | 6.07%   |
| 2400    | 12       | 5.61%   |
| 2133    | 8        | 3.74%   |
| 800     | 8        | 3.74%   |
| 3000    | 7        | 3.27%   |
| 3733    | 6        | 2.8%    |
| 2666    | 5        | 2.34%   |
| 1867    | 5        | 2.34%   |
| 3800    | 4        | 1.87%   |
| 2667    | 4        | 1.87%   |
| 667     | 4        | 1.87%   |
| 3066    | 3        | 1.4%    |
| 1866    | 3        | 1.4%    |
| 1800    | 3        | 1.4%    |
| 3400    | 2        | 0.93%   |
| 1334    | 2        | 0.93%   |
| 533     | 2        | 0.93%   |
| 400     | 2        | 0.93%   |
| 333     | 2        | 0.93%   |
| 5600    | 1        | 0.47%   |
| 5200    | 1        | 0.47%   |
| 4800    | 1        | 0.47%   |
| 3666    | 1        | 0.47%   |
| 3500    | 1        | 0.47%   |
| 3467    | 1        | 0.47%   |
| 3333    | 1        | 0.47%   |
| 3100    | 1        | 0.47%   |
| 2800    | 1        | 0.47%   |
| 1400    | 1        | 0.47%   |
| 1066    | 1        | 0.47%   |
| 200     | 1        | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 6        | 30%     |
| Seiko Epson         | 3        | 15%     |
| Samsung Electronics | 3        | 15%     |
| Ricoh               | 2        | 10%     |
| iDPRT               | 2        | 10%     |
| Prolific Technology | 1        | 5%      |
| Philips (or NXP)    | 1        | 5%      |
| Canon               | 1        | 5%      |
| Brother Industries  | 1        | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Seiko Epson L120 Series                                | 2        | 10%     |
| iDPRT SP410                                            | 2        | 10%     |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1        | 5%      |
| Samsung SCX-3400 Series                                | 1        | 5%      |
| Samsung ML-2010P Mono Laser Printer                    | 1        | 5%      |
| Samsung Composite Device                               | 1        | 5%      |
| Ricoh Printing Support                                 | 1        | 5%      |
| Ricoh Aficio SP 3510DN                                 | 1        | 5%      |
| Prolific PL2305 Parallel Port                          | 1        | 5%      |
| Philips (or NXP) USB Printer                           | 1        | 5%      |
| HP Smart Tank 510 series                               | 1        | 5%      |
| HP LaserJet CP 1025                                    | 1        | 5%      |
| HP LaserJet 1020                                       | 1        | 5%      |
| HP HP Laser 107w                                       | 1        | 5%      |
| HP DeskJet 5810 series                                 | 1        | 5%      |
| HP Deskjet 2540 series                                 | 1        | 5%      |
| Canon G3000 series                                     | 1        | 5%      |
| Brother DCP-T710W                                      | 1        | 5%      |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 20       | 24.39%  |
| KYE Systems (Mouse Systems)   | 10       | 12.2%   |
| Microdia                      | 9        | 10.98%  |
| Chicony Electronics           | 6        | 7.32%   |
| Generalplus Technology        | 5        | 6.1%    |
| Microsoft                     | 4        | 4.88%   |
| Cubeternet                    | 4        | 4.88%   |
| Huawei Technologies           | 3        | 3.66%   |
| GEMBIRD                       | 3        | 3.66%   |
| Sunplus Innovation Technology | 2        | 2.44%   |
| Realtek Semiconductor         | 2        | 2.44%   |
| Arkmicro Technologies         | 2        | 2.44%   |
| WaveRider Communications      | 1        | 1.22%   |
| Unknown                       | 1        | 1.22%   |
| Trust                         | 1        | 1.22%   |
| Sony                          | 1        | 1.22%   |
| Samsung Electronics           | 1        | 1.22%   |
| Pixart Imaging                | 1        | 1.22%   |
| OmniVision Technologies       | 1        | 1.22%   |
| Minton Optic Industry         | 1        | 1.22%   |
| Hewlett-Packard               | 1        | 1.22%   |
| Acer                          | 1        | 1.22%   |
| 2M UVC CAMERA                 | 1        | 1.22%   |
| Unknown                       | 1        | 1.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                  | 6        | 7.32%   |
| Logitech HD Webcam C525                                      | 5        | 6.1%    |
| Microdia Integrated Camera                                   | 4        | 4.88%   |
| Generalplus GENERAL WEBCAM                                   | 4        | 4.88%   |
| KYE Systems (Mouse Systems) FaceCam 1000X                    | 3        | 3.66%   |
| Huawei HiCamera                                              | 3        | 3.66%   |
| Cubeternet GL-UPC822 UVC WebCam                              | 3        | 3.66%   |
| Chicony HP High Definition 1MP Webcam                        | 3        | 3.66%   |
| Sunplus Full HD webcam                                       | 2        | 2.44%   |
| Microdia USB 2.0 Camera                                      | 2        | 2.44%   |
| Logitech Webcam C930e                                        | 2        | 2.44%   |
| Logitech Webcam C170                                         | 2        | 2.44%   |
| GEMBIRD USB2.0 PC CAMERA                                     | 2        | 2.44%   |
| WaveRider USB 2.0 Camera                                     | 1        | 1.22%   |
| Unknown HD camera                                            | 1        | 1.22%   |
| Trust Trust Full HD Webcam                                   | 1        | 1.22%   |
| Sony CEVCECM                                                 | 1        | 1.22%   |
| Samsung Galaxy series, misc. (MTP mode)                      | 1        | 1.22%   |
| Realtek NexiGo N660P FHD Webcam                              | 1        | 1.22%   |
| Realtek FULL HD 1080P Webcam                                 | 1        | 1.22%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                         | 1        | 1.22%   |
| OmniVision Monitor Webcam                                    | 1        | 1.22%   |
| Minton Optic Industry S-Cam F5/D-Link DSC-350 Digital Camera | 1        | 1.22%   |
| Microsoft MicrosoftÂ LifeCam Studio                         | 1        | 1.22%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks          | 1        | 1.22%   |
| Microsoft LifeCam HD-3000                                    | 1        | 1.22%   |
| Microsoft LifeCam Cinema                                     | 1        | 1.22%   |
| Microdia Webcam Vitade AF                                    | 1        | 1.22%   |
| Microdia Sonix USB 2.0 Camera                                | 1        | 1.22%   |
| Microdia Camera                                              | 1        | 1.22%   |
| Logitech Webcam C270                                         | 1        | 1.22%   |
| Logitech HD Webcam C615                                      | 1        | 1.22%   |
| Logitech C922 Pro Stream Webcam                              | 1        | 1.22%   |
| Logitech C505 HD Webcam                                      | 1        | 1.22%   |
| Logitech BRIO Ultra HD Webcam                                | 1        | 1.22%   |
| KYE Systems (Mouse Systems) Genius Webcam                    | 1        | 1.22%   |
| KYE Systems (Mouse Systems) Genius iLook 1321 V2             | 1        | 1.22%   |
| KYE Systems (Mouse Systems) FaceCam 320X                     | 1        | 1.22%   |
| KYE Systems (Mouse Systems) FaceCam 310                      | 1        | 1.22%   |
| KYE Systems (Mouse Systems) FaceCam 2020                     | 1        | 1.22%   |

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
| 0     | 317      | 83.64%  |
| 1     | 54       | 14.25%  |
| 2     | 6        | 1.58%   |
| 4     | 1        | 0.26%   |
| 3     | 1        | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 29       | 41.43%  |
| Net/wireless             | 22       | 31.43%  |
| Communication controller | 7        | 10%     |
| Multimedia controller    | 3        | 4.29%   |
| Unassigned class         | 2        | 2.86%   |
| Storage/raid             | 2        | 2.86%   |
| Network                  | 2        | 2.86%   |
| Sound                    | 1        | 1.43%   |
| Card reader              | 1        | 1.43%   |
| Camera                   | 1        | 1.43%   |

