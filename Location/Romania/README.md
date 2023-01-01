Linux in Romania - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Romania.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Romania/Desktop/README.md) and [notebooks](/Location/Romania/Notebook/README.md).

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

Total: 2318

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [8db34630c3](https://linux-hardware.org/?probe=8db34630c3) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1ff4c4bf09](https://linux-hardware.org/?probe=1ff4c4bf09) | Dec 28, 2022 |
| Lenovo        | No DPK                      | Desktop     | [944f84567a](https://linux-hardware.org/?probe=944f84567a) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ad33bb0d6f](https://linux-hardware.org/?probe=ad33bb0d6f) | Dec 28, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [57a42cabf6](https://linux-hardware.org/?probe=57a42cabf6) | Dec 27, 2022 |
| Dell          | Latitude 7480               | Notebook    | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [62869e3d8c](https://linux-hardware.org/?probe=62869e3d8c) | Dec 26, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [5aa14f474e](https://linux-hardware.org/?probe=5aa14f474e) | Dec 25, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fa7183c982](https://linux-hardware.org/?probe=fa7183c982) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [9a6b000b23](https://linux-hardware.org/?probe=9a6b000b23) | Dec 23, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [7defe87998](https://linux-hardware.org/?probe=7defe87998) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fe159bf4ca](https://linux-hardware.org/?probe=fe159bf4ca) | Dec 23, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [2892951c9c](https://linux-hardware.org/?probe=2892951c9c) | Dec 23, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [81f7e4d804](https://linux-hardware.org/?probe=81f7e4d804) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [ddc35a5b0d](https://linux-hardware.org/?probe=ddc35a5b0d) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | Notebook    | [6306be2273](https://linux-hardware.org/?probe=6306be2273) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | Notebook    | [cf8576151f](https://linux-hardware.org/?probe=cf8576151f) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [721bc5f662](https://linux-hardware.org/?probe=721bc5f662) | Dec 21, 2022 |
| HP            | 89E8 0100                   | All in one  | [0e9567b0a5](https://linux-hardware.org/?probe=0e9567b0a5) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d9db7be046](https://linux-hardware.org/?probe=d9db7be046) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [d27a2a4e0f](https://linux-hardware.org/?probe=d27a2a4e0f) | Dec 20, 2022 |
| Dell          | 0VHWTR A01                  | Desktop     | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [89b8982148](https://linux-hardware.org/?probe=89b8982148) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [082a1fb19e](https://linux-hardware.org/?probe=082a1fb19e) | Dec 20, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [30aec905c0](https://linux-hardware.org/?probe=30aec905c0) | Dec 19, 2022 |
| ASRock        | X670E Steel Legend          | Desktop     | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [20544e55bb](https://linux-hardware.org/?probe=20544e55bb) | Dec 14, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d087536cbf](https://linux-hardware.org/?probe=d087536cbf) | Dec 14, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [20c4b98c2c](https://linux-hardware.org/?probe=20c4b98c2c) | Dec 14, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| MSI           | MS-B1591                    | Desktop     | [33cb107fb9](https://linux-hardware.org/?probe=33cb107fb9) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [a1f1288337](https://linux-hardware.org/?probe=a1f1288337) | Dec 13, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [d1b0bc1c03](https://linux-hardware.org/?probe=d1b0bc1c03) | Dec 12, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [05c7382806](https://linux-hardware.org/?probe=05c7382806) | Dec 11, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [97691e3dca](https://linux-hardware.org/?probe=97691e3dca) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a7a3ccf712](https://linux-hardware.org/?probe=a7a3ccf712) | Dec 11, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [32e7431c24](https://linux-hardware.org/?probe=32e7431c24) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [83b02f1ffb](https://linux-hardware.org/?probe=83b02f1ffb) | Dec 10, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ec32b72261](https://linux-hardware.org/?probe=ec32b72261) | Dec 09, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [e7495f12e4](https://linux-hardware.org/?probe=e7495f12e4) | Dec 08, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [6844d4578b](https://linux-hardware.org/?probe=6844d4578b) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ea7638c0f9](https://linux-hardware.org/?probe=ea7638c0f9) | Dec 07, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [fd65cfedda](https://linux-hardware.org/?probe=fd65cfedda) | Dec 07, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [10f8aab734](https://linux-hardware.org/?probe=10f8aab734) | Dec 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a35bac4078](https://linux-hardware.org/?probe=a35bac4078) | Dec 06, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [2f693620e1](https://linux-hardware.org/?probe=2f693620e1) | Dec 06, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [586b9fe0a6](https://linux-hardware.org/?probe=586b9fe0a6) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b387887bb6](https://linux-hardware.org/?probe=b387887bb6) | Dec 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [d5ada57985](https://linux-hardware.org/?probe=d5ada57985) | Dec 03, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [56a2d42adc](https://linux-hardware.org/?probe=56a2d42adc) | Dec 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3d64de28f5](https://linux-hardware.org/?probe=3d64de28f5) | Dec 01, 2022 |
| MSI           | G41M-S03                    | Desktop     | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1FR0... | Notebook    | [517347d2cf](https://linux-hardware.org/?probe=517347d2cf) | Nov 30, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b7a1fc62d1](https://linux-hardware.org/?probe=b7a1fc62d1) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [8e6e8471a7](https://linux-hardware.org/?probe=8e6e8471a7) | Nov 29, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [972f6f4355](https://linux-hardware.org/?probe=972f6f4355) | Nov 28, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [40c84f5af9](https://linux-hardware.org/?probe=40c84f5af9) | Nov 28, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [5b2f9bfd5c](https://linux-hardware.org/?probe=5b2f9bfd5c) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a39632439e](https://linux-hardware.org/?probe=a39632439e) | Nov 27, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [c58c83e367](https://linux-hardware.org/?probe=c58c83e367) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [85b508d6d3](https://linux-hardware.org/?probe=85b508d6d3) | Nov 26, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [20015fb913](https://linux-hardware.org/?probe=20015fb913) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [16679f50e3](https://linux-hardware.org/?probe=16679f50e3) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a178e673c3](https://linux-hardware.org/?probe=a178e673c3) | Nov 26, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [c1d5a26691](https://linux-hardware.org/?probe=c1d5a26691) | Nov 26, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a41bb9177a](https://linux-hardware.org/?probe=a41bb9177a) | Nov 23, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [52d46ed47e](https://linux-hardware.org/?probe=52d46ed47e) | Nov 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [6c797b4554](https://linux-hardware.org/?probe=6c797b4554) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [b8379d261b](https://linux-hardware.org/?probe=b8379d261b) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| Dell          | Latitude E6410              | Notebook    | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [75af06e026](https://linux-hardware.org/?probe=75af06e026) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c5ec7b9dcc](https://linux-hardware.org/?probe=c5ec7b9dcc) | Nov 20, 2022 |
| Lenovo        | V15 G1 IML 82NB             | Notebook    | [a120cac88b](https://linux-hardware.org/?probe=a120cac88b) | Nov 18, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [2089ec3efb](https://linux-hardware.org/?probe=2089ec3efb) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | Desktop     | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Allview       | Allbook H                   | Notebook    | [4de72c8cba](https://linux-hardware.org/?probe=4de72c8cba) | Nov 17, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| HP            | 843B                        | Desktop     | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [30916d8420](https://linux-hardware.org/?probe=30916d8420) | Nov 16, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [a1e3d4527c](https://linux-hardware.org/?probe=a1e3d4527c) | Nov 15, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [fef97563a0](https://linux-hardware.org/?probe=fef97563a0) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [61bcea3891](https://linux-hardware.org/?probe=61bcea3891) | Nov 13, 2022 |
| Alienware     | Area-51m                    | Notebook    | [11c59a838f](https://linux-hardware.org/?probe=11c59a838f) | Nov 12, 2022 |
| Dell          | Latitude E7270              | Notebook    | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e80d2221f5](https://linux-hardware.org/?probe=e80d2221f5) | Nov 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [0144bb5a89](https://linux-hardware.org/?probe=0144bb5a89) | Nov 08, 2022 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [8384350121](https://linux-hardware.org/?probe=8384350121) | Nov 08, 2022 |
| Acer          | Aspire A314-35              | Notebook    | [14751e1ae3](https://linux-hardware.org/?probe=14751e1ae3) | Nov 08, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [5800bb0b18](https://linux-hardware.org/?probe=5800bb0b18) | Nov 06, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f8d2bbf15a](https://linux-hardware.org/?probe=f8d2bbf15a) | Nov 06, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [12c49f9e36](https://linux-hardware.org/?probe=12c49f9e36) | Nov 05, 2022 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [f435ef302a](https://linux-hardware.org/?probe=f435ef302a) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [55293ff823](https://linux-hardware.org/?probe=55293ff823) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [7dc3ed5f76](https://linux-hardware.org/?probe=7dc3ed5f76) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [1563c60737](https://linux-hardware.org/?probe=1563c60737) | Oct 31, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81A8     | Notebook    | [85efda7536](https://linux-hardware.org/?probe=85efda7536) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [f9238c2035](https://linux-hardware.org/?probe=f9238c2035) | Oct 28, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [9e8ec19352](https://linux-hardware.org/?probe=9e8ec19352) | Oct 26, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [7dca4296ee](https://linux-hardware.org/?probe=7dca4296ee) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [7274eca48b](https://linux-hardware.org/?probe=7274eca48b) | Oct 23, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [18e52559a4](https://linux-hardware.org/?probe=18e52559a4) | Oct 17, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [84941aaa84](https://linux-hardware.org/?probe=84941aaa84) | Oct 14, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [a6a5cdbf04](https://linux-hardware.org/?probe=a6a5cdbf04) | Oct 13, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [478ba58d34](https://linux-hardware.org/?probe=478ba58d34) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| ASUSTek       | V222GAR                     | All in one  | [e7e07dca5c](https://linux-hardware.org/?probe=e7e07dca5c) | Oct 12, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [79236a7a89](https://linux-hardware.org/?probe=79236a7a89) | Oct 11, 2022 |
| Medion        | Akoya E6239                 | Notebook    | [46ce690b32](https://linux-hardware.org/?probe=46ce690b32) | Oct 10, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [abc991002e](https://linux-hardware.org/?probe=abc991002e) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8694ed82a6](https://linux-hardware.org/?probe=8694ed82a6) | Oct 09, 2022 |
| Dell          | Latitude E6410              | Notebook    | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [889099ff63](https://linux-hardware.org/?probe=889099ff63) | Oct 05, 2022 |
| HP            | 2AED                        | All in one  | [9092720ed6](https://linux-hardware.org/?probe=9092720ed6) | Oct 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d9474bd3b9](https://linux-hardware.org/?probe=d9474bd3b9) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [cf4537f9cb](https://linux-hardware.org/?probe=cf4537f9cb) | Oct 02, 2022 |
| Medion        | Akoya P2214T                | Notebook    | [428205d2a5](https://linux-hardware.org/?probe=428205d2a5) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [26961d1b30](https://linux-hardware.org/?probe=26961d1b30) | Sep 29, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [3e92ba3812](https://linux-hardware.org/?probe=3e92ba3812) | Sep 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [96c4c8ba02](https://linux-hardware.org/?probe=96c4c8ba02) | Sep 28, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [11f99758e6](https://linux-hardware.org/?probe=11f99758e6) | Sep 28, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| Lenovo        | ThinkPad T420 4236C53       | Notebook    | [e0983b35fa](https://linux-hardware.org/?probe=e0983b35fa) | Sep 25, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [deed57ec88](https://linux-hardware.org/?probe=deed57ec88) | Sep 23, 2022 |
| Acer          | Aspire 5750Z                | Notebook    | [38e1cc9153](https://linux-hardware.org/?probe=38e1cc9153) | Sep 22, 2022 |
| Fusion5       | S14                         | Notebook    | [9b3e06c4e4](https://linux-hardware.org/?probe=9b3e06c4e4) | Sep 22, 2022 |
| Acer          | Aspire 5750Z                | Notebook    | [b673d5cfe9](https://linux-hardware.org/?probe=b673d5cfe9) | Sep 22, 2022 |
| Dell          | Precision 3561              | Notebook    | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [aba8915769](https://linux-hardware.org/?probe=aba8915769) | Sep 19, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [d52ac897f4](https://linux-hardware.org/?probe=d52ac897f4) | Sep 15, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [39f83f7692](https://linux-hardware.org/?probe=39f83f7692) | Sep 13, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2af6edb7a0](https://linux-hardware.org/?probe=2af6edb7a0) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [b018911117](https://linux-hardware.org/?probe=b018911117) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [43311add57](https://linux-hardware.org/?probe=43311add57) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c13cd2c2ac](https://linux-hardware.org/?probe=c13cd2c2ac) | Sep 09, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [3474424d64](https://linux-hardware.org/?probe=3474424d64) | Sep 04, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3ac55201b6](https://linux-hardware.org/?probe=3ac55201b6) | Sep 04, 2022 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [a2962588fa](https://linux-hardware.org/?probe=a2962588fa) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [e47c8e6967](https://linux-hardware.org/?probe=e47c8e6967) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [3f805d59b5](https://linux-hardware.org/?probe=3f805d59b5) | Sep 04, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [b91c67af87](https://linux-hardware.org/?probe=b91c67af87) | Sep 02, 2022 |
| Dell          | Latitude 5521               | Notebook    | [dcf7869cf6](https://linux-hardware.org/?probe=dcf7869cf6) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [b4a9d1fecc](https://linux-hardware.org/?probe=b4a9d1fecc) | Aug 30, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [c129f7c9b1](https://linux-hardware.org/?probe=c129f7c9b1) | Aug 29, 2022 |
| Dell          | Latitude E7470              | Notebook    | [568c9bfd40](https://linux-hardware.org/?probe=568c9bfd40) | Aug 28, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [4c16a58579](https://linux-hardware.org/?probe=4c16a58579) | Aug 28, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [fbf3d4a87a](https://linux-hardware.org/?probe=fbf3d4a87a) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [02c6bde77b](https://linux-hardware.org/?probe=02c6bde77b) | Aug 27, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [8b85141416](https://linux-hardware.org/?probe=8b85141416) | Aug 26, 2022 |
| Complet       | MY8312                      | Notebook    | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [09feb7053d](https://linux-hardware.org/?probe=09feb7053d) | Aug 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [69281b6cc3](https://linux-hardware.org/?probe=69281b6cc3) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [2af48f00ac](https://linux-hardware.org/?probe=2af48f00ac) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [0910ca3887](https://linux-hardware.org/?probe=0910ca3887) | Aug 22, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [5cf178d7ac](https://linux-hardware.org/?probe=5cf178d7ac) | Aug 22, 2022 |
| Dell          | Latitude 7410               | Notebook    | [ae90ce90ed](https://linux-hardware.org/?probe=ae90ce90ed) | Aug 22, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [5cbe471be8](https://linux-hardware.org/?probe=5cbe471be8) | Aug 19, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [1a0800fc4a](https://linux-hardware.org/?probe=1a0800fc4a) | Aug 19, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [b4bc42c01c](https://linux-hardware.org/?probe=b4bc42c01c) | Aug 18, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [4b585d8c34](https://linux-hardware.org/?probe=4b585d8c34) | Aug 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [f45a97ca40](https://linux-hardware.org/?probe=f45a97ca40) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [9e77f6044a](https://linux-hardware.org/?probe=9e77f6044a) | Aug 12, 2022 |
| Intel         | DQ67SW AAG12527-309         | Desktop     | [ca6a3b3fba](https://linux-hardware.org/?probe=ca6a3b3fba) | Aug 12, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [cdee8ca864](https://linux-hardware.org/?probe=cdee8ca864) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [eb79423b1d](https://linux-hardware.org/?probe=eb79423b1d) | Aug 12, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [86523f9a5f](https://linux-hardware.org/?probe=86523f9a5f) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [6826a8d40d](https://linux-hardware.org/?probe=6826a8d40d) | Aug 08, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [83626d765b](https://linux-hardware.org/?probe=83626d765b) | Aug 08, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [94d50a1c56](https://linux-hardware.org/?probe=94d50a1c56) | Aug 08, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [1fe8a14d3b](https://linux-hardware.org/?probe=1fe8a14d3b) | Aug 06, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d47b2c5c2b](https://linux-hardware.org/?probe=d47b2c5c2b) | Aug 06, 2022 |
| Unknown       | 1.0                         | Desktop     | [4394243123](https://linux-hardware.org/?probe=4394243123) | Aug 05, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G713RS_G713RS     | Notebook    | [707ab083b3](https://linux-hardware.org/?probe=707ab083b3) | Aug 04, 2022 |
| Unknown       | 1.0                         | Desktop     | [545d9cf73c](https://linux-hardware.org/?probe=545d9cf73c) | Aug 04, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [fbe4f4d2ce](https://linux-hardware.org/?probe=fbe4f4d2ce) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [eeccdc2b7f](https://linux-hardware.org/?probe=eeccdc2b7f) | Aug 02, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e6bfde2a29](https://linux-hardware.org/?probe=e6bfde2a29) | Jul 29, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8b3fd99e18](https://linux-hardware.org/?probe=8b3fd99e18) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4ee4fc0689](https://linux-hardware.org/?probe=4ee4fc0689) | Jul 26, 2022 |
| HP            | 8704                        | Desktop     | [eaa4bc0059](https://linux-hardware.org/?probe=eaa4bc0059) | Jul 21, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | Notebook    | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [892229b650](https://linux-hardware.org/?probe=892229b650) | Jul 21, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [9a5f11c4b9](https://linux-hardware.org/?probe=9a5f11c4b9) | Jul 19, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [383ec7a7fd](https://linux-hardware.org/?probe=383ec7a7fd) | Jul 18, 2022 |
| Acer          | Aspire SW3-016              | Notebook    | [c48cdf5576](https://linux-hardware.org/?probe=c48cdf5576) | Jul 17, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [84cd652e24](https://linux-hardware.org/?probe=84cd652e24) | Jul 16, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [55efce6cdc](https://linux-hardware.org/?probe=55efce6cdc) | Jul 13, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [be909dd3b4](https://linux-hardware.org/?probe=be909dd3b4) | Jul 12, 2022 |
| HP            | 355 G2                      | Notebook    | [55239c5062](https://linux-hardware.org/?probe=55239c5062) | Jul 11, 2022 |
| HP            | 355 G2                      | Notebook    | [9b5e64b838](https://linux-hardware.org/?probe=9b5e64b838) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e7b17323df](https://linux-hardware.org/?probe=e7b17323df) | Jul 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| HP            | 250 G4                      | Notebook    | [33dcd9203d](https://linux-hardware.org/?probe=33dcd9203d) | Jul 09, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [a9dd7c4072](https://linux-hardware.org/?probe=a9dd7c4072) | Jul 08, 2022 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | Notebook    | [99172a6e6f](https://linux-hardware.org/?probe=99172a6e6f) | Jul 08, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [cb302e010e](https://linux-hardware.org/?probe=cb302e010e) | Jul 08, 2022 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [f991c1fba8](https://linux-hardware.org/?probe=f991c1fba8) | Jul 07, 2022 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [a5f338ae1a](https://linux-hardware.org/?probe=a5f338ae1a) | Jul 07, 2022 |
| HP            | ProBook 4310s               | Notebook    | [86ae79b260](https://linux-hardware.org/?probe=86ae79b260) | Jul 07, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [32463f298d](https://linux-hardware.org/?probe=32463f298d) | Jul 05, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [457aa90e64](https://linux-hardware.org/?probe=457aa90e64) | Jul 02, 2022 |
| Dell          | Latitude 5521               | Notebook    | [2fda374f06](https://linux-hardware.org/?probe=2fda374f06) | Jun 24, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [eeac425783](https://linux-hardware.org/?probe=eeac425783) | Jun 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [2791443b0d](https://linux-hardware.org/?probe=2791443b0d) | Jun 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [fc053b8a95](https://linux-hardware.org/?probe=fc053b8a95) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [70d6947d54](https://linux-hardware.org/?probe=70d6947d54) | Jun 16, 2022 |
| HP            | 1790                        | Desktop     | [341a6c4c70](https://linux-hardware.org/?probe=341a6c4c70) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [1e88796016](https://linux-hardware.org/?probe=1e88796016) | Jun 15, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4b2037715f](https://linux-hardware.org/?probe=4b2037715f) | Jun 15, 2022 |
| Acer          | Aspire One 522              | Notebook    | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| Dell          | Latitude E6440              | Notebook    | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a144e0b75e](https://linux-hardware.org/?probe=a144e0b75e) | Jun 08, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [992f232db5](https://linux-hardware.org/?probe=992f232db5) | Jun 08, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [ef5b8100ce](https://linux-hardware.org/?probe=ef5b8100ce) | Jun 07, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Prestigio     | PSB141C04CGP                | Notebook    | [4fa2ee47c0](https://linux-hardware.org/?probe=4fa2ee47c0) | Jun 01, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [65ae31976a](https://linux-hardware.org/?probe=65ae31976a) | May 31, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [083e3a354a](https://linux-hardware.org/?probe=083e3a354a) | May 29, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [83209051cb](https://linux-hardware.org/?probe=83209051cb) | May 29, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [74c64ebe72](https://linux-hardware.org/?probe=74c64ebe72) | May 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [940a448ea6](https://linux-hardware.org/?probe=940a448ea6) | May 24, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [51aaf4adcd](https://linux-hardware.org/?probe=51aaf4adcd) | May 24, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [3115570400](https://linux-hardware.org/?probe=3115570400) | May 24, 2022 |
| Allview       | Allbook H                   | Notebook    | [9ea4897c6b](https://linux-hardware.org/?probe=9ea4897c6b) | May 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [b01633e1ae](https://linux-hardware.org/?probe=b01633e1ae) | May 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [815dbb114b](https://linux-hardware.org/?probe=815dbb114b) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9a6c29a243](https://linux-hardware.org/?probe=9a6c29a243) | May 21, 2022 |
| Acer          | Aspire One 522              | Notebook    | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [739ffac681](https://linux-hardware.org/?probe=739ffac681) | May 21, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [949f8f3e50](https://linux-hardware.org/?probe=949f8f3e50) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [4d2d33c41c](https://linux-hardware.org/?probe=4d2d33c41c) | May 20, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [59d945a9b3](https://linux-hardware.org/?probe=59d945a9b3) | May 19, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [60579b7d68](https://linux-hardware.org/?probe=60579b7d68) | May 18, 2022 |
| Lenovo        | ThinkPad P53 20QNS01900     | Notebook    | [158f212b30](https://linux-hardware.org/?probe=158f212b30) | May 13, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [550824d592](https://linux-hardware.org/?probe=550824d592) | May 12, 2022 |
| HP            | 0AA8h                       | Desktop     | [7d29587a1a](https://linux-hardware.org/?probe=7d29587a1a) | May 11, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [324d1abe3b](https://linux-hardware.org/?probe=324d1abe3b) | May 08, 2022 |
| HP            | ProBook 4520s               | Notebook    | [06e044a425](https://linux-hardware.org/?probe=06e044a425) | May 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [52c2a321a4](https://linux-hardware.org/?probe=52c2a321a4) | May 07, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [9fe037820e](https://linux-hardware.org/?probe=9fe037820e) | May 05, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [7a6aa0c236](https://linux-hardware.org/?probe=7a6aa0c236) | May 03, 2022 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [713358f855](https://linux-hardware.org/?probe=713358f855) | May 02, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [a8e967a378](https://linux-hardware.org/?probe=a8e967a378) | May 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6537fb670a](https://linux-hardware.org/?probe=6537fb670a) | May 01, 2022 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [26cd3478c5](https://linux-hardware.org/?probe=26cd3478c5) | Apr 30, 2022 |
| HP            | ProBook 4520s               | Notebook    | [60eab2c6c5](https://linux-hardware.org/?probe=60eab2c6c5) | Apr 30, 2022 |
| Pegatron      | Spring Peak                 | Notebook    | [66a1692171](https://linux-hardware.org/?probe=66a1692171) | Apr 30, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [8dd4d42608](https://linux-hardware.org/?probe=8dd4d42608) | Apr 29, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [efcd6be006](https://linux-hardware.org/?probe=efcd6be006) | Apr 27, 2022 |
| Dell          | Latitude E4310              | Notebook    | [41db45879c](https://linux-hardware.org/?probe=41db45879c) | Apr 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [afe44fa080](https://linux-hardware.org/?probe=afe44fa080) | Apr 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8ece944a7b](https://linux-hardware.org/?probe=8ece944a7b) | Apr 27, 2022 |
| Dell          | Latitude E6520              | Notebook    | [1ca407a69f](https://linux-hardware.org/?probe=1ca407a69f) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bcc0c7612d](https://linux-hardware.org/?probe=bcc0c7612d) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1EH0... | Notebook    | [fae5ee6551](https://linux-hardware.org/?probe=fae5ee6551) | Apr 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [c7dfc69b32](https://linux-hardware.org/?probe=c7dfc69b32) | Apr 26, 2022 |
| HP            | ProBook 4520s               | Notebook    | [1621eddc70](https://linux-hardware.org/?probe=1621eddc70) | Apr 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1d1c33575f](https://linux-hardware.org/?probe=1d1c33575f) | Apr 24, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | Notebook    | [41276f12db](https://linux-hardware.org/?probe=41276f12db) | Apr 23, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | Notebook    | [55733b5ae3](https://linux-hardware.org/?probe=55733b5ae3) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [a551ef1ec7](https://linux-hardware.org/?probe=a551ef1ec7) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [fd6718859d](https://linux-hardware.org/?probe=fd6718859d) | Apr 23, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [2518b6daad](https://linux-hardware.org/?probe=2518b6daad) | Apr 22, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [17d51c502f](https://linux-hardware.org/?probe=17d51c502f) | Apr 22, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [bc175803f2](https://linux-hardware.org/?probe=bc175803f2) | Apr 22, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a3a204ed56](https://linux-hardware.org/?probe=a3a204ed56) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [4521315d14](https://linux-hardware.org/?probe=4521315d14) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [fff2447e5a](https://linux-hardware.org/?probe=fff2447e5a) | Apr 21, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | Notebook    | [de746c72d1](https://linux-hardware.org/?probe=de746c72d1) | Apr 20, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [5d95841f54](https://linux-hardware.org/?probe=5d95841f54) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | Notebook    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [8b54af493a](https://linux-hardware.org/?probe=8b54af493a) | Apr 19, 2022 |
| Dell          | Latitude E6440              | Notebook    | [33955db41e](https://linux-hardware.org/?probe=33955db41e) | Apr 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1825f45bfa](https://linux-hardware.org/?probe=1825f45bfa) | Apr 17, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| HP            | Pavilion 17                 | Notebook    | [acb0c7fd0e](https://linux-hardware.org/?probe=acb0c7fd0e) | Apr 16, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | Notebook    | [a572c901ca](https://linux-hardware.org/?probe=a572c901ca) | Apr 15, 2022 |
| HP            | Pavilion 17                 | Notebook    | [014f42ecee](https://linux-hardware.org/?probe=014f42ecee) | Apr 15, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [73d1368d93](https://linux-hardware.org/?probe=73d1368d93) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [9709ffeb9a](https://linux-hardware.org/?probe=9709ffeb9a) | Apr 14, 2022 |
| Dell          | System XPS L702X            | Notebook    | [9ed530100f](https://linux-hardware.org/?probe=9ed530100f) | Apr 13, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [95ddaa1dae](https://linux-hardware.org/?probe=95ddaa1dae) | Apr 13, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ba6f51707b](https://linux-hardware.org/?probe=ba6f51707b) | Apr 13, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [a06e300bfd](https://linux-hardware.org/?probe=a06e300bfd) | Apr 12, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [ffb5635168](https://linux-hardware.org/?probe=ffb5635168) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [59b9f6ab96](https://linux-hardware.org/?probe=59b9f6ab96) | Apr 09, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [27e9b2e124](https://linux-hardware.org/?probe=27e9b2e124) | Apr 09, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [5fea9b2c3a](https://linux-hardware.org/?probe=5fea9b2c3a) | Apr 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [d49b3ef408](https://linux-hardware.org/?probe=d49b3ef408) | Apr 08, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [dd2c447b48](https://linux-hardware.org/?probe=dd2c447b48) | Apr 07, 2022 |
| HP            | 0AA8h                       | Desktop     | [0de7915496](https://linux-hardware.org/?probe=0de7915496) | Apr 06, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [9cbf0f3aad](https://linux-hardware.org/?probe=9cbf0f3aad) | Apr 04, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [beeceac759](https://linux-hardware.org/?probe=beeceac759) | Apr 04, 2022 |
| Lenovo        | B590 37612LG                | Notebook    | [153a6c2343](https://linux-hardware.org/?probe=153a6c2343) | Apr 04, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| HP            | 1790                        | Desktop     | [9b8f0779ab](https://linux-hardware.org/?probe=9b8f0779ab) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [13aa7656f3](https://linux-hardware.org/?probe=13aa7656f3) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [62982f1e80](https://linux-hardware.org/?probe=62982f1e80) | Apr 02, 2022 |
| Medion        | H81H3-EM2                   | Desktop     | [4c887e357d](https://linux-hardware.org/?probe=4c887e357d) | Mar 31, 2022 |
| HP            | 250 G4                      | Notebook    | [69a3535c1a](https://linux-hardware.org/?probe=69a3535c1a) | Mar 30, 2022 |
| Acer          | Aspire 5920G                | Notebook    | [c2d3fbb93e](https://linux-hardware.org/?probe=c2d3fbb93e) | Mar 30, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [ffde31bd20](https://linux-hardware.org/?probe=ffde31bd20) | Mar 26, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c1e113a82d](https://linux-hardware.org/?probe=c1e113a82d) | Mar 26, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a05a647662](https://linux-hardware.org/?probe=a05a647662) | Mar 25, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [2bbea411a6](https://linux-hardware.org/?probe=2bbea411a6) | Mar 24, 2022 |
| Dell          | 0C522T A03                  | Desktop     | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [c55e29b1e9](https://linux-hardware.org/?probe=c55e29b1e9) | Mar 22, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [ce6cc28ca1](https://linux-hardware.org/?probe=ce6cc28ca1) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8d1c371df2](https://linux-hardware.org/?probe=8d1c371df2) | Mar 21, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [35da4bbe2c](https://linux-hardware.org/?probe=35da4bbe2c) | Mar 21, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [626ee37f9b](https://linux-hardware.org/?probe=626ee37f9b) | Mar 21, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [a93c59159d](https://linux-hardware.org/?probe=a93c59159d) | Mar 20, 2022 |
| Acer          | Swift SF514-55GT            | Notebook    | [ae09c5da41](https://linux-hardware.org/?probe=ae09c5da41) | Mar 20, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [7e8098be12](https://linux-hardware.org/?probe=7e8098be12) | Mar 20, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b8b480e048](https://linux-hardware.org/?probe=b8b480e048) | Mar 20, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [a3a8154156](https://linux-hardware.org/?probe=a3a8154156) | Mar 17, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [177d9b8820](https://linux-hardware.org/?probe=177d9b8820) | Mar 16, 2022 |
| Dell          | 05R2TK A01                  | All in one  | [d678cbb1cc](https://linux-hardware.org/?probe=d678cbb1cc) | Mar 15, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [5da90f10f4](https://linux-hardware.org/?probe=5da90f10f4) | Mar 15, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [4bc060dc9d](https://linux-hardware.org/?probe=4bc060dc9d) | Mar 14, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [28303b98cc](https://linux-hardware.org/?probe=28303b98cc) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a339fe7a39](https://linux-hardware.org/?probe=a339fe7a39) | Mar 13, 2022 |
| Intel         | DG31PR AAD97573-300         | Desktop     | [509c41b106](https://linux-hardware.org/?probe=509c41b106) | Mar 13, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [c82a0d33a2](https://linux-hardware.org/?probe=c82a0d33a2) | Mar 12, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [e8c3922bb3](https://linux-hardware.org/?probe=e8c3922bb3) | Mar 12, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [6034a2269a](https://linux-hardware.org/?probe=6034a2269a) | Mar 09, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [385d1914ee](https://linux-hardware.org/?probe=385d1914ee) | Mar 07, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [ad5413d163](https://linux-hardware.org/?probe=ad5413d163) | Mar 06, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [3b3220eeee](https://linux-hardware.org/?probe=3b3220eeee) | Mar 06, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [b1ac4ae8e7](https://linux-hardware.org/?probe=b1ac4ae8e7) | Mar 05, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f89153c3e1](https://linux-hardware.org/?probe=f89153c3e1) | Mar 05, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [6d26072b9e](https://linux-hardware.org/?probe=6d26072b9e) | Mar 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [53d74176e9](https://linux-hardware.org/?probe=53d74176e9) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [73881ad12e](https://linux-hardware.org/?probe=73881ad12e) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Dell          | 0XHGV1 A02                  | Desktop     | [768657efd5](https://linux-hardware.org/?probe=768657efd5) | Mar 03, 2022 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [6090fb66ea](https://linux-hardware.org/?probe=6090fb66ea) | Mar 02, 2022 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [c56a98389f](https://linux-hardware.org/?probe=c56a98389f) | Mar 01, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| Medion        | E16402                      | Notebook    | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c57b3c9081](https://linux-hardware.org/?probe=c57b3c9081) | Feb 26, 2022 |
| Lenovo        | ThinkPad 10 20C3S0P900      | Tablet      | [a7034fd62e](https://linux-hardware.org/?probe=a7034fd62e) | Feb 26, 2022 |
| Lenovo        | ThinkPad 10 20C3S0P900      | Tablet      | [61c4a46887](https://linux-hardware.org/?probe=61c4a46887) | Feb 26, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [c8dd47fb82](https://linux-hardware.org/?probe=c8dd47fb82) | Feb 26, 2022 |
| Lenovo        | IdeaPadFlex 5 15ALC05 82... | Convertible | [800ecfe818](https://linux-hardware.org/?probe=800ecfe818) | Feb 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [402a27e190](https://linux-hardware.org/?probe=402a27e190) | Feb 24, 2022 |
| ASUSTek       | X55U                        | Notebook    | [c7c38f077d](https://linux-hardware.org/?probe=c7c38f077d) | Feb 24, 2022 |
| HP            | 84DE                        | All in one  | [43184fd6bf](https://linux-hardware.org/?probe=43184fd6bf) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6083eed5da](https://linux-hardware.org/?probe=6083eed5da) | Feb 21, 2022 |
| Lenovo        | ThinkPad T430 2349U15       | Notebook    | [38a194c33d](https://linux-hardware.org/?probe=38a194c33d) | Feb 20, 2022 |
| MSI           | MS-7392                     | Desktop     | [c64a5b4adf](https://linux-hardware.org/?probe=c64a5b4adf) | Feb 20, 2022 |
| MSI           | MS-7392                     | Desktop     | [308ed6c0c6](https://linux-hardware.org/?probe=308ed6c0c6) | Feb 20, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [417a759484](https://linux-hardware.org/?probe=417a759484) | Feb 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [dfc7dad0ee](https://linux-hardware.org/?probe=dfc7dad0ee) | Feb 17, 2022 |
| Lenovo        | ThinkPad P50 20ENS0FQ00     | Notebook    | [8d8e30fdfb](https://linux-hardware.org/?probe=8d8e30fdfb) | Feb 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [5d2de5cd73](https://linux-hardware.org/?probe=5d2de5cd73) | Feb 17, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [be010e2d04](https://linux-hardware.org/?probe=be010e2d04) | Feb 17, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [fec0662c03](https://linux-hardware.org/?probe=fec0662c03) | Feb 16, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [f6383e06d7](https://linux-hardware.org/?probe=f6383e06d7) | Feb 16, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [13989d56ec](https://linux-hardware.org/?probe=13989d56ec) | Feb 14, 2022 |
| MSI           | EX620                       | Notebook    | [8eda01e2a8](https://linux-hardware.org/?probe=8eda01e2a8) | Feb 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e48e07387e](https://linux-hardware.org/?probe=e48e07387e) | Feb 13, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [be994742e1](https://linux-hardware.org/?probe=be994742e1) | Feb 13, 2022 |
| HP            | 09F8h                       | Desktop     | [d887fef9ff](https://linux-hardware.org/?probe=d887fef9ff) | Feb 13, 2022 |
| HP            | EliteBook 8530p             | Notebook    | [6b45115b9e](https://linux-hardware.org/?probe=6b45115b9e) | Feb 13, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [eeeac91ae4](https://linux-hardware.org/?probe=eeeac91ae4) | Feb 13, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [a016adec7d](https://linux-hardware.org/?probe=a016adec7d) | Feb 12, 2022 |
| HP            | 339A                        | Desktop     | [a4eac4d7b8](https://linux-hardware.org/?probe=a4eac4d7b8) | Feb 11, 2022 |
| Lenovo        | NOK                         | Desktop     | [f860aaeaf3](https://linux-hardware.org/?probe=f860aaeaf3) | Feb 11, 2022 |
| HP            | 0AA8h                       | Desktop     | [a78b5c3460](https://linux-hardware.org/?probe=a78b5c3460) | Feb 10, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [5e071a1807](https://linux-hardware.org/?probe=5e071a1807) | Feb 09, 2022 |
| Lenovo        | ThinkPad T410 2522Y15       | Notebook    | [66a496ba4c](https://linux-hardware.org/?probe=66a496ba4c) | Feb 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7d600bcdc7](https://linux-hardware.org/?probe=7d600bcdc7) | Feb 08, 2022 |
| Lenovo        | ThinkPad L380 20M5003FUK    | Notebook    | [fe486b4de6](https://linux-hardware.org/?probe=fe486b4de6) | Feb 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS3W300    | Notebook    | [a49c14ab70](https://linux-hardware.org/?probe=a49c14ab70) | Feb 06, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [275d33a826](https://linux-hardware.org/?probe=275d33a826) | Feb 06, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [23b715cc77](https://linux-hardware.org/?probe=23b715cc77) | Feb 05, 2022 |
| Allview       | Allbook H                   | Notebook    | [f1ba3f22c4](https://linux-hardware.org/?probe=f1ba3f22c4) | Feb 05, 2022 |
| Gigabyte      | P35-DS3R                    | Desktop     | [3164a5ed5b](https://linux-hardware.org/?probe=3164a5ed5b) | Feb 05, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [4975c3b6b7](https://linux-hardware.org/?probe=4975c3b6b7) | Feb 05, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [5eaea69c49](https://linux-hardware.org/?probe=5eaea69c49) | Feb 04, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [d554447e6b](https://linux-hardware.org/?probe=d554447e6b) | Feb 04, 2022 |
| HP            | Pavilion dv6                | Notebook    | [63c8ab5447](https://linux-hardware.org/?probe=63c8ab5447) | Feb 03, 2022 |
| HP            | EliteBook x360 1040 G5      | Notebook    | [4aa3aa1f30](https://linux-hardware.org/?probe=4aa3aa1f30) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [1e330f1e0e](https://linux-hardware.org/?probe=1e330f1e0e) | Feb 02, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [5d9bab6a00](https://linux-hardware.org/?probe=5d9bab6a00) | Feb 02, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [94fefac9e1](https://linux-hardware.org/?probe=94fefac9e1) | Feb 01, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [b80429c5fe](https://linux-hardware.org/?probe=b80429c5fe) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [7c2762f41c](https://linux-hardware.org/?probe=7c2762f41c) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [2aa45a8d1b](https://linux-hardware.org/?probe=2aa45a8d1b) | Jan 31, 2022 |
| Acer          | RS880M05                    | Desktop     | [43b14c0f42](https://linux-hardware.org/?probe=43b14c0f42) | Jan 31, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [b61bba90ad](https://linux-hardware.org/?probe=b61bba90ad) | Jan 30, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Acer          | Extensa 2510                | Notebook    | [1fcabc0254](https://linux-hardware.org/?probe=1fcabc0254) | Jan 26, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [3bcb1d5f53](https://linux-hardware.org/?probe=3bcb1d5f53) | Jan 25, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [6d62bb9596](https://linux-hardware.org/?probe=6d62bb9596) | Jan 24, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [0e47f03d64](https://linux-hardware.org/?probe=0e47f03d64) | Jan 24, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [ded9015aff](https://linux-hardware.org/?probe=ded9015aff) | Jan 23, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [6ab6d3c8b2](https://linux-hardware.org/?probe=6ab6d3c8b2) | Jan 23, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [d90de3e8f7](https://linux-hardware.org/?probe=d90de3e8f7) | Jan 21, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [3609f04919](https://linux-hardware.org/?probe=3609f04919) | Jan 19, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [8e66dbbe5c](https://linux-hardware.org/?probe=8e66dbbe5c) | Jan 19, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [d4187f35fd](https://linux-hardware.org/?probe=d4187f35fd) | Jan 19, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [2f55e0a142](https://linux-hardware.org/?probe=2f55e0a142) | Jan 19, 2022 |
| Dell          | MXG071                      | Notebook    | [cd914ee2f0](https://linux-hardware.org/?probe=cd914ee2f0) | Jan 18, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [e4489c39b8](https://linux-hardware.org/?probe=e4489c39b8) | Jan 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [4b51693e30](https://linux-hardware.org/?probe=4b51693e30) | Jan 17, 2022 |
| Lenovo        | ThinkPad X61s 7666WCQ       | Notebook    | [7e1d764ca8](https://linux-hardware.org/?probe=7e1d764ca8) | Jan 16, 2022 |
| Samsung       | R580/R590                   | Notebook    | [be1e77de84](https://linux-hardware.org/?probe=be1e77de84) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [342f6f2beb](https://linux-hardware.org/?probe=342f6f2beb) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [34f103b8d2](https://linux-hardware.org/?probe=34f103b8d2) | Jan 16, 2022 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [12db3650f6](https://linux-hardware.org/?probe=12db3650f6) | Jan 14, 2022 |
| MSI           | 2A9C                        | Desktop     | [09004ce71d](https://linux-hardware.org/?probe=09004ce71d) | Jan 14, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [efe75d8f3f](https://linux-hardware.org/?probe=efe75d8f3f) | Jan 14, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [6976b6ebbd](https://linux-hardware.org/?probe=6976b6ebbd) | Jan 14, 2022 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [15dd95fdfd](https://linux-hardware.org/?probe=15dd95fdfd) | Jan 14, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [615ed31a98](https://linux-hardware.org/?probe=615ed31a98) | Jan 13, 2022 |
| Acer          | Aspire T3-710 V:1.1         | Desktop     | [088a0a9608](https://linux-hardware.org/?probe=088a0a9608) | Jan 12, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [5f41c8e050](https://linux-hardware.org/?probe=5f41c8e050) | Jan 12, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [7ace73b9e5](https://linux-hardware.org/?probe=7ace73b9e5) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [56d6ea164b](https://linux-hardware.org/?probe=56d6ea164b) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d9bd1bab23](https://linux-hardware.org/?probe=d9bd1bab23) | Jan 09, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [353534e82a](https://linux-hardware.org/?probe=353534e82a) | Jan 08, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [ba78c8aef3](https://linux-hardware.org/?probe=ba78c8aef3) | Jan 07, 2022 |
| HP            | 843B                        | Desktop     | [24e5dae02e](https://linux-hardware.org/?probe=24e5dae02e) | Jan 07, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [1630e680bc](https://linux-hardware.org/?probe=1630e680bc) | Jan 06, 2022 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [3e7d72e09a](https://linux-hardware.org/?probe=3e7d72e09a) | Jan 06, 2022 |
| Chuwi         | Hero Book                   | Notebook    | [b111f44fad](https://linux-hardware.org/?probe=b111f44fad) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Dell          | Inspiron 7586               | Convertible | [9a480f9de9](https://linux-hardware.org/?probe=9a480f9de9) | Jan 04, 2022 |
| ASUSTek       | X550VL                      | Notebook    | [46ed51f6ef](https://linux-hardware.org/?probe=46ed51f6ef) | Jan 04, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [0132076c85](https://linux-hardware.org/?probe=0132076c85) | Jan 04, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| Lenovo        | ThinkPad X220 4291B78       | Notebook    | [76350af57f](https://linux-hardware.org/?probe=76350af57f) | Jan 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a7217db810](https://linux-hardware.org/?probe=a7217db810) | Jan 02, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [286ce69daf](https://linux-hardware.org/?probe=286ce69daf) | Jan 02, 2022 |
| HP            | 1497                        | Desktop     | [540458f943](https://linux-hardware.org/?probe=540458f943) | Jan 02, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [f5eafcc9e4](https://linux-hardware.org/?probe=f5eafcc9e4) | Jan 02, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [50a5dc78eb](https://linux-hardware.org/?probe=50a5dc78eb) | Jan 02, 2022 |
| MSI           | EX705                       | Notebook    | [a969bd4369](https://linux-hardware.org/?probe=a969bd4369) | Dec 31, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [64743b9e56](https://linux-hardware.org/?probe=64743b9e56) | Dec 30, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [a8b3cc88b1](https://linux-hardware.org/?probe=a8b3cc88b1) | Dec 29, 2021 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [af923f06cc](https://linux-hardware.org/?probe=af923f06cc) | Dec 29, 2021 |
| Dell          | Latitude E5420m             | Notebook    | [6f5af5da5c](https://linux-hardware.org/?probe=6f5af5da5c) | Dec 29, 2021 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [a7a37c26c7](https://linux-hardware.org/?probe=a7a37c26c7) | Dec 29, 2021 |
| Dream Mach... | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [c3f88b03df](https://linux-hardware.org/?probe=c3f88b03df) | Dec 28, 2021 |
| Lenovo        | ThinkStation E20 4220RF8    | Desktop     | [e525340bef](https://linux-hardware.org/?probe=e525340bef) | Dec 28, 2021 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [82a0c6cd43](https://linux-hardware.org/?probe=82a0c6cd43) | Dec 28, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b2b9ea9e60](https://linux-hardware.org/?probe=b2b9ea9e60) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 4291B78       | Notebook    | [2c8a912b3e](https://linux-hardware.org/?probe=2c8a912b3e) | Dec 24, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [e4dc4b8711](https://linux-hardware.org/?probe=e4dc4b8711) | Dec 23, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [d6d85114b6](https://linux-hardware.org/?probe=d6d85114b6) | Dec 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1f334f4c1c](https://linux-hardware.org/?probe=1f334f4c1c) | Dec 22, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [85da21d9e9](https://linux-hardware.org/?probe=85da21d9e9) | Dec 22, 2021 |
| HP            | 18E7                        | Desktop     | [b233eb9f3e](https://linux-hardware.org/?probe=b233eb9f3e) | Dec 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [6748ebc68a](https://linux-hardware.org/?probe=6748ebc68a) | Dec 20, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [0a48d9579b](https://linux-hardware.org/?probe=0a48d9579b) | Dec 19, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [00868d9166](https://linux-hardware.org/?probe=00868d9166) | Dec 17, 2021 |
| HP            | 1998                        | Desktop     | [9bfa0ed638](https://linux-hardware.org/?probe=9bfa0ed638) | Dec 17, 2021 |
| Timi          | TM1701                      | Notebook    | [f063712cce](https://linux-hardware.org/?probe=f063712cce) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [ac40d89d27](https://linux-hardware.org/?probe=ac40d89d27) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [7da5a1020d](https://linux-hardware.org/?probe=7da5a1020d) | Dec 15, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [5915e986de](https://linux-hardware.org/?probe=5915e986de) | Dec 15, 2021 |
| Chuwi         | Hero Book                   | Notebook    | [27e37e5a15](https://linux-hardware.org/?probe=27e37e5a15) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2acaeac0de](https://linux-hardware.org/?probe=2acaeac0de) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2c39bc3721](https://linux-hardware.org/?probe=2c39bc3721) | Dec 14, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [45a5dc5b06](https://linux-hardware.org/?probe=45a5dc5b06) | Dec 13, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [85770fb8f5](https://linux-hardware.org/?probe=85770fb8f5) | Dec 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | Notebook    | [b68de5799e](https://linux-hardware.org/?probe=b68de5799e) | Dec 12, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [5d06e53d08](https://linux-hardware.org/?probe=5d06e53d08) | Dec 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ed065155fb](https://linux-hardware.org/?probe=ed065155fb) | Dec 11, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [7fe98389c6](https://linux-hardware.org/?probe=7fe98389c6) | Dec 11, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [5be7aac3a2](https://linux-hardware.org/?probe=5be7aac3a2) | Dec 09, 2021 |
| ASUSTek       | V241FA                      | All in one  | [60c6c7ea7c](https://linux-hardware.org/?probe=60c6c7ea7c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [98f25277f5](https://linux-hardware.org/?probe=98f25277f5) | Dec 08, 2021 |
| ASRockRack    | E3C232D4U-V1L               | Desktop     | [139a75e689](https://linux-hardware.org/?probe=139a75e689) | Dec 07, 2021 |
| Dell          | Inspiron 7586               | Convertible | [53604c12d1](https://linux-hardware.org/?probe=53604c12d1) | Dec 05, 2021 |
| INET          | Z12B                        | Mini pc     | [95470b9d91](https://linux-hardware.org/?probe=95470b9d91) | Dec 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [1c6db4a61b](https://linux-hardware.org/?probe=1c6db4a61b) | Dec 03, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [902395fcce](https://linux-hardware.org/?probe=902395fcce) | Dec 03, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [ad91050095](https://linux-hardware.org/?probe=ad91050095) | Dec 03, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [b42c2359f4](https://linux-hardware.org/?probe=b42c2359f4) | Dec 03, 2021 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [56bd9b515c](https://linux-hardware.org/?probe=56bd9b515c) | Dec 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [e73cda5c1e](https://linux-hardware.org/?probe=e73cda5c1e) | Dec 02, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [d3040ac7d5](https://linux-hardware.org/?probe=d3040ac7d5) | Nov 30, 2021 |
| Allview       | Allbook J                   | Notebook    | [957074dbe3](https://linux-hardware.org/?probe=957074dbe3) | Nov 30, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [317b686b33](https://linux-hardware.org/?probe=317b686b33) | Nov 29, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [c323b490bf](https://linux-hardware.org/?probe=c323b490bf) | Nov 26, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [89729fef47](https://linux-hardware.org/?probe=89729fef47) | Nov 25, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [755b7b85f5](https://linux-hardware.org/?probe=755b7b85f5) | Nov 24, 2021 |
| Medion        | E7218                       | Notebook    | [e4a790a38d](https://linux-hardware.org/?probe=e4a790a38d) | Nov 23, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [dab6e17223](https://linux-hardware.org/?probe=dab6e17223) | Nov 23, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [dba80843bc](https://linux-hardware.org/?probe=dba80843bc) | Nov 23, 2021 |
| HP            | Compaq 2510p                | Notebook    | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [eb7191f8cb](https://linux-hardware.org/?probe=eb7191f8cb) | Nov 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [1169bef865](https://linux-hardware.org/?probe=1169bef865) | Nov 22, 2021 |
| HP            | Compaq 2510p                | Notebook    | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bb48a45349](https://linux-hardware.org/?probe=bb48a45349) | Nov 22, 2021 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [898f3db0ed](https://linux-hardware.org/?probe=898f3db0ed) | Nov 22, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [9a83e53e34](https://linux-hardware.org/?probe=9a83e53e34) | Nov 22, 2021 |
| ASUSTek       | X450CP                      | Notebook    | [7228a5157c](https://linux-hardware.org/?probe=7228a5157c) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [04fa536869](https://linux-hardware.org/?probe=04fa536869) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [097de81570](https://linux-hardware.org/?probe=097de81570) | Nov 20, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [4a77a751d9](https://linux-hardware.org/?probe=4a77a751d9) | Nov 20, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [00f5cc73fe](https://linux-hardware.org/?probe=00f5cc73fe) | Nov 19, 2021 |
| Dell          | Latitude 7410               | Notebook    | [226f912726](https://linux-hardware.org/?probe=226f912726) | Nov 18, 2021 |
| ASUSTek       | K53U                        | Notebook    | [8b542e61d9](https://linux-hardware.org/?probe=8b542e61d9) | Nov 18, 2021 |
| Dell          | Latitude E7470              | Notebook    | [0358863974](https://linux-hardware.org/?probe=0358863974) | Nov 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2e7ed34d33](https://linux-hardware.org/?probe=2e7ed34d33) | Nov 16, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [6677eae4da](https://linux-hardware.org/?probe=6677eae4da) | Nov 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [48f29ffe3a](https://linux-hardware.org/?probe=48f29ffe3a) | Nov 14, 2021 |
| ASUSTek       | X540SA                      | Notebook    | [1292ab6f15](https://linux-hardware.org/?probe=1292ab6f15) | Nov 14, 2021 |
| Dell          | Latitude E6410              | Notebook    | [1a31fa8433](https://linux-hardware.org/?probe=1a31fa8433) | Nov 13, 2021 |
| ASUSTek       | X540SA                      | Notebook    | [463e1f35a9](https://linux-hardware.org/?probe=463e1f35a9) | Nov 13, 2021 |
| Sony          | SVF14N1E2ES                 | Notebook    | [a04441e5cd](https://linux-hardware.org/?probe=a04441e5cd) | Nov 13, 2021 |
| Dell          | Precision 3541              | Notebook    | [8f6085ab9d](https://linux-hardware.org/?probe=8f6085ab9d) | Nov 12, 2021 |
| Packard Be... | EasyNote TN36               | Notebook    | [17ebc64721](https://linux-hardware.org/?probe=17ebc64721) | Nov 11, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [e70882b3fd](https://linux-hardware.org/?probe=e70882b3fd) | Nov 11, 2021 |
| Notebook      | N85_N87HCHNHZ               | Notebook    | [32988fae95](https://linux-hardware.org/?probe=32988fae95) | Nov 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [b79aef683b](https://linux-hardware.org/?probe=b79aef683b) | Nov 11, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [c32869e5a8](https://linux-hardware.org/?probe=c32869e5a8) | Nov 08, 2021 |
| ASUSTek       | A58M-K                      | Desktop     | [0dbc01db57](https://linux-hardware.org/?probe=0dbc01db57) | Nov 08, 2021 |
| Gigabyte      | P31-DS3L                    | Desktop     | [c0ef5646a8](https://linux-hardware.org/?probe=c0ef5646a8) | Nov 07, 2021 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [6dd5b7f191](https://linux-hardware.org/?probe=6dd5b7f191) | Nov 06, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [c1bd9abdd2](https://linux-hardware.org/?probe=c1bd9abdd2) | Nov 03, 2021 |
| HP            | 18E4                        | Desktop     | [1c3ea795a0](https://linux-hardware.org/?probe=1c3ea795a0) | Nov 03, 2021 |
| HP            | 18E4                        | Desktop     | [4994f5c700](https://linux-hardware.org/?probe=4994f5c700) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [0243b19a08](https://linux-hardware.org/?probe=0243b19a08) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [f7d58b572d](https://linux-hardware.org/?probe=f7d58b572d) | Nov 03, 2021 |
| Dell          | G3 3579                     | Notebook    | [f9fdeb003b](https://linux-hardware.org/?probe=f9fdeb003b) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [8cdb34dbc8](https://linux-hardware.org/?probe=8cdb34dbc8) | Nov 01, 2021 |
| Lenovo        | ThinkPad T430 2349U15       | Notebook    | [c9d8efc9b9](https://linux-hardware.org/?probe=c9d8efc9b9) | Oct 31, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [f31e6e3dd0](https://linux-hardware.org/?probe=f31e6e3dd0) | Oct 29, 2021 |
| ASUSTek       | V241EA                      | All in one  | [243713e97a](https://linux-hardware.org/?probe=243713e97a) | Oct 28, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| Dell          | 07T4MC A11                  | Desktop     | [219a3a234f](https://linux-hardware.org/?probe=219a3a234f) | Oct 27, 2021 |
| Dell          | 07T4MC A11                  | Desktop     | [870145802c](https://linux-hardware.org/?probe=870145802c) | Oct 27, 2021 |
| Dell          | Latitude E5450              | Notebook    | [fb61a77e5c](https://linux-hardware.org/?probe=fb61a77e5c) | Oct 26, 2021 |
| IBM           | 82121QG                     | Desktop     | [765d524e7f](https://linux-hardware.org/?probe=765d524e7f) | Oct 26, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [109cb750a6](https://linux-hardware.org/?probe=109cb750a6) | Oct 25, 2021 |
| Lenovo        | ThinkPad X230 2325SWF       | Notebook    | [64f9882936](https://linux-hardware.org/?probe=64f9882936) | Oct 25, 2021 |
| Apple         | MacBookPro14,3              | Notebook    | [69a5d79a58](https://linux-hardware.org/?probe=69a5d79a58) | Oct 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [9b3e361eb7](https://linux-hardware.org/?probe=9b3e361eb7) | Oct 24, 2021 |
| Dell          | Latitude E7470              | Notebook    | [69a251cc1f](https://linux-hardware.org/?probe=69a251cc1f) | Oct 22, 2021 |
| Dell          | Latitude E7470              | Notebook    | [96ef0ee68c](https://linux-hardware.org/?probe=96ef0ee68c) | Oct 22, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [21379aad70](https://linux-hardware.org/?probe=21379aad70) | Oct 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f0c049fc34](https://linux-hardware.org/?probe=f0c049fc34) | Oct 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d550d04ac7](https://linux-hardware.org/?probe=d550d04ac7) | Oct 20, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [8563f3786e](https://linux-hardware.org/?probe=8563f3786e) | Oct 19, 2021 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [ac37b3fd23](https://linux-hardware.org/?probe=ac37b3fd23) | Oct 18, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [cbf3c67be2](https://linux-hardware.org/?probe=cbf3c67be2) | Oct 18, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [cc0290a8df](https://linux-hardware.org/?probe=cc0290a8df) | Oct 18, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [0b2123c367](https://linux-hardware.org/?probe=0b2123c367) | Oct 16, 2021 |
| Dell          | Latitude E7470              | Notebook    | [3bbcb85b9f](https://linux-hardware.org/?probe=3bbcb85b9f) | Oct 16, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [28930b356e](https://linux-hardware.org/?probe=28930b356e) | Oct 16, 2021 |
| ASRock        | A75 Extreme6                | Desktop     | [5735bac676](https://linux-hardware.org/?probe=5735bac676) | Oct 16, 2021 |
| ASRock        | 4X4-4000 Series             | Desktop     | [fd95402aa1](https://linux-hardware.org/?probe=fd95402aa1) | Oct 14, 2021 |
| ASRock        | 4X4-4000 Series             | Desktop     | [538c0f7723](https://linux-hardware.org/?probe=538c0f7723) | Oct 14, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [b59de957b3](https://linux-hardware.org/?probe=b59de957b3) | Oct 11, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [a427a26f34](https://linux-hardware.org/?probe=a427a26f34) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1965a71536](https://linux-hardware.org/?probe=1965a71536) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6166a72ec2](https://linux-hardware.org/?probe=6166a72ec2) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [0acb396573](https://linux-hardware.org/?probe=0acb396573) | Oct 11, 2021 |
| Acer          | Aspire 5741G                | Notebook    | [ea162f9171](https://linux-hardware.org/?probe=ea162f9171) | Oct 10, 2021 |
| HP            | 3031h                       | Desktop     | [eb48a6bfe5](https://linux-hardware.org/?probe=eb48a6bfe5) | Oct 10, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [d79188a009](https://linux-hardware.org/?probe=d79188a009) | Oct 10, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [aae51881da](https://linux-hardware.org/?probe=aae51881da) | Oct 10, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [efb88027ec](https://linux-hardware.org/?probe=efb88027ec) | Oct 09, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [ec7609239e](https://linux-hardware.org/?probe=ec7609239e) | Oct 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [1f29f9efba](https://linux-hardware.org/?probe=1f29f9efba) | Oct 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [2236b91c55](https://linux-hardware.org/?probe=2236b91c55) | Oct 05, 2021 |
| HP            | EliteBook 8770w             | Notebook    | [d23574ecf1](https://linux-hardware.org/?probe=d23574ecf1) | Oct 04, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [97333f9cab](https://linux-hardware.org/?probe=97333f9cab) | Oct 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [2f89b6fcf1](https://linux-hardware.org/?probe=2f89b6fcf1) | Oct 03, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [06d254591f](https://linux-hardware.org/?probe=06d254591f) | Oct 02, 2021 |
| Lenovo        | ThinkPad T470 20HES0FA02    | Notebook    | [b368193a4e](https://linux-hardware.org/?probe=b368193a4e) | Oct 02, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3f4fe97a8a](https://linux-hardware.org/?probe=3f4fe97a8a) | Sep 30, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [02d6cacb04](https://linux-hardware.org/?probe=02d6cacb04) | Sep 30, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [699985f9e6](https://linux-hardware.org/?probe=699985f9e6) | Sep 28, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [d82bdfcf17](https://linux-hardware.org/?probe=d82bdfcf17) | Sep 28, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [032d34e75b](https://linux-hardware.org/?probe=032d34e75b) | Sep 28, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [68a76785a0](https://linux-hardware.org/?probe=68a76785a0) | Sep 27, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [3cbca1757f](https://linux-hardware.org/?probe=3cbca1757f) | Sep 26, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [7baf276ca0](https://linux-hardware.org/?probe=7baf276ca0) | Sep 26, 2021 |
| Alienware     | 17 R2                       | Notebook    | [cbe7430492](https://linux-hardware.org/?probe=cbe7430492) | Sep 26, 2021 |
| ASUSTek       | FX503VD                     | Notebook    | [c91cad59c2](https://linux-hardware.org/?probe=c91cad59c2) | Sep 25, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [a44995aac4](https://linux-hardware.org/?probe=a44995aac4) | Sep 25, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a97e17fc48](https://linux-hardware.org/?probe=a97e17fc48) | Sep 25, 2021 |
| HP            | EliteBook 8530p             | Notebook    | [8002401481](https://linux-hardware.org/?probe=8002401481) | Sep 23, 2021 |
| Dell          | 0GM819                      | Desktop     | [708ca8f58a](https://linux-hardware.org/?probe=708ca8f58a) | Sep 22, 2021 |
| Dell          | 0GM819                      | Desktop     | [37f5afac35](https://linux-hardware.org/?probe=37f5afac35) | Sep 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [72f179ec58](https://linux-hardware.org/?probe=72f179ec58) | Sep 22, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | Notebook    | [f6dfc42935](https://linux-hardware.org/?probe=f6dfc42935) | Sep 22, 2021 |
| MSI           | A55M-E33                    | Desktop     | [695bc5477d](https://linux-hardware.org/?probe=695bc5477d) | Sep 22, 2021 |
| ASUSTek       | UX550VE                     | Notebook    | [72925fef5d](https://linux-hardware.org/?probe=72925fef5d) | Sep 21, 2021 |
| ASUSTek       | GL752VW                     | Notebook    | [ec4b89fd42](https://linux-hardware.org/?probe=ec4b89fd42) | Sep 20, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [75c71d1f1e](https://linux-hardware.org/?probe=75c71d1f1e) | Sep 20, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [7b95b06b4d](https://linux-hardware.org/?probe=7b95b06b4d) | Sep 20, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [3a0a2208fb](https://linux-hardware.org/?probe=3a0a2208fb) | Sep 20, 2021 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [c7e3f44f44](https://linux-hardware.org/?probe=c7e3f44f44) | Sep 19, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [c0b5da7979](https://linux-hardware.org/?probe=c0b5da7979) | Sep 19, 2021 |
| Acer          | AOA110                      | Notebook    | [a54c248743](https://linux-hardware.org/?probe=a54c248743) | Sep 19, 2021 |
| HP            | Pavilion dv6                | Notebook    | [b4d25f6f3a](https://linux-hardware.org/?probe=b4d25f6f3a) | Sep 19, 2021 |
| Sony          | VGN-CR21Z_N                 | Notebook    | [6fc19f4c67](https://linux-hardware.org/?probe=6fc19f4c67) | Sep 19, 2021 |
| HP            | 3397                        | Desktop     | [13d358c48e](https://linux-hardware.org/?probe=13d358c48e) | Sep 18, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [252914c6d3](https://linux-hardware.org/?probe=252914c6d3) | Sep 16, 2021 |
| Supermicro    | X11SSL-CF                   | Server      | [50169a0ffb](https://linux-hardware.org/?probe=50169a0ffb) | Sep 15, 2021 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | Desktop     | [d47952ec42](https://linux-hardware.org/?probe=d47952ec42) | Sep 15, 2021 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | Desktop     | [9c310e15bd](https://linux-hardware.org/?probe=9c310e15bd) | Sep 15, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [1493a2eae1](https://linux-hardware.org/?probe=1493a2eae1) | Sep 15, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| Toshiba       | Satellite C55-C             | Notebook    | [8966b3a7b5](https://linux-hardware.org/?probe=8966b3a7b5) | Sep 14, 2021 |
| HP            | EliteBook 840 G4            | Notebook    | [8bd6acee77](https://linux-hardware.org/?probe=8bd6acee77) | Sep 13, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [da1dd9bb01](https://linux-hardware.org/?probe=da1dd9bb01) | Sep 13, 2021 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [bc6963f758](https://linux-hardware.org/?probe=bc6963f758) | Sep 11, 2021 |
| Packard Be... | EasyNote MV86               | Notebook    | [ea018cddf2](https://linux-hardware.org/?probe=ea018cddf2) | Sep 10, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [151a3381f0](https://linux-hardware.org/?probe=151a3381f0) | Sep 09, 2021 |
| Dell          | Inspiron 5520               | Notebook    | [835f9cb8a1](https://linux-hardware.org/?probe=835f9cb8a1) | Sep 07, 2021 |
| Dell          | Latitude 7410               | Notebook    | [8f1a1a4798](https://linux-hardware.org/?probe=8f1a1a4798) | Sep 06, 2021 |
| Dell          | Latitude 7410               | Notebook    | [b03a0e0152](https://linux-hardware.org/?probe=b03a0e0152) | Sep 06, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [576b96b6da](https://linux-hardware.org/?probe=576b96b6da) | Sep 06, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [638993c7b0](https://linux-hardware.org/?probe=638993c7b0) | Sep 06, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [bb0ef0735f](https://linux-hardware.org/?probe=bb0ef0735f) | Sep 05, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | Notebook    | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| ASUSTek       | D340MC-C                    | Desktop     | [cf81a7ddc2](https://linux-hardware.org/?probe=cf81a7ddc2) | Sep 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [47c2053681](https://linux-hardware.org/?probe=47c2053681) | Sep 02, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [fdb725803b](https://linux-hardware.org/?probe=fdb725803b) | Sep 01, 2021 |
| HP            | 18E9                        | Desktop     | [22f86af485](https://linux-hardware.org/?probe=22f86af485) | Sep 01, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [4765b87a68](https://linux-hardware.org/?probe=4765b87a68) | Sep 01, 2021 |
| MSI           | A88XM-E35                   | Desktop     | [66070c788f](https://linux-hardware.org/?probe=66070c788f) | Sep 01, 2021 |
| HP            | 3032h                       | Desktop     | [7d94cc3baa](https://linux-hardware.org/?probe=7d94cc3baa) | Sep 01, 2021 |
| ASUSTek       | K52F                        | Notebook    | [743e5c8059](https://linux-hardware.org/?probe=743e5c8059) | Sep 01, 2021 |
| ASUSTek       | K52F                        | Notebook    | [54d5076bc6](https://linux-hardware.org/?probe=54d5076bc6) | Sep 01, 2021 |
| ASUSTek       | UX550VE                     | Notebook    | [cd80e1ebb2](https://linux-hardware.org/?probe=cd80e1ebb2) | Aug 31, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [c2b7f1ee7c](https://linux-hardware.org/?probe=c2b7f1ee7c) | Aug 30, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [301be6f800](https://linux-hardware.org/?probe=301be6f800) | Aug 30, 2021 |
| MSI           | MS-16Y1                     | Notebook    | [a9801b616e](https://linux-hardware.org/?probe=a9801b616e) | Aug 29, 2021 |
| HP            | 18E9                        | Desktop     | [539f181954](https://linux-hardware.org/?probe=539f181954) | Aug 29, 2021 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [0a9f1f10d8](https://linux-hardware.org/?probe=0a9f1f10d8) | Aug 29, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [fd9d91270d](https://linux-hardware.org/?probe=fd9d91270d) | Aug 29, 2021 |
| ASUSTek       | X450CP                      | Notebook    | [d646ffd8db](https://linux-hardware.org/?probe=d646ffd8db) | Aug 29, 2021 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [30d745e8d3](https://linux-hardware.org/?probe=30d745e8d3) | Aug 28, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | Notebook    | [954900ccc6](https://linux-hardware.org/?probe=954900ccc6) | Aug 28, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [03a89677c0](https://linux-hardware.org/?probe=03a89677c0) | Aug 26, 2021 |
| HP            | Presario CQ57               | Notebook    | [4b863ffc87](https://linux-hardware.org/?probe=4b863ffc87) | Aug 25, 2021 |
| HP            | 84DE                        | All in one  | [11f4f1348a](https://linux-hardware.org/?probe=11f4f1348a) | Aug 25, 2021 |
| HP            | 84DE                        | All in one  | [ba6157396c](https://linux-hardware.org/?probe=ba6157396c) | Aug 25, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f534340eab](https://linux-hardware.org/?probe=f534340eab) | Aug 22, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4f6bd2a75e](https://linux-hardware.org/?probe=4f6bd2a75e) | Aug 22, 2021 |
| HP            | Presario CQ57               | Notebook    | [a45389ec74](https://linux-hardware.org/?probe=a45389ec74) | Aug 21, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [eb664f1a19](https://linux-hardware.org/?probe=eb664f1a19) | Aug 20, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [cf9c1726af](https://linux-hardware.org/?probe=cf9c1726af) | Aug 19, 2021 |
| HP            | 1587h                       | Desktop     | [3ddbdb3101](https://linux-hardware.org/?probe=3ddbdb3101) | Aug 19, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [70be38d5e1](https://linux-hardware.org/?probe=70be38d5e1) | Aug 18, 2021 |
| HP            | Pavilion dv6                | Notebook    | [40cd012d76](https://linux-hardware.org/?probe=40cd012d76) | Aug 18, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [8cf3477dd1](https://linux-hardware.org/?probe=8cf3477dd1) | Aug 18, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7465dcb16d](https://linux-hardware.org/?probe=7465dcb16d) | Aug 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [8bf5049adc](https://linux-hardware.org/?probe=8bf5049adc) | Aug 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [92e25a1c2c](https://linux-hardware.org/?probe=92e25a1c2c) | Aug 15, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [4b4a995bad](https://linux-hardware.org/?probe=4b4a995bad) | Aug 15, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [f3506aaa1c](https://linux-hardware.org/?probe=f3506aaa1c) | Aug 14, 2021 |
| HP            | 630                         | Notebook    | [eda8d23dba](https://linux-hardware.org/?probe=eda8d23dba) | Aug 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [c8b1a45676](https://linux-hardware.org/?probe=c8b1a45676) | Aug 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [20a828b938](https://linux-hardware.org/?probe=20a828b938) | Aug 11, 2021 |
| ASUSTek       | X550JX                      | Notebook    | [da2cacc763](https://linux-hardware.org/?probe=da2cacc763) | Aug 11, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [86ab410358](https://linux-hardware.org/?probe=86ab410358) | Aug 10, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [d7ad85015d](https://linux-hardware.org/?probe=d7ad85015d) | Aug 10, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [99763e52f1](https://linux-hardware.org/?probe=99763e52f1) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | Notebook    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| HP            | 2AE2                        | Desktop     | [e8a9a769fe](https://linux-hardware.org/?probe=e8a9a769fe) | Aug 07, 2021 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [1d3167cdf0](https://linux-hardware.org/?probe=1d3167cdf0) | Aug 05, 2021 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [3118d29bf0](https://linux-hardware.org/?probe=3118d29bf0) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [1a6e7a1825](https://linux-hardware.org/?probe=1a6e7a1825) | Aug 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [a7feba2af0](https://linux-hardware.org/?probe=a7feba2af0) | Aug 04, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [a7c1a61e9f](https://linux-hardware.org/?probe=a7c1a61e9f) | Aug 03, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [d58be51f72](https://linux-hardware.org/?probe=d58be51f72) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [64dcd58bc3](https://linux-hardware.org/?probe=64dcd58bc3) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [586add668c](https://linux-hardware.org/?probe=586add668c) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [5096c7cbb6](https://linux-hardware.org/?probe=5096c7cbb6) | Aug 03, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [462a00dded](https://linux-hardware.org/?probe=462a00dded) | Aug 02, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [5f2773a82c](https://linux-hardware.org/?probe=5f2773a82c) | Aug 02, 2021 |
| Gigabyte      | P75-D3                      | Desktop     | [5f0bee42c2](https://linux-hardware.org/?probe=5f0bee42c2) | Aug 01, 2021 |
| HP            | 2AE2                        | Desktop     | [61acec4a9c](https://linux-hardware.org/?probe=61acec4a9c) | Aug 01, 2021 |
| HP            | 2AE2                        | Desktop     | [3de122823e](https://linux-hardware.org/?probe=3de122823e) | Aug 01, 2021 |
| HP            | 15                          | Notebook    | [715128c8f0](https://linux-hardware.org/?probe=715128c8f0) | Jul 31, 2021 |
| Toshiba       | Satellite Z30-B             | Notebook    | [af9632e99f](https://linux-hardware.org/?probe=af9632e99f) | Jul 30, 2021 |
| Lenovo        | ThinkPad T410 2537CJ0       | Notebook    | [3722a27c42](https://linux-hardware.org/?probe=3722a27c42) | Jul 28, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [f448eea5b9](https://linux-hardware.org/?probe=f448eea5b9) | Jul 27, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [a5cc51aec1](https://linux-hardware.org/?probe=a5cc51aec1) | Jul 26, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [9e05add91a](https://linux-hardware.org/?probe=9e05add91a) | Jul 26, 2021 |
| HP            | 1850                        | Desktop     | [76e386707a](https://linux-hardware.org/?probe=76e386707a) | Jul 24, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [7fa1d5f6ab](https://linux-hardware.org/?probe=7fa1d5f6ab) | Jul 24, 2021 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [b0ce1bc8f5](https://linux-hardware.org/?probe=b0ce1bc8f5) | Jul 24, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [11daeb0d8d](https://linux-hardware.org/?probe=11daeb0d8d) | Jul 24, 2021 |
| HP            | 0AA8h                       | Desktop     | [a04f3a673d](https://linux-hardware.org/?probe=a04f3a673d) | Jul 23, 2021 |
| HP            | 0AA8h                       | Desktop     | [b3bbc0186c](https://linux-hardware.org/?probe=b3bbc0186c) | Jul 22, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [9f6c5866ae](https://linux-hardware.org/?probe=9f6c5866ae) | Jul 20, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [74f54d66b2](https://linux-hardware.org/?probe=74f54d66b2) | Jul 20, 2021 |
| Toshiba       | Satellite C660D             | Notebook    | [039468c7c5](https://linux-hardware.org/?probe=039468c7c5) | Jul 18, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [f50ab25a97](https://linux-hardware.org/?probe=f50ab25a97) | Jul 17, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [594955a00b](https://linux-hardware.org/?probe=594955a00b) | Jul 17, 2021 |
| HP            | 3047h                       | Desktop     | [ac149ca840](https://linux-hardware.org/?probe=ac149ca840) | Jul 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e2c9b58e23](https://linux-hardware.org/?probe=e2c9b58e23) | Jul 17, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [14ce128e1a](https://linux-hardware.org/?probe=14ce128e1a) | Jul 16, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f656b6c149](https://linux-hardware.org/?probe=f656b6c149) | Jul 16, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d1105aa53f](https://linux-hardware.org/?probe=d1105aa53f) | Jul 16, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [a2a1798503](https://linux-hardware.org/?probe=a2a1798503) | Jul 15, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [14b9ddda83](https://linux-hardware.org/?probe=14b9ddda83) | Jul 14, 2021 |
| Dell          | 0X9X1W A00                  | Desktop     | [702d489268](https://linux-hardware.org/?probe=702d489268) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [876c8173d3](https://linux-hardware.org/?probe=876c8173d3) | Jul 13, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f9d7bd513c](https://linux-hardware.org/?probe=f9d7bd513c) | Jul 13, 2021 |
| Lenovo        | 3102 NOK                    | Desktop     | [71974ffb04](https://linux-hardware.org/?probe=71974ffb04) | Jul 12, 2021 |
| Biostar       | N61PA-M2S                   | Desktop     | [346b5914bf](https://linux-hardware.org/?probe=346b5914bf) | Jul 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c9c8fdd393](https://linux-hardware.org/?probe=c9c8fdd393) | Jul 11, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [76dc55b00e](https://linux-hardware.org/?probe=76dc55b00e) | Jul 11, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [e6d4cd2e90](https://linux-hardware.org/?probe=e6d4cd2e90) | Jul 10, 2021 |
| Acer          | One S1003                   | Tablet      | [5b88dd3887](https://linux-hardware.org/?probe=5b88dd3887) | Jul 09, 2021 |
| HP            | ProBook 4330s               | Notebook    | [64030992e8](https://linux-hardware.org/?probe=64030992e8) | Jul 08, 2021 |
| Dell          | System XPS L502X            | Notebook    | [c384fff091](https://linux-hardware.org/?probe=c384fff091) | Jul 08, 2021 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [6aa95f6599](https://linux-hardware.org/?probe=6aa95f6599) | Jul 08, 2021 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [2a2e03aaa8](https://linux-hardware.org/?probe=2a2e03aaa8) | Jul 08, 2021 |
| Dell          | 04GJJT A00                  | Desktop     | [257e9719c0](https://linux-hardware.org/?probe=257e9719c0) | Jul 07, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [d09c65051f](https://linux-hardware.org/?probe=d09c65051f) | Jul 06, 2021 |
| Lenovo        | ThinkPad T470p 20J7S1860... | Notebook    | [6b3e194f93](https://linux-hardware.org/?probe=6b3e194f93) | Jul 06, 2021 |
| Allview       | Allbook H                   | Notebook    | [ac0835f4f5](https://linux-hardware.org/?probe=ac0835f4f5) | Jul 06, 2021 |
| HP            | EliteBook 8560w             | Notebook    | [e609104d2c](https://linux-hardware.org/?probe=e609104d2c) | Jul 06, 2021 |
| HP            | EliteBook 8560w             | Notebook    | [f3ac1ba96d](https://linux-hardware.org/?probe=f3ac1ba96d) | Jul 06, 2021 |
| Dell          | 0VD5HY A07                  | Desktop     | [398ee87d95](https://linux-hardware.org/?probe=398ee87d95) | Jul 04, 2021 |
| Dell          | 0VD5HY A07                  | Desktop     | [0fa3ef38f2](https://linux-hardware.org/?probe=0fa3ef38f2) | Jul 04, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [b35369b2b3](https://linux-hardware.org/?probe=b35369b2b3) | Jul 03, 2021 |
| Dell          | XPS L501X                   | Notebook    | [27ed8f445a](https://linux-hardware.org/?probe=27ed8f445a) | Jul 03, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [9b296f3c9c](https://linux-hardware.org/?probe=9b296f3c9c) | Jul 03, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [42fcbcb1e4](https://linux-hardware.org/?probe=42fcbcb1e4) | Jul 02, 2021 |
| HP            | 15                          | Notebook    | [b435e6f220](https://linux-hardware.org/?probe=b435e6f220) | Jul 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [2e13a4aff4](https://linux-hardware.org/?probe=2e13a4aff4) | Jul 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [618b266cc7](https://linux-hardware.org/?probe=618b266cc7) | Jul 02, 2021 |
| Toshiba       | Satellite C660D             | Notebook    | [fdbefe0e71](https://linux-hardware.org/?probe=fdbefe0e71) | Jul 01, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a8f90b8625](https://linux-hardware.org/?probe=a8f90b8625) | Jun 30, 2021 |
| ASUSTek       | X751LJ                      | Notebook    | [8a67af6b70](https://linux-hardware.org/?probe=8a67af6b70) | Jun 30, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [21e0e9dda8](https://linux-hardware.org/?probe=21e0e9dda8) | Jun 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [f31a585b5d](https://linux-hardware.org/?probe=f31a585b5d) | Jun 28, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [4a3a417531](https://linux-hardware.org/?probe=4a3a417531) | Jun 28, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [14b760d760](https://linux-hardware.org/?probe=14b760d760) | Jun 28, 2021 |
| Acer          | One S1003                   | Tablet      | [db5be6c431](https://linux-hardware.org/?probe=db5be6c431) | Jun 28, 2021 |
| ASUSTek       | X751LJ                      | Notebook    | [d4314245a2](https://linux-hardware.org/?probe=d4314245a2) | Jun 28, 2021 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [83b0ff67dd](https://linux-hardware.org/?probe=83b0ff67dd) | Jun 28, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [7a20aa2c3b](https://linux-hardware.org/?probe=7a20aa2c3b) | Jun 27, 2021 |
| Gigabyte      | P55-UD5                     | Desktop     | [934948c85f](https://linux-hardware.org/?probe=934948c85f) | Jun 27, 2021 |
| Allview       | Allbook H                   | Notebook    | [02832b0883](https://linux-hardware.org/?probe=02832b0883) | Jun 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a6c3875064](https://linux-hardware.org/?probe=a6c3875064) | Jun 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [3fabc021d6](https://linux-hardware.org/?probe=3fabc021d6) | Jun 25, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [59b653ec10](https://linux-hardware.org/?probe=59b653ec10) | Jun 25, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [f19497e31d](https://linux-hardware.org/?probe=f19497e31d) | Jun 22, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [aa753c135b](https://linux-hardware.org/?probe=aa753c135b) | Jun 21, 2021 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [07cc916c5e](https://linux-hardware.org/?probe=07cc916c5e) | Jun 21, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | Notebook    | [7bc2410a2a](https://linux-hardware.org/?probe=7bc2410a2a) | Jun 20, 2021 |
| MSI           | Z87-G43                     | Desktop     | [c049769b6b](https://linux-hardware.org/?probe=c049769b6b) | Jun 20, 2021 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [368b96ef78](https://linux-hardware.org/?probe=368b96ef78) | Jun 20, 2021 |
| HP            | 255 G4                      | Notebook    | [3a4a67761f](https://linux-hardware.org/?probe=3a4a67761f) | Jun 19, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [5ed8c507ef](https://linux-hardware.org/?probe=5ed8c507ef) | Jun 18, 2021 |
| Dell          | Precision M6600             | Notebook    | [3ba95fa890](https://linux-hardware.org/?probe=3ba95fa890) | Jun 18, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [ba202e6f1e](https://linux-hardware.org/?probe=ba202e6f1e) | Jun 17, 2021 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [4bc7b480e0](https://linux-hardware.org/?probe=4bc7b480e0) | Jun 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [01666caf41](https://linux-hardware.org/?probe=01666caf41) | Jun 16, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [ef3ce7621e](https://linux-hardware.org/?probe=ef3ce7621e) | Jun 13, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [86c9df0816](https://linux-hardware.org/?probe=86c9df0816) | Jun 12, 2021 |
| HP            | 829E                        | Mini pc     | [7795bf0d95](https://linux-hardware.org/?probe=7795bf0d95) | Jun 12, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [1df7b23225](https://linux-hardware.org/?probe=1df7b23225) | Jun 11, 2021 |
| HP            | 1494                        | Desktop     | [d34b022996](https://linux-hardware.org/?probe=d34b022996) | Jun 11, 2021 |
| ASUSTek       | V241FA                      | All in one  | [ab5720591e](https://linux-hardware.org/?probe=ab5720591e) | Jun 11, 2021 |
| Dell          | XPS L501X                   | Notebook    | [53b5e4986f](https://linux-hardware.org/?probe=53b5e4986f) | Jun 10, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | Notebook    | [5a8e01e79d](https://linux-hardware.org/?probe=5a8e01e79d) | Jun 05, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | Notebook    | [98c6853a46](https://linux-hardware.org/?probe=98c6853a46) | Jun 05, 2021 |
| Lenovo        | ThinkPad T440 20B7A04RGE    | Notebook    | [5b0de3fa72](https://linux-hardware.org/?probe=5b0de3fa72) | Jun 04, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| Packard Be... | EasyNote MV86               | Notebook    | [c393f3c880](https://linux-hardware.org/?probe=c393f3c880) | Jun 03, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [290d70d292](https://linux-hardware.org/?probe=290d70d292) | Jun 03, 2021 |
| ASUSTek       | P5LD2-VM                    | Desktop     | [6b68ceb0b3](https://linux-hardware.org/?probe=6b68ceb0b3) | Jun 02, 2021 |
| Lenovo        | G550 20023                  | Notebook    | [a962a76b58](https://linux-hardware.org/?probe=a962a76b58) | Jun 01, 2021 |
| ASUSTek       | P5LD2-VM                    | Desktop     | [3bdb847f96](https://linux-hardware.org/?probe=3bdb847f96) | Jun 01, 2021 |
| Lenovo        | G550 20023                  | Notebook    | [1bbec614aa](https://linux-hardware.org/?probe=1bbec614aa) | May 31, 2021 |
| Huanan        | X99-TF                      | Desktop     | [b92f4485e6](https://linux-hardware.org/?probe=b92f4485e6) | May 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [6aff8771b1](https://linux-hardware.org/?probe=6aff8771b1) | May 30, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b63698a4af](https://linux-hardware.org/?probe=b63698a4af) | May 29, 2021 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [d340a44211](https://linux-hardware.org/?probe=d340a44211) | May 28, 2021 |
| HP            | 3031h                       | Desktop     | [d69cd77c4d](https://linux-hardware.org/?probe=d69cd77c4d) | May 28, 2021 |
| Gigabyte      | 965GM-S2                    | Desktop     | [05ac3124f9](https://linux-hardware.org/?probe=05ac3124f9) | May 26, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [7fb630f632](https://linux-hardware.org/?probe=7fb630f632) | May 26, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [b251de2587](https://linux-hardware.org/?probe=b251de2587) | May 26, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [3ff174d668](https://linux-hardware.org/?probe=3ff174d668) | May 26, 2021 |
| ASUSTek       | X555LN                      | Notebook    | [7baba93fdf](https://linux-hardware.org/?probe=7baba93fdf) | May 25, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [87aca59a7c](https://linux-hardware.org/?probe=87aca59a7c) | May 25, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [522583da69](https://linux-hardware.org/?probe=522583da69) | May 25, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [141475f02b](https://linux-hardware.org/?probe=141475f02b) | May 25, 2021 |
| Dell          | Latitude D630               | Notebook    | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [02d50458ce](https://linux-hardware.org/?probe=02d50458ce) | May 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [8fe5ffb1cc](https://linux-hardware.org/?probe=8fe5ffb1cc) | May 21, 2021 |
| HP            | 3029h                       | Desktop     | [1f0ebaa79c](https://linux-hardware.org/?probe=1f0ebaa79c) | May 20, 2021 |
| HP            | 3029h                       | Desktop     | [9eac66bf17](https://linux-hardware.org/?probe=9eac66bf17) | May 20, 2021 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [d4187bad77](https://linux-hardware.org/?probe=d4187bad77) | May 20, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [9bc3a8a33e](https://linux-hardware.org/?probe=9bc3a8a33e) | May 20, 2021 |
| Gigabyte      | 965GM-S2                    | Desktop     | [7db6d2bc1a](https://linux-hardware.org/?probe=7db6d2bc1a) | May 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [1c24b50a75](https://linux-hardware.org/?probe=1c24b50a75) | May 20, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [32546ecaa0](https://linux-hardware.org/?probe=32546ecaa0) | May 17, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [9f12330c51](https://linux-hardware.org/?probe=9f12330c51) | May 15, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [86b562f999](https://linux-hardware.org/?probe=86b562f999) | May 14, 2021 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [110d291fde](https://linux-hardware.org/?probe=110d291fde) | May 13, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [18ca89b617](https://linux-hardware.org/?probe=18ca89b617) | May 11, 2021 |
| HP            | 1494                        | Desktop     | [26a35b5f46](https://linux-hardware.org/?probe=26a35b5f46) | May 10, 2021 |
| ASUSTek       | J1800I-C                    | Desktop     | [2554e9ed0c](https://linux-hardware.org/?probe=2554e9ed0c) | May 10, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [7a0e366273](https://linux-hardware.org/?probe=7a0e366273) | May 09, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [1809630187](https://linux-hardware.org/?probe=1809630187) | May 09, 2021 |
| HP            | 1496                        | Desktop     | [ef4e0697d7](https://linux-hardware.org/?probe=ef4e0697d7) | May 08, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [356c77df30](https://linux-hardware.org/?probe=356c77df30) | May 07, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [d4cf6a320b](https://linux-hardware.org/?probe=d4cf6a320b) | May 07, 2021 |
| Dell          | Latitude E7470              | Notebook    | [c854d464d4](https://linux-hardware.org/?probe=c854d464d4) | May 07, 2021 |
| Toshiba       | Satellite Pro U200          | Notebook    | [ea94c20118](https://linux-hardware.org/?probe=ea94c20118) | May 06, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [5927d6bfa2](https://linux-hardware.org/?probe=5927d6bfa2) | May 06, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [8770317d57](https://linux-hardware.org/?probe=8770317d57) | May 06, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ec0def5c1e](https://linux-hardware.org/?probe=ec0def5c1e) | May 06, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [cd3b8f3bca](https://linux-hardware.org/?probe=cd3b8f3bca) | May 06, 2021 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [6367a7db0a](https://linux-hardware.org/?probe=6367a7db0a) | May 06, 2021 |
| Toshiba       | Satellite Pro U200          | Notebook    | [1442c68bc8](https://linux-hardware.org/?probe=1442c68bc8) | May 05, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f90ca57fa0](https://linux-hardware.org/?probe=f90ca57fa0) | May 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [b1a5da541f](https://linux-hardware.org/?probe=b1a5da541f) | May 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [155da00fc0](https://linux-hardware.org/?probe=155da00fc0) | May 03, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Lenovo        | ThinkPad T61 7659W1W        | Notebook    | [c366a3e7a2](https://linux-hardware.org/?probe=c366a3e7a2) | May 01, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [3eeaf82899](https://linux-hardware.org/?probe=3eeaf82899) | May 01, 2021 |
| Dell          | Latitude E7470              | Notebook    | [b4d85c0e7c](https://linux-hardware.org/?probe=b4d85c0e7c) | May 01, 2021 |
| Dell          | Latitude E7470              | Notebook    | [1e60f8c14a](https://linux-hardware.org/?probe=1e60f8c14a) | May 01, 2021 |
| Dell          | Latitude E6430              | Notebook    | [4ba28d9505](https://linux-hardware.org/?probe=4ba28d9505) | May 01, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [d0c8d6944c](https://linux-hardware.org/?probe=d0c8d6944c) | Apr 30, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [a72228a343](https://linux-hardware.org/?probe=a72228a343) | Apr 29, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [7f935099f0](https://linux-hardware.org/?probe=7f935099f0) | Apr 28, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [8dbfa5594e](https://linux-hardware.org/?probe=8dbfa5594e) | Apr 27, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [ed71084f85](https://linux-hardware.org/?probe=ed71084f85) | Apr 27, 2021 |
| ASUSTek       | ROG Strix G531GV_G531GV     | Notebook    | [4dfa28cef5](https://linux-hardware.org/?probe=4dfa28cef5) | Apr 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [d5a5a8496d](https://linux-hardware.org/?probe=d5a5a8496d) | Apr 23, 2021 |
| MSI           | MS-7502 Fab D               | Desktop     | [2a2d112995](https://linux-hardware.org/?probe=2a2d112995) | Apr 23, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [06b060c49c](https://linux-hardware.org/?probe=06b060c49c) | Apr 23, 2021 |
| HP            | G62                         | Notebook    | [d728a70b0b](https://linux-hardware.org/?probe=d728a70b0b) | Apr 23, 2021 |
| ASUSTek       | GL552VX                     | Notebook    | [294a96afbb](https://linux-hardware.org/?probe=294a96afbb) | Apr 22, 2021 |
| ASUSTek       | GL552VX                     | Notebook    | [534b39dba5](https://linux-hardware.org/?probe=534b39dba5) | Apr 22, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [1c206551a3](https://linux-hardware.org/?probe=1c206551a3) | Apr 22, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [83c7d6b0a2](https://linux-hardware.org/?probe=83c7d6b0a2) | Apr 22, 2021 |
| Lenovo        | ThinkPad E560 20EV003AUK    | Notebook    | [3f10db447f](https://linux-hardware.org/?probe=3f10db447f) | Apr 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3feeb55814](https://linux-hardware.org/?probe=3feeb55814) | Apr 20, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [42b2eb88ad](https://linux-hardware.org/?probe=42b2eb88ad) | Apr 19, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [b91839a518](https://linux-hardware.org/?probe=b91839a518) | Apr 19, 2021 |
| MSI           | MS-7367                     | Desktop     | [1a103f941a](https://linux-hardware.org/?probe=1a103f941a) | Apr 18, 2021 |
| HP            | 1790                        | Desktop     | [75557f3294](https://linux-hardware.org/?probe=75557f3294) | Apr 18, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [a83dfd361b](https://linux-hardware.org/?probe=a83dfd361b) | Apr 14, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [b8e3c87a38](https://linux-hardware.org/?probe=b8e3c87a38) | Apr 14, 2021 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [22d879f5ea](https://linux-hardware.org/?probe=22d879f5ea) | Apr 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8b5a5a31fb](https://linux-hardware.org/?probe=8b5a5a31fb) | Apr 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d6b88752a0](https://linux-hardware.org/?probe=d6b88752a0) | Apr 12, 2021 |
| Lenovo        | ThinkPad S3-S440 20AYCTO... | Notebook    | [d2d3020f8b](https://linux-hardware.org/?probe=d2d3020f8b) | Apr 12, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [082fe11ffb](https://linux-hardware.org/?probe=082fe11ffb) | Apr 12, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [2e69cf4f5a](https://linux-hardware.org/?probe=2e69cf4f5a) | Apr 12, 2021 |
| Dell          | 04GJJT A00                  | Desktop     | [b687e379b9](https://linux-hardware.org/?probe=b687e379b9) | Apr 11, 2021 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [7b4c090391](https://linux-hardware.org/?probe=7b4c090391) | Apr 11, 2021 |
| Lenovo        | ThinkCentre M91p 4524AS3    | Desktop     | [79febd76c3](https://linux-hardware.org/?probe=79febd76c3) | Apr 11, 2021 |
| Dell          | Latitude E6410              | Notebook    | [9fc394df40](https://linux-hardware.org/?probe=9fc394df40) | Apr 10, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [79528a1998](https://linux-hardware.org/?probe=79528a1998) | Apr 09, 2021 |
| HP            | 2215                        | Desktop     | [0ce403b929](https://linux-hardware.org/?probe=0ce403b929) | Apr 09, 2021 |
| Lenovo        | ThinkCentre M58 7373WB7     | Desktop     | [57e7329bf2](https://linux-hardware.org/?probe=57e7329bf2) | Apr 09, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [7730367108](https://linux-hardware.org/?probe=7730367108) | Apr 08, 2021 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [949f9eb773](https://linux-hardware.org/?probe=949f9eb773) | Apr 06, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [af302c8ef5](https://linux-hardware.org/?probe=af302c8ef5) | Apr 05, 2021 |
| Lenovo        | ThinkCentre M58 7359A59     | Desktop     | [0784afdde4](https://linux-hardware.org/?probe=0784afdde4) | Apr 05, 2021 |
| Lenovo        | ThinkCentre M58 7359A59     | Desktop     | [3c49f2205f](https://linux-hardware.org/?probe=3c49f2205f) | Apr 05, 2021 |
| HP            | G62                         | Notebook    | [b706770f8d](https://linux-hardware.org/?probe=b706770f8d) | Apr 05, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [ac0a48160a](https://linux-hardware.org/?probe=ac0a48160a) | Apr 05, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [533ebeaa6e](https://linux-hardware.org/?probe=533ebeaa6e) | Apr 05, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [4b5d46fe3a](https://linux-hardware.org/?probe=4b5d46fe3a) | Apr 03, 2021 |
| Dell          | Latitude E6410              | Notebook    | [297aaeb4ac](https://linux-hardware.org/?probe=297aaeb4ac) | Apr 03, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [f66cd74385](https://linux-hardware.org/?probe=f66cd74385) | Apr 03, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [11d853a6cd](https://linux-hardware.org/?probe=11d853a6cd) | Apr 03, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [a97fe90c04](https://linux-hardware.org/?probe=a97fe90c04) | Apr 03, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [83700e8ca7](https://linux-hardware.org/?probe=83700e8ca7) | Apr 03, 2021 |
| Samsung       | 300V3Z/300V4Z/300V5Z/200... | Notebook    | [51ed7ce2e8](https://linux-hardware.org/?probe=51ed7ce2e8) | Apr 03, 2021 |
| Samsung       | 300V3Z/300V4Z/300V5Z/200... | Notebook    | [a3bd82613b](https://linux-hardware.org/?probe=a3bd82613b) | Apr 03, 2021 |
| Fujitsu       | LIFEBOOK NH751              | Notebook    | [27bf374b6e](https://linux-hardware.org/?probe=27bf374b6e) | Apr 01, 2021 |
| Fujitsu       | LIFEBOOK NH751              | Notebook    | [24b8bc435b](https://linux-hardware.org/?probe=24b8bc435b) | Apr 01, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [c3bc72bfce](https://linux-hardware.org/?probe=c3bc72bfce) | Mar 29, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [93285dae9e](https://linux-hardware.org/?probe=93285dae9e) | Mar 29, 2021 |
| Lenovo        | ThinkPad T480s 20L7001LR... | Notebook    | [440edfbe7e](https://linux-hardware.org/?probe=440edfbe7e) | Mar 26, 2021 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [3fe5519929](https://linux-hardware.org/?probe=3fe5519929) | Mar 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [3d13dd330c](https://linux-hardware.org/?probe=3d13dd330c) | Mar 25, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [0d1ffacb54](https://linux-hardware.org/?probe=0d1ffacb54) | Mar 24, 2021 |
| ASUSTek       | GL552JX                     | Notebook    | [af998c8996](https://linux-hardware.org/?probe=af998c8996) | Mar 22, 2021 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [103f41c99c](https://linux-hardware.org/?probe=103f41c99c) | Mar 21, 2021 |
| Dell          | Latitude E6440              | Notebook    | [6f00c6ac0b](https://linux-hardware.org/?probe=6f00c6ac0b) | Mar 21, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [6270efa573](https://linux-hardware.org/?probe=6270efa573) | Mar 20, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e76eac394d](https://linux-hardware.org/?probe=e76eac394d) | Mar 20, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [a9efbe668e](https://linux-hardware.org/?probe=a9efbe668e) | Mar 20, 2021 |
| HP            | 3029h                       | Desktop     | [0ddf4fe8c8](https://linux-hardware.org/?probe=0ddf4fe8c8) | Mar 20, 2021 |
| HP            | EliteBook x360 1040 G5      | Notebook    | [6c42757430](https://linux-hardware.org/?probe=6c42757430) | Mar 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [35f9677ce6](https://linux-hardware.org/?probe=35f9677ce6) | Mar 19, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [98d6ff8291](https://linux-hardware.org/?probe=98d6ff8291) | Mar 19, 2021 |
| MSI           | EX620                       | Notebook    | [92223bedbf](https://linux-hardware.org/?probe=92223bedbf) | Mar 18, 2021 |
| HP            | Laptop 17-ak0xx             | Notebook    | [2eee8ebb3d](https://linux-hardware.org/?probe=2eee8ebb3d) | Mar 18, 2021 |
| HP            | Laptop 17-ak0xx             | Notebook    | [4e9b5c0bbe](https://linux-hardware.org/?probe=4e9b5c0bbe) | Mar 18, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Romania/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 204       | 12.09%  |
| Ubuntu 18.04      | 106       | 6.28%   |
| BlackPanther 18.1 | 57        | 3.38%   |
| Ubuntu 22.04      | 45        | 2.67%   |
| OpenMandriva 4.2  | 44        | 2.61%   |
| OpenMandriva 4.3  | 41        | 2.43%   |
| Arch              | 28        | 1.66%   |
| ROSA R10          | 27        | 1.6%    |
| Manjaro           | 25        | 1.48%   |
| KDE neon 20.04    | 24        | 1.42%   |
| Pop!_OS 21.04     | 23        | 1.36%   |
| Debian 11         | 21        | 1.24%   |
| Ubuntu 21.10      | 20        | 1.18%   |
| Pop!_OS 20.04     | 20        | 1.18%   |
| Endless 3.7.8     | 20        | 1.18%   |
| Zorin 16          | 19        | 1.13%   |
| Zorin 15          | 19        | 1.13%   |
| Fedora 35         | 19        | 1.13%   |
| Endless 3.9.5     | 18        | 1.07%   |
| Endless 3.9.1     | 18        | 1.07%   |
| Ubuntu 20.10      | 17        | 1.01%   |
| Ubuntu 19.10      | 17        | 1.01%   |
| ArcoLinux Rolling | 17        | 1.01%   |
| Ubuntu 21.04      | 16        | 0.95%   |
| Arch Rolling      | 16        | 0.95%   |
| Ubuntu 19.04      | 15        | 0.89%   |
| Pop!_OS 22.04     | 15        | 0.89%   |
| Pop!_OS 20.10     | 15        | 0.89%   |
| Linux Mint 20.2   | 15        | 0.89%   |
| Fedora 34         | 15        | 0.89%   |
| Endless 3.8.6     | 15        | 0.89%   |
| Endless 3.8.0     | 15        | 0.89%   |
| Linux Mint 20.3   | 14        | 0.83%   |
| Linux Mint 20.1   | 14        | 0.83%   |
| Fedora 36         | 14        | 0.83%   |
| ROSA R9           | 13        | 0.77%   |
| Pop!_OS 21.10     | 13        | 0.77%   |
| Xubuntu 20.04     | 12        | 0.71%   |
| ROSA R11          | 12        | 0.71%   |
| Endless 3.9.0     | 12        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu            | 444       | 28.43%  |
| Endless           | 245       | 15.69%  |
| OpenMandriva      | 97        | 6.21%   |
| Fedora            | 84        | 5.38%   |
| Pop!_OS           | 82        | 5.25%   |
| Linux Mint        | 78        | 4.99%   |
| ROSA              | 65        | 4.16%   |
| BlackPanther      | 59        | 3.78%   |
| Manjaro           | 54        | 3.46%   |
| Arch              | 43        | 2.75%   |
| Zorin             | 41        | 2.62%   |
| Debian            | 39        | 2.5%    |
| KDE neon          | 26        | 1.66%   |
| Xubuntu           | 21        | 1.34%   |
| Kubuntu           | 19        | 1.22%   |
| ArcoLinux         | 19        | 1.22%   |
| Clear Linux       | 14        | 0.9%    |
| Ubuntu Unity      | 12        | 0.77%   |
| openSUSE          | 12        | 0.77%   |
| Kali              | 10        | 0.64%   |
| Elementary        | 10        | 0.64%   |
| Ubuntu MATE       | 9         | 0.58%   |
| Gentoo            | 8         | 0.51%   |
| Peppermint        | 7         | 0.45%   |
| Garuda Linux      | 6         | 0.38%   |
| EndeavourOS       | 6         | 0.38%   |
| SteamOS           | 5         | 0.32%   |
| LMDE              | 5         | 0.32%   |
| Linux Lite        | 5         | 0.32%   |
| Raspbian          | 4         | 0.26%   |
| Lubuntu           | 4         | 0.26%   |
| Ubuntu Budgie     | 3         | 0.19%   |
| CentOS            | 3         | 0.19%   |
| Ubuntu Studio     | 2         | 0.13%   |
| RHEL              | 2         | 0.13%   |
| Q4OS              | 2         | 0.13%   |
| Oracle Linux      | 2         | 0.13%   |
| MX                | 2         | 0.13%   |
| Xero              | 1         | 0.06%   |
| Ultramarine Linux | 1         | 0.06%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-14-generic                | 69        | 3.89%   |
| 5.4.0-42-generic                | 50        | 2.82%   |
| 4.18.16-desktop-1bP             | 45        | 2.54%   |
| 5.10.14-desktop-1omv4002        | 43        | 2.43%   |
| 5.16.7-desktop-1omv4003         | 36        | 2.03%   |
| 5.4.0-19-generic                | 32        | 1.8%    |
| 5.3.0-28-generic                | 26        | 1.47%   |
| 5.3.0-23-generic                | 18        | 1.02%   |
| 4.18.0-15-generic               | 17        | 0.96%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 16        | 0.9%    |
| 5.0.0-25-generic                | 15        | 0.85%   |
| 5.4.0-40-generic                | 14        | 0.79%   |
| 5.11.0-35-generic               | 14        | 0.79%   |
| 5.3.0-46-generic                | 13        | 0.73%   |
| 5.6.14-desktop-2bP              | 12        | 0.68%   |
| 5.0.0-20-generic                | 12        | 0.68%   |
| 5.4.0-52-generic                | 11        | 0.62%   |
| 5.4.0-29-generic                | 11        | 0.62%   |
| 5.4.0-26-generic                | 11        | 0.62%   |
| 5.3.0-19-generic                | 11        | 0.62%   |
| 5.15.0-52-generic               | 11        | 0.62%   |
| 5.4.0-56-generic                | 10        | 0.56%   |
| 5.4.0-54-generic                | 10        | 0.56%   |
| 5.13.0-28-generic               | 10        | 0.56%   |
| 5.11.0-7620-generic             | 10        | 0.56%   |
| 5.11.0-43-generic               | 10        | 0.56%   |
| 5.0.0-37-generic                | 10        | 0.56%   |
| 4.15.0-15-generic               | 10        | 0.56%   |
| 5.8.0-50-generic                | 9         | 0.51%   |
| 5.4.0-7634-generic              | 9         | 0.51%   |
| 5.4.0-74-generic                | 9         | 0.51%   |
| 5.4.0-66-generic                | 9         | 0.51%   |
| 5.4.0-47-generic                | 9         | 0.51%   |
| 5.4.0-37-generic                | 9         | 0.51%   |
| 5.4.0-31-generic                | 9         | 0.51%   |
| 5.3.0-51-generic                | 9         | 0.51%   |
| 5.15.0-48-generic               | 9         | 0.51%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 9         | 0.51%   |
| 5.8.0-7642-generic              | 8         | 0.45%   |
| 5.4.0-91-generic                | 8         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 302       | 17.87%  |
| 5.8.0   | 149       | 8.82%   |
| 5.3.0   | 117       | 6.92%   |
| 5.11.0  | 96        | 5.68%   |
| 4.15.0  | 96        | 5.68%   |
| 5.0.0   | 80        | 4.73%   |
| 5.15.0  | 75        | 4.44%   |
| 5.13.0  | 65        | 3.85%   |
| 4.18.0  | 52        | 3.08%   |
| 4.18.16 | 45        | 2.66%   |
| 5.10.14 | 44        | 2.6%    |
| 5.16.7  | 36        | 2.13%   |
| 5.10.0  | 27        | 1.6%    |
| 4.9.60  | 18        | 1.07%   |
| 4.9.20  | 15        | 0.89%   |
| 5.6.14  | 13        | 0.77%   |
| 4.19.0  | 11        | 0.65%   |
| 5.19.0  | 10        | 0.59%   |
| 4.13.0  | 10        | 0.59%   |
| 4.9.76  | 8         | 0.47%   |
| 5.8.18  | 7         | 0.41%   |
| 5.18.10 | 6         | 0.36%   |
| 6.0.11  | 5         | 0.3%    |
| 5.9.16  | 5         | 0.3%    |
| 5.9.0   | 5         | 0.3%    |
| 5.18.12 | 5         | 0.3%    |
| 5.18.0  | 5         | 0.3%    |
| 5.17.0  | 5         | 0.3%    |
| 5.16.13 | 5         | 0.3%    |
| 5.15.8  | 5         | 0.3%    |
| 5.15.12 | 5         | 0.3%    |
| 6.0.6   | 4         | 0.24%   |
| 6.0.0   | 4         | 0.24%   |
| 5.8.3   | 4         | 0.24%   |
| 5.4.18  | 4         | 0.24%   |
| 5.3.18  | 4         | 0.24%   |
| 5.16.11 | 4         | 0.24%   |
| 5.15.4  | 4         | 0.24%   |
| 5.14.0  | 4         | 0.24%   |
| 5.12.4  | 4         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 323       | 19.32%  |
| 5.8     | 176       | 10.53%  |
| 5.3     | 127       | 7.6%    |
| 5.15    | 116       | 6.94%   |
| 5.11    | 110       | 6.58%   |
| 4.18    | 99        | 5.92%   |
| 4.15    | 96        | 5.74%   |
| 5.10    | 94        | 5.62%   |
| 5.0     | 85        | 5.08%   |
| 5.13    | 72        | 4.31%   |
| 5.16    | 65        | 3.89%   |
| 4.9     | 50        | 2.99%   |
| 5.19    | 29        | 1.73%   |
| 6.0     | 27        | 1.61%   |
| 5.6     | 27        | 1.61%   |
| 5.18    | 26        | 1.56%   |
| 5.9     | 22        | 1.32%   |
| 5.17    | 21        | 1.26%   |
| 5.12    | 18        | 1.08%   |
| 5.14    | 17        | 1.02%   |
| 4.19    | 14        | 0.84%   |
| 5.7     | 10        | 0.6%    |
| 4.13    | 10        | 0.6%    |
| 4.1     | 8         | 0.48%   |
| 5.5     | 7         | 0.42%   |
| 5.2     | 5         | 0.3%    |
| 6.1     | 4         | 0.24%   |
| 5.1     | 4         | 0.24%   |
| 4.8     | 3         | 0.18%   |
| 4.12    | 2         | 0.12%   |
| 4.4     | 1         | 0.06%   |
| 4.17    | 1         | 0.06%   |
| 4.16    | 1         | 0.06%   |
| 4.14    | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1469      | 97.28%  |
| i686    | 33        | 2.19%   |
| armv7l  | 4         | 0.26%   |
| aarch64 | 4         | 0.26%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 748       | 47.73%  |
| KDE5             | 269       | 17.17%  |
| Unknown          | 221       | 14.1%   |
| XFCE             | 79        | 5.04%   |
| X-Cinnamon       | 59        | 3.77%   |
| KDE4             | 44        | 2.81%   |
| KDE              | 39        | 2.49%   |
| MATE             | 24        | 1.53%   |
| Unity            | 12        | 0.77%   |
| LXDE             | 12        | 0.77%   |
| Cinnamon         | 12        | 0.77%   |
| LXQt             | 10        | 0.64%   |
| Pantheon         | 8         | 0.51%   |
| i3               | 5         | 0.32%   |
| Budgie           | 4         | 0.26%   |
| Openbox          | 3         | 0.19%   |
| Deepin           | 3         | 0.19%   |
| xmonad           | 2         | 0.13%   |
| sway             | 2         | 0.13%   |
| GNOME Flashback  | 2         | 0.13%   |
| GNOME Classic    | 2         | 0.13%   |
| lightdm-xsession | 1         | 0.06%   |
| jwm              | 1         | 0.06%   |
| GNUstep          | 1         | 0.06%   |
| GNOME-Flashback  | 1         | 0.06%   |
| dusk             | 1         | 0.06%   |
| bspwm            | 1         | 0.06%   |
| awesome          | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1226      | 79.66%  |
| Wayland     | 146       | 9.49%   |
| Unknown     | 145       | 9.42%   |
| Tty         | 21        | 1.36%   |
| Unspecified | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 895       | 57.12%  |
| SDDM    | 245       | 15.63%  |
| GDM     | 150       | 9.57%   |
| GDM3    | 98        | 6.25%   |
| LightDM | 87        | 5.55%   |
| KDM     | 44        | 2.81%   |
| TDM     | 41        | 2.62%   |
| XDM     | 3         | 0.19%   |
| SLiM    | 2         | 0.13%   |
| Ly      | 1         | 0.06%   |
| LXDM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 877       | 56.51%  |
| Unknown     | 306       | 19.72%  |
| ro_RO       | 270       | 17.4%   |
| en_GB       | 26        | 1.68%   |
| C           | 23        | 1.48%   |
| hu_HU       | 12        | 0.77%   |
| it_IT       | 10        | 0.64%   |
| de_DE       | 4         | 0.26%   |
| fr_FR       | 3         | 0.19%   |
| es_ES       | 3         | 0.19%   |
| en_IL       | 3         | 0.19%   |
| ru_RU       | 2         | 0.13%   |
| en_IN       | 2         | 0.13%   |
| en_AG       | 2         | 0.13%   |
| nl_NL       | 1         | 0.06%   |
| fr_CH       | 1         | 0.06%   |
| es_MX       | 1         | 0.06%   |
| en_US.UTF8  | 1         | 0.06%   |
| en_US.utf-8 | 1         | 0.06%   |
| en_DE       | 1         | 0.06%   |
| en_CA       | 1         | 0.06%   |
| en_001      | 1         | 0.06%   |
| C.UTF8      | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 769       | 50.03%  |
| EFI  | 768       | 49.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1121      | 72.56%  |
| Unknown | 154       | 9.97%   |
| Overlay | 151       | 9.77%   |
| Btrfs   | 86        | 5.57%   |
| Xfs     | 14        | 0.91%   |
| Tmpfs   | 7         | 0.45%   |
| Zfs     | 4         | 0.26%   |
| F2fs    | 3         | 0.19%   |
| Ext2    | 3         | 0.19%   |
| Jfs     | 1         | 0.06%   |
| Ext3    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 931       | 60.65%  |
| GPT     | 393       | 25.6%   |
| MBR     | 211       | 13.75%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1335      | 86.8%   |
| Yes       | 203       | 13.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1123      | 72.97%  |
| Yes       | 416       | 27.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 394       | 26.13%  |
| Lenovo                  | 233       | 15.45%  |
| Dell                    | 183       | 12.14%  |
| Hewlett-Packard         | 176       | 11.67%  |
| Gigabyte Technology     | 109       | 7.23%   |
| Acer                    | 100       | 6.63%   |
| MSI                     | 73        | 4.84%   |
| ASRock                  | 40        | 2.65%   |
| Toshiba                 | 21        | 1.39%   |
| Intel                   | 14        | 0.93%   |
| Fujitsu Siemens         | 13        | 0.86%   |
| Apple                   | 13        | 0.86%   |
| Complet                 | 12        | 0.8%    |
| Sony                    | 10        | 0.66%   |
| Medion                  | 9         | 0.6%    |
| Unknown                 | 9         | 0.6%    |
| Raspberry Pi Foundation | 8         | 0.53%   |
| HUAWEI                  | 8         | 0.53%   |
| Fujitsu                 | 7         | 0.46%   |
| Samsung Electronics     | 6         | 0.4%    |
| Pegatron                | 6         | 0.4%    |
| Foxconn                 | 6         | 0.4%    |
| Valve                   | 4         | 0.27%   |
| Packard Bell            | 4         | 0.27%   |
| Chuwi                   | 4         | 0.27%   |
| Allview                 | 4         | 0.27%   |
| Alienware               | 3         | 0.2%    |
| TUXEDO                  | 2         | 0.13%   |
| Timi                    | 2         | 0.13%   |
| Supermicro              | 2         | 0.13%   |
| IBM                     | 2         | 0.13%   |
| AMI                     | 2         | 0.13%   |
| ZOTAC                   | 1         | 0.07%   |
| Visual Fan              | 1         | 0.07%   |
| Thomson                 | 1         | 0.07%   |
| Prestigio               | 1         | 0.07%   |
| Panasonic               | 1         | 0.07%   |
| OEM_MB                  | 1         | 0.07%   |
| Notebook                | 1         | 0.07%   |
| nJoy Romania            | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS X541NA                                | 17        | 1.13%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 16        | 1.06%   |
| Unknown                                    | 12        | 0.8%    |
| ASUS All Series                            | 11        | 0.73%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 10        | 0.66%   |
| ASUS VivoBook_ASUSLaptop X509FA_X509FA     | 9         | 0.6%    |
| Dell XPS 15 9530                           | 7         | 0.46%   |
| Complet MY8312                             | 7         | 0.46%   |
| Lenovo Legion Y530-15ICH 81FV              | 6         | 0.4%    |
| ASUS X406UAR                               | 6         | 0.4%    |
| ASUS VivoBook_ASUSLaptop X509FB_X509FB     | 6         | 0.4%    |
| ASUS VivoBook 15_ASUS Laptop X540MA_A540MA | 6         | 0.4%    |
| Lenovo V330-15IKB 81AX                     | 5         | 0.33%   |
| Gigabyte B450M DS3H                        | 5         | 0.33%   |
| ASUS X541UVK                               | 5         | 0.33%   |
| ASUS X541UAK                               | 5         | 0.33%   |
| ASUS VivoBook_ASUS Laptop X505ZA_A505ZA    | 5         | 0.33%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 5         | 0.33%   |
| Valve Jupiter                              | 4         | 0.27%   |
| MSI MS-7996                                | 4         | 0.27%   |
| MSI MS-7721                                | 4         | 0.27%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 4         | 0.27%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 4         | 0.27%   |
| Lenovo G510 20238                          | 4         | 0.27%   |
| HP Notebook                                | 4         | 0.27%   |
| Gigabyte X470 AORUS ULTRA GAMING           | 4         | 0.27%   |
| Dell OptiPlex 7010                         | 4         | 0.27%   |
| Dell Latitude E6410                        | 4         | 0.27%   |
| Dell Inspiron 5558                         | 4         | 0.27%   |
| ASUS ZenBook UX431DA_UM431DA               | 4         | 0.27%   |
| ASUS X542UAR                               | 4         | 0.27%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA     | 4         | 0.27%   |
| ASUS VivoBook_ASUSLaptop X513EA_K513EA     | 4         | 0.27%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 4         | 0.27%   |
| ASUS GL552JX                               | 4         | 0.27%   |
| Acer Aspire E5-573G                        | 4         | 0.27%   |
| Acer Aspire E1-531                         | 4         | 0.27%   |
| Acer Aspire A315-21G                       | 4         | 0.27%   |
| RPi Raspberry Pi                           | 3         | 0.2%    |
| Lenovo V110-15ISK 80TL                     | 3         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUS VivoBook           | 109       | 7.23%   |
| Lenovo IdeaPad          | 73        | 4.84%   |
| Lenovo ThinkPad         | 69        | 4.58%   |
| Acer Aspire             | 67        | 4.44%   |
| Dell Latitude           | 52        | 3.45%   |
| Dell Inspiron           | 43        | 2.85%   |
| HP Compaq               | 31        | 2.06%   |
| HP EliteBook            | 27        | 1.79%   |
| HP ProBook              | 26        | 1.72%   |
| Dell OptiPlex           | 26        | 1.72%   |
| ASUS ROG                | 26        | 1.72%   |
| ASUS PRIME              | 25        | 1.66%   |
| Toshiba Satellite       | 20        | 1.33%   |
| HP Pavilion             | 19        | 1.26%   |
| Dell XPS                | 19        | 1.26%   |
| Lenovo Legion           | 17        | 1.13%   |
| ASUS X541NA             | 17        | 1.13%   |
| HP Laptop               | 15        | 0.99%   |
| ASUS ASUS               | 15        | 0.99%   |
| Lenovo ThinkCentre      | 14        | 0.93%   |
| ASUS TUF                | 14        | 0.93%   |
| Dell Vostro             | 12        | 0.8%    |
| Unknown                 | 12        | 0.8%    |
| Dell Precision          | 11        | 0.73%   |
| ASUS All                | 11        | 0.73%   |
| ASUS ZenBook            | 10        | 0.66%   |
| RPi Raspberry           | 8         | 0.53%   |
| Fujitsu Siemens ESPRIMO | 8         | 0.53%   |
| Acer Nitro              | 8         | 0.53%   |
| Lenovo ThinkBook        | 7         | 0.46%   |
| Complet MY8312          | 7         | 0.46%   |
| Acer Extensa            | 7         | 0.46%   |
| HP ZBook                | 6         | 0.4%    |
| Gigabyte X570           | 6         | 0.4%    |
| Gigabyte B450M          | 6         | 0.4%    |
| Dell System             | 6         | 0.4%    |
| Dell PowerEdge          | 6         | 0.4%    |
| ASUS X406UAR            | 6         | 0.4%    |
| Acer Swift              | 6         | 0.4%    |
| Lenovo Yoga             | 5         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 201       | 13.33%  |
| 2018    | 179       | 11.87%  |
| 2017    | 131       | 8.69%   |
| 2020    | 116       | 7.69%   |
| 2013    | 103       | 6.83%   |
| 2015    | 93        | 6.17%   |
| 2012    | 84        | 5.57%   |
| 2011    | 84        | 5.57%   |
| 2021    | 82        | 5.44%   |
| 2014    | 80        | 5.31%   |
| 2010    | 71        | 4.71%   |
| 2008    | 64        | 4.24%   |
| 2016    | 61        | 4.05%   |
| 2009    | 54        | 3.58%   |
| 2007    | 54        | 3.58%   |
| 2022    | 20        | 1.33%   |
| 2006    | 16        | 1.06%   |
| Unknown | 8         | 0.53%   |
| 2005    | 5         | 0.33%   |
| 2004    | 2         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 982       | 65.12%  |
| Desktop        | 456       | 30.24%  |
| All in one     | 21        | 1.39%   |
| Convertible    | 13        | 0.86%   |
| Mini pc        | 13        | 0.86%   |
| Tablet         | 9         | 0.6%    |
| System on chip | 8         | 0.53%   |
| Server         | 6         | 0.4%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1446      | 95.26%  |
| Enabled  | 72        | 4.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1508      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 435       | 28.34%  |
| 4.01-8.0        | 359       | 23.39%  |
| 8.01-16.0       | 268       | 17.46%  |
| 16.01-24.0      | 239       | 15.57%  |
| 32.01-64.0      | 90        | 5.86%   |
| 1.01-2.0        | 72        | 4.69%   |
| 64.01-256.0     | 28        | 1.82%   |
| 2.01-3.0        | 17        | 1.11%   |
| 24.01-32.0      | 13        | 0.85%   |
| 0.51-1.0        | 13        | 0.85%   |
| More than 256.0 | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 651       | 38.7%   |
| 2.01-3.0    | 398       | 23.66%  |
| 3.01-4.0    | 189       | 11.24%  |
| 0.51-1.0    | 179       | 10.64%  |
| 4.01-8.0    | 168       | 9.99%   |
| 8.01-16.0   | 47        | 2.79%   |
| 0.01-0.5    | 41        | 2.44%   |
| 16.01-24.0  | 3         | 0.18%   |
| 32.01-64.0  | 2         | 0.12%   |
| 24.01-32.0  | 2         | 0.12%   |
| 64.01-256.0 | 2         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1029      | 66.43%  |
| 2      | 344       | 22.21%  |
| 3      | 96        | 6.2%    |
| 4      | 36        | 2.32%   |
| 5      | 16        | 1.03%   |
| 0      | 14        | 0.9%    |
| 6      | 4         | 0.26%   |
| 9      | 2         | 0.13%   |
| 8      | 2         | 0.13%   |
| 7      | 2         | 0.13%   |
| 24     | 1         | 0.06%   |
| 15     | 1         | 0.06%   |
| 14     | 1         | 0.06%   |
| 11     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 908       | 59.74%  |
| Yes       | 612       | 40.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1242      | 82.31%  |
| No        | 267       | 17.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1157      | 76.22%  |
| No        | 361       | 23.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 926       | 60.64%  |
| No        | 601       | 39.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Romania | 1508      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Bucharest             | 490       | 30.57%  |
| Cluj-Napoca           | 111       | 6.92%   |
| Iasi                  | 79        | 4.93%   |
| Timișoara            | 58        | 3.62%   |
| Brasov                | 46        | 2.87%   |
| Târgu Mureş         | 43        | 2.68%   |
| Ploieşti             | 37        | 2.31%   |
| Constanța            | 31        | 1.93%   |
| Oradea                | 28        | 1.75%   |
| Sibiu                 | 27        | 1.68%   |
| Arad                  | 24        | 1.5%    |
| Piteşti              | 23        | 1.43%   |
| Craiova               | 21        | 1.31%   |
| Popesti-Leordeni      | 20        | 1.25%   |
| Galati                | 18        | 1.12%   |
| Baia Mare             | 18        | 1.12%   |
| Zalău                | 15        | 0.94%   |
| Voluntari             | 13        | 0.81%   |
| Satu Mare             | 13        | 0.81%   |
| Râmnicu Vâlcea      | 13        | 0.81%   |
| Miercurea-Ciuc        | 12        | 0.75%   |
| Botosani              | 12        | 0.75%   |
| Bacau                 | 12        | 0.75%   |
| Targoviste            | 11        | 0.69%   |
| Braila                | 11        | 0.69%   |
| Reşiţa              | 10        | 0.62%   |
| Piatra Neamţ         | 10        | 0.62%   |
| Focşani              | 10        | 0.62%   |
| Floresti              | 10        | 0.62%   |
| Drobeta-Turnu Severin | 9         | 0.56%   |
| Alba Iulia            | 9         | 0.56%   |
| Târgu Jiu            | 8         | 0.5%    |
| Mediaş               | 8         | 0.5%    |
| Tulcea                | 7         | 0.44%   |
| Sfantu Gheorghe       | 7         | 0.44%   |
| Deva                  | 7         | 0.44%   |
| Beiuș                | 7         | 0.44%   |
| Iorcani               | 6         | 0.37%   |
| Alexandria            | 6         | 0.37%   |
| Slatina               | 5         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 318       | 452    | 15.18%  |
| Seagate                     | 316       | 473    | 15.08%  |
| Samsung Electronics         | 270       | 355    | 12.89%  |
| Kingston                    | 253       | 341    | 12.08%  |
| Toshiba                     | 153       | 188    | 7.3%    |
| Unknown                     | 81        | 108    | 3.87%   |
| SanDisk                     | 81        | 95     | 3.87%   |
| Intel                       | 72        | 90     | 3.44%   |
| A-DATA Technology           | 71        | 90     | 3.39%   |
| Hitachi                     | 58        | 71     | 2.77%   |
| HGST                        | 58        | 74     | 2.77%   |
| SK hynix                    | 56        | 78     | 2.67%   |
| Micron Technology           | 34        | 40     | 1.62%   |
| Crucial                     | 27        | 33     | 1.29%   |
| Patriot                     | 19        | 22     | 0.91%   |
| Phison                      | 16        | 19     | 0.76%   |
| Maxtor                      | 16        | 22     | 0.76%   |
| SPCC                        | 12        | 14     | 0.57%   |
| OCZ                         | 9         | 16     | 0.43%   |
| KIOXIA                      | 9         | 9      | 0.43%   |
| Hewlett-Packard             | 9         | 11     | 0.43%   |
| FORESEE                     | 9         | 10     | 0.43%   |
| Corsair                     | 9         | 13     | 0.43%   |
| XPG                         | 8         | 12     | 0.38%   |
| Kingston Technology Company | 7         | 7      | 0.33%   |
| Fujitsu                     | 7         | 8      | 0.33%   |
| Realtek Semiconductor       | 6         | 7      | 0.29%   |
| Kingmax                     | 6         | 7      | 0.29%   |
| Apple                       | 6         | 9      | 0.29%   |
| Transcend                   | 5         | 7      | 0.24%   |
| GOODRAM                     | 5         | 5      | 0.24%   |
| Gigabyte Technology         | 5         | 5      | 0.24%   |
| China                       | 5         | 5      | 0.24%   |
| ASMT                        | 5         | 5      | 0.24%   |
| Plextor                     | 4         | 4      | 0.19%   |
| Netac                       | 4         | 6      | 0.19%   |
| Apacer                      | 4         | 5      | 0.19%   |
| Verbatim                    | 3         | 5      | 0.14%   |
| Team                        | 3         | 3      | 0.14%   |
| Silicon Motion              | 3         | 3      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 58        | 2.58%   |
| Toshiba MQ01ABF050 500GB                            | 43        | 1.91%   |
| Seagate ST1000LM035-1RK172 1TB                      | 43        | 1.91%   |
| Seagate ST500LT012-1DG142 500GB                     | 26        | 1.16%   |
| Kingston SA400S37120G 120GB SSD                     | 26        | 1.16%   |
| Kingston SA400S37480G 480GB SSD                     | 25        | 1.11%   |
| Kingston SV300S37A120G 120GB SSD                    | 22        | 0.98%   |
| Toshiba MQ04ABF100 1TB                              | 21        | 0.93%   |
| Seagate ST1000DM010-2EP102 1TB                      | 21        | 0.93%   |
| Samsung NVMe SSD Drive 512GB                        | 21        | 0.93%   |
| Unknown MMC Card  32GB                              | 20        | 0.89%   |
| HGST HTS721010A9E630 1TB                            | 20        | 0.89%   |
| SanDisk NVMe SSD Drive 256GB                        | 18        | 0.8%    |
| Samsung SSD 850 EVO 250GB                           | 18        | 0.8%    |
| Samsung SSD 860 EVO 500GB                           | 17        | 0.76%   |
| SanDisk NVMe SSD Drive 512GB                        | 16        | 0.71%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 14        | 0.62%   |
| Seagate ST500DM002-1BD142 500GB                     | 13        | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 13        | 0.58%   |
| Kingston SV300S37A240G 240GB SSD                    | 13        | 0.58%   |
| SK hynix NVMe SSD Drive 512GB                       | 12        | 0.53%   |
| Patriot Burst 120GB SSD                             | 12        | 0.53%   |
| Intel NVMe SSD Drive 512GB                          | 12        | 0.53%   |
| Toshiba DT01ACA050 500GB                            | 11        | 0.49%   |
| Seagate Expansion 4TB                               | 11        | 0.49%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 11        | 0.49%   |
| A-DATA SU650 240GB SSD                              | 11        | 0.49%   |
| Unknown MMC Card  64GB                              | 10        | 0.45%   |
| Samsung SSD 860 EVO 250GB                           | 10        | 0.45%   |
| Kingston SUV400S37120G 120GB SSD                    | 10        | 0.45%   |
| HGST HTS545050A7E680 500GB                          | 10        | 0.45%   |
| Toshiba MQ01ABD100 1TB                              | 9         | 0.4%    |
| Kingston RBUSNS8180DS3256GJ 256GB SSD               | 9         | 0.4%    |
| Kingston RBUSC180DS37256GJ 256GB SSD                | 9         | 0.4%    |
| HGST HTS541010A9E680 1TB                            | 9         | 0.4%    |
| WDC WD10SPZX-21Z10T0 1TB                            | 8         | 0.36%   |
| Samsung SSD 860 QVO 1TB                             | 8         | 0.36%   |
| Samsung SSD 850 EVO 500GB                           | 8         | 0.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 8         | 0.36%   |
| Kingston SUV500MS480G 480GB SSD                     | 8         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 315       | 472    | 34.81%  |
| WDC                 | 267       | 391    | 29.5%   |
| Toshiba             | 131       | 161    | 14.48%  |
| Hitachi             | 58        | 71     | 6.41%   |
| HGST                | 58        | 74     | 6.41%   |
| Samsung Electronics | 30        | 34     | 3.31%   |
| Maxtor              | 15        | 21     | 1.66%   |
| Unknown             | 7         | 8      | 0.77%   |
| Fujitsu             | 7         | 8      | 0.77%   |
| ASMT                | 5         | 5      | 0.55%   |
| Apple               | 3         | 4      | 0.33%   |
| IBM/Hitachi         | 2         | 2      | 0.22%   |
| Hewlett-Packard     | 2         | 3      | 0.22%   |
| LaCie               | 1         | 4      | 0.11%   |
| Intenso             | 1         | 1      | 0.11%   |
| HGST HTS            | 1         | 1      | 0.11%   |
| ExcelStor           | 1         | 1      | 0.11%   |
| ASMT109x            | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 219       | 293    | 32.4%   |
| Samsung Electronics | 123       | 166    | 18.2%   |
| A-DATA Technology   | 65        | 84     | 9.62%   |
| SanDisk             | 34        | 44     | 5.03%   |
| Intel               | 25        | 28     | 3.7%    |
| Crucial             | 24        | 30     | 3.55%   |
| WDC                 | 21        | 25     | 3.11%   |
| SK hynix            | 18        | 26     | 2.66%   |
| Patriot             | 18        | 21     | 2.66%   |
| Micron Technology   | 14        | 15     | 2.07%   |
| SPCC                | 12        | 14     | 1.78%   |
| Toshiba             | 9         | 9      | 1.33%   |
| OCZ                 | 9         | 16     | 1.33%   |
| FORESEE             | 9         | 10     | 1.33%   |
| Corsair             | 7         | 10     | 1.04%   |
| Kingmax             | 6         | 7      | 0.89%   |
| Hewlett-Packard     | 5         | 5      | 0.74%   |
| GOODRAM             | 5         | 5      | 0.74%   |
| Gigabyte Technology | 5         | 5      | 0.74%   |
| China               | 5         | 5      | 0.74%   |
| Transcend           | 4         | 6      | 0.59%   |
| Netac               | 4         | 6      | 0.59%   |
| Apacer              | 4         | 5      | 0.59%   |
| Verbatim            | 3         | 5      | 0.44%   |
| Team                | 3         | 3      | 0.44%   |
| LITEON              | 3         | 3      | 0.44%   |
| Emtec               | 3         | 3      | 0.44%   |
| Teclast             | 2         | 2      | 0.3%    |
| LITEONIT            | 2         | 2      | 0.3%    |
| Lite-On             | 2         | 2      | 0.3%    |
| W800S               | 1         | 1      | 0.15%   |
| Unknown             | 1         | 1      | 0.15%   |
| TO Exter            | 1         | 3      | 0.15%   |
| PNY                 | 1         | 2      | 0.15%   |
| OCZ-VERTEX3         | 1         | 1      | 0.15%   |
| Maxtor              | 1         | 1      | 0.15%   |
| Kston               | 1         | 5      | 0.15%   |
| KingDian            | 1         | 1      | 0.15%   |
| EDGE SE8            | 1         | 1      | 0.15%   |
| ASUS-PHISON         | 1         | 2      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 790       | 1262   | 41.62%  |
| SSD     | 614       | 877    | 32.35%  |
| NVMe    | 411       | 545    | 21.65%  |
| MMC     | 69        | 92     | 3.64%   |
| Unknown | 14        | 16     | 0.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1152      | 2076   | 68.13%  |
| NVMe | 411       | 544    | 24.31%  |
| MMC  | 69        | 92     | 4.08%   |
| SAS  | 59        | 80     | 3.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 894       | 1395   | 64.09%  |
| 0.51-1.0   | 379       | 506    | 27.17%  |
| 1.01-2.0   | 67        | 103    | 4.8%    |
| 3.01-4.0   | 26        | 41     | 1.86%   |
| 4.01-10.0  | 14        | 46     | 1%      |
| 2.01-3.0   | 12        | 43     | 0.86%   |
| 10.01-20.0 | 3         | 5      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 448       | 27.86%  |
| 251-500        | 359       | 22.33%  |
| 501-1000       | 245       | 15.24%  |
| 1-20           | 151       | 9.39%   |
| 51-100         | 114       | 7.09%   |
| 1001-2000      | 83        | 5.16%   |
| 21-50          | 78        | 4.85%   |
| Unknown        | 70        | 4.35%   |
| More than 3000 | 32        | 1.99%   |
| 2001-3000      | 28        | 1.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 668       | 40.34%  |
| 21-50          | 341       | 20.59%  |
| 101-250        | 177       | 10.69%  |
| 51-100         | 173       | 10.45%  |
| 251-500        | 94        | 5.68%   |
| 501-1000       | 78        | 4.71%   |
| Unknown        | 70        | 4.23%   |
| 1001-2000      | 37        | 2.23%   |
| More than 3000 | 12        | 0.72%   |
| 2001-3000      | 6         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Hitachi HTS725032A7E630 320GB            | 7         | 7      | 4.02%   |
| HGST HTS541010A9E680 1TB                 | 4         | 4      | 2.3%    |
| WDC WD5000AAKX-001CA0 500GB              | 3         | 3      | 1.72%   |
| WDC WD3200AAJS-60Z0A0 320GB              | 3         | 6      | 1.72%   |
| Seagate ST9500420AS 500GB                | 3         | 3      | 1.72%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 1.72%   |
| WDC WD5000AADS-00S9B0 500GB              | 2         | 2      | 1.15%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB SSD | 2         | 2      | 1.15%   |
| Seagate ST95005620AS 500GB               | 2         | 5      | 1.15%   |
| Seagate ST9500325AS 500GB                | 2         | 2      | 1.15%   |
| Seagate ST9160821AS 160GB                | 2         | 2      | 1.15%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 3      | 1.15%   |
| Seagate ST500DM002-1BD142 500GB          | 2         | 2      | 1.15%   |
| Seagate ST3500320AS 500GB                | 2         | 3      | 1.15%   |
| Seagate ST3500312CS 500GB                | 2         | 2      | 1.15%   |
| Seagate ST3250318AS 250GB                | 2         | 3      | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB           | 2         | 2      | 1.15%   |
| Seagate ST1000DM003-1SB102 1TB           | 2         | 2      | 1.15%   |
| OCZ ARC100 240GB SSD                     | 2         | 2      | 1.15%   |
| Maxtor STM3250310AS 250GB                | 2         | 3      | 1.15%   |
| Hitachi HTS545016B9A300 160GB            | 2         | 2      | 1.15%   |
| HGST HTS725050A7E630 500GB               | 2         | 2      | 1.15%   |
| Apacer 16GB SATA Flash Drive SSD         | 2         | 3      | 1.15%   |
| WDC WDS120G2G0A-00JH30 120GB SSD         | 1         | 1      | 0.57%   |
| WDC WD7500BPVT-60HXZT3 752GB             | 1         | 2      | 0.57%   |
| WDC WD7500BPVT-22HXZT3 752GB             | 1         | 1      | 0.57%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.57%   |
| WDC WD5000BPKT-60PK4T0 500GB             | 1         | 2      | 0.57%   |
| WDC WD5000BEVT-60A0RT0 500GB             | 1         | 1      | 0.57%   |
| WDC WD5000AAKX-22ERMA0 500GB             | 1         | 1      | 0.57%   |
| WDC WD5000AACS-00G8B1 500GB              | 1         | 3      | 0.57%   |
| WDC WD400EB-00CPF0 40GB                  | 1         | 1      | 0.57%   |
| WDC WD400BD-08JMC0 40GB                  | 1         | 1      | 0.57%   |
| WDC WD3200BPVT-22JJ5T0 320GB             | 1         | 1      | 0.57%   |
| WDC WD3200AVVS-63L2B0 320GB              | 1         | 1      | 0.57%   |
| WDC WD3200AVBS-63TAA0 320GB              | 1         | 1      | 0.57%   |
| WDC WD3200AAKS-75L9A0 320GB              | 1         | 1      | 0.57%   |
| WDC WD30PURX-64P6ZY0 3TB                 | 1         | 2      | 0.57%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 10     | 0.57%   |
| WDC WD30EFRX-68AX9N0 3TB                 | 1         | 1      | 0.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 56     | 25.3%   |
| WDC                 | 41        | 63     | 24.7%   |
| Hitachi             | 19        | 21     | 11.45%  |
| Samsung Electronics | 13        | 14     | 7.83%   |
| HGST                | 12        | 12     | 7.23%   |
| Toshiba             | 9         | 10     | 5.42%   |
| Maxtor              | 5         | 7      | 3.01%   |
| Kingston            | 4         | 4      | 2.41%   |
| SK hynix            | 3         | 3      | 1.81%   |
| OCZ                 | 2         | 2      | 1.2%    |
| Intel               | 2         | 2      | 1.2%    |
| Fujitsu             | 2         | 2      | 1.2%    |
| Apacer              | 2         | 3      | 1.2%    |
| Teclast             | 1         | 1      | 0.6%    |
| SanDisk             | 1         | 1      | 0.6%    |
| Plextor             | 1         | 1      | 0.6%    |
| Patriot             | 1         | 1      | 0.6%    |
| Micron Technology   | 1         | 1      | 0.6%    |
| LITEONIT            | 1         | 1      | 0.6%    |
| Hewlett-Packard     | 1         | 1      | 0.6%    |
| Crucial             | 1         | 1      | 0.6%    |
| Corsair             | 1         | 3      | 0.6%    |
| A-DATA Technology   | 1         | 1      | 0.6%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 56     | 30.43%  |
| WDC                 | 38        | 60     | 27.54%  |
| Hitachi             | 19        | 21     | 13.77%  |
| HGST                | 12        | 12     | 8.7%    |
| Samsung Electronics | 11        | 12     | 7.97%   |
| Toshiba             | 9         | 10     | 6.52%   |
| Maxtor              | 5         | 7      | 3.62%   |
| Fujitsu             | 2         | 2      | 1.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 128       | 180    | 82.05%  |
| SSD  | 27        | 30     | 17.31%  |
| NVMe | 1         | 1      | 0.64%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60KA9T0 320GB | 1         | 1      | 33.33%  |
| WDC WD2500BEVS-22UST0 250GB  | 1         | 1      | 33.33%  |
| Seagate ST3160215A 160GB     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 992       | 1741   | 60.45%  |
| Works    | 497       | 837    | 30.29%  |
| Malfunc  | 149       | 211    | 9.08%   |
| Failed   | 3         | 3      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1125      | 60.81%  |
| AMD                              | 235       | 12.7%   |
| Samsung Electronics              | 135       | 7.3%    |
| SanDisk                          | 74        | 4%      |
| Kingston Technology Company      | 47        | 2.54%   |
| SK hynix                         | 37        | 2%      |
| Micron Technology                | 20        | 1.08%   |
| Phison Electronics               | 18        | 0.97%   |
| ASMedia Technology               | 18        | 0.97%   |
| ADATA Technology                 | 16        | 0.86%   |
| Nvidia                           | 15        | 0.81%   |
| Marvell Technology Group         | 15        | 0.81%   |
| JMicron Technology               | 15        | 0.81%   |
| Toshiba America Info Systems     | 14        | 0.76%   |
| Realtek Semiconductor            | 11        | 0.59%   |
| KIOXIA                           | 11        | 0.59%   |
| Silicon Motion                   | 8         | 0.43%   |
| Lite-On Technology               | 5         | 0.27%   |
| VIA Technologies                 | 4         | 0.22%   |
| Silicon Integrated Systems [SiS] | 4         | 0.22%   |
| Silicon Image                    | 4         | 0.22%   |
| Micron/Crucial Technology        | 4         | 0.22%   |
| LSI Logic / Symbios Logic        | 4         | 0.22%   |
| Broadcom / LSI                   | 4         | 0.22%   |
| Solid State Storage Technology   | 2         | 0.11%   |
| Lenovo                           | 2         | 0.11%   |
| Seagate Technology               | 1         | 0.05%   |
| Integrated Technology Express    | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 171       | 7.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 96        | 4.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 89        | 4.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 66        | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 66        | 3.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 63        | 2.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 53        | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 46        | 2.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 45        | 2.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 39        | 1.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 39        | 1.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 33        | 1.54%   |
| AMD 400 Series Chipset SATA Controller                                         | 33        | 1.54%   |
| Samsung NVMe SSD Controller 980                                                | 32        | 1.49%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 32        | 1.49%   |
| Intel Volume Management Device NVMe RAID Controller                            | 30        | 1.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 29        | 1.35%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 29        | 1.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 28        | 1.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 28        | 1.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 27        | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 26        | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 25        | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 23        | 1.07%   |
| Kingston Company A2000 NVMe SSD                                                | 23        | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 23        | 1.07%   |
| Intel SSD 660P Series                                                          | 22        | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 22        | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 22        | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 21        | 0.98%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 20        | 0.93%   |
| Micron Non-Volatile memory controller                                          | 20        | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 20        | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 20        | 0.93%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 19        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 18        | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                          | 17        | 0.79%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 17        | 0.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 16        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 16        | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1117      | 58.64%  |
| NVMe | 420       | 22.05%  |
| IDE  | 212       | 11.13%  |
| RAID | 149       | 7.82%   |
| SAS  | 7         | 0.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1204      | 79.84%  |
| AMD    | 296       | 19.63%  |
| ARM    | 8         | 0.53%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 39        | 2.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 25        | 1.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 25        | 1.65%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 24        | 1.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 19        | 1.26%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 18        | 1.19%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 1.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 15        | 0.99%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 14        | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 14        | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 0.86%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 12        | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 0.79%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 11        | 0.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 0.73%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 10        | 0.66%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 10        | 0.66%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 10        | 0.66%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 9         | 0.6%    |
| Intel Core i3-8130U CPU @ 2.20GHz             | 9         | 0.6%    |
| Intel Core i3-7100U CPU @ 2.40GHz             | 9         | 0.6%    |
| Intel Core i3-4005U CPU @ 1.70GHz             | 9         | 0.6%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 9         | 0.6%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 9         | 0.6%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 8         | 0.53%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 8         | 0.53%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 8         | 0.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 0.53%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 8         | 0.53%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 8         | 0.53%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 0.53%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 7         | 0.46%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 7         | 0.46%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 0.46%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 7         | 0.46%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 7         | 0.46%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.46%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.46%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 7         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 296       | 19.62%  |
| Intel Core i5           | 290       | 19.22%  |
| Intel Core i3           | 165       | 10.93%  |
| Intel Celeron           | 130       | 8.61%   |
| Intel Core 2 Duo        | 78        | 5.17%   |
| AMD Ryzen 5             | 76        | 5.04%   |
| Other                   | 68        | 4.51%   |
| AMD Ryzen 7             | 62        | 4.11%   |
| Intel Pentium           | 50        | 3.31%   |
| Intel Atom              | 26        | 1.72%   |
| Intel Xeon              | 21        | 1.39%   |
| AMD Ryzen 3             | 21        | 1.39%   |
| Intel Pentium Dual-Core | 20        | 1.33%   |
| Intel Core 2 Quad       | 16        | 1.06%   |
| AMD A4                  | 15        | 0.99%   |
| AMD Ryzen 9             | 14        | 0.93%   |
| Intel Core 2            | 13        | 0.86%   |
| AMD FX                  | 11        | 0.73%   |
| AMD A8                  | 11        | 0.73%   |
| Intel Core i9           | 10        | 0.66%   |
| Intel Genuine           | 9         | 0.6%    |
| Intel Pentium Dual      | 8         | 0.53%   |
| AMD Phenom II X4        | 7         | 0.46%   |
| AMD E                   | 6         | 0.4%    |
| AMD Athlon              | 6         | 0.4%    |
| AMD Ryzen Threadripper  | 5         | 0.33%   |
| AMD E2                  | 5         | 0.33%   |
| Intel Celeron M         | 4         | 0.27%   |
| ARM BCM                 | 4         | 0.27%   |
| AMD Sempron             | 4         | 0.27%   |
| AMD Ryzen 7 PRO         | 4         | 0.27%   |
| AMD Athlon II X4        | 4         | 0.27%   |
| AMD Athlon 64 X2        | 3         | 0.2%    |
| Intel Pentium Silver    | 2         | 0.13%   |
| Intel Pentium Gold      | 2         | 0.13%   |
| Intel Pentium D         | 2         | 0.13%   |
| Intel Pentium 4         | 2         | 0.13%   |
| Intel Core Duo          | 2         | 0.13%   |
| Intel Core 2 Extreme    | 2         | 0.13%   |
| AMD V140                | 2         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 690       | 45.76%  |
| 4      | 529       | 35.08%  |
| 6      | 117       | 7.76%   |
| 8      | 94        | 6.23%   |
| 1      | 38        | 2.52%   |
| 12     | 13        | 0.86%   |
| 3      | 9         | 0.6%    |
| 16     | 4         | 0.27%   |
| 10     | 4         | 0.27%   |
| 32     | 3         | 0.2%    |
| 14     | 3         | 0.2%    |
| 24     | 2         | 0.13%   |
| 64     | 1         | 0.07%   |
| 20     | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1497      | 99.27%  |
| 2      | 11        | 0.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 959       | 63.55%  |
| 1      | 550       | 36.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1414      | 93.39%  |
| Unknown        | 87        | 5.75%   |
| 32-bit         | 13        | 0.86%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 275       | 17.76%  |
| 0x206a7    | 82        | 5.3%    |
| 0x306c3    | 77        | 4.97%   |
| 0x306a9    | 72        | 4.65%   |
| 0x1067a    | 59        | 3.81%   |
| 0x906ea    | 55        | 3.55%   |
| 0x806ea    | 55        | 3.55%   |
| 0x806ec    | 53        | 3.42%   |
| 0x706a1    | 48        | 3.1%    |
| 0x906e9    | 40        | 2.58%   |
| 0x40651    | 36        | 2.33%   |
| 0x506c9    | 34        | 2.2%    |
| 0x506e3    | 32        | 2.07%   |
| 0x20655    | 30        | 1.94%   |
| 0x806e9    | 28        | 1.81%   |
| 0x806c1    | 27        | 1.74%   |
| 0x306d4    | 26        | 1.68%   |
| 0x10676    | 25        | 1.61%   |
| 0x806eb    | 22        | 1.42%   |
| 0x406e3    | 22        | 1.42%   |
| 0x6fd      | 19        | 1.23%   |
| 0x706e5    | 18        | 1.16%   |
| 0x0a50000c | 18        | 1.16%   |
| 0x010000c8 | 17        | 1.1%    |
| 0x406c4    | 16        | 1.03%   |
| 0x08108109 | 16        | 1.03%   |
| 0x08108102 | 16        | 1.03%   |
| 0xa0652    | 13        | 0.84%   |
| 0x6fb      | 12        | 0.78%   |
| 0x0810100b | 12        | 0.78%   |
| 0x906ed    | 11        | 0.71%   |
| 0x06001119 | 11        | 0.71%   |
| 0x08701021 | 10        | 0.65%   |
| 0x08701013 | 10        | 0.65%   |
| 0x08600104 | 10        | 0.65%   |
| 0x0800820d | 10        | 0.65%   |
| 0x406c3    | 9         | 0.58%   |
| 0x30678    | 9         | 0.58%   |
| 0x806d1    | 8         | 0.52%   |
| 0x706a8    | 8         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 308       | 20.38%  |
| Haswell          | 138       | 9.13%   |
| SandyBridge      | 94        | 6.22%   |
| Penryn           | 90        | 5.96%   |
| IvyBridge        | 84        | 5.56%   |
| Skylake          | 66        | 4.37%   |
| Goldmont plus    | 63        | 4.17%   |
| Core             | 58        | 3.84%   |
| Zen+             | 57        | 3.77%   |
| Zen 2            | 51        | 3.38%   |
| Westmere         | 48        | 3.18%   |
| Silvermont       | 40        | 2.65%   |
| Goldmont         | 39        | 2.58%   |
| Zen              | 37        | 2.45%   |
| Broadwell        | 37        | 2.45%   |
| Zen 3            | 35        | 2.32%   |
| TigerLake        | 34        | 2.25%   |
| Unknown          | 33        | 2.18%   |
| IceLake          | 28        | 1.85%   |
| K10              | 27        | 1.79%   |
| CometLake        | 26        | 1.72%   |
| Piledriver       | 24        | 1.59%   |
| Excavator        | 14        | 0.93%   |
| P6               | 11        | 0.73%   |
| K8 Hammer        | 11        | 0.73%   |
| Nehalem          | 10        | 0.66%   |
| Bonnell          | 10        | 0.66%   |
| Bobcat           | 8         | 0.53%   |
| Puma             | 6         | 0.4%    |
| NetBurst         | 6         | 0.4%    |
| K10 Llano        | 4         | 0.26%   |
| Alderlake Hybrid | 4         | 0.26%   |
| K8 & K10 hybrid  | 3         | 0.2%    |
| Tremont          | 2         | 0.13%   |
| Steamroller      | 2         | 0.13%   |
| Jaguar           | 2         | 0.13%   |
| Bulldozer        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 978       | 52.64%  |
| Nvidia                           | 504       | 27.13%  |
| AMD                              | 364       | 19.59%  |
| Silicon Integrated Systems [SiS] | 4         | 0.22%   |
| ASPEED Technology                | 4         | 0.22%   |
| Matrox Electronics Systems       | 3         | 0.16%   |
| VIA Technologies                 | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 74        | 3.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 61        | 3.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 60        | 3.14%   |
| Intel UHD Graphics 620                                                                   | 51        | 2.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 48        | 2.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 46        | 2.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 44        | 2.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 40        | 2.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 39        | 2.04%   |
| Intel Core Processor Integrated Graphics Controller                                      | 35        | 1.83%   |
| Intel HD Graphics 620                                                                    | 34        | 1.78%   |
| Intel HD Graphics 5500                                                                   | 34        | 1.78%   |
| Intel HD Graphics 630                                                                    | 32        | 1.68%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 29        | 1.52%   |
| Intel HD Graphics 500                                                                    | 28        | 1.47%   |
| Intel HD Graphics 530                                                                    | 27        | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 1.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 1.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 24        | 1.26%   |
| AMD Renoir                                                                               | 23        | 1.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 1.15%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 21        | 1.1%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 20        | 1.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 20        | 1.05%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 20        | 1.05%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 1.05%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 17        | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 16        | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 16        | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.79%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 15        | 0.79%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 15        | 0.79%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 14        | 0.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 14        | 0.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 14        | 0.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 0.73%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 0.68%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 13        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 657       | 43.45%  |
| 1 x AMD        | 259       | 17.13%  |
| Intel + Nvidia | 257       | 17%     |
| 1 x Nvidia     | 214       | 14.15%  |
| Intel + AMD    | 53        | 3.51%   |
| AMD + Nvidia   | 32        | 2.12%   |
| 2 x AMD        | 19        | 1.26%   |
| Other          | 8         | 0.53%   |
| 1 x SiS        | 4         | 0.26%   |
| 1 x Matrox     | 3         | 0.2%    |
| 1 x ASPEED     | 3         | 0.2%    |
| 2 x Nvidia     | 1         | 0.07%   |
| 1 x VIA        | 1         | 0.07%   |
| AMD + ASPEED   | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1196      | 78.63%  |
| Proprietary | 282       | 18.54%  |
| Unknown     | 43        | 2.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 851       | 54.97%  |
| 1.01-2.0   | 218       | 14.08%  |
| 0.01-0.5   | 160       | 10.34%  |
| 3.01-4.0   | 121       | 7.82%   |
| 0.51-1.0   | 106       | 6.85%   |
| 7.01-8.0   | 45        | 2.91%   |
| 5.01-6.0   | 32        | 2.07%   |
| 2.01-3.0   | 9         | 0.58%   |
| 8.01-16.0  | 5         | 0.32%   |
| 16.01-24.0 | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 215       | 13.47%  |
| Samsung Electronics     | 194       | 12.16%  |
| Chimei Innolux          | 170       | 10.65%  |
| BOE                     | 167       | 10.46%  |
| LG Display              | 166       | 10.4%   |
| Dell                    | 106       | 6.64%   |
| Goldstar                | 70        | 4.39%   |
| Philips                 | 60        | 3.76%   |
| PANDA                   | 40        | 2.51%   |
| BenQ                    | 37        | 2.32%   |
| Chi Mei Optoelectronics | 32        | 2.01%   |
| Lenovo                  | 29        | 1.82%   |
| Sharp                   | 27        | 1.69%   |
| Acer                    | 27        | 1.69%   |
| Hewlett-Packard         | 26        | 1.63%   |
| AOC                     | 25        | 1.57%   |
| Ancor Communications    | 22        | 1.38%   |
| Fujitsu Siemens         | 18        | 1.13%   |
| ASUSTek Computer        | 14        | 0.88%   |
| LG Philips              | 11        | 0.69%   |
| LG Electronics          | 10        | 0.63%   |
| Apple                   | 10        | 0.63%   |
| Unknown                 | 9         | 0.56%   |
| KTC                     | 7         | 0.44%   |
| Vestel Elektronik       | 6         | 0.38%   |
| Sony                    | 6         | 0.38%   |
| Lenovo Group Limited    | 6         | 0.38%   |
| Eizo                    | 6         | 0.38%   |
| Toshiba                 | 5         | 0.31%   |
| Panasonic               | 5         | 0.31%   |
| InfoVision              | 5         | 0.31%   |
| CSO                     | 5         | 0.31%   |
| LGD                     | 4         | 0.25%   |
| Iiyama                  | 4         | 0.25%   |
| ViewSonic               | 3         | 0.19%   |
| HannStar                | 3         | 0.19%   |
| CPT                     | 3         | 0.19%   |
| Belinea                 | 3         | 0.19%   |
| Analogix                | 3         | 0.19%   |
| NAD                     | 2         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 26        | 1.59%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 21        | 1.28%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 18        | 1.1%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 18        | 1.1%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 15        | 0.92%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 12        | 0.73%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 12        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.67%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 10        | 0.61%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 10        | 0.61%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 9         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 9         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 9         | 0.55%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 8         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 8         | 0.49%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 8         | 0.49%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                  | 7         | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.43%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 7         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 7         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 7         | 0.43%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch     | 6         | 0.37%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 6         | 0.37%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 6         | 0.37%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 6         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 6         | 0.37%   |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                    | 6         | 0.37%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                    | 6         | 0.37%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.37%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 5         | 0.31%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 5         | 0.31%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 5         | 0.31%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 5         | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 5         | 0.31%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 5         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 703       | 45.8%   |
| 1366x768 (WXGA)    | 345       | 22.48%  |
| 1280x1024 (SXGA)   | 69        | 4.5%    |
| 3840x2160 (4K)     | 65        | 4.23%   |
| 1600x900 (HD+)     | 54        | 3.52%   |
| 2560x1440 (QHD)    | 44        | 2.87%   |
| 1680x1050 (WSXGA+) | 40        | 2.61%   |
| 1280x800 (WXGA)    | 35        | 2.28%   |
| 1440x900 (WXGA+)   | 27        | 1.76%   |
| 1920x1200 (WUXGA)  | 25        | 1.63%   |
| Unknown            | 15        | 0.98%   |
| 1360x768           | 13        | 0.85%   |
| 3200x1800 (QHD+)   | 11        | 0.72%   |
| 2560x1080          | 10        | 0.65%   |
| 3440x1440          | 9         | 0.59%   |
| 2880x1800          | 9         | 0.59%   |
| 1024x600           | 7         | 0.46%   |
| 3840x1080          | 6         | 0.39%   |
| 1024x768 (XGA)     | 6         | 0.39%   |
| 2560x1600          | 5         | 0.33%   |
| 2160x1440          | 5         | 0.33%   |
| 800x1280           | 4         | 0.26%   |
| 5120x1440          | 2         | 0.13%   |
| 3840x2400          | 2         | 0.13%   |
| 1600x1200          | 2         | 0.13%   |
| 1400x1050          | 2         | 0.13%   |
| 1280x720 (HD)      | 2         | 0.13%   |
| 800x600            | 1         | 0.07%   |
| 7680x1440          | 1         | 0.07%   |
| 6400x1440          | 1         | 0.07%   |
| 6000x1440          | 1         | 0.07%   |
| 3926x1440          | 1         | 0.07%   |
| 3840x1600          | 1         | 0.07%   |
| 3600x1200          | 1         | 0.07%   |
| 3286x1080          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2960x1050          | 1         | 0.07%   |
| 2720x1024          | 1         | 0.07%   |
| 2624x1200          | 1         | 0.07%   |
| 2288x1287          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 625       | 39.56%  |
| 14      | 114       | 7.22%   |
| 13      | 104       | 6.58%   |
| 17      | 97        | 6.14%   |
| 24      | 96        | 6.08%   |
| 23      | 84        | 5.32%   |
| 21      | 82        | 5.19%   |
| Unknown | 71        | 4.49%   |
| 27      | 68        | 4.3%    |
| 19      | 46        | 2.91%   |
| 22      | 27        | 1.71%   |
| 18      | 26        | 1.65%   |
| 31      | 18        | 1.14%   |
| 34      | 17        | 1.08%   |
| 12      | 16        | 1.01%   |
| 84      | 14        | 0.89%   |
| 20      | 11        | 0.7%    |
| 54      | 8         | 0.51%   |
| 10      | 8         | 0.51%   |
| 72      | 6         | 0.38%   |
| 32      | 5         | 0.32%   |
| 16      | 5         | 0.32%   |
| 65      | 4         | 0.25%   |
| 11      | 4         | 0.25%   |
| 40      | 3         | 0.19%   |
| 28      | 3         | 0.19%   |
| 26      | 3         | 0.19%   |
| 52      | 2         | 0.13%   |
| 25      | 2         | 0.13%   |
| 8       | 2         | 0.13%   |
| 142     | 1         | 0.06%   |
| 49      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 47      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |
| 43      | 1         | 0.06%   |
| 42      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |
| 29      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 811       | 51.85%  |
| 501-600        | 234       | 14.96%  |
| 401-500        | 155       | 9.91%   |
| 351-400        | 122       | 7.8%    |
| 201-300        | 74        | 4.73%   |
| Unknown        | 71        | 4.54%   |
| 601-700        | 28        | 1.79%   |
| 701-800        | 22        | 1.41%   |
| 1501-2000      | 20        | 1.28%   |
| 1001-1500      | 18        | 1.15%   |
| 801-900        | 4         | 0.26%   |
| 101-200        | 2         | 0.13%   |
| 901-1000       | 2         | 0.13%   |
| More than 2000 | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1160      | 78.8%   |
| 16/10   | 140       | 9.51%   |
| 5/4     | 60        | 4.08%   |
| Unknown | 58        | 3.94%   |
| 21/9    | 20        | 1.36%   |
| 4/3     | 13        | 0.88%   |
| 3/2     | 10        | 0.68%   |
| 6/5     | 5         | 0.34%   |
| 0.62    | 4         | 0.27%   |
| 32/9    | 1         | 0.07%   |
| 1.00    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 625       | 39.81%  |
| 201-250        | 232       | 14.78%  |
| 81-90          | 182       | 11.59%  |
| 151-200        | 85        | 5.41%   |
| 301-350        | 71        | 4.52%   |
| Unknown        | 71        | 4.52%   |
| 121-130        | 63        | 4.01%   |
| 141-150        | 46        | 2.93%   |
| 351-500        | 41        | 2.61%   |
| More than 1000 | 36        | 2.29%   |
| 71-80          | 34        | 2.17%   |
| 251-300        | 31        | 1.97%   |
| 61-70          | 14        | 0.89%   |
| 131-140        | 9         | 0.57%   |
| 501-1000       | 9         | 0.57%   |
| 41-50          | 8         | 0.51%   |
| 51-60          | 4         | 0.25%   |
| 91-100         | 4         | 0.25%   |
| 111-120        | 3         | 0.19%   |
| 1-40           | 2         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 467       | 30.11%  |
| 101-120       | 463       | 29.85%  |
| 51-100        | 437       | 28.18%  |
| Unknown       | 71        | 4.58%   |
| 161-240       | 57        | 3.68%   |
| More than 240 | 29        | 1.87%   |
| 1-50          | 27        | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1306      | 84.92%  |
| 2     | 159       | 10.34%  |
| 0     | 52        | 3.38%   |
| 3     | 20        | 1.3%    |
| 4     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 860       | 39.04%  |
| Intel                             | 659       | 29.91%  |
| Qualcomm Atheros                  | 262       | 11.89%  |
| Broadcom                          | 126       | 5.72%   |
| TP-Link                           | 47        | 2.13%   |
| MediaTek                          | 33        | 1.5%    |
| Ralink                            | 23        | 1.04%   |
| Broadcom Limited                  | 22        | 1%      |
| Marvell Technology Group          | 21        | 0.95%   |
| Ralink Technology                 | 18        | 0.82%   |
| Nvidia                            | 14        | 0.64%   |
| ASUSTek Computer                  | 11        | 0.5%    |
| Huawei Technologies               | 8         | 0.36%   |
| Samsung Electronics               | 7         | 0.32%   |
| D-Link                            | 7         | 0.32%   |
| Xiaomi                            | 6         | 0.27%   |
| Qualcomm Atheros Communications   | 6         | 0.27%   |
| Ericsson Business Mobile Networks | 6         | 0.27%   |
| Microsoft                         | 5         | 0.23%   |
| Hewlett-Packard                   | 5         | 0.23%   |
| ASIX Electronics                  | 5         | 0.23%   |
| Aquantia                          | 5         | 0.23%   |
| ZTE WCDMA Technologies MSM        | 4         | 0.18%   |
| JMicron Technology                | 4         | 0.18%   |
| VIA Technologies                  | 3         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.14%   |
| Standard Microsystems             | 2         | 0.09%   |
| Lenovo                            | 2         | 0.09%   |
| IMC Networks                      | 2         | 0.09%   |
| Giga-Byte Technology              | 2         | 0.09%   |
| Fibocom                           | 2         | 0.09%   |
| Edimax Technology                 | 2         | 0.09%   |
| Dell                              | 2         | 0.09%   |
| D-Link System                     | 2         | 0.09%   |
| Belkin Components                 | 2         | 0.09%   |
| U-Blox                            | 1         | 0.05%   |
| Sierra Wireless                   | 1         | 0.05%   |
| QLogic                            | 1         | 0.05%   |
| Qcom                              | 1         | 0.05%   |
| NetGear                           | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 564       | 21.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 113       | 4.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 70        | 2.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 54        | 2.1%    |
| Intel Wireless 8265 / 8275                                        | 53        | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 53        | 2.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 51        | 1.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 44        | 1.71%   |
| Intel Wi-Fi 6 AX200                                               | 41        | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 38        | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 35        | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 34        | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 32        | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 30        | 1.17%   |
| Intel I211 Gigabit Network Connection                             | 29        | 1.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27        | 1.05%   |
| Intel Wi-Fi 6 AX201                                               | 27        | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 26        | 1.01%   |
| Intel Wireless 7260                                               | 24        | 0.93%   |
| Intel Wireless 7265                                               | 23        | 0.89%   |
| Intel Ethernet Connection I217-LM                                 | 23        | 0.89%   |
| Intel Wireless 8260                                               | 20        | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 20        | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 19        | 0.74%   |
| Intel Wireless 3165                                               | 19        | 0.74%   |
| Intel Wireless 3160                                               | 19        | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 19        | 0.74%   |
| Intel Ethernet Connection (2) I219-V                              | 18        | 0.7%    |
| Broadcom BCM43142 802.11b/g/n                                     | 18        | 0.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 0.66%   |
| Realtek 802.11n WLAN Adapter                                      | 17        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 16        | 0.62%   |
| Intel Centrino Advanced-N 6200                                    | 16        | 0.62%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 16        | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 14        | 0.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 13        | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 13        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 502       | 41.52%  |
| Realtek Semiconductor           | 251       | 20.76%  |
| Qualcomm Atheros                | 211       | 17.45%  |
| Broadcom                        | 82        | 6.78%   |
| TP-Link                         | 40        | 3.31%   |
| MediaTek                        | 28        | 2.32%   |
| Ralink                          | 23        | 1.9%    |
| Ralink Technology               | 18        | 1.49%   |
| Broadcom Limited                | 12        | 0.99%   |
| ASUSTek Computer                | 11        | 0.91%   |
| Qualcomm Atheros Communications | 6         | 0.5%    |
| Microsoft                       | 5         | 0.41%   |
| D-Link                          | 5         | 0.41%   |
| IMC Networks                    | 2         | 0.17%   |
| Fibocom                         | 2         | 0.17%   |
| Edimax Technology               | 2         | 0.17%   |
| Belkin Components               | 2         | 0.17%   |
| Sierra Wireless                 | 1         | 0.08%   |
| Qcom                            | 1         | 0.08%   |
| NetGear                         | 1         | 0.08%   |
| Micro Star International        | 1         | 0.08%   |
| Mercucys                        | 1         | 0.08%   |
| D-Link System                   | 1         | 0.08%   |
| Belkin                          | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 70        | 5.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 54        | 4.44%   |
| Intel Wireless 8265 / 8275                                              | 53        | 4.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 51        | 4.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 44        | 3.62%   |
| Intel Wi-Fi 6 AX200                                                     | 41        | 3.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 38        | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 35        | 2.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 34        | 2.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 32        | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 30        | 2.47%   |
| Intel Wi-Fi 6 AX201                                                     | 27        | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 26        | 2.14%   |
| Intel Wireless 7260                                                     | 24        | 1.97%   |
| Intel Wireless 7265                                                     | 23        | 1.89%   |
| Intel Wireless 8260                                                     | 20        | 1.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 20        | 1.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 19        | 1.56%   |
| Intel Wireless 3165                                                     | 19        | 1.56%   |
| Intel Wireless 3160                                                     | 19        | 1.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 19        | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                           | 18        | 1.48%   |
| Realtek 802.11n WLAN Adapter                                            | 17        | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 1.32%   |
| Intel Centrino Advanced-N 6200                                          | 16        | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 14        | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 13        | 1.07%   |
| Ralink MT7601U Wireless Adapter                                         | 10        | 0.82%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 10        | 0.82%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 9         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 0.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.74%   |
| Intel Centrino Ultimate-N 6300                                          | 9         | 0.74%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 0.58%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 7         | 0.58%   |
| Intel Centrino Advanced-N 6235                                          | 7         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 733       | 56.08%  |
| Intel                            | 319       | 24.41%  |
| Qualcomm Atheros                 | 80        | 6.12%   |
| Broadcom                         | 64        | 4.9%    |
| Marvell Technology Group         | 21        | 1.61%   |
| Nvidia                           | 14        | 1.07%   |
| Broadcom Limited                 | 10        | 0.77%   |
| TP-Link                          | 7         | 0.54%   |
| Samsung Electronics              | 7         | 0.54%   |
| Xiaomi                           | 6         | 0.46%   |
| Huawei Technologies              | 6         | 0.46%   |
| MediaTek                         | 5         | 0.38%   |
| ASIX Electronics                 | 5         | 0.38%   |
| Aquantia                         | 5         | 0.38%   |
| JMicron Technology               | 4         | 0.31%   |
| VIA Technologies                 | 3         | 0.23%   |
| Silicon Integrated Systems [SiS] | 3         | 0.23%   |
| Standard Microsystems            | 2         | 0.15%   |
| Lenovo                           | 2         | 0.15%   |
| Giga-Byte Technology             | 2         | 0.15%   |
| D-Link                           | 2         | 0.15%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.08%   |
| QLogic                           | 1         | 0.08%   |
| HMD Global                       | 1         | 0.08%   |
| Google                           | 1         | 0.08%   |
| DisplayLink                      | 1         | 0.08%   |
| D-Link System                    | 1         | 0.08%   |
| 3Com                             | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 564       | 42.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 113       | 8.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 53        | 3.99%   |
| Intel I211 Gigabit Network Connection                             | 29        | 2.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27        | 2.03%   |
| Intel Ethernet Connection I217-LM                                 | 23        | 1.73%   |
| Intel Ethernet Connection (2) I219-V                              | 18        | 1.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 1.2%    |
| Intel 82577LM Gigabit Network Connection                          | 16        | 1.2%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 13        | 0.98%   |
| Intel Ethernet Connection (7) I219-V                              | 12        | 0.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 0.9%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.6%    |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.6%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 8         | 0.6%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.53%   |
| Nvidia MCP61 Ethernet                                             | 7         | 0.53%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 0.53%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 0.53%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.53%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 7         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.45%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 6         | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 6         | 0.45%   |
| Huawei STK-L21                                                    | 6         | 0.45%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 6         | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.38%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1240      | 51.16%  |
| WiFi     | 1158      | 47.77%  |
| Modem    | 20        | 0.83%   |
| Unknown  | 6         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 931       | 59.6%   |
| Ethernet | 629       | 40.27%  |
| Unknown  | 2         | 0.13%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 816       | 54.04%  |
| 1     | 632       | 41.85%  |
| 0     | 32        | 2.12%   |
| 3     | 26        | 1.72%   |
| 4     | 3         | 0.2%    |
| 6     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1329      | 86.41%  |
| Yes  | 209       | 13.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 393       | 42.12%  |
| IMC Networks                    | 129       | 13.83%  |
| Realtek Semiconductor           | 106       | 11.36%  |
| Qualcomm Atheros Communications | 68        | 7.29%   |
| Lite-On Technology              | 44        | 4.72%   |
| Broadcom                        | 39        | 4.18%   |
| Cambridge Silicon Radio         | 29        | 3.11%   |
| ASUSTek Computer                | 23        | 2.47%   |
| Foxconn / Hon Hai               | 18        | 1.93%   |
| Dell                            | 18        | 1.93%   |
| Hewlett-Packard                 | 13        | 1.39%   |
| Toshiba                         | 10        | 1.07%   |
| Apple                           | 10        | 1.07%   |
| Ralink                          | 9         | 0.96%   |
| MediaTek                        | 5         | 0.54%   |
| Realtek                         | 3         | 0.32%   |
| Alps Electric                   | 3         | 0.32%   |
| SINO WEALTH                     | 2         | 0.21%   |
| Integrated System Solution      | 2         | 0.21%   |
| Chicony Electronics             | 2         | 0.21%   |
| Unknown                         | 1         | 0.11%   |
| Ralink Technology               | 1         | 0.11%   |
| Opticis                         | 1         | 0.11%   |
| Micro Star International        | 1         | 0.11%   |
| Foxconn International           | 1         | 0.11%   |
| Conwise Technology              | 1         | 0.11%   |
| Askey Computer                  | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 163       | 17.47%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 83        | 8.9%    |
| IMC Networks Bluetooth Radio                        | 82        | 8.79%   |
| Realtek Bluetooth Radio                             | 80        | 8.57%   |
| Intel AX201 Bluetooth                               | 68        | 7.29%   |
| Intel AX200 Bluetooth                               | 40        | 4.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 38        | 4.07%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 29        | 3.11%   |
| IMC Networks Bluetooth Device                       | 26        | 2.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 21        | 2.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 1.93%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 17        | 1.82%   |
| IMC Networks Wireless_Device                        | 15        | 1.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 1.18%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.96%   |
| Lite-On Bluetooth Device                            | 9         | 0.96%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 0.96%   |
| Dell DW375 Bluetooth Module                         | 9         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.86%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 0.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 0.86%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 0.75%   |
| Broadcom BCM2045A0                                  | 7         | 0.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 0.64%   |
| MediaTek Wireless_Device                            | 5         | 0.54%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 5         | 0.54%   |
| Intel AX210 Bluetooth                               | 5         | 0.54%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 0.54%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.54%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.54%   |
| Toshiba Bluetooth Device                            | 4         | 0.43%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 4         | 0.43%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.43%   |
| Realtek Bluetooth Radio                             | 3         | 0.32%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.32%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 0.32%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 3         | 0.32%   |
| Dell Wireless 365 Bluetooth                         | 3         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1164      | 58.76%  |
| AMD                                          | 339       | 17.11%  |
| Nvidia                                       | 319       | 16.1%   |
| C-Media Electronics                          | 31        | 1.56%   |
| Creative Labs                                | 20        | 1.01%   |
| Logitech                                     | 11        | 0.56%   |
| GN Netcom                                    | 9         | 0.45%   |
| Creative Technology                          | 7         | 0.35%   |
| Kingston Technology                          | 5         | 0.25%   |
| Giga-Byte Technology                         | 5         | 0.25%   |
| Trust                                        | 4         | 0.2%    |
| Texas Instruments                            | 4         | 0.2%    |
| Silicon Integrated Systems [SiS]             | 4         | 0.2%    |
| Realtek Semiconductor                        | 4         | 0.2%    |
| ASUSTek Computer                             | 4         | 0.2%    |
| VIA Technologies                             | 3         | 0.15%   |
| Sennheiser Communications                    | 3         | 0.15%   |
| Plantronics                                  | 3         | 0.15%   |
| XMOS                                         | 2         | 0.1%    |
| Tenx Technology                              | 2         | 0.1%    |
| Razer USA                                    | 2         | 0.1%    |
| Lenovo                                       | 2         | 0.1%    |
| JMTek                                        | 2         | 0.1%    |
| GYROCOM C&C                                  | 2         | 0.1%    |
| Generalplus Technology                       | 2         | 0.1%    |
| DSEA A/S                                     | 2         | 0.1%    |
| Dell                                         | 2         | 0.1%    |
| Corsair                                      | 2         | 0.1%    |
| Audio-Technica                               | 2         | 0.1%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.05%   |
| Unknown                                      | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.05%   |
| TEAC                                         | 1         | 0.05%   |
| Studiologic                                  | 1         | 0.05%   |
| Sony                                         | 1         | 0.05%   |
| Samson Technologies                          | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)                | 1         | 0.05%   |
| Nam Tai E&E Products                         | 1         | 0.05%   |
| KTMicro                                      | 1         | 0.05%   |
| iCreate Technologies                         | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 122       | 5.21%   |
| Intel Sunrise Point-LP HD Audio                                            | 117       | 4.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 90        | 3.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 82        | 3.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 79        | 3.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 72        | 3.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 66        | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 63        | 2.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 63        | 2.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 54        | 2.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 53        | 2.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 52        | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 50        | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                      | 48        | 2.05%   |
| Intel 8 Series HD Audio Controller                                         | 47        | 2.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 47        | 2.01%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 47        | 2.01%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 41        | 1.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 39        | 1.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 38        | 1.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 35        | 1.49%   |
| Intel Broadwell-U Audio Controller                                         | 35        | 1.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 34        | 1.45%   |
| AMD Starship/Matisse HD Audio Controller                                   | 34        | 1.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 32        | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                              | 31        | 1.32%   |
| AMD FCH Azalia Controller                                                  | 31        | 1.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 30        | 1.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 29        | 1.24%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 27        | 1.15%   |
| Intel 200 Series PCH HD Audio                                              | 27        | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                            | 24        | 1.02%   |
| Intel Comet Lake PCH-LP cAVS                                               | 23        | 0.98%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 20        | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 19        | 0.81%   |
| Intel Comet Lake PCH cAVS                                                  | 19        | 0.81%   |
| Intel CM238 HD Audio Controller                                            | 19        | 0.81%   |
| Nvidia High Definition Audio Controller                                    | 17        | 0.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 17        | 0.73%   |
| Nvidia GP104 High Definition Audio Controller                              | 16        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 174       | 21.67%  |
| SK hynix                     | 143       | 17.81%  |
| Kingston                     | 121       | 15.07%  |
| Micron Technology            | 76        | 9.46%   |
| Unknown                      | 71        | 8.84%   |
| Corsair                      | 60        | 7.47%   |
| Ramaxel Technology           | 24        | 2.99%   |
| Crucial                      | 22        | 2.74%   |
| A-DATA Technology            | 20        | 2.49%   |
| Nanya Technology             | 17        | 2.12%   |
| Elpida                       | 17        | 2.12%   |
| G.Skill                      | 10        | 1.25%   |
| Kingmax                      | 8         | 1%      |
| Unknown (ABCD)               | 7         | 0.87%   |
| Unknown                      | 7         | 0.87%   |
| Patriot                      | 4         | 0.5%    |
| Apacer                       | 3         | 0.37%   |
| Transcend                    | 2         | 0.25%   |
| Silicon Power                | 2         | 0.25%   |
| Qimonda                      | 2         | 0.25%   |
| GOODRAM                      | 2         | 0.25%   |
| Unknown (0x7FDA000000000000) | 1         | 0.12%   |
| Unknown (0B45)               | 1         | 0.12%   |
| TakeMS                       | 1         | 0.12%   |
| SK_Hynix                     | 1         | 0.12%   |
| SHARETRONIC                  | 1         | 0.12%   |
| S                            | 1         | 0.12%   |
| Kingmax Semiconductor        | 1         | 0.12%   |
| H                            | 1         | 0.12%   |
| Exceleram                    | 1         | 0.12%   |
| Avant                        | 1         | 0.12%   |
| ASint Technology             | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 1.24%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.24%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 10        | 1.13%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 1.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.13%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 1.02%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 0.79%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s              | 7         | 0.79%   |
| Unknown                                                          | 7         | 0.79%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 6         | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.68%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.68%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.68%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.68%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 5         | 0.56%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.56%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 5         | 0.56%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.56%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                | 5         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.45%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 4         | 0.45%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.45%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.45%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 4         | 0.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.45%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s          | 4         | 0.45%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 3         | 0.34%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 3         | 0.34%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 3         | 0.34%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 3         | 0.34%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.34%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.34%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.34%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.34%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.34%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 3         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 323       | 46.95%  |
| DDR3    | 233       | 33.87%  |
| DDR2    | 49        | 7.12%   |
| SDRAM   | 26        | 3.78%   |
| Unknown | 20        | 2.91%   |
| LPDDR4  | 15        | 2.18%   |
| LPDDR3  | 11        | 1.6%    |
| DDR5    | 5         | 0.73%   |
| DDR     | 4         | 0.58%   |
| LPDDR5  | 1         | 0.15%   |
| DRAM    | 1         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 416       | 61.72%  |
| DIMM         | 227       | 33.68%  |
| Row Of Chips | 26        | 3.86%   |
| Chip         | 3         | 0.45%   |
| RIMM         | 1         | 0.15%   |
| FB-DIMM      | 1         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 266       | 35.95%  |
| 4096  | 216       | 29.19%  |
| 2048  | 104       | 14.05%  |
| 16384 | 91        | 12.3%   |
| 1024  | 46        | 6.22%   |
| 32768 | 13        | 1.76%   |
| 512   | 4         | 0.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 150       | 19.66%  |
| 2667    | 122       | 15.99%  |
| 3200    | 99        | 12.98%  |
| 2400    | 73        | 9.57%   |
| 1333    | 52        | 6.82%   |
| 1334    | 36        | 4.72%   |
| 2133    | 29        | 3.8%    |
| 800     | 28        | 3.67%   |
| 667     | 25        | 3.28%   |
| Unknown | 16        | 2.1%    |
| 3600    | 15        | 1.97%   |
| 3266    | 11        | 1.44%   |
| 3400    | 8         | 1.05%   |
| 1067    | 8         | 1.05%   |
| 975     | 8         | 1.05%   |
| 4267    | 6         | 0.79%   |
| 1867    | 6         | 0.79%   |
| 4800    | 5         | 0.66%   |
| 3000    | 5         | 0.66%   |
| 1066    | 5         | 0.66%   |
| 533     | 5         | 0.66%   |
| 2933    | 4         | 0.52%   |
| 2048    | 4         | 0.52%   |
| 4199    | 3         | 0.39%   |
| 3866    | 3         | 0.39%   |
| 2800    | 3         | 0.39%   |
| 2666    | 3         | 0.39%   |
| 1866    | 3         | 0.39%   |
| 400     | 3         | 0.39%   |
| 4266    | 2         | 0.26%   |
| 3733    | 2         | 0.26%   |
| 3500    | 2         | 0.26%   |
| 3466    | 2         | 0.26%   |
| 1800    | 2         | 0.26%   |
| 1639    | 2         | 0.26%   |
| 49926   | 1         | 0.13%   |
| 8192    | 1         | 0.13%   |
| 6400    | 1         | 0.13%   |
| 3334    | 1         | 0.13%   |
| 3151    | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 12        | 24.49%  |
| Canon                 | 9         | 18.37%  |
| Brother Industries    | 8         | 16.33%  |
| Seiko Epson           | 7         | 14.29%  |
| Samsung Electronics   | 7         | 14.29%  |
| Xerox                 | 2         | 4.08%   |
| Zebra                 | 1         | 2.04%   |
| QinHeng Electronics   | 1         | 2.04%   |
| Lexmark International | 1         | 2.04%   |
| ATEN International    | 1         | 2.04%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson L3150 Series                      | 2         | 4.08%   |
| Seiko Epson L3110 Series                      | 2         | 4.08%   |
| Samsung M2070 Series                          | 2         | 4.08%   |
| Samsung Composite Device                      | 2         | 4.08%   |
| Canon MF4010 series                           | 2         | 4.08%   |
| Brother HL-1110 series                        | 2         | 4.08%   |
| Zebra GK420t Label Printer                    | 1         | 2.04%   |
| Xerox Phaser 6130N                            | 1         | 2.04%   |
| Xerox Phaser 3020                             | 1         | 2.04%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 2.04%   |
| Seiko Epson ET-3750 Series                    | 1         | 2.04%   |
| Seiko Epson ET-2600 Series                    | 1         | 2.04%   |
| Samsung ML-216x Series Laser Printer          | 1         | 2.04%   |
| Samsung M2020 Series                          | 1         | 2.04%   |
| Samsung CLP-310 Color Laser Printer           | 1         | 2.04%   |
| QinHeng CH340S                                | 1         | 2.04%   |
| Lexmark International InkJet Color Printer    | 1         | 2.04%   |
| HP LaserJet M14-M17                           | 1         | 2.04%   |
| HP LaserJet 3050                              | 1         | 2.04%   |
| HP LaserJet 1022                              | 1         | 2.04%   |
| HP LaserJet 1018                              | 1         | 2.04%   |
| HP Laser 107a                                 | 1         | 2.04%   |
| HP Deskjet F4500 series                       | 1         | 2.04%   |
| HP DeskJet F2492 All-in-One                   | 1         | 2.04%   |
| HP Deskjet 3050A                              | 1         | 2.04%   |
| HP DeskJet 2700 series                        | 1         | 2.04%   |
| HP DeskJet 2300 series                        | 1         | 2.04%   |
| HP DeskJet 2130 series                        | 1         | 2.04%   |
| HP Deskjet 2050 J510                          | 1         | 2.04%   |
| Canon PIXMA MP280                             | 1         | 2.04%   |
| Canon PIXMA MP250                             | 1         | 2.04%   |
| Canon MF4320-4350                             | 1         | 2.04%   |
| Canon MF3200 series                           | 1         | 2.04%   |
| Canon MF3110                                  | 1         | 2.04%   |
| Canon iP7200 series                           | 1         | 2.04%   |
| Canon CanoScan LiDE 300                       | 1         | 2.04%   |
| Brother MFC-7420                              | 1         | 2.04%   |
| Brother HL-5380DN series                      | 1         | 2.04%   |
| Brother HL-5250DN Printer                     | 1         | 2.04%   |
| Brother HL-1210W series                       | 1         | 2.04%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 225       | 22.66%  |
| Chicony Electronics                    | 196       | 19.74%  |
| Realtek Semiconductor                  | 87        | 8.76%   |
| Microdia                               | 74        | 7.45%   |
| Acer                                   | 67        | 6.75%   |
| Sunplus Innovation Technology          | 54        | 5.44%   |
| Quanta                                 | 43        | 4.33%   |
| Syntek                                 | 25        | 2.52%   |
| Cheng Uei Precision Industry (Foxlink) | 25        | 2.52%   |
| Alcor Micro                            | 23        | 2.32%   |
| Lite-On Technology                     | 21        | 2.11%   |
| Suyin                                  | 19        | 1.91%   |
| Logitech                               | 19        | 1.91%   |
| Sonix Technology                       | 12        | 1.21%   |
| Apple                                  | 12        | 1.21%   |
| Samsung Electronics                    | 10        | 1.01%   |
| Ricoh                                  | 9         | 0.91%   |
| Microsoft                              | 9         | 0.91%   |
| Silicon Motion                         | 7         | 0.7%    |
| Luxvisions Innotech Limited            | 7         | 0.7%    |
| Z-Star Microelectronics                | 6         | 0.6%    |
| OmniVision Technologies                | 5         | 0.5%    |
| ALi                                    | 4         | 0.4%    |
| Lenovo                                 | 3         | 0.3%    |
| GEMBIRD                                | 3         | 0.3%    |
| Cubeternet                             | 3         | 0.3%    |
| Sunplus Technology                     | 2         | 0.2%    |
| Primax Electronics                     | 2         | 0.2%    |
| Jieli Technology                       | 2         | 0.2%    |
| Importek                               | 2         | 0.2%    |
| Genesys Logic                          | 2         | 0.2%    |
| Aveo Technology                        | 2         | 0.2%    |
| WaveRider Communications               | 1         | 0.1%    |
| Unknown                                | 1         | 0.1%    |
| Trust                                  | 1         | 0.1%    |
| Philips (or NXP)                       | 1         | 0.1%    |
| Novatek Microelectronics               | 1         | 0.1%    |
| KYE Systems (Mouse Systems)            | 1         | 0.1%    |
| Jeilin Technology                      | 1         | 0.1%    |
| Huawei Technologies                    | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam            | 101       | 10.15%  |
| IMC Networks USB2.0 HD UVC WebCam             | 68        | 6.83%   |
| Chicony Integrated Camera                     | 40        | 4.02%   |
| Realtek Integrated_Webcam_HD                  | 33        | 3.32%   |
| IMC Networks Integrated Camera                | 22        | 2.21%   |
| Acer Integrated Camera                        | 22        | 2.21%   |
| Microdia Integrated_Webcam_HD                 | 19        | 1.91%   |
| Chicony USB2.0 VGA UVC WebCam                 | 16        | 1.61%   |
| Chicony HD Webcam                             | 15        | 1.51%   |
| Syntek Integrated Camera                      | 13        | 1.31%   |
| Chicony USB2.0 HD UVC WebCam                  | 13        | 1.31%   |
| Realtek USB Camera                            | 11        | 1.11%   |
| Microdia USB 2.0 Camera                       | 11        | 1.11%   |
| Sunplus HD WebCam                             | 10        | 1.01%   |
| Samsung Galaxy A5 (MTP)                       | 10        | 1.01%   |
| Acer Lenovo EasyCamera                        | 10        | 1.01%   |
| Sonix USB2.0 HD UVC WebCam                    | 9         | 0.9%    |
| Quanta VGA WebCam                             | 9         | 0.9%    |
| Chicony TOSHIBA Web Camera - HD               | 9         | 0.9%    |
| Microdia Integrated Webcam                    | 8         | 0.8%    |
| Lite-On Integrated Camera                     | 8         | 0.8%    |
| Chicony HP Webcam                             | 8         | 0.8%    |
| Chicony EasyCamera                            | 8         | 0.8%    |
| Alcor Micro USB 2.0 PC Camera                 | 8         | 0.8%    |
| Acer SunplusIT Integrated Camera              | 8         | 0.8%    |
| Acer EasyCamera                               | 8         | 0.8%    |
| Sunplus Integrated_Webcam_HD                  | 7         | 0.7%    |
| Realtek USB2.0 HD UVC WebCam                  | 7         | 0.7%    |
| Microsoft LifeCam HD-3000                     | 7         | 0.7%    |
| Microdia Camera                               | 7         | 0.7%    |
| IMC Networks USB2.0 UVC HD Webcam             | 7         | 0.7%    |
| Chicony VGA WebCam                            | 7         | 0.7%    |
| Syntek EasyCamera                             | 6         | 0.6%    |
| Sunplus ASUS Webcam                           | 6         | 0.6%    |
| Realtek Lenovo EasyCamera                     | 6         | 0.6%    |
| Chicony HP HD Webcam                          | 6         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) Webcam | 6         | 0.6%    |
| Alcor Micro USB 2.0 Camera                    | 6         | 0.6%    |
| Syntek Lenovo EasyCamera                      | 5         | 0.5%    |
| Sunplus Laptop_Integrated_Webcam_FHD          | 5         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 52        | 36.11%  |
| Synaptics                  | 38        | 26.39%  |
| Shenzhen Goodix Technology | 17        | 11.81%  |
| Upek                       | 11        | 7.64%   |
| Elan Microelectronics      | 11        | 7.64%   |
| AuthenTec                  | 7         | 4.86%   |
| LighTuning Technology      | 5         | 3.47%   |
| STMicroelectronics         | 1         | 0.69%   |
| GDMicroelectronics         | 1         | 0.69%   |
| Focal-systems.Corp         | 1         | 0.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 7.64%   |
| Synaptics  WBDI                                                            | 11        | 7.64%   |
| Shenzhen Goodix  FingerPrint Device                                        | 11        | 7.64%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 6.94%   |
| Elan ELAN:Fingerprint                                                      | 9         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 5.56%   |
| Unknown                                                                    | 8         | 5.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 4.86%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 4.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 4.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 3.47%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 3.47%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 3.47%   |
| AuthenTec AES2810                                                          | 5         | 3.47%   |
| Validity Sensors VFS491                                                    | 4         | 2.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.08%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 2.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 2.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.39%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.39%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.39%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.39%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.69%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.69%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.69%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.69%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.69%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.69%   |
| GDMicroelectronics Touch Fingerprint Sensor                                | 1         | 0.69%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.69%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.69%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 39        | 60%     |
| Alcor Micro               | 13        | 20%     |
| Lenovo                    | 4         | 6.15%   |
| O2 Micro                  | 3         | 4.62%   |
| Upek                      | 2         | 3.08%   |
| Gemalto (was Gemplus)     | 1         | 1.54%   |
| Fujitsu Siemens Computers | 1         | 1.54%   |
| Chicony Electronics       | 1         | 1.54%   |
| Aladdin Knowledge Systems | 1         | 1.54%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 20%     |
| Broadcom 58200                                                               | 12        | 18.46%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 15.38%  |
| Broadcom 5880                                                                | 9         | 13.85%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 12.31%  |
| Lenovo Integrated Smart Card Reader                                          | 4         | 6.15%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 4.62%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.08%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.54%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 1.54%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.54%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.54%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1120      | 73.11%  |
| 1     | 338       | 22.06%  |
| 2     | 67        | 4.37%   |
| 3     | 5         | 0.33%   |
| 10    | 1         | 0.07%   |
| 4     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 143       | 29.36%  |
| Graphics card            | 98        | 20.12%  |
| Chipcard                 | 60        | 12.32%  |
| Net/wireless             | 59        | 12.11%  |
| Multimedia controller    | 30        | 6.16%   |
| Communication controller | 20        | 4.11%   |
| Camera                   | 17        | 3.49%   |
| Bluetooth                | 16        | 3.29%   |
| Storage                  | 14        | 2.87%   |
| Sound                    | 7         | 1.44%   |
| Unassigned class         | 4         | 0.82%   |
| Card reader              | 4         | 0.82%   |
| Network                  | 3         | 0.62%   |
| Net/ethernet             | 3         | 0.62%   |
| Storage/ide              | 2         | 0.41%   |
| Unclassified device      | 1         | 0.21%   |
| Storage/raid             | 1         | 0.21%   |
| Storage/nvme             | 1         | 0.21%   |
| Modem                    | 1         | 0.21%   |
| Flash memory             | 1         | 0.21%   |
| Firewire controller      | 1         | 0.21%   |
| Dvb card                 | 1         | 0.21%   |

