Fedora - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Fedora.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora/Desktop/README.md) and [notebooks](/Dist/Fedora/Notebook/README.md).

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

Total: 13601

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 7577               | Notebook    | [2a280dc7df](https://linux-hardware.org/?probe=2a280dc7df) | Nov 02, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [2ece2f7351](https://linux-hardware.org/?probe=2ece2f7351) | Nov 02, 2022 |
| Lenovo        | ThinkPad T61 6464A13        | Notebook    | [5f850cbab6](https://linux-hardware.org/?probe=5f850cbab6) | Nov 02, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [41a93c4dfa](https://linux-hardware.org/?probe=41a93c4dfa) | Nov 02, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [c9041d22be](https://linux-hardware.org/?probe=c9041d22be) | Nov 02, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | Desktop     | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [2069a0e7fc](https://linux-hardware.org/?probe=2069a0e7fc) | Nov 02, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [4fa32ec6af](https://linux-hardware.org/?probe=4fa32ec6af) | Nov 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2d931f9e99](https://linux-hardware.org/?probe=2d931f9e99) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [86bf890d23](https://linux-hardware.org/?probe=86bf890d23) | Nov 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [335af8b89b](https://linux-hardware.org/?probe=335af8b89b) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [22b32d9bac](https://linux-hardware.org/?probe=22b32d9bac) | Nov 02, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [ec359017a2](https://linux-hardware.org/?probe=ec359017a2) | Nov 02, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d4ac3a5f04](https://linux-hardware.org/?probe=d4ac3a5f04) | Nov 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [63bf11c696](https://linux-hardware.org/?probe=63bf11c696) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [aa6c06f2bb](https://linux-hardware.org/?probe=aa6c06f2bb) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [584db1dcb2](https://linux-hardware.org/?probe=584db1dcb2) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a156a7484d](https://linux-hardware.org/?probe=a156a7484d) | Nov 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [36eda457da](https://linux-hardware.org/?probe=36eda457da) | Nov 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4e260473ba](https://linux-hardware.org/?probe=4e260473ba) | Nov 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [7b51138a0b](https://linux-hardware.org/?probe=7b51138a0b) | Nov 02, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d3beec5427](https://linux-hardware.org/?probe=d3beec5427) | Nov 02, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9b093574b9](https://linux-hardware.org/?probe=9b093574b9) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [24c2a01761](https://linux-hardware.org/?probe=24c2a01761) | Nov 02, 2022 |
| Dell          | Latitude 5591               | Notebook    | [bcd8aef9a0](https://linux-hardware.org/?probe=bcd8aef9a0) | Nov 02, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [dfe5dc3d95](https://linux-hardware.org/?probe=dfe5dc3d95) | Nov 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [c90b358eb5](https://linux-hardware.org/?probe=c90b358eb5) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [379443a5d6](https://linux-hardware.org/?probe=379443a5d6) | Nov 01, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [5e099af04c](https://linux-hardware.org/?probe=5e099af04c) | Nov 01, 2022 |
| HP            | 829E                        | Mini pc     | [f568895fbb](https://linux-hardware.org/?probe=f568895fbb) | Nov 01, 2022 |
| Intel         | NUC6i7KYB H90766-410        | Mini pc     | [9c17f472ee](https://linux-hardware.org/?probe=9c17f472ee) | Nov 01, 2022 |
| Gigabyte      | B550 UD AC                  | Desktop     | [c5a5219cf3](https://linux-hardware.org/?probe=c5a5219cf3) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [766e7fb0d0](https://linux-hardware.org/?probe=766e7fb0d0) | Nov 01, 2022 |
| GPD           | G1619-04                    | Notebook    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| ASUSTek       | B150 PRO GAMING             | Desktop     | [b2229c56c4](https://linux-hardware.org/?probe=b2229c56c4) | Nov 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [9608724116](https://linux-hardware.org/?probe=9608724116) | Nov 01, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ee4c33d7b1](https://linux-hardware.org/?probe=ee4c33d7b1) | Nov 01, 2022 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [8890410dfc](https://linux-hardware.org/?probe=8890410dfc) | Nov 01, 2022 |
| HP            | 339A                        | Desktop     | [68392c18c9](https://linux-hardware.org/?probe=68392c18c9) | Nov 01, 2022 |
| Dell          | Latitude 3420               | Notebook    | [9c2b9ab298](https://linux-hardware.org/?probe=9c2b9ab298) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [d63c5de91b](https://linux-hardware.org/?probe=d63c5de91b) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [1d24aac4ce](https://linux-hardware.org/?probe=1d24aac4ce) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2eb32b1bb3](https://linux-hardware.org/?probe=2eb32b1bb3) | Nov 01, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2f3428a435](https://linux-hardware.org/?probe=2f3428a435) | Nov 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [cf7b016772](https://linux-hardware.org/?probe=cf7b016772) | Nov 01, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [f6b6afc8a3](https://linux-hardware.org/?probe=f6b6afc8a3) | Nov 01, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [7254a9a2fc](https://linux-hardware.org/?probe=7254a9a2fc) | Nov 01, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [566d83485b](https://linux-hardware.org/?probe=566d83485b) | Oct 31, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [274a3383db](https://linux-hardware.org/?probe=274a3383db) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [c91800e8c1](https://linux-hardware.org/?probe=c91800e8c1) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [46f1da66b6](https://linux-hardware.org/?probe=46f1da66b6) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [1409a7f78d](https://linux-hardware.org/?probe=1409a7f78d) | Oct 31, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [71cf98e6e8](https://linux-hardware.org/?probe=71cf98e6e8) | Oct 31, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [a2a8473e4b](https://linux-hardware.org/?probe=a2a8473e4b) | Oct 31, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fffb5288e0](https://linux-hardware.org/?probe=fffb5288e0) | Oct 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ce4bda1df2](https://linux-hardware.org/?probe=ce4bda1df2) | Oct 31, 2022 |
| ASUSTek       | X541UVK                     | Notebook    | [15bdbbf952](https://linux-hardware.org/?probe=15bdbbf952) | Oct 31, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [e993af2670](https://linux-hardware.org/?probe=e993af2670) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [479fdd085d](https://linux-hardware.org/?probe=479fdd085d) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [dfde89926c](https://linux-hardware.org/?probe=dfde89926c) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [135f93d663](https://linux-hardware.org/?probe=135f93d663) | Oct 31, 2022 |
| Dell          | Precision M6700             | Notebook    | [aa4b5e4400](https://linux-hardware.org/?probe=aa4b5e4400) | Oct 31, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2f41c9eaa5](https://linux-hardware.org/?probe=2f41c9eaa5) | Oct 31, 2022 |
| HP            | ENVY 17                     | Notebook    | [5b845d9ee3](https://linux-hardware.org/?probe=5b845d9ee3) | Oct 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5bd92395da](https://linux-hardware.org/?probe=5bd92395da) | Oct 31, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [073ba962ff](https://linux-hardware.org/?probe=073ba962ff) | Oct 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4ac9bf1711](https://linux-hardware.org/?probe=4ac9bf1711) | Oct 31, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [221710c9ea](https://linux-hardware.org/?probe=221710c9ea) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [002ab67e5e](https://linux-hardware.org/?probe=002ab67e5e) | Oct 31, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [76906648cb](https://linux-hardware.org/?probe=76906648cb) | Oct 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1deed25a21](https://linux-hardware.org/?probe=1deed25a21) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [cf460716f9](https://linux-hardware.org/?probe=cf460716f9) | Oct 30, 2022 |
| Dell          | Inspiron 14 7425 2-in-1     | Convertible | [e427e48710](https://linux-hardware.org/?probe=e427e48710) | Oct 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3f69e984d1](https://linux-hardware.org/?probe=3f69e984d1) | Oct 30, 2022 |
| Sony          | VAIO                        | All in one  | [b295b1cb6f](https://linux-hardware.org/?probe=b295b1cb6f) | Oct 30, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [98979beea7](https://linux-hardware.org/?probe=98979beea7) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4820bca604](https://linux-hardware.org/?probe=4820bca604) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cdca8a4d95](https://linux-hardware.org/?probe=cdca8a4d95) | Oct 30, 2022 |
| HP            | 15                          | Notebook    | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [1e1f105579](https://linux-hardware.org/?probe=1e1f105579) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [19cddcf899](https://linux-hardware.org/?probe=19cddcf899) | Oct 30, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c52b1fe5fa](https://linux-hardware.org/?probe=c52b1fe5fa) | Oct 30, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [f1478df888](https://linux-hardware.org/?probe=f1478df888) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [197c77e88c](https://linux-hardware.org/?probe=197c77e88c) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [12e08a7d27](https://linux-hardware.org/?probe=12e08a7d27) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [8e2ab3d61b](https://linux-hardware.org/?probe=8e2ab3d61b) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [df654ca0b1](https://linux-hardware.org/?probe=df654ca0b1) | Oct 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c8392f24d9](https://linux-hardware.org/?probe=c8392f24d9) | Oct 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [7ddd09eeec](https://linux-hardware.org/?probe=7ddd09eeec) | Oct 30, 2022 |
| Dell          | Latitude 7490               | Notebook    | [95d0006efb](https://linux-hardware.org/?probe=95d0006efb) | Oct 30, 2022 |
| Dell          | Latitude E7450              | Notebook    | [32a6333f4b](https://linux-hardware.org/?probe=32a6333f4b) | Oct 30, 2022 |
| Aquarius      | Cmp NS765                   | Notebook    | [5e519edbee](https://linux-hardware.org/?probe=5e519edbee) | Oct 30, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [60ba0bc2dd](https://linux-hardware.org/?probe=60ba0bc2dd) | Oct 29, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [ba5da6b270](https://linux-hardware.org/?probe=ba5da6b270) | Oct 29, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1925c8ce1f](https://linux-hardware.org/?probe=1925c8ce1f) | Oct 29, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [b3dd383a83](https://linux-hardware.org/?probe=b3dd383a83) | Oct 29, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [cc62dbe2f6](https://linux-hardware.org/?probe=cc62dbe2f6) | Oct 29, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [301aab9126](https://linux-hardware.org/?probe=301aab9126) | Oct 29, 2022 |
| ASUSTek       | Q550LF                      | Notebook    | [383c45edce](https://linux-hardware.org/?probe=383c45edce) | Oct 29, 2022 |
| Dell          | Latitude E7450              | Notebook    | [012cd7214b](https://linux-hardware.org/?probe=012cd7214b) | Oct 29, 2022 |
| Dell          | Latitude E7450              | Notebook    | [635a60671d](https://linux-hardware.org/?probe=635a60671d) | Oct 29, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [782207dfcf](https://linux-hardware.org/?probe=782207dfcf) | Oct 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [75b050a9f0](https://linux-hardware.org/?probe=75b050a9f0) | Oct 29, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [ce9a718851](https://linux-hardware.org/?probe=ce9a718851) | Oct 28, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [c60b429baa](https://linux-hardware.org/?probe=c60b429baa) | Oct 28, 2022 |
| HP            | 82A5                        | Mini pc     | [c0be7985c0](https://linux-hardware.org/?probe=c0be7985c0) | Oct 28, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [2e4153161f](https://linux-hardware.org/?probe=2e4153161f) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [2f6e4235f7](https://linux-hardware.org/?probe=2f6e4235f7) | Oct 28, 2022 |
| Lenovo        | ThinkPad P52 20M9S1EM00     | Notebook    | [40de74c5c5](https://linux-hardware.org/?probe=40de74c5c5) | Oct 28, 2022 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [e06398e1bc](https://linux-hardware.org/?probe=e06398e1bc) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [83179a6cea](https://linux-hardware.org/?probe=83179a6cea) | Oct 28, 2022 |
| Lenovo        | 3172 NOK                    | Mini pc     | [1ddbbf71eb](https://linux-hardware.org/?probe=1ddbbf71eb) | Oct 28, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [72102d6890](https://linux-hardware.org/?probe=72102d6890) | Oct 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [38135da604](https://linux-hardware.org/?probe=38135da604) | Oct 28, 2022 |
| Sony          | VPCCB3S1R                   | Notebook    | [ee5b1465a1](https://linux-hardware.org/?probe=ee5b1465a1) | Oct 28, 2022 |
| Microsoft     | Surface Go 3                | Tablet      | [85019658e9](https://linux-hardware.org/?probe=85019658e9) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1d64fb48e7](https://linux-hardware.org/?probe=1d64fb48e7) | Oct 27, 2022 |
| Timi          | TM1701                      | Notebook    | [f246345845](https://linux-hardware.org/?probe=f246345845) | Oct 27, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [0c6a68368c](https://linux-hardware.org/?probe=0c6a68368c) | Oct 27, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [3a9f97607d](https://linux-hardware.org/?probe=3a9f97607d) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [36b663cec7](https://linux-hardware.org/?probe=36b663cec7) | Oct 27, 2022 |
| MSI           | H81M-E33                    | Desktop     | [f0613bfce8](https://linux-hardware.org/?probe=f0613bfce8) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [e00fd51503](https://linux-hardware.org/?probe=e00fd51503) | Oct 27, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [44e8a164d1](https://linux-hardware.org/?probe=44e8a164d1) | Oct 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [99152f7783](https://linux-hardware.org/?probe=99152f7783) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [670823778e](https://linux-hardware.org/?probe=670823778e) | Oct 27, 2022 |
| Lenovo        | Yoga 720-13IKB              | Convertible | [1ca9551d4d](https://linux-hardware.org/?probe=1ca9551d4d) | Oct 27, 2022 |
| MSI           | Prestige 14 A10SC           | Notebook    | [263d47772c](https://linux-hardware.org/?probe=263d47772c) | Oct 27, 2022 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [aa2345213b](https://linux-hardware.org/?probe=aa2345213b) | Oct 27, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bd9367f2b7](https://linux-hardware.org/?probe=bd9367f2b7) | Oct 27, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [7d30f96368](https://linux-hardware.org/?probe=7d30f96368) | Oct 27, 2022 |
| Lenovo        | ThinkPad X260 20F5S2WX05    | Notebook    | [710f95eab8](https://linux-hardware.org/?probe=710f95eab8) | Oct 27, 2022 |
| MSI           | X299 SLI PLUS               | Desktop     | [4b79f3c1e6](https://linux-hardware.org/?probe=4b79f3c1e6) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [d2debd1dab](https://linux-hardware.org/?probe=d2debd1dab) | Oct 26, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [85b4bc70fa](https://linux-hardware.org/?probe=85b4bc70fa) | Oct 26, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6c7c7fa216](https://linux-hardware.org/?probe=6c7c7fa216) | Oct 26, 2022 |
| LincPlus      | P1                          | Notebook    | [cc97e9ec36](https://linux-hardware.org/?probe=cc97e9ec36) | Oct 26, 2022 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | Desktop     | [2bed8fe9b1](https://linux-hardware.org/?probe=2bed8fe9b1) | Oct 26, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [0a658be9fc](https://linux-hardware.org/?probe=0a658be9fc) | Oct 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [317d318d85](https://linux-hardware.org/?probe=317d318d85) | Oct 26, 2022 |
| HP            | ProLiant ML350 G6           | Desktop     | [d080f0956b](https://linux-hardware.org/?probe=d080f0956b) | Oct 26, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [958c0a2ae7](https://linux-hardware.org/?probe=958c0a2ae7) | Oct 25, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b35333d9c0](https://linux-hardware.org/?probe=b35333d9c0) | Oct 25, 2022 |
| Dell          | Latitude E7270              | Notebook    | [7f2c8b9e9c](https://linux-hardware.org/?probe=7f2c8b9e9c) | Oct 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [a8c29545e6](https://linux-hardware.org/?probe=a8c29545e6) | Oct 25, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [6764a6860f](https://linux-hardware.org/?probe=6764a6860f) | Oct 25, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [c9123810fd](https://linux-hardware.org/?probe=c9123810fd) | Oct 25, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [6896f337ab](https://linux-hardware.org/?probe=6896f337ab) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [0eb9c3ebff](https://linux-hardware.org/?probe=0eb9c3ebff) | Oct 25, 2022 |
| Dell          | Latitude 5500               | Notebook    | [6e1b321740](https://linux-hardware.org/?probe=6e1b321740) | Oct 25, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [29dd6b053b](https://linux-hardware.org/?probe=29dd6b053b) | Oct 25, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [a78a644cc1](https://linux-hardware.org/?probe=a78a644cc1) | Oct 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [0c63b974e1](https://linux-hardware.org/?probe=0c63b974e1) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [fbd1924bea](https://linux-hardware.org/?probe=fbd1924bea) | Oct 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [055062356e](https://linux-hardware.org/?probe=055062356e) | Oct 25, 2022 |
| ASRock        | FM2A88M-HD+ R2.0            | Desktop     | [10e0a497e9](https://linux-hardware.org/?probe=10e0a497e9) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [82fb357322](https://linux-hardware.org/?probe=82fb357322) | Oct 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [db4db1b508](https://linux-hardware.org/?probe=db4db1b508) | Oct 25, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [88e45a4e65](https://linux-hardware.org/?probe=88e45a4e65) | Oct 25, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [4474edfd79](https://linux-hardware.org/?probe=4474edfd79) | Oct 25, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [1537796302](https://linux-hardware.org/?probe=1537796302) | Oct 25, 2022 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [1d5e3aa9f0](https://linux-hardware.org/?probe=1d5e3aa9f0) | Oct 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b14c37f999](https://linux-hardware.org/?probe=b14c37f999) | Oct 25, 2022 |
| Dell          | Latitude E7450              | Notebook    | [45e65cd626](https://linux-hardware.org/?probe=45e65cd626) | Oct 25, 2022 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [91a8a52c4a](https://linux-hardware.org/?probe=91a8a52c4a) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [a515dd93cd](https://linux-hardware.org/?probe=a515dd93cd) | Oct 25, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Core ... | Desktop     | [601e080563](https://linux-hardware.org/?probe=601e080563) | Oct 25, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [42647c28ba](https://linux-hardware.org/?probe=42647c28ba) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [e4d7dc5f38](https://linux-hardware.org/?probe=e4d7dc5f38) | Oct 25, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [6560f717c9](https://linux-hardware.org/?probe=6560f717c9) | Oct 24, 2022 |
| System76      | Galago UltraPro             | Notebook    | [caf6a992bb](https://linux-hardware.org/?probe=caf6a992bb) | Oct 24, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [261e670072](https://linux-hardware.org/?probe=261e670072) | Oct 24, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [ad6b09bddc](https://linux-hardware.org/?probe=ad6b09bddc) | Oct 24, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [44375f0b06](https://linux-hardware.org/?probe=44375f0b06) | Oct 24, 2022 |
| ASRock        | Z170 Gaming K4              | Desktop     | [184139e7bc](https://linux-hardware.org/?probe=184139e7bc) | Oct 24, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [3f6368ca5a](https://linux-hardware.org/?probe=3f6368ca5a) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [95ad909dc8](https://linux-hardware.org/?probe=95ad909dc8) | Oct 24, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [dc8eab937b](https://linux-hardware.org/?probe=dc8eab937b) | Oct 24, 2022 |
| HP            | 3048h                       | Desktop     | [3c3f7eda5e](https://linux-hardware.org/?probe=3c3f7eda5e) | Oct 24, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [aea737fcab](https://linux-hardware.org/?probe=aea737fcab) | Oct 24, 2022 |
| ASRock        | X370 Gaming K4              | Desktop     | [5658dbff1b](https://linux-hardware.org/?probe=5658dbff1b) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [0ca2dff493](https://linux-hardware.org/?probe=0ca2dff493) | Oct 24, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [2a57a65990](https://linux-hardware.org/?probe=2a57a65990) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5010a8ef47](https://linux-hardware.org/?probe=5010a8ef47) | Oct 24, 2022 |
| Dell          | Latitude E6420              | Notebook    | [eb53f0d580](https://linux-hardware.org/?probe=eb53f0d580) | Oct 24, 2022 |
| ASUSTek       | UX310UQ                     | Notebook    | [5a928ace3b](https://linux-hardware.org/?probe=5a928ace3b) | Oct 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [fe9ec739e2](https://linux-hardware.org/?probe=fe9ec739e2) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | Notebook    | [c1a4fde481](https://linux-hardware.org/?probe=c1a4fde481) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | Notebook    | [80bf151a4d](https://linux-hardware.org/?probe=80bf151a4d) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [8922b0767c](https://linux-hardware.org/?probe=8922b0767c) | Oct 24, 2022 |
| HP            | 2B05                        | Desktop     | [c059b9a786](https://linux-hardware.org/?probe=c059b9a786) | Oct 24, 2022 |
| Lenovo        | ThinkPad X240 20AMS56K00    | Notebook    | [efa84f3716](https://linux-hardware.org/?probe=efa84f3716) | Oct 24, 2022 |
| ASRock        | P45TS                       | Desktop     | [484f63b830](https://linux-hardware.org/?probe=484f63b830) | Oct 24, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [cb2480b22c](https://linux-hardware.org/?probe=cb2480b22c) | Oct 23, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [846cfe5273](https://linux-hardware.org/?probe=846cfe5273) | Oct 23, 2022 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [dac168fe77](https://linux-hardware.org/?probe=dac168fe77) | Oct 23, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [b9e4b934ee](https://linux-hardware.org/?probe=b9e4b934ee) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [22ea226b97](https://linux-hardware.org/?probe=22ea226b97) | Oct 23, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [406538a0de](https://linux-hardware.org/?probe=406538a0de) | Oct 23, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [41dce71fbf](https://linux-hardware.org/?probe=41dce71fbf) | Oct 23, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [b6b5c1468c](https://linux-hardware.org/?probe=b6b5c1468c) | Oct 23, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [22a96186fa](https://linux-hardware.org/?probe=22a96186fa) | Oct 23, 2022 |
| Dell          | Inspiron 1564               | Notebook    | [754b4a0f04](https://linux-hardware.org/?probe=754b4a0f04) | Oct 23, 2022 |
| HP            | Notebook                    | Notebook    | [d713217453](https://linux-hardware.org/?probe=d713217453) | Oct 23, 2022 |
| HP            | 86EE                        | All in one  | [4c631cdc18](https://linux-hardware.org/?probe=4c631cdc18) | Oct 22, 2022 |
| HP            | Notebook                    | Notebook    | [ef9adb0e8a](https://linux-hardware.org/?probe=ef9adb0e8a) | Oct 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b42893c91e](https://linux-hardware.org/?probe=b42893c91e) | Oct 22, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [b633b478aa](https://linux-hardware.org/?probe=b633b478aa) | Oct 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b7ad660d88](https://linux-hardware.org/?probe=b7ad660d88) | Oct 22, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [14830504a7](https://linux-hardware.org/?probe=14830504a7) | Oct 22, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [7f855c9b05](https://linux-hardware.org/?probe=7f855c9b05) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [312828c6a3](https://linux-hardware.org/?probe=312828c6a3) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KY00     | Notebook    | [657b1ee865](https://linux-hardware.org/?probe=657b1ee865) | Oct 22, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3e2bd05f56](https://linux-hardware.org/?probe=3e2bd05f56) | Oct 22, 2022 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [9cfe9f3c51](https://linux-hardware.org/?probe=9cfe9f3c51) | Oct 22, 2022 |
| Dell          | 0PP150 A00                  | Desktop     | [0e07990bda](https://linux-hardware.org/?probe=0e07990bda) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [77b57dbe12](https://linux-hardware.org/?probe=77b57dbe12) | Oct 21, 2022 |
| Lenovo        | ThinkPad X260 20F5S5Q200    | Notebook    | [c2e041fd54](https://linux-hardware.org/?probe=c2e041fd54) | Oct 21, 2022 |
| HP            | ProBook 4530s               | Notebook    | [3cca675c88](https://linux-hardware.org/?probe=3cca675c88) | Oct 21, 2022 |
| HP            | ProBook 4530s               | Notebook    | [e87546da82](https://linux-hardware.org/?probe=e87546da82) | Oct 21, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [41bade1339](https://linux-hardware.org/?probe=41bade1339) | Oct 21, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [27c047341d](https://linux-hardware.org/?probe=27c047341d) | Oct 21, 2022 |
| Purism        | Librem 13 v2                | Notebook    | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| Unknown       | X79                         | Desktop     | [fd8f23bc70](https://linux-hardware.org/?probe=fd8f23bc70) | Oct 21, 2022 |
| LG Electro... | 16Z90P-G.AP75D              | Notebook    | [1e1526e9d8](https://linux-hardware.org/?probe=1e1526e9d8) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [1ab730c85c](https://linux-hardware.org/?probe=1ab730c85c) | Oct 21, 2022 |
| Google        | Swanky                      | Notebook    | [19efb3ecc5](https://linux-hardware.org/?probe=19efb3ecc5) | Oct 21, 2022 |
| HP            | 8459                        | Desktop     | [c2ebcf9e20](https://linux-hardware.org/?probe=c2ebcf9e20) | Oct 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60d4787bb7](https://linux-hardware.org/?probe=60d4787bb7) | Oct 21, 2022 |
| ASUSTek       | Q550LF                      | Notebook    | [0d24151944](https://linux-hardware.org/?probe=0d24151944) | Oct 21, 2022 |
| Itautec       | Infoway N8755               | Notebook    | [7eaba382a5](https://linux-hardware.org/?probe=7eaba382a5) | Oct 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [b374c2dff6](https://linux-hardware.org/?probe=b374c2dff6) | Oct 20, 2022 |
| Acer          | One S1003                   | Tablet      | [304c23119d](https://linux-hardware.org/?probe=304c23119d) | Oct 20, 2022 |
| Lenovo        | B560                        | Notebook    | [3a61700f49](https://linux-hardware.org/?probe=3a61700f49) | Oct 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [33a4634aab](https://linux-hardware.org/?probe=33a4634aab) | Oct 20, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [879fabd350](https://linux-hardware.org/?probe=879fabd350) | Oct 20, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [f03f1bb041](https://linux-hardware.org/?probe=f03f1bb041) | Oct 20, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [f966d5d584](https://linux-hardware.org/?probe=f966d5d584) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| HP            | 8433 11                     | Desktop     | [7e28f54181](https://linux-hardware.org/?probe=7e28f54181) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [06328b7f7c](https://linux-hardware.org/?probe=06328b7f7c) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7d35a56915](https://linux-hardware.org/?probe=7d35a56915) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [f81a40a71c](https://linux-hardware.org/?probe=f81a40a71c) | Oct 20, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f91d8722f9](https://linux-hardware.org/?probe=f91d8722f9) | Oct 20, 2022 |
| Dell          | Precision 5510              | Notebook    | [bb7788ce01](https://linux-hardware.org/?probe=bb7788ce01) | Oct 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9594fcc1e0](https://linux-hardware.org/?probe=9594fcc1e0) | Oct 20, 2022 |
| ASUSTek       | K43SJ                       | Notebook    | [4c27c4945c](https://linux-hardware.org/?probe=4c27c4945c) | Oct 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [502ae94f8f](https://linux-hardware.org/?probe=502ae94f8f) | Oct 20, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [d0dcb7e6e3](https://linux-hardware.org/?probe=d0dcb7e6e3) | Oct 20, 2022 |
| NZXT          | N7 B550                     | Desktop     | [f699b7e1d2](https://linux-hardware.org/?probe=f699b7e1d2) | Oct 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [866d0f49a2](https://linux-hardware.org/?probe=866d0f49a2) | Oct 20, 2022 |
| HP            | 8459                        | Desktop     | [d8ec2e7ee9](https://linux-hardware.org/?probe=d8ec2e7ee9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [13f4800fa8](https://linux-hardware.org/?probe=13f4800fa8) | Oct 20, 2022 |
| Framework     | Laptop                      | Notebook    | [ade55fca33](https://linux-hardware.org/?probe=ade55fca33) | Oct 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [76c0902958](https://linux-hardware.org/?probe=76c0902958) | Oct 19, 2022 |
| Gigabyte      | P67A-UD3                    | Desktop     | [96b72bfa8a](https://linux-hardware.org/?probe=96b72bfa8a) | Oct 19, 2022 |
| Framework     | Laptop                      | Notebook    | [57af01b405](https://linux-hardware.org/?probe=57af01b405) | Oct 19, 2022 |
| Shuttle       | FH67H                       | Desktop     | [6679449225](https://linux-hardware.org/?probe=6679449225) | Oct 19, 2022 |
| Dell          | Latitude 7420               | Notebook    | [332d2cd420](https://linux-hardware.org/?probe=332d2cd420) | Oct 19, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [980d0d7bb2](https://linux-hardware.org/?probe=980d0d7bb2) | Oct 19, 2022 |
| System76      | Kudu                        | Notebook    | [49c0e1c400](https://linux-hardware.org/?probe=49c0e1c400) | Oct 19, 2022 |
| Dell          | Precision 7760              | Notebook    | [a5ab2793ae](https://linux-hardware.org/?probe=a5ab2793ae) | Oct 19, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [aeedc0bfd0](https://linux-hardware.org/?probe=aeedc0bfd0) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [680823db07](https://linux-hardware.org/?probe=680823db07) | Oct 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [71734a9abe](https://linux-hardware.org/?probe=71734a9abe) | Oct 19, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [f91daeac73](https://linux-hardware.org/?probe=f91daeac73) | Oct 19, 2022 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [8665ee6ba6](https://linux-hardware.org/?probe=8665ee6ba6) | Oct 19, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d267c64062](https://linux-hardware.org/?probe=d267c64062) | Oct 19, 2022 |
| Lenovo        | Yoga 900-13ISK2 80UE        | Notebook    | [efadc96c65](https://linux-hardware.org/?probe=efadc96c65) | Oct 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [da8a11aac5](https://linux-hardware.org/?probe=da8a11aac5) | Oct 19, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [41d2e6298d](https://linux-hardware.org/?probe=41d2e6298d) | Oct 19, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [eab0779b74](https://linux-hardware.org/?probe=eab0779b74) | Oct 19, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [95a75ab35b](https://linux-hardware.org/?probe=95a75ab35b) | Oct 19, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [495c7fdc3d](https://linux-hardware.org/?probe=495c7fdc3d) | Oct 18, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [e0c8c2fe15](https://linux-hardware.org/?probe=e0c8c2fe15) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [6941ece1e9](https://linux-hardware.org/?probe=6941ece1e9) | Oct 18, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | Notebook    | [28a1d15220](https://linux-hardware.org/?probe=28a1d15220) | Oct 18, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [70d12e710f](https://linux-hardware.org/?probe=70d12e710f) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [aaa41de825](https://linux-hardware.org/?probe=aaa41de825) | Oct 18, 2022 |
| Lenovo        | B560                        | Notebook    | [717af973da](https://linux-hardware.org/?probe=717af973da) | Oct 18, 2022 |
| Dell          | Precision 5510              | Notebook    | [d56d0aceaf](https://linux-hardware.org/?probe=d56d0aceaf) | Oct 18, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [5c2590f03f](https://linux-hardware.org/?probe=5c2590f03f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [df0afd4326](https://linux-hardware.org/?probe=df0afd4326) | Oct 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d53b4edda1](https://linux-hardware.org/?probe=d53b4edda1) | Oct 18, 2022 |
| Acer          | Spin SP513-52N              | Convertible | [465c32fbf8](https://linux-hardware.org/?probe=465c32fbf8) | Oct 18, 2022 |
| ASRock        | Z97E-ITX/ac                 | Desktop     | [2ae712a746](https://linux-hardware.org/?probe=2ae712a746) | Oct 18, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [527c4e0728](https://linux-hardware.org/?probe=527c4e0728) | Oct 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [76f9929a9c](https://linux-hardware.org/?probe=76f9929a9c) | Oct 17, 2022 |
| MSI           | Summit E16Flip A11UCT       | Notebook    | [f1ec40e34d](https://linux-hardware.org/?probe=f1ec40e34d) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [9e1f6ae49e](https://linux-hardware.org/?probe=9e1f6ae49e) | Oct 17, 2022 |
| Dell          | Latitude 9420               | Convertible | [319c3b9f03](https://linux-hardware.org/?probe=319c3b9f03) | Oct 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7f9219a85f](https://linux-hardware.org/?probe=7f9219a85f) | Oct 17, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [c80df2b63c](https://linux-hardware.org/?probe=c80df2b63c) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [2fd734cbfb](https://linux-hardware.org/?probe=2fd734cbfb) | Oct 17, 2022 |
| Acer          | Aspire A717-71G             | Notebook    | [969c0ac771](https://linux-hardware.org/?probe=969c0ac771) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [528fc3c5ec](https://linux-hardware.org/?probe=528fc3c5ec) | Oct 17, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [f93d1bc535](https://linux-hardware.org/?probe=f93d1bc535) | Oct 17, 2022 |
| Dell          | Inspiron 13 5320            | Notebook    | [9ac52708ad](https://linux-hardware.org/?probe=9ac52708ad) | Oct 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e618e79bd5](https://linux-hardware.org/?probe=e618e79bd5) | Oct 17, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [678415db20](https://linux-hardware.org/?probe=678415db20) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [8c1b258565](https://linux-hardware.org/?probe=8c1b258565) | Oct 16, 2022 |
| Notebook      | W230SS                      | Notebook    | [abb5e7fda8](https://linux-hardware.org/?probe=abb5e7fda8) | Oct 16, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [50fe9fcad5](https://linux-hardware.org/?probe=50fe9fcad5) | Oct 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [f98ff2b890](https://linux-hardware.org/?probe=f98ff2b890) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [f20a72be72](https://linux-hardware.org/?probe=f20a72be72) | Oct 16, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [6a9b93fdeb](https://linux-hardware.org/?probe=6a9b93fdeb) | Oct 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [77c8619d03](https://linux-hardware.org/?probe=77c8619d03) | Oct 16, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [c78fae026e](https://linux-hardware.org/?probe=c78fae026e) | Oct 16, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [834248c556](https://linux-hardware.org/?probe=834248c556) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0cceedcb07](https://linux-hardware.org/?probe=0cceedcb07) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [dce51f4ce7](https://linux-hardware.org/?probe=dce51f4ce7) | Oct 16, 2022 |
| Lenovo        | ThinkPad X230 23257BG       | Notebook    | [6c8a42718a](https://linux-hardware.org/?probe=6c8a42718a) | Oct 16, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [156e3942e5](https://linux-hardware.org/?probe=156e3942e5) | Oct 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2a36feb313](https://linux-hardware.org/?probe=2a36feb313) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [77f04d4628](https://linux-hardware.org/?probe=77f04d4628) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | Notebook    | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [ee436e327b](https://linux-hardware.org/?probe=ee436e327b) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [86e01f1479](https://linux-hardware.org/?probe=86e01f1479) | Oct 16, 2022 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [c3c46266d1](https://linux-hardware.org/?probe=c3c46266d1) | Oct 16, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [d73a82b798](https://linux-hardware.org/?probe=d73a82b798) | Oct 15, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [5d60b980ca](https://linux-hardware.org/?probe=5d60b980ca) | Oct 15, 2022 |
| Timi          | TM1701                      | Notebook    | [c2b709ff0c](https://linux-hardware.org/?probe=c2b709ff0c) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [1993500f68](https://linux-hardware.org/?probe=1993500f68) | Oct 15, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [478b58f9b6](https://linux-hardware.org/?probe=478b58f9b6) | Oct 15, 2022 |
| Dell          | Latitude E5450              | Notebook    | [68e2c17e2f](https://linux-hardware.org/?probe=68e2c17e2f) | Oct 15, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | Desktop     | [985b192440](https://linux-hardware.org/?probe=985b192440) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8557c8b501](https://linux-hardware.org/?probe=8557c8b501) | Oct 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4e66c25e04](https://linux-hardware.org/?probe=4e66c25e04) | Oct 15, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [7979753fa9](https://linux-hardware.org/?probe=7979753fa9) | Oct 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [bf6d77aefd](https://linux-hardware.org/?probe=bf6d77aefd) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [3c5f4ad9a5](https://linux-hardware.org/?probe=3c5f4ad9a5) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | Desktop     | [05fa96288f](https://linux-hardware.org/?probe=05fa96288f) | Oct 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ab212a80b4](https://linux-hardware.org/?probe=ab212a80b4) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [e1bc46388d](https://linux-hardware.org/?probe=e1bc46388d) | Oct 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [49821787e4](https://linux-hardware.org/?probe=49821787e4) | Oct 14, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [6381ab6a1b](https://linux-hardware.org/?probe=6381ab6a1b) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6de814388c](https://linux-hardware.org/?probe=6de814388c) | Oct 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [1200f4104f](https://linux-hardware.org/?probe=1200f4104f) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [79eba98b95](https://linux-hardware.org/?probe=79eba98b95) | Oct 14, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [f9c2c298c4](https://linux-hardware.org/?probe=f9c2c298c4) | Oct 14, 2022 |
| Acer          | Spin SP315-51               | Convertible | [28103297c2](https://linux-hardware.org/?probe=28103297c2) | Oct 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [dbd2328d0f](https://linux-hardware.org/?probe=dbd2328d0f) | Oct 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [3a8bdfb3f5](https://linux-hardware.org/?probe=3a8bdfb3f5) | Oct 14, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2fb7882f4a](https://linux-hardware.org/?probe=2fb7882f4a) | Oct 14, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [1fe306ae1e](https://linux-hardware.org/?probe=1fe306ae1e) | Oct 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f4d190e864](https://linux-hardware.org/?probe=f4d190e864) | Oct 13, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [60b21aed9a](https://linux-hardware.org/?probe=60b21aed9a) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [9b0a923899](https://linux-hardware.org/?probe=9b0a923899) | Oct 13, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [a3f2f1dcc7](https://linux-hardware.org/?probe=a3f2f1dcc7) | Oct 13, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [5985f3564a](https://linux-hardware.org/?probe=5985f3564a) | Oct 13, 2022 |
| Lenovo        | ThinkPad X270 20HMS2R900    | Notebook    | [38739fd54f](https://linux-hardware.org/?probe=38739fd54f) | Oct 13, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [a6083f4dfe](https://linux-hardware.org/?probe=a6083f4dfe) | Oct 13, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [47394cb2b5](https://linux-hardware.org/?probe=47394cb2b5) | Oct 13, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [0c7961c445](https://linux-hardware.org/?probe=0c7961c445) | Oct 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [7af879de72](https://linux-hardware.org/?probe=7af879de72) | Oct 13, 2022 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [2be4dc3fc2](https://linux-hardware.org/?probe=2be4dc3fc2) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4a4b8d42fc](https://linux-hardware.org/?probe=4a4b8d42fc) | Oct 13, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [f1fcb66794](https://linux-hardware.org/?probe=f1fcb66794) | Oct 12, 2022 |
| Tactus        | GeoFlex 110                 | Convertible | [70fe7376b5](https://linux-hardware.org/?probe=70fe7376b5) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d0d2949fd3](https://linux-hardware.org/?probe=d0d2949fd3) | Oct 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [8437ac2ffc](https://linux-hardware.org/?probe=8437ac2ffc) | Oct 12, 2022 |
| Acer          | Aspire A715-71G             | Notebook    | [2b0752150c](https://linux-hardware.org/?probe=2b0752150c) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2412a53d05](https://linux-hardware.org/?probe=2412a53d05) | Oct 12, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [f58608a000](https://linux-hardware.org/?probe=f58608a000) | Oct 11, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [e2a5049dc1](https://linux-hardware.org/?probe=e2a5049dc1) | Oct 11, 2022 |
| HP            | 82A5                        | Mini pc     | [5a8ea35493](https://linux-hardware.org/?probe=5a8ea35493) | Oct 11, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [a993db557b](https://linux-hardware.org/?probe=a993db557b) | Oct 11, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [0355b3f7b8](https://linux-hardware.org/?probe=0355b3f7b8) | Oct 11, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [60b02deb7f](https://linux-hardware.org/?probe=60b02deb7f) | Oct 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [14b0f43bd5](https://linux-hardware.org/?probe=14b0f43bd5) | Oct 11, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [dde4a94108](https://linux-hardware.org/?probe=dde4a94108) | Oct 11, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [d6688af09b](https://linux-hardware.org/?probe=d6688af09b) | Oct 11, 2022 |
| Gigabyte      | H410M DS2V                  | Desktop     | [bd9d9e10c7](https://linux-hardware.org/?probe=bd9d9e10c7) | Oct 11, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [11f3146366](https://linux-hardware.org/?probe=11f3146366) | Oct 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [60037612c1](https://linux-hardware.org/?probe=60037612c1) | Oct 11, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | Notebook    | [71c926fc14](https://linux-hardware.org/?probe=71c926fc14) | Oct 11, 2022 |
| Lenovo        | ThinkPad P50 20EQS5MP00     | Notebook    | [83858a99c3](https://linux-hardware.org/?probe=83858a99c3) | Oct 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [5caff1861e](https://linux-hardware.org/?probe=5caff1861e) | Oct 10, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [cae3279751](https://linux-hardware.org/?probe=cae3279751) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e2d9db1022](https://linux-hardware.org/?probe=e2d9db1022) | Oct 10, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [dc3347c309](https://linux-hardware.org/?probe=dc3347c309) | Oct 10, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | Notebook    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [49fff6123f](https://linux-hardware.org/?probe=49fff6123f) | Oct 10, 2022 |
| ASRock        | X570 PG Velocita            | Desktop     | [ec3a819326](https://linux-hardware.org/?probe=ec3a819326) | Oct 10, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [59f6b7653c](https://linux-hardware.org/?probe=59f6b7653c) | Oct 10, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [29f63f8a32](https://linux-hardware.org/?probe=29f63f8a32) | Oct 10, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| Intel         | DG41TY AAE47335-302         | Desktop     | [c0d07ec775](https://linux-hardware.org/?probe=c0d07ec775) | Oct 10, 2022 |
| MSI           | B450 GAMING PLUS            | Desktop     | [6f95e1591a](https://linux-hardware.org/?probe=6f95e1591a) | Oct 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [cab829a52b](https://linux-hardware.org/?probe=cab829a52b) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [6c2f880759](https://linux-hardware.org/?probe=6c2f880759) | Oct 09, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [52658eb393](https://linux-hardware.org/?probe=52658eb393) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8694ed82a6](https://linux-hardware.org/?probe=8694ed82a6) | Oct 09, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [5d882bd47f](https://linux-hardware.org/?probe=5d882bd47f) | Oct 09, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [edb6e4180f](https://linux-hardware.org/?probe=edb6e4180f) | Oct 09, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [c4e09cdf87](https://linux-hardware.org/?probe=c4e09cdf87) | Oct 09, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [6a56a66eae](https://linux-hardware.org/?probe=6a56a66eae) | Oct 09, 2022 |
| PINE64        | Pinebook Pro                | Soc         | [8d79fe1eba](https://linux-hardware.org/?probe=8d79fe1eba) | Oct 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [4aa8b37ac5](https://linux-hardware.org/?probe=4aa8b37ac5) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | Notebook    | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [dc262edc58](https://linux-hardware.org/?probe=dc262edc58) | Oct 09, 2022 |
| Framework     | Laptop                      | Notebook    | [3d25e7f96c](https://linux-hardware.org/?probe=3d25e7f96c) | Oct 09, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [01abf75c2e](https://linux-hardware.org/?probe=01abf75c2e) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [30ff2d0e8f](https://linux-hardware.org/?probe=30ff2d0e8f) | Oct 09, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [19ad61d9c7](https://linux-hardware.org/?probe=19ad61d9c7) | Oct 09, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [cc8b98a2ff](https://linux-hardware.org/?probe=cc8b98a2ff) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c0c2e0ca69](https://linux-hardware.org/?probe=c0c2e0ca69) | Oct 08, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [0f4a711f6a](https://linux-hardware.org/?probe=0f4a711f6a) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [615578d390](https://linux-hardware.org/?probe=615578d390) | Oct 08, 2022 |
| Lenovo        | ThinkPad L470 20J4CTO1WW    | Notebook    | [3aee91df8c](https://linux-hardware.org/?probe=3aee91df8c) | Oct 08, 2022 |
| Dell          | 0RY007                      | Desktop     | [745f69ec3d](https://linux-hardware.org/?probe=745f69ec3d) | Oct 08, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [126b7b85f2](https://linux-hardware.org/?probe=126b7b85f2) | Oct 08, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3d968cc61a](https://linux-hardware.org/?probe=3d968cc61a) | Oct 08, 2022 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [9836cb655c](https://linux-hardware.org/?probe=9836cb655c) | Oct 08, 2022 |
| HP            | 3647h                       | Desktop     | [ddffa21a6e](https://linux-hardware.org/?probe=ddffa21a6e) | Oct 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [973605d3af](https://linux-hardware.org/?probe=973605d3af) | Oct 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [74f6e9db69](https://linux-hardware.org/?probe=74f6e9db69) | Oct 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8895a815c6](https://linux-hardware.org/?probe=8895a815c6) | Oct 07, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [812ed8c396](https://linux-hardware.org/?probe=812ed8c396) | Oct 07, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [fdab72c478](https://linux-hardware.org/?probe=fdab72c478) | Oct 07, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [26dfdb5aed](https://linux-hardware.org/?probe=26dfdb5aed) | Oct 07, 2022 |
| HP            | Laptop 14s-dr1xxx           | Notebook    | [00d04b6a56](https://linux-hardware.org/?probe=00d04b6a56) | Oct 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d67006c592](https://linux-hardware.org/?probe=d67006c592) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [08e98e28c2](https://linux-hardware.org/?probe=08e98e28c2) | Oct 07, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| Dell          | Latitude 5580               | Notebook    | [4bcae73c95](https://linux-hardware.org/?probe=4bcae73c95) | Oct 07, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [6a9f611fd5](https://linux-hardware.org/?probe=6a9f611fd5) | Oct 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [d5247cbbc3](https://linux-hardware.org/?probe=d5247cbbc3) | Oct 06, 2022 |
| Unknown       | Intel X79                   | Desktop     | [9c0ffde822](https://linux-hardware.org/?probe=9c0ffde822) | Oct 06, 2022 |
| Dell          | Latitude 5400               | Notebook    | [00789b23c6](https://linux-hardware.org/?probe=00789b23c6) | Oct 06, 2022 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [17d5aa4f87](https://linux-hardware.org/?probe=17d5aa4f87) | Oct 06, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [c8c6a428db](https://linux-hardware.org/?probe=c8c6a428db) | Oct 06, 2022 |
| ASUSTek       | X550LA                      | Notebook    | [c0c98c2051](https://linux-hardware.org/?probe=c0c98c2051) | Oct 06, 2022 |
| HP            | 0AECh D                     | Desktop     | [8fd13e9017](https://linux-hardware.org/?probe=8fd13e9017) | Oct 06, 2022 |
| MSI           | X370 SLI PLUS               | Desktop     | [ea7dc6a41a](https://linux-hardware.org/?probe=ea7dc6a41a) | Oct 06, 2022 |
| HP            | 15                          | Notebook    | [9f0981ed52](https://linux-hardware.org/?probe=9f0981ed52) | Oct 06, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [3ea8d4d25e](https://linux-hardware.org/?probe=3ea8d4d25e) | Oct 06, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [ddf48e7a31](https://linux-hardware.org/?probe=ddf48e7a31) | Oct 06, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | Notebook    | [4fe1810c2c](https://linux-hardware.org/?probe=4fe1810c2c) | Oct 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5dbeb45ba5](https://linux-hardware.org/?probe=5dbeb45ba5) | Oct 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6a5822719f](https://linux-hardware.org/?probe=6a5822719f) | Oct 06, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [20b6b5f918](https://linux-hardware.org/?probe=20b6b5f918) | Oct 06, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [b0fa4fab35](https://linux-hardware.org/?probe=b0fa4fab35) | Oct 05, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [7f2b63950d](https://linux-hardware.org/?probe=7f2b63950d) | Oct 05, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [a545cecc64](https://linux-hardware.org/?probe=a545cecc64) | Oct 05, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [06fa787cb1](https://linux-hardware.org/?probe=06fa787cb1) | Oct 05, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [368530a660](https://linux-hardware.org/?probe=368530a660) | Oct 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [f6fc1950ac](https://linux-hardware.org/?probe=f6fc1950ac) | Oct 05, 2022 |
| Dell          | Latitude 5400               | Notebook    | [14ed107028](https://linux-hardware.org/?probe=14ed107028) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d0d3494971](https://linux-hardware.org/?probe=d0d3494971) | Oct 05, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [a60e3c519e](https://linux-hardware.org/?probe=a60e3c519e) | Oct 05, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [77176ee82a](https://linux-hardware.org/?probe=77176ee82a) | Oct 05, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7590ca8bff](https://linux-hardware.org/?probe=7590ca8bff) | Oct 05, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [ddb0e3fb81](https://linux-hardware.org/?probe=ddb0e3fb81) | Oct 05, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [51c401fd4e](https://linux-hardware.org/?probe=51c401fd4e) | Oct 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [ca81117136](https://linux-hardware.org/?probe=ca81117136) | Oct 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [3d5136540e](https://linux-hardware.org/?probe=3d5136540e) | Oct 05, 2022 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [2bd986670e](https://linux-hardware.org/?probe=2bd986670e) | Oct 04, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [b78c69e096](https://linux-hardware.org/?probe=b78c69e096) | Oct 04, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [cb204abf9b](https://linux-hardware.org/?probe=cb204abf9b) | Oct 04, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [128725bb4d](https://linux-hardware.org/?probe=128725bb4d) | Oct 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [dc80de33ee](https://linux-hardware.org/?probe=dc80de33ee) | Oct 04, 2022 |
| HP            | Laptop                      | Notebook    | [3a26ec874f](https://linux-hardware.org/?probe=3a26ec874f) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [4ba3e28201](https://linux-hardware.org/?probe=4ba3e28201) | Oct 04, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [07d4cf95ec](https://linux-hardware.org/?probe=07d4cf95ec) | Oct 04, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7e0854ac78](https://linux-hardware.org/?probe=7e0854ac78) | Oct 04, 2022 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [3a515cdda0](https://linux-hardware.org/?probe=3a515cdda0) | Oct 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [923a579655](https://linux-hardware.org/?probe=923a579655) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | Notebook    | [a9c2a1eca0](https://linux-hardware.org/?probe=a9c2a1eca0) | Oct 03, 2022 |
| Timi          | A35S                        | Notebook    | [fe7ad0ac13](https://linux-hardware.org/?probe=fe7ad0ac13) | Oct 03, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [4e6047ec5b](https://linux-hardware.org/?probe=4e6047ec5b) | Oct 03, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [7bb0235bd2](https://linux-hardware.org/?probe=7bb0235bd2) | Oct 03, 2022 |
| Intel         | NUC10i3FNB K61362-306       | Mini pc     | [e8130be6f2](https://linux-hardware.org/?probe=e8130be6f2) | Oct 03, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [99df624686](https://linux-hardware.org/?probe=99df624686) | Oct 03, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [2f9e023d1e](https://linux-hardware.org/?probe=2f9e023d1e) | Oct 03, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [45a46cdb72](https://linux-hardware.org/?probe=45a46cdb72) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [48e867fba8](https://linux-hardware.org/?probe=48e867fba8) | Oct 02, 2022 |
| Acer          | Veriton X6620G v1.0         | Desktop     | [80e98d9053](https://linux-hardware.org/?probe=80e98d9053) | Oct 02, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [92aca0d081](https://linux-hardware.org/?probe=92aca0d081) | Oct 02, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [253e143d94](https://linux-hardware.org/?probe=253e143d94) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [8f24127ac0](https://linux-hardware.org/?probe=8f24127ac0) | Oct 02, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| Zinox Tech... | x64-Based PC                | Tablet      | [de64a1e585](https://linux-hardware.org/?probe=de64a1e585) | Oct 02, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6121fee541](https://linux-hardware.org/?probe=6121fee541) | Oct 02, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [80a2948ff1](https://linux-hardware.org/?probe=80a2948ff1) | Oct 02, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [9e5ab25f54](https://linux-hardware.org/?probe=9e5ab25f54) | Oct 02, 2022 |
| Dell          | Inspiron 17-7779            | Notebook    | [5bd534e938](https://linux-hardware.org/?probe=5bd534e938) | Oct 02, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [6d8ed9f182](https://linux-hardware.org/?probe=6d8ed9f182) | Oct 02, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [2f8557640c](https://linux-hardware.org/?probe=2f8557640c) | Oct 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a0d36f3810](https://linux-hardware.org/?probe=a0d36f3810) | Oct 02, 2022 |
| ASRock        | X570 Phantom Gaming 4S      | Desktop     | [2215129a47](https://linux-hardware.org/?probe=2215129a47) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [ee22a244e2](https://linux-hardware.org/?probe=ee22a244e2) | Oct 01, 2022 |
| MICROMAX      | Canvas Lapbook L1161        | Notebook    | [9efe9e89d6](https://linux-hardware.org/?probe=9efe9e89d6) | Oct 01, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [1fade0f247](https://linux-hardware.org/?probe=1fade0f247) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [4275ef3653](https://linux-hardware.org/?probe=4275ef3653) | Oct 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [186495d063](https://linux-hardware.org/?probe=186495d063) | Oct 01, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [d60b15ea91](https://linux-hardware.org/?probe=d60b15ea91) | Oct 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [4662cb1d99](https://linux-hardware.org/?probe=4662cb1d99) | Oct 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9f64b9ed3d](https://linux-hardware.org/?probe=9f64b9ed3d) | Oct 01, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | Notebook    | [49bd2b0248](https://linux-hardware.org/?probe=49bd2b0248) | Oct 01, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [af9b794734](https://linux-hardware.org/?probe=af9b794734) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d5407763a0](https://linux-hardware.org/?probe=d5407763a0) | Sep 30, 2022 |
| Dell          | Latitude E4300              | Notebook    | [a860d9a446](https://linux-hardware.org/?probe=a860d9a446) | Sep 30, 2022 |
| GPD           | G1621-02                    | Notebook    | [6ae9fc596e](https://linux-hardware.org/?probe=6ae9fc596e) | Sep 30, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [162334ac1e](https://linux-hardware.org/?probe=162334ac1e) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [02c5cd53e9](https://linux-hardware.org/?probe=02c5cd53e9) | Sep 30, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c06e7e3586](https://linux-hardware.org/?probe=c06e7e3586) | Sep 30, 2022 |
| HP            | ProBook 6570b               | Notebook    | [d9be946342](https://linux-hardware.org/?probe=d9be946342) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d658b9dcbe](https://linux-hardware.org/?probe=d658b9dcbe) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [b15bae8e77](https://linux-hardware.org/?probe=b15bae8e77) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [126b8dd3ec](https://linux-hardware.org/?probe=126b8dd3ec) | Sep 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | Notebook    | [33353fc67c](https://linux-hardware.org/?probe=33353fc67c) | Sep 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS09L0... | Notebook    | [7c384e5578](https://linux-hardware.org/?probe=7c384e5578) | Sep 30, 2022 |
| SK hynix      | HyBook                      | Notebook    | [38b5f704a1](https://linux-hardware.org/?probe=38b5f704a1) | Sep 30, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [251f390772](https://linux-hardware.org/?probe=251f390772) | Sep 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6553398b7d](https://linux-hardware.org/?probe=6553398b7d) | Sep 30, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [d2a3575975](https://linux-hardware.org/?probe=d2a3575975) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [2c6b161d0f](https://linux-hardware.org/?probe=2c6b161d0f) | Sep 29, 2022 |
| Avell High... | A60 MUV                     | Notebook    | [888e375356](https://linux-hardware.org/?probe=888e375356) | Sep 29, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [18afdc2116](https://linux-hardware.org/?probe=18afdc2116) | Sep 29, 2022 |
| Dell          | Latitude 7430               | Notebook    | [2151370437](https://linux-hardware.org/?probe=2151370437) | Sep 29, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [99f729e814](https://linux-hardware.org/?probe=99f729e814) | Sep 29, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [e819e5dc14](https://linux-hardware.org/?probe=e819e5dc14) | Sep 29, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [cc7ad91815](https://linux-hardware.org/?probe=cc7ad91815) | Sep 29, 2022 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [7325511d27](https://linux-hardware.org/?probe=7325511d27) | Sep 29, 2022 |
| ASUSTek       | X555LA                      | Notebook    | [5ec700ea0a](https://linux-hardware.org/?probe=5ec700ea0a) | Sep 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [c6ae2f8a45](https://linux-hardware.org/?probe=c6ae2f8a45) | Sep 29, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [1d612b997a](https://linux-hardware.org/?probe=1d612b997a) | Sep 29, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [4118e245a3](https://linux-hardware.org/?probe=4118e245a3) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [067b155d9b](https://linux-hardware.org/?probe=067b155d9b) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [058aa145d3](https://linux-hardware.org/?probe=058aa145d3) | Sep 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [362c6b7436](https://linux-hardware.org/?probe=362c6b7436) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [a674def12d](https://linux-hardware.org/?probe=a674def12d) | Sep 29, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [23c809d2a7](https://linux-hardware.org/?probe=23c809d2a7) | Sep 29, 2022 |
| Dell          | Precision 7550              | Notebook    | [75f2949521](https://linux-hardware.org/?probe=75f2949521) | Sep 29, 2022 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | Notebook    | [9ac63cdce6](https://linux-hardware.org/?probe=9ac63cdce6) | Sep 29, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [fbba79fc43](https://linux-hardware.org/?probe=fbba79fc43) | Sep 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [d137298cb5](https://linux-hardware.org/?probe=d137298cb5) | Sep 28, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [b30346135b](https://linux-hardware.org/?probe=b30346135b) | Sep 28, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [513d236a1f](https://linux-hardware.org/?probe=513d236a1f) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ARE 81W4        | Notebook    | [b784552e84](https://linux-hardware.org/?probe=b784552e84) | Sep 28, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [89253de6f0](https://linux-hardware.org/?probe=89253de6f0) | Sep 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [84187f87ed](https://linux-hardware.org/?probe=84187f87ed) | Sep 28, 2022 |
| Medion        | Unknown                     | Notebook    | [821c3c8fed](https://linux-hardware.org/?probe=821c3c8fed) | Sep 28, 2022 |
| Alienware     | 14                          | Notebook    | [2d46ecc50e](https://linux-hardware.org/?probe=2d46ecc50e) | Sep 28, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [ded047597e](https://linux-hardware.org/?probe=ded047597e) | Sep 28, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [a4b44081c2](https://linux-hardware.org/?probe=a4b44081c2) | Sep 27, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [a6347449b3](https://linux-hardware.org/?probe=a6347449b3) | Sep 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| MSI           | GS66 Stealth 10SGS          | Notebook    | [644efb07cf](https://linux-hardware.org/?probe=644efb07cf) | Sep 27, 2022 |
| HONOR         | HGE-WX6                     | Notebook    | [5c61df4d20](https://linux-hardware.org/?probe=5c61df4d20) | Sep 27, 2022 |
| Dell          | 0YGYJY A01                  | Desktop     | [73e69debd9](https://linux-hardware.org/?probe=73e69debd9) | Sep 27, 2022 |
| Timi          | A35S                        | Notebook    | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6677830ce4](https://linux-hardware.org/?probe=6677830ce4) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [3d86bcf1b7](https://linux-hardware.org/?probe=3d86bcf1b7) | Sep 27, 2022 |
| HP            | 829A                        | Mini pc     | [1e26c7813f](https://linux-hardware.org/?probe=1e26c7813f) | Sep 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [c60d7e3375](https://linux-hardware.org/?probe=c60d7e3375) | Sep 27, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | Desktop     | [7af967061b](https://linux-hardware.org/?probe=7af967061b) | Sep 27, 2022 |
| Intel         | DP35DP AAD81073-208         | Desktop     | [031ff09179](https://linux-hardware.org/?probe=031ff09179) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [98742c4135](https://linux-hardware.org/?probe=98742c4135) | Sep 27, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [4308420b28](https://linux-hardware.org/?probe=4308420b28) | Sep 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [7c62f5131f](https://linux-hardware.org/?probe=7c62f5131f) | Sep 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [254a78c371](https://linux-hardware.org/?probe=254a78c371) | Sep 26, 2022 |
| MSI           | GT72 6QE                    | Notebook    | [5535b3367e](https://linux-hardware.org/?probe=5535b3367e) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6373bf42ef](https://linux-hardware.org/?probe=6373bf42ef) | Sep 26, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [ed657bfbb6](https://linux-hardware.org/?probe=ed657bfbb6) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [76166adede](https://linux-hardware.org/?probe=76166adede) | Sep 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f1d78ca455](https://linux-hardware.org/?probe=f1d78ca455) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| HP            | Tablet 11m-be0xxx           | Tablet      | [d644aedbdd](https://linux-hardware.org/?probe=d644aedbdd) | Sep 26, 2022 |
| MSI           | GT72 6QE                    | Notebook    | [d739812ce7](https://linux-hardware.org/?probe=d739812ce7) | Sep 26, 2022 |
| MSI           | GT72S 6QE                   | Notebook    | [7ec3a25453](https://linux-hardware.org/?probe=7ec3a25453) | Sep 26, 2022 |
| HP            | Laptop                      | Notebook    | [6d8fc869e4](https://linux-hardware.org/?probe=6d8fc869e4) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [52a86d0701](https://linux-hardware.org/?probe=52a86d0701) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [683aa83ea4](https://linux-hardware.org/?probe=683aa83ea4) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [64fd780b2f](https://linux-hardware.org/?probe=64fd780b2f) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d557cdbe1c](https://linux-hardware.org/?probe=d557cdbe1c) | Sep 26, 2022 |
| HP            | Laptop                      | Notebook    | [be59fc7a97](https://linux-hardware.org/?probe=be59fc7a97) | Sep 26, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [01cf3c6f99](https://linux-hardware.org/?probe=01cf3c6f99) | Sep 26, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [e2232c49ca](https://linux-hardware.org/?probe=e2232c49ca) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f8b76ec5f4](https://linux-hardware.org/?probe=f8b76ec5f4) | Sep 25, 2022 |
| AZW           | SEi                         | Notebook    | [063c3cc52e](https://linux-hardware.org/?probe=063c3cc52e) | Sep 25, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [778f7340fa](https://linux-hardware.org/?probe=778f7340fa) | Sep 25, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [d8b270de2b](https://linux-hardware.org/?probe=d8b270de2b) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [850b486cff](https://linux-hardware.org/?probe=850b486cff) | Sep 25, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [e9205da026](https://linux-hardware.org/?probe=e9205da026) | Sep 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [be1d17baa4](https://linux-hardware.org/?probe=be1d17baa4) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [9f37c7c4fa](https://linux-hardware.org/?probe=9f37c7c4fa) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [0d790a94fa](https://linux-hardware.org/?probe=0d790a94fa) | Sep 25, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [fab5b34402](https://linux-hardware.org/?probe=fab5b34402) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [982d41c1eb](https://linux-hardware.org/?probe=982d41c1eb) | Sep 25, 2022 |
| Lenovo        | ThinkPad T420 4236C53       | Notebook    | [e0983b35fa](https://linux-hardware.org/?probe=e0983b35fa) | Sep 25, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [82b73270ca](https://linux-hardware.org/?probe=82b73270ca) | Sep 25, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [b26f7bf9f5](https://linux-hardware.org/?probe=b26f7bf9f5) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [a5d5950e29](https://linux-hardware.org/?probe=a5d5950e29) | Sep 25, 2022 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [cedbd8909f](https://linux-hardware.org/?probe=cedbd8909f) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [a1f261d09d](https://linux-hardware.org/?probe=a1f261d09d) | Sep 25, 2022 |
| Acer          | Aspire X1900                | Desktop     | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [66b5b65077](https://linux-hardware.org/?probe=66b5b65077) | Sep 25, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [a35dda8c10](https://linux-hardware.org/?probe=a35dda8c10) | Sep 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [2e96ddfdd1](https://linux-hardware.org/?probe=2e96ddfdd1) | Sep 25, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [f5e9524bff](https://linux-hardware.org/?probe=f5e9524bff) | Sep 25, 2022 |
| Dell          | Inspiron 14 7425 2-in-1     | Convertible | [9a7ec70bad](https://linux-hardware.org/?probe=9a7ec70bad) | Sep 25, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [6e7d310781](https://linux-hardware.org/?probe=6e7d310781) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [2d44b203f9](https://linux-hardware.org/?probe=2d44b203f9) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a4b47e7325](https://linux-hardware.org/?probe=a4b47e7325) | Sep 25, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B7402FEA... | Convertible | [593ef93760](https://linux-hardware.org/?probe=593ef93760) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [96f4499ec5](https://linux-hardware.org/?probe=96f4499ec5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [91bd22b430](https://linux-hardware.org/?probe=91bd22b430) | Sep 25, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [332540a4c8](https://linux-hardware.org/?probe=332540a4c8) | Sep 24, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [307a3c2848](https://linux-hardware.org/?probe=307a3c2848) | Sep 24, 2022 |
| ASRock        | Z170M Extreme4              | Desktop     | [bd1e98639b](https://linux-hardware.org/?probe=bd1e98639b) | Sep 24, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [2bdc1228a1](https://linux-hardware.org/?probe=2bdc1228a1) | Sep 24, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [eef9de3daf](https://linux-hardware.org/?probe=eef9de3daf) | Sep 24, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [b598ecc4f8](https://linux-hardware.org/?probe=b598ecc4f8) | Sep 24, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ee8183722c](https://linux-hardware.org/?probe=ee8183722c) | Sep 24, 2022 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [542249f675](https://linux-hardware.org/?probe=542249f675) | Sep 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ab2e3b1767](https://linux-hardware.org/?probe=ab2e3b1767) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0170bcbb42](https://linux-hardware.org/?probe=0170bcbb42) | Sep 24, 2022 |
| Lenovo        | ThinkPad T440s 20ARA0YL0... | Notebook    | [93eedc638b](https://linux-hardware.org/?probe=93eedc638b) | Sep 24, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [08843e7c7c](https://linux-hardware.org/?probe=08843e7c7c) | Sep 24, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [2082a8668b](https://linux-hardware.org/?probe=2082a8668b) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [b7f6ab8ad0](https://linux-hardware.org/?probe=b7f6ab8ad0) | Sep 23, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | Notebook    | [72caf18b5f](https://linux-hardware.org/?probe=72caf18b5f) | Sep 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2bb811e308](https://linux-hardware.org/?probe=2bb811e308) | Sep 23, 2022 |
| Timi          | A35S                        | Notebook    | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| AZW           | GTR V01                     | Mini pc     | [927faa3232](https://linux-hardware.org/?probe=927faa3232) | Sep 23, 2022 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c4c88d72ae](https://linux-hardware.org/?probe=c4c88d72ae) | Sep 23, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [c30d8893ca](https://linux-hardware.org/?probe=c30d8893ca) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [31f1acf273](https://linux-hardware.org/?probe=31f1acf273) | Sep 23, 2022 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [2e45736b42](https://linux-hardware.org/?probe=2e45736b42) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a4ce7c179e](https://linux-hardware.org/?probe=a4ce7c179e) | Sep 23, 2022 |
| Gigabyte      | B660I AORUS PRO DDR4        | Desktop     | [810c7883d4](https://linux-hardware.org/?probe=810c7883d4) | Sep 23, 2022 |
| Dell          | XPS 9320                    | Notebook    | [959d1406dd](https://linux-hardware.org/?probe=959d1406dd) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [7d69f0c6c6](https://linux-hardware.org/?probe=7d69f0c6c6) | Sep 23, 2022 |
| HONOR         | HGE-WX6                     | Notebook    | [337c1097ef](https://linux-hardware.org/?probe=337c1097ef) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [f72f370511](https://linux-hardware.org/?probe=f72f370511) | Sep 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0f750af134](https://linux-hardware.org/?probe=0f750af134) | Sep 23, 2022 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [79509e063b](https://linux-hardware.org/?probe=79509e063b) | Sep 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a5e851730c](https://linux-hardware.org/?probe=a5e851730c) | Sep 23, 2022 |
| Acer          | Aspire A715-43G             | Notebook    | [5ecaaef0b1](https://linux-hardware.org/?probe=5ecaaef0b1) | Sep 23, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [4867faffbf](https://linux-hardware.org/?probe=4867faffbf) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [c916654073](https://linux-hardware.org/?probe=c916654073) | Sep 22, 2022 |
| VALE          | Notebook Classic C140       | Notebook    | [5a8e431c98](https://linux-hardware.org/?probe=5a8e431c98) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [4d47a6bfcf](https://linux-hardware.org/?probe=4d47a6bfcf) | Sep 22, 2022 |
| Foxconn       | H61M-S/H61M                 | Desktop     | [039b5cff54](https://linux-hardware.org/?probe=039b5cff54) | Sep 22, 2022 |
| Dell          | Precision 5540              | Notebook    | [0f09e447ea](https://linux-hardware.org/?probe=0f09e447ea) | Sep 22, 2022 |
| Dell          | Vostro 3558                 | Notebook    | [61f6c99c88](https://linux-hardware.org/?probe=61f6c99c88) | Sep 22, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [efaa235d34](https://linux-hardware.org/?probe=efaa235d34) | Sep 22, 2022 |
| MSI           | H310M PRO-VH                | Desktop     | [c11e067cb5](https://linux-hardware.org/?probe=c11e067cb5) | Sep 22, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [2250b3380d](https://linux-hardware.org/?probe=2250b3380d) | Sep 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bfb470649a](https://linux-hardware.org/?probe=bfb470649a) | Sep 22, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [11ea16f0d6](https://linux-hardware.org/?probe=11ea16f0d6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [ba5fdd39e6](https://linux-hardware.org/?probe=ba5fdd39e6) | Sep 21, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [54d3096bb6](https://linux-hardware.org/?probe=54d3096bb6) | Sep 21, 2022 |
| Framework     | Laptop                      | Notebook    | [8e2d92c817](https://linux-hardware.org/?probe=8e2d92c817) | Sep 21, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [9515dd24c0](https://linux-hardware.org/?probe=9515dd24c0) | Sep 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [3f33a64102](https://linux-hardware.org/?probe=3f33a64102) | Sep 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [0d8e7f2e92](https://linux-hardware.org/?probe=0d8e7f2e92) | Sep 21, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [62a9723eb7](https://linux-hardware.org/?probe=62a9723eb7) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2e5553125e](https://linux-hardware.org/?probe=2e5553125e) | Sep 21, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [85cab20988](https://linux-hardware.org/?probe=85cab20988) | Sep 21, 2022 |
| Razer         | Blade                       | Notebook    | [c835fe2f90](https://linux-hardware.org/?probe=c835fe2f90) | Sep 21, 2022 |
| HP            | Pavilion 17                 | Notebook    | [0f7eec1f7a](https://linux-hardware.org/?probe=0f7eec1f7a) | Sep 21, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [20d37d51bd](https://linux-hardware.org/?probe=20d37d51bd) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [cabebaa0e6](https://linux-hardware.org/?probe=cabebaa0e6) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [deb8b0ca78](https://linux-hardware.org/?probe=deb8b0ca78) | Sep 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [754dfba736](https://linux-hardware.org/?probe=754dfba736) | Sep 21, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [d5b4924a7b](https://linux-hardware.org/?probe=d5b4924a7b) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [015c8dd353](https://linux-hardware.org/?probe=015c8dd353) | Sep 20, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [360e860fb1](https://linux-hardware.org/?probe=360e860fb1) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [1869422fde](https://linux-hardware.org/?probe=1869422fde) | Sep 20, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [a491827753](https://linux-hardware.org/?probe=a491827753) | Sep 20, 2022 |
| Dell          | Latitude 9420               | Convertible | [e8c592b354](https://linux-hardware.org/?probe=e8c592b354) | Sep 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [7561f24877](https://linux-hardware.org/?probe=7561f24877) | Sep 20, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [32120dfcd4](https://linux-hardware.org/?probe=32120dfcd4) | Sep 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [98771092de](https://linux-hardware.org/?probe=98771092de) | Sep 20, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [20c7b9dcf9](https://linux-hardware.org/?probe=20c7b9dcf9) | Sep 20, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [aad09d3281](https://linux-hardware.org/?probe=aad09d3281) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [f4aade3998](https://linux-hardware.org/?probe=f4aade3998) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [21617c5cff](https://linux-hardware.org/?probe=21617c5cff) | Sep 20, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [5cf4494f07](https://linux-hardware.org/?probe=5cf4494f07) | Sep 20, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | Notebook    | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [5b55138f5d](https://linux-hardware.org/?probe=5b55138f5d) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [95c8201663](https://linux-hardware.org/?probe=95c8201663) | Sep 20, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [80d61eb345](https://linux-hardware.org/?probe=80d61eb345) | Sep 20, 2022 |
| Lenovo        | ThinkPad T420 4180PBG       | Notebook    | [857b2acef0](https://linux-hardware.org/?probe=857b2acef0) | Sep 20, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [acf36b1555](https://linux-hardware.org/?probe=acf36b1555) | Sep 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [fa5f7f7245](https://linux-hardware.org/?probe=fa5f7f7245) | Sep 20, 2022 |
| HP            | ENVY 15                     | Notebook    | [6921f93893](https://linux-hardware.org/?probe=6921f93893) | Sep 20, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [7bd22a5e38](https://linux-hardware.org/?probe=7bd22a5e38) | Sep 20, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [75854836f7](https://linux-hardware.org/?probe=75854836f7) | Sep 20, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [4ae5282199](https://linux-hardware.org/?probe=4ae5282199) | Sep 20, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [3f82789198](https://linux-hardware.org/?probe=3f82789198) | Sep 20, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [b6ce2720e2](https://linux-hardware.org/?probe=b6ce2720e2) | Sep 20, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [1da95a964b](https://linux-hardware.org/?probe=1da95a964b) | Sep 20, 2022 |
| ASRock        | H610M-HDV/M.2               | Desktop     | [02a5a10d7a](https://linux-hardware.org/?probe=02a5a10d7a) | Sep 20, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [b88a699d58](https://linux-hardware.org/?probe=b88a699d58) | Sep 19, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [d44ac0cc2a](https://linux-hardware.org/?probe=d44ac0cc2a) | Sep 19, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a6857e4b03](https://linux-hardware.org/?probe=a6857e4b03) | Sep 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [424e3ded44](https://linux-hardware.org/?probe=424e3ded44) | Sep 19, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [8027be6f7e](https://linux-hardware.org/?probe=8027be6f7e) | Sep 19, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a681a7cab8](https://linux-hardware.org/?probe=a681a7cab8) | Sep 19, 2022 |
| HP            | 2B05                        | Desktop     | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [e728637650](https://linux-hardware.org/?probe=e728637650) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f8bf8fd596](https://linux-hardware.org/?probe=f8bf8fd596) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7a1dbe2204](https://linux-hardware.org/?probe=7a1dbe2204) | Sep 19, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [bed329dab4](https://linux-hardware.org/?probe=bed329dab4) | Sep 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [8072b6c0e0](https://linux-hardware.org/?probe=8072b6c0e0) | Sep 19, 2022 |
| ASUSTek       | P8Q77-M2                    | Desktop     | [1e067b7c4f](https://linux-hardware.org/?probe=1e067b7c4f) | Sep 19, 2022 |
| Lenovo        | ThinkPad T540p 20BFS0RK0... | Notebook    | [eaaf80509b](https://linux-hardware.org/?probe=eaaf80509b) | Sep 19, 2022 |
| Toshiba       | Satellite L40t-A            | Notebook    | [b09254248d](https://linux-hardware.org/?probe=b09254248d) | Sep 19, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [7c52790345](https://linux-hardware.org/?probe=7c52790345) | Sep 19, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [9b14ec4438](https://linux-hardware.org/?probe=9b14ec4438) | Sep 19, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [6fd34fa73b](https://linux-hardware.org/?probe=6fd34fa73b) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [bf7318e65e](https://linux-hardware.org/?probe=bf7318e65e) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [ede9aab3fb](https://linux-hardware.org/?probe=ede9aab3fb) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [db46d34737](https://linux-hardware.org/?probe=db46d34737) | Sep 19, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [4c8883345d](https://linux-hardware.org/?probe=4c8883345d) | Sep 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| ASUSTek       | ROG Flow X16 GV601RE_GV6... | Convertible | [ad99d47a5e](https://linux-hardware.org/?probe=ad99d47a5e) | Sep 19, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [37f0f7b888](https://linux-hardware.org/?probe=37f0f7b888) | Sep 19, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [75be2db65c](https://linux-hardware.org/?probe=75be2db65c) | Sep 19, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [9776f2c20c](https://linux-hardware.org/?probe=9776f2c20c) | Sep 19, 2022 |
| Dell          | 02M8NY A01                  | Desktop     | [498286eb91](https://linux-hardware.org/?probe=498286eb91) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [474f619a29](https://linux-hardware.org/?probe=474f619a29) | Sep 19, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ac5b5a53a2](https://linux-hardware.org/?probe=ac5b5a53a2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [be279328b1](https://linux-hardware.org/?probe=be279328b1) | Sep 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [3da12828c0](https://linux-hardware.org/?probe=3da12828c0) | Sep 19, 2022 |
| Dell          | Precision 5560              | Notebook    | [5e70cfd82f](https://linux-hardware.org/?probe=5e70cfd82f) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [bb8fdeb489](https://linux-hardware.org/?probe=bb8fdeb489) | Sep 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [6c63c03b9f](https://linux-hardware.org/?probe=6c63c03b9f) | Sep 19, 2022 |
| Dell          | Latitude 5420               | Notebook    | [1e5a1652cc](https://linux-hardware.org/?probe=1e5a1652cc) | Sep 19, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [7c89dc4342](https://linux-hardware.org/?probe=7c89dc4342) | Sep 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5233832be3](https://linux-hardware.org/?probe=5233832be3) | Sep 19, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [8d2c35d5f2](https://linux-hardware.org/?probe=8d2c35d5f2) | Sep 19, 2022 |
| Lenovo        | ThinkPad T430 2349S4D       | Notebook    | [0c4d98868f](https://linux-hardware.org/?probe=0c4d98868f) | Sep 19, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [27d1f0c593](https://linux-hardware.org/?probe=27d1f0c593) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| ASUSTek       | P8Q77-M2                    | Desktop     | [171e24a5c1](https://linux-hardware.org/?probe=171e24a5c1) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [798bb8eda6](https://linux-hardware.org/?probe=798bb8eda6) | Sep 18, 2022 |
| HP            | 84EF 01100                  | All in one  | [2cde64548f](https://linux-hardware.org/?probe=2cde64548f) | Sep 18, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [b48eda0e37](https://linux-hardware.org/?probe=b48eda0e37) | Sep 18, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [f114799ded](https://linux-hardware.org/?probe=f114799ded) | Sep 18, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| ASUSTek       | PRIME H410M-K R2.0          | Desktop     | [7d18b85f33](https://linux-hardware.org/?probe=7d18b85f33) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b9bb35af47](https://linux-hardware.org/?probe=b9bb35af47) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [2032e77931](https://linux-hardware.org/?probe=2032e77931) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [21da8441d5](https://linux-hardware.org/?probe=21da8441d5) | Sep 18, 2022 |
| Casper        | NIRVANA DESKTOP             | Desktop     | [7cdffad4a2](https://linux-hardware.org/?probe=7cdffad4a2) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [751df30316](https://linux-hardware.org/?probe=751df30316) | Sep 18, 2022 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [1f27376b8e](https://linux-hardware.org/?probe=1f27376b8e) | Sep 18, 2022 |
| Acer          | Aspire TC-780               | Desktop     | [936ece435c](https://linux-hardware.org/?probe=936ece435c) | Sep 18, 2022 |
| Acer          | A75F2-M2 P21-A1             | Desktop     | [2d00ba463b](https://linux-hardware.org/?probe=2d00ba463b) | Sep 18, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [fe325d1046](https://linux-hardware.org/?probe=fe325d1046) | Sep 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECC... | Notebook    | [e09b077e89](https://linux-hardware.org/?probe=e09b077e89) | Sep 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [7161071790](https://linux-hardware.org/?probe=7161071790) | Sep 18, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [1f9f8ee511](https://linux-hardware.org/?probe=1f9f8ee511) | Sep 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0760539d3d](https://linux-hardware.org/?probe=0760539d3d) | Sep 18, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [fa2122b6ee](https://linux-hardware.org/?probe=fa2122b6ee) | Sep 18, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f27404a984](https://linux-hardware.org/?probe=f27404a984) | Sep 18, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [1c3c64ca91](https://linux-hardware.org/?probe=1c3c64ca91) | Sep 17, 2022 |
| Unknown       | Unknown                     | Notebook    | [1e27521b13](https://linux-hardware.org/?probe=1e27521b13) | Sep 17, 2022 |
| Acer          | Spin SP111-31               | Convertible | [fbeb9df498](https://linux-hardware.org/?probe=fbeb9df498) | Sep 17, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [ba54a7bf0c](https://linux-hardware.org/?probe=ba54a7bf0c) | Sep 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [3615e82cb6](https://linux-hardware.org/?probe=3615e82cb6) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [fd0bcfd41d](https://linux-hardware.org/?probe=fd0bcfd41d) | Sep 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [3b0169723f](https://linux-hardware.org/?probe=3b0169723f) | Sep 17, 2022 |
| Irbis         | NB264                       | Notebook    | [e9361bf1c8](https://linux-hardware.org/?probe=e9361bf1c8) | Sep 17, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [5a541fecce](https://linux-hardware.org/?probe=5a541fecce) | Sep 17, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [247e54458c](https://linux-hardware.org/?probe=247e54458c) | Sep 17, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [e138435857](https://linux-hardware.org/?probe=e138435857) | Sep 17, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [379aaf7b61](https://linux-hardware.org/?probe=379aaf7b61) | Sep 16, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [467d4c60c0](https://linux-hardware.org/?probe=467d4c60c0) | Sep 16, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [e191511194](https://linux-hardware.org/?probe=e191511194) | Sep 16, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [88481ce853](https://linux-hardware.org/?probe=88481ce853) | Sep 16, 2022 |
| Dell          | G3 3779                     | Notebook    | [5c24653999](https://linux-hardware.org/?probe=5c24653999) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [70a944e816](https://linux-hardware.org/?probe=70a944e816) | Sep 16, 2022 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [50669d6ff9](https://linux-hardware.org/?probe=50669d6ff9) | Sep 16, 2022 |
| Acidanther... | iMac19,2                    | Notebook    | [94b79ac6e5](https://linux-hardware.org/?probe=94b79ac6e5) | Sep 16, 2022 |
| Dell          | Latitude 5511               | Notebook    | [9a2faa8d22](https://linux-hardware.org/?probe=9a2faa8d22) | Sep 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [07dd87b76b](https://linux-hardware.org/?probe=07dd87b76b) | Sep 16, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [a29728a871](https://linux-hardware.org/?probe=a29728a871) | Sep 16, 2022 |
| HP            | 3397                        | Desktop     | [637a5570cf](https://linux-hardware.org/?probe=637a5570cf) | Sep 16, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [9497f1e17f](https://linux-hardware.org/?probe=9497f1e17f) | Sep 16, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [4d460404c8](https://linux-hardware.org/?probe=4d460404c8) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | Notebook    | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1cbebfbe09](https://linux-hardware.org/?probe=1cbebfbe09) | Sep 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9bfc1472d1](https://linux-hardware.org/?probe=9bfc1472d1) | Sep 16, 2022 |
| ASUSTek       | X550JK                      | Notebook    | [5c399f4fb0](https://linux-hardware.org/?probe=5c399f4fb0) | Sep 15, 2022 |
| ASUSTek       | X550JK                      | Notebook    | [59df382a23](https://linux-hardware.org/?probe=59df382a23) | Sep 15, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [dcaf7e8bd0](https://linux-hardware.org/?probe=dcaf7e8bd0) | Sep 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [80638ed98f](https://linux-hardware.org/?probe=80638ed98f) | Sep 15, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [c62891882f](https://linux-hardware.org/?probe=c62891882f) | Sep 15, 2022 |
| ASRock        | X370 Gaming K4              | Desktop     | [0858e80da7](https://linux-hardware.org/?probe=0858e80da7) | Sep 15, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| Gigabyte      | Z97P-D3                     | Desktop     | [ca9e537823](https://linux-hardware.org/?probe=ca9e537823) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [e633838a51](https://linux-hardware.org/?probe=e633838a51) | Sep 15, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| ASUSTek       | P5PL2-E                     | Desktop     | [84bfb7d319](https://linux-hardware.org/?probe=84bfb7d319) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c70951aae5](https://linux-hardware.org/?probe=c70951aae5) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [4b19ce2aab](https://linux-hardware.org/?probe=4b19ce2aab) | Sep 15, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [f566a009c8](https://linux-hardware.org/?probe=f566a009c8) | Sep 15, 2022 |
| HP            | Snappy                      | Notebook    | [d890c80994](https://linux-hardware.org/?probe=d890c80994) | Sep 15, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [2642647feb](https://linux-hardware.org/?probe=2642647feb) | Sep 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [6d4adb2a44](https://linux-hardware.org/?probe=6d4adb2a44) | Sep 14, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [d34c655d2b](https://linux-hardware.org/?probe=d34c655d2b) | Sep 14, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [efb36530f1](https://linux-hardware.org/?probe=efb36530f1) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [bbc3c68696](https://linux-hardware.org/?probe=bbc3c68696) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [ec8f0a9ebf](https://linux-hardware.org/?probe=ec8f0a9ebf) | Sep 14, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [55216d250b](https://linux-hardware.org/?probe=55216d250b) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [930ee68921](https://linux-hardware.org/?probe=930ee68921) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8fab790c57](https://linux-hardware.org/?probe=8fab790c57) | Sep 14, 2022 |
| HP            | 805D                        | Desktop     | [8acaebbd42](https://linux-hardware.org/?probe=8acaebbd42) | Sep 14, 2022 |
| System76      | Lemur Pro                   | Notebook    | [d6682a260a](https://linux-hardware.org/?probe=d6682a260a) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [c05d80959b](https://linux-hardware.org/?probe=c05d80959b) | Sep 14, 2022 |
| Dell          | Latitude 5521               | Notebook    | [c342e3ab13](https://linux-hardware.org/?probe=c342e3ab13) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| HP            | 1998                        | Desktop     | [bf93a500f4](https://linux-hardware.org/?probe=bf93a500f4) | Sep 14, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [23c756841a](https://linux-hardware.org/?probe=23c756841a) | Sep 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [37d6996290](https://linux-hardware.org/?probe=37d6996290) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [e7cb70c141](https://linux-hardware.org/?probe=e7cb70c141) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [754d0f3a2b](https://linux-hardware.org/?probe=754d0f3a2b) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [3f34e5ed01](https://linux-hardware.org/?probe=3f34e5ed01) | Sep 14, 2022 |
| Dell          | Inspiron 5575               | Notebook    | [1ae871a545](https://linux-hardware.org/?probe=1ae871a545) | Sep 14, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [175c84f6ea](https://linux-hardware.org/?probe=175c84f6ea) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d1b95841a4](https://linux-hardware.org/?probe=d1b95841a4) | Sep 13, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [d3f957e34a](https://linux-hardware.org/?probe=d3f957e34a) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7326474aae](https://linux-hardware.org/?probe=7326474aae) | Sep 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9b2a84cd02](https://linux-hardware.org/?probe=9b2a84cd02) | Sep 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [1285ab4d66](https://linux-hardware.org/?probe=1285ab4d66) | Sep 13, 2022 |
| Dell          | Precision 5560              | Notebook    | [78809c82c2](https://linux-hardware.org/?probe=78809c82c2) | Sep 13, 2022 |
| Dell          | Inspiron 7306 2n1           | Convertible | [4e73a1af5e](https://linux-hardware.org/?probe=4e73a1af5e) | Sep 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [61da5fee97](https://linux-hardware.org/?probe=61da5fee97) | Sep 13, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a6e7414518](https://linux-hardware.org/?probe=a6e7414518) | Sep 13, 2022 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [1faad914c6](https://linux-hardware.org/?probe=1faad914c6) | Sep 13, 2022 |
| Unknown       | X99H                        | Desktop     | [9fb8886110](https://linux-hardware.org/?probe=9fb8886110) | Sep 13, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [e040958337](https://linux-hardware.org/?probe=e040958337) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [472668e67b](https://linux-hardware.org/?probe=472668e67b) | Sep 12, 2022 |
| Lanix         | AL V9                       | Notebook    | [e03f9aecc3](https://linux-hardware.org/?probe=e03f9aecc3) | Sep 12, 2022 |
| Dell          | Latitude 5495               | Notebook    | [23586ab4ef](https://linux-hardware.org/?probe=23586ab4ef) | Sep 12, 2022 |
| Lenovo        | ThinkPad P1 20MD0014RT      | Notebook    | [4935debbce](https://linux-hardware.org/?probe=4935debbce) | Sep 12, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [a901769629](https://linux-hardware.org/?probe=a901769629) | Sep 12, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [e956067fa0](https://linux-hardware.org/?probe=e956067fa0) | Sep 12, 2022 |
| AZW           | SEi                         | Notebook    | [3a4d2086b0](https://linux-hardware.org/?probe=3a4d2086b0) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4a54854cd7](https://linux-hardware.org/?probe=4a54854cd7) | Sep 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [5bbf96fe23](https://linux-hardware.org/?probe=5bbf96fe23) | Sep 12, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [1f32b65385](https://linux-hardware.org/?probe=1f32b65385) | Sep 12, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [7ce5d8e865](https://linux-hardware.org/?probe=7ce5d8e865) | Sep 12, 2022 |
| HP            | ProBook 4540s               | Notebook    | [1f46e342f0](https://linux-hardware.org/?probe=1f46e342f0) | Sep 12, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ec5f57ab65](https://linux-hardware.org/?probe=ec5f57ab65) | Sep 12, 2022 |
| ASUSTek       | ROG Strix G713QR_G713QR     | Notebook    | [d05595b19e](https://linux-hardware.org/?probe=d05595b19e) | Sep 12, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [b23a59ba48](https://linux-hardware.org/?probe=b23a59ba48) | Sep 12, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [47b15d6b6c](https://linux-hardware.org/?probe=47b15d6b6c) | Sep 12, 2022 |
| HP            | 1494                        | Desktop     | [0faa06cff4](https://linux-hardware.org/?probe=0faa06cff4) | Sep 12, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [6847632df3](https://linux-hardware.org/?probe=6847632df3) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [edb2842417](https://linux-hardware.org/?probe=edb2842417) | Sep 12, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [c6df51fa3b](https://linux-hardware.org/?probe=c6df51fa3b) | Sep 11, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [7064ea27f5](https://linux-hardware.org/?probe=7064ea27f5) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [49fe1c56a3](https://linux-hardware.org/?probe=49fe1c56a3) | Sep 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d85067b0f0](https://linux-hardware.org/?probe=d85067b0f0) | Sep 11, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [a3b824ba41](https://linux-hardware.org/?probe=a3b824ba41) | Sep 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [66c2198f48](https://linux-hardware.org/?probe=66c2198f48) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [841be89be6](https://linux-hardware.org/?probe=841be89be6) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [626cf13c17](https://linux-hardware.org/?probe=626cf13c17) | Sep 10, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [4bb5badf61](https://linux-hardware.org/?probe=4bb5badf61) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | Desktop     | [6ce0fb28ee](https://linux-hardware.org/?probe=6ce0fb28ee) | Sep 10, 2022 |
| ASUSTek       | UX310UQK                    | Notebook    | [dc650f1d77](https://linux-hardware.org/?probe=dc650f1d77) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | Desktop     | [5cce5f5ade](https://linux-hardware.org/?probe=5cce5f5ade) | Sep 10, 2022 |
| ASUSTek       | B150 PRO GAMING             | Desktop     | [5e145ec2d1](https://linux-hardware.org/?probe=5e145ec2d1) | Sep 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [2cb423c8e7](https://linux-hardware.org/?probe=2cb423c8e7) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [8fb4287325](https://linux-hardware.org/?probe=8fb4287325) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [03979fc286](https://linux-hardware.org/?probe=03979fc286) | Sep 10, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [20ee71a4d6](https://linux-hardware.org/?probe=20ee71a4d6) | Sep 10, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | Notebook    | [0a7b65b735](https://linux-hardware.org/?probe=0a7b65b735) | Sep 09, 2022 |
| HP            | Elite x2 1013 G3            | Tablet      | [a7b40883c3](https://linux-hardware.org/?probe=a7b40883c3) | Sep 09, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [7fc528e246](https://linux-hardware.org/?probe=7fc528e246) | Sep 09, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [a54dae9e4b](https://linux-hardware.org/?probe=a54dae9e4b) | Sep 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [cada1ee58d](https://linux-hardware.org/?probe=cada1ee58d) | Sep 09, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [9f2534b22e](https://linux-hardware.org/?probe=9f2534b22e) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [c6dac06569](https://linux-hardware.org/?probe=c6dac06569) | Sep 09, 2022 |
| Notebook      | W230SS                      | Notebook    | [9ea483f3dd](https://linux-hardware.org/?probe=9ea483f3dd) | Sep 09, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3c454664b0](https://linux-hardware.org/?probe=3c454664b0) | Sep 09, 2022 |
| Biostar       | A780L3G                     | Desktop     | [e53730ab48](https://linux-hardware.org/?probe=e53730ab48) | Sep 09, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [7d9ebaa4f8](https://linux-hardware.org/?probe=7d9ebaa4f8) | Sep 09, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [e43ef549eb](https://linux-hardware.org/?probe=e43ef549eb) | Sep 08, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [ac6cb859ad](https://linux-hardware.org/?probe=ac6cb859ad) | Sep 08, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [174c263499](https://linux-hardware.org/?probe=174c263499) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [aeb2bae778](https://linux-hardware.org/?probe=aeb2bae778) | Sep 08, 2022 |
| Intel         | DH77DF AAG40293-300         | Desktop     | [217971d572](https://linux-hardware.org/?probe=217971d572) | Sep 08, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [daf3e0182b](https://linux-hardware.org/?probe=daf3e0182b) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [d5040ffbda](https://linux-hardware.org/?probe=d5040ffbda) | Sep 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [8242cc3cab](https://linux-hardware.org/?probe=8242cc3cab) | Sep 08, 2022 |
| HP            | 18E4                        | Desktop     | [1e8addf905](https://linux-hardware.org/?probe=1e8addf905) | Sep 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [30488e19df](https://linux-hardware.org/?probe=30488e19df) | Sep 08, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [dad38946f6](https://linux-hardware.org/?probe=dad38946f6) | Sep 08, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [0f0a18c852](https://linux-hardware.org/?probe=0f0a18c852) | Sep 08, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [e06271e233](https://linux-hardware.org/?probe=e06271e233) | Sep 08, 2022 |
| Dell          | Latitude E5450              | Notebook    | [305ef21301](https://linux-hardware.org/?probe=305ef21301) | Sep 08, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [051ea3b002](https://linux-hardware.org/?probe=051ea3b002) | Sep 08, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [46be1ea134](https://linux-hardware.org/?probe=46be1ea134) | Sep 08, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [bcf93bb718](https://linux-hardware.org/?probe=bcf93bb718) | Sep 08, 2022 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [0bcf279fb8](https://linux-hardware.org/?probe=0bcf279fb8) | Sep 08, 2022 |
| Dell          | Precision 5770              | Notebook    | [41e44b27f4](https://linux-hardware.org/?probe=41e44b27f4) | Sep 08, 2022 |
| Biostar       | H310MHP                     | Desktop     | [6063bede72](https://linux-hardware.org/?probe=6063bede72) | Sep 07, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [2395ab5aed](https://linux-hardware.org/?probe=2395ab5aed) | Sep 07, 2022 |
| ASUSTek       | H97-PRO                     | Desktop     | [fb4bfcf055](https://linux-hardware.org/?probe=fb4bfcf055) | Sep 07, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [bc21b4b2a8](https://linux-hardware.org/?probe=bc21b4b2a8) | Sep 07, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [f91eeba2bd](https://linux-hardware.org/?probe=f91eeba2bd) | Sep 07, 2022 |
| ASRock        | EP2C602                     | Desktop     | [56a6980ddc](https://linux-hardware.org/?probe=56a6980ddc) | Sep 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [dce2728dad](https://linux-hardware.org/?probe=dce2728dad) | Sep 07, 2022 |
| Dell          | Latitude E6420              | Notebook    | [8885f409d8](https://linux-hardware.org/?probe=8885f409d8) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [a90b385c8e](https://linux-hardware.org/?probe=a90b385c8e) | Sep 07, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [42b1a82f1d](https://linux-hardware.org/?probe=42b1a82f1d) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [7a3494a230](https://linux-hardware.org/?probe=7a3494a230) | Sep 07, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [673c26165e](https://linux-hardware.org/?probe=673c26165e) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [d3d092e789](https://linux-hardware.org/?probe=d3d092e789) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c905c86c47](https://linux-hardware.org/?probe=c905c86c47) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [424adc035f](https://linux-hardware.org/?probe=424adc035f) | Sep 07, 2022 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | Desktop     | [a816f4f60b](https://linux-hardware.org/?probe=a816f4f60b) | Sep 07, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e7d57afa70](https://linux-hardware.org/?probe=e7d57afa70) | Sep 06, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [240ace226f](https://linux-hardware.org/?probe=240ace226f) | Sep 06, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [01dbdc3b29](https://linux-hardware.org/?probe=01dbdc3b29) | Sep 06, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [ff127ee255](https://linux-hardware.org/?probe=ff127ee255) | Sep 06, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [7c202a088d](https://linux-hardware.org/?probe=7c202a088d) | Sep 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [826deb0c55](https://linux-hardware.org/?probe=826deb0c55) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [bffe658238](https://linux-hardware.org/?probe=bffe658238) | Sep 06, 2022 |
| Lenovo        | 3111 NOK                    | Mini pc     | [778f8bb16e](https://linux-hardware.org/?probe=778f8bb16e) | Sep 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [dad765ca9e](https://linux-hardware.org/?probe=dad765ca9e) | Sep 06, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [bcd73bee62](https://linux-hardware.org/?probe=bcd73bee62) | Sep 06, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [5f7f592f25](https://linux-hardware.org/?probe=5f7f592f25) | Sep 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b327372b50](https://linux-hardware.org/?probe=b327372b50) | Sep 05, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [e83fa739c9](https://linux-hardware.org/?probe=e83fa739c9) | Sep 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Fedora 36 | 1867      | 19.4%   |
| Fedora 35 | 1624      | 16.87%  |
| Fedora 34 | 1582      | 16.43%  |
| Fedora 33 | 1559      | 16.2%   |
| Fedora 32 | 1371      | 14.24%  |
| Fedora 31 | 910       | 9.45%   |
| Fedora 30 | 313       | 3.25%   |
| Fedora 29 | 171       | 1.78%   |
| Fedora 37 | 144       | 1.5%    |
| Fedora 28 | 42        | 0.44%   |
| Fedora 27 | 19        | 0.2%    |
| Fedora 24 | 6         | 0.06%   |
| Fedora 21 | 6         | 0.06%   |
| Fedora 38 | 5         | 0.05%   |
| Fedora 25 | 4         | 0.04%   |
| Fedora 4  | 1         | 0.01%   |
| Fedora 17 | 1         | 0.01%   |
| Fedora 14 | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Fedora | 8568      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.16.18-200.fc35.x86_64 | 162       | 1.49%   |
| 5.9.16-200.fc33.x86_64  | 159       | 1.46%   |
| 5.17.5-300.fc36.x86_64  | 154       | 1.41%   |
| 5.14.10-300.fc35.x86_64 | 127       | 1.17%   |
| 5.11.12-300.fc34.x86_64 | 120       | 1.1%    |
| 5.18.13-200.fc36.x86_64 | 112       | 1.03%   |
| 5.8.4-200.fc32.x86_64   | 101       | 0.93%   |
| 5.8.15-301.fc33.x86_64  | 100       | 0.92%   |
| 5.8.16-300.fc33.x86_64  | 97        | 0.89%   |
| 5.13.12-200.fc34.x86_64 | 96        | 0.88%   |
| 5.18.11-200.fc36.x86_64 | 90        | 0.83%   |
| 5.19.16-200.fc36.x86_64 | 87        | 0.8%    |
| 5.19.9-200.fc36.x86_64  | 86        | 0.79%   |
| 5.18.16-200.fc36.x86_64 | 84        | 0.77%   |
| 5.8.18-300.fc33.x86_64  | 81        | 0.74%   |
| 5.15.6-200.fc35.x86_64  | 78        | 0.72%   |
| 5.12.13-300.fc34.x86_64 | 78        | 0.72%   |
| 5.9.8-200.fc33.x86_64   | 77        | 0.71%   |
| 5.18.5-200.fc36.x86_64  | 75        | 0.69%   |
| 5.16.16-200.fc35.x86_64 | 75        | 0.69%   |
| 5.17.6-300.fc36.x86_64  | 74        | 0.68%   |
| 5.11.11-200.fc33.x86_64 | 73        | 0.67%   |
| 5.17.11-300.fc36.x86_64 | 72        | 0.66%   |
| 5.9.11-200.fc33.x86_64  | 71        | 0.65%   |
| 5.17.4-200.fc35.x86_64  | 71        | 0.65%   |
| 5.3.16-300.fc31.x86_64  | 68        | 0.62%   |
| 5.14.16-301.fc35.x86_64 | 68        | 0.62%   |
| 5.6.19-300.fc32.x86_64  | 66        | 0.61%   |
| 5.19.8-200.fc36.x86_64  | 66        | 0.61%   |
| 5.7.10-201.fc32.x86_64  | 65        | 0.6%    |
| 5.6.6-300.fc32.x86_64   | 65        | 0.6%    |
| 5.19.6-200.fc36.x86_64  | 65        | 0.6%    |
| 5.16.12-200.fc35.x86_64 | 63        | 0.58%   |
| 5.15.12-200.fc35.x86_64 | 62        | 0.57%   |
| 5.14.18-300.fc35.x86_64 | 62        | 0.57%   |
| 5.7.8-200.fc32.x86_64   | 61        | 0.56%   |
| 5.3.7-301.fc31.x86_64   | 60        | 0.55%   |
| 5.10.19-200.fc33.x86_64 | 60        | 0.55%   |
| 5.12.8-300.fc34.x86_64  | 59        | 0.54%   |
| 5.16.9-200.fc35.x86_64  | 58        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.5  | 208       | 1.91%   |
| 5.9.16  | 176       | 1.62%   |
| 5.16.18 | 174       | 1.6%    |
| 5.8.15  | 151       | 1.39%   |
| 5.14.10 | 138       | 1.27%   |
| 5.8.16  | 131       | 1.2%    |
| 5.11.12 | 130       | 1.2%    |
| 5.8.18  | 121       | 1.11%   |
| 5.11.11 | 119       | 1.09%   |
| 5.18.13 | 117       | 1.08%   |
| 5.19.16 | 111       | 1.02%   |
| 5.19.9  | 102       | 0.94%   |
| 5.13.12 | 102       | 0.94%   |
| 5.8.4   | 101       | 0.93%   |
| 5.18.11 | 94        | 0.86%   |
| 5.14.18 | 91        | 0.84%   |
| 5.18.16 | 89        | 0.82%   |
| 5.15.6  | 88        | 0.81%   |
| 5.9.8   | 86        | 0.79%   |
| 5.17.6  | 86        | 0.79%   |
| 5.19.8  | 85        | 0.78%   |
| 5.18.5  | 85        | 0.78%   |
| 5.17.11 | 84        | 0.77%   |
| 5.17.4  | 83        | 0.76%   |
| 5.12.13 | 83        | 0.76%   |
| 5.6.6   | 82        | 0.75%   |
| 5.14.16 | 81        | 0.74%   |
| 5.9.11  | 78        | 0.72%   |
| 5.16.16 | 78        | 0.72%   |
| 5.12.8  | 74        | 0.68%   |
| 5.19.6  | 73        | 0.67%   |
| 5.14.9  | 73        | 0.67%   |
| 5.15.12 | 72        | 0.66%   |
| 5.6.19  | 71        | 0.65%   |
| 5.16.12 | 71        | 0.65%   |
| 5.11.16 | 70        | 0.64%   |
| 5.3.16  | 69        | 0.63%   |
| 5.3.7   | 67        | 0.62%   |
| 5.10.19 | 66        | 0.61%   |
| 5.7.8   | 65        | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 843       | 8.13%   |
| 5.17    | 803       | 7.74%   |
| 5.11    | 787       | 7.59%   |
| 5.19    | 737       | 7.1%    |
| 5.18    | 729       | 7.03%   |
| 5.16    | 660       | 6.36%   |
| 5.14    | 650       | 6.27%   |
| 5.9     | 563       | 5.43%   |
| 5.10    | 546       | 5.26%   |
| 5.13    | 543       | 5.23%   |
| 5.15    | 526       | 5.07%   |
| 5.6     | 522       | 5.03%   |
| 5.12    | 506       | 4.88%   |
| 5.7     | 423       | 4.08%   |
| 5.3     | 330       | 3.18%   |
| 5.4     | 323       | 3.11%   |
| 5.5     | 319       | 3.08%   |
| 5.0     | 117       | 1.13%   |
| 5.2     | 110       | 1.06%   |
| 5.1     | 75        | 0.72%   |
| 6.0     | 63        | 0.61%   |
| 4.19    | 56        | 0.54%   |
| 4.18    | 49        | 0.47%   |
| 4.20    | 39        | 0.38%   |
| 4.16    | 9         | 0.09%   |
| 6.1     | 7         | 0.07%   |
| 4.15    | 6         | 0.06%   |
| 4.17    | 5         | 0.05%   |
| 4.14    | 5         | 0.05%   |
| 4.11    | 5         | 0.05%   |
| 4.1     | 4         | 0.04%   |
| 3.17    | 3         | 0.03%   |
| 4.8     | 2         | 0.02%   |
| 4.13    | 2         | 0.02%   |
| Unknown | 2         | 0.02%   |
| 4.5     | 1         | 0.01%   |
| 4.10    | 1         | 0.01%   |
| 3.9     | 1         | 0.01%   |
| 2.6.35  | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 8535      | 99.59%  |
| aarch64 | 20        | 0.23%   |
| i686    | 8         | 0.09%   |
| armv7l  | 5         | 0.06%   |
| Unknown | 2         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 6262      | 70.95%  |
| KDE5            | 888       | 10.06%  |
| Unknown         | 598       | 6.78%   |
| KDE             | 268       | 3.04%   |
| XFCE            | 193       | 2.19%   |
| X-Cinnamon      | 142       | 1.61%   |
| Cinnamon        | 132       | 1.5%    |
| MATE            | 130       | 1.47%   |
| GNOME Classic   | 43        | 0.49%   |
| LXQt            | 32        | 0.36%   |
| i3              | 31        | 0.35%   |
| LXDE            | 24        | 0.27%   |
| Deepin          | 24        | 0.27%   |
| sway            | 12        | 0.14%   |
| KDE4            | 10        | 0.11%   |
| awesome         | 7         | 0.08%   |
| openbox         | 5         | 0.06%   |
| Pantheon        | 4         | 0.05%   |
| DWM             | 4         | 0.05%   |
| Budgie          | 4         | 0.05%   |
| GNOME Flashback | 3         | 0.03%   |
| fluxbox         | 3         | 0.03%   |
| bspwm           | 2         | 0.02%   |
| xinit-compat    | 1         | 0.01%   |
| qtile           | 1         | 0.01%   |
| NsCDE           | 1         | 0.01%   |
| KDE:old         | 1         | 0.01%   |
| GNUstep         | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 5127      | 57.36%  |
| X11     | 3268      | 36.56%  |
| Unknown | 347       | 3.88%   |
| Tty     | 191       | 2.14%   |
| Web     | 6         | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4601      | 52.19%  |
| GDM     | 3073      | 34.86%  |
| SDDM    | 611       | 6.93%   |
| LightDM | 321       | 3.64%   |
| TDM     | 169       | 1.92%   |
| XDM     | 18        | 0.2%    |
| KDM     | 14        | 0.16%   |
| LXDM    | 6         | 0.07%   |
| SLiM    | 2         | 0.02%   |
| Ly      | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 4311      | 49.29%  |
| Unknown | 656       | 7.5%    |
| en_GB   | 600       | 6.86%   |
| pt_BR   | 400       | 4.57%   |
| ru_RU   | 349       | 3.99%   |
| de_DE   | 340       | 3.89%   |
| fr_FR   | 262       | 3%      |
| it_IT   | 219       | 2.5%    |
| en_CA   | 177       | 2.02%   |
| en_AU   | 162       | 1.85%   |
| pl_PL   | 128       | 1.46%   |
| es_ES   | 125       | 1.43%   |
| en_IN   | 79        | 0.9%    |
| es_MX   | 66        | 0.75%   |
| cs_CZ   | 62        | 0.71%   |
| en_NZ   | 43        | 0.49%   |
| es_AR   | 42        | 0.48%   |
| nl_NL   | 38        | 0.43%   |
| es_CL   | 33        | 0.38%   |
| hu_HU   | 31        | 0.35%   |
| sv_SE   | 30        | 0.34%   |
| zh_CN   | 28        | 0.32%   |
| tr_TR   | 28        | 0.32%   |
| C       | 28        | 0.32%   |
| es_CO   | 26        | 0.3%    |
| de_AT   | 25        | 0.29%   |
| en_IE   | 24        | 0.27%   |
| en_DK   | 24        | 0.27%   |
| pt_PT   | 22        | 0.25%   |
| fi_FI   | 21        | 0.24%   |
| ru_UA   | 19        | 0.22%   |
| uk_UA   | 18        | 0.21%   |
| nl_BE   | 18        | 0.21%   |
| fr_CA   | 18        | 0.21%   |
| ja_JP   | 16        | 0.18%   |
| sk_SK   | 15        | 0.17%   |
| en_ZA   | 14        | 0.16%   |
| nb_NO   | 13        | 0.15%   |
| fr_BE   | 13        | 0.15%   |
| de_CH   | 13        | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 6378      | 73.39%  |
| BIOS | 2312      | 26.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Btrfs               | 4544      | 51.59%  |
| Ext4                | 3550      | 40.3%   |
| Unknown             | 348       | 3.95%   |
| Xfs                 | 335       | 3.8%    |
| Overlay             | 13        | 0.15%   |
| Zfs                 | 6         | 0.07%   |
| Ext3                | 5         | 0.06%   |
| Fuse.fuse-overlayfs | 4         | 0.05%   |
| F2fs                | 3         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4535      | 51.62%  |
| GPT     | 3524      | 40.11%  |
| MBR     | 726       | 8.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7712      | 88.5%   |
| Yes       | 1002      | 11.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7007      | 80.56%  |
| Yes       | 1691      | 19.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 1774      | 20.7%   |
| ASUSTek Computer        | 1352      | 15.78%  |
| Dell                    | 1185      | 13.83%  |
| Hewlett-Packard         | 1039      | 12.13%  |
| Gigabyte Technology     | 604       | 7.05%   |
| MSI                     | 534       | 6.23%   |
| Acer                    | 370       | 4.32%   |
| ASRock                  | 303       | 3.54%   |
| Apple                   | 200       | 2.33%   |
| Intel                   | 104       | 1.21%   |
| HUAWEI                  | 90        | 1.05%   |
| Samsung Electronics     | 74        | 0.86%   |
| Toshiba                 | 72        | 0.84%   |
| Unknown                 | 65        | 0.76%   |
| Sony                    | 46        | 0.54%   |
| Notebook                | 43        | 0.5%    |
| Microsoft               | 43        | 0.5%    |
| Fujitsu                 | 35        | 0.41%   |
| Timi                    | 29        | 0.34%   |
| Positivo                | 28        | 0.33%   |
| Alienware               | 26        | 0.3%    |
| Supermicro              | 25        | 0.29%   |
| Framework               | 25        | 0.29%   |
| System76                | 20        | 0.23%   |
| LG Electronics          | 18        | 0.21%   |
| Pegatron                | 16        | 0.19%   |
| Biostar                 | 16        | 0.19%   |
| BESSTAR Tech            | 16        | 0.19%   |
| Google                  | 15        | 0.18%   |
| ECS                     | 15        | 0.18%   |
| Chuwi                   | 15        | 0.18%   |
| Razer                   | 14        | 0.16%   |
| Raspberry Pi Foundation | 14        | 0.16%   |
| TUXEDO                  | 12        | 0.14%   |
| Medion                  | 12        | 0.14%   |
| Foxconn                 | 10        | 0.12%   |
| AMI                     | 10        | 0.12%   |
| Packard Bell            | 9         | 0.11%   |
| Huanan                  | 9         | 0.11%   |
| AZW                     | 9         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 89        | 1.04%   |
| Unknown                                    | 84        | 0.98%   |
| MSI MS-7C37                                | 32        | 0.37%   |
| HP Notebook                                | 26        | 0.3%    |
| Gigabyte B450M DS3H                        | 23        | 0.27%   |
| Framework Laptop                           | 22        | 0.26%   |
| Dell XPS 15 7590                           | 21        | 0.25%   |
| Dell XPS 13 9370                           | 21        | 0.25%   |
| Dell XPS 15 9570                           | 20        | 0.23%   |
| ASUS TUF Gaming X570-PLUS                  | 20        | 0.23%   |
| Dell XPS 13 9360                           | 19        | 0.22%   |
| MSI MS-7C02                                | 18        | 0.21%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2          | 18        | 0.21%   |
| Dell XPS 15 9560                           | 18        | 0.21%   |
| Dell Latitude 7490                         | 18        | 0.21%   |
| HP EliteBook 840 G6                        | 17        | 0.2%    |
| MSI MS-7B86                                | 16        | 0.19%   |
| MSI MS-7A38                                | 16        | 0.19%   |
| HP Pavilion dv6                            | 16        | 0.19%   |
| Dell XPS 13 7390                           | 15        | 0.18%   |
| Dell Latitude E7450                        | 15        | 0.18%   |
| MSI MS-7C91                                | 14        | 0.16%   |
| HP Pavilion 15                             | 14        | 0.16%   |
| Dell XPS 15 9550                           | 14        | 0.16%   |
| Dell XPS 15 9500                           | 14        | 0.16%   |
| Dell XPS 13 9310                           | 14        | 0.16%   |
| ASUS ROG STRIX B550-F GAMING               | 14        | 0.16%   |
| ASUS PRIME X370-PRO                        | 14        | 0.16%   |
| MSI MS-7C84                                | 13        | 0.15%   |
| MSI MS-7B79                                | 13        | 0.15%   |
| Dell Latitude 5480                         | 13        | 0.15%   |
| MSI MS-7C56                                | 12        | 0.14%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 12        | 0.14%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 12        | 0.14%   |
| HP Pavilion Notebook                       | 12        | 0.14%   |
| HP ENVY x360 Convertible 13-ay0xxx         | 12        | 0.14%   |
| Dell Inspiron 5570                         | 12        | 0.14%   |
| Dell Inspiron 15 7000 Gaming               | 12        | 0.14%   |
| ASUS ROG STRIX X570-F GAMING               | 12        | 0.14%   |
| ASUS ROG STRIX B550-I GAMING               | 12        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 973       | 11.36%  |
| Lenovo IdeaPad     | 312       | 3.64%   |
| Dell Inspiron      | 312       | 3.64%   |
| Dell Latitude      | 275       | 3.21%   |
| Dell XPS           | 256       | 2.99%   |
| ASUS ROG           | 248       | 2.89%   |
| Acer Aspire        | 233       | 2.72%   |
| HP Pavilion        | 183       | 2.14%   |
| ASUS PRIME         | 160       | 1.87%   |
| HP EliteBook       | 156       | 1.82%   |
| HP ProBook         | 124       | 1.45%   |
| Dell Precision     | 117       | 1.37%   |
| ASUS TUF           | 111       | 1.3%    |
| Lenovo Yoga        | 107       | 1.25%   |
| Dell OptiPlex      | 105       | 1.23%   |
| HP Laptop          | 96        | 1.12%   |
| HP ENVY            | 90        | 1.05%   |
| ASUS All           | 89        | 1.04%   |
| Unknown            | 84        | 0.98%   |
| ASUS VivoBook      | 83        | 0.97%   |
| Toshiba Satellite  | 61        | 0.71%   |
| Lenovo ThinkCentre | 61        | 0.71%   |
| Lenovo Legion      | 58        | 0.68%   |
| Gigabyte X570      | 56        | 0.65%   |
| Dell Vostro        | 47        | 0.55%   |
| Lenovo ThinkBook   | 45        | 0.53%   |
| HP Compaq          | 45        | 0.53%   |
| Microsoft Surface  | 43        | 0.5%    |
| HP ZBook           | 43        | 0.5%    |
| Gigabyte B450      | 40        | 0.47%   |
| ASUS ZenBook       | 39        | 0.46%   |
| Lenovo IdeaPadFlex | 38        | 0.44%   |
| ASUS ASUS          | 35        | 0.41%   |
| Acer Swift         | 35        | 0.41%   |
| Acer Nitro         | 35        | 0.41%   |
| HP EliteDesk       | 34        | 0.4%    |
| Gigabyte B450M     | 34        | 0.4%    |
| MSI MS-7C37        | 32        | 0.37%   |
| HP Spectre         | 29        | 0.34%   |
| HP Notebook        | 26        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1165      | 13.6%   |
| 2020    | 1112      | 12.98%  |
| 2018    | 1071      | 12.5%   |
| 2017    | 764       | 8.92%   |
| 2021    | 685       | 7.99%   |
| 2012    | 531       | 6.2%    |
| 2015    | 530       | 6.19%   |
| 2016    | 515       | 6.01%   |
| 2013    | 514       | 6%      |
| 2014    | 479       | 5.59%   |
| 2011    | 417       | 4.87%   |
| 2010    | 235       | 2.74%   |
| 2009    | 164       | 1.91%   |
| 2008    | 153       | 1.79%   |
| 2022    | 143       | 1.67%   |
| 2007    | 53        | 0.62%   |
| 2006    | 20        | 0.23%   |
| Unknown | 12        | 0.14%   |
| 2005    | 4         | 0.05%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4899      | 57.18%  |
| Desktop        | 2917      | 34.05%  |
| Convertible    | 368       | 4.3%    |
| Tablet         | 116       | 1.35%   |
| Mini pc        | 115       | 1.34%   |
| All in one     | 94        | 1.1%    |
| Server         | 37        | 0.43%   |
| System on chip | 22        | 0.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 7365      | 84.83%  |
| Enabled  | 1317      | 15.17%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8538      | 99.65%  |
| Yes  | 30        | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 2287      | 26.25%  |
| 4.01-8.0        | 2059      | 23.63%  |
| 8.01-16.0       | 1634      | 18.75%  |
| 32.01-64.0      | 1255      | 14.4%   |
| 3.01-4.0        | 783       | 8.99%   |
| 64.01-256.0     | 308       | 3.53%   |
| 24.01-32.0      | 174       | 2%      |
| 1.01-2.0        | 144       | 1.65%   |
| 2.01-3.0        | 40        | 0.46%   |
| 0.51-1.0        | 18        | 0.21%   |
| Unknown         | 6         | 0.07%   |
| More than 256.0 | 5         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 2675      | 27.42%  |
| 4.01-8.0    | 2577      | 26.42%  |
| 3.01-4.0    | 1991      | 20.41%  |
| 1.01-2.0    | 1427      | 14.63%  |
| 8.01-16.0   | 755       | 7.74%   |
| 0.51-1.0    | 140       | 1.44%   |
| 16.01-24.0  | 107       | 1.1%    |
| 24.01-32.0  | 34        | 0.35%   |
| 0.01-0.5    | 21        | 0.22%   |
| 32.01-64.0  | 16        | 0.16%   |
| Unknown     | 8         | 0.08%   |
| 64.01-256.0 | 3         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4983      | 56.32%  |
| 2       | 2294      | 25.93%  |
| 3       | 795       | 8.99%   |
| 4       | 362       | 4.09%   |
| 5       | 175       | 1.98%   |
| 6       | 92        | 1.04%   |
| 7       | 47        | 0.53%   |
| 0       | 45        | 0.51%   |
| 8       | 23        | 0.26%   |
| 9       | 11        | 0.12%   |
| 10      | 6         | 0.07%   |
| 11      | 4         | 0.05%   |
| 36      | 2         | 0.02%   |
| 14      | 2         | 0.02%   |
| 12      | 2         | 0.02%   |
| 27      | 1         | 0.01%   |
| 24      | 1         | 0.01%   |
| 15      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 6332      | 73.37%  |
| Yes       | 2298      | 26.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6973      | 80.99%  |
| No        | 1637      | 19.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6834      | 79.28%  |
| No        | 1786      | 20.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5884      | 67.73%  |
| No        | 2803      | 32.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 1766      | 20.44%  |
| Germany     | 629       | 7.28%   |
| Brazil      | 603       | 6.98%   |
| Russia      | 516       | 5.97%   |
| Italy       | 370       | 4.28%   |
| France      | 341       | 3.95%   |
| UK          | 319       | 3.69%   |
| Canada      | 294       | 3.4%    |
| India       | 246       | 2.85%   |
| Poland      | 236       | 2.73%   |
| Netherlands | 224       | 2.59%   |
| Spain       | 206       | 2.38%   |
| Australia   | 192       | 2.22%   |
| Czechia     | 148       | 1.71%   |
| Sweden      | 126       | 1.46%   |
| Mexico      | 124       | 1.44%   |
| Switzerland | 110       | 1.27%   |
| Austria     | 105       | 1.22%   |
| Turkey      | 98        | 1.13%   |
| Ukraine     | 94        | 1.09%   |
| Belgium     | 91        | 1.05%   |
| Argentina   | 82        | 0.95%   |
| Norway      | 80        | 0.93%   |
| Finland     | 79        | 0.91%   |
| Romania     | 77        | 0.89%   |
| Hungary     | 67        | 0.78%   |
| Portugal    | 66        | 0.76%   |
| Indonesia   | 62        | 0.72%   |
| Chile       | 56        | 0.65%   |
| Denmark     | 54        | 0.62%   |
| New Zealand | 50        | 0.58%   |
| China       | 50        | 0.58%   |
| Greece      | 46        | 0.53%   |
| Colombia    | 43        | 0.5%    |
| Slovakia    | 41        | 0.47%   |
| Japan       | 41        | 0.47%   |
| Belarus     | 39        | 0.45%   |
| Israel      | 37        | 0.43%   |
| Iran        | 37        | 0.43%   |
| Bulgaria    | 36        | 0.42%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 161       | 1.75%   |
| Sao Paulo      | 77        | 0.84%   |
| St Petersburg  | 74        | 0.8%    |
| Berlin         | 70        | 0.76%   |
| Sydney         | 68        | 0.74%   |
| Vienna         | 67        | 0.73%   |
| Warsaw         | 61        | 0.66%   |
| Paris          | 60        | 0.65%   |
| Prague         | 57        | 0.62%   |
| Milan          | 52        | 0.56%   |
| Amsterdam      | 52        | 0.56%   |
| Istanbul       | 48        | 0.52%   |
| Munich         | 42        | 0.46%   |
| Madrid         | 42        | 0.46%   |
| Melbourne      | 41        | 0.45%   |
| Helsinki       | 39        | 0.42%   |
| Oslo           | 38        | 0.41%   |
| Hamburg        | 37        | 0.4%    |
| Brisbane       | 37        | 0.4%    |
| Zurich         | 35        | 0.38%   |
| Rome           | 35        | 0.38%   |
| Rio de Janeiro | 35        | 0.38%   |
| Bengaluru      | 34        | 0.37%   |
| Toronto        | 33        | 0.36%   |
| Mexico City    | 33        | 0.36%   |
| Budapest       | 32        | 0.35%   |
| Montreal       | 31        | 0.34%   |
| Buenos Aires   | 30        | 0.33%   |
| Kyiv           | 29        | 0.31%   |
| Denver         | 29        | 0.31%   |
| Bucharest      | 29        | 0.31%   |
| Athens         | 29        | 0.31%   |
| Auckland       | 28        | 0.3%    |
| Portland       | 26        | 0.28%   |
| Los Angeles    | 26        | 0.28%   |
| Krakow         | 26        | 0.28%   |
| Delft          | 26        | 0.28%   |
| Chicago        | 26        | 0.28%   |
| Brno           | 26        | 0.28%   |
| Seattle        | 25        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 2605      | 4332   | 19.87%  |
| WDC                       | 1853      | 3052   | 14.14%  |
| Seagate                   | 1577      | 2622   | 12.03%  |
| Toshiba                   | 813       | 1110   | 6.2%    |
| SanDisk                   | 756       | 1005   | 5.77%   |
| Kingston                  | 726       | 1008   | 5.54%   |
| Crucial                   | 517       | 739    | 3.94%   |
| Unknown                   | 495       | 701    | 3.78%   |
| Intel                     | 452       | 688    | 3.45%   |
| SK hynix                  | 450       | 562    | 3.43%   |
| Hitachi                   | 242       | 358    | 1.85%   |
| Micron Technology         | 216       | 295    | 1.65%   |
| HGST                      | 207       | 328    | 1.58%   |
| A-DATA Technology         | 207       | 267    | 1.58%   |
| Phison                    | 153       | 201    | 1.17%   |
| KIOXIA                    | 106       | 168    | 0.81%   |
| Apple                     | 104       | 125    | 0.79%   |
| LITEON                    | 84        | 92     | 0.64%   |
| China                     | 74        | 88     | 0.56%   |
| SPCC                      | 72        | 104    | 0.55%   |
| Silicon Motion            | 72        | 98     | 0.55%   |
| Corsair                   | 66        | 93     | 0.5%    |
| Transcend                 | 61        | 86     | 0.47%   |
| PNY                       | 61        | 82     | 0.47%   |
| Micron/Crucial Technology | 52        | 67     | 0.4%    |
| OCZ                       | 49        | 62     | 0.37%   |
| Patriot                   | 48        | 70     | 0.37%   |
| XPG                       | 44        | 64     | 0.34%   |
| Team                      | 32        | 45     | 0.24%   |
| LITEONIT                  | 32        | 40     | 0.24%   |
| Hewlett-Packard           | 32        | 36     | 0.24%   |
| Intenso                   | 29        | 39     | 0.22%   |
| Gigabyte Technology       | 28        | 43     | 0.21%   |
| Unknown                   | 28        | 30     | 0.21%   |
| GOODRAM                   | 27        | 35     | 0.21%   |
| Plextor                   | 26        | 34     | 0.2%    |
| Maxtor                    | 26        | 31     | 0.2%    |
| JMicron Technology        | 25        | 36     | 0.19%   |
| KingSpec                  | 24        | 33     | 0.18%   |
| Realtek Semiconductor     | 22        | 28     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB              | 148       | 1%      |
| Samsung NVMe SSD Drive 512GB           | 148       | 1%      |
| Samsung SSD 860 EVO 500GB              | 142       | 0.96%   |
| Kingston SA400S37240G 240GB SSD        | 140       | 0.95%   |
| Samsung NVMe SSD Drive 500GB           | 131       | 0.88%   |
| Samsung NVMe SSD Drive 1TB             | 119       | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB         | 118       | 0.8%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 115       | 0.78%   |
| Samsung SSD 850 EVO 500GB              | 114       | 0.77%   |
| Samsung SSD 860 EVO 1TB                | 106       | 0.72%   |
| SanDisk NVMe SSD Drive 512GB           | 90        | 0.61%   |
| Kingston SA400S37480G 480GB SSD        | 88        | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 86        | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB         | 80        | 0.54%   |
| Kingston SA400S37120G 120GB SSD        | 79        | 0.53%   |
| HGST HTS721010A9E630 1TB               | 77        | 0.52%   |
| Unknown MMC Card  32GB                 | 73        | 0.49%   |
| Crucial CT500MX500SSD1 500GB           | 73        | 0.49%   |
| Seagate ST2000DM008-2FR102 2TB         | 72        | 0.49%   |
| Samsung NVMe SSD Drive 1024GB          | 70        | 0.47%   |
| Intel NVMe SSD Drive 512GB             | 69        | 0.47%   |
| Samsung SSD 860 EVO 250GB              | 67        | 0.45%   |
| Seagate ST500DM002-1BD142 500GB        | 66        | 0.45%   |
| Toshiba MQ01ABD100 1TB                 | 64        | 0.43%   |
| Unknown MMC Card  64GB                 | 61        | 0.41%   |
| SK hynix NVMe SSD Drive 512GB          | 61        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB            | 61        | 0.41%   |
| Samsung SSD 970 EVO Plus 500GB         | 60        | 0.41%   |
| WDC WD10EZEX-08WN4A0 1TB               | 58        | 0.39%   |
| Toshiba DT01ACA100 1TB                 | 58        | 0.39%   |
| SanDisk NVMe SSD Drive 500GB           | 58        | 0.39%   |
| SanDisk NVMe SSD Drive 1TB             | 58        | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB           | 58        | 0.39%   |
| SanDisk NVMe SSD Drive 256GB           | 53        | 0.36%   |
| Crucial CT240BX500SSD1 240GB           | 51        | 0.34%   |
| Toshiba MQ04ABF100 1TB                 | 50        | 0.34%   |
| Kingston SV300S37A120G 120GB SSD       | 49        | 0.33%   |
| Toshiba NVMe SSD Drive 256GB           | 48        | 0.32%   |
| Seagate Expansion 2TB                  | 48        | 0.32%   |
| Toshiba NVMe SSD Drive 512GB           | 47        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1528      | 2531   | 37.13%  |
| WDC                 | 1336      | 2289   | 32.47%  |
| Toshiba             | 479       | 666    | 11.64%  |
| Hitachi             | 242       | 358    | 5.88%   |
| HGST                | 206       | 327    | 5.01%   |
| Samsung Electronics | 135       | 213    | 3.28%   |
| Unknown             | 39        | 52     | 0.95%   |
| Apple               | 27        | 29     | 0.66%   |
| Maxtor              | 22        | 25     | 0.53%   |
| Fujitsu             | 20        | 22     | 0.49%   |
| SABRENT             | 18        | 20     | 0.44%   |
| ASMT                | 8         | 9      | 0.19%   |
| Hewlett-Packard     | 6         | 7      | 0.15%   |
| USB3.0              | 5         | 5      | 0.12%   |
| JMicron Technology  | 5         | 11     | 0.12%   |
| LIO-ORG             | 4         | 21     | 0.1%    |
| Inateck             | 4         | 9      | 0.1%    |
| MaxDigital          | 3         | 3      | 0.07%   |
| LaCie               | 3         | 6      | 0.07%   |
| Intenso             | 3         | 6      | 0.07%   |
| USB                 | 2         | 2      | 0.05%   |
| External            | 2         | 2      | 0.05%   |
| ASMT109x            | 2         | 2      | 0.05%   |
| USB 3.0             | 1         | 3      | 0.02%   |
| Unknown (583)       | 1         | 1      | 0.02%   |
| Synology            | 1         | 1      | 0.02%   |
| SAGE                | 1         | 1      | 0.02%   |
| RSH-339             | 1         | 1      | 0.02%   |
| Phison              | 1         | 2      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| Magnetic Data       | 1         | 1      | 0.02%   |
| KESU                | 1         | 1      | 0.02%   |
| IB-AC703            | 1         | 1      | 0.02%   |
| HGST HTS            | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| ExcelStor           | 1         | 1      | 0.02%   |
| ASMT106x            | 1         | 2      | 0.02%   |
| Unknown             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1244      | 2014   | 27.38%  |
| Kingston            | 570       | 800    | 12.54%  |
| Crucial             | 465       | 675    | 10.23%  |
| SanDisk             | 403       | 550    | 8.87%   |
| WDC                 | 276       | 373    | 6.07%   |
| A-DATA Technology   | 160       | 212    | 3.52%   |
| Intel               | 159       | 265    | 3.5%    |
| Micron Technology   | 97        | 125    | 2.13%   |
| SK hynix            | 78        | 92     | 1.72%   |
| Toshiba             | 73        | 93     | 1.61%   |
| China               | 73        | 87     | 1.61%   |
| LITEON              | 71        | 79     | 1.56%   |
| PNY                 | 60        | 79     | 1.32%   |
| SPCC                | 59        | 83     | 1.3%    |
| Apple               | 58        | 67     | 1.28%   |
| Transcend           | 54        | 75     | 1.19%   |
| OCZ                 | 48        | 61     | 1.06%   |
| Patriot             | 43        | 63     | 0.95%   |
| Corsair             | 39        | 54     | 0.86%   |
| LITEONIT            | 32        | 40     | 0.7%    |
| Team                | 26        | 39     | 0.57%   |
| GOODRAM             | 26        | 34     | 0.57%   |
| Seagate             | 23        | 26     | 0.51%   |
| KingSpec            | 23        | 31     | 0.51%   |
| Intenso             | 23        | 30     | 0.51%   |
| Plextor             | 22        | 29     | 0.48%   |
| Gigabyte Technology | 20        | 29     | 0.44%   |
| Unknown             | 17        | 17     | 0.37%   |
| Hewlett-Packard     | 16        | 18     | 0.35%   |
| Lexar               | 14        | 22     | 0.31%   |
| Apacer              | 14        | 20     | 0.31%   |
| KingDian            | 13        | 14     | 0.29%   |
| Netac               | 12        | 12     | 0.26%   |
| Mushkin             | 12        | 24     | 0.26%   |
| ASMT                | 12        | 13     | 0.26%   |
| Leven               | 10        | 11     | 0.22%   |
| Verbatim            | 8         | 9      | 0.18%   |
| Unknown             | 8         | 9      | 0.18%   |
| Dogfish             | 7         | 9      | 0.15%   |
| Drevo               | 6         | 8      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 3901      | 6519   | 33.25%  |
| NVMe    | 3843      | 5729   | 32.75%  |
| HDD     | 3407      | 6635   | 29.04%  |
| MMC     | 426       | 617    | 3.63%   |
| Unknown | 157       | 233    | 1.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5646      | 12652  | 54.32%  |
| NVMe | 3835      | 5705   | 36.9%   |
| SAS  | 487       | 759    | 4.69%   |
| MMC  | 426       | 617    | 4.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4083      | 7016   | 52.19%  |
| 0.51-1.0   | 2460      | 3855   | 31.44%  |
| 1.01-2.0   | 696       | 1125   | 8.9%    |
| 3.01-4.0   | 260       | 465    | 3.32%   |
| 2.01-3.0   | 155       | 299    | 1.98%   |
| 4.01-10.0  | 143       | 349    | 1.83%   |
| 10.01-20.0 | 26        | 43     | 0.33%   |
| 0          | 1         | 2      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 1800      | 19.85%  |
| 501-1000       | 1764      | 19.45%  |
| 101-250        | 1617      | 17.83%  |
| 1001-2000      | 1117      | 12.32%  |
| 1-20           | 760       | 8.38%   |
| More than 3000 | 589       | 6.5%    |
| Unknown        | 522       | 5.76%   |
| 2001-3000      | 368       | 4.06%   |
| 51-100         | 350       | 3.86%   |
| 21-50          | 181       | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2414      | 25.39%  |
| 21-50          | 1529      | 16.08%  |
| 101-250        | 1439      | 15.14%  |
| 51-100         | 1205      | 12.68%  |
| 251-500        | 973       | 10.24%  |
| 501-1000       | 719       | 7.56%   |
| Unknown        | 522       | 5.49%   |
| 1001-2000      | 391       | 4.11%   |
| More than 3000 | 180       | 1.89%   |
| 2001-3000      | 132       | 1.39%   |
| 0              | 2         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                | 14        | 35     | 2%      |
| Seagate ST500LT012-1DG142 500GB                | 12        | 12     | 1.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 10        | 19     | 1.43%   |
| HGST HTS721010A9E630 1TB                       | 8         | 11     | 1.14%   |
| HGST HTS545050A7E680 500GB                     | 8         | 8      | 1.14%   |
| Toshiba MQ01ABD100 1TB                         | 7         | 7      | 1%      |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 7      | 1%      |
| Seagate ST9500325AS 500GB                      | 6         | 8      | 0.86%   |
| Seagate ST3500418AS 500GB                      | 6         | 11     | 0.86%   |
| Seagate ST31000528AS 1TB                       | 6         | 8      | 0.86%   |
| HGST HTS541010A9E680 1TB                       | 6         | 6      | 0.86%   |
| Toshiba MQ01ABD050 500GB                       | 5         | 6      | 0.72%   |
| Seagate ST1000DM010-2EP102 1TB                 | 5         | 5      | 0.72%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 5         | 5      | 0.72%   |
| Intel SSDSC2CT120A3 120GB                      | 5         | 19     | 0.72%   |
| Hitachi HTS547575A9E384 752GB                  | 5         | 7      | 0.72%   |
| WDC WD10EZEX-08WN4A0 1TB                       | 4         | 4      | 0.57%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 4         | 4      | 0.57%   |
| Toshiba MQ01ABD075 752GB                       | 4         | 4      | 0.57%   |
| Seagate ST500LM021-1KJ152 500GB                | 4         | 5      | 0.57%   |
| Seagate ST31500341AS 1TB                       | 4         | 4      | 0.57%   |
| Seagate ST31000524AS 1TB                       | 4         | 4      | 0.57%   |
| Samsung Electronics SSD 870 EVO 1TB            | 4         | 4      | 0.57%   |
| Samsung Electronics HD501LJ 500GB              | 4         | 25     | 0.57%   |
| Samsung Electronics HD322HJ 320GB              | 4         | 4      | 0.57%   |
| Kingston SV300S37A120G 120GB SSD               | 4         | 4      | 0.57%   |
| Hitachi HTS545050B9A300 500GB                  | 4         | 4      | 0.57%   |
| Crucial CT128MX100SSD1 128GB                   | 4         | 6      | 0.57%   |
| WDC WD1002FAEX-00Z3A0 1TB                      | 3         | 3      | 0.43%   |
| Toshiba MK3275GSX 320GB                        | 3         | 3      | 0.43%   |
| Toshiba DT01ACA100 1TB                         | 3         | 3      | 0.43%   |
| Seagate ST9750420AS 752GB                      | 3         | 3      | 0.43%   |
| Seagate ST9500420AS 500GB                      | 3         | 4      | 0.43%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 3         | 3      | 0.43%   |
| Seagate ST3000DM001-1ER166 3TB                 | 3         | 6      | 0.43%   |
| Seagate ST2000DM001-1CH164 2TB                 | 3         | 3      | 0.43%   |
| SanDisk SSD PLUS 240GB                         | 3         | 3      | 0.43%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD            | 3         | 3      | 0.43%   |
| Samsung Electronics SSD 870 EVO 500GB          | 3         | 5      | 0.43%   |
| Samsung Electronics HM160HI 160GB              | 3         | 6      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 166       | 248    | 24.59%  |
| WDC                 | 132       | 190    | 19.56%  |
| Samsung Electronics | 55        | 84     | 8.15%   |
| Hitachi             | 54        | 70     | 8%      |
| Toshiba             | 51        | 56     | 7.56%   |
| Intel               | 32        | 60     | 4.74%   |
| HGST                | 30        | 37     | 4.44%   |
| Crucial             | 25        | 32     | 3.7%    |
| SanDisk             | 22        | 23     | 3.26%   |
| Kingston            | 15        | 16     | 2.22%   |
| SK hynix            | 12        | 13     | 1.78%   |
| Micron Technology   | 12        | 15     | 1.78%   |
| A-DATA Technology   | 12        | 12     | 1.78%   |
| LITEON              | 8         | 8      | 1.19%   |
| Maxtor              | 6         | 6      | 0.89%   |
| Fujitsu             | 5         | 5      | 0.74%   |
| Corsair             | 5         | 8      | 0.74%   |
| OCZ                 | 4         | 5      | 0.59%   |
| SPCC                | 3         | 4      | 0.44%   |
| OCZ-VERTEX3         | 3         | 3      | 0.44%   |
| Unknown             | 2         | 2      | 0.3%    |
| LITEONIT            | 2         | 3      | 0.3%    |
| walram              | 1         | 1      | 0.15%   |
| Verbatim            | 1         | 1      | 0.15%   |
| Union Memory        | 1         | 1      | 0.15%   |
| Teclast             | 1         | 1      | 0.15%   |
| Team                | 1         | 4      | 0.15%   |
| SSD                 | 1         | 1      | 0.15%   |
| PNY                 | 1         | 1      | 0.15%   |
| Plextor             | 1         | 1      | 0.15%   |
| Origin              | 1         | 1      | 0.15%   |
| ORICO               | 1         | 1      | 0.15%   |
| Lenovo              | 1         | 2      | 0.15%   |
| KingDian            | 1         | 1      | 0.15%   |
| Hewlett-Packard     | 1         | 1      | 0.15%   |
| China               | 1         | 1      | 0.15%   |
| BIWIN               | 1         | 1      | 0.15%   |
| ASMT                | 1         | 1      | 0.15%   |
| ASMedia             | 1         | 1      | 0.15%   |
| Apple               | 1         | 1      | 0.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 166       | 248    | 35.39%  |
| WDC                 | 130       | 188    | 27.72%  |
| Hitachi             | 54        | 70     | 11.51%  |
| Toshiba             | 50        | 55     | 10.66%  |
| HGST                | 30        | 37     | 6.4%    |
| Samsung Electronics | 25        | 50     | 5.33%   |
| Maxtor              | 6         | 6      | 1.28%   |
| Fujitsu             | 5         | 5      | 1.07%   |
| Hewlett-Packard     | 1         | 1      | 0.21%   |
| ASMT                | 1         | 1      | 0.21%   |
| Apple               | 1         | 1      | 0.21%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 438       | 662    | 68.22%  |
| SSD  | 175       | 228    | 27.26%  |
| NVMe | 29        | 33     | 4.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB    | 2         | 3      | 18.18%  |
| WDC WD5000BEVT-00ZAT0 500GB          | 1         | 2      | 9.09%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB | 1         | 1      | 9.09%   |
| Toshiba THNSN5512GPUK NVMe 512GB     | 1         | 1      | 9.09%   |
| Toshiba HDWD130 3TB                  | 1         | 1      | 9.09%   |
| Seagate ST3320613AS 320GB            | 1         | 1      | 9.09%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 9.09%   |
| Samsung Electronics HD321HJ 320GB    | 1         | 2      | 9.09%   |
| Hitachi HDS721010DLE630 1TB          | 1         | 6      | 9.09%   |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 5      | 27.27%  |
| WDC                 | 2         | 3      | 18.18%  |
| Toshiba             | 2         | 2      | 18.18%  |
| Seagate             | 2         | 2      | 18.18%  |
| Hitachi             | 1         | 6      | 9.09%   |
| HGST                | 1         | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4942      | 11134  | 52.09%  |
| Works    | 3908      | 7657   | 41.19%  |
| Malfunc  | 627       | 923    | 6.61%   |
| Failed   | 10        | 19     | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5135      | 45.18%  |
| AMD                              | 1810      | 15.93%  |
| Samsung Electronics              | 1493      | 13.14%  |
| SanDisk                          | 637       | 5.6%    |
| SK hynix                         | 355       | 3.12%   |
| Toshiba America Info Systems     | 261       | 2.3%    |
| Phison Electronics               | 212       | 1.87%   |
| ASMedia Technology               | 196       | 1.72%   |
| Kingston Technology Company      | 170       | 1.5%    |
| Micron Technology                | 122       | 1.07%   |
| KIOXIA                           | 121       | 1.06%   |
| Marvell Technology Group         | 104       | 0.92%   |
| Micron/Crucial Technology        | 103       | 0.91%   |
| Silicon Motion                   | 97        | 0.85%   |
| ADATA Technology                 | 97        | 0.85%   |
| JMicron Technology               | 79        | 0.7%    |
| Nvidia                           | 76        | 0.67%   |
| Union Memory (Shenzhen)          | 35        | 0.31%   |
| Realtek Semiconductor            | 35        | 0.31%   |
| Lite-On Technology               | 33        | 0.29%   |
| LSI Logic / Symbios Logic        | 23        | 0.2%    |
| Seagate Technology               | 21        | 0.18%   |
| Broadcom / LSI                   | 20        | 0.18%   |
| Solid State Storage Technology   | 19        | 0.17%   |
| Lenovo                           | 19        | 0.17%   |
| Apple                            | 17        | 0.15%   |
| Silicon Image                    | 11        | 0.1%    |
| VIA Technologies                 | 8         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.06%   |
| Hewlett-Packard                  | 6         | 0.05%   |
| Adaptec                          | 6         | 0.05%   |
| Yangtze Memory Technologies      | 5         | 0.04%   |
| Integrated Technology Express    | 4         | 0.04%   |
| Unknown                          | 3         | 0.03%   |
| ULi Electronics                  | 3         | 0.03%   |
| Lite-On IT Corp. / Plextor       | 3         | 0.03%   |
| Transcend                        | 2         | 0.02%   |
| Silicon Integrated Systems [SiS] | 2         | 0.02%   |
| Shenzhen Longsys Electronics     | 2         | 0.02%   |
| HighPoint Technologies           | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1358      | 10.67%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 860       | 6.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 614       | 4.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 371       | 2.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 325       | 2.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 324       | 2.55%   |
| AMD 400 Series Chipset SATA Controller                                         | 320       | 2.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 243       | 1.91%   |
| Samsung NVMe SSD Controller 980                                                | 217       | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 209       | 1.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 206       | 1.62%   |
| Intel Volume Management Device NVMe RAID Controller                            | 206       | 1.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 205       | 1.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 193       | 1.52%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 188       | 1.48%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 179       | 1.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 171       | 1.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 167       | 1.31%   |
| AMD 500 Series Chipset SATA Controller                                         | 163       | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 147       | 1.16%   |
| Intel SATA Controller [RAID mode]                                              | 143       | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 141       | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 137       | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 135       | 1.06%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 133       | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 128       | 1.01%   |
| Intel SSD 660P Series                                                          | 127       | 1%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 126       | 0.99%   |
| Micron Non-Volatile memory controller                                          | 121       | 0.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 121       | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 121       | 0.95%   |
| Phison E12 NVMe Controller                                                     | 117       | 0.92%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 112       | 0.88%   |
| SK hynix Gold P31 SSD                                                          | 106       | 0.83%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 99        | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 95        | 0.75%   |
| SanDisk Non-Volatile memory controller                                         | 94        | 0.74%   |
| AMD 300 Series Chipset SATA Controller                                         | 89        | 0.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 88        | 0.69%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 85        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 6037      | 53.62%  |
| NVMe | 3845      | 34.15%  |
| RAID | 748       | 6.64%   |
| IDE  | 582       | 5.17%   |
| SAS  | 34        | 0.3%    |
| SCSI | 12        | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 6282      | 73.32%  |
| AMD      | 2260      | 26.38%  |
| ARM      | 23        | 0.27%   |
| Unknown  | 2         | 0.02%   |
| QUALCOMM | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 169       | 1.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 145       | 1.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 118       | 1.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 113       | 1.32%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 113       | 1.32%   |
| AMD Ryzen 5 3600 6-Core Processor             | 102       | 1.19%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 98        | 1.14%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 98        | 1.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 98        | 1.14%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 97        | 1.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 94        | 1.1%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 90        | 1.05%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 84        | 0.98%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 83        | 0.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 79        | 0.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 78        | 0.91%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 74        | 0.86%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 63        | 0.73%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 61        | 0.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 61        | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 57        | 0.66%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 55        | 0.64%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 55        | 0.64%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 55        | 0.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 54        | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 54        | 0.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 53        | 0.62%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 51        | 0.59%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 51        | 0.59%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 51        | 0.59%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 49        | 0.57%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 48        | 0.56%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 47        | 0.55%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 45        | 0.52%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 44        | 0.51%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 44        | 0.51%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 43        | 0.5%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 42        | 0.49%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 42        | 0.49%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 41        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 2260      | 26.35%  |
| Intel Core i5           | 1999      | 23.31%  |
| AMD Ryzen 5             | 713       | 8.31%   |
| AMD Ryzen 7             | 567       | 6.61%   |
| Other                   | 523       | 6.1%    |
| Intel Core i3           | 489       | 5.7%    |
| AMD Ryzen 9             | 227       | 2.65%   |
| Intel Xeon              | 189       | 2.2%    |
| Intel Celeron           | 172       | 2.01%   |
| Intel Core 2 Duo        | 162       | 1.89%   |
| Intel Atom              | 139       | 1.62%   |
| AMD FX                  | 121       | 1.41%   |
| Intel Pentium           | 118       | 1.38%   |
| Intel Core i9           | 92        | 1.07%   |
| AMD Ryzen 3             | 87        | 1.01%   |
| AMD Ryzen 7 PRO         | 68        | 0.79%   |
| AMD A10                 | 51        | 0.59%   |
| AMD A6                  | 47        | 0.55%   |
| AMD A8                  | 46        | 0.54%   |
| Intel Core 2 Quad       | 43        | 0.5%    |
| AMD Ryzen 5 PRO         | 42        | 0.49%   |
| AMD Ryzen Threadripper  | 39        | 0.45%   |
| Intel Pentium Dual-Core | 31        | 0.36%   |
| AMD Phenom II X4        | 28        | 0.33%   |
| AMD Athlon              | 24        | 0.28%   |
| AMD A4                  | 24        | 0.28%   |
| Intel Pentium Silver    | 23        | 0.27%   |
| AMD Athlon II X2        | 18        | 0.21%   |
| Intel Core 2            | 15        | 0.17%   |
| AMD Phenom II X6        | 14        | 0.16%   |
| AMD Phenom              | 12        | 0.14%   |
| AMD Athlon 64 X2        | 12        | 0.14%   |
| Intel Core m3           | 11        | 0.13%   |
| AMD E1                  | 10        | 0.12%   |
| AMD E                   | 10        | 0.12%   |
| Intel Pentium Dual      | 9         | 0.1%    |
| AMD A12                 | 9         | 0.1%    |
| Intel Genuine           | 8         | 0.09%   |
| Intel Core m5           | 8         | 0.09%   |
| AMD Athlon X4           | 8         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 3623      | 42.22%  |
| 2       | 2550      | 29.72%  |
| 6       | 1103      | 12.85%  |
| 8       | 857       | 9.99%   |
| 12      | 172       | 2%      |
| 16      | 85        | 0.99%   |
| 3       | 49        | 0.57%   |
| 1       | 47        | 0.55%   |
| 10      | 39        | 0.45%   |
| 14      | 22        | 0.26%   |
| 24      | 12        | 0.14%   |
| 32      | 10        | 0.12%   |
| Unknown | 6         | 0.07%   |
| 20      | 2         | 0.02%   |
| 72      | 1         | 0.01%   |
| 40      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8501      | 99.19%  |
| 2       | 60        | 0.7%    |
| Unknown | 6         | 0.07%   |
| 4       | 2         | 0.02%   |
| 3       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6767      | 78.82%  |
| 1       | 1812      | 21.11%  |
| Unknown | 6         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 8322      | 96.63%  |
| Unknown        | 282       | 3.27%   |
| 64-bit         | 5         | 0.06%   |
| 32-bit         | 3         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 526       | 6.03%   |
| 0x306a9    | 481       | 5.51%   |
| 0x306c3    | 458       | 5.25%   |
| 0x206a7    | 401       | 4.59%   |
| 0x806ea    | 399       | 4.57%   |
| 0x806ec    | 394       | 4.51%   |
| 0x906ea    | 354       | 4.05%   |
| 0x806c1    | 313       | 3.59%   |
| 0x806e9    | 304       | 3.48%   |
| 0x506e3    | 264       | 3.02%   |
| 0x406e3    | 262       | 3%      |
| 0x906e9    | 246       | 2.82%   |
| 0x08701021 | 223       | 2.55%   |
| 0x40651    | 211       | 2.42%   |
| 0x306d4    | 199       | 2.28%   |
| 0x1067a    | 150       | 1.72%   |
| 0x0a50000c | 148       | 1.7%    |
| 0xa0652    | 136       | 1.56%   |
| 0x0800820d | 132       | 1.51%   |
| 0x08108109 | 130       | 1.49%   |
| 0x08600106 | 125       | 1.43%   |
| 0x08108102 | 117       | 1.34%   |
| 0x706e5    | 115       | 1.32%   |
| 0x08701013 | 107       | 1.23%   |
| 0x20655    | 103       | 1.18%   |
| 0x906ed    | 98        | 1.12%   |
| 0x30678    | 86        | 0.99%   |
| 0x806eb    | 85        | 0.97%   |
| 0x06000852 | 73        | 0.84%   |
| 0x08600104 | 71        | 0.81%   |
| 0x406c4    | 66        | 0.76%   |
| 0x0a201016 | 62        | 0.71%   |
| 0x08608103 | 62        | 0.71%   |
| 0x0a201009 | 58        | 0.66%   |
| 0x0810100b | 54        | 0.62%   |
| 0x08600103 | 51        | 0.58%   |
| 0x08001138 | 51        | 0.58%   |
| 0x10676    | 48        | 0.55%   |
| 0x08001137 | 48        | 0.55%   |
| 0x06001119 | 45        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2037      | 23.75%  |
| Haswell          | 762       | 8.88%   |
| Zen 2            | 640       | 7.46%   |
| Skylake          | 580       | 6.76%   |
| IvyBridge        | 522       | 6.09%   |
| SandyBridge      | 447       | 5.21%   |
| Zen+             | 424       | 4.94%   |
| TigerLake        | 345       | 4.02%   |
| Zen 3            | 338       | 3.94%   |
| Zen              | 245       | 2.86%   |
| CometLake        | 236       | 2.75%   |
| Penryn           | 214       | 2.49%   |
| Broadwell        | 214       | 2.49%   |
| Silvermont       | 203       | 2.37%   |
| IceLake          | 181       | 2.11%   |
| Unknown          | 164       | 1.91%   |
| Westmere         | 163       | 1.9%    |
| Piledriver       | 153       | 1.78%   |
| K10              | 101       | 1.18%   |
| Core             | 78        | 0.91%   |
| Alderlake Hybrid | 77        | 0.9%    |
| Nehalem          | 74        | 0.86%   |
| Goldmont plus    | 70        | 0.82%   |
| Excavator        | 70        | 0.82%   |
| Goldmont         | 41        | 0.48%   |
| Puma             | 32        | 0.37%   |
| Steamroller      | 31        | 0.36%   |
| K8 Hammer        | 23        | 0.27%   |
| Jaguar           | 23        | 0.27%   |
| Bulldozer        | 20        | 0.23%   |
| Bobcat           | 20        | 0.23%   |
| K10 Llano        | 15        | 0.17%   |
| Bonnell          | 11        | 0.13%   |
| Tremont          | 10        | 0.12%   |
| NetBurst         | 8         | 0.09%   |
| K8 & K10 hybrid  | 4         | 0.05%   |
| P6               | 2         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5061      | 48.38%  |
| Nvidia                           | 2896      | 27.69%  |
| AMD                              | 2463      | 23.55%  |
| Matrox Electronics Systems       | 19        | 0.18%   |
| ASPEED Technology                | 16        | 0.15%   |
| ATI Technologies                 | 3         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 418       | 3.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 323       | 3.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 314       | 2.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 311       | 2.92%   |
| AMD Renoir                                                                               | 290       | 2.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 282       | 2.64%   |
| Intel HD Graphics 620                                                                    | 281       | 2.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 258       | 2.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 256       | 2.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 250       | 2.34%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 233       | 2.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 213       | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 208       | 1.95%   |
| Intel HD Graphics 630                                                                    | 182       | 1.71%   |
| Intel HD Graphics 5500                                                                   | 176       | 1.65%   |
| Intel HD Graphics 530                                                                    | 175       | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 160       | 1.5%    |
| AMD Cezanne                                                                              | 155       | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 138       | 1.29%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 128       | 1.2%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 115       | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 101       | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 101       | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 100       | 0.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 95        | 0.89%   |
| AMD Lucienne                                                                             | 89        | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 87        | 0.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 85        | 0.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 84        | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 76        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 75        | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 74        | 0.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 72        | 0.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 66        | 0.62%   |
| Nvidia GP108M [GeForce MX150]                                                            | 60        | 0.56%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 58        | 0.54%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 56        | 0.53%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 56        | 0.53%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 55        | 0.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 53        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 3383      | 39.19%  |
| 1 x AMD                  | 1928      | 22.33%  |
| 1 x Nvidia               | 1382      | 16.01%  |
| Intel + Nvidia           | 1313      | 15.21%  |
| Intel + AMD              | 242       | 2.8%    |
| AMD + Nvidia             | 172       | 1.99%   |
| 2 x AMD                  | 120       | 1.39%   |
| Other                    | 29        | 0.34%   |
| 2 x Nvidia               | 21        | 0.24%   |
| 1 x Matrox               | 14        | 0.16%   |
| 1 x ASPEED               | 13        | 0.15%   |
| Nvidia + Matrox          | 3         | 0.03%   |
| Intel + 2 x Nvidia       | 2         | 0.02%   |
| AMD + Matrox             | 2         | 0.02%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.01%   |
| 2 x Intel                | 1         | 0.01%   |
| 1 x SiS                  | 1         | 0.01%   |
| 1 x S3 Graphics          | 1         | 0.01%   |
| Nvidia + ASPEED          | 1         | 0.01%   |
| Intel + 2 x AMD          | 1         | 0.01%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.01%   |
| AMD + 2 x Nvidia         | 1         | 0.01%   |
| AMD + ASPEED             | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 7089      | 81.58%  |
| Proprietary | 1422      | 16.36%  |
| Unknown     | 179       | 2.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4650      | 52.91%  |
| 1.01-2.0   | 1151      | 13.1%   |
| 0.01-0.5   | 799       | 9.09%   |
| 3.01-4.0   | 680       | 7.74%   |
| 0.51-1.0   | 601       | 6.84%   |
| 7.01-8.0   | 504       | 5.74%   |
| 5.01-6.0   | 204       | 2.32%   |
| 8.01-16.0  | 135       | 1.54%   |
| 2.01-3.0   | 61        | 0.69%   |
| 16.01-24.0 | 3         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1184      | 11.48%  |
| Samsung Electronics     | 1064      | 10.31%  |
| BOE                     | 936       | 9.07%   |
| LG Display              | 906       | 8.78%   |
| Chimei Innolux          | 872       | 8.45%   |
| Dell                    | 820       | 7.95%   |
| Goldstar                | 682       | 6.61%   |
| Acer                    | 333       | 3.23%   |
| Hewlett-Packard         | 331       | 3.21%   |
| Sharp                   | 313       | 3.03%   |
| BenQ                    | 274       | 2.66%   |
| AOC                     | 271       | 2.63%   |
| Ancor Communications    | 245       | 2.37%   |
| Philips                 | 218       | 2.11%   |
| Lenovo                  | 217       | 2.1%    |
| Apple                   | 177       | 1.72%   |
| ViewSonic               | 129       | 1.25%   |
| PANDA                   | 116       | 1.12%   |
| Iiyama                  | 114       | 1.11%   |
| ASUSTek Computer        | 81        | 0.79%   |
| InfoVision              | 77        | 0.75%   |
| Chi Mei Optoelectronics | 68        | 0.66%   |
| CSO                     | 60        | 0.58%   |
| Sony                    | 52        | 0.5%    |
| Eizo                    | 41        | 0.4%    |
| Sceptre Tech            | 39        | 0.38%   |
| MSI                     | 36        | 0.35%   |
| Panasonic               | 35        | 0.34%   |
| HannStar                | 35        | 0.34%   |
| NEC Computers           | 28        | 0.27%   |
| Unknown                 | 27        | 0.26%   |
| Vizio                   | 23        | 0.22%   |
| TMX                     | 22        | 0.21%   |
| Gigabyte Technology     | 22        | 0.21%   |
| Insignia                | 19        | 0.18%   |
| Toshiba                 | 17        | 0.16%   |
| Fujitsu Siemens         | 17        | 0.16%   |
| JDI                     | 15        | 0.15%   |
| RTK                     | 14        | 0.14%   |
| LG Electronics          | 13        | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 62        | 0.58%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 50        | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 44        | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 40        | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 40        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 40        | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 40        | 0.37%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 37        | 0.34%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 36        | 0.33%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch             | 34        | 0.32%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 33        | 0.31%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 30        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 30        | 0.28%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 29        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 27        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 27        | 0.25%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 27        | 0.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 25        | 0.23%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 25        | 0.23%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 25        | 0.23%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 24        | 0.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 23        | 0.21%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 23        | 0.21%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 23        | 0.21%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                     | 23        | 0.21%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                    | 22        | 0.2%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 21        | 0.2%    |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch         | 21        | 0.2%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 21        | 0.2%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 21        | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 21        | 0.2%    |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch       | 21        | 0.2%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 20        | 0.19%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 20        | 0.19%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 20        | 0.19%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 20        | 0.19%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 19        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 19        | 0.18%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 19        | 0.18%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch       | 19        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4763      | 49.59%  |
| 1366x768 (WXGA)    | 1258      | 13.1%   |
| 3840x2160 (4K)     | 800       | 8.33%   |
| 2560x1440 (QHD)    | 659       | 6.86%   |
| 1920x1200 (WUXGA)  | 308       | 3.21%   |
| 1600x900 (HD+)     | 278       | 2.89%   |
| 1680x1050 (WSXGA+) | 187       | 1.95%   |
| 1280x1024 (SXGA)   | 182       | 1.89%   |
| 1440x900 (WXGA+)   | 147       | 1.53%   |
| 2560x1080          | 143       | 1.49%   |
| 3440x1440          | 138       | 1.44%   |
| 2560x1600          | 93        | 0.97%   |
| 1280x800 (WXGA)    | 90        | 0.94%   |
| 1360x768           | 58        | 0.6%    |
| 2880x1800          | 55        | 0.57%   |
| 3840x2400          | 42        | 0.44%   |
| 2160x1440          | 40        | 0.42%   |
| Unknown            | 35        | 0.36%   |
| 3840x1080          | 34        | 0.35%   |
| 3200x1800 (QHD+)   | 32        | 0.33%   |
| 2256x1504          | 27        | 0.28%   |
| 1600x1200          | 21        | 0.22%   |
| 2736x1824          | 19        | 0.2%    |
| 3000x2000          | 18        | 0.19%   |
| 1920x540           | 17        | 0.18%   |
| 1024x768 (XGA)     | 17        | 0.18%   |
| 1920x1280          | 12        | 0.12%   |
| 2288x1287          | 10        | 0.1%    |
| 3840x1600          | 9         | 0.09%   |
| 1280x720 (HD)      | 8         | 0.08%   |
| 3456x2160          | 7         | 0.07%   |
| 3200x2000          | 7         | 0.07%   |
| 2048x1152          | 7         | 0.07%   |
| 3072x1920          | 6         | 0.06%   |
| 2240x1400          | 6         | 0.06%   |
| 1280x960           | 5         | 0.05%   |
| 3240x2160          | 4         | 0.04%   |
| 2520x1680          | 4         | 0.04%   |
| 2160x1350          | 4         | 0.04%   |
| 1024x600           | 4         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2378      | 22.97%  |
| 13      | 1207      | 11.66%  |
| 27      | 1018      | 9.83%   |
| 24      | 961       | 9.28%   |
| 14      | 939       | 9.07%   |
| 23      | 679       | 6.56%   |
| 21      | 610       | 5.89%   |
| 17      | 376       | 3.63%   |
| 34      | 245       | 2.37%   |
| 31      | 236       | 2.28%   |
| 19      | 206       | 1.99%   |
| 12      | 206       | 1.99%   |
| 18      | 181       | 1.75%   |
| 22      | 153       | 1.48%   |
| 20      | 127       | 1.23%   |
| Unknown | 126       | 1.22%   |
| 16      | 67        | 0.65%   |
| 11      | 63        | 0.61%   |
| 32      | 59        | 0.57%   |
| 25      | 56        | 0.54%   |
| 84      | 55        | 0.53%   |
| 72      | 55        | 0.53%   |
| 40      | 35        | 0.34%   |
| 26      | 33        | 0.32%   |
| 54      | 32        | 0.31%   |
| 10      | 24        | 0.23%   |
| 48      | 23        | 0.22%   |
| 29      | 22        | 0.21%   |
| 42      | 20        | 0.19%   |
| 28      | 15        | 0.14%   |
| 35      | 14        | 0.14%   |
| 49      | 13        | 0.13%   |
| 46      | 13        | 0.13%   |
| 37      | 13        | 0.13%   |
| 52      | 10        | 0.1%    |
| 39      | 9         | 0.09%   |
| 65      | 8         | 0.08%   |
| 142     | 7         | 0.07%   |
| 43      | 7         | 0.07%   |
| 33      | 7         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3972      | 39.37%  |
| 501-600        | 2415      | 23.93%  |
| 401-500        | 1117      | 11.07%  |
| 201-300        | 897       | 8.89%   |
| 351-400        | 517       | 5.12%   |
| 601-700        | 386       | 3.83%   |
| 701-800        | 312       | 3.09%   |
| Unknown        | 126       | 1.25%   |
| 1501-2000      | 120       | 1.19%   |
| 1001-1500      | 115       | 1.14%   |
| 801-900        | 71        | 0.7%    |
| 901-1000       | 32        | 0.32%   |
| More than 2000 | 9         | 0.09%   |
| 101-200        | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 7060      | 79.41%  |
| 16/10   | 1021      | 11.48%  |
| 21/9    | 280       | 3.15%   |
| 5/4     | 182       | 2.05%   |
| 3/2     | 147       | 1.65%   |
| Unknown | 80        | 0.9%    |
| 4/3     | 57        | 0.64%   |
| 32/9    | 31        | 0.35%   |
| 6/5     | 14        | 0.16%   |
| 1.00    | 7         | 0.08%   |
| 1.96    | 4         | 0.04%   |
| 0.62    | 2         | 0.02%   |
| 3.88    | 1         | 0.01%   |
| 3.73    | 1         | 0.01%   |
| 3.40    | 1         | 0.01%   |
| 3.20    | 1         | 0.01%   |
| 0.80    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2376      | 23.28%  |
| 201-250        | 1811      | 17.74%  |
| 81-90          | 1634      | 16.01%  |
| 301-350        | 1049      | 10.28%  |
| 351-500        | 572       | 5.6%    |
| 71-80          | 522       | 5.11%   |
| 151-200        | 518       | 5.08%   |
| 251-300        | 384       | 3.76%   |
| 121-130        | 297       | 2.91%   |
| 141-150        | 199       | 1.95%   |
| More than 1000 | 196       | 1.92%   |
| 61-70          | 188       | 1.84%   |
| 501-1000       | 140       | 1.37%   |
| Unknown        | 126       | 1.23%   |
| 51-60          | 67        | 0.66%   |
| 111-120        | 57        | 0.56%   |
| 131-140        | 35        | 0.34%   |
| 41-50          | 21        | 0.21%   |
| 91-100         | 12        | 0.12%   |
| 1-40           | 2         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 3065      | 31.05%  |
| 51-100        | 3022      | 30.61%  |
| 101-120       | 2238      | 22.67%  |
| 161-240       | 853       | 8.64%   |
| More than 240 | 393       | 3.98%   |
| 1-50          | 175       | 1.77%   |
| Unknown       | 126       | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 6380      | 72.02%  |
| 2     | 1925      | 21.73%  |
| 0     | 278       | 3.14%   |
| 3     | 246       | 2.78%   |
| 4     | 25        | 0.28%   |
| 5     | 5         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 4907      | 39.03%  |
| Realtek Semiconductor             | 4282      | 34.06%  |
| Qualcomm Atheros                  | 1236      | 9.83%   |
| Broadcom                          | 501       | 3.99%   |
| MediaTek                          | 147       | 1.17%   |
| TP-Link                           | 140       | 1.11%   |
| Ralink Technology                 | 115       | 0.91%   |
| Broadcom Limited                  | 97        | 0.77%   |
| Marvell Technology Group          | 83        | 0.66%   |
| Lenovo                            | 79        | 0.63%   |
| Ralink                            | 72        | 0.57%   |
| ASIX Electronics                  | 66        | 0.52%   |
| Nvidia                            | 61        | 0.49%   |
| Sierra Wireless                   | 57        | 0.45%   |
| Microsoft                         | 45        | 0.36%   |
| DisplayLink                       | 41        | 0.33%   |
| Dell                              | 39        | 0.31%   |
| ASUSTek Computer                  | 39        | 0.31%   |
| Aquantia                          | 39        | 0.31%   |
| Samsung Electronics               | 33        | 0.26%   |
| Qualcomm Atheros Communications   | 33        | 0.26%   |
| Xiaomi                            | 28        | 0.22%   |
| Ericsson Business Mobile Networks | 28        | 0.22%   |
| D-Link                            | 27        | 0.21%   |
| NetGear                           | 25        | 0.2%    |
| Huawei Technologies               | 25        | 0.2%    |
| Qualcomm                          | 23        | 0.18%   |
| Hewlett-Packard                   | 22        | 0.17%   |
| Edimax Technology                 | 21        | 0.17%   |
| Apple                             | 19        | 0.15%   |
| Google                            | 16        | 0.13%   |
| Linksys                           | 15        | 0.12%   |
| D-Link System                     | 14        | 0.11%   |
| FIBOCOM                           | 11        | 0.09%   |
| Motorola PCS                      | 10        | 0.08%   |
| Mellanox Technologies             | 10        | 0.08%   |
| JMicron Technology                | 9         | 0.07%   |
| Belkin Components                 | 9         | 0.07%   |
| ICS Advent                        | 8         | 0.06%   |
| Arduino SA                        | 7         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2933      | 19.41%  |
| Intel Wi-Fi 6 AX200                                               | 702       | 4.65%   |
| Intel Wireless 8265 / 8275                                        | 435       | 2.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 381       | 2.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 355       | 2.35%   |
| Intel I211 Gigabit Network Connection                             | 333       | 2.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 302       | 2%      |
| Intel Wi-Fi 6 AX201                                               | 269       | 1.78%   |
| Intel Wireless 8260                                               | 247       | 1.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 245       | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 240       | 1.59%   |
| Intel Wireless 7260                                               | 218       | 1.44%   |
| Intel Wireless 7265                                               | 206       | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 189       | 1.25%   |
| Intel Ethernet Connection (2) I219-V                              | 188       | 1.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 186       | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 176       | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 163       | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 157       | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 153       | 1.01%   |
| Intel Wireless-AC 9260                                            | 149       | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 143       | 0.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 140       | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 138       | 0.91%   |
| Intel Wireless 3165                                               | 135       | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 131       | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 126       | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 123       | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 123       | 0.81%   |
| Intel Ethernet Connection I217-LM                                 | 118       | 0.78%   |
| Intel Ethernet Controller I225-V                                  | 108       | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 106       | 0.7%    |
| Intel Ethernet Connection (7) I219-V                              | 99        | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 89        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 88        | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 87        | 0.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 85        | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 85        | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 80        | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 76        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3993      | 55.4%   |
| Qualcomm Atheros                      | 1007      | 13.97%  |
| Realtek Semiconductor                 | 956       | 13.26%  |
| Broadcom                              | 354       | 4.91%   |
| MediaTek                              | 141       | 1.96%   |
| TP-Link                               | 122       | 1.69%   |
| Ralink Technology                     | 115       | 1.6%    |
| Ralink                                | 72        | 1%      |
| Broadcom Limited                      | 69        | 0.96%   |
| Sierra Wireless                       | 57        | 0.79%   |
| Microsoft                             | 42        | 0.58%   |
| ASUSTek Computer                      | 36        | 0.5%    |
| Qualcomm Atheros Communications       | 33        | 0.46%   |
| Dell                                  | 29        | 0.4%    |
| Marvell Technology Group              | 25        | 0.35%   |
| NetGear                               | 24        | 0.33%   |
| Edimax Technology                     | 21        | 0.29%   |
| D-Link                                | 20        | 0.28%   |
| Linksys                               | 14        | 0.19%   |
| Qualcomm                              | 13        | 0.18%   |
| FIBOCOM                               | 11        | 0.15%   |
| D-Link System                         | 11        | 0.15%   |
| Belkin Components                     | 9         | 0.12%   |
| Hewlett-Packard                       | 5         | 0.07%   |
| AVM                                   | 5         | 0.07%   |
| Wilocity                              | 4         | 0.06%   |
| IMC Networks                          | 3         | 0.04%   |
| Xiaomi                                | 2         | 0.03%   |
| BUFFALO                               | 2         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.03%   |
| ZyXEL Communications                  | 1         | 0.01%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.01%   |
| TRENDnet                              | 1         | 0.01%   |
| Toshiba                               | 1         | 0.01%   |
| Sitecom Europe                        | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Quectel Wireless Solutions            | 1         | 0.01%   |
| PLANEX                                | 1         | 0.01%   |
| Mercucys                              | 1         | 0.01%   |
| Gemtek                                | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 702       | 9.67%   |
| Intel Wireless 8265 / 8275                                     | 435       | 5.99%   |
| Intel Wi-Fi 6 AX201                                            | 269       | 3.71%   |
| Intel Wireless 8260                                            | 247       | 3.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 245       | 3.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 240       | 3.31%   |
| Intel Wireless 7260                                            | 218       | 3%      |
| Intel Wireless 7265                                            | 206       | 2.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 189       | 2.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 176       | 2.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 163       | 2.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 157       | 2.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 153       | 2.11%   |
| Intel Wireless-AC 9260                                         | 149       | 2.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 143       | 1.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 140       | 1.93%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 138       | 1.9%    |
| Intel Wireless 3165                                            | 135       | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 131       | 1.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 126       | 1.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 123       | 1.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 106       | 1.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 89        | 1.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 85        | 1.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 76        | 1.05%   |
| Intel Wireless 3160                                            | 72        | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 72        | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 70        | 0.96%   |
| Intel Centrino Ultimate-N 6300                                 | 61        | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 55        | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 52        | 0.72%   |
| Broadcom BCM43142 802.11b/g/n                                  | 48        | 0.66%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 45        | 0.62%   |
| Ralink MT7601U Wireless Adapter                                | 43        | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 41        | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 39        | 0.54%   |
| Intel Centrino Advanced-N 6235                                 | 39        | 0.54%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 37        | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 36        | 0.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 34        | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3864      | 51.51%  |
| Intel                             | 2460      | 32.8%   |
| Qualcomm Atheros                  | 328       | 4.37%   |
| Broadcom                          | 217       | 2.89%   |
| Lenovo                            | 79        | 1.05%   |
| ASIX Electronics                  | 66        | 0.88%   |
| Nvidia                            | 61        | 0.81%   |
| Marvell Technology Group          | 58        | 0.77%   |
| DisplayLink                       | 41        | 0.55%   |
| Aquantia                          | 39        | 0.52%   |
| Samsung Electronics               | 32        | 0.43%   |
| Broadcom Limited                  | 28        | 0.37%   |
| Xiaomi                            | 26        | 0.35%   |
| TP-Link                           | 20        | 0.27%   |
| Apple                             | 19        | 0.25%   |
| Google                            | 16        | 0.21%   |
| Huawei Technologies               | 14        | 0.19%   |
| Qualcomm                          | 10        | 0.13%   |
| Mellanox Technologies             | 9         | 0.12%   |
| JMicron Technology                | 9         | 0.12%   |
| Motorola PCS                      | 8         | 0.11%   |
| ICS Advent                        | 8         | 0.11%   |
| D-Link                            | 7         | 0.09%   |
| OnePlus                           | 6         | 0.08%   |
| MediaTek                          | 6         | 0.08%   |
| OPPO Electronics                  | 5         | 0.07%   |
| HMD Global                        | 5         | 0.07%   |
| Hewlett-Packard                   | 5         | 0.07%   |
| Cypress Semiconductor             | 5         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.04%   |
| MosChip Semiconductor             | 3         | 0.04%   |
| D-Link System                     | 3         | 0.04%   |
| ASUSTek Computer                  | 3         | 0.04%   |
| ADMtek                            | 3         | 0.04%   |
| vivo                              | 2         | 0.03%   |
| VIA Technologies                  | 2         | 0.03%   |
| Sundance Technology Inc / IC Plus | 2         | 0.03%   |
| Standard Microsystems             | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.03%   |
| NetXen Incorporated               | 2         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2933      | 37.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 381       | 4.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 355       | 4.59%   |
| Intel I211 Gigabit Network Connection                             | 333       | 4.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 302       | 3.91%   |
| Intel Ethernet Connection (2) I219-V                              | 188       | 2.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 186       | 2.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 123       | 1.59%   |
| Intel Ethernet Connection I217-LM                                 | 118       | 1.53%   |
| Intel Ethernet Controller I225-V                                  | 108       | 1.4%    |
| Intel Ethernet Connection (7) I219-V                              | 99        | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                             | 88        | 1.14%   |
| Intel Ethernet Connection (4) I219-V                              | 87        | 1.13%   |
| Intel Ethernet Connection I219-LM                                 | 85        | 1.1%    |
| Intel Ethernet Connection (6) I219-V                              | 80        | 1.03%   |
| Intel Ethernet Connection I218-LM                                 | 66        | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                             | 66        | 0.85%   |
| Intel Ethernet Connection (10) I219-V                             | 64        | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                             | 58        | 0.75%   |
| Intel Ethernet Connection (2) I218-V                              | 57        | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                     | 57        | 0.74%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 51        | 0.66%   |
| Intel Ethernet Connection I217-V                                  | 50        | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 50        | 0.65%   |
| Intel Ethernet Connection (6) I219-LM                             | 46        | 0.6%    |
| Intel 82574L Gigabit Network Connection                           | 46        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 44        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 41        | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 40        | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 38        | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 37        | 0.48%   |
| Intel Ethernet Connection I219-V                                  | 37        | 0.48%   |
| Intel 82577LM Gigabit Network Connection                          | 36        | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 31        | 0.4%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 30        | 0.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 29        | 0.38%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 29        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 25        | 0.32%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 25        | 0.32%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 25        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6960      | 50.02%  |
| WiFi     | 6836      | 49.13%  |
| Modem    | 103       | 0.74%   |
| Unknown  | 16        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 5450      | 60.19%  |
| Ethernet | 3602      | 39.78%  |
| Modem    | 2         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4557      | 52.9%   |
| 1     | 3562      | 41.35%  |
| 3     | 264       | 3.06%   |
| 0     | 175       | 2.03%   |
| 4     | 31        | 0.36%   |
| 5     | 14        | 0.16%   |
| 6     | 6         | 0.07%   |
| 8     | 3         | 0.03%   |
| 9     | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 7359      | 84.09%  |
| Yes     | 1386      | 15.84%  |
| Unknown | 6         | 0.07%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3395      | 56.98%  |
| Realtek Semiconductor           | 508       | 8.53%   |
| Qualcomm Atheros Communications | 456       | 7.65%   |
| Cambridge Silicon Radio         | 313       | 5.25%   |
| Broadcom                        | 246       | 4.13%   |
| IMC Networks                    | 186       | 3.12%   |
| Apple                           | 177       | 2.97%   |
| Lite-On Technology              | 168       | 2.82%   |
| Foxconn / Hon Hai               | 144       | 2.42%   |
| ASUSTek Computer                | 114       | 1.91%   |
| Realtek                         | 42        | 0.7%    |
| Dell                            | 36        | 0.6%    |
| Ralink                          | 26        | 0.44%   |
| Marvell Semiconductor           | 26        | 0.44%   |
| Hewlett-Packard                 | 24        | 0.4%    |
| Toshiba                         | 19        | 0.32%   |
| MediaTek                        | 16        | 0.27%   |
| TP-Link                         | 10        | 0.17%   |
| Foxconn International           | 9         | 0.15%   |
| Belkin Components               | 6         | 0.1%    |
| HTC (High Tech Computer)        | 5         | 0.08%   |
| Ralink Technology               | 4         | 0.07%   |
| Integrated System Solution      | 3         | 0.05%   |
| Edimax Technology               | 3         | 0.05%   |
| Dynex                           | 3         | 0.05%   |
| Alps Electric                   | 3         | 0.05%   |
| Unknown                         | 2         | 0.03%   |
| Qcom                            | 2         | 0.03%   |
| Opticis                         | 2         | 0.03%   |
| Chicony Electronics             | 2         | 0.03%   |
| USI                             | 1         | 0.02%   |
| Taiyo Yuden                     | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Kensington                      | 1         | 0.02%   |
| D-Link System                   | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1222      | 20.49%  |
| Intel AX200 Bluetooth                               | 674       | 11.3%   |
| Intel AX201 Bluetooth                               | 577       | 9.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 452       | 7.58%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 313       | 5.25%   |
| Realtek Bluetooth Radio                             | 289       | 4.84%   |
| Qualcomm Atheros  Bluetooth Device                  | 250       | 4.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 136       | 2.28%   |
| Realtek  Bluetooth 4.2 Adapter                      | 131       | 2.2%    |
| Intel Wireless-AC 3168 Bluetooth                    | 123       | 2.06%   |
| Intel AX210 Bluetooth                               | 102       | 1.71%   |
| Apple Bluetooth Host Controller                     | 85        | 1.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 81        | 1.36%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 66        | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 65        | 1.09%   |
| Foxconn / Hon Hai Bluetooth Device                  | 58        | 0.97%   |
| IMC Networks Bluetooth Radio                        | 57        | 0.96%   |
| IMC Networks Wireless_Device                        | 56        | 0.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 56        | 0.94%   |
| Apple Bluetooth USB Host Controller                 | 50        | 0.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 47        | 0.79%   |
| Lite-On Bluetooth Device                            | 46        | 0.77%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 45        | 0.75%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 45        | 0.75%   |
| Foxconn / Hon Hai Wireless_Device                   | 43        | 0.72%   |
| Realtek Bluetooth Radio                             | 42        | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 37        | 0.62%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 36        | 0.6%    |
| IMC Networks Bluetooth Device                       | 33        | 0.55%   |
| Broadcom BCM2045B (BDC-2.1)                         | 33        | 0.55%   |
| Intel Bluetooth Device                              | 30        | 0.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 29        | 0.49%   |
| Ralink RT3290 Bluetooth                             | 26        | 0.44%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 22        | 0.37%   |
| Realtek RTL8723B Bluetooth                          | 21        | 0.35%   |
| Realtek RTL8821A Bluetooth                          | 20        | 0.34%   |
| Lite-On Atheros AR3012 Bluetooth                    | 20        | 0.34%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 20        | 0.34%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 19        | 0.32%   |
| Marvell Bluetooth and Wireless LAN Composite        | 19        | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 6027      | 48.12%  |
| AMD                         | 2671      | 21.33%  |
| Nvidia                      | 2076      | 16.57%  |
| C-Media Electronics         | 259       | 2.07%   |
| Logitech                    | 136       | 1.09%   |
| Lenovo                      | 95        | 0.76%   |
| Realtek Semiconductor       | 88        | 0.7%    |
| GN Netcom                   | 69        | 0.55%   |
| Creative Labs               | 63        | 0.5%    |
| JMTek                       | 57        | 0.46%   |
| Texas Instruments           | 52        | 0.42%   |
| Plantronics                 | 52        | 0.42%   |
| Creative Technology         | 51        | 0.41%   |
| Corsair                     | 49        | 0.39%   |
| Kingston Technology         | 48        | 0.38%   |
| SteelSeries ApS             | 46        | 0.37%   |
| Focusrite-Novation          | 41        | 0.33%   |
| Razer USA                   | 37        | 0.3%    |
| Generalplus Technology      | 33        | 0.26%   |
| Blue Microphones            | 29        | 0.23%   |
| Hewlett-Packard             | 24        | 0.19%   |
| GYROCOM C&C                 | 23        | 0.18%   |
| Sony                        | 22        | 0.18%   |
| Sennheiser Communications   | 21        | 0.17%   |
| Samson Technologies         | 20        | 0.16%   |
| ASUSTek Computer            | 20        | 0.16%   |
| XMOS                        | 19        | 0.15%   |
| Dell                        | 16        | 0.13%   |
| Tenx Technology             | 14        | 0.11%   |
| RODE Microphones            | 14        | 0.11%   |
| Apple                       | 14        | 0.11%   |
| Cambridge Silicon Radio     | 13        | 0.1%    |
| SAVITECH                    | 12        | 0.1%    |
| Conexant Systems            | 11        | 0.09%   |
| Giga-Byte Technology        | 10        | 0.08%   |
| PreSonus Audio Electronics  | 9         | 0.07%   |
| FiiO Electronics Technology | 9         | 0.07%   |
| Yamaha                      | 8         | 0.06%   |
| Microsoft                   | 8         | 0.06%   |
| Micro Star International    | 8         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 1022      | 6.8%    |
| AMD Family 17h/19h HD Audio Controller                                     | 952       | 6.34%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 504       | 3.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 503       | 3.35%   |
| AMD Starship/Matisse HD Audio Controller                                   | 481       | 3.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 430       | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 420       | 2.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 411       | 2.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 345       | 2.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 337       | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 306       | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 301       | 2%      |
| Intel Cannon Point-LP High Definition Audio Controller                     | 300       | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 292       | 1.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 259       | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                            | 247       | 1.64%   |
| Intel Comet Lake PCH-LP cAVS                                               | 229       | 1.52%   |
| Intel Haswell-ULT HD Audio Controller                                      | 217       | 1.44%   |
| Intel 8 Series HD Audio Controller                                         | 217       | 1.44%   |
| Intel Broadwell-U Audio Controller                                         | 205       | 1.36%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 200       | 1.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 197       | 1.31%   |
| Intel 200 Series PCH HD Audio                                              | 191       | 1.27%   |
| Intel Comet Lake PCH cAVS                                                  | 178       | 1.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 178       | 1.18%   |
| AMD FCH Azalia Controller                                                  | 164       | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 157       | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 147       | 0.98%   |
| AMD Navi 10 HDMI Audio                                                     | 146       | 0.97%   |
| Intel CM238 HD Audio Controller                                            | 134       | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 133       | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 127       | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 125       | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 122       | 0.81%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 122       | 0.81%   |
| Nvidia GP104 High Definition Audio Controller                              | 115       | 0.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 105       | 0.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 97        | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                         | 95        | 0.63%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 94        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1166      | 22.68%  |
| SK hynix            | 919       | 17.88%  |
| Kingston            | 604       | 11.75%  |
| Micron Technology   | 580       | 11.28%  |
| Unknown             | 382       | 7.43%   |
| Corsair             | 331       | 6.44%   |
| Crucial             | 320       | 6.23%   |
| G.Skill             | 221       | 4.3%    |
| A-DATA Technology   | 111       | 2.16%   |
| Ramaxel Technology  | 88        | 1.71%   |
| Team                | 44        | 0.86%   |
| Elpida              | 41        | 0.8%    |
| Patriot             | 40        | 0.78%   |
| Unknown (ABCD)      | 33        | 0.64%   |
| Smart               | 27        | 0.53%   |
| Nanya Technology    | 26        | 0.51%   |
| Unknown             | 19        | 0.37%   |
| GOODRAM             | 17        | 0.33%   |
| Transcend           | 13        | 0.25%   |
| Smart Brazil        | 11        | 0.21%   |
| Teikon              | 10        | 0.19%   |
| Silicon Power       | 9         | 0.18%   |
| Avant               | 9         | 0.18%   |
| PNY                 | 6         | 0.12%   |
| Goldkey             | 6         | 0.12%   |
| GeIL                | 6         | 0.12%   |
| Qimonda             | 5         | 0.1%    |
| CSX                 | 5         | 0.1%    |
| Apacer              | 5         | 0.1%    |
| Kllisre             | 4         | 0.08%   |
| AMD                 | 4         | 0.08%   |
| Timetec             | 3         | 0.06%   |
| Sesame              | 3         | 0.06%   |
| Qumo                | 3         | 0.06%   |
| OnBoard             | 3         | 0.06%   |
| V-GeN               | 2         | 0.04%   |
| SHARETRONIC         | 2         | 0.04%   |
| RZX                 | 2         | 0.04%   |
| PUSKILL             | 2         | 0.04%   |
| OCZ                 | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 62        | 1.14%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 56        | 1.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 55        | 1.01%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 40        | 0.73%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 36        | 0.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 31        | 0.57%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s            | 31        | 0.57%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 30        | 0.55%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 30        | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 29        | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 27        | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s    | 26        | 0.48%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 26        | 0.48%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 26        | 0.48%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 25        | 0.46%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 25        | 0.46%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s           | 25        | 0.46%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 24        | 0.44%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 24        | 0.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 24        | 0.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 24        | 0.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 24        | 0.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 23        | 0.42%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 23        | 0.42%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s               | 23        | 0.42%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 22        | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 21        | 0.38%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 21        | 0.38%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 21        | 0.38%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 21        | 0.38%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 21        | 0.38%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 20        | 0.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 20        | 0.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 20        | 0.37%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 20        | 0.37%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 19        | 0.35%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 19        | 0.35%   |
| Unknown                                                             | 19        | 0.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 18        | 0.33%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 18        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2499      | 56.58%  |
| DDR3    | 1233      | 27.91%  |
| LPDDR3  | 208       | 4.71%   |
| LPDDR4  | 191       | 4.32%   |
| Unknown | 97        | 2.2%    |
| DDR2    | 90        | 2.04%   |
| SDRAM   | 50        | 1.13%   |
| DDR5    | 19        | 0.43%   |
| LPDDR5  | 16        | 0.36%   |
| DDR     | 13        | 0.29%   |
| DRAM    | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2538      | 57.05%  |
| DIMM         | 1386      | 31.15%  |
| Row Of Chips | 454       | 10.2%   |
| Chip         | 52        | 1.17%   |
| Unknown      | 9         | 0.2%    |
| RIMM         | 8         | 0.18%   |
| FB-DIMM      | 2         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1972      | 41.32%  |
| 4096   | 1279      | 26.8%   |
| 16384  | 875       | 18.33%  |
| 2048   | 395       | 8.28%   |
| 32768  | 164       | 3.44%   |
| 1024   | 77        | 1.61%   |
| 512    | 6         | 0.13%   |
| 3072   | 2         | 0.04%   |
| 129408 | 1         | 0.02%   |
| 256    | 1         | 0.02%   |
| 64     | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 863       | 18.09%  |
| 3200    | 822       | 17.23%  |
| 1600    | 813       | 17.04%  |
| 2400    | 395       | 8.28%   |
| 2133    | 338       | 7.08%   |
| 1333    | 256       | 5.37%   |
| 3600    | 154       | 3.23%   |
| 1867    | 119       | 2.49%   |
| 4267    | 99        | 2.08%   |
| 1334    | 95        | 1.99%   |
| 800     | 61        | 1.28%   |
| 3266    | 60        | 1.26%   |
| 667     | 60        | 1.26%   |
| Unknown | 54        | 1.13%   |
| 3000    | 47        | 0.99%   |
| 1067    | 47        | 0.99%   |
| 1066    | 42        | 0.88%   |
| 3400    | 41        | 0.86%   |
| 3466    | 37        | 0.78%   |
| 2666    | 32        | 0.67%   |
| 3733    | 29        | 0.61%   |
| 4800    | 27        | 0.57%   |
| 8400    | 23        | 0.48%   |
| 2933    | 21        | 0.44%   |
| 1866    | 19        | 0.4%    |
| 6400    | 18        | 0.38%   |
| 3866    | 18        | 0.38%   |
| 3800    | 18        | 0.38%   |
| 4266    | 14        | 0.29%   |
| 4199    | 14        | 0.29%   |
| 2800    | 13        | 0.27%   |
| 1800    | 12        | 0.25%   |
| 3333    | 7         | 0.15%   |
| 3100    | 7         | 0.15%   |
| 533     | 7         | 0.15%   |
| 2000    | 6         | 0.13%   |
| 2733    | 5         | 0.1%    |
| 3666    | 4         | 0.08%   |
| 3334    | 4         | 0.08%   |
| 2048    | 4         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 69        | 38.76%  |
| Brother Industries    | 40        | 22.47%  |
| Canon                 | 22        | 12.36%  |
| Samsung Electronics   | 14        | 7.87%   |
| Seiko Epson           | 12        | 6.74%   |
| Prolific Technology   | 6         | 3.37%   |
| Xerox                 | 2         | 1.12%   |
| Lexmark International | 2         | 1.12%   |
| Kyocera               | 2         | 1.12%   |
| Star Micronics        | 1         | 0.56%   |
| Ricoh                 | 1         | 0.56%   |
| QinHeng Electronics   | 1         | 0.56%   |
| Pantum                | 1         | 0.56%   |
| NXP Semiconductors    | 1         | 0.56%   |
| Graphtec America      | 1         | 0.56%   |
| Dymo-CoStar           | 1         | 0.56%   |
| Dell                  | 1         | 0.56%   |
| Boca Systems          | 1         | 0.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                | 6         | 3.37%   |
| Samsung M2070 Series                         | 5         | 2.81%   |
| HP LaserJet Professional P 1102w             | 4         | 2.25%   |
| Brother Printer                              | 4         | 2.25%   |
| Brother HL-L2340D series                     | 4         | 2.25%   |
| HP ENVY 5000 series                          | 3         | 1.69%   |
| HP ENVY 4520 series                          | 3         | 1.69%   |
| HP DeskJet F300 series                       | 3         | 1.69%   |
| HP DeskJet 2130 series                       | 3         | 1.69%   |
| Brother HL-1110 series                       | 3         | 1.69%   |
| Seiko Epson Printer                          | 2         | 1.12%   |
| Samsung ML-216x Series Laser Printer         | 2         | 1.12%   |
| HP OfficeJet 6950                            | 2         | 1.12%   |
| HP DeskJet 3700 series                       | 2         | 1.12%   |
| HP DeskJet 3630 series                       | 2         | 1.12%   |
| HP Deskjet 3510 series                       | 2         | 1.12%   |
| HP DeskJet 2620 All-in-One Printer           | 2         | 1.12%   |
| Canon TS3300 series                          | 2         | 1.12%   |
| Canon TR4500 series                          | 2         | 1.12%   |
| Canon CanoScan LiDE 300                      | 2         | 1.12%   |
| Brother MFC-9330CDW                          | 2         | 1.12%   |
| Brother HL-5250DN Printer                    | 2         | 1.12%   |
| Brother HL-2230 series                       | 2         | 1.12%   |
| Brother HL-2030 Laser Printer                | 2         | 1.12%   |
| Xerox Phaser 6500DN                          | 1         | 0.56%   |
| Xerox Phaser 3010                            | 1         | 0.56%   |
| Star Micronics TUP592 (STR_T-001)            | 1         | 0.56%   |
| Seiko Epson WF-2830 Series                   | 1         | 0.56%   |
| Seiko Epson WF-2510 Series                   | 1         | 0.56%   |
| Seiko Epson PX-045A Series                   | 1         | 0.56%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.56%   |
| Seiko Epson L3110 Series                     | 1         | 0.56%   |
| Seiko Epson L300 Series                      | 1         | 0.56%   |
| Seiko Epson L222 Series                      | 1         | 0.56%   |
| Seiko Epson L200 Series                      | 1         | 0.56%   |
| Seiko Epson L100 Series                      | 1         | 0.56%   |
| Seiko Epson ET-2710 Series                   | 1         | 0.56%   |
| Samsung Xerox Phaser 3117 Laser Printer      | 1         | 0.56%   |
| Samsung SCX-4200 series                      | 1         | 0.56%   |
| Samsung SCX-3200 Series                      | 1         | 0.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 27        | 58.7%   |
| Seiko Epson     | 13        | 28.26%  |
| Hewlett-Packard | 4         | 8.7%    |
| UMAX            | 1         | 2.17%   |
| Mustek Systems  | 1         | 2.17%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X770 [Perfection V500]                   | 5         | 10.87%  |
| Canon CanoScan LiDE 220                                 | 5         | 10.87%  |
| Canon CanoScan LiDE 210                                 | 4         | 8.7%    |
| Canon CanoScan N670U/N676U/LiDE 20                      | 3         | 6.52%   |
| Canon CanoScan LIDE 25                                  | 3         | 6.52%   |
| Canon CanoScan LiDE 110                                 | 3         | 6.52%   |
| Canon CanoScan LiDE 100                                 | 3         | 6.52%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 2         | 4.35%   |
| UMAX Astra 2200/2200SU                                  | 1         | 2.17%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]        | 1         | 2.17%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 2.17%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 2.17%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]             | 1         | 2.17%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1         | 2.17%   |
| Seiko Epson ES-D400 [GT-S80]                            | 1         | 2.17%   |
| Mustek Systems BearPaw 2448 TA Plus                     | 1         | 2.17%   |
| HP ScanJet G4050                                        | 1         | 2.17%   |
| HP ScanJet 5590                                         | 1         | 2.17%   |
| HP ScanJet 3400cse                                      | 1         | 2.17%   |
| HP ScanJet 2400c                                        | 1         | 2.17%   |
| Canon CanoScan N650U/N656U                              | 1         | 2.17%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 2.17%   |
| Canon CanoScan LiDE 70                                  | 1         | 2.17%   |
| Canon CanoScan LiDE 200                                 | 1         | 2.17%   |
| Canon CanoScan LiDE 120                                 | 1         | 2.17%   |
| Canon CanoScan 4400F                                    | 1         | 2.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1272      | 21.75%  |
| IMC Networks                           | 594       | 10.16%  |
| Realtek Semiconductor                  | 487       | 8.33%   |
| Acer                                   | 477       | 8.16%   |
| Microdia                               | 466       | 7.97%   |
| Logitech                               | 460       | 7.87%   |
| Sunplus Innovation Technology          | 289       | 4.94%   |
| Quanta                                 | 266       | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 215       | 3.68%   |
| Apple                                  | 179       | 3.06%   |
| Lite-On Technology                     | 167       | 2.86%   |
| Syntek                                 | 154       | 2.63%   |
| Microsoft                              | 90        | 1.54%   |
| Suyin                                  | 83        | 1.42%   |
| Luxvisions Innotech Limited            | 67        | 1.15%   |
| Silicon Motion                         | 61        | 1.04%   |
| Samsung Electronics                    | 59        | 1.01%   |
| Alcor Micro                            | 41        | 0.7%    |
| Ricoh                                  | 31        | 0.53%   |
| Lenovo                                 | 26        | 0.44%   |
| KYE Systems (Mouse Systems)            | 24        | 0.41%   |
| Z-Star Microelectronics                | 20        | 0.34%   |
| Generalplus Technology                 | 19        | 0.32%   |
| Primax Electronics                     | 18        | 0.31%   |
| Creative Technology                    | 18        | 0.31%   |
| ARC International                      | 14        | 0.24%   |
| Importek                               | 13        | 0.22%   |
| Sonix Technology                       | 12        | 0.21%   |
| Unknown                                | 10        | 0.17%   |
| MacroSilicon                           | 10        | 0.17%   |
| Cubeternet                             | 10        | 0.17%   |
| SunplusIT                              | 9         | 0.15%   |
| Razer USA                              | 9         | 0.15%   |
| Jieli Technology                       | 9         | 0.15%   |
| Intel                                  | 9         | 0.15%   |
| 2M UVC CAMERA                          | 9         | 0.15%   |
| Hewlett-Packard                        | 8         | 0.14%   |
| icSpring                               | 7         | 0.12%   |
| GEMBIRD                                | 7         | 0.12%   |
| Pixart Imaging                         | 6         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 425       | 7.17%   |
| IMC Networks Integrated Camera                      | 257       | 4.33%   |
| Microdia Integrated_Webcam_HD                       | 243       | 4.1%    |
| Realtek Integrated_Webcam_HD                        | 209       | 3.52%   |
| Acer Integrated Camera                              | 154       | 2.6%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 142       | 2.39%   |
| Chicony HD WebCam                                   | 129       | 2.18%   |
| Sunplus Integrated_Webcam_HD                        | 120       | 2.02%   |
| Logitech HD Pro Webcam C920                         | 108       | 1.82%   |
| Syntek Integrated Camera                            | 104       | 1.75%   |
| Logitech Webcam C270                                | 103       | 1.74%   |
| Lite-On Integrated Camera                           | 74        | 1.25%   |
| Chicony Integrated Camera (1280x720@30)             | 70        | 1.18%   |
| Apple iPhone 5/5C/5S/6/SE                           | 59        | 0.99%   |
| Samsung Galaxy series, misc. (MTP mode)             | 58        | 0.98%   |
| Chicony HP HD Camera                                | 58        | 0.98%   |
| Quanta HD User Facing                               | 54        | 0.91%   |
| Acer SunplusIT Integrated Camera                    | 52        | 0.88%   |
| Acer Lenovo EasyCamera                              | 50        | 0.84%   |
| Apple FaceTime HD Camera (Built-in)                 | 49        | 0.83%   |
| Chicony HP Wide Vision HD Camera                    | 44        | 0.74%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 43        | 0.73%   |
| Quanta HP TrueVision HD Camera                      | 42        | 0.71%   |
| Apple Built-in iSight                               | 42        | 0.71%   |
| Microdia Integrated Webcam                          | 37        | 0.62%   |
| Chicony USB2.0 Camera                               | 36        | 0.61%   |
| Quanta HD Webcam                                    | 34        | 0.57%   |
| Lite-On HP HD Camera                                | 34        | 0.57%   |
| Quanta HP HD Camera                                 | 33        | 0.56%   |
| Acer EasyCamera                                     | 33        | 0.56%   |
| Realtek USB Camera                                  | 32        | 0.54%   |
| Microsoft LifeCam HD-3000                           | 32        | 0.54%   |
| Realtek Integrated Webcam                           | 31        | 0.52%   |
| Logitech C922 Pro Stream Webcam                     | 31        | 0.52%   |
| Chicony EasyCamera                                  | 31        | 0.52%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 31        | 0.52%   |
| Acer BisonCam, NB Pro                               | 30        | 0.51%   |
| Sunplus HD WebCam                                   | 29        | 0.49%   |
| Realtek Integrated Webcam HD                        | 29        | 0.49%   |
| IMC Networks HD Camera                              | 29        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 556       | 38.42%  |
| Validity Sensors           | 431       | 29.79%  |
| Shenzhen Goodix Technology | 228       | 15.76%  |
| Elan Microelectronics      | 83        | 5.74%   |
| Upek                       | 54        | 3.73%   |
| LighTuning Technology      | 48        | 3.32%   |
| AuthenTec                  | 27        | 1.87%   |
| Samsung Electronics        | 8         | 0.55%   |
| STMicroelectronics         | 4         | 0.28%   |
| Focal-systems.Corp         | 4         | 0.28%   |
| DigitalPersona             | 2         | 0.14%   |
| Dell                       | 2         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 221       | 15.26%  |
| Unknown                                                                    | 115       | 7.94%   |
| Shenzhen Goodix  Fingerprint Device                                        | 107       | 7.39%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 93        | 6.42%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 79        | 5.46%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 78        | 5.39%   |
| Shenzhen Goodix Fingerprint Reader                                         | 76        | 5.25%   |
| Elan ELAN:Fingerprint                                                      | 57        | 3.94%   |
| Validity Sensors Synaptics WBDI                                            | 52        | 3.59%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 52        | 3.59%   |
| Synaptics  WBDI                                                            | 49        | 3.38%   |
| Shenzhen Goodix FingerPrint                                                | 45        | 3.11%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 41        | 2.83%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 37        | 2.56%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 35        | 2.42%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 27        | 1.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 26        | 1.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 24        | 1.66%   |
| Elan ELAN:ARM-M4                                                           | 24        | 1.66%   |
| Validity Sensors VFS491                                                    | 23        | 1.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 20        | 1.38%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 1.1%    |
| LighTuning EgisTec_ES603                                                   | 14        | 0.97%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 13        | 0.9%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 0.9%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 0.76%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 0.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 10        | 0.69%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.55%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 6         | 0.41%   |
| Synaptics WBDI Device                                                      | 6         | 0.41%   |
| Samsung Fingerprint Device                                                 | 6         | 0.41%   |
| AuthenTec AES2810                                                          | 5         | 0.35%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.35%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.28%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 4         | 0.28%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.28%   |
| LighTuning Fingerprint Sensor                                              | 4         | 0.28%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.28%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 204       | 40.4%   |
| Broadcom                          | 185       | 36.63%  |
| Upek                              | 30        | 5.94%   |
| Lenovo                            | 26        | 5.15%   |
| O2 Micro                          | 10        | 1.98%   |
| SCM Microsystems                  | 7         | 1.39%   |
| OmniKey                           | 7         | 1.39%   |
| Gemalto (was Gemplus)             | 7         | 1.39%   |
| Yubico.com                        | 6         | 1.19%   |
| Realtek Semiconductor             | 5         | 0.99%   |
| VASCO Data Security International | 3         | 0.59%   |
| Aladdin Knowledge Systems         | 3         | 0.59%   |
| Chicony Electronics               | 2         | 0.4%    |
| Advanced Card Systems             | 2         | 0.4%    |
| Reiner SCT Kartensysteme          | 1         | 0.2%    |
| Hewlett-Packard                   | 1         | 0.2%    |
| Fujitsu Siemens Computers         | 1         | 0.2%    |
| Feitian Technologies              | 1         | 0.2%    |
| Clay Logic                        | 1         | 0.2%    |
| Cherry                            | 1         | 0.2%    |
| Athena Smartcard Solutions        | 1         | 0.2%    |
| Aktiv                             | 1         | 0.2%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 201       | 39.8%   |
| Broadcom 5880                                                                | 61        | 12.08%  |
| Broadcom BCM5880 Secure Applications Processor                               | 47        | 9.31%   |
| Broadcom 58200                                                               | 43        | 8.51%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 32        | 6.34%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 30        | 5.94%   |
| Lenovo Integrated Smart Card Reader                                          | 26        | 5.15%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 1.78%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 5         | 0.99%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 4         | 0.79%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 4         | 0.79%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 4         | 0.79%   |
| OmniKey CardMan 1021                                                         | 3         | 0.59%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 0.59%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.59%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 2         | 0.4%    |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.4%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.4%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.4%    |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.4%    |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.2%    |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.2%    |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.2%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.2%    |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.2%    |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.2%    |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.2%    |
| OmniKey CardMan 4321                                                         | 1         | 0.2%    |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.2%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.2%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.2%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.2%    |
| Feitian Technologies FT SCR310                                               | 1         | 0.2%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.2%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.2%    |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.2%    |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.2%    |
| Aktiv Rutoken lite                                                           | 1         | 0.2%    |
| Advanced Card Systems ACR39U                                                 | 1         | 0.2%    |
| Advanced Card Systems ACR122U                                                | 1         | 0.2%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5931      | 67.37%  |
| 1     | 2368      | 26.9%   |
| 2     | 419       | 4.76%   |
| 3     | 58        | 0.66%   |
| 4     | 11        | 0.12%   |
| 5     | 9         | 0.1%    |
| 6     | 5         | 0.06%   |
| 8     | 2         | 0.02%   |
| 7     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1430      | 42.94%  |
| Graphics card            | 562       | 16.88%  |
| Net/wireless             | 345       | 10.36%  |
| Multimedia controller    | 306       | 9.19%   |
| Chipcard                 | 184       | 5.53%   |
| Camera                   | 120       | 3.6%    |
| Bluetooth                | 64        | 1.92%   |
| Unassigned class         | 59        | 1.77%   |
| Communication controller | 59        | 1.77%   |
| Storage                  | 42        | 1.26%   |
| Card reader              | 42        | 1.26%   |
| Sound                    | 38        | 1.14%   |
| Network                  | 29        | 0.87%   |
| Net/ethernet             | 17        | 0.51%   |
| Modem                    | 12        | 0.36%   |
| Storage/raid             | 10        | 0.3%    |
| Dvb card                 | 3         | 0.09%   |
| Storage/ata              | 2         | 0.06%   |
| Flash memory             | 2         | 0.06%   |
| Firewire controller      | 2         | 0.06%   |
| Wireless                 | 1         | 0.03%   |
| Video                    | 1         | 0.03%   |

