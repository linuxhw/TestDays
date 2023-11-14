Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

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

Total: 5617

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Venue 11 Pro 5130           | Notebook    | [5d63a1487d](https://linux-hardware.org/?probe=5d63a1487d) | Nov 06, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [4ef314d383](https://linux-hardware.org/?probe=4ef314d383) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [8447756322](https://linux-hardware.org/?probe=8447756322) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [af12dd22ba](https://linux-hardware.org/?probe=af12dd22ba) | Nov 06, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [6c8bb1840e](https://linux-hardware.org/?probe=6c8bb1840e) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [0facd311dc](https://linux-hardware.org/?probe=0facd311dc) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [27740d5118](https://linux-hardware.org/?probe=27740d5118) | Nov 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [38b95c0462](https://linux-hardware.org/?probe=38b95c0462) | Nov 05, 2023 |
| Dell          | Latitude E7450              | Notebook    | [71fe592aa3](https://linux-hardware.org/?probe=71fe592aa3) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [4bf4b470a0](https://linux-hardware.org/?probe=4bf4b470a0) | Nov 05, 2023 |
| HP            | 1497                        | Desktop     | [734abf0595](https://linux-hardware.org/?probe=734abf0595) | Nov 05, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [8b3f431a00](https://linux-hardware.org/?probe=8b3f431a00) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [9d8a12d929](https://linux-hardware.org/?probe=9d8a12d929) | Nov 05, 2023 |
| Gigabyte      | M5NM1AI-GB                  | Desktop     | [99e2275a93](https://linux-hardware.org/?probe=99e2275a93) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [dbd2e07499](https://linux-hardware.org/?probe=dbd2e07499) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [e98e6bb977](https://linux-hardware.org/?probe=e98e6bb977) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| Toshiba       | STI 001359                  | Desktop     | [ebf464dbb3](https://linux-hardware.org/?probe=ebf464dbb3) | Nov 04, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [1173519349](https://linux-hardware.org/?probe=1173519349) | Nov 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| TrekStor      | Surfbook W2                 | Notebook    | [cfee0c0363](https://linux-hardware.org/?probe=cfee0c0363) | Nov 04, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7a24e5115a](https://linux-hardware.org/?probe=7a24e5115a) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [c07d28d9bc](https://linux-hardware.org/?probe=c07d28d9bc) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [00cab2c4d1](https://linux-hardware.org/?probe=00cab2c4d1) | Nov 04, 2023 |
| Timi          | A35                         | Notebook    | [1baa5932cc](https://linux-hardware.org/?probe=1baa5932cc) | Nov 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [239e99c725](https://linux-hardware.org/?probe=239e99c725) | Nov 03, 2023 |
| Dell          | Latitude E6520              | Notebook    | [a0e05f5040](https://linux-hardware.org/?probe=a0e05f5040) | Nov 02, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [ea9f809740](https://linux-hardware.org/?probe=ea9f809740) | Nov 02, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [c5e282cbad](https://linux-hardware.org/?probe=c5e282cbad) | Nov 02, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4372a2d9eb](https://linux-hardware.org/?probe=4372a2d9eb) | Nov 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | U36SD                       | Notebook    | [e2045d61a5](https://linux-hardware.org/?probe=e2045d61a5) | Nov 02, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [ef9bc3cc1e](https://linux-hardware.org/?probe=ef9bc3cc1e) | Nov 02, 2023 |
| ONDA          | Tablet                      | Tablet      | [1f8b5d6c72](https://linux-hardware.org/?probe=1f8b5d6c72) | Nov 01, 2023 |
| Dell          | 0XCR8D A01                  | Desktop     | [bc8414b164](https://linux-hardware.org/?probe=bc8414b164) | Nov 01, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [6db0212093](https://linux-hardware.org/?probe=6db0212093) | Nov 01, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [73a395f017](https://linux-hardware.org/?probe=73a395f017) | Nov 01, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [319e545ba5](https://linux-hardware.org/?probe=319e545ba5) | Oct 31, 2023 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [3b667e2123](https://linux-hardware.org/?probe=3b667e2123) | Oct 31, 2023 |
| Pegatron      | EVANS                       | Desktop     | [3ea2a80843](https://linux-hardware.org/?probe=3ea2a80843) | Oct 31, 2023 |
| Pegatron      | EVANS                       | Desktop     | [52c3eeea68](https://linux-hardware.org/?probe=52c3eeea68) | Oct 31, 2023 |
| RCA           | W122SC24T2                  | Tablet      | [1313389b98](https://linux-hardware.org/?probe=1313389b98) | Oct 31, 2023 |
| RCA           | W122SC24T2                  | Tablet      | [f46f159a0c](https://linux-hardware.org/?probe=f46f159a0c) | Oct 31, 2023 |
| Sony          | SVS15116GAB                 | Notebook    | [03634a7731](https://linux-hardware.org/?probe=03634a7731) | Oct 30, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [185b65ebc1](https://linux-hardware.org/?probe=185b65ebc1) | Oct 30, 2023 |
| HP            | 21F5 0A                     | Desktop     | [097ce56daf](https://linux-hardware.org/?probe=097ce56daf) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [c447277c0b](https://linux-hardware.org/?probe=c447277c0b) | Oct 30, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [627ed781b5](https://linux-hardware.org/?probe=627ed781b5) | Oct 30, 2023 |
| HP            | 15                          | Notebook    | [1480b12f56](https://linux-hardware.org/?probe=1480b12f56) | Oct 30, 2023 |
| HP            | Notebook                    | Notebook    | [5538a0e3b2](https://linux-hardware.org/?probe=5538a0e3b2) | Oct 30, 2023 |
| HP            | Pavilion dv4                | Notebook    | [854806c6f4](https://linux-hardware.org/?probe=854806c6f4) | Oct 29, 2023 |
| HP            | 1998                        | Desktop     | [2182b05a45](https://linux-hardware.org/?probe=2182b05a45) | Oct 29, 2023 |
| HP            | ENVY 17                     | Notebook    | [8852bab8c1](https://linux-hardware.org/?probe=8852bab8c1) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [28f261fb9a](https://linux-hardware.org/?probe=28f261fb9a) | Oct 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1T600    | Notebook    | [97fbe59dd7](https://linux-hardware.org/?probe=97fbe59dd7) | Oct 29, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [e13de47400](https://linux-hardware.org/?probe=e13de47400) | Oct 29, 2023 |
| Lenovo        | ThinkPad E420 1141BTU       | Notebook    | [867e950bca](https://linux-hardware.org/?probe=867e950bca) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [a123ac023f](https://linux-hardware.org/?probe=a123ac023f) | Oct 29, 2023 |
| MSI           | Z370M MORTAR                | Desktop     | [0af3708cd3](https://linux-hardware.org/?probe=0af3708cd3) | Oct 29, 2023 |
| HP            | 18E4                        | Desktop     | [b192ce4f35](https://linux-hardware.org/?probe=b192ce4f35) | Oct 28, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [97eabba1a8](https://linux-hardware.org/?probe=97eabba1a8) | Oct 28, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [c2bc73c67b](https://linux-hardware.org/?probe=c2bc73c67b) | Oct 28, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [d48a91cce4](https://linux-hardware.org/?probe=d48a91cce4) | Oct 28, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [b9830b7f02](https://linux-hardware.org/?probe=b9830b7f02) | Oct 28, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [98c2ece6fd](https://linux-hardware.org/?probe=98c2ece6fd) | Oct 28, 2023 |
| HP            | ENVY 17                     | Notebook    | [aaa99aaa53](https://linux-hardware.org/?probe=aaa99aaa53) | Oct 27, 2023 |
| Acer          | TravelMate Spin P614RN-5    | Convertible | [e337a1e208](https://linux-hardware.org/?probe=e337a1e208) | Oct 27, 2023 |
| HCL Infosy... | HCL ME Laptop               | Notebook    | [a23dc90a3b](https://linux-hardware.org/?probe=a23dc90a3b) | Oct 27, 2023 |
| MSI           | Boston                      | Desktop     | [66f7505c8b](https://linux-hardware.org/?probe=66f7505c8b) | Oct 27, 2023 |
| Thomson       | WWNEO14C-4BK32F             | Notebook    | [516a5ee33b](https://linux-hardware.org/?probe=516a5ee33b) | Oct 27, 2023 |
| HP            | 2215                        | Desktop     | [01fd79c4fe](https://linux-hardware.org/?probe=01fd79c4fe) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [463b5f73b5](https://linux-hardware.org/?probe=463b5f73b5) | Oct 26, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [763e54c87b](https://linux-hardware.org/?probe=763e54c87b) | Oct 26, 2023 |
| HP            | G61                         | Notebook    | [d184a33522](https://linux-hardware.org/?probe=d184a33522) | Oct 26, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [67021475e9](https://linux-hardware.org/?probe=67021475e9) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [ec0dcdaa76](https://linux-hardware.org/?probe=ec0dcdaa76) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [4f4d354524](https://linux-hardware.org/?probe=4f4d354524) | Oct 26, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [ca4ce5575c](https://linux-hardware.org/?probe=ca4ce5575c) | Oct 26, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4699d107df](https://linux-hardware.org/?probe=4699d107df) | Oct 26, 2023 |
| LORD ELECT... | Guso G4x + ICH7 Series M... | Desktop     | [c6f81cf996](https://linux-hardware.org/?probe=c6f81cf996) | Oct 25, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3c8f87fe9e](https://linux-hardware.org/?probe=3c8f87fe9e) | Oct 25, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [e0534a1c2a](https://linux-hardware.org/?probe=e0534a1c2a) | Oct 25, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [cd1abadd3a](https://linux-hardware.org/?probe=cd1abadd3a) | Oct 25, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6f9c14dc54](https://linux-hardware.org/?probe=6f9c14dc54) | Oct 24, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [039878b1b2](https://linux-hardware.org/?probe=039878b1b2) | Oct 24, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [706967e8e6](https://linux-hardware.org/?probe=706967e8e6) | Oct 24, 2023 |
| Gigabyte      | B85M-D3V Plus               | Desktop     | [845b1f10ef](https://linux-hardware.org/?probe=845b1f10ef) | Oct 24, 2023 |
| Dell          | 0RCPW3 A03                  | Desktop     | [a461b9f3e7](https://linux-hardware.org/?probe=a461b9f3e7) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [905555c7d5](https://linux-hardware.org/?probe=905555c7d5) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [5f6d67d67e](https://linux-hardware.org/?probe=5f6d67d67e) | Oct 23, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [cd4e6f4d07](https://linux-hardware.org/?probe=cd4e6f4d07) | Oct 23, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [961b658ac5](https://linux-hardware.org/?probe=961b658ac5) | Oct 23, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | Notebook    | [52661c1969](https://linux-hardware.org/?probe=52661c1969) | Oct 22, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6f89b3f8ad](https://linux-hardware.org/?probe=6f89b3f8ad) | Oct 22, 2023 |
| ONDA          | Tablet                      | Tablet      | [2ef7c07bdf](https://linux-hardware.org/?probe=2ef7c07bdf) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ff9e1d6c16](https://linux-hardware.org/?probe=ff9e1d6c16) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9999b4b89a](https://linux-hardware.org/?probe=9999b4b89a) | Oct 22, 2023 |
| Dell          | Precision 7530              | Notebook    | [92f2a2c99e](https://linux-hardware.org/?probe=92f2a2c99e) | Oct 22, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [ef8715c7a7](https://linux-hardware.org/?probe=ef8715c7a7) | Oct 21, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [081a658255](https://linux-hardware.org/?probe=081a658255) | Oct 21, 2023 |
| TrekStor      | Surfbook W2                 | Notebook    | [001d67067b](https://linux-hardware.org/?probe=001d67067b) | Oct 21, 2023 |
| ONDA          | Tablet                      | Tablet      | [835a5e9d6d](https://linux-hardware.org/?probe=835a5e9d6d) | Oct 21, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [5536078e9f](https://linux-hardware.org/?probe=5536078e9f) | Oct 21, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [ef8c0bb04c](https://linux-hardware.org/?probe=ef8c0bb04c) | Oct 21, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [330cbe85c6](https://linux-hardware.org/?probe=330cbe85c6) | Oct 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a7ee33da8f](https://linux-hardware.org/?probe=a7ee33da8f) | Oct 21, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [11d8517f7e](https://linux-hardware.org/?probe=11d8517f7e) | Oct 20, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9ce038aa93](https://linux-hardware.org/?probe=9ce038aa93) | Oct 20, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [d8b8f7bafe](https://linux-hardware.org/?probe=d8b8f7bafe) | Oct 20, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [cb8d8311e7](https://linux-hardware.org/?probe=cb8d8311e7) | Oct 20, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [3dd8426b8f](https://linux-hardware.org/?probe=3dd8426b8f) | Oct 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [af96c09a64](https://linux-hardware.org/?probe=af96c09a64) | Oct 19, 2023 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [77079711d3](https://linux-hardware.org/?probe=77079711d3) | Oct 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7fed113f9b](https://linux-hardware.org/?probe=7fed113f9b) | Oct 19, 2023 |
| ALLDOCUBE     | KnoteGo                     | Tablet      | [17833d30dc](https://linux-hardware.org/?probe=17833d30dc) | Oct 19, 2023 |
| HP            | 829A                        | Mini pc     | [8a3f72e9ef](https://linux-hardware.org/?probe=8a3f72e9ef) | Oct 19, 2023 |
| Dell          | Latitude 5490               | Notebook    | [cdf021cc62](https://linux-hardware.org/?probe=cdf021cc62) | Oct 19, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [060a642de4](https://linux-hardware.org/?probe=060a642de4) | Oct 19, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [051cd3c21e](https://linux-hardware.org/?probe=051cd3c21e) | Oct 19, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d37e5bc4f2](https://linux-hardware.org/?probe=d37e5bc4f2) | Oct 19, 2023 |
| ASUSTek       | X751SA                      | Notebook    | [21a2a5b900](https://linux-hardware.org/?probe=21a2a5b900) | Oct 18, 2023 |
| ONDA          | Tablet                      | Tablet      | [6a43a8d57d](https://linux-hardware.org/?probe=6a43a8d57d) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [cde2726f48](https://linux-hardware.org/?probe=cde2726f48) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [2985805059](https://linux-hardware.org/?probe=2985805059) | Oct 18, 2023 |
| EPSON DIRE... | AT992E                      | Desktop     | [bdc9d825d8](https://linux-hardware.org/?probe=bdc9d825d8) | Oct 18, 2023 |
| EPSON DIRE... | AT992E                      | Desktop     | [ec5284109e](https://linux-hardware.org/?probe=ec5284109e) | Oct 18, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [c1ea75561b](https://linux-hardware.org/?probe=c1ea75561b) | Oct 18, 2023 |
| Sony          | VGN-FZ31Z                   | Notebook    | [9a6fd46a7d](https://linux-hardware.org/?probe=9a6fd46a7d) | Oct 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [03cf657f5a](https://linux-hardware.org/?probe=03cf657f5a) | Oct 17, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | Notebook    | [f1e77b51bc](https://linux-hardware.org/?probe=f1e77b51bc) | Oct 17, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [7116f7edd9](https://linux-hardware.org/?probe=7116f7edd9) | Oct 17, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [848b8d7c20](https://linux-hardware.org/?probe=848b8d7c20) | Oct 17, 2023 |
| Lenovo        | ThinkPad T440 20B7S1D200    | Notebook    | [43185c1e5b](https://linux-hardware.org/?probe=43185c1e5b) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd91b9ece9](https://linux-hardware.org/?probe=fd91b9ece9) | Oct 16, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [76e5cf1323](https://linux-hardware.org/?probe=76e5cf1323) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [e87c9aab74](https://linux-hardware.org/?probe=e87c9aab74) | Oct 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a0f3ae3d1a](https://linux-hardware.org/?probe=a0f3ae3d1a) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [0ca88d127f](https://linux-hardware.org/?probe=0ca88d127f) | Oct 16, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [77c1531b00](https://linux-hardware.org/?probe=77c1531b00) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [2960de2715](https://linux-hardware.org/?probe=2960de2715) | Oct 15, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [d22b6fa2e4](https://linux-hardware.org/?probe=d22b6fa2e4) | Oct 15, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [16a117accb](https://linux-hardware.org/?probe=16a117accb) | Oct 15, 2023 |
| HP            | Pavilion g7                 | Notebook    | [309ca4d5c7](https://linux-hardware.org/?probe=309ca4d5c7) | Oct 15, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [d43a466e59](https://linux-hardware.org/?probe=d43a466e59) | Oct 14, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [39e9986b39](https://linux-hardware.org/?probe=39e9986b39) | Oct 14, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6321b8063](https://linux-hardware.org/?probe=c6321b8063) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [35a5d0ac7c](https://linux-hardware.org/?probe=35a5d0ac7c) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [081856b4e9](https://linux-hardware.org/?probe=081856b4e9) | Oct 14, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [0db9d6a5cf](https://linux-hardware.org/?probe=0db9d6a5cf) | Oct 14, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [f4e7334b7e](https://linux-hardware.org/?probe=f4e7334b7e) | Oct 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [c2cbb1c407](https://linux-hardware.org/?probe=c2cbb1c407) | Oct 13, 2023 |
| HP            | 470 17 inch G9              | Notebook    | [d138f8f9f3](https://linux-hardware.org/?probe=d138f8f9f3) | Oct 13, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [17d1931208](https://linux-hardware.org/?probe=17d1931208) | Oct 13, 2023 |
| MSI           | B85M-E45                    | Desktop     | [6ad9d3ff3c](https://linux-hardware.org/?probe=6ad9d3ff3c) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [ffd832c09d](https://linux-hardware.org/?probe=ffd832c09d) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [c70591ee60](https://linux-hardware.org/?probe=c70591ee60) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [cc3dbe7ccd](https://linux-hardware.org/?probe=cc3dbe7ccd) | Oct 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [314d81343b](https://linux-hardware.org/?probe=314d81343b) | Oct 12, 2023 |
| Schenker      | XMG CORE (REN/M20)          | Notebook    | [48ee28954d](https://linux-hardware.org/?probe=48ee28954d) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [8c1ef64452](https://linux-hardware.org/?probe=8c1ef64452) | Oct 12, 2023 |
| HP            | Pavilion g7                 | Notebook    | [e276347e0a](https://linux-hardware.org/?probe=e276347e0a) | Oct 12, 2023 |
| Acer          | Aspire A317-55P             | Notebook    | [a4e8b9c99a](https://linux-hardware.org/?probe=a4e8b9c99a) | Oct 12, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [02414ff1af](https://linux-hardware.org/?probe=02414ff1af) | Oct 11, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [916bfc1646](https://linux-hardware.org/?probe=916bfc1646) | Oct 11, 2023 |
| Acer          | Aspire A317-55P             | Notebook    | [3805200b55](https://linux-hardware.org/?probe=3805200b55) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | Desktop     | [cc50dc0894](https://linux-hardware.org/?probe=cc50dc0894) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | Desktop     | [754748eac6](https://linux-hardware.org/?probe=754748eac6) | Oct 11, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [adda7a23c2](https://linux-hardware.org/?probe=adda7a23c2) | Oct 11, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [44a7bac1b9](https://linux-hardware.org/?probe=44a7bac1b9) | Oct 10, 2023 |
| AMI           | Intel                       | Desktop     | [1615dc16ba](https://linux-hardware.org/?probe=1615dc16ba) | Oct 10, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [df54ad11e5](https://linux-hardware.org/?probe=df54ad11e5) | Oct 10, 2023 |
| ASUSTek       | K42F                        | Notebook    | [0d099eb4f7](https://linux-hardware.org/?probe=0d099eb4f7) | Oct 10, 2023 |
| Lenovo        | Tiger Hill                  | Desktop     | [cdd9f65bf5](https://linux-hardware.org/?probe=cdd9f65bf5) | Oct 10, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [c4ae24b408](https://linux-hardware.org/?probe=c4ae24b408) | Oct 10, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [9b41869902](https://linux-hardware.org/?probe=9b41869902) | Oct 09, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [407c6f0e29](https://linux-hardware.org/?probe=407c6f0e29) | Oct 09, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [53e4e70567](https://linux-hardware.org/?probe=53e4e70567) | Oct 09, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [332ce6061d](https://linux-hardware.org/?probe=332ce6061d) | Oct 09, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [8984311ce7](https://linux-hardware.org/?probe=8984311ce7) | Oct 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [1eeecb8823](https://linux-hardware.org/?probe=1eeecb8823) | Oct 08, 2023 |
| HP            | Pavilion 15                 | Notebook    | [ae1e07dd63](https://linux-hardware.org/?probe=ae1e07dd63) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [067260a51f](https://linux-hardware.org/?probe=067260a51f) | Oct 08, 2023 |
| Shuttle       | FS110                       | Desktop     | [cd7c40ed57](https://linux-hardware.org/?probe=cd7c40ed57) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS08W0... | Notebook    | [24dee8bc07](https://linux-hardware.org/?probe=24dee8bc07) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [b82e5d0718](https://linux-hardware.org/?probe=b82e5d0718) | Oct 07, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [f347154767](https://linux-hardware.org/?probe=f347154767) | Oct 07, 2023 |
| UMAX          | N14R                        | Notebook    | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | Notebook    | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| Pegatron      | EVANS                       | Desktop     | [f798f24c90](https://linux-hardware.org/?probe=f798f24c90) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [299eee42c7](https://linux-hardware.org/?probe=299eee42c7) | Oct 07, 2023 |
| Alienware     | M14xR2                      | Notebook    | [3b7dd3717c](https://linux-hardware.org/?probe=3b7dd3717c) | Oct 07, 2023 |
| Dynabook      | PORTEGE X30W-J              | Convertible | [aa212009a2](https://linux-hardware.org/?probe=aa212009a2) | Oct 06, 2023 |
| Dell          | Precision 5530              | Notebook    | [38fdcea75f](https://linux-hardware.org/?probe=38fdcea75f) | Oct 06, 2023 |
| Thomson       | GEN360-4C128BK              | Notebook    | [ec04ddb0ba](https://linux-hardware.org/?probe=ec04ddb0ba) | Oct 06, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| Intel         | X99                         | Desktop     | [9bc14ff597](https://linux-hardware.org/?probe=9bc14ff597) | Oct 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [7add8932c3](https://linux-hardware.org/?probe=7add8932c3) | Oct 06, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [9be367f445](https://linux-hardware.org/?probe=9be367f445) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [ff815f228b](https://linux-hardware.org/?probe=ff815f228b) | Oct 05, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [b8f2dc6919](https://linux-hardware.org/?probe=b8f2dc6919) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [8313e4fb72](https://linux-hardware.org/?probe=8313e4fb72) | Oct 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [7eec2f8e4e](https://linux-hardware.org/?probe=7eec2f8e4e) | Oct 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [a80bc8f591](https://linux-hardware.org/?probe=a80bc8f591) | Oct 05, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a6668a2378](https://linux-hardware.org/?probe=a6668a2378) | Oct 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [de22cbed3e](https://linux-hardware.org/?probe=de22cbed3e) | Oct 04, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [040dc9b84b](https://linux-hardware.org/?probe=040dc9b84b) | Oct 04, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [c3e7936a83](https://linux-hardware.org/?probe=c3e7936a83) | Oct 04, 2023 |
| Dell          | 0RW199                      | Desktop     | [f829184aa0](https://linux-hardware.org/?probe=f829184aa0) | Oct 04, 2023 |
| Dell          | G3 3579                     | Notebook    | [7730315a91](https://linux-hardware.org/?probe=7730315a91) | Oct 04, 2023 |
| Lenovo        | Tiger Hill                  | Desktop     | [4a3ef3e12f](https://linux-hardware.org/?probe=4a3ef3e12f) | Oct 03, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [1e6ec4d559](https://linux-hardware.org/?probe=1e6ec4d559) | Oct 03, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c474599b04](https://linux-hardware.org/?probe=c474599b04) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [0ebc5c48b5](https://linux-hardware.org/?probe=0ebc5c48b5) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [00afde76db](https://linux-hardware.org/?probe=00afde76db) | Oct 03, 2023 |
| Pegatron      | EVANS                       | Desktop     | [3f2a4fe53e](https://linux-hardware.org/?probe=3f2a4fe53e) | Oct 03, 2023 |
| Gigabyte      | Z270-HD3-CF                 | Desktop     | [c23994e74a](https://linux-hardware.org/?probe=c23994e74a) | Oct 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b210c95b8e](https://linux-hardware.org/?probe=b210c95b8e) | Oct 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [2519f8a695](https://linux-hardware.org/?probe=2519f8a695) | Oct 02, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [320836ef04](https://linux-hardware.org/?probe=320836ef04) | Oct 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | Notebook    | [aa2d376e85](https://linux-hardware.org/?probe=aa2d376e85) | Oct 02, 2023 |
| MSI           | B85M-E45                    | Desktop     | [12fa4b4da3](https://linux-hardware.org/?probe=12fa4b4da3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | Desktop     | [2c6f35e1d3](https://linux-hardware.org/?probe=2c6f35e1d3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | Desktop     | [ded620f59b](https://linux-hardware.org/?probe=ded620f59b) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [5698c85faa](https://linux-hardware.org/?probe=5698c85faa) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [056bfb8474](https://linux-hardware.org/?probe=056bfb8474) | Oct 01, 2023 |
| HP            | 470 17 inch G9              | Notebook    | [c6043cc6cc](https://linux-hardware.org/?probe=c6043cc6cc) | Oct 01, 2023 |
| Intel         | X79M-S                      | Desktop     | [dfa1322112](https://linux-hardware.org/?probe=dfa1322112) | Oct 01, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [8d558a64e8](https://linux-hardware.org/?probe=8d558a64e8) | Oct 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [127980fc54](https://linux-hardware.org/?probe=127980fc54) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [e0cdb74f25](https://linux-hardware.org/?probe=e0cdb74f25) | Oct 01, 2023 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [d9750c9040](https://linux-hardware.org/?probe=d9750c9040) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| Acer          | Predator G3610              | Desktop     | [cddfa514ba](https://linux-hardware.org/?probe=cddfa514ba) | Sep 30, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [c93af00811](https://linux-hardware.org/?probe=c93af00811) | Sep 30, 2023 |
| MP            | MS-7848                     | Desktop     | [63d5662351](https://linux-hardware.org/?probe=63d5662351) | Sep 30, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [237492c356](https://linux-hardware.org/?probe=237492c356) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [145f7eccd3](https://linux-hardware.org/?probe=145f7eccd3) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | Notebook    | [e9dd0291e0](https://linux-hardware.org/?probe=e9dd0291e0) | Sep 29, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [8ba160ee59](https://linux-hardware.org/?probe=8ba160ee59) | Sep 29, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [4aa521a31f](https://linux-hardware.org/?probe=4aa521a31f) | Sep 29, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | Notebook    | [4f74530d68](https://linux-hardware.org/?probe=4f74530d68) | Sep 28, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | Notebook    | [5fb1e549ea](https://linux-hardware.org/?probe=5fb1e549ea) | Sep 28, 2023 |
| HP            | 2B35                        | Desktop     | [2f63f14724](https://linux-hardware.org/?probe=2f63f14724) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ce3a9f8960](https://linux-hardware.org/?probe=ce3a9f8960) | Sep 28, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [c717c1ab13](https://linux-hardware.org/?probe=c717c1ab13) | Sep 28, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f6c6bfc3fe](https://linux-hardware.org/?probe=f6c6bfc3fe) | Sep 27, 2023 |
| Lenovo        | ThinkPad E14 20RA0050US     | Notebook    | [097539dde8](https://linux-hardware.org/?probe=097539dde8) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | Notebook    | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| Intel         | X79G V2.x                   | Desktop     | [3d001a09ab](https://linux-hardware.org/?probe=3d001a09ab) | Sep 27, 2023 |
| HP            | Notebook                    | Notebook    | [4690fda15e](https://linux-hardware.org/?probe=4690fda15e) | Sep 27, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [811818acb8](https://linux-hardware.org/?probe=811818acb8) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [e7e87a1269](https://linux-hardware.org/?probe=e7e87a1269) | Sep 26, 2023 |
| Dell          | Inspiron 5459               | Notebook    | [1095c770f0](https://linux-hardware.org/?probe=1095c770f0) | Sep 26, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [0c8a57738d](https://linux-hardware.org/?probe=0c8a57738d) | Sep 25, 2023 |
| AZW           | SER                         | Mini pc     | [8e73904b3c](https://linux-hardware.org/?probe=8e73904b3c) | Sep 25, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a778013e21](https://linux-hardware.org/?probe=a778013e21) | Sep 25, 2023 |
| Intel         | W7645                       | Notebook    | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [29feb62e32](https://linux-hardware.org/?probe=29feb62e32) | Sep 25, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [863dfa9b96](https://linux-hardware.org/?probe=863dfa9b96) | Sep 25, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [1bee981c70](https://linux-hardware.org/?probe=1bee981c70) | Sep 25, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [7c901ae7fd](https://linux-hardware.org/?probe=7c901ae7fd) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | Notebook    | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| Alienware     | M17x                        | Notebook    | [5c6b700486](https://linux-hardware.org/?probe=5c6b700486) | Sep 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [6d75f2f29b](https://linux-hardware.org/?probe=6d75f2f29b) | Sep 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [f2a543d0dd](https://linux-hardware.org/?probe=f2a543d0dd) | Sep 24, 2023 |
| Sary          | Tab2                        | Tablet      | [7078e2b899](https://linux-hardware.org/?probe=7078e2b899) | Sep 23, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [fdfd7f2e50](https://linux-hardware.org/?probe=fdfd7f2e50) | Sep 23, 2023 |
| Sary          | Tab2                        | Tablet      | [913ec00764](https://linux-hardware.org/?probe=913ec00764) | Sep 23, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [6897fc6f5a](https://linux-hardware.org/?probe=6897fc6f5a) | Sep 23, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [fd3ce44501](https://linux-hardware.org/?probe=fd3ce44501) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [e2c17f3a64](https://linux-hardware.org/?probe=e2c17f3a64) | Sep 23, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [58b289a69d](https://linux-hardware.org/?probe=58b289a69d) | Sep 23, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | Notebook    | [8b5a2354c5](https://linux-hardware.org/?probe=8b5a2354c5) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e513362f71](https://linux-hardware.org/?probe=e513362f71) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | Notebook    | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [81bf9d5194](https://linux-hardware.org/?probe=81bf9d5194) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [7ecfb9c56f](https://linux-hardware.org/?probe=7ecfb9c56f) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [47e5429752](https://linux-hardware.org/?probe=47e5429752) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [a35f78cead](https://linux-hardware.org/?probe=a35f78cead) | Sep 21, 2023 |
| AZW           | MINI S 10                   | Desktop     | [e393d95960](https://linux-hardware.org/?probe=e393d95960) | Sep 21, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [cc25c24fa5](https://linux-hardware.org/?probe=cc25c24fa5) | Sep 21, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d92a4fb2af](https://linux-hardware.org/?probe=d92a4fb2af) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | Notebook    | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| Acer          | Aspire VN7-572G             | Notebook    | [8936ef0637](https://linux-hardware.org/?probe=8936ef0637) | Sep 21, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [e57a830f9c](https://linux-hardware.org/?probe=e57a830f9c) | Sep 21, 2023 |
| Lenovo        | ThinkPad T570 20HAS1PC00    | Notebook    | [218325e9e3](https://linux-hardware.org/?probe=218325e9e3) | Sep 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | Notebook    | [85a0203a02](https://linux-hardware.org/?probe=85a0203a02) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [dd7f2cf2b2](https://linux-hardware.org/?probe=dd7f2cf2b2) | Sep 20, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | Notebook    | [c96d3bf498](https://linux-hardware.org/?probe=c96d3bf498) | Sep 20, 2023 |
| Lenovo        | H320 10044                  | Desktop     | [bf4ffce3e9](https://linux-hardware.org/?probe=bf4ffce3e9) | Sep 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [776633dd59](https://linux-hardware.org/?probe=776633dd59) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [fcdaf47870](https://linux-hardware.org/?probe=fcdaf47870) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4dc880c6f](https://linux-hardware.org/?probe=e4dc880c6f) | Sep 20, 2023 |
| Dell          | 0RW199                      | Desktop     | [2857c6ada1](https://linux-hardware.org/?probe=2857c6ada1) | Sep 20, 2023 |
| Gigabyte      | Z790 UD AC                  | Desktop     | [83af285806](https://linux-hardware.org/?probe=83af285806) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [3d4f35cc26](https://linux-hardware.org/?probe=3d4f35cc26) | Sep 19, 2023 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [fcd8ef31df](https://linux-hardware.org/?probe=fcd8ef31df) | Sep 19, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [9fb8b99e70](https://linux-hardware.org/?probe=9fb8b99e70) | Sep 19, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [ca70cb035f](https://linux-hardware.org/?probe=ca70cb035f) | Sep 19, 2023 |
| Biostar       | H61MLC                      | Desktop     | [154ead8447](https://linux-hardware.org/?probe=154ead8447) | Sep 19, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [f45c7732e3](https://linux-hardware.org/?probe=f45c7732e3) | Sep 19, 2023 |
| AZW           | GTR V21                     | Desktop     | [5066e153f8](https://linux-hardware.org/?probe=5066e153f8) | Sep 19, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [5ec304bdb6](https://linux-hardware.org/?probe=5ec304bdb6) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [d03b8c1860](https://linux-hardware.org/?probe=d03b8c1860) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [202375fbb7](https://linux-hardware.org/?probe=202375fbb7) | Sep 18, 2023 |
| HP            | 3047h                       | Desktop     | [a955e9b6c6](https://linux-hardware.org/?probe=a955e9b6c6) | Sep 17, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [9e7069cdc3](https://linux-hardware.org/?probe=9e7069cdc3) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | Notebook    | [065988c338](https://linux-hardware.org/?probe=065988c338) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | Notebook    | [1a9e79b92e](https://linux-hardware.org/?probe=1a9e79b92e) | Sep 17, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [08ed0347db](https://linux-hardware.org/?probe=08ed0347db) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [d4d891ca35](https://linux-hardware.org/?probe=d4d891ca35) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [e639402c30](https://linux-hardware.org/?probe=e639402c30) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [b42ad40603](https://linux-hardware.org/?probe=b42ad40603) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [3a230dc10f](https://linux-hardware.org/?probe=3a230dc10f) | Sep 16, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3774dfea8e](https://linux-hardware.org/?probe=3774dfea8e) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [87f26cde55](https://linux-hardware.org/?probe=87f26cde55) | Sep 16, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [8913a6c47f](https://linux-hardware.org/?probe=8913a6c47f) | Sep 16, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [72503b214c](https://linux-hardware.org/?probe=72503b214c) | Sep 16, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [16c14700d3](https://linux-hardware.org/?probe=16c14700d3) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [00fd2287c0](https://linux-hardware.org/?probe=00fd2287c0) | Sep 16, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [f6be487f38](https://linux-hardware.org/?probe=f6be487f38) | Sep 16, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2fa5c8bb34](https://linux-hardware.org/?probe=2fa5c8bb34) | Sep 16, 2023 |
| ASUSTek       | K54C                        | Notebook    | [23a000c4d4](https://linux-hardware.org/?probe=23a000c4d4) | Sep 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [5cd83bcad9](https://linux-hardware.org/?probe=5cd83bcad9) | Sep 15, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2c412a10ca](https://linux-hardware.org/?probe=2c412a10ca) | Sep 15, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [def911de73](https://linux-hardware.org/?probe=def911de73) | Sep 14, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [83cb90361c](https://linux-hardware.org/?probe=83cb90361c) | Sep 14, 2023 |
| Itautec       | Infoway                     | Notebook    | [d4a8bc6420](https://linux-hardware.org/?probe=d4a8bc6420) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| HP            | Notebook                    | Notebook    | [29f1834722](https://linux-hardware.org/?probe=29f1834722) | Sep 14, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [bba9e61120](https://linux-hardware.org/?probe=bba9e61120) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [40aee3739e](https://linux-hardware.org/?probe=40aee3739e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [9bbec30b2f](https://linux-hardware.org/?probe=9bbec30b2f) | Sep 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [3cba209625](https://linux-hardware.org/?probe=3cba209625) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [4dcd4e8234](https://linux-hardware.org/?probe=4dcd4e8234) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [cbfa4c2641](https://linux-hardware.org/?probe=cbfa4c2641) | Sep 13, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [b94c2a0420](https://linux-hardware.org/?probe=b94c2a0420) | Sep 13, 2023 |
| Acer          | Aspire 5750ZG               | Notebook    | [c9ce4cde54](https://linux-hardware.org/?probe=c9ce4cde54) | Sep 13, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [32b69241bf](https://linux-hardware.org/?probe=32b69241bf) | Sep 13, 2023 |
| Sony          | VPCEB1E1E                   | Notebook    | [cbd095ee01](https://linux-hardware.org/?probe=cbd095ee01) | Sep 12, 2023 |
| Acer          | Aspire 5750ZG               | Notebook    | [9029730ffb](https://linux-hardware.org/?probe=9029730ffb) | Sep 12, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [8ddb560fdc](https://linux-hardware.org/?probe=8ddb560fdc) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [5358fa25ef](https://linux-hardware.org/?probe=5358fa25ef) | Sep 12, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | Desktop     | [e4f73d159c](https://linux-hardware.org/?probe=e4f73d159c) | Sep 12, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [8ddbf6665f](https://linux-hardware.org/?probe=8ddbf6665f) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [9fc04871b0](https://linux-hardware.org/?probe=9fc04871b0) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [a80cffbabe](https://linux-hardware.org/?probe=a80cffbabe) | Sep 11, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [5907e59551](https://linux-hardware.org/?probe=5907e59551) | Sep 11, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [21baf66690](https://linux-hardware.org/?probe=21baf66690) | Sep 11, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | Desktop     | [c57a3a012d](https://linux-hardware.org/?probe=c57a3a012d) | Sep 11, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e7c7395c7b](https://linux-hardware.org/?probe=e7c7395c7b) | Sep 11, 2023 |
| ASUSTek       | PRIME H370-A                | Desktop     | [c757d0e2c3](https://linux-hardware.org/?probe=c757d0e2c3) | Sep 11, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [39a15ba0ca](https://linux-hardware.org/?probe=39a15ba0ca) | Sep 10, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [26fc33cb75](https://linux-hardware.org/?probe=26fc33cb75) | Sep 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| ASUSTek       | X541UA                      | Notebook    | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [a8db1b43ce](https://linux-hardware.org/?probe=a8db1b43ce) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [26b9818094](https://linux-hardware.org/?probe=26b9818094) | Sep 09, 2023 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [3ee6c9a460](https://linux-hardware.org/?probe=3ee6c9a460) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [6f66e35ec3](https://linux-hardware.org/?probe=6f66e35ec3) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [9306917366](https://linux-hardware.org/?probe=9306917366) | Sep 09, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [382cd978ab](https://linux-hardware.org/?probe=382cd978ab) | Sep 08, 2023 |
| HP            | 8523 A01                    | Mini pc     | [b050702ce4](https://linux-hardware.org/?probe=b050702ce4) | Sep 08, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [c936953cf7](https://linux-hardware.org/?probe=c936953cf7) | Sep 08, 2023 |
| Lenovo        | ThinkPad T430 2349H2G       | Notebook    | [1d9d7c7f78](https://linux-hardware.org/?probe=1d9d7c7f78) | Sep 08, 2023 |
| HP            | 8299                        | Desktop     | [df4048bcc4](https://linux-hardware.org/?probe=df4048bcc4) | Sep 08, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [97d9faccab](https://linux-hardware.org/?probe=97d9faccab) | Sep 07, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [3112302ff6](https://linux-hardware.org/?probe=3112302ff6) | Sep 07, 2023 |
| Acer          | Aspire X1470                | Desktop     | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | Desktop     | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [002bdcd34d](https://linux-hardware.org/?probe=002bdcd34d) | Sep 07, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [125a7f7c0d](https://linux-hardware.org/?probe=125a7f7c0d) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [6bb77310bf](https://linux-hardware.org/?probe=6bb77310bf) | Sep 06, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [0428af4d14](https://linux-hardware.org/?probe=0428af4d14) | Sep 06, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [415ba1cfc1](https://linux-hardware.org/?probe=415ba1cfc1) | Sep 06, 2023 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [a7e1067ce7](https://linux-hardware.org/?probe=a7e1067ce7) | Sep 06, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [5e6e5cd047](https://linux-hardware.org/?probe=5e6e5cd047) | Sep 06, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [53bfbec77e](https://linux-hardware.org/?probe=53bfbec77e) | Sep 06, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3227a8a6bc](https://linux-hardware.org/?probe=3227a8a6bc) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Toshiba       | Satellite A210              | Notebook    | [54f5fb9c03](https://linux-hardware.org/?probe=54f5fb9c03) | Sep 06, 2023 |
| Alienware     | 0446JC A01                  | Desktop     | [d0c3088707](https://linux-hardware.org/?probe=d0c3088707) | Sep 06, 2023 |
| Framework     | Laptop                      | Notebook    | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| HP            | 0B54h D                     | Desktop     | [6fc93ef4ee](https://linux-hardware.org/?probe=6fc93ef4ee) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [f8ec276ea3](https://linux-hardware.org/?probe=f8ec276ea3) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [788841792b](https://linux-hardware.org/?probe=788841792b) | Sep 04, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [7f0254a775](https://linux-hardware.org/?probe=7f0254a775) | Sep 04, 2023 |
| Toshiba       | Satellite C70D-A            | Notebook    | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [371c148953](https://linux-hardware.org/?probe=371c148953) | Sep 04, 2023 |
| Dell          | Latitude E6530              | Notebook    | [e1aa22b8b9](https://linux-hardware.org/?probe=e1aa22b8b9) | Sep 04, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [78a354984d](https://linux-hardware.org/?probe=78a354984d) | Sep 04, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [ae79e6a689](https://linux-hardware.org/?probe=ae79e6a689) | Sep 04, 2023 |
| Dell          | G15 5511                    | Notebook    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [2c9b64c445](https://linux-hardware.org/?probe=2c9b64c445) | Sep 03, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [f4c15b0551](https://linux-hardware.org/?probe=f4c15b0551) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | Notebook    | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [9845368fc2](https://linux-hardware.org/?probe=9845368fc2) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [eee58fd067](https://linux-hardware.org/?probe=eee58fd067) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6215db2c5a](https://linux-hardware.org/?probe=6215db2c5a) | Sep 02, 2023 |
| AMI           | Intel                       | Convertible | [dd24abacfc](https://linux-hardware.org/?probe=dd24abacfc) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [f05f130786](https://linux-hardware.org/?probe=f05f130786) | Sep 02, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [7f9db7db99](https://linux-hardware.org/?probe=7f9db7db99) | Sep 01, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [027ceec09f](https://linux-hardware.org/?probe=027ceec09f) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Intel         | X79M-S                      | Desktop     | [a6952c68e4](https://linux-hardware.org/?probe=a6952c68e4) | Sep 01, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [24743bf01d](https://linux-hardware.org/?probe=24743bf01d) | Sep 01, 2023 |
| Dell          | Latitude 5400               | Notebook    | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | Notebook    | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| HP            | ProBook 4740s               | Notebook    | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [be8b002a45](https://linux-hardware.org/?probe=be8b002a45) | Aug 31, 2023 |
| HP            | 15                          | Notebook    | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| HP            | Pavilion dv4                | Notebook    | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Sony          | VPCEE23FX                   | Notebook    | [65714e4d48](https://linux-hardware.org/?probe=65714e4d48) | Aug 30, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [035f2909a1](https://linux-hardware.org/?probe=035f2909a1) | Aug 30, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [d963970016](https://linux-hardware.org/?probe=d963970016) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| HP            | 8054                        | Desktop     | [f73271d96e](https://linux-hardware.org/?probe=f73271d96e) | Aug 30, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [3fb03adafb](https://linux-hardware.org/?probe=3fb03adafb) | Aug 29, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [01701d7ab0](https://linux-hardware.org/?probe=01701d7ab0) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [6da5e2d119](https://linux-hardware.org/?probe=6da5e2d119) | Aug 29, 2023 |
| Dell          | Precision 7710              | Notebook    | [9b92626f63](https://linux-hardware.org/?probe=9b92626f63) | Aug 29, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [eba7f74017](https://linux-hardware.org/?probe=eba7f74017) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | Notebook    | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [fffbca3973](https://linux-hardware.org/?probe=fffbca3973) | Aug 28, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [8e13da67ed](https://linux-hardware.org/?probe=8e13da67ed) | Aug 28, 2023 |
| Intel         | H61                         | Desktop     | [9e5ed4db62](https://linux-hardware.org/?probe=9e5ed4db62) | Aug 28, 2023 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [5268d75df2](https://linux-hardware.org/?probe=5268d75df2) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | Notebook    | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | Notebook    | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [cb2419d3df](https://linux-hardware.org/?probe=cb2419d3df) | Aug 27, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4357727561](https://linux-hardware.org/?probe=4357727561) | Aug 27, 2023 |
| TERRA         | TERRAPC                     | Notebook    | [2031fd343b](https://linux-hardware.org/?probe=2031fd343b) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [929efec703](https://linux-hardware.org/?probe=929efec703) | Aug 27, 2023 |
| eMachines     | EL1352                      | Desktop     | [5f9258beb2](https://linux-hardware.org/?probe=5f9258beb2) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [e212f5bc28](https://linux-hardware.org/?probe=e212f5bc28) | Aug 25, 2023 |
| Google        | Rammus                      | Notebook    | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| GuoGuang      | IC2M1028N                   | Desktop     | [ffcd5b9fa5](https://linux-hardware.org/?probe=ffcd5b9fa5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| Samsung       | 960QFG                      | Convertible | [400b83d634](https://linux-hardware.org/?probe=400b83d634) | Aug 24, 2023 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [42d3a714ac](https://linux-hardware.org/?probe=42d3a714ac) | Aug 24, 2023 |
| TERRA         | TERRAPC                     | Notebook    | [b33c6ce6e8](https://linux-hardware.org/?probe=b33c6ce6e8) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | ProBook 4740s               | Notebook    | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| AZW           | MINI S                      | Desktop     | [7712e558c5](https://linux-hardware.org/?probe=7712e558c5) | Aug 24, 2023 |
| AZW           | MINI S                      | Desktop     | [6296a4f71d](https://linux-hardware.org/?probe=6296a4f71d) | Aug 24, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [64859dd75d](https://linux-hardware.org/?probe=64859dd75d) | Aug 24, 2023 |
| HP            | 8299                        | Desktop     | [aa27bed4f1](https://linux-hardware.org/?probe=aa27bed4f1) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [82c63f13d1](https://linux-hardware.org/?probe=82c63f13d1) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [1aee954611](https://linux-hardware.org/?probe=1aee954611) | Aug 22, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | Notebook    | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [9b52370ec1](https://linux-hardware.org/?probe=9b52370ec1) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [51e91dd03e](https://linux-hardware.org/?probe=51e91dd03e) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [a440d57d28](https://linux-hardware.org/?probe=a440d57d28) | Aug 21, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [409855b61b](https://linux-hardware.org/?probe=409855b61b) | Aug 21, 2023 |
| Dell          | Precision M4700             | Notebook    | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7a206bdd57](https://linux-hardware.org/?probe=7a206bdd57) | Aug 21, 2023 |
| HP            | Notebook                    | Notebook    | [5b7ff7f278](https://linux-hardware.org/?probe=5b7ff7f278) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Dell          | Latitude 3350               | Notebook    | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | Unknown                     | Notebook    | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | Notebook    | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Alienware     | 17                          | Notebook    | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [2ac06099d8](https://linux-hardware.org/?probe=2ac06099d8) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [f97c8a25c5](https://linux-hardware.org/?probe=f97c8a25c5) | Aug 19, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [f06dbc1b8c](https://linux-hardware.org/?probe=f06dbc1b8c) | Aug 19, 2023 |
| HP            | 3047h                       | Desktop     | [91d9eaa1de](https://linux-hardware.org/?probe=91d9eaa1de) | Aug 19, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [d109b04177](https://linux-hardware.org/?probe=d109b04177) | Aug 19, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| ASUSTek       | X550ZA                      | Notebook    | [7f23195701](https://linux-hardware.org/?probe=7f23195701) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| HP            | 3047h                       | Desktop     | [a4aa888c24](https://linux-hardware.org/?probe=a4aa888c24) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [d14c477dc9](https://linux-hardware.org/?probe=d14c477dc9) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [7092a32ce5](https://linux-hardware.org/?probe=7092a32ce5) | Aug 17, 2023 |
| Dell          | G3 3579                     | Notebook    | [58866ca1fb](https://linux-hardware.org/?probe=58866ca1fb) | Aug 17, 2023 |
| HP            | 3032h                       | Desktop     | [34a300f540](https://linux-hardware.org/?probe=34a300f540) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | Notebook    | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | Notebook    | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Intel         | X79M-S                      | Desktop     | [d79895d82c](https://linux-hardware.org/?probe=d79895d82c) | Aug 17, 2023 |
| Google        | Coral                       | Notebook    | [f8ed9b3bda](https://linux-hardware.org/?probe=f8ed9b3bda) | Aug 17, 2023 |
| Lenovo        | ThinkPad T480 20L5S04F00    | Notebook    | [7eb670d219](https://linux-hardware.org/?probe=7eb670d219) | Aug 17, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [de9a1cb848](https://linux-hardware.org/?probe=de9a1cb848) | Aug 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [7c1a42d442](https://linux-hardware.org/?probe=7c1a42d442) | Aug 17, 2023 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [78e12f014e](https://linux-hardware.org/?probe=78e12f014e) | Aug 17, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [50731e7c54](https://linux-hardware.org/?probe=50731e7c54) | Aug 16, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [50b5957370](https://linux-hardware.org/?probe=50b5957370) | Aug 16, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [b31bf50c6e](https://linux-hardware.org/?probe=b31bf50c6e) | Aug 16, 2023 |
| Dell          | Latitude D630               | Notebook    | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3da24e6a41](https://linux-hardware.org/?probe=3da24e6a41) | Aug 15, 2023 |
| HP            | 15                          | Notebook    | [645730bff3](https://linux-hardware.org/?probe=645730bff3) | Aug 15, 2023 |
| HP            | 15                          | Notebook    | [08fc74cb7b](https://linux-hardware.org/?probe=08fc74cb7b) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | Notebook    | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| Biostar       | H410MH                      | Desktop     | [abe98ae584](https://linux-hardware.org/?probe=abe98ae584) | Aug 15, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [bb4bf558dd](https://linux-hardware.org/?probe=bb4bf558dd) | Aug 15, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [e79cdd0ba3](https://linux-hardware.org/?probe=e79cdd0ba3) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | Notebook    | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Medion        | E15301                      | Notebook    | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [102a6b136f](https://linux-hardware.org/?probe=102a6b136f) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f09f15784f](https://linux-hardware.org/?probe=f09f15784f) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [dea6e2f8b8](https://linux-hardware.org/?probe=dea6e2f8b8) | Aug 13, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [7e47b7128b](https://linux-hardware.org/?probe=7e47b7128b) | Aug 13, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [777c4f7fb8](https://linux-hardware.org/?probe=777c4f7fb8) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [1034423357](https://linux-hardware.org/?probe=1034423357) | Aug 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [c692882ce4](https://linux-hardware.org/?probe=c692882ce4) | Aug 13, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [ff8bec8b75](https://linux-hardware.org/?probe=ff8bec8b75) | Aug 12, 2023 |
| AMI           | Unknown                     | Notebook    | [326999bd6b](https://linux-hardware.org/?probe=326999bd6b) | Aug 12, 2023 |
| AMI           | Unknown                     | Notebook    | [614b443c5c](https://linux-hardware.org/?probe=614b443c5c) | Aug 12, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [17179d26d5](https://linux-hardware.org/?probe=17179d26d5) | Aug 12, 2023 |
| HP            | 350 G2                      | Notebook    | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| MSI           | 2AE0                        | Desktop     | [b8a2a0eb5c](https://linux-hardware.org/?probe=b8a2a0eb5c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [71f554fd2c](https://linux-hardware.org/?probe=71f554fd2c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [edd42a9a6d](https://linux-hardware.org/?probe=edd42a9a6d) | Aug 12, 2023 |
| Lenovo        | IdeaPad Duet 3 11IAN8 82... | Tablet      | [b61e23d1ec](https://linux-hardware.org/?probe=b61e23d1ec) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Acer          | One Z1402                   | Notebook    | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [d35bac0620](https://linux-hardware.org/?probe=d35bac0620) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [fb7d0009fd](https://linux-hardware.org/?probe=fb7d0009fd) | Aug 12, 2023 |
| Dell          | 0XKD8M A00                  | All in one  | [6cbd6d691c](https://linux-hardware.org/?probe=6cbd6d691c) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [b68d99fd89](https://linux-hardware.org/?probe=b68d99fd89) | Aug 11, 2023 |
| HP            | 3032h                       | Desktop     | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [48a0f64b34](https://linux-hardware.org/?probe=48a0f64b34) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| HP            | 350 G2                      | Notebook    | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [a2756bd55e](https://linux-hardware.org/?probe=a2756bd55e) | Aug 10, 2023 |
| Intel         | DZ68BC AAG30742-401         | Desktop     | [9bf37df045](https://linux-hardware.org/?probe=9bf37df045) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | 350 G2                      | Notebook    | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [6e9ca3c833](https://linux-hardware.org/?probe=6e9ca3c833) | Aug 09, 2023 |
| HP            | 3032h                       | Desktop     | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| HP            | Presario CQ56               | Notebook    | [cf373b9083](https://linux-hardware.org/?probe=cf373b9083) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [7c59be984f](https://linux-hardware.org/?probe=7c59be984f) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [9c789edd52](https://linux-hardware.org/?probe=9c789edd52) | Aug 08, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [2e30c62b25](https://linux-hardware.org/?probe=2e30c62b25) | Aug 08, 2023 |
| Intel         | X79M-S                      | Desktop     | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | Notebook    | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | Notebook    | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c95daf7007](https://linux-hardware.org/?probe=c95daf7007) | Aug 06, 2023 |
| Pegatron      | IPMMB-MQ1                   | Desktop     | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [c40308638c](https://linux-hardware.org/?probe=c40308638c) | Aug 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [1af709c14e](https://linux-hardware.org/?probe=1af709c14e) | Aug 05, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [3bc330734d](https://linux-hardware.org/?probe=3bc330734d) | Aug 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [5d998a099e](https://linux-hardware.org/?probe=5d998a099e) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [e57d71e056](https://linux-hardware.org/?probe=e57d71e056) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [8ee9cccace](https://linux-hardware.org/?probe=8ee9cccace) | Aug 05, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [7ffb6822e6](https://linux-hardware.org/?probe=7ffb6822e6) | Aug 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| Itautec       | Infoway                     | Notebook    | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [3793d876eb](https://linux-hardware.org/?probe=3793d876eb) | Aug 04, 2023 |
| GPD           | G1621-02                    | Notebook    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [cf6d77d650](https://linux-hardware.org/?probe=cf6d77d650) | Aug 04, 2023 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [9f27152a86](https://linux-hardware.org/?probe=9f27152a86) | Aug 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [955c961132](https://linux-hardware.org/?probe=955c961132) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f27f9b2a7f](https://linux-hardware.org/?probe=f27f9b2a7f) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [8193f810ab](https://linux-hardware.org/?probe=8193f810ab) | Aug 03, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [35cf0fd859](https://linux-hardware.org/?probe=35cf0fd859) | Aug 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| HP            | 89B5 A                      | Desktop     | [cb6f36f32c](https://linux-hardware.org/?probe=cb6f36f32c) | Aug 02, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| HP            | Pavilion dv7                | Notebook    | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [ee5b34b232](https://linux-hardware.org/?probe=ee5b34b232) | Aug 02, 2023 |
| ASUSTek       | K54C                        | Notebook    | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [731a8b0e31](https://linux-hardware.org/?probe=731a8b0e31) | Aug 02, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| AZW           | GTR V01                     | Mini pc     | [f3f9a4366b](https://linux-hardware.org/?probe=f3f9a4366b) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [957e1805d3](https://linux-hardware.org/?probe=957e1805d3) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [a522e7336c](https://linux-hardware.org/?probe=a522e7336c) | Aug 01, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| HP            | 1496                        | Desktop     | [24863488f0](https://linux-hardware.org/?probe=24863488f0) | Aug 01, 2023 |
| MSI           | GE72MVR 7RG                 | Notebook    | [d935650def](https://linux-hardware.org/?probe=d935650def) | Jul 31, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [d1651e3e43](https://linux-hardware.org/?probe=d1651e3e43) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [90dce7a9cf](https://linux-hardware.org/?probe=90dce7a9cf) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | Notebook    | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [b1125cd76c](https://linux-hardware.org/?probe=b1125cd76c) | Jul 29, 2023 |
| HP            | Pavilion dv4                | Notebook    | [47e9cba85c](https://linux-hardware.org/?probe=47e9cba85c) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| ASUSTek       | K53U                        | Notebook    | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [bc92202f16](https://linux-hardware.org/?probe=bc92202f16) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [310207e0fd](https://linux-hardware.org/?probe=310207e0fd) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [7583695051](https://linux-hardware.org/?probe=7583695051) | Jul 28, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [fe7c4fd681](https://linux-hardware.org/?probe=fe7c4fd681) | Jul 28, 2023 |
| Google        | Edgar                       | Notebook    | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [9e892612ab](https://linux-hardware.org/?probe=9e892612ab) | Jul 28, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| HP            | 3397                        | Desktop     | [e61ccd6dbf](https://linux-hardware.org/?probe=e61ccd6dbf) | Jul 27, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [b7ce548e5b](https://linux-hardware.org/?probe=b7ce548e5b) | Jul 27, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [e7fdf45ff0](https://linux-hardware.org/?probe=e7fdf45ff0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2f12124bed](https://linux-hardware.org/?probe=2f12124bed) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| MP            | MS-7848                     | Desktop     | [3dd9f22548](https://linux-hardware.org/?probe=3dd9f22548) | Jul 26, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [238c98ee81](https://linux-hardware.org/?probe=238c98ee81) | Jul 26, 2023 |
| Lenovo        | No DPK                      | All in one  | [1b1fa8ccec](https://linux-hardware.org/?probe=1b1fa8ccec) | Jul 26, 2023 |
| Acer          | Elena                       | Desktop     | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [1b062f3c31](https://linux-hardware.org/?probe=1b062f3c31) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [bca4424b5d](https://linux-hardware.org/?probe=bca4424b5d) | Jul 26, 2023 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [1355a4f2f4](https://linux-hardware.org/?probe=1355a4f2f4) | Jul 25, 2023 |
| Acer          | TravelMate B113             | Notebook    | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [7eda84257a](https://linux-hardware.org/?probe=7eda84257a) | Jul 25, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [47fec524e4](https://linux-hardware.org/?probe=47fec524e4) | Jul 25, 2023 |
| Dell          | Inspiron 3721               | Notebook    | [a0874e626b](https://linux-hardware.org/?probe=a0874e626b) | Jul 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [431abc64d1](https://linux-hardware.org/?probe=431abc64d1) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | Notebook    | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Microtech     | ebookPro                    | Notebook    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| HP            | 8350                        | Desktop     | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |
| Acer          | AO756                       | Notebook    | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c271fa70b8](https://linux-hardware.org/?probe=c271fa70b8) | Jul 23, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [19356a725e](https://linux-hardware.org/?probe=19356a725e) | Jul 22, 2023 |
| HP            | Pavilion dv4                | Notebook    | [4854c4b18c](https://linux-hardware.org/?probe=4854c4b18c) | Jul 22, 2023 |
| Dell          | 0MN1TX A04                  | Desktop     | [4ff31f4185](https://linux-hardware.org/?probe=4ff31f4185) | Jul 22, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [b8cf03e7b7](https://linux-hardware.org/?probe=b8cf03e7b7) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [87b85c2e28](https://linux-hardware.org/?probe=87b85c2e28) | Jul 22, 2023 |
| Medion        | E15301                      | Notebook    | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| ASRock        | B85M                        | Desktop     | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| AMI           | Cherry Trail CR             | Notebook    | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| HP            | 3048h                       | Desktop     | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| Dell          | Latitude E6440              | Notebook    | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| HP            | 3047h                       | Desktop     | [07de35877b](https://linux-hardware.org/?probe=07de35877b) | Jul 21, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [9afd0f1d0f](https://linux-hardware.org/?probe=9afd0f1d0f) | Jul 21, 2023 |
| Dell          | Latitude 3520               | Notebook    | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| HP            | 15                          | Notebook    | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [35c4e6ad97](https://linux-hardware.org/?probe=35c4e6ad97) | Jul 20, 2023 |
| HP            | 8767 A                      | Desktop     | [d5275f1025](https://linux-hardware.org/?probe=d5275f1025) | Jul 20, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [3832c8f626](https://linux-hardware.org/?probe=3832c8f626) | Jul 20, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [71f9656ab2](https://linux-hardware.org/?probe=71f9656ab2) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | Notebook    | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [da1c963814](https://linux-hardware.org/?probe=da1c963814) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [02008985ce](https://linux-hardware.org/?probe=02008985ce) | Jul 19, 2023 |
| Sony          | VPCEE23FX                   | Notebook    | [2cb9bf9d50](https://linux-hardware.org/?probe=2cb9bf9d50) | Jul 18, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [8e01cf8f1e](https://linux-hardware.org/?probe=8e01cf8f1e) | Jul 17, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [9be017a8a3](https://linux-hardware.org/?probe=9be017a8a3) | Jul 16, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [71c4faf60f](https://linux-hardware.org/?probe=71c4faf60f) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Dell          | 04075X A00                  | All in one  | [46795bfa31](https://linux-hardware.org/?probe=46795bfa31) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [21bef8253a](https://linux-hardware.org/?probe=21bef8253a) | Jul 15, 2023 |
| Dell          | Latitude E4300              | Notebook    | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | Notebook    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [57b17e7ae1](https://linux-hardware.org/?probe=57b17e7ae1) | Jul 15, 2023 |
| Gigabyte      | Z370M AORUS Gaming-CF       | Desktop     | [64a0d52846](https://linux-hardware.org/?probe=64a0d52846) | Jul 15, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [d32668cf0c](https://linux-hardware.org/?probe=d32668cf0c) | Jul 15, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2f5c2842c2](https://linux-hardware.org/?probe=2f5c2842c2) | Jul 14, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [4155214585](https://linux-hardware.org/?probe=4155214585) | Jul 14, 2023 |
| Alienware     | M11xR3                      | Notebook    | [9397339221](https://linux-hardware.org/?probe=9397339221) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [35399aae18](https://linux-hardware.org/?probe=35399aae18) | Jul 14, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [622890c12a](https://linux-hardware.org/?probe=622890c12a) | Jul 14, 2023 |
| AZW           | SER                         | Mini pc     | [8fdb4e6f42](https://linux-hardware.org/?probe=8fdb4e6f42) | Jul 14, 2023 |
| AZW           | SER                         | Mini pc     | [537e7c9c94](https://linux-hardware.org/?probe=537e7c9c94) | Jul 13, 2023 |
| HP            | 15                          | Notebook    | [215a87518e](https://linux-hardware.org/?probe=215a87518e) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [81f693b5b0](https://linux-hardware.org/?probe=81f693b5b0) | Jul 12, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [b690698c10](https://linux-hardware.org/?probe=b690698c10) | Jul 12, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [d347a1b82e](https://linux-hardware.org/?probe=d347a1b82e) | Jul 12, 2023 |
| Lenovo        | ThinkPad 8 20BN001RMN       | Tablet      | [6801265f9f](https://linux-hardware.org/?probe=6801265f9f) | Jul 12, 2023 |
| HP            | 8299                        | Desktop     | [763cebf303](https://linux-hardware.org/?probe=763cebf303) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [7190b16550](https://linux-hardware.org/?probe=7190b16550) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7c6ad4407b](https://linux-hardware.org/?probe=7c6ad4407b) | Jul 11, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [c81c5855d4](https://linux-hardware.org/?probe=c81c5855d4) | Jul 11, 2023 |
| HP            | Compaq 2510p                | Notebook    | [a7cb1d43fb](https://linux-hardware.org/?probe=a7cb1d43fb) | Jul 11, 2023 |
| HP            | Pavilion g4                 | Notebook    | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ab81f36697](https://linux-hardware.org/?probe=ab81f36697) | Jul 11, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [8e5774c497](https://linux-hardware.org/?probe=8e5774c497) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| HP            | Compaq 2510p                | Notebook    | [98d500c68c](https://linux-hardware.org/?probe=98d500c68c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | Notebook    | [621eaf410c](https://linux-hardware.org/?probe=621eaf410c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | Notebook    | [3631291aa8](https://linux-hardware.org/?probe=3631291aa8) | Jul 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [2ed1092e31](https://linux-hardware.org/?probe=2ed1092e31) | Jul 10, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [6eb4d71389](https://linux-hardware.org/?probe=6eb4d71389) | Jul 10, 2023 |
| HP            | Notebook                    | Notebook    | [7d4bc75f38](https://linux-hardware.org/?probe=7d4bc75f38) | Jul 09, 2023 |
| ASUSTek       | K54C                        | Notebook    | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [213c80bbee](https://linux-hardware.org/?probe=213c80bbee) | Jul 09, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [938e9efd55](https://linux-hardware.org/?probe=938e9efd55) | Jul 09, 2023 |
| Unknown       | SLR-0308                    | Notebook    | [d5b0d30e8d](https://linux-hardware.org/?probe=d5b0d30e8d) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [be65f2aa45](https://linux-hardware.org/?probe=be65f2aa45) | Jul 08, 2023 |
| OTVOC         | N1                          | Notebook    | [1b4d619110](https://linux-hardware.org/?probe=1b4d619110) | Jul 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [7b62ed78d1](https://linux-hardware.org/?probe=7b62ed78d1) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | Notebook    | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [203ffa97b4](https://linux-hardware.org/?probe=203ffa97b4) | Jul 06, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [24a4044173](https://linux-hardware.org/?probe=24a4044173) | Jul 06, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [8a9c93e501](https://linux-hardware.org/?probe=8a9c93e501) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | Notebook    | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| Dell          | 0GFYJR A00                  | Server      | [573c8bd5bd](https://linux-hardware.org/?probe=573c8bd5bd) | Jul 06, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [774ebec1d8](https://linux-hardware.org/?probe=774ebec1d8) | Jul 05, 2023 |
| ASRock        | FP6D4-P1                    | Desktop     | [42b5bdcdd7](https://linux-hardware.org/?probe=42b5bdcdd7) | Jul 05, 2023 |
| Positivo      | POS-EIH61CE SIM             | Desktop     | [48b35c757d](https://linux-hardware.org/?probe=48b35c757d) | Jul 05, 2023 |
| Intel         | H55                         | Desktop     | [8f8ff68380](https://linux-hardware.org/?probe=8f8ff68380) | Jul 04, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [9bca67bb40](https://linux-hardware.org/?probe=9bca67bb40) | Jul 04, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| HP            | 21F5 0A                     | Desktop     | [bc7304ba1c](https://linux-hardware.org/?probe=bc7304ba1c) | Jul 04, 2023 |
| HP            | 2B3E                        | All in one  | [bfa310e490](https://linux-hardware.org/?probe=bfa310e490) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [452fe27c46](https://linux-hardware.org/?probe=452fe27c46) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [168d5b0b7b](https://linux-hardware.org/?probe=168d5b0b7b) | Jul 04, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [21adb87fbd](https://linux-hardware.org/?probe=21adb87fbd) | Jul 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7672f159bf](https://linux-hardware.org/?probe=7672f159bf) | Jul 03, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| HP            | 2B3E                        | All in one  | [c6f01baa52](https://linux-hardware.org/?probe=c6f01baa52) | Jul 03, 2023 |
| OTVOC         | N1                          | Notebook    | [833ed0c86b](https://linux-hardware.org/?probe=833ed0c86b) | Jul 02, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [729dbec695](https://linux-hardware.org/?probe=729dbec695) | Jul 02, 2023 |
| HP            | ENVY m6                     | Notebook    | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [2bc4b36c94](https://linux-hardware.org/?probe=2bc4b36c94) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | Desktop     | [c787bf91c3](https://linux-hardware.org/?probe=c787bf91c3) | Jul 02, 2023 |
| Unknown       | V00                         | Mini pc     | [ab56e54ced](https://linux-hardware.org/?probe=ab56e54ced) | Jul 01, 2023 |
| Unknown       | V00                         | Mini pc     | [36483eddb0](https://linux-hardware.org/?probe=36483eddb0) | Jul 01, 2023 |
| HP            | Compaq 6830s                | Notebook    | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| TrekStor      | YOURBOOK C11B               | Convertible | [8c2340f01f](https://linux-hardware.org/?probe=8c2340f01f) | Jul 01, 2023 |
| Win Elemen... | M9                          | Desktop     | [2e5ea821f1](https://linux-hardware.org/?probe=2e5ea821f1) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | Desktop     | [a4e29f77e5](https://linux-hardware.org/?probe=a4e29f77e5) | Jul 01, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [e47898dc3d](https://linux-hardware.org/?probe=e47898dc3d) | Jun 29, 2023 |
| MSI           | H61M-P31                    | Desktop     | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | Desktop     | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| HP            | ENVY m6                     | Notebook    | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| Dell          | Latitude E6400              | Notebook    | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [663ce69f30](https://linux-hardware.org/?probe=663ce69f30) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [73eab89788](https://linux-hardware.org/?probe=73eab89788) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | Notebook    | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DA50... | Notebook    | [b756e54029](https://linux-hardware.org/?probe=b756e54029) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [0a35c3c750](https://linux-hardware.org/?probe=0a35c3c750) | Jun 27, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [18ab778722](https://linux-hardware.org/?probe=18ab778722) | Jun 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [da86501858](https://linux-hardware.org/?probe=da86501858) | Jun 26, 2023 |
| Dell          | Latitude 3189               | Notebook    | [ad7c98c905](https://linux-hardware.org/?probe=ad7c98c905) | Jun 26, 2023 |
| Dell          | Latitude 3189               | Notebook    | [8547503af5](https://linux-hardware.org/?probe=8547503af5) | Jun 25, 2023 |
| Dell          | Latitude 3189               | Notebook    | [3f44430a36](https://linux-hardware.org/?probe=3f44430a36) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | Notebook    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [23134d6c71](https://linux-hardware.org/?probe=23134d6c71) | Jun 24, 2023 |
| Dell          | Latitude E6400              | Notebook    | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| ASUSTek       | P5B                         | Desktop     | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| Acer          | AOD270                      | Notebook    | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | Notebook    | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [1773c81302](https://linux-hardware.org/?probe=1773c81302) | Jun 23, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [80b535ff26](https://linux-hardware.org/?probe=80b535ff26) | Jun 23, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [177d2fe509](https://linux-hardware.org/?probe=177d2fe509) | Jun 22, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| Google        | Kefka                       | Notebook    | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [ae8c13c6fd](https://linux-hardware.org/?probe=ae8c13c6fd) | Jun 22, 2023 |
| Dell          | 0G9322                      | Desktop     | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| AZW           | SER                         | Mini pc     | [9ef166eb46](https://linux-hardware.org/?probe=9ef166eb46) | Jun 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [3d558ea9aa](https://linux-hardware.org/?probe=3d558ea9aa) | Jun 21, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [b28f58f09e](https://linux-hardware.org/?probe=b28f58f09e) | Jun 20, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [0d3af8114b](https://linux-hardware.org/?probe=0d3af8114b) | Jun 20, 2023 |
| HP            | ENVY m6                     | Notebook    | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [72ef7ff0aa](https://linux-hardware.org/?probe=72ef7ff0aa) | Jun 20, 2023 |
| Dell          | G7 7588                     | Notebook    | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [88d7f8992f](https://linux-hardware.org/?probe=88d7f8992f) | Jun 19, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [93587f51a9](https://linux-hardware.org/?probe=93587f51a9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | Notebook    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| AZW           | GTR V02                     | Desktop     | [f9bee18426](https://linux-hardware.org/?probe=f9bee18426) | Jun 19, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [46bd956cbf](https://linux-hardware.org/?probe=46bd956cbf) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [7546cac791](https://linux-hardware.org/?probe=7546cac791) | Jun 19, 2023 |
| ASUSTek       | P5LD2                       | Desktop     | [7038963b77](https://linux-hardware.org/?probe=7038963b77) | Jun 18, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | Notebook    | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [bb6859a141](https://linux-hardware.org/?probe=bb6859a141) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [1d158627b0](https://linux-hardware.org/?probe=1d158627b0) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [7d9f25dc5f](https://linux-hardware.org/?probe=7d9f25dc5f) | Jun 17, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| Haier         | Y11B                        | Notebook    | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [9c53e4cd72](https://linux-hardware.org/?probe=9c53e4cd72) | Jun 17, 2023 |
| HP            | G62                         | Notebook    | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | Notebook    | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| ASRock        | B85M                        | Desktop     | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [c503081708](https://linux-hardware.org/?probe=c503081708) | Jun 15, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [b00d413241](https://linux-hardware.org/?probe=b00d413241) | Jun 14, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [1d487a1ed5](https://linux-hardware.org/?probe=1d487a1ed5) | Jun 14, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [eab79964fb](https://linux-hardware.org/?probe=eab79964fb) | Jun 14, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b737ce6557](https://linux-hardware.org/?probe=b737ce6557) | Jun 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [f46f1000c0](https://linux-hardware.org/?probe=f46f1000c0) | Jun 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [535d3d42b7](https://linux-hardware.org/?probe=535d3d42b7) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| ASUSTek       | P5B                         | Desktop     | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| HP            | ENVY m6                     | Notebook    | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| MSI           | GL62M 7RDX                  | Notebook    | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9cb593e9e1](https://linux-hardware.org/?probe=9cb593e9e1) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [9ea7188339](https://linux-hardware.org/?probe=9ea7188339) | Jun 11, 2023 |
| HP            | 8350                        | Desktop     | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| ASUSTek       | P5B                         | Desktop     | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| MP            | MS-7848                     | Desktop     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Google        | Pirika                      | Notebook    | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Precision 7520              | Notebook    | [c52fb2f851](https://linux-hardware.org/?probe=c52fb2f851) | Jun 10, 2023 |
| Nvidia        | MCP79                       | Desktop     | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [e1ff6f4e2f](https://linux-hardware.org/?probe=e1ff6f4e2f) | Jun 08, 2023 |
| ASUSTek       | P5B                         | Desktop     | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [74cf1d0b63](https://linux-hardware.org/?probe=74cf1d0b63) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [88cbeea389](https://linux-hardware.org/?probe=88cbeea389) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2ad7aefc45](https://linux-hardware.org/?probe=2ad7aefc45) | Jun 07, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [2ad409f60a](https://linux-hardware.org/?probe=2ad409f60a) | Jun 07, 2023 |
| HP            | 8350                        | Desktop     | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| Dell          | 0G9322                      | Desktop     | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Nvidia        | MCP79                       | Desktop     | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [79f63dcf8e](https://linux-hardware.org/?probe=79f63dcf8e) | Jun 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [d48dc73993](https://linux-hardware.org/?probe=d48dc73993) | Jun 06, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [a98deb1f54](https://linux-hardware.org/?probe=a98deb1f54) | Jun 06, 2023 |
| ASUSTek       | CM1730,CM1830               | Desktop     | [2cc76d0cd9](https://linux-hardware.org/?probe=2cc76d0cd9) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | Desktop     | [7dc46d923e](https://linux-hardware.org/?probe=7dc46d923e) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| Dell          | 00010C A00                  | Desktop     | [fb12198605](https://linux-hardware.org/?probe=fb12198605) | Jun 05, 2023 |
| Dell          | 00010C A00                  | Desktop     | [d94442285c](https://linux-hardware.org/?probe=d94442285c) | Jun 05, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [e3b8e1a109](https://linux-hardware.org/?probe=e3b8e1a109) | Jun 04, 2023 |
| Dell          | Latitude E5250              | Notebook    | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | Notebook    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [a20f9c3365](https://linux-hardware.org/?probe=a20f9c3365) | Jun 03, 2023 |
| Dell          | 0G9322                      | Desktop     | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [01387c3030](https://linux-hardware.org/?probe=01387c3030) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [20260fb3b3](https://linux-hardware.org/?probe=20260fb3b3) | Jun 03, 2023 |
| HP            | 339A                        | Desktop     | [bb4619f4eb](https://linux-hardware.org/?probe=bb4619f4eb) | Jun 02, 2023 |
| Gateway       | SX2851                      | Desktop     | [262ddffda9](https://linux-hardware.org/?probe=262ddffda9) | Jun 02, 2023 |
| IPASON        | P3                          | Notebook    | [bd9e0660a4](https://linux-hardware.org/?probe=bd9e0660a4) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | Notebook    | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| MSI           | H81M-E34                    | Desktop     | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| MSI           | H81M-E34                    | Desktop     | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | Desktop     | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| HP            | 82B5                        | All in one  | [77ecbfa91c](https://linux-hardware.org/?probe=77ecbfa91c) | Jun 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [a7af6cac2c](https://linux-hardware.org/?probe=a7af6cac2c) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [0198d67a15](https://linux-hardware.org/?probe=0198d67a15) | May 31, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [449b742c95](https://linux-hardware.org/?probe=449b742c95) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Sony          | SVF14214CXW                 | Notebook    | [51568ce56e](https://linux-hardware.org/?probe=51568ce56e) | May 30, 2023 |
| Dell          | Latitude 3480               | Notebook    | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| Sony          | SVF14214CXW                 | Notebook    | [6cf7c2d7f2](https://linux-hardware.org/?probe=6cf7c2d7f2) | May 30, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [db28d8f731](https://linux-hardware.org/?probe=db28d8f731) | May 28, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [36bd3a5288](https://linux-hardware.org/?probe=36bd3a5288) | May 28, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | Notebook    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Acer          | Predator G3-605             | Desktop     | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [8c51cdf4ef](https://linux-hardware.org/?probe=8c51cdf4ef) | May 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9f96328490](https://linux-hardware.org/?probe=9f96328490) | May 27, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [48a2156205](https://linux-hardware.org/?probe=48a2156205) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 21D0                        | Desktop     | [7f83859a91](https://linux-hardware.org/?probe=7f83859a91) | May 27, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 230       | 5.46%   |
| 5.11.0-38-generic | 180       | 4.27%   |
| 5.11.0-27-generic | 156       | 3.7%    |
| 5.15.0-46-generic | 152       | 3.61%   |
| 5.15.0-58-generic | 151       | 3.58%   |
| 5.15.0-52-generic | 151       | 3.58%   |
| 5.15.0-67-generic | 143       | 3.39%   |
| 5.15.0-69-generic | 136       | 3.23%   |
| 5.13.0-30-generic | 126       | 2.99%   |
| 5.11.0-40-generic | 124       | 2.94%   |
| 5.13.0-39-generic | 122       | 2.89%   |
| 5.15.0-78-generic | 114       | 2.7%    |
| 5.15.0-60-generic | 109       | 2.59%   |
| 5.11.0-41-generic | 108       | 2.56%   |
| 5.11.0-37-generic | 107       | 2.54%   |
| 5.15.0-76-generic | 105       | 2.49%   |
| 5.15.0-71-generic | 103       | 2.44%   |
| 5.11.0-43-generic | 101       | 2.4%    |
| 5.15.0-48-generic | 95        | 2.25%   |
| 5.11.0-34-generic | 94        | 2.23%   |
| 5.13.0-40-generic | 90        | 2.13%   |
| 5.15.0-53-generic | 81        | 1.92%   |
| 5.15.0-84-generic | 79        | 1.87%   |
| 5.15.0-41-generic | 77        | 1.83%   |
| 5.13.0-44-generic | 76        | 1.8%    |
| 5.13.0-35-generic | 74        | 1.76%   |
| 5.13.0-28-generic | 73        | 1.73%   |
| 5.15.0-73-generic | 68        | 1.61%   |
| 5.15.0-86-generic | 62        | 1.47%   |
| 5.15.0-83-generic | 59        | 1.4%    |
| 5.15.0-72-generic | 59        | 1.4%    |
| 5.13.0-52-generic | 59        | 1.4%    |
| 5.13.0-27-generic | 59        | 1.4%    |
| 5.15.0-79-generic | 55        | 1.3%    |
| 5.13.0-41-generic | 54        | 1.28%   |
| 5.13.0-51-generic | 42        | 1%      |
| 5.15.0-87-generic | 40        | 0.95%   |
| 5.15.0-75-generic | 40        | 0.95%   |
| 5.15.0-43-generic | 40        | 0.95%   |
| 5.11.0-36-generic | 39        | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 1965      | 51.71%  |
| 5.11.0  | 951       | 25.03%  |
| 5.13.0  | 769       | 20.24%  |
| 5.8.0   | 53        | 1.39%   |
| 5.14.0  | 10        | 0.26%   |
| 5.4.0   | 4         | 0.11%   |
| 6.5.7   | 2         | 0.05%   |
| 6.3.2   | 2         | 0.05%   |
| 6.3.13  | 2         | 0.05%   |
| 6.2.16  | 2         | 0.05%   |
| 5.19.12 | 2         | 0.05%   |
| 5.19.0  | 2         | 0.05%   |
| 5.18.15 | 2         | 0.05%   |
| 5.17.5  | 2         | 0.05%   |
| 5.17.1  | 2         | 0.05%   |
| 5.16.0  | 2         | 0.05%   |
| 5.10.0  | 2         | 0.05%   |
| 6.3.1   | 1         | 0.03%   |
| 6.2.7   | 1         | 0.03%   |
| 6.2.14  | 1         | 0.03%   |
| 6.1.8   | 1         | 0.03%   |
| 6.1.7   | 1         | 0.03%   |
| 6.1.22  | 1         | 0.03%   |
| 6.0.9   | 1         | 0.03%   |
| 6.0.8   | 1         | 0.03%   |
| 6.0.19  | 1         | 0.03%   |
| 6.0.0   | 1         | 0.03%   |
| 5.4.180 | 1         | 0.03%   |
| 5.19.9  | 1         | 0.03%   |
| 5.19.6  | 1         | 0.03%   |
| 5.19.2  | 1         | 0.03%   |
| 5.19.14 | 1         | 0.03%   |
| 5.19.1  | 1         | 0.03%   |
| 5.18.6  | 1         | 0.03%   |
| 5.18.19 | 1         | 0.03%   |
| 5.17.9  | 1         | 0.03%   |
| 5.16.5  | 1         | 0.03%   |
| 5.16.14 | 1         | 0.03%   |
| 5.16.12 | 1         | 0.03%   |
| 5.15.49 | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1968      | 51.8%   |
| 5.11    | 951       | 25.03%  |
| 5.13    | 770       | 20.27%  |
| 5.8     | 53        | 1.4%    |
| 5.14    | 10        | 0.26%   |
| 5.19    | 9         | 0.24%   |
| 6.3     | 5         | 0.13%   |
| 5.4     | 5         | 0.13%   |
| 5.17    | 5         | 0.13%   |
| 5.16    | 5         | 0.13%   |
| 6.2     | 4         | 0.11%   |
| 6.0     | 4         | 0.11%   |
| 5.18    | 4         | 0.11%   |
| 6.5     | 2         | 0.05%   |
| 6.1     | 2         | 0.05%   |
| 5.10    | 2         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 3642      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 3121      | 85.02%  |
| XFCE       | 504       | 13.73%  |
| Unknown    | 22        | 0.6%    |
| KDE5       | 6         | 0.16%   |
| X-Cinnamon | 4         | 0.11%   |
| Cinnamon   | 3         | 0.08%   |
| Budgie     | 3         | 0.08%   |
| Unity      | 2         | 0.05%   |
| i3         | 2         | 0.05%   |
| MATE       | 1         | 0.03%   |
| LXQt       | 1         | 0.03%   |
| LXDE       | 1         | 0.03%   |
| KDE        | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3590      | 97.95%  |
| Wayland | 66        | 1.8%    |
| Unknown | 7         | 0.19%   |
| Tty     | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2837      | 76.8%   |
| GDM     | 390       | 10.56%  |
| GDM3    | 331       | 8.96%   |
| LightDM | 132       | 3.57%   |
| SDDM    | 2         | 0.05%   |
| TDM     | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 1446      | 39.52%  |
| de_DE | 344       | 9.4%    |
| en_GB | 246       | 6.72%   |
| pt_BR | 207       | 5.66%   |
| fr_FR | 139       | 3.8%    |
| it_IT | 116       | 3.17%   |
| es_ES | 112       | 3.06%   |
| en_CA | 102       | 2.79%   |
| en_IN | 95        | 2.6%    |
| pl_PL | 89        | 2.43%   |
| en_AU | 70        | 1.91%   |
| nl_NL | 62        | 1.69%   |
| es_MX | 52        | 1.42%   |
| ru_RU | 46        | 1.26%   |
| en_ZA | 37        | 1.01%   |
| pt_PT | 32        | 0.87%   |
| cs_CZ | 31        | 0.85%   |
| es_AR | 30        | 0.82%   |
| hu_HU | 26        | 0.71%   |
| sv_SE | 24        | 0.66%   |
| en_NZ | 21        | 0.57%   |
| tr_TR | 20        | 0.55%   |
| nl_BE | 20        | 0.55%   |
| es_CL | 18        | 0.49%   |
| fr_BE | 17        | 0.46%   |
| de_CH | 16        | 0.44%   |
| fr_CA | 13        | 0.36%   |
| de_AT | 12        | 0.33%   |
| ja_JP | 11        | 0.3%    |
| fi_FI | 11        | 0.3%    |
| es_CO | 11        | 0.3%    |
| en_PH | 10        | 0.27%   |
| nb_NO | 9         | 0.25%   |
| el_GR | 9         | 0.25%   |
| sk_SK | 8         | 0.22%   |
| es_VE | 8         | 0.22%   |
| ar_EG | 8         | 0.22%   |
| es_CR | 7         | 0.19%   |
| da_DK | 7         | 0.19%   |
| zh_CN | 6         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2136      | 57.87%  |
| BIOS | 1555      | 42.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3393      | 92.48%  |
| Tmpfs    | 87        | 2.37%   |
| Zfs      | 68        | 1.85%   |
| Overlay  | 60        | 1.64%   |
| Btrfs    | 36        | 0.98%   |
| Xfs      | 9         | 0.25%   |
| Ext2     | 9         | 0.25%   |
| Ext3     | 5         | 0.14%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3013      | 81.63%  |
| GPT     | 525       | 14.22%  |
| MBR     | 153       | 4.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3550      | 97.21%  |
| Yes       | 102       | 2.79%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3295      | 90.18%  |
| Yes       | 359       | 9.82%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 601       | 16.5%   |
| ASUSTek Computer    | 524       | 14.39%  |
| Dell                | 486       | 13.34%  |
| Lenovo              | 471       | 12.93%  |
| Gigabyte Technology | 209       | 5.74%   |
| Acer                | 186       | 5.11%   |
| MSI                 | 178       | 4.89%   |
| Apple               | 135       | 3.71%   |
| ASRock              | 90        | 2.47%   |
| Toshiba             | 80        | 2.2%    |
| Intel               | 61        | 1.67%   |
| Unknown             | 42        | 1.15%   |
| Samsung Electronics | 40        | 1.1%    |
| Sony                | 32        | 0.88%   |
| Google              | 32        | 0.88%   |
| Fujitsu             | 26        | 0.71%   |
| Microsoft           | 25        | 0.69%   |
| Biostar             | 20        | 0.55%   |
| Pegatron            | 19        | 0.52%   |
| Packard Bell        | 19        | 0.52%   |
| HUAWEI              | 18        | 0.49%   |
| Positivo            | 17        | 0.47%   |
| Foxconn             | 15        | 0.41%   |
| Alienware           | 15        | 0.41%   |
| AZW                 | 14        | 0.38%   |
| Medion              | 13        | 0.36%   |
| Chuwi               | 11        | 0.3%    |
| AMI                 | 10        | 0.27%   |
| Notebook            | 9         | 0.25%   |
| Multilaser          | 7         | 0.19%   |
| GPU Company         | 7         | 0.19%   |
| Fujitsu Siemens     | 7         | 0.19%   |
| Gateway             | 6         | 0.16%   |
| BESSTAR Tech        | 6         | 0.16%   |
| Thomson             | 5         | 0.14%   |
| LG Electronics      | 5         | 0.14%   |
| TrekStor            | 4         | 0.11%   |
| Semp Toshiba        | 4         | 0.11%   |
| RCA                 | 4         | 0.11%   |
| Razer               | 4         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 54        | 1.48%   |
| ASUS All Series                  | 31        | 0.85%   |
| HP Notebook                      | 22        | 0.6%    |
| HP Pavilion Notebook             | 14        | 0.38%   |
| HP 15                            | 13        | 0.36%   |
| Dell OptiPlex 7010               | 13        | 0.36%   |
| MSI MS-7817                      | 9         | 0.25%   |
| HP Pavilion dv7                  | 9         | 0.25%   |
| HP Pavilion dv6                  | 9         | 0.25%   |
| HP Pavilion 15                   | 9         | 0.25%   |
| Dell OptiPlex 790                | 8         | 0.22%   |
| Apple MacBookPro8,1              | 8         | 0.22%   |
| Apple iMac12,2                   | 8         | 0.22%   |
| Apple iMac12,1                   | 8         | 0.22%   |
| Lenovo MIIX 320-10ICR 80XF       | 7         | 0.19%   |
| Dell OptiPlex 780                | 7         | 0.19%   |
| Dell OptiPlex 380                | 7         | 0.19%   |
| ASUS M5A78L-M/USB3               | 7         | 0.19%   |
| Apple iMac10,1                   | 7         | 0.19%   |
| MSI MS-7C02                      | 6         | 0.16%   |
| Microsoft Surface Pro 4          | 6         | 0.16%   |
| Microsoft Surface Pro            | 6         | 0.16%   |
| Gigabyte A320M-S2H               | 6         | 0.16%   |
| Dell Latitude E6540              | 6         | 0.16%   |
| Dell Latitude E6520              | 6         | 0.16%   |
| ASUS TUF Gaming X570-PLUS        | 6         | 0.16%   |
| ASUS M5A97 R2.0                  | 6         | 0.16%   |
| Apple MacBookPro12,1             | 6         | 0.16%   |
| MSI MS-7C37                      | 5         | 0.14%   |
| Intel H61                        | 5         | 0.14%   |
| HP ProBook 640 G1                | 5         | 0.14%   |
| HP Pavilion g7                   | 5         | 0.14%   |
| HP Pavilion g6                   | 5         | 0.14%   |
| HP EliteBook 2570p               | 5         | 0.14%   |
| HP Compaq Pro 6300 SFF           | 5         | 0.14%   |
| GPU Company GWTC116-2            | 5         | 0.14%   |
| Gigabyte B450 AORUS M            | 5         | 0.14%   |
| Dell Precision WorkStation T3500 | 5         | 0.14%   |
| Dell OptiPlex 990                | 5         | 0.14%   |
| Dell OptiPlex 3020               | 5         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 153       | 4.2%    |
| Dell Latitude         | 127       | 3.49%   |
| Acer Aspire           | 126       | 3.46%   |
| Dell Inspiron         | 125       | 3.43%   |
| HP Pavilion           | 122       | 3.35%   |
| Lenovo IdeaPad        | 116       | 3.19%   |
| Dell OptiPlex         | 95        | 2.61%   |
| Toshiba Satellite     | 65        | 1.78%   |
| HP EliteBook          | 65        | 1.78%   |
| HP Compaq             | 55        | 1.51%   |
| Unknown               | 54        | 1.48%   |
| ASUS ROG              | 52        | 1.43%   |
| HP ProBook            | 48        | 1.32%   |
| ASUS PRIME            | 47        | 1.29%   |
| HP Laptop             | 45        | 1.24%   |
| Lenovo ThinkCentre    | 41        | 1.13%   |
| ASUS TUF              | 39        | 1.07%   |
| ASUS VivoBook         | 38        | 1.04%   |
| Dell Precision        | 37        | 1.02%   |
| Dell XPS              | 31        | 0.85%   |
| ASUS All              | 31        | 0.85%   |
| Lenovo Yoga           | 30        | 0.82%   |
| HP ENVY               | 30        | 0.82%   |
| Dell Vostro           | 29        | 0.8%    |
| Microsoft Surface     | 25        | 0.69%   |
| HP Notebook           | 22        | 0.6%    |
| HP EliteDesk          | 21        | 0.58%   |
| HP Stream             | 18        | 0.49%   |
| ASUS ZenBook          | 16        | 0.44%   |
| Apple iMac12          | 16        | 0.44%   |
| Packard Bell EasyNote | 15        | 0.41%   |
| HP 15                 | 15        | 0.41%   |
| Lenovo Legion         | 13        | 0.36%   |
| HP ProDesk            | 13        | 0.36%   |
| HP OMEN               | 13        | 0.36%   |
| Gigabyte B450         | 12        | 0.33%   |
| Fujitsu ESPRIMO       | 12        | 0.33%   |
| ASUS ASUS             | 12        | 0.33%   |
| Lenovo MIIX           | 11        | 0.3%    |
| Dell Studio           | 11        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 307       | 8.43%   |
| 2012    | 305       | 8.37%   |
| 2011    | 302       | 8.29%   |
| 2013    | 298       | 8.18%   |
| 2018    | 283       | 7.77%   |
| 2020    | 272       | 7.47%   |
| 2019    | 257       | 7.06%   |
| 2014    | 251       | 6.89%   |
| 2017    | 235       | 6.45%   |
| 2010    | 203       | 5.57%   |
| 2016    | 193       | 5.3%    |
| 2015    | 186       | 5.11%   |
| 2008    | 152       | 4.17%   |
| 2009    | 133       | 3.65%   |
| 2022    | 108       | 2.97%   |
| 2007    | 82        | 2.25%   |
| 2023    | 42        | 1.15%   |
| 2006    | 23        | 0.63%   |
| 2005    | 6         | 0.16%   |
| Unknown | 4         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1991      | 54.67%  |
| Desktop     | 1329      | 36.49%  |
| Convertible | 96        | 2.64%   |
| All in one  | 89        | 2.44%   |
| Tablet      | 66        | 1.81%   |
| Mini pc     | 62        | 1.7%    |
| Server      | 9         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3218      | 87.54%  |
| Enabled  | 458       | 12.46%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3606      | 99.01%  |
| Yes  | 36        | 0.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1000      | 27.19%  |
| 3.01-4.0        | 793       | 21.56%  |
| 16.01-24.0      | 630       | 17.13%  |
| 8.01-16.0       | 615       | 16.72%  |
| 32.01-64.0      | 290       | 7.88%   |
| 1.01-2.0        | 169       | 4.59%   |
| 64.01-256.0     | 72        | 1.96%   |
| 24.01-32.0      | 51        | 1.39%   |
| 2.01-3.0        | 50        | 1.36%   |
| 0.51-1.0        | 7         | 0.19%   |
| More than 256.0 | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1482      | 37.28%  |
| 2.01-3.0   | 1309      | 32.93%  |
| 3.01-4.0   | 548       | 13.79%  |
| 4.01-8.0   | 471       | 11.85%  |
| 8.01-16.0  | 73        | 1.84%   |
| 0.51-1.0   | 73        | 1.84%   |
| 16.01-24.0 | 11        | 0.28%   |
| 24.01-32.0 | 5         | 0.13%   |
| 32.01-64.0 | 2         | 0.05%   |
| 0.01-0.5   | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2376      | 63.79%  |
| 2      | 897       | 24.08%  |
| 3      | 220       | 5.91%   |
| 4      | 107       | 2.87%   |
| 5      | 54        | 1.45%   |
| 6      | 33        | 0.89%   |
| 0      | 15        | 0.4%    |
| 7      | 11        | 0.3%    |
| 8      | 8         | 0.21%   |
| 51     | 1         | 0.03%   |
| 30     | 1         | 0.03%   |
| 11     | 1         | 0.03%   |
| 9      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2125      | 58.06%  |
| Yes       | 1535      | 41.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3037      | 83.21%  |
| No        | 613       | 16.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2902      | 79.33%  |
| No        | 756       | 20.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2168      | 58.96%  |
| No        | 1509      | 41.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 860       | 23.52%  |
| Germany      | 374       | 10.23%  |
| Brazil       | 230       | 6.29%   |
| UK           | 224       | 6.13%   |
| Canada       | 129       | 3.53%   |
| France       | 128       | 3.5%    |
| Italy        | 127       | 3.47%   |
| Spain        | 122       | 3.34%   |
| Netherlands  | 107       | 2.93%   |
| India        | 99        | 2.71%   |
| Poland       | 86        | 2.35%   |
| Australia    | 71        | 1.94%   |
| Mexico       | 70        | 1.91%   |
| Belgium      | 50        | 1.37%   |
| Russia       | 46        | 1.26%   |
| Sweden       | 42        | 1.15%   |
| South Africa | 41        | 1.12%   |
| Portugal     | 40        | 1.09%   |
| Argentina    | 38        | 1.04%   |
| Switzerland  | 35        | 0.96%   |
| Czechia      | 35        | 0.96%   |
| Austria      | 35        | 0.96%   |
| Turkey       | 32        | 0.88%   |
| Hungary      | 32        | 0.88%   |
| Romania      | 28        | 0.77%   |
| Norway       | 28        | 0.77%   |
| Greece       | 26        | 0.71%   |
| New Zealand  | 23        | 0.63%   |
| Japan        | 22        | 0.6%    |
| Chile        | 22        | 0.6%    |
| Egypt        | 21        | 0.57%   |
| Denmark      | 20        | 0.55%   |
| Indonesia    | 19        | 0.52%   |
| Finland      | 19        | 0.52%   |
| Colombia     | 18        | 0.49%   |
| Bulgaria     | 15        | 0.41%   |
| Serbia       | 13        | 0.36%   |
| Slovakia     | 12        | 0.33%   |
| Philippines  | 12        | 0.33%   |
| Malaysia     | 12        | 0.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 32        | 0.84%   |
| Munich            | 26        | 0.68%   |
| Madrid            | 20        | 0.52%   |
| Athens            | 20        | 0.52%   |
| Rome              | 19        | 0.5%    |
| Vienna            | 18        | 0.47%   |
| Sydney            | 18        | 0.47%   |
| New York          | 18        | 0.47%   |
| Sao Paulo         | 17        | 0.44%   |
| Hamburg           | 17        | 0.44%   |
| Rio de Janeiro    | 16        | 0.42%   |
| Milan             | 16        | 0.42%   |
| Montreal          | 15        | 0.39%   |
| Dallas            | 15        | 0.39%   |
| Amsterdam         | 15        | 0.39%   |
| Paris             | 14        | 0.37%   |
| Denver            | 14        | 0.37%   |
| London            | 13        | 0.34%   |
| Cape Town         | 13        | 0.34%   |
| Melbourne         | 12        | 0.31%   |
| Johannesburg      | 12        | 0.31%   |
| Delhi             | 12        | 0.31%   |
| Toronto           | 11        | 0.29%   |
| Salt Lake City    | 11        | 0.29%   |
| Mexico City       | 11        | 0.29%   |
| Frankfurt am Main | 11        | 0.29%   |
| Valencia          | 10        | 0.26%   |
| Stockholm         | 10        | 0.26%   |
| Seattle           | 10        | 0.26%   |
| Phoenix           | 10        | 0.26%   |
| Perth             | 10        | 0.26%   |
| Moscow            | 10        | 0.26%   |
| Jakarta           | 10        | 0.26%   |
| Istanbul          | 10        | 0.26%   |
| Houston           | 10        | 0.26%   |
| Buenos Aires      | 10        | 0.26%   |
| Bucharest         | 10        | 0.26%   |
| Bengaluru         | 10        | 0.26%   |
| Barcelona         | 10        | 0.26%   |
| Auckland          | 10        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 755       | 1089   | 14.64%  |
| Samsung Electronics         | 681       | 972    | 13.21%  |
| WDC                         | 660       | 909    | 12.8%   |
| Toshiba                     | 356       | 458    | 6.9%    |
| SanDisk                     | 320       | 398    | 6.21%   |
| Unknown                     | 304       | 419    | 5.89%   |
| Kingston                    | 274       | 385    | 5.31%   |
| Crucial                     | 183       | 224    | 3.55%   |
| Hitachi                     | 160       | 211    | 3.1%    |
| SK hynix                    | 107       | 125    | 2.07%   |
| Intel                       | 107       | 139    | 2.07%   |
| HGST                        | 86        | 108    | 1.67%   |
| Micron Technology           | 74        | 87     | 1.43%   |
| China                       | 74        | 90     | 1.43%   |
| A-DATA Technology           | 71        | 90     | 1.38%   |
| Apple                       | 62        | 71     | 1.2%    |
| Intenso                     | 42        | 45     | 0.81%   |
| Silicon Motion              | 38        | 49     | 0.74%   |
| KIOXIA                      | 36        | 41     | 0.7%    |
| Phison                      | 35        | 40     | 0.68%   |
| Unknown                     | 32        | 36     | 0.62%   |
| PNY                         | 31        | 39     | 0.6%    |
| SPCC                        | 30        | 43     | 0.58%   |
| Patriot                     | 28        | 37     | 0.54%   |
| Netac                       | 27        | 30     | 0.52%   |
| Micron/Crucial Technology   | 24        | 29     | 0.47%   |
| GOODRAM                     | 24        | 28     | 0.47%   |
| JMicron Technology          | 20        | 25     | 0.39%   |
| Phison Electronics          | 18        | 21     | 0.35%   |
| OCZ                         | 18        | 21     | 0.35%   |
| LITEON                      | 18        | 20     | 0.35%   |
| Team                        | 16        | 19     | 0.31%   |
| Lexar                       | 16        | 16     | 0.31%   |
| KingSpec                    | 15        | 18     | 0.29%   |
| Hewlett-Packard             | 15        | 19     | 0.29%   |
| Transcend                   | 14        | 31     | 0.27%   |
| Realtek Semiconductor       | 14        | 15     | 0.27%   |
| Maxtor                      | 13        | 17     | 0.25%   |
| LITEONIT                    | 13        | 15     | 0.25%   |
| Kingston Technology Company | 13        | 16     | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                              | 93        | 1.64%   |
| Unknown MMC Card  32GB                              | 90        | 1.59%   |
| Kingston SA400S37240G 240GB SSD                     | 69        | 1.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 48        | 0.85%   |
| Seagate ST500DM002-1BD142 500GB                     | 45        | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB                      | 45        | 0.8%    |
| Toshiba MQ01ABD100 1TB                              | 40        | 0.71%   |
| Unknown MMC Card  128GB                             | 38        | 0.67%   |
| Crucial CT240BX500SSD1 240GB                        | 38        | 0.67%   |
| Samsung SSD 860 EVO 500GB                           | 37        | 0.65%   |
| Kingston SA400S37480G 480GB SSD                     | 36        | 0.64%   |
| Kingston SA400S37120G 120GB SSD                     | 35        | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 33        | 0.58%   |
| Unknown                                             | 32        | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB                      | 30        | 0.53%   |
| Toshiba MQ01ABF050 500GB                            | 28        | 0.49%   |
| Seagate ST500LT012-1DG142 500GB                     | 28        | 0.49%   |
| Unknown SD/MMC/MS PRO 16GB                          | 27        | 0.48%   |
| Toshiba MQ04ABF100 1TB                              | 27        | 0.48%   |
| Samsung SSD 850 EVO 250GB                           | 26        | 0.46%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 26        | 0.46%   |
| Samsung NVMe SSD Drive 512GB                        | 25        | 0.44%   |
| Samsung NVMe SSD Drive 1TB                          | 25        | 0.44%   |
| Crucial CT500MX500SSD1 500GB                        | 25        | 0.44%   |
| Samsung SSD 850 EVO 500GB                           | 24        | 0.42%   |
| Seagate ST9500325AS 500GB                           | 23        | 0.41%   |
| Seagate ST1000DM003-1CH162 1TB                      | 21        | 0.37%   |
| SanDisk NVMe SSD Drive 256GB                        | 21        | 0.37%   |
| Samsung SSD 870 EVO 1TB                             | 21        | 0.37%   |
| Samsung NVMe SSD Drive 500GB                        | 21        | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 20        | 0.35%   |
| Seagate Expansion 1TB                               | 20        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD                    | 20        | 0.35%   |
| Crucial CT1000MX500SSD1 1TB                         | 20        | 0.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 121GB | 19        | 0.34%   |
| Unknown MMC Card  16GB                              | 18        | 0.32%   |
| Toshiba HDWD110 1TB                                 | 18        | 0.32%   |
| SanDisk NVMe SSD Drive 1TB                          | 18        | 0.32%   |
| HGST HTS721010A9E630 1TB                            | 18        | 0.32%   |
| Seagate ST3500418AS 500GB                           | 17        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 745       | 1064   | 36.88%  |
| WDC                 | 567       | 770    | 28.07%  |
| Toshiba             | 275       | 360    | 13.61%  |
| Hitachi             | 160       | 211    | 7.92%   |
| HGST                | 86        | 108    | 4.26%   |
| Samsung Electronics | 83        | 102    | 4.11%   |
| Unknown             | 28        | 35     | 1.39%   |
| Apple               | 28        | 31     | 1.39%   |
| Maxtor              | 13        | 17     | 0.64%   |
| Fujitsu             | 13        | 15     | 0.64%   |
| USB3.0              | 4         | 5      | 0.2%    |
| Hewlett-Packard     | 4         | 7      | 0.2%    |
| Intenso             | 3         | 3      | 0.15%   |
| SSK                 | 2         | 2      | 0.1%    |
| JMicron Technology  | 2         | 2      | 0.1%    |
| TDAS                | 1         | 3      | 0.05%   |
| SABRENT             | 1         | 1      | 0.05%   |
| QUANTUM             | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| External            | 1         | 1      | 0.05%   |
| ACASIS              | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 343       | 480    | 19.2%   |
| Kingston            | 231       | 312    | 12.93%  |
| Crucial             | 176       | 215    | 9.85%   |
| SanDisk             | 173       | 215    | 9.69%   |
| WDC                 | 75        | 99     | 4.2%    |
| China               | 73        | 89     | 4.09%   |
| A-DATA Technology   | 62        | 81     | 3.47%   |
| Intel               | 41        | 48     | 2.3%    |
| Toshiba             | 39        | 46     | 2.18%   |
| SK hynix            | 32        | 32     | 1.79%   |
| Micron Technology   | 32        | 37     | 1.79%   |
| PNY                 | 31        | 39     | 1.74%   |
| SPCC                | 29        | 42     | 1.62%   |
| Intenso             | 28        | 30     | 1.57%   |
| Apple               | 28        | 32     | 1.57%   |
| Patriot             | 27        | 36     | 1.51%   |
| Netac               | 27        | 29     | 1.51%   |
| GOODRAM             | 22        | 26     | 1.23%   |
| LITEON              | 18        | 20     | 1.01%   |
| OCZ                 | 17        | 20     | 0.95%   |
| Team                | 16        | 19     | 0.9%    |
| Lexar               | 15        | 15     | 0.84%   |
| Transcend           | 14        | 31     | 0.78%   |
| KingSpec            | 14        | 17     | 0.78%   |
| LITEONIT            | 13        | 15     | 0.73%   |
| Unknown             | 12        | 15     | 0.67%   |
| SABRENT             | 10        | 11     | 0.56%   |
| Hewlett-Packard     | 10        | 11     | 0.56%   |
| Apacer              | 10        | 13     | 0.56%   |
| Gigabyte Technology | 9         | 10     | 0.5%    |
| Leven               | 6         | 7      | 0.34%   |
| Verbatim            | 5         | 5      | 0.28%   |
| Plextor             | 5         | 6      | 0.28%   |
| Mushkin             | 5         | 5      | 0.28%   |
| FORESEE             | 5         | 6      | 0.28%   |
| Fanxiang            | 5         | 6      | 0.28%   |
| ASMT                | 5         | 5      | 0.28%   |
| Teclast             | 4         | 4      | 0.22%   |
| Super Talent        | 4         | 5      | 0.22%   |
| Phison              | 4         | 5      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1736      | 2741   | 37.07%  |
| SSD     | 1604      | 2290   | 34.25%  |
| NVMe    | 948       | 1296   | 20.24%  |
| MMC     | 290       | 387    | 6.19%   |
| Unknown | 105       | 131    | 2.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2822      | 4876   | 66.23%  |
| NVMe | 940       | 1279   | 22.06%  |
| MMC  | 290       | 387    | 6.81%   |
| SAS  | 209       | 303    | 4.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2089      | 3064   | 60.76%  |
| 0.51-1.0   | 963       | 1346   | 28.01%  |
| 1.01-2.0   | 235       | 334    | 6.84%   |
| 3.01-4.0   | 61        | 128    | 1.77%   |
| 2.01-3.0   | 46        | 75     | 1.34%   |
| 4.01-10.0  | 37        | 57     | 1.08%   |
| 10.01-20.0 | 6         | 26     | 0.17%   |
| 20.01-50.0 | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1227      | 32.49%  |
| 251-500        | 917       | 24.28%  |
| 501-1000       | 570       | 15.09%  |
| 51-100         | 318       | 8.42%   |
| 1001-2000      | 224       | 5.93%   |
| 21-50          | 179       | 4.74%   |
| More than 3000 | 132       | 3.49%   |
| 1-20           | 91        | 2.41%   |
| 2001-3000      | 72        | 1.91%   |
| Unknown        | 47        | 1.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1470      | 37.21%  |
| 21-50          | 1121      | 28.37%  |
| 51-100         | 481       | 12.17%  |
| 101-250        | 382       | 9.67%   |
| 251-500        | 199       | 5.04%   |
| 501-1000       | 120       | 3.04%   |
| More than 3000 | 62        | 1.57%   |
| 1001-2000      | 50        | 1.27%   |
| Unknown        | 47        | 1.19%   |
| 2001-3000      | 19        | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                   | 4         | 4      | 3.64%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 2.73%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.73%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 2         | 2      | 1.82%   |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2      | 1.82%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 1.82%   |
| Seagate ST9500420AS 500GB                | 2         | 2      | 1.82%   |
| Seagate ST9500325AS 500GB                | 2         | 2      | 1.82%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 1.82%   |
| Seagate ST1000LM048-2E7172 1TB           | 2         | 2      | 1.82%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 1.82%   |
| Kingston SUV400S37240G 240GB SSD         | 2         | 2      | 1.82%   |
| HGST HTS545050A7E380 500GB               | 2         | 3      | 1.82%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1         | 1      | 0.91%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.91%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 0.91%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.91%   |
| WDC WD5000BEVT-24A0RT0 500GB             | 1         | 1      | 0.91%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 0.91%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 0.91%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1         | 1      | 0.91%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1         | 1      | 0.91%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 0.91%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 1      | 0.91%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 0.91%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 1      | 0.91%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1         | 2      | 0.91%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1         | 1      | 0.91%   |
| WDC WD Green 2.5 1000GB                  | 1         | 1      | 0.91%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.91%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.91%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 0.91%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1      | 0.91%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 0.91%   |
| Toshiba MK8046GSX 80GB                   | 1         | 1      | 0.91%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1      | 0.91%   |
| Toshiba MG03ACA200 2TB                   | 1         | 1      | 0.91%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 0.91%   |
| Teclast 128GB NS550-2242 SSD             | 1         | 1      | 0.91%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1         | 1      | 0.91%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 36     | 32.11%  |
| WDC                 | 18        | 19     | 16.51%  |
| Toshiba             | 15        | 15     | 13.76%  |
| HGST                | 10        | 11     | 9.17%   |
| Kingston            | 6         | 6      | 5.5%    |
| Samsung Electronics | 5         | 5      | 4.59%   |
| Hitachi             | 3         | 3      | 2.75%   |
| SK hynix            | 2         | 2      | 1.83%   |
| Intel               | 2         | 2      | 1.83%   |
| A-DATA Technology   | 2         | 2      | 1.83%   |
| Teclast             | 1         | 1      | 0.92%   |
| Silicon Motion      | 1         | 1      | 0.92%   |
| POLION              | 1         | 1      | 0.92%   |
| OCZ                 | 1         | 1      | 0.92%   |
| Netac               | 1         | 1      | 0.92%   |
| Maxtor              | 1         | 1      | 0.92%   |
| LITEONIT            | 1         | 1      | 0.92%   |
| Hewlett-Packard     | 1         | 1      | 0.92%   |
| Drevo               | 1         | 1      | 0.92%   |
| China               | 1         | 1      | 0.92%   |
| Unknown             | 1         | 1      | 0.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 36     | 43.75%  |
| WDC                 | 16        | 17     | 20%     |
| Toshiba             | 12        | 12     | 15%     |
| HGST                | 10        | 11     | 12.5%   |
| Samsung Electronics | 3         | 3      | 3.75%   |
| Hitachi             | 3         | 3      | 3.75%   |
| Maxtor              | 1         | 1      | 1.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 76        | 83     | 72.38%  |
| SSD  | 25        | 25     | 23.81%  |
| NVMe | 4         | 4      | 3.81%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3225      | 6041   | 85.61%  |
| Works    | 436       | 689    | 11.57%  |
| Malfunc  | 103       | 112    | 2.73%   |
| Failed   | 2         | 2      | 0.05%   |
| Fixed    | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2472      | 56.92%  |
| AMD                              | 681       | 15.68%  |
| Samsung Electronics              | 322       | 7.41%   |
| SanDisk                          | 164       | 3.78%   |
| SK hynix                         | 70        | 1.61%   |
| Nvidia                           | 64        | 1.47%   |
| Kingston Technology Company      | 61        | 1.4%    |
| ASMedia Technology               | 57        | 1.31%   |
| Phison Electronics               | 54        | 1.24%   |
| Silicon Motion                   | 43        | 0.99%   |
| Micron Technology                | 43        | 0.99%   |
| Toshiba America Info Systems     | 42        | 0.97%   |
| KIOXIA                           | 38        | 0.87%   |
| JMicron Technology               | 34        | 0.78%   |
| Marvell Technology Group         | 32        | 0.74%   |
| Micron/Crucial Technology        | 31        | 0.71%   |
| ADATA Technology                 | 22        | 0.51%   |
| Realtek Semiconductor            | 15        | 0.35%   |
| MAXIO Technology (Hangzhou)      | 14        | 0.32%   |
| VIA Technologies                 | 10        | 0.23%   |
| Seagate Technology               | 9         | 0.21%   |
| Silicon Image                    | 8         | 0.18%   |
| Union Memory (Shenzhen)          | 6         | 0.14%   |
| Solid State Storage Technology   | 6         | 0.14%   |
| Lite-On Technology               | 6         | 0.14%   |
| Apple                            | 5         | 0.12%   |
| Shenzhen Longsys Electronics     | 4         | 0.09%   |
| LSI Logic / Symbios Logic        | 4         | 0.09%   |
| INNOGRIT                         | 4         | 0.09%   |
| Broadcom / LSI                   | 4         | 0.09%   |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| Yangtze Memory Technologies      | 2         | 0.05%   |
| OCZ Technology Group             | 2         | 0.05%   |
| Netac Technology                 | 2         | 0.05%   |
| Lenovo                           | 2         | 0.05%   |
| TenaFe                           | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Dell                             | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 462       | 9.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 183       | 3.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 181       | 3.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 173       | 3.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 135       | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 129       | 2.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 127       | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 101       | 2.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 93        | 1.86%   |
| AMD 400 Series Chipset SATA Controller                                         | 84        | 1.68%   |
| Intel Volume Management Device NVMe RAID Controller                            | 83        | 1.66%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 80        | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 80        | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 79        | 1.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 77        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 75        | 1.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 70        | 1.4%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 69        | 1.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 69        | 1.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 68        | 1.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 66        | 1.32%   |
| Intel SATA Controller [RAID mode]                                              | 64        | 1.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 64        | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 58        | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 52        | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 52        | 1.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 51        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 51        | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 48        | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 47        | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 43        | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 43        | 0.86%   |
| AMD 500 Series Chipset SATA Controller                                         | 42        | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 39        | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 39        | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                            | 38        | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 34        | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                          | 34        | 0.68%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 33        | 0.66%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 32        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2697      | 60.4%   |
| NVMe | 939       | 21.03%  |
| IDE  | 491       | 11%     |
| RAID | 327       | 7.32%   |
| SAS  | 8         | 0.18%   |
| SCSI | 3         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2845      | 78.12%  |
| AMD    | 797       | 21.88%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 52        | 1.43%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 40        | 1.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 38        | 1.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 32        | 0.88%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 30        | 0.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 27        | 0.74%   |
| AMD Ryzen 5 3600 6-Core Processor             | 27        | 0.74%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 26        | 0.71%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 26        | 0.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 25        | 0.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 24        | 0.66%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 23        | 0.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 23        | 0.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 21        | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 21        | 0.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 0.58%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 21        | 0.58%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 21        | 0.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 20        | 0.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 0.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 19        | 0.52%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 19        | 0.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.49%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 18        | 0.49%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 16        | 0.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 16        | 0.44%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 16        | 0.44%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 16        | 0.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.41%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 15        | 0.41%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 15        | 0.41%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 15        | 0.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 15        | 0.41%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 15        | 0.41%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 15        | 0.41%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 14        | 0.38%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 14        | 0.38%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 14        | 0.38%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.38%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 14        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 850       | 23.32%  |
| Intel Core i7           | 518       | 14.21%  |
| Intel Core i3           | 333       | 9.14%   |
| Intel Celeron           | 249       | 6.83%   |
| Other                   | 209       | 5.73%   |
| AMD Ryzen 5             | 191       | 5.24%   |
| Intel Core 2 Duo        | 180       | 4.94%   |
| Intel Atom              | 122       | 3.35%   |
| AMD Ryzen 7             | 118       | 3.24%   |
| Intel Pentium           | 106       | 2.91%   |
| Intel Xeon              | 77        | 2.11%   |
| AMD Ryzen 9             | 55        | 1.51%   |
| AMD FX                  | 53        | 1.45%   |
| Intel Pentium Dual-Core | 52        | 1.43%   |
| AMD A6                  | 45        | 1.23%   |
| AMD Ryzen 3             | 36        | 0.99%   |
| AMD A8                  | 34        | 0.93%   |
| Intel Core 2 Quad       | 33        | 0.91%   |
| Intel Pentium Dual      | 32        | 0.88%   |
| AMD A4                  | 32        | 0.88%   |
| AMD A10                 | 32        | 0.88%   |
| AMD Athlon II X2        | 23        | 0.63%   |
| Intel Core 2            | 20        | 0.55%   |
| AMD E1                  | 17        | 0.47%   |
| Intel Pentium Silver    | 16        | 0.44%   |
| Intel Core i9           | 15        | 0.41%   |
| AMD Phenom II X4        | 14        | 0.38%   |
| Intel Pentium Gold      | 11        | 0.3%    |
| Intel Core M            | 11        | 0.3%    |
| AMD Phenom II X6        | 11        | 0.3%    |
| AMD E                   | 11        | 0.3%    |
| AMD Athlon 64 X2        | 11        | 0.3%    |
| AMD Athlon              | 11        | 0.3%    |
| AMD Turion 64 X2 Mobile | 8         | 0.22%   |
| Intel Pentium 4         | 7         | 0.19%   |
| AMD E2                  | 7         | 0.19%   |
| AMD Athlon II X4        | 7         | 0.19%   |
| AMD Athlon II           | 6         | 0.16%   |
| Intel Core m5           | 5         | 0.14%   |
| AMD Ryzen 7 PRO         | 5         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1687      | 46.27%  |
| 4      | 1318      | 36.15%  |
| 6      | 280       | 7.68%   |
| 8      | 193       | 5.29%   |
| 1      | 48        | 1.32%   |
| 12     | 41        | 1.12%   |
| 10     | 23        | 0.63%   |
| 3      | 22        | 0.6%    |
| 16     | 21        | 0.58%   |
| 14     | 8         | 0.22%   |
| 28     | 2         | 0.05%   |
| 24     | 2         | 0.05%   |
| 40     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 3627      | 99.59%  |
| 2      | 15        | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2187      | 60.03%  |
| 1      | 1456      | 39.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3642      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 279       | 7.54%   |
| 0x306a9    | 271       | 7.32%   |
| Unknown    | 260       | 7.03%   |
| 0x306c3    | 211       | 5.7%    |
| 0x1067a    | 176       | 4.76%   |
| 0x40651    | 106       | 2.86%   |
| 0x806c1    | 101       | 2.73%   |
| 0x406e3    | 92        | 2.49%   |
| 0x806e9    | 90        | 2.43%   |
| 0x20655    | 90        | 2.43%   |
| 0x306d4    | 84        | 2.27%   |
| 0x406c4    | 81        | 2.19%   |
| 0x506e3    | 80        | 2.16%   |
| 0x30678    | 79        | 2.14%   |
| 0x906ea    | 70        | 1.89%   |
| 0x806ea    | 68        | 1.84%   |
| 0x806ec    | 65        | 1.76%   |
| 0x906e9    | 61        | 1.65%   |
| 0x706a8    | 56        | 1.51%   |
| 0x6fd      | 56        | 1.51%   |
| 0x08701021 | 50        | 1.35%   |
| 0x08108109 | 46        | 1.24%   |
| 0x506c9    | 43        | 1.16%   |
| 0x706e5    | 42        | 1.14%   |
| 0x10676    | 40        | 1.08%   |
| 0x20652    | 39        | 1.05%   |
| 0x06000852 | 36        | 0.97%   |
| 0x010000c8 | 34        | 0.92%   |
| 0x406c3    | 31        | 0.84%   |
| 0x0a50000c | 31        | 0.84%   |
| 0x6fb      | 30        | 0.81%   |
| 0x0800820d | 27        | 0.73%   |
| 0x07030105 | 26        | 0.7%    |
| 0x06001119 | 26        | 0.7%    |
| 0x06006705 | 24        | 0.65%   |
| 0xa0655    | 23        | 0.62%   |
| 0xa0653    | 23        | 0.62%   |
| 0x08600106 | 23        | 0.62%   |
| 0x0700010f | 21        | 0.57%   |
| 0xa0652    | 20        | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 430       | 11.8%   |
| Haswell          | 350       | 9.6%    |
| SandyBridge      | 302       | 8.29%   |
| IvyBridge        | 288       | 7.9%    |
| Penryn           | 222       | 6.09%   |
| Silvermont       | 207       | 5.68%   |
| Skylake          | 181       | 4.97%   |
| Westmere         | 140       | 3.84%   |
| Core             | 122       | 3.35%   |
| Zen 2            | 115       | 3.16%   |
| TigerLake        | 113       | 3.1%    |
| Zen 3            | 105       | 2.88%   |
| Zen+             | 98        | 2.69%   |
| Broadwell        | 90        | 2.47%   |
| Unknown          | 83        | 2.28%   |
| Goldmont plus    | 79        | 2.17%   |
| K10              | 78        | 2.14%   |
| CometLake        | 73        | 2%      |
| Piledriver       | 69        | 1.89%   |
| Icelake          | 68        | 1.87%   |
| Excavator        | 62        | 1.7%    |
| Zen              | 51        | 1.4%    |
| Goldmont         | 46        | 1.26%   |
| Puma             | 41        | 1.13%   |
| Nehalem          | 34        | 0.93%   |
| Alderlake Hybrid | 34        | 0.93%   |
| K8 Hammer        | 26        | 0.71%   |
| Jaguar           | 26        | 0.71%   |
| Bobcat           | 21        | 0.58%   |
| K10 Llano        | 18        | 0.49%   |
| Bonnell          | 15        | 0.41%   |
| Tremont          | 14        | 0.38%   |
| Steamroller      | 14        | 0.38%   |
| Bulldozer        | 14        | 0.38%   |
| NetBurst         | 10        | 0.27%   |
| K8 & K10 hybrid  | 5         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2220      | 53.15%  |
| Nvidia                           | 995       | 23.82%  |
| AMD                              | 947       | 22.67%  |
| Matrox Electronics Systems       | 5         | 0.12%   |
| VIA Technologies                 | 4         | 0.1%    |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| ASPEED Technology                | 2         | 0.05%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 230       | 5.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 170       | 3.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 114       | 2.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 107       | 2.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 91        | 2.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 91        | 2.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 90        | 2.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 87        | 2.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 80        | 1.87%   |
| Intel HD Graphics 620                                                                    | 74        | 1.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 68        | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 68        | 1.59%   |
| Intel UHD Graphics 620                                                                   | 67        | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 67        | 1.56%   |
| Intel HD Graphics 5500                                                                   | 54        | 1.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 51        | 1.19%   |
| Intel HD Graphics 630                                                                    | 50        | 1.17%   |
| Intel HD Graphics 530                                                                    | 46        | 1.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 46        | 1.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 45        | 1.05%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 45        | 1.05%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 41        | 0.96%   |
| Intel HD Graphics 500                                                                    | 39        | 0.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 39        | 0.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 38        | 0.89%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 37        | 0.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 36        | 0.84%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 33        | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 33        | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 33        | 0.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 33        | 0.77%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 31        | 0.72%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 31        | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 30        | 0.7%    |
| AMD Lucienne                                                                             | 29        | 0.68%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 26        | 0.61%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 25        | 0.58%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 23        | 0.54%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 22        | 0.51%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 21        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 1760      | 48.09%  |
| 1 x AMD              | 766       | 20.93%  |
| 1 x Nvidia           | 609       | 16.64%  |
| Intel + Nvidia       | 316       | 8.63%   |
| Intel + AMD          | 87        | 2.38%   |
| AMD + Nvidia         | 50        | 1.37%   |
| 2 x AMD              | 44        | 1.2%    |
| 2 x Nvidia           | 7         | 0.19%   |
| Other                | 5         | 0.14%   |
| 1 x VIA              | 4         | 0.11%   |
| 1 x SiS              | 3         | 0.08%   |
| 1 x Matrox           | 3         | 0.08%   |
| 1 x ASPEED           | 2         | 0.05%   |
| 2 x Intel            | 1         | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.03%   |
| Nvidia + Matrox      | 1         | 0.03%   |
| AMD + Matrox         | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2957      | 80.64%  |
| Proprietary | 587       | 16.01%  |
| Unknown     | 123       | 3.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2203      | 59.41%  |
| 0.01-0.5   | 446       | 12.03%  |
| 1.01-2.0   | 343       | 9.25%   |
| 0.51-1.0   | 297       | 8.01%   |
| 3.01-4.0   | 169       | 4.56%   |
| 7.01-8.0   | 122       | 3.29%   |
| 5.01-6.0   | 52        | 1.4%    |
| 8.01-16.0  | 41        | 1.11%   |
| 2.01-3.0   | 31        | 0.84%   |
| 16.01-24.0 | 4         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 468       | 12.66%  |
| AU Optronics            | 428       | 11.57%  |
| BOE                     | 327       | 8.84%   |
| Chimei Innolux          | 324       | 8.76%   |
| LG Display              | 313       | 8.46%   |
| Dell                    | 177       | 4.79%   |
| Goldstar                | 166       | 4.49%   |
| Hewlett-Packard         | 135       | 3.65%   |
| Apple                   | 117       | 3.16%   |
| Acer                    | 102       | 2.76%   |
| Philips                 | 85        | 2.3%    |
| AOC                     | 85        | 2.3%    |
| Lenovo                  | 66        | 1.78%   |
| Chi Mei Optoelectronics | 63        | 1.7%    |
| Ancor Communications    | 63        | 1.7%    |
| BenQ                    | 62        | 1.68%   |
| Sharp                   | 52        | 1.41%   |
| LG Electronics          | 31        | 0.84%   |
| Sony                    | 30        | 0.81%   |
| LG Philips              | 30        | 0.81%   |
| Unknown                 | 28        | 0.76%   |
| ViewSonic               | 27        | 0.73%   |
| InfoVision              | 27        | 0.73%   |
| PANDA                   | 26        | 0.7%    |
| Unknown                 | 23        | 0.62%   |
| Vizio                   | 22        | 0.59%   |
| ASUSTek Computer        | 21        | 0.57%   |
| Iiyama                  | 20        | 0.54%   |
| Fujitsu Siemens         | 16        | 0.43%   |
| Panasonic               | 13        | 0.35%   |
| Eizo                    | 13        | 0.35%   |
| Sceptre Tech            | 12        | 0.32%   |
| NEC Computers           | 12        | 0.32%   |
| CPT                     | 12        | 0.32%   |
| Toshiba                 | 11        | 0.3%    |
| MSI                     | 11        | 0.3%    |
| HPN                     | 10        | 0.27%   |
| HannStar                | 9         | 0.24%   |
| Microstep               | 6         | 0.16%   |
| LGD                     | 6         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 28        | 0.74%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 21        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 18        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 16        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 15        | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 15        | 0.4%    |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch              | 14        | 0.37%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 13        | 0.34%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 13        | 0.34%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 12        | 0.32%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 11        | 0.29%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.29%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch             | 10        | 0.26%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.26%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 10        | 0.26%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 9         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 9         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 9         | 0.24%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 9         | 0.24%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 8         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 8         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 8         | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 8         | 0.21%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                         | 8         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 7         | 0.18%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 7         | 0.18%   |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                         | 7         | 0.18%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 6         | 0.16%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 6         | 0.16%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 6         | 0.16%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 6         | 0.16%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 6         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1364      | 37.85%  |
| 1366x768 (WXGA)    | 892       | 24.75%  |
| 3840x2160 (4K)     | 191       | 5.3%    |
| 1600x900 (HD+)     | 188       | 5.22%   |
| 2560x1440 (QHD)    | 105       | 2.91%   |
| 1280x800 (WXGA)    | 104       | 2.89%   |
| 1680x1050 (WSXGA+) | 100       | 2.77%   |
| 1440x900 (WXGA+)   | 96        | 2.66%   |
| 1280x1024 (SXGA)   | 91        | 2.52%   |
| Unknown            | 66        | 1.83%   |
| 1920x1200 (WUXGA)  | 55        | 1.53%   |
| 1360x768           | 39        | 1.08%   |
| 3440x1440          | 37        | 1.03%   |
| 3840x1080          | 32        | 0.89%   |
| 2560x1600          | 28        | 0.78%   |
| 2560x1080          | 28        | 0.78%   |
| 2736x1824          | 17        | 0.47%   |
| 1920x540           | 16        | 0.44%   |
| 2880x1800          | 12        | 0.33%   |
| 2160x1440          | 12        | 0.33%   |
| 3200x1800 (QHD+)   | 10        | 0.28%   |
| 2256x1504          | 10        | 0.28%   |
| 1024x768 (XGA)     | 9         | 0.25%   |
| 1600x1200          | 8         | 0.22%   |
| 3840x2400          | 6         | 0.17%   |
| 1280x720 (HD)      | 6         | 0.17%   |
| 5760x1080          | 4         | 0.11%   |
| 3840x1600          | 4         | 0.11%   |
| 1920x1280          | 4         | 0.11%   |
| 1024x600           | 4         | 0.11%   |
| 4480x1440          | 3         | 0.08%   |
| 3600x1080          | 3         | 0.08%   |
| 2880x1920          | 3         | 0.08%   |
| 1920x515           | 3         | 0.08%   |
| 5760x2160          | 2         | 0.06%   |
| 5120x1440          | 2         | 0.06%   |
| 4480x1600          | 2         | 0.06%   |
| 4480x1080          | 2         | 0.06%   |
| 3360x1080          | 2         | 0.06%   |
| 3200x1200          | 2         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 929       | 25.35%  |
| 13      | 354       | 9.66%   |
| Unknown | 291       | 7.94%   |
| 14      | 277       | 7.56%   |
| 17      | 211       | 5.76%   |
| 27      | 204       | 5.57%   |
| 24      | 179       | 4.89%   |
| 21      | 168       | 4.59%   |
| 23      | 160       | 4.37%   |
| 19      | 100       | 2.73%   |
| 11      | 91        | 2.48%   |
| 31      | 88        | 2.4%    |
| 12      | 82        | 2.24%   |
| 20      | 77        | 2.1%    |
| 18      | 75        | 2.05%   |
| 22      | 66        | 1.8%    |
| 34      | 49        | 1.34%   |
| 40      | 26        | 0.71%   |
| 16      | 26        | 0.71%   |
| 54      | 23        | 0.63%   |
| 84      | 22        | 0.6%    |
| 72      | 17        | 0.46%   |
| 32      | 16        | 0.44%   |
| 26      | 14        | 0.38%   |
| 10      | 14        | 0.38%   |
| 25      | 12        | 0.33%   |
| 52      | 8         | 0.22%   |
| 49      | 8         | 0.22%   |
| 48      | 7         | 0.19%   |
| 36      | 7         | 0.19%   |
| 65      | 6         | 0.16%   |
| 28      | 5         | 0.14%   |
| 37      | 4         | 0.11%   |
| 29      | 4         | 0.11%   |
| 74      | 3         | 0.08%   |
| 64      | 3         | 0.08%   |
| 58      | 3         | 0.08%   |
| 46      | 3         | 0.08%   |
| 42      | 3         | 0.08%   |
| 39      | 3         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1416      | 39.17%  |
| 501-600        | 514       | 14.22%  |
| 401-500        | 432       | 11.95%  |
| 201-300        | 357       | 9.88%   |
| Unknown        | 291       | 8.05%   |
| 351-400        | 250       | 6.92%   |
| 601-700        | 120       | 3.32%   |
| 701-800        | 75        | 2.07%   |
| 1001-1500      | 70        | 1.94%   |
| 1501-2000      | 45        | 1.24%   |
| 801-900        | 36        | 1%      |
| 901-1000       | 6         | 0.17%   |
| 101-200        | 2         | 0.06%   |
| More than 2000 | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2501      | 73.65%  |
| 16/10   | 397       | 11.69%  |
| Unknown | 260       | 7.66%   |
| 5/4     | 82        | 2.41%   |
| 21/9    | 57        | 1.68%   |
| 3/2     | 52        | 1.53%   |
| 4/3     | 26        | 0.77%   |
| 32/9    | 10        | 0.29%   |
| 6/5     | 4         | 0.12%   |
| 3.73    | 3         | 0.09%   |
| 0.62    | 2         | 0.06%   |
| 1.00    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 923       | 25.35%  |
| 81-90          | 511       | 14.03%  |
| 201-250        | 461       | 12.66%  |
| Unknown        | 291       | 7.99%   |
| 151-200        | 238       | 6.54%   |
| 301-350        | 211       | 5.8%    |
| 351-500        | 164       | 4.5%    |
| 121-130        | 146       | 4.01%   |
| 71-80          | 131       | 3.6%    |
| More than 1000 | 106       | 2.91%   |
| 141-150        | 104       | 2.86%   |
| 51-60          | 93        | 2.55%   |
| 61-70          | 69        | 1.9%    |
| 251-300        | 67        | 1.84%   |
| 501-1000       | 56        | 1.54%   |
| 131-140        | 24        | 0.66%   |
| 111-120        | 23        | 0.63%   |
| 41-50          | 12        | 0.33%   |
| 91-100         | 9         | 0.25%   |
| 1-40           | 2         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1061      | 29.83%  |
| 51-100        | 1049      | 29.49%  |
| 121-160       | 804       | 22.6%   |
| Unknown       | 291       | 8.18%   |
| 161-240       | 187       | 5.26%   |
| 1-50          | 104       | 2.92%   |
| More than 240 | 61        | 1.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3101      | 83.74%  |
| 2     | 441       | 11.91%  |
| 0     | 125       | 3.38%   |
| 3     | 32        | 0.86%   |
| 4     | 3         | 0.08%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1948      | 35.19%  |
| Intel                             | 1578      | 28.51%  |
| Qualcomm Atheros                  | 667       | 12.05%  |
| Broadcom                          | 404       | 7.3%    |
| Broadcom Limited                  | 113       | 2.04%   |
| Ralink Technology                 | 84        | 1.52%   |
| TP-Link                           | 78        | 1.41%   |
| Marvell Technology Group          | 76        | 1.37%   |
| MediaTek                          | 65        | 1.17%   |
| Ralink                            | 64        | 1.16%   |
| Nvidia                            | 56        | 1.01%   |
| Samsung Electronics               | 36        | 0.65%   |
| ASIX Electronics                  | 30        | 0.54%   |
| Dell                              | 25        | 0.45%   |
| NetGear                           | 24        | 0.43%   |
| Xiaomi                            | 19        | 0.34%   |
| Qualcomm Atheros Communications   | 16        | 0.29%   |
| Huawei Technologies               | 16        | 0.29%   |
| Microsoft                         | 15        | 0.27%   |
| DisplayLink                       | 15        | 0.27%   |
| JMicron Technology                | 13        | 0.23%   |
| Sierra Wireless                   | 12        | 0.22%   |
| D-Link System                     | 12        | 0.22%   |
| Hewlett-Packard                   | 11        | 0.2%    |
| D-Link                            | 11        | 0.2%    |
| OPPO Electronics                  | 10        | 0.18%   |
| Edimax Technology                 | 10        | 0.18%   |
| ASUSTek Computer                  | 9         | 0.16%   |
| Qualcomm                          | 7         | 0.13%   |
| Motorola PCS                      | 7         | 0.13%   |
| Linksys                           | 6         | 0.11%   |
| Ericsson Business Mobile Networks | 6         | 0.11%   |
| Aquantia                          | 6         | 0.11%   |
| T & A Mobile Phones               | 5         | 0.09%   |
| Google                            | 5         | 0.09%   |
| Belkin Components                 | 5         | 0.09%   |
| VIA Technologies                  | 4         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.07%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.05%   |
| Lenovo                            | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1230      | 19.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 289       | 4.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 165       | 2.56%   |
| Intel Wi-Fi 6 AX200                                               | 115       | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 109       | 1.69%   |
| Intel Wireless 7265                                               | 105       | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 95        | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 89        | 1.38%   |
| Intel Wireless 8265 / 8275                                        | 87        | 1.35%   |
| Intel Wireless 7260                                               | 83        | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 78        | 1.21%   |
| Intel Wi-Fi 6 AX201                                               | 78        | 1.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 77        | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 76        | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 72        | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 0.96%   |
| Intel Wireless 3165                                               | 61        | 0.95%   |
| Intel I211 Gigabit Network Connection                             | 59        | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                     | 59        | 0.92%   |
| Intel Wireless 8260                                               | 58        | 0.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 56        | 0.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 53        | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 48        | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 44        | 0.68%   |
| Realtek 802.11ac NIC                                              | 44        | 0.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 44        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 43        | 0.67%   |
| Intel Ethernet Connection (2) I219-V                              | 42        | 0.65%   |
| Intel Ethernet Controller I225-V                                  | 41        | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 38        | 0.59%   |
| Ralink MT7601U Wireless Adapter                                   | 37        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 36        | 0.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 36        | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 36        | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 35        | 0.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 35        | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 34        | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 33        | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 32        | 0.5%    |
| Intel WiFi Link 5100                                              | 28        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1200      | 38.61%  |
| Realtek Semiconductor                 | 583       | 18.76%  |
| Qualcomm Atheros                      | 530       | 17.05%  |
| Broadcom                              | 280       | 9.01%   |
| Ralink Technology                     | 84        | 2.7%    |
| Broadcom Limited                      | 74        | 2.38%   |
| TP-Link                               | 67        | 2.16%   |
| Ralink                                | 64        | 2.06%   |
| MediaTek                              | 56        | 1.8%    |
| NetGear                               | 24        | 0.77%   |
| Marvell Technology Group              | 21        | 0.68%   |
| Qualcomm Atheros Communications       | 16        | 0.51%   |
| Dell                                  | 14        | 0.45%   |
| Sierra Wireless                       | 12        | 0.39%   |
| Microsoft                             | 12        | 0.39%   |
| D-Link                                | 11        | 0.35%   |
| Edimax Technology                     | 10        | 0.32%   |
| D-Link System                         | 10        | 0.32%   |
| ASUSTek Computer                      | 8         | 0.26%   |
| Linksys                               | 6         | 0.19%   |
| Belkin Components                     | 5         | 0.16%   |
| ZyDAS                                 | 2         | 0.06%   |
| TRENDnet                              | 2         | 0.06%   |
| Gemtek                                | 2         | 0.06%   |
| Fibocom                               | 2         | 0.06%   |
| AVM                                   | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Xiaomi                                | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Qualcomm                              | 1         | 0.03%   |
| Panasonic (Matsushita)                | 1         | 0.03%   |
| Ovislink                              | 1         | 0.03%   |
| Mercucys                              | 1         | 0.03%   |
| Hewlett-Packard                       | 1         | 0.03%   |
| Askey Computer                        | 1         | 0.03%   |
| ADMtek                                | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 115       | 3.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 109       | 3.47%   |
| Intel Wireless 7265                                            | 105       | 3.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 95        | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 89        | 2.84%   |
| Intel Wireless 8265 / 8275                                     | 87        | 2.77%   |
| Intel Wireless 7260                                            | 83        | 2.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 78        | 2.49%   |
| Intel Wi-Fi 6 AX201                                            | 78        | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 76        | 2.42%   |
| Intel Wireless 3165                                            | 61        | 1.94%   |
| Broadcom BCM43142 802.11b/g/n                                  | 59        | 1.88%   |
| Intel Wireless 8260                                            | 58        | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 56        | 1.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 53        | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 48        | 1.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 44        | 1.4%    |
| Realtek 802.11ac NIC                                           | 44        | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 44        | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 43        | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 38        | 1.21%   |
| Ralink MT7601U Wireless Adapter                                | 37        | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 36        | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 35        | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 35        | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 34        | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 33        | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 32        | 1.02%   |
| Intel WiFi Link 5100                                           | 28        | 0.89%   |
| Intel Wireless-AC 9260                                         | 26        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 25        | 0.8%    |
| Intel Centrino Ultimate-N 6300                                 | 25        | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 24        | 0.76%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 23        | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 22        | 0.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 22        | 0.7%    |
| Intel Wireless 3160                                            | 22        | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 22        | 0.7%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 21        | 0.67%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 21        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1690      | 52.88%  |
| Intel                             | 777       | 24.31%  |
| Qualcomm Atheros                  | 188       | 5.88%   |
| Broadcom                          | 178       | 5.57%   |
| Nvidia                            | 56        | 1.75%   |
| Marvell Technology Group          | 55        | 1.72%   |
| Broadcom Limited                  | 41        | 1.28%   |
| Samsung Electronics               | 35        | 1.1%    |
| ASIX Electronics                  | 30        | 0.94%   |
| Xiaomi                            | 18        | 0.56%   |
| DisplayLink                       | 15        | 0.47%   |
| JMicron Technology                | 13        | 0.41%   |
| Huawei Technologies               | 13        | 0.41%   |
| TP-Link                           | 11        | 0.34%   |
| OPPO Electronics                  | 10        | 0.31%   |
| MediaTek                          | 8         | 0.25%   |
| Qualcomm                          | 6         | 0.19%   |
| Aquantia                          | 6         | 0.19%   |
| Google                            | 5         | 0.16%   |
| VIA Technologies                  | 4         | 0.13%   |
| Motorola PCS                      | 4         | 0.13%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.09%   |
| Hewlett-Packard                   | 3         | 0.09%   |
| Sundance Technology Inc / IC Plus | 2         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.06%   |
| Microsoft                         | 2         | 0.06%   |
| Lenovo                            | 2         | 0.06%   |
| ICS Advent                        | 2         | 0.06%   |
| HMD Global                        | 2         | 0.06%   |
| D-Link System                     | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| T & A Mobile Phones               | 1         | 0.03%   |
| Sun Microsystems                  | 1         | 0.03%   |
| Research In Motion                | 1         | 0.03%   |
| Novatel Wireless                  | 1         | 0.03%   |
| Motorola BCS                      | 1         | 0.03%   |
| LG Electronics                    | 1         | 0.03%   |
| HTC (High Tech Computer)          | 1         | 0.03%   |
| GoPro                             | 1         | 0.03%   |
| Dell                              | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1230      | 37.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 289       | 8.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 165       | 5.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 77        | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 72        | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 1.91%   |
| Intel I211 Gigabit Network Connection                             | 59        | 1.82%   |
| Intel Ethernet Connection (2) I219-V                              | 42        | 1.3%    |
| Intel Ethernet Controller I225-V                                  | 41        | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 36        | 1.11%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 36        | 1.11%   |
| Intel Ethernet Connection I219-LM                                 | 25        | 0.77%   |
| Intel Ethernet Connection I217-V                                  | 25        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 25        | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 24        | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 24        | 0.74%   |
| Nvidia MCP79 Ethernet                                             | 23        | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 22        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 0.68%   |
| Intel 82577LM Gigabit Network Connection                          | 21        | 0.65%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 21        | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 20        | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 0.59%   |
| Nvidia MCP61 Ethernet                                             | 18        | 0.56%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 16        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 16        | 0.49%   |
| Intel 82579V Gigabit Network Connection                           | 16        | 0.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 16        | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.46%   |
| Intel Ethernet Connection I219-V                                  | 15        | 0.46%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 14        | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 13        | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                             | 13        | 0.4%    |
| Intel Ethernet Connection (2) I218-V                              | 13        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3029      | 50.54%  |
| WiFi     | 2904      | 48.46%  |
| Modem    | 49        | 0.82%   |
| Unknown  | 11        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2272      | 59.99%  |
| Ethernet | 1511      | 39.9%   |
| Modem    | 2         | 0.05%   |
| Unknown  | 2         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1961      | 53.64%  |
| 1     | 1500      | 41.03%  |
| 0     | 126       | 3.45%   |
| 3     | 63        | 1.72%   |
| 5     | 3         | 0.08%   |
| 4     | 2         | 0.05%   |
| 7     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2523      | 68.17%  |
| Yes  | 1178      | 31.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 920       | 41.84%  |
| Realtek Semiconductor           | 264       | 12.01%  |
| Qualcomm Atheros Communications | 196       | 8.91%   |
| Broadcom                        | 126       | 5.73%   |
| Apple                           | 125       | 5.68%   |
| Cambridge Silicon Radio         | 114       | 5.18%   |
| IMC Networks                    | 94        | 4.27%   |
| Foxconn / Hon Hai               | 60        | 2.73%   |
| Lite-On Technology              | 53        | 2.41%   |
| Dell                            | 38        | 1.73%   |
| ASUSTek Computer                | 32        | 1.46%   |
| Hewlett-Packard                 | 31        | 1.41%   |
| Toshiba                         | 25        | 1.14%   |
| Marvell Semiconductor           | 20        | 0.91%   |
| Ralink                          | 18        | 0.82%   |
| MediaTek                        | 16        | 0.73%   |
| Realtek                         | 12        | 0.55%   |
| TP-Link                         | 8         | 0.36%   |
| Integrated System Solution      | 6         | 0.27%   |
| Foxconn International           | 6         | 0.27%   |
| Alps Electric                   | 6         | 0.27%   |
| Dynex                           | 5         | 0.23%   |
| Belkin Components               | 4         | 0.18%   |
| Unknown                         | 4         | 0.18%   |
| Actions                         | 3         | 0.14%   |
| Ralink Technology               | 2         | 0.09%   |
| Askey Computer                  | 2         | 0.09%   |
| Sitecom Europe                  | 1         | 0.05%   |
| Qcom                            | 1         | 0.05%   |
| National Semiconductor          | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| D-Link System                   | 1         | 0.05%   |
| Conwise Technology              | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 395       | 17.94%  |
| Realtek Bluetooth Radio                             | 185       | 8.4%    |
| Intel AX201 Bluetooth                               | 141       | 6.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 114       | 5.18%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 113       | 5.13%   |
| Intel AX200 Bluetooth                               | 100       | 4.54%   |
| Qualcomm Atheros  Bluetooth Device                  | 85        | 3.86%   |
| Apple Bluetooth Host Controller                     | 56        | 2.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 55        | 2.5%    |
| Intel AX210 Bluetooth                               | 49        | 2.23%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 36        | 1.63%   |
| IMC Networks Bluetooth Device                       | 34        | 1.54%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 33        | 1.5%    |
| Intel Wireless-AC 3168 Bluetooth                    | 32        | 1.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 29        | 1.32%   |
| Intel Bluetooth Device                              | 28        | 1.27%   |
| IMC Networks Bluetooth Radio                        | 28        | 1.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 27        | 1.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 26        | 1.18%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 25        | 1.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 22        | 1%      |
| Apple Bluetooth USB Host Controller                 | 22        | 1%      |
| Qualcomm Atheros AR9462 Bluetooth                   | 19        | 0.86%   |
| Marvell Bluetooth and Wireless LAN Composite        | 19        | 0.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 19        | 0.86%   |
| Ralink RT3290 Bluetooth                             | 18        | 0.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 18        | 0.82%   |
| Foxconn / Hon Hai Bluetooth Device                  | 17        | 0.77%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.73%   |
| IMC Networks Wireless_Device                        | 16        | 0.73%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 16        | 0.73%   |
| MediaTek Wireless_Device                            | 15        | 0.68%   |
| Dell DW375 Bluetooth Module                         | 14        | 0.64%   |
| Apple Bluetooth HCI                                 | 14        | 0.64%   |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 0.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 0.59%   |
| Realtek Bluetooth Radio                             | 12        | 0.54%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 0.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 12        | 0.54%   |
| Lite-On Bluetooth Device                            | 10        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2682      | 55.09%  |
| AMD                                          | 1010      | 20.75%  |
| Nvidia                                       | 783       | 16.08%  |
| C-Media Electronics                          | 58        | 1.19%   |
| Creative Labs                                | 22        | 0.45%   |
| Logitech                                     | 21        | 0.43%   |
| Texas Instruments                            | 17        | 0.35%   |
| Kingston Technology                          | 17        | 0.35%   |
| JMTek                                        | 17        | 0.35%   |
| Generalplus Technology                       | 16        | 0.33%   |
| ASUSTek Computer                             | 15        | 0.31%   |
| Realtek Semiconductor                        | 12        | 0.25%   |
| Plantronics                                  | 11        | 0.23%   |
| Razer USA                                    | 10        | 0.21%   |
| VIA Technologies                             | 9         | 0.18%   |
| Creative Technology                          | 9         | 0.18%   |
| GN Netcom                                    | 8         | 0.16%   |
| Tenx Technology                              | 6         | 0.12%   |
| SteelSeries ApS                              | 6         | 0.12%   |
| Lenovo                                       | 6         | 0.12%   |
| Focusrite-Novation                           | 6         | 0.12%   |
| Micro Star International                     | 5         | 0.1%    |
| DCMT Technology                              | 5         | 0.1%    |
| Corsair                                      | 5         | 0.1%    |
| Zoran Co. Personal Media Division (Nogatech) | 4         | 0.08%   |
| PreSonus Audio Electronics                   | 4         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.06%   |
| RODE Microphones                             | 3         | 0.06%   |
| KTMicro                                      | 3         | 0.06%   |
| Jieli Technology                             | 3         | 0.06%   |
| DSEA A/S                                     | 3         | 0.06%   |
| BEHRINGER International                      | 3         | 0.06%   |
| Astro Gaming                                 | 3         | 0.06%   |
| Asahi Kasei Microsystems                     | 3         | 0.06%   |
| Yamaha                                       | 2         | 0.04%   |
| XMOS                                         | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.04%   |
| Sony                                         | 2         | 0.04%   |
| SAVITECH                                     | 2         | 0.04%   |
| Samsung Electronics                          | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 290       | 5.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 282       | 4.87%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 265       | 4.58%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 248       | 4.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 208       | 3.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 152       | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 144       | 2.49%   |
| AMD FCH Azalia Controller                                                                         | 140       | 2.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 135       | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 119       | 2.06%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 117       | 2.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 113       | 1.95%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 111       | 1.92%   |
| Intel 8 Series HD Audio Controller                                                                | 109       | 1.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 105       | 1.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 104       | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 89        | 1.54%   |
| Intel Broadwell-U Audio Controller                                                                | 86        | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 86        | 1.49%   |
| AMD Kabini HDMI/DP Audio                                                                          | 85        | 1.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 80        | 1.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 79        | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 78        | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 68        | 1.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 64        | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 61        | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 60        | 1.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 59        | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 57        | 0.98%   |
| Intel 200 Series PCH HD Audio                                                                     | 54        | 0.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 53        | 0.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 51        | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 46        | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 43        | 0.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 43        | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 42        | 0.73%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 42        | 0.73%   |
| Nvidia High Definition Audio Controller                                                           | 40        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 40        | 0.69%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 40        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 198       | 24.15%  |
| SK hynix               | 155       | 18.9%   |
| Micron Technology      | 84        | 10.24%  |
| Unknown                | 75        | 9.15%   |
| Kingston               | 63        | 7.68%   |
| Crucial                | 44        | 5.37%   |
| Unknown (ABCD)         | 24        | 2.93%   |
| Corsair                | 23        | 2.8%    |
| G.Skill                | 21        | 2.56%   |
| A-DATA Technology      | 17        | 2.07%   |
| Team                   | 13        | 1.59%   |
| Elpida                 | 13        | 1.59%   |
| Ramaxel Technology     | 12        | 1.46%   |
| Unknown                | 9         | 1.1%    |
| Nanya Technology       | 8         | 0.98%   |
| Smart                  | 7         | 0.85%   |
| Patriot                | 5         | 0.61%   |
| Timetec                | 3         | 0.37%   |
| Avant                  | 3         | 0.37%   |
| Wilk                   | 2         | 0.24%   |
| Unifosa                | 2         | 0.24%   |
| Transcend              | 2         | 0.24%   |
| Teikon                 | 2         | 0.24%   |
| Qimonda                | 2         | 0.24%   |
| ff                     | 2         | 0.24%   |
| fef5                   | 2         | 0.24%   |
| Apacer                 | 2         | 0.24%   |
| 4ea5                   | 2         | 0.24%   |
| Unknown (08B5)         | 1         | 0.12%   |
| Unknown (07F7)         | 1         | 0.12%   |
| Unknown (000080B30080) | 1         | 0.12%   |
| SUPER KINGSTEK         | 1         | 0.12%   |
| Strontium              | 1         | 0.12%   |
| Smart Brazil           | 1         | 0.12%   |
| Silicon Power          | 1         | 0.12%   |
| SHARETRONIC            | 1         | 0.12%   |
| PUSKILL                | 1         | 0.12%   |
| ProMos/Mosel Vitelic   | 1         | 0.12%   |
| pqi                    | 1         | 0.12%   |
| PNY                    | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 20        | 2.3%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 1.15%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 1.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 1.03%   |
| Unknown                                                          | 9         | 1.03%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.8%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.69%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.69%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 6         | 0.69%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 5         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 5         | 0.57%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.57%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.57%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.57%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 4         | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 4         | 0.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.46%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.46%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 4         | 0.46%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.46%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 4         | 0.46%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.46%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.46%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.34%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 3         | 0.34%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s               | 3         | 0.34%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 3         | 0.34%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s          | 3         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 297       | 42.01%  |
| DDR3    | 251       | 35.5%   |
| LPDDR4  | 53        | 7.5%    |
| LPDDR3  | 30        | 4.24%   |
| DDR2    | 28        | 3.96%   |
| SDRAM   | 18        | 2.55%   |
| Unknown | 16        | 2.26%   |
| DDR5    | 6         | 0.85%   |
| LPDDR5  | 4         | 0.57%   |
| DDR     | 4         | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 437       | 61.99%  |
| DIMM         | 179       | 25.39%  |
| Row Of Chips | 72        | 10.21%  |
| Chip         | 8         | 1.13%   |
| Unknown      | 8         | 1.13%   |
| FB-DIMM      | 1         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 294       | 37.4%   |
| 4096  | 242       | 30.79%  |
| 2048  | 116       | 14.76%  |
| 16384 | 85        | 10.81%  |
| 32768 | 24        | 3.05%   |
| 1024  | 23        | 2.93%   |
| 512   | 2         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 159       | 20.78%  |
| 3200    | 120       | 15.69%  |
| 2667    | 100       | 13.07%  |
| 2400    | 68        | 8.89%   |
| 1333    | 47        | 6.14%   |
| 2133    | 30        | 3.92%   |
| 1334    | 26        | 3.4%    |
| 1867    | 19        | 2.48%   |
| 4267    | 17        | 2.22%   |
| 3600    | 15        | 1.96%   |
| 667     | 14        | 1.83%   |
| Unknown | 14        | 1.83%   |
| 800     | 13        | 1.7%    |
| 1066    | 11        | 1.44%   |
| 3266    | 10        | 1.31%   |
| 3733    | 7         | 0.92%   |
| 3000    | 7         | 0.92%   |
| 2048    | 7         | 0.92%   |
| 1866    | 7         | 0.92%   |
| 4800    | 6         | 0.78%   |
| 1800    | 6         | 0.78%   |
| 6400    | 5         | 0.65%   |
| 1067    | 5         | 0.65%   |
| 8400    | 4         | 0.52%   |
| 2933    | 4         | 0.52%   |
| 975     | 4         | 0.52%   |
| 4266    | 3         | 0.39%   |
| 4199    | 3         | 0.39%   |
| 2666    | 3         | 0.39%   |
| 3866    | 2         | 0.26%   |
| 3800    | 2         | 0.26%   |
| 3666    | 2         | 0.26%   |
| 3500    | 2         | 0.26%   |
| 3466    | 2         | 0.26%   |
| 3400    | 2         | 0.26%   |
| 400     | 2         | 0.26%   |
| 5600    | 1         | 0.13%   |
| 5354    | 1         | 0.13%   |
| 5200    | 1         | 0.13%   |
| 4000    | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 26        | 29.21%  |
| Canon                 | 17        | 19.1%   |
| Brother Industries    | 15        | 16.85%  |
| Seiko Epson           | 14        | 15.73%  |
| Samsung Electronics   | 9         | 10.11%  |
| Lexmark International | 3         | 3.37%   |
| Zebra                 | 1         | 1.12%   |
| Ricoh                 | 1         | 1.12%   |
| QinHeng Electronics   | 1         | 1.12%   |
| Konica Minolta        | 1         | 1.12%   |
| GG IMAGE              | 1         | 1.12%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                     | 3         | 3.37%   |
| Samsung C460 Series                          | 2         | 2.25%   |
| HP OfficeJet 6950                            | 2         | 2.25%   |
| HP LaserJet Professional P1102w              | 2         | 2.25%   |
| HP ENVY Photo 6200 series                    | 2         | 2.25%   |
| HP DeskJet 2700 series                       | 2         | 2.25%   |
| HP DeskJet 2130 series                       | 2         | 2.25%   |
| Canon TS3100 series                          | 2         | 2.25%   |
| Canon LiDE 400                               | 2         | 2.25%   |
| Brother HL-2140 series                       | 2         | 2.25%   |
| Zebra ZP 450 Printer                         | 1         | 1.12%   |
| Seiko Epson XP-7100 Series                   | 1         | 1.12%   |
| Seiko Epson XP-235 Series                    | 1         | 1.12%   |
| Seiko Epson XP-200 Series                    | 1         | 1.12%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 1.12%   |
| Seiko Epson L805 Series                      | 1         | 1.12%   |
| Seiko Epson L355 Series                      | 1         | 1.12%   |
| Seiko Epson ET-3850 Series                   | 1         | 1.12%   |
| Seiko Epson ET-2820 Series                   | 1         | 1.12%   |
| Seiko Epson ET-2810 Series                   | 1         | 1.12%   |
| Seiko Epson ET-2710 Series                   | 1         | 1.12%   |
| Seiko Epson AcuLaser C1700                   | 1         | 1.12%   |
| Samsung SCX-483x 5x3x Series                 | 1         | 1.12%   |
| Samsung SCX-4623 Series                      | 1         | 1.12%   |
| Samsung SCX-4200 series                      | 1         | 1.12%   |
| Samsung SCX-3400 Series                      | 1         | 1.12%   |
| Samsung ML-2950 Series                       | 1         | 1.12%   |
| Samsung ML-216x Series Laser Printer         | 1         | 1.12%   |
| Samsung M2020 Series                         | 1         | 1.12%   |
| Ricoh SP 112SU                               | 1         | 1.12%   |
| QinHeng CH340S                               | 1         | 1.12%   |
| Lexmark International MX317dn                | 1         | 1.12%   |
| Lexmark International Laser Printer E232     | 1         | 1.12%   |
| Lexmark International 2400 series            | 1         | 1.12%   |
| Konica Minolta PagePro 1380MF                | 1         | 1.12%   |
| HP Smart Tank 510 series                     | 1         | 1.12%   |
| HP PSC 1100 series                           | 1         | 1.12%   |
| HP OfficeJet Pro 9010 series                 | 1         | 1.12%   |
| HP Officejet 6600                            | 1         | 1.12%   |
| HP OfficeJet 5600 (USBHUB)                   | 1         | 1.12%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 9         | 60%     |
| Seiko Epson     | 3         | 20%     |
| Hewlett-Packard | 3         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 12.5%   |
| Canon CanoScan LiDE 90                      | 2         | 12.5%   |
| Seiko Epson Scanner                         | 1         | 6.25%   |
| HP ScanJet 2400c                            | 1         | 6.25%   |
| HP Scanjet 200                              | 1         | 6.25%   |
| HP PSC 1200                                 | 1         | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 6.25%   |
| Canon CanoScan LiDE 60                      | 1         | 6.25%   |
| Canon CanoScan LIDE 25                      | 1         | 6.25%   |
| Canon CanoScan LiDE 220                     | 1         | 6.25%   |
| Canon CanoScan LiDE 110                     | 1         | 6.25%   |
| Canon CanoScan LiDE 100                     | 1         | 6.25%   |
| Canon CanoScan D660U                        | 1         | 6.25%   |
| Canon CanoScan 8800F                        | 1         | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 442       | 20.85%  |
| Microdia                               | 193       | 9.1%    |
| Realtek Semiconductor                  | 174       | 8.21%   |
| IMC Networks                           | 156       | 7.36%   |
| Sunplus Innovation Technology          | 118       | 5.57%   |
| Apple                                  | 110       | 5.19%   |
| Bison Electronics                      | 108       | 5.09%   |
| Cheng Uei Precision Industry (Foxlink) | 94        | 4.43%   |
| Quanta                                 | 84        | 3.96%   |
| Logitech                               | 84        | 3.96%   |
| Suyin                                  | 73        | 3.44%   |
| Syntek                                 | 56        | 2.64%   |
| Lite-On Technology                     | 36        | 1.7%    |
| Alcor Micro                            | 35        | 1.65%   |
| Silicon Motion                         | 33        | 1.56%   |
| Acer                                   | 31        | 1.46%   |
| Luxvisions Innotech Limited            | 23        | 1.08%   |
| Samsung Electronics                    | 21        | 0.99%   |
| Microsoft                              | 21        | 0.99%   |
| Ricoh                                  | 18        | 0.85%   |
| Sonix Technology                       | 14        | 0.66%   |
| icSpring                               | 14        | 0.66%   |
| Primax Electronics                     | 12        | 0.57%   |
| Z-Star Microelectronics                | 11        | 0.52%   |
| Generalplus Technology                 | 11        | 0.52%   |
| ARC International                      | 10        | 0.47%   |
| Lenovo                                 | 9         | 0.42%   |
| GEMBIRD                                | 9         | 0.42%   |
| ALi                                    | 8         | 0.38%   |
| SunplusIT                              | 7         | 0.33%   |
| Y Media                                | 5         | 0.24%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.24%   |
| Jieli Technology                       | 5         | 0.24%   |
| Importek                               | 5         | 0.24%   |
| Sunplus Technology                     | 4         | 0.19%   |
| Razer USA                              | 4         | 0.19%   |
| Intel                                  | 4         | 0.19%   |
| Genesys Logic                          | 4         | 0.19%   |
| Tobii Technology AB                    | 3         | 0.14%   |
| OmniVision Technologies                | 3         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 73        | 3.42%   |
| Microdia Integrated_Webcam_HD                       | 44        | 2.06%   |
| Apple FaceTime HD Camera (Built-in)                 | 41        | 1.92%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 39        | 1.83%   |
| Realtek Integrated_Webcam_HD                        | 37        | 1.73%   |
| Syntek Integrated Camera                            | 36        | 1.69%   |
| Chicony HD Webcam                                   | 36        | 1.69%   |
| IMC Networks Integrated Camera                      | 31        | 1.45%   |
| Bison Integrated Camera                             | 31        | 1.45%   |
| Apple Built-in iSight                               | 28        | 1.31%   |
| Chicony HP Truevision HD                            | 27        | 1.27%   |
| Microdia Integrated Webcam                          | 26        | 1.22%   |
| Chicony TOSHIBA Web Camera - HD                     | 23        | 1.08%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 22        | 1.03%   |
| Sunplus Integrated_Webcam_HD                        | 21        | 0.98%   |
| Samsung Galaxy series, misc. (MTP mode)             | 21        | 0.98%   |
| Bison Lenovo EasyCamera                             | 21        | 0.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 20        | 0.94%   |
| Sunplus HD WebCam                                   | 19        | 0.89%   |
| Logitech Webcam C270                                | 19        | 0.89%   |
| Realtek USB Camera                                  | 17        | 0.8%    |
| Microdia Webcam Vitade AF                           | 17        | 0.8%    |
| Alcor Micro USB 2.0 Camera                          | 17        | 0.8%    |
| Chicony EasyCamera                                  | 16        | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 16        | 0.75%   |
| Chicony USB2.0 VGA UVC WebCam                       | 15        | 0.7%    |
| Chicony HP TrueVision HD Camera                     | 15        | 0.7%    |
| Apple FaceTime HD Camera                            | 15        | 0.7%    |
| Realtek Integrated Webcam                           | 14        | 0.66%   |
| Realtek HP Truevision HD                            | 14        | 0.66%   |
| Lite-On HP HD Camera                                | 14        | 0.66%   |
| icSpring camera                                     | 14        | 0.66%   |
| Realtek Integrated Webcam HD                        | 13        | 0.61%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 13        | 0.61%   |
| Logitech HD Pro Webcam C920                         | 13        | 0.61%   |
| Chicony VGA Webcam                                  | 13        | 0.61%   |
| Chicony Lenovo EasyCamera                           | 13        | 0.61%   |
| Chicony HP Wide Vision HD Camera                    | 13        | 0.61%   |
| Chicony HP HD Camera                                | 13        | 0.61%   |
| Quanta HP Wide Vision HD Camera                     | 12        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 138       | 40.23%  |
| Synaptics                          | 55        | 16.03%  |
| Shenzhen Goodix Technology         | 47        | 13.7%   |
| AuthenTec                          | 31        | 9.04%   |
| Upek                               | 24        | 7%      |
| Elan Microelectronics              | 21        | 6.12%   |
| LighTuning Technology              | 12        | 3.5%    |
| STMicroelectronics                 | 7         | 2.04%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.87%   |
| Samsung Electronics                | 2         | 0.58%   |
| Next Biometrics                    | 1         | 0.29%   |
| HOLTEK                             | 1         | 0.29%   |
| Focal-systems.Corp                 | 1         | 0.29%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 27        | 7.87%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 7.58%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 6.41%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 4.96%   |
| Validity Sensors VFS491                                                    | 15        | 4.37%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 4.37%   |
| Elan ELAN:ARM-M4                                                           | 15        | 4.37%   |
| Validity Sensors Fingerprint scanner                                       | 11        | 3.21%   |
| AuthenTec AES2810                                                          | 11        | 3.21%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 2.92%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.92%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 10        | 2.92%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.62%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.62%   |
| Synaptics  WBDI                                                            | 9         | 2.62%   |
| Synaptics UWP WBDI                                                         | 8         | 2.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 2.33%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 2.04%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 2.04%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.04%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.75%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.75%   |
| Synaptics WBDI                                                             | 6         | 1.75%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 1.75%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.75%   |
| LighTuning Fingerprint Sensor                                              | 5         | 1.46%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.46%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.17%   |
| AuthenTec AES1600                                                          | 4         | 1.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.87%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.87%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.87%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.87%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.87%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.58%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.58%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.58%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.58%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.58%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.58%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 77        | 53.1%   |
| Alcor Micro                       | 24        | 16.55%  |
| O2 Micro                          | 14        | 9.66%   |
| Upek                              | 6         | 4.14%   |
| Lenovo                            | 6         | 4.14%   |
| VASCO Data Security International | 3         | 2.07%   |
| Realtek Semiconductor             | 3         | 2.07%   |
| Yubico.com                        | 2         | 1.38%   |
| SCM Microsystems                  | 2         | 1.38%   |
| Fujitsu Siemens Computers         | 2         | 1.38%   |
| Advanced Card Systems             | 2         | 1.38%   |
| Reiner SCT Kartensysteme          | 1         | 0.69%   |
| OmniKey                           | 1         | 0.69%   |
| Jing-Mold Enterprise              | 1         | 0.69%   |
| Chicony Electronics               | 1         | 0.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 29        | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 24        | 16.55%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 13.79%  |
| Broadcom 5880                                                                | 20        | 13.79%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 13        | 8.97%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 4.14%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 4.14%   |
| Broadcom 58200                                                               | 6         | 4.14%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 2.07%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.38%   |
| VASCO Data Security International DIGIPASS 870                               | 2         | 1.38%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 2         | 1.38%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.38%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.69%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.69%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.69%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.69%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.69%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.69%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 0.69%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.69%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.69%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2633      | 70.97%  |
| 1     | 872       | 23.5%   |
| 2     | 182       | 4.91%   |
| 3     | 20        | 0.54%   |
| 4     | 2         | 0.05%   |
| 8     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 337       | 26.62%  |
| Graphics card            | 263       | 20.77%  |
| Net/wireless             | 222       | 17.54%  |
| Multimedia controller    | 154       | 12.16%  |
| Chipcard                 | 134       | 10.58%  |
| Bluetooth                | 27        | 2.13%   |
| Communication controller | 26        | 2.05%   |
| Storage                  | 25        | 1.97%   |
| Sound                    | 13        | 1.03%   |
| Unassigned class         | 10        | 0.79%   |
| Camera                   | 10        | 0.79%   |
| Net/ethernet             | 8         | 0.63%   |
| Modem                    | 7         | 0.55%   |
| Network                  | 6         | 0.47%   |
| Storage/raid             | 5         | 0.39%   |
| Dvb card                 | 5         | 0.39%   |
| Card reader              | 5         | 0.39%   |
| Storage/ide              | 4         | 0.32%   |
| Storage/nvme             | 2         | 0.16%   |
| Flash memory             | 2         | 0.16%   |
| Unclassified device      | 1         | 0.08%   |

