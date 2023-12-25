MX 21 - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MX 21.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX_21/Desktop/README.md) and [notebooks](/Dist/MX_21/Notebook/README.md).

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

Total: 544

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | M4A87TD/USB3                | Desktop     | [df3eb3c253](https://linux-hardware.org/?probe=df3eb3c253) | Dec 17, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [9a5c924695](https://linux-hardware.org/?probe=9a5c924695) | Nov 26, 2023 |
| Lenovo        | ThinkPad T500 20552CU       | Notebook    | [7389e9e37c](https://linux-hardware.org/?probe=7389e9e37c) | Nov 21, 2023 |
| Dell          | 0MNPJ9 A01                  | Desktop     | [80ded618fb](https://linux-hardware.org/?probe=80ded618fb) | Nov 19, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [90ce2b0711](https://linux-hardware.org/?probe=90ce2b0711) | Nov 13, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [0d65b73ae2](https://linux-hardware.org/?probe=0d65b73ae2) | Nov 07, 2023 |
| HP            | Compaq 6730s                | Notebook    | [073756d958](https://linux-hardware.org/?probe=073756d958) | Nov 03, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [2de4949247](https://linux-hardware.org/?probe=2de4949247) | Nov 01, 2023 |
| Lenovo        | V17 G2 ITL 82NX             | Notebook    | [d267711f7e](https://linux-hardware.org/?probe=d267711f7e) | Nov 01, 2023 |
| AMI           | Intel                       | Notebook    | [42ebe1755f](https://linux-hardware.org/?probe=42ebe1755f) | Oct 30, 2023 |
| Dell          | 0K9T56 A00                  | All in one  | [e02693091f](https://linux-hardware.org/?probe=e02693091f) | Oct 25, 2023 |
| Dell          | 0K9T56 A00                  | All in one  | [cc8dcd6a8d](https://linux-hardware.org/?probe=cc8dcd6a8d) | Oct 24, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [f6a5fcd391](https://linux-hardware.org/?probe=f6a5fcd391) | Oct 21, 2023 |
| Acer          | Extensa 2519                | Notebook    | [4d8970a1f5](https://linux-hardware.org/?probe=4d8970a1f5) | Oct 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [20c026b8a7](https://linux-hardware.org/?probe=20c026b8a7) | Oct 16, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [da0024090d](https://linux-hardware.org/?probe=da0024090d) | Oct 16, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [e4f9055fce](https://linux-hardware.org/?probe=e4f9055fce) | Oct 09, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [e583e35b95](https://linux-hardware.org/?probe=e583e35b95) | Oct 03, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [538889d79f](https://linux-hardware.org/?probe=538889d79f) | Oct 03, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [d5e4f28683](https://linux-hardware.org/?probe=d5e4f28683) | Oct 02, 2023 |
| Fujitsu Si... | AMILO A1650G                | Notebook    | [ec61a60044](https://linux-hardware.org/?probe=ec61a60044) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c00e994c2c](https://linux-hardware.org/?probe=c00e994c2c) | Sep 21, 2023 |
| HP            | 620                         | Notebook    | [6fd1497e1a](https://linux-hardware.org/?probe=6fd1497e1a) | Sep 10, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [af96cda252](https://linux-hardware.org/?probe=af96cda252) | Sep 02, 2023 |
| Foxconn       | 2A92                        | Desktop     | [50ca8342d7](https://linux-hardware.org/?probe=50ca8342d7) | Sep 01, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [c8cc960675](https://linux-hardware.org/?probe=c8cc960675) | Aug 21, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [768e7b97fc](https://linux-hardware.org/?probe=768e7b97fc) | Aug 19, 2023 |
| ASUSTek       | F1A75-M LE                  | Desktop     | [f059d25382](https://linux-hardware.org/?probe=f059d25382) | Aug 14, 2023 |
| Dell          | Latitude E5410              | Notebook    | [4ae8d448a2](https://linux-hardware.org/?probe=4ae8d448a2) | Aug 14, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [64a738d034](https://linux-hardware.org/?probe=64a738d034) | Aug 13, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [44556227ff](https://linux-hardware.org/?probe=44556227ff) | Aug 05, 2023 |
| OEM           | Intel H81                   | Desktop     | [82606b5050](https://linux-hardware.org/?probe=82606b5050) | Aug 03, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [482b97d3de](https://linux-hardware.org/?probe=482b97d3de) | Aug 02, 2023 |
| Gigabyte      | B560 AORUS PRO AX           | Desktop     | [c7e057da76](https://linux-hardware.org/?probe=c7e057da76) | Aug 02, 2023 |
| HP            | 620                         | Notebook    | [4c04d9d11e](https://linux-hardware.org/?probe=4c04d9d11e) | Aug 01, 2023 |
| HP            | 620                         | Notebook    | [eafc7ac5c3](https://linux-hardware.org/?probe=eafc7ac5c3) | Aug 01, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [9042ebc249](https://linux-hardware.org/?probe=9042ebc249) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [f84a39b436](https://linux-hardware.org/?probe=f84a39b436) | Jul 31, 2023 |
| Intel         | JSL MRD                     | Desktop     | [feb19ee725](https://linux-hardware.org/?probe=feb19ee725) | Jul 29, 2023 |
| Intel         | JSL MRD                     | Desktop     | [ca5990cfa3](https://linux-hardware.org/?probe=ca5990cfa3) | Jul 29, 2023 |
| ASUSTek       | LEUCITE3                    | Desktop     | [bb2046286f](https://linux-hardware.org/?probe=bb2046286f) | Jul 26, 2023 |
| ASUSTek       | LEUCITE3                    | Desktop     | [6ced09890f](https://linux-hardware.org/?probe=6ced09890f) | Jul 26, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [88f60930be](https://linux-hardware.org/?probe=88f60930be) | Jul 26, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [fd43074149](https://linux-hardware.org/?probe=fd43074149) | Jul 26, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [31c0d94d23](https://linux-hardware.org/?probe=31c0d94d23) | Jul 18, 2023 |
| CONNEX        | L1415-BAY                   | Notebook    | [8f5663e9c8](https://linux-hardware.org/?probe=8f5663e9c8) | Jul 18, 2023 |
| ASRock        | B660M-HDV                   | Desktop     | [3a0685bcf0](https://linux-hardware.org/?probe=3a0685bcf0) | Jul 18, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [18f41b2be6](https://linux-hardware.org/?probe=18f41b2be6) | Jul 17, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [782127b6f6](https://linux-hardware.org/?probe=782127b6f6) | Jul 17, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [d1ef43e488](https://linux-hardware.org/?probe=d1ef43e488) | Jul 16, 2023 |
| Dell          | System XPS L502X            | Notebook    | [e6b4c3cf4e](https://linux-hardware.org/?probe=e6b4c3cf4e) | Jul 12, 2023 |
| Acer          | Aspire ES1-511              | Notebook    | [1e7434d3b0](https://linux-hardware.org/?probe=1e7434d3b0) | Jul 10, 2023 |
| Medion        | MS-7667                     | Desktop     | [52ff08b634](https://linux-hardware.org/?probe=52ff08b634) | Jul 09, 2023 |
| HP            | 620                         | Notebook    | [5f88c564fd](https://linux-hardware.org/?probe=5f88c564fd) | Jul 08, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [ab21b766b6](https://linux-hardware.org/?probe=ab21b766b6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [5bba6eb442](https://linux-hardware.org/?probe=5bba6eb442) | Jul 07, 2023 |
| ASUSTek       | GL703VD                     | Notebook    | [68235880f7](https://linux-hardware.org/?probe=68235880f7) | Jul 06, 2023 |
| AOpen         | D1009 A1A4                  | Desktop     | [2819e086aa](https://linux-hardware.org/?probe=2819e086aa) | Jul 02, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [d04862302e](https://linux-hardware.org/?probe=d04862302e) | Jul 01, 2023 |
| Alienware     | m16 R1 AMD                  | Notebook    | [291c477bd0](https://linux-hardware.org/?probe=291c477bd0) | Jul 01, 2023 |
| ASUSTek       | X201EV                      | Notebook    | [a3fe51bc01](https://linux-hardware.org/?probe=a3fe51bc01) | Jun 30, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [14a983e6d3](https://linux-hardware.org/?probe=14a983e6d3) | Jun 30, 2023 |
| ASUSTek       | X201EV                      | Notebook    | [3cffef17f3](https://linux-hardware.org/?probe=3cffef17f3) | Jun 30, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [cd65c92d12](https://linux-hardware.org/?probe=cd65c92d12) | Jun 27, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [e3b1cdc71c](https://linux-hardware.org/?probe=e3b1cdc71c) | Jun 27, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f4540c6370](https://linux-hardware.org/?probe=f4540c6370) | Jun 27, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [cadc656340](https://linux-hardware.org/?probe=cadc656340) | Jun 25, 2023 |
| HP            | Spectre Folio Convertibl... | Convertible | [123d2215a1](https://linux-hardware.org/?probe=123d2215a1) | Jun 25, 2023 |
| Dell          | Latitude E6510              | Notebook    | [a85838194d](https://linux-hardware.org/?probe=a85838194d) | Jun 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [ed43d5454c](https://linux-hardware.org/?probe=ed43d5454c) | Jun 18, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [56c650c8b1](https://linux-hardware.org/?probe=56c650c8b1) | Jun 15, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c8d7ef5b6](https://linux-hardware.org/?probe=2c8d7ef5b6) | Jun 12, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [bfde2cf63d](https://linux-hardware.org/?probe=bfde2cf63d) | Jun 10, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7c79725474](https://linux-hardware.org/?probe=7c79725474) | Jun 10, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [6e5323aa42](https://linux-hardware.org/?probe=6e5323aa42) | Jun 09, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [fc4b07cbb0](https://linux-hardware.org/?probe=fc4b07cbb0) | Jun 09, 2023 |
| Dell          | Latitude E6540              | Notebook    | [85520c9a0b](https://linux-hardware.org/?probe=85520c9a0b) | Jun 08, 2023 |
| Dell          | Latitude E6540              | Notebook    | [30f20f78ac](https://linux-hardware.org/?probe=30f20f78ac) | Jun 08, 2023 |
| ASUSTek       | X205TA                      | Notebook    | [4c56663011](https://linux-hardware.org/?probe=4c56663011) | Jun 07, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fa8eba55f0](https://linux-hardware.org/?probe=fa8eba55f0) | Jun 05, 2023 |
| Dell          | Latitude E6510              | Notebook    | [49743c8db7](https://linux-hardware.org/?probe=49743c8db7) | Jun 04, 2023 |
| Dell          | Latitude E6510              | Notebook    | [51c45b0aa7](https://linux-hardware.org/?probe=51c45b0aa7) | Jun 04, 2023 |
| MSI           | U200                        | Notebook    | [01900b8117](https://linux-hardware.org/?probe=01900b8117) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [51d10ac11e](https://linux-hardware.org/?probe=51d10ac11e) | Jun 02, 2023 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [c64fbbcad9](https://linux-hardware.org/?probe=c64fbbcad9) | Jun 02, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [c46684adac](https://linux-hardware.org/?probe=c46684adac) | Jun 02, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [7070e55aa0](https://linux-hardware.org/?probe=7070e55aa0) | Jun 01, 2023 |
| Dell          | Latitude 5540               | Notebook    | [98ec8ec8bf](https://linux-hardware.org/?probe=98ec8ec8bf) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [4a2e70149f](https://linux-hardware.org/?probe=4a2e70149f) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [b8fb5e55bc](https://linux-hardware.org/?probe=b8fb5e55bc) | Jun 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [351ca28b27](https://linux-hardware.org/?probe=351ca28b27) | May 29, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fe4a8422c8](https://linux-hardware.org/?probe=fe4a8422c8) | May 29, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | Notebook    | [d83ee3fda2](https://linux-hardware.org/?probe=d83ee3fda2) | May 28, 2023 |
| Dell          | Latitude E6510              | Notebook    | [9edaeb2ffa](https://linux-hardware.org/?probe=9edaeb2ffa) | May 25, 2023 |
| Sony          | SVE1513Q1ESI                | Notebook    | [422e8954f2](https://linux-hardware.org/?probe=422e8954f2) | May 24, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [ef088af2df](https://linux-hardware.org/?probe=ef088af2df) | May 23, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [28a8978593](https://linux-hardware.org/?probe=28a8978593) | May 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [adf9fc9bdb](https://linux-hardware.org/?probe=adf9fc9bdb) | May 22, 2023 |
| Dell          | Latitude E6510              | Notebook    | [342b8d094e](https://linux-hardware.org/?probe=342b8d094e) | May 20, 2023 |
| Dell          | Latitude E6510              | Notebook    | [4d606396f8](https://linux-hardware.org/?probe=4d606396f8) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [5ae19394fc](https://linux-hardware.org/?probe=5ae19394fc) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [14548bc77a](https://linux-hardware.org/?probe=14548bc77a) | May 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e6746606b4](https://linux-hardware.org/?probe=e6746606b4) | May 19, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [5ca1acbf9b](https://linux-hardware.org/?probe=5ca1acbf9b) | May 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [58066198c4](https://linux-hardware.org/?probe=58066198c4) | May 18, 2023 |
| Dell          | Latitude 3190               | Notebook    | [1d867407a6](https://linux-hardware.org/?probe=1d867407a6) | May 15, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [4c33c99aab](https://linux-hardware.org/?probe=4c33c99aab) | May 14, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [d3107c9603](https://linux-hardware.org/?probe=d3107c9603) | May 14, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [3bc96663a8](https://linux-hardware.org/?probe=3bc96663a8) | May 14, 2023 |
| ASUSTek       | X202E                       | Notebook    | [d6b7617a17](https://linux-hardware.org/?probe=d6b7617a17) | May 14, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [08afd40365](https://linux-hardware.org/?probe=08afd40365) | May 13, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [ebd2a32ce2](https://linux-hardware.org/?probe=ebd2a32ce2) | May 12, 2023 |
| Acer          | Extensa 5220                | Notebook    | [935b52f12c](https://linux-hardware.org/?probe=935b52f12c) | May 12, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [352c0902e9](https://linux-hardware.org/?probe=352c0902e9) | May 11, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [81c255952d](https://linux-hardware.org/?probe=81c255952d) | May 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0GK0... | Notebook    | [177f30243c](https://linux-hardware.org/?probe=177f30243c) | May 08, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fb4df1325b](https://linux-hardware.org/?probe=fb4df1325b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [f894b9a2c4](https://linux-hardware.org/?probe=f894b9a2c4) | May 07, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [af9c3172bc](https://linux-hardware.org/?probe=af9c3172bc) | May 05, 2023 |
| HP            | Pro Tablet 10 EE G1         | Notebook    | [6af53fb237](https://linux-hardware.org/?probe=6af53fb237) | May 05, 2023 |
| Lenovo        | ThinkPad T460s 20F9003GU... | Notebook    | [7a570efe74](https://linux-hardware.org/?probe=7a570efe74) | May 05, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [8349b363f4](https://linux-hardware.org/?probe=8349b363f4) | May 03, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [49971d9c29](https://linux-hardware.org/?probe=49971d9c29) | May 03, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [97d802a5d6](https://linux-hardware.org/?probe=97d802a5d6) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [6d2d5b74d2](https://linux-hardware.org/?probe=6d2d5b74d2) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e8721751c6](https://linux-hardware.org/?probe=e8721751c6) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e426e8e40b](https://linux-hardware.org/?probe=e426e8e40b) | May 03, 2023 |
| Lenovo        | ThinkPad X260 20F5S89L02    | Notebook    | [4e2f57ccc3](https://linux-hardware.org/?probe=4e2f57ccc3) | May 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [a36c4e671d](https://linux-hardware.org/?probe=a36c4e671d) | May 02, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [f62abcbed6](https://linux-hardware.org/?probe=f62abcbed6) | May 02, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [2d1086090c](https://linux-hardware.org/?probe=2d1086090c) | May 01, 2023 |
| Dell          | Latitude 3190               | Notebook    | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [e812a255a4](https://linux-hardware.org/?probe=e812a255a4) | May 01, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [3e154e4ccc](https://linux-hardware.org/?probe=3e154e4ccc) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [2628c3040f](https://linux-hardware.org/?probe=2628c3040f) | Apr 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [539369db0e](https://linux-hardware.org/?probe=539369db0e) | Apr 28, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [014215365a](https://linux-hardware.org/?probe=014215365a) | Apr 27, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [4939e609de](https://linux-hardware.org/?probe=4939e609de) | Apr 24, 2023 |
| HP            | G42                         | Notebook    | [58b0a0981e](https://linux-hardware.org/?probe=58b0a0981e) | Apr 23, 2023 |
| HP            | 090Ch                       | Desktop     | [01d609bbab](https://linux-hardware.org/?probe=01d609bbab) | Apr 23, 2023 |
| ASRock        | Z690 Pro RS                 | Desktop     | [acb9cde3d7](https://linux-hardware.org/?probe=acb9cde3d7) | Apr 23, 2023 |
| Gateway       | DX4860                      | Desktop     | [5583641f1b](https://linux-hardware.org/?probe=5583641f1b) | Apr 22, 2023 |
| Compal        | HEL81I                      | Notebook    | [426788b00c](https://linux-hardware.org/?probe=426788b00c) | Apr 22, 2023 |
| Google        | Akali 360                   | Notebook    | [2d18714bb2](https://linux-hardware.org/?probe=2d18714bb2) | Apr 20, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1B30... | Notebook    | [c0207e5f9a](https://linux-hardware.org/?probe=c0207e5f9a) | Apr 19, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [843dd1e105](https://linux-hardware.org/?probe=843dd1e105) | Apr 18, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [c271ba95b9](https://linux-hardware.org/?probe=c271ba95b9) | Apr 16, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [494fc3e648](https://linux-hardware.org/?probe=494fc3e648) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [aa571700ad](https://linux-hardware.org/?probe=aa571700ad) | Apr 13, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | Notebook    | [3d53b9ee9e](https://linux-hardware.org/?probe=3d53b9ee9e) | Apr 12, 2023 |
| HP            | 3646h                       | Desktop     | [c36653d824](https://linux-hardware.org/?probe=c36653d824) | Apr 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c2a70674ac](https://linux-hardware.org/?probe=c2a70674ac) | Apr 10, 2023 |
| Lenovo        | ThinkPad X220 4290WC7       | Notebook    | [07ed4faaa0](https://linux-hardware.org/?probe=07ed4faaa0) | Apr 10, 2023 |
| HP            | 18E5                        | Desktop     | [441d2678ff](https://linux-hardware.org/?probe=441d2678ff) | Apr 07, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [aea33c89a1](https://linux-hardware.org/?probe=aea33c89a1) | Apr 05, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [86d8d7f80f](https://linux-hardware.org/?probe=86d8d7f80f) | Apr 05, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a1fa664431](https://linux-hardware.org/?probe=a1fa664431) | Apr 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9a5c9ee256](https://linux-hardware.org/?probe=9a5c9ee256) | Apr 02, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [ef684c34bb](https://linux-hardware.org/?probe=ef684c34bb) | Mar 28, 2023 |
| HP            | 3029h                       | Desktop     | [153b913406](https://linux-hardware.org/?probe=153b913406) | Mar 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [757f1fc2e7](https://linux-hardware.org/?probe=757f1fc2e7) | Mar 27, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [20d8516896](https://linux-hardware.org/?probe=20d8516896) | Mar 26, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [498bb39808](https://linux-hardware.org/?probe=498bb39808) | Mar 24, 2023 |
| Unknown       | GB01                        | Desktop     | [ad0e76307c](https://linux-hardware.org/?probe=ad0e76307c) | Mar 24, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [2706ed39b7](https://linux-hardware.org/?probe=2706ed39b7) | Mar 23, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| HP            | 3048h                       | Desktop     | [cd326ce9fa](https://linux-hardware.org/?probe=cd326ce9fa) | Mar 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f4bea67dcc](https://linux-hardware.org/?probe=f4bea67dcc) | Mar 20, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [978df2886a](https://linux-hardware.org/?probe=978df2886a) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ac5495bdb4](https://linux-hardware.org/?probe=ac5495bdb4) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [45d6f54263](https://linux-hardware.org/?probe=45d6f54263) | Mar 19, 2023 |
| Samsung       | 950QDB                      | Convertible | [e16175f1c5](https://linux-hardware.org/?probe=e16175f1c5) | Mar 19, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| Dell          | Latitude E5570              | Notebook    | [dc6436b8b2](https://linux-hardware.org/?probe=dc6436b8b2) | Mar 16, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [12e9972d5a](https://linux-hardware.org/?probe=12e9972d5a) | Mar 15, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [46cb84be25](https://linux-hardware.org/?probe=46cb84be25) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [9f3f315f73](https://linux-hardware.org/?probe=9f3f315f73) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [42653f8c2a](https://linux-hardware.org/?probe=42653f8c2a) | Mar 14, 2023 |
| MSI           | CSM-H87M-G43                | Desktop     | [9df13e200e](https://linux-hardware.org/?probe=9df13e200e) | Mar 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [7ccc0f584e](https://linux-hardware.org/?probe=7ccc0f584e) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | Desktop     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| Dell          | Latitude 3190               | Notebook    | [97cc3ffc79](https://linux-hardware.org/?probe=97cc3ffc79) | Mar 13, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [7d35815562](https://linux-hardware.org/?probe=7d35815562) | Mar 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fd0eabacbf](https://linux-hardware.org/?probe=fd0eabacbf) | Mar 08, 2023 |
| Lenovo        | ThinkPad E490 20N9S21H00    | Notebook    | [0bb64aee2c](https://linux-hardware.org/?probe=0bb64aee2c) | Mar 08, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [153652da71](https://linux-hardware.org/?probe=153652da71) | Mar 07, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a3a4113ab4](https://linux-hardware.org/?probe=a3a4113ab4) | Mar 06, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| HP            | 255 G3                      | Notebook    | [9ccab85062](https://linux-hardware.org/?probe=9ccab85062) | Mar 04, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [a84948f124](https://linux-hardware.org/?probe=a84948f124) | Mar 04, 2023 |
| HP            | 8184 X4                     | Desktop     | [b42f6862c7](https://linux-hardware.org/?probe=b42f6862c7) | Mar 04, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [1a0011a745](https://linux-hardware.org/?probe=1a0011a745) | Mar 03, 2023 |
| HP            | 620                         | Notebook    | [421e31de43](https://linux-hardware.org/?probe=421e31de43) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [5718d685e4](https://linux-hardware.org/?probe=5718d685e4) | Mar 02, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1b68738664](https://linux-hardware.org/?probe=1b68738664) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [5fe3c354ff](https://linux-hardware.org/?probe=5fe3c354ff) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [a15227fc75](https://linux-hardware.org/?probe=a15227fc75) | Mar 02, 2023 |
| Dell          | Latitude 3190               | Notebook    | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | 255 G3                      | Notebook    | [49dccf5753](https://linux-hardware.org/?probe=49dccf5753) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [73570a1c9a](https://linux-hardware.org/?probe=73570a1c9a) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [e82b3753f7](https://linux-hardware.org/?probe=e82b3753f7) | Feb 26, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [b6321ee5a4](https://linux-hardware.org/?probe=b6321ee5a4) | Feb 25, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [efc95d4697](https://linux-hardware.org/?probe=efc95d4697) | Feb 25, 2023 |
| Unknown       | 1.0                         | Desktop     | [bab30a1ac1](https://linux-hardware.org/?probe=bab30a1ac1) | Feb 24, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [419493491e](https://linux-hardware.org/?probe=419493491e) | Feb 23, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [e386073c5d](https://linux-hardware.org/?probe=e386073c5d) | Feb 23, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [0e9172bdd5](https://linux-hardware.org/?probe=0e9172bdd5) | Feb 21, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [adc356a0a8](https://linux-hardware.org/?probe=adc356a0a8) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d09dc2494a](https://linux-hardware.org/?probe=d09dc2494a) | Feb 21, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| HP            | ProBook 445 G1              | Notebook    | [bcd5c952f1](https://linux-hardware.org/?probe=bcd5c952f1) | Feb 18, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [351a527308](https://linux-hardware.org/?probe=351a527308) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [aba30bb2d8](https://linux-hardware.org/?probe=aba30bb2d8) | Feb 17, 2023 |
| RTD Embedd... | CMA34CR                     | Notebook    | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [db10d61562](https://linux-hardware.org/?probe=db10d61562) | Feb 16, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [9d060a9cc6](https://linux-hardware.org/?probe=9d060a9cc6) | Feb 15, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [0cbe95253a](https://linux-hardware.org/?probe=0cbe95253a) | Feb 15, 2023 |
| Linx          | LINX1010B                   | Notebook    | [5ca377461f](https://linux-hardware.org/?probe=5ca377461f) | Feb 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [482c922bbc](https://linux-hardware.org/?probe=482c922bbc) | Feb 14, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [3cccebc1ef](https://linux-hardware.org/?probe=3cccebc1ef) | Feb 12, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [dcb95dba09](https://linux-hardware.org/?probe=dcb95dba09) | Feb 12, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [86103b5293](https://linux-hardware.org/?probe=86103b5293) | Feb 12, 2023 |
| Medion        | P6634                       | Notebook    | [ec0002869f](https://linux-hardware.org/?probe=ec0002869f) | Feb 11, 2023 |
| Medion        | P6634                       | Notebook    | [15c3260ecf](https://linux-hardware.org/?probe=15c3260ecf) | Feb 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [13492935fd](https://linux-hardware.org/?probe=13492935fd) | Feb 09, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [d32909e1a4](https://linux-hardware.org/?probe=d32909e1a4) | Feb 09, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [700f0ded17](https://linux-hardware.org/?probe=700f0ded17) | Feb 08, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [b4c5f2e2de](https://linux-hardware.org/?probe=b4c5f2e2de) | Feb 08, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [b4b0bee06c](https://linux-hardware.org/?probe=b4b0bee06c) | Feb 08, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [11f3874a6f](https://linux-hardware.org/?probe=11f3874a6f) | Feb 07, 2023 |
| HP            | 450                         | Notebook    | [26d3505372](https://linux-hardware.org/?probe=26d3505372) | Feb 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [48f423dfae](https://linux-hardware.org/?probe=48f423dfae) | Feb 05, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [ed6c6cc366](https://linux-hardware.org/?probe=ed6c6cc366) | Feb 05, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [7e94a2328d](https://linux-hardware.org/?probe=7e94a2328d) | Feb 05, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [a2ab102eeb](https://linux-hardware.org/?probe=a2ab102eeb) | Feb 04, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [42e242e6bf](https://linux-hardware.org/?probe=42e242e6bf) | Feb 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [793f52c99a](https://linux-hardware.org/?probe=793f52c99a) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ddb7f53b34](https://linux-hardware.org/?probe=ddb7f53b34) | Feb 03, 2023 |
| ECS           | P4M800PRO-M                 | Desktop     | [f446d61863](https://linux-hardware.org/?probe=f446d61863) | Feb 02, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [43101dad89](https://linux-hardware.org/?probe=43101dad89) | Feb 02, 2023 |
| Intel         | D34010WYK H14771-303        | Desktop     | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [dd017ac78a](https://linux-hardware.org/?probe=dd017ac78a) | Jan 31, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [a32a9ba13a](https://linux-hardware.org/?probe=a32a9ba13a) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [1d28352c0f](https://linux-hardware.org/?probe=1d28352c0f) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | Notebook    | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [554aa8592c](https://linux-hardware.org/?probe=554aa8592c) | Jan 28, 2023 |
| BESSTAR Te... | UM340                       | Desktop     | [77efbbb270](https://linux-hardware.org/?probe=77efbbb270) | Jan 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [3d1f5b0ee9](https://linux-hardware.org/?probe=3d1f5b0ee9) | Jan 23, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [e81c0bcfc4](https://linux-hardware.org/?probe=e81c0bcfc4) | Jan 22, 2023 |
| AMI           | Intel                       | Notebook    | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [7671c99c3c](https://linux-hardware.org/?probe=7671c99c3c) | Jan 19, 2023 |
| Dell          | Latitude 3190               | Notebook    | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| HP            | 3396                        | Desktop     | [2085b91098](https://linux-hardware.org/?probe=2085b91098) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [cb84c73399](https://linux-hardware.org/?probe=cb84c73399) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [4a07474fa4](https://linux-hardware.org/?probe=4a07474fa4) | Jan 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge 031925U       | Notebook    | [95feaf21b4](https://linux-hardware.org/?probe=95feaf21b4) | Jan 07, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Toshiba       | Satellite M70               | Notebook    | [616dbdfa63](https://linux-hardware.org/?probe=616dbdfa63) | Jan 05, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [677feeeca9](https://linux-hardware.org/?probe=677feeeca9) | Jan 03, 2023 |
| Dell          | Latitude 3190               | Notebook    | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [c3d5155637](https://linux-hardware.org/?probe=c3d5155637) | Jan 01, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [6c8ec40821](https://linux-hardware.org/?probe=6c8ec40821) | Dec 25, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [c195f58592](https://linux-hardware.org/?probe=c195f58592) | Dec 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [148add29a4](https://linux-hardware.org/?probe=148add29a4) | Dec 24, 2022 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | Desktop     | [70e125f0d0](https://linux-hardware.org/?probe=70e125f0d0) | Dec 23, 2022 |
| Dell          | Latitude 3190               | Notebook    | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [916375929d](https://linux-hardware.org/?probe=916375929d) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [75126bccca](https://linux-hardware.org/?probe=75126bccca) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | Notebook    | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [06e7a6dfe7](https://linux-hardware.org/?probe=06e7a6dfe7) | Dec 12, 2022 |
| Dell          | Latitude 3190               | Notebook    | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [7cefe54b56](https://linux-hardware.org/?probe=7cefe54b56) | Dec 12, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [a583a55071](https://linux-hardware.org/?probe=a583a55071) | Dec 10, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [2e76f24d6a](https://linux-hardware.org/?probe=2e76f24d6a) | Dec 09, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [36b349ff7f](https://linux-hardware.org/?probe=36b349ff7f) | Dec 08, 2022 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | Desktop     | [03cd265cef](https://linux-hardware.org/?probe=03cd265cef) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6487bbd7b7](https://linux-hardware.org/?probe=6487bbd7b7) | Dec 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | Desktop     | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| Acer          | Aspire ES1-732              | Notebook    | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [057b0039b7](https://linux-hardware.org/?probe=057b0039b7) | Dec 01, 2022 |
| HP            | 304Ah                       | Desktop     | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [8fc84889a5](https://linux-hardware.org/?probe=8fc84889a5) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b47217fa0c](https://linux-hardware.org/?probe=b47217fa0c) | Nov 25, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [3f08c2fb11](https://linux-hardware.org/?probe=3f08c2fb11) | Nov 25, 2022 |
| Sony          | VGN-TZ3RXN_B                | Notebook    | [5986f007c8](https://linux-hardware.org/?probe=5986f007c8) | Nov 22, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [614f59ceaf](https://linux-hardware.org/?probe=614f59ceaf) | Nov 22, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| GEO           | GeoFlex 340                 | Convertible | [6e930633c0](https://linux-hardware.org/?probe=6e930633c0) | Nov 18, 2022 |
| Dell          | 0J051K A00                  | Server      | [cb579ef51b](https://linux-hardware.org/?probe=cb579ef51b) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [9884754d7b](https://linux-hardware.org/?probe=9884754d7b) | Nov 14, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0e09796a40](https://linux-hardware.org/?probe=0e09796a40) | Nov 14, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [cb36e9d15c](https://linux-hardware.org/?probe=cb36e9d15c) | Nov 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0459e9f47e](https://linux-hardware.org/?probe=0459e9f47e) | Nov 06, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [91d85f8376](https://linux-hardware.org/?probe=91d85f8376) | Nov 05, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [9c72952af7](https://linux-hardware.org/?probe=9c72952af7) | Nov 04, 2022 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [c165c40a7e](https://linux-hardware.org/?probe=c165c40a7e) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [9819da96f2](https://linux-hardware.org/?probe=9819da96f2) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| SANTECH       | X170KM-G                    | Notebook    | [073f9a1d24](https://linux-hardware.org/?probe=073f9a1d24) | Nov 01, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Vulcan Ele... | Excursion XB                | Notebook    | [30ceac1216](https://linux-hardware.org/?probe=30ceac1216) | Oct 31, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [423ad57e72](https://linux-hardware.org/?probe=423ad57e72) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [f8b4ce6c3f](https://linux-hardware.org/?probe=f8b4ce6c3f) | Oct 29, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [6383143b5b](https://linux-hardware.org/?probe=6383143b5b) | Oct 28, 2022 |
| Biostar       | H61MH                       | Desktop     | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [226e4471e1](https://linux-hardware.org/?probe=226e4471e1) | Oct 27, 2022 |
| Lenovo        | 318E NOK                    | Desktop     | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [59dabaff86](https://linux-hardware.org/?probe=59dabaff86) | Oct 23, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [d34df28814](https://linux-hardware.org/?probe=d34df28814) | Oct 22, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [aa571dded9](https://linux-hardware.org/?probe=aa571dded9) | Oct 22, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [c389b44ab5](https://linux-hardware.org/?probe=c389b44ab5) | Oct 21, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [95ca32a110](https://linux-hardware.org/?probe=95ca32a110) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e33a95e0b0](https://linux-hardware.org/?probe=e33a95e0b0) | Oct 18, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [b6c2cf5b2e](https://linux-hardware.org/?probe=b6c2cf5b2e) | Oct 17, 2022 |
| Dell          | Latitude 3190               | Notebook    | [342d7acb67](https://linux-hardware.org/?probe=342d7acb67) | Oct 17, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [1f6ff0e213](https://linux-hardware.org/?probe=1f6ff0e213) | Oct 17, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [09af41cbf8](https://linux-hardware.org/?probe=09af41cbf8) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b3267ce847](https://linux-hardware.org/?probe=b3267ce847) | Oct 15, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [209d243342](https://linux-hardware.org/?probe=209d243342) | Oct 15, 2022 |
| Pegatron      | NARRA3                      | Desktop     | [1588e60c57](https://linux-hardware.org/?probe=1588e60c57) | Oct 12, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| Medion        | E7424 MD60750               | Notebook    | [7c9ea600ad](https://linux-hardware.org/?probe=7c9ea600ad) | Oct 11, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [f2c440fdf6](https://linux-hardware.org/?probe=f2c440fdf6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [8159009c50](https://linux-hardware.org/?probe=8159009c50) | Oct 05, 2022 |
| Google        | Setzer                      | Notebook    | [6bafaabd48](https://linux-hardware.org/?probe=6bafaabd48) | Oct 04, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| Dell          | Latitude 7490               | Notebook    | [872aafeb50](https://linux-hardware.org/?probe=872aafeb50) | Oct 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f97d2b97ad](https://linux-hardware.org/?probe=f97d2b97ad) | Oct 01, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [992cf7d019](https://linux-hardware.org/?probe=992cf7d019) | Sep 30, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [5b7d4c6b7a](https://linux-hardware.org/?probe=5b7d4c6b7a) | Sep 27, 2022 |
| Dell          | Precision 7520              | Notebook    | [a7b1df0888](https://linux-hardware.org/?probe=a7b1df0888) | Sep 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [6182e4ef84](https://linux-hardware.org/?probe=6182e4ef84) | Sep 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [de3a2e822c](https://linux-hardware.org/?probe=de3a2e822c) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| HP            | 1632                        | Desktop     | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [b4e36a92c7](https://linux-hardware.org/?probe=b4e36a92c7) | Sep 08, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [ac71ea732f](https://linux-hardware.org/?probe=ac71ea732f) | Sep 07, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| MSI           | Modern 14 B11MOL            | Notebook    | [1ce0bfd512](https://linux-hardware.org/?probe=1ce0bfd512) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7702adff5d](https://linux-hardware.org/?probe=7702adff5d) | Sep 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | Notebook    | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | Notebook    | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | Notebook    | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Biostar       | A780L3B                     | Desktop     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [83e026f682](https://linux-hardware.org/?probe=83e026f682) | Aug 12, 2022 |
| Dell          | System XPS 15Z              | Notebook    | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Lenovo        | ThinkPad T560 20FJS0EP00    | Notebook    | [dda2c8f199](https://linux-hardware.org/?probe=dda2c8f199) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| Dell          | Precision 7720              | Notebook    | [9f17ade16f](https://linux-hardware.org/?probe=9f17ade16f) | Aug 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [68e632a5f6](https://linux-hardware.org/?probe=68e632a5f6) | Aug 08, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [d49c27a24a](https://linux-hardware.org/?probe=d49c27a24a) | Jul 29, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| MP            | MS-7848                     | Desktop     | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [56424874b7](https://linux-hardware.org/?probe=56424874b7) | Jul 11, 2022 |
| Dell          | 0DR845                      | Desktop     | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| Alienware     | 13 R2                       | Notebook    | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | Notebook    | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [77c632ea8e](https://linux-hardware.org/?probe=77c632ea8e) | Jul 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell          | 0DR845                      | Desktop     | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | Notebook    | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | Notebook    | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | Notebook    | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c21cd1f8f3](https://linux-hardware.org/?probe=c21cd1f8f3) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | Notebook    | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| AZW           | SER                         | Mini pc     | [9da3c6ca34](https://linux-hardware.org/?probe=9da3c6ca34) | May 18, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | Notebook    | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Intel         | V1.3                        | Desktop     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | Notebook    | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | Desktop     | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [7cc89d3cba](https://linux-hardware.org/?probe=7cc89d3cba) | Apr 14, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [5cd6adf199](https://linux-hardware.org/?probe=5cd6adf199) | Apr 14, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [084e2350e9](https://linux-hardware.org/?probe=084e2350e9) | Apr 05, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [83dab83528](https://linux-hardware.org/?probe=83dab83528) | Apr 01, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | Notebook    | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | Notebook    | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| Sony          | SVE1513Q1ESI                | Notebook    | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | Notebook    | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | Notebook    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | Notebook    | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | Notebook    | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7cc374183b](https://linux-hardware.org/?probe=7cc374183b) | Dec 30, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9147191a67](https://linux-hardware.org/?probe=9147191a67) | Dec 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| GALAX         | B550M                       | Desktop     | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bb58f4914e](https://linux-hardware.org/?probe=bb58f4914e) | Nov 21, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | Notebook    | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | E402MA                      | Notebook    | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | Notebook    | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/MX_21/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.0-21-amd64            | 40        | 9.95%   |
| 6.0.0-6mx-amd64            | 37        | 9.2%    |
| 5.10.0-23-amd64            | 25        | 6.22%   |
| 5.10.0-20-amd64            | 24        | 5.97%   |
| 5.10.0-18-amd64            | 20        | 4.98%   |
| 5.10.0-13-amd64            | 20        | 4.98%   |
| 5.10.0-9-amd64             | 18        | 4.48%   |
| 5.10.0-19-amd64            | 18        | 4.48%   |
| 5.14.0-4mx-amd64           | 17        | 4.23%   |
| 5.16.0-5mx-amd64           | 14        | 3.48%   |
| 5.10.0-16-amd64            | 13        | 3.23%   |
| 5.18.0-4mx-amd64           | 10        | 2.49%   |
| 5.10.0-11-amd64            | 8         | 1.99%   |
| 6.0.0-10.1-liquorix-amd64  | 7         | 1.74%   |
| 5.10.0-22-amd64            | 7         | 1.74%   |
| 5.10.0-14-amd64            | 7         | 1.74%   |
| 5.10.0-15-amd64            | 6         | 1.49%   |
| 6.0.0-4mx-amd64            | 5         | 1.24%   |
| 5.19.0-2mx-amd64           | 5         | 1.24%   |
| 5.10.0-17-amd64            | 4         | 1%      |
| 5.10.0-10-amd64            | 4         | 1%      |
| 6.0.0-3mx-amd64            | 3         | 0.75%   |
| 5.16.0-6mx-amd64           | 3         | 0.75%   |
| 5.16.0-18.1-liquorix-amd64 | 3         | 0.75%   |
| 5.10.0-26-amd64            | 3         | 0.75%   |
| 5.10.0-25-amd64            | 3         | 0.75%   |
| 5.10.0-20-686-pae          | 3         | 0.75%   |
| 6.1.15-2-liquorix-amd64    | 2         | 0.5%    |
| 6.1.0-9mx-ahs-amd64        | 2         | 0.5%    |
| 6.1.0-8mx-ahs-amd64        | 2         | 0.5%    |
| 6.1.0-4mx-amd64            | 2         | 0.5%    |
| 6.1.0-2mx-amd64            | 2         | 0.5%    |
| 5.19.0-17.2-liquorix-amd64 | 2         | 0.5%    |
| 5.17.0-3mx-amd64           | 2         | 0.5%    |
| 5.16.0-4mx-amd64           | 2         | 0.5%    |
| 5.14.0-3mx-amd64           | 2         | 0.5%    |
| 5.10.0-8-amd64             | 2         | 0.5%    |
| 5.10.0-23-686-pae          | 2         | 0.5%    |
| 5.10.0-18-686-pae          | 2         | 0.5%    |
| 5.10.0-13-686-pae          | 2         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 225       | 58.29%  |
| 6.0.0    | 55        | 14.25%  |
| 5.16.0   | 23        | 5.96%   |
| 5.14.0   | 20        | 5.18%   |
| 6.1.0    | 12        | 3.11%   |
| 5.18.0   | 12        | 3.11%   |
| 5.19.0   | 11        | 2.85%   |
| 5.17.0   | 6         | 1.55%   |
| 5.15.0   | 3         | 0.78%   |
| 6.1.15   | 2         | 0.52%   |
| 4.19.0   | 2         | 0.52%   |
| 6.6.0    | 1         | 0.26%   |
| 6.4.3    | 1         | 0.26%   |
| 6.4.0    | 1         | 0.26%   |
| 6.3.0    | 1         | 0.26%   |
| 6.2.7    | 1         | 0.26%   |
| 6.2.14   | 1         | 0.26%   |
| 6.1.12   | 1         | 0.26%   |
| 6.0.5    | 1         | 0.26%   |
| 5.13.0   | 1         | 0.26%   |
| 5.10.82  | 1         | 0.26%   |
| 5.10.52  | 1         | 0.26%   |
| 5.10.142 | 1         | 0.26%   |
| 5.10.113 | 1         | 0.26%   |
| 5.10.111 | 1         | 0.26%   |
| Unknown  | 1         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 230       | 59.59%  |
| 6.0     | 56        | 14.51%  |
| 5.16    | 23        | 5.96%   |
| 5.14    | 20        | 5.18%   |
| 6.1     | 15        | 3.89%   |
| 5.18    | 12        | 3.11%   |
| 5.19    | 11        | 2.85%   |
| 5.17    | 6         | 1.55%   |
| 5.15    | 3         | 0.78%   |
| 6.4     | 2         | 0.52%   |
| 6.2     | 2         | 0.52%   |
| 4.19    | 2         | 0.52%   |
| 6.6     | 1         | 0.26%   |
| 6.3     | 1         | 0.26%   |
| 5.13    | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 358       | 95.98%  |
| i686   | 15        | 4.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 279       | 73.81%  |
| KDE5             | 75        | 19.84%  |
| lightdm-xsession | 6         | 1.59%   |
| Unknown          | 5         | 1.32%   |
| GNOME            | 4         | 1.06%   |
| Budgie           | 3         | 0.79%   |
| fluxbox          | 2         | 0.53%   |
| X-Cinnamon       | 1         | 0.26%   |
| LXQt             | 1         | 0.26%   |
| i3               | 1         | 0.26%   |
| GNOME Classic    | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 370       | 99.2%   |
| Tty     | 2         | 0.54%   |
| Wayland | 1         | 0.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 293       | 78.13%  |
| SDDM    | 72        | 19.2%   |
| SLiM    | 7         | 1.87%   |
| GDM3    | 1         | 0.27%   |
| GDM     | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 175       | 46.67%  |
| de_DE   | 48        | 12.8%   |
| en_GB   | 21        | 5.6%    |
| it_IT   | 20        | 5.33%   |
| ru_RU   | 12        | 3.2%    |
| fr_FR   | 9         | 2.4%    |
| en_AU   | 9         | 2.4%    |
| pl_PL   | 8         | 2.13%   |
| es_ES   | 8         | 2.13%   |
| es_AR   | 8         | 2.13%   |
| de_CH   | 6         | 1.6%    |
| es_MX   | 4         | 1.07%   |
| en_NZ   | 4         | 1.07%   |
| Unknown | 4         | 1.07%   |
| tr_TR   | 3         | 0.8%    |
| pt_BR   | 3         | 0.8%    |
| nl_NL   | 3         | 0.8%    |
| fi_FI   | 3         | 0.8%    |
| sv_SE   | 2         | 0.53%   |
| sk_SK   | 2         | 0.53%   |
| hu_HU   | 2         | 0.53%   |
| fr_CA   | 2         | 0.53%   |
| es_VE   | 2         | 0.53%   |
| es_CO   | 2         | 0.53%   |
| en_CA   | 2         | 0.53%   |
| bg_BG   | 2         | 0.53%   |
| ro_RO   | 1         | 0.27%   |
| nl_BE   | 1         | 0.27%   |
| nb_NO   | 1         | 0.27%   |
| id_ID   | 1         | 0.27%   |
| hr_HR   | 1         | 0.27%   |
| fr_BE   | 1         | 0.27%   |
| eu_ES   | 1         | 0.27%   |
| es_UY   | 1         | 0.27%   |
| es_PE   | 1         | 0.27%   |
| en_IE   | 1         | 0.27%   |
| da_DK   | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 238       | 63.81%  |
| BIOS | 135       | 36.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 316       | 84.04%  |
| Overlay  | 39        | 10.37%  |
| Btrfs    | 15        | 3.99%   |
| Xfs      | 2         | 0.53%   |
| Tmpfs    | 1         | 0.27%   |
| Reiserfs | 1         | 0.27%   |
| F2fs     | 1         | 0.27%   |
| Ext3     | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 263       | 70.32%  |
| MBR     | 109       | 29.14%  |
| Unknown | 2         | 0.53%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 271       | 71.69%  |
| Yes       | 107       | 28.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 208       | 55.47%  |
| Yes       | 167       | 44.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 55        | 14.75%  |
| Lenovo                               | 53        | 14.21%  |
| ASUSTek Computer                     | 53        | 14.21%  |
| Dell                                 | 36        | 9.65%   |
| Acer                                 | 22        | 5.9%    |
| Apple                                | 19        | 5.09%   |
| MSI                                  | 17        | 4.56%   |
| Gigabyte Technology                  | 17        | 4.56%   |
| ASRock                               | 11        | 2.95%   |
| Sony                                 | 8         | 2.14%   |
| Medion                               | 6         | 1.61%   |
| Intel                                | 6         | 1.61%   |
| Unknown                              | 6         | 1.61%   |
| Toshiba                              | 4         | 1.07%   |
| Samsung Electronics                  | 4         | 1.07%   |
| Fujitsu Siemens                      | 4         | 1.07%   |
| Alienware                            | 4         | 1.07%   |
| ZOTAC                                | 2         | 0.54%   |
| TUXEDO                               | 2         | 0.54%   |
| Pegatron                             | 2         | 0.54%   |
| Notebook                             | 2         | 0.54%   |
| Microsoft                            | 2         | 0.54%   |
| Fujitsu                              | 2         | 0.54%   |
| Foxconn                              | 2         | 0.54%   |
| Chuwi                                | 2         | 0.54%   |
| Biostar                              | 2         | 0.54%   |
| AZW                                  | 2         | 0.54%   |
| win element                          | 1         | 0.27%   |
| Vulcan Electronics                   | 1         | 0.27%   |
| Sun Microsystems                     | 1         | 0.27%   |
| SIRAGON                              | 1         | 0.27%   |
| Shenzhen Wangang Technology          | 1         | 0.27%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.27%   |
| SANTECH                              | 1         | 0.27%   |
| RTD Embedded Technologies            | 1         | 0.27%   |
| OEM                                  | 1         | 0.27%   |
| MP                                   | 1         | 0.27%   |
| Linx                                 | 1         | 0.27%   |
| HUAWEI                               | 1         | 0.27%   |
| Huanan                               | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 8         | 2.14%   |
| ASUS All Series                              | 7         | 1.88%   |
| MSI MS-7C91                                  | 2         | 0.54%   |
| HP ProBook 450 G1                            | 2         | 0.54%   |
| HP Pavilion Laptop 15-eh1xxx                 | 2         | 0.54%   |
| HP Laptop 17-ak0xx                           | 2         | 0.54%   |
| Gigabyte GA-MA785GM-US2H                     | 2         | 0.54%   |
| Dell OptiPlex 9020                           | 2         | 0.54%   |
| Dell OptiPlex 780                            | 2         | 0.54%   |
| Dell OptiPlex 755                            | 2         | 0.54%   |
| Chuwi GemiBook Pro                           | 2         | 0.54%   |
| AZW SER                                      | 2         | 0.54%   |
| ASUS ROG Maximus XIII HERO                   | 2         | 0.54%   |
| Apple Macmini8,1                             | 2         | 0.54%   |
| Apple MacBookAir7,2                          | 2         | 0.54%   |
| Acer Nitro AN515-55                          | 2         | 0.54%   |
| ZOTAC ZBOX-ECM73070C/53060C                  | 1         | 0.27%   |
| win element MoreFine S500+                   | 1         | 0.27%   |
| Vulcan Excursion XB                          | 1         | 0.27%   |
| TUXEDO N7x0WU                                | 1         | 0.27%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)           | 1         | 0.27%   |
| Toshiba Satellite M70                        | 1         | 0.27%   |
| Toshiba Satellite L650                       | 1         | 0.27%   |
| Toshiba Satellite C845                       | 1         | 0.27%   |
| Toshiba PORTEGE Z30-C                        | 1         | 0.27%   |
| Sun Microsystems Sun Ultra 40 M2 Workstation | 1         | 0.27%   |
| Sony VPCYB3V1E                               | 1         | 0.27%   |
| Sony VPCSB1V9R                               | 1         | 0.27%   |
| Sony VPCF119FX                               | 1         | 0.27%   |
| Sony VPCEH2N1E                               | 1         | 0.27%   |
| Sony VPCEC3S1E                               | 1         | 0.27%   |
| Sony VPCCB32FD                               | 1         | 0.27%   |
| Sony VGN-TZ3RXN_B                            | 1         | 0.27%   |
| Sony SVE1513Q1ESI                            | 1         | 0.27%   |
| SIRAGON AIO-5150                             | 1         | 0.27%   |
| Shenzhen Wangang AERO 2 Pro                  | 1         | 0.27%   |
| Shenzhen Meigao Electronic Equipment UM450   | 1         | 0.27%   |
| SANTECH X170KM-G                             | 1         | 0.27%   |
| Samsung NC210/NC110                          | 1         | 0.27%   |
| Samsung 355V4C/356V4C/3445VC/3545VC          | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 25        | 6.7%    |
| Acer Aspire              | 14        | 3.75%   |
| Dell OptiPlex            | 9         | 2.41%   |
| HP EliteBook             | 8         | 2.14%   |
| Dell Latitude            | 8         | 2.14%   |
| Dell Inspiron            | 8         | 2.14%   |
| Unknown                  | 8         | 2.14%   |
| Lenovo IdeaPad           | 7         | 1.88%   |
| HP ProBook               | 7         | 1.88%   |
| HP Compaq                | 7         | 1.88%   |
| ASUS All                 | 7         | 1.88%   |
| HP Laptop                | 6         | 1.61%   |
| ASUS VivoBook            | 6         | 1.61%   |
| ASUS ROG                 | 5         | 1.34%   |
| HP Pavilion              | 4         | 1.07%   |
| Dell Precision           | 4         | 1.07%   |
| ASUS TUF                 | 4         | 1.07%   |
| Toshiba Satellite        | 3         | 0.8%    |
| HP 250                   | 3         | 0.8%    |
| Dell Vostro              | 3         | 0.8%    |
| Acer Nitro               | 3         | 0.8%    |
| MSI MS-7C91              | 2         | 0.54%   |
| Microsoft Surface        | 2         | 0.54%   |
| Lenovo Yoga              | 2         | 0.54%   |
| Lenovo V17               | 2         | 0.54%   |
| Lenovo ThinkCentre       | 2         | 0.54%   |
| Lenovo ThinkBook         | 2         | 0.54%   |
| Lenovo Legion            | 2         | 0.54%   |
| Lenovo IdeaCentre        | 2         | 0.54%   |
| HP ZBook                 | 2         | 0.54%   |
| HP Spectre               | 2         | 0.54%   |
| HP ENVY                  | 2         | 0.54%   |
| Gigabyte GA-MA785GM-US2H | 2         | 0.54%   |
| Gigabyte B550M           | 2         | 0.54%   |
| Fujitsu Siemens AMILO    | 2         | 0.54%   |
| Dell System              | 2         | 0.54%   |
| Chuwi GemiBook           | 2         | 0.54%   |
| AZW SER                  | 2         | 0.54%   |
| ASUS PRIME               | 2         | 0.54%   |
| ASUS P5GC-MX             | 2         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 49        | 13.14%  |
| 2020    | 31        | 8.31%   |
| 2022    | 28        | 7.51%   |
| 2011    | 27        | 7.24%   |
| 2013    | 25        | 6.7%    |
| 2019    | 24        | 6.43%   |
| 2016    | 24        | 6.43%   |
| 2010    | 23        | 6.17%   |
| 2018    | 22        | 5.9%    |
| 2015    | 22        | 5.9%    |
| 2012    | 20        | 5.36%   |
| 2014    | 17        | 4.56%   |
| 2008    | 13        | 3.49%   |
| 2007    | 13        | 3.49%   |
| 2017    | 11        | 2.95%   |
| 2009    | 11        | 2.95%   |
| 2023    | 4         | 1.07%   |
| 2006    | 4         | 1.07%   |
| 2005    | 3         | 0.8%    |
| 2004    | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 223       | 59.79%  |
| Desktop     | 118       | 31.64%  |
| Mini pc     | 11        | 2.95%   |
| Convertible | 8         | 2.14%   |
| All in one  | 7         | 1.88%   |
| Tablet      | 3         | 0.8%    |
| Server      | 3         | 0.8%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 370       | 99.2%   |
| Enabled  | 3         | 0.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 372       | 99.73%  |
| Yes  | 1         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 104       | 27.81%  |
| 8.01-16.0   | 74        | 19.79%  |
| 16.01-24.0  | 58        | 15.51%  |
| 3.01-4.0    | 50        | 13.37%  |
| 32.01-64.0  | 41        | 10.96%  |
| 1.01-2.0    | 19        | 5.08%   |
| 24.01-32.0  | 9         | 2.41%   |
| 2.01-3.0    | 8         | 2.14%   |
| 64.01-256.0 | 7         | 1.87%   |
| 0.51-1.0    | 4         | 1.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 138       | 35.38%  |
| 2.01-3.0   | 114       | 29.23%  |
| 3.01-4.0   | 55        | 14.1%   |
| 4.01-8.0   | 46        | 11.79%  |
| 0.51-1.0   | 23        | 5.9%    |
| 8.01-16.0  | 11        | 2.82%   |
| 0.01-0.5   | 2         | 0.51%   |
| 16.01-24.0 | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 223       | 58.99%  |
| 2      | 86        | 22.75%  |
| 3      | 40        | 10.58%  |
| 4      | 15        | 3.97%   |
| 5      | 5         | 1.32%   |
| 8      | 4         | 1.06%   |
| 0      | 3         | 0.79%   |
| 9      | 1         | 0.26%   |
| 7      | 1         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 237       | 63.2%   |
| Yes       | 138       | 36.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 319       | 85.52%  |
| No        | 54        | 14.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 308       | 82.13%  |
| No        | 67        | 17.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 237       | 63.37%  |
| No        | 137       | 36.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 86        | 22.87%  |
| Germany      | 48        | 12.77%  |
| Italy        | 29        | 7.71%   |
| Canada       | 19        | 5.05%   |
| Russia       | 13        | 3.46%   |
| Australia    | 13        | 3.46%   |
| UK           | 11        | 2.93%   |
| Poland       | 11        | 2.93%   |
| France       | 11        | 2.93%   |
| Spain        | 10        | 2.66%   |
| India        | 10        | 2.66%   |
| Argentina    | 7         | 1.86%   |
| Switzerland  | 6         | 1.6%    |
| Netherlands  | 6         | 1.6%    |
| Finland      | 6         | 1.6%    |
| Romania      | 5         | 1.33%   |
| New Zealand  | 5         | 1.33%   |
| Brazil       | 5         | 1.33%   |
| Belgium      | 5         | 1.33%   |
| Sweden       | 4         | 1.06%   |
| Serbia       | 4         | 1.06%   |
| Indonesia    | 4         | 1.06%   |
| Greece       | 4         | 1.06%   |
| Venezuela    | 3         | 0.8%    |
| Turkey       | 3         | 0.8%    |
| South Africa | 3         | 0.8%    |
| Mexico       | 3         | 0.8%    |
| Slovakia     | 2         | 0.53%   |
| Singapore    | 2         | 0.53%   |
| Ireland      | 2         | 0.53%   |
| Hungary      | 2         | 0.53%   |
| Estonia      | 2         | 0.53%   |
| Egypt        | 2         | 0.53%   |
| Czechia      | 2         | 0.53%   |
| Croatia      | 2         | 0.53%   |
| Colombia     | 2         | 0.53%   |
| Bulgaria     | 2         | 0.53%   |
| Bangladesh   | 2         | 0.53%   |
| Austria      | 2         | 0.53%   |
| Vietnam      | 1         | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Berlin        | 7         | 1.8%    |
| Sydney        | 6         | 1.54%   |
| Moscow        | 6         | 1.54%   |
| Milan         | 5         | 1.29%   |
| St Petersburg | 4         | 1.03%   |
| Warsaw        | 3         | 0.77%   |
| Rome          | 3         | 0.77%   |
| Mesquite      | 3         | 0.77%   |
| Melbourne     | 3         | 0.77%   |
| Cambridge     | 3         | 0.77%   |
| Bengaluru     | 3         | 0.77%   |
| Belgrade      | 3         | 0.77%   |
| Amsterdam     | 3         | 0.77%   |
| Walled Lake   | 2         | 0.51%   |
| Vienna        | 2         | 0.51%   |
| Vasco da Gama | 2         | 0.51%   |
| Toronto       | 2         | 0.51%   |
| Singapore     | 2         | 0.51%   |
| Portland      | 2         | 0.51%   |
| Perth         | 2         | 0.51%   |
| Otwock        | 2         | 0.51%   |
| Orange        | 2         | 0.51%   |
| Oakland       | 2         | 0.51%   |
| New York      | 2         | 0.51%   |
| Montreal      | 2         | 0.51%   |
| Krakow        | 2         | 0.51%   |
| Johannesburg  | 2         | 0.51%   |
| Istanbul      | 2         | 0.51%   |
| Hyderabad     | 2         | 0.51%   |
| Houston       | 2         | 0.51%   |
| Helsinki      | 2         | 0.51%   |
| Florence      | 2         | 0.51%   |
| Ettingen      | 2         | 0.51%   |
| Edinburgh     | 2         | 0.51%   |
| Doesburg      | 2         | 0.51%   |
| Dhaka         | 2         | 0.51%   |
| Córdoba      | 2         | 0.51%   |
| Catania       | 2         | 0.51%   |
| Casale Litta  | 2         | 0.51%   |
| Canberra      | 2         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 91        | 130    | 16.08%  |
| WDC                 | 77        | 89     | 13.6%   |
| Seagate             | 65        | 96     | 11.48%  |
| Kingston            | 40        | 44     | 7.07%   |
| Toshiba             | 27        | 28     | 4.77%   |
| Unknown             | 26        | 31     | 4.59%   |
| SanDisk             | 26        | 29     | 4.59%   |
| Crucial             | 25        | 43     | 4.42%   |
| SK hynix            | 20        | 21     | 3.53%   |
| Hitachi             | 13        | 16     | 2.3%    |
| Intel               | 12        | 14     | 2.12%   |
| China               | 12        | 13     | 2.12%   |
| Apple               | 10        | 14     | 1.77%   |
| PNY                 | 7         | 8      | 1.24%   |
| Micron Technology   | 7         | 7      | 1.24%   |
| HGST                | 7         | 7      | 1.24%   |
| SPCC                | 6         | 6      | 1.06%   |
| KIOXIA              | 6         | 8      | 1.06%   |
| Transcend           | 5         | 5      | 0.88%   |
| LITEON              | 5         | 5      | 0.88%   |
| Corsair             | 5         | 5      | 0.88%   |
| Team                | 4         | 4      | 0.71%   |
| Silicon Motion      | 4         | 4      | 0.71%   |
| Netac               | 4         | 4      | 0.71%   |
| Unknown             | 4         | 4      | 0.71%   |
| Phison              | 3         | 4      | 0.53%   |
| OCZ                 | 3         | 3      | 0.53%   |
| Dogfish             | 3         | 3      | 0.53%   |
| Apacer              | 3         | 3      | 0.53%   |
| A-DATA Technology   | 3         | 3      | 0.53%   |
| Patriot             | 2         | 3      | 0.35%   |
| GOODRAM             | 2         | 2      | 0.35%   |
| Gigabyte Technology | 2         | 2      | 0.35%   |
| Fujitsu             | 2         | 2      | 0.35%   |
| EYOTA               | 2         | 2      | 0.35%   |
| External            | 2         | 2      | 0.35%   |
| XPG                 | 1         | 1      | 0.18%   |
| WALRAM              | 1         | 1      | 0.18%   |
| Vaseky              | 1         | 1      | 0.18%   |
| USB                 | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD        | 10        | 1.61%   |
| Samsung SSD 860 EVO 500GB              | 7         | 1.13%   |
| Samsung SSD 850 EVO 250GB              | 7         | 1.13%   |
| Samsung SSD 980 PRO 1TB                | 6         | 0.97%   |
| Samsung SSD 970 EVO Plus 1TB           | 6         | 0.97%   |
| Seagate ST500LM021-1KJ152 500GB        | 5         | 0.81%   |
| Kingston SV300S37A240G 240GB SSD       | 5         | 0.81%   |
| Kingston SA400S37240G 240GB SSD        | 5         | 0.81%   |
| Seagate ST2000DM008-2FR102 2TB         | 4         | 0.64%   |
| Kingston SA400S37120G 120GB SSD        | 4         | 0.64%   |
| Crucial CT500MX500SSD1 500GB           | 4         | 0.64%   |
| Crucial CT480BX500SSD1 480GB           | 4         | 0.64%   |
| Crucial CT120BX500SSD1 120GB           | 4         | 0.64%   |
| Unknown                                | 4         | 0.64%   |
| Unknown SD32G  32GB                    | 3         | 0.48%   |
| Unknown SD/MMC/MS PRO 128GB            | 3         | 0.48%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 3         | 0.48%   |
| SK hynix HFM512GDJTNI-82A0A 512GB      | 3         | 0.48%   |
| Seagate ST4000DM004-2CV104 4TB         | 3         | 0.48%   |
| Seagate ST3500413AS 500GB              | 3         | 0.48%   |
| Seagate ST2000DM001-1ER164 2TB         | 3         | 0.48%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 0.48%   |
| SanDisk SDSSDA240G 240GB               | 3         | 0.48%   |
| SanDisk NVMe SSD Drive 1TB             | 3         | 0.48%   |
| Samsung SSD 970 PRO 512GB              | 3         | 0.48%   |
| Samsung SSD 870 EVO 500GB              | 3         | 0.48%   |
| Samsung SSD 860 EVO 250GB              | 3         | 0.48%   |
| Samsung SSD 850 EVO 1TB                | 3         | 0.48%   |
| Samsung SSD 840 Series 120GB           | 3         | 0.48%   |
| Intel SSDPEKNU512GZ 512GB              | 3         | 0.48%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.48%   |
| Crucial CT240BX500SSD1 240GB           | 3         | 0.48%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 0.32%   |
| WDC WDS100T1X0E-00AFY0 1TB             | 2         | 0.32%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 2         | 0.32%   |
| WDC WD3200AAKS-75B3A0 320GB            | 2         | 0.32%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.32%   |
| WDC WD10EZEX-00BN5A0 1TB               | 2         | 0.32%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 2         | 0.32%   |
| Unknown SDW32G  32GB                   | 2         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 96     | 35.71%  |
| WDC                 | 58        | 69     | 31.87%  |
| Toshiba             | 21        | 22     | 11.54%  |
| Hitachi             | 13        | 16     | 7.14%   |
| Samsung Electronics | 8         | 10     | 4.4%    |
| HGST                | 7         | 7      | 3.85%   |
| Unknown             | 3         | 3      | 1.65%   |
| Fujitsu             | 2         | 2      | 1.1%    |
| External            | 2         | 2      | 1.1%    |
| Maxtor              | 1         | 1      | 0.55%   |
| ASMT                | 1         | 1      | 0.55%   |
| Apple               | 1         | 1      | 0.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 51        | 65     | 23.5%   |
| Kingston            | 29        | 32     | 13.36%  |
| Crucial             | 20        | 36     | 9.22%   |
| SanDisk             | 17        | 19     | 7.83%   |
| China               | 12        | 13     | 5.53%   |
| Apple               | 7         | 10     | 3.23%   |
| WDC                 | 6         | 6      | 2.76%   |
| SPCC                | 6         | 6      | 2.76%   |
| PNY                 | 6         | 6      | 2.76%   |
| Transcend           | 5         | 5      | 2.3%    |
| SK hynix            | 4         | 4      | 1.84%   |
| Netac               | 4         | 4      | 1.84%   |
| LITEON              | 4         | 4      | 1.84%   |
| Team                | 3         | 3      | 1.38%   |
| OCZ                 | 3         | 3      | 1.38%   |
| Micron Technology   | 3         | 3      | 1.38%   |
| Intel               | 3         | 3      | 1.38%   |
| Dogfish             | 3         | 3      | 1.38%   |
| Toshiba             | 2         | 2      | 0.92%   |
| GOODRAM             | 2         | 2      | 0.92%   |
| EYOTA               | 2         | 2      | 0.92%   |
| Apacer              | 2         | 2      | 0.92%   |
| A-DATA Technology   | 2         | 2      | 0.92%   |
| Unknown             | 2         | 2      | 0.92%   |
| WALRAM              | 1         | 1      | 0.46%   |
| Vaseky              | 1         | 1      | 0.46%   |
| Teclast             | 1         | 1      | 0.46%   |
| SWORDBILL           | 1         | 2      | 0.46%   |
| Rogueware           | 1         | 2      | 0.46%   |
| RENICE              | 1         | 1      | 0.46%   |
| Patriot             | 1         | 1      | 0.46%   |
| Mushkin             | 1         | 1      | 0.46%   |
| MMY                 | 1         | 1      | 0.46%   |
| KingSpec            | 1         | 1      | 0.46%   |
| Indilinx            | 1         | 1      | 0.46%   |
| Hewlett-Packard     | 1         | 1      | 0.46%   |
| Gigabyte Technology | 1         | 1      | 0.46%   |
| GeIL                | 1         | 1      | 0.46%   |
| CT500MX5            | 1         | 1      | 0.46%   |
| CT1000MX            | 1         | 1      | 0.46%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 181       | 258    | 35.77%  |
| HDD     | 160       | 230    | 31.62%  |
| NVMe    | 137       | 174    | 27.08%  |
| MMC     | 23        | 28     | 4.55%   |
| Unknown | 5         | 7      | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 266       | 467    | 59.78%  |
| NVMe | 137       | 172    | 30.79%  |
| MMC  | 23        | 28     | 5.17%   |
| SAS  | 19        | 30     | 4.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 215       | 302    | 61.25%  |
| 0.51-1.0   | 92        | 120    | 26.21%  |
| 1.01-2.0   | 26        | 35     | 7.41%   |
| 3.01-4.0   | 7         | 7      | 1.99%   |
| 4.01-10.0  | 6         | 18     | 1.71%   |
| 2.01-3.0   | 4         | 5      | 1.14%   |
| 10.01-20.0 | 1         | 1      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 99        | 25.98%  |
| 251-500        | 87        | 22.83%  |
| 501-1000       | 48        | 12.6%   |
| 21-50          | 37        | 9.71%   |
| 51-100         | 36        | 9.45%   |
| 1001-2000      | 26        | 6.82%   |
| 1-20           | 18        | 4.72%   |
| More than 3000 | 16        | 4.2%    |
| 2001-3000      | 14        | 3.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 155       | 39.74%  |
| 21-50          | 60        | 15.38%  |
| 101-250        | 53        | 13.59%  |
| 51-100         | 50        | 12.82%  |
| 251-500        | 25        | 6.41%   |
| 501-1000       | 19        | 4.87%   |
| 1001-2000      | 17        | 4.36%   |
| More than 3000 | 8         | 2.05%   |
| 2001-3000      | 3         | 0.77%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB          | 2         | 2      | 2.7%    |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 2.7%    |
| China SSD 512GB                       | 2         | 2      | 2.7%    |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 1      | 1.35%   |
| WDC WD5000AAKS-40V6A0 500GB           | 1         | 1      | 1.35%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 1.35%   |
| WDC WD3200BPVT-24JJ5T0 320GB          | 1         | 1      | 1.35%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 1      | 1.35%   |
| WDC WD3200AAKS-00UU3A0 320GB          | 1         | 1      | 1.35%   |
| WDC WD3200AAJS-00B4A0 320GB           | 1         | 1      | 1.35%   |
| WDC WD2500AAJS-00B4A0 250GB           | 1         | 1      | 1.35%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 2      | 1.35%   |
| WDC WD20EARS-00J99B0 2TB              | 1         | 1      | 1.35%   |
| WDC WD10EZRZ-00HTKB0 1TB              | 1         | 1      | 1.35%   |
| WDC WD10EADS-98M2B0 1TB               | 1         | 1      | 1.35%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 1.35%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD  | 1         | 1      | 1.35%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 1.35%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.35%   |
| Toshiba MK5059GSXP 500GB              | 1         | 1      | 1.35%   |
| Toshiba MK1234GSX 120GB               | 1         | 1      | 1.35%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD | 1         | 1      | 1.35%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 1.35%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 1.35%   |
| Seagate ST9320421AS 320GB             | 1         | 1      | 1.35%   |
| Seagate ST9160821AS 160GB             | 1         | 1      | 1.35%   |
| Seagate ST750LM022 HN-M750MBB 752GB   | 1         | 1      | 1.35%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.35%   |
| Seagate ST500LM000-1EJ162 500GB       | 1         | 1      | 1.35%   |
| Seagate ST380815AS 80GB               | 1         | 1      | 1.35%   |
| Seagate ST3500413AS 500GB             | 1         | 1      | 1.35%   |
| Seagate ST3360320AS 360GB             | 1         | 1      | 1.35%   |
| Seagate ST3320418AS 320GB             | 1         | 1      | 1.35%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 1.35%   |
| Seagate ST320LT012-1DG14C 320GB       | 1         | 2      | 1.35%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 4      | 1.35%   |
| Seagate ST250DM000-1BD141 250GB       | 1         | 1      | 1.35%   |
| Seagate ST2000DM001-1ER164 2TB        | 1         | 1      | 1.35%   |
| Seagate ST1000VM002-1CT162 1TB        | 1         | 1      | 1.35%   |
| Seagate ST1000DM003-9YN162 1TB        | 1         | 1      | 1.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 23     | 26.03%  |
| WDC                 | 15        | 16     | 20.55%  |
| Samsung Electronics | 8         | 11     | 10.96%  |
| Toshiba             | 5         | 5      | 6.85%   |
| Hitachi             | 5         | 6      | 6.85%   |
| HGST                | 4         | 4      | 5.48%   |
| SK hynix            | 2         | 2      | 2.74%   |
| Kingston            | 2         | 2      | 2.74%   |
| China               | 2         | 2      | 2.74%   |
| RENICE              | 1         | 1      | 1.37%   |
| OCZ                 | 1         | 1      | 1.37%   |
| Micron Technology   | 1         | 1      | 1.37%   |
| Maxtor              | 1         | 1      | 1.37%   |
| Lexar               | 1         | 1      | 1.37%   |
| KingSpec            | 1         | 1      | 1.37%   |
| Intel               | 1         | 2      | 1.37%   |
| Indilinx            | 1         | 1      | 1.37%   |
| GOODRAM             | 1         | 1      | 1.37%   |
| Fujitsu             | 1         | 1      | 1.37%   |
| Crucial             | 1         | 6      | 1.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 23     | 38%     |
| WDC                 | 14        | 15     | 28%     |
| Hitachi             | 5         | 6      | 10%     |
| Toshiba             | 4         | 4      | 8%      |
| HGST                | 4         | 4      | 8%      |
| Samsung Electronics | 2         | 2      | 4%      |
| Maxtor              | 1         | 1      | 2%      |
| Fujitsu             | 1         | 1      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 56     | 69.01%  |
| SSD  | 19        | 28     | 26.76%  |
| NVMe | 3         | 4      | 4.23%   |

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
| Works    | 311       | 534    | 71.49%  |
| Malfunc  | 71        | 88     | 16.32%  |
| Detected | 53        | 75     | 12.18%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 250       | 51.55%  |
| AMD                          | 60        | 12.37%  |
| Samsung Electronics          | 45        | 9.28%   |
| SanDisk                      | 20        | 4.12%   |
| SK hynix                     | 15        | 3.09%   |
| Phison Electronics           | 12        | 2.47%   |
| Kingston Technology Company  | 11        | 2.27%   |
| ASMedia Technology           | 10        | 2.06%   |
| KIOXIA                       | 8         | 1.65%   |
| Silicon Motion               | 7         | 1.44%   |
| Nvidia                       | 7         | 1.44%   |
| Micron/Crucial Technology    | 7         | 1.44%   |
| Marvell Technology Group     | 5         | 1.03%   |
| Micron Technology            | 4         | 0.82%   |
| JMicron Technology           | 3         | 0.62%   |
| VIA Technologies             | 2         | 0.41%   |
| Toshiba America Info Systems | 2         | 0.41%   |
| Silicon Image                | 2         | 0.41%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.41%   |
| LSI Logic / Symbios Logic    | 2         | 0.41%   |
| Broadcom / LSI               | 2         | 0.41%   |
| Apple                        | 2         | 0.41%   |
| ADATA Technology             | 2         | 0.41%   |
| Union Memory (Shenzhen)      | 1         | 0.21%   |
| ULi Electronics              | 1         | 0.21%   |
| Shenzhen Longsys Electronics | 1         | 0.21%   |
| Lite-On Technology           | 1         | 0.21%   |
| Hewlett-Packard              | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 36        | 6.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 23        | 4.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 19        | 3.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 3.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 2.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 2.38%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 12        | 2.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 2.01%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 2.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 1.83%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 10        | 1.83%   |
| Intel Tiger Lake-LP SATA Controller                                            | 9         | 1.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 1.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 7         | 1.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 1.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 1.28%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 7         | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 1.28%   |
| SK hynix BC511 NVMe SSD                                                        | 6         | 1.1%    |
| Phison E12 NVMe Controller                                                     | 6         | 1.1%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 6         | 1.1%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6         | 1.1%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 0.92%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 0.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 0.92%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 5         | 0.92%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 5         | 0.92%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 5         | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 0.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 0.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 0.92%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 4         | 0.73%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 4         | 0.73%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 4         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 278       | 56.97%  |
| NVMe | 135       | 27.66%  |
| IDE  | 48        | 9.84%   |
| RAID | 24        | 4.92%   |
| SCSI | 2         | 0.41%   |
| SAS  | 1         | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 290       | 77.75%  |
| AMD    | 83        | 22.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 8         | 2.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 5         | 1.34%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 5         | 1.34%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 1.34%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 5         | 1.34%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 4         | 1.07%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 4         | 1.07%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 4         | 1.07%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 0.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 0.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 0.8%    |
| Intel Core i7-3770 CPU @ 3.40GHz        | 3         | 0.8%    |
| Intel Core i5-2430M CPU @ 2.40GHz       | 3         | 0.8%    |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 3         | 0.8%    |
| Intel Core i3-4160 CPU @ 3.60GHz        | 3         | 0.8%    |
| Intel Core i3-2350M CPU @ 2.30GHz       | 3         | 0.8%    |
| Intel Core i3-10110U CPU @ 2.10GHz      | 3         | 0.8%    |
| Intel Celeron J4125 CPU @ 2.00GHz       | 3         | 0.8%    |
| Intel Celeron CPU N3060 @ 1.60GHz       | 3         | 0.8%    |
| Intel 12th Gen Core i7-12700H           | 3         | 0.8%    |
| Intel 12th Gen Core i5-1235U            | 3         | 0.8%    |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 0.8%    |
| AMD Ryzen 5 5625U with Radeon Graphics  | 3         | 0.8%    |
| AMD Ryzen 5 5600H with Radeon Graphics  | 3         | 0.8%    |
| Intel Core i7-8700B CPU @ 3.20GHz       | 2         | 0.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 0.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 0.54%   |
| Intel Core i7-5820K CPU @ 3.30GHz       | 2         | 0.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 0.54%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 2         | 0.54%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 2         | 0.54%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 2         | 0.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.54%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 2         | 0.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 0.54%   |
| Intel Core i5-5350U CPU @ 1.80GHz       | 2         | 0.54%   |
| Intel Core i5-4690K CPU @ 3.50GHz       | 2         | 0.54%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 2         | 0.54%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 2         | 0.54%   |
| Intel Core i5-3350P CPU @ 3.10GHz       | 2         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 68        | 18.23%  |
| Intel Core i7           | 60        | 16.09%  |
| Other                   | 38        | 10.19%  |
| Intel Core i3           | 35        | 9.38%   |
| Intel Celeron           | 25        | 6.7%    |
| AMD Ryzen 5             | 24        | 6.43%   |
| AMD Ryzen 7             | 20        | 5.36%   |
| Intel Core 2 Duo        | 18        | 4.83%   |
| Intel Atom              | 11        | 2.95%   |
| Intel Xeon              | 8         | 2.14%   |
| AMD Ryzen 9             | 6         | 1.61%   |
| Intel Pentium           | 5         | 1.34%   |
| AMD Ryzen 3             | 5         | 1.34%   |
| Intel Pentium Dual-Core | 4         | 1.07%   |
| AMD Phenom II X4        | 3         | 0.8%    |
| AMD Athlon II X4        | 3         | 0.8%    |
| Intel Pentium Silver    | 2         | 0.54%   |
| Intel Pentium M         | 2         | 0.54%   |
| Intel Pentium Gold      | 2         | 0.54%   |
| Intel Pentium Dual      | 2         | 0.54%   |
| Intel Pentium 4         | 2         | 0.54%   |
| Intel Genuine           | 2         | 0.54%   |
| Intel Core i9           | 2         | 0.54%   |
| Intel Core 2            | 2         | 0.54%   |
| AMD Phenom              | 2         | 0.54%   |
| AMD A8                  | 2         | 0.54%   |
| AMD A6                  | 2         | 0.54%   |
| Intel Pentium D         | 1         | 0.27%   |
| Intel Core M            | 1         | 0.27%   |
| Intel Celeron Dual-Core | 1         | 0.27%   |
| AMD Turion 64 X2 Mobile | 1         | 0.27%   |
| AMD Turion 64 Mobile    | 1         | 0.27%   |
| AMD Sempron             | 1         | 0.27%   |
| AMD Ryzen Threadripper  | 1         | 0.27%   |
| AMD Ryzen 5 PRO         | 1         | 0.27%   |
| AMD Phenom II X6        | 1         | 0.27%   |
| AMD Phenom II           | 1         | 0.27%   |
| AMD FX                  | 1         | 0.27%   |
| AMD E2                  | 1         | 0.27%   |
| AMD E1                  | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 147       | 39.41%  |
| 4      | 123       | 32.98%  |
| 6      | 37        | 9.92%   |
| 8      | 32        | 8.58%   |
| 1      | 12        | 3.22%   |
| 12     | 10        | 2.68%   |
| 10     | 6         | 1.61%   |
| 14     | 3         | 0.8%    |
| 16     | 1         | 0.27%   |
| 5      | 1         | 0.27%   |
| 3      | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 369       | 98.93%  |
| 2      | 4         | 1.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 237       | 63.54%  |
| 1      | 136       | 36.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 368       | 98.66%  |
| 32-bit         | 5         | 1.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 9.79%   |
| 0x206a7    | 25        | 6.61%   |
| 0x306a9    | 22        | 5.82%   |
| 0x306c3    | 19        | 5.03%   |
| 0x806c1    | 15        | 3.97%   |
| 0x1067a    | 14        | 3.7%    |
| 0x406e3    | 12        | 3.17%   |
| 0x0a50000c | 12        | 3.17%   |
| 0x506e3    | 10        | 2.65%   |
| 0x20655    | 9         | 2.38%   |
| 0x30678    | 8         | 2.12%   |
| 0x906ea    | 7         | 1.85%   |
| 0x806e9    | 7         | 1.85%   |
| 0x706a8    | 7         | 1.85%   |
| 0x906a3    | 6         | 1.59%   |
| 0x806ec    | 6         | 1.59%   |
| 0x6fd      | 6         | 1.59%   |
| 0x306d4    | 6         | 1.59%   |
| 0x08608103 | 6         | 1.59%   |
| 0xa0652    | 5         | 1.32%   |
| 0x906ed    | 5         | 1.32%   |
| 0x906a4    | 5         | 1.32%   |
| 0x806ea    | 5         | 1.32%   |
| 0x406c4    | 5         | 1.32%   |
| 0x40651    | 5         | 1.32%   |
| 0xa0653    | 4         | 1.06%   |
| 0x906e9    | 4         | 1.06%   |
| 0x906c0    | 4         | 1.06%   |
| 0x106e5    | 4         | 1.06%   |
| 0x0a601203 | 4         | 1.06%   |
| 0x08108109 | 4         | 1.06%   |
| 0xa0671    | 3         | 0.79%   |
| 0x706a1    | 3         | 0.79%   |
| 0x10676    | 3         | 0.79%   |
| 0x0a50000d | 3         | 0.79%   |
| 0x08701021 | 3         | 0.79%   |
| 0x08600106 | 3         | 0.79%   |
| 0x08108102 | 3         | 0.79%   |
| 0x0800820d | 3         | 0.79%   |
| 0x010000db | 3         | 0.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 9.89%   |
| Haswell          | 31        | 8.29%   |
| SandyBridge      | 28        | 7.49%   |
| Skylake          | 24        | 6.42%   |
| IvyBridge        | 24        | 6.42%   |
| Unknown          | 23        | 6.15%   |
| Zen 3            | 21        | 5.61%   |
| Penryn           | 20        | 5.35%   |
| TigerLake        | 17        | 4.55%   |
| Silvermont       | 14        | 3.74%   |
| Zen+             | 12        | 3.21%   |
| Westmere         | 12        | 3.21%   |
| K10              | 10        | 2.67%   |
| Goldmont plus    | 10        | 2.67%   |
| Core             | 10        | 2.67%   |
| CometLake        | 10        | 2.67%   |
| Zen 2            | 9         | 2.41%   |
| Icelake          | 8         | 2.14%   |
| Broadwell        | 7         | 1.87%   |
| Alderlake Hybrid | 7         | 1.87%   |
| Nehalem          | 6         | 1.6%    |
| Tremont          | 4         | 1.07%   |
| Zen              | 3         | 0.8%    |
| Piledriver       | 3         | 0.8%    |
| P6               | 3         | 0.8%    |
| NetBurst         | 3         | 0.8%    |
| K8 Hammer        | 3         | 0.8%    |
| Goldmont         | 3         | 0.8%    |
| Excavator        | 3         | 0.8%    |
| Bonnell          | 3         | 0.8%    |
| Puma             | 2         | 0.53%   |
| Steamroller      | 1         | 0.27%   |
| K8 & K10 hybrid  | 1         | 0.27%   |
| K10 Llano        | 1         | 0.27%   |
| Bobcat           | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 233       | 52.83%  |
| Nvidia                     | 107       | 24.26%  |
| AMD                        | 100       | 22.68%  |
| Matrox Electronics Systems | 1         | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 4.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 3.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 3.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 2.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 2.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 1.98%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 1.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 1.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 1.54%   |
| Intel HD Graphics 530                                                                    | 7         | 1.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 1.54%   |
| AMD Lucienne                                                                             | 7         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.32%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.32%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.1%    |
| Intel UHD Graphics 620                                                                   | 5         | 1.1%    |
| Intel HD Graphics 620                                                                    | 5         | 1.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.1%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.1%    |
| AMD Raphael                                                                              | 5         | 1.1%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 0.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 0.88%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.88%   |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 0.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.88%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 4         | 0.88%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 4         | 0.88%   |
| AMD Barcelo                                                                              | 4         | 0.88%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 0.66%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.66%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3         | 0.66%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 176       | 47.06%  |
| 1 x AMD        | 75        | 20.05%  |
| 1 x Nvidia     | 58        | 15.51%  |
| Intel + Nvidia | 37        | 9.89%   |
| Intel + AMD    | 11        | 2.94%   |
| AMD + Nvidia   | 11        | 2.94%   |
| 2 x AMD        | 4         | 1.07%   |
| 2 x Intel      | 1         | 0.27%   |
| 1 x Matrox     | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 308       | 81.48%  |
| Proprietary | 48        | 12.7%   |
| Unknown     | 22        | 5.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 238       | 63.13%  |
| 0.01-0.5   | 45        | 11.94%  |
| 1.01-2.0   | 26        | 6.9%    |
| 3.01-4.0   | 22        | 5.84%   |
| 0.51-1.0   | 19        | 5.04%   |
| 7.01-8.0   | 17        | 4.51%   |
| 8.01-16.0  | 6         | 1.59%   |
| 2.01-3.0   | 3         | 0.8%    |
| 5.01-6.0   | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 48        | 12.12%  |
| Chimei Innolux          | 43        | 10.86%  |
| Samsung Electronics     | 41        | 10.35%  |
| BOE                     | 32        | 8.08%   |
| LG Display              | 23        | 5.81%   |
| Dell                    | 20        | 5.05%   |
| Hewlett-Packard         | 17        | 4.29%   |
| Acer                    | 15        | 3.79%   |
| Goldstar                | 14        | 3.54%   |
| Apple                   | 13        | 3.28%   |
| Lenovo                  | 10        | 2.53%   |
| Ancor Communications    | 10        | 2.53%   |
| Sony                    | 9         | 2.27%   |
| Chi Mei Optoelectronics | 9         | 2.27%   |
| AOC                     | 9         | 2.27%   |
| PANDA                   | 8         | 2.02%   |
| Philips                 | 7         | 1.77%   |
| BenQ                    | 6         | 1.52%   |
| ViewSonic               | 4         | 1.01%   |
| Sharp                   | 4         | 1.01%   |
| Fujitsu Siemens         | 4         | 1.01%   |
| Eizo                    | 4         | 1.01%   |
| Medion                  | 3         | 0.76%   |
| Iiyama                  | 3         | 0.76%   |
| CPT                     | 3         | 0.76%   |
| ASUSTek Computer        | 3         | 0.76%   |
| Panasonic               | 2         | 0.51%   |
| NEC Computers           | 2         | 0.51%   |
| MSI                     | 2         | 0.51%   |
| MiTAC                   | 2         | 0.51%   |
| InfoVision              | 2         | 0.51%   |
| Hitachi                 | 2         | 0.51%   |
| HannStar                | 2         | 0.51%   |
| Xiaomi                  | 1         | 0.25%   |
| Vizio                   | 1         | 0.25%   |
| Vestel Elektronik       | 1         | 0.25%   |
| TMX                     | 1         | 0.25%   |
| Sunplus                 | 1         | 0.25%   |
| STA                     | 1         | 0.25%   |
| Sangyo                  | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 1.24%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.75%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.75%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 3         | 0.75%   |
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch                | 2         | 0.5%    |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                       | 2         | 0.5%    |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch        | 2         | 0.5%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 0.5%    |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                          | 2         | 0.5%    |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 0.5%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.5%    |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                  | 2         | 0.5%    |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch                 | 2         | 0.5%    |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.5%    |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch         | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch | 2         | 0.5%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 2         | 0.5%    |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 0.5%    |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                     | 2         | 0.5%    |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                         | 2         | 0.5%    |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 2         | 0.5%    |
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                        | 1         | 0.25%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                       | 1         | 0.25%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch                 | 1         | 0.25%   |
| ViewSonic VA2012wSERIES VSC6A1C 1680x1050 430x270mm 20.0-inch            | 1         | 0.25%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch       | 1         | 0.25%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                    | 1         | 0.25%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.25%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.25%   |
| Sony TV SNY3001 1920x1080                                                | 1         | 0.25%   |
| Sony TV *00 SNY7105 3840x2160 1218x685mm 55.0-inch                       | 1         | 0.25%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                     | 1         | 0.25%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                       | 1         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 168       | 44.09%  |
| 1366x768 (WXGA)    | 70        | 18.37%  |
| 3840x2160 (4K)     | 30        | 7.87%   |
| 1680x1050 (WSXGA+) | 16        | 4.2%    |
| 2560x1440 (QHD)    | 14        | 3.67%   |
| 1280x800 (WXGA)    | 12        | 3.15%   |
| 1280x1024 (SXGA)   | 12        | 3.15%   |
| 1600x900 (HD+)     | 10        | 2.62%   |
| 1440x900 (WXGA+)   | 7         | 1.84%   |
| 1920x1200 (WUXGA)  | 6         | 1.57%   |
| 2560x1600          | 4         | 1.05%   |
| 2880x1800          | 3         | 0.79%   |
| 2560x1080          | 3         | 0.79%   |
| 2160x1440          | 3         | 0.79%   |
| 1360x768           | 3         | 0.79%   |
| 1024x768 (XGA)     | 3         | 0.79%   |
| 3440x1440          | 2         | 0.52%   |
| 2256x1504          | 2         | 0.52%   |
| 1280x720 (HD)      | 2         | 0.52%   |
| 1024x600           | 2         | 0.52%   |
| Unknown            | 2         | 0.52%   |
| 3840x2400          | 1         | 0.26%   |
| 3840x1080          | 1         | 0.26%   |
| 3200x2000          | 1         | 0.26%   |
| 3200x1800 (QHD+)   | 1         | 0.26%   |
| 2736x1824          | 1         | 0.26%   |
| 1920x1440          | 1         | 0.26%   |
| 1400x1050          | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 109       | 27.74%  |
| 23      | 32        | 8.14%   |
| 13      | 32        | 8.14%   |
| 27      | 26        | 6.62%   |
| 17      | 25        | 6.36%   |
| 24      | 24        | 6.11%   |
| 14      | 22        | 5.6%    |
| 21      | 21        | 5.34%   |
| 11      | 13        | 3.31%   |
| 22      | 11        | 2.8%    |
| Unknown | 11        | 2.8%    |
| 31      | 10        | 2.54%   |
| 19      | 8         | 2.04%   |
| 16      | 6         | 1.53%   |
| 12      | 6         | 1.53%   |
| 34      | 5         | 1.27%   |
| 18      | 4         | 1.02%   |
| 10      | 4         | 1.02%   |
| 84      | 3         | 0.76%   |
| 40      | 3         | 0.76%   |
| 26      | 3         | 0.76%   |
| 20      | 3         | 0.76%   |
| 65      | 2         | 0.51%   |
| 54      | 2         | 0.51%   |
| 61      | 1         | 0.25%   |
| 52      | 1         | 0.25%   |
| 46      | 1         | 0.25%   |
| 43      | 1         | 0.25%   |
| 42      | 1         | 0.25%   |
| 36      | 1         | 0.25%   |
| 32      | 1         | 0.25%   |
| 25      | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 153       | 39.33%  |
| 501-600     | 79        | 20.31%  |
| 401-500     | 40        | 10.28%  |
| 201-300     | 38        | 9.77%   |
| 351-400     | 33        | 8.48%   |
| 601-700     | 13        | 3.34%   |
| Unknown     | 11        | 2.83%   |
| 701-800     | 7         | 1.8%    |
| 1001-1500   | 7         | 1.8%    |
| 801-900     | 3         | 0.77%   |
| 1501-2000   | 3         | 0.77%   |
| 901-1000    | 2         | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 278       | 76.16%  |
| 16/10   | 51        | 13.97%  |
| 5/4     | 12        | 3.29%   |
| Unknown | 7         | 1.92%   |
| 4/3     | 6         | 1.64%   |
| 3/2     | 6         | 1.64%   |
| 21/9    | 5         | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 108       | 27.62%  |
| 201-250        | 72        | 18.41%  |
| 81-90          | 44        | 11.25%  |
| 301-350        | 28        | 7.16%   |
| 151-200        | 22        | 5.63%   |
| 121-130        | 21        | 5.37%   |
| 351-500        | 16        | 4.09%   |
| 51-60          | 13        | 3.32%   |
| Unknown        | 11        | 2.81%   |
| 71-80          | 10        | 2.56%   |
| More than 1000 | 9         | 2.3%    |
| 251-300        | 9         | 2.3%    |
| 501-1000       | 7         | 1.79%   |
| 141-150        | 6         | 1.53%   |
| 61-70          | 5         | 1.28%   |
| 41-50          | 4         | 1.02%   |
| 111-120        | 3         | 0.77%   |
| 91-100         | 3         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 135       | 35.34%  |
| 121-160       | 115       | 30.1%   |
| 101-120       | 82        | 21.47%  |
| 161-240       | 21        | 5.5%    |
| Unknown       | 11        | 2.88%   |
| More than 240 | 9         | 2.36%   |
| 1-50          | 9         | 2.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 304       | 80.21%  |
| 2     | 50        | 13.19%  |
| 0     | 20        | 5.28%   |
| 3     | 5         | 1.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 196       | 32.78%  |
| Intel                             | 180       | 30.1%   |
| Qualcomm Atheros                  | 62        | 10.37%  |
| Broadcom                          | 35        | 5.85%   |
| MediaTek                          | 18        | 3.01%   |
| Broadcom Limited                  | 14        | 2.34%   |
| TP-Link                           | 12        | 2.01%   |
| Ralink Technology                 | 9         | 1.51%   |
| Marvell Technology Group          | 8         | 1.34%   |
| Samsung Electronics               | 5         | 0.84%   |
| Ralink                            | 5         | 0.84%   |
| Nvidia                            | 5         | 0.84%   |
| OPPO Electronics                  | 4         | 0.67%   |
| Motorola PCS                      | 4         | 0.67%   |
| Microsoft                         | 4         | 0.67%   |
| ASIX Electronics                  | 4         | 0.67%   |
| Qualcomm Atheros Communications   | 3         | 0.5%    |
| AVM                               | 3         | 0.5%    |
| Xiaomi                            | 2         | 0.33%   |
| Sierra Wireless                   | 2         | 0.33%   |
| Linksys                           | 2         | 0.33%   |
| D-Link                            | 2         | 0.33%   |
| VIA Technologies                  | 1         | 0.17%   |
| Sweex                             | 1         | 0.17%   |
| Qualcomm Technologies             | 1         | 0.17%   |
| NetGear                           | 1         | 0.17%   |
| Mercucys                          | 1         | 0.17%   |
| Lenovo                            | 1         | 0.17%   |
| JMicron Technology                | 1         | 0.17%   |
| IMC Networks                      | 1         | 0.17%   |
| Foxconn / Hon Hai                 | 1         | 0.17%   |
| Fibocom                           | 1         | 0.17%   |
| Ericsson Business Mobile Networks | 1         | 0.17%   |
| Edimax Technology                 | 1         | 0.17%   |
| Dell                              | 1         | 0.17%   |
| D-Link System                     | 1         | 0.17%   |
| Attansic Technology               | 1         | 0.17%   |
| ASUSTek Computer                  | 1         | 0.17%   |
| Aquantia                          | 1         | 0.17%   |
| Apple                             | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 129       | 18.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 17        | 2.44%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 2.3%    |
| Intel Wi-Fi 6 AX201                                                     | 13        | 1.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 12        | 1.72%   |
| Intel Wireless 8260                                                     | 12        | 1.72%   |
| Realtek RTL8125 2.5GbE Controller                                       | 11        | 1.58%   |
| Intel Ethernet Controller I225-V                                        | 10        | 1.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.29%   |
| Intel Ethernet Connection I217-LM                                       | 9         | 1.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.15%   |
| Intel Wireless 3165                                                     | 8         | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 1%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1%      |
| Intel Wireless 8265 / 8275                                              | 7         | 1%      |
| Intel Wireless 7265                                                     | 7         | 1%      |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.86%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 6         | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 0.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 5         | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 5         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.72%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 0.72%   |
| Intel Wireless 7260                                                     | 5         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 5         | 0.72%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                       | 5         | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.57%   |
| OPPO RMX3623                                                            | 4         | 0.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4         | 0.57%   |
| Intel Wireless-AC 9260                                                  | 4         | 0.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 0.57%   |
| Intel I211 Gigabit Network Connection                                   | 4         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 139       | 40.76%  |
| Realtek Semiconductor           | 59        | 17.3%   |
| Qualcomm Atheros                | 45        | 13.2%   |
| Broadcom                        | 22        | 6.45%   |
| MediaTek                        | 18        | 5.28%   |
| TP-Link                         | 11        | 3.23%   |
| Ralink Technology               | 9         | 2.64%   |
| Broadcom Limited                | 9         | 2.64%   |
| Ralink                          | 5         | 1.47%   |
| Qualcomm Atheros Communications | 3         | 0.88%   |
| AVM                             | 3         | 0.88%   |
| Sierra Wireless                 | 2         | 0.59%   |
| Microsoft                       | 2         | 0.59%   |
| Linksys                         | 2         | 0.59%   |
| D-Link                          | 2         | 0.59%   |
| Sweex                           | 1         | 0.29%   |
| Qualcomm Technologies           | 1         | 0.29%   |
| NetGear                         | 1         | 0.29%   |
| Mercucys                        | 1         | 0.29%   |
| Marvell Technology Group        | 1         | 0.29%   |
| IMC Networks                    | 1         | 0.29%   |
| Fibocom                         | 1         | 0.29%   |
| Edimax Technology               | 1         | 0.29%   |
| D-Link System                   | 1         | 0.29%   |
| ASUSTek Computer                | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 16        | 4.68%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 3.8%    |
| Intel Wireless 8260                                                     | 12        | 3.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 2.34%   |
| Intel Wireless 3165                                                     | 8         | 2.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 2.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 2.05%   |
| Intel Wireless 8265 / 8275                                              | 7         | 2.05%   |
| Intel Wireless 7265                                                     | 7         | 2.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 2.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.75%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 5         | 1.46%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 5         | 1.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 1.46%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.46%   |
| Intel Wireless 7260                                                     | 5         | 1.46%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4         | 1.17%   |
| Intel Wireless-AC 9260                                                  | 4         | 1.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.17%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 4         | 1.17%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.88%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.88%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.88%   |
| Intel Wireless 3160                                                     | 3         | 0.88%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.88%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 169       | 49.71%  |
| Intel                    | 85        | 25%     |
| Qualcomm Atheros         | 22        | 6.47%   |
| Broadcom                 | 21        | 6.18%   |
| Marvell Technology Group | 7         | 2.06%   |
| Nvidia                   | 5         | 1.47%   |
| Broadcom Limited         | 5         | 1.47%   |
| OPPO Electronics         | 4         | 1.18%   |
| ASIX Electronics         | 4         | 1.18%   |
| Samsung Electronics      | 3         | 0.88%   |
| Motorola PCS             | 3         | 0.88%   |
| Xiaomi                   | 2         | 0.59%   |
| Microsoft                | 2         | 0.59%   |
| VIA Technologies         | 1         | 0.29%   |
| TP-Link                  | 1         | 0.29%   |
| Lenovo                   | 1         | 0.29%   |
| JMicron Technology       | 1         | 0.29%   |
| Foxconn / Hon Hai        | 1         | 0.29%   |
| Attansic Technology      | 1         | 0.29%   |
| Aquantia                 | 1         | 0.29%   |
| Apple                    | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 129       | 37.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 4.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 3.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 3.16%   |
| Intel Ethernet Controller I225-V                                  | 10        | 2.87%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.59%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5         | 1.44%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 1.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.15%   |
| OPPO RMX3623                                                      | 4         | 1.15%   |
| Intel I211 Gigabit Network Connection                             | 4         | 1.15%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.15%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.15%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 1.15%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1.15%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.86%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.86%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.86%   |
| Motorola PCS moto g62 5G                                          | 3         | 0.86%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.86%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.57%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.57%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.57%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.57%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.57%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                 | 2         | 0.57%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.57%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.57%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.57%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 0.57%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 318       | 50.24%  |
| WiFi     | 308       | 48.66%  |
| Modem    | 6         | 0.95%   |
| Unknown  | 1         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 238       | 62.8%   |
| Ethernet | 141       | 37.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 215       | 57.33%  |
| 1     | 142       | 37.87%  |
| 3     | 8         | 2.13%   |
| 0     | 8         | 2.13%   |
| 4     | 2         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 275       | 73.14%  |
| Yes  | 101       | 26.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 105       | 43.21%  |
| Realtek Semiconductor           | 23        | 9.47%   |
| Qualcomm Atheros Communications | 18        | 7.41%   |
| Apple                           | 17        | 7%      |
| Foxconn / Hon Hai               | 13        | 5.35%   |
| Cambridge Silicon Radio         | 13        | 5.35%   |
| Broadcom                        | 11        | 4.53%   |
| Lite-On Technology              | 10        | 4.12%   |
| IMC Networks                    | 8         | 3.29%   |
| MediaTek                        | 7         | 2.88%   |
| Hewlett-Packard                 | 5         | 2.06%   |
| ASUSTek Computer                | 3         | 1.23%   |
| TP-Link                         | 2         | 0.82%   |
| Ralink                          | 2         | 0.82%   |
| Dell                            | 2         | 0.82%   |
| Realtek                         | 1         | 0.41%   |
| Ralink Technology               | 1         | 0.41%   |
| Marvell Semiconductor           | 1         | 0.41%   |
| Alps Electric                   | 1         | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 39        | 16.05%  |
| Realtek Bluetooth Radio                                                             | 20        | 8.23%   |
| Intel AX201 Bluetooth                                                               | 19        | 7.82%   |
| Intel AX200 Bluetooth                                                               | 16        | 6.58%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 13        | 5.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 12        | 4.94%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 3.7%    |
| MediaTek Wireless_Device                                                            | 7         | 2.88%   |
| Apple Bluetooth USB Host Controller                                                 | 6         | 2.47%   |
| Apple Bluetooth Host Controller                                                     | 6         | 2.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 1.65%   |
| Intel Bluetooth Device                                                              | 4         | 1.65%   |
| IMC Networks Wireless_Device                                                        | 4         | 1.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 1.65%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 1.23%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.23%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 1.23%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.23%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.23%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.23%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 1.23%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 1.23%   |
| TP-Link TP-Cdj+ UB5A Adapter                                                        | 2         | 0.82%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 0.82%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.82%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.82%   |
| Lite-On Wireless_Device                                                             | 2         | 0.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 0.82%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 0.82%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.82%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 0.82%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.82%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 0.82%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.82%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.41%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.41%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 273       | 53.01%  |
| AMD                        | 97        | 18.83%  |
| Nvidia                     | 86        | 16.7%   |
| C-Media Electronics        | 8         | 1.55%   |
| Creative Labs              | 5         | 0.97%   |
| VIA Technologies           | 3         | 0.58%   |
| Texas Instruments          | 3         | 0.58%   |
| JMTek                      | 3         | 0.58%   |
| Generalplus Technology     | 3         | 0.58%   |
| ROCCAT                     | 2         | 0.39%   |
| Realtek Semiconductor      | 2         | 0.39%   |
| BEHRINGER International    | 2         | 0.39%   |
| Apple                      | 2         | 0.39%   |
| TerraTec Electronic        | 1         | 0.19%   |
| Shenzhen Riitek Technology | 1         | 0.19%   |
| Setek Elektronik           | 1         | 0.19%   |
| Schiit Audio               | 1         | 0.19%   |
| Razer USA                  | 1         | 0.19%   |
| Plantronics                | 1         | 0.19%   |
| Microsoft                  | 1         | 0.19%   |
| M-Audio                    | 1         | 0.19%   |
| Logitech                   | 1         | 0.19%   |
| LG Electronics             | 1         | 0.19%   |
| Lenovo                     | 1         | 0.19%   |
| Kingston Technology        | 1         | 0.19%   |
| GYROCOM C&C                | 1         | 0.19%   |
| Guillemot                  | 1         | 0.19%   |
| GN Netcom                  | 1         | 0.19%   |
| Giga-Byte Technology       | 1         | 0.19%   |
| Focusrite-Novation         | 1         | 0.19%   |
| FIFINE 683 Microphone      | 1         | 0.19%   |
| Ensoniq                    | 1         | 0.19%   |
| Digidesign                 | 1         | 0.19%   |
| Dell                       | 1         | 0.19%   |
| Creative Technology        | 1         | 0.19%   |
| Conexant Systems           | 1         | 0.19%   |
| CMX Systems                | 1         | 0.19%   |
| Cambridge Silicon Radio    | 1         | 0.19%   |
| BR25                       | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 45        | 7.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 27        | 4.46%   |
| Intel Sunrise Point-LP HD Audio                                            | 26        | 4.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 26        | 4.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23        | 3.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 18        | 2.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16        | 2.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 16        | 2.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 15        | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 1.98%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 11        | 1.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 1.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10        | 1.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 1.65%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10        | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 1.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 1.16%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7         | 1.16%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 1.16%   |
| Nvidia GP104 High Definition Audio Controller                              | 6         | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 0.99%   |
| Nvidia Audio device                                                        | 6         | 0.99%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 0.99%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 0.99%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 0.99%   |
| AMD FCH Azalia Controller                                                  | 6         | 0.99%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 0.99%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.83%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 5         | 0.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 0.83%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 0.83%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 0.83%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 0.83%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 0.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 0.83%   |
| Intel Jasper Lake HD Audio                                                 | 4         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Samsung Electronics            | 93        | 21.48%  |
| SK hynix                       | 71        | 16.4%   |
| Unknown                        | 52        | 12.01%  |
| Kingston                       | 43        | 9.93%   |
| Micron Technology              | 35        | 8.08%   |
| Crucial                        | 25        | 5.77%   |
| Corsair                        | 22        | 5.08%   |
| A-DATA Technology              | 12        | 2.77%   |
| Ramaxel Technology             | 11        | 2.54%   |
| G.Skill                        | 11        | 2.54%   |
| Elpida                         | 10        | 2.31%   |
| Unknown (ABCD)                 | 8         | 1.85%   |
| Unknown                        | 6         | 1.39%   |
| Transcend                      | 5         | 1.15%   |
| Nanya Technology               | 5         | 1.15%   |
| Smart                          | 2         | 0.46%   |
| Patriot                        | 2         | 0.46%   |
| Lexar Co Limited               | 2         | 0.46%   |
| CSX                            | 2         | 0.46%   |
| Avant                          | 2         | 0.46%   |
| Wilk                           | 1         | 0.23%   |
| Unknown (AB)                   | 1         | 0.23%   |
| Unknown (0x0E9D)               | 1         | 0.23%   |
| Unifosa                        | 1         | 0.23%   |
| Team                           | 1         | 0.23%   |
| PNY                            | 1         | 0.23%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.23%   |
| Innodisk                       | 1         | 0.23%   |
| Hewlett-Packard                | 1         | 0.23%   |
| Golden Empire                  | 1         | 0.23%   |
| Essencore                      | 1         | 0.23%   |
| ASint Technology               | 1         | 0.23%   |
| Apacer                         | 1         | 0.23%   |
| 48spaces                       | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 7         | 1.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 6         | 1.3%    |
| Unknown                                                           | 6         | 1.3%    |
| Unknown RAM Module 4GB SODIMM DDR3                                | 5         | 1.08%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 5         | 1.08%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s             | 5         | 1.08%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                       | 4         | 0.87%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 4         | 0.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 4         | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 4         | 0.87%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s             | 4         | 0.87%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 3         | 0.65%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 3         | 0.65%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s             | 3         | 0.65%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s             | 3         | 0.65%   |
| Crucial RAM CT16G4SFRA32A.C16FR 16GB SODIMM DDR4 3200MT/s         | 3         | 0.65%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s           | 3         | 0.65%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                       | 2         | 0.43%   |
| Unknown RAM Module 8GB SODIMM DDR3                                | 2         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.43%   |
| Unknown RAM Module 4GB DIMM SDRAM                                 | 2         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                       | 2         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3                                | 2         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2                                | 2         | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                         | 2         | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                          | 2         | 0.43%   |
| Unknown RAM Module 2GB DIMM 667MT/s                               | 2         | 0.43%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.43%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                     | 2         | 0.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.43%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.43%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.43%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s              | 2         | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.43%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s            | 2         | 0.43%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s           | 2         | 0.43%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 2         | 0.43%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                       | 2         | 0.43%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                       | 2         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 159       | 42.06%  |
| DDR3    | 139       | 36.77%  |
| DDR2    | 22        | 5.82%   |
| LPDDR4  | 16        | 4.23%   |
| SDRAM   | 13        | 3.44%   |
| Unknown | 8         | 2.12%   |
| LPDDR3  | 6         | 1.59%   |
| DDR5    | 6         | 1.59%   |
| DDR     | 6         | 1.59%   |
| DRAM    | 2         | 0.53%   |
| LPDDR5  | 1         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 241       | 64.27%  |
| DIMM         | 111       | 29.6%   |
| Row Of Chips | 19        | 5.07%   |
| Unknown      | 2         | 0.53%   |
| FB-DIMM      | 1         | 0.27%   |
| Chip         | 1         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 131       | 32.27%  |
| 4096  | 123       | 30.3%   |
| 2048  | 62        | 15.27%  |
| 16384 | 58        | 14.29%  |
| 1024  | 19        | 4.68%   |
| 32768 | 11        | 2.71%   |
| 512   | 1         | 0.25%   |
| 256   | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 76        | 19%     |
| 3200    | 70        | 17.5%   |
| 2667    | 43        | 10.75%  |
| 1333    | 38        | 9.5%    |
| 2400    | 26        | 6.5%    |
| Unknown | 16        | 4%      |
| 1334    | 15        | 3.75%   |
| 667     | 14        | 3.5%    |
| 3600    | 12        | 3%      |
| 2133    | 12        | 3%      |
| 1067    | 9         | 2.25%   |
| 800     | 7         | 1.75%   |
| 1867    | 5         | 1.25%   |
| 533     | 5         | 1.25%   |
| 6000    | 3         | 0.75%   |
| 4267    | 3         | 0.75%   |
| 4199    | 3         | 0.75%   |
| 3733    | 3         | 0.75%   |
| 3266    | 3         | 0.75%   |
| 2933    | 3         | 0.75%   |
| 2048    | 3         | 0.75%   |
| 1800    | 3         | 0.75%   |
| 4800    | 2         | 0.5%    |
| 3400    | 2         | 0.5%    |
| 3000    | 2         | 0.5%    |
| 2666    | 2         | 0.5%    |
| 1866    | 2         | 0.5%    |
| 975     | 2         | 0.5%    |
| 333     | 2         | 0.5%    |
| 8400    | 1         | 0.25%   |
| 5800    | 1         | 0.25%   |
| 5500    | 1         | 0.25%   |
| 4266    | 1         | 0.25%   |
| 4133    | 1         | 0.25%   |
| 3866    | 1         | 0.25%   |
| 3533    | 1         | 0.25%   |
| 2800    | 1         | 0.25%   |
| 2200    | 1         | 0.25%   |
| 2000    | 1         | 0.25%   |
| 1639    | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 4         | 33.33%  |
| Canon              | 4         | 33.33%  |
| Brother Industries | 4         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon MF641C             | 2         | 16.67%  |
| HP LaserJet P2055 series | 1         | 8.33%   |
| HP LaserJet 1022         | 1         | 8.33%   |
| HP ENVY 4500 series      | 1         | 8.33%   |
| HP Deskjet 1510          | 1         | 8.33%   |
| Canon MG5700 series      | 1         | 8.33%   |
| Canon LiDE 400           | 1         | 8.33%   |
| Brother Printer          | 1         | 8.33%   |
| Brother MFC-7340         | 1         | 8.33%   |
| Brother HL-2150N series  | 1         | 8.33%   |
| Brother DCP-L2540DW      | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan N1240U/LiDE 30      | 1         | 33.33%  |
| Canon CanoScan LiDE 210            | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 49        | 21.12%  |
| IMC Networks                           | 21        | 9.05%   |
| Microdia                               | 19        | 8.19%   |
| Realtek Semiconductor                  | 16        | 6.9%    |
| Bison Electronics                      | 14        | 6.03%   |
| Quanta                                 | 13        | 5.6%    |
| Cheng Uei Precision Industry (Foxlink) | 12        | 5.17%   |
| Logitech                               | 11        | 4.74%   |
| Apple                                  | 11        | 4.74%   |
| Sunplus Innovation Technology          | 10        | 4.31%   |
| Luxvisions Innotech Limited            | 7         | 3.02%   |
| Suyin                                  | 6         | 2.59%   |
| Lite-On Technology                     | 6         | 2.59%   |
| Acer                                   | 5         | 2.16%   |
| Ricoh                                  | 4         | 1.72%   |
| Microsoft                              | 4         | 1.72%   |
| Alcor Micro                            | 4         | 1.72%   |
| Silicon Motion                         | 3         | 1.29%   |
| Lenovo                                 | 3         | 1.29%   |
| Hewlett-Packard                        | 2         | 0.86%   |
| Z-Star Microelectronics                | 1         | 0.43%   |
| Y Media                                | 1         | 0.43%   |
| Sonix Technology                       | 1         | 0.43%   |
| Primax Electronics                     | 1         | 0.43%   |
| Pixart Imaging                         | 1         | 0.43%   |
| Novatek Microelectronics               | 1         | 0.43%   |
| LG Electronics                         | 1         | 0.43%   |
| Goodong Industry                       | 1         | 0.43%   |
| Generalplus Technology                 | 1         | 0.43%   |
| GEMBIRD                                | 1         | 0.43%   |
| Arkmicro Technologies                  | 1         | 0.43%   |
| 8SSC20F27114V1SR0BK1X4S                | 1         | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 12        | 5.15%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 7         | 3%      |
| Bison Integrated Camera                              | 6         | 2.58%   |
| Microdia Integrated_Webcam_HD                        | 5         | 2.15%   |
| Realtek Integrated_Webcam_HD                         | 4         | 1.72%   |
| Quanta HD User Facing                                | 4         | 1.72%   |
| Logitech Webcam C930e                                | 4         | 1.72%   |
| IMC Networks Integrated Camera                       | 4         | 1.72%   |
| Apple FaceTime HD Camera (Built-in)                  | 4         | 1.72%   |
| Apple Built-in iSight                                | 4         | 1.72%   |
| Quanta HP TrueVision HD Camera                       | 3         | 1.29%   |
| Lite-On HP HD Camera                                 | 3         | 1.29%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 1.29%   |
| Chicony HD WebCam                                    | 3         | 1.29%   |
| Chicony HD User Facing                               | 3         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 3         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 3         | 1.29%   |
| Alcor Micro USB 2.0 Camera                           | 3         | 1.29%   |
| Acer BisonCam,NB Pro                                 | 3         | 1.29%   |
| Suyin Acer CrystalEye Webcam                         | 2         | 0.86%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 0.86%   |
| Sunplus Integrated_Webcam_FHD                        | 2         | 0.86%   |
| Sunplus HD WebCam                                    | 2         | 0.86%   |
| Sunplus HD 720P webcam                               | 2         | 0.86%   |
| Ricoh USB2.0 Camera                                  | 2         | 0.86%   |
| Realtek USB2.0 HD UVC WebCam                         | 2         | 0.86%   |
| Realtek USB Camera                                   | 2         | 0.86%   |
| Microsoft LifeCam HD-3000                            | 2         | 0.86%   |
| Microdia Webcam Vitade AF                            | 2         | 0.86%   |
| Microdia USB Camera                                  | 2         | 0.86%   |
| Microdia USB 2.0 Camera                              | 2         | 0.86%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.86%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 0.86%   |
| Logitech Webcam C270                                 | 2         | 0.86%   |
| Lenovo Integrated Webcam [R5U877]                    | 2         | 0.86%   |
| IMC Networks XHC Camera                              | 2         | 0.86%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 0.86%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 2         | 0.86%   |
| Chicony HP Wide Vision FHD Camera                    | 2         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 2         | 0.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 13        | 30.23%  |
| Synaptics                          | 8         | 18.6%   |
| Shenzhen Goodix Technology         | 7         | 16.28%  |
| AuthenTec                          | 5         | 11.63%  |
| Elan Microelectronics              | 4         | 9.3%    |
| Upek                               | 3         | 6.98%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.33%   |
| Microsoft                          | 1         | 2.33%   |
| Focal-systems.Corp                 | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 11.63%  |
| Shenzhen Goodix  FingerPrint Device                             | 5         | 11.63%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 4         | 9.3%    |
| AuthenTec AES2810                                               | 3         | 6.98%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 2         | 4.65%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 4.65%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 4.65%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 4.65%   |
| Elan ELAN:Fingerprint                                           | 2         | 4.65%   |
| Elan ELAN:ARM-M4                                                | 2         | 4.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 2.33%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 2.33%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 2.33%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 2.33%   |
| Upek TCS5B Fingerprint sensor                                   | 1         | 2.33%   |
| Synaptics WBDI Fingerprint Reader USB 102                       | 1         | 2.33%   |
| Synaptics UWP WBDI Device                                       | 1         | 2.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 2.33%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.33%   |
| Microsoft Fingerprint Reader                                    | 1         | 2.33%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 2.33%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 1         | 2.33%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 2.33%   |
| Unknown                                                         | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 42.86%  |
| Alcor Micro           | 6         | 42.86%  |
| Advanced Card Systems | 2         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 6         | 42.86%  |
| Broadcom 5880                                  | 4         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 7.14%   |
| Broadcom 58200                                 | 1         | 7.14%   |
| Advanced Card Systems ACR38 SmartCard Reader   | 1         | 7.14%   |
| Advanced Card Systems ACR122U                  | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 252       | 66.32%  |
| 1     | 93        | 24.47%  |
| 2     | 30        | 7.89%   |
| 3     | 5         | 1.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 67        | 42.95%  |
| Fingerprint reader       | 43        | 27.56%  |
| Net/wireless             | 12        | 7.69%   |
| Chipcard                 | 12        | 7.69%   |
| Multimedia controller    | 5         | 3.21%   |
| Communication controller | 5         | 3.21%   |
| Unassigned class         | 3         | 1.92%   |
| Camera                   | 3         | 1.92%   |
| Net/ethernet             | 2         | 1.28%   |
| Sound                    | 1         | 0.64%   |
| Flash memory             | 1         | 0.64%   |
| Dvb card                 | 1         | 0.64%   |
| Bluetooth                | 1         | 0.64%   |

