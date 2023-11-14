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

Total: 3068

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Samsung       | DT1234567890 SEC_SW_REVI... | [4ef314d383](https://linux-hardware.org/?probe=4ef314d383) | Nov 06, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | [6c8bb1840e](https://linux-hardware.org/?probe=6c8bb1840e) | Nov 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [38b95c0462](https://linux-hardware.org/?probe=38b95c0462) | Nov 05, 2023 |
| HP            | 1497                        | [734abf0595](https://linux-hardware.org/?probe=734abf0595) | Nov 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [9d8a12d929](https://linux-hardware.org/?probe=9d8a12d929) | Nov 05, 2023 |
| Gigabyte      | M5NM1AI-GB                  | [99e2275a93](https://linux-hardware.org/?probe=99e2275a93) | Nov 05, 2023 |
| Unknown       | Unknown                     | [dbd2e07499](https://linux-hardware.org/?probe=dbd2e07499) | Nov 05, 2023 |
| Unknown       | Unknown                     | [e98e6bb977](https://linux-hardware.org/?probe=e98e6bb977) | Nov 05, 2023 |
| Toshiba       | STI 001359                  | [ebf464dbb3](https://linux-hardware.org/?probe=ebf464dbb3) | Nov 04, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [239e99c725](https://linux-hardware.org/?probe=239e99c725) | Nov 03, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [c5e282cbad](https://linux-hardware.org/?probe=c5e282cbad) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | [bc8414b164](https://linux-hardware.org/?probe=bc8414b164) | Nov 01, 2023 |
| Gigabyte      | H510M H                     | [6db0212093](https://linux-hardware.org/?probe=6db0212093) | Nov 01, 2023 |
| Lenovo        | MAHOBAY                     | [319e545ba5](https://linux-hardware.org/?probe=319e545ba5) | Oct 31, 2023 |
| MSI           | A320M PRO-M2 V2             | [3b667e2123](https://linux-hardware.org/?probe=3b667e2123) | Oct 31, 2023 |
| Pegatron      | EVANS                       | [3ea2a80843](https://linux-hardware.org/?probe=3ea2a80843) | Oct 31, 2023 |
| Pegatron      | EVANS                       | [52c3eeea68](https://linux-hardware.org/?probe=52c3eeea68) | Oct 31, 2023 |
| HP            | 21F5 0A                     | [097ce56daf](https://linux-hardware.org/?probe=097ce56daf) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [c447277c0b](https://linux-hardware.org/?probe=c447277c0b) | Oct 30, 2023 |
| HP            | 1998                        | [2182b05a45](https://linux-hardware.org/?probe=2182b05a45) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [28f261fb9a](https://linux-hardware.org/?probe=28f261fb9a) | Oct 29, 2023 |
| MSI           | Z370M MORTAR                | [0af3708cd3](https://linux-hardware.org/?probe=0af3708cd3) | Oct 29, 2023 |
| HP            | 18E4                        | [b192ce4f35](https://linux-hardware.org/?probe=b192ce4f35) | Oct 28, 2023 |
| Dell          | 06X1TJ A00                  | [c2bc73c67b](https://linux-hardware.org/?probe=c2bc73c67b) | Oct 28, 2023 |
| ASUSTek       | P8B75-M                     | [b9830b7f02](https://linux-hardware.org/?probe=b9830b7f02) | Oct 28, 2023 |
| MSI           | Boston                      | [66f7505c8b](https://linux-hardware.org/?probe=66f7505c8b) | Oct 27, 2023 |
| HP            | 2215                        | [01fd79c4fe](https://linux-hardware.org/?probe=01fd79c4fe) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [463b5f73b5](https://linux-hardware.org/?probe=463b5f73b5) | Oct 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [67021475e9](https://linux-hardware.org/?probe=67021475e9) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | [ec0dcdaa76](https://linux-hardware.org/?probe=ec0dcdaa76) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | [4f4d354524](https://linux-hardware.org/?probe=4f4d354524) | Oct 26, 2023 |
| Intel         | H61                         | [cb396f193e](https://linux-hardware.org/?probe=cb396f193e) | Oct 26, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [ca4ce5575c](https://linux-hardware.org/?probe=ca4ce5575c) | Oct 26, 2023 |
| LORD ELECT... | Guso G4x + ICH7 Series M... | [c6f81cf996](https://linux-hardware.org/?probe=c6f81cf996) | Oct 25, 2023 |
| ASUSTek       | P8Z77-V LX                  | [6f9c14dc54](https://linux-hardware.org/?probe=6f9c14dc54) | Oct 24, 2023 |
| Gigabyte      | B450 AORUS M                | [706967e8e6](https://linux-hardware.org/?probe=706967e8e6) | Oct 24, 2023 |
| Gigabyte      | B85M-D3V Plus               | [845b1f10ef](https://linux-hardware.org/?probe=845b1f10ef) | Oct 24, 2023 |
| Dell          | 0RCPW3 A03                  | [a461b9f3e7](https://linux-hardware.org/?probe=a461b9f3e7) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | [905555c7d5](https://linux-hardware.org/?probe=905555c7d5) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | [5f6d67d67e](https://linux-hardware.org/?probe=5f6d67d67e) | Oct 23, 2023 |
| ASRock        | AB350 Pro4                  | [961b658ac5](https://linux-hardware.org/?probe=961b658ac5) | Oct 23, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6f89b3f8ad](https://linux-hardware.org/?probe=6f89b3f8ad) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | [ff9e1d6c16](https://linux-hardware.org/?probe=ff9e1d6c16) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | [9999b4b89a](https://linux-hardware.org/?probe=9999b4b89a) | Oct 22, 2023 |
| ASUSTek       | SABERTOOTH P67              | [5536078e9f](https://linux-hardware.org/?probe=5536078e9f) | Oct 21, 2023 |
| ASRock        | B450 Pro4                   | [d8b8f7bafe](https://linux-hardware.org/?probe=d8b8f7bafe) | Oct 20, 2023 |
| Lenovo        | SHARKBAY NOK                | [cb8d8311e7](https://linux-hardware.org/?probe=cb8d8311e7) | Oct 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [af96c09a64](https://linux-hardware.org/?probe=af96c09a64) | Oct 19, 2023 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [77079711d3](https://linux-hardware.org/?probe=77079711d3) | Oct 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7fed113f9b](https://linux-hardware.org/?probe=7fed113f9b) | Oct 19, 2023 |
| EPSON DIRE... | AT992E                      | [bdc9d825d8](https://linux-hardware.org/?probe=bdc9d825d8) | Oct 18, 2023 |
| EPSON DIRE... | AT992E                      | [ec5284109e](https://linux-hardware.org/?probe=ec5284109e) | Oct 18, 2023 |
| Unknown       | Unknown                     | [03cf657f5a](https://linux-hardware.org/?probe=03cf657f5a) | Oct 17, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [16a117accb](https://linux-hardware.org/?probe=16a117accb) | Oct 15, 2023 |
| ASUSTek       | H61M-K                      | [d43a466e59](https://linux-hardware.org/?probe=d43a466e59) | Oct 14, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [f4e7334b7e](https://linux-hardware.org/?probe=f4e7334b7e) | Oct 14, 2023 |
| ASUSTek       | P7H55-M LX                  | [17d1931208](https://linux-hardware.org/?probe=17d1931208) | Oct 13, 2023 |
| MSI           | B85M-E45                    | [6ad9d3ff3c](https://linux-hardware.org/?probe=6ad9d3ff3c) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [ffd832c09d](https://linux-hardware.org/?probe=ffd832c09d) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [c70591ee60](https://linux-hardware.org/?probe=c70591ee60) | Oct 12, 2023 |
| Dell          | 0NDYHG A01                  | [02414ff1af](https://linux-hardware.org/?probe=02414ff1af) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | [cc50dc0894](https://linux-hardware.org/?probe=cc50dc0894) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | [754748eac6](https://linux-hardware.org/?probe=754748eac6) | Oct 11, 2023 |
| Dell          | 0XHGV1 A00                  | [adda7a23c2](https://linux-hardware.org/?probe=adda7a23c2) | Oct 11, 2023 |
| AMI           | Intel                       | [1615dc16ba](https://linux-hardware.org/?probe=1615dc16ba) | Oct 10, 2023 |
| Lenovo        | Tiger Hill                  | [cdd9f65bf5](https://linux-hardware.org/?probe=cdd9f65bf5) | Oct 10, 2023 |
| Gigabyte      | H55M-USB3                   | [c4ae24b408](https://linux-hardware.org/?probe=c4ae24b408) | Oct 10, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | [d97f4b5e6f](https://linux-hardware.org/?probe=d97f4b5e6f) | Oct 09, 2023 |
| Unknown       | Unknown                     | [1eeecb8823](https://linux-hardware.org/?probe=1eeecb8823) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [067260a51f](https://linux-hardware.org/?probe=067260a51f) | Oct 08, 2023 |
| Shuttle       | FS110                       | [cd7c40ed57](https://linux-hardware.org/?probe=cd7c40ed57) | Oct 08, 2023 |
| MSI           | G41M-P33 Combo              | [b82e5d0718](https://linux-hardware.org/?probe=b82e5d0718) | Oct 07, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [f347154767](https://linux-hardware.org/?probe=f347154767) | Oct 07, 2023 |
| Pegatron      | EVANS                       | [f798f24c90](https://linux-hardware.org/?probe=f798f24c90) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | [299eee42c7](https://linux-hardware.org/?probe=299eee42c7) | Oct 07, 2023 |
| Intel         | X99                         | [9bc14ff597](https://linux-hardware.org/?probe=9bc14ff597) | Oct 06, 2023 |
| Gigabyte      | H510M H                     | [9be367f445](https://linux-hardware.org/?probe=9be367f445) | Oct 06, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [ff815f228b](https://linux-hardware.org/?probe=ff815f228b) | Oct 05, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [a6668a2378](https://linux-hardware.org/?probe=a6668a2378) | Oct 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [de22cbed3e](https://linux-hardware.org/?probe=de22cbed3e) | Oct 04, 2023 |
| Dell          | 0RW199                      | [f829184aa0](https://linux-hardware.org/?probe=f829184aa0) | Oct 04, 2023 |
| Lenovo        | Tiger Hill                  | [4a3ef3e12f](https://linux-hardware.org/?probe=4a3ef3e12f) | Oct 03, 2023 |
| Pegatron      | EVANS                       | [3f2a4fe53e](https://linux-hardware.org/?probe=3f2a4fe53e) | Oct 03, 2023 |
| Gigabyte      | Z270-HD3-CF                 | [c23994e74a](https://linux-hardware.org/?probe=c23994e74a) | Oct 02, 2023 |
| MSI           | B85M-E45                    | [12fa4b4da3](https://linux-hardware.org/?probe=12fa4b4da3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | [2c6f35e1d3](https://linux-hardware.org/?probe=2c6f35e1d3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | [ded620f59b](https://linux-hardware.org/?probe=ded620f59b) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [5698c85faa](https://linux-hardware.org/?probe=5698c85faa) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [056bfb8474](https://linux-hardware.org/?probe=056bfb8474) | Oct 01, 2023 |
| Intel         | X79M-S                      | [dfa1322112](https://linux-hardware.org/?probe=dfa1322112) | Oct 01, 2023 |
| MSI           | B75MA-E33                   | [8d558a64e8](https://linux-hardware.org/?probe=8d558a64e8) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [e0cdb74f25](https://linux-hardware.org/?probe=e0cdb74f25) | Oct 01, 2023 |
| Acer          | Predator G3610              | [cddfa514ba](https://linux-hardware.org/?probe=cddfa514ba) | Sep 30, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [c93af00811](https://linux-hardware.org/?probe=c93af00811) | Sep 30, 2023 |
| MP            | MS-7848                     | [63d5662351](https://linux-hardware.org/?probe=63d5662351) | Sep 30, 2023 |
| ASUSTek       | P8Z77-V LX                  | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| Gigabyte      | 970A-DS3P                   | [145f7eccd3](https://linux-hardware.org/?probe=145f7eccd3) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| MSI           | A320M-A PRO MAX             | [4aa521a31f](https://linux-hardware.org/?probe=4aa521a31f) | Sep 29, 2023 |
| HP            | 2B35                        | [2f63f14724](https://linux-hardware.org/?probe=2f63f14724) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ce3a9f8960](https://linux-hardware.org/?probe=ce3a9f8960) | Sep 28, 2023 |
| MSI           | A320M-A PRO MAX             | [f6c6bfc3fe](https://linux-hardware.org/?probe=f6c6bfc3fe) | Sep 27, 2023 |
| Intel         | X79G V2.x                   | [3d001a09ab](https://linux-hardware.org/?probe=3d001a09ab) | Sep 27, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [811818acb8](https://linux-hardware.org/?probe=811818acb8) | Sep 26, 2023 |
| Dell          | 0NW6H5 A00                  | [e7e87a1269](https://linux-hardware.org/?probe=e7e87a1269) | Sep 26, 2023 |
| Dell          | 0Y5DDC A00                  | [29feb62e32](https://linux-hardware.org/?probe=29feb62e32) | Sep 25, 2023 |
| Dell          | 0D28YY A01                  | [7c901ae7fd](https://linux-hardware.org/?probe=7c901ae7fd) | Sep 25, 2023 |
| Dell          | 0HN7XN A01                  | [fd3ce44501](https://linux-hardware.org/?probe=fd3ce44501) | Sep 23, 2023 |
| Unknown       | Unknown                     | [e2c17f3a64](https://linux-hardware.org/?probe=e2c17f3a64) | Sep 23, 2023 |
| Intel         | DB85FL AAG89861-201         | [58b289a69d](https://linux-hardware.org/?probe=58b289a69d) | Sep 23, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [e513362f71](https://linux-hardware.org/?probe=e513362f71) | Sep 22, 2023 |
| ASUSTek       | PRIME B460M-A               | [7ecfb9c56f](https://linux-hardware.org/?probe=7ecfb9c56f) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [47e5429752](https://linux-hardware.org/?probe=47e5429752) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [a35f78cead](https://linux-hardware.org/?probe=a35f78cead) | Sep 21, 2023 |
| AZW           | MINI S 10                   | [e393d95960](https://linux-hardware.org/?probe=e393d95960) | Sep 21, 2023 |
| Gigabyte      | GA-870A-UD3                 | [e57a830f9c](https://linux-hardware.org/?probe=e57a830f9c) | Sep 21, 2023 |
| Dell          | 0F3KHR A00                  | [dd7f2cf2b2](https://linux-hardware.org/?probe=dd7f2cf2b2) | Sep 20, 2023 |
| Lenovo        | H320 10044                  | [bf4ffce3e9](https://linux-hardware.org/?probe=bf4ffce3e9) | Sep 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [776633dd59](https://linux-hardware.org/?probe=776633dd59) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | [fcdaf47870](https://linux-hardware.org/?probe=fcdaf47870) | Sep 20, 2023 |
| Unknown       | Unknown                     | [e4dc880c6f](https://linux-hardware.org/?probe=e4dc880c6f) | Sep 20, 2023 |
| Dell          | 0RW199                      | [2857c6ada1](https://linux-hardware.org/?probe=2857c6ada1) | Sep 20, 2023 |
| Gigabyte      | Z790 UD AC                  | [83af285806](https://linux-hardware.org/?probe=83af285806) | Sep 20, 2023 |
| Biostar       | H61MLC                      | [154ead8447](https://linux-hardware.org/?probe=154ead8447) | Sep 19, 2023 |
| ASRock        | AB350 Pro4                  | [f45c7732e3](https://linux-hardware.org/?probe=f45c7732e3) | Sep 19, 2023 |
| AZW           | GTR V21                     | [5066e153f8](https://linux-hardware.org/?probe=5066e153f8) | Sep 19, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [202375fbb7](https://linux-hardware.org/?probe=202375fbb7) | Sep 18, 2023 |
| HP            | 3047h                       | [a955e9b6c6](https://linux-hardware.org/?probe=a955e9b6c6) | Sep 17, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [9e7069cdc3](https://linux-hardware.org/?probe=9e7069cdc3) | Sep 17, 2023 |
| Dell          | 0C27VV A02                  | [08ed0347db](https://linux-hardware.org/?probe=08ed0347db) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [d4d891ca35](https://linux-hardware.org/?probe=d4d891ca35) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | [b42ad40603](https://linux-hardware.org/?probe=b42ad40603) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | [3a230dc10f](https://linux-hardware.org/?probe=3a230dc10f) | Sep 16, 2023 |
| Acer          | Aspire XC-330               | [8913a6c47f](https://linux-hardware.org/?probe=8913a6c47f) | Sep 16, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [2fa5c8bb34](https://linux-hardware.org/?probe=2fa5c8bb34) | Sep 16, 2023 |
| MSI           | B550-A PRO                  | [83cb90361c](https://linux-hardware.org/?probe=83cb90361c) | Sep 14, 2023 |
| MSI           | Z170A-G45 GAMING            | [40aee3739e](https://linux-hardware.org/?probe=40aee3739e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | [9bbec30b2f](https://linux-hardware.org/?probe=9bbec30b2f) | Sep 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [3cba209625](https://linux-hardware.org/?probe=3cba209625) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [4dcd4e8234](https://linux-hardware.org/?probe=4dcd4e8234) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [cbfa4c2641](https://linux-hardware.org/?probe=cbfa4c2641) | Sep 13, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [b94c2a0420](https://linux-hardware.org/?probe=b94c2a0420) | Sep 13, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | [e4f73d159c](https://linux-hardware.org/?probe=e4f73d159c) | Sep 12, 2023 |
| Gigabyte      | B85M-HD3                    | [8ddbf6665f](https://linux-hardware.org/?probe=8ddbf6665f) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [9fc04871b0](https://linux-hardware.org/?probe=9fc04871b0) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [a80cffbabe](https://linux-hardware.org/?probe=a80cffbabe) | Sep 11, 2023 |
| Dell          | 0HY9JP A02                  | [5907e59551](https://linux-hardware.org/?probe=5907e59551) | Sep 11, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | [c57a3a012d](https://linux-hardware.org/?probe=c57a3a012d) | Sep 11, 2023 |
| ASUSTek       | PRIME H370-A                | [c757d0e2c3](https://linux-hardware.org/?probe=c757d0e2c3) | Sep 11, 2023 |
| ASUSTek       | CG8270                      | [a8db1b43ce](https://linux-hardware.org/?probe=a8db1b43ce) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | [26b9818094](https://linux-hardware.org/?probe=26b9818094) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | [6f66e35ec3](https://linux-hardware.org/?probe=6f66e35ec3) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | [9306917366](https://linux-hardware.org/?probe=9306917366) | Sep 09, 2023 |
| HP            | 8299                        | [df4048bcc4](https://linux-hardware.org/?probe=df4048bcc4) | Sep 08, 2023 |
| ASUSTek       | P5KPL-VM                    | [97d9faccab](https://linux-hardware.org/?probe=97d9faccab) | Sep 07, 2023 |
| ASUSTek       | P5KPL-VM                    | [3112302ff6](https://linux-hardware.org/?probe=3112302ff6) | Sep 07, 2023 |
| Acer          | Aspire X1470                | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| ASUSTek       | SABERTOOTH P67              | [002bdcd34d](https://linux-hardware.org/?probe=002bdcd34d) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| Dell          | 02YYK5 A01                  | [6bb77310bf](https://linux-hardware.org/?probe=6bb77310bf) | Sep 06, 2023 |
| Pegatron      | IPXSB-H61                   | [415ba1cfc1](https://linux-hardware.org/?probe=415ba1cfc1) | Sep 06, 2023 |
| Dell          | 0F3KHR A00                  | [53bfbec77e](https://linux-hardware.org/?probe=53bfbec77e) | Sep 06, 2023 |
| Gigabyte      | 970A-DS3P                   | [3227a8a6bc](https://linux-hardware.org/?probe=3227a8a6bc) | Sep 06, 2023 |
| Alienware     | 0446JC A01                  | [d0c3088707](https://linux-hardware.org/?probe=d0c3088707) | Sep 06, 2023 |
| HP            | 0B54h D                     | [6fc93ef4ee](https://linux-hardware.org/?probe=6fc93ef4ee) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [f8ec276ea3](https://linux-hardware.org/?probe=f8ec276ea3) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | [788841792b](https://linux-hardware.org/?probe=788841792b) | Sep 04, 2023 |
| Inventec      | Z CLASS A02                 | [7f0254a775](https://linux-hardware.org/?probe=7f0254a775) | Sep 04, 2023 |
| Pegatron      | IPXSB-H61                   | [78a354984d](https://linux-hardware.org/?probe=78a354984d) | Sep 04, 2023 |
| Dell          | 0D28YY A01                  | [ae79e6a689](https://linux-hardware.org/?probe=ae79e6a689) | Sep 04, 2023 |
| Gigabyte      | Z97X-UD5H                   | [2c9b64c445](https://linux-hardware.org/?probe=2c9b64c445) | Sep 03, 2023 |
| Intel         | DB85FL AAG89861-201         | [9845368fc2](https://linux-hardware.org/?probe=9845368fc2) | Sep 03, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [eee58fd067](https://linux-hardware.org/?probe=eee58fd067) | Sep 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6215db2c5a](https://linux-hardware.org/?probe=6215db2c5a) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Intel         | X79M-S                      | [a6952c68e4](https://linux-hardware.org/?probe=a6952c68e4) | Sep 01, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [be8b002a45](https://linux-hardware.org/?probe=be8b002a45) | Aug 31, 2023 |
| Intel         | DB85FL AAG89861-201         | [035f2909a1](https://linux-hardware.org/?probe=035f2909a1) | Aug 30, 2023 |
| Lenovo        | SDK0E50510 WIN              | [d963970016](https://linux-hardware.org/?probe=d963970016) | Aug 30, 2023 |
| HP            | 8054                        | [f73271d96e](https://linux-hardware.org/?probe=f73271d96e) | Aug 30, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3fb03adafb](https://linux-hardware.org/?probe=3fb03adafb) | Aug 29, 2023 |
| Dell          | 0GY6Y8 A02                  | [fffbca3973](https://linux-hardware.org/?probe=fffbca3973) | Aug 28, 2023 |
| Intel         | H61                         | [9e5ed4db62](https://linux-hardware.org/?probe=9e5ed4db62) | Aug 28, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [929efec703](https://linux-hardware.org/?probe=929efec703) | Aug 27, 2023 |
| eMachines     | EL1352                      | [5f9258beb2](https://linux-hardware.org/?probe=5f9258beb2) | Aug 27, 2023 |
| GuoGuang      | IC2M1028N                   | [ffcd5b9fa5](https://linux-hardware.org/?probe=ffcd5b9fa5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| MSI           | Z87 MPOWER MAX              | [42d3a714ac](https://linux-hardware.org/?probe=42d3a714ac) | Aug 24, 2023 |
| AZW           | MINI S                      | [7712e558c5](https://linux-hardware.org/?probe=7712e558c5) | Aug 24, 2023 |
| AZW           | MINI S                      | [6296a4f71d](https://linux-hardware.org/?probe=6296a4f71d) | Aug 24, 2023 |
| HP            | 8299                        | [aa27bed4f1](https://linux-hardware.org/?probe=aa27bed4f1) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [82c63f13d1](https://linux-hardware.org/?probe=82c63f13d1) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [1aee954611](https://linux-hardware.org/?probe=1aee954611) | Aug 22, 2023 |
| Unknown       | Unknown                     | [9b52370ec1](https://linux-hardware.org/?probe=9b52370ec1) | Aug 22, 2023 |
| Unknown       | Unknown                     | [51e91dd03e](https://linux-hardware.org/?probe=51e91dd03e) | Aug 22, 2023 |
| Dell          | 0GY6Y8 A02                  | [409855b61b](https://linux-hardware.org/?probe=409855b61b) | Aug 21, 2023 |
| Dell          | 08NPPY A00                  | [7a206bdd57](https://linux-hardware.org/?probe=7a206bdd57) | Aug 21, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [2ac06099d8](https://linux-hardware.org/?probe=2ac06099d8) | Aug 19, 2023 |
| ASUSTek       | H97-PRO GAMER               | [f97c8a25c5](https://linux-hardware.org/?probe=f97c8a25c5) | Aug 19, 2023 |
| ASUSTek       | P5L-MX                      | [f06dbc1b8c](https://linux-hardware.org/?probe=f06dbc1b8c) | Aug 19, 2023 |
| HP            | 3047h                       | [91d9eaa1de](https://linux-hardware.org/?probe=91d9eaa1de) | Aug 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [d109b04177](https://linux-hardware.org/?probe=d109b04177) | Aug 19, 2023 |
| HP            | 3047h                       | [a4aa888c24](https://linux-hardware.org/?probe=a4aa888c24) | Aug 18, 2023 |
| HP            | 3032h                       | [34a300f540](https://linux-hardware.org/?probe=34a300f540) | Aug 17, 2023 |
| Intel         | X79M-S                      | [d79895d82c](https://linux-hardware.org/?probe=d79895d82c) | Aug 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [7c1a42d442](https://linux-hardware.org/?probe=7c1a42d442) | Aug 17, 2023 |
| ASUSTek       | B150M-C/BR                  | [78e12f014e](https://linux-hardware.org/?probe=78e12f014e) | Aug 17, 2023 |
| Dell          | 0M6C7G A00                  | [50731e7c54](https://linux-hardware.org/?probe=50731e7c54) | Aug 16, 2023 |
| ASRock        | 970 Pro3 R2.0               | [50b5957370](https://linux-hardware.org/?probe=50b5957370) | Aug 16, 2023 |
| HP            | 09CCh                       | [947fb1edcb](https://linux-hardware.org/?probe=947fb1edcb) | Aug 15, 2023 |
| Gigabyte      | H61M-DS2V                   | [a1dccbbd3f](https://linux-hardware.org/?probe=a1dccbbd3f) | Aug 15, 2023 |
| Biostar       | H410MH                      | [abe98ae584](https://linux-hardware.org/?probe=abe98ae584) | Aug 15, 2023 |
| Gigabyte      | H110M-H-CF                  | [bb4bf558dd](https://linux-hardware.org/?probe=bb4bf558dd) | Aug 15, 2023 |
| Dell          | 02YRK5 A02                  | [e79cdd0ba3](https://linux-hardware.org/?probe=e79cdd0ba3) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09f15784f](https://linux-hardware.org/?probe=f09f15784f) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | [dea6e2f8b8](https://linux-hardware.org/?probe=dea6e2f8b8) | Aug 13, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [7e47b7128b](https://linux-hardware.org/?probe=7e47b7128b) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | [1034423357](https://linux-hardware.org/?probe=1034423357) | Aug 13, 2023 |
| Biostar       | A770 A2+                    | [ff8bec8b75](https://linux-hardware.org/?probe=ff8bec8b75) | Aug 12, 2023 |
| MSI           | 2AE0                        | [b8a2a0eb5c](https://linux-hardware.org/?probe=b8a2a0eb5c) | Aug 12, 2023 |
| HP            | 09CCh                       | [15bfdf7213](https://linux-hardware.org/?probe=15bfdf7213) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | [d35bac0620](https://linux-hardware.org/?probe=d35bac0620) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | [fb7d0009fd](https://linux-hardware.org/?probe=fb7d0009fd) | Aug 12, 2023 |
| HP            | 3032h                       | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Intel         | DZ68BC AAG30742-401         | [9bf37df045](https://linux-hardware.org/?probe=9bf37df045) | Aug 10, 2023 |
| Dell          | 0WMJ54 A01                  | [6e9ca3c833](https://linux-hardware.org/?probe=6e9ca3c833) | Aug 09, 2023 |
| HP            | 3032h                       | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [2e30c62b25](https://linux-hardware.org/?probe=2e30c62b25) | Aug 08, 2023 |
| Intel         | X79M-S                      | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Gigabyte      | B450 AORUS M                | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| Pegatron      | IPMMB-MQ1                   | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [1af709c14e](https://linux-hardware.org/?probe=1af709c14e) | Aug 05, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3bc330734d](https://linux-hardware.org/?probe=3bc330734d) | Aug 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [5d998a099e](https://linux-hardware.org/?probe=5d998a099e) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [e57d71e056](https://linux-hardware.org/?probe=e57d71e056) | Aug 05, 2023 |
| Unknown       | Unknown                     | [8ee9cccace](https://linux-hardware.org/?probe=8ee9cccace) | Aug 05, 2023 |
| ASRock        | N68-VS3 UCC                 | [3793d876eb](https://linux-hardware.org/?probe=3793d876eb) | Aug 04, 2023 |
| Gigabyte      | B550M DS3H AC               | [f27f9b2a7f](https://linux-hardware.org/?probe=f27f9b2a7f) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | [8193f810ab](https://linux-hardware.org/?probe=8193f810ab) | Aug 03, 2023 |
| ASUSTek       | PRIME B450M-K II            | [35cf0fd859](https://linux-hardware.org/?probe=35cf0fd859) | Aug 03, 2023 |
| Intel         | X79M-S                      | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| HP            | 89B5 A                      | [cb6f36f32c](https://linux-hardware.org/?probe=cb6f36f32c) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| Unknown       | Unknown                     | [731a8b0e31](https://linux-hardware.org/?probe=731a8b0e31) | Aug 02, 2023 |
| ASUSTek       | P8H61-M LX                  | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| HP            | 1496                        | [24863488f0](https://linux-hardware.org/?probe=24863488f0) | Aug 01, 2023 |
| Dell          | 0HJ054                      | [85ceb83c22](https://linux-hardware.org/?probe=85ceb83c22) | Jul 31, 2023 |
| ASUSTek       | M4N68T-M LE                 | [90dce7a9cf](https://linux-hardware.org/?probe=90dce7a9cf) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| Gigabyte      | M68MT-S2                    | [b1125cd76c](https://linux-hardware.org/?probe=b1125cd76c) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| ASUSTek       | P7H55-M LX                  | [bc92202f16](https://linux-hardware.org/?probe=bc92202f16) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| MSI           | B75MA-E33                   | [310207e0fd](https://linux-hardware.org/?probe=310207e0fd) | Jul 29, 2023 |
| Pegatron      | BOWIE                       | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| HP            | 3397                        | [e61ccd6dbf](https://linux-hardware.org/?probe=e61ccd6dbf) | Jul 27, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [e7fdf45ff0](https://linux-hardware.org/?probe=e7fdf45ff0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [2f12124bed](https://linux-hardware.org/?probe=2f12124bed) | Jul 27, 2023 |
| MP            | MS-7848                     | [3dd9f22548](https://linux-hardware.org/?probe=3dd9f22548) | Jul 26, 2023 |
| Acer          | Elena                       | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [1b062f3c31](https://linux-hardware.org/?probe=1b062f3c31) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [bca4424b5d](https://linux-hardware.org/?probe=bca4424b5d) | Jul 26, 2023 |
| ASUSTek       | B250 MINING EXPERT          | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| Dell          | 088DT1 A01                  | [1355a4f2f4](https://linux-hardware.org/?probe=1355a4f2f4) | Jul 25, 2023 |
| HP            | 8350                        | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |
| Dell          | 0MN1TX A04                  | [4ff31f4185](https://linux-hardware.org/?probe=4ff31f4185) | Jul 22, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [b8cf03e7b7](https://linux-hardware.org/?probe=b8cf03e7b7) | Jul 22, 2023 |
| ASUSTek       | F1A55-M LX                  | [87b85c2e28](https://linux-hardware.org/?probe=87b85c2e28) | Jul 22, 2023 |
| ASRock        | B85M                        | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| HP            | 3048h                       | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| HP            | 3047h                       | [07de35877b](https://linux-hardware.org/?probe=07de35877b) | Jul 21, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [9afd0f1d0f](https://linux-hardware.org/?probe=9afd0f1d0f) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [35c4e6ad97](https://linux-hardware.org/?probe=35c4e6ad97) | Jul 20, 2023 |
| HP            | 8767 A                      | [d5275f1025](https://linux-hardware.org/?probe=d5275f1025) | Jul 20, 2023 |
| Dell          | 0F5C5X A00                  | [3832c8f626](https://linux-hardware.org/?probe=3832c8f626) | Jul 20, 2023 |
| Dell          | 0C27VV A02                  | [da1c963814](https://linux-hardware.org/?probe=da1c963814) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | [02008985ce](https://linux-hardware.org/?probe=02008985ce) | Jul 19, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [57b17e7ae1](https://linux-hardware.org/?probe=57b17e7ae1) | Jul 15, 2023 |
| Gigabyte      | Z370M AORUS Gaming-CF       | [64a0d52846](https://linux-hardware.org/?probe=64a0d52846) | Jul 15, 2023 |
| Gigabyte      | B450 AORUS M                | [2f5c2842c2](https://linux-hardware.org/?probe=2f5c2842c2) | Jul 14, 2023 |
| Dell          | 0FDY5C A00                  | [35399aae18](https://linux-hardware.org/?probe=35399aae18) | Jul 14, 2023 |
| Dell          | 0D441T A03                  | [622890c12a](https://linux-hardware.org/?probe=622890c12a) | Jul 14, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [b690698c10](https://linux-hardware.org/?probe=b690698c10) | Jul 12, 2023 |
| HP            | 8299                        | [763cebf303](https://linux-hardware.org/?probe=763cebf303) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7c6ad4407b](https://linux-hardware.org/?probe=7c6ad4407b) | Jul 11, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [c81c5855d4](https://linux-hardware.org/?probe=c81c5855d4) | Jul 11, 2023 |
| Acer          | EG31M R01-B1                | [dbc5e1d5db](https://linux-hardware.org/?probe=dbc5e1d5db) | Jul 11, 2023 |
| Acer          | EG31M R01-B1                | [12f533494b](https://linux-hardware.org/?probe=12f533494b) | Jul 11, 2023 |
| ASRock        | A320M-HDV R4.0              | [ab81f36697](https://linux-hardware.org/?probe=ab81f36697) | Jul 11, 2023 |
| Dell          | 09WH54 A00                  | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| ASRock        | B460M Pro4                  | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | [2ed1092e31](https://linux-hardware.org/?probe=2ed1092e31) | Jul 10, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [213c80bbee](https://linux-hardware.org/?probe=213c80bbee) | Jul 09, 2023 |
| ASUSTek       | PRIME B350M-A               | [be65f2aa45](https://linux-hardware.org/?probe=be65f2aa45) | Jul 08, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| Dell          | 0HN7XN A01                  | [24a4044173](https://linux-hardware.org/?probe=24a4044173) | Jul 06, 2023 |
| Gigabyte      | B75M-D3H                    | [8a9c93e501](https://linux-hardware.org/?probe=8a9c93e501) | Jul 06, 2023 |
| ASRock        | FP6D4-P1                    | [42b5bdcdd7](https://linux-hardware.org/?probe=42b5bdcdd7) | Jul 05, 2023 |
| Positivo      | POS-EIH61CE SIM             | [48b35c757d](https://linux-hardware.org/?probe=48b35c757d) | Jul 05, 2023 |
| Intel         | H55                         | [8f8ff68380](https://linux-hardware.org/?probe=8f8ff68380) | Jul 04, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [9bca67bb40](https://linux-hardware.org/?probe=9bca67bb40) | Jul 04, 2023 |
| HP            | 21F5 0A                     | [bc7304ba1c](https://linux-hardware.org/?probe=bc7304ba1c) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | [452fe27c46](https://linux-hardware.org/?probe=452fe27c46) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | [168d5b0b7b](https://linux-hardware.org/?probe=168d5b0b7b) | Jul 04, 2023 |
| Foxconn       | G41S/G41S-K                 | [21adb87fbd](https://linux-hardware.org/?probe=21adb87fbd) | Jul 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [7672f159bf](https://linux-hardware.org/?probe=7672f159bf) | Jul 03, 2023 |
| Dell          | 0GY6Y8 A02                  | [729dbec695](https://linux-hardware.org/?probe=729dbec695) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| MSI           | PRO Z690-A WIFI             | [2bc4b36c94](https://linux-hardware.org/?probe=2bc4b36c94) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [c787bf91c3](https://linux-hardware.org/?probe=c787bf91c3) | Jul 02, 2023 |
| Win Elemen... | M9                          | [2e5ea821f1](https://linux-hardware.org/?probe=2e5ea821f1) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [a4e29f77e5](https://linux-hardware.org/?probe=a4e29f77e5) | Jul 01, 2023 |
| MSI           | H61M-P31                    | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [0a35c3c750](https://linux-hardware.org/?probe=0a35c3c750) | Jun 27, 2023 |
| HP            | 8906 SMVB                   | [18ab778722](https://linux-hardware.org/?probe=18ab778722) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [85eeeb037b](https://linux-hardware.org/?probe=85eeeb037b) | Jun 26, 2023 |
| Gigabyte      | G31M-ES2L                   | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| Dell          | 00V62H A01                  | [23134d6c71](https://linux-hardware.org/?probe=23134d6c71) | Jun 24, 2023 |
| ASUSTek       | P5B                         | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| Dell          | 0G9322                      | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| Intel         | D34010WYK H14771-304        | [0d3af8114b](https://linux-hardware.org/?probe=0d3af8114b) | Jun 20, 2023 |
| AZW           | GTR V02                     | [f9bee18426](https://linux-hardware.org/?probe=f9bee18426) | Jun 19, 2023 |
| ASUSTek       | P5LD2                       | [7038963b77](https://linux-hardware.org/?probe=7038963b77) | Jun 18, 2023 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [707e7d9862](https://linux-hardware.org/?probe=707e7d9862) | Jun 17, 2023 |
| Pegatron      | BOWIE                       | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| ASRock        | B85M                        | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Dell          | 0KC9NP A01                  | [b00d413241](https://linux-hardware.org/?probe=b00d413241) | Jun 14, 2023 |
| Dell          | 0KC9NP A01                  | [1d487a1ed5](https://linux-hardware.org/?probe=1d487a1ed5) | Jun 14, 2023 |
| Dell          | 0WR7PY A02                  | [eab79964fb](https://linux-hardware.org/?probe=eab79964fb) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| ASUSTek       | P5B                         | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | [45696e1d1b](https://linux-hardware.org/?probe=45696e1d1b) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [9ea7188339](https://linux-hardware.org/?probe=9ea7188339) | Jun 11, 2023 |
| HP            | 8350                        | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| ASUSTek       | P5B                         | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| MP            | MS-7848                     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Nvidia        | MCP79                       | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| ASRock        | H81M-HDS                    | [e1ff6f4e2f](https://linux-hardware.org/?probe=e1ff6f4e2f) | Jun 08, 2023 |
| ASUSTek       | P5B                         | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [74cf1d0b63](https://linux-hardware.org/?probe=74cf1d0b63) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [88cbeea389](https://linux-hardware.org/?probe=88cbeea389) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [2ad7aefc45](https://linux-hardware.org/?probe=2ad7aefc45) | Jun 07, 2023 |
| HP            | 8350                        | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| Dell          | 0G9322                      | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| Nvidia        | MCP79                       | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [79f63dcf8e](https://linux-hardware.org/?probe=79f63dcf8e) | Jun 06, 2023 |
| ASUSTek       | CM1730,CM1830               | [2cc76d0cd9](https://linux-hardware.org/?probe=2cc76d0cd9) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | [7dc46d923e](https://linux-hardware.org/?probe=7dc46d923e) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [fb12198605](https://linux-hardware.org/?probe=fb12198605) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [d94442285c](https://linux-hardware.org/?probe=d94442285c) | Jun 05, 2023 |
| ASUSTek       | B75M-A                      | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| Dell          | 0G9322                      | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| Dell          | 0NW6H5 A00                  | [01387c3030](https://linux-hardware.org/?probe=01387c3030) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [20260fb3b3](https://linux-hardware.org/?probe=20260fb3b3) | Jun 03, 2023 |
| HP            | 339A                        | [bb4619f4eb](https://linux-hardware.org/?probe=bb4619f4eb) | Jun 02, 2023 |
| Gateway       | SX2851                      | [262ddffda9](https://linux-hardware.org/?probe=262ddffda9) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| ASRock        | ALiveDual-eSATA2            | [0f490d3b39](https://linux-hardware.org/?probe=0f490d3b39) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| MSI           | B450 TOMAHAWK               | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Acer          | Predator G3-605             | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | [be58596103](https://linux-hardware.org/?probe=be58596103) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | [0eedc4211a](https://linux-hardware.org/?probe=0eedc4211a) | May 27, 2023 |
| Dell          | 0G9322                      | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Dell          | 0G9322                      | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 21D0                        | [7f83859a91](https://linux-hardware.org/?probe=7f83859a91) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| HP            | 18E5                        | [23e2edb1fe](https://linux-hardware.org/?probe=23e2edb1fe) | May 26, 2023 |
| Dell          | 0K095G A02                  | [f11b8418c9](https://linux-hardware.org/?probe=f11b8418c9) | May 26, 2023 |
| HP            | 21D0                        | [8e52c2613c](https://linux-hardware.org/?probe=8e52c2613c) | May 26, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [61dc4c5620](https://linux-hardware.org/?probe=61dc4c5620) | May 25, 2023 |
| ECS           | H510H6-M2                   | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| Vorke         | V1 Plus                     | [81c0b82d6c](https://linux-hardware.org/?probe=81c0b82d6c) | May 24, 2023 |
| ECS           | H510H6-M2                   | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| HP            | 8906 SMVB                   | [ca3ed99a5c](https://linux-hardware.org/?probe=ca3ed99a5c) | May 24, 2023 |
| Pegatron      | 2AC2A                       | [f9e504a430](https://linux-hardware.org/?probe=f9e504a430) | May 24, 2023 |
| HP            | 21EF                        | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | H81M-E34                    | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| HP            | 21EF                        | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| ASRock        | H77M                        | [7f173e0b75](https://linux-hardware.org/?probe=7f173e0b75) | May 22, 2023 |
| HP            | 18E5                        | [d1bc34770d](https://linux-hardware.org/?probe=d1bc34770d) | May 22, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b6465d2950](https://linux-hardware.org/?probe=b6465d2950) | May 21, 2023 |
| Dell          | 02N3WF A01                  | [8d0096c040](https://linux-hardware.org/?probe=8d0096c040) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| Gigabyte      | X570 GAMING X               | [8a6ad6c590](https://linux-hardware.org/?probe=8a6ad6c590) | May 19, 2023 |
| Dell          | 0GDG8Y A00                  | [514fe06c9e](https://linux-hardware.org/?probe=514fe06c9e) | May 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [31568d83f7](https://linux-hardware.org/?probe=31568d83f7) | May 18, 2023 |
| Gigabyte      | H81M-DS2                    | [754dc9d1fc](https://linux-hardware.org/?probe=754dc9d1fc) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [ee37475637](https://linux-hardware.org/?probe=ee37475637) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [68406e2c40](https://linux-hardware.org/?probe=68406e2c40) | May 18, 2023 |
| Acer          | Revo 70                     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| HP            | 2B02                        | [a6bf09d51c](https://linux-hardware.org/?probe=a6bf09d51c) | May 17, 2023 |
| Pegatron      | Benicia                     | [e6ee1c66f6](https://linux-hardware.org/?probe=e6ee1c66f6) | May 17, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [d3c3cc9f96](https://linux-hardware.org/?probe=d3c3cc9f96) | May 15, 2023 |
| Intel         | Tiger Hill                  | [fdbe67045c](https://linux-hardware.org/?probe=fdbe67045c) | May 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [dd8c6c3811](https://linux-hardware.org/?probe=dd8c6c3811) | May 15, 2023 |
| HP            | 18E5                        | [7d5ceb9f5d](https://linux-hardware.org/?probe=7d5ceb9f5d) | May 15, 2023 |
| Gigabyte      | GA-970A-UD3                 | [24c81ddf59](https://linux-hardware.org/?probe=24c81ddf59) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| ASUSTek       | K8N-DRE                     | [395dc0cfb3](https://linux-hardware.org/?probe=395dc0cfb3) | May 13, 2023 |
| ASUSTek       | K8N-DRE                     | [f55a0c735f](https://linux-hardware.org/?probe=f55a0c735f) | May 13, 2023 |
| Vorke         | V1 Plus                     | [19f095fc02](https://linux-hardware.org/?probe=19f095fc02) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e844f3a6fe](https://linux-hardware.org/?probe=e844f3a6fe) | May 13, 2023 |
| Acer          | Predator G3-605             | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Gigabyte      | A520M DS3H                  | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| Acer          | Predator G3-605             | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| Gigabyte      | GA-970A-UD3                 | [080f1c13d8](https://linux-hardware.org/?probe=080f1c13d8) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e2c57c80fc](https://linux-hardware.org/?probe=e2c57c80fc) | May 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d041d35517](https://linux-hardware.org/?probe=d041d35517) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3ab5dcb5d](https://linux-hardware.org/?probe=d3ab5dcb5d) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Gigabyte      | Z77-DS3H                    | [c86f346e1d](https://linux-hardware.org/?probe=c86f346e1d) | May 12, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [719d80a236](https://linux-hardware.org/?probe=719d80a236) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [b25b524237](https://linux-hardware.org/?probe=b25b524237) | May 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [22778449cc](https://linux-hardware.org/?probe=22778449cc) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [ffd84ff48e](https://linux-hardware.org/?probe=ffd84ff48e) | May 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [abf6d2bf1d](https://linux-hardware.org/?probe=abf6d2bf1d) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d45b33c736](https://linux-hardware.org/?probe=d45b33c736) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| HP            | 339A                        | [8b646a0fa1](https://linux-hardware.org/?probe=8b646a0fa1) | May 07, 2023 |
| HP            | 339A                        | [e23aaae239](https://linux-hardware.org/?probe=e23aaae239) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| ASRockRack    | D1521D4I2                   | [136a9303c0](https://linux-hardware.org/?probe=136a9303c0) | May 06, 2023 |
| MSI           | MAG B550M BAZOOKA           | [7b0b45831c](https://linux-hardware.org/?probe=7b0b45831c) | May 06, 2023 |
| MSI           | X570-A PRO                  | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| MSI           | X570-A PRO                  | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d571b75547](https://linux-hardware.org/?probe=d571b75547) | May 05, 2023 |
| ASRock        | B550M-HDV                   | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| Unknown       | Unknown                     | [5b46ed614a](https://linux-hardware.org/?probe=5b46ed614a) | May 04, 2023 |
| ASUSTek       | P5N73-CM                    | [e64a3c2da5](https://linux-hardware.org/?probe=e64a3c2da5) | May 04, 2023 |
| Gigabyte      | Z590 VISION G               | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| ASRock        | H81M-HDS                    | [60e11bdf11](https://linux-hardware.org/?probe=60e11bdf11) | May 04, 2023 |
| Gigabyte      | MFLP5IP-00                  | [c9c14a6da2](https://linux-hardware.org/?probe=c9c14a6da2) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Dell          | 09WH54 A00                  | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3757c615f](https://linux-hardware.org/?probe=d3757c615f) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| ASRock        | G41M-GS                     | [0824a9c571](https://linux-hardware.org/?probe=0824a9c571) | May 01, 2023 |
| Intel         | H55                         | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| ASRock        | H61M-DGS                    | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| Dell          | 02YYK5 A01                  | [1a00a1321e](https://linux-hardware.org/?probe=1a00a1321e) | Apr 30, 2023 |
| MSI           | IONA                        | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| Unknown       | Unknown                     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Dell          | 08NPPY A00                  | [25bc3aa225](https://linux-hardware.org/?probe=25bc3aa225) | Apr 29, 2023 |
| Unknown       | Unknown                     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Pegatron      | IPM41-D3                    | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| Intel         | D34010WYK H14771-304        | [4fbbe6e603](https://linux-hardware.org/?probe=4fbbe6e603) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| HP            | 1632                        | [0355cb4e69](https://linux-hardware.org/?probe=0355cb4e69) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |
| eMachines     | MCP61PM-GM                  | [ff00693839](https://linux-hardware.org/?probe=ff00693839) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| ASUSTek       | P5Q                         | [57e3cfa7dc](https://linux-hardware.org/?probe=57e3cfa7dc) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| Gigabyte      | B650M DS3H                  | [3d07651a47](https://linux-hardware.org/?probe=3d07651a47) | Apr 24, 2023 |
| Dell          | 03NVJ6 A01                  | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Unknown       | G41                         | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [25ee911879](https://linux-hardware.org/?probe=25ee911879) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [468824c4d9](https://linux-hardware.org/?probe=468824c4d9) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [0cd5599131](https://linux-hardware.org/?probe=0cd5599131) | Apr 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| Dell          | 0F373D A00                  | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| Gigabyte      | B650M DS3H                  | [de196a2cfa](https://linux-hardware.org/?probe=de196a2cfa) | Apr 21, 2023 |
| ASUSTek       | H110M-R                     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| HP            | 2ADE                        | [1a3d108a58](https://linux-hardware.org/?probe=1a3d108a58) | Apr 20, 2023 |
| HP            | 8054                        | [0f2c12c877](https://linux-hardware.org/?probe=0f2c12c877) | Apr 20, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Dell          | 0WMJ54 A01                  | [2a7fe6d74b](https://linux-hardware.org/?probe=2a7fe6d74b) | Apr 18, 2023 |
| Dell          | 0WMJ54 A01                  | [be92b53515](https://linux-hardware.org/?probe=be92b53515) | Apr 18, 2023 |
| ASL           | BayTrail JHS773             | [3a5977ad04](https://linux-hardware.org/?probe=3a5977ad04) | Apr 18, 2023 |
| Dell          | 0T656F A02                  | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | [119560d8db](https://linux-hardware.org/?probe=119560d8db) | Apr 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [307e22b0d6](https://linux-hardware.org/?probe=307e22b0d6) | Apr 17, 2023 |
| MSI           | MEG X570 UNIFY              | [b2311e7cac](https://linux-hardware.org/?probe=b2311e7cac) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| ASRock        | H61M-DGS                    | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [c7568482a9](https://linux-hardware.org/?probe=c7568482a9) | Apr 15, 2023 |
| Intel         | H61                         | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| MSI           | B75MA-E33                   | [d50de3a52c](https://linux-hardware.org/?probe=d50de3a52c) | Apr 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| Biostar       | TZ75B                       | [c6720e2db2](https://linux-hardware.org/?probe=c6720e2db2) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [e9c2f8d5ba](https://linux-hardware.org/?probe=e9c2f8d5ba) | Apr 14, 2023 |
| Intel         | H61                         | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| ASRock        | B550 Steel Legend           | [9da868694f](https://linux-hardware.org/?probe=9da868694f) | Apr 14, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4267100894](https://linux-hardware.org/?probe=4267100894) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5e9f89e556](https://linux-hardware.org/?probe=5e9f89e556) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [d72e78c1b0](https://linux-hardware.org/?probe=d72e78c1b0) | Apr 13, 2023 |
| Gigabyte      | M68MT-S2                    | [ac4059b403](https://linux-hardware.org/?probe=ac4059b403) | Apr 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | [6f7e9a6bb2](https://linux-hardware.org/?probe=6f7e9a6bb2) | Apr 13, 2023 |
| ASUSTek       | B85M-G                      | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [82a946e356](https://linux-hardware.org/?probe=82a946e356) | Apr 12, 2023 |
| ASUSTek       | P8H67-M PRO                 | [1627e0654a](https://linux-hardware.org/?probe=1627e0654a) | Apr 11, 2023 |
| ASUSTek       | P8H67-M PRO                 | [57aa7d103d](https://linux-hardware.org/?probe=57aa7d103d) | Apr 11, 2023 |
| ASUSTek       | P5K                         | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| MSI           | B75MA-E33                   | [27e5e2df0d](https://linux-hardware.org/?probe=27e5e2df0d) | Apr 06, 2023 |
| Dell          | 0GY6Y8 A01                  | [ecba971f16](https://linux-hardware.org/?probe=ecba971f16) | Apr 06, 2023 |
| ASUSTek       | H87-PRO                     | [085dc66a77](https://linux-hardware.org/?probe=085dc66a77) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [68d14e873f](https://linux-hardware.org/?probe=68d14e873f) | Apr 05, 2023 |
| eMachines     | MCP61PM-GM                  | [dc35ec4564](https://linux-hardware.org/?probe=dc35ec4564) | Apr 04, 2023 |
| Gigabyte      | H410M S2 V3                 | [fdff0f112e](https://linux-hardware.org/?probe=fdff0f112e) | Apr 04, 2023 |
| Medion        | MS-7707                     | [c490d9dc74](https://linux-hardware.org/?probe=c490d9dc74) | Apr 04, 2023 |
| eMachines     | MCP61PM-GM                  | [59f9325843](https://linux-hardware.org/?probe=59f9325843) | Apr 03, 2023 |
| ASRock        | H61M-DGS                    | [e05fcde338](https://linux-hardware.org/?probe=e05fcde338) | Apr 03, 2023 |
| Acer          | Veriton X4610G              | [49b3c45306](https://linux-hardware.org/?probe=49b3c45306) | Apr 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ea4626fdcc](https://linux-hardware.org/?probe=ea4626fdcc) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [118effffda](https://linux-hardware.org/?probe=118effffda) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| HOUTER        | IPMIP-GS                    | [4ef0c7aaaa](https://linux-hardware.org/?probe=4ef0c7aaaa) | Apr 02, 2023 |
| Pegatron      | 2ACF                        | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| Acer          | Predator G3-605             | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| Dell          | 0K240Y A02                  | [ca6aacf14e](https://linux-hardware.org/?probe=ca6aacf14e) | Mar 31, 2023 |
| Dell          | 09M8Y8 A01                  | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | Benicia                     | [7332efabad](https://linux-hardware.org/?probe=7332efabad) | Mar 30, 2023 |
| HOUTER        | ORO-PC                      | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Gigabyte      | H310M H x.x                 | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| MSI           | B560M-A PRO                 | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [c97dbb0917](https://linux-hardware.org/?probe=c97dbb0917) | Mar 28, 2023 |
| Dell          | 06X1TJ A01                  | [7e99e3d73e](https://linux-hardware.org/?probe=7e99e3d73e) | Mar 28, 2023 |
| ASRock        | Z68 Pro3-M                  | [60f0809fbf](https://linux-hardware.org/?probe=60f0809fbf) | Mar 28, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [dcbcf69a04](https://linux-hardware.org/?probe=dcbcf69a04) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| Dell          | 0GU083 A00                  | [e577b0129c](https://linux-hardware.org/?probe=e577b0129c) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| AZW           | MINI S                      | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| Dell          | 0D28YY A01                  | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [e859e77bc7](https://linux-hardware.org/?probe=e859e77bc7) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [ce7e17cb45](https://linux-hardware.org/?probe=ce7e17cb45) | Mar 24, 2023 |
| ASRock        | X570 Steel Legend           | [05d4059f59](https://linux-hardware.org/?probe=05d4059f59) | Mar 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | [c83000783a](https://linux-hardware.org/?probe=c83000783a) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| Intel         | G41                         | [c9fccfc8c1](https://linux-hardware.org/?probe=c9fccfc8c1) | Mar 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d0b0015eb2](https://linux-hardware.org/?probe=d0b0015eb2) | Mar 22, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9409e4e133](https://linux-hardware.org/?probe=9409e4e133) | Mar 20, 2023 |
| Acer          | Revo RL80                   | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| MSI           | B75MA-E33                   | [cddf0b016f](https://linux-hardware.org/?probe=cddf0b016f) | Mar 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [75996f8bcf](https://linux-hardware.org/?probe=75996f8bcf) | Mar 19, 2023 |
| HP            | 158A                        | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| HP            | 2B01                        | [1a096f9b36](https://linux-hardware.org/?probe=1a096f9b36) | Mar 19, 2023 |
| MSI           | B75MA-E33                   | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [5f4a932bcd](https://linux-hardware.org/?probe=5f4a932bcd) | Mar 18, 2023 |
| HP            | 83E1                        | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| Dell          | 0D28YY A01                  | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| HP            | 158A                        | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [3388dd991a](https://linux-hardware.org/?probe=3388dd991a) | Mar 15, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [eb761f4a30](https://linux-hardware.org/?probe=eb761f4a30) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Gigabyte      | H55M-S2H                    | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| HP            | 83E1                        | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| Soncview      | G41D3C                      | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| Gigabyte      | H97M-D3H                    | [178af6e35b](https://linux-hardware.org/?probe=178af6e35b) | Mar 12, 2023 |
| HP            | 18E7                        | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| HP            | 09CCh                       | [e122b11e42](https://linux-hardware.org/?probe=e122b11e42) | Mar 12, 2023 |
| Dell          | 0GM819                      | [1db4004d05](https://linux-hardware.org/?probe=1db4004d05) | Mar 12, 2023 |
| Medion        | MS-7707                     | [a0621e0cd1](https://linux-hardware.org/?probe=a0621e0cd1) | Mar 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [f45a0d4c01](https://linux-hardware.org/?probe=f45a0d4c01) | Mar 12, 2023 |
| Medion        | MS-7707                     | [4c9432026b](https://linux-hardware.org/?probe=4c9432026b) | Mar 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [bd0c265909](https://linux-hardware.org/?probe=bd0c265909) | Mar 11, 2023 |
| Intel         | H61                         | [5650f6d211](https://linux-hardware.org/?probe=5650f6d211) | Mar 11, 2023 |
| Acer          | WG43M                       | [5858448536](https://linux-hardware.org/?probe=5858448536) | Mar 11, 2023 |
| Acer          | WG43M                       | [3d562885d0](https://linux-hardware.org/?probe=3d562885d0) | Mar 11, 2023 |
| HP            | 09CCh                       | [9421be2c59](https://linux-hardware.org/?probe=9421be2c59) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| ASUSTek       | H110M-R                     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Pegatron      | 2ACB                        | [1599d2a2ef](https://linux-hardware.org/?probe=1599d2a2ef) | Mar 09, 2023 |
| Unknown       | HX90                        | [21530c00a4](https://linux-hardware.org/?probe=21530c00a4) | Mar 09, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [8115c702cb](https://linux-hardware.org/?probe=8115c702cb) | Mar 09, 2023 |
| MSI           | B450 GAMING PLUS            | [5fd5c7db62](https://linux-hardware.org/?probe=5fd5c7db62) | Mar 09, 2023 |
| Dell          | 0T10XW A00                  | [fd255666fc](https://linux-hardware.org/?probe=fd255666fc) | Mar 08, 2023 |
| Gigabyte      | B450 GAMING X               | [6f7b473b62](https://linux-hardware.org/?probe=6f7b473b62) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [5f93500136](https://linux-hardware.org/?probe=5f93500136) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [fdba382132](https://linux-hardware.org/?probe=fdba382132) | Mar 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [00ddbf4ad1](https://linux-hardware.org/?probe=00ddbf4ad1) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX                     | [c7ccf3de7b](https://linux-hardware.org/?probe=c7ccf3de7b) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [aa987a6626](https://linux-hardware.org/?probe=aa987a6626) | Mar 07, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [83c569f727](https://linux-hardware.org/?probe=83c569f727) | Mar 06, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [ca3531a813](https://linux-hardware.org/?probe=ca3531a813) | Mar 06, 2023 |
| Dell          | 0JC474                      | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [7c9b56f288](https://linux-hardware.org/?probe=7c9b56f288) | Mar 05, 2023 |
| Gigabyte      | B450M DS3H V2               | [d1a55c59a3](https://linux-hardware.org/?probe=d1a55c59a3) | Mar 05, 2023 |
| Apple         | Mac-F221BEC8                | [f3c06b377f](https://linux-hardware.org/?probe=f3c06b377f) | Mar 04, 2023 |
| ASUSTek       | H81M-K                      | [05507dab01](https://linux-hardware.org/?probe=05507dab01) | Mar 04, 2023 |
| ASUSTek       | PRIME H410M-R               | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| ASRock        | Wolfdale1333-D667           | [7dd4939e64](https://linux-hardware.org/?probe=7dd4939e64) | Mar 03, 2023 |
| Unknown       | Rev.00                      | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| ASUSTek       | P7H55-M LX                  | [80e66c5eac](https://linux-hardware.org/?probe=80e66c5eac) | Mar 03, 2023 |
| ASUSTek       | P5QPL-AM                    | [52b68672fc](https://linux-hardware.org/?probe=52b68672fc) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [1e039a31d1](https://linux-hardware.org/?probe=1e039a31d1) | Mar 03, 2023 |
| HP            | 805D                        | [4638c85566](https://linux-hardware.org/?probe=4638c85566) | Mar 01, 2023 |
| ASUSTek       | SABERTOOTH P67              | [fa7df5da3b](https://linux-hardware.org/?probe=fa7df5da3b) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| Google        | Buddy                       | [ac3d9aaed0](https://linux-hardware.org/?probe=ac3d9aaed0) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [6c62bbbf3b](https://linux-hardware.org/?probe=6c62bbbf3b) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [2479c3c245](https://linux-hardware.org/?probe=2479c3c245) | Feb 27, 2023 |
| HP            | 1998                        | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [a21ea9613b](https://linux-hardware.org/?probe=a21ea9613b) | Feb 26, 2023 |
| MSI           | B75MA-E33                   | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | H81M-P33                    | [1bc1cedec6](https://linux-hardware.org/?probe=1bc1cedec6) | Feb 25, 2023 |
| ASUSTek       | PRIME B560M-A               | [7357439273](https://linux-hardware.org/?probe=7357439273) | Feb 25, 2023 |
| HP            | 2AF7                        | [a8eba0b0c4](https://linux-hardware.org/?probe=a8eba0b0c4) | Feb 25, 2023 |
| HP            | 2AF7                        | [3bf3afd1d5](https://linux-hardware.org/?probe=3bf3afd1d5) | Feb 25, 2023 |
| HP            | 2129                        | [5118eb06d4](https://linux-hardware.org/?probe=5118eb06d4) | Feb 24, 2023 |
| Dell          | 0HN7XN A01                  | [f283ae7cb2](https://linux-hardware.org/?probe=f283ae7cb2) | Feb 23, 2023 |
| ASUSTek       | P7H55-M/USB3                | [472721d72c](https://linux-hardware.org/?probe=472721d72c) | Feb 22, 2023 |
| HP            | 2129                        | [5a6b1e7169](https://linux-hardware.org/?probe=5a6b1e7169) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [e861797e74](https://linux-hardware.org/?probe=e861797e74) | Feb 21, 2023 |
| ASUSTek       | F2A55-M                     | [c9d150f24c](https://linux-hardware.org/?probe=c9d150f24c) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [40e2157901](https://linux-hardware.org/?probe=40e2157901) | Feb 21, 2023 |
| HP            | 1850                        | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| eMachines     | MCP61PM-GM                  | [aeafa2dbee](https://linux-hardware.org/?probe=aeafa2dbee) | Feb 19, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [be0f73193d](https://linux-hardware.org/?probe=be0f73193d) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [c784a261d4](https://linux-hardware.org/?probe=c784a261d4) | Feb 19, 2023 |
| Gigabyte      | H81M-S2H                    | [d6f4d9d8df](https://linux-hardware.org/?probe=d6f4d9d8df) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [96c9f07207](https://linux-hardware.org/?probe=96c9f07207) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [2734c1a2ae](https://linux-hardware.org/?probe=2734c1a2ae) | Feb 18, 2023 |
| MSI           | H270 PC MATE                | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| MSI           | 760GM-P23                   | [529e0929d2](https://linux-hardware.org/?probe=529e0929d2) | Feb 17, 2023 |
| Gigabyte      | 990FXA-UD3                  | [97e017594b](https://linux-hardware.org/?probe=97e017594b) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [51b7c93a69](https://linux-hardware.org/?probe=51b7c93a69) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [4275665066](https://linux-hardware.org/?probe=4275665066) | Feb 16, 2023 |
| MSI           | Z370M MORTAR                | [5ac9c9a924](https://linux-hardware.org/?probe=5ac9c9a924) | Feb 15, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [995da369f0](https://linux-hardware.org/?probe=995da369f0) | Feb 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [b6b09f6455](https://linux-hardware.org/?probe=b6b09f6455) | Feb 14, 2023 |
| Gigabyte      | 945GZM-S2                   | [e271dc0c66](https://linux-hardware.org/?probe=e271dc0c66) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| Google        | Teemo                       | [53bf6d19ca](https://linux-hardware.org/?probe=53bf6d19ca) | Feb 14, 2023 |
| MSI           | MS-B9181                    | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [1e3c885566](https://linux-hardware.org/?probe=1e3c885566) | Feb 13, 2023 |
| Dell          | 0Y7WYT A00                  | [e289b5bb8d](https://linux-hardware.org/?probe=e289b5bb8d) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Alienware     | 0N43JM A00                  | [ef1d9239ab](https://linux-hardware.org/?probe=ef1d9239ab) | Feb 12, 2023 |
| Lenovo        | ThinkServer TS140           | [59eeaafe59](https://linux-hardware.org/?probe=59eeaafe59) | Feb 12, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| Unknown       | Unknown                     | [ce78e6cdb9](https://linux-hardware.org/?probe=ce78e6cdb9) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [a789235fe3](https://linux-hardware.org/?probe=a789235fe3) | Feb 11, 2023 |
| HP            | 8054                        | [55c5642509](https://linux-hardware.org/?probe=55c5642509) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [f3919f8d69](https://linux-hardware.org/?probe=f3919f8d69) | Feb 11, 2023 |
| IBM           | 819046G                     | [a43370bbbd](https://linux-hardware.org/?probe=a43370bbbd) | Feb 11, 2023 |
| Unknown       | Unknown                     | [f5e5e27e8e](https://linux-hardware.org/?probe=f5e5e27e8e) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| HP            | 8643 SMVB                   | [5e8a88b237](https://linux-hardware.org/?probe=5e8a88b237) | Feb 11, 2023 |
| ASUSTek       | P5K                         | [9f8790812d](https://linux-hardware.org/?probe=9f8790812d) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| Unknown       | Unknown                     | [cb0a834e1a](https://linux-hardware.org/?probe=cb0a834e1a) | Feb 10, 2023 |
| MSI           | GF615M-P31                  | [36dcd2e516](https://linux-hardware.org/?probe=36dcd2e516) | Feb 10, 2023 |
| Gigabyte      | X570 GAMING X               | [458744c54d](https://linux-hardware.org/?probe=458744c54d) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| Gigabyte      | X570 GAMING X               | [dd9b71e8d2](https://linux-hardware.org/?probe=dd9b71e8d2) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [dd76c764a1](https://linux-hardware.org/?probe=dd76c764a1) | Feb 08, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [37aec8a881](https://linux-hardware.org/?probe=37aec8a881) | Feb 08, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [e7ee51ecdd](https://linux-hardware.org/?probe=e7ee51ecdd) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH P67              | [1fdf18a3ed](https://linux-hardware.org/?probe=1fdf18a3ed) | Feb 08, 2023 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [000ed6c589](https://linux-hardware.org/?probe=000ed6c589) | Feb 07, 2023 |
| Intel         | CRESCENTBAY                 | [1830edf54c](https://linux-hardware.org/?probe=1830edf54c) | Feb 07, 2023 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [96f24866e0](https://linux-hardware.org/?probe=96f24866e0) | Feb 06, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [0de7e3b318](https://linux-hardware.org/?probe=0de7e3b318) | Feb 05, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e61bc21eaf](https://linux-hardware.org/?probe=e61bc21eaf) | Feb 05, 2023 |
| HP            | 2B47                        | [3db96ac186](https://linux-hardware.org/?probe=3db96ac186) | Feb 04, 2023 |
| Dell          | 0HN7XN A01                  | [0399613500](https://linux-hardware.org/?probe=0399613500) | Feb 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e5a1cf7284](https://linux-hardware.org/?probe=e5a1cf7284) | Feb 03, 2023 |
| MSI           | B85M-E45                    | [13453f924e](https://linux-hardware.org/?probe=13453f924e) | Feb 03, 2023 |
| Intel         | X58                         | [55a6a5bd82](https://linux-hardware.org/?probe=55a6a5bd82) | Feb 03, 2023 |
| Unknown       | G41 Series                  | [69d4cb64a2](https://linux-hardware.org/?probe=69d4cb64a2) | Feb 03, 2023 |
| HP            | 1825                        | [fd942fd3ba](https://linux-hardware.org/?probe=fd942fd3ba) | Feb 02, 2023 |
| HP            | 09F8h                       | [19339c9512](https://linux-hardware.org/?probe=19339c9512) | Feb 02, 2023 |
| Dell          | 0D28YY A01                  | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| ASRock        | H87 Pro4                    | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| MSI           | H81M-P33                    | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| HP            | 1791                        | [0cb5402c68](https://linux-hardware.org/?probe=0cb5402c68) | Jan 29, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [bc4b6513bb](https://linux-hardware.org/?probe=bc4b6513bb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| HP            | 843F                        | [5e9a5d2afd](https://linux-hardware.org/?probe=5e9a5d2afd) | Jan 28, 2023 |
| MSI           | PRO H610M-G DDR4            | [ad4f37d5a4](https://linux-hardware.org/?probe=ad4f37d5a4) | Jan 28, 2023 |
| HP            | 2B47                        | [cce5f9ec07](https://linux-hardware.org/?probe=cce5f9ec07) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| ASRock        | H61M-DGS                    | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| ASRock        | H87 Pro4                    | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| HP            | 2ADE                        | [b927cb3f98](https://linux-hardware.org/?probe=b927cb3f98) | Jan 24, 2023 |
| Acer          | RS880M05                    | [c7e3fe60e1](https://linux-hardware.org/?probe=c7e3fe60e1) | Jan 23, 2023 |
| ASRock        | H61M                        | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| ASUSTek       | P5Q                         | [9e3b6b7075](https://linux-hardware.org/?probe=9e3b6b7075) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| HP            | 89B5 A                      | [1b6e288840](https://linux-hardware.org/?probe=1b6e288840) | Jan 21, 2023 |
| HP            | 843F                        | [07f6efa703](https://linux-hardware.org/?probe=07f6efa703) | Jan 20, 2023 |
| ASUSTek       | M4A3000E                    | [650236c7cc](https://linux-hardware.org/?probe=650236c7cc) | Jan 19, 2023 |
| ASRock        | B450 Pro4                   | [8131194ea1](https://linux-hardware.org/?probe=8131194ea1) | Jan 19, 2023 |
| ASUSTek       | P7P55D-E                    | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| HP            | 843F                        | [83ca70ac2d](https://linux-hardware.org/?probe=83ca70ac2d) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| ASUSTek       | M4A3000E                    | [4f8a71f0c5](https://linux-hardware.org/?probe=4f8a71f0c5) | Jan 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| HP            | 3397                        | [a58c9ac196](https://linux-hardware.org/?probe=a58c9ac196) | Jan 17, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| Gigabyte      | EX58-EXTREME                | [bb62149054](https://linux-hardware.org/?probe=bb62149054) | Jan 16, 2023 |
| Medion        | MS-7707                     | [9665ceabf1](https://linux-hardware.org/?probe=9665ceabf1) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Gigabyte      | M68MT-S2                    | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Unknown       | Unknown                     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| Alienware     | 2                           | [97c74c0c7b](https://linux-hardware.org/?probe=97c74c0c7b) | Jan 15, 2023 |
| Dell          | 0F0TGN A00                  | [38a44bb08b](https://linux-hardware.org/?probe=38a44bb08b) | Jan 14, 2023 |
| HP            | 18E7                        | [3acf05bf4e](https://linux-hardware.org/?probe=3acf05bf4e) | Jan 14, 2023 |
| Unknown       | Unknown                     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| HC            | HCAR357-MI V1.0             | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| HP            | 0B4Ch D                     | [c5edc9fbc7](https://linux-hardware.org/?probe=c5edc9fbc7) | Jan 14, 2023 |
| Dell          | 0F0TGN A00                  | [dc548d070e](https://linux-hardware.org/?probe=dc548d070e) | Jan 13, 2023 |
| HP            | 3397                        | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Acer          | FRS690L                     | [5b27fe10aa](https://linux-hardware.org/?probe=5b27fe10aa) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [07cedbf55a](https://linux-hardware.org/?probe=07cedbf55a) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| ASUSTek       | H87-PRO                     | [4ac36f25a9](https://linux-hardware.org/?probe=4ac36f25a9) | Jan 11, 2023 |
| HP            | 843B                        | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| HP            | 843B                        | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| ASUSTek       | M4A88T-M                    | [4c3d063774](https://linux-hardware.org/?probe=4c3d063774) | Jan 09, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| HP            | 2129                        | [4d6113e60d](https://linux-hardware.org/?probe=4d6113e60d) | Jan 08, 2023 |
| ASRock        | X670E PG Lightning          | [2b3261504f](https://linux-hardware.org/?probe=2b3261504f) | Jan 08, 2023 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [f3e00dc862](https://linux-hardware.org/?probe=f3e00dc862) | Jan 07, 2023 |
| Standard      | X50-V2                      | [69b7593670](https://linux-hardware.org/?probe=69b7593670) | Jan 07, 2023 |
| HP            | 2B47                        | [8ad8cb5e8f](https://linux-hardware.org/?probe=8ad8cb5e8f) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| Dell          | 0HN7XN A01                  | [e597f176c2](https://linux-hardware.org/?probe=e597f176c2) | Jan 03, 2023 |
| Dell          | 018D1Y A00                  | [9ba9bcee90](https://linux-hardware.org/?probe=9ba9bcee90) | Jan 03, 2023 |
| Foxconn       | H67S/H61SP                  | [c7684d1f93](https://linux-hardware.org/?probe=c7684d1f93) | Jan 03, 2023 |
| HP            | 8350                        | [3ab0d55a41](https://linux-hardware.org/?probe=3ab0d55a41) | Jan 02, 2023 |
| ASUSTek       | D300TA                      | [f522fa7b4d](https://linux-hardware.org/?probe=f522fa7b4d) | Jan 02, 2023 |
| ASUSTek       | H87-PRO                     | [f95906c714](https://linux-hardware.org/?probe=f95906c714) | Jan 01, 2023 |
| Dell          | 0T10XW A00                  | [21638e1dfe](https://linux-hardware.org/?probe=21638e1dfe) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| Gigabyte      | B550 AORUS PRO              | [c8da48f03c](https://linux-hardware.org/?probe=c8da48f03c) | Dec 30, 2022 |
| HOUTER        | IPMIP-GS                    | [6fddf7d035](https://linux-hardware.org/?probe=6fddf7d035) | Dec 30, 2022 |
| Biostar       | TA970                       | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Gigabyte      | 970A-DS3P                   | [c841093094](https://linux-hardware.org/?probe=c841093094) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | [59f6170d5b](https://linux-hardware.org/?probe=59f6170d5b) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [7ce6d4b3e3](https://linux-hardware.org/?probe=7ce6d4b3e3) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [f828f74e07](https://linux-hardware.org/?probe=f828f74e07) | Dec 29, 2022 |
| PCWare        | IPMH61R1                    | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Dell          | 03KWTV A02                  | [82612358ac](https://linux-hardware.org/?probe=82612358ac) | Dec 28, 2022 |
| HP            | 2AF7                        | [9663a281c1](https://linux-hardware.org/?probe=9663a281c1) | Dec 28, 2022 |
| Acer          | Aspire XC-780               | [0d90d1884c](https://linux-hardware.org/?probe=0d90d1884c) | Dec 27, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| HP            | 2AF7                        | [287696b4fc](https://linux-hardware.org/?probe=287696b4fc) | Dec 25, 2022 |
| Gigabyte      | GA-770T-USB3                | [08d1b04754](https://linux-hardware.org/?probe=08d1b04754) | Dec 25, 2022 |
| ASRock        | 970 Extreme4                | [2655b3c6b6](https://linux-hardware.org/?probe=2655b3c6b6) | Dec 24, 2022 |
| Intel         | H61                         | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| HP            | 2AF7                        | [7b79dd8352](https://linux-hardware.org/?probe=7b79dd8352) | Dec 23, 2022 |
| HP            | 2AF7                        | [5ef9ce3357](https://linux-hardware.org/?probe=5ef9ce3357) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | [bd8a5003e8](https://linux-hardware.org/?probe=bd8a5003e8) | Dec 23, 2022 |
| ASRock        | G31M-S                      | [476c5ec563](https://linux-hardware.org/?probe=476c5ec563) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | [cb9ec3d5ad](https://linux-hardware.org/?probe=cb9ec3d5ad) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | [bfdc9d1e12](https://linux-hardware.org/?probe=bfdc9d1e12) | Dec 22, 2022 |
| ECS           | H110M4-C2H                  | [f349ed8914](https://linux-hardware.org/?probe=f349ed8914) | Dec 22, 2022 |
| MSI           | B450M MORTAR                | [2279954594](https://linux-hardware.org/?probe=2279954594) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | G31M-S                      | [88d93da5a7](https://linux-hardware.org/?probe=88d93da5a7) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| PCWare        | IPMH310 PRO 1.0             | [c4dea5edbb](https://linux-hardware.org/?probe=c4dea5edbb) | Dec 21, 2022 |
| HP            | 09CCh                       | [60d8cc87c7](https://linux-hardware.org/?probe=60d8cc87c7) | Dec 20, 2022 |
| Dell          | 0MGK50 A04                  | [931b01be38](https://linux-hardware.org/?probe=931b01be38) | Dec 20, 2022 |
| ASRock        | Z170 Pro4                   | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [08f3a88ab3](https://linux-hardware.org/?probe=08f3a88ab3) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [0d5c4254b7](https://linux-hardware.org/?probe=0d5c4254b7) | Dec 19, 2022 |
| ASRock        | N3150-NUC                   | [5e77ec1117](https://linux-hardware.org/?probe=5e77ec1117) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | [20b69069fa](https://linux-hardware.org/?probe=20b69069fa) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | [e497bf2ce3](https://linux-hardware.org/?probe=e497bf2ce3) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [18d7dcfb19](https://linux-hardware.org/?probe=18d7dcfb19) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [dec0d049f7](https://linux-hardware.org/?probe=dec0d049f7) | Dec 17, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [d9ee8a9854](https://linux-hardware.org/?probe=d9ee8a9854) | Dec 16, 2022 |
| HP            | 8750                        | [a4911352d1](https://linux-hardware.org/?probe=a4911352d1) | Dec 16, 2022 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | [827fabbd5f](https://linux-hardware.org/?probe=827fabbd5f) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | [eeb913fa7c](https://linux-hardware.org/?probe=eeb913fa7c) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | [7a72cfa484](https://linux-hardware.org/?probe=7a72cfa484) | Dec 15, 2022 |
| Dell          | 018D1Y A00                  | [34611b96d0](https://linux-hardware.org/?probe=34611b96d0) | Dec 15, 2022 |
| ASUSTek       | P5PL2-E                     | [d304b202fc](https://linux-hardware.org/?probe=d304b202fc) | Dec 14, 2022 |
| ASUSTek       | M3A78-EM                    | [3339909881](https://linux-hardware.org/?probe=3339909881) | Dec 14, 2022 |
| MSI           | MS-B9071                    | [fc31fe11a2](https://linux-hardware.org/?probe=fc31fe11a2) | Dec 14, 2022 |
| HP            | 1905                        | [21f639657c](https://linux-hardware.org/?probe=21f639657c) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| Gigabyte      | H77N-WIFI                   | [9704c6b7c4](https://linux-hardware.org/?probe=9704c6b7c4) | Dec 12, 2022 |
| Biostar       | A520MH                      | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| Foxconn       | H55MXV-LE                   | [931837aeec](https://linux-hardware.org/?probe=931837aeec) | Dec 12, 2022 |
| Biostar       | A520MH                      | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [80281a1e7b](https://linux-hardware.org/?probe=80281a1e7b) | Dec 11, 2022 |
| Unknown       | T3 MRD                      | [c2cb5ad16b](https://linux-hardware.org/?probe=c2cb5ad16b) | Dec 11, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | [e2a043a361](https://linux-hardware.org/?probe=e2a043a361) | Dec 10, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [9d7365bdd6](https://linux-hardware.org/?probe=9d7365bdd6) | Dec 10, 2022 |
| ASUSTek       | P5Q                         | [fbc5b65636](https://linux-hardware.org/?probe=fbc5b65636) | Dec 10, 2022 |
| ASUSTek       | M3N78-VM                    | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3e0d5dc490](https://linux-hardware.org/?probe=3e0d5dc490) | Dec 09, 2022 |
| ASUSTek       | P5Q                         | [415b325dd0](https://linux-hardware.org/?probe=415b325dd0) | Dec 09, 2022 |
| Unknown       | Unknown                     | [41ff90c88a](https://linux-hardware.org/?probe=41ff90c88a) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [ead8cc9c0a](https://linux-hardware.org/?probe=ead8cc9c0a) | Dec 08, 2022 |
| HP            | 82FE 11                     | [6bf35b7005](https://linux-hardware.org/?probe=6bf35b7005) | Dec 08, 2022 |
| Dell          | 0478VN A00                  | [54eaa6d2f3](https://linux-hardware.org/?probe=54eaa6d2f3) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| MSI           | K9A2 Platinum               | [3ce727deb7](https://linux-hardware.org/?probe=3ce727deb7) | Dec 06, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [8442e3381c](https://linux-hardware.org/?probe=8442e3381c) | Dec 06, 2022 |
| Apple         | Mac-F221BEC8                | [5132e1aba1](https://linux-hardware.org/?probe=5132e1aba1) | Dec 05, 2022 |
| Dell          | 0T10XW A00                  | [d6f876fa52](https://linux-hardware.org/?probe=d6f876fa52) | Dec 05, 2022 |
| HP            | 8350                        | [f7768016d5](https://linux-hardware.org/?probe=f7768016d5) | Dec 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [101ea9ca8e](https://linux-hardware.org/?probe=101ea9ca8e) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| MACHINIST     | E5-MR9A PRO V1.0            | [67fa9fb5aa](https://linux-hardware.org/?probe=67fa9fb5aa) | Dec 03, 2022 |
| MSI           | K9A2 Platinum               | [79c823558a](https://linux-hardware.org/?probe=79c823558a) | Dec 03, 2022 |
| HP            | 2AE2                        | [549eacfc3d](https://linux-hardware.org/?probe=549eacfc3d) | Dec 03, 2022 |
| MSI           | B75A-G41                    | [cbf02bbd94](https://linux-hardware.org/?probe=cbf02bbd94) | Dec 03, 2022 |
| Biostar       | TPower X58                  | [320769fceb](https://linux-hardware.org/?probe=320769fceb) | Dec 02, 2022 |
| AZW           | U59                         | [6a7c9cb905](https://linux-hardware.org/?probe=6a7c9cb905) | Dec 02, 2022 |
| NZXT          | N7 Z590                     | [cc56e65209](https://linux-hardware.org/?probe=cc56e65209) | Dec 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | [dfd11598ed](https://linux-hardware.org/?probe=dfd11598ed) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| MSI           | G41M-S03                    | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Apple         | Mac-F221BEC8                | [7f91a09589](https://linux-hardware.org/?probe=7f91a09589) | Dec 01, 2022 |
| HP            | 8433 11                     | [01f9a28da3](https://linux-hardware.org/?probe=01f9a28da3) | Dec 01, 2022 |
| OEM           | H110 Ver:2.21               | [ad7fffd9e3](https://linux-hardware.org/?probe=ad7fffd9e3) | Nov 30, 2022 |
| ASRock        | B450M Steel Legend          | [9d6aeff37c](https://linux-hardware.org/?probe=9d6aeff37c) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | [2e7e420f42](https://linux-hardware.org/?probe=2e7e420f42) | Nov 29, 2022 |
| Gateway       | SX2851                      | [b408695def](https://linux-hardware.org/?probe=b408695def) | Nov 28, 2022 |
| ASUSTek       | M5A88-M                     | [f4b2035429](https://linux-hardware.org/?probe=f4b2035429) | Nov 28, 2022 |
| HOUTER        | IPMIP-GS                    | [cbc472e6df](https://linux-hardware.org/?probe=cbc472e6df) | Nov 28, 2022 |
| BESSTAR Te... | HM90                        | [eda49557ae](https://linux-hardware.org/?probe=eda49557ae) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | [6867d8eeaf](https://linux-hardware.org/?probe=6867d8eeaf) | Nov 27, 2022 |
| Megaware      | MW-NM70HD-MI 01/13/2013 ... | [95b48709fd](https://linux-hardware.org/?probe=95b48709fd) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [88db74df98](https://linux-hardware.org/?probe=88db74df98) | Nov 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [5b531b7b41](https://linux-hardware.org/?probe=5b531b7b41) | Nov 26, 2022 |
| ASRock        | B450M Pro4                  | [def104dd7d](https://linux-hardware.org/?probe=def104dd7d) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [3ca25803b5](https://linux-hardware.org/?probe=3ca25803b5) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| HP            | 18E7                        | [048d4bd3ae](https://linux-hardware.org/?probe=048d4bd3ae) | Nov 25, 2022 |
| Dell          | 0T10XW A02                  | [83daa0cf15](https://linux-hardware.org/?probe=83daa0cf15) | Nov 25, 2022 |
| Gigabyte      | H110M-H-CF                  | [c43b60c09b](https://linux-hardware.org/?probe=c43b60c09b) | Nov 25, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | [6bcefa911d](https://linux-hardware.org/?probe=6bcefa911d) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| ASRock        | FP6D4-P1                    | [5e52f1b520](https://linux-hardware.org/?probe=5e52f1b520) | Nov 24, 2022 |
| MSI           | Z490-A PRO                  | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [51f3e71650](https://linux-hardware.org/?probe=51f3e71650) | Nov 24, 2022 |
| ASRock        | Z170 Pro4                   | [ac6ad8d54d](https://linux-hardware.org/?probe=ac6ad8d54d) | Nov 24, 2022 |
| Dell          | 0HN7XN A01                  | [5357d43f13](https://linux-hardware.org/?probe=5357d43f13) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | [9dbd34c7bd](https://linux-hardware.org/?probe=9dbd34c7bd) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | [5786af4776](https://linux-hardware.org/?probe=5786af4776) | Nov 23, 2022 |
| Intel         | D946GZAB AAD66610-302       | [5433ee5bc1](https://linux-hardware.org/?probe=5433ee5bc1) | Nov 22, 2022 |
| HP            | 8184 X4                     | [f38ad9d963](https://linux-hardware.org/?probe=f38ad9d963) | Nov 21, 2022 |
| HP            | 822A                        | [b464dc4cf0](https://linux-hardware.org/?probe=b464dc4cf0) | Nov 21, 2022 |
| Acer          | Veriton N4640G              | [a7984c4a95](https://linux-hardware.org/?probe=a7984c4a95) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [cd0f904ca4](https://linux-hardware.org/?probe=cd0f904ca4) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [c4bd142690](https://linux-hardware.org/?probe=c4bd142690) | Nov 20, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [41cca3d850](https://linux-hardware.org/?probe=41cca3d850) | Nov 20, 2022 |
| MSI           | Z77A-G43                    | [2033b97419](https://linux-hardware.org/?probe=2033b97419) | Nov 19, 2022 |
| Acer          | FX58M                       | [837da7d885](https://linux-hardware.org/?probe=837da7d885) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Dell          | 0HN7XN A00                  | [3e217adbf8](https://linux-hardware.org/?probe=3e217adbf8) | Nov 18, 2022 |
| ASUSTek       | PRIME H370-A                | [0c4442c160](https://linux-hardware.org/?probe=0c4442c160) | Nov 18, 2022 |
| Dell          | 0C27VV A02                  | [5f4b4b8571](https://linux-hardware.org/?probe=5f4b4b8571) | Nov 18, 2022 |
| MSI           | H81M-P33                    | [a535339292](https://linux-hardware.org/?probe=a535339292) | Nov 17, 2022 |
| MSI           | 2AE0                        | [c0d9e23faa](https://linux-hardware.org/?probe=c0d9e23faa) | Nov 16, 2022 |
| MSI           | H81M-P33                    | [246d594268](https://linux-hardware.org/?probe=246d594268) | Nov 16, 2022 |
| HP            | 0AA4h                       | [328259669b](https://linux-hardware.org/?probe=328259669b) | Nov 16, 2022 |
| ASUSTek       | PRIME H370-A                | [9a93c5f349](https://linux-hardware.org/?probe=9a93c5f349) | Nov 15, 2022 |
| ASUSTek       | H110M-A                     | [d1e60135e1](https://linux-hardware.org/?probe=d1e60135e1) | Nov 15, 2022 |
| HP            | 18E7                        | [7ecd6a2f37](https://linux-hardware.org/?probe=7ecd6a2f37) | Nov 15, 2022 |
| Dell          | 0478VN A00                  | [5d1cf4ca11](https://linux-hardware.org/?probe=5d1cf4ca11) | Nov 14, 2022 |
| Gigabyte      | H510M H                     | [97b0a5f239](https://linux-hardware.org/?probe=97b0a5f239) | Nov 14, 2022 |
| HP            | 1850                        | [0b5e36c27b](https://linux-hardware.org/?probe=0b5e36c27b) | Nov 13, 2022 |
| Mediacom      | M-AO241/64                  | [8c577b3d8f](https://linux-hardware.org/?probe=8c577b3d8f) | Nov 13, 2022 |
| ASUSTek       | H110M-A                     | [1c7b3f934d](https://linux-hardware.org/?probe=1c7b3f934d) | Nov 12, 2022 |
| Fujitsu Si... | MS-7304VP-A13               | [69b1471202](https://linux-hardware.org/?probe=69b1471202) | Nov 12, 2022 |
| JGINYUE       | X79M-PLUS V2.3              | [8dac2a9292](https://linux-hardware.org/?probe=8dac2a9292) | Nov 12, 2022 |
| Unknown       | 775i65G                     | [b872a779af](https://linux-hardware.org/?probe=b872a779af) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | [16247a3667](https://linux-hardware.org/?probe=16247a3667) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | [bc5562e288](https://linux-hardware.org/?probe=bc5562e288) | Nov 12, 2022 |
| Biostar       | TPower X58                  | [8662697d27](https://linux-hardware.org/?probe=8662697d27) | Nov 11, 2022 |
| Mediacom      | M-AO241/64                  | [d0cac7ee7b](https://linux-hardware.org/?probe=d0cac7ee7b) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | [cf0ed7acab](https://linux-hardware.org/?probe=cf0ed7acab) | Nov 10, 2022 |
| Dell          | 0HN7XN A01                  | [bb4dff706b](https://linux-hardware.org/?probe=bb4dff706b) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | [b7619dbd72](https://linux-hardware.org/?probe=b7619dbd72) | Nov 10, 2022 |
| MSI           | A320M-A PRO MAX             | [c3aaf6eed2](https://linux-hardware.org/?probe=c3aaf6eed2) | Nov 09, 2022 |
| MSI           | A320M-A PRO MAX             | [5030ff83c2](https://linux-hardware.org/?probe=5030ff83c2) | Nov 08, 2022 |
| MSI           | H81M-P33                    | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| Acer          | H81H3-M4                    | [40c67913d8](https://linux-hardware.org/?probe=40c67913d8) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| Gigabyte      | 990XA-UD3                   | [a06275a0f2](https://linux-hardware.org/?probe=a06275a0f2) | Nov 05, 2022 |
| HP            | 1790                        | [8916928344](https://linux-hardware.org/?probe=8916928344) | Nov 05, 2022 |
| HP            | 1790                        | [1de8a8af0d](https://linux-hardware.org/?probe=1de8a8af0d) | Nov 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [507697b22f](https://linux-hardware.org/?probe=507697b22f) | Nov 04, 2022 |
| Dell          | 0C27VV A02                  | [fb4c1f85a2](https://linux-hardware.org/?probe=fb4c1f85a2) | Nov 04, 2022 |
| Dell          | 0HN7XN A01                  | [baf6b79b85](https://linux-hardware.org/?probe=baf6b79b85) | Nov 03, 2022 |
| MSI           | A320M PRO-VD/S              | [920c4567d3](https://linux-hardware.org/?probe=920c4567d3) | Nov 03, 2022 |
| ASUSTek       | P7H55-M LE                  | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Dell          | 0GDG8Y A00                  | [609ccd3204](https://linux-hardware.org/?probe=609ccd3204) | Nov 02, 2022 |
| Gigabyte      | P55-UD6                     | [2898ec20b3](https://linux-hardware.org/?probe=2898ec20b3) | Nov 01, 2022 |
| Lenovo        | ThinkCentre M55E 898578G    | [d025c115d8](https://linux-hardware.org/?probe=d025c115d8) | Nov 01, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [21213fdeec](https://linux-hardware.org/?probe=21213fdeec) | Oct 31, 2022 |
| HP            | 1790                        | [6dc2cef5ea](https://linux-hardware.org/?probe=6dc2cef5ea) | Oct 31, 2022 |
| Seco          | C40 C                       | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| ASUSTek       | PRIME H370-A                | [f7dd154c47](https://linux-hardware.org/?probe=f7dd154c47) | Oct 30, 2022 |
| Gigabyte      | B450M DS3H V2               | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [068d4ec2e6](https://linux-hardware.org/?probe=068d4ec2e6) | Oct 29, 2022 |
| Dell          | 0T2HR0 A02                  | [e4b1137777](https://linux-hardware.org/?probe=e4b1137777) | Oct 29, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [2c57f9b6a3](https://linux-hardware.org/?probe=2c57f9b6a3) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| MSI           | B560M PRO                   | [a84dc6f9cb](https://linux-hardware.org/?probe=a84dc6f9cb) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| Gateway       | SX2851                      | [500b4bb8ec](https://linux-hardware.org/?probe=500b4bb8ec) | Oct 27, 2022 |
| ASUSTek       | P8H61/USB3                  | [c20c97e43e](https://linux-hardware.org/?probe=c20c97e43e) | Oct 27, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7a0f5285f2](https://linux-hardware.org/?probe=7a0f5285f2) | Oct 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [5bc9d4bdc8](https://linux-hardware.org/?probe=5bc9d4bdc8) | Oct 26, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [bb655d6ea7](https://linux-hardware.org/?probe=bb655d6ea7) | Oct 25, 2022 |

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
| Zorin 16 | 1329     | 67.88%  |
| Zorin 15 | 553      | 28.24%  |
| Zorin 12 | 76       | 3.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Zorin | 1954     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 72       | 3.16%   |
| 5.11.0-38-generic | 62       | 2.72%   |
| 5.15.0-67-generic | 58       | 2.55%   |
| 5.15.0-69-generic | 56       | 2.46%   |
| 5.15.0-46-generic | 56       | 2.46%   |
| 5.11.0-27-generic | 56       | 2.46%   |
| 5.11.0-40-generic | 50       | 2.2%    |
| 5.15.0-52-generic | 49       | 2.15%   |
| 5.13.0-39-generic | 49       | 2.15%   |
| 5.15.0-58-generic | 46       | 2.02%   |
| 5.15.0-60-generic | 45       | 1.98%   |
| 5.15.0-78-generic | 41       | 1.8%    |
| 5.15.0-48-generic | 41       | 1.8%    |
| 5.11.0-41-generic | 41       | 1.8%    |
| 5.3.0-40-generic  | 40       | 1.76%   |
| 5.15.0-71-generic | 40       | 1.76%   |
| 5.13.0-30-generic | 40       | 1.76%   |
| 5.13.0-40-generic | 38       | 1.67%   |
| 5.15.0-76-generic | 37       | 1.63%   |
| 5.11.0-43-generic | 36       | 1.58%   |
| 5.15.0-41-generic | 35       | 1.54%   |
| 5.11.0-37-generic | 35       | 1.54%   |
| 5.15.0-84-generic | 34       | 1.49%   |
| 5.4.0-42-generic  | 31       | 1.36%   |
| 5.13.0-28-generic | 31       | 1.36%   |
| 5.11.0-34-generic | 31       | 1.36%   |
| 5.15.0-53-generic | 29       | 1.27%   |
| 5.13.0-35-generic | 28       | 1.23%   |
| 5.15.0-73-generic | 27       | 1.19%   |
| 5.0.0-37-generic  | 27       | 1.19%   |
| 5.13.0-27-generic | 26       | 1.14%   |
| 5.13.0-41-generic | 25       | 1.1%    |
| 5.15.0-83-generic | 24       | 1.05%   |
| 5.13.0-52-generic | 24       | 1.05%   |
| 5.15.0-72-generic | 23       | 1.01%   |
| 5.13.0-44-generic | 21       | 0.92%   |
| 5.4.0-58-generic  | 20       | 0.88%   |
| 5.4.0-47-generic  | 20       | 0.88%   |
| 5.4.0-72-generic  | 19       | 0.83%   |
| 5.15.0-79-generic | 19       | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 718      | 35.28%  |
| 5.11.0  | 334      | 16.41%  |
| 5.4.0   | 326      | 16.02%  |
| 5.13.0  | 293      | 14.4%   |
| 5.3.0   | 158      | 7.76%   |
| 4.15.0  | 75       | 3.69%   |
| 5.0.0   | 58       | 2.85%   |
| 4.18.0  | 27       | 1.33%   |
| 5.8.0   | 26       | 1.28%   |
| 6.5.7   | 1        | 0.05%   |
| 6.3.2   | 1        | 0.05%   |
| 6.2.7   | 1        | 0.05%   |
| 6.2.16  | 1        | 0.05%   |
| 6.1.8   | 1        | 0.05%   |
| 6.1.7   | 1        | 0.05%   |
| 6.0.8   | 1        | 0.05%   |
| 5.8.5   | 1        | 0.05%   |
| 5.7.17  | 1        | 0.05%   |
| 5.7.1   | 1        | 0.05%   |
| 5.7.0   | 1        | 0.05%   |
| 5.19.6  | 1        | 0.05%   |
| 5.19.2  | 1        | 0.05%   |
| 5.19.12 | 1        | 0.05%   |
| 5.17.9  | 1        | 0.05%   |
| 5.17.5  | 1        | 0.05%   |
| 5.17.1  | 1        | 0.05%   |
| 5.15.13 | 1        | 0.05%   |
| 5.14.0  | 1        | 0.05%   |
| 4.4.0   | 1        | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 719      | 35.35%  |
| 5.11    | 334      | 16.42%  |
| 5.4     | 326      | 16.03%  |
| 5.13    | 293      | 14.41%  |
| 5.3     | 158      | 7.77%   |
| 4.15    | 75       | 3.69%   |
| 5.0     | 58       | 2.85%   |
| 5.8     | 27       | 1.33%   |
| 4.18    | 27       | 1.33%   |
| 5.7     | 3        | 0.15%   |
| 5.19    | 3        | 0.15%   |
| 5.17    | 3        | 0.15%   |
| 6.2     | 2        | 0.1%    |
| 6.5     | 1        | 0.05%   |
| 6.3     | 1        | 0.05%   |
| 6.1     | 1        | 0.05%   |
| 6.0     | 1        | 0.05%   |
| 5.14    | 1        | 0.05%   |
| 4.4     | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1842     | 94.27%  |
| i686   | 112      | 5.73%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 1501     | 75.69%  |
| XFCE       | 354      | 17.85%  |
| Unknown    | 119      | 6%      |
| KDE5       | 3        | 0.15%   |
| MATE       | 2        | 0.1%    |
| Cinnamon   | 2        | 0.1%    |
| X-Cinnamon | 1        | 0.05%   |
| KDE        | 1        | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1880     | 95.53%  |
| Unknown | 67       | 3.4%    |
| Wayland | 20       | 1.02%   |
| Tty     | 1        | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1665     | 83.75%  |
| GDM3    | 131      | 6.59%   |
| GDM     | 105      | 5.28%   |
| LightDM | 82       | 4.12%   |
| TDM     | 4        | 0.2%    |
| SDDM    | 1        | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 730      | 37.11%  |
| de_DE       | 166      | 8.44%   |
| pt_BR       | 140      | 7.12%   |
| en_GB       | 127      | 6.46%   |
| Unknown     | 96       | 4.88%   |
| fr_FR       | 61       | 3.1%    |
| it_IT       | 58       | 2.95%   |
| en_CA       | 58       | 2.95%   |
| en_IN       | 44       | 2.24%   |
| es_ES       | 40       | 2.03%   |
| pl_PL       | 39       | 1.98%   |
| nl_NL       | 34       | 1.73%   |
| en_AU       | 34       | 1.73%   |
| es_AR       | 31       | 1.58%   |
| ru_RU       | 25       | 1.27%   |
| es_MX       | 22       | 1.12%   |
| hu_HU       | 21       | 1.07%   |
| en_ZA       | 20       | 1.02%   |
| cs_CZ       | 13       | 0.66%   |
| sv_SE       | 12       | 0.61%   |
| pt_PT       | 12       | 0.61%   |
| fr_CA       | 11       | 0.56%   |
| nl_BE       | 9        | 0.46%   |
| es_CL       | 9        | 0.46%   |
| tr_TR       | 8        | 0.41%   |
| es_CO       | 8        | 0.41%   |
| C           | 8        | 0.41%   |
| nb_NO       | 7        | 0.36%   |
| fi_FI       | 7        | 0.36%   |
| en_NZ       | 7        | 0.36%   |
| ja_JP       | 6        | 0.31%   |
| en_PH       | 6        | 0.31%   |
| el_GR       | 6        | 0.31%   |
| da_DK       | 6        | 0.31%   |
| es_VE       | 5        | 0.25%   |
| de_CH       | 5        | 0.25%   |
| bg_BG       | 5        | 0.25%   |
| sk_SK       | 4        | 0.2%    |
| es_PE       | 4        | 0.2%    |
| sr_RS@latin | 3        | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1197     | 60.67%  |
| EFI  | 776      | 39.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1824     | 92.68%  |
| Tmpfs    | 34       | 1.73%   |
| Overlay  | 34       | 1.73%   |
| Zfs      | 28       | 1.42%   |
| Btrfs    | 17       | 0.86%   |
| Ext2     | 11       | 0.56%   |
| Unknown  | 10       | 0.51%   |
| Xfs      | 5        | 0.25%   |
| Ext3     | 4        | 0.2%    |
| Reiserfs | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1776     | 90.06%  |
| GPT     | 120      | 6.09%   |
| MBR     | 76       | 3.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1831     | 93.13%  |
| Yes       | 135      | 6.87%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1579     | 79.95%  |
| Yes       | 396      | 20.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 436      | 22.31%  |
| Gigabyte Technology | 296      | 15.15%  |
| Dell                | 211      | 10.8%   |
| MSI                 | 180      | 9.21%   |
| Hewlett-Packard     | 175      | 8.96%   |
| ASRock              | 145      | 7.42%   |
| Lenovo              | 89       | 4.55%   |
| Intel               | 60       | 3.07%   |
| Pegatron            | 38       | 1.94%   |
| Unknown             | 38       | 1.94%   |
| Acer                | 37       | 1.89%   |
| Biostar             | 27       | 1.38%   |
| Foxconn             | 25       | 1.28%   |
| Fujitsu             | 24       | 1.23%   |
| ECS                 | 18       | 0.92%   |
| Positivo            | 8        | 0.41%   |
| Medion              | 8        | 0.41%   |
| Alienware           | 8        | 0.41%   |
| Shuttle             | 7        | 0.36%   |
| AZW                 | 6        | 0.31%   |
| Apple               | 6        | 0.31%   |
| Gateway             | 5        | 0.26%   |
| eMachines           | 5        | 0.26%   |
| Packard Bell        | 4        | 0.2%    |
| OEM                 | 4        | 0.2%    |
| IBM                 | 4        | 0.2%    |
| Google              | 4        | 0.2%    |
| BESSTAR Tech        | 4        | 0.2%    |
| Semp Toshiba        | 3        | 0.15%   |
| Huanan              | 3        | 0.15%   |
| ABIT                | 3        | 0.15%   |
| ZOTAC               | 2        | 0.1%    |
| WinFast             | 2        | 0.1%    |
| SiS Technology      | 2        | 0.1%    |
| Samsung Electronics | 2        | 0.1%    |
| QIYIDA              | 2        | 0.1%    |
| PCWare              | 2        | 0.1%    |
| MAXSUN              | 2        | 0.1%    |
| LORD ELECTRONICS    | 2        | 0.1%    |
| JGINYUE             | 2        | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 42       | 2.15%   |
| ASUS All Series                  | 41       | 2.1%    |
| Dell OptiPlex 7010               | 16       | 0.82%   |
| Dell OptiPlex 780                | 11       | 0.56%   |
| MSI MS-7817                      | 10       | 0.51%   |
| Gigabyte A320M-S2H               | 10       | 0.51%   |
| Dell OptiPlex 790                | 10       | 0.51%   |
| Dell OptiPlex 380                | 10       | 0.51%   |
| ASUS M5A97 R2.0                  | 9        | 0.46%   |
| ASUS M5A78L-M/USB3               | 9        | 0.46%   |
| MSI MS-7C02                      | 8        | 0.41%   |
| Dell OptiPlex 755                | 8        | 0.41%   |
| Gigabyte GA-78LMT-USB3 6.0       | 7        | 0.36%   |
| Gigabyte B450 AORUS M            | 7        | 0.36%   |
| Gigabyte 970A-DS3P               | 7        | 0.36%   |
| Dell OptiPlex 990                | 7        | 0.36%   |
| Dell OptiPlex 9020               | 7        | 0.36%   |
| ASUS TUF Gaming X570-PLUS        | 7        | 0.36%   |
| Intel H61                        | 6        | 0.31%   |
| HP ProDesk 600 G1 SFF            | 6        | 0.31%   |
| Dell Precision WorkStation T3500 | 6        | 0.31%   |
| Dell OptiPlex 7040               | 6        | 0.31%   |
| Dell OptiPlex 3010               | 6        | 0.31%   |
| MSI MS-7C37                      | 5        | 0.26%   |
| HP Compaq Pro 6300 SFF           | 5        | 0.26%   |
| HP Compaq Elite 8300 SFF         | 5        | 0.26%   |
| Gigabyte GA-78LMT-USB3           | 5        | 0.26%   |
| Gigabyte B450M DS3H              | 5        | 0.26%   |
| Dell OptiPlex 7020               | 5        | 0.26%   |
| Dell OptiPlex 3020               | 5        | 0.26%   |
| Dell Inspiron 3847               | 5        | 0.26%   |
| ASUS P8Z77-V LX                  | 5        | 0.26%   |
| ASRock N68C-S UCC                | 5        | 0.26%   |
| ASRock B450 Pro4                 | 5        | 0.26%   |
| MSI MS-7C91                      | 4        | 0.2%    |
| MSI MS-7B89                      | 4        | 0.2%    |
| MSI MS-7B86                      | 4        | 0.2%    |
| MSI MS-7B84                      | 4        | 0.2%    |
| MSI MS-7A38                      | 4        | 0.2%    |
| MSI MS-7721                      | 4        | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 132      | 6.76%   |
| HP Compaq              | 64       | 3.28%   |
| Lenovo ThinkCentre     | 57       | 2.92%   |
| ASUS PRIME             | 53       | 2.71%   |
| Unknown                | 42       | 2.15%   |
| ASUS ROG               | 41       | 2.1%    |
| ASUS All               | 41       | 2.1%    |
| ASUS TUF               | 39       | 2%      |
| Dell Precision         | 26       | 1.33%   |
| HP EliteDesk           | 23       | 1.18%   |
| Fujitsu ESPRIMO        | 19       | 0.97%   |
| Acer Aspire            | 17       | 0.87%   |
| Dell Inspiron          | 16       | 0.82%   |
| HP ProDesk             | 15       | 0.77%   |
| Gigabyte B450          | 15       | 0.77%   |
| ASUS M5A97             | 15       | 0.77%   |
| ASUS M5A78L-M          | 14       | 0.72%   |
| Gigabyte GA-78LMT-USB3 | 13       | 0.67%   |
| Lenovo IdeaCentre      | 11       | 0.56%   |
| HP Pavilion            | 11       | 0.56%   |
| Gigabyte A320M-S2H     | 11       | 0.56%   |
| Dell Vostro            | 11       | 0.56%   |
| MSI MS-7817            | 10       | 0.51%   |
| Gigabyte X570          | 10       | 0.51%   |
| Gigabyte B450M         | 10       | 0.51%   |
| Acer Veriton           | 10       | 0.51%   |
| ASRock B450            | 9        | 0.46%   |
| MSI MS-7C02            | 8        | 0.41%   |
| Dell XPS               | 8        | 0.41%   |
| ASUS P8H61-M           | 8        | 0.41%   |
| ASRock B450M           | 8        | 0.41%   |
| Gigabyte 970A-DS3P     | 7        | 0.36%   |
| ASUS P5G41T-M          | 7        | 0.36%   |
| ASRock X570            | 7        | 0.36%   |
| Intel H61              | 6        | 0.31%   |
| ASUS P8Z77-V           | 6        | 0.31%   |
| ASRock N68C-S          | 6        | 0.31%   |
| ASRock 970             | 6        | 0.31%   |
| MSI MS-7C37            | 5        | 0.26%   |
| Gigabyte B550M         | 5        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 172      | 8.8%    |
| 2012    | 171      | 8.75%   |
| 2011    | 169      | 8.65%   |
| 2018    | 150      | 7.68%   |
| 2014    | 144      | 7.37%   |
| 2010    | 141      | 7.22%   |
| 2009    | 132      | 6.76%   |
| 2008    | 114      | 5.83%   |
| 2020    | 105      | 5.37%   |
| 2017    | 100      | 5.12%   |
| 2019    | 99       | 5.07%   |
| 2021    | 86       | 4.4%    |
| 2007    | 83       | 4.25%   |
| 2016    | 67       | 3.43%   |
| 2015    | 67       | 3.43%   |
| 2006    | 47       | 2.41%   |
| 2022    | 41       | 2.1%    |
| 2005    | 29       | 1.48%   |
| 2023    | 15       | 0.77%   |
| 2004    | 10       | 0.51%   |
| 2003    | 6        | 0.31%   |
| Unknown | 5        | 0.26%   |
| 2002    | 1        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1954     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1862     | 94.95%  |
| Enabled  | 99       | 5.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1950     | 99.8%   |
| Yes  | 4        | 0.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 413      | 20.77%  |
| 8.01-16.0       | 396      | 19.92%  |
| 3.01-4.0        | 362      | 18.21%  |
| 4.01-8.0        | 317      | 15.95%  |
| 32.01-64.0      | 216      | 10.87%  |
| 1.01-2.0        | 111      | 5.58%   |
| 64.01-256.0     | 58       | 2.92%   |
| 2.01-3.0        | 50       | 2.52%   |
| 24.01-32.0      | 39       | 1.96%   |
| 0.51-1.0        | 25       | 1.26%   |
| More than 256.0 | 1        | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 851      | 39.84%  |
| 2.01-3.0   | 570      | 26.69%  |
| 3.01-4.0   | 261      | 12.22%  |
| 4.01-8.0   | 242      | 11.33%  |
| 0.51-1.0   | 138      | 6.46%   |
| 8.01-16.0  | 47       | 2.2%    |
| 0.01-0.5   | 16       | 0.75%   |
| 16.01-24.0 | 8        | 0.37%   |
| 32.01-64.0 | 2        | 0.09%   |
| 24.01-32.0 | 1        | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 976      | 48.39%  |
| 2      | 553      | 27.42%  |
| 3      | 237      | 11.75%  |
| 4      | 121      | 6%      |
| 5      | 63       | 3.12%   |
| 6      | 34       | 1.69%   |
| 7      | 12       | 0.59%   |
| 0      | 9        | 0.45%   |
| 8      | 8        | 0.4%    |
| 51     | 1        | 0.05%   |
| 11     | 1        | 0.05%   |
| 10     | 1        | 0.05%   |
| 9      | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1043     | 52.97%  |
| No        | 926      | 47.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1931     | 98.82%  |
| No        | 23       | 1.18%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1000     | 50.61%  |
| Yes       | 976      | 49.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1400     | 70.96%  |
| Yes       | 573      | 29.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 490      | 25%     |
| Germany      | 185      | 9.44%   |
| Brazil       | 155      | 7.91%   |
| UK           | 129      | 6.58%   |
| Canada       | 79       | 4.03%   |
| Italy        | 69       | 3.52%   |
| Netherlands  | 60       | 3.06%   |
| France       | 60       | 3.06%   |
| India        | 47       | 2.4%    |
| Spain        | 45       | 2.3%    |
| Poland       | 44       | 2.24%   |
| Australia    | 37       | 1.89%   |
| Argentina    | 36       | 1.84%   |
| Mexico       | 27       | 1.38%   |
| Hungary      | 25       | 1.28%   |
| South Africa | 22       | 1.12%   |
| Russia       | 21       | 1.07%   |
| Greece       | 19       | 0.97%   |
| Denmark      | 19       | 0.97%   |
| Sweden       | 18       | 0.92%   |
| Czechia      | 18       | 0.92%   |
| Belgium      | 18       | 0.92%   |
| Portugal     | 17       | 0.87%   |
| Indonesia    | 16       | 0.82%   |
| Switzerland  | 15       | 0.77%   |
| Norway       | 15       | 0.77%   |
| Chile        | 15       | 0.77%   |
| Colombia     | 13       | 0.66%   |
| Turkey       | 11       | 0.56%   |
| Serbia       | 11       | 0.56%   |
| Bulgaria     | 11       | 0.56%   |
| Romania      | 10       | 0.51%   |
| Malaysia     | 10       | 0.51%   |
| Egypt        | 10       | 0.51%   |
| Philippines  | 9        | 0.46%   |
| Japan        | 9        | 0.46%   |
| Finland      | 9        | 0.46%   |
| Venezuela    | 8        | 0.41%   |
| Slovakia     | 8        | 0.41%   |
| New Zealand  | 8        | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Berlin         | 16       | 0.78%   |
| Sao Paulo      | 15       | 0.73%   |
| Rio de Janeiro | 15       | 0.73%   |
| Athens         | 15       | 0.73%   |
| Munich         | 12       | 0.59%   |
| Cape Town      | 11       | 0.54%   |
| Milan          | 10       | 0.49%   |
| Toronto        | 9        | 0.44%   |
| Perth          | 9        | 0.44%   |
| Houston        | 9        | 0.44%   |
| Denver         | 9        | 0.44%   |
| Copenhagen     | 9        | 0.44%   |
| Rome           | 8        | 0.39%   |
| Buenos Aires   | 8        | 0.39%   |
| Bogotá        | 8        | 0.39%   |
| Zurich         | 7        | 0.34%   |
| Santiago       | 7        | 0.34%   |
| Phoenix        | 7        | 0.34%   |
| Montreal       | 7        | 0.34%   |
| London         | 7        | 0.34%   |
| Budapest       | 7        | 0.34%   |
| Bengaluru      | 7        | 0.34%   |
| Belgrade       | 7        | 0.34%   |
| Adelaide       | 7        | 0.34%   |
| Warsaw         | 6        | 0.29%   |
| Vienna         | 6        | 0.29%   |
| The Hague      | 6        | 0.29%   |
| Sydney         | 6        | 0.29%   |
| Portland       | 6        | 0.29%   |
| Las Vegas      | 6        | 0.29%   |
| Johannesburg   | 6        | 0.29%   |
| Dayton         | 6        | 0.29%   |
| Dallas         | 6        | 0.29%   |
| Calgary        | 6        | 0.29%   |
| Brasília      | 6        | 0.29%   |
| Yogyakarta     | 5        | 0.24%   |
| San José      | 5        | 0.24%   |
| Richmond       | 5        | 0.24%   |
| Melbourne      | 5        | 0.24%   |
| Hamburg        | 5        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 672      | 1021   | 20.33%  |
| WDC                         | 603      | 866    | 18.25%  |
| Samsung Electronics         | 413      | 626    | 12.5%   |
| Kingston                    | 199      | 283    | 6.02%   |
| Toshiba                     | 167      | 252    | 5.05%   |
| Sandisk                     | 163      | 220    | 4.93%   |
| Hitachi                     | 155      | 191    | 4.69%   |
| Crucial                     | 110      | 135    | 3.33%   |
| China                       | 49       | 56     | 1.48%   |
| Maxtor                      | 47       | 65     | 1.42%   |
| A-DATA Technology           | 40       | 50     | 1.21%   |
| Intel                       | 37       | 45     | 1.12%   |
| Unknown                     | 33       | 58     | 1%      |
| Phison                      | 32       | 41     | 0.97%   |
| Silicon Motion              | 29       | 40     | 0.88%   |
| PNY                         | 27       | 34     | 0.82%   |
| Intenso                     | 24       | 28     | 0.73%   |
| HGST                        | 23       | 31     | 0.7%    |
| Micron/Crucial Technology   | 21       | 24     | 0.64%   |
| SK hynix                    | 19       | 24     | 0.57%   |
| Patriot                     | 19       | 31     | 0.57%   |
| SPCC                        | 18       | 26     | 0.54%   |
| OCZ                         | 18       | 21     | 0.54%   |
| Micron Technology           | 15       | 16     | 0.45%   |
| GOODRAM                     | 14       | 17     | 0.42%   |
| JMicron Technology          | 13       | 18     | 0.39%   |
| Hewlett-Packard             | 12       | 16     | 0.36%   |
| Phison Electronics          | 11       | 14     | 0.33%   |
| Lexar                       | 11       | 11     | 0.33%   |
| KingSpec                    | 11       | 14     | 0.33%   |
| Gigabyte Technology         | 11       | 19     | 0.33%   |
| Realtek Semiconductor       | 10       | 10     | 0.3%    |
| Corsair                     | 10       | 16     | 0.3%    |
| Unknown                     | 10       | 11     | 0.3%    |
| Transcend                   | 9        | 10     | 0.27%   |
| Apple                       | 9        | 10     | 0.27%   |
| Apacer                      | 9        | 12     | 0.27%   |
| XPG                         | 8        | 10     | 0.24%   |
| MAXIO Technology (Hangzhou) | 8        | 8      | 0.24%   |
| Team                        | 7        | 9      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                   | 61       | 1.63%   |
| Kingston SA400S37240G 240GB SSD                   | 56       | 1.49%   |
| Seagate ST1000DM010-2EP102 1TB                    | 43       | 1.15%   |
| Seagate ST3500418AS 500GB                         | 30       | 0.8%    |
| Samsung SSD 860 EVO 500GB                         | 30       | 0.8%    |
| Crucial CT240BX500SSD1 240GB                      | 28       | 0.75%   |
| Kingston SA400S37120G 120GB SSD                   | 27       | 0.72%   |
| Seagate ST1000DM003-1CH162 1TB                    | 26       | 0.69%   |
| Toshiba DT01ACA100 1TB                            | 25       | 0.67%   |
| Samsung SSD 850 EVO 250GB                         | 25       | 0.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 24       | 0.64%   |
| Kingston SA400S37480G 480GB SSD                   | 24       | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 23       | 0.61%   |
| Seagate ST1000DM003-1ER162 1TB                    | 23       | 0.61%   |
| Toshiba HDWD110 1TB                               | 22       | 0.59%   |
| Kingston SV300S37A120G 120GB SSD                  | 22       | 0.59%   |
| Samsung NVMe SSD Drive 1TB                        | 21       | 0.56%   |
| Samsung NVMe SSD Drive 500GB                      | 20       | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB                    | 18       | 0.48%   |
| Seagate ST31000528AS 1TB                          | 17       | 0.45%   |
| Seagate ST2000DM008-2FR102 2TB                    | 17       | 0.45%   |
| Samsung SSD 850 EVO 500GB                         | 17       | 0.45%   |
| Seagate ST3500413AS 500GB                         | 16       | 0.43%   |
| Crucial CT500MX500SSD1 500GB                      | 16       | 0.43%   |
| Toshiba DT01ACA050 500GB                          | 15       | 0.4%    |
| SanDisk NVMe SSD Drive 500GB                      | 15       | 0.4%    |
| Unknown SD/MMC/MS PRO 16GB                        | 14       | 0.37%   |
| Seagate ST4000DM004-2CV104 4TB                    | 14       | 0.37%   |
| Seagate ST3500312CS 500GB                         | 14       | 0.37%   |
| Seagate ST1000DM003-1SB102 1TB                    | 14       | 0.37%   |
| Crucial CT1000MX500SSD1 1TB                       | 14       | 0.37%   |
| Toshiba DT01ACA200 2TB                            | 13       | 0.35%   |
| SanDisk NVMe SSD Drive 1TB                        | 13       | 0.35%   |
| Samsung SSD 840 EVO 250GB                         | 13       | 0.35%   |
| Seagate ST3250310AS 250GB                         | 12       | 0.32%   |
| Seagate ST2000DM001-1CH164 2TB                    | 12       | 0.32%   |
| Samsung SSD 870 EVO 1TB                           | 12       | 0.32%   |
| Samsung HD103SJ 1TB                               | 12       | 0.32%   |
| Seagate ST4000DM000-1F2168 4TB                    | 11       | 0.29%   |
| Seagate ST31000524AS 1TB                          | 11       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 663      | 998    | 37.84%  |
| WDC                 | 558      | 788    | 31.85%  |
| Hitachi             | 155      | 191    | 8.85%   |
| Toshiba             | 148      | 230    | 8.45%   |
| Samsung Electronics | 120      | 160    | 6.85%   |
| Maxtor              | 46       | 64     | 2.63%   |
| HGST                | 23       | 31     | 1.31%   |
| Unknown             | 15       | 20     | 0.86%   |
| Apple               | 6        | 7      | 0.34%   |
| USB3.0              | 4        | 5      | 0.23%   |
| Hewlett-Packard     | 4        | 7      | 0.23%   |
| QUANTUM             | 2        | 2      | 0.11%   |
| External            | 2        | 2      | 0.11%   |
| TDAS                | 1        | 3      | 0.06%   |
| Intenso             | 1        | 1      | 0.06%   |
| Fujitsu             | 1        | 1      | 0.06%   |
| ExcelStor           | 1        | 1      | 0.06%   |
| ASMT109x            | 1        | 2      | 0.06%   |
| ACASIS              | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 208      | 300    | 18.79%  |
| Kingston            | 175      | 236    | 15.81%  |
| Crucial             | 106      | 131    | 9.58%   |
| SanDisk             | 105      | 137    | 9.49%   |
| WDC                 | 54       | 68     | 4.88%   |
| China               | 48       | 55     | 4.34%   |
| A-DATA Technology   | 38       | 48     | 3.43%   |
| PNY                 | 27       | 34     | 2.44%   |
| Intel               | 26       | 31     | 2.35%   |
| Intenso             | 19       | 23     | 1.72%   |
| Patriot             | 18       | 30     | 1.63%   |
| SPCC                | 17       | 25     | 1.54%   |
| OCZ                 | 17       | 20     | 1.54%   |
| Toshiba             | 13       | 15     | 1.17%   |
| GOODRAM             | 13       | 16     | 1.17%   |
| Micron Technology   | 11       | 12     | 0.99%   |
| Lexar               | 11       | 11     | 0.99%   |
| KingSpec            | 10       | 13     | 0.9%    |
| Transcend           | 9        | 10     | 0.81%   |
| Gigabyte Technology | 9        | 16     | 0.81%   |
| Apacer              | 9        | 12     | 0.81%   |
| SK hynix            | 8        | 8      | 0.72%   |
| Hewlett-Packard     | 8        | 9      | 0.72%   |
| Corsair             | 8        | 14     | 0.72%   |
| Team                | 7        | 9      | 0.63%   |
| SABRENT             | 7        | 7      | 0.63%   |
| Netac               | 7        | 9      | 0.63%   |
| Leven               | 7        | 8      | 0.63%   |
| LITEON              | 5        | 6      | 0.45%   |
| Unknown             | 5        | 6      | 0.45%   |
| Verbatim            | 4        | 4      | 0.36%   |
| Super Talent        | 4        | 5      | 0.36%   |
| Seagate             | 3        | 6      | 0.27%   |
| Plextor             | 3        | 4      | 0.27%   |
| Pioneer             | 3        | 3      | 0.27%   |
| Mushkin             | 3        | 3      | 0.27%   |
| KIOXIA-EXCERIA      | 3        | 7      | 0.27%   |
| Drevo               | 3        | 4      | 0.27%   |
| Acer                | 3        | 5      | 0.27%   |
| Zheino              | 2        | 2      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1373     | 2514   | 49.48%  |
| SSD     | 937      | 1449   | 33.77%  |
| NVMe    | 378      | 571    | 13.62%  |
| Unknown | 79       | 104    | 2.85%   |
| MMC     | 8        | 9      | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1830     | 3890   | 78.07%  |
| NVMe | 373      | 554    | 15.91%  |
| SAS  | 133      | 194    | 5.67%   |
| MMC  | 8        | 9      | 0.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1411     | 2330   | 57.45%  |
| 0.51-1.0   | 642      | 978    | 26.14%  |
| 1.01-2.0   | 233      | 341    | 9.49%   |
| 3.01-4.0   | 70       | 152    | 2.85%   |
| 2.01-3.0   | 50       | 74     | 2.04%   |
| 4.01-10.0  | 42       | 60     | 1.71%   |
| 10.01-20.0 | 7        | 27     | 0.29%   |
| 20.01-50.0 | 1        | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 611      | 29.83%  |
| 251-500        | 459      | 22.41%  |
| 501-1000       | 303      | 14.79%  |
| 1001-2000      | 179      | 8.74%   |
| 51-100         | 150      | 7.32%   |
| More than 3000 | 128      | 6.25%   |
| 21-50          | 80       | 3.91%   |
| 2001-3000      | 64       | 3.13%   |
| 1-20           | 55       | 2.69%   |
| Unknown        | 19       | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 851      | 39.88%  |
| 21-50          | 475      | 22.26%  |
| 51-100         | 244      | 11.43%  |
| 101-250        | 191      | 8.95%   |
| 251-500        | 126      | 5.9%    |
| 501-1000       | 94       | 4.4%    |
| 1001-2000      | 60       | 2.81%   |
| More than 3000 | 56       | 2.62%   |
| Unknown        | 19       | 0.89%   |
| 2001-3000      | 18       | 0.84%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD30EFRX-68EUZN0 3TB                 | 2        | 2      | 4.17%   |
| HGST HTS541010A9E680 1TB                 | 2        | 2      | 4.17%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1        | 1      | 2.08%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1        | 1      | 2.08%   |
| WDC WD5000AAKS-00V1A0 500GB              | 1        | 1      | 2.08%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1        | 1      | 2.08%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1        | 1      | 2.08%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1        | 1      | 2.08%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1        | 2      | 2.08%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1        | 1      | 2.08%   |
| WDC WD Green 2.5 1000GB                  | 1        | 1      | 2.08%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1        | 1      | 2.08%   |
| Toshiba MQ01ABD100 1TB                   | 1        | 1      | 2.08%   |
| Toshiba MK8046GSX 80GB                   | 1        | 1      | 2.08%   |
| Toshiba MK3265GSX 320GB                  | 1        | 1      | 2.08%   |
| Toshiba MG03ACA200 2TB                   | 1        | 1      | 2.08%   |
| Toshiba DT01ACA100 1TB                   | 1        | 1      | 2.08%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1        | 1      | 2.08%   |
| Seagate ST9500420AS 500GB                | 1        | 1      | 2.08%   |
| Seagate ST8000DM004-2CX188 8TB           | 1        | 1      | 2.08%   |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1      | 2.08%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 2.08%   |
| Seagate ST3500514NS 500GB                | 1        | 1      | 2.08%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 2.08%   |
| Seagate ST3500312CS 500GB                | 1        | 1      | 2.08%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 2.08%   |
| Seagate ST3320620AS 320GB                | 1        | 1      | 2.08%   |
| Seagate ST3250318AS 250GB                | 1        | 1      | 2.08%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 1      | 2.08%   |
| Seagate ST3160310CS 160GB                | 1        | 1      | 2.08%   |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 1        | 1      | 2.08%   |
| Seagate ST2000DX002-2DV164 2TB           | 1        | 1      | 2.08%   |
| Seagate ST2000DM008-2FR102 2TB           | 1        | 1      | 2.08%   |
| Seagate ST2000DM001-9YN164 2TB           | 1        | 1      | 2.08%   |
| Seagate ST2000DL003-9VT166 2TB           | 1        | 1      | 2.08%   |
| Seagate ST1000DM003-1ER162 1TB           | 1        | 1      | 2.08%   |
| Samsung Electronics HD154UI 1TB          | 1        | 1      | 2.08%   |
| OCZ VERTEX3 120GB SSD                    | 1        | 1      | 2.08%   |
| Maxtor STM3320613AS 320GB                | 1        | 1      | 2.08%   |
| Kingston SV300S37A120G 120GB SSD         | 1        | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 18     | 36.17%  |
| WDC                 | 11       | 12     | 23.4%   |
| Toshiba             | 6        | 6      | 12.77%  |
| HGST                | 3        | 3      | 6.38%   |
| Kingston            | 2        | 2      | 4.26%   |
| A-DATA Technology   | 2        | 2      | 4.26%   |
| Silicon Motion      | 1        | 1      | 2.13%   |
| Samsung Electronics | 1        | 1      | 2.13%   |
| OCZ                 | 1        | 1      | 2.13%   |
| Maxtor              | 1        | 1      | 2.13%   |
| Intel               | 1        | 1      | 2.13%   |
| China               | 1        | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 18     | 47.22%  |
| WDC                 | 9        | 10     | 25%     |
| Toshiba             | 5        | 5      | 13.89%  |
| HGST                | 3        | 3      | 8.33%   |
| Samsung Electronics | 1        | 1      | 2.78%   |
| Maxtor              | 1        | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 32       | 38     | 74.42%  |
| SSD  | 9        | 9      | 20.93%  |
| NVMe | 2        | 2      | 4.65%   |

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
| Detected | 1839     | 4284   | 91.45%  |
| Works    | 130      | 314    | 6.46%   |
| Malfunc  | 42       | 49     | 2.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1261     | 49.22%  |
| AMD                              | 568      | 22.17%  |
| Samsung Electronics              | 120      | 4.68%   |
| Nvidia                           | 92       | 3.59%   |
| SanDisk                          | 69       | 2.69%   |
| ASMedia Technology               | 68       | 2.65%   |
| JMicron Technology               | 61       | 2.38%   |
| Phison Electronics               | 46       | 1.8%    |
| Marvell Technology Group         | 44       | 1.72%   |
| Kingston Technology Company      | 36       | 1.41%   |
| Silicon Motion                   | 31       | 1.21%   |
| VIA Technologies                 | 27       | 1.05%   |
| Micron/Crucial Technology        | 25       | 0.98%   |
| ADATA Technology                 | 13       | 0.51%   |
| Silicon Image                    | 12       | 0.47%   |
| SK hynix                         | 10       | 0.39%   |
| Realtek Semiconductor            | 10       | 0.39%   |
| MAXIO Technology (Hangzhou)      | 9        | 0.35%   |
| Seagate Technology               | 8        | 0.31%   |
| KIOXIA                           | 7        | 0.27%   |
| Silicon Integrated Systems [SiS] | 6        | 0.23%   |
| Broadcom / LSI                   | 6        | 0.23%   |
| Toshiba America Info Systems     | 5        | 0.2%    |
| Micron Technology                | 4        | 0.16%   |
| Shenzhen Longsys Electronics     | 3        | 0.12%   |
| INNOGRIT                         | 3        | 0.12%   |
| OCZ Technology Group             | 2        | 0.08%   |
| Integrated Technology Express    | 2        | 0.08%   |
| Apple                            | 2        | 0.08%   |
| Union Memory (Shenzhen)          | 1        | 0.04%   |
| TenaFe                           | 1        | 0.04%   |
| Solid State Storage Technology   | 1        | 0.04%   |
| Promise Technology               | 1        | 0.04%   |
| Netac Technology                 | 1        | 0.04%   |
| LSI Logic / Symbios Logic        | 1        | 0.04%   |
| Lite-On Technology               | 1        | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.04%   |
| HighPoint Technologies           | 1        | 0.04%   |
| Hewlett-Packard                  | 1        | 0.04%   |
| Beijing Starblaze Technology     | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 297      | 8.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 166      | 4.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 164      | 4.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 131      | 3.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 118      | 3.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 112      | 3.32%   |
| AMD 400 Series Chipset SATA Controller                                                  | 99       | 2.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 88       | 2.61%   |
| Intel SATA Controller [RAID mode]                                                       | 84       | 2.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 80       | 2.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 76       | 2.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 68       | 2.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 61       | 1.81%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 61       | 1.81%   |
| Nvidia MCP61 SATA Controller                                                            | 51       | 1.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 51       | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 48       | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 47       | 1.39%   |
| AMD 500 Series Chipset SATA Controller                                                  | 46       | 1.36%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 38       | 1.13%   |
| Nvidia MCP61 IDE                                                                        | 35       | 1.04%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 35       | 1.04%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 34       | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 32       | 0.95%   |
| AMD FCH SATA Controller D                                                               | 29       | 0.86%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 27       | 0.8%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 27       | 0.8%    |
| AMD 300 Series Chipset SATA Controller                                                  | 27       | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 26       | 0.77%   |
| Phison E12 NVMe Controller                                                              | 26       | 0.77%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 24       | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 24       | 0.71%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 23       | 0.68%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 23       | 0.68%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 23       | 0.68%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 22       | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 22       | 0.65%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 20       | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 19       | 0.56%   |
| AMD FCH IDE Controller                                                                  | 19       | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1397     | 53.32%  |
| IDE  | 690      | 26.34%  |
| NVMe | 371      | 14.16%  |
| RAID | 147      | 5.61%   |
| SAS  | 9        | 0.34%   |
| SCSI | 6        | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1301     | 66.58%  |
| AMD    | 653      | 33.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 37       | 1.88%   |
| AMD Ryzen 5 3600 6-Core Processor           | 31       | 1.58%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 27       | 1.38%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 25       | 1.27%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 25       | 1.27%   |
| Intel Pentium 4 CPU 3.00GHz                 | 18       | 0.92%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 18       | 0.92%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 18       | 0.92%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 18       | 0.92%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 17       | 0.87%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 17       | 0.87%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 16       | 0.82%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 16       | 0.82%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 16       | 0.82%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 16       | 0.82%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 16       | 0.82%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 16       | 0.82%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 15       | 0.76%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 15       | 0.76%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 14       | 0.71%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 14       | 0.71%   |
| AMD FX-8350 Eight-Core Processor            | 14       | 0.71%   |
| AMD FX-6300 Six-Core Processor              | 14       | 0.71%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 13       | 0.66%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 13       | 0.66%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 13       | 0.66%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 12       | 0.61%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 12       | 0.61%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 12       | 0.61%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 12       | 0.61%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 12       | 0.61%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 12       | 0.61%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 11       | 0.56%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 11       | 0.56%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 10       | 0.51%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 10       | 0.51%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 10       | 0.51%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 10       | 0.51%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 10       | 0.51%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 10       | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 348      | 17.76%  |
| Intel Core i7           | 192      | 9.8%    |
| Intel Core i3           | 152      | 7.76%   |
| AMD Ryzen 5             | 129      | 6.58%   |
| Intel Xeon              | 93       | 4.75%   |
| Intel Core 2 Duo        | 91       | 4.65%   |
| AMD FX                  | 77       | 3.93%   |
| AMD Ryzen 7             | 72       | 3.68%   |
| Intel Core 2 Quad       | 64       | 3.27%   |
| Intel Celeron           | 63       | 3.22%   |
| Intel Pentium Dual-Core | 58       | 2.96%   |
| Other                   | 48       | 2.45%   |
| Intel Pentium Dual      | 46       | 2.35%   |
| Intel Pentium           | 44       | 2.25%   |
| AMD Ryzen 9             | 44       | 2.25%   |
| AMD Athlon II X2        | 41       | 2.09%   |
| Intel Pentium 4         | 39       | 1.99%   |
| AMD Athlon 64 X2        | 33       | 1.68%   |
| AMD Ryzen 3             | 31       | 1.58%   |
| AMD A8                  | 26       | 1.33%   |
| AMD Phenom II X4        | 24       | 1.23%   |
| Intel Core 2            | 19       | 0.97%   |
| AMD A6                  | 18       | 0.92%   |
| AMD A10                 | 18       | 0.92%   |
| AMD A4                  | 17       | 0.87%   |
| AMD Athlon              | 16       | 0.82%   |
| Intel Core i9           | 15       | 0.77%   |
| AMD Sempron             | 14       | 0.71%   |
| AMD Phenom II X6        | 13       | 0.66%   |
| Intel Atom              | 12       | 0.61%   |
| AMD Athlon II X4        | 12       | 0.61%   |
| Intel Pentium D         | 10       | 0.51%   |
| AMD Athlon II X3        | 9        | 0.46%   |
| AMD Athlon 64           | 7        | 0.36%   |
| Intel Pentium Gold      | 6        | 0.31%   |
| AMD Phenom              | 6        | 0.31%   |
| AMD Phenom II X2        | 4        | 0.2%    |
| AMD E1                  | 4        | 0.2%    |
| AMD E                   | 4        | 0.2%    |
| AMD Athlon Dual Core    | 4        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 750      | 38.25%  |
| 2      | 651      | 33.2%   |
| 6      | 211      | 10.76%  |
| 8      | 135      | 6.88%   |
| 1      | 105      | 5.35%   |
| 3      | 35       | 1.78%   |
| 12     | 34       | 1.73%   |
| 16     | 20       | 1.02%   |
| 10     | 14       | 0.71%   |
| 28     | 2        | 0.1%    |
| 14     | 2        | 0.1%    |
| 24     | 1        | 0.05%   |
| 20     | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1938     | 99.18%  |
| 2      | 16       | 0.82%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1024     | 52.38%  |
| 2      | 931      | 47.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1925     | 98.52%  |
| 32-bit         | 28       | 1.43%   |
| Unknown        | 1        | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 199      | 10.01%  |
| Unknown    | 188      | 9.45%   |
| 0x1067a    | 152      | 7.64%   |
| 0x206a7    | 144      | 7.24%   |
| 0x306a9    | 120      | 6.03%   |
| 0x506e3    | 71       | 3.57%   |
| 0x6fd      | 56       | 2.82%   |
| 0x06000852 | 56       | 2.82%   |
| 0x08701021 | 53       | 2.66%   |
| 0x010000c8 | 45       | 2.26%   |
| 0x906ea    | 35       | 1.76%   |
| 0x0800820d | 35       | 1.76%   |
| 0x906e9    | 34       | 1.71%   |
| 0x6fb      | 32       | 1.61%   |
| 0x06001119 | 31       | 1.56%   |
| 0xa0655    | 26       | 1.31%   |
| 0xa0653    | 23       | 1.16%   |
| 0x10676    | 20       | 1.01%   |
| 0x0600063e | 20       | 1.01%   |
| 0x20655    | 19       | 0.96%   |
| 0x0a201016 | 19       | 0.96%   |
| 0x08108109 | 19       | 0.96%   |
| 0x010000db | 19       | 0.96%   |
| 0x106e5    | 17       | 0.85%   |
| 0xa0671    | 16       | 0.8%    |
| 0x906ed    | 16       | 0.8%    |
| 0x08001138 | 16       | 0.8%    |
| 0x06003106 | 16       | 0.8%    |
| 0x20652    | 15       | 0.75%   |
| 0x010000dc | 15       | 0.75%   |
| 0x906eb    | 14       | 0.7%    |
| 0x106a5    | 14       | 0.7%    |
| 0x6f6      | 13       | 0.65%   |
| 0x08701013 | 13       | 0.65%   |
| 0x306f2    | 12       | 0.6%    |
| 0x206d7    | 12       | 0.6%    |
| 0x03000027 | 12       | 0.6%    |
| 0xf43      | 11       | 0.55%   |
| 0x206c2    | 11       | 0.55%   |
| 0xf41      | 10       | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 228      | 11.64%  |
| Penryn           | 183      | 9.35%   |
| SandyBridge      | 162      | 8.27%   |
| IvyBridge        | 134      | 6.84%   |
| Core             | 120      | 6.13%   |
| K10              | 115      | 5.87%   |
| KabyLake         | 111      | 5.67%   |
| Piledriver       | 91       | 4.65%   |
| Zen 2            | 85       | 4.34%   |
| Skylake          | 76       | 3.88%   |
| Zen 3            | 67       | 3.42%   |
| Zen+             | 65       | 3.32%   |
| K8 Hammer        | 59       | 3.01%   |
| Zen              | 58       | 2.96%   |
| NetBurst         | 57       | 2.91%   |
| CometLake        | 52       | 2.66%   |
| Westmere         | 46       | 2.35%   |
| Nehalem          | 37       | 1.89%   |
| Unknown          | 35       | 1.79%   |
| Silvermont       | 21       | 1.07%   |
| Bulldozer        | 20       | 1.02%   |
| Steamroller      | 17       | 0.87%   |
| Excavator        | 17       | 0.87%   |
| Icelake          | 14       | 0.72%   |
| Alderlake Hybrid | 14       | 0.72%   |
| K10 Llano        | 12       | 0.61%   |
| Jaguar           | 11       | 0.56%   |
| Bonnell          | 10       | 0.51%   |
| Bobcat           | 9        | 0.46%   |
| Puma             | 8        | 0.41%   |
| Goldmont plus    | 7        | 0.36%   |
| Broadwell        | 7        | 0.36%   |
| Tremont          | 3        | 0.15%   |
| K6               | 3        | 0.15%   |
| Goldmont         | 2        | 0.1%    |
| TigerLake        | 1        | 0.05%   |
| P6               | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 760      | 36.54%  |
| Intel                            | 671      | 32.26%  |
| AMD                              | 634      | 30.48%  |
| VIA Technologies                 | 8        | 0.38%   |
| Silicon Integrated Systems [SiS] | 2        | 0.1%    |
| Trident Microsystems             | 1        | 0.05%   |
| Silicon Motion                   | 1        | 0.05%   |
| Matrox Electronics Systems       | 1        | 0.05%   |
| ATI Technologies                 | 1        | 0.05%   |
| ASPEED Technology                | 1        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 111      | 5.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 82       | 3.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 70       | 3.28%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 67       | 3.14%   |
| Nvidia GK208B [GeForce GT 710]                                              | 56       | 2.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 51       | 2.39%   |
| Intel HD Graphics 530                                                       | 37       | 1.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 36       | 1.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 36       | 1.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 35       | 1.64%   |
| Nvidia GK208B [GeForce GT 730]                                              | 28       | 1.31%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 27       | 1.27%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 27       | 1.27%   |
| Nvidia GT218 [GeForce 210]                                                  | 24       | 1.13%   |
| Intel Core Processor Integrated Graphics Controller                         | 24       | 1.13%   |
| AMD RS780L [Radeon 3000]                                                    | 24       | 1.13%   |
| Intel HD Graphics 630                                                       | 23       | 1.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 22       | 1.03%   |
| Nvidia GF119 [GeForce GT 610]                                               | 21       | 0.98%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 21       | 0.98%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 20       | 0.94%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 18       | 0.84%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 17       | 0.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 17       | 0.8%    |
| Nvidia GF108 [GeForce GT 730]                                               | 16       | 0.75%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 16       | 0.75%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 16       | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 15       | 0.7%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 14       | 0.66%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 14       | 0.66%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 14       | 0.66%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 13       | 0.61%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 13       | 0.61%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 13       | 0.61%   |
| Nvidia GF108 [GeForce GT 630]                                               | 12       | 0.56%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 12       | 0.56%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 12       | 0.56%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 12       | 0.56%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 12       | 0.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 11       | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 707      | 35.85%  |
| 1 x Intel                | 593      | 30.07%  |
| 1 x AMD                  | 570      | 28.9%   |
| 2 x AMD                  | 32       | 1.62%   |
| Intel + Nvidia           | 21       | 1.06%   |
| Intel + AMD              | 16       | 0.81%   |
| AMD + Nvidia             | 14       | 0.71%   |
| 1 x VIA                  | 8        | 0.41%   |
| 2 x Nvidia               | 4        | 0.2%    |
| 1 x SiS                  | 2        | 0.1%    |
| 2 x AMD + 1 x Nvidia     | 1        | 0.05%   |
| 1 x Trident Microsystems | 1        | 0.05%   |
| Nvidia + Silicon Motion  | 1        | 0.05%   |
| 1 x Matrox               | 1        | 0.05%   |
| 1 x ASPEED               | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1387     | 70.05%  |
| Proprietary | 449      | 22.68%  |
| Unknown     | 144      | 7.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 842      | 41.97%  |
| 0.01-0.5   | 285      | 14.21%  |
| 1.01-2.0   | 259      | 12.91%  |
| 0.51-1.0   | 252      | 12.56%  |
| 3.01-4.0   | 136      | 6.78%   |
| 7.01-8.0   | 126      | 6.28%   |
| 5.01-6.0   | 40       | 1.99%   |
| 8.01-16.0  | 40       | 1.99%   |
| 2.01-3.0   | 21       | 1.05%   |
| 16.01-24.0 | 4        | 0.2%    |
| 4.01-5.0   | 1        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 293      | 15.5%   |
| Dell                 | 186      | 9.84%   |
| Goldstar             | 181      | 9.58%   |
| Hewlett-Packard      | 157      | 8.31%   |
| Acer                 | 126      | 6.67%   |
| AOC                  | 104      | 5.5%    |
| Philips              | 90       | 4.76%   |
| Ancor Communications | 75       | 3.97%   |
| BenQ                 | 69       | 3.65%   |
| LG Electronics       | 45       | 2.38%   |
| ViewSonic            | 39       | 2.06%   |
| Unknown              | 34       | 1.8%    |
| Lenovo               | 27       | 1.43%   |
| Sony                 | 22       | 1.16%   |
| Unknown              | 22       | 1.16%   |
| Iiyama               | 18       | 0.95%   |
| NEC Computers        | 17       | 0.9%    |
| Fujitsu Siemens      | 17       | 0.9%    |
| Vizio                | 15       | 0.79%   |
| ASUSTek Computer     | 15       | 0.79%   |
| Sceptre Tech         | 14       | 0.74%   |
| Eizo                 | 13       | 0.69%   |
| Toshiba              | 12       | 0.63%   |
| MSI                  | 10       | 0.53%   |
| HPN                  | 10       | 0.53%   |
| Idek Iiyama          | 8        | 0.42%   |
| HannStar             | 8        | 0.42%   |
| Gateway              | 8        | 0.42%   |
| FUS                  | 7        | 0.37%   |
| Envision             | 7        | 0.37%   |
| AUS                  | 7        | 0.37%   |
| Sharp                | 6        | 0.32%   |
| Panasonic            | 6        | 0.32%   |
| Microstep            | 6        | 0.32%   |
| Medion               | 6        | 0.32%   |
| Pixio                | 5        | 0.26%   |
| MStar                | 5        | 0.26%   |
| KTC                  | 5        | 0.26%   |
| Insignia             | 5        | 0.26%   |
| CVT                  | 5        | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 22       | 1.1%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 9        | 0.45%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 8        | 0.4%    |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch             | 8        | 0.4%    |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                        | 7        | 0.35%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 6        | 0.3%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 6        | 0.3%    |
| Philips LCD Monitor FTV 1920x1080                                       | 6        | 0.3%    |
| Hewlett-Packard 2009 HWP2827 1600x900 440x250mm 19.9-inch               | 6        | 0.3%    |
| Unknown LCD Monitor SAMSUNG 3840x2160                                   | 5        | 0.25%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 5        | 0.25%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 4        | 0.2%    |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 4        | 0.2%    |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 480x270mm 21.7-inch   | 4        | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 4        | 0.2%    |
| Philips PHL 242M8 PHLC253 1920x1080 527x296mm 23.8-inch                 | 4        | 0.2%    |
| Philips FTV PHL01EA 1920x1080 640x360mm 28.9-inch                       | 4        | 0.2%    |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                        | 4        | 0.2%    |
| Hewlett-Packard 24f HPN3546 1920x1080 527x296mm 23.8-inch               | 4        | 0.2%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                     | 4        | 0.2%    |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                     | 4        | 0.2%    |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 4        | 0.2%    |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 4        | 0.2%    |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                      | 4        | 0.2%    |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                      | 4        | 0.2%    |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch        | 4        | 0.2%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch   | 4        | 0.2%    |
| Vizio E420VO VIZ0070 1920x1080 930x523mm 42.0-inch                      | 3        | 0.15%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                               | 3        | 0.15%   |
| Unknown LCD Monitor SAMSUNG                                             | 3        | 0.15%   |
| Toshiba TSB-TV TSB0206 1360x768 930x520mm 41.9-inch                     | 3        | 0.15%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch       | 3        | 0.15%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 3        | 0.15%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 3        | 0.15%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                    | 3        | 0.15%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                    | 3        | 0.15%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 3        | 0.15%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 3        | 0.15%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch   | 3        | 0.15%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768                        | 3        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 759      | 40.48%  |
| 1280x1024 (SXGA)   | 151      | 8.05%   |
| 3840x2160 (4K)     | 134      | 7.15%   |
| 1680x1050 (WSXGA+) | 112      | 5.97%   |
| 1366x768 (WXGA)    | 96       | 5.12%   |
| 1600x900 (HD+)     | 90       | 4.8%    |
| 1440x900 (WXGA+)   | 81       | 4.32%   |
| Unknown            | 75       | 4%      |
| 2560x1440 (QHD)    | 74       | 3.95%   |
| 1360x768           | 54       | 2.88%   |
| 1920x1200 (WUXGA)  | 39       | 2.08%   |
| 3440x1440          | 36       | 1.92%   |
| 3840x1080          | 34       | 1.81%   |
| 2560x1080          | 20       | 1.07%   |
| 1920x540           | 17       | 0.91%   |
| 1024x768 (XGA)     | 17       | 0.91%   |
| 1600x1200          | 9        | 0.48%   |
| 5760x1080          | 6        | 0.32%   |
| 1280x720 (HD)      | 5        | 0.27%   |
| 4480x1440          | 4        | 0.21%   |
| 3840x1600          | 4        | 0.21%   |
| 5760x2160          | 3        | 0.16%   |
| 3600x1080          | 3        | 0.16%   |
| 2560x1600          | 3        | 0.16%   |
| 1152x864           | 3        | 0.16%   |
| 6400x1440          | 2        | 0.11%   |
| 5440x1080          | 2        | 0.11%   |
| 5120x1440          | 2        | 0.11%   |
| 4480x1080          | 2        | 0.11%   |
| 3360x1080          | 2        | 0.11%   |
| 3200x1200          | 2        | 0.11%   |
| 3200x1080          | 2        | 0.11%   |
| 3120x1050          | 2        | 0.11%   |
| 2944x1080          | 2        | 0.11%   |
| 2720x1024          | 2        | 0.11%   |
| 2048x1152          | 2        | 0.11%   |
| 1280x960           | 2        | 0.11%   |
| 7680x1080          | 1        | 0.05%   |
| 6880x1440          | 1        | 0.05%   |
| 6400x1080          | 1        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 357      | 19.23%  |
| 24      | 161      | 8.67%   |
| 23      | 161      | 8.67%   |
| 21      | 160      | 8.62%   |
| 27      | 157      | 8.46%   |
| 19      | 146      | 7.87%   |
| 20      | 100      | 5.39%   |
| 18      | 99       | 5.33%   |
| 22      | 76       | 4.09%   |
| 31      | 75       | 4.04%   |
| 17      | 71       | 3.83%   |
| 34      | 39       | 2.1%    |
| 15      | 34       | 1.83%   |
| 40      | 28       | 1.51%   |
| 84      | 19       | 1.02%   |
| 72      | 19       | 1.02%   |
| 54      | 19       | 1.02%   |
| 32      | 16       | 0.86%   |
| 26      | 15       | 0.81%   |
| 65      | 8        | 0.43%   |
| 52      | 8        | 0.43%   |
| 36      | 7        | 0.38%   |
| 25      | 7        | 0.38%   |
| 49      | 6        | 0.32%   |
| 42      | 6        | 0.32%   |
| 28      | 6        | 0.32%   |
| 48      | 5        | 0.27%   |
| 46      | 4        | 0.22%   |
| 33      | 4        | 0.22%   |
| 74      | 3        | 0.16%   |
| 39      | 3        | 0.16%   |
| 37      | 3        | 0.16%   |
| 35      | 3        | 0.16%   |
| 29      | 3        | 0.16%   |
| 60      | 2        | 0.11%   |
| 58      | 2        | 0.11%   |
| 57      | 2        | 0.11%   |
| 47      | 2        | 0.11%   |
| 41      | 2        | 0.11%   |
| 30      | 2        | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 494      | 27.34%  |
| 501-600        | 449      | 24.85%  |
| Unknown        | 357      | 19.76%  |
| 301-350        | 104      | 5.76%   |
| 601-700        | 101      | 5.59%   |
| 351-400        | 81       | 4.48%   |
| 701-800        | 66       | 3.65%   |
| 1001-1500      | 60       | 3.32%   |
| 1501-2000      | 44       | 2.43%   |
| 801-900        | 37       | 2.05%   |
| 901-1000       | 10       | 0.55%   |
| 201-300        | 3        | 0.17%   |
| More than 2000 | 1        | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 954      | 54.7%   |
| Unknown | 326      | 18.69%  |
| 16/10   | 222      | 12.73%  |
| 5/4     | 135      | 7.74%   |
| 21/9    | 48       | 2.75%   |
| 4/3     | 34       | 1.95%   |
| 32/9    | 12       | 0.69%   |
| 6/5     | 7        | 0.4%    |
| 3/2     | 5        | 0.29%   |
| 1.00    | 1        | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 448      | 24.52%  |
| Unknown        | 357      | 19.54%  |
| 151-200        | 306      | 16.75%  |
| 301-350        | 160      | 8.76%   |
| 351-500        | 143      | 7.83%   |
| 141-150        | 142      | 7.77%   |
| More than 1000 | 91       | 4.98%   |
| 251-300        | 71       | 3.89%   |
| 501-1000       | 63       | 3.45%   |
| 101-110        | 26       | 1.42%   |
| 111-120        | 7        | 0.38%   |
| 131-140        | 6        | 0.33%   |
| 91-100         | 3        | 0.16%   |
| 81-90          | 2        | 0.11%   |
| 71-80          | 1        | 0.05%   |
| 121-130        | 1        | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1007     | 57.51%  |
| Unknown | 357      | 20.39%  |
| 101-120 | 241      | 13.76%  |
| 1-50    | 92       | 5.25%   |
| 121-160 | 38       | 2.17%   |
| 161-240 | 16       | 0.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1598     | 80.22%  |
| 2     | 224      | 11.24%  |
| 0     | 143      | 7.18%   |
| 3     | 25       | 1.26%   |
| 4     | 2        | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 1197     | 41.23%  |
| Intel                                 | 718      | 24.73%  |
| Qualcomm Atheros                      | 179      | 6.17%   |
| Ralink Technology                     | 112      | 3.86%   |
| Broadcom                              | 109      | 3.75%   |
| Nvidia                                | 78       | 2.69%   |
| TP-Link                               | 64       | 2.2%    |
| Ralink                                | 42       | 1.45%   |
| Broadcom Limited                      | 35       | 1.21%   |
| MediaTek                              | 34       | 1.17%   |
| Marvell Technology Group              | 27       | 0.93%   |
| NetGear                               | 24       | 0.83%   |
| D-Link                                | 23       | 0.79%   |
| VIA Technologies                      | 21       | 0.72%   |
| Samsung Electronics                   | 21       | 0.72%   |
| D-Link System                         | 21       | 0.72%   |
| Xiaomi                                | 17       | 0.59%   |
| Qualcomm Atheros Communications       | 14       | 0.48%   |
| Microsoft                             | 14       | 0.48%   |
| Huawei Technologies                   | 13       | 0.45%   |
| Edimax Technology                     | 10       | 0.34%   |
| ASIX Electronics                      | 10       | 0.34%   |
| ASUSTek Computer                      | 9        | 0.31%   |
| Aquantia                              | 9        | 0.31%   |
| Belkin Components                     | 8        | 0.28%   |
| OPPO Electronics                      | 6        | 0.21%   |
| Linksys                               | 6        | 0.21%   |
| Silicon Integrated Systems [SiS]      | 5        | 0.17%   |
| Qualcomm                              | 4        | 0.14%   |
| Motorola PCS                          | 4        | 0.14%   |
| Gemtek                                | 4        | 0.14%   |
| DisplayLink                           | 4        | 0.14%   |
| Sundance Technology Inc / IC Plus     | 3        | 0.1%    |
| Sitecom Europe                        | 3        | 0.1%    |
| Motorola                              | 3        | 0.1%    |
| JMicron Technology                    | 3        | 0.1%    |
| Apple                                 | 3        | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.1%    |
| ZTE WCDMA Technologies MSM            | 2        | 0.07%   |
| TRENDnet                              | 2        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 886      | 27.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 101      | 3.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 88       | 2.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 71       | 2.18%   |
| Intel I211 Gigabit Network Connection                             | 70       | 2.15%   |
| Intel Wi-Fi 6 AX200                                               | 65       | 2%      |
| Intel Ethernet Connection I217-LM                                 | 62       | 1.9%    |
| Ralink MT7601U Wireless Adapter                                   | 49       | 1.51%   |
| Nvidia MCP61 Ethernet                                             | 48       | 1.47%   |
| Intel Ethernet Connection (2) I219-V                              | 48       | 1.47%   |
| Realtek 802.11ac NIC                                              | 38       | 1.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 36       | 1.11%   |
| Intel Ethernet Controller I225-V                                  | 36       | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 33       | 1.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 31       | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 28       | 0.86%   |
| Intel Ethernet Connection I217-V                                  | 28       | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 26       | 0.8%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 25       | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 22       | 0.68%   |
| Intel Ethernet Connection (2) I218-V                              | 21       | 0.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 20       | 0.61%   |
| Intel Wireless-AC 9260                                            | 20       | 0.61%   |
| Intel Wireless 7265                                               | 20       | 0.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 19       | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 19       | 0.58%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 19       | 0.58%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 18       | 0.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 18       | 0.55%   |
| Ralink RT5370 Wireless Adapter                                    | 18       | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 17       | 0.52%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 16       | 0.49%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 15       | 0.46%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 15       | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15       | 0.46%   |
| Intel Ethernet Connection (7) I219-V                              | 15       | 0.46%   |
| Intel 82574L Gigabit Network Connection                           | 15       | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 13       | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13       | 0.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 12       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 289      | 26.76%  |
| Intel                                 | 252      | 23.33%  |
| Ralink Technology                     | 112      | 10.37%  |
| Qualcomm Atheros                      | 88       | 8.15%   |
| TP-Link                               | 61       | 5.65%   |
| Broadcom                              | 44       | 4.07%   |
| Ralink                                | 42       | 3.89%   |
| MediaTek                              | 26       | 2.41%   |
| NetGear                               | 24       | 2.22%   |
| D-Link                                | 23       | 2.13%   |
| D-Link System                         | 17       | 1.57%   |
| Qualcomm Atheros Communications       | 14       | 1.3%    |
| Microsoft                             | 14       | 1.3%    |
| Broadcom Limited                      | 11       | 1.02%   |
| Edimax Technology                     | 10       | 0.93%   |
| Belkin Components                     | 8        | 0.74%   |
| ASUSTek Computer                      | 8        | 0.74%   |
| Linksys                               | 6        | 0.56%   |
| Marvell Technology Group              | 4        | 0.37%   |
| Gemtek                                | 4        | 0.37%   |
| Sitecom Europe                        | 3        | 0.28%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.28%   |
| TRENDnet                              | 2        | 0.19%   |
| Senao                                 | 2        | 0.19%   |
| Philips (or NXP)                      | 2        | 0.19%   |
| Micro Star International              | 2        | 0.19%   |
| AVM                                   | 2        | 0.19%   |
| ZyXEL Communications                  | 1        | 0.09%   |
| ZyDAS                                 | 1        | 0.09%   |
| Xiaomi                                | 1        | 0.09%   |
| Panasonic (Matsushita)                | 1        | 0.09%   |
| Ovislink                              | 1        | 0.09%   |
| IMC Networks                          | 1        | 0.09%   |
| ADMtek                                | 1        | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 65       | 5.95%   |
| Ralink MT7601U Wireless Adapter                                | 49       | 4.48%   |
| Realtek 802.11ac NIC                                           | 38       | 3.48%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 36       | 3.29%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 33       | 3.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 31       | 2.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 26       | 2.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 20       | 1.83%   |
| Intel Wireless-AC 9260                                         | 20       | 1.83%   |
| Intel Wireless 7265                                            | 20       | 1.83%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 19       | 1.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 18       | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 18       | 1.65%   |
| Ralink RT5370 Wireless Adapter                                 | 18       | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 17       | 1.56%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 16       | 1.46%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 15       | 1.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12       | 1.1%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 12       | 1.1%    |
| Intel Wireless 7260                                            | 12       | 1.1%    |
| Qualcomm Atheros AR9271 802.11n                                | 11       | 1.01%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 11       | 1.01%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 11       | 1.01%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 10       | 0.91%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 10       | 0.91%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 10       | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 10       | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10       | 0.91%   |
| Intel Wireless 8260                                            | 10       | 0.91%   |
| Intel Wireless 3165                                            | 10       | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10       | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 9        | 0.82%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 9        | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9        | 0.82%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 8        | 0.73%   |
| Microsoft Xbox 360 Wireless Adapter                            | 8        | 0.73%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 8        | 0.73%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 7        | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7        | 0.64%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 7        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1087     | 51.98%  |
| Intel                             | 574      | 27.45%  |
| Qualcomm Atheros                  | 96       | 4.59%   |
| Nvidia                            | 78       | 3.73%   |
| Broadcom                          | 65       | 3.11%   |
| Broadcom Limited                  | 25       | 1.2%    |
| Marvell Technology Group          | 23       | 1.1%    |
| VIA Technologies                  | 21       | 1%      |
| Samsung Electronics               | 21       | 1%      |
| Xiaomi                            | 16       | 0.77%   |
| Huawei Technologies               | 12       | 0.57%   |
| ASIX Electronics                  | 10       | 0.48%   |
| Aquantia                          | 9        | 0.43%   |
| MediaTek                          | 8        | 0.38%   |
| OPPO Electronics                  | 6        | 0.29%   |
| Silicon Integrated Systems [SiS]  | 5        | 0.24%   |
| Qualcomm                          | 4        | 0.19%   |
| DisplayLink                       | 4        | 0.19%   |
| D-Link System                     | 4        | 0.19%   |
| TP-Link                           | 3        | 0.14%   |
| Sundance Technology Inc / IC Plus | 3        | 0.14%   |
| JMicron Technology                | 3        | 0.14%   |
| Apple                             | 3        | 0.14%   |
| Motorola PCS                      | 2        | 0.1%    |
| ZTE WCDMA Technologies MSM        | 1        | 0.05%   |
| Research In Motion                | 1        | 0.05%   |
| ICS Advent                        | 1        | 0.05%   |
| HMD Global                        | 1        | 0.05%   |
| Google                            | 1        | 0.05%   |
| GCT Semiconductor                 | 1        | 0.05%   |
| ASUSTek Computer                  | 1        | 0.05%   |
| Accton Technology                 | 1        | 0.05%   |
| 3Com                              | 1        | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 886      | 41.54%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 101      | 4.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 88       | 4.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 71       | 3.33%   |
| Intel I211 Gigabit Network Connection                             | 70       | 3.28%   |
| Intel Ethernet Connection I217-LM                                 | 62       | 2.91%   |
| Nvidia MCP61 Ethernet                                             | 48       | 2.25%   |
| Intel Ethernet Connection (2) I219-V                              | 48       | 2.25%   |
| Intel Ethernet Controller I225-V                                  | 36       | 1.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 28       | 1.31%   |
| Intel Ethernet Connection I217-V                                  | 28       | 1.31%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 25       | 1.17%   |
| Intel 82579V Gigabit Network Connection                           | 22       | 1.03%   |
| Intel Ethernet Connection (2) I218-V                              | 21       | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                             | 19       | 0.89%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 19       | 0.89%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 15       | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15       | 0.7%    |
| Intel Ethernet Connection (7) I219-V                              | 15       | 0.7%    |
| Intel 82574L Gigabit Network Connection                           | 15       | 0.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 13       | 0.61%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13       | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 12       | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12       | 0.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 12       | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11       | 0.52%   |
| Nvidia MCP73 Ethernet                                             | 11       | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10       | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 10       | 0.47%   |
| Intel 82578DC Gigabit Network Connection                          | 10       | 0.47%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 9        | 0.42%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 9        | 0.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 8        | 0.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8        | 0.38%   |
| Intel Ethernet Connection (12) I219-V                             | 8        | 0.38%   |
| Intel 82578DM Gigabit Network Connection                          | 8        | 0.38%   |
| Huawei ALP-AL00                                                   | 8        | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7        | 0.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1931     | 65.79%  |
| WiFi     | 977      | 33.29%  |
| Modem    | 22       | 0.75%   |
| Unknown  | 5        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1442     | 70.83%  |
| WiFi     | 592      | 29.08%  |
| Modem    | 1        | 0.05%   |
| Unknown  | 1        | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1321     | 67.12%  |
| 2     | 569      | 28.91%  |
| 3     | 58       | 2.95%   |
| 0     | 14       | 0.71%   |
| 5     | 3        | 0.15%   |
| 4     | 2        | 0.1%    |
| 7     | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1470     | 74.09%  |
| Yes  | 514      | 25.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 209      | 35.73%  |
| Cambridge Silicon Radio         | 126      | 21.54%  |
| Realtek Semiconductor           | 69       | 11.79%  |
| Broadcom                        | 35       | 5.98%   |
| ASUSTek Computer                | 25       | 4.27%   |
| Qualcomm Atheros Communications | 22       | 3.76%   |
| IMC Networks                    | 17       | 2.91%   |
| MediaTek                        | 12       | 2.05%   |
| Apple                           | 10       | 1.71%   |
| TP-Link                         | 8        | 1.37%   |
| Dynex                           | 7        | 1.2%    |
| Integrated System Solution      | 5        | 0.85%   |
| Belkin Components               | 5        | 0.85%   |
| Micro Star International        | 4        | 0.68%   |
| Foxconn / Hon Hai               | 4        | 0.68%   |
| Realtek                         | 3        | 0.51%   |
| Lite-On Technology              | 3        | 0.51%   |
| Actions                         | 3        | 0.51%   |
| Unknown                         | 3        | 0.51%   |
| Logitech                        | 2        | 0.34%   |
| ISSC                            | 2        | 0.34%   |
| Dell                            | 2        | 0.34%   |
| Sitecom Europe                  | 1        | 0.17%   |
| Ralink                          | 1        | 0.17%   |
| National Semiconductor          | 1        | 0.17%   |
| Mobile Action Technology        | 1        | 0.17%   |
| Marvell Semiconductor           | 1        | 0.17%   |
| Hewlett-Packard                 | 1        | 0.17%   |
| Fujitsu                         | 1        | 0.17%   |
| Edimax Technology               | 1        | 0.17%   |
| D-Link System                   | 1        | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 126      | 21.54%  |
| Realtek Bluetooth Radio                                  | 58       | 9.91%   |
| Intel AX200 Bluetooth                                    | 51       | 8.72%   |
| Intel Bluetooth wireless interface                       | 49       | 8.38%   |
| Intel AX210 Bluetooth                                    | 27       | 4.62%   |
| Intel Wireless-AC 3168 Bluetooth                         | 25       | 4.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 21       | 3.59%   |
| Intel AX201 Bluetooth                                    | 16       | 2.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 14       | 2.39%   |
| MediaTek Wireless_Device                                 | 12       | 2.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 12       | 2.05%   |
| IMC Networks Bluetooth Radio                             | 12       | 2.05%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 11       | 1.88%   |
| TP-Link UB500 Adapter                                    | 8        | 1.37%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 7        | 1.2%    |
| Qualcomm Atheros AR9462 Bluetooth                        | 6        | 1.03%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 6        | 1.03%   |
| ASUS Bluetooth Radio                                     | 6        | 1.03%   |
| Apple Bluetooth Host Controller                          | 6        | 1.03%   |
| Realtek RTL8821A Bluetooth                               | 5        | 0.85%   |
| Realtek  Bluetooth 4.2 Adapter                           | 5        | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 5        | 0.85%   |
| Qualcomm Atheros  Bluetooth Device                       | 4        | 0.68%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 4        | 0.68%   |
| Realtek Bluetooth Radio                                  | 3        | 0.51%   |
| Micro Star International Bluetooth Device                | 3        | 0.51%   |
| Lite-On Bluetooth Device                                 | 3        | 0.51%   |
| Integrated System Solution Bluetooth Device              | 3        | 0.51%   |
| Foxconn / Hon Hai Wireless_Device                        | 3        | 0.51%   |
| Broadcom HP Portable Bumble Bee                          | 3        | 0.51%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 3        | 0.51%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 3        | 0.51%   |
| ASUS Qualcomm Bluetooth 4.1                              | 3        | 0.51%   |
| ASUS ASUS USB-BT500                                      | 3        | 0.51%   |
| Actions general adapter                                  | 3        | 0.51%   |
| Unknown                                                  | 3        | 0.51%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 2        | 0.34%   |
| Qualcomm Atheros Bluetooth                               | 2        | 0.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 2        | 0.34%   |
| Logitech BT Mini-Receiver (HCI mode)                     | 2        | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1246     | 39.86%  |
| AMD                                          | 791      | 25.3%   |
| Nvidia                                       | 696      | 22.26%  |
| C-Media Electronics                          | 80       | 2.56%   |
| Creative Labs                                | 36       | 1.15%   |
| VIA Technologies                             | 24       | 0.77%   |
| Logitech                                     | 24       | 0.77%   |
| Kingston Technology                          | 15       | 0.48%   |
| JMTek                                        | 15       | 0.48%   |
| Generalplus Technology                       | 14       | 0.45%   |
| ASUSTek Computer                             | 14       | 0.45%   |
| Texas Instruments                            | 10       | 0.32%   |
| Razer USA                                    | 9        | 0.29%   |
| Plantronics                                  | 9        | 0.29%   |
| GN Netcom                                    | 9        | 0.29%   |
| Creative Technology                          | 8        | 0.26%   |
| Tenx Technology                              | 6        | 0.19%   |
| Silicon Integrated Systems [SiS]             | 6        | 0.19%   |
| Micro Star International                     | 5        | 0.16%   |
| Zoran Co. Personal Media Division (Nogatech) | 4        | 0.13%   |
| Realtek Semiconductor                        | 4        | 0.13%   |
| Focusrite-Novation                           | 4        | 0.13%   |
| SteelSeries ApS                              | 3        | 0.1%    |
| RODE Microphones                             | 3        | 0.1%    |
| KTMicro                                      | 3        | 0.1%    |
| Jieli Technology                             | 3        | 0.1%    |
| Corsair                                      | 3        | 0.1%    |
| Astro Gaming                                 | 3        | 0.1%    |
| Asahi Kasei Microsystems                     | 3        | 0.1%    |
| Yamaha                                       | 2        | 0.06%   |
| Turtle Beach                                 | 2        | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 2        | 0.06%   |
| Samsung Electronics                          | 2        | 0.06%   |
| Microsoft                                    | 2        | 0.06%   |
| Micronas                                     | 2        | 0.06%   |
| Ensoniq                                      | 2        | 0.06%   |
| DSEA A/S                                     | 2        | 0.06%   |
| DigiTech                                     | 2        | 0.06%   |
| DCMT Technology                              | 2        | 0.06%   |
| Cambridge Audio                              | 2        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 177      | 4.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 176      | 4.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 175      | 4.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 170      | 4.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 126      | 3.47%   |
| AMD Starship/Matisse HD Audio Controller                                          | 122      | 3.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 99       | 2.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 90       | 2.48%   |
| AMD Family 17h/19h HD Audio Controller                                            | 85       | 2.34%   |
| AMD FCH Azalia Controller                                                         | 83       | 2.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 74       | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 73       | 2.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 72       | 1.98%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 59       | 1.63%   |
| Intel 200 Series PCH HD Audio                                                     | 56       | 1.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 52       | 1.43%   |
| Nvidia MCP61 High Definition Audio                                                | 50       | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 48       | 1.32%   |
| Intel Cannon Lake PCH cAVS                                                        | 47       | 1.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 47       | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                                     | 43       | 1.18%   |
| Nvidia High Definition Audio Controller                                           | 41       | 1.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 39       | 1.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 39       | 1.07%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 38       | 1.05%   |
| Nvidia GF119 HDMI Audio Controller                                                | 35       | 0.96%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 35       | 0.96%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 35       | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                                     | 34       | 0.94%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 32       | 0.88%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 32       | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 27       | 0.74%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 27       | 0.74%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 27       | 0.74%   |
| AMD Navi 10 HDMI Audio                                                            | 26       | 0.72%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 25       | 0.69%   |
| AMD Kabini HDMI/DP Audio                                                          | 25       | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                                     | 24       | 0.66%   |
| Nvidia GP104 High Definition Audio Controller                                     | 24       | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                                | 23       | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 67       | 21.61%  |
| Kingston            | 42       | 13.55%  |
| Samsung Electronics | 34       | 10.97%  |
| Corsair             | 27       | 8.71%   |
| SK hynix            | 26       | 8.39%   |
| G.Skill             | 24       | 7.74%   |
| Crucial             | 24       | 7.74%   |
| Micron Technology   | 13       | 4.19%   |
| Team                | 10       | 3.23%   |
| Elpida              | 6        | 1.94%   |
| Unknown             | 5        | 1.61%   |
| Ramaxel Technology  | 3        | 0.97%   |
| Patriot             | 3        | 0.97%   |
| Nanya Technology    | 3        | 0.97%   |
| A-DATA Technology   | 3        | 0.97%   |
| Wilk                | 2        | 0.65%   |
| Unifosa             | 2        | 0.65%   |
| Qimonda             | 2        | 0.65%   |
| Avant               | 2        | 0.65%   |
| Transcend           | 1        | 0.32%   |
| SUPER KINGSTEK      | 1        | 0.32%   |
| Ramos Technology    | 1        | 0.32%   |
| PNY                 | 1        | 0.32%   |
| Patriot Memory      | 1        | 0.32%   |
| Goldkey             | 1        | 0.32%   |
| Golden Empire       | 1        | 0.32%   |
| F7852C80            | 1        | 0.32%   |
| CSX                 | 1        | 0.32%   |
| ASint Technology    | 1        | 0.32%   |
| Apacer              | 1        | 0.32%   |
| AMD                 | 1        | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 6        | 1.78%   |
| Unknown                                                | 5        | 1.48%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 4        | 1.18%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 3        | 0.89%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s     | 3        | 0.89%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s   | 3        | 0.89%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 3        | 0.89%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 3        | 0.89%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 3        | 0.89%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s  | 3        | 0.89%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s           | 2        | 0.59%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 2        | 0.59%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s           | 2        | 0.59%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                 | 2        | 0.59%   |
| Unknown RAM Module 4096MB DIMM                         | 2        | 0.59%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 2        | 0.59%   |
| Unknown RAM Module 2GB DIMM 667MT/s                    | 2        | 0.59%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 2        | 0.59%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 2        | 0.59%   |
| Unknown RAM Module 1GB DIMM DDR2                       | 2        | 0.59%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 2        | 0.59%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s            | 2        | 0.59%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 2        | 0.59%   |
| Unknown RAM Module 1024MB DIMM                         | 2        | 0.59%   |
| Team RAM TEAMGROUP-UD4-3200 8192MB DIMM DDR4 3733MT/s  | 2        | 0.59%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2933MT/s    | 2        | 0.59%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s     | 2        | 0.59%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 2        | 0.59%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 2        | 0.59%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 2        | 0.59%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s | 2        | 0.59%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s    | 2        | 0.59%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s    | 2        | 0.59%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 2        | 0.59%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s    | 2        | 0.59%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 0.59%   |
| Kingston RAM KCM633-ELC 1GB DIMM DDR2 2048MT/s         | 2        | 0.59%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s  | 2        | 0.59%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 2        | 0.59%   |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3600MT/s  | 2        | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 100      | 36.23%  |
| DDR3    | 98       | 35.51%  |
| Unknown | 29       | 10.51%  |
| DDR2    | 21       | 7.61%   |
| SDRAM   | 19       | 6.88%   |
| DDR     | 4        | 1.45%   |
| DDR5    | 3        | 1.09%   |
| LPDDR4  | 2        | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 253      | 94.05%  |
| SODIMM       | 13       | 4.83%   |
| Row Of Chips | 2        | 0.74%   |
| FB-DIMM      | 1        | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 100      | 32.89%  |
| 4096  | 82       | 26.97%  |
| 2048  | 50       | 16.45%  |
| 16384 | 27       | 8.88%   |
| 1024  | 27       | 8.88%   |
| 32768 | 16       | 5.26%   |
| 512   | 2        | 0.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 51       | 17%     |
| 1333    | 42       | 14%     |
| 3200    | 22       | 7.33%   |
| 3600    | 19       | 6.33%   |
| 800     | 17       | 5.67%   |
| Unknown | 15       | 5%      |
| 2133    | 10       | 3.33%   |
| 2400    | 9        | 3%      |
| 667     | 9        | 3%      |
| 3000    | 8        | 2.67%   |
| 2667    | 8        | 2.67%   |
| 1866    | 8        | 2.67%   |
| 3733    | 7        | 2.33%   |
| 1800    | 7        | 2.33%   |
| 2933    | 4        | 1.33%   |
| 2666    | 4        | 1.33%   |
| 1867    | 4        | 1.33%   |
| 1066    | 4        | 1.33%   |
| 400     | 4        | 1.33%   |
| 333     | 4        | 1.33%   |
| 4800    | 3        | 1%      |
| 3866    | 3        | 1%      |
| 2800    | 3        | 1%      |
| 3800    | 2        | 0.67%   |
| 3666    | 2        | 0.67%   |
| 3500    | 2        | 0.67%   |
| 3466    | 2        | 0.67%   |
| 3400    | 2        | 0.67%   |
| 3266    | 2        | 0.67%   |
| 2048    | 2        | 0.67%   |
| 49926   | 1        | 0.33%   |
| 5354    | 1        | 0.33%   |
| 5200    | 1        | 0.33%   |
| 4400    | 1        | 0.33%   |
| 4266    | 1        | 0.33%   |
| 4000    | 1        | 0.33%   |
| 3933    | 1        | 0.33%   |
| 3533    | 1        | 0.33%   |
| 3467    | 1        | 0.33%   |
| 3151    | 1        | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 31       | 27.19%  |
| Canon                 | 25       | 21.93%  |
| Brother Industries    | 21       | 18.42%  |
| Seiko Epson           | 15       | 13.16%  |
| Samsung Electronics   | 12       | 10.53%  |
| Ricoh                 | 2        | 1.75%   |
| Lexmark International | 2        | 1.75%   |
| Toshiba TEC           | 1        | 0.88%   |
| STMicroelectronics    | 1        | 0.88%   |
| QinHeng Electronics   | 1        | 0.88%   |
| Pantum                | 1        | 0.88%   |
| Konica Minolta        | 1        | 0.88%   |
| GG IMAGE              | 1        | 0.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Canon TS3100 series                                       | 3        | 2.63%   |
| Canon PIXMA MG2500 Series                                 | 3        | 2.63%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 2        | 1.75%   |
| Seiko Epson L3110 Series                                  | 2        | 1.75%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 1.75%   |
| Samsung C460 Series                                       | 2        | 1.75%   |
| HP OfficeJet 6950                                         | 2        | 1.75%   |
| HP LaserJet Professional P1102w                           | 2        | 1.75%   |
| HP ENVY 5000 series                                       | 2        | 1.75%   |
| HP ENVY 4520 series                                       | 2        | 1.75%   |
| HP DeskJet 2130 series                                    | 2        | 1.75%   |
| Canon MF4010 series                                       | 2        | 1.75%   |
| Canon LiDE 400                                            | 2        | 1.75%   |
| Brother HL-52x0 series                                    | 2        | 1.75%   |
| Brother HL-2130 series                                    | 2        | 1.75%   |
| Toshiba TEC e-STD120 USB                                  | 1        | 0.88%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.88%   |
| Seiko Epson XP-7100 Series                                | 1        | 0.88%   |
| Seiko Epson XP-225 Series                                 | 1        | 0.88%   |
| Seiko Epson XP-200 Series                                 | 1        | 0.88%   |
| Seiko Epson L805 Series                                   | 1        | 0.88%   |
| Seiko Epson L365 Series                                   | 1        | 0.88%   |
| Seiko Epson L360 Series                                   | 1        | 0.88%   |
| Seiko Epson L355 Series                                   | 1        | 0.88%   |
| Seiko Epson L120 Series                                   | 1        | 0.88%   |
| Seiko Epson ET-3850 Series                                | 1        | 0.88%   |
| Seiko Epson ET-2820 Series                                | 1        | 0.88%   |
| Seiko Epson ET-2710 Series                                | 1        | 0.88%   |
| Samsung SCX-483x 5x3x Series                              | 1        | 0.88%   |
| Samsung SCX-4623 Series                                   | 1        | 0.88%   |
| Samsung SCX-4200 series                                   | 1        | 0.88%   |
| Samsung SCX-3400 Series                                   | 1        | 0.88%   |
| Samsung ML-2950 Series                                    | 1        | 0.88%   |
| Samsung ML-2010P Mono Laser Printer                       | 1        | 0.88%   |
| Samsung M2070 Series                                      | 1        | 0.88%   |
| Samsung CLX-3300 Series                                   | 1        | 0.88%   |
| Ricoh SP C250SF                                           | 1        | 0.88%   |
| Ricoh SP 112SU                                            | 1        | 0.88%   |
| QinHeng CH340S                                            | 1        | 0.88%   |
| Pantum P2500W series                                      | 1        | 0.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 11       | 73.33%  |
| Hewlett-Packard | 3        | 20%     |
| Seiko Epson     | 1        | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 3        | 18.75%  |
| Canon CanoScan LiDE 100            | 2        | 12.5%   |
| Seiko Epson Scanner                | 1        | 6.25%   |
| HP ScanJet 2400c                   | 1        | 6.25%   |
| HP Scanjet 200                     | 1        | 6.25%   |
| HP PSC 1200                        | 1        | 6.25%   |
| Canon CanoScan LiDE 90             | 1        | 6.25%   |
| Canon CanoScan LiDE 60             | 1        | 6.25%   |
| Canon CanoScan LIDE 25             | 1        | 6.25%   |
| Canon CanoScan LiDE 220            | 1        | 6.25%   |
| Canon CanoScan LiDE 110            | 1        | 6.25%   |
| Canon CanoScan D660U               | 1        | 6.25%   |
| Canon CanoScan 8800F               | 1        | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 76       | 26.86%  |
| Microdia                      | 27       | 9.54%   |
| Microsoft                     | 23       | 8.13%   |
| Apple                         | 15       | 5.3%    |
| Sunplus Innovation Technology | 12       | 4.24%   |
| Samsung Electronics           | 11       | 3.89%   |
| Chicony Electronics           | 10       | 3.53%   |
| Generalplus Technology        | 9        | 3.18%   |
| ARC International             | 7        | 2.47%   |
| Z-Star Microelectronics       | 6        | 2.12%   |
| Jieli Technology              | 6        | 2.12%   |
| Cubeternet                    | 6        | 2.12%   |
| Realtek Semiconductor         | 4        | 1.41%   |
| Razer USA                     | 4        | 1.41%   |
| GEMBIRD                       | 4        | 1.41%   |
| Tobii Technology AB           | 3        | 1.06%   |
| IMC Networks                  | 3        | 1.06%   |
| HD 2MP WEBCAM                 | 3        | 1.06%   |
| Creative Technology           | 3        | 1.06%   |
| Aveo Technology               | 3        | 1.06%   |
| Arkmicro Technologies         | 3        | 1.06%   |
| A4Tech                        | 3        | 1.06%   |
| Xiongmai                      | 2        | 0.71%   |
| WaveRider Communications      | 2        | 0.71%   |
| Trust                         | 2        | 0.71%   |
| Suyin                         | 2        | 0.71%   |
| Sonix Technology              | 2        | 0.71%   |
| Pixart Imaging                | 2        | 0.71%   |
| MacroSilicon                  | 2        | 0.71%   |
| lihappe8                      | 2        | 0.71%   |
| KYE Systems (Mouse Systems)   | 2        | 0.71%   |
| Guillemot                     | 2        | 0.71%   |
| Genesys Logic                 | 2        | 0.71%   |
| AVerMedia Technologies        | 2        | 0.71%   |
| Alcor Micro                   | 2        | 0.71%   |
| Unknown                       | 1        | 0.35%   |
| Teslong Camera                | 1        | 0.35%   |
| Sweex                         | 1        | 0.35%   |
| Sunplus Technology            | 1        | 0.35%   |
| Silicon Motion                | 1        | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 21       | 7.37%   |
| Logitech HD Pro Webcam C920              | 14       | 4.91%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 13       | 4.56%   |
| Samsung Galaxy series, misc. (MTP mode)  | 11       | 3.86%   |
| Microsoft LifeCam HD-3000                | 11       | 3.86%   |
| ARC International Camera                 | 7        | 2.46%   |
| Microdia Webcam Vitade AF                | 6        | 2.11%   |
| Microdia USB 2.0 Camera                  | 6        | 2.11%   |
| Jieli USB PHY 2.0                        | 6        | 2.11%   |
| Chicony HP High Definition 1MP Webcam    | 6        | 2.11%   |
| Sunplus MTD Camera                       | 5        | 1.75%   |
| Logitech C920 PRO HD Webcam              | 5        | 1.75%   |
| Sunplus Full HD webcam                   | 4        | 1.4%    |
| Razer USA Gaming Webcam [Kiyo]           | 4        | 1.4%    |
| Logitech HD Webcam C615                  | 4        | 1.4%    |
| Generalplus GENERAL WEBCAM               | 4        | 1.4%    |
| Generalplus 808 Camera #9 (web-cam mode) | 4        | 1.4%    |
| Tobii AB EyeChip                         | 3        | 1.05%   |
| Microsoft LifeCam VX-500 [1357]          | 3        | 1.05%   |
| Microdia Integrated Camera               | 3        | 1.05%   |
| Logitech Webcam C925e                    | 3        | 1.05%   |
| Logitech Webcam C310                     | 3        | 1.05%   |
| Logitech HD Webcam C910                  | 3        | 1.05%   |
| Logitech C922 Pro Stream Webcam          | 3        | 1.05%   |
| HD 2MP WEBCAM HD 2MP WEBCAM              | 3        | 1.05%   |
| Cubeternet GL-UPC822 UVC WebCam          | 3        | 1.05%   |
| Z-Star Venus USB2.0 Camera               | 2        | 0.7%    |
| Z-Star Integrated Camera                 | 2        | 0.7%    |
| Xiongmai web camera                      | 2        | 0.7%    |
| WaveRider USB Live camera                | 2        | 0.7%    |
| Suyin HD WebCam                          | 2        | 0.7%    |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 2        | 0.7%    |
| Microsoft MicrosoftÂ LifeCam Cinema     | 2        | 0.7%    |
| Microsoft LifeCam VX-2000                | 2        | 0.7%    |
| Microsoft LifeCam HD-5000                | 2        | 0.7%    |
| Microdia USB Live camera                 | 2        | 0.7%    |
| Microdia PC-LM1E                         | 2        | 0.7%    |
| Microdia Camera                          | 2        | 0.7%    |
| Logitech Webcam C250                     | 2        | 0.7%    |
| Logitech QuickCam Pro for Notebooks      | 2        | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 3        | 75%     |
| AuthenTec             | 1        | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor             | 2        | 50%     |
| LighTuning ES603 Swipe Fingerprint Sensor | 1        | 25%     |
| AuthenTec AES2501 Fingerprint Sensor      | 1        | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2        | 15.38%  |
| Alcor Micro                       | 2        | 15.38%  |
| Advanced Card Systems             | 2        | 15.38%  |
| VASCO Data Security International | 1        | 7.69%   |
| SCM Microsystems                  | 1        | 7.69%   |
| Reiner SCT Kartensysteme          | 1        | 7.69%   |
| Kobil Systems                     | 1        | 7.69%   |
| Jing-Mold Enterprise              | 1        | 7.69%   |
| Fujitsu Siemens Computers         | 1        | 7.69%   |
| Chicony Electronics               | 1        | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                 | 2        | 15.38%  |
| Alcor Micro AU9540 Smartcard Reader                               | 2        | 15.38%  |
| VASCO Data Security International Digipass 905 SmartCard Reader   | 1        | 7.69%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader            | 1        | 7.69%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                   | 1        | 7.69%   |
| Kobil Systems KOBIL Class 3 Reader                                | 1        | 7.69%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard | 1        | 7.69%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                     | 1        | 7.69%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard              | 1        | 7.69%   |
| Advanced Card Systems ACR39U                                      | 1        | 7.69%   |
| Advanced Card Systems ACR1281 1S Dual Reader                      | 1        | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1572     | 78.96%  |
| 1     | 364      | 18.28%  |
| 2     | 48       | 2.41%   |
| 3     | 5        | 0.25%   |
| 4     | 2        | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 194      | 42.08%  |
| Net/wireless             | 154      | 33.41%  |
| Communication controller | 30       | 6.51%   |
| Multimedia controller    | 20       | 4.34%   |
| Unassigned class         | 14       | 3.04%   |
| Modem                    | 9        | 1.95%   |
| Chipcard                 | 9        | 1.95%   |
| Storage/raid             | 6        | 1.3%    |
| Sound                    | 5        | 1.08%   |
| Bluetooth                | 5        | 1.08%   |
| Fingerprint reader       | 4        | 0.87%   |
| Network                  | 2        | 0.43%   |
| Net/ethernet             | 2        | 0.43%   |
| Camera                   | 2        | 0.43%   |
| Storage/nvme             | 1        | 0.22%   |
| Storage/ide              | 1        | 0.22%   |
| Storage                  | 1        | 0.22%   |
| Dvb card                 | 1        | 0.22%   |
| Card reader              | 1        | 0.22%   |

